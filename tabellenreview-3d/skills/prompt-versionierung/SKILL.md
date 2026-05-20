---
name: prompt-versionierung
description: "Versioniert alle Spalten- und Zeilenprompts mit semantischer Versions-ID — patch fuer Wortlautfeinheiten minor fuer geaenderte Antworttypen oder Ampelregeln major fuer geaenderte Pruefdimension. Jede Zelle im Wuerfel traegt die Prompt-Version zum Zeitpunkt der Befuellung. Bei Prompt-Aenderung schlaegt der Skill vor welche Zellen invalidiert und neu zu berechnen sind (siehe `caching-und-teil-rerun`). Sicherheitsnetz gegen `schleichende` Spaltenanderungen. Erzeugt `prompt-historie.yaml` und `aktive-prompts.yaml`."
---

# /tabellenreview-3d:prompt-versionierung

## Zweck

Wenn der Spaltenprompt 'Change-of-Control' heute leicht anders formuliert ist als gestern dann sind die heutigen Zellen mit den gestrigen nicht vergleichbar. Dieser Skill macht den Unterschied explizit.

## Versionierungsschema

Semantische Versions-ID pro Prompt: `<spalte-id>@<major>.<minor>.<patch>`

### Patch (`x.y.Z+1`)

- Wortlautfeinheiten ohne Sinnaenderung (Tippfehler / Stilkorrektur / Beispiel ergaenzt)
- Vorhandene Zellen NICHT invalidiert
- Empfehlung: bestehende Zellen behalten

### Minor (`x.Y+1.0`)

- Antworttyp geaendert (z. B. Freitext zu Ja-Nein)
- Ampelregel geaendert (Schwelle verschoben)
- Antwortdimension hinzugefuegt (z. B. zusaetzlich Schwelle in EUR abfragen)
- Vorhandene Zellen werden auf `nachpruefen` gesetzt
- Empfehlung: betroffene Spalten erneut laufen lassen (Teil-Rerun)

### Major (`X+1.0.0`)

- Pruefdimension geaendert (z. B. Spalte 'AGB-Wirksamkeit' splittet zu 'Wirksam' und 'Anwendbares-AGB-Regime')
- Spalte umbenannt oder zusammengelegt
- Vorhandene Zellen werden invalidiert
- Empfehlung: betroffene Zellen komplett neu berechnen

## Aktivierung und Deaktivierung

- Nur eine Version pro Spalte ist gleichzeitig aktiv (`aktive-prompts.yaml`)
- Alte Versionen liegen im `prompt-historie.yaml` mit `gueltig-bis`-Datum
- Wer den aktiven Prompt aendert traegt zwingend den Migrationspfad fuer bestehende Zellen ein

## Pflichtfelder pro Prompt-Version

```yaml
- spalte-id: change-of-control
  version: "2.1.0"
  wortlaut: |
    Enthaelt der Vertrag eine Klausel die bei Kontrollwechsel ...
  antworttyp: zitat-mit-fundstelle-und-schwelle
  ampel-regel:
    rot: "Klausel vorhanden + harte Kuendigungsfolge ohne Heilung"
    gelb: "Zustimmungsvorbehalt mit unklarer Schwelle"
    gruen: "Keine Klausel oder branchenuebliche Schwelle"
  geaendert-am: "2026-05-20"
  geaendert-von: "anwalt-x"
  migrationspfad: "Patch-Aenderung — bestehende Zellen behalten gueltig."
```

## Integration mit Audit-Trail

Jede Prompt-Aenderung erzeugt einen `prompt.geaendert` Eintrag im `audit-trail-protokoll` mit Versionsnummer und Begruendung.

## Grenzen

Versionierung verhindert keine schlechten Prompts — sie macht sie nur sichtbar. Der Pruefer entscheidet ob Migration noetig ist.
