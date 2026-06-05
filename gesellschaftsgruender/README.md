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

Der `allgemein`-Skill beginnt bewusst leicht. Er fragt nicht sofort nach allen juristischen Details, sondern sortiert zuerst:

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
| `allgemein` | Einstieg, Schnelltriage und Fallrouting für das Gesellschaftsgründer-Plugin; besonders anfängerfreundlich, mit Rollenklärung, Dokumentenintake, Rechtsformwahl und Anschluss-Skills. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `egbr-mopeg-gesellschaftsgruender` | Nutze dies bei Gesellschaftsgruender Egbr Mopeg, Gesellschaftsgruender Familiengesellschaft, Gesellschaftsgruender Finanzierungsrunde Seed, Gesellschaftsgruender Firmenname Prüfung: führt durch diese fachlich verbundenen Module, wählt de... |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `geschaeftsfuehrervertrag-quellenkarte-check` | Nutze dies zur Quellenprüfung bei Geschaeftsfuehrervertrag Quellenkarte Check: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `geschaeftsordnung-gf-gesellschafterstreit` | Nutze dies bei Gesellschaftsgruender Geschaeftsordnung Gf, Gesellschaftsgruender Gesellschafterstreit Eilantraege, Gesellschaftsgruender Gesellschaftervereinbarung, Gesellschaftsgruender Gf Meeting Templates: führt durch diese fachlich v... |
| `gesellschaftsgruender-anfaenger-kaltstart` | Führt absolute Anfänger durch die ersten Entscheidungen einer Gesellschaftsgründung ohne Fachsprachenfalle. |
| `gesellschaftsgruender-bankkonto-kyc-beirat` | Nutze dies bei Gesellschaftsgruender Bankkonto Kyc Paket, Gesellschaftsgruender Beirat Advisory Board, Gesellschaftsgruender Bilinguale Dokumente, Gesellschaftsgruender Board Pack Erste 100 Tage: führt durch diese fachlich verbundenen Mo... |
| `gesellschaftsgruender-cashburn` | Nutze dies bei Gesellschaftsgruender Cashburn Insolvenzfruehwarnung, Gesellschaftsgruender Checkliste Vor Unterschrift, Gesellschaftsgruender Daten Und Ki Compliance Start, Gesellschaftsgruender Deadlock Und Mediation: führt durch diese... |
| `gesellschaftsgruender-freiberufler-partg-gbr` | Nutze dies bei Gesellschaftsgruender Freiberufler Partg Mbb, Gesellschaftsgruender Gbr Zu Ohg Statuswechsel, Gesellschaftsgruender Genehmigtes Kapital, Gesellschaftsgruender Genossenschaft Eg: führt durch diese fachlich verbundenen Modul... |
| `gesellschaftsgruender-gesellschafterliste` | Prüft Gesellschafterliste, Nennbeträge, Nummerierung, Prozentangaben und Veränderungsspalten. |
| `gesellschaftsgruender-gmbh-vorbereitung` | Nutze dies bei Gesellschaftsgruender Gmbh Vorbereitung, Gesellschaftsgruender Golden Share Und Vetorechte, Gesellschaftsgruender Gruenderrollen Konfliktcheck, Gesellschaftsgruender Gv Einladung Tagesordnung: führt durch diese fachlich ve... |
| `gesellschaftsgruender-handelsregister` | Nutze dies bei Gesellschaftsgruender Handelsregister Anmeldung, Gesellschaftsgruender Ihk Und Berufsgenossenschaft, Gesellschaftsgruender Investor Dd Vorbereiten, Gesellschaftsgruender Ip Einbringung: führt durch diese fachlich verbunden... |
| `gesellschaftsgruender-lizenz-vertriebsstart` | Nutze dies bei Gesellschaftsgruender Kommandocenter, Gesellschaftsgruender Lizenz Und Vertriebsstart, Gesellschaftsgruender Lohn Payroll Start, Gesellschaftsgruender Mandantenbrief Naechste Schritte: führt durch diese fachlich verbundene... |
| `gesellschaftsgruender-musterprotokoll-vs` | Nutze dies bei Gesellschaftsgruender Musterprotokoll Vs Satzung, Gesellschaftsgruender Notar Vorbereitung, Gesellschaftsgruender Notarbriefing Onepager, Gesellschaftsgruender One Page Roadmap: führt durch diese fachlich verbundenen Modul... |
| `gesellschaftsgruender-open-source-plain` | Nutze dies bei Gesellschaftsgruender Open Source Startup, Gesellschaftsgruender Plain Language Modus, Gesellschaftsgruender Registerbeanstandung Beantworten, Gesellschaftsgruender Reguliertes Geschaeftsmodell: führt durch diese fachlich... |
| `gesellschaftsgruender-redteam-gruendungspaket` | Prüft das gesamte Gründungspaket auf typische Fehler, Streitbomben und Register-/Bankhindernisse. |
| `gesellschaftsgruender-steuerliche-erfassung` | Nutze dies bei Gesellschaftsgruender Steuerliche Erfassung Elster, Gesellschaftsgruender Treuhand Und Nominee, Gesellschaftsgruender Ag Kleine Ag, Gesellschaftsgruender Aufloesung Liquidation Start: führt durch diese fachlich verbundenen... |
| `gesellschaftsgruender-transparenzregister` | Nutze dies bei Gesellschaftsgruender Transparenzregister Update, Gesellschaftsgruender Ug Vorbereitung, Gesellschaftsgruender Umsatzsteuer Start, Gesellschaftsgruender Versicherungen Start: führt durch diese fachlich verbundenen Module,... |
| `gesellschaftsgruender-wandeldarlehen` | Nutze dies bei Gesellschaftsgruender Wandeldarlehen Safe, Gesellschaften Tatbestand Beweis Und Belege, Ggmbh Risikoampel Und Gegenargumente, Gruendungsassistent Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module,... |
| `gmbh-gesellschaftsgruender` | Nutze dies bei Fristen Und Risikoampel, Gmbh Fristen Form Und Zustaendigkeit, Gesellschaftsgruender Geschaeftsfuehrervertrag, Gesellschaftsgruender Gesellschaftsvertrag Gmbh: führt durch diese fachlich verbundenen Module, wählt den passe... |
| `intake-decision-kg-gmbhcokg` | Nutze dies bei Gesellschaftsgruender Intake Decision Tree, Gesellschaftsgruender Kg Und Gmbhcokg, Gesellschaftsgruender Mitarbeiterbeteiligung Esop Vsop, Gesellschaftsgruender Rechtsformwahl: führt durch diese fachlich verbundenen Module... |
| `leaver-klauseln-mietvertrag-buero-mitarbeiter` | Nutze dies bei Gesellschaftsgruender Leaver Klauseln, Gesellschaftsgruender Mietvertrag Buero Labor, Gesellschaftsgruender Mitarbeiter Gf Arbeitsvertrag, Gesellschaftsvertrag Vergleich Eskalation: führt durch diese fachlich verbundenen M... |
| `rechtsformwahl-ueber` | Nutze dies bei Rechtsformwahl Behörden Gericht Und Registerweg, Ueber Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `sanktionen-investorcheck-gewerbeanmeldung` | Nutze dies bei Gesellschaftsgruender Sanktionen Investorcheck, Gesellschaftsgruender Gewerbeanmeldung Finanzamt, Gesellschaftsgruender Gf Sozialversicherungs Status, Gesellschaftsgruender Gruender Intake: führt durch diese fachlich verbu... |
| `se-crossborder-sha-satzung-stammkapital` | Nutze dies bei Gesellschaftsgruender Se Und Crossborder, Gesellschaftsgruender Sha Satzung Stimmverpflichtung, Gesellschaftsgruender Stammkapital Einzahlung, Gesellschaftsgruender Stammkapitalverlust Paragraf 49 Gmbhg: führt durch diese... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
