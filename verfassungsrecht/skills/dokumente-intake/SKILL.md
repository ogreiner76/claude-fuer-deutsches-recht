---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Verfassungsrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `gesetzgebungskompetenz-grundrechtspruefung` — Gesetzgebungskompetenz Grundrechtspruefung
- `grundrechtspruefung-acht-formelle-interessen` — Grundrechtspruefung Acht Formelle Interessen
- `materielle-petition-sonderfall-recherche` — Materielle Petition Sonderfall Recherche
- `rechtsprechungsgetrieben-rechtsweg-bverfg-verfahrenssicht` — Rechtsprechungsgetrieben Rechtsweg Bverfg Verfahrenssicht
- `sicht-spezialkanzlei-unter` — Sicht Spezialkanzlei Unter
- `verfassung-beweislast-verfassungsbeschwerde` — Verfassung Beweislast Verfassungsbeschwerde
- `verfassung-grundgesetz-verfassung-organstreitverfahren` — Verfassung Grundgesetz Verfassung Organstreitverfahren
- `verfassung-grundrechte-juristische-uebersicht-eu` — Verfassung Grundrechte Juristische Uebersicht Eu
- `verfassung-konkrete-normenkontrolle-parteiverbot-petition` — Verfassung Konkrete Normenkontrolle Parteiverbot Petition
- `verfassung-staatsorganisation-verfassungsrechtliche` — Verfassung Staatsorganisation Verfassungsrechtliche
- `verfassungsbeschwerde-entwurf-formelle-verfassungsmaessigkeit` — Verfassungsbeschwerde Entwurf Formelle Verfassungsmaessigkeit
- `verfassungsrecht-verfassung-abstrakte-verfassung-bund` — Verfassungsrecht Verfassung Abstrakte Verfassung Bund
- `vfgr-bundestreue-foederalismus-grundrechtspruefung-bauleiter` — Vfgr Bundestreue Foederalismus Grundrechtspruefung Bauleiter

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Verfassungsrecht typisch: Letzter fachgerichtl. Beschluss, Verfassungsbeschwerde-Schriftsatz, Vorlagebeschluss.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 93 BVerfGG 1 Monat Verfassungsbeschwerde, Rechtswegerschöpfung).
- **Beweiswert einordnen.** Tragende Erwägungen Vorinstanzen, Substantiierung Grundrechtsverletzung jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Beschwerdeführer.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
