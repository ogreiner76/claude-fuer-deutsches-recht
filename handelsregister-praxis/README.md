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
| `beanstandung-zwischenverfuegung` | Beanstandung Zwischenverfuegung Antwort, Bekanntmachungen Monitoring, Chronologischer Registerauszug: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `closing-handelregister-einstweiliger` | Closing Handelregister Vollzug, Einstweiliger Rechtsschutz Registerstreit, Eintragung Prozessvergleich Registerfolge: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastba... |
| `erlaubnispflichtige-taetigkeit-famfg` | Erlaubnispflichtige Taetigkeit Register, Famfg Beschwerde Registersache, Fehlerhafte Eintragung Berichtigung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `firma-firmenbildung-formwechsel-registercheck` | Firma Firmenbildung Und Irrefuehrung, Formwechsel Registercheck, Genossenschaft Registerschnittstelle: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `gesellschafterlistenstreit-eilstrategie-gmbh` | Gesellschafterlistenstreit Eilstrategie, Gmbh Co Kg Registerdoppelvollzug, Gmbh Geschaeftsfuehrerbestellung Abberufung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belast... |
| `gmbh-gesellschafterliste-paragraph-gruendung` | Gmbh Gesellschafterliste Paragraph 40, Gmbh Gruendung Erstanmeldung, Gmbh Kapitalerhoehung Bareinlage: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `gmbh-kapitalerhoehung-sacheinlage` | Gmbh Kapitalerhoehung Sacheinlage, Gmbh Kapitalherabsetzung Und Schutzjahr, Gmbh Liquidation Und Löschung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `gmbh-satzungsaenderung-handelsvollmacht-nicht` | Gmbh Satzungsaenderung Und Neufassung, Handelsvollmacht Nicht Eintragungsfaehig, Hgb Publizitaet Paragraph 15: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Out... |
| `handelsregister-kaltstart-routing` | Führt durch das erste Registerproblem: Wer meldet was an, welche Gesellschaft, welches Registerblatt, welches Ziel, welcher Fristdruck, welche Urkunden, welche Entscheidungsperson und welches Eskalationsniveau. |
| `insolvenzvermerk-registereintrag` | Insolvenzvermerk Und Registereintrag, Internationaler Registervergleich, Kg Kommanditist Eintritt Austritt Haftsumme: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastba... |
| `ki-registerakte-nachlass` | Ki Registerakte Halluzinationsschutz, Nachlass Und Testamentsvollstrecker Register, Notar Registergericht Kommunikation: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belas... |
| `ohg-kg-online-abruf-partg-partgmbb` | Ohg Kg Egbr Mopeg Statuswechsel, Online Abruf Registerportal Unternehmensregister, Partg Partgmbb Register: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `prokura-eintragung-rechtsabteilung` | Prokura Eintragung Und Widerruf, Rechtsabteilung Geschaeftsfuehrerbestellung Mit Auslandsbezug, Rechtsabteilung Gesellschafterliste Nach Streit Und Ev: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage... |
| `rechtsabteilung-insolvenzvermerk` | Rechtsabteilung Insolvenzvermerk Und Auslaendischer Trustee, Rechtsabteilung Kapitalerhoehung Und Zwischenverfuegung, Rechtsabteilung Mopeg Gesellschaftsregister Und Ohg Sprung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit,... |
| `rechtsprechung-register-frist-vollzugslog` | Rechtsprechung Register Live Verifizieren, Frist Und Vollzugslog Register, Registerrecht Mandatsannahme Notarferne: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbare... |
| `rechtsschein-innenstreit-register` | Rechtsschein Und Innenstreit, Register Mandantenbrief, Register Qualitaetsgate Vor Einreichung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `registerakte-schnellscan-registerauszug-lesen` | Registerakte Schnellscan Und Vollzugskarte, Registerauszug Lesen, Registerbeweis Im Prozess: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `registergericht-rollen-datenschutz` | Registergericht Rollen Rechtspfleger Registerrichter, Registergericht Und Datenschutz, Registerkosten Und Notarkosten: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastb... |
| `registerrecht-aktiengesellschaft-vorstand` | Registerrecht Aktiengesellschaft Vorstand Aufsichtsrat, Registerrecht Beschlussmaengel Und Registervollzug, Registerrecht Digitalgruendung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert... |
| `registerrecht-fehlende-einzahlung-fehlerhafte` | Registerrecht Fehlende Einzahlung, Registerrecht Fehlerhafte Geschaeftsfuehreradresse, Registerrecht Kapitalgesellschaft Co Kg Komplementaerwechsel: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage un... |
| `registerrecht-niederlassung-registergericht` | Registerrecht Niederlassung Filiale, Registerrecht Registergericht Telefonat Protokoll, Registerrecht Registerzeichen Und Aktenzeichen: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den... |
| `registerrecht-scheinloeschung` | Registerrecht Scheinloeschung Und Nachtragsliquidation, Registerrecht Se Und Europaeische Gesellschaft, Registerrecht Umbenennung Rebranding: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefe... |
| `registersperre-closing-sitz-inlandsanschrift` | Registersperre Und Closing Risiko, Sitz Inlandsanschrift Und Geschaeftsanschrift, Todesfall Gesellschafter Register: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbar... |
| `transparenzregister-schnittstelle-umwandlung` | Transparenzregister Schnittstelle, Umwandlung Registervollzug, Unternehmensgegenstand Beanstandung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `umzug-registerbezirk-amtsloeschung` | Umzug Registerbezirk, Amtsloeschung Familienloeschung Registerblatt, Auslandsurkunden Apostille Legalisation Uebersetzung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten bel... |
| `verein-registerschnittstelle-verschmelzung` | Verein Registerschnittstelle, Verschmelzung Gmbh Registercheck, Vollmacht Und Anmeldung Oeffentliche Beglaubigung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren... |
| `zweigniederlassung-auslaendische` | Zweigniederlassung Auslaendische Gesellschaft: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
