---
name: legistik-werkstatt-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Legistik Werkstatt** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen-legw-bmleh` — Allgemein Chronologie Fristen Legw Bmleh
- `begruendung-allgemein-und-besonders` — Begruendung Allgemein Und Besonders
- `dokumente-rendern-docx-pdf` — Dokumente Rendern Docx Pdf
- `europarechtskonformitaet` — Europarechtskonformitaet
- `folgenabschaetzung-erfuellungsaufwand` — Folgenabschaetzung Erfuellungsaufwand
- `folgenabschaetzung-erfuellungsaufwand-folgenabschaetzung` — Folgenabschaetzung Erfuellungsaufwand Folgenabschaetzung
- `folgenabschaetzung-nachhaltigkeit` — Folgenabschaetzung Nachhaltigkeit
- `formulierungshilfe-bauen` — Formulierungshilfe Bauen
- `gesetzesentwurf-kabinett` — Gesetzesentwurf Kabinett
- `gesetzgebungskompetenz-pruefen` — Gesetzgebungskompetenz Prüfen
- `goldplating-vermeiden` — Goldplating Vermeiden
- `goldplating-vermeiden-inkrafttreten-uebergangsrecht-legistik` — Goldplating Vermeiden Inkrafttreten Uebergangsrecht Legistik
- `inkrafttreten-uebergangsrecht` — Inkrafttreten Uebergangsrecht
- `laender-landtage-legistik-ministerien-opposition` — Länder Landtage Legistik Ministerien Opposition

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Legistik-Werkstatt (Gesetzgebung) typisch: Referentenentwurf, Kabinettvorlage, BR-Drucksache, BT-Drucksache.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Beteiligungsfristen, Kabinettsbeschluss).
- **Beweiswert einordnen.** Folgenabschätzung, Stellungnahmen Verbände jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Ressort.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
