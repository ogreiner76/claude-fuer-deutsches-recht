---
name: workflow-redteam-qualitygate
description: "Red-Team Qualitätsgate: abschließende Qualitätskontrolle vor Ausgabe eines Schriftsatzes, Memos, Mandantenbriefs oder Vergleichs — Quellenverifikation, Gegenargument-Check, Fristencheck, Scheingenauigkeit-Scan, Mandatsziel-Abgleich."
---

# Workflow: Red-Team Qualitätsgate

## Zweck
Abschließende Qualitätskontrolle, bevor ein Produkt (Schriftsatz, Memo, Brief, Vergleich) den Skill verlässt. Dieser Workflow findet Fehler, Lücken und Scheingenauigkeiten — bevor der Gegner oder das Gericht sie findet.

## Kaltstart
Wenn ein Dokument zur Qualitätskontrolle vorliegt:

1. **Was ist das Dokument?** Schriftsatz (Klage, Schriftsatz, Berufung), Memo, Mandantenbrief, Vergleich?
2. **Für wen?** Gericht, Mandant, Gegenseite, Akte?
3. **Was ist das Ziel des Dokuments?** Klage einlegen, informieren, Vergleich schließen, Qualitätsnachweis?
4. **Was sind die 3 stärksten Angriffspunkte der Gegenseite?**

## Gate 1: Quellenverifikation

**Prüfaufgabe:** Sind alle Normen und Urteile korrekt zitiert und frei prüfbar?

Checkliste:
- [ ] Alle Paragrafenzitate mit Norm und Fassung korrekt?
- [ ] Alle Aktenzeichen auf bundesarbeitsgericht.de oder openjur.de verifiziert?
- [ ] Kein BeckRS als alleinige Fundstelle?
- [ ] Keine KI-generierten Aktenzeichen ohne verifizierten Link?
- [ ] EuGH-Zitate auf curia.europa.eu geprüft?
- [ ] Normtexte aktuell? (Letzte Änderung bekannt?)

**Fehler-Kategorie:** Rot — kein Dokument mit unverifizierten Quellen ausgeben.

## Gate 2: Scheingenauigkeit-Scan

**Prüfaufgabe:** Gibt es Aussagen, die präzise klingen, aber ohne Grundlage sind?

Typische Scheingenauigkeiten:
- Pauschale Angaben zu BA-Praxis oder Sperrzeiten ohne BA-Quellennachweis
- BAG-Entscheidungen aus Modellwissen ohne Verifikation
- Kostenangaben ohne RVG-Normprüfung
- Formulierungen wie „nach ständiger BAG-Rechtsprechung" ohne konkrete Fundstelle

**Fehler-Kategorie:** Gelb bis Rot — je nach Tragweite der Aussage.

## Gate 3: Beweislast-Check

**Prüfaufgabe:** Sind alle Behauptungen durch Beweismittel unterlegt oder als Beweisangebote formuliert?

Checkliste:
- [ ] Zugangsdatum der Kündigung belegt?
- [ ] BR-Anhörung: Nachweis vorhanden oder Beweisangebot formuliert?
- [ ] Sozialauswahl: Rüge formuliert; Aufklärungsantrag angeboten?
- [ ] Sachverhalt-Angaben durch Urkunden oder Zeugen belegt?

**Fehler-Kategorie:** Gelb — fehlende Beweisangebote schwächen den Schriftsatz.

## Gate 4: Fristencheck

**Prüfaufgabe:** Sind alle laufenden Fristen im Dokument korrekt berücksichtigt?

Checkliste:
- [ ] Klagefrist § 4 KSchG korrekt berechnet und erwähnt?
- [ ] Berufungsfrist § 66 ArbGG wenn relevant?
- [ ] AGG-Frist § 15 Abs. 4 AGG wenn relevant?
- [ ] Ausschlussfristen im Vertrag oder TV beachtet?

**Fehler-Kategorie:** Rot — Fristfehler können irreversibel sein.

## Gate 5: Gegenargument-Simulation

**Prüfaufgabe:** Was wird die Gegenseite angreifen?

Strukturiertes Red-Team:
1. Was ist das schwächste Argument im Dokument?
2. Welche Tatsachenbehauptung ist am leichtesten zu bestreiten?
3. Gibt es eine alternative rechtliche Einordnung, die für die Gegenseite günstiger ist?
4. Gibt es eine prozessuale Falle (Fristversäumnis, fehlendes Beweisangebot, falsche Anträge)?

**Output nach Gate 5:**
> „Die 2 schwächsten Punkte sind: (1) [Punkt] — Gegner wird [Angriff] vorbringen. Reaktion: [Vorab-Antwort im Schriftsatz]. (2) [Punkt] — [gleich]."

## Gate 6: Mandatsziel-Abgleich

**Prüfaufgabe:** Dient das Dokument tatsächlich dem Mandatsziel?

Checkliste:
- [ ] Ist das Mandatsziel (Bestandsschutz / Abfindung / Schadensersatz) klar erkennbar im Dokument?
- [ ] Widerspricht das Dokument einem früheren Schriftsatz oder einer Aussage des Mandanten?
- [ ] Enthält das Dokument Aussagen, die das Mandatsziel gefährden?

## Gate 7: Formelle Vollständigkeit

**Prüfaufgabe:** Ist das Dokument vollständig und einreichungsfertig?

Checkliste:
- [ ] Gericht, Aktenzeichen, Parteienbezeichnung korrekt?
- [ ] Unterschrift des Anwalts (bei Schriftsatz)?
- [ ] Anlagen nummeriert und beigefügt?
- [ ] beA-Einreichung vorbereitet? qeS oder einfache Signatur aus eigenem beA?

## Gesamt-Ampel nach Allen Gates

| Gates bestanden | Gesamtampel | Freigabe |
|---|---|---|
| Alle 7 | Grün | Dokument kann ausgegeben werden |
| 6 von 7, kein Rot | Gelb | Mit Kommentar zu offenem Punkt ausgeben |
| 1 Rot | Rot | Nicht ausgeben; erst korrigieren |
| Mehrere Rot | Rot | Vollständige Überarbeitung erforderlich |

## Anschluss-Skills
- `spezial-aktenzeichen-red-team-und-qualitaetskontrolle` für Aktenzeichen-spezifisches Red-Team
- `workflow-rechtsquellen-livecheck` für Quellenverifikation
- `spezial-quelle-beweislast-und-darlegungslast` für Quellenregeln

## Quellenregel
- Normtext live prüfen auf [gesetze-im-internet.de](https://www.gesetze-im-internet.de).
- BAG: [bundesarbeitsgericht.de](https://www.bundesarbeitsgericht.de).
- EuGH: [curia.europa.eu](https://curia.europa.eu).
- Keine Aktenzeichen aus Modellwissen ohne Verifikation.
- Annahmen explizit kennzeichnen.

## Was dieser Skill nicht macht
- Kein Ersatz für vollständige anwaltliche Prüfung.
- Keine Garantie für Fehlerfreiheit; menschliche Kontrolle bleibt zwingend.
