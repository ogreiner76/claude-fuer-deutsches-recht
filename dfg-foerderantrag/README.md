# DFG-Förderantrag

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`dfg-foerderantrag`) | [`dfg-foerderantrag.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/dfg-foerderantrag.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

Plugin für die praktische Antragstellung bei der Deutschen Forschungsgemeinschaft: Sachbeihilfe, elan-Formalia, Projektbeschreibung, Finanzplan, Forschungsdaten, Ethik-/KI-Check, Reviewer-Perspektive, Wiedereinreichung und strategische Entscheidung zwischen kleinem schnellen Antrag und großem Prestigeprojekt.

Der Stil ist bewusst nicht bürokratisch. Das Plugin fragt zuerst: Was ist wissenschaftlich stark, was ist realistisch förderbar, was kann schneller entschieden werden und wo ist der große Antrag zwar verführerisch, aber prozessual zäher? Es arbeitet adaptiv: Anfänger bekommen eine geführte Mini-Roadmap; erfahrene Antragsteller bekommen direkt Red-Team, Kürzungsrisiko und Programmstrategie.

## Quellen-Gate

Vor jeder belastbaren Ausgabe aktuelle DFG-Seiten prüfen:

- DFG Sachbeihilfe: themenoffene Einzelförderung, Neuanträge jederzeit, Fortsetzungsanträge spätestens 6 Monate vor Mittelverbrauch.
- DFG Begutachtung: grundsätzlich zwei Gutachten; bei Anträgen bis 200.000 Euro kann ausnahmsweise ein aussagekräftiges externes Gutachten reichen.
- Reinhart-Koselleck-Projekte: 500.000 bis 1,25 Mio. Euro für fünf Jahre in Stufen von 250.000 Euro; nur für herausragende, besonders innovative oder risikobehaftete Projekte, die nicht in normale Verfahren passen.
- DFG-Merkblätter, elan-Vorlagen, fachzuständige Ansprechpersonen und aktuelle Vordruckstände immer live gegen `dfg.de` prüfen.

## Schnellstart

```text
/dfg-foerderantrag:allgemein
```

Der Allgemein-Skill führt in 60 Sekunden durch: Forschungsfrage, Förderprogramm, Summe, Tempo, Zielgruppe der Begutachtung, Vorarbeiten, Risiken, Daten-/Ethikthemen und gewünschtes Ergebnis.

Typische Startpunkte:

| Situation | Start |
| --- | --- |
| "Ich habe nur eine Forschungsidee" | `allgemein` → Mini-Roadmap und Minimalprojekt |
| "Sachbeihilfe oder größer?" | `dfg-foerderstrategie-schnell-oder-gross` |
| "Entwurf liegt vor" | `dfg-reviewer-red-team` → danach Text- und Finanzskills |
| "Ablehnung liegt vor" | `dfg-wiedereinreichung-nach-ablehnung` |

## Skill-Matrix

| Skill | Wofür? |
| --- | --- |
| `allgemein` | Einstieg, Triage, Programmroute und erster Arbeitsplan |
| `dfg-foerderstrategie-schnell-oder-gross` | Entscheidung: kleiner schneller Antrag, normale Sachbeihilfe, Koselleck oder anderes Programm |
| `dfg-sachbeihilfe-elan-formalia` | Sachbeihilfe, elan, Anlagen, Vordrucklogik, formales Gate |
| `dfg-bis-200k-begutachtung-light` | Kleine/mittlere Anträge so bauen, dass sie schnell, klar und begutachtbar sind |
| `dfg-koselleck-500k-125m` | Koselleck-Check: 500.000 bis 1,25 Mio. Euro, Risiko, Profil, Vertrauensvorschuss |
| `dfg-projektbeschreibung-arbeitsprogramm` | Forschungsfrage, Stand der Forschung, Ziele, Arbeitspakete, Meilensteine |
| `dfg-finanzplan-module-personal-geraete` | Personal, Geräte, Reisen, Workshops, Mercator Fellow, Chancengleichheit, Budgetbegründung |
| `dfg-reviewer-red-team` | Gutachterperspektive, Angriffsflächen, Kürzungsrisiken, Ablehnungsgründe |
| `dfg-wiedereinreichung-nach-ablehnung` | Ablehnung auswerten, Gutachten ernst nehmen, Neuaufstellung |
| `dfg-ki-ethik-forschungsdaten` | KI-Nutzung, Vertraulichkeit, Forschungsdatenmanagement, Ethik und Datenschutz |

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 70 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `adaptive` | Nutze dies bei Adaptive: Dokumentenmatrix, Lückenliste und Nachforderung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `allgemein` | Adaptiver Einstieg, Schnelltriage und Fallrouting im DFG-Förderantrag-Plugin. Führt Anfänger mit maximal sechs Fragen, fordert Profis mit Go/No-Go und Reviewer-Risiken, klärt Forschungsfrage, Programmroute, Antragssumme, Tempo, Vorarbeit... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, Dfg Foerderstrategie Schnell Oder Gross: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arb... |
| `anfaenger` | Nutze dies bei Anfaenger: Risikoampel, Gegenargumente und Verteidigungslinien: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `anfaenger-antraege-dfg` | Nutze dies bei Anfaenger Risikoampel Und Gegenargumente, Antraege Zahlen Schwellen Und Berechnung, Dfg Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bel... |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `antraege` | Nutze dies bei Antraege: Zahlen, Schwellenwerte und Berechnung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `chronologie-und-belegmatrix` | Nutze dies bei Chronologie und Belegmatrix: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `dfg` | Nutze dies bei DFG: Erstprüfung, Rollenklärung und Mandatsziel: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `dfg-bis-200k-begutachtung-light` | Kleine und mittlere DFG-Anträge bis 200.000 Euro begutachtungsfreundlich bauen: klare Kernfrage, schlanker Finanzplan, ein Gutachten möglich, schnelle Lesbarkeit, Fortsetzungsfähigkeit. |
| `dfg-eigenanteil-und-grundausstattung` | Eigenanteil und Grundausstattung der Hochschule sauber von DFG-Foerderung abgrenzen: Was muss die Hochschule stellen (Buero, Standardrechner, Sekretariat, Bibliothek), was darf die DFG finanzieren (projektspezifische Geraete, Personal ue... |
| `dfg-eigene-vorarbeiten-darstellen` | Eigene Vorarbeiten in DFG-Antrag richtig darstellen: bisher publizierte Ergebnisse, eigene Methodik-Beitraege, Pilotdaten. Reviewer-Perspektive: Anknuepfungsfaehigkeit pruefen, keine Selbstplagiat-Pruefung. Mustertext fuer 2-Seiten-Kapitel. |
| `dfg-erstantragsteller-besondere-checks` | Erstantragsteller-Spezialcheck: Promotion abgeschlossen, gute eigene Vorarbeit (Publikationen Erst- und Letztautor), Anbindung an erfahrene Person ohne Co-Antragstellung wenn moeglich, Lebenslauf mit Eltern- und Pflegezeiten transparent,... |
| `dfg-finanzplan-module-personal-geraete` | DFG-Finanzplan und Modulbegründung erstellen: Personal, Geräte, Verbrauchsmittel, Reisen, Workshops, Mercator Fellow, Chancengleichheit, Öffentlichkeitsarbeit, Kostenlogik und Kürzungsabwehr. |
| `dfg-foerderstrategie-schnell-oder-gross` | Strategischer DFG-Router: entscheidet zwischen kleiner schneller Sachbeihilfe, normalem Antrag über 200.000 Euro, Koselleck ab 500.000 Euro oder anderem DFG-Programm. Enthält Spatz-in-der-Hand-Logik, Kürzungsrisiko, Begutachtungsdichte u... |
| `dfg-grossgeraete-und-cluster-antrag` | Grossgeraete und Cluster-Geraete in DFG-Antrag: Geraete ab 50.000 Euro mit zusaetzlicher Wirtschaftlichkeit, Auslastungsplan, technische Anschlussbedingungen, Wartungsvertrag, Folgekosten. Eigene Geraetekommission der DFG. Pruefraster fu... |
| `dfg-grundsystem-foerderlinien` | Grundsystem der DFG-Foerderlinien einfuehrend erklaeren: Sachbeihilfe (Einzelantrag), Emmy Noether, Heisenberg, Reinhart Koselleck, SFB, GRK, Forschergruppen, Schwerpunktprogramme. Pro Linie: Zielgruppe, Hoehe, Dauer, Antragsweg, Begutac... |
| `dfg-internationale-kooperation-aufbau` | Internationale Kooperation in DFG-Antrag aufbauen: D-A-CH-Lead-Agency-Verfahren (DACH, SNF, FWF), Bilateral mit DFG-Partnerorganisationen (NSF, JSPS, ISF, NSFC). Kooperationszusagen, Mittelverteilung, Hauptantragsteller, Co-Antragsteller... |
| `dfg-ki-ethik-forschungsdaten` | DFG-Antrag auf KI-Nutzung, Ethik, Datenschutz, Forschungsdatenmanagement und gute wissenschaftliche Praxis prüfen. Behandelt Vertraulichkeit in Begutachtung, Datenmanagementplan, sensible Daten, Open Access und Nachnutzung. |
| `dfg-kollegen-review-organisieren` | Kollegen-Review eines DFG-Antrags strukturiert organisieren: 2 erfahrene Profs aus dem Fach plus 1 Methodik-Kollege, Briefing-Mail, Review-Raster (Originalitaet, Arbeitsprogramm, Finanzplan, Vorarbeiten), 1-Wochen-Frist. Output Vorlage B... |
| `dfg-koselleck-500k-125m` | Reinhart-Koselleck-Projekt prüfen und entwerfen: 500.000 Euro bis 1.250.000 Euro, 5 Jahre, Stufen von 250.000 Euro, außergewöhnliches Profil, positives Risiko, Vertrauensvorschuss, Abgrenzung zur Sachbeihilfe. |
| `dfg-koselleck-500k-praeregistrierung` | Nutze dies bei Dfg Koselleck 500k 125m, Dfg Praeregistrierung Replication Studies, Dfg Projektbeschreibung Arbeitsprogramm: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `dfg-praeregistrierung-replication-studies` | Praeregistrierung und Replikationsstudien im DFG-Antrag: Hypothesen ex ante festlegen, registered reports, OSF-Praeregistrierung, Replikationsplaene als eigenstaendiges Vorhaben. DFG-Statement to scientific integrity. Vorteile fuer Revie... |
| `dfg-projektbeschreibung-arbeitsprogramm` | DFG-Projektbeschreibung und Arbeitsprogramm ausarbeiten: Forschungslücke, Stand der Forschung, Ziele, Hypothesen, Methoden, Arbeitspakete, Meilensteine, Risiken, Forschungsdaten und verwertbare Antragssprache. |
| `dfg-publikationsstrategie-projekt` | Publikationsstrategie fuer das beantragte Projekt: realistische Zahl Publikationen, geplante Zeitschriften mit Impact und Open-Access-Status, DFG-Open-Access-Politik, Praeprints, Datenpublikation. Im Antrag muss Publikationsplan zu Arbei... |
| `dfg-replikationskrise-statistik-spezial` | Spezialfall Statistikabschnitt nach Replikationskrise: a-priori-Power-Analyse, Effektgroessenschaetzung, Vorab-Festlegung Hypothesen, Korrektur fuer multiple Testung, Sensitivitaetsanalysen. Pruefraster fuer Reviewer-Akzeptanz. |
| `dfg-reviewer-red-team` | DFG-Antrag aus Gutachterperspektive red-teamen: Originalität, Machbarkeit, Arbeitsprogramm, Qualifikation, Umfeld, Bias-Risiken, Kürzungsargumente, Ablehnungsrisiken und Verbesserungsplan. |
| `dfg-sachbeihilfe-elan-formalia` | DFG-Sachbeihilfe und elan-Formalia prüfen: Antragsberechtigung, Module, Vordrucke, Anlagen, Seitenlogik, Fachzuordnung, Fortsetzungsantrag, internationale Kooperation, formale Einreichungsreife. |
| `dfg-software-veroeffentlichung-spezial` | Spezialfall Software als Forschungsergebnis: DFG-Hinweise zur Open-Source-Veroeffentlichung, Lizenzwahl (MIT, BSD, Apache-2.0, GPL), Zenodo-DOI, Reproducibility. Pruefraster und Mustertext fuer Software-Sektion im Arbeitsprogramm. |
| `dfg-software-veroeffentlichung-tieforschung` | Nutze dies bei Dfg Software Veroeffentlichung Spezial, Dfg Tieforschung Ethik Pflichten, Dfg Wiedereinreichung Nach Ablehnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbar... |
| `dfg-tieforschung-ethik-pflichten` | Tierversuchsethik-Pflichten in DFG-Antraegen: 3R-Prinzip (Replace, Reduce, Refine), TierSchG, TierSchVersV, Tierversuchsantrag bei der Behoerde parallel zur DFG. DFG-Senatskommission fuer tierexperimentelle Forschung. Ethik-Sektion im An... |
| `dfg-wiedereinreichung-nach-ablehnung` | DFG-Ablehnung, Gutachten und Entscheidung auswerten: tragende Kritik extrahieren, Verteidigungsreflex vermeiden, Wiedereinreichung planen, Antrag umbauen, Anschreiben und Änderungsmatrix erstellen. |
| `dfg-zeitplan-und-meilensteine` | Antragszeitplan vom ersten Skizzen-Entwurf bis zur Einreichung in elan strukturieren: 6 Monate vorher Themenfindung, 4 Monate vorher Literaturrecherche und Arbeitsprogramm, 3 Monate vorher Finanzplan, 6 Wochen vorher Kollegenreview, 2 Wo... |
| `dfg-zwischen-und-abschlussbericht` | Zwischen- und Abschlussbericht systematisch vorbereiten: Berichtsraster der DFG, Soll-Ist-Abgleich Arbeitsprogramm, Publikationen, Personal, Geraete, Mittelabfluss. Abschlussbericht ist gleichzeitig Bewertungsbasis fuer Folgeantrag. Typi... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `eigene-vorarbeiten-erstantragsteller` | Nutze dies bei Dfg Eigene Vorarbeiten Darstellen, Dfg Erstantragsteller Besondere Checks, Dfg Finanzplan Module Personal Geraete: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belast... |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `elan` | Nutze dies bei Elan: Formular, Portal und Einreichungslogik: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `elan-ethik-finanzplan` | Nutze dies bei Elan Formular Portal Und Einreichung, Ethik Abschlussprodukt Und Uebergabe, Finanzplan Mandantenkommunikation Entscheidungsvorlage: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert de... |
| `ethik` | Nutze dies bei Ethik: Abschlussprodukt und Übergabe: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `finanzplan` | Nutze dies bei Finanzplan: Mandantenkommunikation und Entscheidungsvorlage: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `foerderantragssteller` | Nutze dies bei Foerderantragssteller: Tatbestandsmerkmale, Beweisfragen und Beleglage: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `foerderantragssteller-formalia-red-fuehrung` | Nutze dies bei Foerderantragssteller Tatbestand Beweis Und Belege, Formalia Red Team Und Qualitaetskontrolle, Fuehrung Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `foerderstrategie-schnell-grossgeraete-cluster` | Nutze dies bei Dfg Foerderstrategie Schnell Oder Gross, Dfg Grossgeraete Und Cluster Antrag, Dfg Grundsystem Foerderlinien: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `formalia-fehlerkatalog` | Nutze dies als Fehlerbremse bei Formalia Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `forschungsdaten-fristennotiz-naechster` | Nutze dies bei Forschungsdaten: Fristennotiz und nächster Schritt: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `fristen-und-risikoampel` | Nutze dies bei Fristen- und Risikoampel: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `fuehrung` | Nutze dies bei Fuehrung: Schriftsatz-, Brief- und Memo-Bausteine: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `grosse` | Nutze dies bei Grosse: Compliance-Dokumentation und Aktenvermerk: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `grosse-kleine-koselleck-interessen` | Nutze dies bei Grosse Compliance Dokumentation Und Akte, Kleine Verhandlung Vergleich Und Eskalation, Koselleck Mehrparteien Konflikt Und Interessen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `internationale-kooperation-ki-ethik-kollegen` | Nutze dies bei Dfg Internationale Kooperation Aufbau, Dfg Ki Ethik Forschungsdaten, Dfg Kollegen Review Organisieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `kleine` | Nutze dies bei Kleine: Verhandlung, Vergleich und Eskalation: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `koselleck-interessen` | Nutze dies bei Koselleck: Mehrparteienkonflikt und Interessenmatrix: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `mandantenkommunikation` | Nutze dies bei Mandantenkommunikation: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `mandantenkommunikation-redteam-qualitygate` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Forschungsdaten Fristennotiz Und Naechster Schritt: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `profi` | Nutze dies bei Profi: Behörden-, Gerichts- oder Registerweg: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `profi-reviewer-beweislast-strategien` | Nutze dies bei Profi Behörden Gericht Und Registerweg, Reviewer Beweislast Und Darlegungslast, Strategien Internationaler Bezug Und Schnittstellen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert d... |
| `publikationsstrategie-projekt` | Nutze dies bei Dfg Publikationsstrategie Projekt, Dfg Replikationskrise Statistik Spezial, Dfg Sachbeihilfe Elan Formalia: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren A... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `redteam-qualitygate` | Nutze dies als Fehlerbremse bei Red-Team Qualitygate: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `reviewer-beweislast-darlegungslast` | Nutze dies bei Reviewer: Beweislast, Darlegungslast und Substantiierung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `sachbeihilfe` | Nutze dies bei Sachbeihilfe: Fristen, Form, Zuständigkeit und Rechtsweg: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `sachbeihilfe-bis-200k-eigenanteil` | Nutze dies bei Sachbeihilfe Fristen Form Und Zustaendigkeit, Dfg Bis 200k Begutachtung Light, Dfg Eigenanteil Und Grundausstattung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `schnelle-quellenkarte` | Nutze dies zur Quellenprüfung bei Schnelle Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `strategien` | Nutze dies bei Strategien: Internationaler Bezug und Schnittstellen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `team-sonderfall` | Nutze dies bei Team Sonderfall Und Edge Case: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `team-sonderfall-edge-case` | Nutze dies bei Team: Sonderfall und Edge-Case-Prüfung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `zeitplan-meilensteine-zwischen` | Nutze dies bei Dfg Zeitplan Und Meilensteine, Dfg Zwischen Und Abschlussbericht, Adaptive Dokumentenmatrix Und Lueckenliste: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
