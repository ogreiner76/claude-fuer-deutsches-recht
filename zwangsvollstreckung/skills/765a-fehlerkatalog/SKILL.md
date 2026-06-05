---
name: 765a-fehlerkatalog
description: "Nutze dies, wenn 765a Fehlerkatalog im Plugin Zwangsvollstreckung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?."
---

# 765a Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Zwangsvollstreckung** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `bank-haertefall-inso`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `kontenpfaendung-notar-interessen-online`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `mahnbescheid-fristennotiz-zv-titel-zv-kontensuche`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `pfueb-raeumung-schuldnerschutz-beweislast`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `vermoegensauskunft-vollstreckungsbescheid-vollstreckungstitel`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `zpo-zwangsvollstreckung-zv-abwehr`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `zv-elektronische-zv-eu-zv`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `zv-mahnbescheid-zv-mobiliar-zv-notarielle`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `zv-pfaendungstabelle-zv-pfueb-zv-pfueb`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
