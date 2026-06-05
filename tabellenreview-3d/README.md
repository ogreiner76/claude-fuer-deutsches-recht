# Tabellenreview 3D

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`tabellenreview-3d`) | [`tabellenreview-3d.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/tabellenreview-3d.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Tabellenreview Paragrafix GmbH — Fortbestehensprognose v23, IDW S 11** (`tabellenreview-finanzplanung-fortbestehensprognose-paragrafix-fortsetzung-vellbruck`) | [Gesamt-PDF lesen](../testakten/tabellenreview-finanzplanung-fortbestehensprognose-paragrafix-fortsetzung-vellbruck/gesamt-pdf/tabellenreview-finanzplanung-fortbestehensprognose-paragrafix-fortsetzung-vellbruck_gesamt.pdf) | [`testakte-tabellenreview-finanzplanung-fortbestehensprognose-paragrafix-fortsetzung-vellbruck.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-tabellenreview-finanzplanung-fortbestehensprognose-paragrafix-fortsetzung-vellbruck.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

3D-Tabellenreview als Würfel: Spaltenprompts pro Datenpunkt x Zeilenprompts pro Dokument x Arbeitsblatt-Perspektiven (Recht / Steuer / Wirtschaft) gestapelt. Massenprüfung Vertragsstapel M&A-DD Immobilien Vendor-Onboarding mit Excel-Mehrblatt Kreuzblatt-Konsistenz Audit-Trail Belegkette.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `arbeitsblatt-perspektiven-definieren` | Definiert die dritte Würfel-Achse — Arbeitsblätter als Perspektiven die über denselben Dokumentenstapel laufen aber jeweils eine andere Brille aufsetzen. Typische Perspektiven: Recht (Anwalt) Steuer (Steuerberater)… |
| `audit-trail-protokoll` | Führt das Audit-Trail-Protokoll des Würfels — jeder Reviewlauf jede Prompt-Änderung jede Prüfer-Abnahme jeder Cache-Treffer jede Hash-Prüfung wird unveränderlich protokolliert. Spalten pro Eintrag: Zeitstempel A… |
| `belegkette-rueckverfolgung` | Sichert die Belegkette jeder Zelle des Würfels — von der Antwort über das wörtliche Zitat bis zur Originalstelle im Quelldokument mit Seite Absatz und Datei-Hash. Erkennt Belegkette-Brüche (Datei-Hash weicht ab / … |
| `caching-und-teil-rerun` | Caching der Würfelzellen und gezielter Teil-Rerun bei Änderungen — vermeidet die voll Neuberechnung von tausenden Zellen wenn nur ein Spaltenprompt eine Zeile oder ein Arbeitsblatt geändert wurde. Cache-Key pro Zel… |
| `dokumentstapel-aufnehmen` | Nimmt einen Dokumentenstapel als Zeilenachse des Würfels auf. Quellen: VDR-Export (Datasite Intralinks Box) lokaler Ordner SharePoint-Bibliothek E-Mail-Anhang-Sammlung gescannte PDF mit OCR-Pipeline. Erzeugt pro Doku… |
| `excel-multi-sheet-export` | Exportiert den dreidimensionalen Würfel in eine einzige Excel-Datei mit mehreren Tabellenblättern — ein Reiter pro Arbeitsblatt-Perspektive (Recht / Steuer / Wirtschaft / Datenschutz / IT / Betrieb / Compliance). Je… |
| `tabellenreview-3d-kaltstart-interview` | Kaltstart-Interview für das tabellenreview-3d-Plugin. Erfragt typische Anwendungsfälle (M&A-DD / Immobilienportfolio / Vendor-Onboarding / Arbeitsverträge / Mietverträge / Anlagedokumente / freie Eigenwuerfel), St… |
| `kreuzblatt-konsistenzpruefung` | Prüft die dritte Würfel-Dimension auf innere Konsistenz — läuft NACH `review-durchfuehren` über alle Arbeitsblätter und sucht Widersprüche zwischen Perspektiven (z. B. ein Vertrag rechtlich grün aber datenschut… |
| `pdf-bericht-erzeugen` | Erstellt einen prüfbaren PDF-Bericht aus dem 3D-Würfel. Struktur: Deckblatt mit Projekt Mandant Stichtag Würfel-Ampel; Management-Summary mit Hotspots und blockierenden Roten; pro Arbeitsblatt-Perspektive ein Absch… |
| `prompt-versionierung` | Versioniert alle Spalten- und Zeilenprompts mit semantischer Versions-ID — patch für Wortlautfeinheiten minor für geänderte Antworttypen oder Ampelregeln major für geänderte Pruefdimension. Jede Zelle im Würfel … |
| `pruefer-uebergabe-paket` | Schnuert das vollständige Prüfer-Paket nach Abschluss eines Würfellaufs — Excel-Würfel-Datei aus Skill `excel-multi-sheet-export` PDF-Bericht aus `pdf-bericht-erzeugen` Belegketten-CSV aus `belegkette-rueckverfolg… |
| `review-durchfuehren` | Führt den eigentlichen Reviewlauf über den Würfel durch — Anzahl Zellen = Spalten x Zeilen x Arbeitsblätter. Pro Zelle: Spaltenprompt + Zeilenprompt + Arbeitsblatt-Perspektive zusammenführen, Antwort aus dem Doku… |
| `risikoampel-aggregation` | Konsolidiert die Ampel-Wertungen entlang aller drei Würfelachsen — pro Zelle (atomisch) pro Zeile (Dokument-Gesamtampel) pro Spalte (Datenpunkt-Hotspots) pro Arbeitsblatt (Perspektiven-Gesamtampel) und pro Gesamtwuer… |
| `spaltenprompts-definieren` | Definiert die Spaltenprompts der ersten Würfel-Achse — jede Spalte ist eine einzige praezise Frage die für ALLE Dokumente identisch gestellt wird damit Vergleichbarkeit über den Stapel entsteht. Enthält eine Bibli… |
| `vorlage-arbeitsvertrag-portfolio` | Würfelvorlage für Massenprüfung von Arbeitsverträgen — 15 Spalten (Vertragsdatum Probezeit Befristung-mit-oder-ohne-Sachgrund Wochenarbeitszeit Kündigungsfrist Tarifbindung Bruttogehalt Sonderzahlung Verschwiegen… |
| `vorlage-immobilien-portfolio` | Würfelvorlage für Immobilien-Portfolioanalyse — 16 Spalten (Gemarkung / Flur / Flurstück / Wirtschaftsart / Größe / Eigentümerkette / Abteilung-II-Lasten / Abteilung-III-Grundpfandrechte / Rang / Löschungserlei… |
| `vorlage-ma-due-diligence` | Fertige Würfelvorlage für M&A-Due-Diligence — 18 Spalten (Vertragsart Laufzeit Kündigungsfrist Change-of-Control MAC-Klausel Abtretungsverbot Haftungsbegrenzung Garantien Vertragsstrafe SLA Datenschutz Geheimhaltun… |
| `vorlage-vendor-onboarding-3d` | Würfelvorlage für Vendor- und Lieferanten-Onboarding — 17 Spalten (Vendor-Stammdaten Branche AVV-Pflicht AVV-vorhanden SLA-Reaktionszeit SLA-Verfügbarkeit Exit-Klausel Datenherausgabe Verschlüsselung Subunternehme… |
| `wuerfel-aufbauen` | Baut die dreidimensionale Würfel-Struktur für ein neues Pruefprojekt auf — drei Achsen: Spalten (Datenpunkte als Spaltenprompts) Zeilen (Dokumente mit optionalen Zeilenprompts) Arbeitsblätter (Perspektiven wie Rech… |
| `zeilenprompts-definieren` | Definiert die Zeilenprompts der zweiten Würfel-Achse — pro Dokument eine optionale Sonderanweisung die das Lesen genau dieses Dokuments steuert. Beispiele: 'Konzernvertrag — AktG Paragraph 311 zusätzlich prüfen' / … |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 69 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `aggregation-spaltenprompts-definieren` | Nutze dies bei Risikoampel Aggregation, Spaltenprompts Definieren, Arbeitsblatt Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `allgemein` | Einstieg, Schnelltriage und Fallrouting im Tabellenreview 3d-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Fachmodule aus diesem Plugin vor und führt in einen klaren Arbeitsplan. Bei Dokum... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `arbeitsblatt` | Nutze dies bei Arbeitsblatt: Schriftsatz-, Brief- und Memo-Bausteine: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `arbeitsblatt-perspektiven-definieren` | Drei Prüfperspektiven (Spalten) für den 3D-Tabellenreview definieren: Forderung, Prüfung, Stellung nach §§ 174 ff. InsO. Normen: §§ 174 ff. InsO, ZPO. Prüfraster: Forderungsaufstellung, Prüfungsraster, Gläubigerstellung. Output: Perspekt... |
| `audit-trail-protokoll` | Audit-Trail aller Review-Schritte protokollieren: wer hat wann was geprüft und geaendert. Normen: §§ 238 257 HGB Buchführungspflichten. Prüfraster: Zeitstempel, Prüfer-ID, Aenderungshistorie, Versionierung. Output: Audit-Trail-Protokoll.... |
| `belegkette-rueckverfolgung` | Belegkette für Forderungen und Zahlungen zurückverfolgen: Originalbeleg, Buchung, Zahlung. Normen: §§ 238 257 HGB, §§ 174 ff. InsO. Prüfraster: Belegverknuepfung, fehlende Belege, Doppelbuchungen. Output: Belegketten-Übersicht. Abgrenzun... |
| `belegkette-rueckverfolgung-caching-rerun` | Nutze dies bei Belegkette Rueckverfolgung, Caching Und Teil Rerun, Dokumentstapel Aufnehmen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `caching-und-teil-rerun` | Zwischenergebnisse des 3D-Tabellenreviews cachen und Teilbereiche erneut ausführen ohne Vollneustart. Normen: technisch. Prüfraster: Cache-Status, verarbeitete Zeilen, Fehlerpunkte. Output: Rerun-Bericht mit gecachten und neu verarbeitet... |
| `chronologie-und-belegmatrix` | Nutze dies bei Chronologie und Belegmatrix: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `datenpunkt` | Nutze dies bei Datenpunkt: Dokumentenmatrix, Lückenliste und Nachforderung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `datenpunkt-dokument-excel-beweislast` | Nutze dies bei Datenpunkt Dokumentenmatrix Und Lueckenliste, Dokument Behörden Gericht Und Registerweg, Excel Beweislast Und Darlegungslast: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näch... |
| `dokument` | Nutze dies für Unterlagen zu Dokument: Behörden-, Gerichts- oder Registerweg: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `dokumentstapel-aufnehmen` | Dokumentenstapel für 3D-Tabellenreview einlesen: PDFs, Excel-Dateien, Word-Dokumente aufnehmen. Normen: §§ 174 ff. InsO. Prüfraster: Dateiformat-Kompatibilitaet, Metadaten, Importfehler. Output: Dokumentenstapel-Inventar. Abgrenzung: nic... |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `excel-beweislast-darlegungslast` | Nutze dies bei Excel: Beweislast, Darlegungslast und Substantiierung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `excel-multi-kreuzblatt-konsistenzpruefung-pdf` | Nutze dies bei Excel Multi Sheet Export, Kreuzblatt Konsistenzpruefung, Pdf Bericht Erzeugen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `excel-multi-sheet-export` | 3D-Review-Ergebnis als Excel-Datei mit mehreren Arbeitsblaettern exportieren: je Perspektive ein Sheet. Normen: HGB, InsO. Prüfraster: Formatvorgaben, Zellenformatierung, Formelkonsistenz. Output: Excel-Exportdatei Multisheet-Struktur. A... |
| `fristen-und-risikoampel` | Nutze dies bei Fristen- und Risikoampel: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `gestapelt` | Nutze dies bei Gestapelt: Compliance-Dokumentation und Aktenvermerk: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `gestapelt-immobilien-massenpruefung` | Nutze dies bei Gestapelt Compliance Dokumentation Und Akte, Immobilien Formular Portal Und Einreichung, Massenpruefung Mehrparteien Konflikt Und Interessen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `immobilien` | Nutze dies bei Immobilien: Formular, Portal und Einreichungslogik: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `kreuzblatt-konsistenzpruefung` | Kreuzblatt-Konsistenzprüfung: Abgleich der drei Dimensionen Forderung-Prüfung-Stellung auf Widerspruchsfreiheit. Normen: §§ 174 ff. InsO. Prüfraster: Betragsabweichungen, Statusinkonsistenzen, fehlende Eintraege. Output: Konsistenz-Prüfb... |
| `mandantenkommunikation` | Nutze dies bei Mandantenkommunikation: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `mandantenkommunikation-redteam-qualitygate` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Spaltenprompts Fristen Form Und Zustaendigkeit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `massenpruefung-interessen` | Nutze dies bei Massenpruefung: Mehrparteienkonflikt und Interessenmatrix: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `mehrblatt-sonderfall-edge-case` | Nutze dies bei Mehrblatt: Sonderfall und Edge-Case-Prüfung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `mehrblatt-sonderfall-onboarding-perspektiven` | Nutze dies bei Mehrblatt Sonderfall Und Edge Case, Onboarding Mandantenkommunikation Entscheidungsvorlage, Perspektiven Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `onboarding` | Nutze dies bei Onboarding: Mandantenkommunikation und Entscheidungsvorlage: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `pdf-bericht-erzeugen` | 3D-Review-Ergebnis als PDF-Bericht erzeugen: Zusammenfassung, Tabellen, Risikoampeln. Normen: §§ 174 ff. InsO. Prüfraster: Vollständigkeit Berichtinhalte, Layout, Signaturfeld. Output: PDF-Bericht 3D-Tabellenreview. Abgrenzung: nicht Exc... |
| `perspektiven` | Nutze dies bei Perspektiven: Verhandlung, Vergleich und Eskalation: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `professional-review-sheet` | Professional Review Sheet mit Rollen-, Daten- und Dokumentenperspektive: führt schnell durch Sachverhalt, Rechtsgrundlagen, Belege, Risiken und erzeugt einen verwertbaren nächsten Output. |
| `professional-review-tabellenreview-vendor-red` | Nutze dies bei Professional Review Sheet, Tabellenreview Erstpruefung Und Mandatsziel, Vendor Red Team Und Qualitaetskontrolle: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastba... |
| `prompt-versionierung` | Prompt-Versionen für den 3D-Review verwalten: Versionierung der Spaltenprompts und Zeilenprompts. Normen: technisch/governance. Prüfraster: Versionsnummer, Aenderungsprotokoll, aktive Version. Output: Prompt-Versionsprotokoll. Abgrenzung... |
| `prompt-versionierung-paket-review` | Nutze dies bei Prompt Versionierung, Prüfer Uebergabe Paket, Review Durchfuehren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `pruefer-uebergabe-paket` | Übergabepaket für Prüferwechsel im 3D-Review zusammenstellen: aktueller Stand, offene Positionen. Normen: §§ 174 ff. InsO. Prüfraster: Fortschrittsstand, kritische Punkte, Dokumentation. Output: Übergabedokument für naechsten Prüfer. Abg... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `redteam-qualitygate` | Nutze dies als Fehlerbremse bei Red-Team Qualitygate: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `review-durchfuehren` | 3D-Tabellenreview konkret durchführen: jede Zeile in allen drei Perspektiven prüfen und bewerten. Normen: §§ 174 ff. 176 InsO. Prüfraster: Forderungshoehe, Prüfergebnis je Spalte, Risikoampel, Ausnahmekennzeichnung. Output: Ausgefuellte... |
| `risikoampel-aggregation` | Risikoampeln für alle geprüften Positionen aggregieren: rot/gelb/gruen je Dimension. Normen: §§ 174 ff. InsO. Prüfraster: Ampellogik, Schwellenwerte, Gesamtrisikoeinschaetzung. Output: Risikoampel-Aggregationsbericht. Abgrenzung: nicht K... |
| `spaltenprompts` | Nutze dies bei Spaltenprompts: Fristen, Form, Zuständigkeit und Rechtsweg: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `spaltenprompts-definieren` | Spaltenprompts für die drei Prüfperspektiven des 3D-Tabellenreviews definieren. Normen: §§ 174 ff. InsO. Prüfraster: Prompt-Formulierung je Spalte, Normverankerung, Eindeutigkeit. Output: Spaltenprompts-Dokument. Abgrenzung: nicht Zeilen... |
| `steuer-quellenkarte` | Nutze dies zur Quellenprüfung bei Steuer Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `tabellenreview` | Nutze dies bei Tabellenreview: Erstprüfung, Rollenklärung und Mandatsziel: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `tabellenreview-3d-kaltstart-interview` | Kaltstart-Interview für den 3D-Tabellenreview: Fallkategorie, Tabellengrösse, Prüfzweck erfassen. Normen: §§ 174 ff. InsO, HGB. Prüfraster: Zweck, Datenlage, Perspektivenwahl, Exportformat. Output: Konfigurationsdokument für 3D-Review-St... |
| `tr3d-bestreitensgruende-leitfaden` | Leitfaden Bestreitensgruende systematisch: dem Grunde, der Hoehe, dem Rang, Verjaehrung, Aufrechnung. Pruefraster fuer Tabellenpruefer. |
| `tr3d-bestreitensgruende-leitfaden-02` | Nutze dies bei Tr3d Bestreitensgruende Leitfaden, Tr3d Feststellungsklage Tabellenfeststellung Spezial, Tr3d Massearmut Tabelle Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `tr3d-feststellungsklage-tabellenfeststellung` | Spezialfall Feststellungsklage zur Tabellenfeststellung § 180 InsO: Klagebefugnis, Frist, Streitwert. Pruefraster fuer Glaeubiger und Insolvenzverwalter. |
| `tr3d-massearmut-tabelle-spezial` | Spezialfall Tabellenfuehrung bei Massearmut: vereinfachte Quote, vereinfachtes Tabellenformat, BGH-Rechtsprechung. Pruefraster fuer Verwalter und Insolvenzgericht. |
| `tr3d-pruefkategorien-bauleiter` | Bauleiter Pruefkategorien fuer Insolvenztabellenreview: Forderungsgrund, Bewertung, Bestreitenshistorie, Verteilungsquote. Pruefraster fuer drei-dimensionalen Aufbau. |
| `tr3d-pruefkategorien-vorlage-vendor-wuerfel` | Nutze dies bei Tr3d Pruefkategorien Bauleiter, Vorlage Vendor Onboarding 3d, Wuerfel Aufbauen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `vendor-fehlerkatalog` | Nutze dies als Fehlerbremse bei Vendor Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `vertragsstapel` | Nutze dies bei Vertragsstapel: Internationaler Bezug und Schnittstellen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `vertragsstapel-vorlage-arbeitsvertrag` | Nutze dies bei Vertragsstapel Internationaler Bezug Und Schnittstellen, Vorlage Arbeitsvertrag Portfolio, Vorlage Immobilien Portfolio: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `vorlage-arbeitsvertrag-portfolio` | Vorlagetabelle für Portfolio-Review von Arbeitsvertraegen im 3D-Format: Forderung/Prüfung/Stellung. Normen: BGB, KSchG, ArbZG. Prüfraster: Vertragsbedingungen, Klauselgueltigkeit, HR-Compliance. Output: Arbeitsvertrag-Portfolio-Tabelle.... |
| `vorlage-immobilien-portfolio` | Vorlagetabelle für Portfolio-Review von Immobilienvertraegen im 3D-Format. Normen: §§ 535 ff. BGB, WEG, GrEStG. Prüfraster: Miete, Grundbuch, steuerliche Belastung, Instandhaltung. Output: Immobilien-Portfolio-Tabelle. Abgrenzung: nicht... |
| `vorlage-ma-arbeitsblatt-perspektiven-audit` | Nutze dies bei Vorlage Ma Due Diligence, Arbeitsblatt Perspektiven Definieren, Audit Trail Protokoll: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vorlage-ma-due-diligence` | Vorlagetabelle für M-und-A-Due-Diligence im 3D-Format: Forderungen, Verbindlichkeiten, Rechtsrisiken. Normen: GmbHG, AktG, HGB, InsO. Prüfraster: Vertragsrisiken, Haftungsuebernahme, steuerliche Lasten. Output: Due-Diligence-Tabelle für... |
| `vorlage-vendor-onboarding-3d` | Vorlagetabelle für Lieferanten-Onboarding-Review im 3D-Format: Vertrag, Compliance, Leistung. Normen: BGB, UWG, GWB. Prüfraster: Vertragskonformität, Compliance-Status, Leistungsindikatoren. Output: Vendor-Onboarding-Prüftabelle. Abgrenz... |
| `wirtschaft` | Nutze dies bei Wirtschaft: Zahlen, Schwellenwerte und Berechnung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `wirtschaft-wuerfel-zeilenprompts` | Nutze dies bei Wirtschaft Zahlen Schwellen Und Berechnung, Wuerfel Tatbestand Beweis Und Belege, Zeilenprompts Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nä... |
| `wuerfel` | Nutze dies bei Wuerfel: Tatbestandsmerkmale, Beweisfragen und Beleglage: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `wuerfel-aufbauen` | 3D-Wuerfelstruktur für den Tabellenreview aufbauen: Zeilen, Spalten, Perspektiven verknuepfen. Normen: §§ 174 ff. InsO. Prüfraster: Dimensionen-Vollständigkeit, Verknuepfungslogik, Konfiguration. Output: Wuerfelkonfigurationsdokument. Ab... |
| `zeilenprompts` | Nutze dies bei Zeilenprompts: Risikoampel, Gegenargumente und Verteidigungslinien: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `zeilenprompts-definieren` | Nutze dies bei Zeilenprompts Definieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
