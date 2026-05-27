---
name: grosskanzlei-corporate-ma-billing-narratives
description: "Big-Law Billing Narratives fuer Corporate-M&A: Erstellt deal-taugliche Time Narratives, Phasenbudgets, Workstream-Rechnungen, Cap- und Success-Fee-Hinweise sowie Matter-Controlling nach RVG und Stundenhonorar-Vereinbarung (§ 3a RVG). GoBD, XRechnung und ZUGFeRD-Anforderungen integriert."
---

# Big-Law Billing Narratives (Corporate M&A)

## Triage zu Beginn

Vor der Erstellung von Billing Narratives klaeren:

1. **Honorarvereinbarung vorhanden?** Stundenhonorar (§ 3a RVG) oder Pauschalhonorar oder Success Fee oder Cap + Success Fee? Kein Narrative ohne klar definiertes Abrechnungsmodell.
2. **Taetigkeiten vollstaendig erfasst?** Alle Time Entries nach Phase, Workstream und Deliverable vorliegend? Fehlende Entries flaggen.
3. **Budgetstatus geprueft?** Aktuelles WIP gegen Budget halten; Scope Creep und Abweichungen markieren bevor Narrative erstellt wird.
4. **Mandantenvertraulichkeit:** Narrative darf kein Mandatsgeheimnis unnoetig offen legen (§ 43a Abs. 2 BRAO); Formulierungen muessen pruefbar aber nicht erlaeuternd sein.
5. **Rechnungsreife?** Sind alle Bedingungen erfuellt (Leistungsstand, SPA-Meilenstein, vereinbarter Faelligkeitspunkt)? Bei Unsicherheit nicht abrechnen.
6. **E-Rechnung erforderlich?** Oeffentlicher Auftraggeber oder SPA-Klausel zu XRechnung/ZUGFeRD? Dann an `grosskanzlei-ma-erechnung-gobd` uebergeben.

## Zentrale Normen

§ 3a RVG (Stundenhonorar-Vereinbarung; Formerfordernis Textform; Verbraucherschutz) — § 49b BRAO (Vergaetungsvereinbarung; Verbot unzulaessiger Erfolgshonorare) — § 4a RVG (Erfolgshonorar; Zulassungsvoraussetzungen) — § 10 UStG (Umsatzsteuerbarkeit; Leistungszeitpunkt) — §§ 14, 33 UStG (Rechnungspflichtangaben) — § 146 AO, §§ 238 ff. HGB (GoBD: Buchfuehrungspflicht; Aufbewahrungspflicht 10 Jahre) — § 50 BRAO (Handakten; Aufbewahrungspflicht 5 Jahre) — Art. 3 RL 2014/55/EU (E-Rechnungspflicht oeffentliche Auftraggeber)

## Aktuelle Rechtsprechung

- BGH, Urt. v. 05.06.2014 – IX ZR 137/12, NJW 2014, 2653 Rn. 18 — Anwaltliche Honorarvereinbarung nach § 3a RVG: Textformerfordernis zwingend; muendliche Abrede genuegt auch bei Kaufleuten nicht; Vereinbarung ist bei Formverstos nichtig, Anwalt kann nur RVG-Gebuehren verlangen.
- BGH, Urt. v. 23.10.2003 – IX ZR 27/02, NJW 2004, 1169 Rn. 12 — Erfolgshonorar unzulaessig bei unklarer Vereinbarung; § 49b Abs. 2 BRAO: Erfolgshonorar nur bei Einzel-/Verbraucherfall nach § 4a RVG zulaessig.
- BGH, Urt. v. 30.09.2010 – IX ZR 70/09, NJW 2011, 63 Rn. 15 — Abrechenbarkeit eines M&A-Beraterhonorars: Leistung muss nachweisbar erbracht sein; Time Sheets als Beweismittel; Pauschalabrede ohne Leistungsnachweise ist riskant.
- BFH, Urt. v. 22.04.2015 – XI R 10/14, BStBl. II 2015, 847 — Rechnungspflichtangaben nach § 14 UStG: Bei fehlerhafter Rechnung kein Vorsteuerabzug fuer Mandant; Kanzlei haftet.

## Kommentarliteratur

