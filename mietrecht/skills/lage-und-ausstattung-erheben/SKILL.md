---
name: lage-und-ausstattung-erheben
description: Strukturierte Datenerhebung für die Einordnung in den Mietspiegel — Adresse Baujahr Wohnflaeche Bad Kueche Heizung Wohnungsausstattung Gebaeudeausstattung. Erfasst alle Merkmale die in qualifizierten Mietspiegeln als Sondermerkmale bewertet werden (Bodenbelag Fenster Balkon Terrasse Aufzug Stellplatz Energieeffizienz). Erzeugt eine Checkliste und ein strukturiertes Erhebungsprotokoll als Grundlage für ortsuebliche Vergleichsmiete Mieterhoehung Mietsenkungsverlangen oder Klage.
---

# Lage und Ausstattung erheben

## V90 Fachkern — Miet- und WEG-Recht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `Lage und Ausstattung erheben` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** BGB §§ 535 ff., 536, 543, 546a, 548, 556, 556a, 558 ff., 573 ff.; BetrKV; HeizkostenV; WEG §§ 18, 19, 20, 23, 24, 28, 44, 45; GEG; CO2KostAufG.
- **Verifizierte Anker:** BGH, Urteil vom 20.01.2016 - VIII ZR 93/15 (formelle Betriebskostenabrechnung); BGH, Urteil vom 15.12.2021 - VIII ZR 66/20 (Belegeinsicht Originale/Kopien); BGH, Urteil vom 14.02.2025 - V ZR 128/23 (§ 16 Abs. 2 Satz 2 WEG, Rücklagen/Kostenverteilung); BGH, Urteil vom 14.02.2025 - V ZR 86/24 (§ 20 WEG, bauliche Veränderung, Vorbefassung/Beschlussersetzung).
- **Arbeitsmodus:** Immer erst Verhältnis Miete/WEG/Gewerbe/Verwaltung trennen, dann Frist, Beschlusskompetenz, Umlagefähigkeit, Belege, Gebrauchsnachteil und Kostenfolge prüfen.
- **Outputpflicht:** Abrechnungsprüftabelle, Beschlussvorschlag, Anfechtungs-/Beschlussersetzungsskizze, Mietermail, Vermieterschreiben oder Verwalter-To-do-Liste.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


Dieser Skill leitet eine vollständige Datenerhebung an. Ergebnis ist ein strukturiertes Protokoll, das in jeden anderen Skill dieses Plugins einfliesst.

## Disclaimer

Diese Erhebung ersetzt keine Rechtsberatung. Sie ist ein Vorbereitungsschritt für eine spätere rechtliche Prüfung. Bei strittigen Punkten amtliche Quellen heranziehen oder Rechtsrat einholen.

## Workflow

### 1. Adresse und Lage

- Vollständige Adresse (Straße, Hausnummer, PLZ, Ort).
- Stadt-/Stadtteil/Quartier.
- Wohnlagen-Zuordnung nach dem amtlichen Straßenverzeichnis oder Geoportal der Stadt (einfach / mittel / gut). Wenn unklar: Link auf das amtliche Verzeichnis aus references/mietspiegel-quellen.md.

### 2. Gebäude

- Baujahr (laut Mietvertrag, Grundbuchauszug oder Bauakte).
- Letzte umfassende Modernisierung (Jahr, Umfang).
- Anzahl Wohneinheiten.
- Aufzug ja/nein.
- Stellplatz/Garage zur Wohnung gehoerig.
- Energieausweis (Verbrauch oder Bedarf, kWh/(m² · a)).

### 3. Wohnung

- Wohnfläche in m² nach Wohnflächenverordnung (WoFlV).
- Anzahl Zimmer.
- Stockwerk.
- Bodenbelaege je Raum (Parkett, Laminat, Fliesen, Teppich).
- Fenster (Doppel- oder Dreifachverglasung, Holz/Kunststoff).
- Balkon / Loggia / Terrasse (Größe, Ausrichtung).
- Keller / Abstellraum außerhalb der Wohnung.

### 4. Bad

- Anzahl Baeder/WCs.
- Wanne und/oder Dusche.
- Fenster im Bad.
- Bodenheizung.

### 5. Küche

- Einbauküche mitvermietet ja/nein.
- Geräte (Herd, Backofen, Kuehlschrank, Geschirrspueler).

### 6. Heizung und Warmwasser

- Heizungsart (Gas, Fernwaerme, Oel, Waermepumpe).
- Zentral oder Etagenheizung.
- Warmwasserbereitung (zentral, dezentral, über Heizung).

### 7. Mietvertrag

- Vertragsdatum.
- Aktuelle Nettokaltmiete und Vorauszahlungen.
- Indexmiete, Staffelmiete oder Festmiete.
- Schönheitsreparaturklausel (im Original-Wortlaut zitieren).
- Schlüsselgeld, Kaution.

## Ausgabe

Protokoll als Markdown mit den oben genannten Abschnitten plus Quellenangabe (woher stammt jede Information: Mietvertrag, Augenschein, Energieausweis, Straßenverzeichnis). Dieses Protokoll ist Input für alle weiteren Skills.

## Aktuelle Rechtsprechung — Leitsaetze

- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.

## Paragrafenkette

- Ortsueblliche Vergleichsmiete: § 558 BGB
- Begruendungsmittel: § 558a BGB
- Kappungsgrenze: § 558 Abs. 3 BGB

## Quellenregel

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.
