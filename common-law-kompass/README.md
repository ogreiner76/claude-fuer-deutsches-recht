# Common-Law-Kompass für deutsche Wirtschaftsjuristen

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`common-law-kompass`) | [`common-law-kompass.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/common-law-kompass.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Common-Law-Kompass: Crossborder Supply & License Agreement** (`common-law-kompass-crossborder-contract`) | [Gesamt-PDF lesen](../testakten/common-law-kompass-crossborder-contract/gesamt-pdf/common-law-kompass-crossborder-contract_gesamt.pdf) | [`testakte-common-law-kompass-crossborder-contract.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-common-law-kompass-crossborder-contract.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Großes, freistehendes Plugin für deutsche Anwältinnen und Anwälte im Wirtschaftsrecht, die mit Common Law, English Law, US Law, internationalen Verträgen, bilingualen Fassungen und gemischtem Business-English arbeiten. Es verhindert, dass deutsche Rechtsbegriffe gedankenlos übersetzt werden, und markiert typische False Friends wie Bürgschaft, Garantie, Gewährleistung, Rücktritt, Vertretung, Consideration, representations, warranties, covenants, indemnity, damages, equity oder discovery.

Dieses Plugin ist **vollständig freistehend**. Es benötigt keine anderen Plugins, keine externen Agenten und keine Kanzleisoftware. Wenn keine Datenbank, kein DMS, kein Übersetzungstool, keine Rechercheplattform oder kein Behördenzugang angeschlossen ist, arbeitet es mit manuellen Uploads oder einem ausdrücklich markierten Simulationsmodus.

## Schnellstart

1. Plugin aktivieren oder ZIP aus dem Release installieren.
2. Neue Sache mit `common-law-kommandocenter` starten.
3. Rechtsordnung, Zieltext, Parteirolle, Verfahrensstand und gewünschtes Arbeitsprodukt nennen.
4. Vertragsauszug, Memo, Bescheid, Normtext, Redline, Übersetzung oder fiktive Simulationsakte hochladen.
5. Am Ende immer das Qualitätstor verlangen: Rechtsquelle, Jurisdiktion, Denkfehler, False Friends, offene Annahmen, Review-Level und nächster Schritt.

## Enthaltene Skills

- `common-law-kommandocenter` - Common-Law-Kommandocenter
- `common-law-false-friends-scanner` - False-Friends-Scanner
- `common-law-begriffe-uebersetzung` - Begriffs- und Übersetzungswerkstatt
- `common-law-governing-law-jurisdiction` - Governing Law, Jurisdiction und Forum
- `common-law-contract-formation-consideration` - Contract Formation und Consideration
- `common-law-surety-guarantee-indemnity` - Surety, Guarantee und Indemnity
- `common-law-representations-warranties-covenants` - Representations, Warranties und Covenants
- `common-law-remedies-damages-equity` - Remedies, Damages und Equity
- `common-law-interpretation-precedent` - Interpretation und Precedent
- `common-law-us-vs-uk-drafting` - UK vs US Drafting
- `common-law-ucc-sales-goods` - UCC und Sale of Goods
- `common-law-litigation-discovery` - Litigation, Discovery und Evidence
- `common-law-ma-commercial-drafting` - M&A und Commercial Drafting
- `common-law-bilingual-contract-review` - Bilingual Contract Review
- `common-law-client-explainer` - Mandanten-Erklärer
- `common-law-humor-coach` - Low-Key Late-Night Coach
- `common-law-quality-gate` - Common-Law-Qualitätstor
- `common-law-simulation-negotiation` - Simulation und Verhandlungstraining

## Vorlagen

- `assets/templates/bilingual-contract-review.md`
- `assets/templates/common-law-mandatskarte.md`
- `assets/templates/common-law-quality-gate.md`
- `assets/templates/consideration-check.md`
- `assets/templates/discovery-litigation-risk.md`
- `assets/templates/false-friends-matrix.md`
- `assets/templates/governing-law-jurisdiction-check.md`
- `assets/templates/ma-commercial-issue-list.md`
- `assets/templates/remedies-damages-map.md`
- `assets/templates/reps-warranties-covenants.md`
- `assets/templates/simulation-negotiation-playbook.md`
- `assets/templates/surety-guarantee-indemnity-map.md`
- `assets/templates/ucc-sales-check.md`
- `assets/templates/uk-us-drafting-styleguide.md`

## Offizielle Startquellen

- [UK Supreme Court](https://www.supremecourt.uk/)
- [Arnold v Britton, UKSC contract interpretation](https://www.supremecourt.uk/cases/uksc-2013-0193)
- [Wood v Capita, UKSC contract interpretation](https://www.supremecourt.uk/cases/uksc-2015-0212)
- [Contracts Rights of Third Parties Act 1999](https://www.legislation.gov.uk/ukpga/1999/31/contents)
- [Sale of Goods Act 1979](https://www.legislation.gov.uk/ukpga/1979/54/contents)
- [Unfair Contract Terms Act 1977](https://www.legislation.gov.uk/ukpga/1977/50/contents)
- [U.S. Courts: federal and state courts](https://www.uscourts.gov/about-federal-courts/court-role-and-structure/comparing-federal-state-courts)
- [Federal Rules of Civil Procedure](https://www.uscourts.gov/rules-policies/current-rules-practice-procedure/federal-rules-civil-procedure)
- [Uniform Law Commission: UCC](https://www.uniformlaws.org/acts/ucc)
- [U.S. Supreme Court](https://www.supremecourt.gov/)

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `begriffe-uebersetzung-bilingual-contract` | Nutze dies bei Common Law Begriffe Uebersetzung, Common Law Bilingual Contract Review, Common Law Client Explainer: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitss... |
| `bilinguale-client-commercial-sonderfall` | Nutze dies bei Bilinguale Compliance Dokumentation Und Akte, Client Mandantenkommunikation Entscheidungsvorlage, Commercial Sonderfall Und Edge Case: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `cl-mandantenuebersicht-cl-prozesskostenrisiko` | Nutze dies bei Cl Mandantenuebersicht Englisch, Cl Prozesskostenrisiko Each Party Bears Own, Cl Precedent Vs Statute: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `cl-vertragsklauseln-vertragsbegriffe-cl` | Nutze dies bei Cl Vertragsklauseln Typische Uebersicht, Vertragsbegriffe Risikoampel Und Gegenargumente, Cl Discovery Doc Production Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näc... |
| `common-consideration-discovery` | Nutze dies bei Common Erstpruefung Und Mandatsziel, Consideration Behörden Gericht Und Registerweg, Discovery Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nä... |
| `contract-formation-false-friends-governing` | Nutze dies bei Common Law Contract Formation Consideration, Common Law False Friends Scanner, Common Law Governing Law Jurisdiction: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bel... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `drafting-interessen-explainer-beweislast` | Nutze dies bei Drafting Mehrparteien Konflikt Und Interessen, Explainer Beweislast Und Darlegungslast, False Friends Contracts: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastba... |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `false-friends` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, False Fristen Form Und Zustaendigkeit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `friends-indemnity-quality` | Nutze dies bei Friends Dokumentenmatrix Und Lueckenliste, Indemnity Verhandlung Vergleich Und Eskalation, Quality Formular Portal Und Einreichung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert de... |
| `gate-fehlerkatalog` | Nutze dies als Fehlerbremse bei Gate Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `humor-coach-interpretation-precedent-common` | Nutze dies bei Common Law Humor Coach, Common Law Interpretation Precedent, Common Law Kommandocenter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `litigation-discovery-ma-commercial-quality` | Nutze dies bei Common Law Litigation Discovery, Common Law Ma Commercial Drafting, Common Law Quality Gate: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `precedent-quellenkarte` | Nutze dies zur Quellenprüfung bei Precedent Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `rechtsvergleichender-begriffscheck-reviews` | Nutze dies bei Rechtsvergleichender Begriffscheck, Reviews Internationaler Bezug Und Schnittstellen, Suretyship Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `remedies-damages-representations-warranties` | Nutze dies bei Common Law Remedies Damages Equity, Common Law Representations Warranties Covenants, Common Law Simulation Negotiation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten b... |
| `surety-guarantee-ucc-sales-us-vs` | Nutze dies bei Common Law Surety Guarantee Indemnity, Common Law Ucc Sales Goods, Common Law Us Vs Uk Drafting: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `wirtschaftsjuristen` | Nutze dies bei Wirtschaftsjuristen Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
