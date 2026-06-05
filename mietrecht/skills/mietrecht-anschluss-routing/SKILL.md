---
name: mietrecht-anschluss-routing
description: "Anschluss-Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Anschluss-Routing

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

- **Engpass zuerst.** Bei Mietrecht (Wohnraum/Gewerbe) typischer Engpass: § 573c BGB Kündigung 3 Mon. oder Mietvertrag.
- **Skill-Auswahl** nach Sachverhalt, Rolle (Mieter, Vermieter), Frist und gewünschtem Output.
- **Nicht parallel aufblasen.** Erst den Engpass lösen, dann den nächsten Pfad öffnen.
- **Grenzfall.** Zwei Skills kurz gegenüberstellen mit Vor-/Nachteil und einer Empfehlung.
- **Akten-Spur.** Router-Entscheidung dokumentieren mit Begründung und Verworfenem.

## Output

Routing-Entscheidung mit Anschluss-Skill, Reihenfolge, Abbruchkriterien und nächster Aktion innerhalb von Mietrecht (Wohnraum/Gewerbe).

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
