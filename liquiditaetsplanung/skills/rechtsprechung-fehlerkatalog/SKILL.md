---
name: rechtsprechung-fehlerkatalog
description: "Nutze dies, wenn Rechtsprechung Fehlerkatalog im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?."
---

# Rechtsprechung Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Liquiditaetsplanung** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `deutschem-dokumentationspaket-excel`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `export-forecast-fortbestehensprognose-international`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `idw-s6-integrierte-sanierungsplanung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `insolvenzrecht-liqui-sonderfall-liquiditaetsplanung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `interessen-verifikation-beweislast-vorschau`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `liqp-bankenreporting-leitfaden`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `liqp-liquiditaetspool-cash-pooling-spezial`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `liqp-liquiditaetspool-cash-rollende-13wochen-warenkredit-skonto`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `liqp-rollende-13wochen-bauleiter`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
