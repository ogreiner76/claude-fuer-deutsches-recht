---
name: workflow-anschluss-skills-router
description: "Anschluss-Skills-Router für fachanwalt-arbeitsrecht: wählt nach Thema, Phase und Output-Bedarf den passenden Spezial-Skill aus dem Plugin aus und erklärt in einem Satz, warum der Wechsel die Arbeit beschleunigt."
---

# Workflow: Anschluss-Skills-Router

## V90 Fachkern — Arbeitsrecht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `Workflow: Anschluss-Skills-Router` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** BGB §§ 611a, 613a, 615, 623; KSchG §§ 1, 4, 7; TzBfG §§ 14, 15, 16; AGG §§ 1, 3, 7, 15, 22; EntgTranspG §§ 3, 5, 7; BUrlG §§ 1, 3, 7; BetrVG §§ 87, 99, 102; ArbZG; NachwG; SGB IX §§ 164, 167, 168.
- **Verifizierte Anker:** BAG, Urteil vom 23.10.2025 - 8 AZR 300/24 (Entgeltgleichheit, Paarvergleich, Beweislast, bundesarbeitsgericht.de); BAG, Urteil vom 03.06.2025 - 9 AZR 104/24 (kein Verzicht auf gesetzlichen Mindesturlaub im bestehenden Arbeitsverhältnis); bei Kündigungszugang immer § 623 BGB, Zugang nach § 130 BGB, Dreiwochenfrist §§ 4, 7 KSchG und Beweis des konkreten Umschlags trennen.
- **Arbeitsmodus:** Zuerst Status, Zugang, Frist, Beteiligungsrechte, Sonderkündigungsschutz, Beweislast und prozessualen nächsten Schritt sichern; dann erst Materiellrecht vertiefen.
- **Outputpflicht:** Fristenblatt, Zugangsmatrix, Beweisangebot, Mandantenmail, Betriebsrats-/Gegnerbrief oder Klage-/Erwiderungsbaustein.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


## Zweck
Dieser Skill wählt nach Abschluss einer Erstanalyse oder eines Workflow-Schritts den optimalen Anschluss-Skill aus dem Plugin `fachanwalt-arbeitsrecht` aus — präzise, begründet und mit klarer Weiterleitung.

## Kaltstart
Wenn der aktuelle Bearbeitungsstand vorliegt, die Frage oder das Dokument:

1. **In welcher Phase befinden wir uns?** Erstprüfung, Klagevorbereitung, Verhandlung, Schriftsatz, Compliance, Mandantenkommunikation?
2. **Was ist das nächste Ziel?** Klage einreichen, Vergleich schließen, Schriftsatz erstellen, Compliance prüfen, Mandant informieren?
3. **Was liegt bereits vor?** Ergebnis des vorherigen Schritts?

## Routing-Übersicht: Alle Skills nach Thema

### Thema: Kündigung (ordentlich und außerordentlich)

| Skill | Einsatz wenn |
|---|---|
| `ar-kuendigungspruefung-workflow` | Erstes Prüfschema; Schritt-für-Schritt-Check |
| `fachanwalt-arbeitsrecht-kuendigungsschutzklage` | Klageschrift erstellen; Verfahrensstrategie |
| `spezial-kschg-risikoampel-und-gegenargumente` | Schnelle Risikoampel; Gegenargumente |
| `spezial-unwirksam-fristennotiz-und-naechster-schritt` | Unwirksamkeit erkannt → sofortiger Handlungsschritt |
| `fachanwalt-arbeitsrecht-massenentlassung-17-kschg` | § 17 KSchG; viele Kündigungen gleichzeitig |
| `fachanwalt-arbeitsrecht-betriebsratsanhoerung` | BR-Anhörung prüfen oder vorbereiten |

### Thema: Zugang der Kündigung

| Skill | Einsatz wenn |
|---|---|
| `fazugang-neu-001-kuendigung-durch-boten-beweisvermerk-und-prozessstrategie` | Boten-Zustellung dokumentieren oder angreifen |
| `fazugang-neu-002-einwurf-einschreiben-risiko-nach-aktueller-bag-linie` | Einschreiben-Risiken prüfen |
| `fazugang-neu-003-zugang-bei-urlaub-krankheit-klinik-und-auslandsaufenthalt` | Abwesenheit beim Zugang |
| `fazugang-neu-004-inhalt-des-umschlags-bestreiten-und-beweisangebot` | Inhaltsbestreiten |
| `fazugang-neu-005-kuendigungsfrist-berechnen-bei-unsicherem-zugang` | Fristberechnung bei unklarem Datum |
| `fazugang-neu-006-arbeitgeber-zustellworkflow-rechtssicher-organisieren` | AG: Zustellung rechtssicher organisieren |
| `fazugang-neu-007-arbeitnehmerverteidigung-zugang-bestreiten-ohne-unwahrheit` | AN: Zugang wahrheitsgemäß bestreiten |
| `fazugang-neu-008-schriftform-kuendigung-original-und-elektronische-kommunikation` | Schriftformfehler prüfen |

