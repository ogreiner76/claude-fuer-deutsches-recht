---
name: vorlage-ma-due-diligence
description: "Fertige Wuerfelvorlage fuer M&A-Due-Diligence — 18 Spalten (Vertragsart Laufzeit Kuendigungsfrist Change-of-Control MAC-Klausel Abtretungsverbot Haftungsbegrenzung Garantien Vertragsstrafe SLA Datenschutz Geheimhaltung Verguetung Preisanpassung Schriftform Gerichtsstand Schiedsklausel anwendbares Recht) x N Vertraege aus dem Datenraum x 4 Arbeitsblaetter (Recht / Steuer / Wirtschaft / Datenschutz). Mit BGB-Verankerung (Paragraph 307 ff. / Paragraph 311 / Paragraph 399 / Paragraph 444) HGB-Verankerung (Paragraph 354a) AktG (Paragraph 311 Konzernrecht) und BGH-Leitsaetzen. Startbar mit einem Klick — kein eigener Wuerfel-Aufbau noetig."
---

# /tabellenreview-3d:vorlage-ma-due-diligence

## Zweck

M&A-DD bei einem Vertragsstapel der Zielgesellschaft. Die Standardfragen sind bekannt — diese Vorlage liefert sie fix und fertig: Spaltenprompts mit BGH-Verankerung, vier Arbeitsblatt-Perspektiven, Ampel-Schwellen praxisbewaehrt.

## Spalten (18 Datenpunkte)

1. **Vertragsart** — Rahmenvertrag / Einzelvertrag / NDA / Lizenz / Lieferung / Werk
2. **Laufzeit und Beginn** — Vertragsdatum + Festlaufzeit / unbefristet
3. **Kuendigungsfrist** — ordentliche / ausserordentliche / Sondertatbestaende
4. **Change-of-Control** — Klausel vorhanden / Schwelle / Rechtsfolge (BGH KZR 2/07)
5. **MAC-Klausel** — Wesentlichkeitsdefinition / Rechtsfolge (BGB Paragraph 313 / 314)
6. **Abtretungsverbot** — BGB Paragraph 399 / HGB Paragraph 354a / Vertragsuebernahme
7. **Haftungsbegrenzung** — pro Fall / pro Jahr / Ausschluss Vorsatz und grobe Fahrlaessigkeit
8. **Garantien** — beschaffenheitsbezogen / verschuldensunabhaengig / Haftungsausschluss BGB Paragraph 444
9. **Vertragsstrafe** — Hoehe / Deckelung / Verschuldensanknuepfung
10. **Service-Level** — Reaktionszeit / Verfuegbarkeit / Wiederherstellungszeit
11. **Datenschutz-AVV** — DSGVO Artikel 28 / Drittlandtransfer / SCC / TIA
12. **Geheimhaltung** — Dauer / Carve-Outs / Rueckgabe / Sanktionen
13. **Verguetung** — Festpreis / Stundensatz / Erfolg / Schwellen
14. **Preisanpassung** — Indexbindung / Schwellen / Kuendigungsrecht der Gegenseite
15. **Schriftform** — Aenderungsvorbehalt / Sprengsatz (BGB Paragraph 125 Satz 2)
16. **Gerichtsstand** — vereinbarter Gerichtsstand / Kaufmannsklausel (ZPO Paragraph 38)
17. **Schiedsklausel** — Schiedsgericht / Sitz / Sprache / Verfahrensordnung
18. **Anwendbares Recht** — Rechtswahl / kollisionsrechtliche Wirkungen

## Arbeitsblatt-Perspektiven (4)

### Recht (Anwaltsperspektive)

- Zusatzspalten: AGB-Wirksamkeit (BGB Paragraph 305 ff.) / Klauselverbote (BGB Paragraph 308 / Paragraph 309) / Verjaehrungsverkuerzung
- Pruefer: M&A-Lead-Counsel
- Materialitaet rot: unwirksame Klausel mit Hauptleistungsbezug

### Steuer (Steuerberater)

- Zusatzspalten: Umsatzsteuer-Behandlung / Reverse-Charge / verdeckte Gewinnausschuettung bei Konzernvertraegen (KStG)
- Pruefer: Steuerberater
- Materialitaet rot: USt-Risiko mehr als 100k EUR

### Wirtschaft (Buyside)

- Zusatzspalten: Vertragsvolumen pro Jahr / Top-Kunde-Konzentration / Working-Capital-Effekt / Verlaengerungsoption
- Pruefer: Deal-Lead
- Materialitaet rot: Vertrag > 10 Prozent Umsatz UND Kuendigungsrecht der Gegenseite < 12 Monate

### Datenschutz (DSGVO)

- Zusatzspalten: Datenkategorien / Rechtsgrundlage Artikel 6 / Drittlandtransfer / Auftragsverarbeitung / Joint-Controller
- Pruefer: Datenschutzbeauftragter
- Materialitaet rot: Auftragsverarbeitung ohne AVV oder Drittlandtransfer ohne SCC

## BGH-Leitsaetze (Auswahl)

- BGH KZR 2/07 — Kuendigung bei mittelbarem Kontrollwechsel
- BGH V ZR 30/08 — Due-Diligence-Pflicht des Kaeufers / Kenntnis von Maengeln
- BGH I ZR 193/15 — Vertragsuebernahme ohne Schuldnerzustimmung
- BGH IX ZR 31/91 — Abtretungsausschluss

## Ausgabe

Wuerfel-Schema fix und fertig in `wuerfel-schema.yaml` mit allen drei Achsen. Direkt einsatzbereit fuer `review-durchfuehren`.
