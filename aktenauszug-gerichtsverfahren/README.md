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
| `aktenauszug-strukturpruefung-akzg-bauleiter` | Nutze dies, wenn Aktenauszug Strukturpruefung, Akzg Aktenauszug Bauleiter, Akzg Vertraulichkeit Redaction Spezial im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Bitte Aktenauszug Strukturpruefung, Akzg... |
| `akzg` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Akzg Multiparteienverfahren Konsolidierung Spezial im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehe... |
| `akzg-zeitstrahl-anlagenverzeichnis-extrakt` | Nutze dies, wenn Akzg Zeitstrahl Checkliste, Anlagenverzeichnis Extrakt, Anwaltsschriftsatz Stilrichtlinie im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Bitte Akzg Zeitstrahl Checkliste, Anlagenverzeic... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, W... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Aktenauszug Gerichtsverfahren.; Welche Unterlagen brauchen Sie?; Welcher Spezialskil... |
| `anwaltsschriftsatz-beweislast-beweismittel` | Nutze dies, wenn Spezial Anwaltsschriftsatz Beweislast Und Darlegungslast, Spezial Beweismittel Mehrparteien Konflikt Und Interessen, Spezial Einleitungssatz Risikoampel Und Gegenargumente im Plugin Aktenauszug Gerichtsverfahren konkret... |
| `arbeitsgerichtsverfahren-modus-terminkalender` | Nutze dies, wenn Arbeitsgerichtsverfahren Modus, Fristen Und Terminkalender, Sozialgerichtsverfahren Modus im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Bitte Arbeitsgerichtsverfahren Modus, Fristen Un... |
| `beweismittel-gegenueberstellung` | Nutze dies, wenn Beweismittel Gegenueberstellung, Einleitungssatz Generator, Neutralitaetspruefung im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Bitte Beweismittel Gegenueberstellung, Einleitungssatz G... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einarbeitung-fehlerkatalog` | Nutze dies, wenn Einarbeitung Fehlerkatalog im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Aktenauszug Gerichtsverfahren.; Welche Unterlagen brauchen Sie?; Welcher Spezials... |
| `erstellen-fristennotiz-gerichtsverfahren` | Nutze dies, wenn Spezial Erstellen Fristennotiz Und Naechster Schritt, Spezial Gerichtsverfahren Fristen Form Und Zustaendigkeit, Spezial Verfahrensgeschichte Vergleich Eskalation im Plugin Aktenauszug Gerichtsverfahren konkret bearbeite... |
| `gegenueberstellung-parteivortraege` | Nutze dies, wenn Spezial Gegenueberstellung Zahlen Schwellen Und Berechnung, Spezial Parteivortraege Compliance Dokumentation Und Akte, Spezial Rechtsargumente Internationaler Bezug Und Schnittstellen im Plugin Aktenauszug Gerichtsverfah... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `parteivortrag-gegenueberstellung` | Nutze dies, wenn Parteivortrag Gegenueberstellung, Rechtsargumente Gegenueberstellung, Sachverhaltschronologie im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Bitte Parteivortrag Gegenueberstellung, Rech... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `sachverhaltschronologie-textbausteine` | Nutze dies, wenn Spezial Sachverhaltschronologie Textbausteine, Spezial Schnelle Formular Portal Und Einreichung, Spezial Stilrichtlinie Sonderfall Und Edge Case im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Aus... |
| `schwerpunktthemen-identifikation-akten` | Nutze dies, wenn Schwerpunktthemen Identifikation, Spezial Akten Mandantenkommunikation Entscheidungsvorlage, Spezial Aktenauszug Tatbestand Beweis Und Belege im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslös... |
| `strukturierter-strafprozess-modus` | Nutze dies, wenn Spezial Strukturierter Erstpruefung Und Mandatsziel, Strafprozess Modus, Verwaltungsprozess Modus im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Bitte Spezial Strukturierter Erstpruefun... |
| `tabellarische-quellenkarte` | Nutze dies, wenn Tabellarische Quellenkarte im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `verfahrensidentifikation` | Nutze dies, wenn Verfahrensidentifikation, Verfahrenszusammenfassung Absatz, Aktenauszug Erstellen im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Bitte Verfahrensidentifikation, Verfahrenszusammenfassun... |
| `verfahrensidentifikation-02` | Nutze dies, wenn Spezial Verfahrensidentifikation Dokumentenmatrix, Spezial Verfahrenszusammenfassung Rechtsweg Register, Verfahrenschronologie im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Bitte Spezi... |
| `zivilprozess-modus` | Nutze dies, wenn Zivilprozess Modus im Plugin Aktenauszug Gerichtsverfahren konkret bearbeitet werden soll. Auslöser: Bitte Zivilprozess Modus prüfen.; Erstelle eine Arbeitsfassung zu Zivilprozess Modus.; Welche Normen und Nachweise brau... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
