# Versammlungsrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`versammlungsrecht`) | [`versammlungsrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/versammlungsrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Verfassungsbeschwerde Klimacamp Initiative Saarbruecken — Art. 8 GG / Versammlungsfreiheit / Bannmeile Landtag** (`verfassungsbeschwerde-versammlungsfreiheit-klimacamp-saarbruecken-art-8-gg-tannenberg`) | [Gesamt-PDF lesen](../testakten/verfassungsbeschwerde-versammlungsfreiheit-klimacamp-saarbruecken-art-8-gg-tannenberg/gesamt-pdf/verfassungsbeschwerde-versammlungsfreiheit-klimacamp-saarbruecken-art-8-gg-tannenberg_gesamt.pdf) | [`testakte-verfassungsbeschwerde-versammlungsfreiheit-klimacamp-saarbruecken-art-8-gg-tannenberg.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verfassungsbeschwerde-versammlungsfreiheit-klimacamp-saarbruecken-art-8-gg-tannenberg.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Praxisplugin für Menschen, Organisationen und anwaltliche Teams, die eine Versammlung unter freiem Himmel, einen Aufzug, eine Mahnwache, ein Camp oder eine konfliktträchtige Kundgebung rechtlich sauber anzeigen, durchführen oder gegen Behördeneingriffe verteidigen wollen.

Das Plugin denkt Versammlungsrecht nicht als Bittgang zur Behörde. Es startet bei Art. 8 GG: friedlich, ohne Waffen, grundsätzlich ohne Erlaubnis. Zugleich nimmt es ernst, dass Versammlungen im öffentlichen Raum geplant werden müssen: richtige Behörde, richtige Frist, klare Leitung, Ordner, Route, Technik, Rettungswege, Kooperationsgespräch, Auflagenprüfung und Eilrechtsschutz, wenn die Behörde ausweicht oder überzieht.

## Kaltstart

1. **Wo?** Bundesland, Stadt, Route, Platz, Bannmeile, mehrere Behördenbezirke?
2. **Was?** Außenversammlung, Aufzug, Innenversammlung, private Runde, Mahnwache, Infostand, Camp, Gegenversammlung?
3. **Wann?** Termin, Bekanntgabezeitpunkt, Einladung, Social-Media-Post, Eil- oder Spontanversammlung?
4. **Wer?** Veranstalter, Leitung, Stellvertretung, Ordner, Organisation, Kontaktkanal?
5. **Wofür?** Anzeige erstellen, Behördenfragen beantworten, Auflagen prüfen, Verbot abwehren, Eilrechtsschutz, Tag-der-Versammlung-Plan?

## Leitgedanke

- **Anzeige statt Genehmigung:** Öffentliche Versammlungen unter freiem Himmel werden angezeigt; die Behörde soll planen und schützen, nicht politisch vorsortieren.
- **Landesrecht zuerst:** Viele Länder haben eigene Versammlungsgesetze. Das Plugin fragt deshalb immer nach Ort und Bundesland.
- **Kooperation ohne Selbstzensur:** Behördenbelange werden ernst genommen, aber Ort, Zeit, Thema und Ausdrucksform bleiben Teil der grundrechtlich geschützten Versammlung.
- **Konkrete Gefahr statt Behördenbauchgefühl:** Auflagen und Verbote müssen tatsachenbasiert und verhältnismäßig sein.
- **Schnelle Outputs:** Anzeige, Ordnerliste, Kooperationsagenda, Behördenbrief, Eilantrag, Notfallkarte und Nachbereitungsvermerk.

## Typische Outputs

| Situation | Passende Skills | Ergebnis |
| --- | --- | --- |
| Versammlung normal planen | `allgemein`, `landesrecht-und-behoerde-finden`, `anzeige-unter-freiem-himmel`, `muster-anzeige-generator` | Anzeige, Fristplan, Behördenkontakt |
| Einladung soll heute raus | `frist-48-stunden-bekanntgabe`, `bekanntgabe-social-media`, `qualitaetsgate-vor-bekanntgabe` | Kommunikationskalender und Go/No-Go |
| Spontane oder eilige Demo | `spontanversammlung`, `eilversammlung`, `behoerdenkommunikation` | Kurzmeldung, Aktenvermerk, Polizeisprechzettel |
| Behörde will verlegen oder verbieten | `auflagen-pruefen`, `falscher-tag-falscher-ort-einwand`, `verbot-und-beschraenkung-abwehren`, `muster-eilantrag` | Gegenbrief und Eilrechtsschutz-Gerüst |
| Ordner und Tag selbst | `ordner-auswahl`, `ordnerliste-und-mitteilung`, `polizei-vor-ort-deeskalation`, `notfallkarte-versammlungstag` | Briefing, Liste, Notfallkarte |
| Camp, Technik, Verkehr | `camp-dauerversammlung`, `technik-lautsprecher-musik`, `verkehr-rettungswege-oepnv` | Konzept und mildere Mittel |

## Quellenstrategie

- **Bundesrecht:** Art. 8 GG, Versammlungsgesetz, VwGO.
- **Landesrecht:** jeweiliges Landesversammlungsgesetz und Zuständigkeitsregel.
- **Behördenpraxis:** offizielle Onlineformulare und Hinweise der konkreten Versammlungsbehörde.
- **Rechtsprechung:** nur mit Gericht, Datum, Aktenzeichen und frei überprüfbarem Link.
- **Keine Blindzitate:** keine BeckRS-, juris-, Kommentar- oder Aufsatzfundstellen aus Modellwissen.

