---
name: aussenwirtschaft-exportkontrolle-dual-use
description: 'Dual-Use-Pruefung fuer Gueter, Software und Technologie nach VO (EU) 2021/821 Anhang I und AWG §§ 8 ff.: Gueterklassifizierung, Genehmigungspflicht, Catch-All nach Art. 4, Technologietransfer, BAFA-Genehmigungsantrag ueber ELAN-K2. Abgrenzung zu Rustungsguetern und Handelssanktionen. Output: Klassifizierungsdossier und Genehmigungspfad.'
---

# Dual-Use-Ausfuhrkontrolle: Klassifizierung und Genehmigungspfad

## Mandantenfall

- Maschinenbauunternehmen exportiert CNC-Fraesmaschine nach China; HS-Code liegt in Grauzone der ML-Liste.
- Software-Unternehmen uebertragt Verschluesselungsmodul ueber Cloud-Download an iranischen Kunden.
- Forschungseinrichtung gibt Technologieunterstuetzung an auslaendischen Gastwissenschaftler; Catch-All geprueft?

## Erste Schritte

1. Ware/Software/Technologie technisch vollstaendig beschreiben (Parameter, Spezifikation, Verwendungszweck).
2. Anhang I VO (EU) 2021/821 durchsuchen: alle 10 Kategorien und relevante Eintraege pruefen.
3. KN-Code bestimmen und TARIC-Doppelverwendungshinweise beachten.
4. Catch-All nach Art. 4 VO (EU) 2021/821 pruefen: Bestimmungsland, Endverwender, Kenntnislage.
5. Bei Listentreffer: Allgemeine EU-Genehmigung pruefen, sonst Einzelgenehmigung BAFA via ELAN-K2.
6. Klassifizierungsergebnis und Genehmigungsstatus dokumentieren.

## Rechtsrahmen

- **Art. 3 VO (EU) 2021/821**: Genehmigungspflicht fuer Anhang-I-Gueter.
- **Art. 4 VO (EU) 2021/821**: Catch-All bei WMD-/Militaer-Endverwendung.
- **Anhang I VO (EU) 2021/821**: Dual-Use-Gueterliste (Kategorien 0-9).
- **§ 8 AWV**: Genehmigungsfreie Ausfuhren, Ausnahmen.
- **§ 18 Abs. 1 AWG**: Strafbarkeit bis 5 Jahre bei unerlaubter Ausfuhr.

## Pruef-Raster

- [ ] Alle 10 Kategorien des Anhangs I systematisch durchsucht?
- [ ] Technische Parameter mit Listenschwellenwerten verglichen?
- [ ] KN-Code und TARIC-Hinweise beachtet?
- [ ] Catch-All-Kriterien geprueft (Bestimmungsland, Endverwender, Kenntnislage)?
- [ ] Allgemeine Genehmigung EU001-EU008 anwendbar?
- [ ] Klassifizierung mit technischer Begruendung archiviert?

## Typische Fallstricke

- Reine Beschreibung des Verwendungszwecks ersetzt keine Listenpruefung nach technischen Parametern.
- Catch-All wird haufig unterschaetzt; Red Flags des Endverwenders uebersehen.
- Allgemeine Genehmigungen haben Ausschlusslisten fuer Bestimmungslaender.
- Technologietransfer durch Wissensweitergabe (E-Mail, Schulung) faellt ebenfalls unter Genehmigungspflicht.

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

Klassifizierungsdossier mit Listenpruefung je Kategorie, Catch-All-Ergebnis, Genehmigungspfad (AGG/Einzelgenehmigung) und BAFA-Antragsunterlagen.

## Quellen

- [VO (EU) 2021/821 auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32021R0821)
- [BAFA Dual-Use](https://www.bafa.de/DE/Aussenwirtschaft/Ausfuhrkontrolle/Dual_Use/dual_use_node.html)
- [TARIC-Datenbank EU-Kommission](https://ec.europa.eu/taxation_customs/dds2/taric/taric_consultation.jsp)
- [AWG auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/awg_2013/index.html)
