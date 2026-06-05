---
name: bietet-fehlerkatalog
description: "Bietet Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Bietet Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Mandantenanfragen Assistent** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `anrede-anwaltskanzleien-bittet`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dankt-dsgvo-sonderfall-e-mail`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dringlichkeitsmarker-einwilligung-hinweis-erstantwort-generator`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `erstantwort-foermlich-mail`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `folgekorrespondenz-vorbereiten-konfliktcheck-vorab-ma`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `ma-einfuehrung-ma-erstvermerk-ma-konfliktcheck`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `ma-mandant-manda-erstgespraechsleitfaden-manda-erstkontakt`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `manda-mandatsablehnung-rechtsschutz-eintrittsanfrage`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `mandantenanfragen-anfrage-eingang-anrede-uebernehmen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
