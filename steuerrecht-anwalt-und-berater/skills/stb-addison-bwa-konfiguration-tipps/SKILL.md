---
name: stb-addison-bwa-konfiguration-tipps
description: "Addison BWA-Konfiguration. Anwendungsfall Kanzleien mit Wolters Kluwer Addison statt DATEV. Methodik Unterschiede zu DATEV Konten-Konfiguration Branchenanpassung. Output BWA in Addison."
---

# Addison BWA-Konfiguration

## V90 Fachkern — Steuerrecht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `Addison BWA-Konfiguration` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** AO, EStG, KStG, GewStG, UStG, GrEStG, UmwStG, AStG, FZulG, MinStG; BMF-Schreiben nur mit Datum, Titel und offizieller BMF-URL verwenden.
- **Verifizierte Anker:** BMF-Schreiben vom 15.10.2025 zur obligatorischen E-Rechnung und UStAE-Anpassung; BMF-Seite Forschungszulage mit Hinweis zu Antrags-/Festsetzungslogik und BMF-Schreiben vom 07.02.2023; BMF/BZSt-Datensatzbeschreibung vom 05.08.2025 für Mindeststeuer-Berichte; BMF-Schreiben vom 25.05.2023 zu § 6a GrEStG; BMF-Schreiben vom 02.01.2025/01.08.2025 zum Umwandlungssteuer-Anwendungserlass live prüfen.
- **Arbeitsmodus:** Erst Steuerart, Zeitraum, Verwaltungsstand, Frist/Festsetzung, Zuständigkeit, Form/Portal und Beleglage klären; dann BMF-Verwaltungslinie von BFH-Rechtsprechung und Gesetz trennen.
- **Outputpflicht:** Steuerartenmatrix, BMF-Radar, Einspruchsbaustein, ELSTER-/Portal-To-do, Risikoampel, DBA-/GrESt-/USt-Tabelle oder Mandantenmemo.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


## Kernsachverhalt

Addison (Wolters Kluwer) ist die zweitstaerkste StB-Kanzleisoftware in Deutschland. Funktionen vergleichbar mit DATEV: Buchfuehrung, BWA, Lohn, Jahresabschluss. Andere Bedienlogik und andere Standardforms. Steuerberater, die mit Addison arbeiten, brauchen aequivalente Praxis-Tipps.

## Kaltstart-Rueckfragen

1. Welche Addison-Version (jaehrliche Updates)?
2. Welche Module (Finanzbuchhaltung, Lohn, Jahresabschluss)?
3. Welche Standard-Form fuer Mandanten?
4. Welche Branchen-Konfiguration?
5. Welche individuellen Anpassungen?
6. Welche Schnittstellen aktiv (eRechnung, Bank)?
7. Welche Berater-Sicht-Konfiguration?
8. Welche Schulungsstand der Sachbearbeiter?

## Workflow

### Phase 1 — Standardformen

| Addison-Bezeichnung | DATEV-Aequivalent | Verwendung |
|---|---|---|
| Standard-BWA / Kurz-BWA | DATEV BWA 01 | Standard 90 % der Mandate |
| Bewegungs-BWA | DATEV BWA 11 | Detaillierter Vormonatsvergleich |
| Branchen-BWA | DATEV BWA 21 | Mit Branchenkennzahlen |
| Liquiditaets-BWA | DATEV BWA 41 | Cashflow-orientiert |
| Kostenstellen-BWA | DATEV BWA 31 | Bei Kostenstellenrechnung |

Hinweis: konkrete Form-Nummern und Bezeichnungen variieren mit der Addison-Version; aktuellen Stand in der Programmdokumentation pruefen.

### Phase 2 — Konten-Konfiguration

