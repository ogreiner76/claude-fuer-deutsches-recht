---
name: mandantenakte-anlegen
description: Legt eine Mandantenakte nach Kanzleikonvention an. Erfasst Stammdaten Bevollmaechtigte Mandatsumfang Konfliktpruefung (§ 43a Abs. 4 BRAO § 3 BORA) Datenschutzhinweis (Art. 13 DSGVO) Geldwaesche-Identifizierung (§§ 10 11 GwG) Honorarvereinbarung oder RVG-Hinweis. Erzeugt Aktenstruktur unter mandate/Aktenzeichen/ mit Standardunterordnern Vollmachts-Entwurf Datenschutzhinweis Geldwaesche-Pruefbeleg. Eintrag im Mandantenstamm. Verbindung zum Fristenbuch falls Fristen mitgeliefert.
---

# Mandantenakte anlegen

## Konfliktpruefung (§ 43a Abs. 4 BRAO)

**Vor jeder Mandatsannahme** Pflichtschritt:

- Pruefung im Mandantenstamm ob Mandat gegen einen bisherigen oder laufenden Mandanten der Kanzlei.
- Pruefung ob Mandatsannahme gegen § 3 BORA (widerstreitende Interessen) verstoesst.
- Bei Konflikt: Mandat ablehnen oder schriftliches Einverstaendnis aller Betroffenen.
- Pruefer-Eintrag mit Datum Initialen.

## Aktennummernsystem

Empfehlung:

`<Jahr>/<lfd. Nr.>` (z. B. `2026/0042`)

oder

`<RG>-<Jahr>-<Nr>` (z. B. `Z-2026-0042` fuer Zivilrecht).

## Verzeichnisstruktur

Unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/kanzlei-cowork/mandate/<az>/`:

```
01_stammdaten/
  mandatsblatt.md
  vollmacht.docx
  vollmacht-unterschrieben.pdf
  datenschutzhinweis.md
  gwg-identifizierung.pdf
  konfliktpruefung.md
  honorarvereinbarung.docx (falls Vereinbarung)
02_eingaenge/
03_schriftsaetze/
04_anlagen/
05_fristen/
06_honorar/
  rechnungen/
  zahlungseingang.yaml
07_korrespondenz_mandant/
08_korrespondenz_dritte/
09_aktennotizen/
_archiv/
```

## Mandatsblatt

```yaml
mandat-az: 2026/0042
mandat-eroeffnet: 2026-05-20
zustaendiger-anwalt: RA Mueller
sekretariat: Frau Schmidt

mandant:
  typ: juristische-person  # juristische-person / natuerliche-person / ehepaare-vergleichsweise
  name: Mueller GmbH
  anschrift: ...
  rechtsform: GmbH
  vertretungsberechtigte: Hans Mueller (Geschaeftsfuehrer)
  registergericht: HRB ... AG Muenchen
  ust-id: DE...
  steuernummer: ...

ansprechpartner:
  name: Hans Mueller
  funktion: Geschaeftsfuehrer
  telefon: ...
  e-mail: ...

mandatsumfang:
  beschreibung: Verteidigung in Zivilrechtsstreit gegen ABC GmbH (Klage)
  rechtsgebiet: Zivilrecht / Vertragsrecht
  instanz: 1. Instanz LG Muenchen
  streitwert: 35.000 EUR

honorar:
  basis: rvg  # rvg / vereinbarung
  stundensatz: 320  # bei Vereinbarung
  pkh-pruefung: nein

konfliktpruefung:
  erfolgt-am: 2026-05-20
  ergebnis: kein-konflikt
  geprueft-von: RA Mueller
```

## Vollmacht

Vollmachtstext mit:

- Beauftragung des Rechtsanwalts der Kanzlei.
- Mandatsumfang konkret bezeichnet (Vorverfahren Klage Vergleich auch ueber Klageweg hinaus).
- Untervollmacht und Substituierung.
- Empfangsvollmacht fuer Zustellungen.
- beA-Vollmacht.
- Datum und Unterschrift des Mandanten.

## Datenschutzhinweis (Art. 13 DSGVO)

Standardhinweis mit:

- Identitaet des Verantwortlichen (Kanzlei).
- Zweck der Verarbeitung (Mandatsdurchfuehrung).
- Rechtsgrundlage (Art. 6 Abs. 1 lit. b DSGVO + § 50 BRAO Aktenfuehrung).
- Empfaenger (Gericht Behoerde Steuerberater Gegenseite — je nach Bedarf).
- Speicherdauer (mindestens 6 Jahre nach Mandatsende § 50 Abs. 1 BRAO).
- Betroffenenrechte (Auskunft Berichtigung Loeschung Widerspruch).

## Geldwaesche-Identifizierung (§§ 10 11 GwG)

Bei Mandaten die unter GwG fallen (z. B. Immobilientransaktionen Bargeldgeschaefte ab Schwellenwert):

- Identifizierung der natuerlichen Person mit Lichtbildausweis Kopie.
- Bei juristischer Person Registerauszug HRB plus wirtschaftlich Berechtigte nach Transparenzregister.
- Pruefung gegen Sanktionslisten EU und nationale.
- Pruefer-Eintrag mit Datum Initialen.

## Mandantenstamm-Eintrag

In `~/.claude/plugins/config/claude-fuer-deutsches-recht/kanzlei-cowork/mandantenstamm.yaml`:

```yaml
- mandant-id: M-00874
  name: Mueller GmbH
  typ: juristische-person
  mandate:
    - 2026/0042
  konfliktstatus: kein-konflikt
  letzte-pruefung: 2026-05-20
```

## Audit

- Aktenanlage mit Audit-Eintrag (Datum Anwalt Sekretariat).
- Aenderungen mit Audit-Trail.

## Ausgabe

- Vollstaendige Aktenstruktur.
- Mandatsblatt und Pflichtdokumente.
- Eintrag im Mandantenstamm.
- Hinweis ans Fristenbuch falls Fristen sofort relevant.
