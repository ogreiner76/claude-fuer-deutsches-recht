---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Agrarrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `agrar-einfuehrung-rechtsquellen` — Agrar Einfuehrung Rechtsquellen
- `agrar-jagdpacht-streit-mandantenfragen-typisch-paechterbetrieb` — Agrar Jagdpacht Streit Mandantenfragen Typisch Paechterbetrieb
- `agrar-tierhaltung-erstgespraech-mandatsannahme-duenge` — Agrar Tierhaltung Erstgespraech Mandatsannahme Duenge
- `agrar-wolfsschaden-cross-glozez-foerderung-gap` — Agrar Wolfsschaden Cross Glozez Foerderung Gap
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `anerbenrecht-bgb-spezial-compliance` — Anerbenrecht Bgb Compliance
- `cross-duengeverordnung-interessen-erbrecht-beweislast` — Cross Duengeverordnung Interessen Erbrecht Beweislast
- `eu-agrarfoerderung-gap-direktzahlungen-hoefe` — Eu Agrarfoerderung Gap Direktzahlungen Hoefe
- `fachanwalt-agrarrecht-landpacht-hoferbfolge-triage` — Fachanwalt Agrarrecht Landpacht Hoferbfolge Triage
- `fachanwalt-forstrecht-red-hoefe-sonderfall` — Fachanwalt Forstrecht Red Hoefe Sonderfall
- `fristennotiz-naechster-pachtvertrag-streitig-pachtvertrag` — Fristennotiz Naechster Pachtvertrag Streitig Pachtvertrag
- `hoefeo-laender-landpachtrecht` — Hoefeo Länder Landpachtrecht
- `orientierung-tierhaltung-genehmigung-landpacht-schlichtung` — Orientierung Tierhaltung Genehmigung Landpacht Schlichtung
- `pflanzenschutz-schnittstelle-mandantenentscheidung-tierschutz` — Pflanzenschutz Schnittstelle Mandantenentscheidung Tierschutz

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Agrarrecht typisch: Pachtvertrag, GAP-Antrag, Grundbuchauszug, Hofübergabe-Vertrag.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Pachtjahr Kündigungsfristen, Beschwerde gegen GAP-Bescheid).
- **Beweiswert einordnen.** Flächennachweise, InVeKoS-Daten, Pachtverzeichnis jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Landwirt.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
