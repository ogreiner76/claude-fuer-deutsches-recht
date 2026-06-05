---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Medizinrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `aerztewerbung-innovative-amnog-millionen` — Aerztewerbung Innovative Amnog Millionen
- `anaesthesie-hochrisiko-approbation-digitales-arzt-anstellung` — Anaesthesie Hochrisiko Approbation Digitales Arzt Anstellung
- `apothekenrecht-interessen-aufklaerung-beweislast` — Apothekenrecht Interessen Aufklaerung Beweislast
- `atmp-chain-atmp-classification` — Atmp Chain Atmp Classification
- `atmp-pharmakovigilanz-aufklaerungsfehler-beweisstrategie` — Atmp Pharmakovigilanz Aufklaerungsfehler Beweisstrategie
- `aufklaerungsfehler-behandlungsfehler` — Aufklaerungsfehler Behandlungsfehler
- `berufsrecht-bgb-einwilligung-sonderfall-fachanwalt` — Berufsrecht Bgb Einwilligung Sonderfall Fachanwalt
- `beweislast-hightech-biobank-consent` — Beweislast Hightech Biobank Consent
- `cannabis-medizinisch-combined-atmp-companion-diagnostic` — Cannabis Medizinisch Combined Atmp Companion Diagnostic
- `car-t-diga-hersteller` — Car T Diga Hersteller
- `crispr-base-cybersecurity-medizinprodukt` — Crispr Base Cybersecurity Medizinprodukt
- `dokumentationsaudit-630f-einwilligungsunfaehigkeit-ablehnung` — Dokumentationsaudit 630f Einwilligungsunfaehigkeit Ablehnung
- `epa-befuellpflicht-impfschaden-arzthaftung-medr-checkliste` — Epa Befuellpflicht Impfschaden Arzthaftung Medr Checkliste
- `experimentelle-behandlung-fachanwalt-medizinrecht-honorarvertrag` — Experimentelle Behandlung Fachanwalt Medizinrecht Honorarvertrag

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Medizinrecht typisch: Behandlungsvertrag, Patientenakte, Aufklärungsbogen, Honorarbescheid KV.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Verjährung 3 Jahre § 195 BGB, Klagefrist KV-Bescheid).
- **Beweiswert einordnen.** Patientenakte, SV-Gutachten Arzthaftung, Aufklärungsbogen mit Unterschrift jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Patient.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
