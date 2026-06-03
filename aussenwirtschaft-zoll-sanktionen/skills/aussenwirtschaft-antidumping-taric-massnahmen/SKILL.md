---
name: aussenwirtschaft-antidumping-taric-massnahmen
description: 'Identifizierung und Anwendung handelspolitischer Schutzmassnahmen (Antidumping, Ausgleichszoll, Safeguards) im TARIC-System: Zuordnung der KN-Position, Ursprungsland und Hersteller zu geltenden Massnahmen. Ermittelt TARIC-Zusatzcode, Preisverpflichtungen und Schwellenwerte fuer relevante Waren. Output: TARIC-Massnahmen-Uebersicht mit Handlungsempfehlung fuer Zollabfertigung.'
---

# TARIC-Massnahmen: Antidumping und Ausgleichszoelle in der Zollabfertigung

## Mandantenfall

- Zollagent findet beim Import von Stahlrohren aus China drei konkurrierende Massnahmen-Codes in TARIC.
- Importeur zahlt falsche Antidumping-Zoelle weil Hersteller-TARIC-Code veraltet.
- Unternehmen importiert Fahrraeder aus Kambodscha; Frage ob EU-Antiumgehungsmassnahme greift.

## Erste Schritte

1. KN-8-Steller und Ursprungsland klar bestimmen; TARIC-Abfrage mit aktueller Fassung.
2. Alle gueltigen Massnahmen (ADD, CVD, Safeguard, Surveillance) fuer den Code auflisten.
3. Hersteller-Code (TARIC ADD-Zusatzcode) beim Lieferanten erfragen und validieren.
4. Preisverpflichtungen (Price Undertakings) und Mindestimportpreise pruefen.
5. Freimengen und Zollkontingente (TRQ) pruefen, falls Massnahme-Ausnahmen bestehen.
6. Massnahmen-Stand in Dokumentation vermerken (Datum, TARIC-Version).

## Rechtsrahmen

- **UZK Art. 56 Abs. 2**: Massnahmen des Gemeinsamen Zolltarifs inkl. Antidumping.
- **VO (EU) 2016/1036**: Antidumping-Grundverordnung.
- **VO (EU) 2016/1037**: Ausgleichszoll-Grundverordnung (Subventionen).
- **VO (EU) 2015/478**: Gemeinsame Einfuhrregelung und Safeguards.
- **Durchfuehrungsverordnungen**: Einzelne ADD- und CVD-Massnahmen per Durchfuehrungs-VO.

## Pruef-Raster

- [ ] KN-Code und Ursprungsland korrekt fuer TARIC-Abfrage?
- [ ] Alle aktiven Massnahmen (ADD, CVD, Safeguard) aufgelistet?
- [ ] Hersteller-TARIC-Code validiert und nicht gesperrt?
- [ ] Preisverpflichtungs-Compliance dokumentiert?
- [ ] Freimengen/Kontingente (TRQ) geprueft?
- [ ] Massnahmen-Stand mit Datum protokolliert?

## Typische Fallstricke

- TARIC-Datenbank mit Stand-Datum nutzen; keine Offline-Auszuege aus Vormonat.
- Mehrere parallele Massnahmen (ADD + CVD + Safeguard) sind kumulativ anwendbar.
- Hersteller-ID kann sich durch Fusionen oder Rueckzug der Anerkennung aendern.
- Massnahmen gelten per Einreihung; marginale Unterschiede im KN-Code vermeiden.

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

TARIC-Massnahmen-Tabelle mit ADD-/CVD-Zusatzcodes, Hersteller-Zuordnung, Preisverpflichtungsstatus und Zollberechnungsblatt.

## Quellen

- [TARIC-Datenbank der EU-Kommission](https://ec.europa.eu/taxation_customs/dds2/taric/taric_consultation.jsp)
- [VO (EU) 2016/1036 auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32016R1036)
- [VO (EU) 2016/1037 auf EUR-Lex](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32016R1037)
- [Zoll.de Besondere Einfuhrabgaben](https://www.zoll.de/DE/Fachthemen/Zoelle/Zollrechtliche-Einfuhrbestimmungen/Besondere-Einfuhrabgaben/besondere-einfuhrabgaben_node.html)
