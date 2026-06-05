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
| `ablauf-laufzeitende-erbbaurecht-aktenstruktur` | Erbbaurecht Ablauf Laufzeitende Exitplan, Erbbaurecht Aktenstruktur: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `altlasten-rueckbau-erbbaurecht` | Erbbaurecht Altlasten Und Rueckbau, Erbbaurecht Betreiberwechsel: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `change-control-dingliche-vorkaufsrechte` | Erbbaurecht Change Of Control Bei Erbbauberechtigtem, Erbbaurecht Dingliche Vorkaufsrechte: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `erbbau-beschwerde-erbbaugrundbuch-lesen` | Erbbau Beschwerde Grundbuchamt, Erbbaugrundbuch Lesen: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `erbbaurecht-kaltstart-routing` | Führt durch Grundstück, Erbbauberechtigte, Eigentümer, Laufzeit, Bauwerk, Erbbauzins, Heimfall, Finanzierung, Zustimmung und Grundbuchvollzug. |
| `erbbaurecht-photovoltaik-untererbbaurecht` | Erbbaurecht Und Photovoltaik, Erbbaurecht Untererbbaurecht Und Weitergabe: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `erbbaurecht-qualitygate-vertrag` | Checkt, ob ein Entwurf investierbar, vollziehbar, finanzierbar und konfliktfest ist. |
| `erbbauzins-struktur-erbbauzinsanpassung` | Erbbauzins Struktur Und Reallast, Erbbauzinsanpassung Paragraph 9a: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `erbbauzinsrang-finanzierungsbank-erbbaurecht` | Erbbaurecht Erbbauzinsrang Vor Finanzierungsbank, Erbbaurecht Gewerbepark: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `finanzierung-bankfaehigkeit-gemeinde-kirche` | Finanzierung Erbbaurecht Bankfaehigkeit, Gemeinde Kirche Stiftung Als Eigentuemer: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `heimfall-gruende-indexklausel-inflation` | Heimfall Gruende Und Verfahren, Erbbaurecht Indexklausel Inflation: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `heimfall-verteidigung-insolvenz` | Heimfall Verteidigung, Insolvenz Erbbauberechtigter: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `instandhaltung-versicherung-investoren-q` | Erbbaurecht Instandhaltung Versicherung Betriebspflichten, Erbbaurecht Investoren Q And A: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `kauf-due-kita-sozialimmobilie` | Erbbaurecht Kauf Und Due Diligence, Erbbaurecht Kita Sozialimmobilie: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `kommunale-beschlussvorlage-erbbaurecht` | Erbbaurecht Kommunale Beschlussvorlage, Erbbaurecht Mandantenbrief: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `laufzeit-verlaengerung-wohnungs-weg` | Laufzeit Verlaengerung Und Neubestellung, Wohnungs Erbbaurecht Und Weg: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `nachhaltigkeit-baupflicht-notar` | Erbbaurecht Nachhaltigkeit Und Baupflicht, Erbbaurecht Notar Und Grundbuchkosten: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `nutzungszweckwechsel-wohnen-rangruecktritt` | Erbbaurecht Nutzungszweckwechsel Wohnen Gewerbe Sozial, Erbbaurecht Rangruecktritt Bank: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `rechtsprechung-live-erbbaurecht-reminder` | Rechtsprechung Erbbaurecht Live Verifizieren, Erbbaurecht Fristen Und Reminder: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `rueckbau-am-schieds-gerichtsstand` | Erbbaurecht Rueckbau Am Laufzeitende, Erbbaurecht Schieds Und Gerichtsstand: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `sicherheiten-buergschaft-teilerbbaurecht` | Erbbaurecht Sicherheiten Buergschaft Depot Lastschrift, Erbbaurecht Teilerbbaurecht Und Aufteilung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `steuern-grunderwerbsteuer-entschaedigung` | Erbbaurecht Steuern Und Grunderwerbsteuer, Entschaedigung Bei Heimfall Und Ablauf: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `verjaehrung-verwirkung-vorlage` | Erbbaurecht Verjaehrung Verwirkung Duldung, Erbbaurecht Vorlage Zustimmungsantrag: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `verkauf-spa-erbbaurechtsvertrag-pflichtinhalt` | Erbbaurecht Verkauf Spa Klauseln, Erbbaurechtsvertrag Pflichtinhalt: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `vs-eigentum-erbbauzins-rueckstand` | Erbbaurecht Vs Eigentum Vs Miete, Erbbauzins Rueckstand Mahnung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `zustimmung-veraeusserung-zwangsversteigerung` | Zustimmung Veraeusserung Belastung, Zwangsversteigerung Erbbaurecht: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
