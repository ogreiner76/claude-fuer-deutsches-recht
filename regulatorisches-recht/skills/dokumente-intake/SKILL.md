---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Regulatorisches Recht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-anschluss-router-workflow-chronologie` — Allgemein Anschluss Router Chronologie
- `aufsichts-feed-monitor` — Aufsichts Feed Monitor
- `aufsichtsverfahren-anhoerung-aufsichtsverfahren-gwg` — Aufsichtsverfahren Anhoerung Aufsichtsverfahren Gwg
- `dora-ikt-vertragspruefung` — Dora Ikt Vertragspruefung
- `enwg-feeds-heilmwerbg` — Enwg Feeds Heilmwerbg
- `inkasso-massnahme-regulator` — Inkasso Massnahme Regulator
- `inkasso-rdg-luecken-mar-mifid` — Inkasso Rdg Luecken Mar Mifid
- `interview-fristennotiz-aufsichtssanktion-revision-umsatzsteuer` — Interview Fristennotiz Aufsichtssanktion Revision Umsatzsteuer
- `luecken-aufzeiger` — Luecken Aufzeiger
- `regr-dora-resilienz-finanzdienstleistungsregulierung-bauleiter` — Regr Dora Resilienz Finanzdienstleistungsregulierung Bauleiter
- `regr-mifid2-regrecht-einfuehrung-regrecht-internal` — Regr Mifid2 Regrecht Einfuehrung Regrecht Internal
- `regulatorisches-recht-kaltstart-interview` — Regulatorisches Recht Kaltstart Interview
- `regulatorisches-richtlinien-neufassung` — Regulatorisches Richtlinien Neufassung
- `regulatorisches-stellungnahmen-beweislast-voranmeldung` — Regulatorisches Stellungnahmen Beweislast Voranmeldung

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Regulatorisches Recht (Sektoren) typisch: Genehmigungsbescheid, Aufsichtsbescheid, Compliance-Manual.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Beschwerdefrist Aufsichtsbescheid, Berichtspflichten zyklisch).
- **Beweiswert einordnen.** Compliance-Logs, Audit-Reports jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Unternehmen reguliert.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
