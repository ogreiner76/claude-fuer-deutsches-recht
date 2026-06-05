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
| `akteneinsicht-wbo-arbeitsrecht-zivile` | Akteneinsicht Wbo Wdo, Arbeitsrecht Zivile Bundeswehrbeschaeftigte, Ausbildung Studium Bundeswehr Rueckforderung Ausbildungskosten: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den näc... |
| `auslandseinsatz-einsatzregeln-beamtenrecht` | Auslandseinsatz Mandat Einsatzregeln, Beamtenrecht Bundeswehrverwaltung Abgrenzung, Befehl Verweigern Gewissensnot Rechtswidrigkeit: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nä... |
| `beschwerde-besoldung-zulagen-beurteilung` | Beschwerde Gegen Beurteilung Und Laufbahnentscheidung, Besoldung Zulagen Auslandsverwendungszuschlag, Beurteilung Konkurrentenstreit Auswahlentscheidung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundla... |
| `beschwerde-sofortcheck-bwbes` | Beschwerde Fristen Sofortcheck, Bwbes Besoldungswiderspruch Soldat Und Fristen, Disziplinarverfahren Intake: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `bundesverwaltungsgericht-wehrdienstsenate` | Bundesverwaltungsgericht Wehrdienstsenate, Bwbes Soldatenbesoldung Grundgehalt Und Dienstgrad, Bwbes Wehrsold Freiwilliger Wehrdienst Und Unterhaltssic: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlag... |
| `bundeswehrrecht-wehrrecht-kaltstart-triage` | Einstieg, Schnelltriage und Fallrouting im Bundeswehrrecht und Wehrrecht-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, erkennt stumme Uploads und schlägt passende Fachmodule aus diesem Plugin vor. |
| `bwbes-auslandsverwendungszuschlag` | Bwbes Auslandsverwendungszuschlag Und Einsatzversorgung, Bwbes Trennungsgeld Umzugskosten Reisebeihilfe, Bwbes Erschwerniszulagen Militaerischer Dienst: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlag... |
| `bwbes-besoldung-reservist-kdv` | Bwbes Besoldung Reservist Wehruebung Und Arbeitgeberausg, Bwbes Kdv Und Besoldungsfolgen Bei Statuswechsel, Bwbes Disziplinarbusse Kuerzung Und Besoldung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundl... |
| `bwbes-dienstzeitversorgung` | Bwbes Dienstzeitversorgung Berufsfoerderungsdienst, Bwbes Soldatenversorgung Dienstunfall Wehrdienstbeschaed, Bwbes Heilfuersorge Truppenaerztliche Versorgung Und Pkv: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und... |
| `bwbes-verwendungsfaehigkeit-tauglichkeit` | Bwbes Verwendungsfaehigkeit Tauglichkeit Und Finanzielle, Bwbes Auslandseinsatz Anerkennung Und Nachweise, Bwbes Ruhensregelungen Versorgung Und Erwerbseinkommen: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rech... |
| `dienstunfaehigkeit-entlassung-dienstzeit` | Dienstunfaehigkeit Entlassung Zurruhesetzung, Dienstzeit Soldat Auf Zeit Berufssoldat Fwdl, Einsatz Unfall Versorgung Dokumentenplan: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den n... |
| `eilverfahren-konkurrentenstreit` | Eilverfahren Konkurrentenstreit Wehrdienstsenat, Fristenkalender Bundeswehrrecht, Gerichtliches Disziplinarverfahren Soldat: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten b... |
| `einsatzunfall-wehrdienstbeschaedigung` | Einsatzunfall Wehrdienstbeschaedigung, Entlassung Auf Eigenen Antrag, Ernennung Dienstgrad Laufbahnrecht: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `extremismus-verdachtsfall-geheimschutz` | Extremismus Verdachtsfall Sicherheitsrecht, Geheimschutz Sicherheitsueberpruefung Sueg, Gehorsam Befehl Und Rechtswidriger Befehl: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den näch... |
| `gleichstellung-diskriminierung-impfpflicht` | Gleichstellung Diskriminierung Soldatinnen Soldaten, Impfpflicht Tauglichkeit Musterung, Kameradschaft Achtungs Und Vertrauenspflicht: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den... |
| `kaltstart-bundeswehrrecht` | Kaltstart Bundeswehrrecht: schneller Einstieg und Routing zu den passendes Fachmoduls bei unbekanntem Sachverhalt. Norm-/Quellenanker: SG, WBO, WDO, SVG. |
| `kriegsdienstverweigerung-verfahren` | Kriegsdienstverweigerung Verfahren, Rechtsbeistand Im Disziplinarverfahren, Truppendienstgericht Zustaendigkeit Verfahren: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten bel... |
| `livecheck-sg-mandantenbrief-soldat-mobbing` | Livecheck Sg Wbo Wdo Wpflg Svg, Mandantenbrief Soldat Verstaendlich, Mobbing Fuersorgepflicht Bundeswehr: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `nebentaetigkeit-geschenkannahme-personalakte` | Nebentaetigkeit Geschenkannahme Compliance, Personalakte Einsicht Datenschutz, Personalvertretung Zivile Beschaeftigte Schnittstelle: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den n... |
| `output-beschwerde-antrag-stellungnahme` | Output Beschwerde, Antrag, Stellungnahme: erstellt strukturierte Schriftstücke nach WBO, WDO und VwGO. Norm-/Quellenanker: WBO §§ 6–11, WDO, VwGO. |
| `pflicht-treuen-politische-betaetigung` | Pflicht Zum Treuen Dienen 7 Sg, Politische Betaetigung Maessigung Neutralitaet, Presseaeusserung Meinungsfreiheit Soldat: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten bela... |
| `ptbs-einsatzfolge-reservistendienst` | Ptbs Einsatzfolge Beweisfuehrung, Reservistendienst Dienstleistungspflicht, Sanitaetsdienst Heilfuersorge: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `red-team-bundeswehr-beschwerde` | Red-Team Bundeswehr-Beschwerde: kritische Gegenprüfung einer Beschwerde auf Schwachstellen, Gegenargumente und Verbesserungen. Norm-/Quellenanker: WBO, WDO, VwGO. |
| `sexuelle-belaestigung-social-media` | Sexuelle Belaestigung Beschwerde Schutzpflicht, Social Media Soldat Dienstpflichten, Soldatenbeteiligung Vertrauensperson Sbg: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten... |
| `soldatengesetz-rechtsstellung` | Soldatengesetz Rechtsstellung Grundpflichten, Soldatenversorgungsgesetz Beschaedigtenversorgung, Status Soldat Beamter Zivilbeschaeftigter Klaeren: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und... |
| `statusrechte-einsatz-trennungsgeld` | Statusrechte Im Einsatz Urlaub Betreuung, Trennungsgeld Umzugskosten Reisekosten, Unterhaltssicherung Reservisten: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren... |
| `versetzung-kommandierung-vorlaeufige` | Versetzung Kommandierung Abordnung, Vorlaeufige Dienstenthebung Einbehaltung Bezuege, Wehrdisziplinarordnung Einfache Disziplinarmassnahme: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert... |
| `wehrbeschwerdeordnung-beschwerde` | Wehrbeschwerdeordnung Beschwerde Frist Form, Schadenersatz Regress Dienstunfall Material, Aerztliche Begutachtung Dienstfaehigkeit: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den näc... |
| `wehrpflicht-wehrdienst-wehrpflichtgesetz` | Wehrpflicht Wehrdienst Reservist Routing, Wehrpflichtgesetz Spannungs Und Verteidigungsfall, Wehrstrafrecht Fahnenflucht Gehorsamsverweigerung Schnittstelle: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgru... |
| `wehruebungen-heranziehungsbescheid-weitere` | Wehruebungen Heranziehungsbescheid, Weitere Beschwerde Und Gerichtlicher Antrag Wehrdienstgericht, Widerruf Ernennung Arglistige Taeuschung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefer... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
