---
name: audit-trail-protokoll
description: "Fuehrt das Audit-Trail-Protokoll des Wuerfels — jeder Reviewlauf jede Prompt-Aenderung jede Pruefer-Abnahme jeder Cache-Treffer jede Hash-Pruefung wird unveraenderlich protokolliert. Spalten pro Eintrag: Zeitstempel Aktion Verantwortlicher Wuerfelversion Prompt-Version Modell-Version Eingangs-Hash Ausgangs-Hash Begruendung. Ablage als `audit-trail.jsonl` (append-only) und als `audit-trail.md` (menschenlesbar). Pflichteintrag vor jeder Mandatsuebergabe. Erlaubt Nachweis gegenueber Mandant Pruefer Aufsicht und Versicherung dass der Wuerfel reproduzierbar entstand."
---

# /tabellenreview-3d:audit-trail-protokoll

## Zweck

Wer mit KI Vertraege prueft muss spaeter erklaeren koennen wie das Ergebnis zustande kam. Dieser Skill ist die Erklaerung — Append-only-Log fuer den gesamten Lebenszyklus des Wuerfels.

## Ereignistypen

### Wuerfel-Lebenszyklus

- `wuerfel.erstellt` — Wuerfel-Schema neu angelegt
- `wuerfel.dimension-erweitert` — Spalte / Zeile / Arbeitsblatt hinzugefuegt
- `wuerfel.dimension-gekuerzt` — Spalte / Zeile / Arbeitsblatt entfernt
- `wuerfel.archiviert` — Wuerfel abgeschlossen

### Prompts

- `prompt.erstellt` — neuer Spalten- oder Zeilenprompt definiert
- `prompt.geaendert` — Prompt-Wortlaut geaendert (Versions-ID erhoeht)
- `prompt.deaktiviert` — Prompt aus aktivem Schema genommen

### Reviewlauf

- `lauf.gestartet` — Reviewlauf begonnen, mit Wuerfel-Snapshot-Hash
- `lauf.beendet` — Reviewlauf beendet, mit Ergebnis-Hash
- `lauf.fehler` — Reviewlauf abgebrochen, mit Fehlermeldung

### Caching

- `cache.treffer` — Zelle aus Cache uebernommen, Quell-Zell-ID
- `cache.invalidiert` — Cache-Eintrag verworfen weil Prompt-Version geaendert

### Pruefer-Workflow

- `prueferflag.gesetzt` — Zelle braucht menschliche Pruefung, Grund
- `prueferabnahme.eingegeben` — Pruefer hat abgehakt, Pruefer-ID und Entscheidung
- `pruefer.kommentar` — Pruefer-Kommentar zu Zelle

### Belegkette

- `datei.gehasht` — Hash einer Quelldatei berechnet
- `hash-bruch` — Quelldatei-Hash weicht vom registrierten Hash ab (Manipulationsverdacht)

## Pflichtfelder pro Eintrag

```json
{
  "zeitstempel": "2026-05-20T14:23:11Z",
  "aktion": "lauf.beendet",
  "verantwortlicher": "system",
  "wuerfel-version": "v3",
  "prompt-version": "p12",
  "modell-version": "claude-opus-4-7",
  "eingangs-hash": "sha256:...",
  "ausgangs-hash": "sha256:...",
  "anzahl-zellen": 4176,
  "anzahl-prueferflag": 87,
  "begruendung": "Standardlauf nach Schema-Aenderung Spalte 'MAC'"
}
```

## Ablage

- `audit-trail.jsonl` — append-only, eine JSON-Zeile pro Ereignis. Nie aendern, nur anhaengen.
- `audit-trail.md` — periodisch zu menschenlesbarem Markdown verdichtet (z. B. wochenweise).

## Integritaet

- Jeder Eintrag enthaelt den Hash des vorherigen Eintrags (Chain-of-Trust). Wer einen Eintrag aendert bricht die Kette.
- Optional: kryptografische Signatur des Pruefers bei Abnahme-Ereignissen.

## Verwendung

- Pflicht vor jeder Mandatsuebergabe — der Pruefer signiert den letzten Audit-Stand.
- Bei Beschwerden Aufsicht oder Haftungsfrage rueckverfolgbar nachweisen welcher Reviewlauf welchen Output produziert hat.
- Verhindert dass Prompts schleichend geaendert werden und alte Zellen `nicht mehr nachvollziehbar` sind.
