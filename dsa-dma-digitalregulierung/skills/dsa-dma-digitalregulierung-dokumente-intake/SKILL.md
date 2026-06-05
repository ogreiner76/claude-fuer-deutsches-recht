---
name: dsa-dma-digitalregulierung-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Dsa Dma Digitalregulierung** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `dark-patterns-internes-beschwerdesystem` — Dark Patterns Internes Beschwerdesystem
- `data-digitalregulierung-dora` — Data Digitalregulierung Dora
- `dma-business-user-gatekeeper-kernplattformdienste` — Dma Business User Gatekeeper Kernplattformdienste
- `dma-pflichten-dsa-art-forschungsdatenzugang-algorithmen` — Dma Pflichten Dsa Art Forschungsdatenzugang Algorithmen
- `dsa-eidas-einordnung` — Dsa Eidas Einordnung
- `erstellung-forschungsdatenzugang-mehrparteienkonflikt-gatekeeper` — Erstellung Forschungsdatenzugang Mehrparteienkonflikt Gatekeeper
- `kernplattformdienste-sonderfall-klagewege-risikobewertung` — Kernplattformdienste Sonderfall Klagewege Risikobewertung
- `out-court-pflichten-pyramide-systemic-risk` — Out Court Pflichten Pyramide Systemic Risk
- `pyramide-check-dsgvo-p2b-anti-steering` — Pyramide Check Dsgvo P2b Anti Steering
- `transparenzbericht-erstellung-trusted-flagger-vlop-vlose` — Transparenzbericht Erstellung Trusted Flagger Vlop Vlose
- `transparenzbericht-fristennotiz-dsa-dma-account-sperre` — Transparenzbericht Fristennotiz Dsa Dma Account Sperre
- `werbearchiv-aufbauen-klage-gegen-account` — Werbearchiv Aufbauen Klage Gegen Account
- `zustellung-vertreter` — Zustellung Vertreter

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei DSA/DMA Digitalregulierung typisch: AGB, Risikobewertung, Transparenzberichte, Notice-Templates.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (DSA Risikoberichte jährlich, VLOP/VLOSE-Designation).
- **Beweiswert einordnen.** Compliance-Tickets, Audit-Reports, User-Statistiken jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Plattform/VLOP.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
