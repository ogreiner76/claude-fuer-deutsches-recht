# Wandeldarlehen-Lebenszyklus

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`wandeldarlehen-lebenszyklus`) | [`wandeldarlehen-lebenszyklus.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/wandeldarlehen-lebenszyklus.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Nebelstern Ventures - Berliner VC-Pipeline, Wandeldarlehen und Follow-on-Chaos** (`venture-capital-geber-nebelstern-portfolio-berlin`) | [Gesamt-PDF lesen](../testakten/venture-capital-geber-nebelstern-portfolio-berlin/gesamt-pdf/venture-capital-geber-nebelstern-portfolio-berlin_gesamt.pdf) | [`testakte-venture-capital-geber-nebelstern-portfolio-berlin.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-venture-capital-geber-nebelstern-portfolio-berlin.zip) |
| **Wandeldarlehen-Lebenszyklus (Sonnenglas Solartechnologie UG)** (`wandeldarlehen-beispielcase`) | [Gesamt-PDF lesen](../testakten/wandeldarlehen-beispielcase/gesamt-pdf/wandeldarlehen-beispielcase_gesamt.pdf) | [`testakte-wandeldarlehen-beispielcase.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-wandeldarlehen-beispielcase.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Vollständiger Workflow-Assistent für den Lebenszyklus eines Wandeldarlehens bei GmbH und UG (haftungsbeschränkt) — von der ersten Mandatsbesprechung über Vertragsgestaltung (bilingual DE/EN oder einsprachig DE), Beurkundungsprüfung, Wandelereignisse und Wandlungsberechnung bis zum Cap-Table-Update, Gesellschafterbeschluss und Handelsregisteranmeldung durch den Notar.

## Lebenszyklus-Visualisierung

```
Phase A — Erstellung
  └─ Mandat-Triage → Parteien erfassen → Konditionen → Wandlungsmechanik
     → Rangrücktritt → Vertragserstellung (bilingual / einsprachig)
     → Vertraulichkeit und Sprachklausel

Phase B — Beurkundung und Unterzeichnung
  └─ Beurkundungserfordernis → Form (Textform/Schriftform/Notariell)
     → Formfehler-Heilungs-Timeline → DocuSign-Unterzeichnung
     → Gesellschafterbeschluss (Absicht) → KYC/AML

Phase C — Wandelereignisse und Wandlungsberechnung
  └─ Eingang Wandlungserklärung → Trigger-Dispatcher → Trigger-Prüfung
     (Qualified Financing / Maturity / Liquidation) → Wandlungspreis-Berechnung
     → Cap-Table Pre/Post → Dokumente-Extraktion
     → Ausschluss-Prüfung → Mehrere WD → Kommunikation

Phase D — Gesellschafterbeschluss und Notar
  └─ Gesellschafterversammlung einberufen → Beschluss Kapitalerhöhung
     → Sacheinlagebericht → Notar-Paket → Gesellschafterliste
     → HR-Anmeldung → Post-Eintragung-Checkliste
```

## Skills nach Phasen

### Phase A — Erstellung (8 Skills)

| Slug | Beschreibung |
|---|---|
| `mandat-triage-wandeldarlehen` | Erstgespräch: Rechtsform, Beteiligte, Wandelereignisse, Sprachen-Stack |
| `parteien-erfassen` | Gesellschaft, Gesellschafterinnen, Darlehensgeber, KYC, Vertretungsmacht |
| `darlehenshoehe-konditionen` | Darlehensbetrag, Laufzeit, Zinssatz, Auszahlung, Bankverbindung |
| `wandlungsmechanik-konzipieren` | Cap, Discount, Trigger-Logik, Wandlungsformel, MFN, Pro-rata |
| Rechtsprechung live prüfen | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| `bilinguale-vertragserstellung` | Vollständiger Vertrag DE/EN zweispaltig, Sprachklausel |
| `einsprachige-vertragsfassung-de` | Einsprachige DE-Fassung, identischer materieller Inhalt |
| `vertraulichkeit-und-sprachklausel` | § 8 Vertraulichkeit, Sprachklausel, DIS-Schiedsklausel, salvatorische Klausel |

### Phase B — Beurkundung und Unterzeichnung (6 Skills)

| Slug | Beschreibung |
|---|---|
| Rechtsprechung live prüfen | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| `textform-vs-schriftform-vs-notariell` | § 126b/§ 126/§ 128 BGB, Formstufen, DocuSign-Praxis |
| `formfehler-heilungs-timeline` | Form-Stufen § 126b/§ 126/§ 128 BGB, Heilung durch nachfolgende Beurkundung § 15 Abs. 4 S. 2 GmbHG, Insolvenz-Risiko-Fenster |
| `unterzeichnung-elektronisch-docusign` | Authentifizierung, Audit Trail, zehn Jahre Archivierung § 147 AO |
| `gesellschafterbeschluss-vorbereiten` | Grundsatzbeschluss Kapitalerhöhungsbereitschaft, § 51 GmbHG |
| `kyc-aml-geldwaesche` | GwG KYC, wirtschaftlich Berechtigte, PEP, Sanktionslisten EU/OFAC/UN |

### Phase C — Wandelereignisse und Wandlungsberechnung (11 Skills)

| Slug | Beschreibung |
|---|---|
| `wandelereignis-eingang` | Eingang Wandlungserklärung, Vier-Augen-Prüfung, Eingangsbestätigung |
| `wandelereignis-trigger-dispatcher` | Master-Logik bei parallelen Triggern, Prioritäts-Regelung, Cap-Table-Simulation, MFN-Kaskade |
| `wandlungspruefung-trigger-qualified-financing` | Schwellentest, MIN-Methode Cap/Discount/Rundenpreis |
| `wandlungspruefung-trigger-maturity` | Laufzeitablauf, Fall-back-Bewertung, Wahlrecht Lender |
| `wandlungspruefung-trigger-liquidation` | Exit/Trade Sale/IPO, Liquidationspräferenz, Wahlrecht |
| `wandlungspreis-berechnung` | Vollständige Formel, Aufrundung § 5 GmbHG, Kapitalrücklage § 272 HGB |
| `cap-table-update-pre-post` | Pre-Money und Post-Money Cap-Table, Verwässerungsdarstellung |
| `dokumenten-upload-extraktion` | Term Sheet, SPA, IRA: relevante Zahlen extrahieren |
| `wandlungsausschluss-pruefung` | Verfristung, Verjährung, Verwirkung, Verzicht |
| `mehrere-wandeldarlehen-parallel` | Stack-Order, MFN, gleichzeitige Wandlung, kombinierter Cap-Table |
| `wandlung-kommunikation-paketverteilung` | Lender, Gesellschaft, Steuerberater, Buchhaltung informieren |

### Phase D — Gesellschafterbeschluss und Notar (7 Skills)

| Slug | Beschreibung |
|---|---|
| `gesellschafterversammlung-einberufen` | Einberufung, § 51 GmbHG, Ladungsfristen, Vollmacht, Notartermin |
| `gesellschafterbeschluss-kapitalerhoehung` | Beschluss Kapitalerhöhung gegen Sacheinlage, § 53 Abs. 2 GmbHG |
| `sacheinlagebericht-werthaltigkeit` | Werthaltigkeit Forderung, Differenzhaftung § 9 GmbHG, IDW RS HFA 42 |
| `notar-paket-uebermittlung` | Vollständigkeitscheckliste, Notar-Briefing, § 57 GmbHG-Anmeldung |
| `gesellschafterliste-aktualisieren` | § 40 GmbHG, Gutglaubenswirkung § 16 GmbHG, Transparenzregister |
| `handelsregisteranmeldung-kapitalerhoehung` | § 57 GmbHG, Bearbeitungsdauer, Beanstandungsgründe, § 19 GwG |
| `post-eintragung-checkliste` | Bestätigung, Steuer (§ 20 UmwStG), Sperrfrist § 22 UmwStG, Abschluss-Memo |

## Rechtsgrundlagen

| Bereich | Normen |
|---|---|
| GmbH-Gesellschaftsrecht | GmbHG §§ 1, 5, 5a, 15, 40, 46, 49–51, 53–57, 78 |
| Insolvenzrecht | InsO §§ 17, 19, 38, 39, 44, 15a, 15b |
| Zivilrecht / Form | BGB §§ 126, 126b, 128, 130, 194 ff., 311, 314, 397, 398, 488 ff. |
| Geldwäscherecht | GwG §§ 1–3, 10–13, 19, 43, 47, 56 |
| Handelsrecht | Normtext, Register-/Gesetzesquellen, bereitgestellte Materialien |
| Steuerrecht | UmwStG §§ 20, 22; EStG § 17; AO § 147 |
| Elektronische Signatur | eIDAS-VO 910/2014; Art. 26 ff. |
| Schiedsgerichtsbarkeit | DIS-Schiedsordnung 2018 |

## Verwendungsbeispiel

**Einstiegs-Prompt:**

> "Ich möchte ein Wandeldarlehen aufsetzen — was brauchst du von mir?"

Das Plugin startet mit `mandat-triage-wandeldarlehen` und führt durch:
1. Rechtsform und Parteien klären
2. Konditionen und Wandlungsmechanik festlegen
3. Vertrag erstellen (bilingual DE/EN oder nur DE)
4. Beurkundungserfordernis prüfen
5. DocuSign-Unterzeichnung koordinieren
6. Bei Wandlungsereignis: Trigger prüfen, Preis berechnen, Cap-Table aktualisieren
7. Gesellschafterbeschluss und Notarpaket erstellen
8. Handelsregisteranmeldung begleiten

## Wichtiger Hinweis

Alle Texte dienen als Arbeitshilfe für die anwaltliche Praxis. Sie ersetzen keine rechtliche Beratung im Einzelfall. Jeder Skill verweist auf die maßgebliche Rechtsprechung (BGH/OLG mit Aktenzeichen und Datum). Änderungen in GmbHG, InsO, UmwStG oder GwG sind einzuarbeiten (Stand: 05/2026).

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 28 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Fallrouting im Wandeldarlehen Lebenszyklus-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Fachmodule aus diesem Plugin vor und führt in einen klaren Arbeitsplan.... |
| `beurkundungspruefung-quellenkarte-check` | Nutze dies zur Quellenprüfung bei Beurkundungspruefung Quellenkarte Check: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `bilingual-einsprachig` | Nutze dies bei Bilingual Schriftsatz Brief Und Memo Bausteine, Einsprachig Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschr... |
| `cap-table-darlehenshoehe-konditionen` | Nutze dies bei Cap Table Update Pre Post, Darlehenshoehe Konditionen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `chronologie-fristen` | Nutze dies bei Chronologie Und Belegmatrix, Fristen Und Risikoampel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `dokumenten-upload-formfehler-heilungs` | Nutze dies bei Dokumenten Upload Extraktion, Formfehler Heilungs Timeline: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `einsprachige-vertragsfassung` | Nutze dies bei Einsprachige Vertragsfassung De, Vertragserstellung Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `gesellschafterbeschluss-kapitalerhoehung` | Nutze dies bei Gesellschafterbeschluss Kapitalerhoehung, Gesellschafterbeschluss Vorbereiten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `gesellschafterliste-aktualisieren` | Nutze dies bei Gesellschafterliste Aktualisieren, Gesellschafterversammlung Einberufen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `gmbh-vollstaendigen` | Nutze dies bei Gmbh Risikoampel Und Gegenargumente, Vollstaendigen Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `handelsregisteranmeldung-kapitalerhoehung-kyc` | Nutze dies bei Handelsregisteranmeldung Kapitalerhoehung, Kyc Aml Geldwaesche: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `lebenszyklus-bilinguale-vertragserstellung` | Nutze dies bei Lebenszyklus Fristen Form Und Zustaendigkeit, Bilinguale Vertragserstellung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `mandat-triage-mehrere-parallel` | Nutze dies bei Mandat Triage Wandeldarlehen, Mehrere Wandeldarlehen Parallel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `notar-paket-parteien-erfassen` | Nutze dies bei Notar Paket Uebermittlung, Parteien Erfassen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `post-eintragung-rangruecktritt-formulieren` | Nutze dies bei Post Eintragung Checkliste, Rangruecktritt Formulieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `sacheinlagebericht-werthaltigkeit-begleitet` | Nutze dies bei Sacheinlagebericht Werthaltigkeit, Begleitet Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `unterzeichnung-elektronisch-wandelereignis` | Nutze dies bei Unterzeichnung Elektronisch Docusign, Wandelereignis Eingang: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vertraulichkeit-sprachklausel` | Nutze dies bei Vertraulichkeit Und Sprachklausel, Beurkundungserfordernis Prüfung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `wandeldarlehens-wandelereignisse` | Nutze dies bei Wandeldarlehens Dokumentenmatrix Und Lueckenliste, Wandelereignisse Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitss... |
| `wandelereignis-trigger-wandlung-kommunikation` | Nutze dies bei Wandelereignis Trigger Dispatcher, Wandlung Kommunikation Paketverteilung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `wandlungsausloeser-cap-textform-vs` | Nutze dies bei Wandlungsausloeser Cap Und Discount, Textform Vs Schriftform Vs Notariell: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `wandlungsausschluss-wandlungsmechanik` | Nutze dies bei Wandlungsausschluss Prüfung, Wandlungsmechanik Konzipieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `wandlungspreis-wandlungspruefung-trigger` | Nutze dies bei Wandlungspreis Berechnung, Wandlungspruefung Trigger Liquidation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `wandlungspruefung-trigger` | Nutze dies bei Wandlungspruefung Trigger Maturity, Wandlungspruefung Trigger Qualified Financing: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
