# Meinungsprüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`meinungspruefer`) | [`meinungspruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/meinungspruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Meinungsprüfer - Grenzfälle im Alltag** (`meinungspruefer-grenzfaelle-alltag`) | [Gesamt-PDF lesen](../testakten/meinungspruefer-grenzfaelle-alltag/gesamt-pdf/meinungspruefer-grenzfaelle-alltag_gesamt.pdf) | [`testakte-meinungspruefer-grenzfaelle-alltag.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-meinungspruefer-grenzfaelle-alltag.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Plugin für die Prüfung von Äußerungen nach einfachem Recht, Verfassungsrecht, Europarecht und Rechtsvergleich: Meinung oder Tatsachenbehauptung, Beleidigung, üble Nachrede, Verleumdung, Personen des politischen Lebens, Wahrnehmung berechtigter Interessen, zivilrechtliche Unterlassung, Widerruf, Geldentschädigung, Plattform- und Social-Media-Kontext, EGMR/EuGH/GRCh, OLG-/KG-Praxis und US-Supreme-Court-Vergleich.

**Keine Rechtsberatung.** Das Plugin erzeugt eine strukturierte Vorprüfung und dokumentierbare Arbeitsprodukte zur anwaltlichen Kontrolle. Rechtsprechung wird nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle verwendet.

## Start

```
/meinungspruefer:allgemein
```

Der Einstieg fragt schnell ab: exakter Wortlaut, Medium, Publikum, Anlass, Vorgeschichte, Betroffene, Tatsachenkern, Belege, Wiederholungsgefahr, gewünschter Output und Risikotoleranz. Danach routet er zu den passenden Spezialskills.

## Skills (36)

