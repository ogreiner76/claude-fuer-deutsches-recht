---
name: nda-abgleich-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Nda Abgleich** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `ausgabe-changes-docx-beweislast` — Ausgabe Changes Docx Beweislast
- `durch-interessen-echten-sonderfall-eigenen` — Durch Interessen Echten Sonderfall Eigenen
- `gegen-gelb-gleicht` — Gegen Gelb Gleicht
- `gegenseite-tracked-fristennotiz-nda-definitionsklausel` — Gegenseite Tracked Fristennotiz Nda Definitionsklausel
- `geschaeftsgeheimnis-geschgehg-kartellsensitiven-daten` — Geschaeftsgeheimnis Geschgehg Kartellsensitiven Daten
- `haltelinien-setzt-standard` — Haltelinien Setzt Standard
- `it-saas-laufzeit-survival-m-a` — It Saas Laufzeit Survival M A
- `m-a-aenderungsmodus-ampelmatrix` — M A Aenderungsmodus Ampelmatrix
- `mitarbeiter-need-non-solicit-permitted-disclosure` — Mitarbeiter Need Non Solicit Permitted Disclosure
- `nda-abgleich` — Nda Abgleich
- `nda-abgleich-arbeitnehmer-kuendigung-bewerbungen-pitches` — Nda Abgleich Arbeitnehmer Kündigung Bewerbungen Pitches
- `nda-anwendbares-recht-gerichtsstand` — Nda Anwendbares Recht Gerichtsstand
- `nda-bei-arbeitnehmer-kuendigung` — Nda Bei Arbeitnehmer Kündigung

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei NDA-Abgleich typisch: NDA-Entwurf, Mustervorlage, Vorvertrags-Korrespondenz.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Geltungsdauer NDA (5-10 Jahre)).
- **Beweiswert einordnen.** Versionsverlauf, Mailverkehr jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Vertragspartner.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
