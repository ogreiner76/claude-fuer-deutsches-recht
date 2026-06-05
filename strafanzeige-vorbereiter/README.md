# Strafanzeige-Vorbereiter

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`strafanzeige-vorbereiter`) | [`strafanzeige-vorbereiter.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/strafanzeige-vorbereiter.zip) |

### Demonstrations-Akten

Dieses Plugin hat derzeit keine eigene Demonstrations-Akte. Es arbeitet mit Sachverhaltsnotizen, Chats, E-Mails, EML-Dateien, Screenshots, Fotos, Videos, Zeugenlisten, Belegen, ärztlichen Unterlagen, Verträgen und vorhandenen Anzeigeentwürfen.

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
| `anzeige-allgemeiner-kaltstart` | Geführter Einstieg für Strafanzeigen: Sachverhalt, Beweise, Straftatverdacht, Strafantrag, Risiken falscher Verdächtigung, Alternativen und anwaltliche Eskalationsschwelle. |
| `anzeige-anfangsverdacht-anlagenverzeichnis` | Nutze dies, wenn Anzeige Anfangsverdacht 152 160 Stpo, Anzeige Anlagenverzeichnis Hashlog im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Anfangsverdacht 152 160 Stpo, Anzeige Anlagenverzeichnis... |
| `anzeige-antragsdelikte-anzeige-strafantrag` | Nutze dies, wenn Anzeige Antragsdelikte 77B Frist, Anzeige Strafantrag Form Frist im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Antragsdelikte 77B Frist, Anzeige Strafantrag Form Frist prüfen.... |
| `anzeige-anwalt-anzeige-arbeitsplatz` | Nutze dies, wenn Anzeige Anwalt Einschalten Schwelle, Anzeige Arbeitsplatz Sexuelle Belaestigung im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Anwalt Einschalten Schwelle, Anzeige Arbeitsplatz... |
| `anzeige-bankrott-anzeige-bedrohung` | Nutze dies, wenn Anzeige Bankrott 283, Anzeige Bedrohung 241 im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Bankrott 283, Anzeige Bedrohung 241 prüfen.; Erstelle eine Arbeitsfassung zu Anzeige... |
| `anzeige-beleidigung-anzeige-betrug` | Nutze dies, wenn Anzeige Beleidigung 185 194, Anzeige Betrug 263 im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Beleidigung 185 194, Anzeige Betrug 263 prüfen.; Erstelle eine Arbeitsfassung zu... |
| `anzeige-beweismatrix-anzeige-chatverlaeufe` | Nutze dies, wenn Anzeige Beweismatrix Tatsachen Meinungen, Anzeige Chatverlaeufe Emails Header im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Beweismatrix Tatsachen Meinungen, Anzeige Chatverla... |
| `anzeige-datenstraftaten-anzeige-diebstahl` | Nutze dies, wenn Anzeige Datenstraftaten 202A 303A, Anzeige Diebstahl Unterschlagung im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Datenstraftaten 202A 303A, Anzeige Diebstahl Unterschlagung p... |
| `anzeige-druckmittel-anzeige-falsche` | Nutze dies, wenn Anzeige Druckmittel Verbot Noetigung, Anzeige Falsche Verdaechtigung 164 im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Druckmittel Verbot Noetigung, Anzeige Falsche Verdaechti... |
| `anzeige-gegenanzeige-anzeige-geldwaesche` | Nutze dies, wenn Anzeige Gegenanzeige Risiko, Anzeige Geldwaesche 261 im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Gegenanzeige Risiko, Anzeige Geldwaesche 261 prüfen.; Erstelle eine Arbeitsf... |
| `anzeige-geschgehg-anzeige-haeusliche` | Nutze dies, wenn Anzeige Geschgehg 23 Geheimnisverrat, Anzeige Haeusliche Gewalt Gewschg im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Geschgehg 23 Geheimnisverrat, Anzeige Haeusliche Gewalt G... |
| `anzeige-hausfriedensbruch` | Nutze dies, wenn Anzeige Hausfriedensbruch 123, Anzeige Insolvenzverschleppung 15A im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Hausfriedensbruch 123, Anzeige Insolvenzverschleppung 15A prüfe... |
| `anzeige-international-anzeige-klageerzwingung` | Nutze dies, wenn Anzeige International Eu 158 3, Anzeige Klageerzwingung 172 Stpo im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige International Eu 158 3, Anzeige Klageerzwingung 172 Stpo prüfen.... |
| `anzeige-koerperverletzung-anzeige-korruption` | Nutze dies, wenn Anzeige Koerperverletzung 223 230, Anzeige Korruption 299 331Ff im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Koerperverletzung 223 230, Anzeige Korruption 299 331Ff prüfen.;... |
| `anzeige-kreditgefaehrdung-minderjaehrige` | Nutze dies, wenn Anzeige Kreditgefaehrdung 824 Bgb, Anzeige Minderjaehrige Schule im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweisla... |
| `anzeige-muster-anzeige-noetigung` | Nutze dies, wenn Anzeige Muster Strafanzeige Generator, Anzeige Noetigung 240 im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Muster Strafanzeige Generator, Anzeige Noetigung 240 prüfen.; Erstel... |
| `anzeige-nicht-anzeigen-redteam` | Red-Team prüft, ob eine Strafanzeige unnötig, riskant, zivilrechtlich kontraproduktiv oder straf-/haftungsrechtlich gefährlich wäre. |
| `anzeige-notruf-anzeige-online` | Nutze dies, wenn Anzeige Notruf Akut Gefahr, Anzeige Online Plattform Screenshots im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Notruf Akut Gefahr, Anzeige Online Plattform Screenshots prüfen.... |
| `anzeige-onlinewache-anzeige-opferschutz` | Nutze dies, wenn Anzeige Onlinewache Vs Staatsanwaltschaft, Anzeige Opferschutz Nebenklage im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Onlinewache Vs Staatsanwaltschaft, Anzeige Opferschutz... |
| `anzeige-rechtsfolgen-anzeige-ruecknahme` | Nutze dies, wenn Anzeige Rechtsfolgen Und Zivilstrategie, Anzeige Rücknahme Einstellung 170 153 im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Rechtsfolgen Und Zivilstrategie, Anzeige Rücknahme... |
| `anzeige-sachbeschaedigung-anzeige-sachverhalt` | Nutze dies, wenn Anzeige Sachbeschaedigung 303, Anzeige Sachverhalt Ohne Adjektive im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Sachbeschaedigung 303, Anzeige Sachverhalt Ohne Adjektive prüfe... |
| `anzeige-stalking-anzeige-vs` | Nutze dies, wenn Anzeige Stalking 238, Anzeige Strafanzeige Vs Strafantrag 158 im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Stalking 238, Anzeige Strafanzeige Vs Strafantrag 158 prüfen.; Erst... |
| `anzeige-steuerhinterziehung-akteneinsicht` | Nutze dies, wenn Anzeige Steuerhinterziehung 370 Ao, Anzeige Akteneinsicht Verletzter 406E im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Steuerhinterziehung 370 Ao, Anzeige Akteneinsicht Verle... |
| `anzeige-tierschutz-anzeige-ueblerede` | Nutze dies, wenn Anzeige Tierschutz 17, Anzeige Ueblerede Verleumdung 186 187 im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast ü... |
| `anzeige-umweltstraftaten-anzeige-unternehmen` | Nutze dies, wenn Anzeige Umweltstraftaten 324Ff, Anzeige Unternehmen Internal Investigation im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Umweltstraftaten 324Ff, Anzeige Unternehmen Internal I... |
| `anzeige-untreue-anzeige-urheberrecht` | Nutze dies, wenn Anzeige Untreue 266, Anzeige Urheberrecht Markenrecht im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Untreue 266, Anzeige Urheberrecht Markenrecht prüfen.; Erstelle eine Arbeit... |
| `anzeige-verkehrsunfall-anzeige-video` | Nutze dies, wenn Anzeige Verkehrsunfall Flucht 142, Anzeige Video Audio Kug 201 im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Verkehrsunfall Flucht 142, Anzeige Video Audio Kug 201 prüfen.; Er... |
| `anzeige-wer-anzeige-zeugenliste` | Nutze dies, wenn Anzeige Wer Was Wann Wo Wie, Anzeige Zeugenliste Kontakt im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Wer Was Wann Wo Wie, Anzeige Zeugenliste Kontakt prüfen.; Erstelle eine... |
| `anzeige-whistleblower-anzeige-computerbetrug` | Nutze dies, wenn Anzeige Compliance Whistleblower Hinschg, Anzeige Computerbetrug Phishing im Plugin Strafanzeige Vorbereiter konkret bearbeitet werden soll. Auslöser: Bitte Anzeige Compliance Whistleblower Hinschg, Anzeige Computerbetru... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
