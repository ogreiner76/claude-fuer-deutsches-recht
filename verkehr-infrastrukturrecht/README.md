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
| `anschluss-router` | Nutze dies bei Allgemein, Anschluss Skills Router, Chronologie Und Belegmatrix, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `autonomous-driving-interessen-grossprojekt` | Nutze dies bei Autonomous Compliance Dokumentation Und Akte, Driving Mehrparteien Konflikt Und Interessen, Grossprojekt Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lief... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `foerderung-vergabe-ladeinfrastruktur` | Nutze dies bei Verkehr Infrastrukturrecht Foerderung Vergabe, Verkehr Infrastrukturrecht Ladeinfrastruktur, Verkehr Infrastrukturrecht Planfeststellung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lief... |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies bei Fristen Und Risikoampel, Mandantenkommunikation, Redteam Qualitygate: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `infrastruktur-foerderung-nachhaltige` | Nutze dies bei Infrastruktur Foerderung Uebersicht, Nachhaltige Bahninfrastruktur Emissionen, Planfeststellung Grundzuege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren A... |
| `infrastrukturrecht-intake-ladeinfrastruktur` | Nutze dies bei Infrastrukturrecht Tatbestand Beweis Und Belege, Intake Mandantenkommunikation Entscheidungsvorlage, Ladeinfrastruktur Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen Module, wählt den passenden Pr... |
| `livecheck-sonderfall-mobilitaetsprojekt` | Nutze dies bei Livecheck Sonderfall Und Edge Case, Mobilitaetsprojekt Intake, Mobilitaetsprojekt Red Team Und Qualitaetskontrolle: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belas... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `parkraum-planfeststellung-strassenbahn` | Nutze dies bei Parkraum Schriftsatz Brief Und Memo Bausteine, Planfeststellung Dokumentenmatrix Und Lueckenliste, Strassenbahn Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad un... |
| `parkraumbewirtschaftung-verkehr` | Nutze dies bei Parkraumbewirtschaftung Formular Portal Und Einreichung, Verkehr Infrastrukturrecht Parkraumbewirtschaftung, Planfeststellung Grossprojekt: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und li... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `rechtsquellen-beweislast-darlegungslast` | Nutze dies zur Quellenprüfung bei Rechtsquellen: Beweislast, Darlegungslast und Substantiierung: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `schulwegsicherheit-sondernutzung-strassenbahn` | Nutze dies bei Verkehr Infrastrukturrecht Schulwegsicherheit, Verkehr Infrastrukturrecht Sondernutzung, Verkehr Infrastrukturrecht Strassenbahn: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `strassenrecht-verkehrs-verkehrswende` | Nutze dies bei Strassenrecht Internationaler Bezug Und Schnittstellen, Verkehrs Erstpruefung Und Mandatsziel, Verkehrswende Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `verkehr-infrastrukturrecht-autonomous-driving` | Nutze dies bei Verkehr Infrastrukturrecht Kommandocenter, Autonomous Driving Strassenrecht, Buergerentscheid Strassenbahn Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belas... |
| `verkehr-quellenkarte` | Nutze dies zur Quellenprüfung bei Verkehr Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `verkehrsplanung-verfahren-vertragsmodell` | Nutze dies bei Verkehrsplanung Fristen Form Und Zustaendigkeit, Verkehr Infrastrukturrecht Verfahren, Vertragsmodell Strasse App Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächste... |
| `verkehrsplanung-verkehrswende` | Nutze dies bei Verkehr Infrastrukturrecht Verkehrsplanung, Verkehr Infrastrukturrecht Verkehrswende, Verkehr Infrastrukturrecht Wirtschaftsverkehr: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert d... |
| `vi-rechtsquellen-uebersicht` | Rechtsquellen Verkehrs- und Infrastrukturrecht: BFStrG, PBefG, AEG, EnWG-Trasse, BImSchG, BNatSchG, WHG, VwVfG, UVPG. Pro Norm: Anwendungsbereich, Verfahrensart, Aufsicht. Entscheidungstabelle fuer ein konkretes Infrastrukturvorhaben. |
| `vifr-aeg-bahnrecht-deutschlandticket` | Nutze dies bei Vifr Aeg Bahnrecht Leitfaden, Vifr Deutschlandticket Tarifrecht Spezial, Vifr Luftverkehrsrecht Flughafen Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belast... |
| `vifr-planfeststellung` | Nutze dies bei Vifr Planfeststellung Strasse Bauleiter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
