# Bundeswehrrecht und Wehrrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`bundeswehrrecht-wehrrecht`) | [`bundeswehrrecht-wehrrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/bundeswehrrecht-wehrrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **KDV-Verfahren Malte Eberhard Rabenow / Berlin-Köln 2026** (`kriegsdienstverweigerung-gewissensantrag-berlin-2026`) | [Gesamt-PDF lesen](../testakten/kriegsdienstverweigerung-gewissensantrag-berlin-2026/gesamt-pdf/kriegsdienstverweigerung-gewissensantrag-berlin-2026_gesamt.pdf) | [`testakte-kriegsdienstverweigerung-gewissensantrag-berlin-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kriegsdienstverweigerung-gewissensantrag-berlin-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Super-Plugin für Soldatenrecht, Wehrbeschwerde, Disziplinarrecht, Wehrpflicht, Reservisten, Versorgung und Bundeswehrverwaltung.

## Wofür dieses Plugin da ist
Bundeswehrrecht mit Soldatengesetz, Wehrbeschwerdeordnung, Wehrdisziplinarordnung, Wehrpflichtgesetz, Reservistenrecht, Soldatenversorgung, Befehlsrecht, Fürsorge und Rechtsschutz.

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

Automatisch generierte Komplett-Liste aller 30 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `akteneinsicht-wbo-arbeitsrecht-zivile` | Akteneinsicht WBO Arbeitsrecht Zivile im Bundeswehrrecht / Wehrrecht: prüft konkret Akteneinsicht WBO und WDO, Arbeitsrecht zivile Bundeswehrbeschäftigte, Rückforderung Ausbildungskosten Bundeswehr. Liefert priorisierten Output mit Norm-... |
| `auslandseinsatz-einsatzregeln-beamtenrecht` | Auslandseinsatz Einsatzregeln Beamtenrecht im Bundeswehrrecht / Wehrrecht: prüft konkret Auslandseinsatz Mandat Einsatzregeln, Beamtenrecht Bundeswehrverwaltung Abgrenzung, Befehlsverweigerung, Gewissensnot. Liefert priorisierten Output... |
| `beschwerde-besoldung-zulagen-beurteilung` | Beschwerde Besoldung Zulagen Beurteilung im Bundeswehrrecht / Wehrrecht: prüft konkret Beschwerde gegen Beurteilung und Laufbahnentscheidung, Besoldung, Zulagen, AVZ. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächs... |
| `beschwerde-sofortcheck-bwbes` | Beschwerde Sofortcheck Bwbes im Bundeswehrrecht / Wehrrecht: prüft konkret Beschwerde-Fristen Sofortcheck WBO, Besoldungswiderspruch Soldat, Disziplinarverfahren Intake. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nä... |
| `bundesverwaltungsgericht-wehrdienstsenate` | Bundesverwaltungsgericht Wehrdienstsenate im Bundeswehrrecht / Wehrrecht: prüft konkret Bundesverwaltungsgericht Wehrdienstsenate, Soldatenbesoldung Grundgehalt Dienstgrad, Wehrsold FWD Unterhaltssicherung. Liefert priorisierten Output m... |
| `bundeswehrrecht-wehrrecht-kaltstart-triage` | Einstieg, Schnelltriage und Fallrouting im Bundeswehrrecht und Wehrrecht-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, erkennt stumme Uploads und schlägt passende Fachmodule aus diesem Plugin vor. |
| `bwbes-auslandsverwendungszuschlag` | Bwbes Auslandsverwendungszuschlag im Bundeswehrrecht / Wehrrecht: prüft konkret AVZ und Einsatzversorgung, Trennungsgeld, Umzugskosten, Reisebeihilfe. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `bwbes-besoldung-reservist-kdv` | Bwbes Besoldung Reservist KDV im Bundeswehrrecht / Wehrrecht: prüft konkret Besoldung Reservisten, Wehrübung, Arbeitgeberausgleich, KDV und Besoldungsfolgen Statuswechsel. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und... |
| `bwbes-dienstzeitversorgung` | Bwbes Dienstzeitversorgung im Bundeswehrrecht / Wehrrecht: prüft konkret Dienstzeitversorgung und BFD, Dienstunfall und WDB, Heilfürsorge, truppenärztliche Versorgung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näch... |
| `bwbes-verwendungsfaehigkeit-tauglichkeit` | Bwbes Verwendungsfaehigkeit Tauglichkeit im Bundeswehrrecht / Wehrrecht: prüft konkret Verwendungsfähigkeit, Tauglichkeit, finanzielle Folgen, Auslandseinsatz Anerkennung und Nachweise. Liefert priorisierten Output mit Norm-Pinpoints, Ri... |
| `dienstunfaehigkeit-entlassung-dienstzeit` | Dienstunfaehigkeit Entlassung Dienstzeit im Bundeswehrrecht / Wehrrecht: prüft konkret Dienstunfähigkeit Entlassung Zurruhesetzung, Dienstzeiten SaZ, BeruSold, FWDL. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächst... |
| `eilverfahren-konkurrentenstreit` | Eilverfahren Konkurrentenstreit im Bundeswehrrecht / Wehrrecht: prüft konkret Eilverfahren Konkurrentenstreit Wehrdienstsenat, Fristenkalender Bundeswehrrecht, Gerichtliches Disziplinarverfahren TDG. Liefert priorisierten Output mit Norm... |
| `einsatzunfall-wehrdienstbeschaedigung` | Einsatzunfall Wehrdienstbeschaedigung im Bundeswehrrecht / Wehrrecht: prüft konkret Einsatzunfall Wehrdienstbeschädigung, Entlassung auf eigenen Antrag, Ernennung, Dienstgrad. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel... |
| `extremismus-verdachtsfall-geheimschutz` | Extremismus Verdachtsfall Geheimschutz im Bundeswehrrecht / Wehrrecht: prüft konkret Extremismus-Verdachtsfall und Sicherheitsrecht Bundeswehr, Geheimschutz und Sicherheitsüberprüfung SÜG, Gehorsam Befehl und rechtswidriger Befehl. Liefe... |
| `gleichstellung-diskriminierung-impfpflicht` | Gleichstellung Diskriminierung Impfpflicht im Bundeswehrrecht / Wehrrecht: prüft konkret Gleichstellung und Diskriminierung Soldatinnen und Soldaten, Impfpflicht, Tauglichkeit und Musterung, Kameradschaft. Liefert priorisierten Output mi... |
| `kaltstart-bundeswehrrecht` | Kaltstart Bundeswehrrecht: schneller Einstieg und Routing zu den passendes Fachmoduls bei unbekanntem Sachverhalt. Norm-/Quellenanker: SG, WBO, WDO, SVG. |
| `kriegsdienstverweigerung-verfahren` | Kriegsdienstverweigerung Verfahren im Bundeswehrrecht / Wehrrecht: prüft konkret Kriegsdienstverweigerung Verfahren, Rechtsbeistand im Disziplinarverfahren, Truppendienstgericht Zuständigkeit Verfahren. Liefert priorisierten Output mit N... |
| `livecheck-sg-mandantenbrief-soldat-mobbing` | Livecheck SG Mandantenbrief Soldat Mobbing im Bundeswehrrecht / Wehrrecht: prüft konkret Live-Check SG, WBO, WDO, WPflG. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `nebentaetigkeit-geschenkannahme-personalakte` | Nebentaetigkeit Geschenkannahme Personalakte im Bundeswehrrecht / Wehrrecht: prüft konkret Nebentätigkeit Geschenkannahme Compliance, Personalakte, Einsicht, Datenschutz. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und n... |
| `output-beschwerde-antrag-stellungnahme` | Output Beschwerde, Antrag, Stellungnahme: erstellt strukturierte Schriftstücke nach WBO, WDO und VwGO. Norm-/Quellenanker: WBO §§ 6–11, WDO, VwGO. |
| `pflicht-treuen-politische-betaetigung` | Pflicht Treuen Politische Betaetigung im Bundeswehrrecht / Wehrrecht: prüft konkret Pflicht zum treuen Dienen § 7 SG, Politische Betätigung Mäßigung Neutralität, Presseäußerung Meinungsfreiheit Soldat. Liefert priorisierten Output mit No... |
| `ptbs-einsatzfolge-reservistendienst` | Ptbs Einsatzfolge Reservistendienst im Bundeswehrrecht / Wehrrecht: prüft konkret PTBS Einsatzfolge Beweisführung, Reservistendienst und Dienstleistungspflicht, Sanitätsdienst und Heilfürsorge. Liefert priorisierten Output mit Norm-Pinpo... |
| `red-team-bundeswehr-beschwerde` | Red-Team Bundeswehr-Beschwerde: kritische Gegenprüfung einer Beschwerde auf Schwachstellen, Gegenargumente und Verbesserungen. Norm-/Quellenanker: WBO, WDO, VwGO. |
| `sexuelle-belaestigung-social-media` | Sexuelle Belaestigung Social Media im Bundeswehrrecht / Wehrrecht: prüft konkret Sexuelle Belästigung, Beschwerde, Schutzpflicht, Social Media und Dienstpflichten Soldat. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und n... |
| `soldatengesetz-rechtsstellung` | Soldatengesetz Rechtsstellung im Bundeswehrrecht / Wehrrecht: prüft konkret Soldatengesetz Rechtsstellung Grundpflichten, Soldatenversorgungsgesetz Beschädigtenversorgung, zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema S... |
| `statusrechte-einsatz-trennungsgeld` | Statusrechte Einsatz Trennungsgeld im Bundeswehrrecht / Wehrrecht: prüft konkret Statusrechte im Einsatz, Urlaub, Betreuung, Trennungsgeld. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `versetzung-kommandierung-vorlaeufige` | Versetzung Kommandierung Vorlaeufige im Bundeswehrrecht / Wehrrecht: prüft konkret Versetzung, Kommandierung, Abordnung, Vorläufige Dienstenthebung und Einbehaltung Bezüge. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und... |
| `wehrbeschwerdeordnung-beschwerde` | Wehrbeschwerdeordnung Beschwerde im Bundeswehrrecht / Wehrrecht: prüft konkret Wehrbeschwerdeordnung Beschwerde Frist Form, Schadensersatz, Regress, Dienstunfall. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem... |
| `wehrpflicht-wehrdienst-wehrpflichtgesetz` | Wehrpflicht Wehrdienst Wehrpflichtgesetz im Bundeswehrrecht / Wehrrecht: prüft konkret Wehrpflicht, Wehrdienst, Reservist Routing, Wehrpflichtgesetz Spannungs- und Verteidigungsfall. Liefert priorisierten Output mit Norm-Pinpoints, Risik... |
| `wehruebungen-heranziehungsbescheid-weitere` | Wehruebungen Heranziehungsbescheid Weitere im Bundeswehrrecht / Wehrrecht: prüft konkret Wehrübungen und Heranziehungsbescheid, Weitere Beschwerde und gerichtlicher Antrag TDG, Widerruf Ernennung arglistige Täuschung. Liefert priorisiert... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
