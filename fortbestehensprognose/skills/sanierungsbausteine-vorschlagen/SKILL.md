---
name: sanierungsbausteine-vorschlagen
description: Wenn die Fortbestehensprognose ohne Massnahmen negativ oder knapp positiv ist schlaegt dieser Skill konkrete Sanierungsbausteine vor. Auswahl Patronatserklaerung hart Comfortletter Gesellschafterdarlehen mit Rangruecktritt Stundungsvereinbarungen Forderungsverzichte mit Besserungsschein Eigenkapitalmassnahme StaRUG-Restrukturierungsplan. Empfehlungsmatrix nach Effekt und Umsetzungszeit. Empfiehlt konkret welche Dokumente erzeugt werden sollten (Skills patronatserklaerung-extern-hart-erzeugen gesellschafterdarlehen-rangruecktritt stundungsanfrage-glaeubiger).
---

# Sanierungsbausteine vorschlagen

## Auswahlmatrix

Aus der Zusammenfuehrung (Skill `fortbestehensprognose-zusammenfuehren`) ergibt sich die Luecke zwischen aktueller Liquiditaet / Bilanzbasis und der Schwelle zur positiven Fortbestehensprognose. Die Bausteine sind nach Effekt und Umsetzungszeit zu waehlen.

| Baustein | Effekt | Umsetzungszeit | Skill |
|---|---|---|---|
| Externe harte Patronatserklaerung | Liquiditaets- und Bilanzeffekt sofort | 1 bis 2 Tage | patronatserklaerung-extern-hart-erzeugen |
| Comfortletter (intern/weich) | Symbolisch / Reputation; kein Bilanzeffekt | 1 Tag | comfortletter-weich-erzeugen |
| Gesellschafterdarlehen mit Rangruecktritt | Bilanzeffekt sofort; Liquiditaet bei Auszahlung | 3 bis 7 Tage notariell | gesellschafterdarlehen-rangruecktritt |
| Forderungsverzicht mit Besserungsschein | Bilanzeffekt sofort | 5 bis 14 Tage | forderungsverzicht-besserungsschein |
| Stundung Forderung (Lieferant Bank) | Liquiditaetseffekt sofort | 5 bis 10 Tage | stundungsanfrage-glaeubiger |
| Kapitalerhoehung Gesellschafter | Bilanz- und Liquiditaetseffekt | 14 bis 28 Tage notariell | (Plugin gesellschaftsrecht) |
| Sale-and-Lease-back | Liquiditaet einmalig | 14 bis 30 Tage | externe Bank |
| Kreditlinienerhoehung | Liquiditaet sofort wenn zugesagt | je nach Bank | externe Bank |
| StaRUG-Restrukturierungsplan | Vielschichtig — bei drohender Zahlungsunfaehigkeit | mehrere Wochen | Plugin insolvenzrecht / StaRUG-Berater |

## Pruefraster pro Baustein

### Externe harte Patronatserklaerung

- **Patron** muss bonitaer sein und sich gegenueber dem Begueneten **direkt** verpflichten.
- Patronatserklaerung **schriftlich** mit **klarem Verzicht auf Insolvenzanforderung** im Insolvenzfall.
- Mehrwert: Forderung des Patrons gegen sich selbst (im Insolvenzfall) entlastet den Status.
- Skill `patronatserklaerung-extern-hart-erzeugen` mit Mustervorlage.

### Comfortletter (weich)

- **Nicht** ausreichend fuer die Fortbestehensprognose-Bilanzentlastung.
- Kann aber **Liquiditaetsunterstuetzung** signalisieren (z. B. an Bank).
- Skill `comfortletter-weich-erzeugen`.

### Gesellschafterdarlehen mit qualifiziertem Rangruecktritt

- Bestehendes Gesellschafterdarlehen wird mit **qualifiziertem Rangruecktritt** versehen.
- Im Status nicht passiviert (§ 19 Abs. 2 S. 2 InsO).
- BGH-Anforderungen an die Rangruecktrittsformulierung beachten (BGH II ZR 18/19).
- Form: **notariell oder mit Schriftform unterzeichnet von beiden Parteien**.
- Skill `gesellschafterdarlehen-rangruecktritt`.

### Forderungsverzicht mit Besserungsschein

