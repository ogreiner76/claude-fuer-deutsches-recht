# Fluggastrechte

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`fluggastrechte`) | [`fluggastrechte.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/fluggastrechte.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Fluggastrechte – Familie Bräutigam-Zaytuna** (`fluggastrechte-familie-braeutigam`) | [Gesamt-PDF lesen](../testakten/fluggastrechte-familie-braeutigam/gesamt-pdf/fluggastrechte-familie-braeutigam_gesamt.pdf) | [`testakte-fluggastrechte-familie-braeutigam.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-fluggastrechte-familie-braeutigam.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Fluggastrechte selber geltend machen — VO (EG) Nr. 261/2004 plus EuGH-Rspr. Tickets erfassen Annullierung vs Verspätung prüfen außergewöhnliche Umstände Distanz und Ausgleich Forderungsschreiben Mahnung Klage Amtsgericht. Vollmacht Familie. Katalog Airline-Standardausreden.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `airline-standardausreden-pruefen` | Katalog typischer Standardausreden der Fluggesellschaften mit Gegenargumenten und Pinpoint auf EuGH-Rechtsprechung. Behandelt technischer Defekt wilder Streik Streik der Gewerkschaft Crew-Engpass verdeckter Konstrukti… |
| Rechtsprechung live prüfen | Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren. |
| Rechtsprechung live prüfen | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| `ausnahmen-aussergewoehnliche-umstaende-pruefen` | Prüft die Einrede außergewöhnliche Umstände nach Art. 5 Abs. 3 VO 261/2004. Differenziert zwischen Wetter Vulkanasche Vogelschlag Streik Flugsicherung Streik der eigenen Mitarbeiter wilder Streik technischem Defek… |
| `distanz-und-ausgleich-berechnen` | Berechnet die Ausgleichszahlung nach Art. 7 VO 261/2004. Distanzbestimmung nach Großkreisrechnung zwischen Abflug- und Zielflughafen. Drei Stufen 250 EUR bis 1500 km / 400 EUR mehr als 1500 km innergemeinschaftlich o… |
| `forderungsschreiben-erste-stufe` | Erstes Forderungsschreiben an die Airline. Erfasst Anspruchsteller (alle Passagiere mit Vollmachten) Anspruchsgrundlage Art. 7 VO 261/2004 konkrete Berechnung Frist zur Zahlung (typisch zwei Wochen) Bankverbindung. In… |
| `forderungsschreiben-mahnung` | Zweite Stufe nach Ablauf der Frist aus dem ersten Forderungsschreiben oder nach erfolgloser Reaktion der Airline. Setzt Nachfrist (typisch zehn Tage) bezieht sich auf die erste Forderung weist Verzugszinsen aus und dr… |
| `fluggastrechte-kaltstart-interview` | Kaltstart-Interview für das Fluggastrechte-Plugin. Klärt Anwendungsrolle (eigener Fluggastrechte-Anspruch / Vertretung Familie / Mitreisende). Erfasst Buchungsstammdaten Vertragspartner (Airline IATA-Code) und Reise… |
| `klage-amtsgericht-fluggast` | Klageentwurf zum Amtsgericht in Fluggastrechtsangelegenheiten. Sachliche Zuständigkeit § 23 Nr. 1 GVG bei Streitwert bis zehntausend Euro (i. d. F. seit 01.01.2026). Örtlich wahlweise Abflughafen oder Zielflughafen … |
| `ticket-und-fluginformationen-erfassen` | Erfasst die Falldaten aus hochgeladenen Tickets Buchungsbestätigungen Boardingpässe PDF-Scans Foto-Belegen. Extrahiert Buchungscode (PNR) Flugnummer Datum Abflughafen Zielflughafen geplante Abflugzeit geplante Ankun… |
| `vollmacht-familienmitglieder` | Erzeugt Vollmachten für Mitreisende (Familienmitglieder Freunde) damit der Hauptansprechpartner deren Fluggastrechtsanspruch im Schriftverkehr und im gerichtlichen Verfahren mitvertreten kann. Pro Person eigene Vollm… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 69 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `abtretung-an-fluggastportal-spezial` | Abtretung an Fluggastrechte-Portale (Flightright, EUclaim, AirHelp): Wirksamkeit nach RDG seit 2021, Provisionen, Vertragsklauseln gegenueber Mandanten. Eigene Vertretung gegen Portale, Vor- und Nachteile der Direktklage gegenueber Porta... |
| `airline-bonitaet-und-vollstreckung` | Airline-Bonitaetspruefung und Vollstreckung: Risikoliste bekannter Insolvenzen, Hinterlegung in dotierten Reisesicherungsfonds, EU-Garantien, Pruefraster bevor Klage erhoben wird. Vollstreckung im Ausland (Bruessel-I-VO, EuVTVO). Pruefli... |
| `airline-standardausreden-annullierung` | Nutze dies, wenn Airline Standardausreden Prüfen, Annullierung Oder Verspaetung Einordnen, Anschlussflug Und Reiseplan im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.;... |
| `airline-standardausreden-pruefen` | Katalog typischer Standardausreden der Fluggesellschaften mit Gegenargumenten und Pinpoint auf EuGH-Rechtsprechung. Behandelt technischer Defekt wilder Streik Streik der Gewerkschaft Crew-Engpass verdeckter Konstruktionsfehler vorheriger... |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Fluggastrechte-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Spezial-Skills aus diesem Plugin vor und führt in einen klaren Arbeitsplan. Bei... |
| `annullierung` | Nutze dies, wenn Annullierung: Schriftsatz-, Brief- und Memo-Bausteine im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Annullierung: Schriftsatz-, Brief- und Memo-Bausteine prüfen.; Erstelle eine Arbeitsfassung z... |
| `annullierung-oder-verspaetung-einordnen` | Workflow-Skill zu annullierung oder verspaetung einordnen. Nutzt Normtext, Nutzerangaben und verifizierte Quellen; Rechtsprechung nur nach Live-Pruefung mit Gericht, Datum und Aktenzeichen. |
| `anschluss-router` | Nutze dies, wenn Allgemein, Workflow Anschluss Skills Router, Workflow Chronologie Und Belegmatrix im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Anschluss Skills Router, Workflow Chronologie... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Fluggastrechte.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `anschlussflug-und-reiseplan` | Workflow-Skill zu anschlussflug und reiseplan. Nutzt Normtext, Nutzerangaben und verifizierte Quellen; Rechtsprechung nur nach Live-Pruefung mit Gericht, Datum und Aktenzeichen. |
| `ausgleich` | Nutze dies, wenn Ausgleich: Internationaler Bezug und Schnittstellen im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Ausgleich: Internationaler Bezug und Schnittstellen prüfen.; Erstelle eine Arbeitsfassung zu Au... |
| `ausnahmen-aussergewoehnliche-umstaende` | Nutze dies, wenn Ausnahmen Aussergewoehnliche Umstaende Prüfen, Aussergewoehnliche Umstaende Strikt, Distanz Und Ausgleich Berechnen im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Ausnahmen Aussergewoehnliche Um... |
| `ausnahmen-aussergewoehnliche-umstaende-02` | Workflow-Skill zu ausnahmen aussergewoehnliche umstaende pruefen. Nutzt Normtext, Nutzerangaben und verifizierte Quellen; Rechtsprechung nur nach Live-Pruefung mit Gericht, Datum und Aktenzeichen. |
| `aussergewoehnliche` | Nutze dies, wenn Aussergewoehnliche: Zahlen, Schwellenwerte und Berechnung im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Aussergewoehnliche: Zahlen, Schwellenwerte und Berechnung prüfen.; Erstelle eine Arbeitsf... |
| `aussergewoehnliche-distanz-interessen` | Nutze dies, wenn Spezial Aussergewoehnliche Zahlen Schwellen Und Berechnung, Spezial Distanz Mehrparteien Konflikt Und Interessen, Spezial Erfassen Behörden Gericht Und Registerweg im Plugin Fluggastrechte konkret bearbeitet werden soll.... |
| `aussergewoehnliche-umstaende-strikt` | Streng auszulegende aussergewoehnliche Umstaende Art. 5 Abs. 3 VO 261: Wetter, Streik nicht eigener Mitarbeiter, gerichtlich verfuegte Flugverbote, Wildschlag in Triebwerk. Keine aussergewoehnlichen Umstaende: technische Defekte (EuGH Wa... |
| `chronologie-und-belegmatrix` | Nutze dies, wenn Chronologie und Belegmatrix im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Chronologie und Belegmatrix prüfen.; Erstelle eine Arbeitsfassung zu Chronologie und Belegmatrix.; Welche Normen und Na... |
| `distanz-interessen` | Nutze dies, wenn Distanz: Mehrparteienkonflikt und Interessenmatrix im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Distanz: Mehrparteienkonflikt und Interessenmatrix prüfen.; Erstelle eine Arbeitsfassung zu Dist... |
| `distanz-und-ausgleich-berechnen` | Berechnet die Ausgleichszahlung nach Art. 7 VO 261/2004. Distanzbestimmung nach Grosskreisrechnung zwischen Abflug- und Zielflughafen. Drei Stufen 250 EUR bis 1500 km / 400 EUR mehr als 1500 km innergemeinschaftlich oder 1500 bis 3500 km... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Fluggastrechte.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `erfassen` | Nutze dies, wenn Erfassen: Behörden-, Gerichts- oder Registerweg im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Erfassen: Behörden-, Gerichts- oder Registerweg prüfen.; Erstelle eine Arbeitsfassung zu Erfassen:... |
| `flug-anschlussflug-codeshare-anspruch` | Nutze dies, wenn Flug Anschlussflug Codeshare Spezial, Flug Anspruch Uebersicht, Flug Ausserordentlicher Umstand Leitfaden im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Flug Anschlussflug Codeshare Spezial, Flu... |
| `flug-anschlussflug-codeshare-spezial` | Spezialfall Anschlussflug und Codeshare: einheitliche Buchung, ausfuehrendes Luftfahrtunternehmen, Drittland-Strecken nach EuGH wegfin. Pruefraster fuer Klagezustaendigkeit. |
| `flug-anspruch-uebersicht` | Uebersicht Fluggastrechte VO 261 / 2004: Annullierung, grosse Verspaetung ab drei Stunden, Nichtbefoerderung, Pauschalentschaedigung 250 Euro / 400 Euro / 600 Euro je nach Distanz. Pruefraster Anspruchsgrundlage. |
| `flug-ausserordentlicher-umstand-leitfaden` | Leitfaden ausserordentlicher Umstand: EuGH-Kasuistik Streik / Wetter / technischer Defekt, Beweislast Airline, zumutbare Massnahmen. Pruefraster fuer Klaegeranwalt. |
| `flug-massenklage-einfuehrung-vo` | Nutze dies, wenn Flug Massenklage Prozessfinanzierung Spezial, Fluggastrechte Einfuehrung Vo 261, Forderungsschreiben Erste Stufe im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Flug Massenklage Prozessfinanzieru... |
| `flug-massenklage-prozessfinanzierung-spezial` | Spezialfall Massenklage und Prozessfinanzierung in Fluggastrechten: Abtretung, Inkasso-Modelle, RDG-Grenzen, Anti-Claim-Klausel. Pruefraster fuer Verbraucher und Legal-Tech. |
| `fluggastrechte` | Nutze dies, wenn Fluggastrechte: Erstprüfung, Rollenklärung und Mandatsziel im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Fluggastrechte: Erstprüfung, Rollenklärung und Mandatsziel prüfen.; Erstelle eine Arbeit... |
| `fluggastrechte-anlagen-bauen` | Baut aus den Belegen eines Fluggastrechte-Mandats ein beA-konformes Anlagenkonvolut. Verwendet zum bestehenden Schriftsatz (Forderungsschreiben Mahnung Klage) die Belege Buchungsbestätigung Boardingpass Annullierungsbestätigung E-Mail-Ve... |
| `fluggastrechte-einfuehrung-vo-261` | Einfuehrung VO (EG) 261/2004: Anwendungsbereich (Abflug aus EU, Ankunft in EU mit EU-Carrier), Annullierung, Verspaetung ab 3 Stunden (EuGH-Sturgeon), Nichtbefoerderung. Ausgleichsstufen 250 Euro / 400 Euro / 600 Euro. Betreuungsleistung... |
| `fluggastrechte-forderungsschreiben-klage` | Nutze dies, wenn Spezial Fluggastrechte Erstpruefung Und Mandatsziel, Spezial Forderungsschreiben Formular Portal Und Einreichung, Spezial Klage Mandantenkommunikation Entscheidungsvorlage im Plugin Fluggastrechte konkret bearbeitet werd... |
| `fluggastrechte-kaltstart-interview` | Kaltstart-Interview für das Fluggastrechte-Plugin. Klaert Anwendungsrolle (eigener Fluggastrechte-Anspruch / Vertretung Familie / Mitreisende). Erfasst Buchungsstammdaten Vertragspartner (Airline IATA-Code) und Reiseplan-Konvention. Schr... |
| `forderungsschreiben` | Nutze dies, wenn Forderungsschreiben: Formular, Portal und Einreichungslogik im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Forderungsschreiben: Formular, Portal und Einreichungslogik prüfen.; Erstelle eine Arbe... |
| `forderungsschreiben-erste-stufe` | Workflow-Skill zu forderungsschreiben erste stufe. Nutzt Normtext, Nutzerangaben und verifizierte Quellen; Rechtsprechung nur nach Live-Pruefung mit Gericht, Datum und Aktenzeichen. |
| `forderungsschreiben-mahnung` | Zweite Stufe nach Ablauf der Frist aus dem ersten Forderungsschreiben oder nach erfolgloser Reaktion der Airline. Setzt Nachfrist (typisch zehn Tage) bezieht sich auf die erste Forderung weist Verzugszinsen aus und droht konkret SOEP-Sch... |
| `forderungsschreiben-mahnung-klage-amtsgericht` | Nutze dies, wenn Forderungsschreiben Mahnung, Klage Amtsgericht Fluggast, Pauschalreise Statt Flug Prüfen im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Forderungsschreiben Mahnung, Klage Amtsgericht Fluggast, P... |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies, wenn Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation, Workflow Redteam Qualitygate im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welch... |
| `fristen-und-risikoampel` | Nutze dies, wenn Fristen- und Risikoampel im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Fristen- und Risikoampel prüfen.; Erstelle eine Arbeitsfassung zu Fristen- und Risikoampel.; Welche Normen und Nachweise b... |
| `geltend` | Nutze dies, wenn Geltend: Fristen, Form, Zuständigkeit und Rechtsweg im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Geltend: Fristen, Form, Zuständigkeit und Rechtsweg prüfen.; Erstelle eine Arbeitsfassung zu Ge... |
| `kaltstart-abschlussprodukt-und-uebergabe` | Nutze dies, wenn Kaltstart: Abschlussprodukt und Übergabe im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Fluggastrechte.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `klage` | Nutze dies, wenn Klage: Mandantenkommunikation und Entscheidungsvorlage im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Klage: Mandantenkommunikation und Entscheidungsvorlage prüfen.; Erstelle eine Arbeitsfassung... |
| `klage-amtsgericht-fluggast` | Workflow-Skill zu klage amtsgericht fluggast. Nutzt Normtext, Nutzerangaben und verifizierte Quellen; Rechtsprechung nur nach Live-Pruefung mit Gericht, Datum und Aktenzeichen. |
| `live-sonderfall-edge-case` | Nutze dies, wenn Live: Sonderfall und Edge-Case-Prüfung im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Live: Sonderfall und Edge-Case-Prüfung prüfen.; Erstelle eine Arbeitsfassung zu Live: Sonderfall und Edge-Ca... |
| `live-sonderfall-machen-mahnung-red` | Nutze dies, wenn Spezial Live Sonderfall Und Edge Case, Spezial Machen Dokumentenmatrix Und Lueckenliste, Spezial Mahnung Red Team Und Qualitaetskontrolle im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Was kann hier s... |
| `machen` | Nutze dies, wenn Machen: Dokumentenmatrix, Lückenliste und Nachforderung im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `mahnung-fehlerkatalog` | Nutze dies, wenn Mahnung Fehlerkatalog im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `mandantenkommunikation` | Nutze dies, wenn Mandantenkommunikation im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Mandantenkommunikation prüfen.; Erstelle eine Arbeitsfassung zu Mandantenkommunikation.; Welche Normen und Nachweise brauche... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `pauschalreise-statt-flug-pruefen` | Pauschalreise gegen Flug-Einzelbuchung: Reiseveranstalterhaftung nach §§ 651a ff. BGB, Pauschalreise-RL EU 2015 2302. Minderung, Schadensersatz, Ruecktritt. Verhaeltnis zur VO 261 (kumulativ moeglich, Anrechnung nach BGH). Pruefraster ob... |
| `pruefen-quellenkarte` | Nutze dies, wenn Prüfen Quellenkarte im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `rechtsprechung-beweislast-darlegungslast` | Nutze dies, wenn Rechtsprechung: Beweislast, Darlegungslast und Substantiierung im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Rechtsprechung: Beweislast, Darlegungslast und Substantiierung prüfen.; Erstelle ein... |
| `rechtsprechung-beweislast-vorverlegung-flug` | Nutze dies, wenn Spezial Rechtsprechung Beweislast Und Darlegungslast, Vorverlegung Flug Rechtsprechung, Spezial Geltend Fristen Form Und Zustaendigkeit im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Spezial Rec... |
| `rechtsweg-gerichtsstand-annullierung` | Nutze dies, wenn Rechtsweg Und Gerichtsstand Fluggast, Spezial Annullierung Schriftsatz Brief Und Memo Bausteine, Spezial Ausgleich Internationaler Bezug Und Schnittstellen im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöse... |
| `rechtsweg-und-gerichtsstand-fluggast` | Rechtsweg und Gerichtsstand bei Flugverspaetung und Annullierung: Wohnsitz oder Flughafen Klaegerwahl nach EuGH Rehder. Amtsgericht bei bis 5000 Euro Streitwert. Zustaendige Schlichtungsstellen soep. Internationale Fragen Montrealer Uebe... |
| `redteam-qualitygate` | Nutze dies, wenn Red-Team Qualitygate im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `selber` | Nutze dies, wenn Selber: Tatbestandsmerkmale, Beweisfragen und Beleglage im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Selber: Tatbestandsmerkmale, Beweisfragen und Beleglage prüfen.; Erstelle eine Arbeitsfassu... |
| `selber-tickets-umstaende` | Nutze dies, wenn Spezial Selber Tatbestand Beweis Und Belege, Spezial Tickets Risikoampel Und Gegenargumente, Spezial Umstaende Compliance Dokumentation Und Akte im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Sp... |
| `ticket-und-fluginformationen-erfassen` | Erfasst die Falldaten aus hochgeladenen Tickets Buchungsbestätigungen Boardingpaesse PDF-Scans Foto-Belegen. Extrahiert Buchungscode (PNR) Flugnummer Datum Abflughafen Zielflughafen geplante Abflugzeit geplante Ankunftszeit Tarifklasse P... |
| `tickets` | Nutze dies, wenn Tickets: Risikoampel, Gegenargumente und Verteidigungslinien im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Tickets: Risikoampel, Gegenargumente und Verteidigungslinien prüfen.; Erstelle eine Ar... |
| `umstaende` | Nutze dies, wenn Umstaende: Compliance-Dokumentation und Aktenvermerk im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `verifikation-fristennotiz-abtretung-an` | Nutze dies, wenn Spezial Verifikation Fristennotiz Und Naechster Schritt, Abtretung An Fluggastportal Spezial, Airline Bonitaet Und Vollstreckung im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Spezial Verifikati... |
| `verifikation-fristennotiz-naechster-schritt` | Nutze dies, wenn Verifikation: Fristennotiz und nächster Schritt im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Verifikation: Fristennotiz und nächster Schritt prüfen.; Erstelle eine Arbeitsfassung zu Verifikati... |
| `verspaetung` | Nutze dies, wenn Verspaetung: Verhandlung, Vergleich und Eskalation im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Verspaetung: Verhandlung, Vergleich und Eskalation prüfen.; Erstelle eine Arbeitsfassung zu Vers... |
| `verspaetung-ticket-fluginformationen` | Nutze dies, wenn Spezial Verspaetung Verhandlung Vergleich Und Eskalation, Ticket Und Fluginformationen Erfassen, Vollmacht Familienmitglieder im Plugin Fluggastrechte konkret bearbeitet werden soll. Auslöser: Bitte Spezial Verspaetung V... |
| `vollmacht-familienmitglieder` | Erzeugt Vollmachten für Mitreisende (Familienmitglieder Freunde) damit der Hauptansprechpartner deren Fluggastrechtsanspruch im Schriftverkehr und im gerichtlichen Verfahren mitvertreten kann. Pro Person eigene Vollmacht mit Inhalt Bezug... |
| `vorverlegung-flug-rechtsprechung` | Vorverlegung des Fluges um mehr als 1 Stunde gilt als Annullierung nach EuGH C-188/20 Azurair. Pruefraster und Berechnungsbeispiel, wann Ausgleichsanspruch entsteht. Abgrenzung zur Umbuchung ohne Ausgleichsanspruch. Schriftsatzbausteine. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
