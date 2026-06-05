# Kriegsdienstverweigerung und Wehrdienst

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`kriegsdienstverweigerung-wehrdienst`) | [`kriegsdienstverweigerung-wehrdienst.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/kriegsdienstverweigerung-wehrdienst.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **KDV-Verfahren Malte Eberhard Rabenow / Berlin-Köln 2026** (`kriegsdienstverweigerung-gewissensantrag-berlin-2026`) | [Gesamt-PDF lesen](../testakten/kriegsdienstverweigerung-gewissensantrag-berlin-2026/gesamt-pdf/kriegsdienstverweigerung-gewissensantrag-berlin-2026_gesamt.pdf) | [`testakte-kriegsdienstverweigerung-gewissensantrag-berlin-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kriegsdienstverweigerung-gewissensantrag-berlin-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Praxisplugin für Kriegsdienstverweigerung aus Gewissensgründen nach Art. 4 Abs. 3 GG und KDVG. Es ist ausdrücklich kein Plugin für Totalverweigerung, Dienstflucht, Befehlsboykott oder politische Leistungsverweigerung. Es behandelt die verfassungsrechtlich loyale Inanspruchnahme eines Grundrechts: Wer nicht gegen sein Gewissen Kriegsdienst mit der Waffe leisten kann, stellt sich nicht außerhalb der Ordnung, sondern beruft sich auf eine ihrer zentralen Gewissensgarantien.

Das Plugin führt von der ersten inneren Klärung über den Antrag beim Bundesamt für das Personalmanagement der Bundeswehr bis zur BAFzA-Entscheidung, Anhörung, Nachreichung, Anerkennung, Ablehnung, Widerspruch, Untätigkeitsklage und Eilrechtsschutz. Es berücksichtigt den Stand 2026 nach dem Wehrdienstmodernisierungsgesetz, insbesondere § 13 KDVG n. F. für ungediente Wehrpflichtige, die vor dem 01.01.2010 geboren wurden.

## Kaltstart

1. **Status klären:** ungedient, wehrpflichtig, vor/nach 01.01.2010 geboren, gemustert, einberufen, Reservist, FWDL, Soldat auf Zeit, Berufssoldat, Soldatin, frühere Soldatin/früherer Soldat?
2. **Ziel klären:** Antrag stellen, Begründung ordnen, Unterlagen vervollständigen, Sachstand erzwingen, Anhörung vorbereiten, Ablehnung angreifen, laufenden Dienstkonflikt entschärfen?
3. **Gewissen klären:** Geht es wirklich um Kriegsdienst mit der Waffe als solcher oder nur um einen bestimmten Krieg, eine politische Lage, Angst, Karriere, Gesundheit oder Totalverweigerung?
4. **Verfahren klären:** Antrag läuft über BAPersBw; BAFzA entscheidet inhaltlich nach Zuleitung. Direkte Übersendung an das BAFzA ist nicht der gesetzliche Standardweg.
5. **Rechtsschutz klären:** Sachstand, Nachreichung, Widerspruch, § 75 VwGO, § 80 VwGO oder § 123 VwGO nur nach Lage und Frist.

## Leitgedanke

Das Plugin soll nicht fertige Gewissensformeln produzieren. Es hilft, eine echte persönliche Entscheidung so zu strukturieren, dass sie rechtlich verständlich wird: Lebensweg, innere Entwicklung, Auslöser, Stabilität, Konsequenzen, Abgrenzung zu bloßer Politik und Plausibilität. Allgemeine Mustersätze sind gefährlich; eine persönliche, wahrhaftige und prüffähige Darstellung ist stärker.

## Typische Outputs

| Situation | Skills | Ergebnis |
| --- | --- | --- |
| Erster Antrag | `kriegsdienstverweigerung-wehrdienst-allgemein`, `status-routing`, `antrag-bapersbw-form`, `gewissensbegruendung-werkstatt` | Antragspaket mit Lebenslauf- und Begründungsplan |
| Antrag liegt, nichts passiert | `eingang-und-pk-nachweis`, `sachstandsanfrage-und-frist`, `untaetigkeitsklage-vwgo-75` | Sachstandsschreiben, Fristenmatrix, Eskalationsplan |
| Soldat oder Soldatin im Dienst | `aktive-soldaten-prioritaet`, `entlassung-berufssoldat-sg-46`, `entlassung-saz-sg-55`, `dienstpflichten-waehrend-verfahren` | Statusstrategie ohne unnötiges Disziplinarrisiko |
| Anhörung oder Zweifel | `schriftliche-anhoerung-kdvg-6`, `muendliche-anhoerung-vorbereitung`, `zweifel-ausraeumen-gesamtvorbringen` | Antwortentwurf, Anhörungsleitfaden, Belegliste |
| Ablehnung | `ablehnungsbescheid-analyse`, `widerspruch-kdvg-9`, `verwaltungsgericht-kdvg-10` | Rechtsbehelfsplan und Klagegerüst |
| 2026-Sonderfall | `wdmodg-2026-uebergang`, `kdvg-13-neun-monate`, `ungedient-vor-2010` | Prüfung der neuen Sonderregeln |

## Keine Totalverweigerung

Dieses Plugin erklärt bei Bedarf die Abgrenzung, unterstützt aber nicht beim bewussten Bruch mit allen Dienst- und Ersatzdienstpflichten. Der Fokus liegt auf der rechtmäßigen, offenen und dokumentierten Berufung auf das Gewissen gegen den Kriegsdienst mit der Waffe.

## Quellenstrategie

- **Amtlich zuerst:** GG, KDVG, WPflG, SG, VwGO, BAFzA-Hinweise, BAPersBw/Bundeswehr-Hinweise.
- **Rechtsprechung verifiziert:** BVerwG und BVerfG nur mit Datum, Aktenzeichen und freiem Link.
- **Aktualität 2026:** Vor Ausgabe immer prüfen, ob Wehrdienstmodernisierung, Bedarfswehrpflicht oder Verwaltungspraxis geändert wurden.
- **Keine Blindzitate:** keine BeckRS-, juris-, Kommentar- oder Aufsatzfundstellen aus Modellwissen.

## Datenschutz und Sicherheit

Gewissensbegründungen, Gesundheitsdaten, Personalakten, Musterungsunterlagen und Soldatenakten sind hochsensibel. In produktiven Verfahren nur in einem dafür freigegebenen, datenschutz- und berufsrechtskonformen System arbeiten.

## Lizenz

Apache-2.0 OR MIT. Siehe Repository-Stammverzeichnis.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 29 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `akteneinsicht-kdv-aktenvernichtung-kdvg` | Akteneinsicht KDV Aktenvernichtung Kdvg im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Routet Akteneinsicht bei BAFzA, BAPersBw und Gericht, Erklärt Aufbewahrung und Löschung von KDV-Akten, Nutzt § 4 KDVG für vorrangige Entsch... |
| `anerkennung-voraussetzungen` | Anerkennung Voraussetzungen im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft Vollständigkeit, geeignete Beweggründe und fehlende Wahrheitszweifel, Erklärt Fortgeltung alter Anerkennungsbescheide und, Unterscheidet Gewissen... |
| `anschreiben-kurz-antrag-bapersbw` | Anschreiben Kurz Antrag Bapersbw im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Erstellt ein kurzes Anschreiben mit Art.-4-Berufung und, Führt durch Adresse, Form, Unterschrift. Liefert priorisierten Output mit Norm-Pinpoints,... |
| `arbeitgeber-fehlzeit-argumente-nicht` | Arbeitgeber Fehlzeit Argumente Nicht im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Kommuniziert Anhörungstermine datensparsam gegenüber, Markiert KDV-schwache Argumente und passende Alternativwege, Erklärt § 3 KDVG, § 11 KDVG... |
| `ausland-aufenthalt-bafza-entscheidungspfad` | Ausland Aufenthalt Bafza Entscheidungspfad im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft Ruhen der Wehrpflicht und Genehmigungspflichten bei, Trennt Registrierung/Zuleitung durch BAPersBw von der, Hält das Plugin anschl... |
| `begruendung-ehemalige-anerkannte-reservisten` | Begruendung Ehemalige Anerkannte Reservisten im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft Widerspruch zwischen alter Anerkennung und späterer, Spezialwerkstatt für Reservisten mit früherem Dienst und, Spezialwerkstatt... |
| `berufliche-folgen-berufssoldaten-kdv-bescheid` | Berufliche Folgen Berufssoldaten KDV Bescheid im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft Arbeitgeber, Ausbildung, Studium und Nachweise außerhalb der Bundeswehr, Prüft KDV-Antrag. Liefert priorisierten Output mit Nor... |
| `bverwg-sanitaetsdienst-innere-umkehr` | Bverwg Sanitaetsdienst Innere Umkehr im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Wendet BVerwG 22.02.2012 - 6 C 31.11/6 C 11.11 an, Wendet BVerwG 03.08.2018 - 6 B 124.18 auf Gediente an, Bereitet persönliche gerichtliche Be... |
| `datenschutz-gewissensakte-dienststelle` | Datenschutz Gewissensakte Dienststelle im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Schützt Gewissensbegründung, Gesundheitsdaten und Personalakten, Formuliert sachliche Dienststellenkommunikation ohne, Warnt vor Disziplinar... |
| `eidesstattliche-versicherung-eilrechtsschutz` | Eidesstattliche Versicherung Eilrechtsschutz im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft, ob eidesstattliche Versicherungen zulässig oder sinnvoll, Prüft § 80 oder § 123 VwGO bei drohendem Dienst an der Waffe, ob Einb... |
| `europa-menschenrechte-familie-partnerschaft` | Europa Menschenrechte Familie Partnerschaft im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Ergänzt EMRK/EU-Grundrechte bei internationalen Bezügen, Trennt externe Erwartungen von der eigenen, Prüft Bescheide auf richtige Recht... |
| `frueherer-abgelehnter-fuehrungszeugnis` | Frueherer Abgelehnter Fuehrungszeugnis im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft Folgen früherer Ablehnung oder Rücknahme für, Erklärt begrenzte Anforderung eines Führungszeugnisses bei, Unterscheidet KDV von einfac... |
| `gewissensentscheidung-massstab-glossar-kdv` | Gewissensentscheidung Massstab Glossar KDV im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft schwere Gewissensnot, unbedingte Bindung und Entscheidung gegen Töten im K, Erklärt Wehrpflicht, Musterung. Liefert priorisierten... |
| `karrierecenter-bapersbw-kdvg-neun-kein` | Karrierecenter Bapersbw Kdvg Neun Kein im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Erklärt Behördennamen, Wehrersatzbehörde und frühere Kreiswehrersatzamt-Begriffe, Nutzt § 13 Abs, Grenzt KDV vom bewussten Bruch mit jeder D... |
| `kommunikation-familie-kosten-auslagen` | Kommunikation Familie Kosten Auslagen im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Erklärt KDV ruhig gegenüber Familie und Umfeld ohne private, Prüft Auslagen, Entgeltfortzahlung und notwendige Aufwendungen bei Anhörung, Prü... |
| `kriegsdienstverweigerung-wehrdienst-kaltstart-triage` | Kaltstart für Kriegsdienstverweigerung aus Gewissensgründen: Status, Verfahrenslage, Gewissenskern, Antragspfad, Fristen, Rechtsschutz und passende Fachmodule auswählen. |
| `minderjaehrige-antragstellung-muendliche` | Minderjaehrige Antragstellung Muendliche im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft Antrag sechs Monate vor 18 oder vor 17 unter, Bereitet nichtöffentliche mündliche Anhörung ohne auswendig, Erklärt Ablehnungsrisiko... |
| `nachreichung-fehlender-unterlagen` | Formuliert fristwahrende Nachreichungen nach behördlicher Aufforderung. |
| `notfallplan-dienstantritt-parteivernehmung` | Notfallplan Dienstantritt Parteivernehmung im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Erstellt 24/48-Stunden-Plan bei kurzfristiger Musterung, Übung oder Dienstantrit, Bereitet persönliche gerichtliche Befragung ehrlich un... |
| `presseanfragen-kdv-psychische-belastung` | Presseanfragen KDV Psychische Belastung im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Hilft bei öffentlicher Kommunikation ohne Verfahrensschaden, Routet Belastungen durch Gewissenskonflikt zu Hilfe ohne, Erzwingt Normstand,... |
| `rechtsprechung-livecheck-dienstpflichten` | Rechtsprechung Livecheck Dienstpflichten im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft KDV-Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und Link, Minimiert Disziplinarrisiken während laufendem KDV-Antrag. Liefert... |
| `rechtsschutzbeduerfnis-religioese` | Rechtsschutzbeduerfnis Religioese im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft Sachbescheidungsinteresse bei ausgesetzter, Ordnet religiöse, humanistische und weltanschauliche Gründe ohne, Prüft KDV bei Beorderung. Lie... |
| `schluesselerlebnis-wandel-schriftliche` | Schluesselerlebnis Wandel Schriftliche im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Unterscheidet einzelne Schlüsselerlebnisse und längere, Beantwortet Zweifel des BAFzA konkret, wahrhaftig und belegbar, Trennt Gewissensents... |
| `soldat-zeit-soldatinnen-kdv-spannungs` | Soldat Zeit Soldatinnen KDV Spannungs im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft KDV, § 55 SG und Nebenfolgen bei Soldaten auf Zeit, Stellt KDV-Rechte von Frauen dar, die dienen oder früher gedient haben. Liefert pri... |
| `status-stellungnahmen-dritter-ungedient-ab` | Status Stellungnahmen Dritter Ungedient AB im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Bestimmt, ob jemand ungedient, wehrpflichtig, Soldat. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `unterlagenmappe-kdv-verwaltungsakt` | Unterlagenmappe KDV Verwaltungsakt im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Strukturiert Antrag, Lebenslauf, Begründung, Belege. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `waffenbesitz-jagd-wahrheitspflicht` | Waffenbesitz Jagd Wahrheitspflicht im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Unterscheidet zivilen Waffenbezug von Kriegsdienst mit der, Entfernt austauschbare KI-/Musterprosa und stärkt eigene, Prüft Ruhen der Wehrpflich... |
| `widerspruch-sonderlagen-ablehnungsbescheid` | Widerspruch Sonderlagen Ablehnungsbescheid im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft normale und verkürzte Widerspruchsfristen, insbesondere § 11 KDVG, Analysiert Tenor, Begründung. Liefert priorisierten Output mit... |
| `zivildienst-altfaelle-ziviler-ersatzdienst` | Zivildienst Altfaelle Ziviler Ersatzdienst im Kriegsdienstverweigerung und Wehrdienst: prüft konkret Prüft Dienstzeit- oder Anerkennungsbescheinigungen aus, Erklärt Ersatzdienst nach Art, Bearbeitet Zweifel aus Gesamtvorbringen und bekan... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
