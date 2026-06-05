---
name: aktenanlage-fehlerkatalog
description: "Nutze dies, wenn Aktenanlage Fehlerkatalog im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?."
---

# Aktenanlage Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Strafbefehl Verteidiger** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `deal-beweislast-einspruch-einspruchsentscheidung-folgen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `einstellung-153a-hauptverhandlung-vorbereitung-strafbefehl`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `einstellung-fahrerlaubnis-mandantenentscheidung-hauptverhandlung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `gegen-strafbefehl-einspruch-strafbefehl-aktenanlage`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `nebenfolgen-fahrerlaubnis-strafbefehl-pflichtverteidiger`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `nebenfolgen-strafbefehl-strafbefehls`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `rechtsmittel-nach-tagessaetze-geldstrafe-strafbefehl`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `stbv-einspruch-strafbefehl-fahrerlaubnis-auslaendischer-mandant`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `stbv-strafbefehl-abwesenheit-vertretung-akteneinsicht`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
