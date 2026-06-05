---
name: einarbeitung-fehlerkatalog
description: "Nutze dies als Fehlerbremse bei Einarbeitung Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Einarbeitung Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Aktenauszug Gerichtsverfahren** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `aktenauszug-strukturpruefung-akzg-bauleiter-vertraulichkeit`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `akzg-zeitstrahl-anlagenverzeichnis-extrakt-anwaltsschriftsatz`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anwaltsschriftsatz-beweislast-beweismittel-interessen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `arbeitsgerichtsverfahren-modus-terminkalender`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `beweismittel-gegenueberstellung-einleitungssatz-generator`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `erstellen-fristennotiz-gerichtsverfahren-verfahrensgeschichte`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `gegenueberstellung-parteivortraege-rechtsargumente`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `parteivortrag-gegenueberstellung-rechtsargumente`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `sachverhaltschronologie-textbausteine-schnelle-stilrichtlinie`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
