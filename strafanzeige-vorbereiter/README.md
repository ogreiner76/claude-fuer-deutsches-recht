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
| `anzeige-anfangsverdacht-anlagenverzeichnis` | Nutze dies bei Anzeige Anfangsverdacht 152 160 Stpo, Anzeige Anlagenverzeichnis Hashlog: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-antragsdelikte-anzeige-strafantrag` | Nutze dies bei Anzeige Antragsdelikte 77b Frist, Anzeige Strafantrag Form Frist: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-anwalt-anzeige-arbeitsplatz` | Nutze dies bei Anzeige Anwalt Einschalten Schwelle, Anzeige Arbeitsplatz Sexuelle Belaestigung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-bankrott-anzeige-bedrohung` | Nutze dies bei Anzeige Bankrott 283, Anzeige Bedrohung 241: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-beleidigung-anzeige-betrug` | Nutze dies bei Anzeige Beleidigung 185 194, Anzeige Betrug 263: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-beweismatrix-anzeige-chatverlaeufe` | Nutze dies bei Anzeige Beweismatrix Tatsachen Meinungen, Anzeige Chatverlaeufe Emails Header: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-datenstraftaten-anzeige-diebstahl` | Nutze dies bei Anzeige Datenstraftaten 202a 303a, Anzeige Diebstahl Unterschlagung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-druckmittel-anzeige-falsche` | Nutze dies bei Anzeige Druckmittel Verbot Noetigung, Anzeige Falsche Verdaechtigung 164: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-gegenanzeige-anzeige-geldwaesche` | Nutze dies bei Anzeige Gegenanzeige Risiko, Anzeige Geldwaesche 261: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-geschgehg-anzeige-haeusliche` | Nutze dies bei Anzeige Geschgehg 23 Geheimnisverrat, Anzeige Haeusliche Gewalt Gewschg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-hausfriedensbruch` | Nutze dies bei Anzeige Hausfriedensbruch 123, Anzeige Insolvenzverschleppung 15a: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-international-anzeige-klageerzwingung` | Nutze dies bei Anzeige International Eu 158 3, Anzeige Klageerzwingung 172 Stpo: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-koerperverletzung-anzeige-korruption` | Nutze dies bei Anzeige Koerperverletzung 223 230, Anzeige Korruption 299 331ff: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-kreditgefaehrdung-minderjaehrige` | Nutze dies bei Anzeige Kreditgefaehrdung 824 Bgb, Anzeige Minderjaehrige Schule: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-muster-anzeige-noetigung` | Nutze dies bei Anzeige Muster Strafanzeige Generator, Anzeige Noetigung 240: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-nicht-anzeigen-redteam` | Red-Team prüft, ob eine Strafanzeige unnötig, riskant, zivilrechtlich kontraproduktiv oder straf-/haftungsrechtlich gefährlich wäre. |
| `anzeige-notruf-anzeige-online` | Nutze dies bei Anzeige Notruf Akut Gefahr, Anzeige Online Plattform Screenshots: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-onlinewache-anzeige-opferschutz` | Nutze dies bei Anzeige Onlinewache Vs Staatsanwaltschaft, Anzeige Opferschutz Nebenklage: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-rechtsfolgen-anzeige-ruecknahme` | Nutze dies bei Anzeige Rechtsfolgen Und Zivilstrategie, Anzeige Ruecknahme Einstellung 170 153: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-sachbeschaedigung-anzeige-sachverhalt` | Nutze dies bei Anzeige Sachbeschaedigung 303, Anzeige Sachverhalt Ohne Adjektive: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-stalking-anzeige-vs` | Nutze dies bei Anzeige Stalking 238, Anzeige Strafanzeige Vs Strafantrag 158: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-steuerhinterziehung-akteneinsicht` | Nutze dies bei Anzeige Steuerhinterziehung 370 Ao, Anzeige Akteneinsicht Verletzter 406e: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-tierschutz-anzeige-ueblerede` | Nutze dies bei Anzeige Tierschutz 17, Anzeige Ueblerede Verleumdung 186 187: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-umweltstraftaten-anzeige-unternehmen` | Nutze dies bei Anzeige Umweltstraftaten 324ff, Anzeige Unternehmen Internal Investigation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-untreue-anzeige-urheberrecht` | Nutze dies bei Anzeige Untreue 266, Anzeige Urheberrecht Markenrecht: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-verkehrsunfall-anzeige-video` | Nutze dies bei Anzeige Verkehrsunfall Flucht 142, Anzeige Video Audio Kug 201: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-wer-anzeige-zeugenliste` | Nutze dies bei Anzeige Wer Was Wann Wo Wie, Anzeige Zeugenliste Kontakt: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anzeige-whistleblower-anzeige-computerbetrug` | Nutze dies bei Anzeige Compliance Whistleblower Hinschg, Anzeige Computerbetrug Phishing: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
