---
name: vaf-plausibilitaetscheck
description: "Prüft Zahlen, Fristen, Querverweise, Anlagen, Parteidaten, Umsatzsteuer, Kaution, Optionen und interne Widersprüche vor Ausgabe."
---

# Plausibilitätscheck

## Aufgabe

Der Skill härtet den Entwurf vor Versand oder Verhandlung. Er arbeitet freistehend innerhalb des Vertragsausfüller-Plugins und setzt keine anderen Plugins voraus.

## Startet bei

- hochgeladener Word-Vorlage oder altem Vertrag
- Term Sheet, E-Mail, Tabelle oder Freitext mit Eckdaten
- Wunsch nach neuem Vertragsentwurf
- Wunsch nach Redline oder Track Changes

## Workflow

1. Gesamtmiete gegen Kaltmiete und Nebenkosten rechnen.
2. Kaution gegen Monatsmieten, Mietbeginn gegen Laufzeitende und Optionsfristen prüfen.
3. Verweise auf Anlagen, Klauseln und Signaturblöcke kontrollieren.
4. Unplausibles als rote Rückfrage markieren, nicht still korrigieren.

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
