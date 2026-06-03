---
name: aussenwirtschaft-cbam-co2-zoll
description: 'Carbon Border Adjustment Mechanism (CBAM): Berechnung der CO2-Abgabe auf Einfuhren kohlenstoffintensiver Waren nach VO (EU) 2023/956. Ab 2026 Pflicht zum Kauf von CBAM-Zertifikaten entsprechend eingebetteter Emissionen. Schnittpunkte mit TARIC und Zollwert. Output: CBAM-Kostenabschaetzung und Zertifikatskalkulation fuer Importplanung.'
---

# CBAM CO2-Zoll: Zertifikatspflicht und Kostenberechnung ab 2026

## Mandantenfall

- Stahlimporteur plant 2026 weiterhin grosse Mengen aus Nicht-EU-Laendern einzufuehren; CBAM-Kosten kalkulieren.
- Aluminium-Importeur fragt, ob Vorleistungsemissionen in Drittland abgezogen werden koennen.
- Elektrizitaetsimporteur aus Schweiz prueft CBAM-Relevanz nach Ende der Uebergangsphase.

## Erste Schritte

1. CBAM-pflichtige Waren nach Anhang I VO 2023/956 und KN-Code pruefen.
2. Eingebettete Emissionen je Tonne Ware ermitteln (Lieferantendaten oder Standardwerte).
3. Anzahl der erforderlichen CBAM-Zertifikate berechnen: Emissionen - angerechnetes Drittland-CO2-Preis.
4. CBAM-Zertifikatspreis (CO2-Preis EU-ETS aktuell) fuer Kostenschaetzung ansetzen.
5. CBAM-Konto als 'Declarant' beim nationalen Zustaendigkeitspunkt anlegen.
6. Jaehrliche Zertifikatsabgabepflicht nach 31. Mai des Folgejahres einplanen.

## Rechtsrahmen

- **Art. 6-7 VO (EU) 2023/956**: CBAM-Zertifikate und Jahreserklarungspflicht.
- **Art. 4-5 VO (EU) 2023/956**: Meldepflichten und Erklaerungspflichten ab 2026.
- **Richtlinie 2003/87/EG (ETS-RL)**: EU-Emissionshandelssystem als Bezugssystem.
- **UZK Art. 56**: CBAM-Abgaben als Teil des Zolltarifs.
- **Art. 9 VO (EU) 2023/956**: Befreiungen fuer Laender mit vergleichbarem CO2-Preis.

## Pruef-Raster

- [ ] Alle CBAM-pflichtigen Waren und KN-Codes korrekt ermittelt?
- [ ] Emissionsintensitaet vom Lieferanten dokumentiert?
- [ ] CBAM-Konto als Declarant eingerichtet?
- [ ] Anrechenbares Drittland-CO2-Preis ermittelt?
- [ ] Kostenabschaetzung und Budget-Planung erstellt?
- [ ] Jahrliche Abgabepflicht nach 31. Mai eingeplant?

## Typische Fallstricke

- Standardwerte koennen hoeher sein als tatsaechliche Emissionen; Lieferantendaten einholen.
- CBAM und Antidumping/Safeguards sind kumulativ anwendbar; Gesamtkosten summieren.
- Drittland-CO2-Preis muss tatsaechlich entrichtet worden sein; Scheinzahlungen nicht anerkannt.
- CBAM-Zertifikatspreis schwankt mit EU-ETS; Kalkulation regelmaessig aktualisieren.

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

CBAM-Kostenkalkulation mit Emissionsschema und Zertifikatsanzahl, Zertifikatspreis-Szenarioanalyse und Jahresplanung, Muster-Erklaerungsformular.

## Quellen

- [VO (EU) 2023/956 auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32023R0956)
- [EU-Kommission CBAM-Info](https://taxation-customs.ec.europa.eu/carbon-border-adjustment-mechanism_en)
- [ETS-Richtlinie 2003/87/EG auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32003L0087)
- [Zoll.de CBAM](https://www.zoll.de/DE/Fachthemen/Steuern/Einfuhrumsatzsteuer/cbam/cbam_node.html)
