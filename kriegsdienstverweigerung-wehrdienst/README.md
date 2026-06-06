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

Automatisch generierte Komplett-Liste aller 133 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `ablehnungsbescheid-analyse` | Analysiert Tenor, Begründung, Rechtsbehelfsbelehrung und Fehler eines Ablehnungsbescheids: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `ablehnungsgruende-kdvg-7` | Zerlegt Ablehnungen wegen Musterungsverweigerung, Unvollständigkeit, ungeeigneter Gründe oder Zweifel: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `adressat-und-versandwege` | Prüft Post, Fax, E-Mail, Unterschrift und Zugangsnachweis: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `akte-fuer-gericht-aufbauen` | Ordnet Tatsachen, Gewissen, Belege und Verfahrensfehler gerichtsfest: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `akteneinsicht-kdv-aktenvernichtung-kdvg` | Routet Akteneinsicht bei BAFzA, BAPersBw und Gericht: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `aktive-soldaten-prioritaet` | Nutzt § 4 KDVG für vorrangige Entscheidung bei laufendem Dienst: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `aktuelle-lage-2026` | Prüft keine aktive Einberufung, fortbestehendes KDV-Recht und WDModG-Änderungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anerkennung-und-dienstfolgen` | Ordnet Folgen der Anerkennung für Wehrpflichtige, Soldaten und Reservisten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anerkennung-voraussetzungen` | Prüft Vollständigkeit, geeignete Beweggründe und fehlende Wahrheitszweifel: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anerkennungsbescheid-gueltigkeit` | Erklärt Fortgeltung alter Anerkennungsbescheide und Nachweisstrategien: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `angst-karriere-gesundheit-abgrenzen` | Unterscheidet Gewissensgründe von Angst, Karriere, Familienlage und Tauglichkeitsfragen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anhoerungsprotokoll-und-korrektur` | Prüft Protokoll der Anhörung auf Missverständnisse und Ergänzungsbedarf: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anlagenverzeichnis-kdv` | Erstellt ein nachvollziehbares Anlagenverzeichnis für den KDV-Antrag: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anschreiben-kurz-antrag-bapersbw` | Erstellt ein kurzes Anschreiben mit Art.-4-Berufung und Anlagenliste: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `antrag-bapersbw-form` | Führt durch Adresse, Form, Unterschrift, Lebenslauf und persönliche Begründung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `antrag-zur-niederschrift` | Erklärt Antragstellung zur Niederschrift beim BAPersBw: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anwaltlicher-brief-bafza` | Formuliert Schreiben im inhaltlichen Anerkennungsverfahren: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `anwaltlicher-brief-bapersbw` | Formuliert Schreiben zu Eingang, Weiterleitung, Musterung und §13: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `arbeitgeber-fehlzeit-argumente-nicht` | Kommuniziert Anhörungstermine datensparsam gegenüber Arbeitgebern: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `argumente-die-nicht-tragen` | Markiert KDV-schwache Argumente und passende Alternativwege: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `aufschiebende-wirkung-kdvg-3` | Erklärt § 3 KDVG, § 11 KDVG und die Sonderwirkung des § 13 Abs. 3: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `ausbildungskosten-rueckforderung` | Prüft mögliche Rückforderungen und Härteargumente nach KDV-bezogenem Ausscheiden: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `auslaendischer-wehrdienst-und-asyl` | Trennt deutsche KDV von Asyl-, Auslieferungs- und ausländischem Wehrrecht: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `ausland-aufenthalt-bafza-entscheidungspfad` | Prüft Ruhen der Wehrpflicht und Genehmigungspflichten bei Auslandsaufenthalten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `bafza-entscheidungspfad` | Trennt Registrierung/Zuleitung durch BAPersBw von der inhaltlichen Entscheidung des BAFzA: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `bedarfswehrpflicht-wpflg-2a` | Hält das Plugin anschlussfähig an aktivierte Bedarfswehrpflicht: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `befehl-und-gewissenskonflikt` | Routet akute Befehlsgewissenskonflikte neben dem KDV-Verfahren: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `begruendung-ehemalige-anerkannte-reservisten` | Prüft Widerspruch zwischen alter Anerkennung und späterer Bundeswehrnähe: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `begruendung-fuer-aktive-soldaten` | Spezialwerkstatt für aktive Soldaten mit früherer Dienstbereitschaft: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `begruendung-fuer-reservisten` | Spezialwerkstatt für Reservisten mit früherem Dienst und aktueller Heranziehungsnähe: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `begruendung-fuer-ungediente` | Spezialwerkstatt für ungediente Antragsteller ohne Umkehrproblem: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `begruendung-redaktion-ohne-schablone` | Überarbeitet persönliche Begründung sprachlich, ohne sie zu standardisieren: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `beistand-kirchen-beratung` | Ordnet Beistand, kirchliche Beauftragte und anwaltliche Vertretung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `berufliche-folgen-berufssoldaten-kdv-bescheid` | Prüft Arbeitgeber, Ausbildung, Studium und Nachweise außerhalb der Bundeswehr: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `berufssoldaten-kdv` | Prüft KDV-Antrag, Entlassungsfolge und Statusrisiken bei Berufssoldaten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `bescheid-archivieren` | Erstellt Nachweis- und Archivstrategie für Anerkennungsbescheide: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `beweislast-und-ueberzeugungsbildung` | Erklärt hohe Wahrscheinlichkeit und gerichtliche Überzeugungsbildung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `bverwg-2005-pfaff-befehl` | Ordnet BVerwG 2 WD 12.04 als konkreten Gewissenskonflikt ein: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `bverwg-2018-innere-umkehr` | Wendet BVerwG 03.08.2018 - 6 B 124.18 auf Gediente an: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `bverwg-2021-parteivernehmung` | Bereitet persönliche gerichtliche Befragung nach BVerwG 31.03.2021 vor: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `bverwg-sanitaetsdienst-innere-umkehr` | Wendet BVerwG 22.02.2012 - 6 C 31.11/6 C 11.11 an: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `checkliste-nach-antrag` | Ordnet Eingangsnachweis, Aktenlog, Sachstand und Fristen nach Antragstellung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `checkliste-vor-antrag` | Letztes Qualitätsgate vor Absendung des KDV-Antrags: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `datenschutz-gewissensakte-dienststelle` | Schützt Gewissensbegründung, Gesundheitsdaten und Personalakten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `dienstpflichten-waehrend-verfahren` | Minimiert Disziplinarrisiken während laufendem KDV-Antrag: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `dienststelle-kommunikation` | Formuliert sachliche Dienststellenkommunikation ohne Provokation: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `disziplinarrisiken-soldaten` | Warnt vor Disziplinar- und Strafrisiken bei eigenmächtigem Verhalten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `disziplinarvorgesetzter-stellungnahme` | Erklärt Stellungnahme der Disziplinarvorgesetzten bei Berufs- und Zeitsoldaten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `doppelte-staatsangehoerigkeit` | Routet deutsche KDV und ausländische Wehrpflichten ohne falsche Auslandsversprechen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `eidesstattliche-versicherung-eilrechtsschutz` | Prüft, ob eidesstattliche Versicherungen zulässig oder sinnvoll sind: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `eilrechtsschutz-drohende-einberufung` | Prüft § 80 oder § 123 VwGO bei drohendem Dienst an der Waffe: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `einberufung-nach-antrag` | Prüft, ob Einberufung trotz KDV-Antrag zulässig sein kann: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `eingang-und-pk-nachweis` | Sichert Zugang, Aktenzeichen und Fristbeginn für spätere Rechtsschutzschritte: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `einstweilige-anordnung-vwgo-123` | Prüft vorläufige Regelung ohne passenden §80-Fall: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `europa-menschenrechte-familie-partnerschaft` | Ergänzt EMRK/EU-Grundrechte bei internationalen Bezügen vorsichtig: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `familie-partnerschaft-gesellschaftsdruck` | Trennt externe Erwartungen von der eigenen Gewissensentscheidung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `fehlende-rechtsschutzbelehrung` | Prüft Bescheide auf richtige Rechtsbehelfsbelehrung und Fristfolgen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `formularmythen-social-media` | Entlarvt falsche Tipps zu Adresse, Mustern, Fristen und angeblichen Automatismen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `frist-bei-nachforderung-ein-monat` | Prüft Monatsfrist zur Vervollständigung nach § 7 KDVG: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `fristenkalender-kdv` | Erstellt Fristenkalender für Antrag, Nachreichung, Anhörung, Widerspruch, § 75 und § 13: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `fruehere-soldaten-und-erneute-heranziehung` | Prüft Rechtsschutzinteresse früherer Soldaten wegen möglicher erneuter Heranziehung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `frueherer-abgelehnter-fuehrungszeugnis` | Prüft Folgen früherer Ablehnung oder Rücknahme für Schutzwirkung und Glaubhaftigkeit: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `fuehrungszeugnis-zweifel` | Erklärt begrenzte Anforderung eines Führungszeugnisses bei Zweifeln: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `fwdl-probezeit-und-kdv` | Unterscheidet KDV von einfacher Beendigung des freiwilligen Wehrdienstes: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gesetzliche-vertreter-rechtsbehelfe` | Erklärt Rechte gesetzlicher Vertreter im Widerspruchs- und Gerichtsverfahren: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gewissensbegruendung-werkstatt` | Strukturiert Lebensweg, Auslöser, Wandel und heutige Unbedingtheit ohne fremde Mustersätze: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gewissensentscheidung-massstab-glossar-kdv` | Prüft schwere Gewissensnot, unbedingte Bindung und Entscheidung gegen Töten im Krieg: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `glossar-kdv` | Erklärt Wehrpflicht, Musterung, Anerkennung, Ersatzdienst, BAPersBw und BAFzA: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundrecht-art-4-abs-3` | Rahmt KDV als staatstreue Grundrechtsausübung statt Staatsablehnung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `humanistische-pazifistische-gruende` | Formt säkulare Ethik in eine persönliche KDV-Begründung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `innere-umkehr-gediente` | Erarbeitet bei Gedienten den grundlegenden Wandel seit früherer Dienstbereitschaft: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `karrierecenter-bapersbw-kdvg-neun-kein` | Erklärt Behördennamen, Wehrersatzbehörde und frühere Kreiswehrersatzamt-Begriffe: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `kdvg-13-neun-monate` | Nutzt § 13 Abs. 2 KDVG als Argument gegen unbegrenztes Liegenlassen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `kein-totalverweigerungs-tool` | Grenzt KDV vom bewussten Bruch mit jeder Dienst- oder Ersatzdienstpflicht ab: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `ki-nutzung-gewissensbegruendung` | Setzt Grenzen für KI-Hilfe: strukturieren ja, fremde Begründung nein: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `klage-ohne-berufung` | Erklärt § 10 KDVG und warum erstinstanzliche Sorgfalt besonders wichtig ist: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `kommunikation-familie-kosten-auslagen` | Erklärt KDV ruhig gegenüber Familie und Umfeld ohne private Überoffenbarung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `kosten-und-auslagen-anhoerung` | Prüft Auslagen, Entgeltfortzahlung und notwendige Aufwendungen bei Anhörung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `kriegsdienstverweigerung-wehrdienst-kaltstart-triage` | Kaltstart für Kriegsdienstverweigerung aus Gewissensgründen: Status, Verfahrenslage, Gewissenskern, Antragspfad, Fristen, Rechtsschutz und passende Fachmodule auswählen. |
| `lebensfuehrung-und-plausibilitaet` | Prüft, welche Lebensstationen die Gewissensentscheidung stützen oder erklären: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `lebenslauf-luecken-und-widersprueche` | Bearbeitet frühere Waffenaffinität, Bundeswehrbewerbung oder Lebenslauflücken ehrlich: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `mehrsprachige-orientierung` | Hilft Nicht-Muttersprachlern mit deutschen KDV-Begriffen ohne falsche Übersetzungssicherheit: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `minderjaehrige-antragstellung-muendliche` | Prüft Antrag sechs Monate vor 18 oder vor 17 unter Sondervoraussetzungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `muendliche-anhoerung-vorbereitung` | Bereitet nichtöffentliche mündliche Anhörung ohne auswendig gelernte Musterantworten vor: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `musterung-verweigert-ablehnung` | Erklärt Ablehnungsrisiko bei Musterungsverweigerung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `musterungen-und-eignung` | Erklärt, warum KDV-Antrag Musterung grundsätzlich nicht ersetzt und wie § 13 wirkt: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `musterungsbescheid-bestandskraft` | Prüft Bedeutung des Musterungsbescheids für Zuleitung und Entscheidung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `nachreichung-fehlender-unterlagen` | Formuliert fristwahrende Nachreichungen nach behördlicher Aufforderung. |
| `notfallplan-dienstantritt-parteivernehmung` | Erstellt 24/48-Stunden-Plan bei kurzfristiger Musterung, Übung oder Dienstantritt: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `parteivernehmung-vorbereiten` | Bereitet persönliche gerichtliche Befragung ehrlich und konsistent vor: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `personalakte-und-datenschutz-soldaten` | Prüft Personalaktenzuleitung und Datenschutz bei Soldaten-KDV: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `personenkennziffer-und-grundakte` | Erklärt Registrierung, PK, Grundakte und Zuleitung im BAPersBw-Verfahren: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `politische-motive-abgrenzen` | Trennt allgemeine Gewissensentscheidung von Kritik an einem bestimmten Krieg oder Staat: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `presseanfragen-kdv-psychische-belastung` | Hilft bei öffentlicher Kommunikation ohne Verfahrensschaden: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `psychische-belastung-und-beratung` | Routet Belastungen durch Gewissenskonflikt zu Hilfe ohne Pathologisierung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `qualitaetsgate-vor-ausgabe` | Erzwingt Normstand, Behördenstand, Statusprüfung, Quellenhygiene und Abgrenzung zur Totalverweigerung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `recht-auf-entscheidung-mein-gewissen-schlaeft-nicht` | Formuliert grundrechtsbewusst, warum eine ernste Gewissensentscheidung nicht beliebig liegen bleiben darf: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `rechtsanwaltliche-vollmacht` | Erstellt Vollmacht, Akteneinsicht und Zustellungsbitte: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `rechtsprechung-livecheck-dienstpflichten` | Prüft KDV-Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und Link: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `rechtsschutzbeduerfnis-religioese` | Prüft Sachbescheidungsinteresse bei ausgesetzter Wehrpflicht und Soldatenstatus: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `religioese-weltanschauliche-gruende` | Ordnet religiöse, humanistische und weltanschauliche Gründe ohne Bekenntniszwang: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `reservisten-heranziehung` | Prüft KDV bei Beorderung, Heranziehungsbescheid und Übungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `ruecknahme-oder-verzicht` | Erklärt Rücknahme eines Antrags oder Verzicht auf Anerkennung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `sachstandsanfrage-und-frist` | Formuliert gezielte Sachstandsanfragen vor Eskalation in § 75 VwGO: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `sanitaetsdienst-und-waffenloser-dienst` | Setzt BVerwG 2012 zu Sanitätsdienst und waffenlosem Dienst um: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `schluesselerlebnis-wandel-schriftliche` | Unterscheidet einzelne Schlüsselerlebnisse und längere innere Wandelungsprozesse: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `schriftliche-anhoerung-kdvg-6` | Beantwortet Zweifel des BAFzA konkret, wahrhaftig und belegbar: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `sicherheitsueberpruefung-und-extremismus` | Trennt Gewissensentscheidung von Loyalitäts- oder Extremismusvorwürfen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `social-media-und-oeffentlichkeit` | Prüft Posts, öffentliche Kampagnen und Dienstgeheimnisse im KDV-Kontext: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `sofortvollzug-und-anordnung` | Prüft Sofortvollzug und aufschiebende Wirkung im KDV-Kontext: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `soldat-zeit-soldatinnen-kdv-spannungs` | Prüft KDV, § 55 SG und Nebenfolgen bei Soldaten auf Zeit: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `soldatinnen-und-kdv` | Stellt KDV-Rechte von Frauen dar, die dienen oder früher gedient haben: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `spannungs-verteidigungsfall` | Prüft Sonderregeln im Spannungs-, Verteidigungs- und Bereitschaftsdienstfall: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `sprache-der-loyalitaet` | Formuliert staatstreu und grundgesetznah ohne Unterwürfigkeit: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `sprachlich-einfache-erklaerung` | Erklärt KDV in einfacher Sprache für Menschen ohne Juristensprache: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `status-stellungnahmen-dritter-ungedient-ab` | Bestimmt, ob jemand ungedient, wehrpflichtig, Soldat, Reservist, frühere Soldatin oder Sonderfall ist: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `stellungnahmen-dritter` | Prüft, wann Wahrnehmungen Dritter nach § 2 Abs. 3 KDVG helfen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `ungedient-ab-2010` | Prüft jüngere ungediente Personen, Antragstermin und fehlendes aktuelles Bescheidungsinteresse: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `ungedient-vor-2010` | Wendet § 13 KDVG n. F. auf vor 2010 geborene ungediente Wehrpflichtige an: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `unterlagenmappe-kdv-verwaltungsakt` | Strukturiert Antrag, Lebenslauf, Begründung, Belege, Nachweise und Bescheide: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verwaltungsakt-oder-informelles-schreiben` | Unterscheidet Bescheid, Aufforderung, Sachstand und informelle E-Mail: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `vollstaendiger-lebenslauf` | Erstellt einen vollständigen, datensparsamen Lebenslauf mit gewissensrelevanten Stationen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `vollstaendigkeit-kdvg-2` | Prüft Anschreiben, Art.-4-Berufung, Lebenslauf und persönliche Begründung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `waffenbesitz-jagd-wahrheitspflicht` | Unterscheidet zivilen Waffenbezug von Kriegsdienst mit der Waffe: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `wahrheitspflicht-und-authentizitaet` | Entfernt austauschbare KI-/Musterprosa und stärkt eigene Sprache: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `wehrpflicht-ruht-ausland` | Prüft Ruhen der Wehrpflicht bei ständiger Lebensgrundlage im Ausland: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `widerspruch-kdvg-9` | Erstellt Widerspruch gegen Ablehnung oder verfahrensrelevante Entscheidung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `widerspruch-sonderlagen-ablehnungsbescheid` | Prüft normale und verkürzte Widerspruchsfristen, insbesondere § 11 KDVG: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `zeugenauswahl-und-aussage` | Prüft geeignete Zeugen für persönliche Entwicklung und Lebensführung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `zivildienst-altfaelle-ziviler-ersatzdienst` | Prüft Dienstzeit- oder Anerkennungsbescheinigungen aus früherem Zivildienst: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `ziviler-ersatzdienst-art-12a` | Erklärt Ersatzdienst nach Art. 12a GG und § 1 Abs. 2 KDVG: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `zweifel-ausraeumen-gesamtvorbringen` | Bearbeitet Zweifel aus Gesamtvorbringen und bekannten Tatsachen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `zweitbescheid-bescheinigung` | Formuliert Antrag auf Bestätigung oder Zweitausfertigung einer früheren Anerkennung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
