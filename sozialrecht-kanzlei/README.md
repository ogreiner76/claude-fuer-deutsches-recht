# Sozialrecht-Kanzlei

Vollassistenz fuer die sozialrechtliche Kanzlei: Bescheidanalyse Widerspruch Klage zum Sozialgericht Eilantrag Akteneinsicht Anlagenerstellung. Spezialisiert auf Buergergeld SGB II SGB IX Schwerbehinderung Pflege Hilfsmittel (Rollstuhl Hoerhilfe Vorlesekraft) Eingliederungshilfe SGB VIII Schulbegleitung. Fristenbuch und PKH. Funktioniert allein; empfohlenes Begleitplugin kanzlei-cowork (Skill versand-vor-check fuer Versandkontrolle Fristenbuch Mandantenakte).

## ⬇️ Direkt-Download (einzelnes ZIP)

| Plugin | Direkt-Download |
| --- | --- |
| Sozialrecht-Kanzlei (`sozialrecht-kanzlei`, dieses Plugin) | [sozialrecht-kanzlei.zip](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/sozialrecht-kanzlei.zip) |

Die URL ist stabil und zeigt immer auf die neueste Version. Alle weiteren Plugins sind unter [Releases · latest](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest) genauso einzeln verfügbar.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus „Code → Download ZIP“ verwenden.

## Zum Ausprobieren: Beispielakte (separat)

Fiktive Mandatsakte zum sofortigen Testen — **kein Teil des Plugins**, separater Download:

[testakte-sozialrecht-rollstuhl-tannenberg.zip](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-sozialrecht-rollstuhl-tannenberg.zip)

