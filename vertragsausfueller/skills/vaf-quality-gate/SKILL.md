---
name: vaf-quality-gate
description: "Sucht vor Ausgabe fehlende Werte, ungeklärte Wahlklauseln, Rechenfehler, Normierungsprobleme, Anlagenlücken und Freigabehindernisse."
---

# Quality Gate

## Aufgabe

Der Skill ist die letzte Schleuse vor Vertragserzeugung. Er arbeitet freistehend innerhalb des Vertragsausfüller-Plugins und setzt keine anderen Plugins voraus.

## Startet bei

- hochgeladener Word-Vorlage oder altem Vertrag
- Term Sheet, E-Mail, Tabelle oder Freitext mit Eckdaten
- Wunsch nach neuem Vertragsentwurf
- Wunsch nach Redline oder Track Changes

## Workflow

1. Pflichtfelder und Platzhalterreste prüfen.
2. Zahlen- und Fristenlogik prüfen.
3. Track-Changes-Nachfrage prüfen.
4. Go, Go mit Warnungen oder No-go ausgeben.

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
