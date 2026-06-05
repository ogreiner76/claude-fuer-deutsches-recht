# Aktenaufbereiter Strafrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`aktenaufbereiter-strafrecht`) | [`aktenaufbereiter-strafrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/aktenaufbereiter-strafrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **EG Juwel Stuttgart — Sammelverfahren bandenmaessiger schwerer Raub, Königstrasse** (`sammelakte-bandentaeter-eg-juwel-stuttgart-koffer-raub`) | [Gesamt-PDF lesen](../testakten/sammelakte-bandentaeter-eg-juwel-stuttgart-koffer-raub/gesamt-pdf/sammelakte-bandentaeter-eg-juwel-stuttgart-koffer-raub_gesamt.pdf) | [`testakte-sammelakte-bandentaeter-eg-juwel-stuttgart-koffer-raub.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-sammelakte-bandentaeter-eg-juwel-stuttgart-koffer-raub.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Aktenaufbereiter für die Strafverteidigung. Bringt große Strafakten in den Griff durch sechs Excel-fähige Übersichten — Aktenvorblatt; Personenverzeichnis; Tatkomplexe; Beziehungen; Chronologie; Fristen. Fortlaufend ergänzbar. Erkennt Lücken und Widersprüche. Kein Ersatz für Aktenlektüre.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `aktenaufbereiter-strafrecht` | Strukturierte Aufbereitung strafrechtlicher Akten für die Verteidigung. Erzeugt sechs Übersichten — Aktenvorblatt mit Blattangaben; Personenverzeichnis mit Rolle und Erstnennung; Tatkomplex- und Vorwurfsverzeichnis … |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `aktenaufbereiter-strafrecht` | Strafverteidiger erhaelt Strafakte nach § 147 StPO Akteneinsicht und will diese strukturiert aufbereiten. Wirtschaftsstrafverfahren BtM-Verfahren Vermögensdelikte komplexe Strafverfahren. Sechs Übersichten: Aktenvorblatt Personenverzeich... |
| `akteneinsicht-uebersicht-aktenvorblatt` | Nutze dies bei Akteneinsicht Uebersicht, Aktenvorblatt Erstellen, Anklageschrift Zerlegen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `beweismittel-katalog-beweisverwertungsverbote` | Nutze dies bei Beweismittel Katalog, Beweisverwertungsverbote Prüfen, Beziehungsmatrix Personen Taten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `beziehungen-spezial-chronologie-ergaenzbar` | Nutze dies bei Beziehungen Zahlen Schwellen Und Berechnung, Chronologie Compliance Dokumentation Und Akte, Ergaenzbar Formular Portal Und Einreichung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefer... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `erkennt-fehlerkatalog` | Nutze dies als Fehlerbremse bei Erkennt Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `ersatz-sonderfall-excel-faehige` | Nutze dies bei Ersatz Sonderfall Und Edge Case, Excel Dokumentenmatrix Und Lueckenliste, Faehige Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastb... |
| `fortlaufend-luecken-personenverzeichnis` | Nutze dies bei Fortlaufend Internationaler Bezug Und Schnittstellen, Luecken Mandantenkommunikation Entscheidungsvorlage, Personenverzeichnis Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den... |
| `fristenliste-strafverfahren-aktenlektuere` | Nutze dies bei Fristenliste Strafverfahren, Aktenlektuere Fristennotiz Und Naechster Schritt, Fristen Mehrparteien Konflikt Und Interessen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächs... |
| `kronzeugen-regelung-opferzeugen-besondere` | Nutze dies bei Kronzeugen Regelung Spezial, Opferzeugen Besondere Faelle, Personenverzeichnis Aufbau: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `mandantenkommunikation-redteam-qualitygate` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Chronologie Strafverfahren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `revision-rechtsfehler-aktenaufbereiter` | Nutze dies bei Revision Rechtsfehler Katalog, Aktenaufbereiter Erstpruefung Und Mandatsziel, Aktenvorblatt Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `sechs-u-haft-aussageanalyse` | Nutze dies bei Sechs Fristen Form Und Zustaendigkeit, U Haft Fristenwacht, Aussageanalyse Aussagepsychologie: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `strafbefehl-einspruchsstrategie` | Nutze dies bei Strafbefehl Einspruchsstrategie, Strafzumessung Deutsches Strafrecht, Tatkomplexe Uebersicht: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `strafrecht-strafverteidigung-uebersichten` | Nutze dies bei Strafrecht Abschlussprodukt Und Uebergabe, Strafverteidigung Tatbestand Beweis Und Belege, Uebersichten Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lief... |
| `tatkomplexe-quellenkarte` | Nutze dies zur Quellenprüfung bei Tatkomplexe Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `vermoegensabschoepfung-dritt-einziehung` | Nutze dies bei Vermoegensabschoepfung Dritt Arrest, Vermoegensabschoepfung Einziehung, Verstaendigung Deal Strategie: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `widersprueche-beweislast-strafakte-gate` | Nutze dies bei Widersprueche Beweislast Und Darlegungslast, Strafakte Quality Gate, Strafakte Uebergabe Vorbereiten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeits... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
