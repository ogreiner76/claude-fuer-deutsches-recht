---
name: verkehrsowi-verteidiger-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Verkehrsowi Verteidiger** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `alkohol-drogen-beweisverwertung-standardisiert-verkehrsowi` — Alkohol Drogen Beweisverwertung Standardisiert Verkehrsowi
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `amtsgericht-drogen-interessen-einspruch` — Amtsgericht Drogen Interessen Einspruch
- `anhoerung-verkehrsowi-einspruch-messverfahren-geschwindigkeit` — Anhoerung Verkehrsowi Einspruch Messverfahren Geschwindigkeit
- `fahrverbot-geschwindigkeit-handy` — Fahrverbot Geschwindigkeit Handy
- `hauptverhandlung-sonderfall-messakte-messung-fahrverbot` — Hauptverhandlung Sonderfall Messakte Messung Fahrverbot
- `punkte-rotlicht-verkehrsowi` — Punkte Rotlicht Verkehrsowi
- `simulation-training-verjaehrung-zustellung-zeugen-polizei` — Simulation Training Verjaehrung Zustellung Zeugen Polizei
- `verkehrsowi-haertefall-fahrverbot-hauptverhandlung-amtsgericht` — Verkehrsowi Haertefall Fahrverbot Hauptverhandlung Amtsgericht
- `verkehrsowi-punkte-fahrverbot-rechtsbeschwerde-rotlicht-abstand` — Verkehrsowi Punkte Fahrverbot Rechtsbeschwerde Rotlicht Abstand
- `verteidiger-beweislast-verkehrsowi-aktenanlage-akteneinsicht` — Verteidiger Beweislast Verkehrsowi Aktenanlage Akteneinsicht
- `vowi-akteneinsicht` — Vowi Akteneinsicht
- `vowi-bussgeldbescheid-verkehrsowi-quality-gate` — Vowi Bussgeldbescheid Verkehrsowi Quality Gate
- `vowi-handyverstoss-akteneinsicht-alkohol` — Vowi Handyverstoss Akteneinsicht Alkohol

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Verkehrs-OWi-Verteidigung typisch: Bußgeldbescheid, Anhörungsbogen, Messprotokoll, Eichschein.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Einspruch 2 Wochen § 67 OWiG, Verjährung 3 Mon. Fahrlässigkeit).
- **Beweiswert einordnen.** Messprotokoll, Rohmessdaten, Fahrerfeststellung jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Betroffener.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
