---
name: geas-fehlerkatalog
description: "Geas Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Geas Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Fachanwalt Migrationsrecht** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `allgemein-abschiebungsabwehr-sofort-arbeitgeber-arbeitsrecht`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `arbeitgeberwechsel-asyl-anhoerung-asylg-ausbildungsduldung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `aufenthaltstitel-ausweisung-start-behoerdenkommunikation-blaue`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `aufenthaltstitel-erstgespraech-mandatsannahme-fachanwalt-asyl`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `ba-zustimmung-beschaeftigungsduldung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `blaue-karte-blaue-karte-bleiberecht-25a-chancenaufenthalt`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `botschaft-visumtermin-workflow-chronologie-dokumentenstapel`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `datenschutz-sicherheit-daueraufenthalt-eu-digitalbeweise-flucht`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dublin-ueberstellung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `einbuergerung-lebensunterhalt-mehrstaatigkeit-strafen-einreise`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
