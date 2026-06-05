---
name: prozessrecht-unterlagen-luecken
description: "Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

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

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Prozessrecht (ZPO/VwGO/StPO/SGG) oft fehlend: Klageschrift, Klageerwiderung, Schriftsätze.
- **Pro Lücke.** Beweisthema, Beweismittel (Urkunden, Zeugen), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: Berufung 1 Mon. § 517 ZPO.
- **Beschaffung extern.** Erste Instanz / Rechtsmittelgerichte (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Prozessrecht (ZPO/VwGO/StPO/SGG) typischerweise Klageschrift, Klageerwiderung zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
