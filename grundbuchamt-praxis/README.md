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

Automatisch generierte Komplett-Liste aller 23 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `abteilung-ii-iii-grundschuld-auflassung` | Abteilung II III Grundschuld Auflassung im Plugin Grundbuchamt Praxis: prüft konkret Analysiert Wegerecht, Leitungsrecht, Nießbrauch, Wohnungsrecht. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `auslandsurkunden-apostille-baulast-ist` | Auslandsurkunden Apostille Baulast IST im Plugin Grundbuchamt Praxis: prüft konkret Prüft Apostille, Legalisation, notarielle Bescheinigung, Übersetzung und Registe. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächst... |
| `bestandsverzeichnis-flurstueck-briefrecht` | Bestandsverzeichnis Flurstueck Briefrecht im Plugin Grundbuchamt Praxis: prüft konkret Prüft Grundstück, Flurstück, Gemarkung, Wirtschaftsart. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `elektronischer-rechtsverkehr` | Elektronischer Rechtsverkehr im Plugin Grundbuchamt Praxis: prüft konkret Prüft elektronische Einreichung, notarielle Signatur, Scans, Ausfertigungen und. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `gbo-antrag-gbr-egbr-genehmigungen` | GBO Antrag GBR Egbr Genehmigungen im Plugin Grundbuchamt Praxis: prüft konkret Prüft GBO-Mechanik aus Antrag, Bewilligung, Eintragungsfähigkeit, Eintragungsrei. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Sc... |
| `grundbuch-grunderwerbsteuer-unbedenklichkeit` | Grundbuch Grunderwerbsteuer Unbedenklichkeit im Plugin Grundbuchamt Praxis: prüft konkret Prüft GrESt-Schnittstelle, Fälligkeitslogik, Ausnahmen und Vollzugshindernis, Prüft Bewilligung. Liefert priorisierten Output mit Norm-Pinpoints, R... |
| `grundbuch-qualitygate-vor-vollzug` | Prüft Antrag, Bewilligung, Rang, Nachweise, Anlagen, Genehmigungen, Urkundenform und Zahlungslogik. |
| `grundbuch-vollzugslog-amtswiderspruch` | Grundbuch Vollzugslog Amtswiderspruch im Plugin Grundbuchamt Praxis: prüft konkret Erstellt Fristen-, Rang- und Nachweisliste mit Verantwortlichen, Stand und nächs, Prüft offensichtliche Unrichtigkeit. Liefert priorisierten Output mit No... |
| `grundbuchamt-eilfall-rangverlust-erbbaurecht` | Eilfall Rangverlust Erbbaurecht im Plugin Grundbuchamt Praxis: prüft konkret Erarbeitet Sofortplan bei drohendem Rangverlust oder, Verknüpft Grundstücksgrundbuch, Erbbaugrundbuch, Reallast. Liefert priorisierten Output mit Norm-Pinpoints... |
| `grundbuchamt-gesamtgrundschuld-mithaft` | Gesamtgrundschuld Mithaft im Plugin Grundbuchamt Praxis: prüft konkret Prüft Mithaft mehrerer Grundstücke, Pfandfreigabe, Rang und Bankauflagen, Prüft Handelsregister. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näch... |
| `grundbuchamt-kaltstart-routing` | Führt durch Eigentum, Belastungen, Vollzugsziel, Grundbuchbezirk, Urkundentyp, Nachweise, Rang, Fristdruck und Kommunikationsweg mit dem Grundbuchamt. |
| `grundbuchamt-kommunikation-konkurrierende` | Kommunikation Konkurrierende im Plugin Grundbuchamt Praxis: prüft konkret Formuliert sachliche Anfragen, Nachreichungen, Fristbitten und Beschwerdeankündi, Prüft. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem... |
| `grundbuchamt-maengelmatrix-notariat` | Maengelmatrix Notariat im Plugin Grundbuchamt Praxis: prüft konkret Klassifiziert jedes Hindernis nach Form, Berechtigung, Genehmigung, Rang. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `grundbuchamt-nichtigkeitsrisiko-kaufvertrags` | Nichtigkeitsrisiko Kaufvertrags im Plugin Grundbuchamt Praxis: prüft konkret Prüft, ob ein möglicher Form-, Genehmigungs-, Vertretungs- oder Verbotsgesetzman. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schr... |
| `grundbuchauszug-due-lesen-abteilung` | Grundbuchauszug DUE Lesen Abteilung im Plugin Grundbuchamt Praxis: prüft konkret Baut eine DD-Tabelle aus Eigentum, Belastungen, Rang, Vollzugshindernissen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `insolvenzvermerk-zwangsversteigerung-kataster` | Insolvenzvermerk Zwangsversteigerung Kataster im Plugin Grundbuchamt Praxis: prüft konkret Prüft Verfügungsbeschränkung, Zwangsversteigerungsvermerk, Rang, Löschung und Er. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und... |
| `loeschungsbewilligung-bank-nacherbenvermerk` | Loeschungsbewilligung Bank Nacherbenvermerk im Plugin Grundbuchamt Praxis: prüft konkret Checkt Bankformular, Unterschriften, Vertretungsmacht, Briefvorlage. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `paragraph-gbo-prioritaetsmitteilung` | Paragraph GBO Prioritaetsmitteilung im Plugin Grundbuchamt Praxis: prüft konkret Prüft öffentliche oder öffentlich beglaubigte Urkunden, Registerauszüge, Erbnach, Prüft. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nä... |
| `reallast-erbbauzins-sanierungsvermerk` | Reallast Erbbauzins Sanierungsvermerk im Plugin Grundbuchamt Praxis: prüft konkret Prüft Inhalt, Anpassung, Rang, Vollstreckbarkeit und Zusammenhang mit Erbbaurech. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächste... |
| `rechtsprechung-grundbuch-aufgebotsverfahren` | Rechtsprechung Grundbuch Aufgebotsverfahren im Plugin Grundbuchamt Praxis: prüft konkret Verlangt bei jeder Entscheidung Gericht, Datum, Aktenzeichen und frei zugänglich, Prüft Zuständigkeit. Liefert priorisierten Output mit Norm-Pinpoin... |
| `testamentsvollstrecker-grundbuch-vollmacht` | Testamentsvollstrecker Grundbuch Vollmacht im Plugin Grundbuchamt Praxis: prüft konkret Prüft Verfügungsbefugnis, Zeugnis, Beschränkungen, Nachweisform und Verkaufsvoll. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nä... |
| `verlorene-genehmigung-verwalterzustimmung-weg` | Verlorene Genehmigung Verwalterzustimmung WEG im Plugin Grundbuchamt Praxis: prüft konkret Prüft, wie eine verlorene familiengerichtliche, betreuungsgerichtliche, sanierun. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und... |
| `weg-teilungsgrundbuch-zwischenverfuegung` | WEG Teilungsgrundbuch Zwischenverfuegung im Plugin Grundbuchamt Praxis: prüft konkret Prüft Teilungserklärung, Aufteilungsplan, Abgeschlossenheit, Sonder-/Gemeinschaf. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näch... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