## Berufs- und Datenschutzhinweis

Bei echten Mandaten keine sensiblen personenbezogenen Daten, politischen Mitgliedschaften, Teilnehmerlisten oder Behördenakten in ungeprüfte Systeme laden. Ordnerlisten, Minderjährigendaten, Gesundheitsdaten und Polizeikommunikation sind datensensibel. Für produktiven Kanzleieinsatz ist das jeweils eigene Datenschutz-, Berufsrechts- und Hosting-Setup maßgeblich.

## Lizenz

Apache-2.0 OR MIT. Siehe Repository-Stammverzeichnis.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 29 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Allgemeiner Kaltstart im Versammlungsrecht: Land und Ort, Art der Versammlung, Frist, Behörde, Risiko und Ziel klären, dann passende Fachmodule und nächsten Output auswählen. |
| `anwaltlicher-an-anzeige-unter` | Nutze dies bei Anwaltlicher Brief An Behörde, Anzeige Unter Freiem Himmel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `auflagen-auflagenverstoss-owi` | Nutze dies bei Auflagen Prüfen, Auflagenverstoss Und Owi: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `bannmeile-schutzbereiche-barrierefreiheit` | Nutze dies bei Bannmeile Schutzbereiche, Barrierefreiheit Und Inklusion: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `behoerdenkommunikation-bekanntgabe-social` | Nutze dies bei Behoerdenkommunikation, Bekanntgabe Social Media: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `bescheid-lesen-beweissicherung-am` | Nutze dies bei Bescheid Lesen, Beweissicherung Am Versammlungstag: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `blockade-sitzblockade-bundeslaender-synopse` | Nutze dies bei Blockade Sitzblockade Friedlichkeit, Bundeslaender Synopse: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `camp-dauerversammlung-datenschutz-fotos` | Nutze dies bei Camp Dauerversammlung, Datenschutz Fotos Livestream: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `dritte-anwohner-eilversammlung` | Nutze dies bei Dritte Anwohner Laerm Geschaeft, Eilversammlung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `eingangsbestaetigung-aktenzeichen-falscher` | Nutze dies bei Eingangsbestaetigung Und Aktenzeichen, Falscher Tag Falscher Ort Einwand: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `frist-stunden-kosten-haftung` | Nutze dies bei Frist 48 Stunden Bekanntgabe, Kosten Haftung Und Versicherung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `gefahrenprognose-redteam` | Zerlegt die behördliche Gefahrenprognose und baut eine eigene, realistische Sicherheitslage auf. |
| `gegenveranstaltung-trennung-infostand` | Nutze dies bei Gegenveranstaltung Und Trennung, Infostand Mahnwache Kleinstversammlung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `innenraum-versammlung-kooperationsgespraech` | Nutze dies bei Innenraum Versammlung Abgrenzen, Kooperationsgespraech: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `kundgebung-stationaer-landesrecht-behoerde` | Nutze dies bei Kundgebung Stationaer Platzwahl, Landesrecht Und Behörde Finden: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `leiter-verantwortung-mildere-mittel` | Nutze dies bei Leiter Verantwortung, Mildere Mittel Matrix: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `muster-anzeige-muster-eilantrag` | Nutze dies bei Muster Anzeige Generator, Muster Eilantrag: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `nachbereitung-aktenvermerk-notfallkarte` | Nutze dies bei Nachbereitung Und Aktenvermerk, Notfallkarte Versammlungstag: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `offizielle-quellen-ordner-auswahl` | Nutze dies bei Offizielle Quellen Livecheck, Ordner Auswahl: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ordnerliste-mitteilung-partei-gewerkschaft` | Nutze dies bei Ordnerliste Und Mitteilung, Partei Gewerkschaft Verein Veranstalter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `polizei-ort-polizeifilmerei-beweissicherung` | Nutze dies bei Polizei Vor Ort Deeskalation, Polizeifilmerei Beweissicherung Kug 201 Stgb: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `presse-oeffentlichkeitsarbeit-privat` | Nutze dies bei Presse Und Oeffentlichkeitsarbeit, Privat Öffentlich Abgrenzen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `qualitaetsgate-bekanntgabe-route-aufzug` | Nutze dies bei Qualitaetsgate Vor Bekanntgabe, Route Aufzug Und Streckenplanung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `schule-universitaet-schutz-vorauseilendem` | Nutze dies bei Schule Universitaet Jugendliche, Schutz Vor Vorauseilendem Gehorsam: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `spontanversammlung-strafrecht-versg` | Nutze dies bei Spontanversammlung, Strafrecht Versg Risiken: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `technik-lautsprecher-untatigkeit-schweigen` | Nutze dies bei Technik Lautsprecher Musik, Untatigkeit Und Schweigen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `verbot-beschraenkung-verkehr-rettungswege` | Nutze dies bei Verbot Und Beschraenkung Abwehren, Verkehr Rettungswege Oepnv: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `versammlungskonzept-wahlkampf-politische` | Nutze dies bei Versammlungskonzept, Wahlkampf Und Politische Kundgebung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `widerspruch-klage` | Nutze dies bei Widerspruch Klage Eilrechtsschutz: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