- Glaeubiger verzichtet auf Forderung — im Insolvenzfall waere er ohnehin Auseinandersetzungsglaeubiger.
- **Besserungsschein** lebt die Forderung wieder auf wenn das Unternehmen wieder zahlungsfaehig.
- Steuerliche Folgen pruefen (Ertrag aus Forderungsverzicht — Sanierungsklausel § 3a EStG).
- Skill `forderungsverzicht-besserungsschein`.

### Stundungen

- Lieferanten Bank Steuern (Achtung: Steuerstundung § 222 AO) Sozialversicherung (sehr restriktiv).
- **Schriftlich** und mit **klarem Termin**.
- Skill `stundungsanfrage-glaeubiger`.

### Kapitalerhoehung

- Bareinlage durch Gesellschafter oder Sacheinlage (mit Sachgruendungsbericht).
- Notarurkunde Handelsregistereintragung.
- Plugin `gesellschaftsrecht` (Skill kapitalerhoehung).

### Sale-and-Lease-back

- Verkauf eines Vermoegenswerts (Maschine Grundstueck) an Leasing-Geber mit anschliessendem Leasing.
- Liquiditaetseffekt einmalig.
- Folgekosten (Leasingraten) im Liquiditaetsplan beruecksichtigen.

### StaRUG-Restrukturierungsplan

- Nur bei **drohender** Zahlungsunfaehigkeit (§ 18 InsO mit Prognose 24 Monate) — nicht bei akuter Zahlungsunfaehigkeit oder Ueberschuldung.
- Restrukturierungsbeauftragter wird vom Gericht bestellt.
- Plan kann **mit Mehrheit der Glaeubiger** durchgesetzt werden.
- Externe Begleitung durch StaRUG-Anwalt notwendig.

## Empfehlungslogik

```yaml
empfehlungen:
  zur-erreichung-positive-prognose:
    pflicht:
      - baustein: patronatserklaerung-extern-hart
        umfang: 200000 EUR
        patron: Hauptgesellschafter
        skill: patronatserklaerung-extern-hart-erzeugen
        prioritaet: kritisch
        umsetzung-bis: 2026-05-27
    
    empfohlen:
      - baustein: stundungsanfrage-glaeubiger
        anzahl: 5 Lieferanten
        skill: stundungsanfrage-glaeubiger
        prioritaet: hoch
        umsetzung-bis: 2026-06-15
      
      - baustein: gesellschafterdarlehen-rangruecktritt
        umfang: 120000 EUR bestehend
        skill: gesellschafterdarlehen-rangruecktritt
        prioritaet: hoch
        umsetzung-bis: 2026-05-25 notariell
    
    optional-bei-eskalation:
      - baustein: forderungsverzicht-besserungsschein
        umfang: 50000 EUR Bank
        skill: forderungsverzicht-besserungsschein
        prioritaet: mittel
        umsetzung-bis: 2026-06-30

  ergebnis-nach-massnahmen:
    bilanzbasis-vorher: positiv 133000 EUR
    bilanzbasis-nach-massnahmen: positiv 333000 EUR (zusaetzlich Patronage 200000)
    liquiditaet-vorher-stress: negativ
    liquiditaet-nach-massnahmen-stress: positiv
    gesamtprognose: positiv mit Massnahmen
```

## Zeitliche Reihenfolge

- **Sofort** (binnen Tagen): Patronatserklaerung Rangruecktritt
- **Innerhalb Wochen** (drei Wochen Frist § 15a InsO bei Zahlungsunfaehigkeit beachten): Stundungen Forderungsverzichte
- **Innerhalb Frist § 15a InsO Sechs Wochen**: alle Massnahmen verbindlich
- **Bei Frist-Ueberschreitung**: keine zusaetzliche Massnahme mehr ausreichend — sofort Insolvenzantrag (Skill `wenn-prognose-negativ-naechste-schritte`).

## Ausgabe

- `sanierungsbausteine-empfehlung.md` mit konkreter Massnahmenliste je Prioritaet.
- Naechste Skill-Verlinkungen je Massnahme.
- Eintrag in Tagesnotizen zur Umsetzungskontrolle.
- Stichtag-Wiedervorlage in zwei Wochen zur Pruefung der tatsaechlichen Umsetzung.
