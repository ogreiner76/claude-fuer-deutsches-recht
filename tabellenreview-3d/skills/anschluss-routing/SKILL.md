---
name: anschluss-routing
description: "Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Anschluss-Routing

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

- **Engpass zuerst.** Bei Tabellenreview (Excel/CSV) typischer Engpass: erste Frist oder Excel-/CSV-Datei.
- **Skill-Auswahl** nach Sachverhalt, Rolle (Datenverantwortlicher, Prüfer), Frist und gewünschtem Output.
- **Nicht parallel aufblasen.** Erst den Engpass lösen, dann den nächsten Pfad öffnen.
- **Grenzfall.** Zwei Skills kurz gegenüberstellen mit Vor-/Nachteil und einer Empfehlung.
- **Akten-Spur.** Router-Entscheidung dokumentieren mit Begründung und Verworfenem.

## Output

Routing-Entscheidung mit Anschluss-Skill, Reihenfolge, Abbruchkriterien und nächster Aktion innerhalb von Tabellenreview (Excel/CSV).

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
