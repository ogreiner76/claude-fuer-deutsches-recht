---
name: insolvenzlage-fehlerkatalog
description: "Insolvenzlage Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Insolvenzlage Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Forschungszulage Antragstellung** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `abgrenzung-adaptiver-antrag`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `antragstellung-auszahlung-beihilfen-beweislast`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `bemessungsgrundlage-interessen-bsfz-definition`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `forsch-bsfz-pruefung-spezial`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `forsch-konzernverbund-forschung-spezial`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `forsch-projektbeschreibung-bauleiter`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `forsch-stundenaufzeichnung-fz-ablehnung-bemessungsgrundlage`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `forsch-stundenaufzeichnung-leitfaden`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `forschungszulage-insolvenzlage-red-portaltexte`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
