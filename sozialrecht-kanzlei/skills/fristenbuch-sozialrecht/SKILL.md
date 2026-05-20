---
name: fristenbuch-sozialrecht
description: Fristenbuch fuer sozialrechtliche Verfahren — pflegt zentrale Datei mit Hauptfristen und Vorfristen. Standardfristen SGG (§ 84 Widerspruch ein Monat / § 87 Klage ein Monat / § 173 Beschwerde ein Monat) SGB X (§ 84 Untaetigkeit nach drei Monaten / § 13 Abs. 3a SGB V drei Wochen Genehmigungsfiktion / § 18 SGB IX zwei Monate). Berechnet Fristbeginn nach § 37 SGB X (Drei-Tages-Fiktion Zustellung) und § 26 SGB X (Fristberechnung). Setzt Vorfristen (typisch drei bis fuenf Tage vor Hauptfrist).
---

# Fristenbuch Sozialrecht

## Zentralablage

`~/.claude/plugins/config/claude-fuer-deutsches-recht/sozialrecht-kanzlei/fristenbuch.yaml`

Pro Eintrag:

```yaml
- mandat-az: SR-2026-0042
  mandant: Mueller, Hans
  vorgang: Buergergeld-Bescheid 12.03.2026
  fristart: widerspruchsfrist
  rechtsgrundlage: "§ 84 Abs. 1 SGG"
  fristbeginn: 2026-03-15  # Zugang nach Drei-Tages-Fiktion § 37 SGB X
  hauptfrist: 2026-04-15
  vorfrist-tage: 5
  vorfrist: 2026-04-10
  zustaendig: RA Mueller
  status: offen
  bemerkung: Widerspruchsbegruendung benoetigt Akteneinsicht
```

## Standardfristen

### SGG

| Frist | Norm | Dauer |
|---|---|---|
| Widerspruchsfrist | § 84 Abs. 1 SGG | ein Monat ab Bekanntgabe; ein Jahr bei fehlender Rechtsbehelfsbelehrung § 66 Abs. 2 SGG |
| Klagefrist nach Widerspruchsbescheid | § 87 Abs. 1 SGG | ein Monat |
| Untaetigkeitsklage | § 88 SGG | drei Monate Untaetigkeit der Behoerde |
| Beschwerde gegen Beschluesse des SG | § 173 SGG | ein Monat |
| Berufung gegen Urteile des SG | § 151 SGG | ein Monat |
| Revisionsfrist | § 164 SGG | ein Monat |
| Wiedereinsetzung | § 67 SGG | zwei Wochen ab Wegfall des Hindernisses |

### SGB X / SGB V

| Frist | Norm | Bedeutung |
|---|---|---|
| Drei-Tages-Fiktion Zustellung | § 37 Abs. 2 SGB X | Bekanntgabe drei Tage nach Aufgabe zur Post |
| Genehmigungsfiktion Krankenkasse | § 13 Abs. 3a SGB V | drei Wochen (fuenf Wochen bei MDK) |
| Entscheidungsfrist Reha-Antrag | § 18 SGB IX | zwei Monate |
| Ueberpruefungsantrag | § 44 SGB X | keine eigentliche Frist aber Wirkung nur fuer Vergangenheit |

## Berechnung Fristbeginn

- **Postzustellung** drei Tage nach Aufgabe (§ 37 Abs. 2 SGB X). Wenn nachweislich frueherer Zugang: Zugang massgeblich.
- **EGVP / beA** Tag der erfolgreichen Uebertragung.
- **Bekanntgabe durch Aushaendigung** Tag der Aushaendigung.
- **Fristberechnung** § 26 SGB X iVm §§ 187 ff. BGB — Beginn des Folgetages; Ende mit Ablauf des entsprechenden Tages des letzten Monats; bei Wochenende / Feiertag auf naechsten Werktag.

## Vorfristen

- Standard fuenf Werktage vor Hauptfrist.
- Bei Klagefristen Vorfrist mindestens sieben Tage (Akteneinsicht beA-Versand Anlagenkonvolut).
- Eskalation bei Vorfrist-Erreichung an zustaendigen Anwalt.

## Pflege

- Bei Eingang Bescheid: sofort Eintrag im Fristenbuch.
- Bei Eingang Widerspruchsbescheid: Eintrag Klagefrist.
- Bei Untaetigkeit der Behoerde: Eintrag Drei-Monats-Frist Untaetigkeitsklage.
- Bei Bewilligung mit Aenderungsvorbehalt: ggf. Wiedervorlage.

## Ausgabe

- `fristenbuch.yaml` aktualisiert
- `fristen-uebersicht.md` als Sekretariats-Bericht (Tagesbericht naechste sieben Tage)
- Bei Vorfristerreichung: Erinnerungs-Eintrag im Sekretariats-Tagesbrief (Plugin `kanzlei-cowork`)

## Sicherheit

- Niemals Fristen aendern ohne dokumentierte Begruendung.
- Audit-Trail in der Aktenchronik.
- Sekretariat und Anwalt gegenseitig pruefen.
