---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Datenschutzrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `anwendungsfall-triage` — Anwendungsfall Triage
- `avv-art-26-joint-controllership-deutsch` — Avv Art 26 Joint Controllership Deutsch
- `avv-art-28-dsgvo-grundtatbestand` — Avv Art 28 Dsgvo Grundtatbestand
- `avv-art-28-mindestinhalte-checkliste` — Avv Art 28 Mindestinhalte Checkliste
- `avv-audit-avv-cloud-avv-eu-avv-konzern-avv` — Avv Audit Avv Cloud Avv Eu Avv Konzern Avv
- `avv-audit-und-kontrollrechte` — Avv Audit Und Kontrollrechte
- `avv-bestehender-avv-rolemix-avv-tom-datenpanne-meldung` — Avv Bestehender Avv Rolemix Avv Tom Datenpanne Meldung
- `avv-cloud-und-subverarbeitung-art-28-iv` — Avv Cloud Und Subverarbeitung Art 28 Iv
- `avv-eu-kommission-musterklauseln-2021-915` — Avv Eu Kommission Musterklauseln 2021 915
- `avv-eu-us-data-privacy-framework-bezug` — Avv Eu Us Data Privacy Framework Bezug
- `avv-haftung-datenschutz-schadensersatz-dsfa-risikoanalyse-dsr` — Avv Haftung Datenschutz Schadensersatz Dsfa Risikoanalyse Dsr
- `avv-haftung-risikoallokation-art-82-dsgvo` — Avv Haftung Risikoallokation Art 82 Dsgvo
- `avv-konzern-und-multi-party-konstellation` — Avv Konzern Und Multi Party Konstellation
- `avv-loeschung-rueckgabe-nach-vertragsende` — Avv Löschung Rueckgabe Nach Vertragsende

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Datenschutzrecht DSGVO/BDSG typisch: Verarbeitungsverzeichnis, DSFA, AVV, Datenschutzerklärung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Art. 33 Meldung 72h, Art. 12 Antrag 1 Monat).
- **Beweiswert einordnen.** Log-Dateien, AVV-Verträge, Audit-Berichte jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Verantwortlicher.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
