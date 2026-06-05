---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Insolvenzrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `anfechtungsrechte-antragspflicht-15a-auslaendischer` — Anfechtungsrechte Antragspflicht 15a Auslaendischer
- `antragspflicht-spezial-belegmatrix-spezial-chronologie` — Antragspflicht Belegmatrix Chronologie
- `feststellung-sonderfall-glaeubigerantrag-inso-insolvenzrecht` — Feststellung Sonderfall Glaeubigerantrag Inso Insolvenzrecht
- `glaeubigerantrag-glaeubigerausschuss-mitwirkung-inso-dsgvo` — Glaeubigerantrag Glaeubigerausschuss Mitwirkung Inso Dsgvo
- `glaeubigerausschuss-fristennotiz-ueberschuldung-do-versicherung` — Glaeubigerausschuss Fristennotiz Ueberschuldung Do Versicherung
- `inso-gerichtliche-aufsichtswege-glaeubigerausschuss-praxis` — Inso Gerichtliche Aufsichtswege Glaeubigerausschuss Praxis
- `inso-lma-facility-massearmut-massekostenmangel-negativeintrag` — Inso Lma Facility Massearmut Massekostenmangel Negativeintrag
- `inso-npl-kreditkauf-restschuldbefreiung-versagungsgruende-schufa` — Inso Npl Kreditkauf Restschuldbefreiung Versagungsgruende Schufa
- `inso-tabelle-verbraucherinsolvenz-leitfaden-insol-insolvenzgeld` — Inso Tabelle Verbraucherinsolvenz Leitfaden Insol Insolvenzgeld
- `insol-sanierungsgewinn-7b-debt-equity-eigenverwaltung-cra-fruehe` — Insol Sanierungsgewinn 7b Debt Equity Eigenverwaltung Cra Fruehe
- `insol-sanierungsgewinn-insolvenzreife-antragspflicht-insol` — Insol Sanierungsgewinn Insolvenzreife Antragspflicht Insol
- `insol-sanierungsgewinn-liquidation-mandantenwarnung-iv` — Insol Sanierungsgewinn Liquidation Mandantenwarnung Iv
- `insol-sanierungsgewinn-uebertragende-finanzamt-stundung-verzicht` — Insol Sanierungsgewinn Uebertragende Finanzamt Stundung Verzicht
- `insolvenzrecht-kaltstart-interview` — Insolvenzrecht Kaltstart Interview

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Insolvenzrecht (Allgemein) typisch: Insolvenzantrag, Vermögensverzeichnis, Gutachten Sachverständiger, Schlussbericht.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 15a Antragspflicht 3 Wochen, Anmeldungsfrist).
- **Beweiswert einordnen.** Bilanzen, Liquiditätsplan, Geschäftsführerprotokolle jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Schuldner GmbH/Person.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
