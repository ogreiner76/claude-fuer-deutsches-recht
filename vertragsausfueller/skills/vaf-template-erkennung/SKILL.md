---
name: vaf-template-erkennung
description: "Erkennt Vertragstyp, Klauselstruktur, Pflichtfelder, variable Felder, feste Corporate-Daten und Wahlklauseln aus Vorlagen und Altverträgen."
---

# Template-Erkennung

## Aufgabe

Der Skill klassifiziert den Vertrag und trennt Fixtext von Variablen. Er arbeitet freistehend innerhalb des Vertragsausfüller-Plugins und setzt keine anderen Plugins voraus.

## Startet bei

- hochgeladener Word-Vorlage oder altem Vertrag
- Term Sheet, E-Mail, Tabelle oder Freitext mit Eckdaten
- Wunsch nach neuem Vertragsentwurf
- Wunsch nach Redline oder Track Changes

## Workflow

1. Vertragstyp, Parteien, Gegenstand, Leistung, Entgelt, Laufzeit, Kündigung, Haftung, Anlagen und Signaturen erkennen.
2. Fixe Stammdaten des Verwenders von variablen Mandatsdaten trennen.
3. Wahlklauseln als Entscheidungspunkte markieren, nicht stillschweigend streichen.
4. Feldnamen normalisieren, damit Term Sheet und Vorlage zusammengeführt werden können.

## Ausgabe

- Vertragsdatenmatrix
- Rückfragenliste
- Ausfüllprotokoll
- Entwurfs- oder Prüfvermerk
- klare Stopper vor Track Changes, falls noch keine ausdrückliche Bestätigung vorliegt

## Leitplanken

- Originaldateien werden nie überschrieben.
- Track Changes, Redline oder Vergleichsfassung nur nach ausdrücklicher Rückfrage und Bestätigung.
- Offene Werte bleiben sichtbar; sie werden nicht erfunden.
- Juristische Wahlentscheidungen werden erklärt und protokolliert.
