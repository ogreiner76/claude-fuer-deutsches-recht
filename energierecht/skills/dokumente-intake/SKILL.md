---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Energierecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `einfuehrung-energieprojekt-intake-energierecht-industrie` — Einfuehrung Energieprojekt Intake Energierecht Industrie
- `energierecht-emobility-wasserstoff-energievertraege` — Energierecht Emobility Wasserstoff Energievertraege
- `energierecht-netz-speicher-projektfinanzierung-transaktionen-dd` — Energierecht Netz Speicher Projektfinanzierung Transaktionen Dd
- `energierecht-vertrieb-marktrollen-waerme-quartier-wettbewerb` — Energierecht Vertrieb Marktrollen Waerme Quartier Wettbewerb
- `er-bess-abstandsflaechen-baurecht-brandenburg-behoerdenstrategie` — Er Bess Abstandsflaechen Baurecht Brandenburg Behoerdenstrategie
- `er-bess-brandschutz-co-location-datenschutz-video` — Er Bess Brandschutz Co Location Datenschutz Video
- `er-bess-epc-fca-agnes-finanzierung-bankability-kapazitaetsmarkt` — Er Bess Epc Fca Agnes Finanzierung Bankability Kapazitaetsmarkt
- `er-bess-er-bess-er-einfuehrung-er-fusion` — Er Bess Er Bess Er Einfuehrung Er Fusion
- `er-bess-er-bess-er-stakeholder-eeg-kwkg` — Er Bess Er Bess Er Stakeholder Eeg Kwkg
- `er-bess-kaltstart-projektaufnahme` — Er Bess Kaltstart Projektaufnahme
- `er-bess-kritis-marktrollen-bilanzkreis-naturschutz-artenschutz` — Er Bess Kritis Marktrollen Bilanzkreis Naturschutz Artenschutz
- `er-bess-netzentgelte-output-board-physische-sicherheit-power-emv` — Er Bess Netzentgelte Output Board Physische Sicherheit Power Emv
- `er-bess-ppa-projektakte-rechtsmittel-nachbarabwehr-regelenergie` — Er Bess Ppa Projektakte Rechtsmittel Nachbarabwehr Regelenergie
- `er-fusion-buergerbeteiligung-foerderung-beihilfe-netzanschluss` — Er Fusion Buergerbeteiligung Foerderung Beihilfe Netzanschluss

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Energierecht (EnWG, EEG) typisch: Netzanschlussvertrag, EEG-Vergütungsbescheid, Marktstammdatenregister-Eintrag.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Beschwerde BNetzA-Beschluss 1 Monat § 75 EnWG, Netzanschlussfristen).
- **Beweiswert einordnen.** Messdaten, Anschlussberichte, Audit-Bescheinigungen jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Erzeuger.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
