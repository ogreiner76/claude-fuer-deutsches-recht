---
name: fristenbuch-fuehren
description: Zentrales Fristenbuch fuer die Kanzlei mit Haupt- und Vorfristen ueber alle Rechtsgebiete. Berechnet Fristbeginn nach den jeweiligen Verfahrensordnungen (ZPO StPO SGG FGO VwGO FamFG AO BGB) Drei-Tages-Fiktionen bei Postzustellung. Trennt Notfristen (BRAO-Haftungsrisiko) von Beobachtungsfristen. Setzt Vorfristen typisch fuenf Werktage vor Hauptfrist; bei BRAO-relevanten Notfristen sieben Werktage. Eskalation an Sekretariat und zustaendigen Anwalt bei Vorfristerreichung. Audit-Trail jeder Fristaenderung.
---

# Zentrales Fristenbuch der Kanzlei

## Pflicht

Jede Kanzlei muss ein Fristenbuch fuehren — die Versaeumung einer Notfrist ist anwaltliche Pflichtverletzung mit Haftungsrisiko (§ 51 BRAO).

## Zentralablage

`~/.claude/plugins/config/claude-fuer-deutsches-recht/kanzlei-cowork/fristenbuch.yaml`

```yaml
- mandat-az: 2026/0042
  mandant: Mueller GmbH
  vorgang: Kundenklage
  fristart: berufungsfrist
  rechtsgrundlage: "§ 517 ZPO"
  fristbeginn: 2026-03-15
  hauptfrist: 2026-04-15
  vorfrist-tage: 7
  vorfrist: 2026-04-06
  zustaendig: RA Mueller
  status: offen
  bemerkung: Berufungsbegruendung gemaess § 520 ZPO innerhalb von zwei Monaten
```

## Fristarten und Standardfristen

### Zivilprozess (ZPO)

| Frist | Norm | Dauer |
|---|---|---|
| Klageerwiderung | § 276 ZPO | nach gerichtlicher Setzung (regelmaessig zwei Wochen Notfrist plus zwei Wochen weitere Frist) |
| Berufung | § 517 ZPO | ein Monat ab Zustellung |
| Berufungsbegruendung | § 520 ZPO | zwei Monate ab Zustellung |
| Revision | § 548 ZPO | ein Monat |
| Revisionsbegruendung | § 551 ZPO | zwei Monate |
| Sofortige Beschwerde | § 569 ZPO | zwei Wochen Notfrist |
| Einspruch Versaeumnisurteil | § 339 ZPO | zwei Wochen Notfrist |

### Arbeitsgericht (ArbGG)

| Frist | Norm | Dauer |
|---|---|---|
| Kuendigungsschutzklage | § 4 KSchG | drei Wochen Notfrist |
| Berufung | § 66 ArbGG | ein Monat |

### Strafprozess (StPO)

| Frist | Norm | Dauer |
|---|---|---|
| Berufung | § 314 StPO | eine Woche Notfrist |
| Revision | § 341 StPO | eine Woche Notfrist |
| Revisionsbegruendung | § 345 StPO | ein Monat |
| Beschwerde | § 311 StPO | eine Woche |

### Verwaltungsgericht (VwGO)

| Frist | Norm | Dauer |
|---|---|---|
| Widerspruchsfrist | § 70 VwGO | ein Monat |
| Klagefrist | § 74 VwGO | ein Monat |
| Berufungsantrag | § 124a VwGO | ein Monat (Zulassungsbeschwerde) |
| Eilrechtsschutz | § 80 Abs. 5 VwGO | keine eigene Antragsfrist |

### Sozialgericht (SGG) — siehe Plugin `sozialrecht-kanzlei`

### Finanzgericht (FGO) — siehe Plugin `steuerrecht-kanzlei`

### Familiengericht (FamFG)

| Frist | Norm | Dauer |
|---|---|---|
| Beschwerde | § 63 FamFG | ein Monat |
| Sofortige Beschwerde | § 64 FamFG | zwei Wochen |

## Notfrist vs Beobachtungsfrist

- **Notfristen** (Versaeumnis = Verlust): Berufung Revision Kuendigungsschutzklage. Vorfrist sieben Werktage.
- **Beobachtungsfristen** (z. B. Vorlauf zur Stellungnahme): Vorfrist drei bis fuenf Werktage.

## Drei-Tages-Fiktionen

- **§ 270 Satz 2 ZPO** Schriftsatzzustellung
- **§ 122 Abs. 2 AO** Steuerbescheid
- **§ 41 Abs. 2 VwVfG** Verwaltungsakt
- **§ 37 Abs. 2 SGB X** Sozialleistungsbescheid

Beim Eintragen automatisch beruecksichtigen — bei nachweislich frueherem Zugang Zugang massgeblich.

## Vorfristen

- **Standard** fuenf Werktage vor Hauptfrist.
- **Notfristen** sieben Werktage.
- **Berufungs-/Revisionsbegruendung** zehn Werktage (zwei-Monats-Fristen).

## Workflow

1. **Eintragen** sofort bei Posteingang Bescheid Urteil Zustellung.
2. **Kontrolle** durch Sekretariat **und** zustaendigen Anwalt (Vier-Augen-Prinzip).
3. **Vorfrist** loest Eintrag im Tagesbrief aus (Skill `sekretariats-tagesbrief`).
4. **Erledigung** mit Datum und Unterschrift / Initial.
5. **Audit** bei jeder Aenderung Eintrag in Audit-Trail.

## Ausgabe

- `fristenbuch.yaml` aktualisiert
- `fristen-uebersicht.md` Tagesbericht naechste sieben und naechste vierzehn Tage
- Vorfristen-Erinnerung in `sekretariats-tagesbrief`
- Audit-Eintrag bei Aenderungen

## Haftungshinweis

Das Fristenbuch ist nur so gut wie seine Pflege. Die Letztverantwortung liegt beim Anwalt. Bei Versaeumnis Wiedereinsetzung pruefen (jeweilige Verfahrensordnung).
