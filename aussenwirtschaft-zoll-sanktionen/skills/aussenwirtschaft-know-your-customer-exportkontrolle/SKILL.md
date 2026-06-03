---
name: aussenwirtschaft-know-your-customer-exportkontrolle
description: 'KYC-Prozess fuer Exportkontrollzwecke: Kundenidentifizierung, Endverwender-Screening, UBO-Ermittlung nach VO (EU) 2021/821 und BAFA-Anforderungen, Red-Flag-Analyse bei verdaechtigen Bestellmuster und Sanktionslistenabgleich. Output: KYC-Kundenprofil und Freigabe-/Sperrentscheidung.'
---

# Know Your Customer im Exportkontrollkontext: Kundenscreening und Endverwenderidentifizierung

## Mandantenfall

- Neuer Kunde aus UAE bestellt Hochfrequenzelektronik; ungewoehnlich hohe Bestellmenge, Endverwendung unklar.
- Vertrieb hat Stammkunden in Tuerkei; Umgehungsroute nach Russland aus Presseberichten bekannt.
- Forschungspartner in China ist staatliche Universitaet mit militaerischen Verbindungen.

## Erste Schritte

1. Kundenidentitaet vollstaendig verifizieren: Firmenname, Handelsregisternummer, Adresse, UBO.
2. Sanktionslistenscreening aller Parteien und verbundener Unternehmen.
3. Red-Flag-Analyse: Bestellmuster, Mengen, Verwendungszweck, Zahlungsmodalitaeten.
4. Endverwender-Erklaerung oder EUC anfordern und auf Plausibilitaet pruefen.
5. Offene Quellen recherchieren: BAFA-Informationen, US-Denied-Persons-List, Presseberichte.
6. KYC-Kundenprofil erstellen und Entscheidung mit Beleglage dokumentieren.

## Rechtsrahmen

- **Art. 4 VO (EU) 2021/821**: Catch-All bei Kenntnislagen bezueglich militaerischer Endverwendung.
- **BAFA-Merkblatt Red Flags**: Anzeichen fuer Umgehungsversuche.
- **§ 18 AWG**: Strafbarkeit auch bei leichtfertiger Unkenntnis von Risiken.
- **§ 10 GwG**: KYC-Pflichten (gleichzeitig relevant fuer Sanktions-Compliance).
- **VO (EU) 269/2014 Art. 2**: Bereitstellungsverbot fuer gelistete Personen.

## Pruef-Raster

- [ ] Kundenidentitaet vollstaendig und verifiziert?
- [ ] UBO ermittelt und gegen Sanktionslisten geprueft?
- [ ] Red-Flag-Checkliste vollstaendig abgearbeitet?
- [ ] Endverwender-Erklaerung plausibel und konkret?
- [ ] Offene Quellen (Denied Parties, Presse) konsultiert?
- [ ] KYC-Entscheidung mit Datumsstempel und Verantwortlichem dokumentiert?

## Typische Fallstricke

- Stammkunden werden seltener neu gescreent; Situation kann sich aendern.
- Red Flags einzeln unbedenklich, zusammen signifikant (Gesamtbild).
- UAE, Tuerkei, Armenien als bekannte Umgehungslaender erfordern erhoehte Sorgfalt.
- EUC-Formulierung 'Eigenbedarf' ohne Angabe des konkreten Verwendungszwecks ist unzureichend.

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

KYC-Kundenprofil mit UBO-Kette, Red-Flag-Protokoll, Sanktionsscreening-Ergebnis, Endverwender-Bewertung und Freigabe-/Sperrentscheidung.

## Quellen

- [BAFA Red-Flags-Merkblatt](https://www.bafa.de/DE/Aussenwirtschaft/Ausfuhrkontrolle/Dual_Use/dual_use_node.html)
- [VO (EU) 2021/821 auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32021R0821)
- [GwG auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/gwg_2017/index.html)
- [AWG auf gesetze-im-internet.de](https://www.gesetze-im-internet.de/awg_2013/index.html)
