# NDA-Abgleich

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`nda-abgleich`) | [`nda-abgleich.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/nda-abgleich.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Waldkrone HealthTech GmbH - NDA, Meldekanal und Lieferantenhinweis** (`hinweisgeberschutz-nda-meldekanal-waldkrone`) | [Gesamt-PDF lesen](../testakten/hinweisgeberschutz-nda-meldekanal-waldkrone/gesamt-pdf/hinweisgeberschutz-nda-meldekanal-waldkrone_gesamt.pdf) | [`testakte-hinweisgeberschutz-nda-meldekanal-waldkrone.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-hinweisgeberschutz-nda-meldekanal-waldkrone.zip) |
| **NDA-Vertragsabgleich Windsysteme Norderhof AG / Eickmann Wirtschaftspartner Pte. Ltd. — Joint Venture, GeschGehG, Exportkontrolle** (`nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft`) | [Gesamt-PDF lesen](../testakten/nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft/gesamt-pdf/nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft_gesamt.pdf) | [`testakte-nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

NDA-Verhandlungshilfe für die empfangende Seite. Akzeptiert den Entwurf der Gegenseite und setzt den eigenen Standard chirurgisch durch. Ampelmatrix ROT/GELB/GRUEN. Ausgabe .docx mit echten Word-Tracked-Changes. Keine Absatzlöschungen, keine Klausel-Neufassungen.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `nda-abgleich` | NDA-Verhandlungshilfe für die empfangende Seite. Zwei Modi: (A) Standard-Destillation aus 1 bis n eigenen NDAs und frei beschreibbarer Erfahrung in einen konsolidierten Haltelinien-Standard mit Ampelmatrix ROT/GELB/G… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 70 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `aenderungsmodus` | Nutze dies bei Aenderungsmodus: Compliance-Dokumentation und Aktenvermerk: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `allgemein` | Einstieg, Schnelltriage und Fallrouting im NDA Abgleich-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Fachmodule aus diesem Plugin vor und führt in einen klaren Arbeitsplan. Bei Dokument-U... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ampelmatrix` | Nutze dies bei Ampelmatrix: Internationaler Bezug und Schnittstellen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `ausgabe` | Nutze dies bei Ausgabe: Mandantenkommunikation und Entscheidungsvorlage: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `ausgabe-changes-docx-beweislast` | Nutze dies bei Ausgabe Mandantenkommunikation Entscheidungsvorlage, Changes Abschlussprodukt Und Uebergabe, Docx Beweislast Und Darlegungslast: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den n... |
| `changes` | Nutze dies bei Changes: Abschlussprodukt und Übergabe: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `chirurgisch-quellenkarte` | Nutze dies zur Quellenprüfung bei Chirurgisch Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `chronologie-und-belegmatrix` | Nutze dies bei Chronologie und Belegmatrix: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `docx-beweislast-darlegungslast` | Nutze dies bei Docx: Beweislast, Darlegungslast und Substantiierung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `durch-interessen` | Nutze dies bei Durch: Mehrparteienkonflikt und Interessenmatrix: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `durch-interessen-echten-sonderfall-eigenen` | Nutze dies bei Durch Mehrparteien Konflikt Und Interessen, Echten Sonderfall Und Edge Case, Eigenen Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `echten-sonderfall-edge-case` | Nutze dies bei Echten: Sonderfall und Edge-Case-Prüfung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `eigenen` | Nutze dies bei Eigenen: Risikoampel, Gegenargumente und Verteidigungslinien: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `entwurf` | Nutze dies bei Entwurf: Tatbestandsmerkmale, Beweisfragen und Beleglage: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `fristen-und-risikoampel` | Nutze dies bei Fristen- und Risikoampel: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `gegen-dokumentenmatrix-und-lueckenliste` | Nutze dies für Unterlagen zu Gegen: Dokumentenmatrix, Lückenliste und Nachforderung: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `gegen-gelb-gleicht` | Nutze dies bei Gegen Dokumentenmatrix Und Lueckenliste, Gelb Formular Portal Und Einreichung, Gleicht Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `gegenseite` | Nutze dies bei Gegenseite: Fristen, Form, Zuständigkeit und Rechtsweg: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `gegenseite-tracked-fristennotiz-nda` | Nutze dies bei Gegenseite Fristen Form Und Zustaendigkeit, Tracked Fristennotiz Und Naechster Schritt, Nda Definitionsklausel Abgleichen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächste... |
| `gelb` | Nutze dies bei Gelb: Formular, Portal und Einreichungslogik: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `geschaeftsgeheimnis-geschgehg` | Nutze dies bei Nda Mit Geschaeftsgeheimnis Geschgehg, Nda Mit Kartellsensitiven Daten, Nda Mit Personenbezogenen Daten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbe... |
| `gleicht` | Nutze dies bei Gleicht: Erstprüfung, Rollenklärung und Mandatsziel: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `gruen-fehlerkatalog` | Nutze dies als Fehlerbremse bei Gruen Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `haltelinien` | Nutze dies bei Haltelinien: Verhandlung, Vergleich und Eskalation: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `haltelinien-setzt-standard` | Nutze dies bei Haltelinien Verhandlung Vergleich Und Eskalation, Setzt Schriftsatz Brief Und Memo Bausteine, Standard Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefe... |
| `it-saas-laufzeit-survival-m-a` | Nutze dies bei Nda It Saas Vendor, Nda Laufzeit Und Survival, Nda M Und A Clean Team Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `m-a-aenderungsmodus-ampelmatrix` | Nutze dies bei Nda Vor M A Data Room, Aenderungsmodus Compliance Dokumentation Und Akte, Ampelmatrix Internationaler Bezug Und Schnittstellen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nä... |
| `mandantenkommunikation` | Nutze dies bei Mandantenkommunikation: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `mitarbeiter-need-non-solicit-permitted` | Nutze dies bei Nda Mitarbeiter Need To Know, Nda Non Solicit Kartellrechtlich, Nda Permitted Disclosure: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `nda` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Nda Anwendbares Recht Gerichtsstand: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `nda-abgleich` | Empfangende Seite soll NDA der Gegenseite prüfen und verhandeln oder Kanzlei will aus mehreren NDAs einen eigenen Standard destillieren. NDA-Verhandlungshilfe. Modus A Destillation: 1 bis n eigene NDAs in konsolidierten Haltelinien-Stand... |
| `nda-abgleich-arbeitnehmer-kuendigung` | Nutze dies bei Nda Abgleich, Nda Bei Arbeitnehmer Kündigung, Nda Bei Bewerbungen Pitches: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `nda-anwendbares-recht-gerichtsstand` | Anwendbares Recht und Gerichtsstand bei NDA: Empfehlung deutsches Recht + LG Sitz des Discloser; Schiedsklausel (DIS Regeln) ab hoeherer Bedeutung. Pruefraster: internationale NDAs vs. nationale, Verbraucherbeteiligung. |
| `nda-bei-arbeitnehmer-kuendigung` | Post-Termination-NDA bei Arbeitnehmer-Kuendigung: Wirksamkeit, Karenzentschaedigung § 74 HGB analog, Reichweite (keine generelle Wettbewerbssperre). Schnittstelle Arbeitsrecht. Empfehlung: nur ergaenzend zu nachvertraglichem Wettbewerbsv... |
| `nda-bei-bewerbungen-pitches` | NDA bei Bewerbungen/Pitches/Investorengespraechen: Investor-NDAs sind ungewoehnlich; ueblich nur enge Mutual-NDAs fuer fortgeschrittene Stage. Empfehlung: nicht beleidigt sein, wenn VC unterschreibt nicht; Verhandlungsstrategie. |
| `nda-bei-r-d-kooperation` | NDA bei F&E-Kooperation: Background-IP / Foreground-IP-Trennung, IP-Zuordnung bei gemeinsamer Erfindung, Foerderrechtshinweise (BMBF/EU). Empfehlung: NDA + Pre-LoI mit IP-Grundsaetzen. |
| `nda-definitionsklausel-abgleichen` | Definitionsklausel 'Vertrauliche Information' abgleichen: weiter Begriff (alle Informationen) vs. eng definiert (nur als vertraulich markiert). Empfehlung je nach Rolle: Discloser will weit, Recipient will eng. Wortlautempfehlungen. |
| `nda-grundstruktur-pruefen` | NDA-Grundstruktur pruefen: Parteien, Zweck der Offenlegung, Definition Vertrauliche Information, Pflichten, Laufzeit, Aufbewahrung/Rueckgabe, Vertragsstrafe, Geheimhaltungsdauer nach Vertragsende, Jurisdiction. Pruefraster gegen marktueb... |
| `nda-international-arbitration-spezial` | Spezialfall internationale NDAs und Schiedsklauseln: Rechtswahl, Schiedsort, einstweiliger Rechtsschutz, Common-Law-Begriffe Equity. Pruefraster fuer Cross-Border-Mandat. |
| `nda-it-saas-vendor` | NDA fuer SaaS-/IT-Vendor-Pitches: Cloud-Hosting, Datentrennung, Subprozessoren, Audit-Rechte, Penetration-Testing-Erlaubnis. Empfehlung: nicht-exklusive Lizenz fuer Test-Daten, klare Loeschpflicht nach Pitch. |
| `nda-laufzeit-und-survival` | Laufzeit und Survival der Geheimhaltungspflicht: Festlaufzeit, automatische Verlaengerung, Survival 2/3/5 Jahre nach Vertragsende. Bei Geschaeftsgeheimnissen i. S. GeschGehG ist Survival 'so lange die Information Geschaeftsgeheimnis ist'... |
| `nda-m-und-a-clean-team-spezial` | Spezialfall NDA fuer M-and-A und Clean-Team-Arrangements: Datenraum, Sondervertraulichkeit Wettbewerbsdaten, Kartellrecht. Pruefraster fuer Antitrust-Counsel. |
| `nda-mit-geschaeftsgeheimnis-geschgehg` | NDA als angemessene Geheimhaltungsmassnahme i. S. § 2 Nr. 1 b GeschGehG: NDA allein reicht nicht, technisch-organisatorische Massnahmen erforderlich (Zugangsschutz, Klassifizierung, Logging). Pruefraster. |
| `nda-mit-kartellsensitiven-daten` | NDA mit kartellsensitiven Daten (Preise, Mengen, Kunden): Clean Team Agreement, Aggregation, externe Berater zwischen den Parteien. Empfehlung: Vorabklaerung ob Daten ueberhaupt ausgetauscht werden duerfen. |
| `nda-mit-personenbezogenen-daten` | NDA mit personenbezogenen Daten: ggf. AV-Vertrag § 28 BDSG / Art. 28 DSGVO erforderlich, gemeinsame Verantwortlichkeit Art. 26 DSGVO pruefen. NDA ersetzt AV nicht. Empfehlung: separater AVV anlagengeb. |
| `nda-mitarbeiter-need-to-know` | Mitarbeiter und Need-to-Know: NDA verpflichtet Mitarbeiter ueber Arbeitsvertrag, externe Berater nur ueber separate NDA oder Backup-Klausel. Empfehlung: Liste freigegebener Personen, Bestaetigung Mitarbeiter-NDA, kein Datenraum-Zugriff o... |
| `nda-non-solicit-kartellrechtlich` | Non-Solicit in NDA kartellrechtlich pruefen: zeitlich begrenzt (12-24 Monate), sachlich begrenzt (nur fuer NDA-Zweck involvierte Mitarbeiter), keine generelle Bewerbungs-Sperre. Andernfalls Risiko § 1 GWB / Art. 101 AEUV. |
| `nda-permitted-disclosure` | Permitted Disclosure: Konzern, Beraterklausel, gesetzliche Offenlegungspflichten (Aufsicht, Strafverfolgung, Gericht). Standard-Wortlaut und typische Fallstricke (z. B. Konzernbegriff zu eng). |
| `nda-rueckgabe-vernichtung` | Rueckgabe und Vernichtung Vertraulicher Information: Pflicht, Bestaetigung, Backup-Ausnahme (technisch unmoeglich zu loeschende Backups). Bei Daten in Cloud: Loeschbestaetigung Vendor erforderlich. Wortlautempfehlungen. |
| `nda-standardklauseln-bauleiter` | Bauleiter NDA-Standardklauseln: Vertraulichkeitsumfang, Empfaengerkreis, Laufzeit, Rechtsfolgen, Schriftform. Pruefraster fuer mutual und one-way NDA. |
| `nda-typen-vergleich` | NDA-Typen vergleichen: einseitig (unilateral), gegenseitig (mutual), mehrparteiig. Empfehlung pro Situation: Verkaeufer in M&A unilateral; gemeinsame Entwicklung mutual; Konsortium mehrparteiig. Praxisanker fuer Templates. |
| `nda-vergleichsmatrix-leitfaden` | Leitfaden NDA-Vergleichsmatrix: relevante Klauseln vergleichen, Markup, Risikoampel, Wechselwirkungen mit Geschaeftsgeheimnisgesetz. Pruefraster fuer Reviewteam. |
| `nda-vertragsstrafe-pruefen` | Vertragsstrafe pruefen: Hoehe, AGB-Kontrolle §§ 305 ff. BGB, Bestimmtheitsgrundsatz, Schadensersatzkumulation oder Anrechnung. Bei Verbraucher-NDA strengere Grenzen. Bei B2B-Standard: ueblich 5000-25000 EUR pro Vorfall, Kumulation moeglich. |
| `nda-vor-m-a-data-room` | NDA vor M&A-Data-Room: enge Zweckbindung (Pruefung Transaktion), Standstill-Klausel, Non-Solicit, Verbot Reverse-Engineering. Empfehlung: separater Clean Team Agreement fuer Kartell-/Wettbewerbsdaten. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `r-d-nda-grundstruktur-international` | Nutze dies bei Nda Bei R D Kooperation, Nda Grundstruktur Prüfen, Nda International Arbitration Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `redteam-qualitygate` | Nutze dies als Fehlerbremse bei Red-Team Qualitygate: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `rueckgabe-vernichtung-nda-typen` | Nutze dies bei Nda Rueckgabe Vernichtung, Nda Typen Vergleich, Nda Vergleichsmatrix Leitfaden: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `setzt` | Nutze dies bei Setzt: Schriftsatz-, Brief- und Memo-Bausteine: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `standard` | Nutze dies bei Standard: Behörden-, Gerichts- oder Registerweg: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `standardklauseln-bauleiter-nda-vertragsstrafe` | Nutze dies bei Nda Standardklauseln Bauleiter, Nda Vertragsstrafe Prüfen, Entwurf Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `tracked-fristennotiz-naechster-schritt` | Nutze dies bei Tracked: Fristennotiz und nächster Schritt: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `word` | Nutze dies bei Word Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `word-02` | Nutze dies bei Word: Zahlen, Schwellenwerte und Berechnung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
