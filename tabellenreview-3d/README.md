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
| `aggregation-spaltenprompts-definieren` | Nutze dies, wenn Risikoampel Aggregation, Spaltenprompts Definieren, Spezial Arbeitsblatt Schriftsatz Brief Und Memo Bausteine im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Risikoampel Aggregation, Spaltenpr... |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Tabellenreview 3d-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Spezial-Skills aus diesem Plugin vor und führt in einen klaren Arbeitsplan.... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fris... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Tabellenreview 3d.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `arbeitsblatt` | Nutze dies, wenn Arbeitsblatt: Schriftsatz-, Brief- und Memo-Bausteine im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Arbeitsblatt: Schriftsatz-, Brief- und Memo-Bausteine prüfen.; Erstelle eine Arbeitsfassun... |
| `arbeitsblatt-perspektiven-definieren` | Drei Prüfperspektiven (Spalten) für den 3D-Tabellenreview definieren: Forderung, Prüfung, Stellung nach §§ 174 ff. InsO. Normen: §§ 174 ff. InsO, ZPO. Prüfraster: Forderungsaufstellung, Prüfungsraster, Gläubigerstellung. Output: Perspekt... |
| `audit-trail-protokoll` | Audit-Trail aller Review-Schritte protokollieren: wer hat wann was geprüft und geaendert. Normen: §§ 238 257 HGB Buchführungspflichten. Prüfraster: Zeitstempel, Prüfer-ID, Aenderungshistorie, Versionierung. Output: Audit-Trail-Protokoll.... |
| `belegkette-rueckverfolgung` | Belegkette für Forderungen und Zahlungen zurückverfolgen: Originalbeleg, Buchung, Zahlung. Normen: §§ 238 257 HGB, §§ 174 ff. InsO. Prüfraster: Belegverknuepfung, fehlende Belege, Doppelbuchungen. Output: Belegketten-Übersicht. Abgrenzun... |
| `belegkette-rueckverfolgung-caching-rerun` | Nutze dies, wenn Belegkette Rueckverfolgung, Caching Und Teil Rerun, Dokumentstapel Aufnehmen im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `caching-und-teil-rerun` | Zwischenergebnisse des 3D-Tabellenreviews cachen und Teilbereiche erneut ausführen ohne Vollneustart. Normen: technisch. Prüfraster: Cache-Status, verarbeitete Zeilen, Fehlerpunkte. Output: Rerun-Bericht mit gecachten und neu verarbeitet... |
| `chronologie-und-belegmatrix` | Nutze dies, wenn Chronologie und Belegmatrix im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Chronologie und Belegmatrix prüfen.; Erstelle eine Arbeitsfassung zu Chronologie und Belegmatrix.; Welche Normen und... |
| `datenpunkt` | Nutze dies, wenn Datenpunkt: Dokumentenmatrix, Lückenliste und Nachforderung im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `datenpunkt-dokument-excel-beweislast` | Nutze dies, wenn Spezial Datenpunkt Dokumentenmatrix Und Lueckenliste, Spezial Dokument Behörden Gericht Und Registerweg, Spezial Excel Beweislast Und Darlegungslast im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: I... |
| `dokument` | Nutze dies, wenn Dokument: Behörden-, Gerichts- oder Registerweg im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `dokumentstapel-aufnehmen` | Dokumentenstapel für 3D-Tabellenreview einlesen: PDFs, Excel-Dateien, Word-Dokumente aufnehmen. Normen: §§ 174 ff. InsO. Prüfraster: Dateiformat-Kompatibilitaet, Metadaten, Importfehler. Output: Dokumentenstapel-Inventar. Abgrenzung: nic... |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Tabellenreview 3d.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `excel-beweislast-darlegungslast` | Nutze dies, wenn Excel: Beweislast, Darlegungslast und Substantiierung im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Excel: Beweislast, Darlegungslast und Substantiierung prüfen.; Erstelle eine Arbeitsfassun... |
| `excel-multi-kreuzblatt-konsistenzpruefung-pdf` | Nutze dies, wenn Excel Multi Sheet Export, Kreuzblatt Konsistenzpruefung, Pdf Bericht Erzeugen im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Excel Multi Sheet Export, Kreuzblatt Konsistenzpruefung, Pdf Beric... |
| `excel-multi-sheet-export` | 3D-Review-Ergebnis als Excel-Datei mit mehreren Arbeitsblaettern exportieren: je Perspektive ein Sheet. Normen: HGB, InsO. Prüfraster: Formatvorgaben, Zellenformatierung, Formelkonsistenz. Output: Excel-Exportdatei Multisheet-Struktur. A... |
| `fristen-und-risikoampel` | Nutze dies, wenn Fristen- und Risikoampel im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Fristen- und Risikoampel prüfen.; Erstelle eine Arbeitsfassung zu Fristen- und Risikoampel.; Welche Normen und Nachweis... |
| `gestapelt` | Nutze dies, wenn Gestapelt: Compliance-Dokumentation und Aktenvermerk im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `gestapelt-immobilien-massenpruefung` | Nutze dies, wenn Spezial Gestapelt Compliance Dokumentation Und Akte, Spezial Immobilien Formular Portal Und Einreichung, Spezial Massenpruefung Mehrparteien Konflikt Und Interessen im Plugin Tabellenreview 3d konkret bearbeitet werden s... |
| `immobilien` | Nutze dies, wenn Immobilien: Formular, Portal und Einreichungslogik im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Immobilien: Formular, Portal und Einreichungslogik prüfen.; Erstelle eine Arbeitsfassung zu I... |
| `kreuzblatt-konsistenzpruefung` | Kreuzblatt-Konsistenzprüfung: Abgleich der drei Dimensionen Forderung-Prüfung-Stellung auf Widerspruchsfreiheit. Normen: §§ 174 ff. InsO. Prüfraster: Betragsabweichungen, Statusinkonsistenzen, fehlende Eintraege. Output: Konsistenz-Prüfb... |
| `mandantenkommunikation` | Nutze dies, wenn Mandantenkommunikation im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Mandantenkommunikation prüfen.; Erstelle eine Arbeitsfassung zu Mandantenkommunikation.; Welche Normen und Nachweise brau... |
| `mandantenkommunikation-redteam-qualitygate` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Spaltenprompts Fristen Form Und Zustaendigkeit im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitt... |
| `massenpruefung-interessen` | Nutze dies, wenn Massenpruefung: Mehrparteienkonflikt und Interessenmatrix im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Massenpruefung: Mehrparteienkonflikt und Interessenmatrix prüfen.; Erstelle eine Arbei... |
| `mehrblatt-sonderfall-edge-case` | Nutze dies, wenn Mehrblatt: Sonderfall und Edge-Case-Prüfung im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Mehrblatt: Sonderfall und Edge-Case-Prüfung prüfen.; Erstelle eine Arbeitsfassung zu Mehrblatt: Sond... |
| `mehrblatt-sonderfall-onboarding-perspektiven` | Nutze dies, wenn Spezial Mehrblatt Sonderfall Und Edge Case, Spezial Onboarding Mandantenkommunikation Entscheidungsvorlage, Spezial Perspektiven Verhandlung Vergleich Und Eskalation im Plugin Tabellenreview 3d konkret bearbeitet werden... |
| `onboarding` | Nutze dies, wenn Onboarding: Mandantenkommunikation und Entscheidungsvorlage im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Onboarding: Mandantenkommunikation und Entscheidungsvorlage prüfen.; Erstelle eine A... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `pdf-bericht-erzeugen` | 3D-Review-Ergebnis als PDF-Bericht erzeugen: Zusammenfassung, Tabellen, Risikoampeln. Normen: §§ 174 ff. InsO. Prüfraster: Vollständigkeit Berichtinhalte, Layout, Signaturfeld. Output: PDF-Bericht 3D-Tabellenreview. Abgrenzung: nicht Exc... |
| `perspektiven` | Nutze dies, wenn Perspektiven: Verhandlung, Vergleich und Eskalation im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Perspektiven: Verhandlung, Vergleich und Eskalation prüfen.; Erstelle eine Arbeitsfassung zu... |
| `professional-review-sheet` | Professional Review Sheet mit Rollen-, Daten- und Dokumentenperspektive: führt schnell durch Sachverhalt, Rechtsgrundlagen, Belege, Risiken und erzeugt einen verwertbaren nächsten Output. |
| `professional-review-tabellenreview-vendor-red` | Nutze dies, wenn Spezial Professional Review Sheet, Spezial Tabellenreview Erstpruefung Und Mandatsziel, Spezial Vendor Red Team Und Qualitaetskontrolle im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Was kann hier... |
| `prompt-versionierung` | Prompt-Versionen für den 3D-Review verwalten: Versionierung der Spaltenprompts und Zeilenprompts. Normen: technisch/governance. Prüfraster: Versionsnummer, Aenderungsprotokoll, aktive Version. Output: Prompt-Versionsprotokoll. Abgrenzung... |
| `prompt-versionierung-paket-review` | Nutze dies, wenn Prompt Versionierung, Prüfer Übergabe Paket, Review Durchfuehren im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Prompt Versionierung, Prüfer Übergabe Paket, Review Durchfuehren prüfen.; Erste... |
| `pruefer-uebergabe-paket` | Übergabepaket für Prüferwechsel im 3D-Review zusammenstellen: aktueller Stand, offene Positionen. Normen: §§ 174 ff. InsO. Prüfraster: Fortschrittsstand, kritische Punkte, Dokumentation. Output: Übergabedokument für naechsten Prüfer. Abg... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `redteam-qualitygate` | Nutze dies, wenn Red-Team Qualitygate im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `review-durchfuehren` | 3D-Tabellenreview konkret durchführen: jede Zeile in allen drei Perspektiven prüfen und bewerten. Normen: §§ 174 ff. 176 InsO. Prüfraster: Forderungshoehe, Prüfergebnis je Spalte, Risikoampel, Ausnahmekennzeichnung. Output: Ausgefuellte... |
| `risikoampel-aggregation` | Risikoampeln für alle geprüften Positionen aggregieren: rot/gelb/gruen je Dimension. Normen: §§ 174 ff. InsO. Prüfraster: Ampellogik, Schwellenwerte, Gesamtrisikoeinschaetzung. Output: Risikoampel-Aggregationsbericht. Abgrenzung: nicht K... |
| `spaltenprompts` | Nutze dies, wenn Spaltenprompts: Fristen, Form, Zuständigkeit und Rechtsweg im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Spaltenprompts: Fristen, Form, Zuständigkeit und Rechtsweg prüfen.; Erstelle eine Arb... |
| `spaltenprompts-definieren` | Spaltenprompts für die drei Prüfperspektiven des 3D-Tabellenreviews definieren. Normen: §§ 174 ff. InsO. Prüfraster: Prompt-Formulierung je Spalte, Normverankerung, Eindeutigkeit. Output: Spaltenprompts-Dokument. Abgrenzung: nicht Zeilen... |
| `steuer-quellenkarte` | Nutze dies, wenn Steuer Quellenkarte im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `tabellenreview` | Nutze dies, wenn Tabellenreview: Erstprüfung, Rollenklärung und Mandatsziel im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Tabellenreview: Erstprüfung, Rollenklärung und Mandatsziel prüfen.; Erstelle eine Arb... |
| `tabellenreview-3d-kaltstart-interview` | Kaltstart-Interview für den 3D-Tabellenreview: Fallkategorie, Tabellengrösse, Prüfzweck erfassen. Normen: §§ 174 ff. InsO, HGB. Prüfraster: Zweck, Datenlage, Perspektivenwahl, Exportformat. Output: Konfigurationsdokument für 3D-Review-St... |
| `tr3d-bestreitensgruende-leitfaden` | Leitfaden Bestreitensgruende systematisch: dem Grunde, der Hoehe, dem Rang, Verjaehrung, Aufrechnung. Pruefraster fuer Tabellenpruefer. |
| `tr3d-bestreitensgruende-leitfaden-02` | Nutze dies, wenn Tr3D Bestreitensgruende Leitfaden, Tr3D Feststellungsklage Tabellenfeststellung Spezial, Tr3D Massearmut Tabelle Spezial im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Tr3D Bestreitensgruende... |
| `tr3d-feststellungsklage-tabellenfeststellung` | Spezialfall Feststellungsklage zur Tabellenfeststellung § 180 InsO: Klagebefugnis, Frist, Streitwert. Pruefraster fuer Glaeubiger und Insolvenzverwalter. |
| `tr3d-massearmut-tabelle-spezial` | Spezialfall Tabellenfuehrung bei Massearmut: vereinfachte Quote, vereinfachtes Tabellenformat, BGH-Rechtsprechung. Pruefraster fuer Verwalter und Insolvenzgericht. |
| `tr3d-pruefkategorien-bauleiter` | Bauleiter Pruefkategorien fuer Insolvenztabellenreview: Forderungsgrund, Bewertung, Bestreitenshistorie, Verteilungsquote. Pruefraster fuer drei-dimensionalen Aufbau. |
| `tr3d-pruefkategorien-vorlage-vendor-wuerfel` | Nutze dies, wenn Tr3D Pruefkategorien Bauleiter, Vorlage Vendor Onboarding 3D, Wuerfel Aufbauen im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Tr3D Pruefkategorien Bauleiter, Vorlage Vendor Onboarding 3D, Wue... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `vendor-fehlerkatalog` | Nutze dies, wenn Vendor Fehlerkatalog im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `vertragsstapel` | Nutze dies, wenn Vertragsstapel: Internationaler Bezug und Schnittstellen im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Vertragsstapel: Internationaler Bezug und Schnittstellen prüfen.; Erstelle eine Arbeits... |
| `vertragsstapel-vorlage-arbeitsvertrag` | Nutze dies, wenn Spezial Vertragsstapel Internationaler Bezug Und Schnittstellen, Vorlage Arbeitsvertrag Portfolio, Vorlage Immobilien Portfolio im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Spezial Vertrags... |
| `vorlage-arbeitsvertrag-portfolio` | Vorlagetabelle für Portfolio-Review von Arbeitsvertraegen im 3D-Format: Forderung/Prüfung/Stellung. Normen: BGB, KSchG, ArbZG. Prüfraster: Vertragsbedingungen, Klauselgueltigkeit, HR-Compliance. Output: Arbeitsvertrag-Portfolio-Tabelle.... |
| `vorlage-immobilien-portfolio` | Vorlagetabelle für Portfolio-Review von Immobilienvertraegen im 3D-Format. Normen: §§ 535 ff. BGB, WEG, GrEStG. Prüfraster: Miete, Grundbuch, steuerliche Belastung, Instandhaltung. Output: Immobilien-Portfolio-Tabelle. Abgrenzung: nicht... |
| `vorlage-ma-arbeitsblatt-perspektiven-audit` | Nutze dies, wenn Vorlage Ma Due Diligence, Arbeitsblatt Perspektiven Definieren, Audit Trail Protokoll im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Vorlage Ma Due Diligence, Arbeitsblatt Perspektiven Defini... |
| `vorlage-ma-due-diligence` | Vorlagetabelle für M-und-A-Due-Diligence im 3D-Format: Forderungen, Verbindlichkeiten, Rechtsrisiken. Normen: GmbHG, AktG, HGB, InsO. Prüfraster: Vertragsrisiken, Haftungsuebernahme, steuerliche Lasten. Output: Due-Diligence-Tabelle für... |
| `vorlage-vendor-onboarding-3d` | Vorlagetabelle für Lieferanten-Onboarding-Review im 3D-Format: Vertrag, Compliance, Leistung. Normen: BGB, UWG, GWB. Prüfraster: Vertragskonformität, Compliance-Status, Leistungsindikatoren. Output: Vendor-Onboarding-Prüftabelle. Abgrenz... |
| `wirtschaft` | Nutze dies, wenn Wirtschaft: Zahlen, Schwellenwerte und Berechnung im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Wirtschaft: Zahlen, Schwellenwerte und Berechnung prüfen.; Erstelle eine Arbeitsfassung zu Wir... |
| `wirtschaft-wuerfel-zeilenprompts` | Nutze dies, wenn Spezial Wirtschaft Zahlen Schwellen Und Berechnung, Spezial Wuerfel Tatbestand Beweis Und Belege, Spezial Zeilenprompts Risikoampel Und Gegenargumente im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser:... |
| `wuerfel` | Nutze dies, wenn Wuerfel: Tatbestandsmerkmale, Beweisfragen und Beleglage im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Wuerfel: Tatbestandsmerkmale, Beweisfragen und Beleglage prüfen.; Erstelle eine Arbeits... |
| `wuerfel-aufbauen` | 3D-Wuerfelstruktur für den Tabellenreview aufbauen: Zeilen, Spalten, Perspektiven verknuepfen. Normen: §§ 174 ff. InsO. Prüfraster: Dimensionen-Vollständigkeit, Verknuepfungslogik, Konfiguration. Output: Wuerfelkonfigurationsdokument. Ab... |
| `zeilenprompts` | Nutze dies, wenn Zeilenprompts: Risikoampel, Gegenargumente und Verteidigungslinien im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Zeilenprompts: Risikoampel, Gegenargumente und Verteidigungslinien prüfen.; E... |
| `zeilenprompts-definieren` | Nutze dies, wenn Zeilenprompts Definieren im Plugin Tabellenreview 3d konkret bearbeitet werden soll. Auslöser: Bitte Zeilenprompts Definieren prüfen.; Erstelle eine Arbeitsfassung zu Zeilenprompts Definieren.; Welche Normen und Nachweis... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
