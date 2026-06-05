---
name: fluggastrechte-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fluggastrechte** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `abtretung-an-fluggastportal-spezial` — Abtretung An Fluggastportal Spezial
- `airline-bonitaet-und-vollstreckung` — Airline Bonitaet Und Vollstreckung
- `airline-standardausreden-annullierung-verspaetung-anschlussflug` — Airline Standardausreden Annullierung Verspaetung Anschlussflug
- `airline-standardausreden-pruefen` — Airline Standardausreden Prüfen
- `allgemein-anschluss-router-workflow-chronologie` — Allgemein Anschluss Router Chronologie
- `annullierung-oder-verspaetung-einordnen` — Annullierung Oder Verspaetung Einordnen
- `anschlussflug-und-reiseplan` — Anschlussflug Und Reiseplan
- `ausnahmen-aussergewoehnliche-aussergewoehnliche-umstaende` — Ausnahmen Aussergewoehnliche Aussergewoehnliche Umstaende
- `ausnahmen-aussergewoehnliche-umstaende-pruefen` — Ausnahmen Aussergewoehnliche Umstaende Prüfen
- `aussergewoehnliche-distanz-interessen-erfassen` — Aussergewoehnliche Distanz Interessen Erfassen
- `aussergewoehnliche-umstaende-strikt` — Aussergewoehnliche Umstaende Strikt
- `distanz-und-ausgleich-berechnen` — Distanz Und Ausgleich Berechnen
- `flug-anschlussflug-codeshare-anspruch-uebersicht` — Flug Anschlussflug Codeshare Anspruch Uebersicht
- `flug-anschlussflug-codeshare-spezial` — Flug Anschlussflug Codeshare Spezial

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fluggastrechte VO 261/2004 typisch: Buchungsbestätigung, Boardingpass, Verspätungsbestätigung, Fluggesellschafts-Korrespondenz.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Verjährung 3 Jahre § 195 BGB, Reklamation umgehend).
- **Beweiswert einordnen.** Boardingpass, Verspätungsdokumentation Flightradar/LBA, Annullierungsemails jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Fluggast.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
