# Energierecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`energierecht`) | [`energierecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/energierecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Märkische Reserve Süd — Batteriespeicher Brandenburg/Berlin** (`batteriespeicher-brandenburg-berlin-resilienz`) | [Gesamt-PDF lesen](../testakten/batteriespeicher-brandenburg-berlin-resilienz/gesamt-pdf/batteriespeicher-brandenburg-berlin-resilienz_gesamt.pdf) | [`testakte-batteriespeicher-brandenburg-berlin-resilienz.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-batteriespeicher-brandenburg-berlin-resilienz.zip) |
| **Akte Energierecht: Stadtwerke Klotzkette AG – Quartier Hafenbogen** (`energierecht-stadtwerke-quartier`) | [Gesamt-PDF lesen](../testakten/energierecht-stadtwerke-quartier/gesamt-pdf/energierecht-stadtwerke-quartier_gesamt.pdf) | [`testakte-energierecht-stadtwerke-quartier.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-energierecht-stadtwerke-quartier.zip) |
| **Projekt Isarlicht — Kernfusion und Transrapid am Starnberger See** (`kernfusion-transrapid-starnberger-see`) | [Gesamt-PDF lesen](../testakten/kernfusion-transrapid-starnberger-see/gesamt-pdf/kernfusion-transrapid-starnberger-see_gesamt.pdf) | [`testakte-kernfusion-transrapid-starnberger-see.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kernfusion-transrapid-starnberger-see.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Vollständiger Energierechts-Assistent für Stadtwerke, Energieversorger, Wärmewirtschaft, energieintensive Unternehmen, Immobilienwirtschaft, Infrastrukturbetreiber, Contracting, Wasserstoff, E-Mobility, Transaktionen und Projektfinanzierung.

Dieses Plugin ist **vollständig freistehend**. Es erwartet keine anderen Plugins, keine externen Agenten und keine besonderen Repo-Dateien außerhalb seines eigenen Ordners. Wenn ein Anschluss an Register, Behördenportale, E-Mail, beA, Datenraum, Bank, GIS, Tabellen oder Kanzleisoftware fehlt, arbeitet es mit manuellen Uploads oder mit einem gekennzeichneten Simulationsmodus.

## Schnellstart

1. Plugin aktivieren oder die ZIP aus dem Release installieren.
2. Eine neue Sache mit `energierecht-kommandocenter` starten.
3. Mandant, Ziel, Frist, Dokumente und gewünschtes Ergebnis nennen.
4. Bei fehlenden Systemanschlüssen `Simulation` sagen; das Plugin erzeugt dann realistische Testdaten und erklärt, welche echte Schnittstelle später ersetzt werden müsste.
5. Am Ende immer das Qualitätstor ausgeben lassen: offene Annahmen, Fristen, Rechenprüfung, Anlagen, Zuständigkeiten und nächste Schritte.

## Enthaltene Skills

- `energierecht-kommandocenter` - Energierecht-Kommandocenter
- `energierecht-infrastrukturprojekte` - Energieinfrastrukturprojekte
- `energierecht-netz-speicher-zugang` - Netz-, Speicher- und Anschlussregulierung
- `energierecht-energievertraege` - Energieverträge
- `energierecht-vertrieb-marktrollen` - Energievertrieb und Marktrollen
- `energierecht-industriekunden` - Industriekunden und Kostenoptimierung
- `energierecht-eeg-kwkg-erzeugung` - EEG, KWKG und Erzeugung
- `energierecht-waerme-quartier` - Wärme, Quartier und Fernwärme
- `energierecht-emobility-wasserstoff` - E-Mobility, Wasserstoff und Power-to-Gas
- `energierecht-wettbewerb` - Energie und Wettbewerb
- `energierecht-verfahren` - Verwaltungs- und Gerichtsverfahren Energie
- `energierecht-transaktionen-dd` - Energierechtliche Transaktions-Due-Diligence
- `energierecht-projektfinanzierung` - Erneuerbare-Energien-Projektfinanzierung

## Vorlagen

- `assets/templates/energie-mandatskarte.md` - Energierecht-Mandatskarte
- `assets/templates/energie-projektphasenplan.md` - Projektphasenplan Energieinfrastruktur
- `assets/templates/netzanschluss-zugangsmatrix.md` - Netzanschluss- und Zugangsmatrix
- `assets/templates/energieliefervertrag-check.md` - Energieliefervertrag-Check
- `assets/templates/waerme-quartier-playbook.md` - Wärme- und Quartiers-Playbook
- `assets/templates/industrie-umlagen-check.md` - Industrie-Umlagen- und Entlastungscheck
- `assets/templates/eeg-kwkg-foerdermatrix.md` - EEG/KWKG-Fördermatrix
- `assets/templates/vertrieb-marktrollen-map.md` - Vertrieb- und Marktrollenkarte
- `assets/templates/transaktions-dd-energielaw.md` - Energierechtliche DD-Matrix
- `assets/templates/verwaltungsverfahren-energie.md` - Energie-Verfahrensplan
- `assets/templates/wasserstoff-ptg-check.md` - Wasserstoff- und Power-to-Gas-Check
- `assets/templates/energie-wettbewerb-uwg-kartell.md` - Energie-Wettbewerbscheck

## Freistehende Leitplanken

- Keine stillen Verweise auf andere Plugins.
- Keine produktive Rechtsberatung ohne anwaltliche Prüfung.
- Keine echten Mandatsgeheimnisse in ungeprüfte Cloud- oder KI-Umgebungen.
- Keine erfundenen Fundstellen; unsichere Normen und Rechtsprechung werden als Prüfbedarf markiert.
- Zahlen, Fristen, Schwellenwerte und Zuständigkeiten werden sichtbar hergeleitet oder als Annahme gekennzeichnet.
- Ausgabe immer so, dass eine Berufsträgerin oder ein Berufsträger sie sofort prüfen, kürzen, freigeben oder verwerfen kann.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 29 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anschluss` | Nutze dies bei Allgemein, Anschluss Skills Router, Chronologie Und Belegmatrix, Fristen Und Risikoampel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einfuehrung-energieprojekt-intake` | Nutze dies bei Einfuehrung Mandantenkommunikation Entscheidungsvorlage, Energieprojekt Intake Und Regulierungsweiche, Energierecht Erstpruefung Und Mandatsziel, Industrie Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich v... |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `energierecht-emobility-wasserstoff` | Nutze dies bei Energierecht Emobility Wasserstoff, Energierecht Energievertraege, Energierecht Industriekunden, Energierecht Infrastrukturprojekte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert d... |
| `energierecht-netz-speicher` | Nutze dies bei Energierecht Kommandocenter, Energierecht Netz Speicher Zugang, Energierecht Projektfinanzierung, Energierecht Transaktionen Dd: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den n... |
| `energierecht-vertrieb-marktrollen-waerme` | Nutze dies bei Energierecht Vertrieb Marktrollen, Energierecht Waerme Quartier, Energierecht Wettbewerb, Er Bess Abfall Recycling Rueckbau: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächs... |
| `er-bess-abstandsflaechen-baurecht-brandenburg` | Nutze dies bei Er Bess Abstandsflaechen Und Layout, Er Bess Baurecht Brandenburg, Er Bess Behoerdenstrategie, Er Bess Bimschg Und 4 Bimschv: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näch... |
| `er-bess-brandschutz-co-location-datenschutz` | Nutze dies bei Er Bess Brandschutz Lithium Ionen, Er Bess Co Location Pv Wind, Er Bess Datenschutz Video Leitwarte, Er Bess Dieselgenerator Notstrom: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `er-bess-epc-fca-agnes-finanzierung` | Nutze dies bei Er Bess Epc O And M Vertraege, Er Bess Fca Agnes Bnetza, Er Bess Finanzierung Bankability, Er Bess Kapazitaetsmarkt Grundlast: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näc... |
| `er-bess-er-bess-er-einfuehrung-er-fusion` | Nutze dies bei Er Bess Vergabe Kommunale Stadtwerke, Er Bess Wasser Awsv Und Boden, Er Einfuehrung System, Er Fusion Bauleitplanung Starnberger See: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `er-bess-er-bess-er-stakeholder-eeg-kwkg` | Nutze dies bei Er Bess Produktsicherheit Haftung, Er Bess Versicherung Und Schadenfall, Er Stakeholder Mapping Energie, Energierecht Eeg Kwkg Erzeugung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lief... |
| `er-bess-kaltstart-projektaufnahme` | Batteriespeicherprojekt aufnehmen: Projektgröße, Standort, Netzebene, Betreiberrolle, Fristen, Unterlagen und Zieloutput. |
| `er-bess-kritis-marktrollen-bilanzkreis` | Nutze dies bei Er Bess Kritis Nis2 Cyber, Er Bess Marktrollen Bilanzkreis, Er Bess Naturschutz Artenschutz, Er Bess Netzanschluss Hoehe Spannung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `er-bess-netzentgelte-board-physische` | Nutze dies bei Er Bess Netzentgelte Und Abgaben, Er Bess Output Board Paper, Er Bess Physische Sicherheit Terror, Er Bess Power Quality Emv: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näch... |
| `er-bess-ppa-projektakte-rechtsmittel` | Nutze dies bei Er Bess Ppa Und Merchant Risk, Er Bess Projektakte Qualitygate, Er Bess Rechtsmittel Und Nachbarabwehr, Er Bess Regelenergie Systemdienstleistung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `er-fusion-buergerbeteiligung-foerderung` | Nutze dies bei Er Fusion Buergerbeteiligung Und Politik, Er Fusion Foerderung Beihilfe, Er Fusion Netzanschluss Und Systemnutzen, Er Fusion Sicherheitsnachweis: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `er-fusion-er-fusion-er-h2-er-netzanschluss` | Nutze dies bei Er Fusion Strahlenschutz Neutronen, Er Fusion Transrapid Anbindung, Er H2 Electrolyseur Foerderung, Er Netzanschluss Praesumtion Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lief... |
| `er-fusion-kaltstart-regulierungsweg` | Ordnet Fusionsreaktor-Projekt zwischen Atomrecht, Strahlenschutz, Baurecht, Immissionsschutz und Forschungsförderung. |
| `er-netzentgelte-er-redispatch-er-typ-anfrage` | Nutze dies bei Er Netzentgelte Rechtsfragen, Er Redispatch 3 0 Spezial, Er Typ Anfrage Mandanten Routing, Anfrage Mehrparteien Konflikt Und Interessen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefe... |
| `kwkg-netzanschluss-netze-praesumtion-red` | Nutze dies bei Kwkg Verhandlung Vergleich Und Eskalation, Netzanschluss Formular Portal Und Einreichung, Netze Risikoampel Und Gegenargumente, Praesumtion Red Team Und Qualitaetskontrolle: führt durch diese fachlich verbundenen Module, w... |
| `livecheck-fristennotiz-versorger` | Nutze dies bei Livecheck Fristennotiz Und Naechster Schritt, Versorger Fristen Form Und Zustaendigkeit, Ladeinfrastruktur Vertragskette, Ppa Cppa Vertragsspezialitaeten: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `projektfinanzierung-stadtwerke-system` | Nutze dies bei Projektfinanzierung Compliance Dokumentation Und Akte, Routing Internationaler Bezug Und Schnittstellen, Stadtwerke Tatbestand Beweis Und Belege, System Beweislast Und Darlegungslast: führt durch diese fachlich verbundenen... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `rechtsquellen-sonderfall-edge-case` | Nutze dies zur Quellenprüfung bei Rechtsquellen: Sonderfall und Edge-Case-Prüfung: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `transaktionen-vertrieb-waerme` | Nutze dies bei Transaktionen Zahlen Schwellen Und Berechnung, Vertrieb Behörden Gericht Und Registerweg, Waerme Dokumentenmatrix Und Lueckenliste, Strompreisbremse Und Extras: führt durch diese fachlich verbundenen Module, wählt den pass... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `verfahren-quellenkarte` | Nutze dies zur Quellenprüfung bei Verfahren Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `waehlen` | Nutze dies bei Mandantenkommunikation, Output Waehlen, Redteam Qualitygate, Energierecht Verfahren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
