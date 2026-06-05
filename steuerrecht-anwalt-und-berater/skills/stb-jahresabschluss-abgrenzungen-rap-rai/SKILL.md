---
name: stb-jahresabschluss-abgrenzungen-rap-rai
description: "Rechnungsabgrenzungsposten RAP aktiv und passiv. Anwendungsfall Jahresabschluss-Buchung Versicherung Miete Kfz-Steuer Vorauszahlungen periodengerechte Zuordnung. Methodik Identifikation Berechnung Buchung. Output Periodengerechte JA-Bestaende."
---

# Rechnungsabgrenzungsposten (RAP) aktiv und passiv

## V90 Fachkern — Steuerrecht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `Rechnungsabgrenzungsposten (RAP) aktiv und passiv` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** AO, EStG, KStG, GewStG, UStG, GrEStG, UmwStG, AStG, FZulG, MinStG; BMF-Schreiben nur mit Datum, Titel und offizieller BMF-URL verwenden.
- **Verifizierte Anker:** BMF-Schreiben vom 15.10.2025 zur obligatorischen E-Rechnung und UStAE-Anpassung; BMF-Seite Forschungszulage mit Hinweis zu Antrags-/Festsetzungslogik und BMF-Schreiben vom 07.02.2023; BMF/BZSt-Datensatzbeschreibung vom 05.08.2025 für Mindeststeuer-Berichte; BMF-Schreiben vom 25.05.2023 zu § 6a GrEStG; BMF-Schreiben vom 02.01.2025/01.08.2025 zum Umwandlungssteuer-Anwendungserlass live prüfen.
- **Arbeitsmodus:** Erst Steuerart, Zeitraum, Verwaltungsstand, Frist/Festsetzung, Zuständigkeit, Form/Portal und Beleglage klären; dann BMF-Verwaltungslinie von BFH-Rechtsprechung und Gesetz trennen.
- **Outputpflicht:** Steuerartenmatrix, BMF-Radar, Einspruchsbaustein, ELSTER-/Portal-To-do, Risikoampel, DBA-/GrESt-/USt-Tabelle oder Mandantenmemo.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


## Kernsachverhalt

Rechnungsabgrenzungsposten (RAP) sind die bilanzielle Zuordnung von Aufwand und Ertrag zur richtigen Periode. Aktive RAP: Vorauszahlungen, die der Mandant gemacht hat und die in das Folgejahr gehoeren (z.B. Versicherungspraemie fuer 12 Monate, gezahlt im Dezember). Passive RAP: Einzahlungen, die im aktuellen Jahr empfangen wurden, aber Leistungen fuer das Folgejahr betreffen.

## Kaltstart-Rueckfragen

1. Welche Vorauszahlungen wurden geleistet (Versicherung, Miete, Leasing, Kfz-Steuer)?
2. Welche Einnahmen wurden empfangen, die Folgejahr betreffen (Mietvorauszahlungen, Service-Vertraege)?
3. Welcher Vertragszeitraum?
4. Welche Belege liegen vor?
5. Welche Standard-RAP wiederkehrend (Versicherung, Miete)?
6. Welche Sonderzahlungen?
7. Welcher Konten-Plan (RAP-Konten SKR 03)?
8. Welche steuerliche Behandlung (Massgeblichkeit § 5 EStG)?

## Rechtlicher Rahmen

### Primaernormen

**§ 250 HGB** — Rechnungsabgrenzungsposten.

**§ 252 Abs. 1 Nr. 5 HGB** — Periodenabgrenzung.

**§ 5 Abs. 5 EStG** — Steuerliche Massgeblichkeit RAP.

**§ 6 EStG** — Bewertung.

### Standards

- IDW PS 480.

## Workflow

### Phase 1 — Aktive RAP-Identifikation

| Beispiel | Vorauszahlung | RAP-Berechnung |
|---|---|---|
| Versicherungspraemie 12 Monate fuer Folgejahr | 1.200 EUR im Dezember | RAP aktiv 1.200 EUR |
| Miete Januar des Folgejahres in Dezember | 1.000 EUR | RAP aktiv 1.000 EUR |
| Leasing-Vorauszahlung | 5.000 EUR fuer 24 Monate | RAP aktiv 5.000 EUR (5.000 / 24 x 24 Monate) |
| Kfz-Steuer Folgejahr | 800 EUR | RAP aktiv 800 EUR |
| GEZ-Beitrag Folgejahr | 70 EUR | RAP aktiv 70 EUR |

