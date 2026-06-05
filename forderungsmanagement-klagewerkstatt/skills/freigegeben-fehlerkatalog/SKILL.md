---
name: freigegeben-fehlerkatalog
description: "Freigegeben Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Freigegeben Fehlerkatalog

## Einsatzlage

Dieser Fehlerkatalog prüft im Bereich **Forderungsmanagement Klagewerkstatt** Ergebnisse vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegen.

## Fachspezifische Fehlerachsen

- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `belegte-faellige-fmkw`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `bgb-zpo-fmkw-saumselig-fmkw-titulierung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `fmkw-mahnverfahren-bauleiter`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `fmkw-saumselig-streitig-erfahrung-spezial`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `fmkw-titulierung-streckung-leitfaden`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `fmkw-verbraucherklage-cookies-rdg-spezial`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `fmkw-verbraucherklage-forderung-anwaltshonorar-forderung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `forderung-anwaltshonorar-rvg`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `forderung-arzthonorar-goae`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
