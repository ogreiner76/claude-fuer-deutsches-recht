# Handelsregister Praxis

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`handelsregister-praxis`) | [`handelsregister-praxis.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/handelsregister-praxis.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Rabenhof Sensorik GmbH - Registergericht Charlottenburg, HRB 246810 B** (`handelsregister-registergericht-rabenhof-gmbh-2026`) | [Gesamt-PDF lesen](../testakten/handelsregister-registergericht-rabenhof-gmbh-2026/gesamt-pdf/handelsregister-registergericht-rabenhof-gmbh-2026_gesamt.pdf) | [`testakte-handelsregister-registergericht-rabenhof-gmbh-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-handelsregister-registergericht-rabenhof-gmbh-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein Registergerichts-Cockpit für Gesellschaftsrechtler, Notariate, Kanzleien und Rechtsabteilungen. Es ordnet, was eingetragen werden soll, welche Urkunden nötig sind, wer beim Registergericht entscheidet, wie man Beanstandungen beantwortet und wann Beschwerde oder Eilrechtsschutz Sinn ergeben.

## Wofür dieses Plugin da ist

Dieses Plugin ist ein Praxiswerkzeug. Es fragt zuerst die Lage ab, baut dann eine Dokumenten- und Vollzugsmatrix und erzeugt schließlich das konkrete Arbeitsprodukt: Nachreichung, Beanstandungsantwort, Beschwerdegerüst, Mandantenbrief, Checkliste, Fristenlog oder Vertrags-/Urkundenreview. Es ersetzt keine Berufsträgerentscheidung, aber es verhindert, dass ein formeller Nachweis, ein Rang, eine Abteilung-II-Belastung oder eine Registerfolge in der Hektik untergeht.

## Kaltstart

Starte mit dem allgemeinen Skill `handelsregister-allgemeiner-kaltstart`. Lade danach möglichst den aktuellen Register- oder Grundbuchauszug, das Gerichtsschreiben, die Anmeldung/Bewilligung, den Vertragsentwurf und vorhandene Anlagen hoch. Das Plugin sortiert erst, dann prüft es.

## Quellen- und Halluzinationsschutz

- Normen werden als Prüfanker verwendet, nicht als Schmuck.
- Rechtsprechung wird nur ausgegeben, wenn Gericht, Datum, Aktenzeichen und ein frei zugänglicher Fundlink geprüft sind.
- Unsichere Register-/Grundbuchstände werden nicht geraten; das Plugin fordert aktuelle Auszüge oder Nachweise an.

## Amtliche Startquellen

- [HGB §§ 8 ff., § 15](https://www.gesetze-im-internet.de/hgb/)
- [FamFG Registersachen und Beschwerde](https://www.gesetze-im-internet.de/famfg/)
- [GmbHG Anmeldung, Gesellschafterliste, Kapitalmaßnahmen](https://www.gesetze-im-internet.de/gmbhg/)
- [Registerportal der Länder](https://www.handelsregister.de/)
- [Unternehmensregister](https://www.unternehmensregister.de/)

## Typische Ergebnisse

- Prüfmatrix und Vollzugsfahrplan
- Entwurf für Nachreichung oder Antwort an das Gericht/Amt
- Mandantenbrief in normalem Deutsch
- Fristen- und Ranglog
- Beschwerde- oder Eilrechtsschutz-Skizze
- Liste fehlender Originale, Nachweise und Formmängel

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `beanstandung-zwischenverfuegung` | Nutze dies bei Beanstandung Zwischenverfuegung Antwort, Bekanntmachungen Monitoring, Chronologischer Registerauszug: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeits... |
| `closing-handelregister-einstweiliger` | Nutze dies bei Closing Handelregister Vollzug, Einstweiliger Rechtsschutz Registerstreit, Eintragung Prozessvergleich Registerfolge: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bel... |
| `erlaubnispflichtige-taetigkeit-famfg` | Nutze dies bei Erlaubnispflichtige Taetigkeit Register, Famfg Beschwerde Registersache, Fehlerhafte Eintragung Berichtigung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `firma-firmenbildung-formwechsel-registercheck` | Nutze dies bei Firma Firmenbildung Und Irrefuehrung, Formwechsel Registercheck, Genossenschaft Registerschnittstelle: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `gesellschafterlistenstreit-eilstrategie-gmbh` | Nutze dies bei Gesellschafterlistenstreit Eilstrategie, Gmbh Co Kg Registerdoppelvollzug, Gmbh Geschaeftsfuehrerbestellung Abberufung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten b... |
| `gmbh-gesellschafterliste-paragraph-gruendung` | Nutze dies bei Gmbh Gesellschafterliste Paragraph 40, Gmbh Gruendung Erstanmeldung, Gmbh Kapitalerhoehung Bareinlage: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `gmbh-kapitalerhoehung-sacheinlage` | Nutze dies bei Gmbh Kapitalerhoehung Sacheinlage, Gmbh Kapitalherabsetzung Und Schutzjahr, Gmbh Liquidation Und Löschung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Ar... |
| `gmbh-satzungsaenderung-handelsvollmacht-nicht` | Nutze dies bei Gmbh Satzungsaenderung Und Neufassung, Handelsvollmacht Nicht Eintragungsfaehig, Hgb Publizitaet Paragraph 15: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbare... |
| `handelsregister-allgemeiner-kaltstart` | Führt durch das erste Registerproblem: Wer meldet was an, welche Gesellschaft, welches Registerblatt, welches Ziel, welcher Fristdruck, welche Urkunden, welche Entscheidungsperson und welches Eskalationsniveau. |
| `insolvenzvermerk-registereintrag` | Nutze dies bei Insolvenzvermerk Und Registereintrag, Internationaler Registervergleich, Kg Kommanditist Eintritt Austritt Haftsumme: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bel... |
| `ki-registerakte-nachlass` | Nutze dies bei Ki Registerakte Halluzinationsschutz, Nachlass Und Testamentsvollstrecker Register, Notar Registergericht Kommunikation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `ohg-kg-online-abruf-partg-partgmbb` | Nutze dies bei Ohg Kg Egbr Mopeg Statuswechsel, Online Abruf Registerportal Unternehmensregister, Partg Partgmbb Register: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren A... |
| `prokura-eintragung-rechtsabteilung` | Nutze dies bei Prokura Eintragung Und Widerruf, Rechtsabteilung Geschaeftsfuehrerbestellung Mit Auslandsbezug, Rechtsabteilung Gesellschafterliste Nach Streit Und Ev: führt durch diese fachlich verbundenen Module, wählt den passenden Prü... |
| `rechtsabteilung-insolvenzvermerk` | Nutze dies bei Rechtsabteilung Insolvenzvermerk Und Auslaendischer Trustee, Rechtsabteilung Kapitalerhoehung Und Zwischenverfuegung, Rechtsabteilung Mopeg Gesellschaftsregister Und Ohg Sprung: führt durch diese fachlich verbundenen Modul... |
| `rechtsprechung-register-frist-vollzugslog` | Nutze dies bei Rechtsprechung Register Live Verifizieren, Frist Und Vollzugslog Register, Registerrecht Mandatsannahme Notarferne: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belas... |
| `rechtsschein-innenstreit-register` | Nutze dies bei Rechtsschein Und Innenstreit, Register Mandantenbrief, Register Qualitaetsgate Vor Einreichung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `registerakte-schnellscan-registerauszug-lesen` | Nutze dies bei Registerakte Schnellscan Und Vollzugskarte, Registerauszug Lesen, Registerbeweis Im Prozess: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `registergericht-rollen-datenschutz` | Nutze dies bei Registergericht Rollen Rechtspfleger Registerrichter, Registergericht Und Datenschutz, Registerkosten Und Notarkosten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten be... |
| `registerrecht-aktiengesellschaft-vorstand` | Nutze dies bei Registerrecht Aktiengesellschaft Vorstand Aufsichtsrat, Registerrecht Beschlussmaengel Und Registervollzug, Registerrecht Digitalgruendung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und li... |
| `registerrecht-fehlende-einzahlung-fehlerhafte` | Nutze dies bei Registerrecht Fehlende Einzahlung, Registerrecht Fehlerhafte Geschaeftsfuehreradresse, Registerrecht Kapitalgesellschaft Co Kg Komplementaerwechsel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpf... |
| `registerrecht-niederlassung-registergericht` | Nutze dies bei Registerrecht Niederlassung Filiale, Registerrecht Registergericht Telefonat Protokoll, Registerrecht Registerzeichen Und Aktenzeichen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefer... |
| `registerrecht-scheinloeschung` | Nutze dies bei Registerrecht Scheinloeschung Und Nachtragsliquidation, Registerrecht Se Und Europaeische Gesellschaft, Registerrecht Umbenennung Rebranding: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `registersperre-closing-sitz-inlandsanschrift` | Nutze dies bei Registersperre Und Closing Risiko, Sitz Inlandsanschrift Und Geschaeftsanschrift, Todesfall Gesellschafter Register: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `transparenzregister-schnittstelle-umwandlung` | Nutze dies bei Transparenzregister Schnittstelle, Umwandlung Registervollzug, Unternehmensgegenstand Beanstandung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitssc... |
| `umzug-registerbezirk-amtsloeschung` | Nutze dies bei Umzug Registerbezirk, Amtsloeschung Familienloeschung Registerblatt, Auslandsurkunden Apostille Legalisation Uebersetzung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächste... |
| `verein-registerschnittstelle-verschmelzung` | Nutze dies bei Verein Registerschnittstelle, Verschmelzung Gmbh Registercheck, Vollmacht Und Anmeldung Oeffentliche Beglaubigung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belast... |
| `zweigniederlassung-auslaendische` | Nutze dies bei Zweigniederlassung Auslaendische Gesellschaft: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