- Mayer, in: Gerold/Schmidt, RVG, 26. Aufl. 2023, § 3a Rn. 5 ff. (Stundenhonorar; Formerfordernis; Wirksamkeitsvoraussetzungen).
- Hartung, in: Hartung/Scharmer, BRAO, 7. Aufl. 2024, § 49b Rn. 15 ff. (Verguetungsvereinbarung; Erfolgshonorar; Verbote).
- Sterzinger, in: Tipke/Kruse, AO/FGO, § 146 AO Rn. 5 ff. (GoBD; Buchfuehrungspflicht bei Kanzleien).

## Billing-Narrative-Struktur fuer M&A-Deals

### Time-Entry-Kategorien

| Phase | Workstream | Typische Taetigkeit |
|---|---|---|
| Pre-DD | Transaction Setup | Mandatsanlage, NDA-Verhandlung, VDR-Einrichtung |
| Due Diligence | Legal DD | Vertragsreview, Issue-Extraktion, Red-Flag-Report |
| Due Diligence | Corporate DD | Handelsregister-Auswertung, Gesellschafterliste |
| Signing | SPA-Verhandlung | Vertragsverhandlung, Kommentierung, Signing-Prep |
| Closing | Vollzug | CP-Tracking, Closing-Actions, Notartermin |
| Post-Closing | PMI | Vertragsuebernahmen, § 613a BGB, Gesellschafterliste |

### Narrative-Formulierungsregeln

1. **Mandantentauglich:** Keine Rechtsbegriffe ohne Erklaerung; kein unnoetig detaillierter Sachverhalt.
2. **Pruefbar:** Jede Taetigkeit muss einem Workstream und Deliverable zugeordnet sein.
3. **Vertraulich:** Kein Inhalt aus privilegierten Dokumenten (anwaltliche Stellungnahmen, DD-Reports) in externe Narrative.
4. **Zeitgenau:** Time Entries tagesgenau; keine rueckwirkenden Grosskorrekturen ohne Erklaerung.
5. **Budget-Delta markieren:** Abweichungen > 10 % zum vereinbarten Budget kommentieren.

### Narrative-Muster nach Workstream

```
Due Diligence — Legal: Vertragsreview (Commercial Contracts)
Pruefen und Analysieren von [N] Lieferantenvertraegen im Datenraum; Erstellung eines
Issue-Summary fuer [N] Material-Contract-Eintraege; Identifizierung von [N] Change-of-
Control-Klauseln mit Zustimmungserfordernis; Abstimmung mit Deal-Team zu CP-Implikationen.
[N.N h]
```

```
Signing — SPA-Verhandlung: Kommentierung § [Klausel] / Garantiekatalog
Erarbeitung der Kanzleiposition zu Abschnitt [X] des SPA-Entwurfs (Garantiekatalog);
Abstimmung mit Mandant zu akzeptablem Risikoprofil; Einarbeitung in Track-Changes-Version;
Verhandlungssitzung [DATUM] mit Gegenseite.
[N.N h]
```

## Schritt-fuer-Schritt-Workflow

1. **Time Entries importieren:** Alle Zeiteintragungen fuer den Abrechnungszeitraum nach Phase und Workstream sortieren.
2. **Budget-Abgleich:** WIP gegen vereinbartes Budget halten; Abweichungen > 10 % markieren und begruenden.
3. **Narrative verfassen:** Pro Workstream ein Narrative-Block nach Formulierungsregeln oben.
4. **Mandantenvertraulichkeit pruefen:** Kein Mandatsgeheimnis unnoetig offen gelegt? Narratives mandantentauglich formuliert?
5. **Rechnungspflichtangaben pruefen:** § 14 UStG-Angaben vollstaendig (Leistungsbeschreibung, Zeitraum, Steuernummer, USt-ID)?
6. **Cap-/Success-Fee-Check:** Gesamthonorar gegen vereinbarten Cap pruefen; Success-Fee-Bedingungen eingetreten?
7. **E-Rechnungspflicht pruefen:** Oeffentlicher Auftraggeber? XRechnung/ZUGFeRD erforderlich? → an `grosskanzlei-ma-erechnung-gobd` uebergeben.
8. **Rechnungsreife-Ampel ausgeben:** Gruen (alle Bedingungen erfuellt), Gelb (offene Punkte), Rot (Rechnung zurueckhalten).

## Output-Template

**Adressat:** Mandant / Matter-Controller — Tonfall: knapp, pruefbar, mandantentauglich

