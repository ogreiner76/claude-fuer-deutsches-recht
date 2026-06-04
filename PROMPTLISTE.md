# Klotzkettes Juristische Promptliste

**Eine kuratierte Liste praxisnaher Mega-Prompts, sortiert nach Fachanwaltschaften.**

## Gigantischer Disclaimer — bitte zuerst lesen

**Alle Angaben ohne Gewaehr. Jede Nutzerin, jeder Nutzer setzt diese Promptliste auf eigenes Risiko ein.**

Dieses Repository und damit auch diese Promptliste ist und bleibt ein **Experiment**. Probiert die Prompts aus und schaut, ob sie euch bei der **haendischen Erstellung von juristischen Dokumenten und Workflows** unterstuetzen koennen — mehr ist hier ausdruecklich nicht versprochen.

- **Diese Prompts koennen kein Jura.** Sie sind strukturierte Anweisungen an Sprachmodelle. Sprachmodelle koennen kein Jura. Es gibt keinerlei Anspruch auf inhaltliche Richtigkeit, Vollstaendigkeit, Aktualitaet oder Anwendbarkeit auf den konkreten Fall.

- **Wenn Fehler entstehen, entstehen sie durch Fehlgebrauch oder durch eine danebenliegende KI** — nicht durch die hier abgelegten Vorlagen. Die Prompts sind reine Anregungen. Sie ersetzen keine anwaltliche Pruefung, keine eigene Recherche und keine eigene juristische Verantwortung.

- **Keine Rechtsberatung.** Diese Prompts liefern weder ein Rechtsgutachten noch eine Rechtsauskunft im Einzelfall. Wer auf Basis eines Prompt-Outputs einen Schriftsatz, eine Klausel oder einen Bescheid erstellt, traegt die **vollstaendige Verantwortung** fuer Inhalt, Korrektheit und Rechtsstand.

- **Mandatsgeheimnis, Berufsrecht, Datenschutz, KI-Governance** — §§ 203 und 204 StGB, § 43e BRAO, § 2 BORA, §§ 53 und 97 und 160a StPO, DSGVO und BDSG einschliesslich Drittlandtransfer, US-Cloud-Act und FISA, die KI-VO (VO EU 2024 zu 1689) und alle einschlaegigen berufsrechtlichen, datenschutzrechtlichen und regulatorischen Vorgaben muesst ihr **eigenstaendig** pruefen und einhalten. Diese Promptliste sagt dazu nichts.

- **Testbetrieb dringend empfohlen.** Setzt die Prompts zunaechst ohne echte Mandatsgeheimnisse, ohne identifizierbare Personendaten und ohne sensible Akten ein. Validiert jeden Output gegen Gesetzestext, amtliche Materialien und ueberpruefbare Rechtsprechung.

- **Veraltung.** Rechtsstaende altern. Was heute korrekt formuliert ist, kann morgen ueberholt sein. Pruefe immer die aktuelle Gesetzes- und Rechtsprechungslage.

- **Aenderung ausdruecklich erwuenscht.** Diese Prompts sind Anregungen, keine Vorgaben. Kuerze, ergaenze, korrigiere, schaerfe — wie es deine Praxis erfordert.

Wer das nicht akzeptieren kann oder will, sollte diese Promptliste nicht nutzen.

## Worum es geht

Viele dieser Skills sind im Kern strukturierte Mega-Prompts — also keine reinen Workflow-Eingangs- oder Kaltstart-Skills, sondern Prompt-Bausteine, die auch ausserhalb von Claude Code, Codex oder Perplexity Computer ihren Wert entfalten. Du kannst sie als Markdown herunterladen, in den Chat deines bevorzugten Assistenten kopieren, in einen GPT- oder Claude-Projekt-Container legen oder als Vorlage in jedes Tool einfuegen, das Systemprompts oder Anweisungen akzeptiert. Veraenderungen, Kuerzungen und Anpassungen an die eigene Mandantenpraxis sind ausdruecklich erwuenscht.

## So nutzt du die Promptliste

1. Suche dir unten die Fachanwaltschaft oder Praxisrichtung heraus, die zu deinem Fall passt.
2. Klicke auf einen Plugin-Link — du landest im jeweiligen Plugin-Verzeichnis auf GitHub.
3. Im Unterordner `skills/<skill-name>/SKILL.md` findest du den Prompt im Klartext.
4. Kopiere den Inhalt oder lade die Datei roh herunter (Schaltflaeche **Raw** in GitHub).
5. Fuege den Prompt in ChatGPT, Claude, Gemini, Perplexity, Mistral, Le Chat oder ein anderes Tool ein.
6. Passe den Prompt nach Bedarf an oder kombiniere ihn mit deinem eigenen Vorlauf-Text.

Wenn du Claude Code, Codex oder Perplexity Computer einsetzt, kannst du das jeweilige Plugin natuerlich auch direkt als Plugin laden — siehe Hauptseite des Repos.

## Auswahlkriterien fuer diese Liste

Aufgenommen sind nur Plugins mit klarem Praxisnutzen — also Pruefer, Generatoren, Checker, Workflow-Helfer und thematische Tiefenbohrungen. Ausgenommen sind historische und exotische Plugins wie das Allgemeine Preussische Landrecht, das roemische Recht, das roemisch-katholische Kirchenrecht und das Weltraumrecht — diese bleiben im Hauptverzeichnis verfuegbar, gehoeren aber nicht in eine Praxis-Prompt-Liste.

## Inhaltsverzeichnis

