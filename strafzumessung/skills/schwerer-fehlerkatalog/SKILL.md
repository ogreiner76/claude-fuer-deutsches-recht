---
name: schwerer-fehlerkatalog
description: "Schwerer Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Schwerer Fehlerkatalog

## Einsatzlage

Dieser Fehlerkatalog prüft im Bereich **Strafzumessung** Ergebnisse vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegen.

## Fachspezifische Fehlerachsen

- `153a-stpo-iii-stpo-bewaehrung-stgb`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `bewaehrung-auflagen-bewaehrungswiderruf-56f-freiheitsstrafe-ohne`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `bewaehrung-interessen-deutschem-freiheitsstrafe`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `freiheitsstrafe-strafmass-geldstrafe-tagessatzanzahl-vs-stgb`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `geldstrafe-grossen-rechtsmittel-gesamtstrafenfolgen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `gesamtstrafenbildung-stgb-gestaendnis-strafmilderung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `jgg-jugendstrafe-minder-schwerer-nachtraegliche`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `orientierung-triage-paragraph-stgb-besonders`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `regelbeispiele-stgb-strafbefehl`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `strafbefehl-stpo-strafmilderung-stgb-strafrahmen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
