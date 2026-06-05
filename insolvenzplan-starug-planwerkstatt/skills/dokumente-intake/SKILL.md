---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Insolvenzplan Starug Planwerkstatt** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `abstimmung-anlagen-interessen-cram` — Abstimmung Anlagen Interessen Cram
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `down-red-gestaltender-gruppen` — Down Red Gestaltender Gruppen
- `insolvenzplan-intake-klassen` — Insolvenzplan Intake Klassen
- `ips-abstimmung-ips-anlagenpaket-ips-asset` — Ips Abstimmung Ips Anlagenpaket Ips Asset
- `ips-cramdown-ips-datenraum-ips-gestaltender` — Ips Cramdown Ips Datenraum Ips Gestaltender
- `ips-gerichtliche-ips-ips-steuern` — Ips Gerichtliche Ips Ips Steuern
- `ips-gruppen-ips-architektur-ips-integrierte` — Ips Gruppen Ips Architektur Ips Integrierte
- `ips-ips-sanierungskonzept-ips-sicherheiten` — Ips Ips Sanierungskonzept Ips Sicherheiten
- `ips-kaltstart-interview` — Ips Kaltstart Interview
- `ips-minderheitenschutz-ips-planbetroffene-ips-planvollzug` — Ips Minderheitenschutz Ips Planbetroffene Ips Planvollzug
- `ips-stabilisierung-ips-stakeholder-ips-plan` — Ips Stabilisierung Ips Stakeholder Ips Plan
- `ips-verfahrenswahl-restrukturierungsplan-ips-darstellender` — Ips Verfahrenswahl Restrukturierungsplan Ips Darstellender
- `ips-vergleichsrechnung-ipsplan-cram-ipsplan-gruppenbildung` — Ips Vergleichsrechnung Ipsplan Cram Ipsplan Gruppenbildung

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Insolvenzplan / StaRUG typisch: Insolvenzplan, Restrukturierungsplan, Gruppenbildung, Vergleichsrechnung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Erörterungstermin, Stop-and-go-Verfahren StaRUG).
- **Beweiswert einordnen.** Liquiditätsplan, Sanierungskonzept, IDW S 6 jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Schuldnerunternehmen.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
