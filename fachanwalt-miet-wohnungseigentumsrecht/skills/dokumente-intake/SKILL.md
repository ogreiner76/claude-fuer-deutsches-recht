---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Miet Wohnungseigentumsrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-abschlusskontrolle-weg-anschluss-router` — Allgemein Abschlusskontrolle Weg Anschluss Router
- `antennen-satellitenschuessel-aufrechnung-zurueckbehaltung` — Antennen Satellitenschuessel Aufrechnung Zurueckbehaltung
- `bauliche-veraenderung-betriebskosten-schnellscan-workflow` — Bauliche Veraenderung Betriebskosten Schnellscan Workflow
- `baurecht-schnittstelle-belegeinsicht-betriebskosten-berliner` — Baurecht Schnittstelle Belegeinsicht Betriebskosten Berliner
- `beschlussanfechtung-abrechnungsfrist-nachforderung-erhalt` — Beschlussanfechtung Abrechnungsfrist Nachforderung Erhalt
- `betrkv-interessen-bgb-co2kostenaufteilung-diskriminierung-agg` — Betrkv Interessen Bgb Co2kostenaufteilung Diskriminierung Agg
- `dokumentenstapel-sortieren-first-year-fotobeweis-mangel-workflow` — Dokumentenstapel Sortieren First Year Fotobeweis Mangel Workflow
- `eigenbedarf-personenkreis-energieausweis-mietrecht-erhaltung-vs` — Eigenbedarf Personenkreis Energieausweis Mietrecht Erhaltung Vs
- `fachanwalt-miet-wohnungseigentumsrecht-mieterhoehung-weg` — Fachanwalt Miet Wohnungseigentumsrecht Mieterhoehung Weg
- `fachanwalt-steuer-schnittstelle-erstgespraech-mandatsannahme` — Fachanwalt Steuer Schnittstelle Erstgespraech Mandatsannahme
- `gartenpflege-baumfaellung-gewerberaum-betriebspflicht` — Gartenpflege Baumfaellung Gewerberaum Betriebspflicht
- `geg-waermepumpe-gerichtstermin-vorbereitung-gewerberaum-intake` — Geg Waermepumpe Gerichtstermin Vorbereitung Gewerberaum Intake
- `gewerberaum-umsatzmiete-gewerberaummiete-glasfaser-kabel` — Gewerberaum Umsatzmiete Gewerberaummiete Glasfaser Kabel
- `heizkostenverordnung-heizung-warmwasser-indexmiete-anpassung` — Heizkostenverordnung Heizung Warmwasser Indexmiete Anpassung

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Miet- und Wohnungseigentumsrecht typisch: Mietvertrag, Nebenkostenabrechnung, WEG-Versammlungsprotokoll, Wirtschaftsplan.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 573c BGB Kündigung, § 44/45 WEG Beschlussanfechtung).
- **Beweiswert einordnen.** Beschlusssammlung, Mietspiegel, SV-Gutachten Mangel jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Mieter.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
