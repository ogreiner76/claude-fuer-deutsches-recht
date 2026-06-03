---
name: aussenwirtschaft-endverwendung-endverwender-euc
description: 'Endverwender-Pruefung und End-Use-Certificate (EUC): Identifizierung des tatsaechlichen Endverwenders, Pruefen des Endverwendungszwecks und Authentizitaet der Endverwendungserklaerung nach BAFA-Anforderungen und VO (EU) 2021/821. Besondere Risiken bei Staatsunternehmen, Forschungseinrichtungen und Zwischenhaendlern. Output: EUC-Pruefprotokoll und Vervollstaendigungsanforderung.'
---

# Endverwender-Pruefung und EUC: Authentizitaet und Risikoeinschaetzung

## Mandantenfall

- Exporteur erhalt EUC von unbekannter Firma in Pakistan; Authentizitaet zweifelhaft.
- BAFA fordert Nachweise ueber tatsaechlichen Endverwender; Lieferant hat nur Handelsgesellschaft angegeben.
- Technologie-Transfer an staatliches Forschungsinstitut in sensitivem Land; EUC-Pruefung noetig.

## Erste Schritte

1. EUC-Formular auf Vollstaendigkeit pruefen: Endverwender-Name und -Adresse, Verwendungszweck, Unterschrift und Firmenstempel.
2. Authentizitaetspruefung: Unternehmensregister, Web-Praesenz, Gegencheck mit Handelspartnern.
3. Abgleich der EUC-Angaben mit technischer Spezifikation; plausibel fuer zivilen Verwendungszweck?
4. Red Flags der BAFA-Checkliste abarbeiten: Staatsunternehmen, Ruestungsnaeehe, ungewoehnliche Spezifikation.
5. BAFA-Anfrage an Exporteur oder Nachfrage-Schreiben an Endverwender wenn Luecken.
6. Ergebnis und Entscheidung im Compliance-System dokumentieren.

## Rechtsrahmen

- **Art. 10 Abs. 1 lit. g VO (EU) 2021/821**: EUC als Genehmigungsbestandteil.
- **BAFA-Merkblatt Endverwendung**: Anforderungen an EUC-Inhalt und Authentizitaet.
- **AWG § 9**: Genehmigungsvoraussetzungen inkl. Endverwender-Nachweis.
- **§ 18 AWG**: Strafbarkeit bei Falschangaben zur Endverwendung.
- **Art. 4 Abs. 1 VO (EU) 2021/821**: Catch-All bei Kenntnis militaerischer Endverwendung.

## Pruef-Raster

- [ ] EUC vollstaendig ausgefuellt und unterschrieben?
- [ ] Endverwender-Identitaet verifiziert?
- [ ] Endverwendungszweck plausibel und zivil?
- [ ] Red Flags der BAFA-Checkliste negativ?
- [ ] Dokumentation archiviert und mit Freigabeentscheidung verknuepft?
- [ ] Catch-All-Tatbestand ausgeschlossen?

## Typische Fallstricke

- Zwischenhaendler als angeblicher Endverwender reicht nicht; tatsaechliche Nutzung muss identifizierbar sein.
- Staatlliche Forschungseinrichtungen in Hochrisikolaendern haben oft Dual-Use-Kapazitaeten.
- EUC-Faelschungen durch Lieferanten nehmen zu; Gegenverifizierung ueber unabhaengige Kanaele noetig.
- Nachtraegliche EUC-Einholung nach Lieferung schutzt nicht vor Strafverfolgung.

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

EUC-Pruefprotokoll mit Authentizitaetsnachweis, Red-Flag-Checkliste, Vervollstaendigungs-Anforderungsschreiben und Freigabe-/Sperrprotokoll.

## Quellen

- [VO (EU) 2021/821 auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32021R0821)
- [BAFA Endverwendung und EUC](https://www.bafa.de/DE/Aussenwirtschaft/Ausfuhrkontrolle/Dual_Use/dual_use_node.html)
- [AWG auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/awg_2013/index.html)
- [AWV auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/awv_2013/index.html)
