---
name: forderungsverzicht-besserungsschein
description: Erzeugt eine Forderungsverzichtsvereinbarung mit Besserungsschein. Glaeubiger verzichtet auf Forderung — bei Wiedererstarken der Zahlungsfaehigkeit der Schuldnerin lebt die Forderung wieder auf. Effekt im insolvenzrechtlichen Status die verzichtete Forderung wird nicht passiviert. Steuerliche Folge beim Schuldner Ertragsbuchung (Sanierungserloes Sanierungsgewinn § 3a EStG bei Sanierungsbedarf). Beim Glaeubiger Forderungsausfall ggf abzugsfaehig.
---

# Forderungsverzicht mit Besserungsschein

## Wirkung

Glaeubiger verzichtet auf eine Forderung. Effekt:

- **Im Status**: Forderung entfaellt aus den Passiva. Bilanzbild verbessert sich.
- **Liquiditaet**: keine direkte Liquiditaetszuflussverbesserung (die Forderung war ggf ohnehin nicht in den naechsten 12 Monaten zur Zahlung faellig).
- **Bilanz**: Ertrag (Sanierungserloes).

Mit **Besserungsschein**: Wenn die Schuldnerin spaeter wieder zahlungsfaehig wird lebt die Forderung wieder auf. Der Verzicht ist also bedingt.

## Anwendungsfall

- Bank verzichtet auf Teil-Tilgung eines Darlehens.
- Lieferant verzichtet auf Forderung mit Besserungsschein als Sanierungsbeitrag.
- Hauptgesellschafter verzichtet auf Forderung (statt Rangruecktritt).

## Steuerliche Folgen

### Beim Schuldner

Ertragsbuchung Sanierungserloes. **Sanierungsgewinn § 3a EStG** kann steuerbefreit sein wenn die Voraussetzungen (Sanierungsabsicht Sanierungsfaehigkeit Sanierungseignung Glaeubigergleichbehandlung) erfuellt sind.

Vor Unterzeichnung **steuerliche Beratung** zwingend.

### Beim Glaeubiger

Forderungsausfall regelmaessig als Betriebsausgabe abzugsfaehig. Bei Banken Wertberichtigung. Steuerlich vor Verzicht pruefen lassen.

## Mustervorlage

```
FORDERUNGSVERZICHTSVEREINBARUNG MIT BESSERUNGSSCHEIN

zwischen

  [Vor- und Nachname Glaeubiger]
  [Anschrift]
  - im Folgenden „der Glaeubiger" -

und

  [Firma der Schuldnerin]
  vertreten durch [Geschaeftsfuehrer]
  [Anschrift]
  HRB [...] AG [...]
  - im Folgenden „die Schuldnerin" -

1. Praeambel

Der Glaeubiger ist Inhaber folgender Forderung gegen die Schuldnerin:

  [Bezeichnung der Forderung]
  Hauptforderung [Betrag] EUR
  zuzueglich Zinsen
  zum [Stichtag] insgesamt [Gesamtbetrag] EUR

Die Schuldnerin befindet sich in einer angespannten wirtschaftlichen Lage 
und hat eine Fortbestehensprognose nach § 19 Abs. 2 InsO erstellt. Mit
Sanierungsbeitrag durch den Glaeubiger ist die Prognose positiv.

2. Verzicht

2.1 Der Glaeubiger verzichtet hiermit gegenueber der Schuldnerin auf die 
oben bezeichnete Forderung in voller Hoehe einschliesslich Zinsen und 
Nebenforderungen.

2.2 Die Forderung erlischt im Status der Schuldnerin und ist in der 
insolvenzrechtlichen Status-Aufstellung nicht mehr zu passivieren.

3. Besserungsschein

3.1 Der Verzicht ist bedingt durch das Wiedererstarken der Zahlungsfaehigkeit 
der Schuldnerin.

3.2 Die Forderung lebt wieder auf wenn

  a) die Schuldnerin im Jahresabschluss ein positives Eigenkapital aufweist 
     oder
  b) die Schuldnerin in einem Geschaeftsjahr einen Jahresueberschuss von mehr 
     als [X] EUR erwirtschaftet oder
  c) der Glaeubiger bei nachhaltiger Verbesserung der wirtschaftlichen Lage 
     in Textform die Wiederaufnahme verlangt.

3.3 Der Rueckzahlungsbetrag betraegt im Fall des Wiederauflebens

  - hoechstens den urspruenglichen Forderungsbetrag,
  - mindestens [X] Prozent des verfuegbaren Eigenkapitals des Folgejahres,
  - wird in Raten ueber [N] Monate getilgt.

3.4 Die Besserungsklausel laeuft fuer [N] Jahre ab Unterzeichnung. Nach 
Ablauf entfaellt die Wiederauflebensmoeglichkeit endgueltig.

4. Steuerliche Hinweise

Die Parteien sind sich bewusst dass dieser Verzicht beim Schuldner Ertrag 
ausloest. Vor Unterzeichnung wurde steuerlicher Rat eingeholt.

5. Form und Wirksamkeit

5.1 Diese Vereinbarung ist beidseitig unterzeichnet wirksam.

5.2 Aenderungen und Ergaenzungen beduerfen der Schriftform.

5.3 Gerichtsstand: [Sitz der Schuldnerin].

[Ort], [Datum]

___________________________
[Glaeubiger]


___________________________
[Geschaeftsfuehrer]
fuer die Schuldnerin
```

## Hinweise

### Echtheit der Sanierungsabsicht

Wird der Forderungsverzicht spaeter als Scheingeschaeft angesehen (z. B. weil keine ernsthafte Sanierungsabsicht vorlag) kann er anfechtbar sein.

### Glaeubigergleichbehandlung

Bei Sanierungsverzicht ist auf Glaeubigergleichbehandlung zu achten. Wenn nur einzelne Glaeubiger verzichten und andere nicht ist das in Ordnung — solange der Vorgang nicht als Begueneten-Bezugnahme zu Lasten der nicht-verzichtenden Glaeubiger zu werten ist.

### Besserungsschein-Trigger genau definieren

Der Trigger fuer das Wiederaufleben muss objektiv und nachpruefbar sein. Klauseln wie „wenn es uns wieder besser geht" sind ungeeignet.

## Ausgabe

- `forderungsverzicht-besserungsschein-<glaeubiger>.docx`.
- Steuerliche Pruefer-Flag — Steuerberater einbinden.
- Statusupdate (Skill `bilanzieller-status-aufnehmen`): Forderung entfaellt aus den Passiva.
- Eintrag im Sanierungsbausteine-Tracker.