- Kontenrahmen SKR 03 / SKR 04 wie in DATEV; alternativ branchenspezifische Rahmen (z.B. SKR 14 Landwirtschaft, IKR fuer Industrieunternehmen).
- BWA-Konten-Zuordnung ueber Berater-Stammdaten (typischer Pfad `Stammdaten → BWA-Konfiguration → Konten-Zuordnung`; konkreter Menue-Pfad variiert je Addison-Version — im Zweifelsfall in der Programm-Onlinehilfe unter "BWA-Konfiguration" nachschlagen).
- Bei individuellen Konten manuelle Zuordnung zur BWA-Zeile vor erstem Lauf.

### Phase 3 — Periodenvergleich

- Vorjahresdaten werden bei vorhandener Buchhaltungs-Historie automatisch herangezogen.
- Planwerte ueber das Plan-Erfassungs-Modul (jaehrlich/monatlich) erfassen; Plan-Ist-Vergleich in der BWA aktivieren.
- Mehrjahresvergleich bis 5 Jahre zurueck moeglich.

### Phase 4 — Branchenvergleich

- Wolters Kluwer Branchenberichte als Alternative zu DATEV BBE-Branchenberichten.
- Branchenschluessel (WZ-Code) im Mandantenstamm hinterlegen.
- Aktualitaet der Branchendaten pruefen — typischerweise jaehrliche Aktualisierung.

### Phase 5 — Ausgabe

- PDF-Export mit Mandanten-Briefkopf.
- Excel-Export fuer Detailauswertung (Pivot-tauglich).
- Mandantenportal "Wolters Kluwer Mandanten-Cockpit" als Pendant zu DATEV Unternehmen Online.

### Phase 6 — Updates

- Jaehrliche Programm-Updates zum 1. Januar (Lohnsteuer-, SV-Tabellen, USt-Aenderungen, AfA-Tabellen).
- Bei groesseren Reformen unterjaehrige Updates (z.B. Wachstumschancengesetz, eRechnung).
- Update-Pflicht aus § 146 AO (Programm muss aktuelle Tabellen abbilden).

## Output

- Konfigurierte Addison-BWA.

## Strategie und Praxis-Tipps

- Addison-Schulungen ueber Wolters Kluwer Akademie.
- Wechsel von DATEV zu Addison oder umgekehrt sorgfaeltig planen — Mandantenmigration aufwendig.
- Hybrid-Modelle (z.B. Lohn Addison, Buchhaltung DATEV) sind selten und teuer.

## Querverweise

- `stb-bwa-aufbau-grundlagen` — BWA.
- `stb-datev-bwa-modul-bedienen-tipps` — DATEV Pendant.
- `stb-sage-buchhalter-bwa-konfiguration` — Sage.

## Quellen und Updates

Stand: 05/2026.

- Wolters Kluwer Addison Programm- und Bedienungsdokumentation (aktuelle Version pruefen).
- Wolters Kluwer Branchenberichte als Vergleichsdatenbank.
- Verifikations-Hinweis: konkrete Programmpfade und Form-Nummern ggf. abweichend in aktueller Addison-Version.

<!-- AUDIT 27.05.2026 | welle 6 | 1 Marker aufgeloest: 1 ersetzt (Programmpfad-Hinweis ohne Marker neu formuliert) -->


## Qualitäts-Hardening

- Arbeite aktennah: Tatsachen, Belege, Fristen, Zuständigkeit und gewünschtes Arbeitsprodukt zuerst klären.
- Keine Rechtsprechung aus Modellwissen zitieren. Jede Entscheidung vor Ausgabe mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei oder amtlich prüfbarer Quelle absichern.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate. Literatur nur verwenden, wenn der Nutzer sie bereitstellt oder ein lizenzierter Live-Zugriff im konkreten Arbeitsschritt dokumentiert ist.
- Wenn eine Quelle, Randnummer, Behördenpraxis oder Frist nicht sicher geprüft ist, sichtbar als Prüfpunkt markieren und keine Scheinpräzision erzeugen.
- Ergebnisse so liefern, dass sie sofort weiterverwendbar sind: Kurzbild, Prüfpfad, Risikoampel, Lückenliste und konkrete nächste Schritte.
