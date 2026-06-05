---
name: einstieg-routing
description: "Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Einstieg und Routing

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Kanzlei Allgemein** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `aktenbestand-pflege-bea-versand` — Aktenbestand Pflege Bea Versand
- `buchhaltung-konten-kanzlei-erechnung` — Buchhaltung Konten Kanzlei Erechnung
- `freundlicher-copilot-kanzlei-handelsregisterabruf` — Freundlicher Copilot Kanzlei Handelsregisterabruf
- `geburtstage-feiertage-abwesenheiten-urlaub` — Geburtstage Feiertage Abwesenheiten Urlaub
- `hr-personal-kanzlei-intake` — Hr Personal Kanzlei Intake
- `integrationen-simulation-kanzlei-kanzleikalender` — Integrationen Simulation Kanzlei Kanzleikalender
- `kanzlei-allgemein-kaltstart` — Kanzlei Allgemein Kaltstart
- `kanzlei-allgemein-output-versand` — Kanzlei Allgemein Output Versand
- `kanzlei-automationen-bea-journal` — Kanzlei Automationen Bea Journal
- `kanzlei-cowork-kaltstart-interview` — Kanzlei Cowork Kaltstart Interview
- `kanzlei-kanzlei-aktenzeichen` — Kanzlei Kanzlei Aktenzeichen
- `kanzlei-mandatsvereinbarung-kanzlei-postlauf` — Kanzlei Mandatsvereinbarung Kanzlei Postlauf
- `kanzlei-monitor-kanzlei-vertragsentwurf` — Kanzlei Monitor Kanzlei Vertragsentwurf
- `kanzlei-rechtsprechungsrecherche-fristenbuch-fuehren` — Kanzlei Rechtsprechungsrecherche Fristenbuch Fuehren

## Arbeitsweg

- **Rolle und Ziel klären.** Wer fragt aus welcher Position (Anwalt, Mandant, Mitarbeitende) und welcher Output wird gebraucht?
- **Fristen zuerst.** Mandatsannahme; RVG-Vergütung.
- **Normenanker.** BRAO, BORA, FAO, RVG, DSGVO. Tragende Norm vor Detail prüfen.
- **Zuständigkeit.** RAK / Anwaltsgericht — Verfahrens- und Verwaltungsweg trennen.
- **Eine Rückfrage maximal.** Nur fragen, was die nächste Weiche entscheidet.

## Output

Triage-Notiz mit Frist, Norm, Zuständigkeit, Anschluss-Skill-Vorschlag und konkret nächstem Schritt. Bei Kanzlei-Allgemein typische Eskalationsstufen: Mandatsvertrag, Honorarvereinbarung, Mandantenrundschreiben.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
