---
name: workflow-dokumentenintake
description: "Dokumentenintake: strukturierter Empfang, Sichtung und Klassifikation von Mandantenunterlagen im Arbeitsrechtsmandat — Kündigung, Vertrag, Abmahnung, BR-Protokoll, Zeugnis, Abrechnung. Erste Auswertung und Routing in Spezial-Skills."
---

# Workflow: Dokumentenintake

## Zweck
Strukturierter Empfang und Erste-Auswertung von Mandantenunterlagen. Dieser Workflow stellt sicher, dass keine relevanten Dokumente übersehen werden und die sofortige Klassifikation in den richtigen Spezial-Skill führt.

## Kaltstart
Wenn Unterlagen vorgelegt werden (upload, E-Mail, Beschreibung):

1. **Was wurde vorgelegt?** (Art des Dokuments: Kündigung, Vertrag, Abmahnung, Urteil, Bescheid?)
2. **Vollständig?** (Original oder Kopie? Alle Seiten? Unterschriften vorhanden?)
3. **Was ist das Anliegen des Mandanten?** (Prüfung, Klage, Verhandlung, Information?)
4. **Gibt es laufende Fristen?** (Sofort prüfen: Datum des Dokuments → Fristberechnung)

## Dokumentenklassen und Sofort-Auswertung

### Klasse A: Kündigung

**Sofort-Prüfpunkte (innerhalb von 5 Minuten):**
- Datum der Kündigung
- Art: ordentlich oder außerordentlich?
- Zugangsdatum (auf dem Schreiben oder aus Mandantenangabe)
- Schriftform: eigenhändige Unterschrift sichtbar?
- Absender: wer hat unterzeichnet? Vollmacht beigefügt?
- Klagefrist: 3 Wochen ab Zugang → konkretes Datum berechnen

**Output nach Intake:**
> „Kündigung vom [Datum] liegt vor. Zugang nach Mandantenangabe am [Datum]. Klagefrist läuft bis [Datum]. Schriftform: [OK/Fehler]. Nächster Schritt: ar-kuendigungspruefung-workflow."

### Klasse B: Arbeitsvertrag

**Sofort-Prüfpunkte:**
- Beginn des Arbeitsverhältnisses
- Befristung? (Dauer, Sachgrund)
- Probezeit? (Kündigung in Probezeit: 2 Wochen § 622 Abs. 3 BGB)
- Vergütung
- Ausschlussfristen (Verfallklauseln) — Gültigkeit prüfen (§ 307 BGB)
- Wettbewerbsverbot
- Sonderkündigungsschutz-Hinweise

**Output nach Intake:**
> „Arbeitsvertrag vom [Datum] vorgelegt. Befristung: [ja/nein]. Beginn: [Datum]. Ausschlussklausel: [vorhanden/nicht vorhanden — Wirksamkeit prüfen]."

### Klasse C: Abmahnung

**Sofort-Prüfpunkte:**
- Datum der Abmahnung
- Welches Verhalten wird beanstandet?
- Ist das Verhalten konkret beschrieben?
- Wurde Abhilfe gefordert? Wiederholungswarnung?
- Liegt Abmahnung im Original vor oder nur in Abschrift?

**Wirksamkeitsprüfung Abmahnung:**
- Bestimmtheitsgebot: Tatsachen konkret, nicht pauschal
- Keine übermäßige Aufzählung von Vorwürfen (Sammelpunktabmahnung)
- Richtige Person (war es wirklich der abgemahnte AN, der das Verhalten gezeigt hat?)
- Möglichkeit zur Gegendarstellung (§ 83 Abs. 1 BetrVG)

### Klasse D: BR-Unterlagen (Anhörungsschreiben, Protokoll)

**Sofort-Prüfpunkte:**
- Datum des Anhörungsschreibens
- Enthält es: Kündigungsart, vollständige Kündigungsgründe, Sozialdaten des AN?
- Datum der BR-Stellungnahme (Frist § 102 BetrVG: 1 Woche/3 Tage gewahrt?)
- Hat BR Einwand erhoben? Wenn ja: welche Gründe?

### Klasse E: Arbeitsbescheinigung / Zeugnis

**Sofort-Prüfpunkte bei Zeugnis:**
- Beendigungsart korrekt angegeben?
- Bewertungsformulierungen (Codierungen identifizieren: „stets zu unserer Zufriedenheit" = befriedigend)
- Aufgabenbeschreibung vollständig?
- Schlussformel vorhanden? Formulierung?

### Klasse F: Gehaltsabrechnungen

**Sofort-Prüfpunkte:**
- Monatliche Gesamtlöhne der letzten 12 Monate
- Sonderzahlungen (Bonus, 13. Gehalt)
- Überstunden erfasst?
- Mindestlohn unterschritten? (aktuellen MiLoG-Satz live prüfen)

### Klasse G: Behördenpost (Integrationsamt, BA, Gericht)

**Sofort-Prüfpunkte:**
- Art des Bescheids
- Fristen im Bescheid
- Rechtsmittelbelehrung

## Intake-Checkliste (Eingang eines neuen Mandats)

- [ ] Alle Dokumente gesichtet und klassifiziert
- [ ] Fristkritische Dokumente identifiziert (Kündigung → Klagefrist, Befristungsende → Entfristungsfrist)
- [ ] Fristen berechnet und im Kalender eingetragen
- [ ] Mandant über Fristen informiert
- [ ] Routing in Spezial-Skill vorgenommen
- [ ] Lückenliste erstellt (fehlende Unterlagen identifiziert)

## Sofort-Output-Format nach Intake

```
INTAKE-PROTOKOLL — [Mandant, Datum]

Empfangene Dokumente:
1. [Dokumentenart, Datum, Auffälligkeiten]
2. [...]

Fristkritische Erkenntnisse:
- Klagefrist endet am: [Datum]
- AGG-Frist endet am: [Datum, falls relevant]

Erste Einschätzung:
[Zwei bis drei Sätze zum Mandatsziel und zum offensichtlichsten Angriffspunkt]

Routing:
→ Primär: [Skill-Name]
→ Ergänzend: [Skill-Name]

Fehlende Unterlagen:
- [Dokument] → [Beschaffungsweg]
```

## Anschluss-Skills
- `workflow-unterlagen-lueckenliste` für detaillierte Lückenliste
- `ar-einfuehrung-mandantenanliegen` für Themenrouting
- `ar-kuendigungspruefung-workflow` wenn Kündigung das Kerndokument ist
- `spezial-befristung-compliance-dokumentation-und-akte` wenn Befristungsvertrag vorliegt

## Quellenregel
- Normtext live prüfen auf [gesetze-im-internet.de](https://www.gesetze-im-internet.de).
- Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und frei prüfbarem Link: [dejure.org](https://dejure.org), [bundesarbeitsgericht.de](https://www.bundesarbeitsgericht.de).
- Annahmen explizit kennzeichnen.

## Was dieser Skill nicht macht
- Keine vollständige Rechtsprüfung im Intake; nur Erstklassifikation und Fristensicherung.
- Keine OCR oder automatische Dokumentenverarbeitung ohne explizite Eingabe.
