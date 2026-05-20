---
name: kaltstart-interview
description: "Kaltstart-Interview fuer die sozialrechtliche Kanzlei. Erfragt Schwerpunktbereiche (Buergergeld SGB II / SGB IX Schwerbehinderung / SGB V Krankenversicherung / SGB XI Pflege / Asylbewerberleistungsgesetz) zustaendige Sozialgerichte typische Mandate (Bescheid-Widerspruch / Klage / Eilrechtsschutz) Prozesskostenhilfe-Quote Sekretariatslast Aktenstruktur-Konvention Versandwege (beA / Post / ePostfach Behoerde) Eskalation. Schreibt Profil nach ~/.claude/plugins/config/claude-fuer-deutsches-recht/sozialrecht-kanzlei/CLAUDE.md. Mit --redo neu interviewen."
---

# /sozialrecht-kanzlei:kaltstart-interview

## Ablauf

1. Konfigurationsdatei `~/.claude/plugins/config/claude-fuer-deutsches-recht/sozialrecht-kanzlei/CLAUDE.md` pruefen.
2. Falls vorhanden ohne Platzhalter: bestaetigen.
3. Andernfalls Interview unten durchfuehren.
4. Datei schreiben.
5. Zusammenfassung anzeigen mit naechsten Skill-Empfehlungen.

## Kaltstart-Interview

### 1. Rolle und Kanzlei

- **Rolle:** Fachanwalt fuer Sozialrecht / Rechtsanwalt mit sozialrechtlichem Schwerpunkt / Syndikus eines Sozialverbands / Beratungsstelle?
- **Kanzleigroesse:** Einzelkanzlei / Sozietaet / mittelstaendisch / Verband
- **Sekretariat:** ja / nein (entscheidet ob Sekretariats-Workflows aktiv)
- **Mandantenklientel:** Privatpersonen / Verbaende / Eingliederungstraeger / gemischt

### 2. Schwerpunktbereiche

- **SGB II** Buergergeld (Regelbedarfe Kosten der Unterkunft Sanktionen): ja / nein
- **SGB III** Arbeitsfoerderung Arbeitslosengeld I: ja / nein
- **SGB V** Krankenversicherung (Leistungsantraege Krankengeld): ja / nein
- **SGB VI** Rente: ja / nein
- **SGB VII** Unfallversicherung BG: ja / nein
- **SGB VIII** Kinder- und Jugendhilfe (Hilfe zur Erziehung Schulbegleitung): ja / nein
- **SGB IX** Rehabilitation und Teilhabe (Schwerbehinderung Hilfsmittel): ja / nein
- **SGB XI** Pflegeversicherung (Pflegegrade): ja / nein
- **SGB XII** Sozialhilfe (Grundsicherung im Alter Eingliederungshilfe): ja / nein
- **AsylbLG** Asylbewerberleistungen: ja / nein

### 3. Zustaendige Gerichte

- **Hauptsozialgericht** mit Adresse und beA-/EGVP-Postfach
- **LSG** des Bundeslandes
- Bundessozialgericht Kassel (Revision)

### 4. Versandwege

- **beA** vorhanden (Pflicht fuer RA seit 01.01.2022)
- **EGVP** Behoerden- und Gerichtsversand
- **Post** Restfaelle (Mandanten ohne digitalen Zugang)
- **ePostfach** Mandanten-eAkte

### 5. Prozesskostenhilfe

- **PKH-Quote** geschaetzt im Mandantenstamm
- **Vorlagen** fuer PKH-Antrag und ZP1a vorhanden
- **Belege** Standardliste fuer Einkommens- und Vermoegensnachweis

### 6. Sekretariat und Aktenfuehrung

- **Aktenstruktur-Konvention:** Mandat-Nummer + Mandantenname + Rechtsbereich
- **Postausgangsbuch:** digital / papier / hybrid
- **Fristenbuch:** zentral / je Anwalt
- **Vorfristen:** typischer Vorlauf vor Fristablauf

### 7. Standort und Eskalation

- **Bundesland** (entscheidet ueber LSG und LSG-Praxis)
- **Eskalationspartner** bei verfahrensrechtlichen Sonderfaellen

## Ausgabe

Profil wird geschrieben. Naechste sinnvolle Skills:

- `/sozialrecht-kanzlei:mandanten-intake` — fuer neue Mandanten
- `/sozialrecht-kanzlei:bescheidanalyse` — wenn Bescheid auf dem Tisch liegt
- `/sozialrecht-kanzlei:fristenbuch-sozialrecht` — Fristen-Check

## Rechtlicher Rahmen

- **SGG** Sozialgerichtsgesetz: § 78 Vorverfahren / § 84 Widerspruchsfrist / § 87 Klagefrist / § 86b Eilrechtsschutz
- **SGB X** Sozialverwaltungsverfahren: §§ 41 ff. Heilung / § 25 Akteneinsicht / § 44 Ueberpruefung
- **BRAO** § 31a beA-Pflicht
- **RVG** + RVG-VV fuer Sozialrechtsverfahren (Sondergebuehren) und PKH

## Hinweise

Dieses Plugin ist Werkzeug der zugelassenen Anwaltschaft. Mandantenkommunikation bleibt anwaltliche Verantwortung. Anlagen vor Versand sichten. Vor jedem Versand der `versand-vor-check` aus dem Plugin `kanzlei-cowork`.
