---
name: caching-und-teil-rerun
description: "Caching der Wuerfelzellen und gezielter Teil-Rerun bei Aenderungen — vermeidet die voll Neuberechnung von tausenden Zellen wenn nur ein Spaltenprompt eine Zeile oder ein Arbeitsblatt geaendert wurde. Cache-Key pro Zelle = Hash aus Spaltenprompt-Version Zeilenprompt-Version Dokument-Hash Arbeitsblatt-Perspektive Modell-Version. Invalidiert automatisch bei Versions-Aenderung. Schaetzt Kosten und Laufzeit vor Rerun. Geeignet auch fuer Quasi-Duplikate (Aehnlichkeit ueber 95 Prozent uebernimmt Cache-Treffer als Vorschlag fuer Pruefer-Bestaetigung)."
---

# /tabellenreview-3d:caching-und-teil-rerun

## Zweck

Ein 25.000-Zellen-Wuerfel komplett neu zu berechnen weil ein einziger Spaltenprompt um drei Worte praeziser wurde ist verschwenderisch. Dieser Skill macht den Wuerfel inkrementell.

## Cache-Key

Pro Zelle ein deterministischer Hash:

```
sha256(spaltenprompt-version + zeilenprompt-version + dokument-hash + arbeitsblatt-perspektive + modell-version)
```

Wenn irgendeine dieser Komponenten sich aendert wird der Cache-Eintrag invalidiert.

## Invalidierungsregeln

- **Patch-Aenderung am Spaltenprompt:** Cache bleibt gueltig (siehe `prompt-versionierung`)
- **Minor-Aenderung am Spaltenprompt:** Cache wird auf `nachpruefen` gesetzt — Pruefer entscheidet ob neu rechnen
- **Major-Aenderung am Spaltenprompt:** Cache invalidiert, betroffene Zellen muessen neu berechnet werden
- **Zeilenprompt geaendert:** nur die betroffene Zeile invalidiert, ueber alle Arbeitsblaetter
- **Arbeitsblatt-Perspektive geaendert:** alle Zellen dieses Arbeitsblatts invalidiert
- **Dokument-Hash geaendert (z. B. neue Version):** alle Zellen dieser Zeile invalidiert
- **Modell-Version geaendert:** Vorgehen waehlbar — komplett neu / Stichprobe pruefen / Cache uebernehmen mit Hinweis

## Quasi-Duplikate

Ein Vertrag-Cousin (sehr aehnlich) kann Cache-Treffer vom geprueften Originalvertrag uebernehmen — als VORSCHLAG nicht als Befund. Schwelle: Cosine-Aehnlichkeit ueber 95 Prozent UND derselbe Dokumenttyp UND derselbe Vertragspartner-Stamm. Pruefer-Flag automatisch. Pruefer bestaetigt oder verwirft.

## Kostenschaetzung

Vor jedem Teil-Rerun schaetzt der Skill:
- Anzahl zu berechnender Zellen
- erwartete Laufzeit
- erwartete Token-/Kosten-Aufnahme
- Auswirkung auf Audit-Trail

Pruefer kann Rerun beauftragen / ablehnen / nur Stichprobe rechnen lassen.

## Ausgabe

- `cache.parquet` — alle Zellen mit Cache-Key Antwort Belegkette Ampel
- `rerun-vorschlag.md` — pro Aenderung welche Zellen invalidiert sind und Kostenschaetzung
- Eintrag in `audit-trail-protokoll`

## Grenzen

Caching ist ein Effizienzwerkzeug nicht ein Beweismittel. Wer auf gerichtsfeste Reproduzierbarkeit angewiesen ist (z. B. Verfahrenseingabe) sollte einen kompletten Lauf ohne Cache machen und das Ergebnis hashen.
