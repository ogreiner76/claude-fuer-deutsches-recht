---
name: risikoampel-aggregation
description: "Konsolidiert die Ampel-Wertungen entlang aller drei Wuerfelachsen — pro Zelle (atomisch) pro Zeile (Dokument-Gesamtampel) pro Spalte (Datenpunkt-Hotspots) pro Arbeitsblatt (Perspektiven-Gesamtampel) und pro Gesamtwuerfel (Projekt-Ampel). Verwendet Schweregrad-Boden — eine rote Zelle macht die Zeile mindestens orange. Erkennt Hotspots (Spalten mit ueberproportional vielen roten Zellen). Erzeugt `ampel-aggregat.md` und Heatmap-Daten fuer Excel-Export. Pflichtschritt vor `pruefer-uebergabe-paket`."
---

# /tabellenreview-3d:risikoampel-aggregation

## Zweck

4000 Zellen einzeln zu sichten ist nicht praktikabel. Diese Aggregation reduziert die Sicht ohne Information zu verlieren — wer reinzoomen will klickt durch.

## Aggregationsstufen

### Zellen-Ampel (atomisch)

Aus `review-durchfuehren`. Vier Werte: gruen / gelb / rot / pruefer-flag.

### Zeilen-Ampel (Dokument)

Konsolidierung ueber alle Zellen einer Zeile (also ueber alle Spalten aller Arbeitsblaetter):
- mindestens 1 rote Zelle = Zeile **rot**
- keine rote aber mindestens 2 gelbe = Zeile **gelb**
- nur gruen = Zeile **gruen**
- mindestens 1 Pruefer-Flag = `pruefer-flag` zusaetzlich

### Spalten-Ampel (Datenpunkt-Hotspot)

Anzahl roter Zellen ueber alle Zeilen ueber alle Arbeitsblaetter pro Spalte. Top-5-Spalten mit hoechstem Rot-Anteil = Hotspot-Spalten. Beispiel: 'Change of Control' rot in 42 von 87 Vertraegen = Hotspot.

### Arbeitsblatt-Ampel (Perspektive)

Anteil roter Zeilen je Arbeitsblatt. Erlaubt Aussage: 'aus Datenschutzsicht ist das Portfolio kritisch, aus Wirtschaftssicht passabel'.

### Wuerfel-Ampel (Gesamtprojekt)

Worst-of-Worst-Konsolidierung: wenn irgendein Arbeitsblatt rot ist und irgendeine Zeile rot ist und Pruefer noch nicht abgenommen hat = **rot blockierend**.

## Schweregrad-Boden

Wenn ein Skill ein Finding mit einem Schweregrad produziert und ein anderer Skill (z. B. `kreuzblatt-konsistenzpruefung`) ihn aendern will, gilt der vorgelagerte Schweregrad als BODEN — eine rote Zelle kann nicht still nach gelb verschoben werden, nur dokumentiert ueberschrieben.

## Ausgabe

- `ampel-aggregat.md` mit:
  - Wuerfel-Ampel (gesamt)
  - Arbeitsblatt-Ampeln (eine je Perspektive)
  - Spalten-Hotspots (Top-N)
  - Zeilen-Ampel-Liste (sortiert nach Schwere)
- `heatmap.json` mit Daten fuer Excel-Heatmap-Visualisierung

## Hinweis zur Pruefer-Abnahme

Vor Mandatsabnahme muessen ALLE Zellen mit `pruefer-flag` durch den Pruefer abgehakt sein. Ohne Pruefer-Abnahme darf das Aggregat nicht an Mandanten gehen.
