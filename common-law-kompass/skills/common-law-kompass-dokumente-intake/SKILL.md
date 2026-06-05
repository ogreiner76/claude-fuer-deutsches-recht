---
name: common-law-kompass-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Common Law Kompass** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `begriffe-uebersetzung-bilingual-contract-client-explainer` — Begriffe Uebersetzung Bilingual Contract Client Explainer
- `bilinguale-client-commercial-sonderfall` — Bilinguale Client Commercial Sonderfall
- `cl-mandantenuebersicht-cl-prozesskostenrisiko-cl-precedent` — Cl Mandantenuebersicht Cl Prozesskostenrisiko Cl Precedent
- `cl-vertragsklauseln-vertragsbegriffe-cl-discovery` — Cl Vertragsklauseln Vertragsbegriffe Cl Discovery
- `common-consideration-discovery` — Common Consideration Discovery
- `contract-formation-false-friends-governing-jurisdiction` — Contract Formation False Friends Governing Jurisdiction
- `drafting-interessen-explainer-beweislast-false-friends` — Drafting Interessen Explainer Beweislast False Friends
- `friends-indemnity-quality` — Friends Indemnity Quality
- `humor-coach-interpretation-precedent-common-law` — Humor Coach Interpretation Precedent Common Law
- `litigation-discovery-ma-commercial-quality-gate` — Litigation Discovery Ma Commercial Quality Gate
- `rechtsvergleichender-begriffscheck-reviews-suretyship` — Rechtsvergleichender Begriffscheck Reviews Suretyship
- `remedies-damages-representations-warranties-simulation` — Remedies Damages Representations Warranties Simulation
- `surety-guarantee-ucc-sales-us-vs` — Surety Guarantee Ucc Sales Us Vs

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Common Law Kompass typisch: Pleadings, Discovery requests, Affidavits, Judgments/Orders.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Statutes of Limitations je Jurisdiction, Discovery deadlines).
- **Beweiswert einordnen.** Witness statements, Expert reports, Documentary evidence jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Mandant US/UK.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
