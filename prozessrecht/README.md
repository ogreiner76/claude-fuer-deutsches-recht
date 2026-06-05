# Prozessrecht-Plugin

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`prozessrecht`) | [`prozessrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/prozessrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Kita Mühlenhof Lichtenrade - HOAI-Leistungsphasen und Bauüberwachung 2026** (`hoai-leistungsphasen-kita-muehlenhof-lichtenrade-2026`) | [Gesamt-PDF lesen](../testakten/hoai-leistungsphasen-kita-muehlenhof-lichtenrade-2026/gesamt-pdf/hoai-leistungsphasen-kita-muehlenhof-lichtenrade-2026_gesamt.pdf) | [`testakte-hoai-leistungsphasen-kita-muehlenhof-lichtenrade-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-hoai-leistungsphasen-kita-muehlenhof-lichtenrade-2026.zip) |
| **Werkvertragsstreit Pohlmann / Saalbau Rosenheim — Baumängel, BGH-Revision, Zurückverweisung** (`zivilprozess-werkvertragsstreit-saalbau-rosenheim-bgh-revision-pohlmann`) | [Gesamt-PDF lesen](../testakten/zivilprozess-werkvertragsstreit-saalbau-rosenheim-bgh-revision-pohlmann/gesamt-pdf/zivilprozess-werkvertragsstreit-saalbau-rosenheim-bgh-revision-pohlmann_gesamt.pdf) | [`testakte-zivilprozess-werkvertragsstreit-saalbau-rosenheim-bgh-revision-pohlmann.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-zivilprozess-werkvertragsstreit-saalbau-rosenheim-bgh-revision-pohlmann.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Unterstützung für Prozessanwälte und Syndikusrechtsanwälte bei der Führung eines Mandatsportfolios im deutschen Zivil-, Straf-, Verwaltungs- und Arbeitsrecht. Der Kaltstart-Interview erfasst Risikobereitschaft, Mandatslandschaft und Kanzleistil – der Rahmen, gegen den jedes neue Mandat eingeordnet wird. Einheitliche Aufnahme (Intake) überführt neue Mandate in strukturierte Logeinträge und mandatsbezogene Historiendateien. Statusübersichten und Tiefenbriefings lesen aus dem Log.

Konzipiert für Anwälte, die viele Mandate gleichzeitig betreuen, von denen die meisten durch externe Kanzleien oder Korrespondenzanwälte bearbeitet werden. Dieses Plugin ist ein Denkpartner, kein Mandatsverwaltungssystem. Wenn Sie LawVu, SimpleLegal oder eine vergleichbare Software einsetzen, ersetzt dieses Plugin diese nicht – es ergänzt sie als strukturierte Argumentations- und Analyseschicht.

**Jede Ausgabe ist ein Entwurf zur anwaltlichen Prüfung – zitiert, markiert und abgesichert –, keine rechtliche Schlussfolgerung.** Das Plugin erledigt die Arbeit: liest die Dokumente, wendet Ihr Playbook an, findet die Probleme, entwirft das Memo. Ein Anwalt prüft, verifiziert und entscheidet. Zitate sind nach Quelle gekennzeichnet, damit klar ist, welche aus einem Recherchetool stammen und welche noch zu überprüfen sind. Mandatsgeheimnismarker werden konservativ angewendet, damit keine unbeabsichtigte Offenbarung erfolgt (§ 43a Abs. 2 BRAO, § 203 StGB). Folgenreiche Handlungen – Einreichen, Versenden, Vollstrecken – sind durch ausdrückliche Bestätigung abgesichert.

## Voraussetzungen

Einige Funktionen verweisen auf Outlook- und Kalender-Integrationen. Diese erfordern MCP-Server in Ihrer Umgebung – sie sind nicht im Plugin enthalten. Ohne sie werden Ausgaben als Dateien gespeichert:

- **Outlook MCP** – `/gegenseite-status` erstellt Outlook-Entwürfe, sofern authentifiziert; andernfalls Markdown-Entwürfe in `gegenseite-status/[JJJJ-MM-TT]/[slug].md`.
- **Kalender-MCP** – keine automatische Terminplanung enthalten. Richten Sie eine Wiederholungserinnerung ein, um wöchentliche Befehle aufzurufen.

Das Plugin funktioniert vollständig ohne beide Integrationen; diese sind additiv.

## Für wen ist das?

| Rolle | Hauptverwendung |
|---|---|
| **Prozessanwalt (Kanzlei oder Syndikus)** | Alles – Intake, Triage, Status, Historie, Briefings |
| **Stellvertretender Justiziar / leitender Syndikus** | Portfolio-Übersicht, Vorstandsberichterstattung |
| **Hauptjustiziar / Leiter Rechtsabteilung** | Schneller Portfoliostatus, Tiefeneinblick in einzelne Mandate |
| **Außenanwalt** | Per-Mandat-Verlaufsdokumentation, Schriftsatzentwürfe, Fristen |

## Anwendungsbereich

Das Plugin deckt das **deutsche Zivilprozessrecht (ZPO)** als Kernbereich ab und enthält spezialisierte Skills für:

- **Strafrecht / Strafverteidigung** – StPO, Pflichtverteidigung, Akteneinsicht
- **Digitale StPO-Ermittlungsmaßnahmen** – biometrischer Internetabgleich, KI-Analyseplattformen, Akteneinsicht, Benachrichtigung, Löschung und Verwertungsangriffe
- **Verwaltungsrecht** – VwGO, Widerspruchsverfahren
- **Arbeitsrecht** – ArbGG, einstweiliger Rechtsschutz
- **Familienrecht** – FamFG
- **Steuerrecht** – FGO, BFH
- **Sozialrecht** – SGG, BSG
- **Zwangsvollstreckung** – §§ 704 ff. ZPO
- **Einstweilige Verfügung** – §§ 935, 940 ZPO
- **Mahnverfahren** – §§ 688 ff. ZPO
- **Verkehrsunfallrecht** – StVG, § 115 VVG

Für harte ZPO-Fakten gibt es den Spezialskill `amtlicher-zpo-verfahrenscheck`. Er nutzt den aktuellen amtlichen ZPO-Normkern und trennt Zuständigkeit, Form, Zustellung, Fristen, Klage, Beweis, Mahnverfahren, Vollstreckung, Arrest und einstweilige Verfügung.

## Vorprozessuale Beweiserhebung im deutschen Recht

Informationsbeschaffung erfolgt durch:
- §§ 142, 144 ZPO (gerichtliche Urkundenvorlegung und Augenschein)
- § 810 BGB (Einsichtnahme in Urkunden)
- §§ 242, 259, 260, 666 BGB (Auskunftsansprüche)
- Art. 15 DSGVO (Auskunftsrecht)
- § 254 ZPO (Stufenklage)
- §§ 485 ff. ZPO (Selbständiges Beweisverfahren)

Zum Schutz anwaltlicher Unterlagen: § 43a Abs. 2 BRAO, § 203 StGB; Zeugnisverweigerungsrecht § 383 Abs. 1 Nr. 6 ZPO; Beschlagnahmefreiheit §§ 97, 53 StPO; Editionsverweigerung §§ 142, 383 ZPO.

Urteile sind nicht bindend (außer § 31 BVerfGG). Literatur und Kommentare sind tragende Argumentationsquellen.

## Rechtsgebiete und Verfahrensordnungen

| Verfahren | Rechtsgrundlage |
|---|---|
| Zivilprozess | ZPO, GVG, RVG, GKG |
| Strafprozess | StPO, GVG, RVG |
| Verwaltungsstreit | VwGO, VwVfG |
| Finanzgerichtsbarkeit | FGO, AO |
| Sozialgerichtsbarkeit | SGG, SGB |
| Arbeitsgerichtsbarkeit | ArbGG, KSchG |
| Familiensachen | FamFG, BGB |
| Zwangsvollstreckung | §§ 704–915h ZPO |

## Dateistruktur

```
prozessrecht/
├── CLAUDE.md              # Praxisprofil (vom Kaltstart geschrieben)
├── README.md              # Diese Datei
├── mandate/               # Pro-Mandat-Ordner: mandat.md + verlauf.md
│   └── _log.yaml          # Portfolio-Log aller Mandate
├── demand-letters/        # Ausgehende Schreiben und Entwürfe
├── inbound/               # Eingegangene Schreiben, Mahnungen, Beschlüsse
├── gegenseite-status/             # Korrespondenz mit Gegenseite / Außenanwälten
└── skills/                # Plugin-Skills (automatisch geladen)
```

## Nutzungshinweis

Alle Ausgaben des Plugins sind **Entwürfe zur anwaltlichen Prüfung**. Das Plugin ersetzt keine Rechtsberatung und trifft keine Entscheidungen. Berufsrechtliche Pflichten nach BRAO, BORA, RVG und die anwaltliche Verschwiegenheit nach § 43a Abs. 2 BRAO bleiben unberührt. Für die Überprüfung und Freigabe jedes Dokuments ist stets der verantwortliche Anwalt zuständig.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 25 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen U... |
| `amtlicher-zpo-proz-bauleiter-eilverfahren` | Nutze dies, wenn Amtlicher Zpo Verfahrenscheck, Proz Zustaendigkeit Bauleiter, Spezial Eilverfahren Risikoampel Und Gegenargumente im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Amtlicher Zpo Verfahrenscheck, Proz... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Prozessrecht.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `anspruchstabelle` | Anspruchstabelle für zivilprozessuales Mandat erstellen: alle Ansprüche und Gegenansprüche tabellarisch erfassen. Normen: §§ 253 261 ZPO. Prüfraster: Anspruchsgrundlage, Betrag, Verjaebrung, Beweisstatus. Output: Anspruchstabelle als Gru... |
| `anspruchstabelle-gegenseite-interessen` | Nutze dies, wenn Spezial Anspruchstabelle Compliance Dokumentation Und Akte, Spezial Gegenseite Mehrparteien Konflikt Und Interessen, Spezial Mahnbescheid Dokumentenmatrix Und Lueckenliste im Plugin Prozessrecht konkret bearbeitet werden... |
| `beweissicherung-einstweilige-verfuegung` | Nutze dies, wenn Beweissicherung, Chronologie, Einstweilige Verfuegung im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Beweissicherung, Chronologie, Einstweilige Verfuegung prüfen.; Erstelle eine Arbeitsfassung zu... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Prozessrecht.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `gegenseite-status-mahnbescheid-mahnschreiben` | Nutze dies, wenn Gegenseite Status, Mahnbescheid, Mahnschreiben Aufnahme im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Gegenseite Status, Mahnbescheid, Mahnschreiben Aufnahme prüfen.; Erstelle eine Arbeitsfassung... |
| `mahnschreiben-entwurf-anwaltsgeheimnis` | Nutze dies, wenn Mahnschreiben Entwurf, Anwaltsgeheimnis Prüfung, Argumentationsverbesserung Red Team im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Mahnschreiben Entwurf, Anwaltsgeheimnis Prüfung, Argumentationsv... |
| `mahnschreiben-erhalten-aktualisierung` | Nutze dies, wenn Mahnschreiben Erhalten, Mandat Aktualisierung, Mandat Aufnahme im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Mahnschreiben Erhalten, Mandat Aktualisierung, Mandat Aufnahme prüfen.; Erstelle eine... |
| `mandat-briefing-schliessen-portfolio-status` | Nutze dies, wenn Mandat Briefing, Mandat Schliessen, Portfolio Status im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Mandat Briefing, Mandat Schliessen, Portfolio Status prüfen.; Erstelle eine Arbeitsfassung zu Ma... |
| `mandat-mandate-prozessrecht` | Nutze dies, wenn Spezial Mandat Formular Portal Und Einreichung, Spezial Mandate Tatbestand Beweis Und Belege, Spezial Prozessrecht Verhandlung Vergleich Und Eskalation im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bit... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `proz-beweismittel-leitfaden-mediationsklage` | Nutze dies, wenn Proz Beweismittel Leitfaden, Proz Mediationsklage Guete Spezial, Proz Prozessfinanzierung Spezial im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Proz Beweismittel Leitfaden, Proz Mediationsklage G... |
| `proz-quellenkarte` | Nutze dies, wenn Proz Quellenkarte im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `prozessrecht-kaltstart-interview` | Prozessrechtliches Erstinterview strukturiert durchführen: Sachverhalt, Klagebegehren, Fristen, Kosten. Normen: §§ 253 261 ZPO, BRAO. Prüfraster: Anspruchsgrundlage, Zuständigkeit, Verjaebrung, Kostenrisiko. Output: Interviewprotokoll mi... |
| `prozessrecht-mandat-arbeitsbereich-abschnitt` | Nutze dies, wenn Prozessrecht Anpassen, Prozessrecht Mandat Arbeitsbereich, Schriftsatz Abschnitt im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Prozessrecht Anpassen, Prozessrecht Mandat Arbeitsbereich, Schriftsa... |
| `prozessrechtliche-schriftsaetze-status` | Nutze dies, wenn Spezial Prozessrechtliche Erstpruefung Und Mandatsziel, Spezial Schriftsaetze Schriftsatz Brief Und Memo Bausteine, Spezial Status Internationaler Bezug Und Schnittstellen im Plugin Prozessrecht konkret bearbeitet werden... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `streitwert-verkehrsunfall-vollstreckung` | Nutze dies, wenn Streitwert, Verkehrsunfall, Vollstreckung im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Streitwert, Verkehrsunfall, Vollstreckung prüfen.; Erstelle eine Arbeitsfassung zu Streitwert, Verkehrsunfa... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `verfahrensart-rechtsweg` | Nutze dies, wenn Spezial Fristen Fristen Form Und Zustaendigkeit, Spezial Verfahrensart Rechtsweg Zustaendigkeit, Spezial Zustaendigkeit Zahlen Schwellen Und Berechnung im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bit... |
| `vollstreckung-stpo-biometrischer` | Nutze dies, wenn Spezial Vollstreckung Behörden Gericht Und Registerweg, Stpo Biometrischer Internetabgleich Und Ki Ermittlung, Strafverteidigung Ersttermin im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Spezial V... |
| `vorlageanordnung-zeuge-vorbereitung` | Nutze dies, wenn Vorlageanordnung, Zeuge Vorbereitung im Plugin Prozessrecht konkret bearbeitet werden soll. Auslöser: Bitte Vorlageanordnung, Zeuge Vorbereitung prüfen.; Erstelle eine Arbeitsfassung zu Vorlageanordnung, Zeuge Vorbereitu... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
