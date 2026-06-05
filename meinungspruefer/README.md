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
| `meinungspruefer-allgemein` | Schöner Einstieg, Schnelltriage, Quellenhygiene und Routing |
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
| `abwaegung-art-arbeitgeber-betrieb` | Abwaegung ART Arbeitgeber Betrieb im Plugin Meinungspruefer: prüft konkret Erstellt die verfassungsrechtliche Normalabwägung zwischen, Prüft Äußerungen im Betrieb, in der Kantine, im Kollegenkreis. Liefert priorisierten Output mit Norm-P... |
| `beleglage-tatsachenbehauptung-beweissicherung` | Beleglage Tatsachenbehauptung Beweissicherung im Plugin Meinungspruefer: prüft konkret Erstellt eine Belegmatrix für Tatsachenbehauptungen, Verdachtsäußerungen und gem, Erstellt einen Beweissicherungsplan für Screenshots, URLs. Liefert p... |
| `beleidigung-meinungspruefer` | Beleidigung Meinungspruefer im Plugin Meinungspruefer: prüft konkret Beleidigung, Meinungspruefer. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `egmr-art-eugh-grch` | Egmr ART Eugh Grch im Plugin Meinungspruefer: prüft konkret Prüft Äußerungsfälle mit der EGMR-Linie zu Art 10 EMRK, Prüft EuGH- und Art 11 GRCh-Bezüge bei Äußerungen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächs... |
| `europarecht-emrk-gegendarstellung` | Europarecht Emrk Gegendarstellung im Plugin Meinungspruefer: prüft konkret Ordnet Art 10 EMRK und Art 11 GRCh in die Äußerungsprüfung, Entwickelt Reaktionsoptionen bei eskalierten Äußerungen. Liefert priorisierten Output mit Norm-Pinpoin... |
| `kommunalrecht-buergermeister-machtkritik` | Kommunalrecht Buergermeister Machtkritik im Plugin Meinungspruefer: prüft konkret Prüft kommunale Meinungsfälle um Bürgermeister, Rat, Verwaltung und Bauprojekte, Prüft Kritik an Amtsträgern. Liefert priorisierten Output mit Norm-Pinpoin... |
| `mehrdeutigkeit-sinnermittlung-meinung` | Mehrdeutigkeit Sinnermittlung Meinung im Plugin Meinungspruefer: prüft konkret Ermittelt den objektiven Sinn einer mehrdeutigen Äußerung, Kontext, Prüft, ob eine Äußerung Meinung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoam... |
| `meinung-strafantrag-verfahren` | Meinung Strafantrag Verfahren im Plugin Meinungspruefer: prüft konkret Meinung, Prüft Strafantrag, Fristen, Antragsberechtigung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `meinungspruefer-chronologie-fristen` | Chronologie Fristen im Plugin Meinungspruefer: prüft konkret Chronologie und Belegmatrix im Plugin meinungspruefer, Fristen- und Risikoampel im Plugin meinungspruefer. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näch... |
| `meinungspruefer-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `meinungspruefer-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `meinungspruefer-kaltstart-triage` | Einstieg, Schnelltriage und Fallrouting im Meinungsprüfer. Fragt Wortlaut, Kontext, Medium, Publikum, Tatsachenkern, Belege, betroffene Person, Anlass, Vorgeschichte, gewünschtes Ziel und Risiko ab; schlägt passende Fachmodule zu Beleidi... |
| `meinungspruefer-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `nachrede-tatsache` | Nachrede Tatsache im Plugin Meinungspruefer: prüft konkret Nachrede, Tatsache. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `olg-kg-rechtsprechungsbank-verifiziert` | OLG KG Rechtsprechungsbank Verifiziert im Plugin Meinungspruefer: prüft konkret Nutzt obergerichtliche Praxis zu Äußerungen, Enthält eine verifizierte Rechtsprechungsbank zur. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel... |
| `output-memo-pruefvermerk` | Erzeugt den finalen Prüfvermerk zum Meinungsfall mit Sachverhalt, Wortlaut, Kontext, Normen, Rechtsprechung, Subsumtion, Risikoampel, Belegliste, Alternativformulierungen und Handlungsempfehlung. |
| `personen-politisches-presserecht-plattformen` | Personen Politisches Presserecht Plattformen im Plugin Meinungspruefer: prüft konkret Prüft § 188 StGB bei Äußerungen gegen Personen des, Prüft Medien- und Plattformfälle mit Löschung, Sperrung, Meldung. Liefert priorisierten Output mit... |
| `rechtsvergleich-usa-risikomatrix-ampel` | Rechtsvergleich USA Risikomatrix Ampel im Plugin Meinungspruefer: prüft konkret Vergleicht deutsche Meinungsfreiheit mit der, Erzeugt eine verständliche Risikoampel für Äußerungen mit, Zivilrecht. Liefert priorisierten Output mit Norm-Pi... |
| `satire-ironisierung-schimpfwort-lackaffe` | Satire Ironisierung Schimpfwort Lackaffe im Plugin Meinungspruefer: prüft konkret Prüft satirische, ironische und bildhafte Äußerungen wie Pinocchio-Vergleiche, Prüft Spott- und Schimpfwörter wie Lackaffe im Kontext, Amts. Liefert priori... |
| `schmaehkritik-formalbeleidigung-schnelltriage` | Schmaehkritik Formalbeleidigung Schnelltriage im Plugin Meinungspruefer: prüft konkret Prüft die engen Ausnahmefälle Schmähkritik, Formalbeleidigung und Menschenwürdea, Schnelle Erstbewertung einer Äußerung mit Ampel für, Zivilrecht. Lie... |
| `soziale-medien-aeusserungsrecht` | Soziale Medien Aeusserungsrecht im Plugin Meinungspruefer: prüft konkret Prüft Äußerungen auf X, LinkedIn, Bewertungsportalen und Kommentarspalten, Aeusserungsrecht. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächst... |
| `stellungnahme-verteidigung-schule-elternchat` | Stellungnahme Verteidigung Schule Elternchat im Plugin Meinungspruefer: prüft konkret Erstellt strukturierte Stellungnahmen und, Prüft Äußerungen über Lehrkräfte, Schulleitung und Eltern in Elternchat, Schulma. Liefert priorisierten Outp... |
| `stgb-quellenkarte` | Stgb Quellenkarte: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `strafrecht-beleidigung-testakte-auswertung` | Strafrecht Beleidigung Testakte Auswertung im Plugin Meinungspruefer: prüft konkret Prüft § 185 StGB bei ehrverletzenden Werturteilen und, Wertet die Testakte meinungspruefer-grenzfaelle-alltag aus, LinkedIn. Liefert priorisierten Output... |
| `ueble-nachrede-verleumdung` | Ueble Nachrede Verleumdung im Plugin Meinungspruefer: prüft konkret Prüft § 186 StGB bei ehrenrührigen Tatsachenbehauptungen, die nicht erweislich w, Prüft § 187 StGB bei bewusst unwahren ehrverletzenden. Liefert priorisierten Output mit... |
| `ueble-verleumdung` | Ueble Verleumdung im Plugin Meinungspruefer: prüft konkret Ueble, Verleumdung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `wahrnehmung-berechtigter-zitat` | Wahrnehmung Berechtigter Zitat im Plugin Meinungspruefer: prüft konkret Prüft § 193 StGB bei Beschwerde, Bewertung, Anzeige, arbeitsbezogener Kritik. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `zivilrecht-unterlassung-abmahnung` | Zivilrecht Unterlassung Abmahnung im Plugin Meinungspruefer: prüft konkret Prüft zivilrechtliche Ansprüche bei Äußerungen, Hilft bei Reaktion auf Abmahnung, Strafanzeige, polizeiliche Anhörung. Liefert priorisierten Output mit Norm-Pinpo... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
