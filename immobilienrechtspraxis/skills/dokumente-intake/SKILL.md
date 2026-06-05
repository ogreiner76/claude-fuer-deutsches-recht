---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Immobilienrechtspraxis** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `case-gegen-grundbuchanalyse` — Case Gegen Grundbuchanalyse
- `case-management-grundbuchanalyse-immo-aufteilungsplan` — Case Management Grundbuchanalyse Immo Aufteilungsplan
- `immo-bauliche-veraenderung-energieausweis-gewerbliche-mieter` — Immo Bauliche Veraenderung Energieausweis Gewerbliche Mieter
- `immo-bauvertrag-vob-kaufvertrag-grundstueck-mietkaufvertrag` — Immo Bauvertrag Vob Kaufvertrag Grundstueck Mietkaufvertrag
- `immo-grundschuld-bestellung-makler-honorar-wohnungseigentum` — Immo Grundschuld Bestellung Makler Honorar Wohnungseigentum
- `immo-immobilienrechtliche-live-beweislast` — Immo Immobilienrechtliche Live Beweislast
- `immo-zwangsversteigerung-frist-naechster-rechtsabteilungen` — Immo Zwangsversteigerung Frist Naechster Rechtsabteilungen
- `immor-bauvertrag-vob-erbbaurecht-vertrag-grundstueckskaufvertrag` — Immor Bauvertrag Vob Erbbaurecht Vertrag Grundstueckskaufvertrag
- `immor-bodenrichtwert-betriebskostenabrechnung-erstellen` — Immor Bodenrichtwert Betriebskostenabrechnung Erstellen
- `klauselschutz-vertragserstellung-vertragspruefung` — Klauselschutz Vertragserstellung Vertragspruefung
- `management-mieteranfragen-interessen-musterbasierte` — Management Mieteranfragen Interessen Musterbasierte
- `mieteranfragen-bearbeitung-projekt-arbeitsweise` — Mieteranfragen Bearbeitung Projekt Arbeitsweise
- `sachverhaltsermittlung-verifikation-sonderfall-werkzeuge` — Sachverhaltsermittlung Verifikation Sonderfall Werkzeuge

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Immobilienrechtspraxis typisch: Notarvertrag, Grundbuchauszug, Energieausweis, Übergabeprotokoll.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Vormerkung, Auflassungsvormerkung).
- **Beweiswert einordnen.** Grundbuchauszug, Verkehrswertgutachten, Erschließungsbescheinigung jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Käufer.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
