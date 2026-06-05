---
name: einstieg-routing
description: "Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Einstieg und Routing

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Verkehrsowi Verteidiger** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `alkohol-drogen-beweisverwertung-standardisiert-verkehrsowi` — Alkohol Drogen Beweisverwertung Standardisiert Verkehrsowi
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `amtsgericht-drogen-interessen-einspruch` — Amtsgericht Drogen Interessen Einspruch
- `anhoerung-verkehrsowi-einspruch-messverfahren-geschwindigkeit` — Anhoerung Verkehrsowi Einspruch Messverfahren Geschwindigkeit
- `fahrverbot-geschwindigkeit-handy` — Fahrverbot Geschwindigkeit Handy
- `hauptverhandlung-sonderfall-messakte-messung-fahrverbot` — Hauptverhandlung Sonderfall Messakte Messung Fahrverbot
- `punkte-rotlicht-verkehrsowi` — Punkte Rotlicht Verkehrsowi
- `simulation-training-verjaehrung-zustellung-zeugen-polizei` — Simulation Training Verjaehrung Zustellung Zeugen Polizei
- `verkehrsowi-haertefall-fahrverbot-hauptverhandlung-amtsgericht` — Verkehrsowi Haertefall Fahrverbot Hauptverhandlung Amtsgericht
- `verkehrsowi-punkte-fahrverbot-rechtsbeschwerde-rotlicht-abstand` — Verkehrsowi Punkte Fahrverbot Rechtsbeschwerde Rotlicht Abstand
- `verteidiger-beweislast-verkehrsowi-aktenanlage-akteneinsicht` — Verteidiger Beweislast Verkehrsowi Aktenanlage Akteneinsicht
- `vowi-akteneinsicht` — Vowi Akteneinsicht
- `vowi-bussgeldbescheid-verkehrsowi-quality-gate` — Vowi Bussgeldbescheid Verkehrsowi Quality Gate
- `vowi-handyverstoss-akteneinsicht-alkohol` — Vowi Handyverstoss Akteneinsicht Alkohol

## Arbeitsweg

- **Rolle und Ziel klären.** Wer fragt aus welcher Position (Betroffener, Bußgeldbehörde, AG) und welcher Output wird gebraucht?
- **Fristen zuerst.** Einspruch 2 Wochen § 67 OWiG; Verjährung 3 Mon. Fahrlässigkeit.
- **Normenanker.** OWiG, StVO, StVG, BKatV. Tragende Norm vor Detail prüfen.
- **Zuständigkeit.** Bußgeldbehörde / Amtsgericht — Verfahrens- und Verwaltungsweg trennen.
- **Eine Rückfrage maximal.** Nur fragen, was die nächste Weiche entscheidet.

## Output

Triage-Notiz mit Frist, Norm, Zuständigkeit, Anschluss-Skill-Vorschlag und konkret nächstem Schritt. Bei Verkehrs-OWi-Verteidigung typische Eskalationsstufen: Einspruch, Akteneinsicht-Antrag, Sachverständigen-Antrag Messung.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
