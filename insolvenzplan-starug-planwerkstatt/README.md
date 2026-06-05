# Insolvenzplan- und StaRUG-Planwerkstatt

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`insolvenzplan-starug-planwerkstatt`) | [`insolvenzplan-starug-planwerkstatt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/insolvenzplan-starug-planwerkstatt.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Metallbau Hansa GmbH – Insolvenzplan und StaRUG-Restrukturierung** (`insolvenzplan-starug-planwerkstatt-metallbau-hansa`) | [Gesamt-PDF lesen](../testakten/insolvenzplan-starug-planwerkstatt-metallbau-hansa/gesamt-pdf/insolvenzplan-starug-planwerkstatt-metallbau-hansa_gesamt.pdf) | [`testakte-insolvenzplan-starug-planwerkstatt-metallbau-hansa.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-insolvenzplan-starug-planwerkstatt-metallbau-hansa.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Cowork-Plugin für die Erstellung, Prüfung und Härtung von Insolvenzplänen und StaRUG-Restrukturierungsplänen. Es führt vom Kaltstart über Datenraum, Sanierungskonzept, integrierte Planung, Vergleichsrechnung, Gruppen- und Klassenbildung, darstellenden und gestaltenden Teil, Anlagen, Abstimmung, Cram-down, Minderheitenschutz, gerichtliche Schritte und Planvollzug bis zum Monitoring.

## Wofür das Plugin gedacht ist

- Insolvenzplan im Regelverfahren, in Eigenverwaltung und im Schutzschirm.
- StaRUG-Restrukturierungsplan mit Auswahl der Planbetroffenen, Gruppen, Abstimmung, gerichtlichen Instrumenten und Stabilisierung.
- Vergleichsrechnung als zentrales Entscheidungselement mit Planfall, Fortführung ohne Plan, Liquidation, Sicherheiten, Sonderaktiva und Planmehrwert.
- Sanierungskonzept, integrierte Ertrags-, Finanz- und Liquiditätsplanung sowie Maßnahmenprogramm.
- Gerichtsfeste Entwurfsarbeit mit Anlagen, Red-Team-Prüfung, Freigabeampel und Planvollzug.

## Leitprinzip

Das Plugin ist verzeihend im Intake und streng im Ergebnis. Es darf mit chaotischen Tabellen, unvollständigen OPOS-Listen, widersprüchlichen Sicherheitenangaben und unfertigen Managementannahmen starten. Es macht daraus aber keinen scheinbar fertigen Plan. Jede Annahme bleibt sichtbar, jede Zahl bekommt eine Quelle oder Warnung, jede Rechtswirkung wird auf Bestimmtheit, Vergleichsrechnung und Minderheitenschutz zurückgeführt.

## Typischer Ablauf

1. Kaltstart: Rolle, Route, Schuldnerdaten, Krise, Zielbild, Gericht, Fristen und verfügbare Unterlagen erfassen.
2. Datenraum: Jahresabschlüsse, BWA, SuSa, OPOS, Liquidität, Verträge, Sicherheiten, Personal, Steuern und Organunterlagen sortieren.
3. Sanierung: Krisenursachen, Maßnahmen, Fortführungsfähigkeit, Stakeholderbeiträge und integrierte Planung erarbeiten.
4. Vergleich: Planfall, Ohne-Plan-Szenario, Sicherheitenwerte, Sonderaktiva, Kosten, Quoten und Planmehrwert berechnen.
5. Plan bauen: Darstellender Teil, gestaltender Teil, Gruppen oder Klassen, Anlagen, Abstimmung und gerichtliche Route entwerfen.
6. Härtung: Cram-down, Minderheitenschutz, Bestätigungsrisiken, Einwände und Vollzug red-teamen.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| ips-kommandocenter | Route, Material, Risiken und nächste Ausgaben steuern. |
| ips-verfahrenswahl | Den passenden Sanierungsrahmen auswählen. |
| ips-kaltstart-interview | Aus wenigen Angaben eine belastbare Arbeitsakte machen. |
| ips-datenraum-register | Alle Planbausteine belegbar machen. |
| ips-sanierungskonzept | Das wirtschaftliche Fundament des Plans herstellen. |
| ips-integrierte-planung | Zahlen konsistent, nachvollziehbar und gerichtsfähig machen. |
| ips-vergleichsrechnung | Herzstück des Plans rechnen und erklären. |
| ips-insolvenzplan-architektur | Einen vollständigen InsO-Plan strukturieren. |
| ips-starug-plan-architektur | Einen vollständigen Restrukturierungsplan strukturieren. |
| ips-darstellender-teil | Die Entscheidungsgrundlage vollständig machen. |
| ips-gestaltender-teil | Rechtswirkungen bestimmt und vollziehbar formulieren. |
| ips-gruppen-klassenbildung | Abstimmungsarchitektur belastbar machen. |
| ips-sicherheiten-drittsicherheiten | Besicherte Positionen planfest und wertklar behandeln. |
| ips-planbetroffene-auswahl | StaRUG-Eingriffe fokussiert und begründet halten. |
| ips-abstimmung-mehrheiten | Mehrheiten vor dem Termin realistisch prüfen. |
| ips-cramdown-obstruktion | Ablehnende Gruppen gerichtsfest einordnen. |
| ips-minderheitenschutz | Opposition ernst nehmen und Planangriff vermeiden. |
| ips-anlagenpaket | Nichts einreichen, was Anlagenlücken hat. |
| ips-gerichtliche-schritte | Verfahren und Gerichtskommunikation steuern. |
| ips-stabilisierung-starug | Zeit kaufen, ohne die Planroute zu beschädigen. |
| ips-planvollzug-monitoring | Nach Bestätigung die Umsetzung führen. |
| ips-steuern-bilanz-folgen | Planwirkungen nicht an Nebenfolgen scheitern lassen. |
| ips-stakeholder-kommunikation | Akzeptanz für den Plan organisieren. |
| ips-redteam-qualitygate | Den Plan vor Gegnern und Gericht hart prüfen. |

## Grenzen

Das Plugin ersetzt keine anwaltliche, steuerliche oder betriebswirtschaftliche Endprüfung. Es ist ein Arbeits-, Strukturierungs- und Qualitätssicherungswerkzeug. Bei Planbestätigung, gerichtlicher Einreichung, steuerlichen Folgen, Organpflichten, Sicherheitenwerten, Drittsicherheiten und streitigen Gläubigerrechten verlangt es menschliche Freigabe.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `abstimmung-anlagen-interessen-cram` | Nutze dies bei Abstimmung Internationaler Bezug Und Schnittstellen, Anlagen Mehrparteien Konflikt Und Interessen, Cram Formular Portal Und Einreichung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefe... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `darstellender-quellenkarte` | Nutze dies zur Quellenprüfung bei Darstellender Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `down-red-gestaltender-gruppen` | Nutze dies bei Down Red Team Und Qualitaetskontrolle, Gestaltender Zahlen Schwellen Und Berechnung, Gruppen Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `insolvenzplan-intake-klassen` | Nutze dies bei Insolvenzplan Erstpruefung Und Mandatsziel, Intake Dokumentenmatrix Und Lueckenliste, Klassen Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert de... |
| `ips-abstimmung-ips-anlagenpaket-ips-asset` | Nutze dies bei Ips Abstimmung Mehrheiten, Ips Anlagenpaket, Ips Asset Deals Im Plan Grundstuecke Marken Kundendaten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeits... |
| `ips-cramdown-ips-datenraum-ips-gestaltender` | Nutze dies bei Ips Cramdown Obstruktion, Ips Datenraum Register, Ips Gestaltender Teil: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ips-gerichtliche-ips-ips-steuern` | Nutze dies bei Ips Gerichtliche Schritte, Ips Kommandocenter, Ips Steuern Bilanz Folgen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ips-gruppen-ips-architektur-ips-integrierte` | Nutze dies bei Ips Gruppen Klassenbildung, Ips Insolvenzplan Architektur, Ips Integrierte Planung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ips-ips-sanierungskonzept-ips-sicherheiten` | Nutze dies bei Ips Redteam Qualitygate, Ips Sanierungskonzept, Ips Sicherheiten Drittsicherheiten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ips-kaltstart-interview` | Insolvenzplan- oder StaRUG-Mandat durch strukturiertes Erstgespraech aufgleisen wenn Unterlagen fehlen. §§ 13 15a InsO §§ 29 42 StaRUG Antragspflichten. Prüfraster: Basisdaten Krisenursachen Gläubigerlandschaft Liquiditaetslage Sanierung... |
| `ips-minderheitenschutz-ips-planbetroffene-ips` | Nutze dies bei Ips Minderheitenschutz, Ips Planbetroffene Auswahl, Ips Planvollzug Monitoring: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ips-stabilisierung-ips-stakeholder-ips-plan` | Nutze dies bei Ips Stabilisierung Starug, Ips Stakeholder Kommunikation, Ips Starug Plan Architektur: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ips-verfahrenswahl-restrukturierungsplan-ips` | Nutze dies bei Ips Verfahrenswahl, Restrukturierungsplan Fristen Form Und Zustaendigkeit, Ips Darstellender Teil: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitssch... |
| `ips-vergleichsrechnung-ipsplan-cram` | Nutze dies bei Ips Vergleichsrechnung, Ipsplan Cram Down Spezial, Ipsplan Gruppenbildung Leitfaden: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ipsplan-planstruktur-prepack-plan` | Nutze dies bei Ipsplan Planstruktur Bauleiter, Ipsplan Prepack Plan Spezial, Sanierungsmoderation 94 Starug: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `sanierungskonzept-starug-spezial-teil` | Nutze dies bei Sanierungskonzept Risikoampel Und Gegenargumente, Starug Tatbestand Beweis Und Belege, Teil Compliance Dokumentation Und Akte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näc... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `vergleichsrechnung` | Nutze dies bei Vergleichsrechnung Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
