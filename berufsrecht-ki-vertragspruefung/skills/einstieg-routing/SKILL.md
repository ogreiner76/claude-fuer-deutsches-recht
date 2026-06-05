---
name: einstieg-routing
description: "Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Einstieg und Routing

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Berufsrecht Ki Vertragspruefung** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `ai-act-rollen-kanzlei-provider-deployer-api` — Ai Act Rollen Kanzlei Provider Deployer Api
- `allgemein-brki-rollout-workflow-chronologie` — Allgemein Brki Rollout Chronologie
- `anbietern-belehrung-sonderfall-edge` — Anbietern Belehrung Sonderfall Edge
- `art-50-ki-vo-schriftsatz-marketing-chatbot` — Art 50 Ki Vo Schriftsatz Marketing Chatbot
- `avv-grenzpruefung-brki-anbieter-brki-eu` — Avv Grenzpruefung Brki Anbieter Brki Eu
- `avv-grenzpruefung-datenschutz` — Avv Grenzpruefung Datenschutz
- `berufsrecht-ki-vertragspruefung-kaltstart-interview` — Berufsrecht Ki Vertragspruefung Kaltstart Interview
- `berufsrechtliche-bnoto-interessen-brao` — Berufsrechtliche Bnoto Interessen Brao
- `brki-anbieter-due-diligence` — Brki Anbieter Due Diligence
- `brki-eu-us-dpf-transferpruefung` — Brki Eu Us Dpf Transferpruefung
- `brki-rag-bro-grundlagen-cloud-act` — Brki Rag Bro Grundlagen Cloud Act
- `brki-rag-vertraulichkeit-spezial` — Brki Rag Vertraulichkeit Spezial
- `brki-rollout-trainings-workflow` — Brki Rollout Trainings Workflow
- `bro-grundlagen-ki-einsatz` — Bro Grundlagen Ki Einsatz

## Arbeitsweg

- **Rolle und Ziel klären.** Wer fragt aus welcher Position (Anwalt/Kanzlei, Mandant, KI-Anbieter) und welcher Output wird gebraucht?
- **Fristen zuerst.** Rechtzeitige Mandatsannahme; Schriftform-Erfordernisse.
- **Normenanker.** § 43a BRAO, § 50 BRAO Aktenführung, DSGVO Art. 28 AVV. Tragende Norm vor Detail prüfen.
- **Zuständigkeit.** RAK / Datenschutzaufsicht — Verfahrens- und Verwaltungsweg trennen.
- **Eine Rückfrage maximal.** Nur fragen, was die nächste Weiche entscheidet.

## Output

Triage-Notiz mit Frist, Norm, Zuständigkeit, Anschluss-Skill-Vorschlag und konkret nächstem Schritt. Bei Berufsrechts-KI bei Vertragsprüfung typische Eskalationsstufen: Mandanten-Hinweisblatt, AVV-Muster, Risikoampel KI-Einsatz.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