### Thema: Abfindung und Aufhebungsvertrag

| Skill | Einsatz wenn |
|---|---|
| `ar-abfindungs-rechner-modular` | Abfindung berechnen; Verhandlungsformel |
| `ar-aufhebungsvertrag-praxis` | Aufhebungsvertrag prüfen oder verhandeln |
| `fachanwalt-arbeitsrecht-aufhebungsvertrag-sperrzeit` | Sperrzeitgestaltung vertiefen |
| `fachanwalt-arbeitsrecht-verhandlung-guete-abfindung-arbg` | Gütermin-Strategie |

### Thema: Befristung

| Skill | Einsatz wenn |
|---|---|
| `fachanwalt-arbeitsrecht-befristung-tzbfg` | Befristungsrecht Tiefenprüfung |
| `spezial-befristung-compliance-dokumentation-und-akte` | Compliance und Aktenführung |
| `spezial-tzbfg-schriftsatz-brief-und-memo-bausteine` | Schriftsatz, Brief, Memo erstellen |

### Thema: Betriebsrat / Kollektivrecht

| Skill | Einsatz wenn |
|---|---|
| `fachanwalt-arbeitsrecht-betriebsratsanhoerung` | § 102 BetrVG; Anhörungsprüfung |
| `fachanwalt-arbeitsrecht-betriebsratsbeschluss-heilung` | Beschlussmängel heilen |
| `spezial-betriebsrat-zahlen-schwellen-und-berechnung` | Schwellenwerte, BR-Größe |
| `spezial-betrvg-behoerden-gericht-und-registerweg` | Verfahrenswege; Beschlussverfahren |
| `spezial-vergleichspraxis-mehrparteien-konflikt-und-interessen` | Dreiparteien; Sozialplan |

### Thema: Sonstige Themen

| Skill | Einsatz wenn |
|---|---|
| `ar-einfuehrung-mandantenanliegen` | Erstes Routing; Themenklassifikation |
| `ar-betriebsuebergang-spezial` | § 613a BGB; Asset-Deal |
| `ar-konkurrenzklausel-spezial` | Nachvertragliches Wettbewerbsverbot |
| `ar-leiharbeit-equal-pay-spezial` | AÜG; Equal Pay |
| `spezial-entgtranspg-verhandlung-vergleich-und-eskalation` | EntgTranspG; Lohnlücke |
| `fachanwalt-arbeitsrecht-hinschg-whistleblower-repressalie` | Whistleblowing; HinSchG |
| `spezial-freistellungsklausel-sonderfall-und-edge-case` | Freistellungsklausel nach BAG 5 AZR 108/25 |
| `spezial-urlaub-livequellen-und-rechtsprechungscheck` | Urlaubsrecht |

### Thema: Qualität und Quellen

| Skill | Einsatz wenn |
|---|---|
| `spezial-aktenzeichen-red-team-und-qualitaetskontrolle` | Schriftsatz Red-Team |
| `spezial-quelle-beweislast-und-darlegungslast` | Quellenregeln; Beweislast |
| `spezial-rechtsprechung-livecheck-arbeitsrecht` | Aktenzeichen verifizieren |
| `workflow-redteam-qualitygate` | Qualitätsgate vor Abschluss |
| `workflow-rechtsquellen-livecheck` | Normen live prüfen |

## Routing-Entscheidungsbaum (vereinfacht)

```
Kündigung eingegangen?
  → Sofort: fazugang-neu-008 (Schriftform) + fazugang-neu-00X (Zugang)
  → Dann: ar-kuendigungspruefung-workflow
  → Wenn Unwirksamkeit: spezial-unwirksam-fristennotiz...
  → Klage: fachanwalt-arbeitsrecht-kuendigungsschutzklage

Befristung läuft aus?
  → fachanwalt-arbeitsrecht-befristung-tzbfg
  → Bei Frist: spezial-tzbfg-schriftsatz...

Abfindung verhandeln?
  → ar-abfindungs-rechner-modular
  → fachanwalt-arbeitsrecht-verhandlung-guete-abfindung-arbg

Betriebsrat-Thema?
  → spezial-betriebsrat-zahlen-schwellen-und-berechnung
  → fachanwalt-arbeitsrecht-betriebsratsanhoerung
```

## Anschluss-Skills
Dieser Skill ist der Router; alle anderen Skills sind die Ziele.

## Quellenregel
- Normtext live prüfen auf [gesetze-im-internet.de](https://www.gesetze-im-internet.de).
- Rechtsprechung nur mit verifizierbarem Link: [dejure.org](https://dejure.org), [bundesarbeitsgericht.de](https://www.bundesarbeitsgericht.de).
- Annahmen explizit kennzeichnen.

## Was dieser Skill nicht macht
- Keine Fachbearbeitung; nur Routing.
- Keine Entscheidung über die rechtliche Strategie; das bleibt dem Anwalt.
