---
name: aussenwirtschaft-aml-kyc-sanktionen
description: 'Schnittstelle von AML/KYC-Pflichten und Sanktionsrecht: Risikobasierte Kundenpruefung nach GwG (§§ 10-17 GwG) kombiniert mit Sanktionsscreening nach EU-Finanzsanktionsrecht (VO 269/2014 und andere). Identifizierung wirtschaftlich Berechtigter (UBO), Pruefung von PEP-Status und Hochrisikoindikatoren. Output: KYC-Dossier mit Sanktionsabklaerungsvermerk und Eskalationspfad.'
---

# AML/KYC und Sanktionen: Risikobasierte Kundenpruefung und Sanktionsscreening

## Mandantenfall

- Bank erhalt Zahlungsauftrag aus UAE mit unklaren UBO-Angaben; Fragestellung Sanktions-Treffer moeglich?
- Handelsunternehmen onboardet neuen Kunden aus der Tuerkei; interne KYC-Abteilung fordert enhanced due diligence.
- Finanzdienstleister prueft, ob Russe mit Oligarchen-Nahbeziehung unter Art. 2 VO 269/2014 faellt.

## Erste Schritte

1. Identifizierungspflicht ausloesen: Ist Geschaeftsbeziehung gemaess §§ 10 GwG begruendet?
2. UBO-Ermittlung nach § 3 GwG und Art. 3 Nr. 6 4. EU-GwRL (AMLD4): Eigentums- und Kontrollstrukturen bis zum natuerllichen Endbeguenstigten aufloesen.
3. Sanktionsscreening in konsolidierter EU-Finanzsanktionsliste (OFAC, UK-HMT optional ergaenzend).
4. PEP-Status pruefen (§ 1 Abs. 12 GwG) und erweiterte Sorgfaltspflichten aktivieren.
5. Risikobewertung nach geldwaescherechtlicher Risikoanalyse erstellen.
6. Entscheidung: Kundenbeziehung freigeben, einschraenken oder ablehnen; Meldung an FIU pruefen.

## Rechtsrahmen

- **§§ 10-17 GwG**: Kundensorgfaltspflichten, UBO-Ermittlung, Hochrisikofaelle.
- **Art. 2 VO (EU) 269/2014**: Bereitstellungsverbot fuer gelistete Personen/Unternehmen (Russland-Sanktionen).
- **Art. 11 VO (EU) 269/2014**: Meldepflicht bei eingefrorenen Geldern.
- **§ 43 GwG**: Verdachtsmeldepflicht an FIU.
- **Zahlungsdiensteaufsichtsgesetz (ZAG)**: Erweiterter Anwendungsbereich fuer Zahlungsdienstleister.

## Pruef-Raster

- [ ] UBO vollstaendig und belegt ermittelt (25 %-Schwelle und Kontrollpruefung)?
- [ ] Sanktionsscreening mit Trefferprotokoll durchgefuehrt?
- [ ] PEP-Status und Hochrisikoindikatoren bewertet?
- [ ] Abweichende/unklare Angaben des Kunden dokumentiert?
- [ ] Risikoklasse korrekt eingestuft und Massnahmen angemessen?
- [ ] Meldepflicht an FIU geprueft?

## Typische Fallstricke

- Indirektes Eigentum ueber Offshore-Strukturen wird unterschaetzt; nur direkte Anteilseigner pruefen reicht nicht.
- 'Fuzzy Match' bei abweichender Schreibweise des Namens fuehrt zu Nichtentdeckung.
- PEP-Status laeuft nach Amt-Ende weiter (mindestens 12 Monate); kein automatischer Wegfall.
- Sanktions- und GwG-Pruefung werden organisatorisch getrennt durchgefuehrt und kommunizieren nicht.

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

KYC-Dossier mit UBO-Mapping, Sanktions-Trefferlog, PEP-Klassifizierung, Risikoampel und Freigabe-/Ablehnungsvermerk.

## Quellen

- [GwG auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/gwg_2017/index.html)
- [VO (EU) 269/2014 konsolidiert auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32014R0269)
- [EU Finanzsanktionsliste (FSDB)](https://eeas.europa.eu/topics/sanctions-policy/8442/consolidated-list-sanctions_en)
- [BaFin Merkblatt Geldwaeschegesetz](https://www.bafin.de/DE/Aufsicht/Geldwaeschebekaempfung/geldwaeschebekaempfung_node.html)
- [AWG auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/awg_2013/index.html)
