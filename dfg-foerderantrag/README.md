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
| `adaptive` | Nutze dies, wenn Adaptive: Dokumentenmatrix, Lückenliste und Nachforderung im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `allgemein` | Adaptiver Einstieg, Schnelltriage und Workflow-Routing im DFG-Förderantrag-Plugin. Führt Anfänger mit maximal sechs Fragen, fordert Profis mit Go/No-Go und Reviewer-Risiken, klärt Forschungsfrage, Programmroute, Antragssumme, Tempo, Vora... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fris... |
| `anfaenger` | Nutze dies, wenn Anfaenger: Risikoampel, Gegenargumente und Verteidigungslinien im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Anfaenger: Risikoampel, Gegenargumente und Verteidigungslinien prüfen.; Erstelle... |
| `anfaenger-antraege-dfg` | Nutze dies, wenn Spezial Anfaenger Risikoampel Und Gegenargumente, Spezial Antraege Zahlen Schwellen Und Berechnung, Spezial Dfg Erstpruefung Und Mandatsziel im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Spe... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Dfg Foerderantrag.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `antraege` | Nutze dies, wenn Antraege: Zahlen, Schwellenwerte und Berechnung im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Antraege: Zahlen, Schwellenwerte und Berechnung prüfen.; Erstelle eine Arbeitsfassung zu Antraeg... |
| `chronologie-und-belegmatrix` | Nutze dies, wenn Chronologie und Belegmatrix im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Chronologie und Belegmatrix prüfen.; Erstelle eine Arbeitsfassung zu Chronologie und Belegmatrix.; Welche Normen und... |
| `dfg` | Nutze dies, wenn DFG: Erstprüfung, Rollenklärung und Mandatsziel im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte DFG: Erstprüfung, Rollenklärung und Mandatsziel prüfen.; Erstelle eine Arbeitsfassung zu DFG: Er... |
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
| `dfg-koselleck-500k-praeregistrierung` | Nutze dies, wenn Dfg Koselleck 500K 125M, Dfg Praeregistrierung Replication Studies, Dfg Projektbeschreibung Arbeitsprogramm im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Dfg Koselleck 500K 125M, Dfg Praereg... |
| `dfg-praeregistrierung-replication-studies` | Praeregistrierung und Replikationsstudien im DFG-Antrag: Hypothesen ex ante festlegen, registered reports, OSF-Praeregistrierung, Replikationsplaene als eigenstaendiges Vorhaben. DFG-Statement to scientific integrity. Vorteile fuer Revie... |
| `dfg-projektbeschreibung-arbeitsprogramm` | DFG-Projektbeschreibung und Arbeitsprogramm ausarbeiten: Forschungslücke, Stand der Forschung, Ziele, Hypothesen, Methoden, Arbeitspakete, Meilensteine, Risiken, Forschungsdaten und verwertbare Antragssprache. |
| `dfg-publikationsstrategie-projekt` | Publikationsstrategie fuer das beantragte Projekt: realistische Zahl Publikationen, geplante Zeitschriften mit Impact und Open-Access-Status, DFG-Open-Access-Politik, Praeprints, Datenpublikation. Im Antrag muss Publikationsplan zu Arbei... |
| `dfg-replikationskrise-statistik-spezial` | Spezialfall Statistikabschnitt nach Replikationskrise: a-priori-Power-Analyse, Effektgroessenschaetzung, Vorab-Festlegung Hypothesen, Korrektur fuer multiple Testung, Sensitivitaetsanalysen. Pruefraster fuer Reviewer-Akzeptanz. |
| `dfg-reviewer-red-team` | DFG-Antrag aus Gutachterperspektive red-teamen: Originalität, Machbarkeit, Arbeitsprogramm, Qualifikation, Umfeld, Bias-Risiken, Kürzungsargumente, Ablehnungsrisiken und Verbesserungsplan. |
| `dfg-sachbeihilfe-elan-formalia` | DFG-Sachbeihilfe und elan-Formalia prüfen: Antragsberechtigung, Module, Vordrucke, Anlagen, Seitenlogik, Fachzuordnung, Fortsetzungsantrag, internationale Kooperation, formale Einreichungsreife. |
| `dfg-software-veroeffentlichung-spezial` | Spezialfall Software als Forschungsergebnis: DFG-Hinweise zur Open-Source-Veroeffentlichung, Lizenzwahl (MIT, BSD, Apache-2.0, GPL), Zenodo-DOI, Reproducibility. Pruefraster und Mustertext fuer Software-Sektion im Arbeitsprogramm. |
| `dfg-software-veroeffentlichung-tieforschung` | Nutze dies, wenn Dfg Software Veroeffentlichung Spezial, Dfg Tieforschung Ethik Pflichten, Dfg Wiedereinreichung Nach Ablehnung im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Dfg Software Veroeffentlichung Sp... |
| `dfg-tieforschung-ethik-pflichten` | Tierversuchsethik-Pflichten in DFG-Antraegen: 3R-Prinzip (Replace, Reduce, Refine), TierSchG, TierSchVersV, Tierversuchsantrag bei der Behoerde parallel zur DFG. DFG-Senatskommission fuer tierexperimentelle Forschung. Ethik-Sektion im An... |
| `dfg-wiedereinreichung-nach-ablehnung` | DFG-Ablehnung, Gutachten und Entscheidung auswerten: tragende Kritik extrahieren, Verteidigungsreflex vermeiden, Wiedereinreichung planen, Antrag umbauen, Anschreiben und Änderungsmatrix erstellen. |
| `dfg-zeitplan-und-meilensteine` | Antragszeitplan vom ersten Skizzen-Entwurf bis zur Einreichung in elan strukturieren: 6 Monate vorher Themenfindung, 4 Monate vorher Literaturrecherche und Arbeitsprogramm, 3 Monate vorher Finanzplan, 6 Wochen vorher Kollegenreview, 2 Wo... |
| `dfg-zwischen-und-abschlussbericht` | Zwischen- und Abschlussbericht systematisch vorbereiten: Berichtsraster der DFG, Soll-Ist-Abgleich Arbeitsprogramm, Publikationen, Personal, Geraete, Mittelabfluss. Abschlussbericht ist gleichzeitig Bewertungsbasis fuer Folgeantrag. Typi... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `eigene-vorarbeiten-erstantragsteller` | Nutze dies, wenn Dfg Eigene Vorarbeiten Darstellen, Dfg Erstantragsteller Besondere Checks, Dfg Finanzplan Module Personal Geraete im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Dfg Eigene Vorarbeiten Darstel... |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Dfg Foerderantrag.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `elan` | Nutze dies, wenn Elan: Formular, Portal und Einreichungslogik im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Elan: Formular, Portal und Einreichungslogik prüfen.; Erstelle eine Arbeitsfassung zu Elan: Formula... |
| `elan-ethik-finanzplan` | Nutze dies, wenn Spezial Elan Formular Portal Und Einreichung, Spezial Ethik Abschlussprodukt Und Übergabe, Spezial Finanzplan Mandantenkommunikation Entscheidungsvorlage im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslös... |
| `ethik` | Nutze dies, wenn Ethik: Abschlussprodukt und Übergabe im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Ethik: Abschlussprodukt und Übergabe prüfen.; Erstelle eine Arbeitsfassung zu Ethik: Abschlussprodukt und Ü... |
| `finanzplan` | Nutze dies, wenn Finanzplan: Mandantenkommunikation und Entscheidungsvorlage im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Finanzplan: Mandantenkommunikation und Entscheidungsvorlage prüfen.; Erstelle eine A... |
| `foerderantragssteller` | Nutze dies, wenn Foerderantragssteller: Tatbestandsmerkmale, Beweisfragen und Beleglage im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Foerderantragssteller: Tatbestandsmerkmale, Beweisfragen und Beleglage pr... |
| `foerderantragssteller-formalia-red-fuehrung` | Nutze dies, wenn Spezial Foerderantragssteller Tatbestand Beweis Und Belege, Spezial Formalia Red Team Und Qualitaetskontrolle, Spezial Fuehrung Schriftsatz Brief Und Memo Bausteine im Plugin Dfg Foerderantrag konkret bearbeitet werden s... |
| `foerderstrategie-schnell-grossgeraete-cluster` | Nutze dies, wenn Dfg Foerderstrategie Schnell Oder Gross, Dfg Grossgeraete Und Cluster Antrag, Dfg Grundsystem Foerderlinien im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Dfg Foerderstrategie Schnell Oder Gr... |
| `formalia-fehlerkatalog` | Nutze dies, wenn Formalia Fehlerkatalog im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `forschungsdaten-fristennotiz-naechster` | Nutze dies, wenn Forschungsdaten: Fristennotiz und nächster Schritt im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Forschungsdaten: Fristennotiz und nächster Schritt prüfen.; Erstelle eine Arbeitsfassung zu F... |
| `fristen-und-risikoampel` | Nutze dies, wenn Fristen- und Risikoampel im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Fristen- und Risikoampel prüfen.; Erstelle eine Arbeitsfassung zu Fristen- und Risikoampel.; Welche Normen und Nachweis... |
| `fuehrung` | Nutze dies, wenn Fuehrung: Schriftsatz-, Brief- und Memo-Bausteine im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Fuehrung: Schriftsatz-, Brief- und Memo-Bausteine prüfen.; Erstelle eine Arbeitsfassung zu Fue... |
| `grosse` | Nutze dies, wenn Grosse: Compliance-Dokumentation und Aktenvermerk im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `grosse-kleine-koselleck-interessen` | Nutze dies, wenn Spezial Grosse Compliance Dokumentation Und Akte, Spezial Kleine Verhandlung Vergleich Und Eskalation, Spezial Koselleck Mehrparteien Konflikt Und Interessen im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Au... |
| `internationale-kooperation-ki-ethik-kollegen` | Nutze dies, wenn Dfg Internationale Kooperation Aufbau, Dfg Ki Ethik Forschungsdaten, Dfg Kollegen Review Organisieren im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Dfg Internationale Kooperation Aufbau, Dfg... |
| `kleine` | Nutze dies, wenn Kleine: Verhandlung, Vergleich und Eskalation im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Kleine: Verhandlung, Vergleich und Eskalation prüfen.; Erstelle eine Arbeitsfassung zu Kleine: Ver... |
| `koselleck-interessen` | Nutze dies, wenn Koselleck: Mehrparteienkonflikt und Interessenmatrix im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Koselleck: Mehrparteienkonflikt und Interessenmatrix prüfen.; Erstelle eine Arbeitsfassung... |
| `mandantenkommunikation` | Nutze dies, wenn Mandantenkommunikation im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Mandantenkommunikation prüfen.; Erstelle eine Arbeitsfassung zu Mandantenkommunikation.; Welche Normen und Nachweise brau... |
| `mandantenkommunikation-redteam-qualitygate` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Forschungsdaten Fristennotiz Und Naechster Schritt im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?;... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `profi` | Nutze dies, wenn Profi: Behörden-, Gerichts- oder Registerweg im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Profi: Behörden-, Gerichts- oder Registerweg prüfen.; Erstelle eine Arbeitsfassung zu Profi: Behörd... |
| `profi-reviewer-beweislast-strategien` | Nutze dies, wenn Spezial Profi Behörden Gericht Und Registerweg, Spezial Reviewer Beweislast Und Darlegungslast, Spezial Strategien Internationaler Bezug Und Schnittstellen im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Ausl... |
| `publikationsstrategie-projekt` | Nutze dies, wenn Dfg Publikationsstrategie Projekt, Dfg Replikationskrise Statistik Spezial, Dfg Sachbeihilfe Elan Formalia im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Dfg Publikationsstrategie Projekt, Df... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `redteam-qualitygate` | Nutze dies, wenn Red-Team Qualitygate im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `reviewer-beweislast-darlegungslast` | Nutze dies, wenn Reviewer: Beweislast, Darlegungslast und Substantiierung im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Reviewer: Beweislast, Darlegungslast und Substantiierung prüfen.; Erstelle eine Arbeits... |
| `sachbeihilfe` | Nutze dies, wenn Sachbeihilfe: Fristen, Form, Zuständigkeit und Rechtsweg im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Sachbeihilfe: Fristen, Form, Zuständigkeit und Rechtsweg prüfen.; Erstelle eine Arbeits... |
| `sachbeihilfe-bis-200k-eigenanteil` | Nutze dies, wenn Spezial Sachbeihilfe Fristen Form Und Zustaendigkeit, Dfg Bis 200K Begutachtung Light, Dfg Eigenanteil Und Grundausstattung im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Spezial Sachbeihilfe... |
| `schnelle-quellenkarte` | Nutze dies, wenn Schnelle Quellenkarte im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `strategien` | Nutze dies, wenn Strategien: Internationaler Bezug und Schnittstellen im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Strategien: Internationaler Bezug und Schnittstellen prüfen.; Erstelle eine Arbeitsfassung... |
| `team-sonderfall` | Nutze dies, wenn Spezial Team Sonderfall Und Edge Case im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Spezial Team Sonderfall Und Edge Case prüfen.; Erstelle eine Arbeitsfassung zu Spezial Team Sonderfall Und... |
| `team-sonderfall-edge-case` | Nutze dies, wenn Team: Sonderfall und Edge-Case-Prüfung im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Team: Sonderfall und Edge-Case-Prüfung prüfen.; Erstelle eine Arbeitsfassung zu Team: Sonderfall und Edge... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `zeitplan-meilensteine-zwischen` | Nutze dies, wenn Dfg Zeitplan Und Meilensteine, Dfg Zwischen Und Abschlussbericht, Spezial Adaptive Dokumentenmatrix Und Lueckenliste im Plugin Dfg Foerderantrag konkret bearbeitet werden soll. Auslöser: Bitte Dfg Zeitplan Und Meilenstei... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
