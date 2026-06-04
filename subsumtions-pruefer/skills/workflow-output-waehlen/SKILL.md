---
name: workflow-output-waehlen
description: "Output wählen im Plugin subsumtions-pruefer: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung."
---

# Output wählen

## Aufgabe

Dieser Workflow-Skill wählt den richtigen Output-Typ für die Arbeitsaufgabe. Er unterscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline und Mandantenübersetzung und gibt Stil- und Formatierungsanweisungen.

## Output-Typen und wann sie passen

| Output-Typ | Wann | Ton | Struktur |
|---|---|---|---|
| Klausurgutachten | Klausur, Hausarbeit, Lernmaterial | Gutachtenstil (Konjunktiv im Obersatz) | Vier-Schritt je TBM; Zwischenergebnis |
| Kurzgutachten / Memo | Interne Prüfung; erste Einschätzung | Sachlich, juristisch | Kurzlage, Prüfpfad, Ergebnis, offene Punkte |
| Klageschrift / Schriftsatz | Einreichung beim Gericht | Urteilsstil (Ergebnis zuerst) | Rubrum, Antrag, Begründung, Beweisangebote |
| Mandantenbrief | Kommunikation mit Mandant | Alltagssprache (→ output-alltagssprache-de) | Kurzzusammenfassung, Handlungsaufforderung, Hinweis |
| Subsumtionstabelle | Mehrere TBM oder mehrere Parteien | Tabellarisch | TBM, Definition, Tatsache, Subsumtion, Ergebnis |
| Checkliste | Vorbereitung, Intake, Mandatsziel | Knappe Aufzählung | Abhakbar; Fristen; Zuständigkeiten |
| Vermerk / Aktenvermerk | Interne Dokumentation | Sachlich, komprimiert | Datum, Sachverhalt, Prüfung, Ergebnis, nächste Schritte |
| Redline / Änderungsmarkierung | Vertragsprüfung, Entwurfsüberarbeitung | Kommentar-Ton | Track-Changes-Stil; Begründung je Änderung |
| Fremdsprachig | Internationale Mandanten | Englisch / Französisch | → output-fremdsprachig-en-fr |

## Entscheidungsbaum Output-Wahl

```
Wer liest den Output?
├─ Gericht → Schriftsatz (Urteilsstil; § 253 ZPO-Konformität)
├─ Mandant ohne Jurastudium → Mandantenbrief (Alltagssprache)
├─ Anwalt intern → Memo oder Vermerk (Gutachtenstil kurz)
├─ Klausurbetreuer → Gutachten (Vollgutachtenstil)
├─ Mehrere TBM / Parteien → Tabelle
└─ Checkliste für Intake/Routing → Checkliste
```

## Subsumtion — Output-Stil-Regeln

**Voller Gutachtenstil:**
- Memo, Hausarbeit, Klausur, gerichtliches Gutachten.
- Vier-Schritt-Schema (Obersatz, Definition, Subsumtion, Ergebnis) pro TBM.
- Konjunktiv im Obersatz; Indikativ in Subsumtion und Zwischenergebnis.

**Urteilsstil (Kurzgutachten / Schriftsatz):**
- Deduktiver Stil: "Die Klage ist begründet, weil ..."
- Kein Konjunktiv im Einstieg.
- Begründung folgt, nicht vorangehend.

**Subsumtionstabelle:**
- Mehrstöckige Anspruchsgrundlagen oder mehrere Anspruchsteller/-gegner.
- Spalten: TBM, Definition, Tatsache, Subsumtion, Ergebnis.

**Anti-Pattern:**
- "Hier liegt ein Vertrag vor, weil die Parteien einen Vertrag geschlossen haben" → Zirkelschluss.
- Statt dessen: "Hier liegt ein Vertrag iSd § 145 BGB vor, weil A am TT.MM.JJJJ ein Angebot iSd § 145 BGB abgegeben hat (Tatsachen) und B am TT.MM.JJJJ durch Erklärung Y angenommen hat (§ 147 BGB)."

## Kaltstart

Wenn Material vorliegt, arbeite zuerst mit dem Material. Stelle nur Rückfragen, die für die nächste Weiche nötig sind:

1. Wer fragt in welcher Rolle?
2. Was ist das gewünschte Ergebnis?
3. Gibt es Fristen, Termine, Zustellungen, Zahlungen oder Sanktionen?
4. Welche Unterlagen, Daten oder Belege liegen bereits vor?

## Arbeitsworkflow

1. Rolle, Ziel, Frist und Unterlagenlage in höchstens fünf Fragen klären.
2. Output-Typ anhand der Entscheidungsmatrix bestimmen.
3. Stil- und Strukturanweisungen für den gewählten Output-Typ anwenden.
4. Passende Spezialskills vorschlagen.
5. Ein sofort nutzbares Ergebnis erzeugen.

## Output-Standard

- Kurzbild: worum es geht, was gesichert ist, was offen ist.
- Output-Typ-Empfehlung mit Begründung.
- Fertiger Entwurf im gewählten Format.
- Konkreter nächster Schritt mit Frist, Zuständigkeit und Unterlagen.

## Quellenregel

- Normen live prüfen: gesetze-im-internet.de.
- Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle.
- Keine Blindzitate. Paywall-Literatur nur mit Nutzerquelle.
- Unsicherheiten und Annahmen ausdrücklich markieren.

## Qualitäts-Hardening

- Arbeite aktennah: Tatsachen, Belege, Fristen, Zuständigkeit und gewünschtes Arbeitsprodukt zuerst klären.
- Keine Rechtsprechung aus Modellwissen zitieren. Jede Entscheidung vor Ausgabe absichern.
- Wenn eine Quelle, Randnummer, Behördenpraxis oder Frist nicht sicher geprüft ist, sichtbar als Prüfpunkt markieren.
- Ergebnisse so liefern, dass sie sofort weiterverwendbar sind: Kurzbild, Prüfpfad, Risikoampel, Lückenliste und konkrete nächste Schritte.
- Im Memo-Format immer Zwischenergebnis je Tatbestandsmerkmal — leichter zu prüfen und besser zu lesen.
