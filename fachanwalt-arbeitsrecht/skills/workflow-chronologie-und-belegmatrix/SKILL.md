---
name: workflow-chronologie-und-belegmatrix
description: "Chronologie und Belegmatrix für arbeitsrechtliche Mandate: zeitliche Sachverhaltsaufbereitung, Ereignis-Zeitachse, Dokumentenzuordnung nach Datum, Lückenidentifikation, Erstellung einer strukturierten Fallchronologie als Arbeitsgrundlage."
---

# Workflow: Chronologie und Belegmatrix

## Zweck
Strukturierte Aufbereitung des Sachverhalts in einer zeitlichen Abfolge mit Belegzuordnung — Grundlage für Schriftsatz, Prüfvermerk und Mandantengespräch. Verhindert, dass wichtige Ereignisse vergessen oder falsch eingeordnet werden.

## Kaltstart
Wenn Unterlagen oder ein Sachverhaltsbericht vorliegen:

1. **Alle relevanten Daten sammeln:** Vertragsdatum, Kündigungsdatum, Zugangsdatum, BR-Anhörungsdatum, Fristdaten, Verhandlungsdaten
2. **Unterlagen sichten:** Welche Dokumente liegen vor? Welche fehlen?
3. **Zeitstrahl erstellen:** Chronologisch alle Ereignisse auflisten
4. **Belege zuordnen:** Welches Dokument belegt welches Ereignis?
5. **Lücken identifizieren:** Was fehlt, um die Chronologie zu vervollständigen?

## Chronologie-Vorlage

### Ereignis-Zeitachse (Beispiel Kündigung)

| Datum | Ereignis | Beteiligter | Belege vorhanden? | Lücke? |
|---|---|---|---|---|
| TT.MM.JJJJ | Beginn Arbeitsverhältnis | AG + AN | Arbeitsvertrag (K1) | — |
| TT.MM.JJJJ | Erste Abmahnung | AG an AN | Abmahnungsschreiben (K2) | — |
| TT.MM.JJJJ | Zweite Abmahnung | AG an AN | ? | Fehlt |
| TT.MM.JJJJ | BR-Anhörungsschreiben | AG an BR | Anhörungsschreiben (K3) | — |
| TT.MM.JJJJ | Ablauf BR-Anhörungsfrist (1 Woche) | BR | BR-Stellungnahme? | Fehlt |
| TT.MM.JJJJ | Ausspruch der Kündigung | AG | Kündigungsschreiben (K4) | — |
| TT.MM.JJJJ | Zugang der Kündigung | AN | Beweisvermerk (K5)? | Fehlt |
| TT.MM.JJJJ + 3W | Ablauf Klagefrist § 4 KSchG | — | — | KRITISCH |
| TT.MM.JJJJ | Einreichung Klageschrift | Anwalt | Klageschrift (K6) | — |
| TT.MM.JJJJ | Gütermin | ArbG | Protokoll | — |

## Belegmatrix-Vorlage

### Schema nach Dokument

| Dokument | Datum | Beweiszweck | Vorhanden? | Anlage |
|---|---|---|---|---|
| Arbeitsvertrag | [Datum] | Betriebszugehörigkeit, Vergütung, Fristen | ? | K1 |
| Abmahnung(en) | [Datum] | Vorwarnung; verhaltensbedingte Kündigung | ? | K2 |
| BR-Anhörungsschreiben | [Datum] | § 102 BetrVG ordnungsgemäß? | ? | K3 |
| BR-Stellungnahme | [Datum] | Einwand oder Zustimmungsfiktion | ? | K4 |
| Kündigungsschreiben (Original) | [Datum] | Schriftform; Inhalt; Kündigungsfrist | ? | K5 |
| Beweisvermerk Zugang | [Datum] | Zugangszeitpunkt | ? | K6 |
| Sozialdaten des Mandanten | — | Sozialauswahl § 1 Abs. 3 KSchG | ? | K7 |
| Vergleichsliste Vergleichsgruppe | — | Sozialauswahl: andere AN | ? | K8 |
| Massenentlassungsanzeige | [Datum] | § 17 KSchG | ? | K9 |

## Lückenanalyse — Output-Format

```
LÜCKENANALYSE — [Mandant, Datum]

VERFÜGBARE BELEGE:
✓ Arbeitsvertrag vom [Datum]
✓ Kündigungsschreiben vom [Datum]
[weitere ...]

FEHLENDE BELEGE (kritisch):
✗ BR-Anhörungsschreiben → Sofort beim AG anfordern (Auskunftspflicht)
✗ Beweisvermerk Zugang → Zeugen benennen; AG auffordern, Beweis darzulegen
[weitere ...]

FEHLENDE BELEGE (mittel):
✗ Zweite Abmahnung → Personalakte beim AG anfordern (§ 83 BetrVG analog)
[weitere ...]

BESCHAFFUNGSWEGE:
1. Personalakte: § 83 BetrVG (bei vorhandenem BR) oder § 630 BGB-analog (AN-Anspruch)
2. BA-Unterlagen: § 17 KSchG-Anzeige → BA-Auskunft anfordern
3. Behördenakten: Integrationsamt-Zustimmung → Akteneinsicht beantragen
```

## Praxishinweis: Zeitkritische Belege zuerst

**Priorität 1 — vor Klagefristablauf:**
- Zugangsdatum sichern (Beweisvermerk, Zeuge)
- Schriftform prüfen (Original sehen)
- Klageschrift einreichen (auch wenn Belege noch fehlen)

**Priorität 2 — nach Klageeinreichung:**
- Vollständige Belegsammlung über Auskunftsansprüche
- BR-Protokolle anfordern
- Sozialauswahl-Unterlagen anfordern (Namensliste § 1 Abs. 3 Satz 1 KSchG)

**Priorität 3 — für Kammertermin:**
- Expertengutachten (wenn nötig)
- Zeugenaussagen vorbereiten

## Anschluss-Skills
- `spezial-paragraf-dokumentenmatrix-und-lueckenliste` für Normen-Dokument-Zuordnung
- `workflow-unterlagen-lueckenliste` für detaillierte Unterlagenprüfung
- `spezial-arbeitsrecht-tatbestand-beweis-und-belege` für Beweislaststrategie

## Quellenregel
- Normtext live prüfen auf [gesetze-im-internet.de](https://www.gesetze-im-internet.de).
- Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und frei prüfbarem Link: [dejure.org](https://dejure.org), [bundesarbeitsgericht.de](https://www.bundesarbeitsgericht.de).
- Annahmen explizit kennzeichnen.

## Was dieser Skill nicht macht
- Keine automatische Chronologie-Erstellung ohne Sachverhaltsangaben des Mandanten.
- Keine Beschaffung von Unterlagen; das bleibt beim Anwalt und Mandanten.