| Skill | Zweck |
|---|---|
| `allgemein` | Schöner Einstieg, Schnelltriage, Quellenhygiene und Routing |
| `schnelltriage-aeusserung` | Erste Ampel für Strafrecht, Zivilrecht, Plattform und arbeits-/schulbezogene Risiken |
| `zitat-und-kontextaufnahme` | Wortlaut, Kontext, Adressatenkreis, Medium und Vorgeschichte sauber erfassen |
| `meinung-tatsache-abgrenzung` | Meinung, Tatsache, gemischte Äußerung und Tatsachenkern trennen |
| `mehrdeutigkeit-sinnermittlung` | Sinnermittlung, Durchschnittspublikum und nicht ehrverletzende Deutungen |
| `beleglage-tatsachenbehauptung` | Belegmatrix für Tatsachen, Verdachtsäußerung und erwiesen unwahre Behauptung |
| `strafrecht-185-beleidigung` | § 185 StGB mit Art.-5-GG-Abwägung |
| `ueble-nachrede-186` | § 186 StGB, Nichterweislichkeit und Tatsachenkern |
| `verleumdung-187` | § 187 StGB, Wissen um Unwahrheit und Belegprüfung |
| `personen-politisches-leben-188` | § 188 StGB, Person des politischen Lebens, Öffentlichkeit und Erschwerung des Wirkens |
| `wahrnehmung-berechtigter-interessen-193` | § 193 StGB, Beschwerde, Bewertung, Mandats-/Arbeits-/Bürgerkontext |
| `strafantrag-194-und-verfahren` | Strafantrag, Antragsberechtigte, Fristen, Privatklage, Einstellungsoptionen |
| `schmaehkritik-formalbeleidigung-menschenwuerde` | Enge Ausnahmen ohne Normalabwägung |
| `abwaegung-art-5-gg` | Verfassungsrechtlicher Abwägungskern nach Art. 5 GG |
| `machtkritik-amtstraeger` | Amtsträger, Behörden, Bürgermeister, Schule, Justiz und Machtkritik |
| `arbeitgeber-betrieb-kantine` | Arbeitsplatz, Kantine, Kollegium, Betriebsrat, arbeitsrechtliche Nebenfolgen |
| `schule-elternchat` | Schule, Elternchat, Lehrkräfte, Schulleitung und pädagogischer Konflikt |
| `soziale-medien-x-linkedin` | X, LinkedIn, Kommentarspalten, Sichtbarkeit, Prangerwirkung, Screenshots |
| `kommunalrecht-buergermeister` | Kommunale Debatte, Bauprojekt, Ratssitzung, Amts- und Privatrolle |
| `satire-ironisierung-pinocchio` | Satire, Überzeichnung, Pinocchio-Vergleich, Lügenvorwurf als Wertung oder Tatsache |
| `schimpfwort-lackaffe-und-spott` | Spottbegriffe wie Lackaffe im Kontext prüfen |
| `zivilrecht-unterlassung-widerruf-schadensersatz` | APR, §§ 823, 1004 BGB analog, § 824 BGB und Beseitigungsansprüche |
| `presserecht-plattformen-loeschung-dsa` | Medien, Plattformmeldungen, Löschung, Sperrung und DSA-Schnittstellen |
| `europarecht-emrk-grch` | Art. 10 EMRK, Art. 11 GRCh, unions- und konventionsfreundliche Lesart |
| `egmr-art-10-rechtsprechung` | EGMR-Leitlinien zu öffentlicher Debatte, Werturteil, Tatsachengrundlage, Art.-8-/Art.-10-Abwägung, Hyperlinks und Drittkommentaren |
| `eugh-grch-art-11-rechtsprechung` | EuGH/GRCh bei Plattformen, Suchmaschinen, Datenschutz, Uploadfiltern, De-Referenzierung und journalistischen Zwecken |
| `olg-kg-praxis-rechtsprechung` | Obergerichtliche Praxis zu Unterlassung, Sinnermittlung, Social Media, Verdachtsäußerung, Plattformlabel und Tenorrisiko |
| `rechtsvergleich-usa-supreme-court` | US-Supreme-Court-Vergleich zu First Amendment, actual malice, public concern, opinion, parody, threats und incitement |
| `beweissicherung-screenshots` | Screenshots, Metadaten, Zeugen, URLs, Löschungen, Chatverläufe |
| `risikomatrix-ampel` | Ergebnis als Grün/Gelb/Rot mit Unsicherheiten und nächstem Schritt |
| `gegendarstellung-entschuldigung-deeskalation` | Reaktionsoptionen ohne unnötige Eskalation |
| `abmahnung-strafanzeige-reaktion` | Eingang von Abmahnung, Strafanzeige, Anhörung oder Plattformmeldung bearbeiten |
| `schriftsatz-stellungnahme-verteidigung` | Verteidigungs- und Erwiderungsbausteine |
| `output-memo-pruefvermerk` | Dokumentierter Prüfvermerk mit Zitat, Kontext, Normen und Ergebnis |
| `testakte-auswertung` | Die Testakte strukturiert auswerten |
| `rechtsprechungsbank-verifiziert` | Verifizierte Rechtsprechung mit Datum, Aktenzeichen und freier Quelle |

## Quellenstand