Fiktive Akte zur Familie Tannenberg in Kiel mit **vier disparaten Sozialrechtsverfahren parallel**: Olaf (Aktivrollator SGB V), Lena (Schulbegleitung SGB VIII), Margarete (Pflegegrad 3 auf 4 SGB XI), Bodo (volle EM-Rente SGB VI). Bescheide, Gutachten, Atteste, Pflegetagebuch (XLSX), Widerspruchsentwürfe, Mandantenbrief in einfacher Sprache, Trainerhandbuch für 1-Tages-Schulung.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `akteneinsicht-anfordern` | Erstellt einen Akteneinsichtsantrag nach § 25 SGB X (Verwaltungsverfahren) bzw. § 120 SGG (gerichtliches Verfahren) Art. 15 DSGVO ergaenzend bei personenbezogenen Daten. Antrag richtet sich an die Verwaltungsbehoerde … |
| `akteneinsicht-auswerten` | Systematische Auswertung der beigezogenen Verwaltungs- oder Gerichtsakte — chronologische Sichtung Identifikation entscheidungserheblicher Aktenstuecke (Antrag Bescheid Widerspruch medizinische Gutachten Sachverstaend… |
| `anlagen-erstellen` | Strukturiert Anlagen zu sozialrechtlichen Schriftsaetzen — Konvention K1 K2 K3 fuer Klage W1 W2 W3 fuer Widerspruch A1 A2 A3 fuer Anlagenkonvolut. Pro Anlage werden erfasst Sigel kurze Bezeichnung Quelle Datum Seitenz… |
| `bescheidanalyse` | Strukturierte Auswertung eines sozialrechtlichen Bescheids — erfasst Behoerde Aktenzeichen Bescheiddatum Zugangsdatum Bescheidart (Ablehnung / teilweise Bewilligung / Aufhebung / Rueckforderung / Sanktion) Tenor Begru… |
| `buergergeld-pruefen` | Prueft Buergergeld-Bescheide nach SGB II — Regelbedarf (§ 20 SGB II) Mehrbedarfe (§ 21 SGB II) Kosten der Unterkunft und Heizung (§ 22 SGB II) Einkommen (§§ 11 ff. SGB II) Vermoegen (§ 12 SGB II inkl Schonvermoegen) B… |
| `eilantrag-sozialrecht` | Eilrechtsschutz nach § 86b SGG — Antrag auf Anordnung der aufschiebenden Wirkung (§ 86b Abs. 1 SGG bei Aufhebungs- und Rueckforderungsbescheiden) oder einstweilige Anordnung (§ 86b Abs. 2 SGG bei Verpflichtungs- und L… |
| `eingliederungshilfe-schule` | Eingliederungshilfe nach SGB IX Teil 2 (§§ 90 ff. SGB IX) Schulbegleitung Integrationshelfer Hilfen zur Schulbildung und Teilhabe an Bildung. Klaert Anspruchsgrundlage (Behinderung iSd § 99 SGB IX iVm § 2 SGB IX) zust… |
| `fristenbuch-sozialrecht` | Fristenbuch fuer sozialrechtliche Verfahren — pflegt zentrale Datei mit Hauptfristen und Vorfristen. Standardfristen SGG (§ 84 Widerspruch ein Monat / § 87 Klage ein Monat / § 173 Beschwerde ein Monat) SGB X (§ 84 Unt… |
| `hilfsmittelantrag-pruefen` | Prueft die rechtliche Anspruchsgrundlage fuer ein Hilfsmittel (Rollstuhl Hoerhilfe Brille Inkontinenzversorgung Prothese Pflegebett Treppenlift) im SGB V (gesetzliche Krankenversicherung) SGB IX (Teilhabe) SGB XI (Pfl… |
| `sozialrecht-kanzlei-kaltstart-interview` | Kaltstart-Interview fuer die sozialrechtliche Kanzlei. Erfragt Schwerpunktbereiche (Buergergeld SGB II / SGB IX Schwerbehinderung / SGB V Krankenversicherung / SGB XI Pflege / Asylbewerberleistungsgesetz) zustaendige … |
| `klage-sozialgericht` | Entwurf einer Klage zum Sozialgericht nach §§ 87 ff. SGG. Klagefrist ein Monat nach Zustellung des Widerspruchsbescheids (§ 87 Abs. 1 SGG; bei fehlender Rechtsbehelfsbelehrung ein Jahr § 66 Abs. 2 SGG). Sachliche Zust… |
| `mandanten-intake` | Strukturierter Erst-Intake in einer sozialrechtlichen Kanzlei. Erfasst Mandantenstammdaten Geburtsdatum Versichertennummer aktuell zustaendige Behoerden bisheriger Verfahrensstand laufende Fristen Bevollmaechtigungssi… |
| `prozesskostenhilfe-antrag` | Erstellt einen Prozesskostenhilfe-Antrag fuer sozialgerichtliche Verfahren nach § 73a SGG iVm §§ 114 ff. ZPO. Pflichtbelege Erklaerung ueber die persoenlichen und wirtschaftlichen Verhaeltnisse (Formular ZP1a) Nachwei… |
| `mandat-triage-sozialrecht` | Routet eingehende Mandate zu den richtigen Folge-Skills nach Sachgebiet und Sofort-Frist. |
| `mandantenbrief-leichte-sprache` | Mandantenbrief in drei Stufen B1 / A2 / Leichte Sprache nach DIN SPEC 33429. |
| `pflegegrad-widerspruch` | Widerspruch gegen Pflegegrad-Bescheide nach SGB XI — sechs Module Bewertung MD-Begutachtung Pflegetagebuch. |
| `pkh-erfolgsaussicht-pruefen` | Vorab-Pruefraster fuer PKH-Erfolgsaussicht §§ 73a SGG iVm 114 ZPO Mutwilligkeit. |
| `schulung-fallbesprechung` | Trainerleitfaden fuer Schulung Inhouse Fortbildung Pruefungs-AG mit fuenf Stationen. |
| `schwerbehindertenausweis-gdb` | GdB- und Merkzeichen-Bescheide nach VersMedV aG G B Bl Gl H RF TBl. |
| `sozialrecht-fallaufnahme-routing` | Master-Entscheidungsbaum: in drei Schritten zur richtigen Skill-Reihenfolge. |
| `sozialrecht-kanzlei-kaltstart-interview` | Kaltstart-Interview fuer die Kanzlei-Profilierung schreibt CLAUDE.md. |
| `widerspruch-formulieren` | Entwirft einen begruendeten Widerspruch gegen einen Sozialleistungsbescheid nach § 84 SGG (Widerspruchsfrist ein Monat ab Bekanntgabe — bei fehlender Rechtsbehelfsbelehrung ein Jahr nach § 66 Abs. 2 SGG). Aus der Besc… |
| `widerspruchsfrist-und-zustellung-sgb` | Pruefraster Bekanntgabe Zustellung Drei-Tages-Fiktion Wiedereinsetzung Untaetigkeitsklage. |
| `bescheid-frist-quick-check` | 60-Sekunden-Sofortpruefung der Frist eines Bescheids mit Ampel rot/gelb/gruen. |
| `erwerbsminderungsrente-pruefen` | DRV-Bescheid pruefen voll vs teilweise EM Wartezeit Arbeitsmarktrente sozialmedizinisches Gutachten. |
| `eingliederungshilfe-schule` | Eingliederungshilfe SGB IX Teil 2 §§ 90 ff Schulbegleitung Integrationshelfer. |
| `eilantrag-sozialrecht` | Eilrechtsschutz § 86b SGG Anordnungsanspruch Anordnungsgrund Glaubhaftmachung. |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Alle Aussagen beruhen auf der im Plugin hinterlegten Rechtsprechung und genannter Kommentarliteratur. Die Skills ersetzen keine eigene anwaltliche, steuerberatende oder berufsbetreuerische Prüfung im Einzelfall.
