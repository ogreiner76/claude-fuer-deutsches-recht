---
name: einfache-leichte-sprache-jura-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Einfache Leichte Sprache Jura** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `leichte-sprache-jura-ls-bescheid-chronologie` — Allgemein Ls Bescheid Chronologie
- `einfache-elsj-bescheidmodus-elsj` — Einfache Elsj Bescheidmodus Elsj
- `elsj-aufenthaltsrecht-mandant` — Elsj Aufenthaltsrecht Mandant
- `elsj-aufenthaltsrecht-mandant-betreuung-vormundschaft-einfache` — Elsj Aufenthaltsrecht Mandant Betreuung Vormundschaft Einfache
- `elsj-bescheidmodus` — Elsj Bescheidmodus
- `elsj-betreuung-vormundschaft` — Elsj Betreuung Vormundschaft
- `elsj-einfache-sprache` — Elsj Einfache Sprache
- `elsj-familienrecht-erstgespraech` — Elsj Familienrecht Erstgespraech
- `elsj-familienrecht-erstgespraech-juristische-sicherung` — Elsj Familienrecht Erstgespraech Juristische Sicherung
- `elsj-juristische-sicherung` — Elsj Juristische Sicherung
- `elsj-kommandocenter` — Elsj Kommandocenter
- `elsj-kommunikation-mandant` — Elsj Kommunikation Mandant
- `elsj-leichte-sprache` — Elsj Leichte Sprache
- `elsj-leichte-sprache-mietrecht-kuendigungserklaerung` — Elsj Leichte Sprache Mietrecht Kuendigungserklaerung

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Einfache/Leichte Sprache Jura typisch: Originalbescheid, Vereinfachte Fassung, Lese-Test.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (materielle und prozessuale Fristen).
- **Beweiswert einordnen.** Verständlichkeits-Test, Lese-Probanden-Feedback jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Adressat mit Lese-/Lernbeeinträchtigung.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
