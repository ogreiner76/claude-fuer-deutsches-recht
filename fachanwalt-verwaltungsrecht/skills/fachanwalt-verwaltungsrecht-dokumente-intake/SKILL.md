---
name: fachanwalt-verwaltungsrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Verwaltungsrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `anfechtungs-eilrechtsschutz-abs-eilrechtsschutz` — Anfechtungs Eilrechtsschutz Abs Eilrechtsschutz
- `einstweilige-fachanwalt-kanzlei` — Einstweilige Fachanwalt Kanzlei
- `erstgespraech-mandatsannahme-fa-vwgo-anfechtungsklage` — Erstgespraech Mandatsannahme Fa Vwgo Anfechtungsklage
- `fachanwalt-verwaltungsrecht-drittanfechtung-einstweiliger` — Fachanwalt Verwaltungsrecht Drittanfechtung Einstweiliger
- `fachanwalt-verwaltungsrecht-verwaltungsakt-rechtsbehelf-vwgo` — Fachanwalt Verwaltungsrecht Verwaltungsakt Rechtsbehelf Vwgo
- `normenkontrolle-ordnungsrecht-interessen-orientierung-sonderfall` — Normenkontrolle Ordnungsrecht Interessen Orientierung Sonderfall
- `normenkontrolle-vwgo-orientierung-vwgo-behoerde` — Normenkontrolle Vwgo Orientierung Vwgo Behörde
- `polizei-polizei-filmen-rechtsschutz-beweislast` — Polizei Polizei Filmen Rechtsschutz Beweislast
- `schnittstelle-verpflichtungsklage-verwaltungsrecht` — Schnittstelle Verpflichtungsklage Verwaltungsrecht
- `verwr-folgenbeseitigung-planfeststellung-grossvorhaben` — Verwr Folgenbeseitigung Planfeststellung Grossvorhaben
- `verwr-verwaltungsverfahren-eilantrag-abs-energietrassen` — Verwr Verwaltungsverfahren Eilantrag Abs Energietrassen
- `vorlaeufiger-vwvfg-vergleichsverhandlung-strategie` — Vorlaeufiger Vwvfg Vergleichsverhandlung Strategie
- `vwr-eilrechtsschutz-widerspruch-klage` — Vwr Eilrechtsschutz Widerspruch Klage

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Verwaltungsrecht typisch: Verwaltungsakt, Widerspruchsbescheid, Klageschrift, Anhörungsprotokoll.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 74 VwGO Klagefrist 1 Mon., § 80 V VwGO eA).
- **Beweiswert einordnen.** Verwaltungsakte, Anhörung, Sachverständigengutachten jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Bürger/Antragsteller.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
