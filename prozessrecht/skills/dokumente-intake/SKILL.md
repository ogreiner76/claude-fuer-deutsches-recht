---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Prozessrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `amtlicher-zpo-proz-bauleiter-eilverfahren` — Amtlicher Zpo Proz Bauleiter Eilverfahren
- `anspruchstabelle` — Anspruchstabelle
- `anspruchstabelle-gegenseite-interessen-mahnbescheid` — Anspruchstabelle Gegenseite Interessen Mahnbescheid
- `beweissicherung-chronologie-einstweilige-verfuegung` — Beweissicherung Chronologie Einstweilige Verfuegung
- `gegenseite-status-mahnbescheid-mahnschreiben-aufnahme` — Gegenseite Status Mahnbescheid Mahnschreiben Aufnahme
- `mahnschreiben-entwurf-anwaltsgeheimnis` — Mahnschreiben Entwurf Anwaltsgeheimnis
- `mahnschreiben-erhalten-aktualisierung-aufnahme` — Mahnschreiben Erhalten Aktualisierung Aufnahme
- `mandat-briefing-mandat-schliessen-portfolio-status` — Mandat Briefing Mandat Schliessen Portfolio Status
- `mandat-mandate-prozessrecht` — Mandat Mandate Prozessrecht
- `proz-beweismittel-leitfaden-mediationsklage-guete` — Proz Beweismittel Leitfaden Mediationsklage Guete
- `prozessrecht-kaltstart-interview` — Prozessrecht Kaltstart Interview
- `prozessrecht-mandat-arbeitsbereich-abschnitt` — Prozessrecht Mandat Arbeitsbereich Abschnitt
- `prozessrechtliche-schriftsaetze-status` — Prozessrechtliche Schriftsaetze Status

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Prozessrecht (ZPO/VwGO/StPO/SGG) typisch: Klageschrift, Klageerwiderung, Schriftsätze, Urteil.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Berufung 1 Mon. § 517 ZPO, Revision 1 Mon.).
- **Beweiswert einordnen.** Urkunden, Zeugen, SV-Gutachten jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Mandant.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
