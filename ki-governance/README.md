# KI-Governance-Plugin

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`ki-governance`) | [`ki-governance.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/ki-governance.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **NeuroChain Labs — Gründung eines KI/Krypto-Startups in Berlin, Musterprotokoll vs. individuelle Satzung** (`gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll`) | [Gesamt-PDF lesen](../testakten/gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll/gesamt-pdf/gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll_gesamt.pdf) | [`testakte-gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll.zip) |
| **KI-Governance Konzern-Rollout — Thalheim Industries SE** (`ki-governance-konzern-rollout-thalheim-industries`) | [Gesamt-PDF lesen](../testakten/ki-governance-konzern-rollout-thalheim-industries/gesamt-pdf/ki-governance-konzern-rollout-thalheim-industries_gesamt.pdf) | [`testakte-ki-governance-konzern-rollout-thalheim-industries.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-ki-governance-konzern-rollout-thalheim-industries.zip) |
| **Akte Lahnwerke Maschinenbau AG - Slack, AirTags und IT-Sicherheitslage** (`nis2-cybersecurity-lahnwerke-slack-airtags-it-sicherheit`) | [Gesamt-PDF lesen](../testakten/nis2-cybersecurity-lahnwerke-slack-airtags-it-sicherheit/gesamt-pdf/nis2-cybersecurity-lahnwerke-slack-airtags-it-sicherheit_gesamt.pdf) | [`testakte-nis2-cybersecurity-lahnwerke-slack-airtags-it-sicherheit.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-nis2-cybersecurity-lahnwerke-slack-airtags-it-sicherheit.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Abläufe für betriebliche und kanzleiinterne KI-Governance: Use-Case-Triage, KI-Folgenabschätzungen,
Vendor-KI-Review und Gap-Analyse neuer Rechtsakte gegenüber bestehender Richtlinien- und Praxislage.
Das Plugin ist auf die EU-KI-Verordnung (VO 2024/1689, "KI-VO"), die DSGVO, das BDSG sowie
einschlägige deutschsprachige Rechtsgrundlagen (ProdHaftG, GeschGehG, UrhG, § 203 StGB) ausgerichtet.

**Jede Ausgabe ist ein Entwurf zur anwaltlichen Prüfung – mit Fundstellen, Markierungen und
Kontrollgates versehen; kein Rechtsgutachten.** Das Plugin erledigt die Vorarbeit: Dokumente
lesen, Prüfrahmen anwenden, Probleme aufdecken, Memo entwerten. Der Anwalt prüft, verifiziert
und entscheidet. Quellenangaben sind nach Herkunft gekennzeichnet. Berufsrechtliche Markierungen
(§ 203 StGB, § 43a Abs. 2 BRAO) werden konservativ gesetzt. Folgenreiche Handlungen
(Einreichen, Versenden, Ausführen) werden vor Umsetzung explizit bestätigt.

## Zielgruppe

| Rolle | Primäre Abläufe |
|---|---|
| **Datenschutzbeauftragte / KI-Governance-Counsel** | Folgenabschätzungen, Vendor-KI-Review, Gap-Analyse |
| **Syndikusanwälte / Produktjuristen** | Use-Case-Triage, Launch-Review mit KI-Komponente |
| **GC / Legal Ops** | KI-Richtlinien-Governance, Eskalation, Vorstandsthemen |
| **Einkauf / Vertragsrecht** | Vendor-KI-Vertragsreview nach Art. 28 DSGVO / Art. 11 KI-VO |

## Erster Start: das Kaltstart-Interview

Das Plugin befragt Sie, um zu erfahren: Sind Sie Anbieter, Betreiber oder beides? Welche
Regelwerke greifen konkret? Wo sind die roten Linien? Wie sieht eine interne Folgenabschätzung
bei Ihnen aus? Danach liest es Ihre Seed-Dokumente und lernt Ihre tatsächlichen Positionen
und Ihren Haustil.

```
/ki-governance:ki-governance-kaltstart-interview
```

## Befehle

| Befehl | Funktion |
|---|---|
| `/ki-governance:ki-governance-kaltstart-interview` | Kaltstart-Interview – schreibt Ihr Praxisprofil |
| `/ki-governance:ki-inventar [list \| add \| edit \| classify \| show]` | KI-Inventar verwalten – Rolle und Risikoklasse je KI-System nach KI-VO erfassen |
| `/ki-governance:anwendungsfall-triage [Anwendungsfall]` | Use-Case gegen Ihr Register prüfen (genehmigt / bedingt / nie) |
| `/ki-governance:ki-folgenabschaetzung [Anwendungsfall]` | KI-Folgenabschätzung (FRIA Art. 27 KI-VO + DSFA Art. 35 DSGVO) erstellen |
| `/ki-governance:ki-anbieter-pruefung [Anbieter/Datei]` | Vendor-KI-Vertrag gegen Ihre Positionen prüfen |
| `/ki-governance:regulierungs-luecken-analyse [Rechtsakt]` | Neuen Rechtsakt oder Leitlinie gegen aktuelle Richtlinien/Praxis abgleichen |
| `/ki-governance:richtlinien-monitor` | Wöchentliche Prüfung auf Richtliniendrift oder direkte Anfrage zu neuer Praxis |
| `/ki-governance:richtlinien-vorlage` | Erstentwurf einer KI-Richtlinie auf Basis Ihres Praxisprofils erstellen |
| `/ki-governance:ki-governance-mandat-arbeitsbereich` | Mandatsworkspaces verwalten (nur Kanzleipraxis) – new, list, switch, close, none |

## Skills

| Skill | Zweck |
|---|---|
| **kaltstart-interview** | Schreibt `~/.claude/plugins/config/claude-fuer-deutsches-recht/ki-governance/CLAUDE.md` aus Interview + Seed-Dokumente |
| **ki-inventar** | KI-Inventar nach KI-VO – Rolle (Anbieter, Betreiber, Einführer, Händler, Bevollmächtigter, Produkthersteller) und Risikoklasse je System, Art. 6 KI-VO |
| **anwendungsfall-triage** | Prüft Anwendungsfälle gegen das Register; meldet fehlende Folgenabschätzungen |
| **ki-folgenabschaetzung** | KI-Folgenabschätzung im Hausformat (FRIA + DSFA) |
| **ki-anbieter-pruefung** | KI-spezifischer Vertragsreview gegen Governance-Positionen (Art. 11 KI-VO, Art. 28 DSGVO) |
| **regulierungs-luecken-analyse** | Neuer Rechtsakt/Leitlinie vs. Ist-Stand, Remediation-Plan |
| **richtlinien-monitor** | Prüft Ausgaben auf Praxisdrift; entwirft KI-Richtlinien-Updates |
| **richtlinien-vorlage** | Erstellt KI-Richtlinien-Entwurf auf Basis publizierter Musterrichtlinien (BVDW, Bitkom, EDSA, BSI, KI-VO), angepasst an Ihr Praxisprofil |
| **mandat-arbeitsbereich** | Mandatsworkspaces anlegen, auflisten, wechseln und schließen; isoliert jeden Mandanten/Auftrag, damit Kontext nicht durchsickert |

## Schnellstart

### 1. Einrichtung

```
/ki-governance:ki-governance-kaltstart-interview
```

Halten Sie bereit (soweit vorhanden): Ihre KI- oder Acceptable-Use-Richtlinie, eine frühere
Folgenabschätzung, Vendor-KI-Verträge, KI-Modell-Inventar oder genehmigte Tool-Liste.

Ihre Konfiguration wird gespeichert unter
`~/.claude/plugins/config/claude-fuer-deutsches-recht/ki-governance/CLAUDE.md`
und überlebt Plugin-Updates.

### 2. Neuen Anwendungsfall prüfen

```
/ki-governance:anwendungsfall-triage "Vertrieb möchte KI zur automatischen Lead-Bewertung einsetzen"
```

Ausgabe: Risikoklasse nach KI-VO, Registerabgleich oder -lücke, erforderliche Bedingungen,
Folgenabschätzung erforderlich oder nicht.

### 3. Folgenabschätzung erstellen

```
/ki-governance:ki-folgenabschaetzung "KI-gestützte Lebenslauf-Analyse für HR"
```

Aufnahme-Fragen → Folgenabschätzung im Hausformat → Richtlinien-Konsistenzprüfung →
Mitigationsbedingungen.

### 4. Vendor-KI-Vertrag prüfen

```
/ki-governance:ki-anbieter-pruefung openai-terms.pdf
```

Ausgabe: Klausel-für-Klausel-Vergleich mit Ihren Positionen, vorgeschlagene Änderungen,
Eskalationslücken.

## Dreieck: KI-Governance ↔ Produktrecht ↔ Datenschutzrecht

Diese drei Plugins sind aufeinander abgestimmt. KI-Governance ist das dritte Element.

- **Produktrecht** erkennt, wenn ein Launch eine KI-Komponente enthält → Übergabe an
  `/ki-governance:anwendungsfall-triage` und `/ki-governance:ki-folgenabschaetzung`
- **Datenschutzrecht** erkennt, wenn ein KI-Anwendungsfall personenbezogene Daten umfasst →
  Übergabe an `/datenschutzrecht:dsfa-erstellung`, sofern das Plugin installiert ist
- **KI-Governance** erkennt, wenn eine Folgenabschätzung datenschutzrechtliche Fragen aufwirft →
  Übergabe an `/datenschutzrecht:dsfa-erstellung`

Die Übergabe ist explizit: Jedes Plugin meldet, wann das andere benötigt wird, und benennt
die zu klärende Frage.

## Rechtliche Grundlagen (Überblick)

| Rechtsakt | Relevanz im Plugin |
|---|---|
| **KI-VO (VO 2024/1689)** | Risikoklassen (Art. 6, Anh. I–III), Verbote (Art. 5), Betreiberpflichten (Art. 26), Transparenz (Art. 50), Bußgeld (Art. 99), FRIA (Art. 27), Technische Dokumentation (Art. 11) |
| **DSGVO** | DSFA (Art. 35), Auftragsverarbeitung (Art. 28), Auskunftsrecht (Art. 15), Automatisierte Entscheidungen (Art. 22) |
| **BDSG** | Beschäftigtendatenschutz (§ 26), ergänzende Regelungen zur DSGVO |
| **ProdHaftG / Produktsicherheitsrecht** | KI-Systeme als Produkte; Haftung für fehlerhafte KI-Ausgaben |
| **GeschGehG** | Schutz von Trainings- und Prozessdaten, Geheimhaltungspflichten |
| **UrhG / § 44b UrhG** | Text- und Data-Mining-Schranke (Art. 4 DSM-RL), Trainingsdaten, Opt-out |
| **§ 203 StGB** | Mandantengeheimnis, Schweigepflicht bei KI-Einsatz in der Kanzlei |

## Dateistruktur

```
ki-governance/
├── CLAUDE.md
├── README.md
├── references/
│   └── currency-watch.md
└── skills/
    ├── kaltstart-interview/
    ├── ki-inventar/          (ki-inventar)
    ├── anwendungsfall-triage/
    ├── ki-folgenabschaetzung/
    ├── ki-anbieter-pruefung/
    ├── regulierungs-luecken-analyse/
    ├── richtlinien-monitor/
    ├── richtlinien-vorlage/
    ├── mandat-arbeitsbereich/
    └── anpassen/
```

## Wie das Plugin lernt

Ihr Praxisprofil unter
`~/.claude/plugins/config/claude-fuer-deutsches-recht/ki-governance/CLAUDE.md`
ist nicht statisch – es verbessert sich durch die Nutzung. Skills zeigen an, wenn eine Ausgabe
auf einem Standard basiert, den Sie anpassen sollten. Der `richtlinien-monitor`-Agent beobachtet
Drift zwischen Ihrer KI-Governance-Richtlinie und Ihrer Praxis und schlägt Updates vor.
Sie können das Setup wiederholen, die Datei direkt bearbeiten oder einem Skill mitteilen, eine
neue Position zu erfassen.

## Hinweise

- **Gap-Analyse** (`regulierungs-luecken-analyse`) verarbeitet eingehende Rechtsakte. **Policy-Monitor**
  behandelt internen Praxisdrift. Verschiedene Werkzeuge für verschiedene Änderungsrichtungen.
- Policy-Monitor benötigt einen konfigurierten Ausgabeordner für den Sweep. Direktabfrage-Modus
  funktioniert ohne diesen.
- Use-Case-Triage ist nur so gut wie das Register. Verbringen Sie Zeit im Setup-Interview damit,
  die roten Linien richtig zu erfassen – sie steuern alles.
- Format der Folgenabschätzung kommt aus Ihrer Seed-Folgenabschätzung. Ohne Seed-Dokument
  wird eine Grundstruktur verwendet – führen Sie das Setup erneut durch, um es zu verbessern.
- Anbieter- und Betreiberpflichten werden getrennt behandelt. Wenn Sie beides sind, fragen die
  Skills, welche Rolle Sie für die jeweilige Aufgabe tragen.
- Gap-Analyse ist manuell (Sie weisen auf einen Rechtsakt oder ein Leitliniendokument hin). Für
  automatisiertes Monitoring koppeln Sie mit dem `regulatorisches-recht`-Plugin.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anschluss-router` | Nutze dies, wenn Allgemein, Workflow Anschluss Skills Router, Workflow Chronologie Und Belegmatrix im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Anschluss Skills Router, Workflow Chronologie... |
| `case-dpia-drift` | Nutze dies, wenn Spezial Case Tatbestand Beweis Und Belege, Spezial Dpia Risikoampel Und Gegenargumente, Spezial Drift Verhandlung Vergleich Und Eskalation im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Spezial C... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `dsgvo-governance-inventar` | Nutze dies, wenn Spezial Dsgvo Erstpruefung Und Mandatsziel, Spezial Governance Compliance Dokumentation Und Akte, Spezial Inventar Dokumentenmatrix Und Lueckenliste im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte... |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Ki Governance.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies, wenn Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation, Workflow Redteam Qualitygate im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche... |
| `gpai-modelle-ki-anbieter-arbeitsrecht` | Nutze dies, wenn Gpai Modelle Systemic Risk, Ki Anbieter Prüfung, Ki Arbeitsrecht Mitbestimmung im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Gpai Modelle Systemic Risk, Ki Anbieter Prüfung, Ki Arbeitsrecht Mitb... |
| `inventar-kontrollen-konformitaetsbewertung` | Nutze dies, wenn Spezial Ki Inventar Governance Und Kontrollen, Spezial Konformitaetsbewertung Red Team Und Qualitaetskontrolle, Spezial Marketing Mandantenkommunikation Entscheidungsvorlage im Plugin Ki Governance konkret bearbeitet wer... |
| `ki-folgenabschaetzung-ki-governance-mandat` | Nutze dies, wenn Ki Folgenabschaetzung, Ki Governance Anpassen, Ki Governance Mandat Arbeitsbereich im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Ki Folgenabschaetzung, Ki Governance Anpassen, Ki Governance Mand... |
| `ki-governance-kaltstart-interview` | KI-Governance-Plugin erstmalig einrichten oder Inventar der KI-Systeme im Unternehmen erfassen und AI-Act-Anwendungsbereich prüfen. Führt Erstgespraech durch ermittelt KI-Inventar Rolle im KI-Lieferkette (Anbieter/Betreiber Art. 3 KI-VO... |
| `ki-inventar-marketing-werbung-rote-linien` | Nutze dies, wenn Ki Inventar, Ki Marketing Und Werbung, Ki Rote Linien Art 5 Prüfen im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Ki Inventar, Ki Marketing Und Werbung, Ki Rote Linien Art 5 Prüfen prüfen.; Erste... |
| `kig-konformitaetsbewertung-risikobewertung` | Nutze dies, wenn Kig Konformitaetsbewertung Spezial, Kig Risikobewertung Hochrisiko Leitfaden, Regulierungs Luecken Analyse im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Kig Konformitaetsbewertung Spezial, Kig R... |
| `monitoring-quellenkarte` | Nutze dies, wenn Monitoring Quellenkarte im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `rechtsquellen-sonderfall-edge-case` | Nutze dies, wenn Rechtsquellen: Sonderfall und Edge-Case-Prüfung im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `review-richtlinie` | Nutze dies, wenn Spezial Prüfung Internationaler Bezug Und Schnittstellen, Spezial Review Schriftsatz Brief Und Memo Bausteine, Spezial Richtlinie Zahlen Schwellen Und Berechnung im Plugin Ki Governance konkret bearbeitet werden soll. Au... |
| `richtlinien-monitor-vorlage-anbieter` | Nutze dies, wenn Richtlinien Monitor, Richtlinien Vorlage, Spezial Anbieter Mehrparteien Konflikt Und Interessen im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Richtlinien Monitor, Richtlinien Vorlage, Spezial An... |
| `rollen-rasci-hochrisiko-anhang-incident` | Nutze dies, wenn Ki Governance Rollen Rasci, Ki Hochrisiko Anhang Iii Prüfen, Ki Incident Management Art 73 im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Ki Governance Rollen Rasci, Ki Hochrisiko Anhang Iii Prüf... |
| `rollenmodell-use-case-vendor` | Nutze dies, wenn Spezial Rollenmodell Formular Portal Und Einreichung, Spezial Use Case Risk Classification, Spezial Vendor Behörden Gericht Und Registerweg im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Spezial... |
| `triage-haftung-versicherung-anwendungsfall` | Nutze dies, wenn Spezial Triage Fristen Form Und Zustaendigkeit, Ki Haftung Und Versicherung, Anwendungsfall Triage im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Spezial Triage Fristen Form Und Zustaendigkeit, K... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `vo-pflichtenpyramide-kig-ai-kig-foundation` | Nutze dies, wenn Ki Vo Pflichtenpyramide Einfuehrung, Kig Ai Act Rollenmodell Bauleiter, Kig Foundation Model Anbieterpflichten Spezial im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Ki Vo Pflichtenpyramide Einfu... |
| `werbung-beweislast` | Nutze dies, wenn Spezial Werbung Beweislast Und Darlegungslast im Plugin Ki Governance konkret bearbeitet werden soll. Auslöser: Bitte Spezial Werbung Beweislast Und Darlegungslast prüfen.; Erstelle eine Arbeitsfassung zu Spezial Werbung... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
