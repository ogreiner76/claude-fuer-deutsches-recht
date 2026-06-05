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
| `allgemein` | Einstieg, Schnelltriage und Fallrouting im Berufsrecht KI Vertragspruefung-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Fachmodule aus diesem Plugin vor und führt in einen klaren Arbeitsp... |
| `allgemein-brki-rollout-workflow-chronologie` | Nutze dies bei Allgemein, Brki Rollout Trainings Workflow, Chronologie Und Belegmatrix, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anbietern` | Nutze dies bei Anbietern: Schriftsatz-, Brief- und Memo-Bausteine: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `anbietern-belehrung-sonderfall-edge` | Nutze dies bei Anbietern Schriftsatz Brief Und Memo Bausteine, Belehrung Abschlussprodukt Und Uebergabe, Berufsrecht Sonderfall Und Edge Case: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nä... |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `art-50-ki-vo-schriftsatz-marketing-chatbot` | Art. 50 KI-VO in Kanzleien prüfen: Mandantenchatbot, Website, Legal Update, Newsletter, Marketingbild, Schriftsatzentwurf, menschliche redaktionelle Kontrolle, Kennzeichnung, Zeitplan 02.08.2026 und Berufsrecht. |
| `avv-grenzpruefung-brki-anbieter-brki-eu` | Nutze dies bei Avv Grenzpruefung Datenschutz, Brki Anbieter Due Diligence, Brki Eu Us Dpf Transferpruefung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `avv-grenzpruefung-datenschutz` | Kanzlei nutzt KI-Dienstleister und prüft ob AVV nach Art. 28 DSGVO die berufsrechtliche Prüfung ersetzt. Berufsrecht laeuft parallel und ist strenger als Datenschutzrecht. Normen Art. 28 DSGVO §§ 43e BRAO 62a StBerG. Prüfraster AVV-Prüfp... |
| `belehrung` | Nutze dies bei Belehrung: Abschlussprodukt und Übergabe: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `berufsrecht-ki-vertragspruefung-interview` | Erfasse Beruf des Auftraggebers (Rechtsanwalt Steuerberater Wirtschaftsprüfer Patentanwalt Notar) Anbieter Produktname Vertragsdokument Datenarten Verarbeitungszweck Hostingland und Subunternehmerstruktur. Bilde daraus den Norm-Adapter (... |
| `berufsrecht-sonderfall-edge-case` | Nutze dies bei Berufsrecht: Sonderfall und Edge-Case-Prüfung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `berufsrechtliche` | Nutze dies bei Berufsrechtliche: Erstprüfung, Rollenklärung und Mandatsziel: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `berufsrechtliche-bnoto-interessen-brao` | Nutze dies bei Berufsrechtliche Erstpruefung Und Mandatsziel, Bnoto Mehrparteien Konflikt Und Interessen, Brao Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den n... |
| `bnoto-interessen` | Nutze dies bei Bnoto: Mehrparteienkonflikt und Interessenmatrix: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `brao` | Nutze dies bei Brao: Zahlen, Schwellenwerte und Berechnung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `brki-anbieter-due-diligence` | Anbieter-Due-Diligence beim Einsatz von KI in der Kanzlei: Sitz, Rechtsform, Zertifizierungen (ISO 27001, SOC 2 Typ II), Datenhaltung, Subunternehmer, Auditierbarkeit, Datenschutz-Folgenabschaetzung. Strukturierte Bewertung mit Score je... |
| `brki-eu-us-dpf-transferpruefung` | Spezialfall Transfer nach USA unter EU-US-Data-Privacy-Framework DPF: Liste teilnehmender Unternehmen, Pruefraster fuer Wirksamkeit (Selbstzertifizierung, Annual-Recertification), Backup-Plan SCC Modul 2 plus TIA bei Verlust DPF. |
| `brki-rag-bro-grundlagen-cloud-act` | Nutze dies bei Brki Rag Vertraulichkeit Spezial, Bro Grundlagen Ki Einsatz, Cloud Act Und Drittstaat Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `brki-rag-vertraulichkeit-spezial` | Spezialfall RAG-Architekturen mit Mandantenakten: Embedding-Speicher, Vektor-DB im EU-Hosting, Loeschkonzept Embedding bei Mandantenwiderruf, Trennung pro Mandat. Pruefraster und technische Mindestanforderungen. |
| `brki-rollout-trainings-workflow` | Nutze dies bei BRKI: Rollout-Trainings: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `bro-grundlagen-ki-einsatz` | BRAO-Grundlagen fuer KI-Einsatz in der Kanzlei einfuehrend: § 43a BRAO Verschwiegenheit, § 43e BRAO IT-Dienste, § 203 StGB Strafbarkeit Geheimnisverletzung, Datenschutz nach DSGVO und BDSG. Strukturierte Uebersicht zur Pflichtenkette bei... |
| `chronologie-und-belegmatrix` | Nutze dies bei Chronologie und Belegmatrix: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `cloud-act-und-drittstaat-pruefen` | Prüfe Auslandsbezug des KI-Anbieters nach Absatz vier der einschlaegigen Dienstleisterregelung (BRAO StBerG WPO PAO BNotO). EU/EWR sind regelmäßig leichter vertretbar; Drittstaaten benötigen eine eigene Berufsgeheimnisprüfung. US-CLOUD A... |
| `consumer-ki-datentransfer-eu-erforderlichkeit` | Nutze dies bei Consumer Ki Vs 43e Dienstleister, Datentransfer Eu Drittstaat, Erforderlichkeit Dokumentieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `consumer-ki-vs-43e-dienstleister` | Consumer-KI, Enterprise-KI, Kanzleisoftware und §-43e-Dienstleister trennen: prüft Mandatsdaten, Vertragsbindung, Toolzweck, Subunternehmer, Anonymisierungspflicht, Mandanteninformation und Freigabeentscheidung. |
| `datentransfer-eu-drittstaat` | Datentransfer EU nach Drittstaat: Angemessenheitsbeschluss EU-US-Data-Privacy-Framework, Standardvertragsklauseln Modul 2, Transfer Impact Assessment nach EuGH Schrems II. Pruefraster fuer US-KI-Anbieter, technische Massnahmen wie Tokeni... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `erforderlichkeit-dokumentieren` | Prüfe die Erforderlichkeit der Offenlegung von Berufsgeheimnissen gegenüber dem KI-Dienstleister nach Absatz eins der einschlaegigen Dienstleisterregelung (BRAO StBerG WPO PAO BNotO). Bezugspunkt ist der Zweck der konkreten Offenlegung,... |
| `forensische-prompt-gutachten-erstellen` | Nutze dies bei Forensische Prüfung Prompt Injection, Gutachten Erstellen, Kanzleisoftware Mandantendaten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `forensische-pruefung-prompt-injection` | Forensische Pruefung Prompt-Injection-Risiko: Indirekte Prompt-Injection ueber hochgeladene Dokumente, RAG-Vergiftung, Datenexfiltration. Pruefraster fuer Reviewer-Audit, Sandbox-Test, Sicherheits-Hardening durch Anbieter. Pflicht des An... |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies bei Fristen Und Risikoampel, Mandantenkommunikation, Redteam Qualitygate: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `fristen-und-risikoampel` | Nutze dies bei Fristen- und Risikoampel: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `fristennotiz-naechster-vorpruefung` | Nutze dies bei Vertragspruefung Fristennotiz Und Naechster Schritt, Vorpruefung Fristen Form Und Zustaendigkeit, Klauselvorschlaege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bel... |
| `gutachten-erstellen` | Erstelle das zusammenfassende Vorprüfungs-Gutachten zum KI-Anbietervertrag. Aufbau Eingangsdaten Norm-Adapter Prüfpunkte Erforderlichkeit Verschwiegenheit Belehrung Subunternehmer Strafprozess TOM Drittstaat Ampelbewertung Lückenliste Ha... |
| `gutachten-fehlerkatalog` | Nutze dies als Fehlerbremse bei Gutachten Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `gutachten-red-legal-patentanwaelte` | Nutze dies bei Gutachten Red Team Und Qualitaetskontrolle, Legal Behörden Gericht Und Registerweg, Patentanwaelte Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefe... |
| `kanzleisoftware-spezial-mandantendaten` | Spezialfall Kanzleisoftware mit KI-Funktionen (RA-MICRO, Datev DMS, Acta Nova, vRA): Mandantendaten in Cloud, KI-Funktion Volltextsuche, Diktat, Vertragsanalyse. Pruefraster fuer Einwilligung Mandant, Auftragsverarbeitung, Loeschkonzepte. |
| `ki-erforderlichkeit-ex-ante-vermerk` | Ex-ante-Vermerk zur Erforderlichkeit nach § 43e BRAO für KI-Outsourcing: Zweck der Offenlegung, Datenminimierung, Alternativen, Mandatsklassen, Kanzleiinfrastruktur, Einzelmandat, No-Training und Freigabebegründung dokumentieren. |
| `ki-erforderlichkeit-no-training-mandanten` | Nutze dies bei Ki Erforderlichkeit Ex Ante Vermerk, Ki No Training Modellverbesserung Telemetrie, Mandanten Aufklaerungspflicht Ki: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `ki-no-training-modellverbesserung-telemetrie` | No-Training, Modellverbesserung und Telemetrie im KI-Vertrag prüfen: Mandatsdaten dürfen nicht für Training, Produktverbesserung, Benchmarks, Supportauswertung oder allgemeine Modelloptimierung abfließen; Klausel- und Rückfragebausteine. |
| `klauseln-beweislast-darlegungslast` | Nutze dies bei Klauseln: Beweislast, Darlegungslast und Substantiierung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `klauseln-beweislast-verschwiegenheitsklausel` | Nutze dies bei Klauseln Beweislast Und Darlegungslast, Verschwiegenheitsklausel Prüfen, Schatten Ki Governance Und Sanktionslogik: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belas... |
| `klauselvorschlaege` | Liefere konkrete Mustertexte für Vertragsklauseln mit dem KI-Anbieter. Bausteine Verschwiegenheit Belehrung §§ 203 204 StGB Subunternehmer no training Zero-Retention EU-Hosting Audit-Recht Löschkonzept Professional Secrecy Addendum für U... |
| `legal` | Nutze dies bei Legal: Behörden-, Gerichts- oder Registerweg: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `mandanten-aufklaerungspflicht-ki` | Aufklaerungspflicht gegenueber Mandanten beim KI-Einsatz: § 43 BRAO Vertrauensverhaeltnis, § 13 BORA, BGH-Rechtsprechung zur Informationsweitergabe. Mustertexte Mandantenanschreiben und Mandatsvertrag. Pruefraster fuer notwendigen Inform... |
| `mandantenkommunikation` | Nutze dies bei Mandantenkommunikation: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `notare-quellenkarte` | Nutze dies zur Quellenprüfung bei Notare Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `parallelnormen-andere-ai-act-art-vo` | Nutze dies bei Parallelnormen Andere Berufe, Ai Act Rollen Kanzlei Provider Deployer Api, Art 50 Ki Vo Schriftsatz Marketing Chatbot: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten be... |
| `parallelnormen-andere-berufe` | Norm-Adapter-Referenz für alle fuenf Berufsgeheimnistraeger Rechtsanwalt Steuerberater Wirtschaftsprüfer Patentanwalt Notar. Mapping der Dienstleisterregelungen Verschwiegenheitspflichten und § 203 StGB-Tatbestaende. Sonderregeln für Ber... |
| `patentanwaelte` | Nutze dies bei Patentanwälte: Verhandlung, Vergleich und Eskalation: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `privaten` | Nutze dies bei Privaten: Risikoampel, Gegenargumente und Verteidigungslinien: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `privaten-rueckfragebrief` | Nutze dies bei Privaten Risikoampel Und Gegenargumente, Rueckfragebrief Mandantenentscheidung, Stberg Compliance Dokumentation Und Akte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `rechtspolitische-unsicherheit-43e-brao` | Rechtsunsicherheit bei § 43e BRAO und KI-Outsourcing dokumentieren: abweichende Kammer-/Verbandspositionen, fehlende höchstrichterliche KI-Rechtsprechung, Reformmonitor, Safe-Harbor-Argumente und Mandatsrisiko transparent machen. |
| `rechtspolitische-unsicherheit-rueckfragebrief` | Nutze dies bei Rechtspolitische Unsicherheit 43e Brao Dokumentieren, Rueckfragebrief An Anbieter, Schwarmpruefung Mehrere Tools: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastb... |
| `redteam-qualitygate` | Nutze dies als Fehlerbremse bei Red-Team Qualitygate: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `rueckfragebrief-an-anbieter` | Erstelle einen strukturierten Rückfragebrief an den KI-Anbieter zur Klaerung der berufsrechtlichen und strafrechtlichen Pflichten. Aufbau Anschreiben Kontext drei Fragenbloecke (Verschwiegenheit Subunternehmer TOM und Drittstaat) Fragen... |
| `rueckfragebrief-mandantenentscheidung` | Nutze dies bei Rueckfragebrief: Mandantenkommunikation und Entscheidungsvorlage: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `schatten-ki-governance-und-sanktionslogik` | Schatten-KI-Governance für Kanzleien: private Tools, Teamdisziplin, Freigabelisten, Verbote, Schulung nach Art. 4 KI-VO, Incident Response, arbeitsrechtliche Sanktionen und berufsrechtliche Organisationspflicht verbinden. |
| `schwarmpruefung-mehrere-tools` | Mehrere KI-Tools im parallelen Einsatz pruefen: ein Vertrag pro Anbieter, datentechnische Verkettung, Aggregationsrisiko, Gesamt-DPIA. Pruefraster fuer Mandant der gleichzeitig ChatGPT Enterprise, MS 365 Copilot, Claude Enterprise einsetzt. |
| `stberg` | Nutze dies bei Stberg: Compliance-Dokumentation und Aktenvermerk: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `stellungnahme` | Nutze dies bei Stellungnahme: Formular, Portal und Einreichungslogik: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `stellungnahme-stgb-strafrechtliche` | Nutze dies bei Stellungnahme Formular Portal Und Einreichung, Stgb Internationaler Bezug Und Schnittstellen, Strafrechtliche Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und li... |
| `stgb` | Nutze dies bei Stgb: Internationaler Bezug und Schnittstellen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `strafprozessuale-regelung-pruefen` | Prüfe die strafprozessuale Absicherung des KI-Dienstleisters nach §§ 53a 97 StPO. Zeugnisverweigerungsrecht der mitwirkenden Personen Beschlagnahmeverbot für Mandatsdaten Widerspruchspflicht des Dienstleisters bei behoerdlichen Auskunfts... |
| `strafrechtliche` | Nutze dies bei Strafrechtliche: Tatbestandsmerkmale, Beweisfragen und Beleglage: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `strafrechtliche-belehrung-pruefen` | Prüfe die strafrechtliche Belehrung des Dienstleisters nach Absatz drei Satz zwei Nummer eins der einschlaegigen Dienstleisterregelung. Pflichtinhalte § 203 Absatz eins drei vier und sechs StGB und § 204 StGB. Empfehlung Normtext als Ver... |
| `subunternehmer-regelung-pruefen` | Prüfe die Subunternehmerklausel im KI-Anbietervertrag. Norm Absatz drei Satz zwei Nummer drei der einschlaegigen Dienstleisterregelung. Pflichtinhalte Zustimmungsvorbehalt der Kanzlei Subunternehmerliste Weiterverpflichtung in Textform B... |
| `subunternehmer-regelung-tom-zertifizierungen` | Nutze dies bei Subunternehmer Regelung Prüfen, Tom Und Zertifizierungen Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `tom-und-zertifizierungen-pruefen` | Prüfe technische und organisatorische Massnahmen des KI-Anbieters und seine Zertifizierungen. Maßstab Art. 32 DS-GVO ISO 27001 BSI C5 (Cloud Computing Compliance Criteria Catalogue) SOC zwei Typ zwei TISAX. Zentral für Berufsrecht no tra... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `verschwiegenheitsklausel-pruefen` | Prüfe die vertragliche Verpflichtung des Dienstleisters auf Verschwiegenheit nach Absatz drei der einschlaegigen Dienstleisterregelung (§§ 43e BRAO 62a StBerG 50a WPO 39c PAO 26a BNotO). Anforderungen Textform (§ 126b BGB) Verpflichtung... |
| `vertraegen` | Nutze dies bei Verträgen: Dokumentenmatrix, Lückenliste und Nachforderung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `vertraegen-strafprozessuale-regelung` | Nutze dies bei Vertraegen Dokumentenmatrix Und Lueckenliste, Strafprozessuale Regelung Prüfen, Strafrechtliche Belehrung Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastb... |
| `vertragspruefung-fristennotiz-naechster` | Nutze dies bei Vertragspruefung: Fristennotiz und nächster Schritt: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `vorpruefung` | Nutze dies bei Vorpruefung: Fristen, Form, Zuständigkeit und Rechtsweg: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
