---
name: umweltrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Umweltrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `abfall-anlagen-bimschg` — Abfall Anlagen Bimschg
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `boden-csddd-csrd-sonderfall` — Boden Csddd Csrd Sonderfall
- `diligence-greenwashing-beweislast-klimaklagen-interessen` — Diligence Greenwashing Beweislast Klimaklagen Interessen
- `esg-greenwashing-klimaklagen-verbandsklage-lksg-csddd` — Esg Greenwashing Klimaklagen Verbandsklage Lksg Csddd
- `lieferkettensorgfalt-lksg-red-naturschutz` — Lieferkettensorgfalt Lksg Red Naturschutz
- `stoerfall-anlagen-transaktionen-dd-umweltinformation-uig` — Stoerfall Anlagen Transaktionen Dd Umweltinformation Uig
- `tehg-verfahren-umweltrecht-verfahren` — Tehg Verfahren Umweltrecht Verfahren
- `umwelt-umweltrecht-umwrg` — Umwelt Umweltrecht Umwrg
- `umweltrecht-bussgeld-emissionshandel-tehg-uwr-ets` — Umweltrecht Bussgeld Emissionshandel Tehg Uwr Ets
- `umweltrecht-immissionsschutz-bimschg-naturschutz-artenschutz` — Umweltrecht Immissionsschutz Bimschg Naturschutz Artenschutz
- `uwr-bundesnaturschutzgesetz-uwr-co2-uwr-immissionsschutz` — Uwr Bundesnaturschutzgesetz Uwr Co2 Uwr Immissionsschutz
- `uwr-einfuehrung-rechtsquellen` — Uwr Einfuehrung Rechtsquellen
- `uwr-wasserrechtliche` — Uwr Wasserrechtliche

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Umweltrecht typisch: UVP-Bericht, Genehmigungsbescheid, Stellungnahmen Umweltverbände.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Klagefrist UVPG, Genehmigungsverfahren).
- **Beweiswert einordnen.** Immissionsmessungen, Bodengutachten, Artenschutz-Bericht jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Vorhabenträger.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
