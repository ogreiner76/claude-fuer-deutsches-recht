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
| `beurkundungspruefung-quellenkarte-check` | Beurkundungspruefung Quellenkarte Check: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `bilingual-einsprachig` | Bilingual Einsprachig im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Bilingual, Einsprachig. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `cap-table-darlehenshoehe-konditionen` | CAP Table Darlehenshoehe Konditionen im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Cap-Table vor und nach Wandlung aktualisieren und, Darlehenshoehe Zinsen Laufzeit und Konditionen für. Liefert priorisierten Output mit Norm-Pinpoi... |
| `dokumenten-upload-formfehler-heilungs` | Dokumenten Upload Formfehler Heilungs im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Hochgeladene Wandeldarlehens-Dokumente analysieren und, Formfehler in Wandeldarlehen oder. Liefert priorisierten Output mit Norm-Pinpoints, Risiko... |
| `einsprachige-vertragsfassung` | Einsprachige Vertragsfassung im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Wandeldarlehensvertrag auf Deutsch erstellen oder, Vertragserstellung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `gesellschafterbeschluss-kapitalerhoehung` | Gesellschafterbeschluss Kapitalerhoehung im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Gesellschafterbeschluss für Kapitalerhohung nach Wandlung, Gesellschafterbeschluss für Wandeldarlehensaufnahme oder. Liefert priorisierten Outp... |
| `gesellschafterliste-aktualisieren` | Gesellschafterliste Aktualisieren im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Gesellschafterliste nach Kapitalerhohung durch Wandlung, Gesellschafterversammlung für Wandeldarlehensmandat. Liefert priorisierten Output mit Norm-Pi... |
| `gmbh-vollstaendigen` | Gmbh Vollstaendigen im Plugin Wandeldarlehen Lebenszyklus: prüft konkret GmbH, Vollstaendigen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `handelsregisteranmeldung-kapitalerhoehung-kyc` | Handelsregisteranmeldung Kapitalerhoehung KYC im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Handelsregisteranmeldung nach Kapitalerhohung durch, KYC- und AML-Anforderungen bei Wandeldarlehensmandat prüfen. Liefert priorisierten Ou... |
| `lebenszyklus-bilinguale-vertragserstellung` | Bilinguale Vertragserstellung im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Lebenszyklus, Wandeldarlehensvertrag zweisprachig deutsch und englisch. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `mandat-triage-mehrere-parallel` | Mandat Triage Mehrere Parallel im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Wandeldarlehensmandat einordnen Verfahrensroute bestimmen, Mehrere parallele Wandeldarlehen von verschiedenen. Liefert priorisierten Output mit Norm-Pinp... |
| `notar-paket-parteien-erfassen` | Notar Paket Parteien Erfassen im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Notarpaket für Beurkundungstermin bei Kapitalerhohung durch, Vertragsparteien eines Wandeldarlehens vollständig. Liefert priorisierten Output mit Norm-Pin... |
| `post-eintragung-rangruecktritt-formulieren` | Post Eintragung Rangruecktritt Formulieren im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Nacharbeiten nach Handelsregistereintragung der, Rangrücktrittserklärung für Wandeldarlehen formulieren um. Liefert priorisierten Output mit... |
| `sacheinlagebericht-werthaltigkeit-begleitet` | Sacheinlagebericht Werthaltigkeit Begleitet im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Sacheinlagebericht für Sachkapitalerhohung durch, Begleitet. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `unterzeichnung-elektronisch-wandelereignis` | Unterzeichnung Elektronisch Wandelereignis im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Elektronische Unterzeichnung von Wandeldarlehensvertraegen, Eingehende Wandelereignis-Notification prüfen und naechste. Liefert priorisierten... |
| `vertraulichkeit-sprachklausel` | Vertraulichkeit Sprachklausel im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Vertraulichkeits- und Sprachklauseln in, Beurkundungserfordernis für Wandeldarlehen und. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und... |
| `wandeldarlehen-lebenszyklus-chronologie-fristen` | Chronologie Fristen im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Chronologie und Belegmatrix im Plugin, Fristen- und Risikoampel im Plugin. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `wandeldarlehen-lebenszyklus-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `wandeldarlehen-lebenszyklus-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `wandeldarlehen-lebenszyklus-kaltstart-triage` | Einstieg, Schnelltriage und Fallrouting im Wandeldarlehen Lebenszyklus-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Fachmodule aus diesem Plugin vor und führt in einen klaren Arbeitsplan.... |
| `wandeldarlehen-lebenszyklus-output-waehlen` | Output wählen im Plugin Wandeldarlehen Lebenszyklus: Diese Output-Weiche für Wandeldarlehen Lebenszyklus entscheidet, ob Memo, Antrag, Schriftsatz, Tabelle, Risikoampel, Fragenliste oder Mandantenbrief der richtige nächste Schritt ist. |
| `wandeldarlehen-lebenszyklus-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `wandeldarlehens-wandelereignisse` | Wandeldarlehens Wandelereignisse im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Wandeldarlehens, Wandelereignisse. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `wandelereignis-trigger-wandlung-kommunikation` | Wandelereignis Trigger Wandlung Kommunikation im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Wandlungstrigger kategorisieren und an den richtigen, Kommunikation und Dokumentenversand an alle Beteiligten. Liefert priorisierten Outpu... |
| `wandlungsausloeser-cap-textform-vs` | Wandlungsausloeser CAP Textform VS im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Wandlungsauslöser, Cap und Discount sauber berechnen, Formerfordernis für einzelne Wandeldarlehens-Dokumente. Liefert priorisierten Output mit Norm-P... |
| `wandlungsausschluss-wandlungsmechanik` | Wandlungsausschluss Wandlungsmechanik im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Prüfen ob Wandlung gesperrt oder ausgeschlossen ist bei, Wandlungsmechanik eines SAFE oder Convertible Note. Liefert priorisierten Output mit Norm... |
| `wandlungspreis-wandlungspruefung-trigger` | Wandlungspreis Wandlungspruefung Trigger im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Wandlungspreis auf Basis vertraglich vereinbarter Parameter, Wandlung bei Liquidationsereignis Auflösung oder Exit prüfen. Liefert priorisierte... |
| `wandlungspruefung-trigger` | Wandlungspruefung Trigger im Plugin Wandeldarlehen Lebenszyklus: prüft konkret Wandlung bei Laufzeitablauf des Wandeldarlehens prüfen wenn, Wandlung bei qualifizierter Finanzierungsrunde prüfen wenn. Liefert priorisierten Output mit Norm... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
