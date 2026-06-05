---
name: einstieg-routing
description: "Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Einstieg und Routing

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Forderungsmanagement Klagewerkstatt** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `belegte-faellige-fmkw` — Belegte Faellige Fmkw
- `bgb-zpo-fmkw-saumselig-fmkw-titulierung` — Bgb Zpo Fmkw Saumselig Fmkw Titulierung
- `fmkw-mahnverfahren-bauleiter` — Fmkw Mahnverfahren Bauleiter
- `fmkw-saumselig-streitig-erfahrung-spezial` — Fmkw Saumselig Streitig Erfahrung Spezial
- `fmkw-titulierung-streckung-leitfaden` — Fmkw Titulierung Streckung Leitfaden
- `fmkw-verbraucherklage-cookies-rdg-spezial` — Fmkw Verbraucherklage Cookies Rdg Spezial
- `fmkw-verbraucherklage-forderung-anwaltshonorar-forderung` — Fmkw Verbraucherklage Forderung Anwaltshonorar Forderung
- `forderung-anwaltshonorar-rvg` — Forderung Anwaltshonorar Rvg
- `forderung-arzthonorar-goae` — Forderung Arzthonorar Goae
- `forderung-aus-werkvertrag-bgb-bau` — Forderung Aus Werkvertrag Bgb Bau
- `forderung-gegen-gesellschafter-13-gmbhg` — Forderung Gegen Gesellschafter 13 Gmbhg
- `forderung-gegen-gesellschafter-insolventen-schuldner-ausland` — Forderung Gegen Gesellschafter Insolventen Schuldner Ausland
- `forderung-gegen-insolventen-schuldner` — Forderung Gegen Insolventen Schuldner

## Arbeitsweg

- **Rolle und Ziel klären.** Wer fragt aus welcher Position (Gläubiger, Schuldner, Gerichtsvollzieher) und welcher Output wird gebraucht?
- **Fristen zuerst.** Mahnbescheid-Widerspruch 2 Wochen; Vollstreckungstitel.
- **Normenanker.** BGB §§ 280, 286, 288, ZPO §§ 688 ff. Mahnbescheid, RVG/RDG. Tragende Norm vor Detail prüfen.
- **Zuständigkeit.** AG Mahngericht (zentral) / Streit-AG/LG — Verfahrens- und Verwaltungsweg trennen.
- **Eine Rückfrage maximal.** Nur fragen, was die nächste Weiche entscheidet.

## Output

Triage-Notiz mit Frist, Norm, Zuständigkeit, Anschluss-Skill-Vorschlag und konkret nächstem Schritt. Bei Forderungsmanagement Klagewerkstatt typische Eskalationsstufen: Mahnung, Mahnbescheid online (zentrales MB-Gericht), Klage.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
