---
name: stb-jahresabschluss-bestandskonten-abstimmung
description: "Bestandskonten-Abstimmung zum Jahresabschluss. Anwendungsfall Endbestaende Bank Kasse Forderungen Verbindlichkeiten Anlagen Eigenkapital abstimmen Inventur-Werte einarbeiten. Methodik Saldenabstimmung Vergleich. Output abgestimmte Bestandskonten."
---

# Bestandskonten-Abstimmung zum Jahresabschluss

## V90 Fachkern — Steuerrecht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `Bestandskonten-Abstimmung zum Jahresabschluss` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** AO, EStG, KStG, GewStG, UStG, GrEStG, UmwStG, AStG, FZulG, MinStG; BMF-Schreiben nur mit Datum, Titel und offizieller BMF-URL verwenden.
- **Verifizierte Anker:** BMF-Schreiben vom 15.10.2025 zur obligatorischen E-Rechnung und UStAE-Anpassung; BMF-Seite Forschungszulage mit Hinweis zu Antrags-/Festsetzungslogik und BMF-Schreiben vom 07.02.2023; BMF/BZSt-Datensatzbeschreibung vom 05.08.2025 für Mindeststeuer-Berichte; BMF-Schreiben vom 25.05.2023 zu § 6a GrEStG; BMF-Schreiben vom 02.01.2025/01.08.2025 zum Umwandlungssteuer-Anwendungserlass live prüfen.
- **Arbeitsmodus:** Erst Steuerart, Zeitraum, Verwaltungsstand, Frist/Festsetzung, Zuständigkeit, Form/Portal und Beleglage klären; dann BMF-Verwaltungslinie von BFH-Rechtsprechung und Gesetz trennen.
- **Outputpflicht:** Steuerartenmatrix, BMF-Radar, Einspruchsbaustein, ELSTER-/Portal-To-do, Risikoampel, DBA-/GrESt-/USt-Tabelle oder Mandantenmemo.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


## Kernsachverhalt

Vor dem JA-Endlauf muessen alle Bestandskonten (Klasse 0-3 SKR 03 bzw. entsprechende SKR-04-Konten) abgestimmt sein: Bank gegen Bankauszug, Kasse gegen Kassenbericht, Forderungen gegen Personenkonten, Anlagen gegen Anlagenspiegel, Eigenkapital gegen Gesellschaftervereinbarungen. Differenzen muessen aufgeklaert werden.

## Kaltstart-Rueckfragen

1. Welche Bestandskonten sind vorhanden?
2. Welche Saldenabstimmungs-Antworten liegen vor?
3. Liegen Bankbestaetigungen vor (Saldenbestaetigung)?
4. Anlagenspiegel mit Hauptbuch abgestimmt?
5. Liegen Inventur-Werte vor?
6. Welche Korrekturen aus der Saldenabstimmung?
7. Welche Sondervorgaenge (Kapitalbewegungen)?
8. Welche Werterhellung nach Stichtag?

## Rechtlicher Rahmen

### Primaernormen

**§ 240 HGB** — Inventarpflicht.

**§ 252 HGB** — Bewertungsgrundsaetze.

**§ 253 HGB** — Bewertung Vermoegen.

**§ 246 HGB** — Vollstaendigkeit.

**§ 5 EStG** — Massgeblichkeit Handelsbilanz.

### Standards

- IDW PS 480.
- IDW PS 302 (Saldenbestaetigungen).

## Workflow

### Phase 1 — Bestandskonten-Inventur

