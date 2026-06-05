---
name: fahrlaessigkeit-fehlerkatalog
description: "Nutze dies als Fehlerbremse bei Fahrlaessigkeit Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Fahrlaessigkeit Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Phishing Vorfall Prüfer** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `675u-675w-banking`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `arbeitnehmer-haftung-bgb-675u-phish-ceo`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `aufsicht-bafin-bank-strategie-banking-app`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `bankpflichten-beweislast-beweislast-bgb`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `bea-notfall-bgb-675v-erstkontakt-mandant`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `call-interessen-faelle-freistehender`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `grobe-online-phishing`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `klage-fristennotiz-vorfall-phish-banking`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `phish-incident-phish-meldepflichten-arten-erkennen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
