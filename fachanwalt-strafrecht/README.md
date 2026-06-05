# Fachanwalt Strafrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`fachanwalt-strafrecht`) | [`fachanwalt-strafrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/fachanwalt-strafrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **BtM-Akte** (`betaeubungsmittelrecht-apotheke-substitution-festival`) | [Gesamt-PDF lesen](../testakten/betaeubungsmittelrecht-apotheke-substitution-festival/gesamt-pdf/betaeubungsmittelrecht-apotheke-substitution-festival_gesamt.pdf) | [`testakte-betaeubungsmittelrecht-apotheke-substitution-festival.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-betaeubungsmittelrecht-apotheke-substitution-festival.zip) |
| **Grossbankrott und Zeugenstreit — Mehrere Deliktszweige, Pellbach Logistik & Spedition GmbH, LG Koeln** (`grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln`) | [Gesamt-PDF lesen](../testakten/grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln/gesamt-pdf/grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln_gesamt.pdf) | [`testakte-grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln.zip) |
| **Wirtschaftsstrafsache Bankert — U-Haft, Betrug, Steuerhinterziehung, LG Frankfurt** (`wirtschaftsstrafsache-uhaft-bankert-frankfurt`) | [Gesamt-PDF lesen](../testakten/wirtschaftsstrafsache-uhaft-bankert-frankfurt/gesamt-pdf/wirtschaftsstrafsache-uhaft-bankert-frankfurt_gesamt.pdf) | [`testakte-wirtschaftsstrafsache-uhaft-bankert-frankfurt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-wirtschaftsstrafsache-uhaft-bankert-frankfurt.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

## Was dieses Plugin im Strafprozess leistet

Dieses Plugin ist als Arbeitscockpit für Strafverteidigung gedacht: nicht nur für die große Strategie, sondern für die täglichen Schritte einer laufenden Strafakte. Es ordnet Eingänge, markiert Fristen, baut Aktenlog und Wiedervorlagen, steuert Akteneinsicht, U-Haft, Pflichtverteidigung, Hauptverhandlung, Antragslog, Mandanteninstruktionen, Rechtsmittel und Vollstreckungsnachlauf.

Der Kaltstart soll sofort praktisch werden: Was ist heute gefährlich, welche Frist läuft, welcher Schriftsatz oder Anruf muss raus, welche Aktenbestandteile fehlen, was darf der Mandant keinesfalls ohne Rücksprache tun? Danach schlägt das Plugin die passenden Strafprozess-Skills aus diesem Plugin vor und hält das Ergebnis als Checkliste, Matrix, Memo, Mandantenbrief oder Schriftsatzbaustein fest.

Neu aufgenommen ist ein vertiefter Prüfpfad für digitale Ermittlungsmaßnahmen: biometrischer Internetabgleich, KI-gestützte Trefferlisten, verfahrensübergreifende Analyseplattformen, Akteneinsicht in technische Protokolle, Löschung, Benachrichtigung, KI-VO-Konformität und Verwertungsangriffe. Der Skill behandelt solche Maßnahmen ausdrücklich als rechtsstandsabhängig: Entwurf, Inkrafttreten und aktueller Wortlaut sind vor jeder tragenden Aussage live zu prüfen.

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `strafprozess-cockpit-taegliche-kanzleifuehrung` | Laufendes Verteidigungs-Cockpit mit Verfahrensstand, Fristen, Haftlage, Akteneinsicht, offenen Anträgen, Terminen und nächstem Schritt. |
| `strafprozess-aktenlog-fristen-und-wiedervorlagen` | Macht aus beA-/EGVP-Eingängen, Beschlüssen, Ladungen, Strafbefehlen, Urteilen und Nachlieferungen ein belastbares Fristen- und Aufgabenlog. |
| `strafprozess-haft-und-besuchsmanagement` | Organisiert U-Haft, Haftprüfung, Haftbeschwerde, Haftverschonung, Akteneinsicht, Besuch, Telefon, Familie, Arbeitgeber und Beschleunigungskontrolle. |
| `strafprozess-hv-tagesmappe-und-sitzungsplan` | Baut für jeden Sitzungstag eine Hauptverhandlungs-Tagesmappe mit Zeugenprogramm, Fragelisten, Einlassungsfenster, Antragsentwürfen und Nachbereitung. |
| `strafprozess-sitzungsprotokoll-und-revisionssicherung` | Sichert Protokollierung, Anträge, Belehrungen, Verständigung, letztes Wort und mögliche Revisionsrügen während und nach der Hauptverhandlung. |
| `fachanwalt-strafrecht-orientierung` | Orientierung im Strafrecht — FAO-Voraussetzungen Normen typische Mandate Notfristen Quellenprüfung. Plugin für schnelle Verortung. Strafverteidigung im Ermittlungsverfahren (Akteneinsicht § 147 StPO) H… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 37 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `adhaesionsverfahren-ermittlungsverfahren` | Nutze dies bei Redteam Qualitygate, Fachanwalt Strafrecht Adhaesionsverfahren, Ermittlungsverfahren Vergleich Eskalation, Orientierung Fristen Form Und Zustaendigkeit: führt durch diese fachlich verbundenen Module, wählt den passenden Pr... |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `aussagepsychologie-staatsanwaltschaft` | Nutze dies bei Strafrecht Aussagepsychologie Staatsanwaltschaft Replik, Strafrecht Aussagepsychologie Vernehmungslehre Praxis, Strafrecht Aussetzung 221 Stgb, Strafrecht Bandenbetrug 263 Stgb: führt durch diese fachlich verbundenen Modul... |
| `chatcontrol-csam-einlassung-vorbereiten` | Nutze dies bei Fachanwalt Strafrecht Chatcontrol Csam Anwaltsgeheimnis 53 Stpo, Fachanwalt Strafrecht Einlassung Vorbereiten, Fachanwalt Strafrecht Hauptverhandlung Vorbereiten, Fachanwalt Strafrecht Insolvenzantrag Staatsanwaltschaft: f... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `ergaenzt-fachanwalt-insolvenzantrag-red` | Nutze dies bei Ergaenzt Mandantenkommunikation Entscheidungsvorlage, Fachanwalt Erstpruefung Und Mandatsziel, Insolvenzantrag Red Team Und Qualitaetskontrolle, Kanzlei Sonderfall Und Edge Case: führt durch diese fachlich verbundenen Modu... |
| `fachanwalt-strafrecht-orientierung` | Nutze dies bei Fachanwalt Strafrecht Orientierung, Fachanwalt Strafrecht Untersuchungshaft Haftpruefung, Fachanwalt Strafrecht Verstaendigung 257c Toa 46a, Fachanwalt Strafrecht Wahlverteidiger Mandat: führt durch diese fachlich verbunde... |
| `hauptverhandlung-quellenkarte` | Nutze dies zur Quellenprüfung bei Hauptverhandlung Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `koerperverletzung-stgb-todesfolge` | Nutze dies bei Strafrecht Koerperverletzung 223 Stgb Grund, Strafrecht Koerperverletzung Mit Todesfolge 227 Stgb, Strafrecht Konkursrechtliche Anfechtungsbezuege, Strafrecht Kreditbetrug 265b Stgb: führt durch diese fachlich verbundenen... |
| `mandat-triage-plaedoyer-vorbereitung` | Nutze dies bei Mandat Triage Strafrecht, Plaedoyer Vorbereitung Strafverteidigung, Schriftsatzkern Substantiierung, Adhaesion Formular Portal Und Einreichung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad un... |
| `nebenklage-nebenstrafrecht-opfervertretung` | Nutze dies bei Nebenklage Compliance Dokumentation Und Akte, Nebenstrafrecht Behörden Gericht Und Registerweg, Opfervertretung Mehrparteien Konflikt Und Interessen, Revision Zahlen Schwellen Und Berechnung: führt durch diese fachlich ver... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `raub-stgb-raub-todesfolge-rechtsbeugung-stgb` | Nutze dies bei Strafrecht Raub 249 Stgb, Strafrecht Raub Mit Todesfolge 251 Stgb, Strafrecht Rechtsbeugung 339 Stgb, Strafrecht Schuldnerbeguenstigung 283d Stgb: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `rechtsquellen-fristennotiz-naechster-schritt` | Nutze dies zur Quellenprüfung bei Rechtsquellen: Fristennotiz und nächster Schritt: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `steuerstrafrecht-ao-akteneinsicht-auswerten` | Nutze dies bei Strafrecht Steuerstrafrecht 371 Ao Selbstanzeige, Akteneinsicht Strafrecht Auswerten, Erstgespraech Mandatsannahme, Fachanwalt Strafrecht Akteneinsicht Beantragen: führt durch diese fachlich verbundenen Module, wählt den p... |
| `stpo-strafrecht-strafverteidigung` | Nutze dies bei Stpo Dokumentenmatrix Und Lueckenliste, Strafrecht Tatbestand Beweis Und Belege, Strafverteidigung Schriftsatz Brief Und Memo Bausteine, Zeugenbeistand Internationaler Bezug Und Schnittstellen: führt durch diese fachlich v... |
| `strafprozess-antragslog-beweisantraege` | Nutze dies bei Strafprozess Antragslog Beweisantraege Und Widerspruch, Strafprozess Biometrischer Internetabgleich 98d Stpo E, Strafprozess Cockpit Taegliche Kanzleifuehrung, Strafprozess Haft Und Besuchsmanagement: führt durch diese fac... |
| `strafprozess-instruktionen` | Nutze dies bei Strafprozess Mandantenkommunikation Und Instruktionen, Strafprozess Pflichtverteidigung Beiordnung Und Wechsel, Strafprozess Sitzungsprotokoll Und Revisionssicherung, Strafprozess Verhandlungslog Sta Gericht Nebenklage: fü... |
| `strafr-dysfunk-befangenheitsantrag` | Nutze dies bei Strafr Dysfunk Befangenheitsantrag Zielgenau, Strafr Dysfunk Beistandsleistung 137 Stpo, Strafr Dysfunk Beweisantrag Fundament, Strafr Dysfunk Beweisantragsstrategie: führt durch diese fachlich verbundenen Module, wählt de... |
| `strafr-dysfunk-darlegungslast-empirie-nutzen` | Nutze dies bei Strafr Dysfunk Darlegungslast Umkehren, Strafr Dysfunk Empirie Nutzen, Strafr Dysfunk Erklaerungsrecht 257 Stpo, Strafr Dysfunk Hinweis Auf Heilbaren Fehler: führt durch diese fachlich verbundenen Module, wählt den passend... |
| `strafr-dysfunk-sitzungspolizei` | Nutze dies bei Strafr Dysfunk Sitzungspolizei Ordnungsmittel, Strafr Dysfunk Verschleppungsabsicht Abgrenzen, Strafr Dysfunk Vorwurf Einordnen, Strafr Dysfunk Wahlverteidigerausschluss 138a: führt durch diese fachlich verbundenen Module,... |
| `strafr-haftpruefung` | Nutze dies bei Allgemein, Strafr Haftpruefung Haftbeschwerde Workflow, Chronologie Und Belegmatrix, Fristen Und Risikoampel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `strafr-vermoegensabschoepfung` | Nutze dies bei Strafr Vermoegensabschoepfung Spezial, Strafr Wirtschaftsstrafrecht Leitfaden, Strafrecht Polizeifilmerei 201 Stgb Kug Verteidigung, Strafrecht 188 Stgb Anklage Und Strafbefehl: führt durch diese fachlich verbundenen Modul... |
| `strafrecht-aussagepsy-suggestion-tuechtigkeit` | Nutze dies bei Strafrecht Aussagepsy Suggestion Falscherinnerung, Strafrecht Aussagepsy Tuechtigkeit Bereitschaft, Strafrecht Aussagepsy Vernehmungsfehler Falschgestand, Strafrecht Aussagepsychologie Bgh Grundsaetze: führt durch diese fa... |
| `strafrecht-betrug-stgb-btmg-grundtatbestand` | Nutze dies bei Strafrecht Betrug 263 Stgb Grundtatbestand, Strafrecht Btmg 29 Grundtatbestand, Strafrecht Btmg 29a Nicht Geringe Menge, Strafrecht Btmg 30 Handeltreiben: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `strafrecht-computerbetrug-263a-design-designg` | Nutze dies bei Strafrecht Computerbetrug 263a Stgb, Strafrecht Design Strafrecht 51 Designg, Strafrecht Erpresserischer Menschenraub 239a 239b Stgb, Strafrecht Faktische Geschaeftsfuehrer: führt durch diese fachlich verbundenen Module, w... |
| `strafrecht-gmbh-verletzung-insiderhandel-wphg` | Nutze dies bei Strafrecht Gmbh Verletzung Anzeigepflicht 84 Gmbhg, Strafrecht Insiderhandel 119 Wphg, Strafrecht Insolvenzverschleppung 15a Inso, Strafrecht Ip Strafrecht Grenzbeschlagnahme: führt durch diese fachlich verbundenen Module,... |
| `strafrecht-markenrecht-143a-marktmanipulation` | Nutze dies bei Strafrecht Markenrecht 143a Markeng Bandenmaessig, Strafrecht Marktmanipulation 120 Wphg, Strafrecht Mietwucher 5 Wistg, Strafrecht Minder Schwerer Fall 213 Stgb: führt durch diese fachlich verbundenen Module, wählt den pa... |
| `strafrecht-stgb-easy-social-media-amtsdelikte` | Nutze dies bei Strafrecht 188 Stgb Easy Verteidigung, Strafrecht 188 Stgb Social Media Beweise, Strafrecht Amtsdelikte 340 Stgb Koerperverletzung Im Amt, Strafrecht Amtstraegerbestechung 332 334 Stgb: führt durch diese fachlich verbunden... |
| `strafrecht-strafprozess-ermittlungsverfahren` | Nutze dies bei Strafprozess Ermittlungsverfahren Sofortmassnahmen, Strafprozess Rechtsmittel Und Notfristencockpit, Strafrecht Btmg Strafverfahren Praxis, Strafrecht Haeusliche Gewalt Im Strafverfahren: führt durch diese fachlich verbund... |
| `strafrecht-untreue-schaden` | Nutze dies bei Strafrecht Untreue Schaden Und Bezifferbarkeit, Strafrecht Verbandssanktionengesetz Stand 2026, Strafprozess Akteneinsicht Nachlieferungen Und Sonderbaende, Strafrecht Steuerstrafrecht 370 Ao Steuerhinterziehung: führt dur... |
| `strafrecht-urheberrecht-urhg-108a-gewerblich` | Nutze dies bei Strafrecht Urheberrecht 108 Urhg Unerlaubte Eingriffe, Strafrecht Urheberrecht 108a Urhg Gewerblich, Strafrecht Urheberrecht 108b Urhg Tpm, Strafrecht Vergewaltigung 177 Stgb: führt durch diese fachlich verbundenen Module,... |
| `subventionsbetrug-stgb-toetung-verlangen` | Nutze dies bei Strafrecht Subventionsbetrug 264 Stgb, Strafrecht Toetung Auf Verlangen 216 Stgb, Strafrecht Totschlag 212 Stgb, Strafrecht Umweltstrafrecht 324 Stgb Gewaesser: führt durch diese fachlich verbundenen Module, wählt den pass... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `versicherungsbetrug-stgb-vorenthalten` | Nutze dies bei Strafrecht Versicherungsbetrug 265 Stgb, Strafrecht Vorenthalten Arbeitgeberanteile 266a Stgb, Strafrecht Vorteilsannahme Gewaehrung 331 333 Stgb, Strafrecht Waffg Strafvorschriften 51 52: führt durch diese fachlich verbun... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
