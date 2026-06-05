---
name: tabellenreview-3d-unterlagen-luecken
description: "Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

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

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Tabellenreview (Excel/CSV) oft fehlend: Excel-/CSV-Datei, Formelreview, Datenqualitätsbericht.
- **Pro Lücke.** Beweisthema, Beweismittel (Quelldaten, Abstimmungen), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: erste Frist.
- **Beschaffung extern.** Finanzamt (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Tabellenreview (Excel/CSV) typischerweise Excel-/CSV-Datei, Formelreview zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
