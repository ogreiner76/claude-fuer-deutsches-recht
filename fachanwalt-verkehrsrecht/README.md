# Fachanwalt Verkehrsrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`fachanwalt-verkehrsrecht`) | [`fachanwalt-verkehrsrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/fachanwalt-verkehrsrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **StVO-Akte Schulstraße/Lieferzone** (`strassenverkehrsrecht-stvo-schulstrasse-lieferzone`) | [Gesamt-PDF lesen](../testakten/strassenverkehrsrecht-stvo-schulstrasse-lieferzone/gesamt-pdf/strassenverkehrsrecht-stvo-schulstrasse-lieferzone_gesamt.pdf) | [`testakte-strassenverkehrsrecht-stvo-schulstrasse-lieferzone.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-strassenverkehrsrecht-stvo-schulstrasse-lieferzone.zip) |
| **Verkehrsunfall Tannenbruck — A45 Quotenstreit, OWi, Fahrerlaubnis-Entzug, MPU** (`verkehrsunfall-quotenstreit-tannenbruck-a45`) | [Gesamt-PDF lesen](../testakten/verkehrsunfall-quotenstreit-tannenbruck-a45/gesamt-pdf/verkehrsunfall-quotenstreit-tannenbruck-a45_gesamt.pdf) | [`testakte-verkehrsunfall-quotenstreit-tannenbruck-a45.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verkehrsunfall-quotenstreit-tannenbruck-a45.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Plugin Fachanwalt für Verkehrsrecht. Orientierung StVG StVO PflVG VVG-Bezüge. Verkehrsunfall Personenschaden Sachschaden Bußgeld Fahrerlaubnis OWi-Verfahren Verkehrsstrafrecht (§§ 315c 316 StGB). Schnittstellen zu Versicherungs- und Strafrecht.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `fachanwalt-verkehrsrecht-orientierung` | Orientierung im Verkehrsrecht — FAO Voraussetzungen Normen typische Mandate Fristen Quellenprüfung. Verkehrsunfall mit Personen- und Sachschaden Schadensregulierung Versicherung Haftpflicht Kasko Bußgeld Fahrerlau… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `autonom-bezuege-fachanwalt` | Nutze dies bei Autonom Abschlussprodukt Und Uebergabe, Bezuege Behörden Gericht Und Registerweg, Fachanwalt Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächste... |
| `bussgeld-unfall-haftungsquote-vkr` | Nutze dies bei Bussgeld Zahlen Schwellen Und Berechnung, Unfall Haftungsquote Berechnen, Vkr Totalschaden Fiktiv Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Ar... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `erstgespraech-mandatsannahme-verkehr-autonom` | Nutze dies bei Erstgespraech Mandatsannahme, Fachanwalt Verkehr Autonom 1d Stvg, Fachanwalt Verkehrsrecht Fahrerlaubnis Entzug: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastba... |
| `fahrerlaubnis-kanzlei-personen` | Nutze dies bei Fahrerlaubnis Compliance Dokumentation Und Akte, Kanzlei Mandantenkommunikation Entscheidungsvorlage, Personen Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpf... |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies bei Fristen Und Risikoampel, Mandantenkommunikation, Redteam Qualitygate: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `mandat-triage-schriftsatzkern-substantiierung` | Nutze dies bei Mandat Triage Verkehrsrecht, Schriftsatzkern Substantiierung, 315c Internationaler Bezug Und Schnittstellen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `mpu-vorbereitung-orientierung` | Nutze dies bei Fachanwalt Verkehrsrecht Mpu Vorbereitung, Fachanwalt Verkehrsrecht Orientierung, Fachanwalt Verkehrsrecht Regulierungsanforderung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert de... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `pflvg-quoten-sonderfall-stgb` | Nutze dies bei Pflvg Risikoampel Und Gegenargumente, Quoten Sonderfall Und Edge Case, Stgb Formular Portal Und Einreichung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `sachschaden-quellenkarte` | Nutze dies zur Quellenprüfung bei Sachschaden Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `schnittstelle-fehlerkatalog` | Nutze dies als Fehlerbremse bei Schnittstelle Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `stvg-verkehr-fristennotiz-vkr-blitzer` | Nutze dies bei Stvg Fristen Form Und Zustaendigkeit, Verkehr Fristennotiz Und Naechster Schritt, Vkr Blitzer Messverfahren Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `stvo-unfallregulierung-beweislast` | Nutze dies bei Stvo Dokumentenmatrix Und Lueckenliste, Unfallregulierung Beweislast Und Darlegungslast, Verkehrsrecht Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert d... |
| `tempo-messung-unfallregulierung-quoten` | Nutze dies bei Fachanwalt Verkehrsrecht Tempo Messung Beweis, Fachanwalt Verkehrsrecht Unfallregulierung Quoten, Fachanwalt Verkehrsrecht Versicherer Quotenverhandlung Vergleich: führt durch diese fachlich verbundenen Module, wählt den p... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `verk-fahrerlaubnisrecht-leitfaden-fahrtenbuch` | Nutze dies bei Verk Fahrerlaubnisrecht Leitfaden, Verk Fahrtenbuch Anordnung Spezial, Verk Trunkenheit Drogenfahrt Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `verk-unfallregulierung` | Nutze dies bei Allgemein, Verk Unfallregulierung Workflow, Chronologie Und Belegmatrix, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `verkehrsstrafrecht-interessen-verkehrsunfall` | Nutze dies bei Verkehrsstrafrecht Mehrparteien Konflikt Und Interessen, Verkehrsunfall Schriftsatz Brief Und Memo Bausteine, Vergleichsverhandlung Strategie: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `vkr-bussgeldverfahren-bussgeld-einspruch` | Nutze dies bei Vkr Bussgeldverfahren Grundzuege, Bussgeld Einspruch Prüfen, Fachanwalt Verkehrsrecht Bussgeldbescheid Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbare... |
| `vkr-einfuehrung` | Nutze dies bei Vkr Einfuehrung Rechtsfelder: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
