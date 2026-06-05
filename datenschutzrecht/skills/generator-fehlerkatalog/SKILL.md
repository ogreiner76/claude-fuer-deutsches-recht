---
name: generator-fehlerkatalog
description: "Nutze dies als Fehlerbremse bei Generator Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Generator Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Datenschutzrecht** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `anwendungsfall-triage`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `avv-art-26-joint-controllership-deutsch`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `avv-art-28-dsgvo-grundtatbestand`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `avv-art-28-mindestinhalte-checkliste`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `avv-audit-avv-cloud-avv-eu-avv-konzern-avv`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `avv-audit-und-kontrollrechte`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `avv-bestehender-avv-rolemix-avv-tom-datenpanne-meldung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `avv-cloud-und-subverarbeitung-art-28-iv`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `avv-eu-kommission-musterklauseln-2021-915`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `avv-eu-us-data-privacy-framework-bezug`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
