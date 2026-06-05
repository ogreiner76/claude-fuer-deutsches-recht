# Erbbaurecht Praxis

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`erbbaurecht-praxis`) | [`erbbaurecht-praxis.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/erbbaurecht-praxis.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Lindenwerder Erbbaurecht - Erbbauzins, Heimfall und Kita-Finanzierung** (`erbbaurecht-erbbauzins-heimfall-lindenwerder-2026`) | [Gesamt-PDF lesen](../testakten/erbbaurecht-erbbauzins-heimfall-lindenwerder-2026/gesamt-pdf/erbbaurecht-erbbauzins-heimfall-lindenwerder-2026_gesamt.pdf) | [`testakte-erbbaurecht-erbbauzins-heimfall-lindenwerder-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-erbbaurecht-erbbauzins-heimfall-lindenwerder-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein Spezialplugin für das Recht des Erbbaurechts: vom ersten Vertragsentwurf über Erbbauzins und Heimfall bis zu Finanzierung, Zustimmung, Versteigerung und Erbbaugrundbuch. Es erklärt die Sache auch für Menschen, die sonst nur Eigentum oder Miete kennen.

## Wofür dieses Plugin da ist

Dieses Plugin ist ein Praxiswerkzeug. Es fragt zuerst die Lage ab, baut dann eine Dokumenten- und Vollzugsmatrix und erzeugt schließlich das konkrete Arbeitsprodukt: Nachreichung, Beanstandungsantwort, Beschwerdegerüst, Mandantenbrief, Checkliste, Fristenlog oder Vertrags-/Urkundenreview. Es ersetzt keine Berufsträgerentscheidung, aber es verhindert, dass ein formeller Nachweis, ein Rang, eine Abteilung-II-Belastung oder eine Registerfolge in der Hektik untergeht.

## Kaltstart

Starte mit dem allgemeinen Skill `erbbaurecht-allgemeiner-kaltstart`. Lade danach möglichst den aktuellen Register- oder Grundbuchauszug, das Gerichtsschreiben, die Anmeldung/Bewilligung, den Vertragsentwurf und vorhandene Anlagen hoch. Das Plugin sortiert erst, dann prüft es.

## Quellen- und Halluzinationsschutz

- Normen werden als Prüfanker verwendet, nicht als Schmuck.
- Rechtsprechung wird nur ausgegeben, wenn Gericht, Datum, Aktenzeichen und ein frei zugänglicher Fundlink geprüft sind.
- Unsichere Register-/Grundbuchstände werden nicht geraten; das Plugin fordert aktuelle Auszüge oder Nachweise an.

## Amtliche Startquellen

- [ErbbauRG](https://www.gesetze-im-internet.de/erbbauv/)
- [GBO](https://www.gesetze-im-internet.de/gbo/)
- [GBV](https://www.gesetze-im-internet.de/gbvfg/)
- [BGB Sachenrecht](https://www.gesetze-im-internet.de/bgb/)
- [FamFG](https://www.gesetze-im-internet.de/famfg/)

## Typische Ergebnisse

- Prüfmatrix und Vollzugsfahrplan
- Entwurf für Nachreichung oder Antwort an das Gericht/Amt
- Mandantenbrief in normalem Deutsch
- Fristen- und Ranglog
- Beschwerde- oder Eilrechtsschutz-Skizze
- Liste fehlender Originale, Nachweise und Formmängel

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 26 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `ablauf-laufzeitende-erbbaurecht-aktenstruktur` | Ablauf Laufzeitende Erbbaurecht Aktenstruktur im Plugin Erbbaurecht Praxis: prüft konkret Prüft die letzten zehn Jahre eines Erbbaurechts, Sortiert Vertrag, Grundbuch, Zins. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel un... |
| `altlasten-rueckbau-erbbaurecht` | Altlasten Rueckbau Erbbaurecht im Plugin Erbbaurecht Praxis: prüft konkret Ordnet Baugrund, Kontamination, Rückbaupflicht, Kostenverteilung und Beweissiche. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `change-control-dingliche-vorkaufsrechte` | Change Control Dingliche Vorkaufsrechte im Plugin Erbbaurecht Praxis: prüft konkret Prüft, ob Anteilsübertragung, Verschmelzung, Formwechsel oder Kontrollwechsel be. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächst... |
| `erbbau-beschwerde-erbbaugrundbuch-lesen` | Erbbau Beschwerde Erbbaugrundbuch Lesen im Plugin Erbbaurecht Praxis: prüft konkret Prüft Zwischenverfügung, Rangproblem, Zustimmung, Nachweise und Beschwerde. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Sch... |
| `erbbaurecht-kaltstart-routing` | Führt durch Grundstück, Erbbauberechtigte, Eigentümer, Laufzeit, Bauwerk, Erbbauzins, Heimfall, Finanzierung, Zustimmung und Grundbuchvollzug. |
| `erbbaurecht-photovoltaik-untererbbaurecht` | Photovoltaik Untererbbaurecht im Plugin Erbbaurecht Praxis: prüft konkret Prüft Nutzungszweck, bauliche Veränderung, Dienstbarkeit, Einspeisung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `erbbaurecht-qualitygate-vertrag` | Checkt, ob ein Entwurf investierbar, vollziehbar, finanzierbar und konfliktfest ist. |
| `erbbauzins-struktur-erbbauzinsanpassung` | Erbbauzins Struktur Erbbauzinsanpassung im Plugin Erbbaurecht Praxis: prüft konkret Prüft dingliche Sicherung, Fälligkeit, Wertsicherung, Anpassung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `erbbauzinsrang-finanzierungsbank-erbbaurecht` | Erbbauzinsrang Finanzierungsbank Erbbaurecht im Plugin Erbbaurecht Praxis: prüft konkret Prüft, wann der Rang der Erbbauzinsreallast die Finanzierung, wie Rang, Prüft Nutzung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel... |
| `finanzierung-bankfaehigkeit-gemeinde-kirche` | Finanzierung Bankfaehigkeit Gemeinde Kirche im Plugin Erbbaurecht Praxis: prüft konkret Prüft Beleihbarkeit, Rang, Laufzeitrest, Heimfallrisiko. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `heimfall-gruende-indexklausel-inflation` | Heimfall Gruende Indexklausel Inflation im Plugin Erbbaurecht Praxis: prüft konkret Prüft Vertragsgrund, Verzug, Pflichtverletzung, Fristen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `heimfall-verteidigung-insolvenz` | Heimfall Verteidigung Insolvenz im Plugin Erbbaurecht Praxis: prüft konkret Entwickelt Einwendungen, Nachholung, Verhältnismäßigkeit, Vergleich. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `instandhaltung-versicherung-investoren-q` | Instandhaltung Versicherung Investoren Q im Plugin Erbbaurecht Praxis: prüft konkret Prüft Gebäudeunterhaltung, Verkehrssicherung, Versicherung, Nachweispflichten. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem... |
| `kauf-due-kita-sozialimmobilie` | Kauf DUE Kita Sozialimmobilie im Plugin Erbbaurecht Praxis: prüft konkret Baut DD-Liste, Prüft kommunale Zwecke, Betreiberwechsel, Fördermittel. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `kommunale-beschlussvorlage-erbbaurecht` | Kommunale Beschlussvorlage Erbbaurecht im Plugin Erbbaurecht Praxis: prüft konkret Erstellt Gemeinderatsvorlage für Bestellung, Änderung, Verlängerung oder Heimfal, Erklärt Lage. Liefert priorisierten Output mit Norm-Pinpoints, Risikoamp... |
| `laufzeit-verlaengerung-wohnungs-weg` | Laufzeit Verlaengerung Wohnungs WEG im Plugin Erbbaurecht Praxis: prüft konkret Prüft Verlängerung, Neubestellung, Rang, Zustimmung der Gläubiger und kommunale. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Sc... |
| `nachhaltigkeit-baupflicht-notar` | Nachhaltigkeit Baupflicht Notar im Plugin Erbbaurecht Praxis: prüft konkret Prüft Bauverpflichtung, energetische Standards, Fördermittel, Verzögerung und Sa. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `nutzungszweckwechsel-wohnen-rangruecktritt` | Nutzungszweckwechsel Wohnen Rangruecktritt im Plugin Erbbaurecht Praxis: prüft konkret Prüft Nutzungszweck, baurechtliche und vertragliche Grenzen, Zustimmungserforder, Prüft Eigentümerzustimmung. Liefert priorisierten Output mit Norm-Pi... |
| `rechtsprechung-live-erbbaurecht-reminder` | Rechtsprechung Live Erbbaurecht Reminder im Plugin Erbbaurecht Praxis: prüft konkret Sichert, dass Entscheidungen nur mit Gericht, Datum, Aktenzeichen und freiem Lin. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächs... |
| `rueckbau-am-schieds-gerichtsstand` | Rueckbau AM Schieds Gerichtsstand im Plugin Erbbaurecht Praxis: prüft konkret Ordnet Rückbaupflicht, Entschädigung, Zustandserfassung, Sicherheiten und Konfli. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Sch... |
| `sicherheiten-buergschaft-teilerbbaurecht` | Sicherheiten Buergschaft Teilerbbaurecht im Plugin Erbbaurecht Praxis: prüft konkret Prüft Bürgschaft, Kaution, Rückbausicherheit, Lastschrift. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `steuern-grunderwerbsteuer-entschaedigung` | Steuern Grunderwerbsteuer Entschaedigung im Plugin Erbbaurecht Praxis: prüft konkret Markiert GrESt-, Ertragsteuer-, USt- und Bewertungsfragen als Schnittstellen mit, Prüft Entschädigung bei Heimfall. Liefert priorisierten Output mit Nor... |
| `verjaehrung-verwirkung-vorlage` | Verjaehrung Verwirkung Vorlage im Plugin Erbbaurecht Praxis: prüft konkret Prüft, ob lange geduldete Nutzungen, verspätete Zinsforderungen oder alte Pflich, Entwirft Antrag an Grundstückseigentümer für Veräußerung. Liefert priorisierten... |
| `verkauf-spa-erbbaurechtsvertrag-pflichtinhalt` | Verkauf SPA Erbbaurechtsvertrag Pflichtinhalt im Plugin Erbbaurecht Praxis: prüft konkret Entwirft SPA-Klauseln zu Zustimmung, Zinsrückstand, Heimfallrisiko, Belastungen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und n... |
| `vs-eigentum-erbbauzins-rueckstand` | VS Eigentum Erbbauzins Rueckstand im Plugin Erbbaurecht Praxis: prüft konkret Erklärt den dogmatischen Unterschied zu Eigentum, Miete, Nießbrauch, Dienstbarke. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Sch... |
| `zustimmung-veraeusserung-zwangsversteigerung` | Zustimmung Veraeusserung Zwangsversteigerung im Plugin Erbbaurecht Praxis: prüft konkret Prüft Zustimmungserfordernis, Versagungsgründe, Frist, Ersatz durch Gericht und. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nä... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
