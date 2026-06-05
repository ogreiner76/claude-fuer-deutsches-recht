---
name: dfg-foerderantrag-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Dfg Foerderantrag** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `anfaenger-antraege-dfg` — Anfaenger Antraege Dfg
- `dfg-bis-200k-begutachtung-light` — Dfg Bis 200k Begutachtung Light
- `dfg-eigenanteil-und-grundausstattung` — Dfg Eigenanteil Und Grundausstattung
- `dfg-eigene-vorarbeiten-darstellen` — Dfg Eigene Vorarbeiten Darstellen
- `dfg-erstantragsteller-besondere-checks` — Dfg Erstantragsteller Besondere Checks
- `dfg-finanzplan-module-personal-geraete` — Dfg Finanzplan Module Personal Geraete
- `dfg-foerderstrategie-schnell-oder-gross` — Dfg Foerderstrategie Schnell Oder Gross
- `dfg-grossgeraete-und-cluster-antrag` — Dfg Grossgeraete Und Cluster Antrag
- `dfg-grundsystem-foerderlinien` — Dfg Grundsystem Foerderlinien
- `dfg-internationale-kooperation-aufbau` — Dfg Internationale Kooperation Aufbau
- `dfg-ki-ethik-forschungsdaten` — Dfg Ki Ethik Forschungsdaten
- `dfg-kollegen-review-organisieren` — Dfg Kollegen Review Organisieren
- `dfg-koselleck-500k-125m` — Dfg Koselleck 500k 125m

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei DFG-Förderantrag typisch: Projektbeschreibung, Finanzierungsplan, Lebenslauf, Publikationsliste.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Antragsfrist Ausschreibungstermin, Berichtspflichten jährlich).
- **Beweiswert einordnen.** Publikationsverzeichnis, Vorarbeiten, Kooperationsbestätigungen jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Antragsteller.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
