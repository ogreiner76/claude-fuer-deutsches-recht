---
name: review-durchfuehren
description: "Fuehrt den eigentlichen Reviewlauf ueber den Wuerfel durch — Anzahl Zellen = Spalten x Zeilen x Arbeitsblaetter. Pro Zelle: Spaltenprompt + Zeilenprompt + Arbeitsblatt-Perspektive zusammenfuehren, Antwort aus dem Dokument extrahieren mit woertlichem Zitat und Fundstelle, Ampel anhand der Spalten-Ampelregel setzen. Bei Quasi-Duplikaten Cache aus `caching-und-teil-rerun` nutzen. Bei OCR-Konfidenz unter 90 Prozent automatisch Pruefer-Flag. Pro Reviewlauf Audit-Eintrag in `audit-trail-protokoll`. Schreibt `wuerfel.parquet` mit allen Zellen sowie `lauf-zusammenfassung.md`."
---

# /tabellenreview-3d:review-durchfuehren

## Zweck

Das ist der Hauptlauf. Wenn der Wuerfel 25 Spalten 200 Zeilen und 5 Arbeitsblaetter hat sind das 25.000 Zellen. Jede Zelle braucht: Antwort + woertliches Zitat + Fundstelle + Ampel + Pruefer-Flag.

## Eingaben

- `wuerfel-schema.yaml`
- `spaltenprompts.yaml`
- `zeilenprompts.yaml`
- `arbeitsblaetter.yaml`
- `zeilen-inventar.yaml`
- Praxisprofil unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/tabellenreview-3d/CLAUDE.md`

## Ablauf pro Zelle

1. **Prompt zusammenfuehren:** Arbeitsblatt-Perspektive vor Spaltenprompt vor Zeilenprompt. Konflikte protokollieren.
2. **Quelldokument oeffnen:** Pfad + Hash gegen Inventar abgleichen — falls Hash abweicht: Belegkette unterbrochen Pruefer-Flag setzen.
3. **Antwort extrahieren:** Antworttyp aus Spaltenprompt-Definition beachten (Freitext / zitat-mit-fundstelle / ja-nein / Datum / Geldbetrag / Aufzaehlung).
4. **Belegkette schreiben:** woertliches Zitat in Anfuehrungszeichen, danach Fundstelle (Datei-ID + Seite + Absatz + ggf. Ziffer).
5. **Ampel setzen:** anhand `ampel-regel` aus dem Spaltenprompt (rot / gelb / gruen).
6. **Pruefer-Flag setzen wenn:**
   - OCR-Konfidenz unter 90 Prozent
   - Antworttyp `zitat-mit-fundstelle` aber kein Zitat extrahierbar
   - Konflikt zwischen Spalten- und Zeilenprompt
   - Mehrdeutigkeit (mehrere plausible Antworten im Dokument)
7. **Querweis aufbauen:** wenn Zellen-Ergebnis auf anderen Vertrag referenziert (`siehe Anlage 7 zu Vertrag X`) als Cross-Ref vermerken.
8. **Cache pruefen:** bei Quasi-Duplikaten (Aehnlichkeit ueber 95 Prozent) zur Zelle eines bereits geprueften Dokuments Cache-Treffer vorschlagen — Pruefer entscheidet ob uebernommen.

## Ausgabeformat

- `wuerfel.parquet` (oder JSON) mit einer Zeile pro Zelle:

```
arbeitsblatt-id, zeile-id, spalte-id, antwort, woertliches-zitat, fundstelle, ampel, pruefer-flag, prompt-version, lauf-zeitstempel
```

- `lauf-zusammenfassung.md` — Anzahl Zellen pro Ampel, Anzahl Pruefer-Flags, Anzahl Cache-Treffer, Laufdauer, Modell-Version, Audit-Trail-Eintrag-ID.

## Reihenfolge

Standard: Arbeitsblatt-aussen, Zeile-mittel, Spalte-innen. Optional: Spalte-aussen wenn Spaltenprompt aufwaendig (z. B. Volltext-Indexierung) und ueber den Stapel gemeinsam profitiert.

## Grenzen

Jede Zelle ist ein Hinweis kein Befund. Pruefer-Flags sind die wichtigste Ausgabe — sie sagen wo der menschliche Pruefer hinschauen muss. Untermarkierung ist eine Einbahnstrasse; Uebermarkierung ist eine Zweiwegtuer die ein Anwalt in 30 Sekunden schliesst.
