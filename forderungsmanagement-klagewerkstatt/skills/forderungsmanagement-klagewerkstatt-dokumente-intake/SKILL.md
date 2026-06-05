---
name: forderungsmanagement-klagewerkstatt-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Forderungsmanagement Klagewerkstatt** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `belegte-faellige-fmkw` — Belegte Faellige Fmkw
- `bgb-zpo-fmkw-saumselig-fmkw-titulierung` — Bgb Zpo Fmkw Saumselig Fmkw Titulierung
- `fmkw-mahnverfahren-bauleiter` — Fmkw Mahnverfahren Bauleiter
- `fmkw-saumselig-streitig-erfahrung-spezial` — Fmkw Saumselig Streitig Erfahrung Spezial
- `fmkw-titulierung-streckung-leitfaden` — Fmkw Titulierung Streckung Leitfaden
- `fmkw-verbraucherklage-cookies-rdg-spezial` — Fmkw Verbraucherklage Cookies Rdg Spezial
- `fmkw-verbraucherklage-forderung-anwaltshonorar-forderung` — Fmkw Verbraucherklage Forderung Anwaltshonorar Forderung
- `forderung-anwaltshonorar-rvg` — Forderung Anwaltshonorar Rvg
- `forderung-arzthonorar-goae` — Forderung Arzthonorar Goae
- `forderung-aus-werkvertrag-bgb-bau` — Forderung Aus Werkvertrag Bgb Bau
- `forderung-gegen-gesellschafter-13-gmbhg` — Forderung Gegen Gesellschafter 13 Gmbhg
- `forderung-gegen-gesellschafter-insolventen-schuldner-ausland` — Forderung Gegen Gesellschafter Insolventen Schuldner Ausland
- `forderung-gegen-insolventen-schuldner` — Forderung Gegen Insolventen Schuldner

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Forderungsmanagement Klagewerkstatt typisch: Mahnung, Mahnbescheid, Vollstreckungsbescheid, Klage.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Mahnbescheid-Widerspruch 2 Wochen, Vollstreckungstitel).
- **Beweiswert einordnen.** Vertrag, Rechnung, Lieferschein jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Gläubiger.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
