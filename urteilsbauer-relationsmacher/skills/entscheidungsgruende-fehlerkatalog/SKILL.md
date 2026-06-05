---
name: entscheidungsgruende-fehlerkatalog
description: "Entscheidungsgruende Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Entscheidungsgruende Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Urteilsbauer Relationsmacher** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `aktenintake-zivil`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `amts-aktenintake-zivil-anspruchsgrundlagen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anspruchsgrundlagen-pruefen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `berufungsfest-beschluss-bauen-beweisbeschluss-vorbereiten`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `berufungsfest-pruefen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `beschluss-bauen-zpo`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `beweisbeschluss-vorbereiten`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `beweiswuerdigung-mit-richter-input`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `beweiswuerdigung-richter-cisg-dsgvo-rechtswidriges`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
