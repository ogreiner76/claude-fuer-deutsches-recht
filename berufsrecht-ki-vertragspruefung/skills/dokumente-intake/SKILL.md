---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

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

- **Sortieren nach Dokumenttyp.** Bei Berufsrechts-KI bei Vertragsprüfung typisch: AVV-Vertrag, Mandatsvertrag, Datenschutzfolgeabschätzung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Rechtzeitige Mandatsannahme, Schriftform-Erfordernisse).
- **Beweiswert einordnen.** Tool-Dokumentation, Auftragsverarbeitungs-Verzeichnis jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Anwalt/Kanzlei.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
