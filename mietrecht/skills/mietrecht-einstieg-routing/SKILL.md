---
name: mietrecht-einstieg-routing
description: "Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Einstieg und Routing

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Mietrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `amtlichen-amtsgericht-sonderfall-ausschliesslich` — Amtlichen Amtsgericht Sonderfall Ausschliesslich
- `bundesland-datenerhebung-grossstadt-mietspiegel` — Bundesland Datenerhebung Grossstadt Mietspiegel
- `klageentwurf-amtsgericht-miet-gewerbemiete-mietvertrag-bauleiter` — Klageentwurf Amtsgericht Miet Gewerbemiete Mietvertrag Bauleiter
- `lage-ausstattung-mahnung-zahlungsverzug-mandat-triage` — Lage Ausstattung Mahnung Zahlungsverzug Mandat Triage
- `miet-kuendigungsschutz-miet-mietminderung-mieteranfragen` — Miet Kuendigungsschutz Miet Mietminderung Mieteranfragen
- `mieter-mieteranfragen-mandantenentscheidung-mieterhoehungs` — Mieter Mieteranfragen Mandantenentscheidung Mieterhoehungs
- `mieterhoehung-widersprechen-mieterhoehungsverlangen-erstellen` — Mieterhoehung Widersprechen Mieterhoehungsverlangen Erstellen
- `mietpreisueberhoehung-wistrg-mietsenkungsverlangen-mietspiegel` — Mietpreisueberhoehung Wistrg Mietsenkungsverlangen Mietspiegel
- `mietrecht-mietsenkungsverlangen-international-mietspiegel` — Mietrecht Mietsenkungsverlangen International Mietspiegel
- `mr-betriebskostenabrechnung-mr-kuendigungsschutz-mr` — Mr Betriebskostenabrechnung Mr Kuendigungsschutz Mr
- `mr-einfuehrung-klageentwurf-beweislast-eigenbedarfskuendigung` — Mr Einfuehrung Klageentwurf Beweislast Eigenbedarfskuendigung
- `nebenkostenabrechnung-erstellen-faktenbank` — Nebenkostenabrechnung Erstellen Faktenbank
- `nebenkostenpruefung-prozessstrategie-mieterhoehung-quellen` — Nebenkostenpruefung Prozessstrategie Mieterhoehung Quellen

## Arbeitsweg

- **Rolle und Ziel klären.** Wer fragt aus welcher Position (Mieter, Vermieter, Hausverwaltung) und welcher Output wird gebraucht?
- **Fristen zuerst.** § 573c BGB Kündigung 3 Mon.; § 574 BGB Widerspruch 2 Mon. vor Beendigung.
- **Normenanker.** BGB §§ 535, 536, 543, 558, 573 ff., WEG, BetrKV. Tragende Norm vor Detail prüfen.
- **Zuständigkeit.** Amtsgericht Belegenheit / Mieterverein — Verfahrens- und Verwaltungsweg trennen.
- **Eine Rückfrage maximal.** Nur fragen, was die nächste Weiche entscheidet.

## Output

Triage-Notiz mit Frist, Norm, Zuständigkeit, Anschluss-Skill-Vorschlag und konkret nächstem Schritt. Bei Mietrecht (Wohnraum/Gewerbe) typische Eskalationsstufen: Kündigungsschreiben, Mietminderungserklärung, Klage AG.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
