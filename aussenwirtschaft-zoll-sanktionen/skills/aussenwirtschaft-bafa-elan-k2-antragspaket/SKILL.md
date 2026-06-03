---
name: aussenwirtschaft-bafa-elan-k2-antragspaket
description: 'Aufbau und Einreichung eines vollstaendigen Genehmigungsantrags ueber das BAFA-Online-System ELAN-K2: technische Gueterbeschreibung nach Anhang I VO (EU) 2021/821 oder nationaler Gueterliste, Endverwendungserklaerung (EUC), Lieferplandokument und begleitende Compliance-Nachweise. Output: Vollstaendiges Antragspaket fuer BAFA-Genehmigungsantrag.'
---

# BAFA ELAN-K2: Vollstaendiges Genehmigungsantragspaket aufbauen

## Mandantenfall

- Maschinenbauunternehmen muss BAFA-Einzelgenehmigung fuer Lieferung von CNC-Maschinen nach Russland (vor Embargo) einholen.
- Elektronikexporteur reicht Dual-Use-Genehmigungsantrag ein; BAFA fordert Nachbesserung der EUC.
- Ruestungslieferant stellt Sammelgenehmigungsantrag fuer laufende Lieferbeziehung in NATO-Partnerland.

## Erste Schritte

1. Gueterlisten-Code und einschlaeige Genehmigungsnorm (VO 2021/821 oder AWV) bestimmen.
2. ELAN-K2-Systemzugang einrichten; Benutzerkonto und Vollmachten klaeren.
3. Endverwendungserklaerung (EUC) vom Endverwender unterschrieben einholen und pruefen.
4. Technische Spezifikation mit Gueterlisten-Referenz und Leistungsparametern aufbereiten.
5. Lieferplan, Wert und Mengenangaben vollstaendig eintragen.
6. Antrag vollstaendig auf Luecken pruefen; BAFA-Merkblatt Antragstellung als Checkliste nutzen.

## Rechtsrahmen

- **Art. 10 VO (EU) 2021/821**: Voraussetzungen der Einzelgenehmigung.
- **AWV §§ 8-12**: Nationale Genehmigungsverfahren.
- **BAFA-Merkblatt ELAN-K2**: Formale Antragsanforderungen.
- **Art. 9 VO (EU) 2021/821**: ICP-Voraussetzungen als Antragsbestandteil.
- **§ 18 AWG**: Strafbarkeit bei unerlaubter Ausfuhr ohne Genehmigung.

## Pruef-Raster

- [ ] Gueterlisten-Code eindeutig und korrekt?
- [ ] EUC vollstaendig, unterschrieben und authentisch?
- [ ] Technische Beschreibung mit Leistungsparametern vollstaendig?
- [ ] Lieferplan mit Datum, Menge, Wert vollstaendig?
- [ ] Antrag ohne Lueckenfelder eingereicht?
- [ ] Begleitdokumente in ELAN-K2 hochgeladen?

## Typische Fallstricke

- Unvollstaendige EUC ist haeufigster Rueckweisungsgrund; Authentizitaet des Unterschreibers pruefen.
- Technische Parameter nicht auf Listeneintrag abgestimmt; keine pauschale Beschreibung.
- Sammelgenehmigungsantrag erfordert abweichende Formularwahl von Einzelantrag.
- Lieferplan muss realistisch sein; spaetere Aenderungen erfordern Nachtrag.

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

Vollstaendiges Antragspaket: EUC-Vorlage, technische Beschreibungstemplate, ELAN-K2-Checkliste und Einreichungsprotokoll.

## Quellen

- [BAFA ELAN-K2 Portal](https://elan-k2.bafa.de)
- [BAFA Ausfuhrkontrolle Genehmigungen](https://www.bafa.de/DE/Aussenwirtschaft/Ausfuhrkontrolle/ausfuhrkontrolle_node.html)
- [VO (EU) 2021/821 auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32021R0821)
- [AWV auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/awv_2013/index.html)
