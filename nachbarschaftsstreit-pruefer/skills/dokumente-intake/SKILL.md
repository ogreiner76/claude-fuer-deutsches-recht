---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Nachbarschaftsstreit Prüfer** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-anschluss-router-workflow-chronologie` — Allgemein Anschluss Router Chronologie
- `anspruchslandkarte-bgb-aufforderungsschreiben-nachbar` — Anspruchslandkarte Bgb Aufforderungsschreiben Nachbar
- `aufforderung-beweise-red-grenzbaum` — Aufforderung Beweise Red Grenzbaum
- `drohender-einsturz-einfriedung-zaun-einstweilige-verfuegung` — Drohender Einsturz Einfriedung Zaun Einstweilige Verfuegung
- `fristennotiz-naechster-ueberbau-akten-grundstuecksaufnahme` — Fristennotiz Naechster Ueberbau Akten Grundstuecksaufnahme
- `grenzbaum-grenzanlage-hammerschlags-leiterrecht-horrorfall` — Grenzbaum Grenzanlage Hammerschlags Leiterrecht Horrorfall
- `hammerschlagsrecht-hecke-immissionen` — Hammerschlagsrecht Hecke Immissionen
- `immissionen-laerm-landesnachbarrecht-nach-grenzbebauung` — Immissionen Laerm Landesnachbarrecht Nach Grenzbebauung
- `klage-beweislast-nachbarrecht-nachbarschaftsstreit` — Klage Beweislast Nachbarrecht Nachbarschaftsstreit
- `nach-laermimmissionen-mediation-vorrang-nachbarrechtsuebersicht` — Nach Laermimmissionen Mediation Vorrang Nachbarrechtsuebersicht
- `nachbarrecht-kaltstart-triage` — Nachbarrecht Kaltstart Triage
- `notweg-ueberhang-sonderfall-edge` — Notweg Ueberhang Sonderfall Edge
- `notweg-zufahrt-selbsthilfe-eskalationsgrenzen-aeste` — Notweg Zufahrt Selbsthilfe Eskalationsgrenzen Aeste
- `ueberbau-ueberhang-aeste-mediation-nachbarschaftsfrieden` — Ueberbau Ueberhang Aeste Mediation Nachbarschaftsfrieden

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Nachbarschaftsstreit typisch: Schiedsamtsprotokoll, Lärmaufzeichnung, Lichtbilder Grenzbau, Baugenehmigung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 906 II 2 BGB jährliche Berechnung, Schiedsamtsverfahren vor Klage).
- **Beweiswert einordnen.** Lärmprotokoll, Lichtbilder, Zeugen jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Mandant.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
