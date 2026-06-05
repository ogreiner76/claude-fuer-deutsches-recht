---
name: stb-datev-lohn-modul-lodas-luh
description: "DATEV LODAS und Lohn und Gehalt LUG. Anwendungsfall Lohnabrechnung in DATEV-Welt Konfiguration ELSTER ELStAM sv.net Schnittstellen. Methodik Unterschiede LODAS vs Lohn und Gehalt Praxis-Tipps. Output Lohnprogramm konfiguriert."
---

# DATEV LODAS und Lohn und Gehalt

## V90 Fachkern — Steuerrecht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `DATEV LODAS und Lohn und Gehalt` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** AO, EStG, KStG, GewStG, UStG, GrEStG, UmwStG, AStG, FZulG, MinStG; BMF-Schreiben nur mit Datum, Titel und offizieller BMF-URL verwenden.
- **Verifizierte Anker:** BMF-Schreiben vom 15.10.2025 zur obligatorischen E-Rechnung und UStAE-Anpassung; BMF-Seite Forschungszulage mit Hinweis zu Antrags-/Festsetzungslogik und BMF-Schreiben vom 07.02.2023; BMF/BZSt-Datensatzbeschreibung vom 05.08.2025 für Mindeststeuer-Berichte; BMF-Schreiben vom 25.05.2023 zu § 6a GrEStG; BMF-Schreiben vom 02.01.2025/01.08.2025 zum Umwandlungssteuer-Anwendungserlass live prüfen.
- **Arbeitsmodus:** Erst Steuerart, Zeitraum, Verwaltungsstand, Frist/Festsetzung, Zuständigkeit, Form/Portal und Beleglage klären; dann BMF-Verwaltungslinie von BFH-Rechtsprechung und Gesetz trennen.
- **Outputpflicht:** Steuerartenmatrix, BMF-Radar, Einspruchsbaustein, ELSTER-/Portal-To-do, Risikoampel, DBA-/GrESt-/USt-Tabelle oder Mandantenmemo.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


## Kernsachverhalt

DATEV bietet zwei Lohnprogramme: LODAS (Lohnbuchhaltungs- und Datenerfassungs-System; haeufiger in Steuerberater-Buros) und Lohn und Gehalt (LUG; vorwiegend bei Mandanten selbst). Beide Programme decken Lohnabrechnung, SV-Meldungen, ELStAM, ELSTER, Jahresmeldungen ab. Der Steuerberater waehlt das passende System fuer die Mandantenstruktur und konfiguriert die Schnittstellen.

## Kaltstart-Rueckfragen

1. Welche Mandantengroesse — bis 50 AN, ueber 50 AN?
2. Welche Branche und Sondersituationen (Sonn-/Feiertag, Schichtarbeit)?
3. Welche Schnittstellen erforderlich (Bank, ERP)?
4. Welche Module aktiv (BG, bAV, JobRad)?
5. Welche Mandanten-Sicht (Mandant selbst sieht Lohnabrechnungen)?
6. Welche Zertifikate (ITSG, ELSTER)?
7. Welche Kanzlei-Praeferenz (LODAS oder LUG)?
8. Welche Schulungsbedarf Sachbearbeiter?

## Workflow

### Phase 1 — System-Wahl

| Kriterium | LODAS | Lohn und Gehalt |
|---|---|---|
| Anwendungsumgebung | StB-Kanzlei | Mandant selbst |
| Mandantenzahl | viele Mandanten parallel | Einzelmandant |
| Datenstruktur | Multimandant | Einzelmandant |
| ITSG-Zertifikat | pro Mandant | pro Mandant |
| Module | BG, bAV, JobRad, Werkstudent etc. | gleich |

### Phase 2 — Mandanten-Anlage

- Mandanten-Stammdaten: Branche, BG, KK, Tarifvertrag.
- AN-Stammdaten: SV, ELStAM, Lohnform.
- Konten-Konfiguration im Hauptbuch.

### Phase 3 — Monatslauf

- Datenimport (Variabler Lohn, Krankheit, Sonderzahlungen).
- ELStAM-Abruf.
- Lohnabrechnung erstellen.
- Pruefliste durchgehen.
- ELSTER-Anmeldung.
- SV-Meldungen.
- Buchungssatz an Hauptbuch.

### Phase 4 — Schnittstellen

- ELStAM: Standard.
- ELSTER: Standard.
- DAKOTA (sv.net Alternative): empfohlen.
- BG-Schnittstelle.
- DATEV-Banking: ueberweisung Loehne und SV.

### Phase 5 — Sondermodule

- BG-Lohnnachweis.
- bAV mit Versicherer-Schnittstelle.
- JobRad mit Leasing-Vertraegen.
- Werkstudent mit Immatrikulations-Pruefung.

### Phase 6 — Updates und Wartung

- Jaehrliche Updates zum 1. Januar (Beitragssaetze, BBG).
- ITSG-Zertifikate erneuern.
- Mandanten-Stammdaten aktualisieren.

## Output

- Konfiguriertes Lohnprogramm.
- Mandanten gepflegt.
- Schnittstellen aktiv.

## Strategie und Praxis-Tipps

- LODAS ist Standard fuer StB-Kanzleien — multimandantenfaehig.
- Lohn und Gehalt fuer Mandanten, die selbst Loehne abrechnen, aber StB-Schnittstelle wuenschen.
- Schulungen DATEV-Akademie jaehrlich empfehlenswert.
- Bei Aenderungen am ELStAM-Verfahren: Updates zwingend.

## Querverweise

- `stb-lohn-mandantenaufnahme-onboarding` — Onboarding.
- `stb-lohn-lohnsteuer-monatsabschluss` — Monatsabschluss.
- `stb-lohn-sv-meldungen-dakota-svnet` — sv.net.
- `stb-lohn-meldungen-sv-elstam-zugang` — ELStAM.

## Quellen und Updates

Stand: 05/2026.

- DATEV LODAS und Lohn und Gehalt Programm- und Bedienungs-Dokumentation (aktuelle Version pruefen).
- DATEV-Programm-Updates jaehrlich (Stand 01.01.) sowie unterjaehrige Reform-Updates (SV-Beitragsbemessungsgrenzen, Mindestlohn).
- Verifikations-Hinweis: konkrete Programmpfade und Menue-Bezeichnungen ggf. abweichend in aktueller DATEV-Version.


## Qualitäts-Hardening

- Arbeite aktennah: Tatsachen, Belege, Fristen, Zuständigkeit und gewünschtes Arbeitsprodukt zuerst klären.
- Keine Rechtsprechung aus Modellwissen zitieren. Jede Entscheidung vor Ausgabe mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei oder amtlich prüfbarer Quelle absichern.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate. Literatur nur verwenden, wenn der Nutzer sie bereitstellt oder ein lizenzierter Live-Zugriff im konkreten Arbeitsschritt dokumentiert ist.
- Wenn eine Quelle, Randnummer, Behördenpraxis oder Frist nicht sicher geprüft ist, sichtbar als Prüfpunkt markieren und keine Scheinpräzision erzeugen.
- Ergebnisse so liefern, dass sie sofort weiterverwendbar sind: Kurzbild, Prüfpfad, Risikoampel, Lückenliste und konkrete nächste Schritte.
