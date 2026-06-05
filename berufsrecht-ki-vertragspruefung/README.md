# berufsrecht-ki-vertragspruefung

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`berufsrecht-ki-vertragspruefung`) | [`berufsrecht-ki-vertragspruefung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/berufsrecht-ki-vertragspruefung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Berufsrecht / KI-Vertragsprüfung — Rügeverfahren RAK Köln und Haftungsklage Habernau** (`berufsrecht-ki-rugekomitee-anwaltskammer-koeln-mandant-richtl-dr-rotbruch`) | [Gesamt-PDF lesen](../testakten/berufsrecht-ki-rugekomitee-anwaltskammer-koeln-mandant-richtl-dr-rotbruch/gesamt-pdf/berufsrecht-ki-rugekomitee-anwaltskammer-koeln-mandant-richtl-dr-rotbruch_gesamt.pdf) | [`testakte-berufsrecht-ki-rugekomitee-anwaltskammer-koeln-mandant-richtl-dr-rotbruch.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-berufsrecht-ki-rugekomitee-anwaltskammer-koeln-mandant-richtl-dr-rotbruch.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

> Hinweis: Inhaltlich verantwortlich ist Klotzkette. Die rechtlichen Bezugspunkte sind auf bestmöglichem Stand recherchiert; gleichwohl ersetzt keine Skill dieses Plugins die Prüfung durch einen spezialisierten Rechtsanwalt.

## Worum es geht

Kanzleien, Steuerberatungen, Wirtschaftsprüfungsgesellschaften, Patentanwaltskanzleien und Notariate setzen zunehmend Legal-KI-Tools privater Anbieter ein (Recherche mit Sprachmodellen, Dokumentenanalyse, Vertragsgeneratoren, Chatbots). Sobald solche Tools mit Mandats- oder Beteiligtendaten gefüttert werden, betreten wir berufsrechtliches und strafrechtliches Terrain. Datenschutzrecht läuft daneben, ersetzt aber die Prüfung des Berufsgeheimnisses nicht.

Dieses Plugin liefert eine **berufsrechtliche und strafrechtliche Vorprüfung** des Anbietervertrags. Es ist keine vollwertige juristische Begutachtung. Es ist ein strukturierter Argumentationsapparat, mit dem die Kanzlei dem Anbieter sagen kann: "So, wie macht ihr das eigentlich? Wie gewährleistet ihr die Anforderungen aus § 43e BRAO Absatz 3? Wo ist eure ISO-27001-Zertifizierung? Wo steht 'no training' im Vertrag?".

## Maßstab

Maßgeblich sind zuerst die geltenden Normen: § 43e BRAO, § 43a Abs. 2 BRAO, § 2 BORA, § 203 StGB, die Parallelnormen der anderen Berufsgeheimnisträger, DSGVO und KI-Verordnung. Die berufsrechtliche KI-Debatte wird als Auslegungshilfe verarbeitet, aber nicht als Ersatz für Gesetz, Rechtsprechung, Kammerpraxis oder eine konkrete Vertragsprüfung behandelt.

Arbeitslinie: KI-Outsourcing kann berufsrechtlich möglich sein, wenn der Dienstleister bewusst einbezogen, sorgfältig ausgewählt, in Textform verpflichtet, technisch-organisatorisch kontrolliert und in der Nutzung auf den erforderlichen Zugriff beschränkt wird. Public- oder Consumer-Tools ohne solche Bindung bleiben für Mandatsgeheimnisse tabu, solange nicht anonymisiert oder abstrahiert gearbeitet wird. Zur strafrechtlichen Absicherung dient § 203 StGB als verbindendes Element für alle fünf Berufsgruppen.

## Berufsgruppen

| Beruf | Verschwiegenheit | Dienstleisterregelung | § 203 StGB |
|---|---|---|---|
| Rechtsanwalt | § 43a Abs. 2 BRAO | § 43e BRAO | Abs. 1 Nr. 3 |
| Steuerberater | § 57 Abs. 1 StBerG | § 62a StBerG | Abs. 1 Nr. 3 |
| Wirtschaftsprüfer | § 43 WPO | § 50a WPO (§ 59c bei BG) | Abs. 1 Nr. 3 |
| Patentanwalt | § 39a Abs. 2 PAO | § 39c PAO | Abs. 1 Nr. 3 |
| Notar | § 18 BNotO | § 26a BNotO | Abs. 1 Nr. 1 |

Die Dienstleisterregelungen sind nahezu wortgleich aufgebaut. Das Plugin abstrahiert die gemeinsame Prüfung und stellt pro Beruf eine Norm-Adapter-Tabelle bereit.

## Skills

| Skill | Zweck |
|---|---|
| `berufsrecht-ki-vertragspruefung-kaltstart-interview` | Beruf, Anbieter, Datenarten, Vertragstyp erfassen |
| `consumer-ki-vs-43e-dienstleister` | Public Tool, Enterprise Tool, Kanzleisoftware, §-43e-Dienstleister und Einzelmandats-Tool trennen |
| `erforderlichkeit-dokumentieren` | Erforderlichkeit der Offenlegung (Abs. 1) — unternehmerischer Beurteilungsspielraum nach DAV |
| `ki-erforderlichkeit-ex-ante-vermerk` | Kanzlei-Vermerk zur Erforderlichkeit, Datenminimierung, Zweckbindung und Freigabeentscheidung |
| `verschwiegenheitsklausel-pruefen` | Textform, jedermann, zeitlich unbegrenzt, alle Berufsgeheimnisse |
| `strafrechtliche-belehrung-pruefen` | Belehrung über §§ 203, 204 StGB; Anlage Normtext |
| `subunternehmer-regelung-pruefen` | Zustimmungsvorbehalt, Weiterverpflichtung in Textform |
| `strafprozessuale-regelung-pruefen` | §§ 53a, 97 StPO — Widerspruchsrecht des Dienstleisters, Beschlagnahmefreiheit |
| `avv-grenzpruefung-datenschutz` | Schnittstelle zu Art. 28 DS-GVO — explizit andere Prüfung |
| `tom-und-zertifizierungen-pruefen` | TOM nach Art. 32 DS-GVO, ISO 27001, BSI C5, "no training", Zero-Retention |
| `ki-no-training-modellverbesserung-telemetrie` | Training, Produktverbesserung, Logs, Supportzugriffe, Telemetrie und Retention prüfen |
| `cloud-act-und-drittstaat-pruefen` | Auslandsregelung Abs. 4; CLOUD Act; Professional Secrecy Addendum |
| `schatten-ki-governance-und-sanktionslogik` | Private Tools, Schatten-KI, Freigabeliste, Incident Response und Team-Schulung organisieren |
| `ai-act-rollen-kanzlei-provider-deployer-api` | KI-VO-Rollen der Kanzlei als Betreiberin, Anbieterin oder API-Orchestratorin prüfen |
| `art-50-ki-vo-schriftsatz-marketing-chatbot` | Transparenzpflichten bei Mandantenchatbot, Website, Marketing, Legal Update und Schriftsatz abgrenzen |
| `rechtspolitische-unsicherheit-43e-brao-dokumentieren` | offene Auslegungsfragen, Reformmonitor und vertretbare Safe-Harbor-Argumente dokumentieren |
| `parallelnormen-andere-berufe` | Norm-Adapter pro Beruf — Mapping-Referenz |
| `gutachten-erstellen` | Zusammenfassendes Vorprüfungs-Gutachten |
| `rueckfragebrief-an-anbieter` | Strukturierter Brief mit präzisen Anbieterfragen |
| `klauselvorschlaege` | Mustertexte für nachverhandelbare Klauseln |

## Outputs

- **Vorprüfungs-Gutachten** mit Ampelbewertung (grün/gelb/rot) je Prüfpunkt
- **Rückfragebrief an den Anbieter** zur Klärung offener Versprechen
- **Klauselvorschläge** als Verhandlungsmaterial (Verschwiegenheit, "no training", Subunternehmerliste, EU/EWR-Beschränkung, Professional Secrecy Addendum)
- **Zertifizierungs- und Sicherheits-Checkliste** (ISO 27001, BSI C5, TOM Art. 32)
- **KI-Governance-Vermerk** für Toolfreigabe, Schatten-KI, Art.-4-KI-Kompetenz, Art.-50-Transparenz und anwaltliche Endkontrolle

## Wichtiger Hinweis (mehrfach)

**Diese Vorprüfung ist ausdrücklich keine Rechtsberatung.** Sie ist eine strukturierte Argumentationshilfe für das Anbietergespräch. Die berufsrechtliche und strafrechtliche Beurteilung des konkreten Einzelfalls bleibt der nutzenden Kanzlei (interne Compliance) bzw. einer beauftragten Spezialkanzlei vorbehalten.

## Quellenpolitik

- Gesetze zuerst: § 43e BRAO, § 43a Abs. 2 BRAO, § 2 BORA, § 203 StGB, Parallelnormen der anderen Berufsgeheimnisträger, DSGVO, KI-Verordnung
- BT-Drs. 18/12940 für die Genese der Dienstleisterregelungen
- Berufsrechtliche KI-Stellungnahmen, Kammerhinweise und Fachdebatte nur als Auslegungshilfe, nicht als verbindlicher Ersatzmaßstab
- BGH-Pinpoint mit Aktenzeichen und Randnummer
- Quellenregel: Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff; keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 79 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `ai-act-rollen-kanzlei-provider-deployer-api` | KI-VO-Rollen der Kanzlei prüfen: Betreiber/Deployer, Anbieter/Provider, eigener API-Wrapper, White-Label-Tool, GPAI-Abgrenzung, Art. 3, Art. 4, Art. 6, Art. 50 KI-VO und Schnittstelle zu § 43e BRAO. |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Berufsrecht KI Vertragspruefung-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Spezial-Skills aus diesem Plugin vor und führt in einen klaren... |
| `allgemein-brki-rollout-workflow-chronologie` | Nutze dies, wenn Allgemein, Brki Rollout Trainings Workflow, Workflow Chronologie Und Belegmatrix im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Brki Rollout Trainings Workflow, Workf... |
| `anbietern` | Nutze dies, wenn Anbietern: Schriftsatz-, Brief- und Memo-Bausteine im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Anbietern: Schriftsatz-, Brief- und Memo-Bausteine prüfen.; Erstelle eine Arbei... |
| `anbietern-belehrung-sonderfall-edge` | Nutze dies, wenn Spezial Anbietern Schriftsatz Brief Und Memo Bausteine, Spezial Belehrung Abschlussprodukt Und Übergabe, Spezial Berufsrecht Sonderfall Und Edge Case im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden so... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Berufsrecht Ki Vertragspruefung.; Welche Unterlagen brauchen Sie?; Welcher Spezial... |
| `art-50-ki-vo-schriftsatz-marketing-chatbot` | Art. 50 KI-VO in Kanzleien prüfen: Mandantenchatbot, Website, Legal Update, Newsletter, Marketingbild, Schriftsatzentwurf, menschliche redaktionelle Kontrolle, Kennzeichnung, Zeitplan 02.08.2026 und Berufsrecht. |
| `avv-grenzpruefung-brki-anbieter-brki-eu` | Nutze dies, wenn Avv Grenzpruefung Datenschutz, Brki Anbieter Due Diligence, Brki Eu Us Dpf Transferpruefung im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Avv Grenzpruefung Datenschutz, Brki An... |
| `avv-grenzpruefung-datenschutz` | Kanzlei nutzt KI-Dienstleister und prüft ob AVV nach Art. 28 DSGVO die berufsrechtliche Prüfung ersetzt. Berufsrecht laeuft parallel und ist strenger als Datenschutzrecht. Normen Art. 28 DSGVO §§ 43e BRAO 62a StBerG. Prüfraster AVV-Prüfp... |
| `belehrung` | Nutze dies, wenn Belehrung: Abschlussprodukt und Übergabe im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Belehrung: Abschlussprodukt und Übergabe prüfen.; Erstelle eine Arbeitsfassung zu Belehru... |
| `berufsrecht-ki-vertragspruefung-interview` | Erfasse Beruf des Auftraggebers (Rechtsanwalt Steuerberater Wirtschaftsprüfer Patentanwalt Notar) Anbieter Produktname Vertragsdokument Datenarten Verarbeitungszweck Hostingland und Subunternehmerstruktur. Bilde daraus den Norm-Adapter (... |
| `berufsrecht-sonderfall-edge-case` | Nutze dies, wenn Berufsrecht: Sonderfall und Edge-Case-Prüfung im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Berufsrecht: Sonderfall und Edge-Case-Prüfung prüfen.; Erstelle eine Arbeitsfassung... |
| `berufsrechtliche` | Nutze dies, wenn Berufsrechtliche: Erstprüfung, Rollenklärung und Mandatsziel im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Berufsrechtliche: Erstprüfung, Rollenklärung und Mandatsziel prüfen.;... |
| `berufsrechtliche-bnoto-interessen-brao` | Nutze dies, wenn Spezial Berufsrechtliche Erstpruefung Und Mandatsziel, Spezial Bnoto Mehrparteien Konflikt Und Interessen, Spezial Brao Zahlen Schwellen Und Berechnung im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden... |
| `bnoto-interessen` | Nutze dies, wenn Bnoto: Mehrparteienkonflikt und Interessenmatrix im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Bnoto: Mehrparteienkonflikt und Interessenmatrix prüfen.; Erstelle eine Arbeitsfa... |
| `brao` | Nutze dies, wenn Brao: Zahlen, Schwellenwerte und Berechnung im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Brao: Zahlen, Schwellenwerte und Berechnung prüfen.; Erstelle eine Arbeitsfassung zu B... |
| `brki-anbieter-due-diligence` | Anbieter-Due-Diligence beim Einsatz von KI in der Kanzlei: Sitz, Rechtsform, Zertifizierungen (ISO 27001, SOC 2 Typ II), Datenhaltung, Subunternehmer, Auditierbarkeit, Datenschutz-Folgenabschaetzung. Strukturierte Bewertung mit Score je... |
| `brki-eu-us-dpf-transferpruefung` | Spezialfall Transfer nach USA unter EU-US-Data-Privacy-Framework DPF: Liste teilnehmender Unternehmen, Pruefraster fuer Wirksamkeit (Selbstzertifizierung, Annual-Recertification), Backup-Plan SCC Modul 2 plus TIA bei Verlust DPF. |
| `brki-rag-bro-grundlagen-cloud-act` | Nutze dies, wenn Brki Rag Vertraulichkeit Spezial, Bro Grundlagen Ki Einsatz, Cloud Act Und Drittstaat Prüfen im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Brki Rag Vertraulichkeit Spezial, Bro... |
| `brki-rag-vertraulichkeit-spezial` | Spezialfall RAG-Architekturen mit Mandantenakten: Embedding-Speicher, Vektor-DB im EU-Hosting, Loeschkonzept Embedding bei Mandantenwiderruf, Trennung pro Mandat. Pruefraster und technische Mindestanforderungen. |
| `brki-rollout-trainings-workflow` | Workflow fuer KI-Rollout in der Kanzlei: Pilotgruppe, Trainings (Halbtages-Workshop), Approval-Prozess fuer eingesetzte Tools, Reviewer-Liste, Dokumentation, KPIs. Routet in berufsrecht-ki-vertragspruefung-kaltstart-interview. |
| `bro-grundlagen-ki-einsatz` | BRAO-Grundlagen fuer KI-Einsatz in der Kanzlei einfuehrend: § 43a BRAO Verschwiegenheit, § 43e BRAO IT-Dienste, § 203 StGB Strafbarkeit Geheimnisverletzung, Datenschutz nach DSGVO und BDSG. Strukturierte Uebersicht zur Pflichtenkette bei... |
| `chronologie-und-belegmatrix` | Nutze dies, wenn Chronologie und Belegmatrix im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Chronologie und Belegmatrix prüfen.; Erstelle eine Arbeitsfassung zu Chronologie und Belegmatrix.; Wel... |
| `cloud-act-und-drittstaat-pruefen` | Prüfe Auslandsbezug des KI-Anbieters nach Absatz vier der einschlaegigen Dienstleisterregelung (BRAO StBerG WPO PAO BNotO). EU/EWR sind regelmäßig leichter vertretbar; Drittstaaten benötigen eine eigene Berufsgeheimnisprüfung. US-CLOUD A... |
| `consumer-ki-datentransfer-eu-erforderlichkeit` | Nutze dies, wenn Consumer Ki Vs 43E Dienstleister, Datentransfer Eu Drittstaat, Erforderlichkeit Dokumentieren im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?... |
| `consumer-ki-vs-43e-dienstleister` | Consumer-KI, Enterprise-KI, Kanzleisoftware und §-43e-Dienstleister trennen: prüft Mandatsdaten, Vertragsbindung, Toolzweck, Subunternehmer, Anonymisierungspflicht, Mandanteninformation und Freigabeentscheidung. |
| `datentransfer-eu-drittstaat` | Datentransfer EU nach Drittstaat: Angemessenheitsbeschluss EU-US-Data-Privacy-Framework, Standardvertragsklauseln Modul 2, Transfer Impact Assessment nach EuGH Schrems II. Pruefraster fuer US-KI-Anbieter, technische Massnahmen wie Tokeni... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Berufsrecht Ki Vertragspruefung.; Welche Unterlagen brauchen Sie?; Welcher Spez... |
| `erforderlichkeit-dokumentieren` | Prüfe die Erforderlichkeit der Offenlegung von Berufsgeheimnissen gegenüber dem KI-Dienstleister nach Absatz eins der einschlaegigen Dienstleisterregelung (BRAO StBerG WPO PAO BNotO). Bezugspunkt ist der Zweck der konkreten Offenlegung,... |
| `forensische-prompt-gutachten-erstellen` | Nutze dies, wenn Forensische Prüfung Prompt Injection, Gutachten Erstellen, Kanzleisoftware Spezial Mandantendaten im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Forensische Prüfung Prompt Injec... |
| `forensische-pruefung-prompt-injection` | Forensische Pruefung Prompt-Injection-Risiko: Indirekte Prompt-Injection ueber hochgeladene Dokumente, RAG-Vergiftung, Datenexfiltration. Pruefraster fuer Reviewer-Audit, Sandbox-Test, Sicherheits-Hardening durch Anbieter. Pflicht des An... |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies, wenn Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation, Workflow Redteam Qualitygate im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-te... |
| `fristen-und-risikoampel` | Nutze dies, wenn Fristen- und Risikoampel im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Fristen- und Risikoampel prüfen.; Erstelle eine Arbeitsfassung zu Fristen- und Risikoampel.; Welche Norme... |
| `fristennotiz-naechster-vorpruefung` | Nutze dies, wenn Spezial Vertragspruefung Fristennotiz Und Naechster Schritt, Spezial Vorpruefung Fristen Form Und Zustaendigkeit, Klauselvorschlaege im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bit... |
| `gutachten-erstellen` | Erstelle das zusammenfassende Vorprüfungs-Gutachten zum KI-Anbietervertrag. Aufbau Eingangsdaten Norm-Adapter Prüfpunkte Erforderlichkeit Verschwiegenheit Belehrung Subunternehmer Strafprozess TOM Drittstaat Ampelbewertung Lückenliste Ha... |
| `gutachten-fehlerkatalog` | Nutze dies, wenn Gutachten Fehlerkatalog im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `gutachten-red-legal-patentanwaelte` | Nutze dies, wenn Spezial Gutachten Red Team Und Qualitaetskontrolle, Spezial Legal Behörden Gericht Und Registerweg, Spezial Patentanwaelte Verhandlung Vergleich Und Eskalation im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet... |
| `kanzleisoftware-spezial-mandantendaten` | Spezialfall Kanzleisoftware mit KI-Funktionen (RA-MICRO, Datev DMS, Acta Nova, vRA): Mandantendaten in Cloud, KI-Funktion Volltextsuche, Diktat, Vertragsanalyse. Pruefraster fuer Einwilligung Mandant, Auftragsverarbeitung, Loeschkonzepte. |
| `ki-erforderlichkeit-ex-ante-vermerk` | Ex-ante-Vermerk zur Erforderlichkeit nach § 43e BRAO für KI-Outsourcing: Zweck der Offenlegung, Datenminimierung, Alternativen, Mandatsklassen, Kanzleiinfrastruktur, Einzelmandat, No-Training und Freigabebegründung dokumentieren. |
| `ki-erforderlichkeit-no-training-mandanten` | Nutze dies, wenn Ki Erforderlichkeit Ex Ante Vermerk, Ki No Training Modellverbesserung Telemetrie, Mandanten Aufklaerungspflicht Ki im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Ki Erforderlic... |
| `ki-no-training-modellverbesserung-telemetrie` | No-Training, Modellverbesserung und Telemetrie im KI-Vertrag prüfen: Mandatsdaten dürfen nicht für Training, Produktverbesserung, Benchmarks, Supportauswertung oder allgemeine Modelloptimierung abfließen; Klausel- und Rückfragebausteine. |
| `klauseln-beweislast-darlegungslast` | Nutze dies, wenn Klauseln: Beweislast, Darlegungslast und Substantiierung im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Klauseln: Beweislast, Darlegungslast und Substantiierung prüfen.; Erstell... |
| `klauseln-beweislast-verschwiegenheitsklausel` | Nutze dies, wenn Spezial Klauseln Beweislast Und Darlegungslast, Verschwiegenheitsklausel Prüfen, Schatten Ki Governance Und Sanktionslogik im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Spezial... |
| `klauselvorschlaege` | Liefere konkrete Mustertexte für Vertragsklauseln mit dem KI-Anbieter. Bausteine Verschwiegenheit Belehrung §§ 203 204 StGB Subunternehmer no training Zero-Retention EU-Hosting Audit-Recht Löschkonzept Professional Secrecy Addendum für U... |
| `legal` | Nutze dies, wenn Legal: Behörden-, Gerichts- oder Registerweg im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Legal: Behörden-, Gerichts- oder Registerweg prüfen.; Erstelle eine Arbeitsfassung zu... |
| `mandanten-aufklaerungspflicht-ki` | Aufklaerungspflicht gegenueber Mandanten beim KI-Einsatz: § 43 BRAO Vertrauensverhaeltnis, § 13 BORA, BGH-Rechtsprechung zur Informationsweitergabe. Mustertexte Mandantenanschreiben und Mandatsvertrag. Pruefraster fuer notwendigen Inform... |
| `mandantenkommunikation` | Nutze dies, wenn Mandantenkommunikation im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Mandantenkommunikation prüfen.; Erstelle eine Arbeitsfassung zu Mandantenkommunikation.; Welche Normen und... |
| `notare-quellenkarte` | Nutze dies, wenn Notare Quellenkarte im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `parallelnormen-andere-ai-act-art-vo` | Nutze dies, wenn Parallelnormen Andere Berufe, Ai Act Rollen Kanzlei Provider Deployer Api, Art 50 Ki Vo Schriftsatz Marketing Chatbot im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Parallelnorm... |
| `parallelnormen-andere-berufe` | Norm-Adapter-Referenz für alle fuenf Berufsgeheimnistraeger Rechtsanwalt Steuerberater Wirtschaftsprüfer Patentanwalt Notar. Mapping der Dienstleisterregelungen Verschwiegenheitspflichten und § 203 StGB-Tatbestaende. Sonderregeln für Ber... |
| `patentanwaelte` | Nutze dies, wenn Patentanwälte: Verhandlung, Vergleich und Eskalation im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Patentanwälte: Verhandlung, Vergleich und Eskalation prüfen.; Erstelle eine A... |
| `privaten` | Nutze dies, wenn Privaten: Risikoampel, Gegenargumente und Verteidigungslinien im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Privaten: Risikoampel, Gegenargumente und Verteidigungslinien prüfen... |
| `privaten-rueckfragebrief` | Nutze dies, wenn Spezial Privaten Risikoampel Und Gegenargumente, Spezial Rueckfragebrief Mandantenentscheidung, Spezial Stberg Compliance Dokumentation Und Akte im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. A... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `rechtspolitische-unsicherheit-43e-brao` | Rechtsunsicherheit bei § 43e BRAO und KI-Outsourcing dokumentieren: abweichende Kammer-/Verbandspositionen, fehlende höchstrichterliche KI-Rechtsprechung, Reformmonitor, Safe-Harbor-Argumente und Mandatsrisiko transparent machen. |
| `rechtspolitische-unsicherheit-rueckfragebrief` | Nutze dies, wenn Rechtspolitische Unsicherheit 43E Brao Dokumentieren, Rueckfragebrief An Anbieter, Schwarmpruefung Mehrere Tools im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Rechtspolitische... |
| `redteam-qualitygate` | Nutze dies, wenn Red-Team Qualitygate im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `rueckfragebrief-an-anbieter` | Erstelle einen strukturierten Rückfragebrief an den KI-Anbieter zur Klaerung der berufsrechtlichen und strafrechtlichen Pflichten. Aufbau Anschreiben Kontext drei Fragenbloecke (Verschwiegenheit Subunternehmer TOM und Drittstaat) Fragen... |
| `rueckfragebrief-mandantenentscheidung` | Nutze dies, wenn Rueckfragebrief: Mandantenkommunikation und Entscheidungsvorlage im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Rueckfragebrief: Mandantenkommunikation und Entscheidungsvorlage... |
| `schatten-ki-governance-und-sanktionslogik` | Schatten-KI-Governance für Kanzleien: private Tools, Teamdisziplin, Freigabelisten, Verbote, Schulung nach Art. 4 KI-VO, Incident Response, arbeitsrechtliche Sanktionen und berufsrechtliche Organisationspflicht verbinden. |
| `schwarmpruefung-mehrere-tools` | Mehrere KI-Tools im parallelen Einsatz pruefen: ein Vertrag pro Anbieter, datentechnische Verkettung, Aggregationsrisiko, Gesamt-DPIA. Pruefraster fuer Mandant der gleichzeitig ChatGPT Enterprise, MS 365 Copilot, Claude Enterprise einsetzt. |
| `stberg` | Nutze dies, wenn Stberg: Compliance-Dokumentation und Aktenvermerk im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `stellungnahme` | Nutze dies, wenn Stellungnahme: Formular, Portal und Einreichungslogik im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Stellungnahme: Formular, Portal und Einreichungslogik prüfen.; Erstelle eine... |
| `stellungnahme-stgb-strafrechtliche` | Nutze dies, wenn Spezial Stellungnahme Formular Portal Und Einreichung, Spezial Stgb Internationaler Bezug Und Schnittstellen, Spezial Strafrechtliche Tatbestand Beweis Und Belege im Plugin Berufsrecht Ki Vertragspruefung konkret bearbei... |
| `stgb` | Nutze dies, wenn Stgb: Internationaler Bezug und Schnittstellen im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Stgb: Internationaler Bezug und Schnittstellen prüfen.; Erstelle eine Arbeitsfassun... |
| `strafprozessuale-regelung-pruefen` | Prüfe die strafprozessuale Absicherung des KI-Dienstleisters nach §§ 53a 97 StPO. Zeugnisverweigerungsrecht der mitwirkenden Personen Beschlagnahmeverbot für Mandatsdaten Widerspruchspflicht des Dienstleisters bei behoerdlichen Auskunfts... |
| `strafrechtliche` | Nutze dies, wenn Strafrechtliche: Tatbestandsmerkmale, Beweisfragen und Beleglage im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Strafrechtliche: Tatbestandsmerkmale, Beweisfragen und Beleglage... |
| `strafrechtliche-belehrung-pruefen` | Prüfe die strafrechtliche Belehrung des Dienstleisters nach Absatz drei Satz zwei Nummer eins der einschlaegigen Dienstleisterregelung. Pflichtinhalte § 203 Absatz eins drei vier und sechs StGB und § 204 StGB. Empfehlung Normtext als Ver... |
| `subunternehmer-regelung-pruefen` | Prüfe die Subunternehmerklausel im KI-Anbietervertrag. Norm Absatz drei Satz zwei Nummer drei der einschlaegigen Dienstleisterregelung. Pflichtinhalte Zustimmungsvorbehalt der Kanzlei Subunternehmerliste Weiterverpflichtung in Textform B... |
| `subunternehmer-regelung-tom-zertifizierungen` | Nutze dies, wenn Subunternehmer Regelung Prüfen, Tom Und Zertifizierungen Prüfen im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Subunternehmer Regelung Prüfen, Tom Und Zertifizierungen Prüfen pr... |
| `tom-und-zertifizierungen-pruefen` | Prüfe technische und organisatorische Massnahmen des KI-Anbieters und seine Zertifizierungen. Maßstab Art. 32 DS-GVO ISO 27001 BSI C5 (Cloud Computing Compliance Criteria Catalogue) SOC zwei Typ zwei TISAX. Zentral für Berufsrecht no tra... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `verschwiegenheitsklausel-pruefen` | Prüfe die vertragliche Verpflichtung des Dienstleisters auf Verschwiegenheit nach Absatz drei der einschlaegigen Dienstleisterregelung (§§ 43e BRAO 62a StBerG 50a WPO 39c PAO 26a BNotO). Anforderungen Textform (§ 126b BGB) Verpflichtung... |
| `vertraegen` | Nutze dies, wenn Verträgen: Dokumentenmatrix, Lückenliste und Nachforderung im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `vertraegen-strafprozessuale-regelung` | Nutze dies, wenn Spezial Vertraegen Dokumentenmatrix Und Lueckenliste, Strafprozessuale Regelung Prüfen, Strafrechtliche Belehrung Prüfen im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Spezial V... |
| `vertragspruefung-fristennotiz-naechster` | Nutze dies, wenn Vertragspruefung: Fristennotiz und nächster Schritt im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Vertragspruefung: Fristennotiz und nächster Schritt prüfen.; Erstelle eine Arb... |
| `vorpruefung` | Nutze dies, wenn Vorpruefung: Fristen, Form, Zuständigkeit und Rechtsweg im Plugin Berufsrecht Ki Vertragspruefung konkret bearbeitet werden soll. Auslöser: Bitte Vorpruefung: Fristen, Form, Zuständigkeit und Rechtsweg prüfen.; Erstelle... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
