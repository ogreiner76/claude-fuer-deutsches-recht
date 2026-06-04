---
name: workflow-kaltstart-und-routing
description: "Kaltstart und Routing im Plugin fachanwalt-arbeitsrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko, laufende Fristen und Anschluss-Skills. Risikoampel, Fristensicherung, sofortiger Handlungsschritt."
---

# Kaltstart und Routing — fachanwalt-arbeitsrecht

## V90 Fachkern — Arbeitsrecht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `Kaltstart und Routing — fachanwalt-arbeitsrecht` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** BGB §§ 611a, 613a, 615, 623; KSchG §§ 1, 4, 7; TzBfG §§ 14, 15, 16; AGG §§ 1, 3, 7, 15, 22; EntgTranspG §§ 3, 5, 7; BUrlG §§ 1, 3, 7; BetrVG §§ 87, 99, 102; ArbZG; NachwG; SGB IX §§ 164, 167, 168.
- **Verifizierte Anker:** BAG, Urteil vom 23.10.2025 - 8 AZR 300/24 (Entgeltgleichheit, Paarvergleich, Beweislast, bundesarbeitsgericht.de); BAG, Urteil vom 03.06.2025 - 9 AZR 104/24 (kein Verzicht auf gesetzlichen Mindesturlaub im bestehenden Arbeitsverhältnis); bei Kündigungszugang immer § 623 BGB, Zugang nach § 130 BGB, Dreiwochenfrist §§ 4, 7 KSchG und Beweis des konkreten Umschlags trennen.
- **Arbeitsmodus:** Zuerst Status, Zugang, Frist, Beteiligungsrechte, Sonderkündigungsschutz, Beweislast und prozessualen nächsten Schritt sichern; dann erst Materiellrecht vertiefen.
- **Outputpflicht:** Fristenblatt, Zugangsmatrix, Beweisangebot, Mandantenmail, Betriebsrats-/Gegnerbrief oder Klage-/Erwiderungsbaustein.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


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
