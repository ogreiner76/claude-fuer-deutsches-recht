---
name: anlagen-zu-schriftsaetzen-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Anlagen Zu Schriftsaetzen** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `anlage-red-anlagen-anlagenkonvolut-sonderfall-arial` — Anlage Red Anlagen Anlagenkonvolut Sonderfall Arial
- `anlagen-an-assistenz-uebersetzungspflicht-vorlagepflicht-zpo` — Anlagen An Assistenz Uebersetzungspflicht Vorlagepflicht Zpo
- `anlagen-aus-datenraum-und-sharepoint` — Anlagen Aus Datenraum Und Sharepoint
- `anlagen-aus-edv-systemen` — Anlagen Aus Edv Systemen
- `anlagen-aus-mandantenmaterial` — Anlagen Aus Mandantenmaterial
- `anlagen-bei-berufung-revision` — Anlagen Bei Berufung Revision
- `anlagen-bei-eilantrag-eu-arrest` — Anlagen Bei Eilantrag Eu Arrest
- `anlagen-berufung-revision-eilantrag-eu-bilder-screenshots` — Anlagen Berufung Revision Eilantrag Eu Bilder Screenshots
- `anlagen-bilder-screenshots` — Anlagen Bilder Screenshots
- `anlagen-check-zustellung-redaktion-dsgvo-schwaerzen-stempel` — Anlagen Check Zustellung Redaktion Dsgvo Schwaerzen Stempel
- `anlagen-duplikate-versionen-hashlog` — Anlagen Duplikate Versionen Hashlog
- `anlagen-elektronische-dokumente-format-dateinamen-bea-versand` — Anlagen Elektronische Dokumente Format Dateinamen Bea Versand
- `anlagen-elektronische-dokumente-spezial` — Anlagen Elektronische Dokumente Spezial
- `anlagen-format-und-dateinamen` — Anlagen Format Und Dateinamen

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Anlagen zu Schriftsätzen typisch: Verträge, Korrespondenz, Rechnungen, Lichtbilder.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Klageerwiderungsfrist, Ergänzende Stellungnahme im Termin).
- **Beweiswert einordnen.** Urkunden, Lichtbilder, Sachverständigengutachten jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Mandant.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
