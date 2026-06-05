---
name: weg-hausverwaltung-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Weg Hausverwaltung** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `abrechnung-ist-plan-mieterschnittstelle` — Abrechnung Ist Plan Mieterschnittstelle
- `anwalt-amtsgericht-gewerbe-restaurant-grossakte` — Anwalt Amtsgericht Gewerbe Restaurant Grossakte
- `bad-umbau-barrierefreie-einladung-bauliche-veraenderung` — Bad Umbau Barrierefreie Einladung Bauliche Veraenderung
- `bad-umbau-bodengleiche-dusche-sondereigentum-gemeinschaft` — Bad Umbau Bodengleiche Dusche Sondereigentum Gemeinschaft
- `barrierefreie-einladung-protokoll-versammlung` — Barrierefreie Einladung Protokoll Versammlung
- `bauliche-veraenderung-aufzug-treppenlift-20-abs-2-weg` — Bauliche Veraenderung Aufzug Treppenlift 20 Abs 2 Weg
- `bauliche-veraenderungen-20-weg` — Bauliche Veraenderungen 20 Weg
- `bauliche-veraenderungen-beirat-controlling-beschlussanfechtung` — Bauliche Veraenderungen Beirat Controlling Beschlussanfechtung
- `beirat-controlling-verwalter` — Beirat Controlling Verwalter
- `beschlussanfechtung-risiko` — Beschlussanfechtung Risiko
- `beschlusssammlung-betriebskosten-interessen` — Beschlusssammlung Betriebskosten Interessen
- `beschlusssammlung-protokoll` — Beschlusssammlung Protokoll
- `beschlusssammlung-protokoll-beschlussvorlagen-erstellen` — Beschlusssammlung Protokoll Beschlussvorlagen Erstellen
- `beschlussvorlagen-erstellen` — Beschlussvorlagen Erstellen

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei WEG/Hausverwaltung typisch: TE/GO, Versammlungsprotokoll, Wirtschaftsplan, Jahresabrechnung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 44 WEG Beschlussanfechtung 1 Mon., § 45 WEG Beschlussklage 2 Mon. Begründung).
- **Beweiswert einordnen.** Beschlusssammlung, Versammlungsprotokoll, Einladungs-Zugang jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an WEG-Eigentümer.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