### Phase 2 — Passive RAP-Identifikation

| Beispiel | Einzahlung | RAP-Berechnung |
|---|---|---|
| Mietvorauszahlung fuer Folgejahr | 5.000 EUR | RAP passiv 5.000 EUR |
| Service-Vertrag Vorauszahlung | 2.400 EUR fuer 24 Monate | RAP passiv 2.400 EUR x 12/24 = 1.200 EUR |
| Jahresvorauszahlung Wartungsvertrag | 600 EUR | RAP passiv 600 EUR |

### Phase 3 — Berechnung

- Anteil des Vorgangs, der in das Folgejahr gehoert.
- Bei 12-Monats-Vorauszahlung im Dezember: 11/12 RAP, 1/12 Aufwand/Ertrag.
- Bei kuerzeren Perioden anteilig genau.

### Phase 4 — Buchung

- Aktive RAP: Konto 980 SKR 03 (1900 SKR 04).
- Buchung: Aktive RAP an Aufwand (z.B. 4360 Versicherung).
- Passive RAP: Konto 990 SKR 03 (3900 SKR 04).
- Buchung: Ertrag (z.B. 8500) an Passive RAP.

### Phase 5 — Aufloesung im Folgejahr

- Eroeffnungsbilanz hat RAP-Bestaende.
- Im Folgejahr: Aufloesung anteilig.
- Buchung: Aufwand an Aktive RAP / Passive RAP an Ertrag.

### Phase 6 — Steuerliche Behandlung

- § 5 Abs. 5 EStG: aktive RAP sind in der Steuerbilanz zwingend.
- Steuerbilanz und Handelsbilanz oft identisch in RAP.

## Output

- RAP-Liste mit Berechnungsbasis.
- Buchungen im Hauptbuch.
- Bilanz mit RAP-Posten.

## Strategie und Praxis-Tipps

- Standard-RAP (Versicherung, Miete, Kfz-Steuer) sind wiederkehrend — Routine.
- Bei Mehrjahresvertraegen (z.B. 5-Jahres-Wartung): RAP gestaffelt.
- Bei kleinen RAP-Betraegen unter Wesentlichkeitsschwelle: ggf. nicht abgrenzen (vgl. BMF zu RAP-Bagatelle).
- Bei Pruefungspflicht: WP prueft RAP detailliert.
- DATEV-Tipp: DATEV-AfA-Modul kann RAP-Aufloesung monatlich automatisch.

## Querverweise

- `stb-jahresabschluss-vorbereitung-stichtag` — JA-Vorbereitung.
- `stb-jahresabschluss-rueckstellungen-bewertung` — Rueckstellungen.
- `stb-bwa-aufbau-grundlagen` — BWA mit Periodenabgrenzung.

## Quellen und Updates

Stand: 05/2026.

- HGB §§ 250, 252.
- EStG §§ 5, 6.
- IDW PS 480.


## Qualitäts-Hardening

- Arbeite aktennah: Tatsachen, Belege, Fristen, Zuständigkeit und gewünschtes Arbeitsprodukt zuerst klären.
- Keine Rechtsprechung aus Modellwissen zitieren. Jede Entscheidung vor Ausgabe mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei oder amtlich prüfbarer Quelle absichern.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate. Literatur nur verwenden, wenn der Nutzer sie bereitstellt oder ein lizenzierter Live-Zugriff im konkreten Arbeitsschritt dokumentiert ist.
- Wenn eine Quelle, Randnummer, Behördenpraxis oder Frist nicht sicher geprüft ist, sichtbar als Prüfpunkt markieren und keine Scheinpräzision erzeugen.
- Ergebnisse so liefern, dass sie sofort weiterverwendbar sind: Kurzbild, Prüfpfad, Risikoampel, Lückenliste und konkrete nächste Schritte.
