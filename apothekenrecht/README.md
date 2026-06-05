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
| `allgemein` | Einstieg, Schnelltriage und Fallrouting im Apothekenrecht-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, erkennt stumme Uploads und schlägt passende Fachmodule aus diesem Plugin vor. |
| `amts-medikationsanalyse` | Nutze dies bei Amts Medikationsanalyse Beratungspflicht, Apothekenbetriebsordnung Grundpflichten, Apothekenerlaubnis Apog Persoenliche Voraussetzungen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefe... |
| `apothekenbetrieb-dokumentenintake` | Nutze dies für Unterlagen zu Apothekenbetrieb Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `apothekenrevision-vorbereitung` | Nutze dies bei Apothekenrevision Vorbereitung Antwort, Apothekenuebliche Waren Abgrenzung, Arzneimittelpruefung Ausgangsstoffe Pruefprotokoll: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nä... |
| `arzneimittelabgabe-verschreibungspflicht` | Nutze dies bei Arzneimittelabgabe Verschreibungspflicht, Cannabis Medizinalcannabis Abgabe Dokumentation, Tierarzneimittel Apothekenabgabe Versand Ab 2026: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und l... |
| `arzneimittelrisiken-rueckruf-aufsicht` | Nutze dies bei Arzneimittelrisiken Rueckruf Chargenrueckverfolgung, Aufsicht Anhoerung Ordnungswidrigkeit, Beanstandung Durch Aufsichtsbehoerde Anhoerung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und li... |
| `beschwerdemanagement-patient-blutprodukte` | Nutze dies bei Beschwerdemanagement Patient Kunden, Blutprodukte Haemophilie Registerpflicht, Btm Rezept Betaeubungsmittel Dokumentation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächste... |
| `btm-rezeptur-audit-apothekenverbund` | Nutze dies bei Btm Rezeptur Amts Schnellcheck, Compliance Audit Apothekenverbund, Datenschutz In Apotheke Gesundheitsdaten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `defektur-100er-dienstbereitschaft-notdienst` | Nutze dies bei Defektur 100er Regel Qualitaetssicherung, Dienstbereitschaft Notdienst Schliessung, Digitale Plattformen Marktplatz Apothekenrecht: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert de... |
| `e-rezept-erlaubnis-filialverbund` | Nutze dies bei E Rezept Ti Gematik Apothekenprozess, Erlaubnis Filialverbund Routing, Filialapotheke Hauptapotheke Leitung Vertretung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten b... |
| `fremd-mehrbesitzverbot-gefahrstoffe` | Nutze dies bei Fremd Und Mehrbesitzverbot Apothekenrecht, Gefahrstoffe Chemikalien Ausgangsstoffe, Hygiene Pandemie Infektionsschutz: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten be... |
| `heimversorgung-versorgungsvertrag-mietvertrag` | Nutze dies bei Heimversorgung Versorgungsvertrag, Mietvertrag Apothekenstandort Konkurrenzschutz, Substitution Rabattvertrag Aut Idem: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten b... |
| `impfleistungen-apotheken-import-einzelimport` | Nutze dies bei Impfleistungen In Apotheken, Import Einzelimport 73 Amg, Inhaberwechsel Kauf Apothekenbetrieb: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `kaltstart-apothekenrecht` | Nutze dies zum Einstieg in Kaltstart Apothekenrecht: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `kooperation-arzt-krankenhausversorgung` | Nutze dies bei Kooperation Arzt Apotheke Antikorruption, Krankenhausversorgung Krankenhausapotheke, Kuehlkette Temperaturmonitoring Gdp: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `lieferengpaesse-austausch-livecheck-apog` | Nutze dies bei Lieferengpaesse Austausch Dokumentation, Livecheck Apog Apbetro Amg, Notfallkontrazeption Beratung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitssc... |
| `onlinewerbung-hwg-owi-strafrisiken-personal` | Nutze dies bei Onlinewerbung Hwg Apotheken, Owi Strafrisiken Apog Amg Btmg, Personal Pharmazeutisch Nichtpharmazeutisch Vertretung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `output-behoerdenbrief-sop-mandantenmemo` | Nutze dies bei Output Behördenbrief SOP Mandantenmemo: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `pharmazeutische-dienstleistungen-preisangaben` | Nutze dies bei Pharmazeutische Dienstleistungen Verguetung, Preisangaben E Commerce Apotheke, Preisbindung Arzneimittel Ampreisv: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belast... |
| `qualitaetsmanagement-qms-raeume-ausstattung` | Nutze dies bei Qualitaetsmanagement Qms Sops, Raeume Ausstattung Rezeptur Defektur Labor, Rechnung Retaxation Krankenkasse: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `retaxationsabwehr-nullretax` | Nutze dies bei Retaxationsabwehr Nullretax Risiko, Rezeptsammelstelle Botendienst Versandhandel, Rezeptur Plausibilitaetspruefung Herstellungsanweisung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lief... |
| `schiedsstellen-krankenkassen-schweigepflicht` | Nutze dies bei Schiedsstellen Krankenkassen Apotheke, Schweigepflicht Berufsrecht Pta Approbation, Securpharm Faelschungsschutz: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastb... |
| `skonti-boni-t-rezept-telepharmazie-grenzen` | Nutze dies bei Skonti Boni Rabatte Zuweisungsverbot, T Rezept Besondere Arzneimittel, Telepharmazie Grenzen Chancen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeits... |
| `versandhandel-e-versandhandelserlaubnis-eu` | Nutze dies bei Versandhandel Und E Rezept Intake, Versandhandelserlaubnis Eu Versandapotheke, Versorgung Pflegeheim Schnittstelle: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belas... |
| `widerruf-ruecknahme` | Nutze dies bei Widerruf Ruecknahme Ruhen Apothekenerlaubnis: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
