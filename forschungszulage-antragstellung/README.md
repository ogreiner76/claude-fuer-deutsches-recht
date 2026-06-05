# Forschungszulage-Antragstellung

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`forschungszulage-antragstellung`) | [`forschungszulage-antragstellung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/forschungszulage-antragstellung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Forschungszulage Riedblick Sensorik GmbH** (`forschungszulage-sensorik-startup-taunus`) | [Gesamt-PDF lesen](../testakten/forschungszulage-sensorik-startup-taunus/gesamt-pdf/forschungszulage-sensorik-startup-taunus_gesamt.pdf) | [`testakte-forschungszulage-sensorik-startup-taunus.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-forschungszulage-sensorik-startup-taunus.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Plugin für die steuerliche Forschungsförderung nach dem Forschungszulagengesetz: Fördercheck, BSFZ-Bescheinigung, Projektbeschreibung, FuE-Abgrenzung, Bemessungsgrundlage, Finanzamt-Antrag, Auszahlung, Verlust-/Krisenlage, Dokumentation für Außenprüfung, Kumulierung und Nachbesserung.

Das Plugin ist für Unternehmen, Start-ups, Mittelstand, Steuerberaterinnen, Rechtsanwälte, CFOs und Produkt-/Entwicklungsteams gebaut. Es übersetzt technische Entwicklung in die Sprache, die BSFZ und Finanzamt brauchen: Neuheit, Risiko, systematisches Vorgehen, förderfähige Aufwendungen und saubere Belege. Es kann bewusst zwei Geschwindigkeiten: geführter Modus für Einsteiger und harter Ampel-/Cashflow-Modus für Profis.

## Quellen-Gate

Vor jeder belastbaren Ausgabe live prüfen:

- Forschungszulagengesetz auf `gesetze-im-internet.de`, insbesondere §§ 1 bis 7 und § 10 FZulG.
- BSFZ-Antragsverfahren: zweistufig, erst FuE-Bescheinigung bei der BSFZ, dann Antrag beim Finanzamt.
- BMF-Forschungszulage und BMF-Schreiben vom 07.02.2023, soweit noch nicht durch ein neues finales Schreiben ersetzt.
- Änderungen ab 2026: Bemessungsgrundlagenhöchstbetrag 12 Mio. Euro, 20-%-Pauschale für Gemein- und Betriebskosten bei nach dem 31.12.2025 begonnenen Vorhaben, Eigenleistung 100 Euro pro Stunde bis max. 40 Stunden/Woche.

## Skill-Matrix

| Skill | Wofür? |
| --- | --- |
| `allgemein` | Einstieg, Triage, Förderroute und Projektaufnahme |
| `fz-foerdercheck-kaltstart` | Anspruchsberechtigung, Projektart, Jahre, Risiken, Sofortpotenzial |
| `fz-bsfz-bescheinigung-projektbeschreibung` | BSFZ-Antrag, Vorhabenbeschreibung, technische Neuheit, Risiko |
| `fz-plaedoyer-begruendung-und-verteidigung` | Plädoyer, Begründung und Verteidigung gegenüber BSFZ, Finanzamt, Geschäftsführung, Insolvenzverwaltung oder Einspruchsstelle |
| `fz-fue-definition-frascati-abgrenzung` | Grundlagenforschung, industrielle Forschung, experimentelle Entwicklung |
| `fz-bemessungsgrundlage-2026` | Personal, Eigenleistung, Auftragsforschung, Wirtschaftsgüter, 12-Mio.-Grenze |
| `fz-finanzamt-festsetzung-auszahlung` | Antrag beim Finanzamt, Anrechnung, Auszahlung, Vorauszahlungssenkung |
| `fz-insolvenz-verlust-liquiditaet` | Krise, Verlustjahr, Insolvenz, Forderungs-/Masseblick, Liquidität |
| `fz-dokumentationspaket-betriebspruefung` | Stundenzettel, Projektakte, Kostenbelege, Prüferpaket |
| `fz-kumulierung-beihilfen-agvo` | Doppelförderung, AGVO, andere Zuschüsse, EU/EWR-Auftragsforschung |
| `fz-ablehnung-nachbesserung-einspruch` | BSFZ-Nachforderung, Ablehnung, Finanzamt-Einspruch, Reparatur |
| `fz-roadmap-mehrjahresantrag` | Mehrjahresstrategie, rückwirkende Jahre, Jahreswechsel, Portfolio |

## Typische Startpunkte

| Situation | Start |
| --- | --- |
| "Wir wissen nicht, ob unser Vorhaben FuE ist" | `allgemein` → `fz-foerdercheck-kaltstart` |
| "Wir müssen den BSFZ-Antrag schreiben" | `fz-fue-definition-frascati-abgrenzung` → `fz-bsfz-bescheinigung-projektbeschreibung` |
| "Wir brauchen ein überzeugendes Plädoyer / eine Begründung" | `fz-plaedoyer-begruendung-und-verteidigung` |
| "Wir wollen wissen, wie viel Geld kommt" | `fz-bemessungsgrundlage-2026` → `fz-finanzamt-festsetzung-auszahlung` |
| "Wir sind im Verlust / in der Krise" | `fz-insolvenz-verlust-liquiditaet` |
| "BSFZ fragt nach oder lehnt ab" | `fz-ablehnung-nachbesserung-einspruch` |

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 71 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `abgrenzung` | Nutze dies, wenn Abgrenzung: Compliance-Dokumentation und Aktenvermerk im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `abgrenzung-adaptiver-antrag` | Nutze dies, wenn Spezial Abgrenzung Compliance Dokumentation Und Akte, Spezial Adaptiver Dokumentenmatrix Und Lueckenliste, Spezial Antrag Zahlen Schwellen Und Berechnung im Plugin Forschungszulage Antragstellung konkret bearbeitet werde... |
| `adaptiver` | Nutze dies, wenn Adaptiver: Dokumentenmatrix, Lückenliste und Nachforderung im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `allgemein` | Adaptiver Einstieg, Mandatsklärung und Routing im Forschungszulage-Plugin. Führt Einsteiger, Technikteams, CFOs und Steuerberater unterschiedlich, klärt Unternehmen, FuE-Vorhaben, Wirtschaftsjahre, BSFZ-Status, Finanzamt-Antrag, Liquidit... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix,... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Forschungszulage Antragstellung.; Welche Unterlagen brauchen Sie?; Welcher Spezial... |
| `antrag` | Nutze dies, wenn Antrag: Zahlen, Schwellenwerte und Berechnung im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Antrag: Zahlen, Schwellenwerte und Berechnung prüfen.; Erstelle eine Arbeitsfassung... |
| `antragstellung` | Nutze dies, wenn Antragstellung: Tatbestandsmerkmale, Beweisfragen und Beleglage im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Antragstellung: Tatbestandsmerkmale, Beweisfragen und Beleglage pr... |
| `antragstellung-auszahlung-beihilfen` | Nutze dies, wenn Spezial Antragstellung Tatbestand Beweis Und Belege, Spezial Auszahlung Internationaler Bezug Und Schnittstellen, Spezial Beihilfen Beweislast Und Darlegungslast im Plugin Forschungszulage Antragstellung konkret bearbeit... |
| `auszahlung` | Nutze dies, wenn Auszahlung: Internationaler Bezug und Schnittstellen im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Auszahlung: Internationaler Bezug und Schnittstellen prüfen.; Erstelle eine A... |
| `beihilfen-beweislast-darlegungslast` | Nutze dies, wenn Beihilfen: Beweislast, Darlegungslast und Substantiierung im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Beihilfen: Beweislast, Darlegungslast und Substantiierung prüfen.; Erste... |
| `bemessungsgrundlage-interessen` | Nutze dies, wenn Bemessungsgrundlage: Mehrparteienkonflikt und Interessenmatrix im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Bemessungsgrundlage: Mehrparteienkonflikt und Interessenmatrix prüf... |
| `bemessungsgrundlage-interessen-bsfz` | Nutze dies, wenn Spezial Bemessungsgrundlage Mehrparteien Konflikt Und Interessen, Spezial Bsfz Behörden Gericht Und Registerweg, Spezial Definition Abschlussprodukt Und Übergabe im Plugin Forschungszulage Antragstellung konkret bearbeit... |
| `bsfz` | Nutze dies, wenn Bsfz: Behörden-, Gerichts- oder Registerweg im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Bsfz: Behörden-, Gerichts- oder Registerweg prüfen.; Erstelle eine Arbeitsfassung zu B... |
| `chronologie-und-belegmatrix` | Nutze dies, wenn Chronologie und Belegmatrix im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Chronologie und Belegmatrix prüfen.; Erstelle eine Arbeitsfassung zu Chronologie und Belegmatrix.; Wel... |
| `definition` | Nutze dies, wenn Definition: Abschlussprodukt und Übergabe im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Definition: Abschlussprodukt und Übergabe prüfen.; Erstelle eine Arbeitsfassung zu Defin... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einspruch-sonderfall-edge-case` | Nutze dies, wenn Einspruch: Sonderfall und Edge-Case-Prüfung im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Einspruch: Sonderfall und Edge-Case-Prüfung prüfen.; Erstelle eine Arbeitsfassung zu E... |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Forschungszulage Antragstellung.; Welche Unterlagen brauchen Sie?; Welcher Spez... |
| `finanzamt-quellenkarte` | Nutze dies, wenn Finanzamt Quellenkarte im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `foerdercheck` | Nutze dies, wenn Foerdercheck: Risikoampel, Gegenargumente und Verteidigungslinien im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Foerdercheck: Risikoampel, Gegenargumente und Verteidigungslinie... |
| `forsch-bsfz-pruefung-spezial` | Spezialfall BSFZ-Pruefung und Nachfragen: typische Rueckfragen Bescheinigungsstelle, Stellungnahmefrist, Widerspruch. Pruefraster fuer Antragsteller und Steuerberater. |
| `forsch-konzernverbund-forschung-spezial` | Spezialfall Konzernverbundforschung und verbundene Unternehmen: § 3 Abs. 1 FZulG, Auftragsforschung, KMU-Status, Beihilfen-Kumulation. Pruefraster fuer Konzerntochter und Forschungs-GmbH. |
| `forsch-projektbeschreibung-bauleiter` | Bauleiter Projektbeschreibung FZulG: FuE-Definition Frascati, Neuheit, technologisches Risiko, systematische Vorgehensweise. Pruefraster fuer schluessige Darstellung gegenueber BSFZ. |
| `forsch-stundenaufzeichnung-fz-ablehnung` | Nutze dies, wenn Forsch Stundenaufzeichnung Leitfaden, Fz Ablehnung Nachbesserung Einspruch, Fz Bemessungsgrundlage 2026 im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Forsch Stundenaufzeichnung... |
| `forsch-stundenaufzeichnung-leitfaden` | Leitfaden Stundenaufzeichnung FZulG: zuwendungsfaehige Personalkosten, eigene Beschaeftigte, Auftragsforschung, Dokumentationspflichten. Pruefraster fuer Personalcontrolling. |
| `forschungszulage` | Nutze dies, wenn Forschungszulage: Erstprüfung, Rollenklärung und Mandatsziel im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Forschungszulage: Erstprüfung, Rollenklärung und Mandatsziel prüfen.;... |
| `forschungszulage-insolvenzlage-red` | Nutze dies, wenn Spezial Forschungszulage Erstpruefung Und Mandatsziel, Spezial Insolvenzlage Red Team Und Qualitaetskontrolle, Spezial Portaltexte Schriftsatz Brief Und Memo Bausteine im Plugin Forschungszulage Antragstellung konkret be... |
| `fristen-und-risikoampel` | Nutze dies, wenn Fristen- und Risikoampel im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Fristen- und Risikoampel prüfen.; Erstelle eine Arbeitsfassung zu Fristen- und Risikoampel.; Welche Norme... |
| `fz-ablehnung-nachbesserung-einspruch` | Ablehnung oder Nachforderung bei Forschungszulage strukturiert bearbeiten: BSFZ-Rückfrage, negative Bescheinigung, BSFZ-Widerspruch, Finanzamt-Kürzung, Einspruch nach AO, neue Tatsachen, Beleg- und Textreparatur, Klage Finanzgericht als... |
| `fz-auftragsforschung-vertragsgestaltung` | Auftragsforschung im Sinne § 3 Abs. 4 FZulG: Auftraggeber-Auftragnehmer-Konstellation, Pflichten des Auftraggebers (Risikotragung, Verwertung), foerderfaehige Quote 60 oder 70 Prozent der vereinbarten Vergueng. Pruefraster Vertragsgestal... |
| `fz-bemessungsgrundlage-2026` | Bemessungsgrundlage Forschungszulage ab 2026 belastbar berechnen: eigene FuE-Personalkosten, Eigenleistung 100 Euro je Stunde, Auftragsforschung 70 Prozent EU/EWR, AfA für Wirtschaftsgüter, 20-Prozent-Gemeinkostenpauschale, 12-Mio-Cap, K... |
| `fz-bescheidung-fz-bsfz-fz-dokumentationspaket` | Nutze dies, wenn Fz Bescheidung Rechtsmittel, Fz Bsfz Bescheinigung Projektbeschreibung, Fz Dokumentationspaket Betriebspruefung im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch... |
| `fz-bescheidung-rechtsmittel` | Bescheidung Forschungszulage: Bescheinigungsbescheid BSFZ und Festsetzungsbescheid Finanzamt sind zwei getrennte Verwaltungsakte. Rechtsmittelketten: BSFZ-Widerspruch dann Verpflichtungsklage; Finanzamt-Einspruch dann Klage Finanzgericht... |
| `fz-betriebspruefung-fz-finanzamt-fz-historie` | Nutze dies, wenn Fz Betriebspruefung Strategie, Fz Finanzamt Festsetzung Auszahlung, Fz Historie Und Rechtsgrundlagen im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Fz Betriebspruefung Strategie... |
| `fz-betriebspruefung-strategie` | Strategie bei Betriebspruefung mit Schwerpunkt Forschungszulage: Vorbereitung, Selbstanzeige bei Fehlern (auch wenn keine Steuerstraftat), Argumentationspakete, Schlussbesprechung. Pruefraster: Stundennachweise, Auftragsforschungsvertrae... |
| `fz-bsfz-bescheinigung-projektbeschreibung` | BSFZ-Antrag und FuE-Projektbeschreibung praxistauglich erstellen: Portaltexte mit Zeichenbudgets, Ausgangsproblem, Stand der Technik, Neuheit, technisches Risiko, systematisches Vorgehen, Arbeitspakete, Prüferlogik, Anti-Floskel-Regeln u... |
| `fz-dokumentationspaket-betriebspruefung` | Dokumentationspaket Forschungszulage prüfungsfest aufbauen: Projektakte mit BSFZ-Antrag und Bescheid, Stundenaufzeichnung je Mitarbeiter Tag Vorhaben, Personalkostenbeleg aus Lohnabrechnung, Auftragsforschungsbeleg mit Vertrag und Rechnu... |
| `fz-finanzamt-festsetzung-auszahlung` | Forschungszulage beim Finanzamt beantragen, festsetzen und auszahlen lassen: ELSTER-Antrag, Vorlage der BSFZ-Bescheinigung, Forschungszulagenbescheid, Anrechnung auf Einkommen- oder Körperschaftsteuer, Auszahlung eines Überschusses, Vora... |
| `fz-foerdercheck-kaltstart` | Schneller Fördercheck Forschungszulage in zehn Minuten: Anspruchsberechtigung, FuE-Kategorie nach Frascati, KMU-Status, Personalkosten-Schwelle, Projektjahre, Kostenarten, BSFZ-/Finanzamt-Status, Kumulierung, Ausschlussrisiken und realis... |
| `fz-fue-abgrenzung-grenzfaelle` | FuE-Definition Grenzfaelle nach Frascati-Manual und FZulG: Neuheit und Unsicherheit, Routinearbeiten gegen Versuch und Irrtum. Beispielszenarien Software-Entwicklung, klinische Studien, Produktoptimierung, Reverse Engineering. Pruefraste... |
| `fz-fue-definition-frascati-abgrenzung` | FuE-Definition für die Forschungszulage praxisnah prüfen: Grundlagenforschung, industrielle Forschung, experimentelle Entwicklung, Frascati-Kriterien (Neuheit, Schöpferisch, Ungewissheit, Systematik, Reproduzierbarkeit), AGVO-Definitione... |
| `fz-fue-fz-fue-fz-konzern` | Nutze dies, wenn Fz Fue Abgrenzung Grenzfaelle, Fz Fue Definition Frascati Abgrenzung, Fz Konzern Und Organschaft Spezial im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Fz Fue Abgrenzung Grenzfa... |
| `fz-historie-und-rechtsgrundlagen` | Historie und Rechtsgrundlagen der steuerlichen Forschungszulage einfuehrend: FZulG seit 2020, Wachstumschancengesetz 2024 mit Erhoehung auf 10 Mio. Euro Bemessungsgrundlage, KMU-Bonus 5 Mio. Euro. Verhaeltnis zu Projektfoerderung (Bund,... |
| `fz-insolvenz-forsch-konzernverbund` | Nutze dies, wenn Fz Insolvenz Verlust Liquiditaet, Forsch Konzernverbund Forschung Spezial, Forsch Projektbeschreibung Bauleiter im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Fz Insolvenz Verlu... |
| `fz-insolvenz-verlust-liquiditaet` | Forschungszulage in Verlust-, Krisen- und Insolvenzlagen als Liquiditätshebel nutzen: Auszahlung statt bloßer Steuerersparnis, Vorauszahlungssenkung, Massezugehörigkeit, Antragsbefugnis Geschäftsleitung oder Insolvenzverwaltung, Aufrechn... |
| `fz-konzern-und-organschaft-spezial` | Spezialfall Konzern und Organschaft: Zurechnung von FuE-Aktivitaeten zwischen Mutter und Tochter, Auftragsforschung im Konzernverbund, Verrechnungspreise mit Fremdvergleich, KMU-Status bei Konzernzugehoerigkeit nach KMU-Empfehlung 2003 3... |
| `fz-koordinierung-fz-kumulierung-fz` | Nutze dies, wenn Fz Koordinierung Zwei Foerderwege, Fz Kumulierung Beihilfen Agvo, Fz Personalkosten Und Stundennachweis im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Fz Koordinierung Zwei Foer... |
| `fz-koordinierung-zwei-foerderwege` | Koordinierung Forschungszulage mit anderen Foerderwegen: keine Doppelfoerderung derselben Kosten, aber Kombination ueber Modulgrenze hinweg (ZIM, IGF, Horizon Europe, Landesfoerderung). Pruefraster fuer Kostentrennung, Buchhaltung, Besch... |
| `fz-kumulierung-beihilfen-agvo` | Kumulierung Forschungszulage mit anderen Förderungen und Beihilfen sauber prüfen: AGVO Art. 25, EU/EWR-Auftragsforschung, ZIM, BMBF-Programme, Landesprogramme, De-minimis-Nähe, Horizon, Doppelförderung, Nachweis- und Abzugslogik. Mit Kum... |
| `fz-personalkosten-und-stundennachweis` | Foerderfaehige Personalkosten der Forschungszulage: Bruttoarbeitslohn plus Arbeitgeberanteile, Stundenpauschale 70 Euro Eigenunternehmer, Auftragsforschung 60 Prozent (KMU 70 Prozent). Stundennachweissystem: tagesgenau, Aufgabenbezug, Pl... |
| `fz-plaedoyer-begruendung-und-verteidigung` | Plädoyer, Begründung und Verteidigung der Forschungszulage: macht aus Technik, Belegen, Kosten und Behördenkritik einen überzeugenden Vortrag für BSFZ, Finanzamt, Einspruch, Mandantenmemo oder Geschäftsführungsentscheidung. Mit Argumenta... |
| `fz-plaedoyer-fz-roadmap-fz-start` | Nutze dies, wenn Fz Plaedoyer Begründung Und Verteidigung, Fz Roadmap Mehrjahresantrag, Fz Start Up Und Personengesellschaft im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Fz Plaedoyer Begründun... |
| `fz-roadmap-mehrjahresantrag` | Mehrjahresstrategie Forschungszulage: BSFZ-Bescheinigung für mehrjährige Vorhaben, jährliche Aktualisierung der Stundenaufzeichnung und Projektakte, Folgeanträge knapp halten, Roadmap-Pflege, Liquiditätsplanung über Wirtschaftsjahre, rüc... |
| `fz-start-up-und-personengesellschaft` | Start-up- und Personengesellschafts-Konstellation Forschungszulage: GmbH und Co KG, atypisch stille Beteiligung, Mitunternehmerschaft, Verluste in Anfangsjahren mit Zulage als Liquiditaetshebel. Beispielrechnungen, typische Pruefpunkte.... |
| `fzulg` | Nutze dies, wenn FZulG: Fristen, Form, Zuständigkeit und Rechtsweg im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte FZulG: Fristen, Form, Zuständigkeit und Rechtsweg prüfen.; Erstelle eine Arbeits... |
| `fzulg-02` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Fzulg Fristen Form Und Zustaendigkeit im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?;... |
| `insolvenzlage-fehlerkatalog` | Nutze dies, wenn Insolvenzlage Fehlerkatalog im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `mandantenentscheidung` | Nutze dies, wenn Dokumentation: Mandantenkommunikation und Entscheidungsvorlage im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `mandantenentscheidung-einspruch-sonderfall` | Nutze dies, wenn Spezial Dokumentation Mandantenentscheidung, Spezial Einspruch Sonderfall Und Edge Case, Spezial Foerdercheck Risikoampel Und Gegenargumente im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslö... |
| `mandantenkommunikation` | Nutze dies, wenn Mandantenkommunikation im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Mandantenkommunikation prüfen.; Erstelle eine Arbeitsfassung zu Mandantenkommunikation.; Welche Normen und... |
| `mehrjahresroadmap-fristennotiz-fz` | Nutze dies, wenn Spezial Mehrjahresroadmap Fristennotiz Und Naechster Schritt, Fz Auftragsforschung Vertragsgestaltung, Forsch Bsfz Prüfung Spezial im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte... |
| `mehrjahresroadmap-fristennotiz-naechster` | Nutze dies, wenn Mehrjahresroadmap: Fristennotiz und nächster Schritt im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Mehrjahresroadmap: Fristennotiz und nächster Schritt prüfen.; Erstelle eine A... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `portaltexte` | Nutze dies, wenn Portaltexte: Schriftsatz-, Brief-, Memo- und Plädoyer-Bausteine im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Portaltexte: Schriftsatz-, Brief-, Memo- und Plädoyer-Bausteine pr... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `redteam-qualitygate` | Nutze dies, wenn Red-Team Qualitygate im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `verlust` | Nutze dies, wenn Verlust: Formular, Portal und Einreichungslogik im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Verlust: Formular, Portal und Einreichungslogik prüfen.; Erstelle eine Arbeitsfass... |
| `verlust-zeichenbudgets` | Nutze dies, wenn Spezial Verlust Formular Portal Und Einreichung, Spezial Zeichenbudgets Verhandlung Vergleich Und Eskalation im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Spezial Verlust Formu... |
| `zeichenbudgets` | Nutze dies, wenn Zeichenbudgets: Verhandlung, Vergleich und Eskalation im Plugin Forschungszulage Antragstellung konkret bearbeitet werden soll. Auslöser: Bitte Zeichenbudgets: Verhandlung, Vergleich und Eskalation prüfen.; Erstelle eine... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
