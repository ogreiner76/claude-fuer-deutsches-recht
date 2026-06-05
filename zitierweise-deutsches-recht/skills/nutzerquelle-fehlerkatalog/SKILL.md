---
name: nutzerquelle-fehlerkatalog
description: "Nutze dies als Fehlerbremse bei Nutzerquelle Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Nutzerquelle Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Zitierweise Deutsches Recht** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `aufsatz-interessen-beckrs-blindzitate`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `datum-entscheidungsform-spezial-gericht`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `hauszitierweise-juristische-kommentar`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `literatur-live-beweislast-lizenziertem`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `rechtsprechung-zit-rechtsprechungszitierung-zitat-eugh`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `verifizierbarer-zugriff-sonderfall-zit-gesetzeszitierung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `zit-gesetzeszitierung-bauleiter`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `zit-internationale-urteile-spezial`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `zit-internationale-zit-kommentar-zitat-amtliche`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
