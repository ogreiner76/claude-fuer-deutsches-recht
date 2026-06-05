---
name: anlage-fehlerkatalog
description: "Anlage Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Anlage Fehlerkatalog

## Einsatzlage

Dieser Fehlerkatalog prüft im Bereich **Anlagen Zu Schriftsaetzen** Ergebnisse vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegen.

## Fachspezifische Fehlerachsen

- `anlage-red-anlagen-anlagenkonvolut-sonderfall-arial`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anlagen-an-assistenz-uebersetzungspflicht-vorlagepflicht-zpo`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anlagen-aus-datenraum-und-sharepoint`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anlagen-aus-edv-systemen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anlagen-aus-mandantenmaterial`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anlagen-bei-berufung-revision`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anlagen-bei-eilantrag-eu-arrest`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anlagen-berufung-revision-eilantrag-eu-bilder-screenshots`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anlagen-bilder-screenshots`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anlagen-check-zustellung-redaktion-dsgvo-schwaerzen-stempel`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
