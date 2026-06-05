---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Jurastudium** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `ag-vorbereitung-examens-prognose-examensvorbereitung-fragen` — Ag Vorbereitung Examens Prognose Examensvorbereitung Fragen
- `allgemein-anschluss-router-workflow-chronologie` — Allgemein Anschluss Router Chronologie
- `fall-zusammenfassung-gliederungs-baukasten-gutachten-uebung` — Fall Zusammenfassung Gliederungs Baukasten Gutachten Uebung
- `jurastudium-juristisches-schreiben-jus-klausurtraining` — Jurastudium Juristisches Schreiben Jus Klausurtraining
- `jurastudium-kaltstart-interview` — Jurastudium Kaltstart Interview
- `jurastudium-klausurkorrektur-lernplanung-red` — Jurastudium Klausurkorrektur Lernplanung Red
- `jus-referendariat-jus-staatsexamen-jus-studienplan` — Jus Referendariat Jus Staatsexamen Jus Studienplan
- `karteikarten-lernplan-lernsitzung` — Karteikarten Lernplan Lernsitzung
- `lernstrategien-livecheck-sonderfall-loesungsschemata-interessen` — Lernstrategien Livecheck Sonderfall Loesungsschemata Interessen
- `lernstrategien-loesungsschemata-methodenlehre-grundlagen` — Lernstrategien Loesungsschemata Methodenlehre Grundlagen
- `methodenlehre-oeffentliches-methodenlehre-strafrecht` — Methodenlehre Oeffentliches Methodenlehre Strafrecht
- `methodenlehre-rechtsgeschichte-referendariat` — Methodenlehre Rechtsgeschichte Referendariat
- `pruefungsgespraech-ag-rechtsgeschichte-gutachtenstil` — Pruefungsgespraech Ag Rechtsgeschichte Gutachtenstil
- `strafrecht-studium-subsumtionslehre` — Strafrecht Studium Subsumtionslehre

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Jurastudium (Klausur, AG, Examen) typisch: Klausuren, Hausarbeiten, Karteikarten, Skripte.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Klausurzeit, Hausarbeitsfristen).
- **Beweiswert einordnen.** Urkunden, Zeugen, Sachverständige jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Studierender.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
