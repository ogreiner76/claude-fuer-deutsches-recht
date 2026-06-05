---
name: einstieg-routing
description: "Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Einstieg und Routing

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Weg Hausverwaltung** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `abrechnung-ist-plan-mieterschnittstelle` — Abrechnung Ist Plan Mieterschnittstelle
- `anwalt-amtsgericht-gewerbe-restaurant-grossakte` — Anwalt Amtsgericht Gewerbe Restaurant Grossakte
- `bad-umbau-barrierefreie-einladung-bauliche-veraenderung` — Bad Umbau Barrierefreie Einladung Bauliche Veraenderung
- `bad-umbau-bodengleiche-dusche-sondereigentum-gemeinschaft` — Bad Umbau Bodengleiche Dusche Sondereigentum Gemeinschaft
- `barrierefreie-einladung-protokoll-versammlung` — Barrierefreie Einladung Protokoll Versammlung
- `bauliche-veraenderung-aufzug-treppenlift-20-abs-2-weg` — Bauliche Veraenderung Aufzug Treppenlift 20 Abs 2 Weg
- `bauliche-veraenderungen-20-weg` — Bauliche Veraenderungen 20 Weg
- `bauliche-veraenderungen-beirat-controlling-beschlussanfechtung` — Bauliche Veraenderungen Beirat Controlling Beschlussanfechtung
- `beirat-controlling-verwalter` — Beirat Controlling Verwalter
- `beschlussanfechtung-risiko` — Beschlussanfechtung Risiko
- `beschlusssammlung-betriebskosten-interessen` — Beschlusssammlung Betriebskosten Interessen
- `beschlusssammlung-protokoll` — Beschlusssammlung Protokoll
- `beschlusssammlung-protokoll-beschlussvorlagen-erstellen` — Beschlusssammlung Protokoll Beschlussvorlagen Erstellen
- `beschlussvorlagen-erstellen` — Beschlussvorlagen Erstellen

## Arbeitsweg

- **Rolle und Ziel klären.** Wer fragt aus welcher Position (WEG-Eigentümer, Verwalter, Mehrheit/Minderheit) und welcher Output wird gebraucht?
- **Fristen zuerst.** § 44 WEG Beschlussanfechtung 1 Mon.; § 45 WEG Beschlussklage 2 Mon. Begründung.
- **Normenanker.** WEG §§ 18, 19, 20, 23-28, 44, 45, HeizkostenV, BetrKV. Tragende Norm vor Detail prüfen.
- **Zuständigkeit.** Amtsgericht Belegenheit — Verfahrens- und Verwaltungsweg trennen.
- **Eine Rückfrage maximal.** Nur fragen, was die nächste Weiche entscheidet.

## Output

Triage-Notiz mit Frist, Norm, Zuständigkeit, Anschluss-Skill-Vorschlag und konkret nächstem Schritt. Bei WEG/Hausverwaltung typische Eskalationsstufen: Beschlussklage, Beschlussersetzungsklage, Verwalter-Memo.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
