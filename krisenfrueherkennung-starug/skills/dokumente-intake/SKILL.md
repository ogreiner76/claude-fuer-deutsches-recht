---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Krisenfrueherkennung Starug** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `berater-drohende-fruehwarnsystem` — Berater Drohende Fruehwarnsystem
- `drohende-zahlungsunfaehigkeit-fortbestehensprognose-zweistufig` — Drohende Zahlungsunfaehigkeit Fortbestehensprognose Zweistufig
- `integrierte-interessen-kennzahlenset-mandantenentscheidung` — Integrierte Interessen Kennzahlenset Mandantenentscheidung
- `integrierte-planung-kennzahlenset-ampelsystem-kfe` — Integrierte Planung Kennzahlenset Ampelsystem Kfe
- `kfe-krisenstab-cross-class-dokumentationspflicht-protokollierung` — Kfe Krisenstab Cross Class Dokumentationspflicht Protokollierung
- `kfe-restrukturierungsbeauftragter-stabilisierungsanordnung` — Kfe Restrukturierungsbeauftragter Stabilisierungsanordnung
- `krisenfrueherkennung-krisenmanagement-monats` — Krisenfrueherkennung Krisenmanagement Monats
- `krisenstadien-fristennotiz-starug-gf-haftung` — Krisenstadien Fristennotiz Starug Gf Haftung
- `mandantenbrief-warnung-paragraph-starug-warnpflicht` — Mandantenbrief Warnung Paragraph Starug Warnpflicht
- `pflicht-planung-restrukturierungsplan` — Pflicht Planung Restrukturierungsplan
- `pflichtenkollision-shift-restructuring-lounge` — Pflichtenkollision Shift Restructuring Lounge
- `restrukturierungsplan-architektur-rollierende` — Restrukturierungsplan Architektur Rollierende
- `stabilisierungsanordnung-vollstreckungssperre` — Stabilisierungsanordnung Vollstreckungssperre

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Krisenfrüherkennung StaRUG typisch: Liquiditätsplan, Frühwarn-Indikatoren, Sanierungskonzept IDW S 6.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Frühzeitige Indikatoren, Restrukturierungsanzeige).
- **Beweiswert einordnen.** Forderungen offen, Bankenrunde-Protokolle jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Geschäftsführung.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
