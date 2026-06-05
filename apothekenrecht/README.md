# Apothekenrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`apothekenrecht`) | [`apothekenrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/apothekenrecht.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

Super-Plugin für Apothekenrecht: Betriebserlaubnis, ApBetrO, Versand, E-Rezept, BtM, Retaxation, Aufsicht und Compliance.

## Wofür dieses Plugin da ist
Apothekenrecht zwischen ApoG, ApBetrO, AMG, AMPreisV, SGB V, HWG, BtMG, Datenschutz, Aufsicht, Versandhandel, E-Rezept und Apothekenpraxis.

Das Plugin ist als Arbeitswerkzeug gedacht: Es startet mit einem Kaltstart-Interview, sortiert Unterlagen, prüft Fristen und routet dann in Spezial-Skills. Es soll Anfänger an die Hand nehmen und Profis schnell zu belastbaren Outputs bringen.

## Typischer Workflow
1. **Allgemein-Skill starten:** Rolle, Ziel, Frist, Unterlagen und gewünschtes Ergebnis klären.
2. **Dokumente einlesen:** Verträge, Bescheide, Rechnungen, Tabellen, Registerdaten, Behördenpost oder Screenshots strukturieren.
3. **Spezial-Skill wählen:** Das Plugin schlägt den passenden Skill vor und erklärt, welches Ergebnis damit entsteht.
4. **Live-Quellen prüfen:** Normtext, Behördenseite, EU-Text, Formular oder frei zugängliche Rechtsprechung aktualisieren.
5. **Output erzeugen:** Memo, Antrag, Stellungnahme, Vertragsklausel, Berechnung, Checkliste oder Mandantenbrief.
6. **Red-Team:** Fristen, Zuständigkeit, Zahlen, Quellen und Gegenargumente kontrollieren.

## Quellenanker
- Amtliche Gesetzestexte: gesetze-im-internet.de.
- EU-Recht: EUR-Lex und amtliche Kommissionsseiten.
- Behördenpraxis: zuständige Bundes-/Landesbehörden, Bundesnetzagentur, BaFin, BfArM, G-BA, BKartA oder Länderstellen je nach Thema.
- Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und frei/amtlich prüfbarer Quelle.

## Skill-Schwerpunkte
| Gruppe | Inhalt |
| --- | --- |
| Einstieg und Workflow | Kaltstart, Dokumentenintake, Fristen, Quellencheck, Output-Wahl, Red-Team |
| Materielle Prüfung | Tatbestände, Ausnahmen, Schwellen, Beweislast, Berechnungen, Rechtsfolgen |
| Verfahren und Kommunikation | Anträge, Anhörungen, Beschwerden, Schriftsätze, Behördenkontakt, Mandantenkommunikation |
| Spezialthemen | Branchen-, Vertrags-, Gebühren-, Aufsichts-, EU- und Edge-Case-Prüfungen |

## Quellen- und Halluzinationsschutz
Dieses Plugin soll keine nicht prüfbaren Fundstellen produzieren. Bei unsicherer oder dynamischer Rechtslage wird der Live-Quellencheck ausdrücklich vorgeschaltet.

