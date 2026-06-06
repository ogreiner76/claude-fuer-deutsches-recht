# Strafanzeige-Vorbereiter

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`strafanzeige-vorbereiter`) | [`strafanzeige-vorbereiter.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/strafanzeige-vorbereiter.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist ausdrücklich keine Strafanzeigenkanone. Es soll Gerichte und Staatsanwaltschaften nicht mit wütenden, unbelegten Anzeigen fluten und niemanden durch haltlose Vorwürfe unter Druck setzen. Wenn eine Strafanzeige aber nötig ist, führt es zu einem sauberen, nüchternen, beweisnahen Entwurf.

## Leitplanke

Wehe, es werden Dinge behauptet, die nicht stimmen. Das Plugin zwingt zur Trennung von eigener Wahrnehmung, Dokument, Zeuge, Vermutung und rechtlicher Bewertung. Bei eigener Beteiligung, Unternehmensfällen, schweren Gewalt-/Sexualdelikten, Wirtschaftsstrafsachen oder Berufsgeheimnissen: anwaltliche Hilfe einschalten.

## Was dieses Plugin gut kann

- Trennt Strafanzeige, Strafantrag, zivilrechtliche Alternativen und bloße Beschwerde.
- Prüft vorab § 164 StGB, §§ 186/187 StGB, § 824 BGB und Druckmittelrisiken.
- Baut Sachverhalt, Beweismatrix, Anlagenverzeichnis und Strafantragsfristen auf.
- Erzeugt erst am Ende einen Anzeigeentwurf, wenn die Tatsachenbasis trägt.

## Startlogik

Beginne mit dem allgemeinen Kaltstart-Skill. Er fragt Rolle, Ziel, Frist, Unterlagen, Risiken und gewünschten Output ab. Danach werden nur passende Spezial-Skills vorgeschlagen.

## Quellenhygiene

Normtexte werden aus amtlichen Quellen geprüft. Rechtsprechung wird nur mit Gericht, Datum, Aktenzeichen und frei zugänglicher Quelle verwendet. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 56 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anzeige-akteneinsicht-verletzter-406e` | Akteneinsicht für Verletzte und ihre Anwälte: Voraussetzungen, Schutzinteressen, Datenschutz und Taktik: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-anfangsverdacht-anlagenverzeichnis` | Anfangsverdacht strukturieren: zureichende tatsächliche Anhaltspunkte, Ermittlungsauftrag der StA, keine bloße Spekulation: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-anlagenverzeichnis-hashlog` | Anlagen zu Strafanzeigen: Nummerierung, Hashwerte, Originale, Kopien, Versandnachweis und digitale Kette: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-antragsdelikte-strafantrag` | Strafantragsfrist und Antragsberechtigung bei Beleidigung, Hausfriedensbruch, einfacher Körperverletzung und weiteren Antragsdelikten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-anwalt-arbeitsplatz` | Schwellen für anwaltliche Hilfe: eigene Beteiligung, Wirtschaftsstrafrecht, Sexual-/Gewaltdelikte, Berufsgeheimnisse, Unternehmen, Presse: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-arbeitsplatz-sexuelle-belaestigung` | Arbeitsplatzvorfälle: strafrechtliche Anzeige, AGG/Arbeitsrecht, Beweise, Schutz, interne Untersuchung und Betroffenenrechte: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-bankrott-bedrohung` | Bankrott und Buchführungsdelikte: Vermögensverschiebung, Buchführung, Krise, Gläubigerbenachteiligung und Insolvenzakten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-bedrohung-241` | Bedrohung anzeigen: Inhalt, Ernstlichkeit, Adressat, Beweise, Schutzmaßnahmen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-beleidigung-betrug` | Beleidigung anzeigen: Kontext, Meinungsfreiheit, Strafantrag, Beweise, Plattform/Arbeitsplatz: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-betrug-263` | Betrugsanzeige: Täuschung, Irrtum, Vermögensverfügung, Schaden, Vorsatz, Belege und zivilrechtliche Parallelspur: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-beweismatrix-chatverlaeufe` | Ordnet jedes Element der Anzeige nach Tatsachenwissen, Beleg, Zeuge, Dokument, Meinung und Vermutung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-chatverlaeufe-emails-header` | Chatverläufe, EML-Dateien, E-Mail-Header, Messenger-Screenshots, Export und Kontext sichern: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-computerbetrug-phishing` | Computerbetrug/Phishing anzeigen: Zahlungsdaten, TAN, Social Engineering, Bankkommunikation, Logs und Sofortmaßnahmen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-datenstraftaten-diebstahl` | Ausspähen, Abfangen, Datenveränderung, Computersabotage: technische Beweise, Logs, Forensik und ZAC: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-diebstahl-unterschlagung` | Diebstahl/Unterschlagung anzeigen: Gewahrsam, Eigentum, Wegnahme, Zueignung, Beweise, Herausgabeverlangen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-druckmittel-falsche` | Prüft, ob Drohung mit Strafanzeige oder Anzeige selbst als unzulässiges Druckmittel/Nötigung wirken kann: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-falsche-verdaechtigung-164` | Warn- und Prüfskill zu § 164 StGB: niemanden sicher beschuldigen, wenn nur Verdachtsmomente oder Hörensagen vorliegen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-gegenanzeige-geldwaesche` | Risiko der Gegenanzeige wegen falscher Verdächtigung, Verleumdung, Nötigung, Datenschutzverstoß oder Prozessbetrug: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-geldwaesche-261` | Geldwäscheverdacht: Tatertrag, Verschleierung, Transaktionen, GwG-Verdachtsmeldung vs Strafanzeige: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-geschgehg-haeusliche` | Geschäftsgeheimnis-Strafanzeige: Geheimnisqualität, angemessene Geheimhaltungsmaßnahmen, Erlangen/Nutzen/Offenlegen, Strafantrag: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-haeusliche-gewalt-gewschg` | Strafanzeige bei häuslicher Gewalt plus Schutzanordnung, Beweissicherung, medizinische Dokumentation und Sicherheitsplan: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-hausfriedensbruch` | Hausfriedensbruch anzeigen: befriedetes Besitztum, Wohnung/Geschäft, Aufforderung zu gehen, Strafantrag: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-insolvenzverschleppung-15a` | Insolvenzverschleppung anzeigen: Organstellung, Zahlungsunfähigkeit/Überschuldung, Fristen, Gläubigerschaden und Belege: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-international-klageerzwingung` | Internationale Sachverhalte: Tatort, Zuständigkeit, Europol/Interpol nicht direkt, ausländische Behörden, Übersetzungen und Beweise: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-kaltstart-routing` | Geführter Einstieg für Strafanzeigen: Sachverhalt, Beweise, Straftatverdacht, Strafantrag, Risiken falscher Verdächtigung, Alternativen und anwaltliche Eskalationsschwelle. |
| `anzeige-klageerzwingung-172-stpo` | Nach Einstellung: Beschwerde, Klageerzwingung, Fristen, Verletztenstellung und anwaltliche Schwelle: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-koerperverletzung-korruption` | Körperverletzung: Verletzung, Arztbericht, Fotos, Zeugen, Strafantrag bei § 223 und besonderes öffentliches Interesse: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-korruption-299-331ff` | Korruptionsanzeige: Bestechlichkeit/Bestechung im geschäftlichen Verkehr oder Amt, Vorteil, Unrechtsvereinbarung, Belege, Selbstbelastung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-kreditgefaehrdung-minderjaehrige` | Zivilrechtliches Haftungsrisiko bei Behauptungen über Insolvenz, Betrug, Zahlungsunfähigkeit oder Unzuverlässigkeit: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-minderjaehrige-schule` | Strafanzeige bei Minderjährigen/Schule: Jugendstrafrecht, Schutz, Schulrecht, Eltern, Jugendamt und Deeskalation: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-muster-noetigung` | Erzeugt eine nüchterne Strafanzeige mit optionalem Strafantrag, Anlagen, Beweismatrix und Risikoformulierungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-nicht-anzeigen-redteam` | Red-Team prüft, ob eine Strafanzeige unnötig, riskant, zivilrechtlich kontraproduktiv oder straf-/haftungsrechtlich gefährlich wäre. |
| `anzeige-noetigung-240` | Nötigung prüfen: Gewalt/Drohung, empfindliches Übel, Verwerflichkeit, legitime Anzeigeandrohung vs. Missbrauch: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-notruf-online` | Akute Gefahr, laufende Tat, Selbst-/Fremdgefährdung: Sofort Polizei/112/110 statt Entwurf: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-online-plattform-screenshots` | Screenshots, URLs, Zeitstempel, Accountdaten, Plattformmeldungen und Löschrisiko beweissicher sichern: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-onlinewache-opferschutz` | Adressat und Form: Onlinewache, Polizeidienststelle, Staatsanwaltschaft, Spezialdienststelle Cybercrime, Zoll oder Finanzbehörde: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-opferschutz-nebenklage` | Rechte Verletzter: Nebenklage, psychosoziale Prozessbegleitung, Adhäsion, Schutzanordnung, Akteneinsicht: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-rechtsfolgen-ruecknahme` | Strafanzeige mit Zivilrecht koordinieren: Schadensersatz, Unterlassung, einstweilige Verfügung, Kündigung, Versicherung, Adhäsion: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-ruecknahme-einstellung-170-153` | Was nach Anzeige passiert: Einstellung, Rücknahme Strafantrag, Opportunität, Beschwerde, Kommunikation mit StA: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-sachbeschaedigung-sachverhalt` | Sachbeschädigung: Beschädigung/Zerstörung/Veränderung, Fotos, Kostenvoranschlag, Strafantrag, Zivilforderung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-sachverhalt-ohne-adjektive` | Entfernt Polemik und Rechtswertungen aus Anzeigen; schreibt nüchtern, präzise und beweisnah: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-stalking-vs` | Nachstellung anzeigen: wiederholtes Verhalten, Eignung zur Beeinträchtigung, Dokumentation, Kontaktverbote und Plattformbeweise: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-steuerhinterziehung-akteneinsicht` | Steuerstraftaten anzeigen oder Selbstbelastung vermeiden: Drittanzeige, Selbstanzeige-Abgrenzung, Belege, Finanzamt/Steufa: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-strafantrag-form-frist` | Strafantrag richtig stellen, beweisen und Rücknahmefolgen prüfen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-strafanzeige-vs-strafantrag-158` | Unterscheidet Strafanzeige, Strafantrag, Dienstaufsichtsbeschwerde, Privatklage und zivilrechtliche Abmahnung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-tierschutz-ueblerede` | Tierschutzanzeige: erhebliche Schmerzen/Leiden, Rohheit, länger anhaltende Wiederholung, Veterinäramt und Beweise: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-ueblerede-verleumdung-186-187` | Strafanzeige und Kommunikation so formulieren, dass keine unnötige ehrverletzende Drittverbreitung entsteht: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-umweltstraftaten-unternehmen` | Umweltstraftaten anzeigen: Gewässer, Boden, Luft, Abfall, Genehmigungen, Beweise und Umweltbehörde: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-unternehmen-internal-investigation` | Unternehmensanzeige nach interner Untersuchung: Legal Hold, Mitarbeiterinterviews, Datenschutz, Arbeitsrecht, Beschlagnahmerisiko und Bericht: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-untreue-urheberrecht` | Untreue anzeigen: Vermögensbetreuungspflicht, Pflichtverletzung, Vermögensnachteil, Organ-/Mitarbeiterfälle: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-urheberrecht-markenrecht` | IP-Strafanzeigen bei Urheber-, Marken-, Design- und Patentrechtsverletzungen: Strafantrag, Testkauf, Originalitätsnachweis, Zoll: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-verkehrsunfall-video` | Unerlaubtes Entfernen vom Unfallort: Schaden, Wartepflicht, Feststellungen, Dashcam/Zeugen, Selbstmeldung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-video-audio-kug-201` | Video-/Audioaufnahmen als Beweis: Recht am Bild, Vertraulichkeit des Wortes, öffentliche Situation, Polizei/Versammlung und Veröffentlichungsverbot: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-wer-zeugenliste` | Sachverhaltskern einer Anzeige: chronologisch, nüchtern, belegbar, ohne Polemik: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-whistleblower-computerbetrug` | Hinweisgebermeldung, interne Stelle, externe Meldung, Strafanzeige und Schutz vor Repressalien koordinieren: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anzeige-zeugenliste-kontakt` | Zeugen benennen, aber nicht beeinflussen: Kontaktdaten, Wahrnehmung, Reihenfolge und Dokumentation: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
