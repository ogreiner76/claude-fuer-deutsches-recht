---
name: workflow-output-waehlen
description: "Output wählen: Entscheidungsraster für das richtige Ausgabeformat im Arbeitsrechtsmandat — Memo, Prüfmatrix, Klageschrift-Gerüst, Mandantenbrief, Checkliste, Ampel, Fristenblatt, Schriftsatzbaustein oder Vergleichsformel."
---

# Workflow: Output wählen

## Zweck
Entscheidungsraster für das optimale Output-Format in der jeweiligen Arbeitsphase. Nicht jede Antwort muss ein vollständiger Aufsatz sein — oft ist eine Ampel, eine Checkliste oder eine Vergleichsformel das nützlichere Ergebnis.

## Kaltstart
Wenn klar ist, was der Sachverhalt ist:

1. **Für wen ist der Output?** Anwalt intern, Mandant, Gericht, Gegenseite, Betriebsrat?
2. **In welcher Phase sind wir?** Erstberatung, Klagevorbereitung, Verhandlung, Abschluss?
3. **Was ist die nächste Entscheidung?** Klage, Vergleich, Aufhebungsvertrag, Beschwerde?
4. **Wie viel Zeit ist verfügbar?** (Kurzbild vs. vollständige Analyse)

## Output-Formate im Überblick

### Format 1: Risikoampel (5–10 Zeilen)
**Wann:** Erstberatung; wenn Mandant schnell wissen will, ob die Kündigung Bestand hat.

**Inhalt:**
```
Risikoampel — Kündigung [Datum]

Grün (starke Angriffspunkte):
• BR-Anhörung fehlt → § 102 BetrVG → Unwirksamkeit
• Schriftform: Faksimile-Stempel statt Original

Gelb (mittleres Risiko):
• Sozialauswahl: nicht dokumentiert; Angriff möglich

Rot (schwache Punkte):
• KSchG anwendbar (> 10 VZÄ; > 6 Monate)
• Betriebsbedingt: Stelle ist tatsächlich weggefallen

Empfehlung: Klage einlegen; Angriff über BR-Anhörung.
Frist: [Datum]
```

### Format 2: Prüfmatrix (Tabelle)
**Wann:** Umfassende Prüfung; wenn mehrere Gesichtspunkte systematisch abgearbeitet werden müssen.

**Muster:**
| Punkt | Norm | Befund | Bewertung | Handlungsbedarf |
|---|---|---|---|---|
| Schriftform | § 623 BGB | Original vorhanden | OK | — |
| BR-Anhörung | § 102 BetrVG | Kein Nachweis | Kritisch | Anforderung |
| Sozialauswahl | § 1 Abs. 3 KSchG | Nicht dokumentiert | Rüge möglich | In Klage rügen |

### Format 3: Klageschrift-Gerüst
**Wann:** Wenn Klage vorbereitet werden soll; Anwalt braucht Rohentwurf.

**Inhalt:**
- Antrag (präzise formuliert)
- Sachverhalt (chronologisch)
- Rechtliche Ausführungen (Normen, Argumente)
- Beweisangebote
- → Verweis auf `fachanwalt-arbeitsrecht-kuendigungsschutzklage` für vollständige Vorlage

### Format 4: Mandantenbrief
**Wann:** Wenn Ergebnis für den Mandanten schriftlich festgehalten werden soll.

**Inhalt:**
- Sachverhaltsdarstellung (kurz, verständlich)
- Rechtliche Ersteinschätzung
- Empfehlung
- Fristen
- Kosten
- Nächste Schritte
- → Verweis auf `workflow-mandantenkommunikation` für Muster

### Format 5: Checkliste
**Wann:** Wenn ein Workflow abgearbeitet werden muss; bei Compliance-Fragen.

**Beispiel:**
```
Checkliste Kündigung (AG-Seite vor Ausspruch):
□ Kündigungsgrund klar und dokumentiert
□ BR angehört (§ 102 BetrVG) — Frist abgelaufen?
□ Sonderkündigungsschutz geprüft
□ Sozialauswahl dokumentiert
□ Massenentlassung § 17 KSchG: Schwelle erreicht?
□ Zustellungsweg vorbereitet
□ Kündigungsschreiben: Original-Unterschrift, korrekte Frist
```

### Format 6: Fristenblatt
**Wann:** Wenn mehrere Fristen gleichzeitig laufen; für Wiedervorlage.
→ Verweis auf `workflow-fristen-und-risikoampel` für Template

### Format 7: Schriftsatzbaustein
**Wann:** Wenn ein Textbaustein für den Schriftsatz gebraucht wird (nicht der vollständige Schriftsatz).

**Beispiel:**
> „Zum Beweis des Vortrags, dass eine ordnungsgemäße Betriebsratsanhörung nicht stattgefunden hat, benennt der Kläger / die Klägerin den Betriebsratsvorsitzenden [Name], [Adresse], als Zeugen."

### Format 8: Vergleichsformel
**Wann:** Im Gütermin oder bei Verhandlung.
→ Verweis auf `spezial-vergleichspraxis-mehrparteien-konflikt-und-interessen` für Muster

### Format 9: Memo / Prüfvermerk
**Wann:** Für die interne Akte; strukturierter Prüfvermerk.

**Muster:**
```
PRÜFVERMERK — [Datum], [Anwalt/-in]
Mandat: [Name], [Kurzbeschreibung]

Sachverhalt: [2-3 Sätze]
Rechtslage: [3-5 Sätze]
Offene Punkte: [Lücken, unsichere Fakten]
Empfehlung: [Klare Handlungsempfehlung]
Nächster Schritt: [Konkret mit Datum]
```

## Entscheidungsmatrix Output-Format

| Phase | Empfänger | Dringlichkeit | Empfohlenes Format |
|---|---|---|---|
| Erstberatung | Mandant | Hoch | Risikoampel + Fristenblatt |
| Tiefenprüfung | Intern (Akte) | Mittel | Prüfmatrix + Memo |
| Klagevorbereitung | Gericht | Hoch | Klageschrift-Gerüst |
| Verhandlung | Mandant | Hoch | Vergleichsformel + Mandantenbrief |
| Compliance | AG intern | Mittel | Checkliste |
| Abschluss | Mandant | Normal | Mandantenbrief |

## Anschluss-Skills
- `workflow-mandantenkommunikation` für Mandantenbriefe
- `workflow-fristen-und-risikoampel` für Fristenblatt
- `fachanwalt-arbeitsrecht-kuendigungsschutzklage` für Klageschrift-Vollversion
- `spezial-vergleichspraxis-mehrparteien-konflikt-und-interessen` für Vergleichsformeln

## Quellenregel
- Normtext live prüfen auf [gesetze-im-internet.de](https://www.gesetze-im-internet.de).
- Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und frei prüfbarem Link: [dejure.org](https://dejure.org), [bundesarbeitsgericht.de](https://www.bundesarbeitsgericht.de).
- Annahmen explizit kennzeichnen.

## Was dieser Skill nicht macht
- Kein Ersatz für inhaltliche Facharbeit; dieser Skill wählt das Format, nicht den Inhalt.
