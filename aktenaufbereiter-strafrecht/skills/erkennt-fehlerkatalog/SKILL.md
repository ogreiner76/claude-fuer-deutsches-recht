---
name: erkennt-fehlerkatalog
description: "Nutze dies, wenn Erkennt Fehlerkatalog im Plugin Aktenaufbereiter Strafrecht konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?."
---

# Erkennt Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Aktenaufbereiter Strafrecht** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `aktenaufbereiter-strafrecht`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `akteneinsicht-uebersicht-aktenvorblatt-erstellen-anklageschrift`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `beweismittel-katalog-beweisverwertungsverbote-beziehungsmatrix`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `beziehungen-spezial-chronologie-ergaenzbar`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `ersatz-sonderfall-excel-faehige`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `fortlaufend-luecken-personenverzeichnis`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `fristenliste-strafverfahren-aktenlektuere-fristennotiz`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `kronzeugen-regelung-opferzeugen-besondere-personenverzeichnis`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `revision-rechtsfehler-aktenaufbereiter-aktenvorblatt`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
