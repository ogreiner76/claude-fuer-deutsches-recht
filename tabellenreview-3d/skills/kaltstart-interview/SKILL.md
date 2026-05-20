---
name: kaltstart-interview
description: "Kaltstart-Interview fuer das tabellenreview-3d-Plugin. Erfragt typische Anwendungsfaelle (M&A-DD / Immobilienportfolio / Vendor-Onboarding / Arbeitsvertraege / Mietvertraege / Anlagedokumente / freie Eigenwuerfel), Standard-Wuerfeldimensionen (Spalten Zeilen Arbeitsblaetter), Hauszitierweise, Schwellen fuer Risikoampel (gruen / gelb / rot), Excel-Vorlagen-Pfade, Verzeichnis fuer Belegkette, Reviewer-Eskalationspfad und Standard-Materialitaet. Schreibt das Praxisprofil nach ~/.claude/plugins/config/claude-fuer-deutsches-recht/tabellenreview-3d/CLAUDE.md. Mit --redo neu interviewen, mit --integrationen-pruefen nur Konnektoren testen."
---

# /tabellenreview-3d:kaltstart-interview

## Ablauf

1. Zustand der Konfigurationsdatei `~/.claude/plugins/config/claude-fuer-deutsches-recht/tabellenreview-3d/CLAUDE.md` pruefen.
2. Falls vorhanden und ohne `[PLATZHALTER]`-Marker: bestaetigen, dass das Praxisprofil schon befuellt ist, und Modus erfragen (`--redo` fuer vollstaendiges Neu-Interview).
3. Falls nicht vorhanden oder mit Platzhaltern: das Kaltstart-Interview unten durchfuehren.
4. Konfigurationsdatei schreiben (uebergeordnete Verzeichnisse bei Bedarf anlegen).
5. Zusammenfassung zeigen und naechste Schritte vorschlagen.

## `--integrationen-pruefen`

Prueft Konnektoren-Verfuegbarkeit (Datenraum-Tool, Excel-Generator, PDF-Generator, Dokumentenspeicher, OCR-Pipeline, Anwaltspruefer-Postfach). Aktualisiert nur den Abschnitt `## Verfuegbare Integrationen`, fuehrt kein neues Interview durch.

Beim Pruefen: nur `OK` melden, wenn ein MCP-Tool-Aufruf tatsaechlich erfolgreich war. Konfigurierte-aber-ungetestete Konnektoren als `unbekannt` markieren.

---

## Kaltstart-Interview: tabellenreview-3d

### 1. Wer nutzt dieses Plugin?

- **Rolle:** Rechtsanwalt (M&A / Immobilien / Arbeit / Datenschutz) / Syndikus / Wirtschaftspruefer / Steuerberater / Notar / Nicht-Jurist mit anwaltlicher Ruecksprache?
- **Praxiskontext:** Einzelkanzlei / kleine Kanzlei / Grosskanzlei / Inhouse / Beratungsstelle / Hochschule
- **Anwaltlicher Pruefer fuer Endabnahme:** Name, Erreichbarkeit (jede Wuerfel-Ausgabe geht erst nach Pruefer-Abnahme ans Mandat)

### 2. Typische Anwendungsfaelle

- **M&A-Due-Diligence** (Vertragsstapel der Zielgesellschaft): ja / nein
- **Immobilien-Portfolio** (Grundbuchauszuege + Mietvertraege + Baulasten): ja / nein
- **Vendor-/Lieferanten-Onboarding** (AGB + AVV + Wirtschaftsdaten + Compliance): ja / nein
- **Arbeitsvertrags-Massenpruefung** (Tarifbezug + AGB-Klauseln + DSGVO + Sozialversicherung): ja / nein
- **Mietvertrags-Portfolio** (Schoenheitsreparaturen + Indexmiete + Betriebskosten): ja / nein
- **Anlagedokumente** (Fondsvertraege / KAGB-Konformitaet / Anlegerschutz): ja / nein
- **Freie Eigenwuerfel:** ja, mit eigener Spalten- / Zeilen- / Arbeitsblatt-Definition

### 3. Standard-Wuerfeldimensionen

