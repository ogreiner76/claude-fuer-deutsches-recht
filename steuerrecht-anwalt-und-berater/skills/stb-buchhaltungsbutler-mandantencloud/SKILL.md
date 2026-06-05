---
name: stb-buchhaltungsbutler-mandantencloud
description: "BuchhaltungsButler und vergleichbare Cloud-Buchhaltung beim Mandanten. Anwendungsfall Mandant arbeitet mit BuchhaltungsButler sevDesk Lexware Office Candis StB-Schnittstelle DATEV-Export Datenqualitaetsprüfung AVV. Methodik Konfiguration Belegworkflow GoBD-Risiken Honoraranpassung. Output eingerichtete Cloud-Schnittstelle und Prüfroutine."
---

# BuchhaltungsButler — Mandanten-Cloud-Loesung

## V90 Fachkern — Steuerrecht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `BuchhaltungsButler — Mandanten-Cloud-Loesung` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** AO, EStG, KStG, GewStG, UStG, GrEStG, UmwStG, AStG, FZulG, MinStG; BMF-Schreiben nur mit Datum, Titel und offizieller BMF-URL verwenden.
- **Verifizierte Anker:** BMF-Schreiben vom 15.10.2025 zur obligatorischen E-Rechnung und UStAE-Anpassung; BMF-Seite Forschungszulage mit Hinweis zu Antrags-/Festsetzungslogik und BMF-Schreiben vom 07.02.2023; BMF/BZSt-Datensatzbeschreibung vom 05.08.2025 für Mindeststeuer-Berichte; BMF-Schreiben vom 25.05.2023 zu § 6a GrEStG; BMF-Schreiben vom 02.01.2025/01.08.2025 zum Umwandlungssteuer-Anwendungserlass live prüfen.
- **Arbeitsmodus:** Erst Steuerart, Zeitraum, Verwaltungsstand, Frist/Festsetzung, Zuständigkeit, Form/Portal und Beleglage klären; dann BMF-Verwaltungslinie von BFH-Rechtsprechung und Gesetz trennen.
- **Outputpflicht:** Steuerartenmatrix, BMF-Radar, Einspruchsbaustein, ELSTER-/Portal-To-do, Risikoampel, DBA-/GrESt-/USt-Tabelle oder Mandantenmemo.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


## Kernsachverhalt

BuchhaltungsButler (auch sevDesk, Lexware-Office, Billbee, Candis) sind Cloud-Buchhaltungsloesungen fuer Mandanten, die ihre Buchfuehrung weitgehend selbst betreiben. Sie bieten Beleg-Scan, Bank-Abruf, automatische Buchungs-Vorschlaege. Der Steuerberater erhaelt Daten ueber DATEV-Export oder andere Schnittstellen. Vorteil: Mandant traegt einen Teil der Arbeit; Nachteil: Daten-Qualitaet variabel.

## Kaltstart-Rueckfragen

1. Welche Cloud-Loesung verwendet der Mandant?
2. Welche Schnittstellen zu DATEV existieren?
3. Wer bucht — Mandant, StB, automatisch?
4. Welche Datenqualitaet wird geliefert?
5. Welche Pflichten des Mandanten (Buchungs-Kontrolle, GoBD-Konformitaet)?
6. Welche AVV mit Cloud-Anbieter?
7. Welche Sicherheits-Vorkehrungen?
8. Welche Mandanten-Schulungsstand?

## Workflow

### Phase 1 — System-Wahl

| Tool | Geeignet fuer |
|---|---|
| BuchhaltungsButler | KMU mit hohem Belegaufkommen |
| sevDesk | Solo-Selbstaendige, Kleinunternehmer |
| Lexware-Office | Kleinmandanten, Klein-GmbH |
| Candis | Mittelstand mit Beleg-Workflow |
| Datev DUO | StB-Mandanten (Standard) |

### Phase 2 — Schnittstelle zu DATEV

- DATEV-Buchungsstapel-Export aus der Cloud im DATEV-CSV-Format (sog. "ASCII-Format" bzw. neuer "Belege Online"-Schnittstelle).
- Import in DATEV Kanzlei-Rechnungswesen ueber `Datei → Datenuebernahme → Buchungsstapel` (konkrete Programmpfade in der aktuellen DATEV-Programmversion ggf. abweichend).
- Plausibilitaetspruefung der Buchungen (Konten-Mapping, USt-Schluessel, Belegverknuepfung).

### Phase 3 — Mandanten-Setup

- Mandant erhaelt Cloud-Konto.
- StB-Lese-Zugang.
- Belegworkflow festlegen.

### Phase 4 — Buchungsfreigabe

- Mandant bucht (oder Cloud schlaegt vor).
- StB prueft und freigibt.
- Bei Fehlern Korrektur.

### Phase 5 — Auswertung

- BWA aus DATEV oder direkt aus Cloud.
- Bei Cloud-BWA: in der Regel nicht GoBD-Standard.
- StB-BWA aus DATEV bleibt verbindlich.

### Phase 6 — DSGVO

- AVV mit Cloud-Anbieter zwingend.
- Daten-Hosting in EU.
- Backup-Strategie.

## Output

- Cloud-Konto eingerichtet.
- Schnittstelle zu DATEV.
- Mandant geschult.

## Strategie und Praxis-Tipps

- Cloud-Tools sind Effizienzhebel, wenn Mandant disziplinarisch arbeitet.
- Datenqualitaet schwankend — StB-Pruefung bleibt Pflicht.
- DSGVO-Compliance staendig pruefen.
- Honorar oft niedriger bei Cloud-betreibenden Mandanten (Buchungs-Anteil reduziert).
- StBVV: Honorarmodell anpassen (Pauschal niedriger, Pruefung Stunden).

## Querverweise

- `stb-online-portal-datev-mandantenshop` — DUO.
- `stb-belegtransfer-datev-unternehmen-online` — Belegtransfer.
- `stb-datentransfer-mandant-cloud-dsgvo` — DSGVO im Datenverkehr.

## Quellen und Updates

Stand: 05/2026.

- BuchhaltungsButler, sevDesk, Lexware Dokumentation.
- DSGVO Art. 28.
- BMF v. 28.11.2019 zu GoBD.


## Qualitäts-Hardening

- Arbeite aktennah: Tatsachen, Belege, Fristen, Zuständigkeit und gewünschtes Arbeitsprodukt zuerst klären.
- Keine Rechtsprechung aus Modellwissen zitieren. Jede Entscheidung vor Ausgabe mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei oder amtlich prüfbarer Quelle absichern.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate. Literatur nur verwenden, wenn der Nutzer sie bereitstellt oder ein lizenzierter Live-Zugriff im konkreten Arbeitsschritt dokumentiert ist.
- Wenn eine Quelle, Randnummer, Behördenpraxis oder Frist nicht sicher geprüft ist, sichtbar als Prüfpunkt markieren und keine Scheinpräzision erzeugen.
- Ergebnisse so liefern, dass sie sofort weiterverwendbar sind: Kurzbild, Prüfpfad, Risikoampel, Lückenliste und konkrete nächste Schritte.
