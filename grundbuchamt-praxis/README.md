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

Automatisch generierte Komplett-Liste aller 23 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `abteilung-ii-iii-grundschuld-auflassung` | Nutze dies bei Abteilung Ii Dienstbarkeit Vormerkung Beschraenkung, Abteilung Iii Grundschuld Hypothek Rang, Auflassung Und Eigentumsumschreibung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert de... |
| `auslandsurkunden-apostille-baulast-ist` | Nutze dies bei Auslandsurkunden Apostille Grundbuch, Baulast Ist Nicht Grundbuch, Beschwerde Grundbuchsache: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `bestandsverzeichnis-flurstueck-briefrecht` | Nutze dies bei Bestandsverzeichnis Flurstueck Und Zuschreibung, Briefrecht Abtretung Und Löschung, Dienstbarkeit Wegerecht Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belas... |
| `elektronischer-rechtsverkehr` | Nutze dies bei Elektronischer Rechtsverkehr Grundbuch, Familiengerichtliche Genehmigung Grundbuch, Finanzierung Und Rangstelle: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastba... |
| `gbo-antrag-gbr-egbr-genehmigungen` | Nutze dies bei Gbo Antrag Bewilligung Eintragung, Gbr Egbr Grundbuch, Genehmigungen Landwirtschaft Verkehrswert: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschr... |
| `grundbuch-qualitygate-vor-vollzug` | Prüft Antrag, Bewilligung, Rang, Nachweise, Anlagen, Genehmigungen, Urkundenform und Zahlungslogik. |
| `grundbuch-vollzugslog-amtswiderspruch` | Nutze dies bei Grundbuch Vollzugslog, Grundbuchamt Amtswiderspruch Und Richtigstellung, Grundbuchamt Brief Vs Buchrecht Erklaerung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `grundbuchamt-allgemeiner-kaltstart` | Führt durch Eigentum, Belastungen, Vollzugsziel, Grundbuchbezirk, Urkundentyp, Nachweise, Rang, Fristdruck und Kommunikationsweg mit dem Grundbuchamt. |
| `grundbuchamt-eilfall-rangverlust-erbbaurecht` | Nutze dies bei Grundbuchamt Eilfall Rangverlust, Grundbuchamt Erbbaurecht Schnittstelle, Grundbuchamt Flurbereinigung Und Umlegung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `grundbuchamt-gesamtgrundschuld-mithaft` | Nutze dies bei Grundbuchamt Gesamtgrundschuld Und Mithaft, Grundbuchamt Gesellschaftsrechtliche Vertretung, Grundbuchamt Insolvenz Auslaendischer Trustee: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und li... |
| `grundbuchamt-kommunikation-konkurrierende` | Nutze dies bei Grundbuchamt Kommunikation, Grundbuchamt Konkurrierende Antraege Rangkonflikt, Grundbuchamt Teilloesung Rangfreigabe: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bel... |
| `grundbuchamt-maengelmatrix-notariat` | Nutze dies bei Grundbuchamt Maengelmatrix, Notariat Vollzugsauftrag Grundbuch, Abteilung I Eigentum Und Erwerbsgrund: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `grundbuchamt-nichtigkeitsrisiko-kaufvertrags` | Nutze dies bei Grundbuchamt Nichtigkeitsrisiko Kaufvertrag, Kaufvertrags Check Grundbuch, Amtshaftung Und Vollzugsfehler: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Ar... |
| `grundbuchauszug-due-lesen-abteilung` | Nutze dies bei Grundbuchauszug Für Due Diligence, Grundbuchauszug Lesen Abteilung I Ii Iii, Grundbuchberichtigung Erbfall: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren A... |
| `grunderwerbsteuer` | Nutze dies bei Grunderwerbsteuer Unbedenklichkeitsbescheinigung, Grundschuld Bestellung Buchgrundschuld, Grundschuldbrief Verlust Aufgebot: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächs... |
| `insolvenzvermerk-zwangsversteigerung-kataster` | Nutze dies bei Insolvenzvermerk Zwangsversteigerung, Kataster Liegenschaftskarte Abgleich, Leitungsrecht Und Energieanlagen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `loeschungsbewilligung-bank-nacherbenvermerk` | Nutze dies bei Loeschungsbewilligung Bank, Nacherbenvermerk Und Verfuegungsbeschraenkung, Niessbrauch Wohnungsrecht: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeits... |
| `paragraph-gbo-prioritaetsmitteilung` | Nutze dies bei Paragraph 29 Gbo Formnachweis, Prioritaetsmitteilung Und Rangbescheinigung, Rangprinzip Und Rangvorbehalt: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Ar... |
| `reallast-erbbauzins-sanierungsvermerk` | Nutze dies bei Reallast Und Erbbauzins, Sanierungsvermerk Und Vorkaufsrechte Kommune, Teilflaechenkauf Und Vermessung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbei... |
| `rechtsprechung-grundbuch-aufgebotsverfahren` | Nutze dies bei Rechtsprechung Grundbuch Live Verifizieren, Aufgebotsverfahren Famfg, Auflassungsvormerkung Kaufvertrag: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbe... |
| `testamentsvollstrecker-grundbuch-vollmacht` | Nutze dies bei Testamentsvollstrecker Grundbuch, Vollmacht Vorsorgevollmacht Grundbuch, Vorkaufsrecht Wiederkaufsrecht: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbe... |
| `verlorene-genehmigung-verwalterzustimmung-weg` | Nutze dies bei Grundbuchamt Verlorene Genehmigung Und Ersatznachweis, Grundbuchamt Verwalterzustimmung Weg, Grundbuchamt Vollstreckungsunterwerfung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `weg-teilungsgrundbuch-zwischenverfuegung` | Nutze dies bei Weg Teilungsgrundbuch, Zwischenverfuegung Paragraph 18 Gbo: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