- **Spalten (Datenpunkte):** typische Anzahl pro Wuerfel — z. B. 8 bis 25 Spaltenprompts
- **Zeilen (Dokumente):** typische Stapelgroesse — z. B. 10 bis 2000 Dokumente
- **Arbeitsblaetter (Perspektiven):** wie viele Perspektiven werden uebereinander gestapelt — typisch 3 bis 6 (Recht / Steuer / Wirtschaft / Datenschutz / IT / Betrieb)

### 4. Hauszitierweise

- BGH-Stil mit Pinpoint-Randnummer (siehe `references/zitierweise.md` im Repository)
- Kommentar-Stil: Bearbeiter in: Werk, Auflage Jahr, Norm Rn.
- Bei Vertragsstellen: woertliches Zitat in Anfuehrungszeichen, danach Fundstelle (Ziffer Absatz Seite)

### 5. Risikoampel-Schwellen

- **Rot (Blockierend):** [PLATZHALTER — z. B. AGB-unwirksame Klausel BGB Paragraph 307; fehlende AVV bei Auftragsverarbeitung; offene Briefgrundschuld ohne Loeschungsbewilligung]
- **Gelb (Pruefenswert):** [PLATZHALTER — z. B. unklare Kuendigungsfrist; Dienstbarkeit zugunsten unbekannter Dritter]
- **Gruen (Niedrig):** [PLATZHALTER — z. B. branchenueblich; in Vorlage erfasst]

### 6. Excel- und Belegkette-Pfade

- **Excel-Ausgabe-Verzeichnis:** [PLATZHALTER — z. B. `~/.claude/plugins/config/claude-fuer-deutsches-recht/tabellenreview-3d/wuerfel/<projekt>/`]
- **Belegketten-Verzeichnis:** [PLATZHALTER — Speicherort fuer woertliche Quellenzitate mit Datei-Hash]
- **Audit-Trail-Verzeichnis:** [PLATZHALTER — Pfad fuer Prompt-Versionen Laufprotokolle und Pruefer-Abnahmen]

### 7. Standort

- **Bundesland:** [PLATZHALTER]
- **Praxistypus:** Einzelkanzlei / Sozietaet / Partnerschaftsgesellschaft / Inhouse-Rechtsabteilung

---

## Ausgabe

Das Praxisprofil wird in `~/.claude/plugins/config/claude-fuer-deutsches-recht/tabellenreview-3d/CLAUDE.md` geschrieben. Anschliessend zeigen:

- Was eingerichtet wurde
- Welche Skills jetzt sinnvoll als naechstes laufen koennen:
  - `/tabellenreview-3d:wuerfel-aufbauen` — Wuerfel-Struktur fuer ein neues Projekt anlegen
  - `/tabellenreview-3d:vorlage-ma-due-diligence` — bei M&A-DD direkt mit Vorlage starten
  - `/tabellenreview-3d:vorlage-immobilien-portfolio` — bei Immobilienportfolio
  - `/tabellenreview-3d:vorlage-arbeitsvertrag-portfolio` — bei Massenpruefung Arbeitsvertraege
  - `/tabellenreview-3d:vorlage-vendor-onboarding-3d` — bei Lieferanten-Anbindung
- Hinweis auf Mandatsgeheimnis (Paragraph 43a Absatz 2 BRAO, Paragraph 203 StGB) und Notwendigkeit anwaltlicher Endabnahme

## Rechtlicher Rahmen

- **BRAO** — Paragraph 43a Absatz 2 (Verschwiegenheitspflicht)
- **StGB** — Paragraph 203 (Verletzung von Privatgeheimnissen)
- **DSGVO** — Artikel 28 (Auftragsverarbeitung) bei Verarbeitung von Vertragsstapeln durch Dritte
- **RDG** — Paragraph 2 (Rechtsdienstleistung — Endabnahme durch zugelassenen Rechtsanwalt)

## Hinweise

Dieses Plugin liefert eine Vorstrukturierung. Es ersetzt nicht die Pruefung durch einen zugelassenen Rechtsanwalt. Jede Zelle des Wuerfels ist ein Hinweis der Verifikation bedarf, kein abschliessender Befund. Vor Mandatsabnahme erfolgt die Pruefung durch den anwaltlichen Pruefer (siehe Skill `pruefer-uebergabe-paket`).
