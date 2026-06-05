---
name: vendor-fehlerkatalog
description: "Nutze dies, wenn Vendor Fehlerkatalog im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?."
---

# Vendor Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Tabellenreview 3d** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `aggregation-spaltenprompts-definieren-arbeitsblatt`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `allgemein-workflow-chronologie-workflow-fristen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `arbeitsblatt-perspektiven-definieren`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `audit-trail-protokoll`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `belegkette-rueckverfolgung`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `belegkette-rueckverfolgung-caching-rerun-dokumentstapel`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `caching-und-teil-rerun`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `datenpunkt-dokument-excel-beweislast`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `dokumentstapel-aufnehmen`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `excel-multi-kreuzblatt-konsistenzpruefung-pdf-bericht`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
