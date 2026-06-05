---
name: formalia-fehlerkatalog
description: "Formalia Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Formalia Fehlerkatalog

## Einsatzlage

Dieser Fehlerkatalog prüft im Bereich **Dfg Foerderantrag** Ergebnisse vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegen.

## Fachspezifische Fehlerachsen

- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anfaenger-antraege-dfg`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dfg-bis-200k-begutachtung-light`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dfg-eigenanteil-und-grundausstattung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dfg-eigene-vorarbeiten-darstellen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dfg-erstantragsteller-besondere-checks`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dfg-finanzplan-module-personal-geraete`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dfg-foerderstrategie-schnell-oder-gross`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dfg-grossgeraete-und-cluster-antrag`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dfg-grundsystem-foerderlinien`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
