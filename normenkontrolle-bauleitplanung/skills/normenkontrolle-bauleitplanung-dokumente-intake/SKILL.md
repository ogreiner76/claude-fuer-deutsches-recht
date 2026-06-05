---
name: normenkontrolle-bauleitplanung-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Normenkontrolle Bauleitplanung** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `abwaegungsgebot-1-abs-7-baugb` — Abwaegungsgebot 1 Abs 7 Baugb
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `normenkontrolle-satzungsnormenkontrolle-47-vwgo` — Allgemeine Satzungsnormenkontrolle 47 Vwgo
- `allgemeine-satzungsnormenkontrolle-anpassungsgebot` — Allgemeine Satzungsnormenkontrolle Anpassungsgebot
- `anfechtung-antragsbefugnis-red-antragstellervertretung` — Anfechtung Antragsbefugnis Red Antragstellervertretung
- `anpassungsgebot-flaechennutzungsplan` — Anpassungsgebot Flaechennutzungsplan
- `antragsbefugnis-eigentuemer-nachbar` — Antragsbefugnis Eigentuemer Nachbar
- `artenschutz-naturschutz-aufstellungsbeschluss-bekanntmachung` — Artenschutz Naturschutz Aufstellungsbeschluss Bekanntmachung
- `artenschutz-naturschutz-planung` — Artenschutz Naturschutz Planung
- `aufstellungsbeschluss-bekanntmachung` — Aufstellungsbeschluss Bekanntmachung
- `aufstellungsbeschluss-mandantenentscheidung-bauleitplanung` — Aufstellungsbeschluss Mandantenentscheidung Bauleitplanung
- `bayvgh-bekanntmachung-beweislast-eilantrag-abs` — Bayvgh Bekanntmachung Beweislast Eilantrag Abs
- `bebauungsplaenen-kommunalabgaben-beitragssatzungen` — Bebauungsplaenen Kommunalabgaben Beitragssatzungen
- `benutzungssatzung-kommunale-einrichtung` — Benutzungssatzung Kommunale Einrichtung

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Normenkontrolle Bauleitplanung typisch: Bebauungsplan, Begründung, Abwägungsmaterial, Beteiligungs-Akten.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 47 II VwGO 1 Jahr ab Bekanntmachung).
- **Beweiswert einordnen.** Abwägungsfehler-Dokumentation, Bürgerbeteiligung Protokolle jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Antragsteller (Anwohner/Nachbargemeinde).

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
