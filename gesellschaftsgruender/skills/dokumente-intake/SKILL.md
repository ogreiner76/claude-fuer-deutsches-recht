---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Gesellschaftsgruender** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `egbr-mopeg-gesellschaftsgruender-familiengesellschaft` — Egbr Mopeg Gesellschaftsgruender Familiengesellschaft
- `geschaeftsordnung-gf-gesellschafterstreit-eilantraege` — Geschaeftsordnung Gf Gesellschafterstreit Eilantraege
- `gesellschaftsgruender-anfaenger-kaltstart` — Gesellschaftsgruender Anfaenger Kaltstart
- `gesellschaftsgruender-bankkonto-kyc-beirat-advisory-bilinguale` — Gesellschaftsgruender Bankkonto Kyc Beirat Advisory Bilinguale
- `gesellschaftsgruender-cashburn-insolvenzfruehwarnung-checkliste` — Gesellschaftsgruender Cashburn Insolvenzfruehwarnung Checkliste
- `gesellschaftsgruender-freiberufler-partg-gbr-ohg-genehmigtes` — Gesellschaftsgruender Freiberufler Partg Gbr Ohg Genehmigtes
- `gesellschaftsgruender-gesellschafterliste-qualitygate` — Gesellschaftsgruender Gesellschafterliste Qualitygate
- `gesellschaftsgruender-gmbh-vorbereitung-golden-share-gv` — Gesellschaftsgruender Gmbh Vorbereitung Golden Share Gv
- `gesellschaftsgruender-handelsregister-anmeldung-ihk-investor-dd` — Gesellschaftsgruender Handelsregister Anmeldung Ihk Investor Dd
- `gesellschaftsgruender-lizenz-vertriebsstart-lohn-payroll` — Gesellschaftsgruender Lizenz Vertriebsstart Lohn Payroll
- `gesellschaftsgruender-musterprotokoll-vs-notar-vorbereitung` — Gesellschaftsgruender Musterprotokoll Vs Notar Vorbereitung
- `gesellschaftsgruender-open-source-plain-language-reguliertes` — Gesellschaftsgruender Open Source Plain Language Reguliertes
- `gesellschaftsgruender-redteam-gruendungspaket` — Gesellschaftsgruender Redteam Gruendungspaket
- `gesellschaftsgruender-steuerliche-erfassung-treuhand-nominee` — Gesellschaftsgruender Steuerliche Erfassung Treuhand Nominee

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Gesellschaftsgründung typisch: Gesellschaftsvertrag, Notarurkunde, Liste Gesellschafter, Handelsregisteranmeldung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Handelsregistereintragung, ELSTER Anmeldung Steuern).
- **Beweiswert einordnen.** Stammeinlage-Bestätigung, Geschäftsanschrift-Nachweis jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Gründer.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
