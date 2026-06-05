# gesellschaftsgründer — Gründungsassistent für deutsche Gesellschaften

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`gesellschaftsgruender`) | [`gesellschaftsgruender.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/gesellschaftsgruender.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Knusperkrone: Franchise-Expansion, Gebietsschutz und Systemhandbuch-Streit** (`franchiserecht-systemgastronomie-expansion-streit`) | [Gesamt-PDF lesen](../testakten/franchiserecht-systemgastronomie-expansion-streit/gesamt-pdf/franchiserecht-systemgastronomie-expansion-streit_gesamt.pdf) | [`testakte-franchiserecht-systemgastronomie-expansion-streit.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-franchiserecht-systemgastronomie-expansion-streit.zip) |
| **NeuroChain Labs — Gründung eines KI/Krypto-Startups in Berlin, Musterprotokoll vs. individuelle Satzung** (`gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll`) | [Gesamt-PDF lesen](../testakten/gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll/gesamt-pdf/gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll_gesamt.pdf) | [`testakte-gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll.zip) |
| **Roeschen Tech GmbH — Gründung, Series A, B-Shares und Streit-Eskalation** (`gesellschaftsgruender-streit-roeschen-tech`) | [Gesamt-PDF lesen](../testakten/gesellschaftsgruender-streit-roeschen-tech/gesamt-pdf/gesellschaftsgruender-streit-roeschen-tech_gesamt.pdf) | [`testakte-gesellschaftsgruender-streit-roeschen-tech.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-gesellschaftsgruender-streit-roeschen-tech.zip) |
| **Handelsrecht HGB — Elbwerft Solar: eGbR, OHG-Statuswechsel, KG und Handelskauf** (`handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona`) | [Gesamt-PDF lesen](../testakten/handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona/gesamt-pdf/handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona_gesamt.pdf) | [`testakte-handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona.zip) |
| **Nebelstern Ventures - Berliner VC-Pipeline, Wandeldarlehen und Follow-on-Chaos** (`venture-capital-geber-nebelstern-portfolio-berlin`) | [Gesamt-PDF lesen](../testakten/venture-capital-geber-nebelstern-portfolio-berlin/gesamt-pdf/venture-capital-geber-nebelstern-portfolio-berlin_gesamt.pdf) | [`testakte-venture-capital-geber-nebelstern-portfolio-berlin.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-venture-capital-geber-nebelstern-portfolio-berlin.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes, anfängerfreundliches und zugleich professionelles Plugin für die Gründung und frühe Führung deutscher Gesellschaften. Es hilft beim ersten Sortieren ebenso wie bei einem fast fertigen Gründungspaket: Rechtsformwahl, Rollen der Gründerinnen und Gründer, Satzung, Gesellschaftervereinbarung, Cap Table, Notar, Handelsregister, Bank/KYC, Behörden, Steuerstart, IP, Datenschutz, erste 100 Tage und Streitprävention.

## Installation

1. Claude Code oder Claude Desktop/Cowork öffnen.
2. **Customize Plugins** bzw. **Personal plugins** wählen.
3. **Install from .zip** und `gesellschaftsgruender.zip` hochladen.
4. Mit einem konkreten Auftrag starten, zum Beispiel: `Starte die Gesellschaftsgründung. Ich habe drei Gründer, eine GmbH-Idee und noch keine Satzung.`

Alternativ via Marketplace:

```text
/plugin marketplace add Klotzkette/claude-fuer-deutsches-recht
/plugin install gesellschaftsgruender@claude-fuer-deutsches-recht
```

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json` und das Verzeichnis `skills/` enthalten.

## So Startet Es

Der `gesellschaftsgruender-allgemein`-Skill beginnt bewusst leicht. Er fragt nicht sofort nach allen juristischen Details, sondern sortiert zuerst:

1. **Wer gründet?** Personen, Rollen, Wohnsitz, Auslandsbezug, Minderjährige, Treuhand, Familien- oder Investorensituation.
2. **Was soll die Gesellschaft tun?** Geschäftszweck, reguliertes Geschäft, IP, Daten, KI, Produkt, Finanzierung, Personal.
3. **Welche Rechtsform liegt nahe?** GmbH, UG, eGbR, OHG, KG, GmbH & Co. KG, PartG mbB, gGmbH, eG, AG, Holding oder Sonderstruktur.
4. **Was muss jetzt zuerst passieren?** Notarbriefing, Gesellschaftsvertrag, Bankkonto, Transparenzregister, Steuererfassung, Gewerbe, IHK/BG, Versicherungen.
5. **Wo brennt es?** Registerbeanstandung, Gründerstreit, KYC-Blockade, IP-Lücke, Sacheinlage, Stammkapitalverlust, Liquiditätsproblem.

Das Plugin schlägt danach aktiv die passenden Anschluss-Skills vor, statt die Nutzerin oder den Nutzer mit einer langen Skillliste allein zu lassen.

## Arbeitsphasen

| Phase | Ziel | Typische Outputs |
| --- | --- | --- |
| **0 Intake** | Idee, Beteiligte, Geld, Risiko und Zeitplan verstehen | One-Page-Roadmap, Rückfragenliste, Risikoampel |
| **1 Rechtsform** | passende Struktur auswählen und falsche Abzweigungen vermeiden | Rechtsformmatrix, Entscheidungsvorlage, Stoppschilder |
| **2 Dokumente** | Gründungspaket bauen | Satzung, SHA, Geschäftsführerunterlagen, Gesellschafterliste, Notarbriefing |
| **3 Vollzug** | Notar, Register, Bank, Behörden und Steuerstart koordinieren | Closing-Checkliste, KYC-Paket, ELSTER-/Gewerbe-/BG-Liste |
| **4 Betrieb** | erste 100 Tage sauber organisieren | Board Pack, Beschlussvorlagen, Versicherungs- und Compliance-Check |
| **5 Konflikt** | Streit früh erkennen und kontrolliert eskalieren | Deadlock-Matrix, Mediationsplan, Eilmaßnahmen-Check, Registerstrategie |

## Skillgruppen

- **Einstieg und Anfängerführung:** Kaltstart, einfache Sprache, One-Page-Roadmap, Gründerrollen, Mandantenbrief, Checkliste vor Unterschrift.
- **Rechtsformen:** GmbH, UG, eGbR, OHG, KG, GmbH & Co. KG, PartG mbB, gGmbH, eG, AG, SE und Holdingmodelle.
- **Dokumente und Vollzug:** Satzung, Gesellschaftervereinbarung, Geschäftsführervertrag, Geschäftsordnung, Gesellschafterliste, Notarbriefing, Registerbeanstandung.
- **Finanzierung und Beteiligung:** Cap Table, Seed-Runde, Wandeldarlehen, Founder Vesting, Leaver, ESOP/VSOP, Vinkulierung, Drag/Tag, Bezugsrechte.
- **Risikothemen:** Auslandsgründer, KYC, Sanktionen, Transparenzregister, Sacheinlagen, IP-Übertragung, Open Source, Datenschutz/KI, regulierte Geschäftsmodelle.
- **Operativer Start:** Bankkonto, Steuerliche Erfassung, Umsatzsteuer, Payroll, Mietvertrag, Kundenstart, Produkthaftung, Versicherungen, Cash Burn und Insolvenzfrühwarnung.

## Demonstrationsakte

Die Akte `gesellschaftsgruender-streit-roeschen-tech` zeigt eine Gründung, die nicht lehrbuchartig glatt läuft: drei Gründer, ein technisches Produkt, IP-Fragen, Series-A-Druck, B-Shares, Bezugsrechtsstreit, KYC-Rückfragen, Registerlogik, Gründer-Vesting, Leaver-Risiken, Datenschutz-/KI-Fragen und ein Konflikt, der parallel über Notar, Bank, Investorin, Beirat und Registergericht läuft.

Sie enthält unter anderem Satzungsentwurf, Gesellschaftervereinbarung, Cap-Table-Varianten, E-Mails, Register-/Notarvermerke, KYC-Nachfragen, IP-/Open-Source-Notizen, Vesting-Matrix, Board Pack, Cash-Burn-Übersicht, Compliance-Startliste, CSV-Tabellen und ein Gesamt-PDF.

## Stoppschilder

- **Notar:** Beurkundung, Handelsregisteranmeldung und bestimmte Vollmachten müssen notariell laufen.
- **Steuer:** Rechtsform, Holding, Sacheinlage, ESOP/VSOP, USt und Verrechnungspreise gehören früh in steuerkundige Hände.
- **Aufsicht und Erlaubnis:** Finanzen, Versicherung, Kryptowerte, Zahlungsdienste, Medizin, Bewachung, Handwerk, Lebensmittel, Transport und ähnliche Modelle brauchen einen Erlaubnischeck vor dem Start.
- **Krise:** Bei Zahlungsunfähigkeit, Überschuldung, hälftigem Stammkapitalverlust oder Liquiditätslücke geht es nicht mehr nur um Gründung, sondern um Organhaftung und Insolvenzrecht.
- **Streit:** Bei Gesellschafterstreit, Registerblockade oder Investorendruck braucht es eine Beweis-, Fristen- und Eskalationsstrategie.

## Quellenhygiene

Gesetzesstände, Registervorgaben, Formularwege und Behördenpraxis sind vor produktiver Verwendung live zu prüfen. Rechtsprechung wird nicht aus Modellwissen zitiert; sie muss vor Ausgabe mit Gericht, Entscheidungsform, Datum, Aktenzeichen und freier oder amtlicher Quelle verifiziert werden.

Wichtige Startanker sind insbesondere BGB §§ 705 ff., HGB §§ 105 ff. und §§ 161 ff., GmbHG, AktG, PartGG, GenG, GwG/Transparenzregister, GewO, AO/UStG, SGB IV/SGB VII, InsO § 15a und die Register-/Notarvorgaben nach BeurkG und HRegV.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `egbr-mopeg-gesellschaftsgruender` | Egbr Mopeg Gesellschaftsgruender im Plugin Gesellschaftsgruender: prüft konkret GbR nach MoPeG 2024 und Eintragung ins, Prüft Familien-GbR/GmbH/KG für Vermögen, Nachfolge, Minderjährige und Stimmrecht. Liefert priorisierten Output mit No... |
| `geschaeftsfuehrervertrag-quellenkarte-check` | Geschaeftsfuehrervertrag Quellenkarte Check: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `geschaeftsordnung-gf-gesellschafterstreit` | Geschaeftsordnung GF Gesellschafterstreit im Plugin Gesellschaftsgruender: prüft konkret Geschäftsordnung für GmbH-Geschäftsführung entwerfen, Eilmassnahmen im Gesellschafterstreit der GmbH, Gesellschaftervereinbarung (SHA) neben dem, Vo... |
| `gesellschaftsgruender-anfaenger-kaltstart` | Führt absolute Anfänger durch die ersten Entscheidungen einer Gesellschaftsgründung ohne Fachsprachenfalle. |
| `gesellschaftsgruender-bankkonto-kyc-beirat` | Bankkonto KYC Beirat im Plugin Gesellschaftsgruender: prüft konkret Erstellt Bankkonto-Unterlagenpaket für Gründung und, Beirat oder Advisory Board für GmbH oder UG einrichten, Gesellschaftsrechtliche Dokumente in Deutsch und Englisch, E... |
| `gesellschaftsgruender-cashburn` | Cashburn im Plugin Gesellschaftsgruender: prüft konkret Prüft Liquiditätsreichweite, Stammkapitalverlust, Zahlungsunfähigkeit und Übersc, Letztes Qualitygate vor Satzung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und n... |
| `gesellschaftsgruender-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `gesellschaftsgruender-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `gesellschaftsgruender-freiberufler-partg-gbr` | Freiberufler Partg GBR im Plugin Gesellschaftsgruender: prüft konkret Prüft Freiberuflerstrukturen, PartG, PartG mbB, Berufshaftpflicht und Berufsrech. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `gesellschaftsgruender-gesellschafterliste` | Prüft Gesellschafterliste, Nennbeträge, Nummerierung, Prozentangaben und Veränderungsspalten. |
| `gesellschaftsgruender-gmbh-vorbereitung` | Gmbh Vorbereitung im Plugin Gesellschaftsgruender: prüft konkret GmbH-Gründung vorbereiten, Golden Shares und Vetorechte in GmbH oder AG satzungsmäßig, Klärt Rollen, Beiträge. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel... |
| `gesellschaftsgruender-handelsregister` | Handelsregister im Plugin Gesellschaftsgruender: prüft konkret Erstanmeldung der GmbH zum Handelsregister vorbereiten, IHK-Pflichtmitgliedschaft und, Baut Datenraum für Investor-DD, Prüft. Liefert priorisierten Output mit Norm-Pinpoints,... |
| `gesellschaftsgruender-kaltstart-triage` | Einstieg, Schnelltriage und Fallrouting für das Gesellschaftsgründer-Plugin; besonders anfängerfreundlich, mit Rollenklärung, Dokumentenintake, Rechtsformwahl und Anschluss-Skills. |
| `gesellschaftsgruender-lizenz-vertriebsstart` | Lizenz Vertriebsstart im Plugin Gesellschaftsgruender: prüft konkret Navigationszentrum für alle Gründungs-Skills, Erstellt rechtliche Startliste für erste Kundenverträge, AGB, Datenschutz. Liefert priorisierten Output mit Norm-Pinpoints... |
| `gesellschaftsgruender-musterprotokoll-vs` | Musterprotokoll VS im Plugin Gesellschaftsgruender: prüft konkret Entscheidet, ob Musterprotokoll reicht oder individuelle Satzung nötig, Notartermin für GmbH-Gründung vorbereiten, Erstellt ein Notarbriefing mit Firma. Liefert priorisier... |
| `gesellschaftsgruender-open-source-plain` | Open Source Plain im Plugin Gesellschaftsgruender: prüft konkret Prüft Open-Source-Risiken vor Gründung, Finanzierung und Due Diligence, Übersetzt Gründungsrecht in einfache Sprache, ohne rechtliche Präzision zu verli. Liefert priorisier... |
| `gesellschaftsgruender-redteam-gruendungspaket` | Prüft das gesamte Gründungspaket auf typische Fehler, Streitbomben und Register-/Bankhindernisse. |
| `gesellschaftsgruender-steuerliche-erfassung` | Steuerliche Erfassung im Plugin Gesellschaftsgruender: prüft konkret Führt durch Fragebogen steuerliche Erfassung, USt, Dauerfristverlängerung und Lo, Prüft Treuhand. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächs... |
| `gesellschaftsgruender-transparenzregister` | Transparenzregister im Plugin Gesellschaftsgruender: prüft konkret Prüft Aktualisierung wirtschaftlich Berechtigter nach, Treuhand, UG haftungsbeschraenkt gründen, Prüft USt-Startfragen. Liefert priorisierten Output mit Norm-Pinpoints, R... |
| `gesellschaftsgruender-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `gesellschaftsgruender-wandeldarlehen` | Wandeldarlehen im Plugin Gesellschaftsgruender: prüft konkret Prüft Wandeldarlehen, Discount, Cap, Wandlung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `gmbh-gesellschaftsgruender` | Gmbh Gesellschaftsgruender im Plugin Gesellschaftsgruender: prüft konkret Fristen- und Risikoampel im Plugin gesellschaftsgruender, GmbH, Geschäftsführervertrag für GmbH-Geschäftsführer aufsetzen, GmbH-Gesellschaftsvertrag aufsetzen. Lie... |
| `intake-decision-kg-gmbhcokg` | Intake Decision KG Gmbhcokg im Plugin Gesellschaftsgruender: prüft konkret Entscheidungsbaum für GmbH-Gründung, KG und GmbH und Co, Prüft Mitarbeiterbeteiligung, virtuelle Anteile. Liefert priorisierten Output mit Norm-Pinpoints, Risikoa... |
| `leaver-klauseln-mietvertrag-buero-mitarbeiter` | Leaver Klauseln Mietvertrag Buero Mitarbeiter im Plugin Gesellschaftsgruender: prüft konkret Prüft Good/Bad-Leaver-Klauseln, Abfindung, Einziehung und Durchsetzbarkeit, Prüft Mietvertrag vor Gründung/Eintragung. Liefert priorisierten Out... |
| `rechtsformwahl-ueber` | Rechtsformwahl Ueber im Plugin Gesellschaftsgruender: prüft konkret Rechtsformwahl, Ueber. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `sanktionen-investorcheck-gewerbeanmeldung` | Sanktionen Investorcheck Gewerbeanmeldung im Plugin Gesellschaftsgruender: prüft konkret Prüft Investoren und Gesellschafter auf Sanktions-, Geldwäsche- und Außenwirtsch, Gewerbeanmeldung und steuerliche Ersterfassung nach, Sozialversich... |
| `se-crossborder-sha-satzung-stammkapital` | SE Crossborder SHA Satzung Stammkapital im Plugin Gesellschaftsgruender: prüft konkret Prüft SE und grenzüberschreitende Gründungs-/Holdingfragen, Stimmbindungsvereinbarung und SHA-Regelungen zu, Stammkapitaleinzahlung bei GmbH-Gründung... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
