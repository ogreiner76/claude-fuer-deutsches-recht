---
name: vaf-bsag-mietvertrag
description: "Spezialworkflow für den BSAG-Kiosk-Mietvertrag: Term Sheet Huckelriede in die Mietvertragsvorlage übertragen, Lücken markieren und Klauselentscheidungen abfragen."
---

# BSAG-Mietvertrag

## Aufgabe

Der Skill setzt den Huckelriede-Term-Sheet-Fall in die BSAG-Vorlage um. Er arbeitet freistehend innerhalb des Vertragsausfüller-Plugins und setzt keine anderen Plugins voraus.

## Startet bei

- hochgeladener Word-Vorlage oder altem Vertrag
- Term Sheet, E-Mail, Tabelle oder Freitext mit Eckdaten
- Wunsch nach neuem Vertragsentwurf
- Wunsch nach Redline oder Track Changes

## Workflow

1. BSAG-Stammdaten als feste Vermieterdaten übernehmen.
2. Mieter, Mietobjekt, Fläche, Nutzung, Miete, Nebenkosten, Kaution, Laufzeit, Option, Indexierung, Öffnungszeiten und Sonderbedingungen mappen.
3. Sonderpunkte wie Konkurrenzschutz, Fettabscheider, Sauberhaltung, Sortiment, Werbung und Rückbau als Klauselentscheidungen abfragen.
4. Clean-Entwurf, Ausfüllprotokoll und auf Wunsch nach Rückfrage Redline-Fassung vorbereiten.

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
