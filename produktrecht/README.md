# Produkthaftung und Produktrecht (Plugin `produktrecht`)

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`produktrecht`) | [`produktrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/produktrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **BGB BT — Smart-Kühlschrank, digitale Elemente und Reparaturblockade** (`bgb-bt-smart-kuehlschrank-digital-repair-koeln`) | [Gesamt-PDF lesen](../testakten/bgb-bt-smart-kuehlschrank-digital-repair-koeln/gesamt-pdf/bgb-bt-smart-kuehlschrank-digital-repair-koeln_gesamt.pdf) | [`testakte-bgb-bt-smart-kuehlschrank-digital-repair-koeln.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bgb-bt-smart-kuehlschrank-digital-repair-koeln.zip) |
| **Projekt Isarlicht — Kernfusion und Transrapid am Starnberger See** (`kernfusion-transrapid-starnberger-see`) | [Gesamt-PDF lesen](../testakten/kernfusion-transrapid-starnberger-see/gesamt-pdf/kernfusion-transrapid-starnberger-see_gesamt.pdf) | [`testakte-kernfusion-transrapid-starnberger-see.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kernfusion-transrapid-starnberger-see.zip) |
| **Produkthaftung Frischwind Mobility GmbH — Akku-Brände E-Bike Wind-X7, Produktrückruf, Strafverfahren** (`produkthaftung-akku-brand-e-bike-frischwind-mobility-erfurt`) | [Gesamt-PDF lesen](../testakten/produkthaftung-akku-brand-e-bike-frischwind-mobility-erfurt/gesamt-pdf/produkthaftung-akku-brand-e-bike-frischwind-mobility-erfurt_gesamt.pdf) | [`testakte-produkthaftung-akku-brand-e-bike-frischwind-mobility-erfurt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-produkthaftung-akku-brand-e-bike-frischwind-mobility-erfurt.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Rechtliche Abläufe für Produktteams, Hersteller, Händler und Kanzleien: Produktsicherheit, Produkthaftung, Produktbeobachtung, Rückruf, Marktüberwachung, Software-/OTA-Updates, Right to Repair und Launch-Review. Der Ordner heißt weiter `produktrecht`, damit bestehende Links stabil bleiben; inhaltlich ist das Plugin jetzt ausdrücklich auch ein Produkthaftungs- und Produktlebenszyklus-Plugin.

Es trennt sauber zwischen Produktsicherheit/Behördenpflichten, verschuldensunabhängiger Produkthaftung, deliktischer Produzentenhaftung, vertraglicher Gewährleistung, digitalem Kaufrecht und künftigen Reparaturpflichten. Gerade bei vernetzten Waren wird nicht mehr gefragt “Hardware oder App?”, sondern: Welche Funktion hängt an Firmware, Cloud, Konto, Sensorik, Update oder Reparaturzugang?

**Alle Ausgaben sind Entwürfe zur anwaltlichen Prüfung – zitiert, markiert und abgesichert – keine rechtlichen Schlussfolgerungen.** Das Plugin erledigt die Arbeit: liest Dokumente, wendet Ihr Playbook an, findet Probleme, erstellt das Memo. Ein Anwalt prüft, verifiziert und entscheidet. Zitate sind nach Quelle gekennzeichnet. Berufsrechtliche Verschwiegenheitspflichten (§ 43a Abs. 2 BRAO, § 203 StGB) werden konservativ angewendet. Folgenreiche Maßnahmen – Abmahnungen, Einreichungen, Vertragsunterzeichnungen – sind durch explizite Bestätigung gesichert.

## Für wen ist dieses Plugin?

| Rolle | Hauptworkflows |
|---|---|
| **Produktjurist / Syndikusanwalt** | Launch-Review, Produktsicherheit, GPSR, Rückruf, Repair-/Update-Policy |
| **Produkthaftungsanwalt** | ProdHaftG, § 823 BGB, Produzentenhaftung, Beweisakte, Serienfehler, Regress |
| **Produktmanager / Engineering** | "Ist-das-ein-Problem?"-Triage, Software-/OTA-Änderungen, Repair-by-design |
| **Marketing / Brand** | Werbeaussagen-Prüfung vor Veröffentlichung |
| **GC / Leiter Rechtsabteilung** | Eskalierte Produktfälle, Marktüberwachung, Behördenkommunikation, Krisenstab |

## Erster Start: das Kaltstart-Interview

Verbindet sich mit Ihrem Launch-Tracker (Jira/Linear), liest zehn vergangene Launch-Reviews, lernt was Sie tatsächlich blockieren vs. durchwinken. Erstellt eine Risikokalibrierungstabelle, auf die jeder andere Skill zurückgreift.

Ihre Konfiguration wird unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/produktrecht/CLAUDE.md` gespeichert und überlebt Plugin-Updates.

```
/produktrecht:produktrecht-kaltstart-interview
```

## Befehle

| Befehl | Funktion |
|---|---|
| `/produktrecht:produktrecht-kaltstart-interview` | Kaltstart-Interview |
| `/produktrecht:launch-pruefung [PRD oder Ticket]` | Vollständiger Launch-Review gegen Ihr Framework |
| `/produktrecht:werbeaussagen-pruefung [Text]` | Werbeaussagen-Prüfung |
| `/produktrecht:ist-das-ein-problem [Frage]` | Schnelle "Ist-das-ein-Problem?"-Antwort |
| `/produktrecht:feature-risikobewertung [Feature]` | Tiefgehende Feature-Risikobewertung |
| `/produktrecht:impressum-pflicht` | Impressumspflichten prüfen (DDG, MStV) |
| `/produktrecht:preisangaben` | Preisangabenpflichten prüfen (PAngV) |
| `/produktrecht:produktrecht-mandat-arbeitsbereich` | Mandate verwalten (nur Multi-Mandanten-Praxis) |

## Skills

| Skill | Zweck |
|---|---|
| **kaltstart-interview** | Erstellt `~/.claude/plugins/config/claude-fuer-deutsches-recht/produktrecht/CLAUDE.md` aus Interview + vergangenen Launch-Reviews |
| **launch-pruefung** | Kategorie-für-Kategorie-Review, kalibriert auf Ihr Unternehmen (Sieben-Kategorien-Framework: Werberecht, Datenschutz, Produktsicherheit, AGB, Verbraucherrechte, Geistiges Eigentum, Aufsichtsrecht) |
| **werbeaussagen-pruefung** | Werbeaussagen-Taxonomie: Marktschreierische Anpreisung / Tatsachenbehauptung / Vergleich / implizierte Aussage / absolute Aussage; Prüfung nach §§ 5, 5a, 5b UWG und PAngV |
| **feature-risikobewertung** | Tiefgehende Analyse eines einzelnen Features (UWG, DSGVO, DSA, KI-VO, Verbraucherschutz BGB) |
| **ist-das-ein-problem** | Gleich-Minuten-Triage für die schnelle Slack-Frage |
| **impressum-pflicht** | Anbieterkennzeichnung §§ 5, 6 DDG (vormals TMG), § 18 MStV |
| **preisangaben** | PAngV-Prüfung: Gesamtpreis, Grundpreis, Streichpreise, Versandkosten |
| **mandat-arbeitsbereich** | Mandate anlegen, auflisten, wechseln und schließen für Multi-Mandanten-Praxis; isoliert Mandanten/Mandate so dass kein Kontext leckt |

## Interaktive Befehle vs. geplante Agenten

Die obigen Befehle laufen bei Aufruf – für laufende Arbeit an einem Mandat. Die Agenten unten laufen auf einem Zeitplan – für das, was sich bewegt während Sie nicht hinschauen:

| Agent | Was wird überwacht | Standard-Takt |
|---|---|---|
| **markteinführungs-monitor** | Launch-Tracker (Jira/Linear) auf bevorstehende Launches die wahrscheinlich rechtliche Prüfung benötigen; filtert Tickets mit Launch-Terminen in den nächsten 30 Tagen per Kalibrierungstabelle | Täglich |

## Integrationen

**Verbinden Sie zuerst ein Recherche-Tool – die Zitatschranken hängen davon ab.** Ohne eines wird jede Quellenangabe als `[prüfen]` markiert und der Prüfvermerk über jeder Ausgabe hält fest, dass Quellen nicht verifiziert wurden. Skills arbeiten beides; ein Recherche-Tool verschiebt Verifikationsarbeit von Ihrer Schulter.

Ausgeliefert mit in `.mcp.json` konfigurierten Konnektoren:

- **Slack** – Nachrichten suchen, Kanäle lesen, Diskussionen finden
- **Google Drive** – Dokumente suchen, lesen und abrufen
- **Linear** – Issue-Tracking und Projektmanagement
- **Atlassian** – Jira-Issues und Confluence-Seiten
- **Asana** – Aufgaben und Projekt-Tracking

Mit verbundenem Tracker: Kaltstart liest Launch-Historie, launch-pruefung liest Ticket-Kontext, markteinführungs-monitor-Agent überwacht den Kalender.

## Schnellstart

```
/produktrecht:produktrecht-kaltstart-interview
```

Dann:

```
/produktrecht:ist-das-ein-problem "Können wir den Preis auf der Preisseite A/B-testen?"
```

→ Antwort in einer Minute, kalibriert auf Ihre Risikotabelle.

```
/produktrecht:launch-pruefung PROJ-1234
```

→ Vollständiger Review, Kategorie für Kategorie, mit Aufgabenliste.

## Wie das Plugin lernt

Ihr Praxisprofil unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/produktrecht/CLAUDE.md` ist nicht statisch – es verbessert sich durch Nutzung. Skills zeigen an, wenn eine Ausgabe eine Standard-Einstellung verwendet hat, die Sie anpassen sollten. Sie können das Setup erneut ausführen, die Datei direkt bearbeiten oder einem Skill mitteilen, eine neue Position zu erfassen.

## Wichtige Normen dieses Plugins

- **UWG** (§§ 3, 5, 5a, 5b, 7 – unlautere Werbung, Irreführung, Belästigung)
- **PAngV 2022** (Preisangabenpflichten, Grundpreis § 4, Streichpreise § 11)
- **BGB §§ 305 ff.** (AGB-Kontrolle, Einbeziehung, Inhaltskontrolle)
- **DDG** (vormals TMG – Impressumspflicht §§ 5, 6, Haftung §§ 7 ff.)
- **TDDDG** (Cookie-Einwilligung, § 25 TDDDG)
- **ProdHaftG / § 823 BGB** (verschuldensunabhängige Produkthaftung und deliktische Produzentenhaftung)
- **ProdSG / GPSR VO (EU) 2023/988** (Produktsicherheit, Marktüberwachung, Rückverfolgbarkeit, Safety Business Gateway)
- **BGB §§ 327 ff., 434, 475b, 475c, 475e, 476, 477** (digitale Produkte, Waren mit digitalen Elementen, Updatepflichten, Beweislast, Verjährung)
- **Richtlinie (EU) 2024/1799** (Recht auf Reparatur; Umsetzungsstand jeweils live prüfen)
- **Richtlinie (EU) 2024/2853** (neue Produkthaftungsrichtlinie; Umsetzung und zeitliche Anwendbarkeit live prüfen)
- **MarkenG** (Markenverletzung, Benutzungsmarken, Verwechslungsgefahr)
- **AGG** (Diskriminierungsverbot, Benachteiligung)
- **EU-Verordnungen:** DSA, DMA, KI-VO (AI Act, EU 2024/1689)

## Hinweise

- Die Kalibrierungstabelle ist das Herzstück. Wenn sie falsch ist, ist jeder Review falsch. Neu ausführen wenn sich Ihre Risikoposition ändert (neues Regulierungsumfeld, neuer GC, neue Bußgeld-Entscheidung).
- `ist-das-ein-problem` ist so konzipiert, dass PMs es eigenständig nutzen können. Es antwortet schnell und leitet zu einer echten Prüfung weiter, wenn nötig.
- Feature-Risikobewertung ist für die 10% der Launches, die Tiefe benötigen. Die meisten tun es nicht – keine unnötige Dokumentenpflege.
- GPSR ist VO (EU) 2023/988. Die BatterieVO ist VO (EU) 2023/1542 und nur bei Batterie-/Akkubezug einschlägig.
- Right to Repair und neue Produkthaftungsrichtlinie sind in Übergang und Umsetzung zu behandeln. Tragende Aussagen zum deutschen Umsetzungsstand immer live verifizieren.

## Voraussetzungen

Einige Features referenzieren externe Integrationen (Dokumentenmanagementsystem, Launch-Tracker, Fallmanagementsystem, Regulierungs-Feeds). Diese sind nicht mitgeliefert – wenn Sie einen MCP-Server dafür in Ihrer Umgebung haben, verwenden ihn die relevanten Features. Ohne einen fällt das Plugin auf Datei-Upload und manuelle Abläufe zurück. Führen Sie `/produktrecht:produktrecht-kaltstart-interview --check-integrations` aus um zu sehen, was in Ihrer Umgebung verfügbar ist.

## Konfiguration

Ihre Konfiguration wird unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/produktrecht/CLAUDE.md` gespeichert und überlebt Plugin-Updates – Sie führen das Setup nur einmal aus.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 28 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `bewertungen-red-team-impressumspflicht` | Bewertungen RED Team Impressumspflicht im Plugin Produktrecht: prüft konkret Bewertungen, Chronologie, Impressumspflicht. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `eu-produktsicherheitsverordnung-feature` | EU Produktsicherheitsverordnung Feature im Plugin Produktrecht: prüft konkret EU-Produktsicherheitsverordnung GPSR (VO (EU) 2023/988) in, Tiefgehende Risikobewertung für ein einzelnes Feature oder, Prüft die Impressumspflicht für Website... |
| `ist-ki-act-marktueberwachung-kommunikation` | IST KI ACT Marktueberwachung Kommunikation im Plugin Produktrecht: prüft konkret Schnelle Ist-das-ein-Problem?-Antwort für die schnelle, KI-Verordnung-Integration in Produkte, Kommunikation mit Marktueberwachungsbehoerden (zentrale, BAu.... |
| `launch-livecheck-machinery` | Launch Livecheck Machinery im Plugin Produktrecht: prüft konkret Launch, Livecheck, Machinery. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `launch-pruefung` | Produktmanager oder Rechtsabteilung will vor dem Launch prüfen, ob das Produkt oder Feature produktrechtlich freigegeben werden kann. Vollständige rechtliche Freigabeprüfung gegen konfiguriertes Prüfrahmenwerk und Risikokalibrierung. Nor... |
| `nachhaltigkeitsklage-werbeaussagen` | Nachhaltigkeitsklage Werbeaussagen im Plugin Produktrecht: prüft konkret Nachhaltigkeits- und Greenwashing-Klagen nach UWG sowie, Prüft die Einhaltung der Preisangabenverordnung 2022, Spezialfall GPSR und CRA Fitness-Check digitale Produ... |
| `pangv-prodr-produktbeobachtung` | Pangv Prodr Produktbeobachtung im Plugin Produktrecht: prüft konkret Pangv, Prodr, Produktbeobachtung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `prodr-machinery-produktrueckruf` | Prodr Machinery Produktrueckruf im Plugin Produktrecht: prüft konkret Spezialfall Maschinenverordnung VO 2023 / 1230 Machinery, Leitfaden Produktrueckruf, Produktbeobachtung und Feldueberwachung nach § 4 ProdSG und. Liefert priorisierten... |
| `produktbeobachtung-software-produktrecht` | Produktbeobachtung Software Produktrecht im Plugin Produktrecht: prüft konkret Prüft Produktbeobachtungspflichten für Software, Firmware, OTA-Updates, digitale. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Sc... |
| `produkthaftung-grundlagen-produktsicherheit` | Produkthaftung Grundlagen Produktsicherheit im Plugin Produktrecht: prüft konkret Grundlagen Produkthaftung, Korrigiert und prüft die Produktsicherheitsroute nach, Prüft, wie Reparaturen. Liefert priorisierten Output mit Norm-Pinpoints,... |
| `produktlaunch-beweislast-rechtscheck` | Produktlaunch Beweislast Rechtscheck im Plugin Produktrecht: prüft konkret Produktlaunch, Produktlaunch-Rechtscheck von Impressum bis Marktüberwachung, Produktnutzung, Werbeclaim und Sicherheitsversprechen prüfen. Liefert priorisierten O... |
| `produktrecht-anschluss-router` | Anschluss Router im Plugin Produktrecht: prüft konkret Einstieg, Schnelltriage und Fallrouting im Produktrecht-Plugin, Zie, Anschluss-Skills Router im Plugin produktrecht. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und... |
| `produktrecht-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `produktrecht-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `produktrecht-fristen-risikoampel-mandantenkommunikation` | Fristen Risikoampel Mandantenkommunikation im Plugin Produktrecht: prüft konkret Fristen- und Risikoampel im Plugin produktrecht, Mandantenkommunikation im Plugin produktrecht, Red-Team Qualitygate im Plugin produktrecht. Liefert prioris... |
| `produktrecht-kaltstart-interview` | Produktrecht-Plugin erstmalig einrichten und Launch-Tracker verbinden sowie Risikokalibrierung der Rechtsabteilung erfassen. Verbindet Launch-Tracker liest vergangene Reviews lernt Risikokalibrierung. Normen ProdSG MarktueberwG CE-Kennze... |
| `produktrecht-output-waehlen` | Output wählen im Plugin Produktrecht: Diese Output-Weiche für Produktrecht entscheidet, ob Memo, Antrag, Schriftsatz, Tabelle, Risikoampel, Fragenliste oder Mandantenbrief der richtige nächste Schritt ist. |
| `produktrecht-produktrechtliche-rechtscheck` | Produktrechtliche Rechtscheck im Plugin Produktrecht: prüft konkret Produktrecht, Produktrechtliche, Rechtscheck. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `produktrecht-quellen-livecheck` | Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `produktrecht-rechtsquellen` | Rechtsquellen: Quellenprüfung; Internationaler Bezug und Schnittstellen: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `produktrecht-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `rechtsabteilung-cybersecurity-digitale` | Rechtsabteilung Cybersecurity Digitale im Plugin Produktrecht: prüft konkret Rechtsabteilungs-Fachmodul für Cybersecurity als, Rechtsabteilungs-Fachmodul für Digitale Elemente im, Rechtsabteilungs-Fachmodul für Right to Repair im. Liefer... |
| `rechtsabteilung-produkthaftungsrichtlinie-ce` | Rechtsabteilung Produkthaftungsrichtlinie CE im Plugin Produktrecht: prüft konkret Rechtsabteilungs-Fachmodul für Neue, CE-Kennzeichnung systematisch planen, Dual-Use-Gueter (EG-Dual-Use-VO 2021 821). Liefert priorisierten Output mit Nor... |
| `rechtsabteilung-rueckrufmanagement-repair-by` | Rechtsabteilung Rueckrufmanagement Repair BY im Plugin Produktrecht: prüft konkret Rechtsabteilungs-Fachmodul für Rückrufmanagement mit, Prüft technische und vertragliche Reparaturhindernisse wie, Seriennummer, Prüft. Liefert priorisiert... |
| `regulation-interessen-werbeaussagen` | Regulation Interessen Werbeaussagen im Plugin Produktrecht: prüft konkret Regulation, Prüfung von Werbeaussagen auf Irreführungs- und. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `review-prodr-produkthaftung-digital` | Review Prodr Produkthaftung Digital im Plugin Produktrecht: prüft konkret Review, Bauleiter Produkthaftung ProdHaftG und § 823 BGB, Prüft die neue EU-Produkthaftungsrichtlinie 2024/2853 für, KI-Systeme. Liefert priorisierten Output mit N... |
| `right-to-rueckruf-strategie` | Right TO Rueckruf Strategie im Plugin Produktrecht: prüft konkret Prüft das EU-Recht auf Reparatur nach Richtlinie (EU), Umsetzungsstand, Konzern-Rueckrufstrategie bei sicherheitsrelevanten Maengeln, Belegmatrix. Liefert priorisierten Ou... |
| `software-quellenkarte` | Software Quellenkarte: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
