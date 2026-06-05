---
name: berufsrecht-ki-vertragspruefung-unterlagen-luecken
description: "Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Berufsrecht Ki Vertragspruefung** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `ai-act-rollen-kanzlei-provider-deployer-api` — Ai Act Rollen Kanzlei Provider Deployer Api
- `br-ki-vertragspruefung-brki-rollout-chronologie` — Allgemein Brki Rollout Chronologie
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

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Berufsrechts-KI bei Vertragsprüfung oft fehlend: AVV-Vertrag, Mandatsvertrag, Datenschutzfolgeabschätzung.
- **Pro Lücke.** Beweisthema, Beweismittel (Tool-Dokumentation, Auftragsverarbeitungs-Verzeichnis), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: Rechtzeitige Mandatsannahme.
- **Beschaffung extern.** RAK (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Berufsrechts-KI bei Vertragsprüfung typischerweise AVV-Vertrag, Mandatsvertrag zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
