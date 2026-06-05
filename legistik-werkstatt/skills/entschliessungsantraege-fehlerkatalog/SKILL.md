---
name: entschliessungsantraege-fehlerkatalog
description: "Nutze dies, wenn Entschliessungsantraege Fehlerkatalog im Plugin Legistik Werkstatt konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?."
---

# Entschliessungsantraege Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Legistik Werkstatt** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `allgemein-workflow-chronologie-workflow-fristen-legw-bmleh`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `begruendung-allgemein-und-besonders`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dokumente-rendern-docx-pdf`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `europarechtskonformitaet`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `folgenabschaetzung-erfuellungsaufwand`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `folgenabschaetzung-erfuellungsaufwand-folgenabschaetzung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `folgenabschaetzung-nachhaltigkeit`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `formulierungshilfe-bauen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `gesetzesentwurf-kabinett`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `gesetzgebungskompetenz-pruefen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
