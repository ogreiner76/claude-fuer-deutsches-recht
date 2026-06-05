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
| `allgemein` | Allgemeiner Kaltstart im Versammlungsrecht: Land und Ort, Art der Versammlung, Frist, Behörde, Risiko und Ziel klären, dann passende Spezialskills und nächsten Output auswählen. |
| `anwaltlicher-an-anzeige-unter` | Nutze dies, wenn Anwaltlicher Brief An Behörde, Anzeige Unter Freiem Himmel im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Anwaltlicher Brief An Behörde, Anzeige Unter Freiem Himmel prüfen.; Erstelle eine Arb... |
| `auflagen-auflagenverstoss-owi` | Nutze dies, wenn Auflagen Prüfen, Auflagenverstoss Und Owi im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Auflagen Prüfen, Auflagenverstoss Und Owi prüfen.; Erstelle eine Arbeitsfassung zu Auflagen Prüfen, Au... |
| `bannmeile-schutzbereiche-barrierefreiheit` | Nutze dies, wenn Bannmeile Schutzbereiche, Barrierefreiheit Und Inklusion im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Bannmeile Schutzbereiche, Barrierefreiheit Und Inklusion prüfen.; Erstelle eine Arbeits... |
| `behoerdenkommunikation-bekanntgabe-social` | Nutze dies, wenn Behoerdenkommunikation, Bekanntgabe Social Media im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Behoerdenkommunikation, Bekanntgabe Social Media prüfen.; Erstelle eine Arbeitsfassung zu Behoe... |
| `bescheid-lesen-beweissicherung-am` | Nutze dies, wenn Bescheid Lesen, Beweissicherung Am Versammlungstag im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Bescheid Lesen, Beweissicherung Am Versammlungstag prüfen.; Erstelle eine Arbeitsfassung zu B... |
| `blockade-sitzblockade-bundeslaender-synopse` | Nutze dies, wenn Blockade Sitzblockade Friedlichkeit, Bundeslaender Synopse im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Blockade Sitzblockade Friedlichkeit, Bundeslaender Synopse prüfen.; Erstelle eine Arb... |
| `camp-dauerversammlung-datenschutz-fotos` | Nutze dies, wenn Camp Dauerversammlung, Datenschutz Fotos Livestream im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Camp Dauerversammlung, Datenschutz Fotos Livestream prüfen.; Erstelle eine Arbeitsfassung zu... |
| `dritte-anwohner-eilversammlung` | Nutze dies, wenn Dritte Anwohner Laerm Geschaeft, Eilversammlung im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Dritte Anwohner Laerm Geschaeft, Eilversammlung prüfen.; Erstelle eine Arbeitsfassung zu Dritte... |
| `eingangsbestaetigung-aktenzeichen-falscher` | Nutze dies, wenn Eingangsbestaetigung Und Aktenzeichen, Falscher Tag Falscher Ort Einwand im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Eingangsbestaetigung Und Aktenzeichen, Falscher Tag Falscher Ort Einwan... |
| `frist-stunden-kosten-haftung` | Nutze dies, wenn Frist 48 Stunden Bekanntgabe, Kosten Haftung Und Versicherung im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Frist 48 Stunden Bekanntgabe, Kosten Haftung Und Versicherung prüfen.; Erstelle ei... |
| `gefahrenprognose-redteam` | Zerlegt die behördliche Gefahrenprognose und baut eine eigene, realistische Sicherheitslage auf. |
| `gegenveranstaltung-trennung-infostand` | Nutze dies, wenn Gegenveranstaltung Und Trennung, Infostand Mahnwache Kleinstversammlung im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Gegenveranstaltung Und Trennung, Infostand Mahnwache Kleinstversammlung... |
| `innenraum-versammlung-kooperationsgespraech` | Nutze dies, wenn Innenraum Versammlung Abgrenzen, Kooperationsgespraech im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Innenraum Versammlung Abgrenzen, Kooperationsgespraech prüfen.; Erstelle eine Arbeitsfass... |
| `kundgebung-stationaer-landesrecht-behoerde` | Nutze dies, wenn Kundgebung Stationaer Platzwahl, Landesrecht Und Behörde Finden im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Kundgebung Stationaer Platzwahl, Landesrecht Und Behörde Finden prüfen.; Erstell... |
| `leiter-verantwortung-mildere-mittel` | Nutze dies, wenn Leiter Verantwortung, Mildere Mittel Matrix im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Leiter Verantwortung, Mildere Mittel Matrix prüfen.; Erstelle eine Arbeitsfassung zu Leiter Verantwo... |
| `muster-anzeige-muster-eilantrag` | Nutze dies, wenn Muster Anzeige Generator, Muster Eilantrag im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Muster Anzeige Generator, Muster Eilantrag prüfen.; Erstelle eine Arbeitsfassung zu Muster Anzeige Ge... |
| `nachbereitung-aktenvermerk-notfallkarte` | Nutze dies, wenn Nachbereitung Und Aktenvermerk, Notfallkarte Versammlungstag im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Nachbereitung Und Aktenvermerk, Notfallkarte Versammlungstag prüfen.; Erstelle eine... |
| `offizielle-quellen-ordner-auswahl` | Nutze dies, wenn Offizielle Quellen Livecheck, Ordner Auswahl im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `ordnerliste-mitteilung-partei-gewerkschaft` | Nutze dies, wenn Ordnerliste Und Mitteilung, Partei Gewerkschaft Verein Veranstalter im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Ordnerliste Und Mitteilung, Partei Gewerkschaft Verein Veranstalter prüfen.;... |
| `polizei-ort-polizeifilmerei-beweissicherung` | Nutze dies, wenn Polizei Vor Ort Deeskalation, Polizeifilmerei Beweissicherung Kug 201 Stgb im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Polizei Vor Ort Deeskalation, Polizeifilmerei Beweissicherung Kug 201... |
| `presse-oeffentlichkeitsarbeit-privat` | Nutze dies, wenn Presse Und Oeffentlichkeitsarbeit, Privat Öffentlich Abgrenzen im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Presse Und Oeffentlichkeitsarbeit, Privat Öffentlich Abgrenzen prüfen.; Erstelle... |
| `qualitaetsgate-bekanntgabe-route-aufzug` | Nutze dies, wenn Qualitaetsgate Vor Bekanntgabe, Route Aufzug Und Streckenplanung im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast über... |
| `schule-universitaet-schutz-vorauseilendem` | Nutze dies, wenn Schule Universitaet Jugendliche, Schutz Vor Vorauseilendem Gehorsam im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Schule Universitaet Jugendliche, Schutz Vor Vorauseilendem Gehorsam prüfen.;... |
| `spontanversammlung-strafrecht-versg` | Nutze dies, wenn Spontanversammlung, Strafrecht Versg Risiken im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Spontanversammlung, Strafrecht Versg Risiken prüfen.; Erstelle eine Arbeitsfassung zu Spontanversam... |
| `technik-lautsprecher-untatigkeit-schweigen` | Nutze dies, wenn Technik Lautsprecher Musik, Untatigkeit Und Schweigen im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Technik Lautsprecher Musik, Untatigkeit Und Schweigen prüfen.; Erstelle eine Arbeitsfassun... |
| `verbot-beschraenkung-verkehr-rettungswege` | Nutze dies, wenn Verbot Und Beschraenkung Abwehren, Verkehr Rettungswege Oepnv im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Verbot Und Beschraenkung Abwehren, Verkehr Rettungswege Oepnv prüfen.; Erstelle ei... |
| `versammlungskonzept-wahlkampf-politische` | Nutze dies, wenn Versammlungskonzept, Wahlkampf Und Politische Kundgebung im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Versammlungskonzept, Wahlkampf Und Politische Kundgebung prüfen.; Erstelle eine Arbeits... |
| `widerspruch-klage` | Nutze dies, wenn Widerspruch Klage Eilrechtsschutz im Plugin Versammlungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Widerspruch Klage Eilrechtsschutz prüfen.; Erstelle eine Arbeitsfassung zu Widerspruch Klage Eilrechtsschutz.;... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
