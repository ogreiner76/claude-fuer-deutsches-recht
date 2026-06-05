---
name: metadaten-fehlerkatalog
description: "Nutze dies als Fehlerbremse bei Metadaten Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand."
---

# Metadaten Fehlerkatalog

## Einsatzlage

Nutze diesen Fehlerkatalog, wenn ein Ergebnis im Bereich **Verlagsredaktion** vor Abgabe, Versand, Einreichung oder Mandantenfreigabe belastbar gegengeprüft werden soll.

## Fachspezifische Fehlerachsen

- `eingangskorb-heftplanung-interessen-juristische-manuskript`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `eingangskorb-triage-entscheidungsmonitor-fremdtext-plagiat`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `lektorat-struktur-manuskriptaufnahme-materialinventar-marketing`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `qualitaetsgate-verlag-quellen-zitate-rechtecheck-urhg`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `redaktion-satzfahnen-verlage-verlagsdesk-sprachlektorat-stil`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `sales-katalog-satzfahne-korrekturlauf-autorenkommunikation`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `verl-abstimmung-lektorat-produktion-satz-rechtsabteilung-audio`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `verl-aussagensicherheit-buchprojekt-bauleiter-email-konvolute`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `verl-fussnoten-quellen-glossar-konsistenz-grammatik-handschrift`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.
- `verl-ideenpool-priorisierung-impressum-pflicht-interview-roh`: typischen Fehler aus diesem Fachpfad aktiv gegenprüfen.

## Red-Team-Fragen

1. Ist die richtige Rolle, Zuständigkeit und Verfahrensart gewählt?
2. Sind Fristbeginn, Fristende, Form, Zugang und Beweislast getrennt dokumentiert?
3. Gibt es eine Spezialnorm, die die allgemeine Lösung verdrängt?
4. Sind tatsächliche Annahmen als Annahmen markiert und Belege benannt?
5. Enthält der Output unnötige Zugeständnisse, vertrauliche Daten oder ungeprüfte Fundstellen?
6. Ist der nächste Schritt praktisch ausführbar: wer tut was bis wann mit welchem Dokument?

## Heilung

Jeden roten Punkt mit Symptom, Diagnose, Korrektur und verbleibendem Restrisiko ausgeben. Quellenhygiene nach `references/quellenhygiene.md`.
