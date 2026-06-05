---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Bank Kapitalmarktrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-bk-bafin-workflow-chronologie` — Allgemein Bk Bafin Chronologie
- `anlageberatung-fehlerhaft-cybertrading-anlagebetrug` — Anlageberatung Fehlerhaft Cybertrading Anlagebetrug
- `anlageberatungsfehler-bankrecht-akkreditiv-buergschaft-erste` — Anlageberatungsfehler Bankrecht Akkreditiv Buergschaft Erste
- `bankaufsicht-erlaubnis-emissionsprospekt-mandantenentscheidung` — Bankaufsicht Erlaubnis Emissionsprospekt Mandantenentscheidung
- `bankrecht-buergschaft-aval-garantieabruf-eilrechtsschutz` — Bankrecht Buergschaft Aval Garantieabruf Eilrechtsschutz
- `bankrecht-privatbuergschaft-bankrecht-regress-bk-aufsicht` — Bankrecht Privatbuergschaft Bankrecht Regress Bk Aufsicht
- `beratungshaftung-haftung-beweislast-bk-cum` — Beratungshaftung Haftung Beweislast Bk Cum
- `bk-bankenfehlberatung-bk-einfuehrung-bk-mandantenrouting` — Bk Bankenfehlberatung Bk Einfuehrung Bk Mandantenrouting
- `bk-mifid-bk-prip-erstgespraech-mandatsannahme` — Bk Mifid Bk Prip Erstgespraech Mandatsannahme
- `fehlerhaft-fristennotiz-kapitalmarktrecht-bk-emissionsprospekt` — Fehlerhaft Fristennotiz Kapitalmarktrecht Bk Emissionsprospekt
- `gesellschaftsrecht-interessen-micar-mifid` — Gesellschaftsrecht Interessen Micar Mifid
- `kreditkuendigung-bgb-mica-stablecoin-ombudsmann-bafin` — Kreditkuendigung Bgb Mica Stablecoin Ombudsmann Bafin
- `mandat-triage-schriftsatzkern-substantiierung-bank` — Mandat Triage Schriftsatzkern Substantiierung Bank
- `orientierung-schufa-eintrag-schufa-loeschungsanspruch` — Orientierung Schufa Eintrag Schufa Loeschungsanspruch

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Bank- und Kapitalmarktrecht typisch: Darlehensvertrag, Wertpapierorder, Beratungsprotokoll, Prospekt.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Widerrufsfrist Verbraucherdarlehen 14 Tage § 355 BGB, MiFID II-Reports).
- **Beweiswert einordnen.** Beratungsprotokoll, Geeignetheitsprüfung, Anlegerprofil jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Anleger/Kunde.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
