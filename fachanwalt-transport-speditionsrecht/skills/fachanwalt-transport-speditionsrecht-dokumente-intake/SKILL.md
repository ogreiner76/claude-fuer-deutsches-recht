---
name: fachanwalt-transport-speditionsrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Transport Speditionsrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `autonome-lkw-cmr-schadensregulierung-speditionshaftung-hgb` — Autonome Lkw Cmr Schadensregulierung Speditionshaftung Hgb
- `cmr-haftung-ladungsschaden-frachtfuehrerhaftung` — Cmr Haftung Ladungsschaden Frachtfuehrerhaftung
- `cotif-fachanwalt-haager` — Cotif Fachanwalt Haager
- `hgb-kabotage-beweislast-kanzlei-red` — Hgb Kabotage Beweislast Kanzlei Red
- `lieferverzug-orientierung-mandat-triage` — Lieferverzug Orientierung Mandat Triage
- `marktzugang-sonderfall-montrealer-spezial-pruefen` — Marktzugang Sonderfall Montrealer Prüfen
- `regeln-interessen-schnittstelle-spedition` — Regeln Interessen Schnittstelle Spedition
- `reklamationsschreiben-cmr-schriftsatzkern-substantiierung-adsp` — Reklamationsschreiben Cmr Schriftsatzkern Substantiierung Adsp
- `speditionsrecht-tio-schiedsgericht-frachtvertrag` — Speditionsrecht Tio Schiedsgericht Frachtvertrag
- `trans-cmr-frachtbrief-hgb-spedition-kabotage-marktzugang` — Trans Cmr Frachtbrief Hgb Spedition Kabotage Marktzugang
- `trans-multimodaler-transr-cmr-transr-multimodaler` — Trans Multimodaler Transr Cmr Transr Multimodaler
- `trans-transport-visby` — Trans Transport Visby
- `transr-einfuehrung-rechtsquellen` — Transr Einfuehrung Rechtsquellen

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Transport- und Speditionsrecht typisch: Frachtbrief, CMR-Frachtbrief, Schadensanzeige, Beschädigungs-Beleg.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (CMR Klage 1 Jahr / 3 Jahre Vorsatz, Schadensanzeige sofort/7 Tage).
- **Beweiswert einordnen.** Lichtbilder Schaden, Übergabeprotokoll, Lieferschein jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Absender.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
