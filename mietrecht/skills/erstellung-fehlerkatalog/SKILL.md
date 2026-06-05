---
name: erstellung-fehlerkatalog
description: "Erstellung Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Erstellung Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Mietrecht** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `amtlichen-amtsgericht-sonderfall-ausschliesslich`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `bundesland-datenerhebung-grossstadt-mietspiegel`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `klageentwurf-amtsgericht-miet-gewerbemiete-mietvertrag-bauleiter`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `lage-ausstattung-mahnung-zahlungsverzug-mandat-triage`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `miet-kuendigungsschutz-miet-mietminderung-mieteranfragen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `mieter-mieteranfragen-mandantenentscheidung-mieterhoehungs`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `mieterhoehung-widersprechen-mieterhoehungsverlangen-erstellen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `mietpreisueberhoehung-wistrg-mietsenkungsverlangen-mietspiegel`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `mietrecht-mietsenkungsverlangen-international-mietspiegel`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
