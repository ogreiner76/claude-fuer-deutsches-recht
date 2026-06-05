# aktenauszug-gerichtsverfahren

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`aktenauszug-gerichtsverfahren`) | [`aktenauszug-gerichtsverfahren.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/aktenauszug-gerichtsverfahren.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

**Version:** 3.2.1
**Autor:** Klotzkette

---

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Plugin erscheint in der Plugin-Liste; alle 21 Skills sind sofort verfügbar.
4. Für Updates: neues ZIP herunterladen und Plugin ersetzen.
5. Hinweis: Das Plugin-ZIP muss direkt `.claude-plugin/plugin.json`, `skills/` und `references/` im ZIP-Root enthalten — nicht das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Überblick

Das Plugin `aktenauszug-gerichtsverfahren` generiert strukturierte Aktenauszüge für deutsche Gerichtsverfahren. Es richtet sich an Rechtsanwältinnen und Rechtsanwälte, die sich schnell in ein neues oder übernommenes Mandat einarbeiten müssen.

**Einsatzgebiete:**

- Mandatswechsel und Übernahme von laufenden Verfahren
- Einarbeitung neuer Sachbearbeiter in komplexe Akten
- Vorbereitung auf mündliche Verhandlungen
- Strukturierung umfangreicher Akten vor Beratungsgesprächen
- Erstellung von Mandantenberichten zum Verfahrensstand

**Verfahrensarten:**

- Zivilverfahren (ZPO) inkl. Berufung, Revision, einstweilige Verfügung
- Strafverfahren (StPO) inkl. Revision und Wiederaufnahme
- Verwaltungsverfahren (VwGO) inkl. Berufung und Revision
- Arbeitsgerichtsverfahren (ArbGG) inkl. Urteilsverfahren und Beschlussverfahren
- Sozialgerichtsverfahren (SGG) inkl. Berufung und Eilrechtsschutz

## Skills-Übersicht

| Skill | Zweck |
| --- | --- |
| `aktenauszug-erstellen` | Hauptworkflow: erzeugt alle sechs Bausteine des strukturierten Aktenauszugs aus PDFs und Schriftsätzen |
| `verfahrensidentifikation` | Extrahiert Gericht Kammer Aktenzeichen Streitwert Parteien Instanz und Verfahrensart |
| `einleitungssatz-generator` | Verfasst einen prägnanten ein- bis zweiSatz-Kern des Rechtsstreits mit Hauptnorm |
| `verfahrenszusammenfassung-absatz` | Schreibt zusammenfassenden Absatz mit acht bis zehn Sätzen zu Hintergrund Streitstand prozessualer Lage und nächsten Schritten |
| `sachverhaltschronologie` | Chronologische Bullet-Liste aller wesentlichen außerprozessualen Tatsachen mit Datum und Fundstelle |
| `verfahrenschronologie` | Chronologische Bullet-Liste aller prozessualen Schritte mit hervorgehobenen Fristen |
| `parteivortrag-gegenueberstellung` | Tabelle mit Kläger- und Beklagtenposition zu jedem Streitpunkt |
| `beweismittel-gegenueberstellung` | Tabelle aller Beweisangebote (Zeugen Urkunden Sachverständige) nach Partei und Beweisthema |
| `rechtsargumente-gegenueberstellung` | Tabelle der Rechtsargumente beider Parteien mit Anspruchsgrundlagen Einwendungen Einreden und Rechtsprechungsnachweisen |
| `fristen-und-terminkalender` | Identifiziert und hebt alle prozessrelevanten Fristen und Termine hervor |
| `anlagenverzeichnis-extrakt` | Vollständiges Anlagenverzeichnis aller K-/B-Anlagen mit Inhalt und Fundstelle |
| `schwerpunktthemen-identifikation` | Identifiziert drei bis fünf zentrale Rechtsfragen ohne Erfolgsprognose |
| `neutralitaetspruefung` | Prüft den Aktenauszug auf unzulässige Wertungen und Prognosen und schlägt Korrekturen vor |
| `aktenauszug-strukturpruefung` | Vollständigkeitsprüfung aller sechs Bausteine und Qualitätsgrundsätze |
| `zivilprozess-modus` | ZPO-spezifische Einstellungen für ordentliche Klage Berufung Revision und einstweilige Verfügung |
| `strafprozess-modus` | StPO-spezifische Einstellungen für Anklageverfahren Hauptverhandlung und Revision |
| `verwaltungsprozess-modus` | VwGO-spezifische Einstellungen mit Vorverfahren aufschiebender Wirkung und Berufungszulassung |
| `arbeitsgerichtsverfahren-modus` | ArbGG-spezifische Einstellungen mit Gütetermin KSchG-Dreiwochenfrist und Beschlussverfahren |
| `sozialgerichtsverfahren-modus` | SGG-spezifische Einstellungen mit Widerspruchsverfahren Amtsermittlung und Eilrechtsschutz |
| `anwaltsschriftsatz-stilrichtlinie` | Verbindliche Stilregeln für Sprache Gliederung Nomenklatur und Markdown-Formatierung |

## Methodik

Ausführliche Erläuterung der Methodik unter [references/methodik.md](references/methodik.md).

- Quellenregel: Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff; keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen.

## Beispielprompt

```
Erstelle einen strukturierten Aktenauszug für das anhängende Verfahren vor dem Landgericht Frankfurt am Main (Az. 3 O 456/23). Die Akte enthält Klageschrift, Klageerwiderung und den Beweisbeschluss vom 15.09.2023. Verwende den Zivilprozess-Modus.
```

## Disclaimer

Dieses Plugin erstellt keine Rechtsberatung und gibt keine Erfolgsprognose ab. Die erstellten Aktenauszüge sind Arbeitsinstrumente, die der Prüfung und Freigabe durch den zuständigen Rechtsanwalt bedürfen. Das Plugin ersetzt nicht die eigene Aktenlektüre.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `aktenauszug-strukturpruefung-akzg-bauleiter` | Nutze dies bei Aktenauszug Strukturpruefung, Akzg Aktenauszug Bauleiter, Akzg Vertraulichkeit Redaction Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschr... |
| `akzg` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Akzg Multiparteienverfahren Konsolidierung Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `akzg-zeitstrahl-anlagenverzeichnis-extrakt` | Nutze dies bei Akzg Zeitstrahl Checkliste, Anlagenverzeichnis Extrakt, Anwaltsschriftsatz Stilrichtlinie: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `anwaltsschriftsatz-beweislast-beweismittel` | Nutze dies bei Anwaltsschriftsatz Beweislast Und Darlegungslast, Beweismittel Mehrparteien Konflikt Und Interessen, Einleitungssatz Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpf... |
| `arbeitsgerichtsverfahren-modus-terminkalender` | Nutze dies bei Arbeitsgerichtsverfahren Modus, Fristen Und Terminkalender, Sozialgerichtsverfahren Modus: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `beweismittel-gegenueberstellung` | Nutze dies bei Beweismittel Gegenueberstellung, Einleitungssatz Generator, Neutralitaetspruefung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einarbeitung-fehlerkatalog` | Nutze dies als Fehlerbremse bei Einarbeitung Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `erstellen-fristennotiz-gerichtsverfahren` | Nutze dies bei Erstellen Fristennotiz Und Naechster Schritt, Gerichtsverfahren Fristen Form Und Zustaendigkeit, Verfahrensgeschichte Vergleich Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und li... |
| `gegenueberstellung-parteivortraege` | Nutze dies bei Gegenueberstellung Zahlen Schwellen Und Berechnung, Parteivortraege Compliance Dokumentation Und Akte, Rechtsargumente Internationaler Bezug Und Schnittstellen: führt durch diese fachlich verbundenen Module, wählt den pass... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `parteivortrag-gegenueberstellung` | Nutze dies bei Parteivortrag Gegenueberstellung, Rechtsargumente Gegenueberstellung, Sachverhaltschronologie: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `sachverhaltschronologie-textbausteine` | Nutze dies bei Sachverhaltschronologie Textbausteine, Schnelle Formular Portal Und Einreichung, Stilrichtlinie Sonderfall Und Edge Case: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `schwerpunktthemen-identifikation-akten` | Nutze dies bei Schwerpunktthemen Identifikation, Akten Mandantenkommunikation Entscheidungsvorlage, Aktenauszug Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näc... |
| `strukturierter-strafprozess-modus` | Nutze dies bei Strukturierter Erstpruefung Und Mandatsziel, Strafprozess Modus, Verwaltungsprozess Modus: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `tabellarische-quellenkarte` | Nutze dies zur Quellenprüfung bei Tabellarische Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `verfahrensidentifikation` | Nutze dies bei Verfahrensidentifikation, Verfahrenszusammenfassung Absatz, Aktenauszug Erstellen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `verfahrensidentifikation-02` | Nutze dies bei Verfahrensidentifikation Dokumentenmatrix, Verfahrenszusammenfassung Rechtsweg Register, Verfahrenschronologie: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbar... |
| `zivilprozess-modus` | Nutze dies bei Zivilprozess Modus: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
