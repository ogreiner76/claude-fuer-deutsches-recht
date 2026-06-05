---
name: liquiditaetsplanung-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Liquiditaetsplanung** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `deutschem-dokumentationspaket-excel` — Deutschem Dokumentationspaket Excel
- `export-forecast-fortbestehensprognose-international` — Export Forecast Fortbestehensprognose International
- `idw-s6-integrierte-sanierungsplanung` — Idw S6 Integrierte Sanierungsplanung
- `insolvenzrecht-liqui-sonderfall-liquiditaetsplanung` — Insolvenzrecht Liqui Sonderfall Liquiditaetsplanung
- `interessen-verifikation-beweislast-vorschau` — Interessen Verifikation Beweislast Vorschau
- `liqp-bankenreporting-leitfaden` — Liqp Bankenreporting Leitfaden
- `liqp-liquiditaetspool-cash-pooling-spezial` — Liqp Liquiditaetspool Cash Pooling Spezial
- `liqp-liquiditaetspool-cash-rollende-13wochen-warenkredit-skonto` — Liqp Liquiditaetspool Cash Rollende 13wochen Warenkredit Skonto
- `liqp-rollende-13wochen-bauleiter` — Liqp Rollende 13wochen Bauleiter
- `liqp-warenkredit-skonto-szenarien-spezial` — Liqp Warenkredit Skonto Szenarien Spezial
- `liqui-ausgabengruppen-systematik` — Liqui Ausgabengruppen Systematik
- `liqui-bei-drohender-zahlungsunfaehigkeit` — Liqui Bei Drohender Zahlungsunfaehigkeit
- `liqui-bei-eingetretener-zahlungsunfaehigkeit` — Liqui Bei Eingetretener Zahlungsunfaehigkeit

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Liquiditätsplanung typisch: Liquiditätsplan, Bankenstatus, Forderungs-/Verbindlichkeitenliste.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Rolling 13-week-Plan, Quartalsplan).
- **Beweiswert einordnen.** Bankbestätigungen, Eingangs-/Ausgangsrechnungen jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Geschäftsführung.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
