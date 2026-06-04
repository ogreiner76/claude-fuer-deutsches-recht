---
name: workflow-kaltstart-und-routing
description: "Kaltstart und Routing im Plugin fachanwalt-arbeitsrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko, laufende Fristen und Anschluss-Skills. Risikoampel, Fristensicherung, sofortiger Handlungsschritt."
---

# Kaltstart und Routing — fachanwalt-arbeitsrecht

## Zweck
Eingangsworkflow für das Plugin `fachanwalt-arbeitsrecht`. Aus dem ersten Satz, dem ersten Dokument oder der ersten Frage wird innerhalb von Sekunden das Mandat klassifiziert, die kritischen Fristen gesichert und der passende Spezial-Skill aktiviert.

## Kaltstart — Fünf Weichen

Wenn Material vorliegt, zuerst damit arbeiten. Keine überflüssigen Rückfragen — nur was für die nächste Weiche entscheidend ist:

1. **Rolle:** Wer fragt? Arbeitnehmer (AN), Arbeitgeber (AG), Betriebsrat (BR), Kanzlei, Unternehmen?
2. **Kernereignis:** Was ist das auslösende Ereignis? Kündigung, Befristungsende, Diskriminierung, Vergütungsstreit, Betriebsänderung, Betriebsübergang?
3. **Fristen:** Gibt es eine laufende 3-Wochen-Frist (§ 4 KSchG, § 17 TzBfG) oder AGG-Frist (§ 15 Abs. 4 AGG)? Zugangsdatum sichern.
4. **Unterlagen:** Liegt ein Dokument vor (Kündigung, Vertrag, Abmahnung, Bescheid)? Wenn ja, direkt auswerten.
5. **Ziel:** Was will der Mandant erreichen? Bestandsschutz, Abfindung, Schadensersatz, Compliance, Information?

## Sofort-Ampel (erste 60 Sekunden)

### Grün — Zeit vorhanden, keine akute Frist
- Kündigung noch nicht ausgesprochen; Vertragsgestaltung; allgemeine Beratung; Betriebsratsthemen ohne akute Frist

### Gelb — Frist läuft, aber Zeit für gründliche Prüfung
- Kündigung eingegangen, mehr als 14 Tage bis Fristablauf
- Befristungsende in mehr als 14 Tagen

### Rot — sofortiger Handlungsbedarf
- Kündigung eingegangen, weniger als 7 Tage bis Fristablauf
- AGG-Frist läuft aus
- Vollmachtsrüge nötig (§ 174 BGB: unverzüglich)
- Bereits abgelaufene Frist → § 5 KSchG-Antrag prüfen

## Routing-Matrix

### AN erhält Kündigung
```
→ fazugang-neu-008 (Schriftformprüfung: Original? E-Mail? Faks.?)
→ fazugang-neu-00X (Zugangsfragen je nach Zustellungsart)
→ ar-kuendigungspruefung-workflow (Vollständige Prüfung)
→ spezial-kschg-risikoampel-und-gegenargumente (Risikoampel)
→ fachanwalt-arbeitsrecht-kuendigungsschutzklage (Klageschrift)
```

### AN erhält Kündigung — Formfehler erkannt
```
→ spezial-unwirksam-fristennotiz-und-naechster-schritt
→ workflow-fristen-und-risikoampel
```

### AG spricht Kündigung aus
```
→ ar-kuendigungspruefung-workflow (Prüfung vor Ausspruch)
→ fachanwalt-arbeitsrecht-betriebsratsanhoerung (§ 102 BetrVG)
→ fazugang-neu-006-arbeitgeber-zustellworkflow-rechtssicher-organisieren
→ fachanwalt-arbeitsrecht-massenentlassung-17-kschg (wenn viele Kündigungen)
```

### Befristungsende
```
→ fachanwalt-arbeitsrecht-befristung-tzbfg (Prüfung Befristungswirksamkeit)
→ spezial-befristung-compliance-dokumentation-und-akte
→ spezial-tzbfg-schriftsatz-brief-und-memo-bausteine (Klagebaustein)
```

### Abfindung verhandeln
```
→ ar-abfindungs-rechner-modular (Rechenlogik)
→ ar-aufhebungsvertrag-praxis (Klauselprüfung, Sperrzeitgestaltung)
→ fachanwalt-arbeitsrecht-verhandlung-guete-abfindung-arbg (Gütermin)
```

### Betriebsrat-Frage
```
→ spezial-betriebsrat-zahlen-schwellen-und-berechnung (Schwellenwerte)
→ fachanwalt-arbeitsrecht-betriebsratsanhoerung (§ 102 BetrVG)
→ spezial-betrvg-behoerden-gericht-und-registerweg (Verfahrenwege)
```

### Diskriminierung / Entgelt
```
→ spezial-entgtranspg-verhandlung-vergleich-und-eskalation (EntgTranspG, AGG)
→ ar-leiharbeit-equal-pay-spezial (wenn Leiharbeit)
```

### Betriebsübergang
```
→ ar-betriebsuebergang-spezial (§ 613a BGB)
```

### Whistleblowing / Compliance
```
→ fachanwalt-arbeitsrecht-hinschg-whistleblower-repressalie
```

## Erstgesprächs-Schnellcheck (3 Fragen für sofortigen Einstieg)

1. **Liegt eine Kündigung vor?** Datum und Art nennen.
2. **Was ist das Ziel des Mandanten?** Klage? Abfindung? Beides offenhalten?
3. **Gibt es besondere Umstände?** Betriebsrat, Schwangerschaft, Schwerbehinderung, Elternzeit?

Mit diesen drei Antworten ist das Routing zu 90 % bestimmt.

## Output-Optionen nach Kaltstart

| Situation | Output |
|---|---|
| Frist droht in < 7 Tagen | Sofortiger Handlungsplan mit Fristdatum; Klageschrift-Baustein |
| Vollständige Prüfung möglich | Prüfmatrix (Risikoampel, offene Punkte, Lückenliste) |
| Verhandlungsvorbereitung | Abfindungsberechnung + Verhandlungsstrategie |
| Mandantenmemo | Kurzes Memo: Was ist das Problem, was sind die Optionen, was empfehle ich |

## Anschluss-Skills
- `workflow-anschluss-skills-router` für detailliertes Routing
- `spezial-fachanwalt-erstpruefung-und-mandatsziel` für Mandatsaufnahme
- `workflow-fristen-und-risikoampel` für Fristenkontrolle
- `workflow-dokumentenintake` für Dokumentenauswertung

## Quellenregel
- Normtext live prüfen auf [gesetze-im-internet.de](https://www.gesetze-im-internet.de).
- Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und frei prüfbarem Link: [dejure.org](https://dejure.org), [bundesarbeitsgericht.de](https://www.bundesarbeitsgericht.de).
- Keine BeckRS-, juris- oder Kommentar-Blindzitate.
- Annahmen explizit markieren.

## Was dieser Skill nicht macht
- Keine Fachbearbeitung; nur Erstklassifikation und Routing.
- Keine Mandantenentscheidung ohne ausdrückliche Beauftragung.
