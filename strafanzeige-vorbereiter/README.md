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

Automatisch generierte Komplett-Liste aller 29 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anzeige-anfangsverdacht-anlagenverzeichnis` | Anzeige Anfangsverdacht Anlagenverzeichnis im Strafanzeigen-Vorbereitung: prüft konkret Anfangsverdacht strukturieren, Anlagen zu Strafanzeigen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-antragsdelikte-strafantrag` | Anzeige Antragsdelikte Strafantrag im Strafanzeigen-Vorbereitung: prüft konkret Strafantragsfrist und Antragsberechtigung bei Beleidigung, Hausfriedensbruch, Strafantrag richtig stellen, beweisen und Rücknahmefolgen prüfen. Liefert prior... |
| `anzeige-anwalt-arbeitsplatz` | Anzeige Anwalt Arbeitsplatz im Strafanzeigen-Vorbereitung: prüft konkret Schwellen für anwaltliche Hilfe, Arbeitsplatzvorfälle. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-bankrott-bedrohung` | Anzeige Bankrott Bedrohung im Strafanzeigen-Vorbereitung: prüft konkret Bankrott und Buchführungsdelikte, Bedrohung anzeigen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-beleidigung-betrug` | Anzeige Beleidigung Betrug im Strafanzeigen-Vorbereitung: prüft konkret Beleidigung anzeigen, Betrugsanzeige. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-beweismatrix-chatverlaeufe` | Anzeige Beweismatrix Chatverlaeufe im Strafanzeigen-Vorbereitung: prüft konkret Ordnet jedes Element der Anzeige nach Tatsachenwissen, Beleg, Zeuge, Dokument. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schr... |
| `anzeige-datenstraftaten-diebstahl` | Anzeige Datenstraftaten Diebstahl im Strafanzeigen-Vorbereitung: prüft konkret Ausspähen, Abfangen, Datenveränderung, Computersabotage. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-druckmittel-falsche` | Anzeige Druckmittel Falsche im Strafanzeigen-Vorbereitung: prüft konkret Prüft, ob Drohung mit Strafanzeige oder Anzeige selbst als, Warn- und Prüfskill zu § 164 StGB. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näch... |
| `anzeige-gegenanzeige-geldwaesche` | Anzeige Gegenanzeige Geldwaesche im Strafanzeigen-Vorbereitung: prüft konkret Risiko der Gegenanzeige wegen falscher Verdächtigung, Verleumdung, Nötigung, Dat. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Sch... |
| `anzeige-geschgehg-haeusliche` | Anzeige Geschgehg Haeusliche im Strafanzeigen-Vorbereitung: prüft konkret Geschäftsgeheimnis-Strafanzeige, Strafanzeige bei häuslicher Gewalt plus Schutzanordnung, Beweissicherung, medizi. Liefert priorisierten Output mit Norm-Pinpoints,... |
| `anzeige-hausfriedensbruch` | Anzeige Hausfriedensbruch im Strafanzeigen-Vorbereitung: prüft konkret Hausfriedensbruch anzeigen, Insolvenzverschleppung anzeigen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-international-klageerzwingung` | Anzeige International Klageerzwingung im Strafanzeigen-Vorbereitung: prüft konkret Internationale Sachverhalte, Nach Einstellung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-kaltstart-routing` | Geführter Einstieg für Strafanzeigen: Sachverhalt, Beweise, Straftatverdacht, Strafantrag, Risiken falscher Verdächtigung, Alternativen und anwaltliche Eskalationsschwelle. |
| `anzeige-koerperverletzung-korruption` | Anzeige Koerperverletzung Korruption im Strafanzeigen-Vorbereitung: prüft konkret Körperverletzung, Korruptionsanzeige. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-kreditgefaehrdung-minderjaehrige` | Anzeige Kreditgefaehrdung Minderjaehrige im Strafanzeigen-Vorbereitung: prüft konkret Zivilrechtliches Haftungsrisiko bei Behauptungen über, Betrug, Zahlung, Strafanzeige bei Minderjährigen/Schule. Liefert priorisierten Output mit Norm-P... |
| `anzeige-muster-noetigung` | Anzeige Muster Noetigung im Strafanzeigen-Vorbereitung: prüft konkret Erzeugt eine nüchterne Strafanzeige mit optionalem, Anlagen, Beweism, Nötigung prüfen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-nicht-anzeigen-redteam` | Red-Team prüft, ob eine Strafanzeige unnötig, riskant, zivilrechtlich kontraproduktiv oder straf-/haftungsrechtlich gefährlich wäre. |
| `anzeige-notruf-online` | Anzeige Notruf Online im Strafanzeigen-Vorbereitung: prüft konkret Akute Gefahr, laufende Tat, Selbst-/Fremdgefährdung, Screenshots. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-onlinewache-opferschutz` | Anzeige Onlinewache Opferschutz im Strafanzeigen-Vorbereitung: prüft konkret Adressat und Form, Rechte Verletzter. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-rechtsfolgen-ruecknahme` | Anzeige Rechtsfolgen Ruecknahme im Strafanzeigen-Vorbereitung: prüft konkret Strafanzeige mit Zivilrecht koordinieren, Was nach Anzeige passiert. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-sachbeschaedigung-sachverhalt` | Anzeige Sachbeschaedigung Sachverhalt im Strafanzeigen-Vorbereitung: prüft konkret Sachbeschädigung, Entfernt Polemik und Rechtswertungen aus Anzeigen, präzise un. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem... |
| `anzeige-stalking-vs` | Anzeige Stalking VS im Strafanzeigen-Vorbereitung: prüft konkret Nachstellung anzeigen, Unterscheidet Strafanzeige, Strafantrag, Dienstaufsichtsbeschwerde. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-steuerhinterziehung-akteneinsicht` | Anzeige Steuerhinterziehung Akteneinsicht im Strafanzeigen-Vorbereitung: prüft konkret Steuerstraftaten anzeigen oder Selbstbelastung vermeiden, Akteneinsicht für Verletzte und ihre Anwälte. Liefert priorisierten Output mit Norm-Pinpoint... |
| `anzeige-tierschutz-ueblerede` | Anzeige Tierschutz Ueblerede im Strafanzeigen-Vorbereitung: prüft konkret Tierschutzanzeige, Strafanzeige und Kommunikation so formulieren, dass keine unnötige ehrverletzend. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel u... |
| `anzeige-umweltstraftaten-unternehmen` | Anzeige Umweltstraftaten Unternehmen im Strafanzeigen-Vorbereitung: prüft konkret Umweltstraftaten anzeigen, Unternehmensanzeige nach interner Untersuchung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-untreue-urheberrecht` | Anzeige Untreue Urheberrecht im Strafanzeigen-Vorbereitung: prüft konkret Untreue anzeigen, IP-Strafanzeigen bei Urheber-, Marken-, Design- und Patentrechtsverletzungen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nä... |
| `anzeige-verkehrsunfall-video` | Anzeige Verkehrsunfall Video im Strafanzeigen-Vorbereitung: prüft konkret Unerlaubtes Entfernen vom Unfallort, Video-/Audioaufnahmen als Beweis. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-wer-zeugenliste` | Anzeige WER Zeugenliste im Strafanzeigen-Vorbereitung: prüft konkret Sachverhaltskern einer Anzeige, Zeugen benennen, aber nicht beeinflussen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anzeige-whistleblower-computerbetrug` | Anzeige Whistleblower Computerbetrug im Strafanzeigen-Vorbereitung: prüft konkret Hinweisgebermeldung, interne Stelle, externe Meldung, Strafanzeige und Schutz vo. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
