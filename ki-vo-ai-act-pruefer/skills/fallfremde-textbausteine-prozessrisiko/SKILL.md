---
name: fallfremde-textbausteine-prozessrisiko
description: "Fallfremde KI-Textbausteine erkennen und entschärfen: Namen, Daten, Aktenzeichen, Tatvorwürfe, falsche Anlagen, fremde Prozessgeschichte und bewusst/unbewusst irreführender Vortrag in Schriftsatz, Einspruch, Klage oder Behördenantwort."
---

# Fallfremde Textbausteine

## Warum dieser Skill wichtig ist

KI-gestützte Textarbeit produziert manchmal flüssige, aber fremde Inhalte: anderer Fall, falsche Behörde, unpassender Tatvorwurf, erfundene Anlage, falscher Streitgegenstand. Im Prozess kann das die Glaubwürdigkeit zerstören und berufsrechtliche Folgefragen auslösen.

## Suchmuster

Prüfe gezielt:

- Namen, Firmen, Orte, Gerichte, Behörden.
- Aktenzeichen und Geschäftsnummern.
- Datumslogik und Fristen.
- Anlagenbezeichnungen und Anlagenreihenfolge.
- Beträge, Kontonummern, Vertragsdaten, Bescheidnummern.
- Rechtsgebietssprünge: Strafrecht im Zivilprozess, Mietrecht im Datenschutzfall, falsche Verfahrensordnung.

## Ampel

- **Grün:** Aktenbezug eindeutig.
- **Gelb:** plausibel, aber nicht belegt.
- **Rot:** fremd, erfunden, widersprüchlich oder gefährlich.

## Output

Erstelle:

1. Korrekturliste mit Fundstelle im Dokument.
2. Ersatzformulierung ohne fremden Tatsachenkern.
3. Hinweis, ob eine Berichtigung gegenüber Gericht/Behörde erforderlich sein kann.
4. Kanzlei-Lernpunkt fuer Prompt- und Reviewprozess.

## Qualitätsregel

Wenn ein Satz wie "unstreitig" oder "nachweislich" auftaucht, muss ein Aktenbeleg daneben stehen. Sonst neutralisieren.
