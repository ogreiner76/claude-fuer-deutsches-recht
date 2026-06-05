# Verkehrs- und Infrastrukturrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`verkehr-infrastrukturrecht`) | [`verkehr-infrastrukturrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/verkehr-infrastrukturrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Märkische Reserve Süd — Batteriespeicher Brandenburg/Berlin** (`batteriespeicher-brandenburg-berlin-resilienz`) | [Gesamt-PDF lesen](../testakten/batteriespeicher-brandenburg-berlin-resilienz/gesamt-pdf/batteriespeicher-brandenburg-berlin-resilienz_gesamt.pdf) | [`testakte-batteriespeicher-brandenburg-berlin-resilienz.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-batteriespeicher-brandenburg-berlin-resilienz.zip) |
| **Projekt Isarlicht — Kernfusion und Transrapid am Starnberger See** (`kernfusion-transrapid-starnberger-see`) | [Gesamt-PDF lesen](../testakten/kernfusion-transrapid-starnberger-see/gesamt-pdf/kernfusion-transrapid-starnberger-see_gesamt.pdf) | [`testakte-kernfusion-transrapid-starnberger-see.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kernfusion-transrapid-starnberger-see.zip) |
| **Akte Verkehrs- und Infrastrukturrecht: Straßenbahn Linie 7, Ladezonen und Schulwegsicherheit** (`verkehr-infrastrukturrecht-strassenbahn-ladezonen`) | [Gesamt-PDF lesen](../testakten/verkehr-infrastrukturrecht-strassenbahn-ladezonen/gesamt-pdf/verkehr-infrastrukturrecht-strassenbahn-ladezonen_gesamt.pdf) | [`testakte-verkehr-infrastrukturrecht-strassenbahn-ladezonen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verkehr-infrastrukturrecht-strassenbahn-ladezonen.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Vollständiger Assistent für Verkehrsplanung, Infrastrukturprojekte, Elektromobilität, Straßenbahn, Sondernutzung, Parkraumbewirtschaftung, Liefer- und Ladezonen, Verkehrswende, Schulwegsicherheit, Fördermittel und Vergabe.

Dieses Plugin ist **vollständig freistehend**. Es erwartet keine anderen Plugins, keine externen Agenten und keine besonderen Repo-Dateien außerhalb seines eigenen Ordners. Wenn ein Anschluss an Register, Behördenportale, E-Mail, beA, Datenraum, Bank, GIS, Tabellen oder Kanzleisoftware fehlt, arbeitet es mit manuellen Uploads oder mit einem gekennzeichneten Simulationsmodus.

## Schnellstart

1. Plugin aktivieren oder die ZIP aus dem Release installieren.
2. Eine neue Sache mit `verkehr-infrastrukturrecht-kommandocenter` starten.
3. Mandant, Ziel, Frist, Dokumente und gewünschtes Ergebnis nennen.
4. Bei fehlenden Systemanschlüssen `Simulation` sagen; das Plugin erzeugt dann realistische Testdaten und erklärt, welche echte Schnittstelle später ersetzt werden müsste.
5. Am Ende immer das Qualitätstor ausgeben lassen: offene Annahmen, Fristen, Rechenprüfung, Anlagen, Zuständigkeiten und nächste Schritte.

## Enthaltene Skills

- `verkehr-infrastrukturrecht-kommandocenter` - Verkehrs- und Infrastruktur-Kommandocenter
- `verkehr-infrastrukturrecht-verkehrsplanung` - Verkehrsplanung und Projektstrategie
- `verkehr-infrastrukturrecht-planfeststellung` - Planfeststellung und Abwägung
- `verkehr-infrastrukturrecht-strassenbahn` - Straßenbahn- und ÖPNV-Projekte
- `verkehr-infrastrukturrecht-ladeinfrastruktur` - Ladeinfrastruktur und Elektromobilität
- `verkehr-infrastrukturrecht-sondernutzung` - Sondernutzung, Widmung und Straßenrecht
- `verkehr-infrastrukturrecht-parkraumbewirtschaftung` - Parkraumbewirtschaftung
- `verkehr-infrastrukturrecht-wirtschaftsverkehr` - Wirtschaftsverkehr, Liefer- und Ladezonen
- `verkehr-infrastrukturrecht-verkehrswende` - Verkehrswende und Verkehrsberuhigung
- `verkehr-infrastrukturrecht-schulwegsicherheit` - Schulwegsicherheit
- `verkehr-infrastrukturrecht-verfahren` - Verkehrsrechtliche Verfahren und Streit
- `verkehr-infrastrukturrecht-foerderung-vergabe` - Förderung und Vergabe Infrastruktur

## Vorlagen

- `assets/templates/verkehr-mandatskarte.md` - Verkehrs- und Infrastruktur-Mandatskarte
- `assets/templates/infrastruktur-projektfahrplan.md` - Infrastruktur-Projektfahrplan
- `assets/templates/planfeststellung-abwaegungsmatrix.md` - Planfeststellungs- und Abwägungsmatrix
- `assets/templates/strassenbahn-workstream-plan.md` - Straßenbahn-Workstream-Plan
- `assets/templates/ladeinfrastruktur-check.md` - Ladeinfrastruktur-Check
- `assets/templates/sondernutzung-erlaubnis.md` - Sondernutzung und Straßenrecht
- `assets/templates/parkraumkonzept.md` - Parkraumbewirtschaftungskonzept
- `assets/templates/liefer-ladeflaechen-konzept.md` - Liefer- und Ladeflächenkonzept
- `assets/templates/verkehrswende-massnahmenplan.md` - Verkehrswende-Maßnahmenplan
- `assets/templates/schulwegsicherheit-check.md` - Schulwegsicherheitscheck
- `assets/templates/verkehrsverfahren-fristen.md` - Verkehrs-Verfahrens- und Fristenplan
- `assets/templates/foerderung-vergabe-matrix.md` - Förder- und Vergabematrix

## Freistehende Leitplanken

- Keine stillen Verweise auf andere Plugins.
- Keine produktive Rechtsberatung ohne anwaltliche Prüfung.
- Keine echten Mandatsgeheimnisse in ungeprüfte Cloud- oder KI-Umgebungen.
- Keine erfundenen Fundstellen; unsichere Normen und Rechtsprechung werden als Prüfbedarf markiert.
- Zahlen, Fristen, Schwellenwerte und Zuständigkeiten werden sichtbar hergeleitet oder als Annahme gekennzeichnet.
- Ausgabe immer so, dass eine Berufsträgerin oder ein Berufsträger sie sofort prüfen, kürzen, freigeben oder verwerfen kann.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anschluss-router` | Nutze dies, wenn Allgemein, Workflow Anschluss Skills Router, Workflow Chronologie Und Belegmatrix im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Anschluss Skills Router, Workflow... |
| `autonomous-driving-interessen-grossprojekt` | Nutze dies, wenn Spezial Autonomous Compliance Dokumentation Und Akte, Spezial Driving Mehrparteien Konflikt Und Interessen, Spezial Grossprojekt Zahlen Schwellen Und Berechnung im Plugin Verkehr Infrastrukturrecht konkret bearbeitet wer... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Verkehr Infrastrukturrecht.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill p... |
| `foerderung-vergabe-ladeinfrastruktur` | Nutze dies, wenn Verkehr Infrastrukturrecht Foerderung Vergabe, Verkehr Infrastrukturrecht Ladeinfrastruktur, Verkehr Infrastrukturrecht Planfeststellung im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Bitt... |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies, wenn Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation, Workflow Redteam Qualitygate im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team pr... |
| `infrastruktur-foerderung-nachhaltige` | Nutze dies, wenn Infrastruktur Foerderung Uebersicht, Nachhaltige Bahninfrastruktur Emissionen, Planfeststellung Grundzuege im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Bitte Infrastruktur Foerderung Ueb... |
| `infrastrukturrecht-intake-ladeinfrastruktur` | Nutze dies, wenn Spezial Infrastrukturrecht Tatbestand Beweis Und Belege, Spezial Intake Mandantenkommunikation Entscheidungsvorlage, Spezial Ladeinfrastruktur Behörden Gericht Und Registerweg im Plugin Verkehr Infrastrukturrecht konkret... |
| `livecheck-sonderfall-mobilitaetsprojekt` | Nutze dies, wenn Spezial Livecheck Sonderfall Und Edge Case, Spezial Mobilitaetsprojekt Intake, Spezial Mobilitaetsprojekt Red Team Und Qualitaetskontrolle im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: We... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `parkraum-planfeststellung-strassenbahn` | Nutze dies, wenn Spezial Parkraum Schriftsatz Brief Und Memo Bausteine, Spezial Planfeststellung Dokumentenmatrix Und Lueckenliste, Spezial Strassenbahn Risikoampel Und Gegenargumente im Plugin Verkehr Infrastrukturrecht konkret bearbeit... |
| `parkraumbewirtschaftung-verkehr` | Nutze dies, wenn Spezial Parkraumbewirtschaftung Formular Portal Und Einreichung, Verkehr Infrastrukturrecht Parkraumbewirtschaftung, Spezial Planfeststellung Grossprojekt im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden so... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `rechtsquellen-beweislast-darlegungslast` | Nutze dies, wenn Rechtsquellen: Beweislast, Darlegungslast und Substantiierung im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bit... |
| `schulwegsicherheit-sondernutzung-strassenbahn` | Nutze dies, wenn Verkehr Infrastrukturrecht Schulwegsicherheit, Verkehr Infrastrukturrecht Sondernutzung, Verkehr Infrastrukturrecht Strassenbahn im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Bitte Verkeh... |
| `strassenrecht-verkehrs-verkehrswende` | Nutze dies, wenn Spezial Strassenrecht Internationaler Bezug Und Schnittstellen, Spezial Verkehrs Erstpruefung Und Mandatsziel, Spezial Verkehrswende Verhandlung Vergleich Und Eskalation im Plugin Verkehr Infrastrukturrecht konkret bearb... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `verkehr-infrastrukturrecht-autonomous-driving` | Nutze dies, wenn Verkehr Infrastrukturrecht Kommandocenter, Autonomous Driving Strassenrecht, Buergerentscheid Strassenbahn Spezial im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Bitte Verkehr Infrastruktu... |
| `verkehr-quellenkarte` | Nutze dies, wenn Verkehr Quellenkarte im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `verkehrsplanung-verfahren-vertragsmodell` | Nutze dies, wenn Spezial Verkehrsplanung Fristen Form Und Zustaendigkeit, Verkehr Infrastrukturrecht Verfahren, Vertragsmodell Strasse App Spezial im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Bitte Spezi... |
| `verkehrsplanung-verkehrswende` | Nutze dies, wenn Verkehr Infrastrukturrecht Verkehrsplanung, Verkehr Infrastrukturrecht Verkehrswende, Verkehr Infrastrukturrecht Wirtschaftsverkehr im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Bitte Ver... |
| `vi-rechtsquellen-uebersicht` | Rechtsquellen Verkehrs- und Infrastrukturrecht: BFStrG, PBefG, AEG, EnWG-Trasse, BImSchG, BNatSchG, WHG, VwVfG, UVPG. Pro Norm: Anwendungsbereich, Verfahrensart, Aufsicht. Entscheidungstabelle fuer ein konkretes Infrastrukturvorhaben. |
| `vifr-aeg-bahnrecht-deutschlandticket` | Nutze dies, wenn Vifr Aeg Bahnrecht Leitfaden, Vifr Deutschlandticket Tarifrecht Spezial, Vifr Luftverkehrsrecht Flughafen Spezial im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Bitte Vifr Aeg Bahnrecht Le... |
| `vifr-planfeststellung` | Nutze dies, wenn Vifr Planfeststellung Strasse Bauleiter im Plugin Verkehr Infrastrukturrecht konkret bearbeitet werden soll. Auslöser: Bitte Vifr Planfeststellung Strasse Bauleiter prüfen.; Erstelle eine Arbeitsfassung zu Vifr Planfests... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
