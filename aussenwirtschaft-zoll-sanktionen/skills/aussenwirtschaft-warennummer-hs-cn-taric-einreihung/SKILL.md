---
name: aussenwirtschaft-warennummer-hs-cn-taric-einreihung
description: 'Wareneinreihung nach Harmonisiertem System (HS) Kombinierter Nomenklatur (KN) und TARIC: Anwendung der Allgemeinen Vorschriften (AV 1-6) ErlBem und Einreihungsverordnungen. Typische Problemfelder wie Sets Teile Zubehoer Konfektionierung und Mischprodukte. Output: Einreihungsvermerk mit Normbegründung und TARIC-Abfrage-Dokumentation.'
---

# Wareneinreihung HS/KN/TARIC: Allgemeine Vorschriften und Problemfelder

## Mandantenfall

- Importeur meldet Elektromotoren unter falscher KN-Nummer an; Hauptzollamt stellt abweichende Einreihung fest.
- Unternehmen fragt ob Set aus Maschine und Ersatzteilen zusammen eingereiht werden muss.
- Lebensmittel-Exporteur muss TARIC-Code fuer verarbeitetes Produkt bestimmen; mehrere KN-Positionen moeglich.

## Erste Schritte

1. Ware vollstaendig beschreiben: Beschaffenheit Zusammensetzung Funktion und Verwendungszweck.
2. AV 1 anwenden: Einreihung nach Wortlaut der Positionen und Anmerkungen.
3. AV 2 bis 6 schrittweise pruefen: unvollstaendige Waren Sets Gemische spezifischere Bestimmung.
4. EZT-online (Elektronischer Zolltarif) und TARIC-Datenbank konsultieren.
5. Erlaeuterungen zur KN (ErlBem) und Einreihungsverordnungen zum HS-Code pruefen.
6. Einreihungsvermerk erstellen mit Normbegruendung und TARIC-Abfrage-Dokumentation.

## Rechtsrahmen

- **VO (EWG) 2658/87 (KN-VO)**: Kombinierte Nomenklatur als EU-Zolltarif.
- **Allgemeine Vorschriften (AV) 1-6 KN**: Einreihungsregeln.
- **HS-Erlaeuterungen (WCO)**: Internationale Auslegungshilfen zum Harmonisierten System.
- **Einreihungsverordnungen EU**: Verbindliche Einreihungsentscheidungen der Kommission.
- **UZK Art. 56**: Zolltarif und Einreihungspflicht des Anmelders.

## Pruef-Raster

- [ ] Ware vollstaendig und technisch beschrieben?
- [ ] AV 1 bis 6 schrittweise angewendet?
- [ ] EZT-online und TARIC konsultiert?
- [ ] ErlBem und Einreihungsverordnungen geprueft?
- [ ] Einreihungsvermerk mit Normbegruendung erstellt?
- [ ] TARIC-Abfrage mit Datum dokumentiert?

## Typische Fallstricke

- Sets und Garnituren werden oft faelschlicherweise aufgeteilt; AV 3 beachten.
- Teile und Zubehoer haben eigene Positionen; Zuordnung zum Hauptprodukt nicht automatisch.
- Software als integraler Bestandteil einer Maschine aendert Einreihung moeglicherweise.
- Beschriftung und Verpackung koennen Einreihung beeinflussen (AV 5).

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

Einreihungsvermerk mit AV-Begruendung, TARIC-Abfrage-Dokumentation mit Datum, Empfehlung fuer vZTA bei Unsicherheiten und Checkliste fuer Folgesendungen.

## Quellen

- [TARIC-Datenbank EU-Kommission](https://ec.europa.eu/taxation_customs/dds2/taric/taric_consultation.jsp)
- [Zoll.de EZT-online](https://www.zoll.de/DE/Fachthemen/Zoelle/Zolltarif/EZT-Online/ezt-online_node.html)
- [KN-VO auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:31987R2658)
- [UZK auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32013R0952)
