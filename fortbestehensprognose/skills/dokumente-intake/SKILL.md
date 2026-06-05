---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fortbestehensprognose** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `annahmen-sammeln-bilanzieller-status-comfortletter-weich` — Annahmen Sammeln Bilanzieller Status Comfortletter Weich
- `comfortletter-sonderfall-edge-forderungsverzicht` — Comfortletter Sonderfall Edge Forderungsverzicht
- `fbp-bankenkommunikation-fbp-integrierte-fbp-stresstest` — Fbp Bankenkommunikation Fbp Integrierte Fbp Stresstest
- `fbp-zahlungsunfaehigkeit-fortbestehensprognose-zusammenfuehren` — Fbp Zahlungsunfaehigkeit Fortbestehensprognose Zusammenfuehren
- `fortbestehensdokumentation-insolvenzrecht-fortbestehensprognose` — Fortbestehensdokumentation Insolvenzrecht Fortbestehensprognose
- `fortbestehensprognose-kaltstart-interview` — Fortbestehensprognose Kaltstart Interview
- `fp-gerichtsfaehigkeit-fp-einfuehrung-fp-zeitraum` — Fp Gerichtsfaehigkeit Fp Einfuehrung Fp Zeitraum
- `gesellschafterdarlehen-rangruecktritt-liquiditaet-monate` — Gesellschafterdarlehen Rangruecktritt Liquiditaet Monate
- `liquiditaet-patronatserklaerung-interessen-plausibilisierung` — Liquiditaet Patronatserklaerung Interessen Plausibilisierung
- `negativer-fristennotiz-ausloesendes-ereignis-forderungsverzicht` — Negativer Fristennotiz Ausloesendes Ereignis Forderungsverzicht
- `prognose-stichtag-stundungsanfrage-glaeubiger-annahmen` — Prognose Stichtag Stundungsanfrage Glaeubiger Annahmen
- `rangruecktritt-sanierungsbausteine-selbstdokumentation` — Rangruecktritt Sanierungsbausteine Selbstdokumentation
- `sanierungsbausteine-vorschlagen-annahmen-bilanzstatus` — Sanierungsbausteine Vorschlagen Annahmen Bilanzstatus

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fortbestehensprognose StaRUG/InsO typisch: Liquiditätsplan 24 Monate, Erfolgsplan, Bilanz, GuV.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Antragsfrist 3 Wochen § 15a InsO, StaRUG-Restrukturierungsanzeige).
- **Beweiswert einordnen.** Bankbestätigungen, Forderungslisten, Verbindlichkeitenliste jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Geschäftsführung.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
