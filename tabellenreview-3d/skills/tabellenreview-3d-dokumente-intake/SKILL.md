---
name: tabellenreview-3d-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Tabellenreview 3d** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `aggregation-spaltenprompts-definieren-arbeitsblatt` — Aggregation Spaltenprompts Definieren Arbeitsblatt
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `arbeitsblatt-perspektiven-definieren` — Arbeitsblatt Perspektiven Definieren
- `audit-trail-protokoll` — Audit Trail Protokoll
- `belegkette-rueckverfolgung` — Belegkette Rueckverfolgung
- `belegkette-rueckverfolgung-caching-rerun-dokumentstapel` — Belegkette Rueckverfolgung Caching Rerun Dokumentstapel
- `caching-und-teil-rerun` — Caching Und Teil Rerun
- `datenpunkt-dokument-excel-beweislast` — Datenpunkt Dokument Excel Beweislast
- `dokumentstapel-aufnehmen` — Dokumentstapel Aufnehmen
- `excel-multi-kreuzblatt-konsistenzpruefung-pdf-bericht` — Excel Multi Kreuzblatt Konsistenzpruefung Pdf Bericht
- `excel-multi-sheet-export` — Excel Multi Sheet Export
- `gestapelt-immobilien-massenpruefung-interessen` — Gestapelt Immobilien Massenpruefung Interessen
- `kreuzblatt-konsistenzpruefung` — Kreuzblatt Konsistenzpruefung
- `mehrblatt-sonderfall-onboarding-perspektiven` — Mehrblatt Sonderfall Onboarding Perspektiven

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Tabellenreview (Excel/CSV) typisch: Excel-/CSV-Datei, Formelreview, Datenqualitätsbericht.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (materielle und prozessuale Fristen).
- **Beweiswert einordnen.** Quelldaten, Abstimmungen jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Datenverantwortlicher.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