```
BILLING NARRATIVE LEDGER
Mandat: [MANDATSCODE] / [ZIELGESELLSCHAFT]
Abrechnungszeitraum: [DATUM] bis [DATUM]
Erstellt: [TT.MM.JJJJ]
Matter-Controller: [NAME]

> Vertraulich — Mandatsgeheimnis § 43a Abs. 2 BRAO.

--- BUDGET-STATUS ---
Vereinbartes Budget: [BETRAG EUR]
WIP aktuell: [BETRAG EUR]
Abweichung: [+ / - BETRAG EUR] ([%])
Scope-Creep-Flag: [KEIN / JA: BESCHREIBUNG]

--- TIME ENTRIES NACH WORKSTREAM ---

WORKSTREAM: Due Diligence — Legal
[DATUM] | [TIMEKEEPER] | [N.N h] | [NARRATIVE]
[DATUM] | [TIMEKEEPER] | [N.N h] | [NARRATIVE]
Gesamt Workstream: [N.N h] / [BETRAG EUR]

WORKSTREAM: SPA-Verhandlung
[Analog]
Gesamt Workstream: [N.N h] / [BETRAG EUR]

WORKSTREAM: Closing
[Analog]
Gesamt Workstream: [N.N h] / [BETRAG EUR]

--- RECHNUNGS-ZUSAMMENFASSUNG ---
Honorar netto: [BETRAG EUR]
Umsatzsteuer 19 %: [BETRAG EUR]
Auslagen: [BETRAG EUR]
Summe brutto: [BETRAG EUR]
Cap-Pruefung: [UNTER CAP / CAP ERREICHT]
Success Fee: [NICHT FAELLIG / FAELLIG: BETRAG EUR]

--- RECHNUNGSREIFE-AMPEL ---
Status: [GRUEN / GELB / ROT]
Offene Punkte: [KEINE / LISTE]
Freigabe durch: [PARTNER-NAME]

--- E-RECHNUNG ---
XRechnung/ZUGFeRD erforderlich: [JA → Uebergabe grosskanzlei-ma-erechnung-gobd / NEIN]
```

## Rote Schwellen

- **Honorarvereinbarung § 3a RVG muendlich oder fehlend** — Formverstos; Anwalt kann nur RVG-Pflichtgebuehren verlangen; Vereinbarung unverzueglich schriftlich nachholen.
- **Narrative enthaelt Mandatsgeheimnis** — § 43a Abs. 2 BRAO; Formulierungen vor Versand pruefen; keine anwaltlichen Stellungnahmen, keine Parteiinterna in externen Narratives.
- **WIP ueberschreitet Cap ohne Mandanteninformation** — Haftungsrisiko; Mandant informieren und Scope-Abgleich durchfuehren bevor weitergearbeitet wird.
- **Rechnungspflichtangaben § 14 UStG unvollstaendig** — kein Vorsteuerabzug fuer Mandant; Rechnung korrigieren; Mahngebueehr-Risiko.
- **Leistung ohne Akte / Workstream** — GoBD-Verstos; Time Entry kann nicht verbucht werden; Nacherfassung nur mit Erklaerung.

## Arbeitsmodus

- Taetigkeiten nach Phase, Workstream und Deliverable erfassen.
- Narratives knapp, mandantentauglich und pruefbar formulieren.
- Budgetabweichungen und Scope Creep markieren.
- WIP, Cap, Success Fee, Auslagen, Rabatte und Steuerlogik als eigene Pruefpunkte fuehren.
- Bei Rechnungsreife an `grosskanzlei-ma-erechnung-gobd` uebergeben.

## Standardausgabe

- Billing Narrative Ledger.
- Budgetstatus nach Workstream.
- Rechnungsreife-Ampel.
- Uebergabe an E-Rechnung/GoBD mit Belegkette.

## Vorlagen

- assets/templates/billing-narrative-ledger.md
- assets/templates/erechnung-gobd-billing.md

## Quellen und Vertiefung

- § 3a RVG (Stundenhonorar-Vereinbarung; Formerfordernis)
- § 49b BRAO (Vergaetungsvereinbarung)
- § 4a RVG (Erfolgshonorar)
- § 14 UStG (Rechnungspflichtangaben)
- § 146 AO / §§ 238 ff. HGB (GoBD; Buchfuehrungspflicht)
- BGH: `BGH, Urt. v. 05.06.2014 – IX ZR 137/12, NJW 2014, 2653 Rn. 18`
- Mayer, in: Gerold/Schmidt, RVG, 26. Aufl. 2023, § 3a Rn. 5 ff.

Hinweis: Dieser Skill ersetzt keine anwaltliche Beratung im konkreten Einzelfall.
