---
name: bescheid-frist-quick-check
description: "60-Sekunden-Sofortpruefung der Frist eines sozialrechtlichen Bescheids. Eingabe Datum der Bekanntgabe (Zugang) und Datum des Bescheids und Status der Rechtsbehelfsbelehrung. Berechnung Widerspruchsfrist § 84 SGG ein Monat ab Bekanntgabe. Bei fehlender oder unrichtiger Rechtsbehelfsbelehrung ein Jahr ab Bekanntgabe nach § 66 Abs. 2 SGG. Bekanntgabe-Fiktion bei einfachem Brief drei Tage ab Aufgabe zur Post § 37 Abs. 2 SGB X. Endet mit Ampel rot (verstrichen) gelb (knapp unter zwei Wochen) gruen (komfortabel) plus Frist-Datum und Vorfrist-Datum. Vorschalt-Skill fuer alles weitere. Pruefung Wiedereinsetzung § 67 SGG bei roter Ampel. Pruefung § 44 SGB X Ueberpruefungsantrag wenn Wiedereinsetzung ausgeschlossen."
---

# Frist-Quick-Check

Sofort-Eingangstuer zu jedem Bescheid. Vor Bescheidanalyse, vor Widerspruchsentwurf. **Nichts** vorher tun.

## Eingabe

- Datum auf dem Bescheid
- Datum der Bekanntgabe (Zugang, Posteingang)
- Hat der Bescheid eine **Rechtsbehelfsbelehrung**? (ja / nein / unklar / nur teilweise)
- Versandweg (einfacher Brief / Postzustellungsurkunde PZU / Einschreiben mit Rueckschein / elektronisch)

## Rechtsgrundlagen — Kompakt

| Norm | Inhalt |
|---|---|
| § 84 Abs. 1 SGG | Widerspruchsfrist ein Monat ab Bekanntgabe |
| § 66 Abs. 1 SGG | Frist laeuft nur bei korrekter Rechtsbehelfsbelehrung |
| § 66 Abs. 2 SGG | Bei fehlender / unrichtiger Belehrung ein Jahr ab Bekanntgabe |
| § 37 Abs. 2 SGB X | Bekanntgabe-Fiktion einfacher Brief — am dritten Tag nach Aufgabe zur Post |
| § 87 SGG | Klagefrist ein Monat nach Zustellung Widerspruchsbescheid |
| § 67 SGG | Wiedereinsetzung in den vorigen Stand bei unverschuldeter Versaeumung |
| § 44 SGB X | Ueberpruefungsantrag — auch nach Bestandskraft |
| § 86b SGG | Eilrechtsschutz beim Sozialgericht |

## Algorithmus

Schritt 1 — Bekanntgabe bestimmen:
- PZU oder Einschreiben mit Rueckschein → Datum auf Urkunde
- Einfacher Brief → drei Tage nach Aufgabe zur Post (Datum auf Bescheid plus drei Tage, sofern nicht Mandant frueheres Zugangsdatum angibt)
- Elektronisch über Postfach → tatsaechliches Abrufdatum, spaetestens drei Tage

Schritt 2 — Fristbeginn ist der Tag nach Bekanntgabe (§ 26 Abs. 1 SGB X iVm § 187 Abs. 1 BGB).

Schritt 3 — Fristende ist eine Monat spaeter, abends 24 Uhr, ggf. mit § 26 Abs. 3 SGB X (Wochenende, Feiertag).

Schritt 4 — Falls Rechtsbehelfsbelehrung fehlt oder fehlerhaft: Frist ist ein Jahr.

## Ampel

| Status | Verbleibende Tage | Sofortaktion |
|---|---|---|
| GRUEN | mehr als 14 | normale Bearbeitung, Akteneinsicht parallel |
| GELB | 4 bis 14 | Vorrang Widerspruch heute oder morgen, Begruendung nachreichen § 84 Abs. 1 SGG |
| ROT | weniger als 4 | sofort Widerspruchsschreiben „dem Grunde nach" — Begruendung folgt |
| VERSTRICHEN | minus | Wiedereinsetzung § 67 SGG pruefen, ggf. § 44 SGB X |
| EILBEDARF | egal | parallel `eilantrag-sozialrecht` |

## Output-Format

Liefere immer diese genau drei Zeilen plus Aktion:

```
FRIST-QUICK-CHECK [Mandant] — [Az]

Bekanntgabe: [TT.MM.JJJJ] (Grundlage: [PZU / Brief plus drei Tage / Mandantenangabe])
Frist Widerspruch: [TT.MM.JJJJ] — verbleibend [N Tage]
Belehrung: [korrekt / fehlt / unrichtig — Konsequenz: Frist Monat / Jahr]
Ampel: [GRUEN / GELB / ROT / VERSTRICHEN / EILBEDARF]
Sofort: [konkrete erste Handlung heute]
```

## Wiedereinsetzung § 67 SGG — Kurzpruefung

Voraussetzungen alle:
- Frist unverschuldet versaeumt (Krankheit, Naturkatastrophe, kein Verschulden der Anwaltschaft auf den Mandanten zugerechnet § 73 Abs. 6 SGG iVm § 85 ZPO)
- Antrag binnen zwei Wochen nach Wegfall des Hindernisses
- Glaubhaftmachung (Attest, Bestaetigung)
- Nachholung der versaeumten Handlung im selben Schriftsatz

Wenn nicht alle erfuellt → kein Wiedereinsetzungsantrag, stattdessen `§ 44 SGB X` Ueberpruefungsantrag pruefen.

## Faustregel Bestandskraft und § 44

§ 44 Abs. 1 SGB X greift, wenn der Bescheid **rechtswidrig** war und der Mandant deshalb zu wenig oder gar keine Leistung erhalten hat. Rueckwirkung max. vier Jahre § 44 Abs. 4 SGB X. Antragsstellung jederzeit moeglich.

## Anschluss-Skills

| Ergebnis | Naechster Skill |
|---|---|
| Ampel gruen oder gelb | `bescheidanalyse` |
| Ampel rot | `widerspruch-formulieren` (Kurzfassung dem Grunde nach) |
| Ampel verstrichen, Wiedereinsetzung moeglich | `widerspruch-formulieren` mit Antrag § 67 SGG |
| Ampel verstrichen, keine Wiedereinsetzung | Pruefung § 44 SGB X (eigenstaendiger Pfad) |
| Eilbedarf | `eilantrag-sozialrecht` parallel |
