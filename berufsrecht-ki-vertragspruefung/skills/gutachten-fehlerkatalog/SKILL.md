---
name: gutachten-fehlerkatalog
description: "Nutze dies als Fehlerbremse bei Gutachten Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Gutachten Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Berufsrecht Ki Vertragspruefung** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `ai-act-rollen-kanzlei-provider-deployer-api`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `allgemein-brki-rollout-workflow-chronologie`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anbietern-belehrung-sonderfall-edge`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `art-50-ki-vo-schriftsatz-marketing-chatbot`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `avv-grenzpruefung-brki-anbieter-brki-eu`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `avv-grenzpruefung-datenschutz`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `berufsrecht-ki-vertragspruefung-kaltstart-interview`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `berufsrechtliche-bnoto-interessen-brao`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `brki-anbieter-due-diligence`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `brki-eu-us-dpf-transferpruefung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
