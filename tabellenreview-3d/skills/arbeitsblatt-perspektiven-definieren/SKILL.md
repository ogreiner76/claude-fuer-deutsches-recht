---
name: arbeitsblatt-perspektiven-definieren
description: "Definiert die dritte Wuerfel-Achse — Arbeitsblaetter als Perspektiven die ueber denselben Dokumentenstapel laufen aber jeweils eine andere Brille aufsetzen. Typische Perspektiven: Recht (Anwalt) Steuer (Steuerberater) Wirtschaft (Buyside-Analyst) Datenschutz (DSGVO-Beauftragter) IT (Architekt) Betrieb (Operations) Compliance (GwG / Lieferkettengesetz). Pro Arbeitsblatt: eigene Zusatzspalten Auslassungen Sonderprompts Ampelregeln. Erzeugt `arbeitsblaetter.yaml`. Erlaubt Kreuzblatt-Konsistenzpruefung."
---

# /tabellenreview-3d:arbeitsblatt-perspektiven-definieren

## Zweck

Excel kann mehrere Tabellenblaetter nebeneinander. Der 3D-Wuerfel uebernimmt dieses Bild: dieselben Dokumente (Zeilen) werden mehrfach geprueft, jedes Mal aus einer anderen Perspektive (Arbeitsblatt). Die Spalten sind je Arbeitsblatt zum Teil deckungsgleich (vergleichbare Datenpunkte) und zum Teil arbeitsblattspezifisch.

## Standard-Perspektiven

### Recht (Anwaltsperspektive)

- Spalten: AGB-Wirksamkeit Haftungsregime Verjaehrungsverkuerzung Gerichtsstand Schiedsklausel Schriftformklausel
- Materialitaet: rot bei Klauseln die nach BGB Paragraph 307 unwirksam sind
- Pruefer: zugelassener Rechtsanwalt

### Steuer (Steuerberater)

- Spalten: Umsatzsteuer-Behandlung Rechnungspflichtangaben UStG Paragraph 14 grenzueberschreitend ja / nein Reverse-Charge ja / nein
- Materialitaet: rot bei UStG-Compliance-Risiken
- Pruefer: Steuerberater oder Wirtschaftspruefer

### Wirtschaft (Buyside-Analyst)

- Spalten: Vertragsvolumen Laufzeit Kuendigungsdatum Preisanpassungsmechanik Working-Capital-Effekt
- Materialitaet: rot bei Top-5-Kunden-Konzentration ueber 60 Prozent
- Pruefer: Deal-Lead / Corp-Dev

### Datenschutz (DSGVO-Beauftragter)

- Spalten: Datenkategorien Rechtsgrundlage Auftragsverarbeitung-Pflicht AVV vorhanden Drittlandtransfer SCC vorhanden
- Materialitaet: rot bei fehlender AVV trotz Auftragsverarbeitung (DSGVO Artikel 28)
- Pruefer: Datenschutzbeauftragter

### IT (Architekt)

- Spalten: Hosting-Modell Verschluesselungs-Standard Lock-in-Risiko Schnittstellen-Dokumentation Exit-Daten-Format
- Materialitaet: rot bei nicht standardisierten Datenformaten ohne Exit-Pflicht
- Pruefer: IT-Architekt

### Betrieb (Operations)

- Spalten: Service-Level Reaktionszeit Wiederherstellungszeit Eskalationsstufen Vertretungsregelung
- Materialitaet: rot bei SLA-Reaktionszeit ueber 4 Stunden bei produktionskritischen Services
- Pruefer: Operations-Lead

### Compliance (GwG / LkSG)

- Spalten: Wirtschaftlich Berechtigter bekannt Sanktionslisten-Pruefung Lieferketten-Risiko-Region nach LkSG
- Materialitaet: rot bei Sanktionslisten-Treffer
- Pruefer: Compliance-Officer

## Pflichtfelder pro Arbeitsblatt

```yaml
- id: recht
  titel: "Rechtliche Perspektive"
  perspektive: "anwalt"
  pruefer-rolle: "rechtsanwalt"
  eigene-spalten-zusaetze:
    - id: agb-wirksamkeit
      prompt: "Sind die AGB-Klauseln nach BGB Paragraph 305 ff. wirksam?"
  auslassungen:
    - umsatzsteuer  # Steuerblatt; hier nicht zustaendig
  ampel-regel:
    rot: "Unwirksame Klausel BGB Paragraph 307"
    gelb: "AGB-Wirksamkeit zweifelhaft"
    gruen: "Wirksam oder Individualvereinbarung"
```

## Stapelung

Die Arbeitsblaetter werden in der Excel-Ausgabe als Tabellenreiter nebeneinander dargestellt. Im PDF-Bericht erscheinen sie als aufeinanderfolgende Abschnitte. In `kreuzblatt-konsistenzpruefung` werden Widersprueche zwischen Arbeitsblaettern gefunden (z. B. ein Vertrag der rechtlich gruen aber wirtschaftlich rot ist — das ist legitim und soll markiert werden).

## Ausgabe

- `arbeitsblaetter.yaml` mit allen Arbeitsblaettern, deren Spaltenzusaetze, Auslassungen und Pruefer-Rollen
- `arbeitsblatt-matrix.md` als menschenlesbare Uebersicht