| Konto | Abstimmungs-Basis |
|---|---|
| Bank | Bankauszuege, Saldenbestaetigung Bank |
| Kasse | Kassenbericht, Z-Bons |
| Forderungen LuL | Debitoren-OPOS, Saldenbestaetigung Kunden |
| Sonstige Forderungen | Einzelnachweis |
| Vorraete | Inventur-Protokoll |
| Anlagen | Anlagenspiegel |
| Verbindlichkeiten LuL | Kreditoren-OPOS, Saldenbestaetigung Lieferanten |
| Bank-Verbindlichkeiten | Darlehensvertraege, Saldenbestaetigung Bank |
| Steuerverbindlichkeiten | FA-Bescheide |
| SV-Verbindlichkeiten | KK-Beitragsabrechnungen |
| Rueckstellungen | Bewertungsgrundlagen |
| Eigenkapital | Gesellschaftervereinbarungen, Vorjahresvortrag |

### Phase 2 — Differenzen klaeren

- Bei Hauptbuch-Nebenbuch-Differenzen: Personenkonto-Pflege.
- Bei Bankabstimmungs-Differenzen: Cut-off-Buchungen.
- Bei Vorraete-Differenzen: Inventur-Pruefung.

### Phase 3 — Anpassungs-Buchungen

- Endgueltige AfA-Buchung.
- Periodenabgrenzungs-Buchungen.
- Rueckstellungs-Buchungen.

### Phase 4 — Werterhellung

- Wesentliche Ereignisse zwischen Stichtag und Aufstellung pruefen.
- Insolvenz-Antraege bei Schuldnern (Forderungsausfall-Risiko).
- Wesentliche Vertragsabschluesse (Auswirkung auf Risiko/Rueckstellung).

### Phase 5 — Bestand-Bewertung

- Forderungen: Einzelwertberichtigung bei zweifelhaften Schuldnern.
- Vorraete: Niederstwertprinzip; Veraltete Bestaende.
- Anlagen: Ausserplanmaessige Abschreibung bei dauerhafter Wertminderung.

### Phase 6 — Endgueltige Bilanz

- Bestandskonten-Endsalden bilden Bilanzposten.
- Endsalden in Bilanz uebernehmen.
- Konsistenzcheck.

## Output

- Abgestimmte Bestandskonten.
- Anpassungs-Buchungen dokumentiert.
- Bilanz vorbereitet.

## Strategie und Praxis-Tipps

- Bestandskonten-Abstimmung ist Pflicht — nicht abgekuerzte Pruefung.
- Bei Pruefungspflicht: WP fordert Abstimmung formell.
- Bei groesseren Mandanten: Saldenabstimmung mit Lieferanten/Kunden Standard.
- Werterhellung-Pruefung kann erhebliche Auswirkungen haben.

## Querverweise

- `stb-susa-saldenabstimmung-bestaetigung` — Saldenabstimmung.
- `stb-jahresabschluss-vorbereitung-stichtag` — JA-Vorbereitung.
- `stb-jahresabschluss-warenbestand-inventur` — Inventur.
- `stb-jahresabschluss-anlagenverzeichnis-afa` — AfA.
- `stb-jahresabschluss-rueckstellungen-bewertung` — Rueckstellungen.

## Quellen und Updates

Stand: 05/2026.

- HGB §§ 240, 246, 252, 253.
- EStG § 5.
- IDW PS 480, IDW PS 302.


## Qualitäts-Hardening

- Arbeite aktennah: Tatsachen, Belege, Fristen, Zuständigkeit und gewünschtes Arbeitsprodukt zuerst klären.
- Keine Rechtsprechung aus Modellwissen zitieren. Jede Entscheidung vor Ausgabe mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei oder amtlich prüfbarer Quelle absichern.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate. Literatur nur verwenden, wenn der Nutzer sie bereitstellt oder ein lizenzierter Live-Zugriff im konkreten Arbeitsschritt dokumentiert ist.
- Wenn eine Quelle, Randnummer, Behördenpraxis oder Frist nicht sicher geprüft ist, sichtbar als Prüfpunkt markieren und keine Scheinpräzision erzeugen.
- Ergebnisse so liefern, dass sie sofort weiterverwendbar sind: Kurzbild, Prüfpfad, Risikoampel, Lückenliste und konkrete nächste Schritte.