- [BGB Allgemeiner Teil und Methodenlehre](#bgb-allgemeiner-teil-und-methodenlehre) (7)
- [BGB Besonderer Teil - Allgemeines Schuldrecht und Bereicherungsrecht](#bgb-besonderer-teil---allgemeines-schuldrecht-und-bereicherungsrecht) (5)
- [Fachanwalt fuer Agrarrecht](#fachanwalt-fuer-agrarrecht) (2)
- [Fachanwalt fuer Arbeitsrecht](#fachanwalt-fuer-arbeitsrecht) (7)
- [Fachanwalt fuer Bank- und Kapitalmarktrecht](#fachanwalt-fuer-bank--und-kapitalmarktrecht) (6)
- [Fachanwalt fuer Bau- und Architektenrecht](#fachanwalt-fuer-bau--und-architektenrecht) (5)
- [Fachanwalt fuer Erbrecht](#fachanwalt-fuer-erbrecht) (1)
- [Fachanwalt fuer Familienrecht](#fachanwalt-fuer-familienrecht) (2)
- [Fachanwalt fuer Gewerblichen Rechtsschutz](#fachanwalt-fuer-gewerblichen-rechtsschutz) (8)
- [Fachanwalt fuer Handels- und Gesellschaftsrecht](#fachanwalt-fuer-handels--und-gesellschaftsrecht) (16)
- [Fachanwalt fuer Insolvenz- und Sanierungsrecht](#fachanwalt-fuer-insolvenz--und-sanierungsrecht) (10)
- [Fachanwalt fuer Internationales Wirtschaftsrecht](#fachanwalt-fuer-internationales-wirtschaftsrecht) (6)
- [Fachanwalt fuer IT-Recht](#fachanwalt-fuer-it-recht) (17)
- [Fachanwalt fuer Medizinrecht](#fachanwalt-fuer-medizinrecht) (6)
- [Fachanwalt fuer Miet- und Wohnungseigentumsrecht](#fachanwalt-fuer-miet--und-wohnungseigentumsrecht) (4)
- [Fachanwalt fuer Migrationsrecht](#fachanwalt-fuer-migrationsrecht) (1)
- [Fachanwalt fuer Sozialrecht](#fachanwalt-fuer-sozialrecht) (3)
- [Fachanwalt fuer Sportrecht](#fachanwalt-fuer-sportrecht) (1)
- [Fachanwalt fuer Strafrecht](#fachanwalt-fuer-strafrecht) (9)
- [Fachanwalt fuer Transport- und Speditionsrecht](#fachanwalt-fuer-transport--und-speditionsrecht) (4)
- [Fachanwalt fuer Urheber- und Medienrecht](#fachanwalt-fuer-urheber--und-medienrecht) (5)
- [Fachanwalt fuer Vergaberecht](#fachanwalt-fuer-vergaberecht) (1)
- [Fachanwalt fuer Verkehrsrecht](#fachanwalt-fuer-verkehrsrecht) (2)
- [Fachanwalt fuer Versicherungsrecht](#fachanwalt-fuer-versicherungsrecht) (2)
- [Fachanwalt fuer Verwaltungsrecht](#fachanwalt-fuer-verwaltungsrecht) (30)
- [Steuerrecht (FA Steuerrecht)](#steuerrecht-fa-steuerrecht) (3)
- [Prozess- und Verfahrenspraxis](#prozess--und-verfahrenspraxis) (13)
- [Anwaltliches Berufsrecht und Kanzleimanagement](#anwaltliches-berufsrecht-und-kanzleimanagement) (16)
- [Sprache, Lehre und Hilfsskills](#sprache-lehre-und-hilfsskills) (7)
- [Kartell- und Wettbewerbsrecht](#kartell--und-wettbewerbsrecht) (1)
- [Franchise und Leasing](#franchise-und-leasing) (2)
- [Vereinsrecht und Genossenschaften](#vereinsrecht-und-genossenschaften) (1)
- [Rechtsgeschichte und Vermoegensrecht der Wiedervereinigung](#rechtsgeschichte-und-vermoegensrecht-der-wiedervereinigung) (2)

## BGB Allgemeiner Teil und Methodenlehre

### [bgb-at-pruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bgb-at-pruefer)

Großes Prüfplugin zum BGB Allgemeiner Teil: Vertragsschluss, Willenserklärung, Zugang, Geschäftsfähigkeit, Form, qES, beA, Anfechtung, Stellvertretung, Fristen, Verjährung und Routing für digitale Ele

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bgb-at-pruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [methodenlehre-buergerliches-recht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/methodenlehre-buergerliches-recht)

Methodenlehre und Rechtsanwendung im deutschen buergerlichen Recht aus Anwaltsperspektive: Anspruchsaufbau, Auslegung, Abwaegung, Praezedenzarbeit, Rechtsfortbildung, Methodenwahl, EU-Methodik und met

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/methodenlehre-buergerliches-recht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [rechtstheorie-rechtsphilosophie](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/rechtstheorie-rechtsphilosophie)

Rechtstheorie- und Rechtsphilosophie-Plugin fuer juristische Praxis: Rechtsbegriff, Kelsen-orientierte Normgeltung, Demokratie, Rechtsrealismus, Systemdenken, Besitzdogmatik, Law-and-Economics, Hayek-

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/rechtstheorie-rechtsphilosophie/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [schriftform-und-textform-bgb](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/schriftform-und-textform-bgb)

Formerfordernisse im deutschen Zivilrecht: Schriftform, Textform, qES, Zugang, beA/ERV und Prozessordnungen. Mit Checklisten, Dokumentation und Rechtsprechung nur nach Live-Verifikation.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/schriftform-und-textform-bgb/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [subsumtions-pruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/subsumtions-pruefer)

Interaktiver Subsumtions-Workflow für deutsches Recht und Europarecht: Tatbestandsmerkmale zerlegen, Vier-Schritt-Schema anwenden, Rechtsfolgen und Einreden prüfen. Keine Rechtsberatung.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/subsumtions-pruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [vertragsausfueller](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/vertragsausfueller)

Freistehendes Vertragsausfüller-Plugin: DOCX-Vorlagen und Altverträge strippen, Felder erkennen, Term Sheets mappen, Rückfragen führen, neue Verträge erzeugen und Track-Changes-Fassungen nur nach ausd

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/vertragsausfueller/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [vertragsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/vertragsrecht)

Vertragsrecht – Lieferanten- und Vertriebsverträge, AGB §§ 305 ff. BGB, NDA, SaaS-/MSA-Review, Renewal-Tracking, Eskalations-Routing, Business-Zusammenfassungen.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/vertragsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## BGB Besonderer Teil - Allgemeines Schuldrecht und Bereicherungsrecht

### [agb-recht-pruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/agb-recht-pruefer)

Gigantischer AGB-Rechtsprüfer und Klausel-Entwerfer für deutsches Recht: §§ 305 bis 310 BGB, UKlaG, B2C/B2B, Branchen-AGB, Redlining, Klauselrisiko und rechtssichere Entwurfsworkflows.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/agb-recht-pruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [bereicherungs-und-anfechtungsrecht-pruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bereicherungs-und-anfechtungsrecht-pruefer)

Mechanisches Durchprüfen von Bereicherungsrecht §§ 812 ff. BGB, AnfG und Insolvenzanfechtung §§ 129-147 InsO. Mit KI-Screening von Schuldnerakten, § 135 Gesellschafterdarlehen, Bargeschäft § 142 und V

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bereicherungs-und-anfechtungsrecht-pruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [bgb-bt-pruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bgb-bt-pruefer)

Großer BGB-BT-Prüfer für Schuldrecht Besonderer Teil: Kauf einschließlich Verbrauchsgüterkauf, Waren mit digitalen Elementen, Updatepflichten und Right-to-Repair-Schnittstellen, außerdem Miete, Werk,

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bgb-bt-pruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [nda-abgleich](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/nda-abgleich)

Gleicht NDA-Entwurf der Gegenseite gegen eigenen Standard ab und setzt Haltelinien chirurgisch im Word-Aenderungsmodus durch. Ampelmatrix ROT/GELB/GRUEN. Ausgabe .docx mit echten Tracked Changes. Kein

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/nda-abgleich/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [nda-verschwiegenheit-generator-checker](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/nda-verschwiegenheit-generator-checker)

Allgemeiner NDA-Ersteller und NDA-Prüfer für deutsche und internationale Verschwiegenheitsvereinbarungen: Entwurf, Redline, GeschGehG, HinSchG, AGB, Arbeitsrecht, M&A, Forschung, Software, Datenraum u

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/nda-verschwiegenheit-generator-checker/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Agrarrecht

### [fachanwalt-agrarrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-agrarrecht)

Plugin Fachanwalt für Agrarrecht. Höferecht (HöfeO Anerbenrecht Länder) Landpachtrecht BGB §§ 581 ff. GAP EU-Direktzahlungen Cross-Compliance Düngeverordnung Pflanzenschutz Tierschutz Forstrecht. Schn

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-agrarrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [tierschutzrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/tierschutzrecht)

Tierschutzrecht-Plugin für TierSchG, BGB § 90a, Haltung, Zucht, Transport, Tierversuche, Behördenverfahren, Strafrecht, Bußgeld und zivilrechtliche Tierfälle.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/tierschutzrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Arbeitsrecht

### [arbeitsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/arbeitsrecht)

Arbeitsrechtliche Workflows fuer Kuendigung, Befristung, Urlaub, AGG, Aufhebungsvertrag, Betriebsrat, Arbeitszeit, Lohn und Expansion. Rechtsprechung wird nur mit Gericht, Datum, Aktenzeichen und veri

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/arbeitsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [arbeitszeugnis-analyse](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/arbeitszeugnis-analyse)

Analyse deutscher Arbeitszeugnisse nach Ampelsystem (Rot/Orange/Grün). Geheimcodes, Schaufenster-Drift, negative Codeworte, Steigerungsadverbien. Satzweise Notenmatrix, begründete Gesamtnotenspanne. V

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/arbeitszeugnis-analyse/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [bav-strategie-konzern](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bav-strategie-konzern)

Strategische Beratung zur betrieblichen Altersversorgung in Konzernen: Pensionsmodelle alle fuenf Durchführungswege CTA Pension Buyouts Drei-Stufen-Theorie Versorgungssystem-Harmonisierung internation

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bav-strategie-konzern/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fachanwalt-arbeitsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-arbeitsrecht)

Fachanwalt-Arbeitsrecht nach FAO Paragraf 10: KSchG, BetrVG, TzBfG, AGG, EntgTranspG, Urlaub, Betriebsrat, Befristung und Vergleichspraxis. Rechtsprechung nur mit Datum, Aktenzeichen und verifizierter

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-arbeitsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [kriegsdienstverweigerung-wehrdienst](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kriegsdienstverweigerung-wehrdienst)

Praxisplugin für Kriegsdienstverweigerung und Wehrdienst aus Gewissensgründen: Art. 4 Abs. 3 GG, KDVG n. F. 2026, Antrag über BAPersBw, BAFzA-Entscheidung, Gewissensbegründung, Soldaten, Reservisten,

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kriegsdienstverweigerung-wehrdienst/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [sozialversicherungsstatus-pruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/sozialversicherungsstatus-pruefer)

Sozialversicherungsstatus und DRV-Statusfeststellung: Geschäftsführer, Freelancer, Anwälte, Lehrkräfte, Musikschulen, Plattformarbeit und Scheinselbständigkeit.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/sozialversicherungsstatus-pruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [startup-hr-personalabteilung-berlin](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/startup-hr-personalabteilung-berlin)

Personalabteilungs- und HR-Operations-Plugin für ein Berliner Start-up mit ca. 100 Beschäftigten: Arbeitsverträge, Payroll/DATEV-Schnittstelle, Personalakten, Datenschutz, AGG-Vorfälle, Betriebsrat, B

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/startup-hr-personalabteilung-berlin/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Bank- und Kapitalmarktrecht

### [bank-rechtsabteilung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bank-rechtsabteilung)

Rechtsabteilung einer mittelgroßen deutschen Bank: Aufsicht, Kredit, ZAG/PSD2, PSD3/PSR-Vorschau, eWpG, MiCAR, Tokenisierung, BaFin, Vorstand, HV und Kanzleisteuerung.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bank-rechtsabteilung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fachanwalt-bank-kapitalmarktrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-bank-kapitalmarktrecht)

Plugin Fachanwalt für Bank- und Kapitalmarktrecht. KWG ZAG WpHG WpIG MiFID-II MAR MiCAR Verbraucherkredit Vermögensanlage Beratungshaftung. Schnittstellen Plugin gesellschaftsrecht regulatorisches-rec

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-bank-kapitalmarktrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [factoring-recht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/factoring-recht)

Super-Plugin für Factoring, Forderungskauf, Aufsichtsrecht, Vertragsgestaltung, Debitorenkommunikation, Insolvenz- und Sanierungsfragen.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/factoring-recht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [geldwaeschepraevention-aml-kyc](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/geldwaeschepraevention-aml-kyc)

Freistehendes Plugin für Geldwäscheprävention, AML, KYC, GwG-Risikoanalyse, UBO, PEP, Sanktionen, FIU/goAML, Transparenzregister und Behördenverfahren.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/geldwaeschepraevention-aml-kyc/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [insiderrecht-compliance](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/insiderrecht-compliance)

Insiderrecht- und Marktmissbrauchs-Compliance nach MAR, WpHG und BaFin-Praxis: Insiderinformationen, Ad-hoc, Insiderlisten, Handelsverbote, Aufschub, Directors Dealings, Aufklärung und Verteidigung.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/insiderrecht-compliance/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [wandeldarlehen-lebenszyklus](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/wandeldarlehen-lebenszyklus)

Begleitet den vollständigen Lebenszyklus eines Wandeldarlehens für GmbH und UG: Vertragserstellung (bilingual/einsprachig), Beurkundungsprüfung, Wandelereignisse, Wandlungsberechnung, Cap-Table-Update

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/wandeldarlehen-lebenszyklus/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Bau- und Architektenrecht

### [erbbaurecht-praxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/erbbaurecht-praxis)

Praxisplugin für Erbbaurecht und Erbbaugrundbuch: Erbbaurechtsvertrag, Erbbauzins, Wertsicherung, Heimfall, Zustimmung, Belastung, Finanzierung, Veräußerung, Laufzeit, Entschädigung, Zwangsversteigeru

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/erbbaurecht-praxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fachanwalt-bau-architektenrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-bau-architektenrecht)

Plugin Fachanwalt für Bau- und Architektenrecht. BGB Werkvertrag VOB-A VOB-B VOB-C HOAI Bauordnungsrecht. Bauvertrag Maengelhaftung Abnahme Vergaberecht. Schnittstellen Plugin fachanwalt-vergaberecht

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-bau-architektenrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [hoai-leistungsphasen-praxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/hoai-leistungsphasen-praxis)

Großplugin für HOAI-Leistungsphasen 1 bis 9: Grundlagenermittlung, Vorplanung, Entwurf, Genehmigung, Ausführungsplanung, Vergabe, Bauüberwachung, Objektbetreuung, Honorar, Vertrag, Haftung, Nachträge

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/hoai-leistungsphasen-praxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [immobilienrechtspraxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/immobilienrechtspraxis)

Werkzeuge fuer immobilienrechtliche Rechtsabteilungen: musterbasierte Vertragserstellung mit Klauselschutz, Vertragspruefung gegen Playbook, Grundbuchanalyse, Sachverhaltsermittlung, Mieteranfragen, C

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/immobilienrechtspraxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [nachbarschaftsstreit-pruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/nachbarschaftsstreit-pruefer)

Nachbarrecht und Nachbarschaftsstreit: Überbau, Überhang, Äste/Wurzeln, Grenzbaum, Zaun/Mauer/Hecke, Immissionen, Vertiefung, Notweg, Hammerschlagsrecht, Beweise, Aufforderung, Klage und Vergleich.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/nachbarschaftsstreit-pruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Erbrecht

### [fachanwalt-erbrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-erbrecht)

Plugin Fachanwalt für Erbrecht. BGB Erbrecht §§ 1922 ff. Pflichtteil Testament Erbschein Erbauseinandersetzung Erbschaftsteuer EU-ErbVO. Schnittstellen Plugin steuerrecht-anwalt-und-berater kanzlei-al

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-erbrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Familienrecht

### [betreuungsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/betreuungsrecht)

Betreuungsrechtliche Skills für ehrenamtliche Familienbetreuer, Berufs- und Vereinsbetreuer: Kaltstart, Scan-Akte, Kalender, Gerichtskommunikation, Jahresbericht, Vermögensverzeichnis, Genehmigungspfl

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/betreuungsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fachanwalt-familienrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-familienrecht)

Plugin Fachanwalt für Familienrecht. Orientierung Normen Mandate Fristen Literatur. Familiengericht FamFG Scheidung Sorge Umgang Unterhalt Zugewinn Ehevertrag eingetragene Lebenspartnerschaft. Ergaenz

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-familienrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Gewerblichen Rechtsschutz

### [designrecht-geschmacksmusterrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/designrecht-geschmacksmusterrecht)

Eigenständiges Plugin für deutsches und europäisches Designrecht: DesignG, EU-Design, DPMA, EUIPO, WIPO-Hague, Neuheit, Eigenart, Anmeldung, Nichtigkeit, Verletzung, Eilrechtsschutz, Zoll, Plattformen

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/designrecht-geschmacksmusterrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fachanwalt-gewerblicher-rechtsschutz](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-gewerblicher-rechtsschutz)

Plugin Fachanwalt für gewerblichen Rechtsschutz nach FAO § 14k. MarkenG. DesignG. UWG. PatG GebrMG. UrhG-Bezuege. Markenanmeldung DPMA EUIPO. UWG-Abmahnung §§ 8 ff. UWG. Designverletzung. Einstweilige

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-gewerblicher-rechtsschutz/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fashion-law-moderecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fashion-law-moderecht)

Praxisplugin Fashion Law/Moderecht für Modeunternehmen, Designer, Händler und Kanzleien: IP, Designs, Marken, Textilkennzeichnung, Produktsicherheit, Nachhaltigkeit, Lieferkette, Plattformen, E-Commer

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fashion-law-moderecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [gebrauchsmusterrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/gebrauchsmusterrecht)

Eigenständiges Plugin für deutsches Gebrauchsmusterrecht: GebrMG, DPMA-Anmeldung, Recherche nach § 7 GebrMG, Abzweigung, Neuheitsschonfrist, Verletzung, Löschung, BPatG-Beschwerde, Lizenz, FTO und Sch

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/gebrauchsmusterrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [gewerblicher-rechtsschutz](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/gewerblicher-rechtsschutz)

Gewerblicher Rechtsschutz – DPMA/EUIPO-Markenrecherche und -anmeldung, Freedom-to-Operate, Patentscreening, UWG- und Urheberrechts-Abmahnung (Versand und Reaktion), Open-Source-Compliance, IP-Klausel-

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/gewerblicher-rechtsschutz/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [markenrecht-fashion-luxus](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/markenrecht-fashion-luxus)

Großes Markenrechts-Plugin für DE/EU/US und internationale Portfolios: DPMA, EUIPO, WIPO/Madrid, USPTO, Markenarten, Schutzhindernisse, Benutzung, Widerspruch, Verfall/Nichtigkeit, Enforcement, Plattf

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/markenrecht-fashion-luxus/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [patentrecherche](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/patentrecherche)

Patentrecherche für Patentanwaelte agentisch in Espacenet Google Patents DPMAregister DEPATISnet EPO Register WIPO USPTO. Stand der Technik Neuheit § 3 PatG Art. 54 EPUe erfinderische Tätigkeit § 4 Pa

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/patentrecherche/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [patentrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/patentrecht)

Großes Patentrechts-Plugin für Erfindungsaufnahme, Patentanmeldung, Anspruchsentwurf, Recherche, Neuheit, erfinderische Tätigkeit, FTO, Abmahnung, Claim Chart, Vorbenutzungsrecht, Lizenz, Erfinderbene

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/patentrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Handels- und Gesellschaftsrecht

### [aktienrecht-hauptversammlung-ag-se](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/aktienrecht-hauptversammlung-ag-se)

Hauptversammlungs-Vorbereiter, Leitfaden-Ersteller und Durchführungsplugin für kleine AG, normale AG, börsennotierte AG und SE: Einberufung, Tagesordnung, virtuelle HV, Q&A, Abstimmung, Niederschrift,

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/aktienrecht-hauptversammlung-ag-se/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [aufsichtsrat-ag-se-praxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/aufsichtsrat-ag-se-praxis)

Praxisplugin für Aufsichtsräte in AG und SE: Überwachung, Informationsrechte, Vorstand bestellen/abberufen, Vergütung, Ausschüsse, Protokoll, Business Judgment, Haftungsvermeidung, Börse, SE und Mitbe

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/aufsichtsrat-ag-se-praxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [corporate-kanzlei](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/corporate-kanzlei)

Corporate-Kanzlei-Plugin: Deal-Kommandocenter, Datenraum, Due Diligence, SPA/APA, Umwandlung, StaRUG, Insolvenzplan, W&I, Signing/Closing, PMI.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/corporate-kanzlei/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fachanwalt-handels-gesellschaftsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-handels-gesellschaftsrecht)

Plugin Fachanwalt für Handels- und Gesellschaftsrecht nach FAO § 14i. HGB. AktG. GmbHG. PartGG. UmwG. Geschäftsführerhaftung §§ 43 GmbHG 93 AktG. Gesellschafterstreit Beschlussanfechtung. Handelsvertr

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-handels-gesellschaftsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [gesellschaftsgruender](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/gesellschaftsgruender)

Anfängerfreundlicher Gründungsassistent für deutsche Gesellschaften: Rechtsformwahl, Satzung, SHA, Cap Table, Notar, Handelsregister, Bank/KYC, Behörden, Steuerstart, IP, Datenschutz, erste 100 Tage u

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/gesellschaftsgruender/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [gesellschaftsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/gesellschaftsrecht)

Gesellschaftsrecht – GmbH/AG/Personengesellschaften, M&A-Due-Diligence ohne Discovery (Q&A + Datenraum), Gesellschafterbeschlüsse, HRB/HRA-Anmeldungen, Closing Checklists, Compliance-Fristen.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/gesellschaftsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [gesellschaftsrecht-legal-english](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/gesellschaftsrecht-legal-english)

Didaktisches Gesellschaftsrecht — English Business Terms: Corporate Legal English fuer Big-Law-Anfaenger. Dealroom: Cap Table vs Gesellschafterliste; Term Sheet; SHA; Vesting; Drag/Tag; Liquidation Pr

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/gesellschaftsrecht-legal-english/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [gesellschaftsrechtliche-treuepflicht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/gesellschaftsrechtliche-treuepflicht)

Großes Prüfplugin zur gesellschaftsrechtlichen Treuepflicht in GmbH, AG, SE, Personengesellschaft, Familiengesellschaft und Konzern: Stimmrecht, Minderheitenschutz, Gesellschafterliste, Einziehung, Au

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/gesellschaftsrechtliche-treuepflicht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [grosskanzlei-corporate-ma](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/grosskanzlei-corporate-ma)

Freistehendes Big-Law-Corporate/M&A-Plugin: Deal-OS, Padlet-Canvas, Anfänger-/First-Year-Coach, Aktenanlage, Datenraum, Legal DD, Tabellenreview, SPA/APA, W&I, Public M&A, UmwG/UmwStG, StaRUG, Fusions

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/grosskanzlei-corporate-ma/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [handelsrecht-hgb](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/handelsrecht-hgb)

Reines HGB-Plugin für Handelsrecht: Kaufmann, Handelsregister, Firma, Prokura, Handlungsvollmacht, Handelsgeschäfte, Handelskauf, Handelsvertreter, Makler, Kommission, Fracht, Spedition, Lager, Handel

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/handelsrecht-hgb/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [handelsregister-praxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/handelsregister-praxis)

Praxisplugin für den Umgang mit dem Handelsregister: Anmeldung, Registergericht, Rechtspfleger, Registerrichter, Beanstandung, Zwischenverfügung, Beschwerde, Gesellschafterliste, Kapitalmaßnahmen, Fir

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/handelsregister-praxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [handelsvertreterrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/handelsvertreterrecht)

Handelsvertreterrecht nach HGB: Status, Provision, Buchauszug, Kündigung, Ausgleich § 89b, Wettbewerbsverbot § 90a und Vertriebsmodelle.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/handelsvertreterrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [mittelstand-corporate-ma](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/mittelstand-corporate-ma)

Freistehendes Mittelstandsmandat-Corporate/M&A-Plugin: Deal-Kommandocenter, Aktenanlage, Datenraum, Legal DD, Tabellenreview, Liquiditätsvorschau, SPA/APA, W&I, Public M&A, Umwandlung, StaRUG/Insolven

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/mittelstand-corporate-ma/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [private-equity-praxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/private-equity-praxis)

Private-Equity-Praxis-Plugin für deutsche Kanzleien, Investoren, Fonds, Family Offices und Unternehmen: Fund Formation, KAGB/AIF, ELTIF, Deal Execution, Private Credit, Schuldschein, LMA, NPL, Portfol

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/private-equity-praxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [schoeffen-handelsrichter-praxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/schoeffen-handelsrichter-praxis)

Plugin für Schöffen, Jugendschöffen, ehrenamtliche Richter und Handelsrichter: Rolle, Rechte, Pflichten, Sitzung, Beratung, Befangenheit, Beweiswürdigung, Handelskammer, Verwaltungsgericht und sichere

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/schoeffen-handelsrichter-praxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [venture-capital-geber](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/venture-capital-geber)

VC-Geber-Plugin für deutsche Venture-Capital-Investoren, Family Offices, Angels und junge VCs: Sourcing, Deal-Tracking, Wandeldarlehen, SAFE, Pre-Seed, Series A/B, Cap Table, Follow-on, Portfolio-Upda

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/venture-capital-geber/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Insolvenz- und Sanierungsrecht

### [fachanwalt-insolvenz-sanierungsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-insolvenz-sanierungsrecht)

Plugin Fachanwalt für Insolvenz- und Sanierungsrecht nach FAO § 14. InsO Eroeffnung Antragspflicht § 15a Gläubigerantrag § 14 InsO. StaRUG Restrukturierungsplan. Insolvenzanfechtung §§ 129 ff. InsO. S

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-insolvenz-sanierungsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fortbestehensprognose](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fortbestehensprognose)

Fortbestehensprognose § 19 Abs. 2 InsO als Geschäftsführer-Selbstdokumentation. Bilanzstatus Annahmen Plausibilisierung Zwoelf-Monats-Liquiditaet. Sanierungsbausteine Patronatserklärung Comfortletter

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fortbestehensprognose/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [insolvenzforderungsanmeldungspruefung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/insolvenzforderungsanmeldungspruefung)

Freistehendes Plugin für die Insolvenzforderungsanmeldungsprüfung: Intake, § 174 InsO, Belege, Grund, Betrag, Rang, vbuH, Nachforderungen, Tabellenimport, Prüfungstermin, Bestreiten, Feststellung, Tab

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/insolvenzforderungsanmeldungspruefung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [insolvenzplan-starug-planwerkstatt](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/insolvenzplan-starug-planwerkstatt)

Freistehendes Plugin für Insolvenzplan und StaRUG-Restrukturierungsplan: Intake, Sanierungskonzept, Vergleichsrechnung, Gruppen, Klassen, darstellender und gestaltender Teil, Anlagen, Abstimmung, Cram

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/insolvenzplan-starug-planwerkstatt/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [insolvenzrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/insolvenzrecht)

Insolvenzrechtliche Skills zu Zahlungsunfähigkeit, Überschuldung, Antragspflicht und Gläubigerantrag.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/insolvenzrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [insolvenzverwaltung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/insolvenzverwaltung)

Freistehendes Insolvenzverwaltungs-Plugin aus Sicht von Insolvenzverwalter, Sachwalter und vorläufiger Verwaltung: Regelverfahren, Eigenverwaltung, Schutzschirm, Anfechtung, § 15b InsO, Masse, Forderu

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/insolvenzverwaltung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [krisenfrueherkennung-starug](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/krisenfrueherkennung-starug)

Krisenfrüherkennung und Krisenmanagement nach StaRUG: Pflicht zum 24-Monats-Frühwarnsystem nach § 1 StaRUG, § 102 StaRUG Warnpflicht der Berater, Geschäftsführerhaftung, drohende Zahlungsunfähigkeit,

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/krisenfrueherkennung-starug/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [liquiditaetsplanung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/liquiditaetsplanung)

Liquiditaetsplanung nach deutschem Recht: 3-Wochen-Vorschau, 13/26/52-Wochen-Forecast, Excel-Export, Quote/Luecken-Ampel, Dokumentationspaket und Schnittstellen zu Fortbestehensprognose und Insolvenzr

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/liquiditaetsplanung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [us-bankruptcy-code](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/us-bankruptcy-code)

US Bankruptcy Code Title 11: Chapters 7/9/11/12/13/15, Automatic Stay, Claims, DIP, 363 Sales, Plans und Cross-Border.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/us-bankruptcy-code/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [verbraucherinsolvenz-schuldenbereinigung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verbraucherinsolvenz-schuldenbereinigung)

Verbraucherinsolvenz und Schuldenbereinigung nach InsO: außergerichtlicher Einigungsversuch, Schuldenbereinigungsplan, Antrag, Restschuldbefreiung, P-Konto, ehemalige Selbstständige und lebensnahe Ver

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verbraucherinsolvenz-schuldenbereinigung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Internationales Wirtschaftsrecht

### [aussenwirtschaft-zoll-sanktionen](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/aussenwirtschaft-zoll-sanktionen)

Freistehendes Plugin für Außenwirtschaft, Sanktionen, Zoll, Exportkontrolle, BAFA, TARIC, CBAM, Verbrauchsteuer, AWV, AML/KYC und Ermittlungen.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/aussenwirtschaft-zoll-sanktionen/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [commercial-courts-deutschland](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/commercial-courts-deutschland)

Commercial-Courts-Plugin für englischsprachige Wirtschaftsverfahren in Deutschland: Zuständigkeit, Wahlklauseln, Klage, Case Management, Beweis, Geheimnisschutz, Wortprotokoll/Transcript, Rechtsmittel

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/commercial-courts-deutschland/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [common-law-kompass](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/common-law-kompass)

Freistehendes Common-Law-Plugin für deutsche Wirtschaftsjuristen: UK/US-False-Friends, Vertragsbegriffe, Consideration, Suretyship, Indemnity, UCC, Precedent, Discovery und bilinguale Drafting-Reviews

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/common-law-kompass/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fachanwalt-internationales-wirtschaftsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-internationales-wirtschaftsrecht)

Plugin Fachanwalt für Internationales Wirtschaftsrecht. CISG Bruessel Ia Rom I Rom II Schiedsverfahren ICC UNCITRAL Investitionsschutz ICSID WTO EU-Aussenhandel LkSG. Schnittstelle Plugin kanzlei-allg

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-internationales-wirtschaftsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [festlandchina-wirtschaftsverkehr](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/festlandchina-wirtschaftsverkehr)

Mega-Plugin für wirtschaftlichen Umgang mit Festlandchina: Fabrik, Import, Export, Investition, De-Risking, Lieferkette, IP, Daten, Exportkontrolle und politisches Risiko.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/festlandchina-wirtschaftsverkehr/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [internationales-handelsrecht-lex-mercatoria](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/internationales-handelsrecht-lex-mercatoria)

Mega-Plugin für internationales Handelsrecht, CISG, Incoterms, UNIDROIT Principles, Lex Mercatoria, Schiedsverfahren, Trade Finance und Lieferkettenverträge.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/internationales-handelsrecht-lex-mercatoria/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer IT-Recht

### [barrierefreiheit-web-checker](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/barrierefreiheit-web-checker)

Web-Barrierefreiheits-Checker für BFSG, BFSGV, BITV 2.0, EN 301 549 und WCAG: Scope, Audit, Tastatur, Screenreader, Formulare, PDFs, Erklärung, Roadmap und Abnahme.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/barrierefreiheit-web-checker/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [berufsrecht-ki-vertragspruefung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsrecht-ki-vertragspruefung)

Berufsrechtliche und strafrechtliche Vorprüfung von Vertraegen mit privaten Legal-AI-Anbietern. Für Anwaelte StB WP Patentanwaelte Notare. §§ 43e BRAO 62a StBerG 50a WPO 39c PAO 26a BNotO § 203 StGB.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsrecht-ki-vertragspruefung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [datenbankrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/datenbankrecht)

Großes Plugin zum deutschen und europäischen Datenbankrecht: UrhG §§ 87a ff., Datenbankrichtlinie, Investitionsschutz, Scraping, API, KI-Training, Vertrags- und Plattformkonflikte.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/datenbankrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [datenschutz-sanktionsverfahren-verteidigung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/datenschutz-sanktionsverfahren-verteidigung)

Spezialplugin für Vertretung und Verteidigung in datenschutzrechtlichen Sanktionsverfahren: DSGVO-Bußgeld, OWiG/StPO, Art.-58-Anordnung, Verwaltungsgericht, Aufsichtsbehördenkommunikation, EuGH/EDPB u

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/datenschutz-sanktionsverfahren-verteidigung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [datenschutzrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/datenschutzrecht)

DSGVO/BDSG/TDDDG – PIA/DPIA, AVV-Review, Auskunft Art. 15, Datenpanne Art. 33/34, Drittlandstransfer Art. 44 ff. inkl. US-Transfer, DPF, SCC, TIA, Behördenpaket und Brückenskills zur Sanktionsverteidi

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/datenschutzrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [dsa-dma-digitalregulierung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/dsa-dma-digitalregulierung)

Digitalregulierung der EU: DSA (VO 2022/2065) und DMA (VO 2022/1925) plus Data Act DGA AI Act NIS-2 DORA CRA eIDAS 2.0 DDG P2B-VO und § 19a GWB. Gatekeeper-Schwellen VLOP-Einordnung Risikobewertung Ar

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/dsa-dma-digitalregulierung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [ecommerce-recht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/ecommerce-recht)

Super-Plugin für Online-Shops, Plattformen, Marktplätze und digitale Verbraucherprozesse.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/ecommerce-recht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fachanwalt-it-recht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-it-recht)

Plugin Fachanwalt für Informationstechnologierecht. SaaS Software-Lizenz DSGVO BDSG TTDSG TKG NIS2 DDG DSA DMA EU-KI-VO Open-Source. Schnittstellen Plugin datenschutzrecht ki-governance kanzlei-allgem

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-it-recht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [influencer-recht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/influencer-recht)

Plugin für Influencer, Creator, Agenturen und Unternehmen: Werbekennzeichnung, Steuer, Umsatzsteuer, Sachleistungen, Plattformrecht, Medienrecht, Marken, Urheberrecht, Datenschutz und Verträge.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/influencer-recht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [ki-governance](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/ki-governance)

EU-KI-VO + DSGVO – Use-Case-Triage, KI-Inventar, AIA/DPIA, Vendor-Review, Drift-Monitoring der KI-Richtlinie.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/ki-governance/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [ki-richtlinie-kanzleien](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/ki-richtlinie-kanzleien)

Erstellt und pflegt eine berufsrechtskonforme KI-Nutzungsrichtlinie für Kanzleien und Rechtsabteilungen mit Anwaelten und Syndikus-Anwaelten. Beruht auf BRAO, BORA, DSGVO, KI-Verordnung sowie BRAK- un

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/ki-richtlinie-kanzleien/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [ki-vo-ai-act-pruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/ki-vo-ai-act-pruefer)

Mechanik-Workflow zur KI-VO (EU 2024/1689): KI-System-Definition, Rollen, Risikoklassen, Hochrisiko-Diagnose, GPAI, Art. 43-Konformitätsbewertung, CE/EU-DB, Marktbeobachtung und Konformitäts-Evidence-

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/ki-vo-ai-act-pruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [nis2-cybersecurity-compliance](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/nis2-cybersecurity-compliance)

NIS-2, BSIG 2025, BSI, IT-Grundschutz, Cloud, Incident Response und technische Security-Compliance für Geschäftsleitung, CISO und Legal.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/nis2-cybersecurity-compliance/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [phishing-vorfall-pruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/phishing-vorfall-pruefer)

Freistehender Phishing-Vorfall-Prüfer für Online-Banking: BGB § 675u, § 675v, § 675w, pushTAN, Call-ID-Spoofing, grobe Fahrlässigkeit, Beweislast, Bankpflichten, Schlichtung und Klage.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/phishing-vorfall-pruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [robotik-recht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/robotik-recht)

Robotik-Recht Deutschland/EU: Maschinenverordnung, KI-VO, Produkthaftung, ProdSG, Datenschutz, CRA, Data Act, CE, Marktüberwachung, Unfälle, Rückruf, Verträge und Robotik-Testakte.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/robotik-recht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [softwarerecht-de-eu-us](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/softwarerecht-de-eu-us)

Softwarerecht Deutschland/EU/International/USA: Entwicklung, Lizenzen, SaaS, Open Source, Arbeitnehmer/Freelancer, Softwarepatente, AI-Code und Streit.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/softwarerecht-de-eu-us/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [telekommunikationsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/telekommunikationsrecht)

Großes Telekommunikationsrecht-Plugin für TKG, Bundesnetzagentur, Internetanschlüsse, Anbieterwechsel, Kundenschutz, Netzregulierung, Frequenzen, Nummerierung, Sonderkartellrecht, Datenschutz und Sich

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/telekommunikationsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Medizinrecht

### [apothekenrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/apothekenrecht)

Super-Plugin für Apothekenrecht: Betriebserlaubnis, ApBetrO, Versand, E-Rezept, BtM, Retaxation, Aufsicht und Compliance.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/apothekenrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [betaeubungsmittelrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/betaeubungsmittelrecht)

Betäubungsmittelrecht-Plugin für BtMG, BtMVV, KCanG/MedCanG-Schnittstellen, Strafverfahren, Therapie, ärztliche Praxis, Apotheken und Compliance.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/betaeubungsmittelrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fachanwalt-medizinrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-medizinrecht)

Plugin Fachanwalt für Medizinrecht. Arzthaftung §§ 630a ff. BGB Patientenrechte Vertragsarztrecht Berufsrecht Aerzte SGB V Krankenversicherung MPDG Apothekenrecht. Schnittstellen Plugin fachanwalt-soz

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-medizinrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [goae-gebuehrenordnung-aerzte](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/goae-gebuehrenordnung-aerzte)

Super-Plugin zur GOÄ: private Arztrechnungen prüfen, erstellen, begründen, beanstanden und prozessual verwerten.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/goae-gebuehrenordnung-aerzte/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [krankenhausrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/krankenhausrecht)

Super-Plugin für deutsches Krankenhausrecht: Planung, Finanzierung, Entgelte, Reform, Qualität, MD-Prüfung, Klinikbetrieb und Rechtsstreit.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/krankenhausrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [krankenkassenrecht-krankenversicherung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/krankenkassenrecht-krankenversicherung)

Plugin für GKV, PKV, Beihilfe-Schnittstellen und Krankenversicherungsrecht: Leistungen, Beiträge, Krankengeld, Hilfsmittel, Widerspruch, MD, Versicherungsvertrag und Kostenerstattung.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/krankenkassenrecht-krankenversicherung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Miet- und Wohnungseigentumsrecht

### [fachanwalt-miet-wohnungseigentumsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-miet-wohnungseigentumsrecht)

Großer Fachanwalt-Kompass Miet- und Wohnungseigentumsrecht mit über 200 Skills für Wohnraum, Gewerberaum, Betriebskosten, WEG, Hausverwaltung, Beschlüsse, GEG, Beweise, Fristen und Workflows.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-miet-wohnungseigentumsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [grundbuchamt-praxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/grundbuchamt-praxis)

Praxisplugin für Grundbuchamt, Grundbuchauszug und grundbuchtaugliche Nachweise: Abteilung I/II/III lesen, Bewilligung, Antrag, Auflassung, Rang, Zwischenverfügung, Beschwerde, Grundschuldbrief, Aufge

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/grundbuchamt-praxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [mietrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/mietrecht)

Mietrecht für Mieter und Vermieter mit ausschließlich amtlichen Mietspiegel-Quellen pro Bundesland und für Top- und Universitaetsstaedte. Datenerhebung Mieterhoehungs-Widerspruch Mietsenkungsverlangen

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/mietrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [weg-hausverwaltung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/weg-hausverwaltung)

Operatives WEG- und Hausverwaltungs-Plugin fuer Beschluesse, Eigentuemerversammlung, Protokoll, Beschlusssammlung, Wirtschaftsplan, Jahresabrechnung, Hausgeld, Sonderumlage, Betriebskosten, Handwerker

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/weg-hausverwaltung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Migrationsrecht

### [fachanwalt-migrationsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-migrationsrecht)

Großer Fachanwalt-Kompass Migrationsrecht mit über 200 Skills für Aufenthalt, Blaue Karte EU, Fachkräfte, Asyl, Dublin/GEAS, Einbürgerung, Staaten-/Gebietschecks und spanische/einfache Erklärung.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-migrationsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Sozialrecht

### [fachanwalt-sozialrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-sozialrecht)

Plugin Fachanwalt für Sozialrecht nach FAO § 11. SGB I-XII und Sozialgerichtsbarkeit SGG. Widerspruch § 84 SGG Klage § 87 SGG Eilantrag § 86b SGG. Buergergeld Erwerbsminderung GdB Pflegegrad Hilfsmitt

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-sozialrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [rentenpruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/rentenpruefer)

Rentenprüfer für gesetzliche Rente, Versorgungswerk und internationale Versicherungszeiten: Kontenklärung, Rentenantrag, Nachversicherung, Auslandszeiten, Bescheide, Widerspruch und verständliche Doku

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/rentenpruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [selbstvertreter-sozialgericht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/selbstvertreter-sozialgericht)

Selbstvertretung vor dem Sozialgericht ohne Anwalt: Anfänger-Workflow, Widerspruch, Klage, Eilantrag, Pflegegrad, Krankenkasse, Bürgergeld, EM-Rente, GdB, Belege, Gutachten, Kostenfreiheit, Sanity-Che

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/selbstvertreter-sozialgericht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Sportrecht

### [fachanwalt-sportrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-sportrecht)

Plugin Fachanwalt für Sportrecht. Verbandsrecht (DFB FIFA UEFA IOC DOSB) CAS Schiedsverfahren Spielerverträge Doping WADA-Code NADA Sponsoring Persönlichkeitsrechte Veranstalterhaftung. Schnittstelle

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-sportrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Strafrecht

### [aktenaufbereiter-strafrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/aktenaufbereiter-strafrecht)

Aktenaufbereiter für die Strafverteidigung. Sechs Excel-fähige Übersichten — Aktenvorblatt; Personenverzeichnis; Tatkomplexe; Beziehungen; Chronologie; Fristen. Fortlaufend ergaenzbar. Erkennt Luecken

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/aktenaufbereiter-strafrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fachanwalt-strafrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-strafrecht)

Plugin Fachanwalt Strafrecht: StPO/StGB, Nebenstrafrecht, Verteidigung, Ermittlungsverfahren, HV, Revision, Nebenklage und Zeugenbeistand plus Strafprozess-Cockpit fuer Fristen, Aktenlog, U-Haft, Akte

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-strafrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [internal-investigations-praxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/internal-investigations-praxis)

Internal-Investigations-Praxisplugin fuer Kanzleien und Unternehmen: Untersuchungsauftrag, Scope, Interviews, Arbeitsrecht, Datenschutz, Privilege-Risiko, StPO-Beschlagnahme, HinSchG, Dokumentation un

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/internal-investigations-praxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [ordnungswidrigkeitenrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/ordnungswidrigkeitenrecht)

Allgemeines OWiG-Plugin für Bußgeldverfahren: Anhörung, Bescheid, Einspruch, Behörde, Akteneinsicht, Gericht, Verjährung, Einziehung und Nebenfolgen.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/ordnungswidrigkeitenrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [staatsanwaltschaft-praxis-einstieg](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/staatsanwaltschaft-praxis-einstieg)

Praxisplugin für neue Staatsanwältinnen, Staatsanwälte und Sitzungsdienst: Ermittlungsverfahren, Polizei, RiStBV, Vermerke, Beschlagnahme, digitale Beweise, Anklage, Strafbefehl, Hauptverhandlung, Plä

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/staatsanwaltschaft-praxis-einstieg/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [strafanzeige-vorbereiter](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/strafanzeige-vorbereiter)

Vorsichtiger Strafanzeigen-Vorbereiter: prüft Anfangsverdacht, Beweise, Strafantrag, Risiken falscher Verdächtigung, Alternativen und erstellt nur bei tragfähiger Tatsachengrundlage eine nüchterne Str

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/strafanzeige-vorbereiter/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [strafbefehl-verteidiger](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/strafbefehl-verteidiger)

Freistehendes Strafbefehls-Plugin für Verteidigung gegen Strafbefehl, Einspruch, Akteneinsicht, Tagessätze, Nebenfolgen, Pflichtverteidigung, Wiedereinsetzung, Einstellung, Zeugenstrategie und Hauptve

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/strafbefehl-verteidiger/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [strafzumessung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/strafzumessung)

Strafzumessung nach deutschem Strafrecht vom Strafbefehl bis zur grossen Strafkammer. § 46 StGB Strafzumessungstatsachen Tagessatz Geldstrafe Freiheitsstrafe Bewaehrung § 56 § 49 Regelbeispiele besond

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/strafzumessung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [verkehrsowi-verteidiger](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verkehrsowi-verteidiger)

Freistehendes VerkehrsOWi-Plugin für Bußgeldbescheid, Anhörung, Einspruch, Punkte, Fahrverbot, Rotlicht, Geschwindigkeit, Abstand, Handy, Alkohol, Drogen, Akteneinsicht, Messakte, Zeugenstrategie und

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verkehrsowi-verteidiger/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Transport- und Speditionsrecht

### [fachanwalt-transport-speditionsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-transport-speditionsrecht)

Plugin Fachanwalt für Transport- und Speditionsrecht. HGB §§ 407 ff. Frachtvertrag §§ 453 ff. Spedition CMR COTIF Montrealer Übereinkommen Haager Visby Regeln ADSp. Schnittstelle Plugin kanzlei-allgem

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-transport-speditionsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fluggastrechte](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fluggastrechte)

Fluggastrechte selber geltend machen nach VO (EG) Nr. 261/2004. Tickets erfassen, Annullierung oder Verspaetung pruefen, aussergewoehnliche Umstaende, Distanz, Ausgleich, Forderungsschreiben, Mahnung

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fluggastrechte/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [luftrecht-flughafenrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/luftrecht-flughafenrecht)

Luftrecht-Plugin für LuftVG, LuftSiG, LBA, Flughäfen, Airlines, Slots, Flugzeugpfandrechte, Beschlagnahme, Insolvenz, Drohnen und Aviation-Compliance.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/luftrecht-flughafenrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [seerecht-schifffahrtsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/seerecht-schifffahrtsrecht)

See- und Schifffahrtsrecht-Plugin für Schiffskauf, Schiffbau, Werften, Schiffshypothek, Schiffsregister, Arrest, Wrack, Bergung, Charter und ITLOS.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/seerecht-schifffahrtsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Urheber- und Medienrecht

### [fachanwalt-urheber-medienrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-urheber-medienrecht)

Plugin Fachanwalt für Urheber- und Medienrecht. UrhG UWG KUG Recht am eigenen Bild Presserecht Persoenlichkeitsrecht Medienstaatsvertrag. Schnittstellen Plugin gewerblicher-rechtsschutz verlagsredakti

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-urheber-medienrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [urheberrecht-de-eu](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/urheberrecht-de-eu)

Deutsches und EU-Urheberrecht fuer Werkhoehe, Musik, KI, TDM, Software, Lizenzen, Abmahnung, Schranken, Leistungsschutz und Rechteclearing.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/urheberrecht-de-eu/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [us-copyright-registrierung-verlag](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/us-copyright-registrierung-verlag)

US Copyright Act fuer deutsche Verlage und Rechteinhaber: Title 17, Registrierung, Rechte, Fair Use, DMCA, Musik, AI, Litigation und Deals.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/us-copyright-registrierung-verlag/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [verlagsrecht-buchpreisbindung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verlagsrecht-buchpreisbindung)

Plugin für Verlagsrecht, Verlagsgesetz, Autoren- und Herausgeberverträge, Buchpreisbindung, Titelschutz, Vertrieb, E-Book, Hörbuch und verlagsnahe Compliance.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verlagsrecht-buchpreisbindung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [verlagsredaktion](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verlagsredaktion)

Verlagsdesk fuer juristische und fachliche Verlage: Eingangskorb, Manuskript, Redaktion, Rechtecheck, Zitate, Bildrechte, Autorenkommunikation, Heftplanung, Buchprojekte, Satzfahnen, Metadaten, Market

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verlagsredaktion/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Vergaberecht

### [fachanwalt-vergaberecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-vergaberecht)

Plugin Fachanwalt fuer Vergaberecht als Vergabe-Workbench: GWB 97 ff., VgV, UVgO, SektVO, KonzVgV, VOB/A, Schwellenwerte 2026/2027, Vergabeakte, Ruge, Nachpruefung, TED/eForms, Wettbewerbsregister und

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-vergaberecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Verkehrsrecht

### [fachanwalt-verkehrsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-verkehrsrecht)

Plugin Fachanwalt für Verkehrsrecht. StVG StVO PflVG VVG-Bezuege. Verkehrsunfall Personen- und Sachschaden Bußgeld Fahrerlaubnis Verkehrsstrafrecht (§§ 315c 316 StGB). Schnittstelle Plugin kanzlei-all

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-verkehrsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [strassenverkehrsrecht-stvo](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/strassenverkehrsrecht-stvo)

StVO-/Straßenverkehrsrecht-Plugin für Verkehrsregeln, Zeichen, Anordnungen, Ausnahmegenehmigungen, Fahrerlaubnis, Bußgeld-Schnittstellen und Behördenpraxis.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/strassenverkehrsrecht-stvo/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Versicherungsrecht

### [fachanwalt-versicherungsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-versicherungsrecht)

Plugin Fachanwalt für Versicherungsrecht. VVG VAG Berufsunfähigkeit private Krankenversicherung Lebens- und Rentenversicherung Sachversicherung Haftpflicht D-und-O. Schnittstelle Plugin kanzlei-allgem

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-versicherungsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [versicherungsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/versicherungsrecht)

Großes Versicherungsrecht-Plugin für VVG, VAG, europäische Versicherungsaufsicht, Lebensversicherung, BU, PKV, Rechtsschutz, Kreditversicherung, D&O, Cyber, Sach- und Haftpflichtdeckung.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/versicherungsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Fachanwalt fuer Verwaltungsrecht

### [beamtenrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/beamtenrecht)

Beamtenrecht für Bund, Länder und Richterdienst: Status, Laufbahn, Besoldung, Versorgung, Konkurrentenstreit, Disziplinarrecht, Dienstunfähigkeit, Richterlaufbahn, Landesrecht und verständliche Mandat

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/beamtenrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [buerokratieversteher-entbuerokratisierer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/buerokratieversteher-entbuerokratisierer)

Allgemeiner Bürokratieversteher und Entbürokratisierer für Laien, Menschen mit Deutsch als Zweitsprache und alle, die Bescheide, Anträge, Vorladungen, Behördenbriefe, Jugendamt-, Schul-, Bau-, Sozial-

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/buerokratieversteher-entbuerokratisierer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [bundesnetzagentur-verfahren](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bundesnetzagentur-verfahren)

Großes Regulierungs-Plugin für anwaltliche Arbeit mit der Bundesnetzagentur in Energie, Telekommunikation, Post, Eisenbahn und Digital Services.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bundesnetzagentur-verfahren/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [bundeswehrrecht-wehrrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bundeswehrrecht-wehrrecht)

Super-Plugin für Soldatenrecht, Wehrbeschwerde, Disziplinarrecht, Wehrpflicht, Reservisten, Versorgung und Bundeswehrverwaltung.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/bundeswehrrecht-wehrrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [energierecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/energierecht)

Freistehendes Energierecht-Plugin für Stadtwerke, Versorger, Wärme, Netze, Vertrieb, Industrie, EEG, KWKG, Verfahren, Transaktionen und Projektfinanzierung.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/energierecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [europarecht-kompass](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/europarecht-kompass)

Freistehendes Europarecht-Plugin gegen deutsche Denkfehler: Vorrang, unmittelbare Wirkung, Richtlinien, Verordnungen, Charta, Grundfreiheiten, Beihilfen, Vorlageverfahren und EU-Drafting.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/europarecht-kompass/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [fachanwalt-verwaltungsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-verwaltungsrecht)

Plugin Fachanwalt für Verwaltungsrecht. VwGO VwVfG. Anfechtungs- und Verpflichtungsklage Eilrechtsschutz § 80 Abs 5 VwGO einstweilige Anordnung Normenkontrolle Polizei- und Ordnungsrecht. Schnittstell

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/fachanwalt-verwaltungsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [haushaltsrecht-bho-bund-laender](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/haushaltsrecht-bho-bund-laender)

Großes Haushaltsrecht-Plugin für BHO, HGrG, Bundeshaushalt, Länderhaushalte, Titelanalyse, Umschichtung, Sondervermögen, Szenarien und Dashboard.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/haushaltsrecht-bho-bund-laender/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [hochschulrecht-laender](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/hochschulrecht-laender)

Hochschulrecht der Länder: Hochschulgesetze, Satzungen, Gremien, Zulassung, Exmatrikulation, Berufung, Drittmittel, Promotion und Aufsicht.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/hochschulrecht-laender/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [informationsfreiheit-presseauskunft](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/informationsfreiheit-presseauskunft)

IFG-, Transparenz-, UIG-, VIG- und Presseauskunfts-Plugin für Bund, Länder und Behörden: Antrag, Kosten, Fristen, Widerspruch, Klage und Tracking.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/informationsfreiheit-presseauskunft/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [kommunalrecht-laender](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kommunalrecht-laender)

Großes Kommunalrecht-Plugin für Gemeinden, Städte, Landkreise, Satzungen, Räte, Bürgerbegehren, Kommunalfinanzen, Aufsicht und Landesrecht.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kommunalrecht-laender/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [lobbyregister-bundestag](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/lobbyregister-bundestag)

Lobbyregister-Bundestag-Superplugin mit 50 geführten Skills für Registrierungspflicht, Ausnahmen, Registereintrag, Regelungsvorhaben, Stellungnahmen, Finanzdaten, Aktualisierung, Verhaltenskodex, Meld

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/lobbyregister-bundestag/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [normenkontrolle-bauleitplanung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/normenkontrolle-bauleitplanung)

Freistehendes Plugin für die Prüfung und Anfechtung von Bebauungsplänen, Flächennutzungsplänen und örtlichen Bauvorschriften nach § 47 VwGO vor BayVGH und OVG. Mandatsperspektive Antragstellervertretu

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/normenkontrolle-bauleitplanung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [normenkontrollrat-nkr](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/normenkontrollrat-nkr)

Plugin fuer den Nationalen Normenkontrollrat (NKR): Pruefung von Referentenentwuerfen Formulierungshilfen und Gesetzentwuerfen auf Erfuellungsaufwand Erforderlichkeit Verhaeltnismaessigkeit One-in-one

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/normenkontrollrat-nkr/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [oeffentliches-wirtschaftsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/oeffentliches-wirtschaftsrecht)

Öffentliches-Wirtschaftsrecht-Plugin für Scheinprivatisierung, ÖPP, Projektfinanzierung, kommunale Unternehmen, Beihilfen, Vergabe und Regulierung.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/oeffentliches-wirtschaftsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [parteienrecht-parteiorganisation](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/parteienrecht-parteiorganisation)

Parteienrechts- und Parteiorganisations-Plugin für formale Parteiarbeit: Parteiengesetz, Satzung, Mitgliederrechte, Parteitage, Kreis- und Bezirksversammlungen, Kandidatenaufstellung, Wahlvorschläge,

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/parteienrecht-parteiorganisation/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [produktrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/produktrecht)

Produkthaftung und Produktrecht: Produktsicherheit, GPSR, ProdHaftG, deliktische Produzentenhaftung, Right to Repair, Software-/OTA-Updates, digitale Produktlebenszyklen, Rückruf, Marktüberwachung und

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/produktrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [pruefungsrecht-hochschule](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/pruefungsrecht-hochschule)

Hochschulprüfungsrecht: Prüfungsordnung, Bewertungsspielraum, Akteneinsicht, Krankheit, Nachteilsausgleich, Täuschung, KI, Drittversuch und Eilrechtsschutz.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/pruefungsrecht-hochschule/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [regulatorisches-recht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/regulatorisches-recht)

Aufsichtsrecht – KWG, ZAG, WpHG, GwG, EnWG, TKG, HeilMWerbG, Umsatzsteuer-Voranmeldung, Inkasso/RDG, Regulator-Feeds, Wochendigest.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/regulatorisches-recht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [schulrecht-laender](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/schulrecht-laender)

Schulrecht der Länder: Schulpflicht, Aufnahme, Inklusion, Noten, Versetzung, Ordnungsmaßnahmen, Datenschutz, Elternrechte und Eilrechtsschutz.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/schulrecht-laender/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [strassenrecht-infrastruktur](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/strassenrecht-infrastruktur)

Straßenrecht-Plugin für Bundesfernstraßen, Landesstraßen, Gemeindestraßen, Widmung, Planfeststellung, Sondernutzung, Baulast und Erhaltung.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/strassenrecht-infrastruktur/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [umweltrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/umweltrecht)

Freistehendes Umweltrecht-Plugin für BImSchG, TEHG, Abfall, Wasser, Boden, Naturschutz, UIG, Verfahren, Bußgeld, Umwelt-Due-Diligence, Klimaklagen UmwRG, Lieferkettensorgfalt LkSG/CSDDD und ESG-Greenw

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/umweltrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [umweltschutzverband-verbandsklage](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/umweltschutzverband-verbandsklage)

Plugin für Umweltverbände: UmwRG, Aarhus, UIG, UVP, BImSchG, Planfeststellung, § 47 VwGO, Naturschutz, Klima, Verbandsklage und Eilrechtsschutz.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/umweltschutzverband-verbandsklage/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [verbraucher-rechtsstaat-alltag](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verbraucher-rechtsstaat-alltag)

Kleines, hilfreiches Plugin für Verbraucher: E-Commerce, Kaufrecht, Reparaturen, kleine Dienstleistungen, Rechnungen, Inkasso, Plattformen, Behördenbriefe und Gerichtspost verständlich einordnen und v

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verbraucher-rechtsstaat-alltag/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [verbraucherschutzrecht-pruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verbraucherschutzrecht-pruefer)

Großer Verbraucherschutz-Prüfer für BGB, EGBGB, UWG, UKlaG, VSBG, E-Commerce, digitale Produkte, Reise, Finanzen, Energie, Gesundheit und Alltag.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verbraucherschutzrecht-pruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [verbraucherschutzverband-durchsetzung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verbraucherschutzverband-durchsetzung)

Plugin für Verbraucherverbände: VDuG, UKlaG, UWG, Abhilfeklage, Musterfeststellung, Unterlassung, Register, Finanzierung, Vergleich und Kampagnenakte.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verbraucherschutzverband-durchsetzung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [verfassungsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verfassungsrecht)

Deutsches Verfassungsrecht unter dem Grundgesetz aus Sicht einer Spezialkanzlei. Rechtsprechungsgetrieben mit Live-Recherche auf bundesverfassungsgericht.de. Acht Skills für Gesetzgebungskompetenz for

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verfassungsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [verkehr-infrastrukturrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verkehr-infrastrukturrecht)

Freistehendes Verkehrs- und Infrastrukturrecht-Plugin für Verkehrsplanung, Planfeststellung, Straßenbahn, Ladeinfrastruktur, Parkraum und Verkehrswende.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/verkehr-infrastrukturrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [versammlungsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/versammlungsrecht)

Praxisplugin für Versammlungsrecht und Versammlungsfreiheit: Anzeige unter freiem Himmel, Landesrecht, Behörde, Fristen, Spontan- und Eilversammlung, Ordner, Kooperationsgespräch, Auflagen, Verbot, Ei

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/versammlungsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [wahlkampfrecht-praxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/wahlkampfrecht-praxis)

Wahlkampfrecht und Wahlkampfpraxis fuer Parteien, Kandidierende und Kampagnenteams: Strategie, Plakatierung, Social Media, Datenschutz, politische Werbung, Parteienfinanzierung, Desinformation, Verans

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/wahlkampfrecht-praxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Steuerrecht (FA Steuerrecht)

### [dfg-foerderantrag](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/dfg-foerderantrag)

DFG-Förderantragssteller für Sachbeihilfe, adaptive Anfänger-/Profi-Führung, kleine schnelle Anträge, große Koselleck-Strategien, elan-Formalia, Finanzplan, Reviewer-Red-Team, Forschungsdaten, KI-/Eth

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/dfg-foerderantrag/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [forschungszulage-antragstellung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/forschungszulage-antragstellung)

Forschungszulage-Antragstellung nach FZulG: adaptiver Fördercheck, BSFZ-Portaltexte mit Zeichenbudgets, Finanzamt-Antrag, FuE-Abgrenzung, Bemessungsgrundlage 2026, Auszahlung, Verlust-/Insolvenzlage,

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/forschungszulage-antragstellung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [steuerrecht-anwalt-und-berater](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/steuerrecht-anwalt-und-berater)

Steuerrecht für Anwalt (anw- FAO § 9) und Steuerberater (stb-): Einspruch Klage FG Aussenprüfung Selbstanzeige, Grundsteuer, Grunderwerbsteuer, Share Deals, Signing Closing, BWA SuSa Lohnbuchhaltung J

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/steuerrecht-anwalt-und-berater/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Prozess- und Verfahrenspraxis

### [aktenauszug-gerichtsverfahren](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/aktenauszug-gerichtsverfahren)

Strukturierter Aktenauszug für deutsche Gerichtsverfahren: Verfahrensidentifikation Einleitungssatz Verfahrenszusammenfassung Sachverhaltschronologie Verfahrensgeschichte tabellarische Gegenüberstellu

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/aktenauszug-gerichtsverfahren/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [anlagen-zu-schriftsaetzen](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/anlagen-zu-schriftsaetzen)

Anlagenmanagement fuer gerichtliche Schriftsaetze: sortiert chaotische Mandantenordner, E-Mails, Scans, Tabellen und Vorversionen zu beA-tauglichen K/B/AST/AG-Anlagen mit Verzeichnis, Konvolutdeckblae

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/anlagen-zu-schriftsaetzen/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [berichtspflichten-erlediger](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berichtspflichten-erlediger)

Berichtspflichten-Erlediger für mittelständische Unternehmen: amtliche Statistik, Portale, Umwelt-, Produkt-, Steuer-, Sozial-, Lieferketten-, Datenschutz- und Aufsichtsmeldungen mit Fristenboard, Dat

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berichtspflichten-erlediger/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [forderungsmanagement-klagewerkstatt](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/forderungsmanagement-klagewerkstatt)

Klagewerkstatt für Forderungsmanagement mit Zuständigkeitsprüfung, Mahnvorlauf, Inkasso-Zahlungsklage und Anspruchs-Gatekeeper: Nur klare, fällige und belegte Forderungen werden zur Klage freigegeben.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/forderungsmanagement-klagewerkstatt/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [jveg-kostenpruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/jveg-kostenpruefer)

Freistehender JVEG-Kostenprüfer für Zeugenentschädigung, Vorschuss, Fahrtkosten, Übernachtung, Verdienstausfall, Sachverständigen- und Dolmetscherkosten, Fristen, Festsetzung, Beschwerde und belegfest

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/jveg-kostenpruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [memorandums-ersteller](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/memorandums-ersteller)

Wandelt Mandantenunterlagen in ein juristisches Memorandum mit Vier-Teile-Gliederung — Sachverhalt mit Quellenreferenz; Ein-Satz-Fragen; Ein-Satz-Antworten; rechtliche Ausführungen mit Pinpoint-Zitier

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/memorandums-ersteller/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [prozessrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/prozessrecht)

Prozessrechtliche Skills für Mandate, Fristen, Mahnbescheid, Eilverfahren, Vollstreckung und Schriftsätze.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/prozessrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [selbstvertreter-amtsgericht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/selbstvertreter-amtsgericht)

Selbstvertretung vor dem Amtsgericht ohne Anwalt: Anfänger-Workflow, Fristen, Zuständigkeit, §23 GVG/§511 ZPO-Grenzen, Klage/Erwiderung/Replik, Beweise, PKH, Termin, Sanity-Check, Rechtsprechungschat,

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/selbstvertreter-amtsgericht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [tabellenreview-3d](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/tabellenreview-3d)

3D-Tabellenreview als Wuerfel: Spaltenprompts pro Datenpunkt x Zeilenprompts pro Dokument x Arbeitsblatt-Perspektiven (Recht / Steuer / Wirtschaft) gestapelt. Massenprüfung Vertragsstapel M&A-DD Immob

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/tabellenreview-3d/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [urteilsbauer-relationsmacher](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/urteilsbauer-relationsmacher)

Urteils- und Beschluss-Werkstatt für Amts- Land- und Familienrichter sowie Rechtspfleger. Aktenintake Relation Beweiswürdigung mit Richter-Input Tatbestandsmerkmale Tenor Tatbestand Entscheidungsgründ

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/urteilsbauer-relationsmacher/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [zitierweise-deutsches-recht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/zitierweise-deutsches-recht)

Deutsche juristische Hauszitierweise v4.0: Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und verifizierbarer Quelle; keine BeckRS-, Kommentar- oder Aufsatz-Blindzitate. Litera

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/zitierweise-deutsches-recht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [zwangsverwaltung-zvg](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/zwangsverwaltung-zvg)

Freistehendes ZVG-Plugin für Zwangsverwaltung und Versteigerung: Beschlagnahme, Besitz, Mieten, Treuhandkonto, Berichte, Verteilung, ZVG-Portal-Recherche, Bieterangebote und Versteigerungsteilnahme.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/zwangsverwaltung-zvg/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [zwangsvollstreckung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/zwangsvollstreckung)

Plugin Zwangsvollstreckung §§ 704 ff. ZPO: Mahn-/Vollstreckungsbescheid, PfÜB Bank/Arbeit, § 802l Kontensuche, Vermögensauskunft, Räumung, § 800 ZPO Notar, § 201 InsO, ZVG, EU-Kontenpfändung VO 655/20

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/zwangsvollstreckung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Anwaltliches Berufsrecht und Kanzleimanagement

### [berufsgerichtliche-verfahren-freie-berufe](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsgerichtliche-verfahren-freie-berufe)

Plugin für anwaltsgerichtliche und berufsgerichtliche Verfahren gegen Anwälte, Patentanwälte, Steuerberater, Wirtschaftsprüfer und Notare: Kammeraufsicht, Rüge, Disziplinarverfahren, Zulassung, Vermög

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsgerichtliche-verfahren-freie-berufe/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [berufsrecht-anwaelte](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsrecht-anwaelte)

Plugin für anwaltliches Berufsrecht: BRAO, BORA, FAO, beA, Kanzleisitz, Werbung, Interessenkollision, Verschwiegenheit, Fremdbesitz, Berufsausübungsgesellschaft, Gebühren, Kammeraufsicht und anwaltsge

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsrecht-anwaelte/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [berufsrecht-notare](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsrecht-notare)

Plugin für Notarrecht: BNotO, BeurkG, DONot, Dienstaufsicht, Urkundspflichten, Neutralität, Verwahrung, Amtspflichten, Vertreter/Verwalter, Disziplinarverfahren und notarielle Berufspraxis.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsrecht-notare/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [berufsrecht-patentanwaelte](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsrecht-patentanwaelte)

Plugin für Patentanwaltsrecht: PAO, Patentanwaltskammer, Vertretungsbefugnis, Schutzrechtsmandate, Verschwiegenheit, Interessenkollision, Werbung, Berufsausübungsgesellschaft und berufsgerichtliche Ri

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsrecht-patentanwaelte/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [berufsrecht-steuerberater](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsrecht-steuerberater)

Plugin für Steuerberaterrecht: StBerG, BOStB, Steuerberaterkammer, Vorbehaltsaufgaben, Werbung, Verschwiegenheit, Gebühren, Geldwäsche, Berufsgericht, Berufsausübungsgesellschaft und Haftungspräventio

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsrecht-steuerberater/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [berufsrecht-wirtschaftspruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsrecht-wirtschaftspruefer)

Plugin für Wirtschaftsprüferrecht: WPO, Berufssatzung, WPK, APAS, Unabhängigkeit, Qualitätskontrolle, Abschlussprüfung, Bestätigungsvermerk, PIE, Berufsaufsicht und berufsgerichtliche Risiken.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/berufsrecht-wirtschaftspruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [email-umformulierer-berufsrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/email-umformulierer-berufsrecht)

Formuliert unfreundliche, emotionale oder unsachliche E-Mails in hoefliche, sachliche und berufsrechtskonform formulierte Texte um. Fokus auf BRAO/BORA-Konformität, mit Varianten für Steuerberater, No

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/email-umformulierer-berufsrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [hinweisgeberschutz-compliance](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/hinweisgeberschutz-compliance)

Hinweisgeberschutzgesetz in der Praxis: interne/externe Meldestelle, NDA-Konflikte, Repressalien, Untersuchungen, Datenschutz und Governance.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/hinweisgeberschutz-compliance/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [kanzlei-allgemein](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kanzlei-allgemein)

Kanzlei-Allgemein-Plugin (fusioniert mit Cowork): edles Kommandocenter Mandatsannahme/GwG Klage/Replik Vertrag Rechtsprechung Handelsregister beA-Journal Rechnung UStVA Fristenbuch Timesheet RVG Versa

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kanzlei-allgemein/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [kanzlei-builder-hub](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kanzlei-builder-hub)

Findet, prüft und installiert Community-Skills mit Security-Review-Gate vor dem Deployment in die Kanzleiumgebung.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kanzlei-builder-hub/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [kanzlei-management](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kanzlei-management)

Mega-Plugin für Kanzlei-Management: Managing Partner, Management Committee, Cashflow, Pricing, UBT, FTE, Utilization, WIP, Associates, Partnerkreis und Dashboards.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kanzlei-management/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [kanzlei-mandant-lifecycle](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kanzlei-mandant-lifecycle)

Lifecycle-Plugin für Kanzlei, Mandant und Rechtsabteilung: Mandatsstart, OCG, Budget, Dashboard, Rechnung, Litigation, Erwartungsmanagement und Relationship-Governance.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kanzlei-mandant-lifecycle/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [mandantenanfragen-assistent](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/mandantenanfragen-assistent)

Assistent für Anwaltskanzleien zur Erstantwort auf Mandantenanfragen per E-Mail: dankt foermlich übernimmt die Anrede aus der eingehenden E-Mail nennt die telefonische Terminvergabe bittet um Sachverh

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/mandantenanfragen-assistent/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [notariat-alltag](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/notariat-alltag)

Alltagsplugin für Notariat, Notariatsmitarbeitende und Notarinnen/Notare: Beurkundung, Vollzug, Register, Grundbuch, Geldwäsche, Kosten, Fristen und Mandantenkommunikation.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/notariat-alltag/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [rechtsberatungsstelle](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/rechtsberatungsstelle)

Pro-Bono- und Rechtsberatungsstellen (RDG-konform): Mandantenintake, Fristenkontrolle, Übergabe am Semesterende, mandantenfreundliche Briefe.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/rechtsberatungsstelle/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [solo-selbststaendige-praxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/solo-selbststaendige-praxis)

Praxisplugin für Solo-Selbstständige in Deutschland: Start, Anmeldung, Steuern, Verträge, Rechnungen, Datenschutz, Statusfeststellung, KSK, Versicherungen, Zahlungsausfall, Krise, Wachstum und Alltag

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/solo-selbststaendige-praxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Sprache, Lehre und Hilfsskills

### [einfache-leichte-sprache-jura](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/einfache-leichte-sprache-jura)

Juristische Texte in Einfache Sprache oder Leichte Sprache übertragen: experimentelle Standard-Annäherung, Zielgruppe klären, Rechtsinhalt sichern und Qualitätsgate nutzen.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/einfache-leichte-sprache-jura/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [hausarbeitenmacher](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/hausarbeitenmacher)

Didaktisches Plugin für juristische Hausarbeiten und Seminararbeiten. Führt sokratisch durch Zivilrecht öffentliches Recht Strafrecht mit Ausfluegen in Europarecht und Rechtstheorie. Adressaten-Strate

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/hausarbeitenmacher/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [jurastudium](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/jurastudium)

Studium und Referendariat – Prüfungsgespräch nach AG-Tradition, Subsumtionslehre, Methodenlehre (Zivilrecht, Strafrecht, Öffentliches Recht), Rechtsgeschichte, Lernstrategien, Lösungsschemata, Gutacht

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/jurastudium/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [juristische-sprache-deutsch-als-zweitsprache](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/juristische-sprache-deutsch-als-zweitsprache)

Plugin fuer Menschen im deutschen Recht mit anderer Herkunftssprache: einfache Erklaerungen, Juristendeutsch, Bescheide, Schriftsaetze, Grammatik, Fristen und Verfahrenslogik.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/juristische-sprache-deutsch-als-zweitsprache/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [legistik-werkstatt](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/legistik-werkstatt)

Legistik-Werkstatt für Ministerien, Bundestag, Fraktionen/Opposition, Länder, Landtage und Normgeber. Baut Referenten- und Kabinettsentwürfe, Vorlagen aus der Mitte, Änderungs-/Entschließungsanträge,

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/legistik-werkstatt/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [meinungspruefer](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/meinungspruefer)

Meinungsprüfer für Äußerungsrecht: Meinung oder Tatsache, Beleidigung, üble Nachrede, Verleumdung, § 188 StGB, Art. 5 GG, Art. 10 EMRK, Art. 11 GRCh, EGMR/EuGH, OLG-Praxis, US-Supreme-Court-Vergleich,

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/meinungspruefer/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [word-legal-ai-plugin-and-skill-for-german-lawyers](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/word-legal-ai-plugin-and-skill-for-german-lawyers)

Word Legal AI for German Lawyers: Kaltstart, Kanzleistil, makrofreies Word-Finish, Verträge, Schriftsätze, Memos, Redlines, Klauselbibliothek, Defensive Drafting, Term Sheet, DE-EN Bilingual, US/UK Le

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/word-legal-ai-plugin-and-skill-for-german-lawyers/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Kartell- und Wettbewerbsrecht

### [kartellrecht-marktabgrenzung-pruefung](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kartellrecht-marktabgrenzung-pruefung)

Globales Kartellrecht/Competition Law: GWB, Art 101/102 AEUV, Fusionskontrolle, BKartA, DG Competition, FTC/DOJ, ICN-Jurisdiktionen, Dawn Raids, Marktabgrenzung, Missbrauch, Private Enforcement.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/kartellrecht-marktabgrenzung-pruefung/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Franchise und Leasing

### [franchiserecht-praxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/franchiserecht-praxis)

Wirtschaftsrechtliches Plugin für Franchise-Systeme: vorvertragliche Aufklärung, Handbuch, Gebühren, Gebietsschutz, Kartellrecht, Kündigung, Expansion, Streit und Insolvenz.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/franchiserecht-praxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [leasingrecht-praxis](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/leasingrecht-praxis)

Wirtschaftsrechtliches Praxisplugin für Leasing, Sale-and-lease-back, Equipment Finance, Fahrzeugflotten, IT-Leasing, Insolvenz, Restwert, Sicherheiten und Vertragsgestaltung.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/leasingrecht-praxis/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Vereinsrecht und Genossenschaften

### [vereinsrecht-vereinsmanager](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/vereinsrecht-vereinsmanager)

Vereinsrechts- und Vereinsmanagement-Plugin für eingetragene und nicht eingetragene Vereine: Gründung, Satzung, Mitgliederversammlung, Vorstand, Protokolle, Beschlüsse, Gemeinnützigkeit, Register, Haf

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/vereinsrecht-vereinsmanager/skills) — laden, kopieren, in beliebiges Tool einfuegen.

## Rechtsgeschichte und Vermoegensrecht der Wiedervereinigung

### [deutsche-rechtsgeschichte](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/deutsche-rechtsgeschichte)

Mega-Plugin zur deutschen Rechtsgeschichte: Epochen, Quellenkritik, Rezeption, Reichsrecht, BGB, Weimar, NS-Unrecht, DDR/BRD und rechtsgeschichtliche Argumentation.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/deutsche-rechtsgeschichte/skills) — laden, kopieren, in beliebiges Tool einfuegen.

### [einigungsvertrag-vermoegensrecht](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/einigungsvertrag-vermoegensrecht)

Einigungsvertrag-Plugin für DDR/BRD-Übergangsrecht, Volksvermögen, Parteivermögen, Treuhand, Bodenreform, Mauergrundstücke, VermG und Restitution.

**Skills:** [skills/](https://github.com/Klotzkette/claude-fuer-deutsches-recht/tree/main/einigungsvertrag-vermoegensrecht/skills) — laden, kopieren, in beliebiges Tool einfuegen.

---

## Hinweis fuer Skill-Autoren und KI-Assistenten

Wenn du neue Skills erzeugst (egal ob als Perplexity Computer, Claude Code oder Codex): pruefe bitte, ob der Skill sich als alleinstehender Mega-Prompt eignet — also nicht primaer ein Kaltstart-Skill, kein generischer Router und kein reiner Workflow-Anker ist, sondern ein eigenstaendig nutzbarer, inhaltlich substanzieller Prompt mit klarer Struktur. Solche Skills tragen in diese Promptliste hier ein und werden nach Fachanwaltschaft einsortiert. Aktualisierungen an Plugin-Listen, neue Plugin-Namen und Re-Klassifikationen wandern ebenfalls in diese Datei.

**Pflegehinweis:** Diese Datei wird bei jedem groesseren Versionsbump (Minor und Major) durchgesehen und an den aktuellen Plugin-Stand angepasst.

