---
name: fachanwalt-sportrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Sportrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `cas-berufung-erstgespraech-mandatsannahme-doping-cas` — Cas Berufung Erstgespraech Mandatsannahme Doping Cas
- `dosb-fachanwalt-fifa` — Dosb Fachanwalt Fifa
- `fachanwalt-sportrecht-athletenvertrag-fristennotiz` — Fachanwalt Sportrecht Athletenvertrag Fristennotiz
- `fachanwalt-sportrecht-sportr-athletenvertrag-esports` — Fachanwalt Sportrecht Sportr Athletenvertrag Esports
- `gesellschaftsrecht-beweislast-mandat-nada-interessen` — Gesellschaftsrecht Beweislast Mandat Nada Interessen
- `mandat-triage-schriftsatzkern-substantiierung-code` — Mandat Triage Schriftsatzkern Substantiierung Code
- `orientierung-stadion-hausverbot-vereinsstrafrecht` — Orientierung Stadion Hausverbot Vereinsstrafrecht
- `persoenlichkeitsrechte-schnittstelle-mandantenentscheidung` — Persoenlichkeitsrechte Schnittstelle Mandantenentscheidung
- `sponsoring-sportr-sonderfall-sportrecht` — Sponsoring Sportr Sonderfall Sportrecht
- `sportr-arbeitsrecht-sport-einfuehrung-rechtsfelder` — Sportr Arbeitsrecht Sport Einfuehrung Rechtsfelder
- `sportr-stadionverbot-sportr-stadionverbot-verbandsstrafe` — Sportr Stadionverbot Sportr Stadionverbot Verbandsstrafe
- `uefa-wada-sportr-anti` — Uefa Wada Sportr Anti
- `verbandsrecht-sportr-doping-spielervertrag` — Verbandsrecht Sportr Doping Spielervertrag

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Sportrecht typisch: Spielerlizenz, Verbandssatzung, Transferregister, Doping-Probe-Protokoll.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Berufung CAS 21 Tage, Doping-Anhörung).
- **Beweiswert einordnen.** Spielprotokolle, Doping-Analyse Labor, Zeugenvernehmungen jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Sportler.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
