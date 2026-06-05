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
| `ablauf-laufzeitende-erbbaurecht-aktenstruktur` | Nutze dies bei Erbbaurecht Ablauf Laufzeitende Exitplan, Erbbaurecht Aktenstruktur: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `altlasten-rueckbau-erbbaurecht` | Nutze dies bei Erbbaurecht Altlasten Und Rueckbau, Erbbaurecht Betreiberwechsel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `change-control-dingliche-vorkaufsrechte` | Nutze dies bei Erbbaurecht Change Of Control Bei Erbbauberechtigtem, Erbbaurecht Dingliche Vorkaufsrechte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `erbbau-beschwerde-erbbaugrundbuch-lesen` | Nutze dies bei Erbbau Beschwerde Grundbuchamt, Erbbaugrundbuch Lesen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `erbbaurecht-allgemeiner-kaltstart` | Führt durch Grundstück, Erbbauberechtigte, Eigentümer, Laufzeit, Bauwerk, Erbbauzins, Heimfall, Finanzierung, Zustimmung und Grundbuchvollzug. |
| `erbbaurecht-photovoltaik-untererbbaurecht` | Nutze dies bei Erbbaurecht Und Photovoltaik, Erbbaurecht Untererbbaurecht Und Weitergabe: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `erbbaurecht-qualitygate-vertrag` | Checkt, ob ein Entwurf investierbar, vollziehbar, finanzierbar und konfliktfest ist. |
| `erbbauzins-struktur-erbbauzinsanpassung` | Nutze dies bei Erbbauzins Struktur Und Reallast, Erbbauzinsanpassung Paragraph 9a: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `erbbauzinsrang-finanzierungsbank-erbbaurecht` | Nutze dies bei Erbbaurecht Erbbauzinsrang Vor Finanzierungsbank, Erbbaurecht Gewerbepark: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `finanzierung-bankfaehigkeit-gemeinde-kirche` | Nutze dies bei Finanzierung Erbbaurecht Bankfaehigkeit, Gemeinde Kirche Stiftung Als Eigentuemer: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `heimfall-gruende-indexklausel-inflation` | Nutze dies bei Heimfall Gruende Und Verfahren, Erbbaurecht Indexklausel Inflation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `heimfall-verteidigung-insolvenz` | Nutze dies bei Heimfall Verteidigung, Insolvenz Erbbauberechtigter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `instandhaltung-versicherung-investoren-q` | Nutze dies bei Erbbaurecht Instandhaltung Versicherung Betriebspflichten, Erbbaurecht Investoren Q And A: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `kauf-due-kita-sozialimmobilie` | Nutze dies bei Erbbaurecht Kauf Und Due Diligence, Erbbaurecht Kita Sozialimmobilie: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `kommunale-beschlussvorlage-erbbaurecht` | Nutze dies bei Erbbaurecht Kommunale Beschlussvorlage, Erbbaurecht Mandantenbrief: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `laufzeit-verlaengerung-wohnungs-weg` | Nutze dies bei Laufzeit Verlaengerung Und Neubestellung, Wohnungs Erbbaurecht Und Weg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `nachhaltigkeit-baupflicht-notar` | Nutze dies bei Erbbaurecht Nachhaltigkeit Und Baupflicht, Erbbaurecht Notar Und Grundbuchkosten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `nutzungszweckwechsel-wohnen-rangruecktritt` | Nutze dies bei Erbbaurecht Nutzungszweckwechsel Wohnen Gewerbe Sozial, Erbbaurecht Rangruecktritt Bank: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `rechtsprechung-live-erbbaurecht-reminder` | Nutze dies bei Rechtsprechung Erbbaurecht Live Verifizieren, Erbbaurecht Fristen Und Reminder: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `rueckbau-am-schieds-gerichtsstand` | Nutze dies bei Erbbaurecht Rueckbau Am Laufzeitende, Erbbaurecht Schieds Und Gerichtsstand: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `sicherheiten-buergschaft-teilerbbaurecht` | Nutze dies bei Erbbaurecht Sicherheiten Buergschaft Depot Lastschrift, Erbbaurecht Teilerbbaurecht Und Aufteilung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitssc... |
| `steuern-grunderwerbsteuer-entschaedigung` | Nutze dies bei Erbbaurecht Steuern Und Grunderwerbsteuer, Entschaedigung Bei Heimfall Und Ablauf: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `verjaehrung-verwirkung-vorlage` | Nutze dies bei Erbbaurecht Verjaehrung Verwirkung Duldung, Erbbaurecht Vorlage Zustimmungsantrag: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `verkauf-spa-erbbaurechtsvertrag-pflichtinhalt` | Nutze dies bei Erbbaurecht Verkauf Spa Klauseln, Erbbaurechtsvertrag Pflichtinhalt: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vs-eigentum-erbbauzins-rueckstand` | Nutze dies bei Erbbaurecht Vs Eigentum Vs Miete, Erbbauzins Rueckstand Mahnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `zustimmung-veraeusserung-zwangsversteigerung` | Nutze dies bei Zustimmung Veraeusserung Belastung, Zwangsversteigerung Erbbaurecht: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
