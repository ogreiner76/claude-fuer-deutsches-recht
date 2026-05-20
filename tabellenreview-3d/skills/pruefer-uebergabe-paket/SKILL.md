---
name: pruefer-uebergabe-paket
description: "Schnuert das vollstaendige Pruefer-Paket nach Abschluss eines Wuerfellaufs — Excel-Wuerfel-Datei aus Skill `excel-multi-sheet-export` PDF-Bericht aus `pdf-bericht-erzeugen` Belegketten-CSV aus `belegkette-rueckverfolgung` Audit-Trail-Auszug aus `audit-trail-protokoll` Prompt-Versionen aus `prompt-versionierung` Widerspruchsbericht aus `kreuzblatt-konsistenzpruefung` Ampel-Aggregat aus `risikoampel-aggregation` Pruefer-Flag-Arbeitsliste. Erzeugt ein ZIP-Paket plus Begleitschreiben. Pflichtschritt vor Mandatsabnahme. Ohne Pruefer-Unterschrift kein Versand an Mandant."
---

# /tabellenreview-3d:pruefer-uebergabe-paket

## Zweck

Das Plugin liefert nicht das fertige Mandatsergebnis. Es liefert das Pruefer-Paket — alles was der zugelassene Rechtsanwalt braucht um in vertretbarer Zeit die Endabnahme machen zu koennen. Dieser Skill schnuert das Paket.

## Bestandteile

### 1. Hauptdatei

- `<projekt>-wuerfel.xlsx` aus `excel-multi-sheet-export` mit allen Tabellenreitern.

### 2. Erzaehlfassung

- `<projekt>-bericht.pdf` aus `pdf-bericht-erzeugen` mit Deckblatt Management-Summary und Anhang.

### 3. Belegkette

- `belegkette.csv` aus `belegkette-rueckverfolgung` — Pflichtanhang fuer Reproduzierbarkeit.

### 4. Audit

- `audit-trail-auszug.md` aus `audit-trail-protokoll` — die letzten N Ereignisse, mindestens aber Lauf-Start Lauf-Ende Prompt-Versionen und Pruefer-Flags.

### 5. Prompt-Versionen

- `prompt-historie.yaml` aus `prompt-versionierung` — welche Versionen aktiv waren beim Lauf.

### 6. Widersprueche

- `widerspruchsbericht.md` aus `kreuzblatt-konsistenzpruefung` — Konflikte zwischen Arbeitsblaettern.

### 7. Ampel-Aggregat

- `ampel-aggregat.md` aus `risikoampel-aggregation` — Gesamtbild auf Wuerfel- Arbeitsblatt- Spalten- und Zeilenebene.

### 8. Pruefer-Flag-Arbeitsliste

- `pruefer-flags.xlsx` — Liste aller Zellen die menschliche Pruefung brauchen. Spalten: Zeile Arbeitsblatt Spalte Grund Antwortvorschlag Entscheidung (leer).

### 9. Begleitschreiben

- `begleitschreiben.md` — eine Seite. Was wurde gemacht. Wie viele Dokumente. Wie viele Hotspots. Wie viele Pruefer-Flags. Erwartete Pruefdauer. Ablauf der Abnahme.

## Zusammenstellung

Alles in einem ZIP: `<projekt>-pruefer-paket-<zeitstempel>.zip`

## Abnahme

Der Pruefer:

1. Liest das Begleitschreiben.
2. Geht die Pruefer-Flag-Arbeitsliste durch — Entscheidung pro Flag.
3. Stichprobenpruefung an gelben und gruenen Zellen.
4. Pruefung der roten Zellen und Hotspots vollstaendig.
5. Unterschrift im Audit-Trail (`prueferabnahme.eingegeben`).

## Erst nach Abnahme

Erst nach dokumentierter Pruefer-Abnahme darf das Paket (oder Auszuege davon) an den Mandanten gehen. Das Plugin sperrt die Mandantenausgabe per Schwellenwert: ohne `prueferabnahme.eingegeben` im Audit-Trail wird der Skill `mandant-versenden` (sofern in der Praxis vorgesehen) verweigert.

## Begruendung

- BRAO Paragraph 43a Absatz 2 — Verschwiegenheit
- StGB Paragraph 203 — Privatgeheimnisse
- RDG Paragraph 2 — Rechtsdienstleistung darf nur durch Rechtsanwalt erbracht werden — der Wuerfel ist Vorbereitung, die Abnahme ist die Rechtsdienstleistung
