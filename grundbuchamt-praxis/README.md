# Grundbuchamt Praxis

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`grundbuchamt-praxis`) | [`grundbuchamt-praxis.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/grundbuchamt-praxis.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Haus Altenau - verlorener Grundschuldbrief, Wegerecht und Kaufpreisfälligkeit** (`grundbuchamt-briefgrundschuld-wegerecht-altenau-2026`) | [Gesamt-PDF lesen](../testakten/grundbuchamt-briefgrundschuld-wegerecht-altenau-2026/gesamt-pdf/grundbuchamt-briefgrundschuld-wegerecht-altenau-2026_gesamt.pdf) | [`testakte-grundbuchamt-briefgrundschuld-wegerecht-altenau-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-grundbuchamt-briefgrundschuld-wegerecht-altenau-2026.zip) |
| **Akte Wusterhagen: Mühlenstau, Chaussee und Aufopferung** (`preussisches-landrecht-wusterhagen-muehlenstau-aufopferung`) | [Gesamt-PDF lesen](../testakten/preussisches-landrecht-wusterhagen-muehlenstau-aufopferung/gesamt-pdf/preussisches-landrecht-wusterhagen-muehlenstau-aufopferung_gesamt.pdf) | [`testakte-preussisches-landrecht-wusterhagen-muehlenstau-aufopferung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-preussisches-landrecht-wusterhagen-muehlenstau-aufopferung.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein Grundbuch-Cockpit für alle, die Auszüge lesen, Urkunden grundbuchtauglich nachweisen, Zwischenverfügungen verstehen und Grundbuchvollzug sauber betreiben müssen. Schwerpunkt ist die praktische Leseführung durch Abteilung I, II und III, damit keine Dienstbarkeit, Vormerkung, Rangstelle oder Briefgrundschuld übersehen wird.

## Wofür dieses Plugin da ist

Dieses Plugin ist ein Praxiswerkzeug. Es fragt zuerst die Lage ab, baut dann eine Dokumenten- und Vollzugsmatrix und erzeugt schließlich das konkrete Arbeitsprodukt: Nachreichung, Beanstandungsantwort, Beschwerdegerüst, Mandantenbrief, Checkliste, Fristenlog oder Vertrags-/Urkundenreview. Es ersetzt keine Berufsträgerentscheidung, aber es verhindert, dass ein formeller Nachweis, ein Rang, eine Abteilung-II-Belastung oder eine Registerfolge in der Hektik untergeht.

## Kaltstart

Starte mit dem allgemeinen Skill `grundbuchamt-allgemeiner-kaltstart`. Lade danach möglichst den aktuellen Register- oder Grundbuchauszug, das Gerichtsschreiben, die Anmeldung/Bewilligung, den Vertragsentwurf und vorhandene Anlagen hoch. Das Plugin sortiert erst, dann prüft es.

## Quellen- und Halluzinationsschutz

- Normen werden als Prüfanker verwendet, nicht als Schmuck.
- Rechtsprechung wird nur ausgegeben, wenn Gericht, Datum, Aktenzeichen und ein frei zugänglicher Fundlink geprüft sind.
- Unsichere Register-/Grundbuchstände werden nicht geraten; das Plugin fordert aktuelle Auszüge oder Nachweise an.

## Amtliche Startquellen

- [GBO](https://www.gesetze-im-internet.de/gbo/)
- [GBV](https://www.gesetze-im-internet.de/gbvfg/)
- [FamFG Aufgebotsverfahren](https://www.gesetze-im-internet.de/famfg/)
- [BGB Grundstücksrechte](https://www.gesetze-im-internet.de/bgb/)
- [Justizportal des Bundes und der Länder](https://justiz.de/)

## Typische Ergebnisse

- Prüfmatrix und Vollzugsfahrplan
- Entwurf für Nachreichung oder Antwort an das Gericht/Amt
- Mandantenbrief in normalem Deutsch
- Fristen- und Ranglog
- Beschwerde- oder Eilrechtsschutz-Skizze
- Liste fehlender Originale, Nachweise und Formmängel

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 64 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `abteilung-i-eigentum-und-erwerbsgrund` | Prüft Eigentümer, Erwerbsgrund, Erbengemeinschaft, Bruchteile, Gesamthand, eGbR und Voreintragung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `abteilung-ii-iii-grundschuld-auflassung` | Analysiert Wegerecht, Leitungsrecht, Nießbrauch, Wohnungsrecht, Vormerkung, Sanierungsvermerk, Nacherbfolge und Verfügungsbeschränkung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `abteilung-iii-grundschuld-hypothek-rang` | Prüft Grundschuld, Hypothek, Rentenschuld, Brief/Buch, Rang, Löschung, Abtretung und Sicherungszweck-Schnittstelle: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `amtshaftung-und-vollzugsfehler` | Ordnet Fehler von Notar, Grundbuchamt, Partei und Bank ohne vorschnelle Schuldzuweisung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `aufgebotsverfahren-famfg` | Prüft Zuständigkeit, Antragsberechtigung, Glaubhaftmachung, Aufgebotsfrist, öffentliche Bekanntmachung und Beschlussverwertung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `auflassung-und-eigentumsumschreibung` | Prüft Auflassung, Antrag, Voreintragung, Unbedenklichkeitsbescheinigung, Genehmigungen und Vollzug: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `auflassungsvormerkung-kaufvertrag` | Prüft Vormerkungszweck, Rang, Löschung, Sicherung gegen Zwischenverfügungen und Käufer-/Bankenschutz: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `auslandsurkunden-apostille-baulast-ist` | Prüft Apostille, Legalisation, notarielle Bescheinigung, Übersetzung und Register-/Vertretungsnachweis: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `baulast-ist-nicht-grundbuch` | Erklärt, warum Baulasten nicht im Grundbuch stehen müssen und wie man Baulastenverzeichnis/Grundbuch zusammenliest: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `beschwerde-grundbuchsache` | Prüft Statthaftigkeit, Beschwer, Frist, Abhilfe, Nichtabhilfe und OLG-Vorlage in Grundbuchsachen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `bestandsverzeichnis-flurstueck-briefrecht` | Prüft Grundstück, Flurstück, Gemarkung, Wirtschaftsart, Zuschreibung, Bestandsteil und Katasterabgleich: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `briefrecht-abtretung-und-loeschung` | Prüft Besitz am Brief, Abtretungserklärung, Löschungsbewilligung, Briefvorlage und Ersatzwege: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `dienstbarkeit-wegerecht-pruefen` | Liest Inhalt, herrschendes/dienendes Grundstück, Ausübungsbereich, Baulast-Schnittstelle und Löschbarkeit: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `elektronischer-rechtsverkehr` | Prüft elektronische Einreichung, notarielle Signatur, Scans, Ausfertigungen und Medienbruchrisiken: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `familiengerichtliche-genehmigung-grundbuch` | Prüft Minderjährige, betreute Personen, Genehmigungsbedürftigkeit, Rechtskraft und Nachweisform: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `finanzierung-und-rangstelle` | Koordiniert Bankauflagen, Rangbescheinigung, Belastungsvollmacht, Zweckerklärung und Auszahlungsvoraussetzungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gbo-antrag-gbr-egbr-genehmigungen` | Prüft GBO-Mechanik aus Antrag, Bewilligung, Eintragungsfähigkeit, Eintragungsreife und Vollzugshindernis: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gbr-egbr-grundbuch` | Prüft Gesellschaftsregister, Voreintragung, Vertretung, Gesellschafterwechsel und MoPeG-Folgen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `genehmigungen-landwirtschaft-verkehrswert` | Prüft Grundstücksverkehr, siedlungsrechtliche Genehmigungen, Vorkaufsrechte und Registervollzug: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuch-grunderwerbsteuer-unbedenklichkeit` | Prüft GrESt-Schnittstelle, Fälligkeitslogik, Ausnahmen und Vollzugshindernis: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuch-qualitygate-vor-vollzug` | Prüft Antrag, Bewilligung, Rang, Nachweise, Anlagen, Genehmigungen, Urkundenform und Zahlungslogik. |
| `grundbuch-vollzugslog-amtswiderspruch` | Erstellt Fristen-, Rang- und Nachweisliste mit Verantwortlichen, Stand und nächstem Schritt: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-amtswiderspruch-und-richtigstellung` | Prüft offensichtliche Unrichtigkeit, Amtswiderspruch, Amtslöschung, Berichtigung und Rechtsschutz: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-brief-vs-buchrecht-erklaerung` | Erklärt Mandanten, warum der Briefkörper zählt und warum Kopien nicht reichen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-eilfall-rangverlust-erbbaurecht` | Erarbeitet Sofortplan bei drohendem Rangverlust oder konkurrierendem Antrag: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-erbbaurecht-schnittstelle` | Verknüpft Grundstücksgrundbuch, Erbbaugrundbuch, Reallast, Zustimmung und Belastungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-flurbereinigung-und-umlegung` | Prüft neue Grundstücksbezeichnungen, Surrogation, Rangfortsetzung und Vollzugsnachweise: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-gesamtgrundschuld-mithaft` | Prüft Mithaft mehrerer Grundstücke, Pfandfreigabe, Rang und Bankauflagen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-gesellschaftsrechtliche-vertretung` | Prüft Handelsregister, Gesellschafterliste, Geschäftsführer, Prokura, Liquidator und ausländische Vertreter: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-insolvenz-auslaendischer-trustee` | Prüft inzidente Anerkennung, Vertretungsmacht, Urkundenform, Übersetzung und Register-/Grundbuchfähigkeit: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-kaltstart-routing` | Führt durch Eigentum, Belastungen, Vollzugsziel, Grundbuchbezirk, Urkundentyp, Nachweise, Rang, Fristdruck und Kommunikationsweg mit dem Grundbuchamt. |
| `grundbuchamt-kommunikation-konkurrierende` | Formuliert sachliche Anfragen, Nachreichungen, Fristbitten und Beschwerdeankündigungen ohne Vollzug zu gefährden: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-konkurrierende-antraege-rangkonflikt` | Prüft, was zu tun ist, wenn Vormerkung, Grundschuld, Pfändung, Insolvenz-/ZVG-Vermerk oder Dienstbarkeit konkurrierend eingehen und der Rang wirtschaftlich entscheidend wird: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel un... |
| `grundbuchamt-maengelmatrix-notariat` | Klassifiziert jedes Hindernis nach Form, Berechtigung, Genehmigung, Rang, Kosten, Steuer und Inhalt: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-nichtigkeitsrisiko-kaufvertrags` | Prüft, ob ein möglicher Form-, Genehmigungs-, Vertretungs- oder Verbotsgesetzmangel den Grundbuchvollzug blockiert und wie Zwischenverfügung, Nachgenehmigung oder Rückabwicklung vorbereitet werden: eigenständiges Prüffeld mit Norm-/Quell... |
| `grundbuchamt-teilloesung-rangfreigabe` | Prüft Teilflächen, Freigabeerklärung, Rangwirkung, Bankbrief und Vollzug: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-verwalterzustimmung-weg` | Prüft Teilungserklärung, Verwalternachweis, Beschluss, Form und Nachreichung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchamt-vollstreckungsunterwerfung` | Prüft § 800 ZPO-Schnittstelle, dingliche Unterwerfung, Klausel und Zustellung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchauszug-due-lesen-abteilung` | Baut eine DD-Tabelle aus Eigentum, Belastungen, Rang, Vollzugshindernissen, offenen Fragen und Deal-Relevanz: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundbuchauszug-lesen-abteilung-i-ii-iii` | Erklärt Bestandsverzeichnis, Abteilung I, II und III mit Warnsystem gegen übersehene Dienstbarkeiten, Vormerkungen, Verfügungsbeschränkungen und Rangfallen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Out... |
| `grundbuchberichtigung-erbfall` | Prüft Erbschein, notarielle Verfügung von Todes wegen, Europäisches Nachlasszeugnis, Grundbuchberichtigung und Kostenfristen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundschuld-bestellung-buchgrundschuld` | Prüft Bewilligung, Rang, Betrag, Zinsen, Nebenleistung, Unterwerfung und Sicherungsabrede: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `grundschuldbrief-verlust-aufgebot` | Führt durch Feststellung des Verlusts, Aufgebotsantrag, Nachweise, Ausschließungsbeschluss, Ersatzbrief/Löschung und Bankkommunikation: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `insolvenzvermerk-zwangsversteigerung-kataster` | Prüft Verfügungsbeschränkung, Zwangsversteigerungsvermerk, Rang, Löschung und Erwerb aus Verfahren: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `kataster-liegenschaftskarte-abgleich` | Prüft Flurstücksidentität, Vermessung, Teilung, Vereinigung, Fortführung und Vollzugshindernisse: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `kaufvertrags-check-grundbuch` | Prüft Belastungen, Fälligkeit, Löschung, Vormerkung, Finanzierung, Besitzübergang und Risiken aus Abteilung II: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `leitungsrecht-und-energieanlagen` | Prüft Strom, Wasser, Fernwärme, Telekommunikation, dingliche Sicherung und Rangkonflikte: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `loeschungsbewilligung-bank-nacherbenvermerk` | Checkt Bankformular, Unterschriften, Vertretungsmacht, Briefvorlage, Teillöschung und Verwahrstelle: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `nacherbenvermerk-und-verfuegungsbeschraenkung` | Prüft Vermerk, Zustimmung, Befreiung, Löschung und Erwerberrisiko: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `niessbrauch-wohnungsrecht` | Prüft Berechtigte, Inhalt, Rang, Löschung, Tod, Heimunterbringung, Vermietung und Finanzierungskonflikt: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `notariat-vollzugsauftrag-grundbuch` | Steuert Notarvollzug, Treuhandauflagen, Fälligkeitsmitteilung, Bankunterlagen und Mandantenkommunikation: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `paragraph-gbo-prioritaetsmitteilung` | Prüft öffentliche oder öffentlich beglaubigte Urkunden, Registerauszüge, Erbnachweise, Vollmachten, Auslandsurkunden und Übersetzungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `prioritaetsmitteilung-und-rangbescheinigung` | Prüft, wann Rang gesichert ist und wie Notar/Bank/Grundbuchamt die Reihenfolge dokumentieren: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `rangprinzip-und-rangvorbehalt` | Ordnet Rangfolge, Rangrücktritt, Gleichrang, Rangvorbehalt und Prioritätsrisiken: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `reallast-erbbauzins-sanierungsvermerk` | Prüft Inhalt, Anpassung, Rang, Vollstreckbarkeit und Zusammenhang mit Erbbaurechten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `rechtsprechung-grundbuch-aufgebotsverfahren` | Verlangt bei jeder Entscheidung Gericht, Datum, Aktenzeichen und frei zugänglichen Link, sonst nur als Prüfbedarf ausgeben: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `sanierungsvermerk-und-vorkaufsrechte-kommune` | Prüft Genehmigung, Vorkaufsrecht, Löschung, Bescheinigung und Kaufvertragsvollzug: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `teilflaechenkauf-und-vermessung` | Plant Vormerkung, Messungsanerkennung, Fortführungsnachweis, Rang, Kaufpreisfälligkeit und Umschreibung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `testamentsvollstrecker-grundbuch-vollmacht` | Prüft Verfügungsbefugnis, Zeugnis, Beschränkungen, Nachweisform und Verkaufsvollzug: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verlorene-genehmigung-verwalterzustimmung-weg` | Prüft, wie eine verlorene familiengerichtliche, betreuungsgerichtliche, sanierungsrechtliche oder behördliche Genehmigung grundbuchtauglich ersetzt oder erneut beschafft wird: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel u... |
| `vollmacht-vorsorgevollmacht-grundbuch` | Prüft notarielle Vollmacht, Ausfertigung, Betreuungs-/Vorsorgevollmacht, Widerruf, Auslandsbezug und Missbrauchsrisiko: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `vorkaufsrecht-wiederkaufsrecht` | Prüft dingliches Recht, Ausübungsfall, Frist, Löschung, Rang und Kaufvertragsgestaltung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `weg-teilungsgrundbuch-zwischenverfuegung` | Prüft Teilungserklärung, Aufteilungsplan, Abgeschlossenheit, Sonder-/Gemeinschaftseigentum, Sondernutzungsrechte und Grundbuchblätter: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `zwischenverfuegung-paragraph-18-gbo` | Analysiert beanstandete Hindernisse, Behebbarkeit, Rangwahrung, Frist und Antwortstrategie: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
