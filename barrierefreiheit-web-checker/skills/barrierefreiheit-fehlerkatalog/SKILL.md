---
name: barrierefreiheit-fehlerkatalog
description: "Barrierefreiheit Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Barrierefreiheit Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Barrierefreiheit Web Checker** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `audit-barrierefreiheits-bfsg`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `bf-kiosk-bf-mediendienste-bf-pdf`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `bfsg-zeitleiste-ecommerce-checkout-en301549-wcag`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `bfsgv-schulung-fristennotiz-agentur-abnahme`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `bitv-checkout-beweislast-ecommerce`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `erklaerung-interessen-formulare-pdfs`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `formulare-checkout-kontrast-farbe-native-apps`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `pdf-downloads-remediation-roadmap-schulung-rolle`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `pdf-formulare-automatisierter-audit-bf-kanzleiwebsite`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
