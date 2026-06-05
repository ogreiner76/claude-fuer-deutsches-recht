---
name: betreuungsrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Betreuungsrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-anschluss-router-workflow-chronologie` — Allgemein Anschluss Router Chronologie
- `aufgabenkreise-festlegen` — Aufgabenkreise Festlegen
- `bericht-betreuer-betreuerpflichten` — Bericht Betreuer Betreuerpflichten
- `betreuer-als-erbe` — Betreuer Als Erbe
- `betreuer-als-registrierung-betreuung-anwaltskosten` — Betreuer Als Registrierung Betreuung Anwaltskosten
- `betreuer-registrierung` — Betreuer Registrierung
- `betreuerpflichten-genehmigung-betreuung-interessen` — Betreuerpflichten Genehmigung Betreuung Interessen
- `betreuung-anwaltskosten-rvg` — Betreuung Anwaltskosten Rvg
- `betreuung-bei-demenz` — Betreuung Bei Demenz
- `betreuung-demenz-erbe-werden-erwachsene-kinder` — Betreuung Demenz Erbe Werden Erwachsene Kinder
- `betreuung-erbe-werden` — Betreuung Erbe Werden
- `betreuung-fuer-erwachsene-kinder` — Betreuung Für Erwachsene Kinder
- `betreuung-grenzueberschreitend` — Betreuung Grenzueberschreitend
- `betreuung-grenzueberschreitend-betreuungsantrag-erstellen` — Betreuung Grenzueberschreitend Betreuungsantrag Erstellen

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Betreuungsrecht typisch: Betreuungsbeschluss, Sachverständigengutachten, Vorsorgevollmacht, Patientenverfügung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Beschwerde 1 Monat § 63 FamFG, Genehmigung gerichtlich vor Maßnahme).
- **Beweiswert einordnen.** Ärztliches Gutachten, Persönliche Anhörung Betroffener, Sozialbericht jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Betroffener.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