## Lizenz
Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 25 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `amts-medikationsanalyse` | Amts Medikationsanalyse Beratungspflicht, Apothekenbetriebsordnung Grundpflichten, Apothekenerlaubnis Apog Persoenliche Voraussetzungen: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert de... |
| `apothekenbetrieb-dokumentenintake` | Apothekenbetrieb Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `apothekenrecht-kaltstart-triage` | Einstieg, Schnelltriage und Fallrouting im Apothekenrecht-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, erkennt stumme Uploads und schlägt passende Fachmodule aus diesem Plugin vor. |
| `apothekenrevision-vorbereitung` | Apothekenrevision Vorbereitung Antwort, Apothekenuebliche Waren Abgrenzung, Arzneimittelpruefung Ausgangsstoffe Pruefprotokoll: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächste... |
| `arzneimittelabgabe-verschreibungspflicht` | Arzneimittelabgabe Verschreibungspflicht, Cannabis Medizinalcannabis Abgabe Dokumentation, Tierarzneimittel Apothekenabgabe Versand Ab 2026: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefer... |
| `arzneimittelrisiken-rueckruf-aufsicht` | Arzneimittelrisiken Rueckruf Chargenrueckverfolgung, Aufsicht Anhoerung Ordnungswidrigkeit, Beanstandung Durch Aufsichtsbehoerde Anhoerung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert... |
| `beschwerdemanagement-patient-blutprodukte` | Beschwerdemanagement Patient Kunden, Blutprodukte Haemophilie Registerpflicht, Btm Rezept Betaeubungsmittel Dokumentation: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten bel... |
| `btm-rezeptur-audit-apothekenverbund` | Btm Rezeptur Amts Schnellcheck, Compliance Audit Apothekenverbund, Datenschutz In Apotheke Gesundheitsdaten: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `defektur-100er-dienstbereitschaft-notdienst` | Defektur 100er Regel Qualitaetssicherung, Dienstbereitschaft Notdienst Schliessung, Digitale Plattformen Marktplatz Apothekenrecht: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den näc... |
| `e-rezept-erlaubnis-filialverbund` | E Rezept Ti Gematik Apothekenprozess, Erlaubnis Filialverbund Routing, Filialapotheke Hauptapotheke Leitung Vertretung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belast... |
| `fremd-mehrbesitzverbot-gefahrstoffe` | Fremd Und Mehrbesitzverbot Apothekenrecht, Gefahrstoffe Chemikalien Ausgangsstoffe, Hygiene Pandemie Infektionsschutz: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastb... |
| `heimversorgung-versorgungsvertrag-mietvertrag` | Heimversorgung Versorgungsvertrag, Mietvertrag Apothekenstandort Konkurrenzschutz, Substitution Rabattvertrag Aut Idem: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belast... |
| `impfleistungen-apotheken-import-einzelimport` | Impfleistungen In Apotheken, Import Einzelimport 73 Amg, Inhaberwechsel Kauf Apothekenbetrieb: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `kaltstart-apothekenrecht` | Kaltstart Apothekenrecht: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `kooperation-arzt-krankenhausversorgung` | Kooperation Arzt Apotheke Antikorruption, Krankenhausversorgung Krankenhausapotheke, Kuehlkette Temperaturmonitoring Gdp: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten bela... |
| `lieferengpaesse-austausch-livecheck-apog` | Lieferengpaesse Austausch Dokumentation, Livecheck Apog Apbetro Amg, Notfallkontrazeption Beratung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `onlinewerbung-hwg-owi-strafrisiken-personal` | Onlinewerbung Hwg Apotheken, Owi Strafrisiken Apog Amg Btmg, Personal Pharmazeutisch Nichtpharmazeutisch Vertretung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbar... |
| `output-behoerdenbrief-sop-mandantenmemo` | Output Behördenbrief SOP Mandantenmemo: prüft Normen, Belege, Risiken, Gegenargumente und erzeugt ein verwertbares Arbeitsergebnis. |
| `pharmazeutische-dienstleistungen-preisangaben` | Pharmazeutische Dienstleistungen Verguetung, Preisangaben E Commerce Apotheke, Preisbindung Arzneimittel Ampreisv: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren... |
| `qualitaetsmanagement-qms-raeume-ausstattung` | Qualitaetsmanagement Qms Sops, Raeume Ausstattung Rezeptur Defektur Labor, Rechnung Retaxation Krankenkasse: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `retaxationsabwehr-nullretax` | Retaxationsabwehr Nullretax Risiko, Rezeptsammelstelle Botendienst Versandhandel, Rezeptur Plausibilitaetspruefung Herstellungsanweisung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert d... |
| `schiedsstellen-krankenkassen-schweigepflicht` | Schiedsstellen Krankenkassen Apotheke, Schweigepflicht Berufsrecht Pta Approbation, Securpharm Faelschungsschutz: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren... |
| `skonti-boni-t-rezept-telepharmazie-grenzen` | Skonti Boni Rabatte Zuweisungsverbot, T Rezept Besondere Arzneimittel, Telepharmazie Grenzen Chancen: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `versandhandel-e-versandhandelserlaubnis-eu` | Versandhandel Und E Rezept Intake, Versandhandelserlaubnis Eu Versandapotheke, Versorgung Pflegeheim Schnittstelle: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbare... |
| `widerruf-ruecknahme` | Widerruf Ruecknahme Ruhen Apothekenerlaubnis: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
