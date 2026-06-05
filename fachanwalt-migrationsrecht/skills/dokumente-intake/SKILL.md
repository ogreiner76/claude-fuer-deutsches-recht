---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Migrationsrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-abschiebungsabwehr-sofort-arbeitgeber-arbeitsrecht` — Allgemein Abschiebungsabwehr Sofort Arbeitgeber Arbeitsrecht
- `arbeitgeberwechsel-asyl-anhoerung-asylg-ausbildungsduldung` — Arbeitgeberwechsel Asyl Anhoerung Asylg Ausbildungsduldung
- `aufenthaltstitel-ausweisung-start-behoerdenkommunikation-blaue` — Aufenthaltstitel Ausweisung Start Behoerdenkommunikation Blaue
- `aufenthaltstitel-erstgespraech-mandatsannahme-fachanwalt-asyl` — Aufenthaltstitel Erstgespraech Mandatsannahme Fachanwalt Asyl
- `ba-zustimmung-beschaeftigungsduldung` — Ba Zustimmung Beschaeftigungsduldung
- `blaue-karte-blaue-karte-bleiberecht-25a-chancenaufenthalt` — Blaue Karte Blaue Karte Bleiberecht 25a Chancenaufenthalt
- `botschaft-visumtermin-workflow-chronologie-dokumentenstapel` — Botschaft Visumtermin Chronologie Dokumentenstapel
- `datenschutz-sicherheit-daueraufenthalt-eu-digitalbeweise-flucht` — Datenschutz Sicherheit Daueraufenthalt Eu Digitalbeweise Flucht
- `dublin-ueberstellung` — Dublin Ueberstellung
- `einbuergerung-lebensunterhalt-mehrstaatigkeit-strafen-einreise` — Einbuergerung Lebensunterhalt Mehrstaatigkeit Strafen Einreise
- `einbuergerung-start-fachkraefte-start` — Einbuergerung Start Fachkraefte Start
- `eurodac-treffer-fachanwalt` — Eurodac Treffer Fachanwalt
- `fachanwalt-migrationsrecht-aufenthaltstitel-ausweisung-bamf` — Fachanwalt Migrationsrecht Aufenthaltstitel Ausweisung Bamf
- `familiennachzug-ehegatte-kind-forscher-ict-freizuegigkeit-eu` — Familiennachzug Ehegatte Kind Forscher Ict Freizuegigkeit Eu

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Migrationsrecht typisch: Bescheid BAMF/ABH, Pass, Aufenthaltstitel, Niederlassungserlaubnis.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 74 AsylG Klagefrist 2 Wochen / 1 Mon., Aufenthaltstitel-Verlängerung 8 Wochen vorher).
- **Beweiswert einordnen.** Identitätsnachweise, Sprachzeugnisse, Erwerbsnachweise jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Mandant Ausländer/Geflüchteter.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
