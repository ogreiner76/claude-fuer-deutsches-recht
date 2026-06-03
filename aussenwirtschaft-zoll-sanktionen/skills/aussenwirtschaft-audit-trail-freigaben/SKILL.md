---
name: aussenwirtschaft-audit-trail-freigaben
description: 'Aufbau und Pflege revisionssicherer Audit-Trails fuer Exportkontroll-Freigaben: Dokumentationsstandards nach AWG § 14 und AWV § 24 (Aufbewahrungsfristen) sowie Anforderungen der EU-Dual-Use-VO Art. 20. Sichert Freigabeprotokolle, Screening-Logs, Genehmigungsunterlagen und Kommunikation fuer Pruefungssituationen. Output: Audit-Trail-Struktur und Dokumentationsrichtlinie.'
---

# Audit-Trail: Revisionssichere Freigabedokumentation im Aussenhandel

## Mandantenfall

- BAFA prueft Exporteur nach wiederholten Genehmigungsantraegen; Auditoren verlangen vollstaendigen Freigabe-Trail.
- Hauptzollamt fordert bei Aussen-pruefung lueckenlosen Nachweis fuer Sanktionsscreening der letzten 3 Jahre.
- Unternehmensberatung hilft KMU beim Aufbau ersttauglicher Exportkontroll-Dokumentation fuer ICP.

## Erste Schritte

1. Pflicht zur Aufbewahrung von Exportkontrolldokumentation nach AWV § 24 und UZK Art. 51 feststellen (in der Regel 5-10 Jahre).
2. Kategorien von Freigabedokumenten inventarisieren: Screening-Logs, Klassifizierungsdossiers, Genehmigungen, Endverwendungserklaerungen.
3. Elektronisches Ablagesystem mit Zeitstempeln und Versionierung aufbauen.
4. Freigabeprozess mit Vier-Augen-Prinzip und Unterschriftenregelung etablieren.
5. Automatische Backup- und Loeschroutinen gem. DSGVO abstimmen.
6. Regelmaessige interne Audit-Tests zum Vollstaendigkeitsnachweis einplanen.

## Rechtsrahmen

- **AWV § 24**: Aufzeichnungs- und Aufbewahrungspflichten.
- **UZK Art. 51**: Aufbewahrung zollrelevanter Unterlagen (3 Jahre + Verlaehngerung).
- **Art. 20 VO (EU) 2021/821**: Aufzeichnungspflichten des Ausfuehrers.
- **§ 14 AWG**: Auskunftspflichten und Kontrollbefugnisse der Behoerden.
- **GoBD (BMF-Schreiben 2019)**: Grundsaetze ordnungsmaessiger Buchfuehrung fuer digitale Unterlagen.

## Pruef-Raster

- [ ] Aufbewahrungspflicht je Dokument-Kategorie bekannt und umgesetzt?
- [ ] Zeitstempel und Versionierung fuer alle elektronischen Dokumente sichergestellt?
- [ ] Vier-Augen-Prinzip bei Freigabeentscheidungen dokumentiert?
- [ ] Zugriffsberechtigungen und Protokollierung eingerichtet?
- [ ] Backup und Wiederherstellbarkeit getestet?
- [ ] DSGVO-Kompatibilitaet der Langzeitarchivierung sichergestellt?

## Typische Fallstricke

- Papier-Dokumente ungeschuetzt archiviert; im Pruefungsfall nicht auffindbar.
- Screening-Logs ohne Datum oder Quellangabe sind als Nachweis wertlos.
- Zugriffsberechtigungen nicht protokolliert; Manipulationsrisiko im Audit.
- Aufbewahrungsfristen je Dokumenttyp verschieden; pauschale 5-Jahres-Regel reicht nicht.

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

Audit-Trail-Konzept mit Dokumentenkategorien und Aufbewahrungsfristen, Prozess-Flussdiagramm, Muster-Freigabeprotokoll und Pruefungs-FAQ fuer Auditoren.

## Quellen

- [AWV auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/awv_2013/index.html)
- [AWG auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/awg_2013/index.html)
- [VO (EU) 2021/821 Art. 20 auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32021R0821)
- [UZK Art. 51 auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32013R0952)
- [BAFA Kontrollpflichten](https://www.bafa.de/DE/Aussenwirtschaft/Ausfuhrkontrolle/ausfuhrkontrolle_node.html)
