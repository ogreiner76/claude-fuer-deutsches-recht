# Immobilienrechtspraxis

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`immobilienrechtspraxis`) | [`immobilienrechtspraxis.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/immobilienrechtspraxis.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Grundstückskauf / Baulast / Mehrfamilienhaus Rosenmündl — Stuttgart-Ost** (`grundstueckskauf-baulast-mehrfamilienhaus-rosenmuendl-stuttgart-ost`) | [Gesamt-PDF lesen](../testakten/grundstueckskauf-baulast-mehrfamilienhaus-rosenmuendl-stuttgart-ost/gesamt-pdf/grundstueckskauf-baulast-mehrfamilienhaus-rosenmuendl-stuttgart-ost_gesamt.pdf) | [`testakte-grundstueckskauf-baulast-mehrfamilienhaus-rosenmuendl-stuttgart-ost.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-grundstueckskauf-baulast-mehrfamilienhaus-rosenmuendl-stuttgart-ost.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Werkzeuge für immobilienrechtliche Rechtsabteilungen — musterbasierte Vertragserstellung mit Klauselschutz; Vertragsprüfung gegen Playbook; Grundbuchanalyse; Sachverhaltsermittlung; Mieteranfragen mit BGH-Verankerung; Case Management; projektbasierte Arbeitsweise mit AVV-Prüfung.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `case-management` | KI-gestütztes Case Management für immobilienrechtliche Vorgänge. Pro Fall werden Akte Korrespondenz Verträge Schriftsätze und Fristen strukturiert dokumentiert und fortgeschrieben. Erzeugt Fallübersicht in Markd… |
| `grundbuchanalyse` | Strukturierte Auswertung großer Mengen Grundbuchdaten — Grundbuchauszüge Flurkarten Baulastenverzeichnis Altlastenkataster. Extrahiert pro Objekt Eigentümerkette Belastungen in Abteilung II und III Rang Löschungse… |
| `mieteranfragen-bearbeitung` | Bearbeitet eingehende mietrechtliche Anfragen — Mietmängelanzeigen Kündigungen Mieterhöhungsverlangen Widersprüche nach § 574 BGB Betriebskosten-Einwendungen Untervermietungsanfragen — und erstellt fundierte Antwo… |
| `projekt-arbeitsweise` | Strukturierte Projekt- und Ordnerarbeit für immobilienrechtliche Rechtsabteilungen statt freihändigem Prompting. Pro Mandat oder Objekt entsteht ein Projekt-Ordner mit fixierten Vorgaben — Playbook Musterverträge K… |
| `sachverhaltsermittlung` | Unterstützt Inhouse-Juristen bei der zeitraubendsten Phase eines Vorgangs — der Sachverhaltsermittlung. Statt sofort den vollen Sachverhalt zu fordern, führt der Skill einen strukturierten Frageprozess in mehreren S… |
| `vertragserstellung-musterbasiert` | Erstellt immobilienrechtliche Verträge strikt auf Basis hausinterner Musterverträge und Term Sheets. Kernregel ist Klauselschutz — vorgegebene Musterklauseln werden NICHT umformuliert. KI füllt nur markierte Platzh… |
| `vertragspruefung-playbook` | Prüft externe Immobilienverträge gegen das hauseigene Playbook der Rechtsabteilung. Drei Ausgaben — Ampelmatrix nach Klauselkatalog, Redline-Empfehlung als chirurgische Tracked Changes und Business-Memo für das Ass… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 25 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `case-gegen-grundbuchanalyse` | Nutze dies bei Case Internationaler Bezug Und Schnittstellen, Gegen Verhandlung Vergleich Und Eskalation, Grundbuchanalyse Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und l... |
| `case-management-grundbuchanalyse-immo` | Nutze dies bei Case Management, Grundbuchanalyse, Immo Aufteilungsplan Weg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `immo-bauliche-veraenderung-energieausweis` | Nutze dies bei Immo Bauliche Veraenderung Weg, Immo Energieausweis, Immo Gewerbliche Mieter Konkurs: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `immo-bauvertrag-vob-kaufvertrag-grundstueck` | Nutze dies bei Immo Bauvertrag Vob B, Immo Kaufvertrag Grundstueck, Immo Mietkaufvertrag: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `immo-grundschuld-bestellung-makler-honorar` | Nutze dies bei Immo Grundschuld Bestellung, Immo Makler Honorar, Immo Wohnungseigentum Grundlagen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `immo-immobilienrechtliche-live-beweislast` | Nutze dies bei Immo Abschlussprodukt Und Uebergabe, Immobilienrechtliche Tatbestand Beweis Und Belege, Live Beweislast Und Darlegungslast: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächst... |
| `immo-zwangsversteigerung-frist-naechster` | Nutze dies bei Immo Zwangsversteigerung Verfahren, Immobilienrechtspraxis Frist Naechster Schritt, Rechtsabteilungen Fristen Form Und Zustaendigkeit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `immor-bauvertrag-vob-erbbaurecht-vertrag` | Nutze dies bei Immor Bauvertrag Vob Bgb Leitfaden, Immor Erbbaurecht Vertrag Spezial, Immor Grundstueckskaufvertrag Bauleiter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbar... |
| `immor-bodenrichtwert-betriebskostenabrechnung` | Nutze dies bei Immor Bodenrichtwert Bewertung Spezial, Betriebskostenabrechnung Erstellen Asset Management, Betriebskostenabrechnung Prüfen Asset Management: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `klauselschutz-vertragserstellung` | Nutze dies bei Klauselschutz Behörden Gericht Und Registerweg, Vertragserstellung Risikoampel Und Gegenargumente, Vertragspruefung Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden P... |
| `management-mieteranfragen-interessen` | Nutze dies bei Management Formular Portal Und Einreichung, Mieteranfragen Mehrparteien Konflikt Und Interessen, Musterbasierte Dokumentenmatrix Und Lueckenliste: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `mandantenkommunikation-redteam-qualitygate` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Rechtsprechung Mandantenentscheidung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `mieteranfragen-bearbeitung-projekt` | Nutze dies bei Mieteranfragen Bearbeitung, Projekt Arbeitsweise, Sachverhaltsermittlung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `playbook-quellenkarte` | Nutze dies zur Quellenprüfung bei Playbook Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `pruefung-fehlerkatalog` | Nutze dies als Fehlerbremse bei Prüfung Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `sachverhaltsermittlung-verifikation` | Nutze dies bei Sachverhaltsermittlung Compliance Dokumentation Und Akte, Verifikation Sonderfall Und Edge Case, Werkzeuge Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefe... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `vertragserstellung-musterbasiert` | Nutze dies bei Vertragserstellung Musterbasiert, Vertragspruefung Playbook, Immo Share Deal Grunderwerbsteuer: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `weg-abrechnung` | Nutze dies bei Weg Abrechnung Mieterschnittstelle Datenpaket: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
