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
| `einfuehrung-energieprojekt-intake` | Einfuehrung Energieprojekt Intake im Plugin Energierecht: prüft konkret Einfuehrung, Energieprojekt-Intake mit Regulierungs-, Netz- und Förderweiche, Energierecht. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem... |
| `energie-bess-produktsicherheit-haftung-versicherung-schadenfall` | Energie Bess Produktsicherheit Haftung Versicherung Schadenfall im Plugin Energierecht: prüft konkret Prüft Batteriecontainer, BMS, Wechselrichter, Herstellerdokumentation. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und... |
| `energie-bess-vergabe-kommunale-wasser-awsv-einfuehrung-system` | Energie Bess Vergabe Kommunale Wasser Awsv Einfuehrung System im Plugin Energierecht: prüft konkret Prüft, ob Stadtwerk, Kommune oder öffentlich beherrschte Gesellschaft Vergaberec, Prüft Kühlmittel. Liefert priorisierten Output mit Norm... |
| `energie-fusion-strahlenschutz-neutronen-transrapid-anbindung-h2` | Energie Fusion Strahlenschutz Neutronen Transrapid Anbindung H2 im Plugin Energierecht: prüft konkret Prüft Strahlenschutzfragen, Aktivierung von Materialien, Überwachung, Dosismanag. Liefert priorisierten Output mit Norm-Pinpoints, Risi... |
| `energie-mandantenkommunikation-output-waehlen-redteam` | Energie Mandantenkommunikation Output Waehlen Redteam im Plugin Energierecht: prüft konkret Mandantenkommunikation im Plugin energierecht, Output wählen im Plugin energierecht, Red-Team Qualitygate im Plugin energierecht, Regulierungsver... |
| `energie-netzentgelte-rechtsfragen-redispatch-spezial-typ-anfrage` | Energie Netzentgelte Rechtsfragen Redispatch Spezial TYP Anfrage im Plugin Energierecht: prüft konkret Netzentgelte aktuell, Spezialfall Redispatch 3.0, Anfrage-Routing im Energierecht, Anfrage. Liefert priorisierten Output mit Norm-Pinp... |
| `energierecht-anschluss` | Anschluss im Plugin Energierecht: prüft konkret Einstieg, Schnelltriage und Fallrouting im Energierecht-Plugin, Zie, Anschluss-Skills Router im Plugin energierecht. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächste... |
| `energierecht-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `energierecht-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `energierecht-emobility-wasserstoff` | Emobility Wasserstoff im Plugin Energierecht: prüft konkret Rechtliche Rahmenbedingungen für Elektromobilitaet und, Energieliefervertraege prüfen und entwerfen, Sonderregelungen für Industriekunden im Energierecht, Energieinfrastrukturpr... |
| `energierecht-netz-speicher` | Netz Speicher im Plugin Energierecht: prüft konkret Navigationszentrum für alle Energierecht-Skills, Netzanschluss und Netzzugang für Erzeugungsanlagen und, Projektfinanzierung für Energieanlagen strukturieren, Due Diligence bei Energier... |
| `energierecht-quellen-livecheck` | Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `energierecht-rechtsquellen-sonderfall-edge-case` | Rechtsquellen: Quellenprüfung; Sonderfall und Edge-Case-Prüfung: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `energierecht-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `energierecht-vertrieb-marktrollen-waerme` | Vertrieb Marktrollen Waerme im Plugin Energierecht: prüft konkret Energievertrieb und Marktrollen im liberalisierten, Waermenetze und Quartiersversorgung rechtlich strukturieren, Wettbewerbs- und Kartellrecht im Energiesektor prüfen, Prü... |
| `er-bess-abstandsflaechen-baurecht-brandenburg` | ER Bess Abstandsflaechen Baurecht Brandenburg im Plugin Energierecht: prüft konkret Prüft Containerabstände, Transformatoren, Umrichter, Zaun. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `er-bess-brandschutz-co-location-datenschutz` | ER Bess Brandschutz CO Location Datenschutz im Plugin Energierecht: prüft konkret Prüft Brandabschnitte, Abstände, Löschwasserkonzept, Thermal Runaway. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `er-bess-epc-fca-agnes-finanzierung` | ER Bess EPC FCA Agnes Finanzierung im Plugin Energierecht: prüft konkret Prüft Bau-/Liefervertrag, O&M, Garantien, Degradation. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `er-bess-kaltstart-projektaufnahme` | Batteriespeicherprojekt aufnehmen: Projektgröße, Standort, Netzebene, Betreiberrolle, Fristen, Unterlagen und Zieloutput. |
| `er-bess-kritis-marktrollen-bilanzkreis` | ER Bess Kritis Marktrollen Bilanzkreis im Plugin Energierecht: prüft konkret Prüft, ob Speicher, Leitwarte, Netzanschluss oder Betreiber kritische Anlage/IT-. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schr... |
| `er-bess-netzentgelte-board-physische` | ER Bess Netzentgelte Board Physische im Plugin Energierecht: prüft konkret Prüft Strombezug, Einspeicherung, Ausspeicherung, Netzentgelte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `er-bess-ppa-projektakte-rechtsmittel` | ER Bess PPA Projektakte Rechtsmittel im Plugin Energierecht: prüft konkret Prüft Erlösverträge für Speicher, Prüft die gesamte Speicherakte auf Lücken, Widersprüche, fehlende Quellen. Liefert priorisierten Output mit Norm-Pinpoints, Risi... |
| `er-fusion-buergerbeteiligung-foerderung` | ER Fusion Buergerbeteiligung Foerderung im Plugin Energierecht: prüft konkret Plant Beteiligung, Umweltinformationen, Presse, Einwendungen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `er-fusion-kaltstart-regulierungsweg` | Ordnet Fusionsreaktor-Projekt zwischen Atomrecht, Strahlenschutz, Baurecht, Immissionsschutz und Forschungsförderung. |
| `kwkg-netzanschluss-netze-praesumtion-red` | Kwkg Netzanschluss Netze Praesumtion RED im Plugin Energierecht: prüft konkret Kwkg, Netzanschluss, Netze, Praesumtion. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `livecheck-fristennotiz-versorger` | Livecheck Fristennotiz Versorger im Plugin Energierecht: prüft konkret Livecheck, Versorger, Spezialfall Ladeinfrastruktur, PPA und Corporate PPA Vertragsspezialitaeten. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nä... |
| `projektfinanzierung-stadtwerke-system` | Projektfinanzierung Stadtwerke System im Plugin Energierecht: prüft konkret Projektfinanzierung, Routing, Stadtwerke, System. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `transaktionen-vertrieb-waerme` | Transaktionen Vertrieb Waerme im Plugin Energierecht: prüft konkret Transaktionen, Vertrieb, Waerme, Strompreisbremse. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `verfahren-quellenkarte` | Verfahren Quellenkarte: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
