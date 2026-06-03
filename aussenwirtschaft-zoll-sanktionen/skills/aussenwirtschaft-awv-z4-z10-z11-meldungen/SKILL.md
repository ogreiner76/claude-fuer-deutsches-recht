---
name: aussenwirtschaft-awv-z4-z10-z11-meldungen
description: 'Meldepflichten nach AWV fuer spezifische Formulare Z4 (Direktinvestitionen), Z10 (Wertpapiertransaktionen) und Z11 (Kapitalverkehr/Kredite): Anwendungsbereiche, Schwellenwerte und Fristen. Abgrenzung der Formulare je Transaktionstypus. Output: Korrekt ausgefuellte Z4/Z10/Z11-Meldungen und Ausfuellhilfe.'
---

# AWV Z4/Z10/Z11: Spezifische Bundesbank-Meldungen im Kapitalverkehr

## Mandantenfall

- Unternehmen gewahrt auslaendischem Tochterunternehmen Darlehen; Z11-Meldepflicht pruefen.
- Kapitalanlagegesellschaft kauft Aktien einer US-Gesellschaft; Z10 vs. Z4 klaeren.
- GmbH in Deutschland vergibt Gesellschafterdarlehen an Muttergesellschaft im Ausland.

## Erste Schritte

1. Transaktionstyp einordnen: Direktinvestition (Z4), Wertpapier (Z10) oder Darlehen/Kapitalverkehr (Z11).
2. Meldepflichtige Schwellenwerte pruefen (§ 67 AWV, spezifische Regelung je Formular).
3. Fristen bestimmen: Z4 trimestrisch oder jaehrlich, Z10/Z11 monatlich.
4. Bundesbank-Ausfuellhinweise zum jeweiligen Formular heranziehen.
5. Formular vollstaendig ausfuellen und fristgerecht ueber ExtraNet einreichen.
6. Einreichungsbestaetigung archivieren.

## Rechtsrahmen

- **AWV §§ 56-71**: Gesamtes Meldewesen fuer Kapitalverkehr und Direktinvestitionen.
- **§ 57 AWV**: Z4-Meldepflicht fuer Direktinvestitionen.
- **§ 68 AWV**: Wertpapiermeldungen (Z10).
- **§ 69 AWV**: Kreditgeschaefte mit dem Ausland (Z11).
- **AWG § 13**: Allgemeine Auskunftspflicht.

## Pruef-Raster

- [ ] Transaktionstyp eindeutig klassifiziert?
- [ ] Richtiges Formular (Z4/Z10/Z11) ausgewaehlt?
- [ ] Meldepflicht-Schwellenwert getriggert?
- [ ] Fristen (monatlich/trimestrisch/jaehrlich) bekannt?
- [ ] Meldung elektronisch eingereicht?
- [ ] Archivierung und Bestaetigung gesichert?

## Typische Fallstricke

- Gesellschafterdarlehen und Direktinvestitionsdarlehn koennen sowohl Z4 als auch Z11 ausloesen.
- Wertpapiertransaktionen ueber auslaendische Depotbanken koennen trotzdem Z10-Pflicht ausloesen.
- Fristen Z4 und Z10/Z11 unterscheiden sich; Kumulierung uebersehen.
- Automatische Verrechnung von Forderungen und Verbindlichkeiten loescht Meldepflicht nicht.

## Arbeitsweise

Dieser Skill fuehrt strukturiert durch den Sachverhalt. Beginn mit Tatsachenerhebung:
Beteiligte (Exporteur Importeur Spediteur Zwischenhaendler Bank Endverwender), betroffene Waren
(mit HS-/KN-/TARIC-Code und Dual-Use-Klassifizierung), Laender und Routen, Vertragslage,
behordliche Vorgeschichte und Fristen. Danach Rechtsrahmen abschichten: harte Verbote zuerst,
dann Genehmigungspflichten, Meldeobliegenheiten und Dokumentationsanforderungen.
Sofortmassnahmen benennen (Stop-Ship, Legal Hold, Eskalation) bevor Genehmigungsantrag
oder Offenlegungsstrategie erarbeitet wird. Jede Entscheidung mit Quellenstand und Datum
protokollieren. Offene Punkte bleiben sichtbar und werden nicht als Freigabe getarnt.
Keine Listenlage aus Modellwissen behaupten. Nur amtliche oder frei zugaengliche Quellen
(EUR-Lex, gesetze-im-internet.de, bafa.de, zoll.de) zitieren; Abrufdatum festhalten.

## Schnittstellen zu anderen Skills

Dieser Skill kann mit thematisch benachbarten Skills kombiniert werden, insbesondere:
- Sanktionsscreening und Listenpruefung: `aussenwirtschaft-sanktionsscreening-fuzzy-match`
- Exportkontrollklassifizierung: `aussenwirtschaft-gueterlisten-klassifizierung`
- Freiwillige Offenlegung gegenueber BAFA oder Hauptzollamt: `aussenwirtschaft-freiwillige-offenlegung-bafa-zoll`
- Interne Compliance-Programme: `aussenwirtschaft-icp-kontrollsystem`

## Qualitaetsanforderungen

- Sachverhalt vollstaendig: Alle Beteiligten inklusive UBO/Eigentum/Kontrolle erfasst?
- Normverweise konkret: Artikel und Absatz zitiert, nicht nur Verordnungsnummer?
- Quellenstand datiert: Sanktionslisten, TARIC, Gueltigkeitsdaten dokumentiert?
- Sofortmassnahmen klar: Stop-Ship, Hold, Eskalation explizit benannt wenn Risiko rot?
- Audit-Trail vollstaendig: Entscheidung, Begruendung, Verantwortlicher, Frist?
- Output mandantentauglich: Kein Fachwort ohne Erlaeuterung fuer Compliance und Business?
- Vertraulichkeit: Mandatsgeheimnisse nicht in ungesicherte externe Systeme eingeben.

## Output

Ausgefuellte Z4/Z10/Z11-Formulare, Transaktions-Einstufungstabelle, Fristen-Kalender und Muster-Einreichungsbestaetigung.

## Quellen

- [AWV auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/awv_2013/index.html)
- [Bundesbank Meldewesen Formulare](https://www.bundesbank.de/de/aufgaben/aussenwirtschaft/meldepflichten)
- [AWG auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/awg_2013/index.html)
