---
name: kaltstart-interview
description: "Kaltstart-Interview fuer das Fortbestehensprognose-Plugin. Stellt fest wer das Plugin nutzt (Geschaeftsfuehrer / Vorstand / Gesellschafter mit Eigenverantwortung / Finanzleiter mit Mandat) wer der Anwaltliche und steuerliche Ansprechpartner ist welches Geschaeftsjahr und welche Rechtsform vorliegt und welche Anwendung der Buchhaltungs- und Bilanzierungssysteme. Schreibt das Profil unter ~/.claude/plugins/config/claude-fuer-deutsches-recht/fortbestehensprognose/CLAUDE.md. Disclaimer Selbstdokumentation ersetzt nicht Insolvenzrechtsanwalt."
---

# /fortbestehensprognose:kaltstart-interview

## Disclaimer (Schluesselstelle)

Dieses Plugin liefert eine **Selbstdokumentation** der Fortbestehensprognose nach § 19 Abs. 2 InsO. Es ersetzt **nicht** die anwaltliche Pruefung durch einen Insolvenzrechtler bei Anzeichen fuer Insolvenzreife. Die Antragspflicht nach § 15a InsO (drei Wochen bei Zahlungsunfaehigkeit, sechs Wochen bei Ueberschuldung) ist persoenliche Pflicht des Geschaeftsleiters mit strafrechtlicher Bewehrung (§ 15a Abs. 4 InsO) und Haftungsrisiko (§ 15b InsO, fruehere § 64 GmbHG). Im Zweifel **vor** Ablauf der Frist Insolvenzanwalt konsultieren.

## Ablauf

1. Datei `~/.claude/plugins/config/claude-fuer-deutsches-recht/fortbestehensprognose/CLAUDE.md` pruefen.
2. Falls befuellt: bestaetigen, gegebenenfalls --redo fuer Neu-Interview.
3. Andernfalls Interview unten ausfuehren.

## Interview

### 1. Wer nutzt das Plugin

- **Rolle:** Geschaeftsfuehrer GmbH / Vorstand AG / Geschaeftsleiter Personengesellschaft / Gesellschafter mit Eigenverantwortung / Finanzleiter / sonst?
- **Persoenliche Antragspflicht** nach § 15a InsO? Wer ist Geschaeftsleiter mit Antragspflicht? Bei mehreren ist jeder einzeln verpflichtet (BGH-Rspr.).
- **Anwaltlicher Ansprechpartner** (Insolvenzanwalt) — Name, Erreichbarkeit. Bei negativer Prognose sofort eskalieren.
- **Steuerlicher Ansprechpartner** (Steuerberater / Wirtschaftspruefer) — Name, Erreichbarkeit.

### 2. Unternehmensprofil

- **Rechtsform** GmbH AG GmbH und Co. KG Aktiengesellschaft Personengesellschaft.
- **Stammkapital** (relevant fuer Mantel- bzw. Anhalt-Insolvenzreife).
- **Geschaeftsjahr** und Bilanzstichtag.
- **Branche** (relevant fuer Plausibilisierung).
- **Beschaeftigte** Anzahl.
- **Umsatz** im laufenden Jahr und Vorjahr.

### 3. Buchhaltung und Bilanzierung

- **Buchhaltungssoftware** DATEV Lexware SAP sevDesk sonst.
- **Bilanzierungsstandard** HGB / IFRS / Mischung.
- **Letzter Jahresabschluss** Datum.
- **Aktueller Stand** unterjaehrige BWA SuSa Konzernreporting verfuegbar.

### 4. Ausgangslage

- Was hat den Anlass gegeben fuer diese Pruefung? (siehe Skill `ausloesendes-ereignis-erfassen`)
- Bilanzielle Ueberschuldung bereits festgestellt? (Aktiva kleiner als Passiva?)
- Stille Reserven oder Lasten vorhanden?
- Aktuelle Liquiditaetslage subjektiv: angespannt? ausreichend? bereits ueberschritten?

### 5. Eskalationspfad

- **Ab welchem Befund** wird sofort der Insolvenzanwalt eingeschaltet? Empfehlung: bei jedem 🔴-Flag im Verlauf.
- **Drei-Wochen-Frist** § 15a InsO bei Zahlungsunfaehigkeit (§ 17 InsO) ist persoenliche Pflicht. **Sechs Wochen** bei Ueberschuldung (§ 19 InsO seit SanInsFoG 2021).
- **Kein Aufschieben** wegen Sanierungsverhandlungen — die Frist beginnt mit Eintritt der Insolvenzreife (objektives Kriterium).

### 6. Standort

- **Sitz und Insolvenzgericht** (Belegenheits-AG nach § 3 InsO).
- **Bundesland** (relevant fuer Justiznetzwerk).

## Rechtlicher Rahmen

- **InsO** § 15a (Antragspflicht), § 15b (Zahlungsverbot ab Insolvenzreife), § 17 (Zahlungsunfaehigkeit), § 18 (drohende Zahlungsunfaehigkeit, Prognose 24 Monate seit 2021), § 19 (Ueberschuldung, Fortbestehensprognose 12 Monate seit 2021).
- **StaRUG** §§ 29 ff. (Restrukturierungsrahmen vor Insolvenzreife), § 102 (Hinweispflicht Steuerberater).
- **IDW S 11** Beurteilung des Vorliegens von Insolvenzeroeffnungsgruenden.
- **IDW S 6** Anforderungen an Sanierungskonzepte.
- **GmbHG** § 64 a.F. — heute § 15b InsO.

## Ausgabe

Profil wird geschrieben. Empfohlene naechste Skills:

1. `/fortbestehensprognose:ausloesendes-ereignis-erfassen` — Anlass und Vorinformation
2. `/fortbestehensprognose:bilanzieller-status-aufnehmen` — Ausgangsfeststellung
3. `/fortbestehensprognose:annahmen-sammeln-fortfuehrung` — Prognoseannahmen
4. (parallel) `/liquiditaetsplanung` — fuer die rollierende 12-Monats-Liquiditaet

Bei aktuten Anzeichen fuer Zahlungsunfaehigkeit (Liquiditaetsluecke ueber 10 Prozent seit mehr als drei Wochen) **sofort** Insolvenzanwalt einschalten und mit Plugin `insolvenzrecht` arbeiten — nicht in diesem Plugin weiterarbeiten.