Stand: 05/2026. Kernnormen: Art. 5 GG, Art. 10 EMRK, Art. 11 GRCh, §§ 185-188, 192-194 StGB, §§ 823, 824, 1004 BGB analog, § 22 KUG bei Bildern und DSA-Schnittstellen bei Plattformen. Leitentscheidungen sind im Skill `rechtsprechungsbank-verifiziert` dokumentiert; der USA-Vergleich ist ausdrücklich nur Vergleich, kein Import amerikanischer Standards in die deutsche Prüfung.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 28 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `abwaegung-art-arbeitgeber-betrieb` | Nutze dies bei Abwaegung Art 5 Gg, Arbeitgeber Betrieb Kantine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `allgemein` | Einstieg, Schnelltriage und Fallrouting im Meinungsprüfer. Fragt Wortlaut, Kontext, Medium, Publikum, Tatsachenkern, Belege, betroffene Person, Anlass, Vorgeschichte, gewünschtes Ziel und Risiko ab; schlägt passende Fachmodule zu Beleidi... |
| `beleglage-tatsachenbehauptung-beweissicherung` | Nutze dies bei Beleglage Tatsachenbehauptung, Beweissicherung Screenshots: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `beleidigung-meinungspruefer` | Nutze dies bei Beleidigung Risikoampel Und Gegenargumente, Meinungspruefer Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `chronologie-fristen` | Nutze dies bei Chronologie Und Belegmatrix, Fristen Und Risikoampel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `egmr-art-eugh-grch` | Nutze dies bei Egmr Art 10 Rechtsprechung, Eugh Grch Art 11 Rechtsprechung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `europarecht-emrk-gegendarstellung` | Nutze dies bei Europarecht Emrk Grch, Gegendarstellung Entschuldigung Deeskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `kommunalrecht-buergermeister-machtkritik` | Nutze dies bei Kommunalrecht Buergermeister, Machtkritik Amtstraeger: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `mehrdeutigkeit-sinnermittlung-meinung` | Nutze dies bei Mehrdeutigkeit Sinnermittlung, Meinung Tatsache Abgrenzung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `meinung-strafantrag-verfahren` | Nutze dies bei Meinung Fristen Form Und Zustaendigkeit, Strafantrag 194 Und Verfahren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `nachrede-tatsache` | Nutze dies bei Nachrede Schriftsatz Brief Und Memo Bausteine, Tatsache Dokumentenmatrix Und Lueckenliste: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `olg-kg-rechtsprechungsbank-verifiziert` | Nutze dies bei Olg Kg Praxis Rechtsprechung, Rechtsprechungsbank Verifiziert: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `output-memo-pruefvermerk` | Erzeugt den finalen Prüfvermerk zum Meinungsfall mit Sachverhalt, Wortlaut, Kontext, Normen, Rechtsprechung, Subsumtion, Risikoampel, Belegliste, Alternativformulierungen und Handlungsempfehlung. |
| `personen-politisches-presserecht-plattformen` | Nutze dies bei Personen Politisches Leben 188, Presserecht Plattformen Löschung Dsa: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `rechtsvergleich-usa-risikomatrix-ampel` | Nutze dies bei Rechtsvergleich Usa Supreme Court, Risikomatrix Ampel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `satire-ironisierung-schimpfwort-lackaffe` | Nutze dies bei Satire Ironisierung Pinocchio, Schimpfwort Lackaffe Und Spott: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `schmaehkritik-formalbeleidigung-schnelltriage` | Nutze dies bei Schmaehkritik Formalbeleidigung Menschenwuerde, Schnelltriage Aeusserung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `soziale-medien-aeusserungsrecht` | Nutze dies bei Soziale Medien X Linkedin, Aeusserungsrecht Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `stellungnahme-verteidigung-schule-elternchat` | Nutze dies bei Schriftsatz Stellungnahme Verteidigung, Schule Elternchat: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `stgb-quellenkarte` | Nutze dies zur Quellenprüfung bei Stgb Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `strafrecht-beleidigung-testakte-auswertung` | Nutze dies bei Strafrecht 185 Beleidigung, Testakte Auswertung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ueble-nachrede-verleumdung` | Nutze dies bei Ueble Nachrede 186, Verleumdung 187: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ueble-verleumdung` | Nutze dies bei Ueble Behörden Gericht Und Registerweg, Verleumdung Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `wahrnehmung-berechtigter-zitat` | Nutze dies bei Wahrnehmung Berechtigter Interessen 193, Zitat Und Kontextaufnahme: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `zivilrecht-unterlassung-abmahnung` | Nutze dies bei Zivilrecht Unterlassung Widerruf Schadensersatz, Abmahnung Strafanzeige Reaktion: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
