---
name: aussenwirtschaft-internal-investigation-aussenwirtschaft
description: 'Interne Ermittlung bei Verdacht auf Verstoss gegen Exportkontroll- oder Sanktionsrecht: Sicherung digitaler und physischer Beweise (Legal Hold), Mitarbeiterbefragungen, Compliance-Bericht, Schadensquantifizierung und Weichenstellung fuer freiwillige Offenlegung oder Verteidigung. Output: Investigation-Protokoll und Abschlussberichtsgliederung.'
---

# Interne Ermittlung bei Exportkontroll- und Sanktionsverstoss

## Mandantenfall

- Hinweisgeber meldet, dass Exportabteilung systematisch falsche HS-Codes zur Umgehung von Genehmigungspflichten verwendet.
- Zollpruefung deckt auf, dass drei Sendungen ohne BAFA-Genehmigung exportiert wurden; Umfang unklar.
- Banktransfer an russische Gegenpartei; Compliance identifiziert Sanktionspotenzial erst nach Ausfuehrung.

## Erste Schritte

1. Legal Hold sofort einrichten: E-Mails, ATLAS-Daten, ERP-Exportdaten, interne Kommunikation sichern.
2. Untersuchungsauftrag und Untersuchungsrahmen durch Geschaeftsfuehrung oder Aufsichtsrat freigeben.
3. Untersuchungsteam zusammenstellen: externer Rechtsanwalt, interner Compliance, IT-Forensik.
4. Sachverhaltserstellung durch strukturierte Befragungen und Dokumentenanalyse.
5. Schadensquantifizierung: Anzahl Verstoesse, Zeitraum, beteiligte Personen, betroffene Gueter und Werte.
6. Abschlussbericht mit Empfehlung: freiwillige Offenlegung, Verteidigung oder beides.

## Rechtsrahmen

- **§ 22 Abs. 4 AWG**: Strafmilderung bei freiwilliger Offenlegung.
- **§ 130 OWiG**: Aufsichtspflichtverletzung, Unternehmensgeldbuse.
- **§ 97 StPO**: Beschlagnahmefreiheit anwaltlicher Unterlagen.
- **§ 14 AWG**: Auskunftspflichten gegenueber Behoerden.
- **DSGVO Art. 6**: Rechtsgrundlage fuer Mitarbeiterdatenzugriff bei Investigation.

## Pruef-Raster

- [ ] Legal Hold umfasst alle relevanten Datenkategorien?
- [ ] Untersuchungsauftrag schriftlich erteilt und Rahmen definiert?
- [ ] Rechtsanwaltsprivileg fuer Investigation-Unterlagen sichergestellt?
- [ ] Mitarbeiterbefragungen mit Belehrungsprotokoll durchgefuehrt?
- [ ] Datenschutzrechtliche Grundlage fuer Datenzugriff geprueft?
- [ ] Schadensquantifizierung vollstaendig und belegbar?
- [ ] Abschlussbericht mit konkreter Empfehlung versehen?

## Typische Fallstricke

- Legal Hold zu spaet eingeleitet; Beweise ueberschrieben oder Datenschutzloeschfristen abgelaufen.
- Interne Mitarbeiter untersuchen sich selbst; Interessenkonflikt.
- Investigation-Berichte ohne Anwaltsprivileg koennen von Behoerden beschlagnahmt werden.
- Mitarbeiter ohne Belehrung ueber Aussageverweigerungsrecht befragt; spaetere Verwertungsprobleme.

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

Legal-Hold-Anordnung, Investigation-Protokoll mit Befragungsprotokollen, Schadenstabelle, Abschlussbericht-Gliederung und Empfehlung freiwillige Offenlegung oder Verteidigung.

## Quellen

- [AWG auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/awg_2013/index.html)
- [OWiG auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/owig_1968/index.html)
- [BAFA Exportkontrolle](https://www.bafa.de/DE/Aussenwirtschaft/Ausfuhrkontrolle/ausfuhrkontrolle_node.html)
- [Zoll.de Zollrecht](https://www.zoll.de/DE/Fachthemen/Zoelle/zoll_node.html)
