# Umweltrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`umweltrecht`) | [`umweltrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/umweltrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Märkische Reserve Süd — Batteriespeicher Brandenburg/Berlin** (`batteriespeicher-brandenburg-berlin-resilienz`) | [Gesamt-PDF lesen](../testakten/batteriespeicher-brandenburg-berlin-resilienz/gesamt-pdf/batteriespeicher-brandenburg-berlin-resilienz_gesamt.pdf) | [`testakte-batteriespeicher-brandenburg-berlin-resilienz.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-batteriespeicher-brandenburg-berlin-resilienz.zip) |
| **Projekt Isarlicht — Kernfusion und Transrapid am Starnberger See** (`kernfusion-transrapid-starnberger-see`) | [Gesamt-PDF lesen](../testakten/kernfusion-transrapid-starnberger-see/gesamt-pdf/kernfusion-transrapid-starnberger-see_gesamt.pdf) | [`testakte-kernfusion-transrapid-starnberger-see.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kernfusion-transrapid-starnberger-see.zip) |
| **Akte Umweltrecht: Industrieanlage — Genehmigung, Emissionshandel, Altlast und Transaktion** (`umweltrecht-industrieanlage-genehmigung`) | [Gesamt-PDF lesen](../testakten/umweltrecht-industrieanlage-genehmigung/gesamt-pdf/umweltrecht-industrieanlage-genehmigung_gesamt.pdf) | [`testakte-umweltrecht-industrieanlage-genehmigung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-umweltrecht-industrieanlage-genehmigung.zip) |
| **Umweltverbandsakte Moorbach** (`umweltschutzverband-windpark-moorbach-umwrg`) | [Gesamt-PDF lesen](../testakten/umweltschutzverband-windpark-moorbach-umwrg/gesamt-pdf/umweltschutzverband-windpark-moorbach-umwrg_gesamt.pdf) | [`testakte-umweltschutzverband-windpark-moorbach-umwrg.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-umweltschutzverband-windpark-moorbach-umwrg.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Vollständiger Umweltrechts-Assistent für Anlagenbetreiber, Verbände, Investoren, Kommunen und öffentliche Hand: Emissionshandel, Immissionsschutz, Abfall, Wasser, Boden, Naturschutz, Umweltinformation, Verfahren, Sanktionen und Transaktionen.

Dieses Plugin ist **vollständig freistehend**. Es erwartet keine anderen Plugins, keine externen Agenten und keine besonderen Repo-Dateien außerhalb seines eigenen Ordners. Wenn ein Anschluss an Register, Behördenportale, E-Mail, beA, Datenraum, Bank, GIS, Tabellen oder Kanzleisoftware fehlt, arbeitet es mit manuellen Uploads oder mit einem gekennzeichneten Simulationsmodus.

## Schnellstart

1. Plugin aktivieren oder die ZIP aus dem Release installieren.
2. Eine neue Sache mit `umweltrecht-kommandocenter` starten.
3. Mandant, Ziel, Frist, Dokumente und gewünschtes Ergebnis nennen.
4. Bei fehlenden Systemanschlüssen `Simulation` sagen; das Plugin erzeugt dann realistische Testdaten und erklärt, welche echte Schnittstelle später ersetzt werden müsste.
5. Am Ende immer das Qualitätstor ausgeben lassen: offene Annahmen, Fristen, Rechenprüfung, Anlagen, Zuständigkeiten und nächste Schritte.

## Enthaltene Skills

- `umweltrecht-kommandocenter` - Umweltrecht-Kommandocenter
- `umweltrecht-emissionshandel-tehg` - Emissionshandel und TEHG
- `umweltrecht-immissionsschutz-bimschg` - Immissionsschutz und BImSchG
- `umweltrecht-stoerfall-anlagen` - Störfall, Anlagenbetrieb und Betreiberpflichten
- `umweltrecht-abfall-circular-economy` - Abfallrecht und Circular Economy
- `umweltrecht-wasser-bodenschutz` - Wasser- und Bodenschutzrecht
- `umweltrecht-naturschutz-artenschutz` - Naturschutz und Artenschutz
- `umweltrecht-umweltinformation-uig-ifg` - Umweltinformation nach UIG und IFG
- `umweltrecht-verfahren` - Umweltrechtliche Verwaltungs- und Gerichtsverfahren
- `umweltrecht-bussgeld-sanktionen` - Bußgeld, Sanktionen und Anhörung
- `umweltrecht-transaktionen-dd` - Umweltrechtliche Transaktions-Due-Diligence
- `umweltrecht-compliance-schulung` - Compliance, Beauftragte und Schulung
- `klimaklagen-verbandsklage-umwrg` - Klimaklagen, Verbandsklage UmwRG, EGMR Klima-Seniorinnen
- `lksg-csddd-lieferkettensorgfalt` - Lieferkettensorgfalt LkSG und CSDDD-Richtlinie (EU) 2024/1760
- `esg-greenwashing-csrd` - ESG-Greenwashing, CSRD-Umsetzung, ESRS, UWG-Werbung

## Vorlagen

- `assets/templates/umwelt-mandatskarte.md` - Umweltrecht-Mandatskarte
- `assets/templates/tehg-zuteilung-check.md` - TEHG-Zuteilungs- und Sanktionscheck
- `assets/templates/bimschg-genehmigungsfahrplan.md` - BImSchG-Genehmigungsfahrplan
- `assets/templates/stoerfall-anlagenmatrix.md` - Störfall- und Anlagenpflichtenmatrix
- `assets/templates/abfall-circular-matrix.md` - Abfall- und Circular-Economy-Matrix
- `assets/templates/wasser-boden-pruefplan.md` - Wasser- und Boden-Prüfplan
- `assets/templates/naturschutz-artenschutz-check.md` - Naturschutz- und Artenschutzcheck
- `assets/templates/uig-ifg-verfahren.md` - UIG/IFG-Verfahrenskarte
- `assets/templates/umweltverfahren-fristen.md` - Umwelt-Verfahrens- und Fristenplan
- `assets/templates/bussgeld-verteidigungsplan.md` - Bußgeld-Verteidigungsplan Umwelt
- `assets/templates/umwelt-dd-grid.md` - Umwelt-DD-Grid
- `assets/templates/schulung-beauftragte-plan.md` - Schulungs- und Beauftragtenplan

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
| `abfall-anlagen-bimschg` | Nutze dies bei Abfall Dokumentenmatrix Und Lueckenliste, Anlagen Abschlussprodukt Und Uebergabe, Bimschg Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten b... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `boden-csddd-csrd-sonderfall` | Nutze dies bei Boden Behörden Gericht Und Registerweg, Csddd Mandantenkommunikation Entscheidungsvorlage, Csrd Sonderfall Und Edge Case: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `bussgeld-quellenkarte` | Nutze dies zur Quellenprüfung bei Bussgeld Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `diligence-greenwashing-beweislast-klimaklagen` | Nutze dies bei Diligence Compliance Dokumentation Und Akte, Greenwashing Beweislast Und Darlegungslast, Klimaklagen Mehrparteien Konflikt Und Interessen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `esg-greenwashing-klimaklagen-verbandsklage` | Nutze dies bei Esg Greenwashing Csrd, Klimaklagen Verbandsklage Umwrg, Lksg Csddd Lieferkettensorgfalt: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `lieferkettensorgfalt-lksg-red-naturschutz` | Nutze dies bei Lieferkettensorgfalt Formular Portal Und Einreichung, Lksg Red Team Und Qualitaetskontrolle, Naturschutz Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `stoerfall` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Stoerfall Fristennotiz Und Naechster Schritt: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `stoerfall-anlagen-transaktionen-dd` | Nutze dies bei Umweltrecht Stoerfall Anlagen, Umweltrecht Transaktionen Dd, Umweltrecht Umweltinformation Uig Ifg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitssc... |
| `tehg-verfahren-umweltrecht-verfahren` | Nutze dies bei Tehg Fristen Form Und Zustaendigkeit, Verfahren Verhandlung Vergleich Und Eskalation, Umweltrecht Verfahren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `umwelt-umweltrecht-umwrg` | Nutze dies bei Umwelt Zahlen Schwellen Und Berechnung, Umweltrecht Erstpruefung Und Mandatsziel, Umwrg Internationaler Bezug Und Schnittstellen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `umweltrecht-bussgeld-emissionshandel-tehg-uwr` | Nutze dies bei Umweltrecht Bussgeld Sanktionen, Umweltrecht Emissionshandel Tehg, Uwr Emissionshandel Ets Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitssc... |
| `umweltrecht-immissionsschutz-bimschg` | Nutze dies bei Umweltrecht Immissionsschutz Bimschg, Umweltrecht Kommandocenter, Umweltrecht Naturschutz Artenschutz: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `uwr-bundesnaturschutzgesetz-uwr-co2-uwr` | Nutze dies bei Uwr Bundesnaturschutzgesetz Eingriff Spezial, Uwr Co2 Emissionshandel Spezial, Uwr Immissionsschutz Praxis: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren A... |
| `uwr-einfuehrung-rechtsquellen` | Umweltrecht einfuehrend: BImSchG, BNatSchG, WHG, KrWG, BBodSchG, USchadG, EU-IED, REACH. Pro Norm Anwendungsbereich, Aufsicht, typische Mandantenfragen. Entscheidungstabelle. |
| `uwr-wasserrechtliche` | Nutze dies bei Uwr Wasserrechtliche Erlaubnis Leitfaden: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `wasser-abfall-circular-umweltrecht-schulung` | Nutze dies bei Wasser Risikoampel Und Gegenargumente, Umweltrecht Abfall Circular Economy, Umweltrecht Compliance Schulung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `wasser-bodenschutz-uwr-altlasten-uwr-bimschg` | Nutze dies bei Umweltrecht Wasser Bodenschutz, Uwr Altlasten Prüfung Spezial, Uwr Bimschg Genehmigung Bauleiter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschr... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
