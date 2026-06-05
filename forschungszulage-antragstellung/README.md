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
| `abgrenzung` | Nutze dies bei Abgrenzung: Compliance-Dokumentation und Aktenvermerk: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `abgrenzung-adaptiver-antrag` | Nutze dies bei Abgrenzung Compliance Dokumentation Und Akte, Adaptiver Dokumentenmatrix Und Lueckenliste, Antrag Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `adaptiver` | Nutze dies bei Adaptiver: Dokumentenmatrix, Lückenliste und Nachforderung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `allgemein` | Adaptiver Einstieg, Mandatsklärung und Routing im Forschungszulage-Plugin. Führt Einsteiger, Technikteams, CFOs und Steuerberater unterschiedlich, klärt Unternehmen, FuE-Vorhaben, Wirtschaftsjahre, BSFZ-Status, Finanzamt-Antrag, Liquidit... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `antrag` | Nutze dies bei Antrag: Zahlen, Schwellenwerte und Berechnung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `antragstellung` | Nutze dies bei Antragstellung: Tatbestandsmerkmale, Beweisfragen und Beleglage: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `antragstellung-auszahlung-beihilfen` | Nutze dies bei Antragstellung Tatbestand Beweis Und Belege, Auszahlung Internationaler Bezug Und Schnittstellen, Beihilfen Beweislast Und Darlegungslast: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `auszahlung` | Nutze dies bei Auszahlung: Internationaler Bezug und Schnittstellen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `beihilfen-beweislast-darlegungslast` | Nutze dies bei Beihilfen: Beweislast, Darlegungslast und Substantiierung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `bemessungsgrundlage-interessen` | Nutze dies bei Bemessungsgrundlage: Mehrparteienkonflikt und Interessenmatrix: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `bemessungsgrundlage-interessen-bsfz` | Nutze dies bei Bemessungsgrundlage Mehrparteien Konflikt Und Interessen, Bsfz Behörden Gericht Und Registerweg, Definition Abschlussprodukt Und Uebergabe: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und li... |
| `bsfz` | Nutze dies bei Bsfz: Behörden-, Gerichts- oder Registerweg: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `chronologie-und-belegmatrix` | Nutze dies bei Chronologie und Belegmatrix: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `definition` | Nutze dies bei Definition: Abschlussprodukt und Übergabe: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einspruch-sonderfall-edge-case` | Nutze dies bei Einspruch: Sonderfall und Edge-Case-Prüfung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `finanzamt-quellenkarte` | Nutze dies zur Quellenprüfung bei Finanzamt Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `foerdercheck` | Nutze dies bei Foerdercheck: Risikoampel, Gegenargumente und Verteidigungslinien: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `forsch-bsfz-pruefung-spezial` | Spezialfall BSFZ-Pruefung und Nachfragen: typische Rueckfragen Bescheinigungsstelle, Stellungnahmefrist, Widerspruch. Pruefraster fuer Antragsteller und Steuerberater. |
| `forsch-konzernverbund-forschung-spezial` | Spezialfall Konzernverbundforschung und verbundene Unternehmen: § 3 Abs. 1 FZulG, Auftragsforschung, KMU-Status, Beihilfen-Kumulation. Pruefraster fuer Konzerntochter und Forschungs-GmbH. |
| `forsch-projektbeschreibung-bauleiter` | Bauleiter Projektbeschreibung FZulG: FuE-Definition Frascati, Neuheit, technologisches Risiko, systematische Vorgehensweise. Pruefraster fuer schluessige Darstellung gegenueber BSFZ. |
| `forsch-stundenaufzeichnung-fz-ablehnung` | Nutze dies bei Forsch Stundenaufzeichnung Leitfaden, Fz Ablehnung Nachbesserung Einspruch, Fz Bemessungsgrundlage 2026: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbe... |
| `forsch-stundenaufzeichnung-leitfaden` | Leitfaden Stundenaufzeichnung FZulG: zuwendungsfaehige Personalkosten, eigene Beschaeftigte, Auftragsforschung, Dokumentationspflichten. Pruefraster fuer Personalcontrolling. |
| `forschungszulage` | Nutze dies bei Forschungszulage: Erstprüfung, Rollenklärung und Mandatsziel: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `forschungszulage-insolvenzlage-red` | Nutze dies bei Forschungszulage Erstpruefung Und Mandatsziel, Insolvenzlage Red Team Und Qualitaetskontrolle, Portaltexte Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad u... |
| `fristen-und-risikoampel` | Nutze dies bei Fristen- und Risikoampel: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `fz-ablehnung-nachbesserung-einspruch` | Ablehnung oder Nachforderung bei Forschungszulage strukturiert bearbeiten: BSFZ-Rückfrage, negative Bescheinigung, BSFZ-Widerspruch, Finanzamt-Kürzung, Einspruch nach AO, neue Tatsachen, Beleg- und Textreparatur, Klage Finanzgericht als... |
| `fz-auftragsforschung-vertragsgestaltung` | Auftragsforschung im Sinne § 3 Abs. 4 FZulG: Auftraggeber-Auftragnehmer-Konstellation, Pflichten des Auftraggebers (Risikotragung, Verwertung), foerderfaehige Quote 60 oder 70 Prozent der vereinbarten Vergueng. Pruefraster Vertragsgestal... |
| `fz-bemessungsgrundlage-2026` | Bemessungsgrundlage Forschungszulage ab 2026 belastbar berechnen: eigene FuE-Personalkosten, Eigenleistung 100 Euro je Stunde, Auftragsforschung 70 Prozent EU/EWR, AfA für Wirtschaftsgüter, 20-Prozent-Gemeinkostenpauschale, 12-Mio-Cap, K... |
| `fz-bescheidung-fz-bsfz-fz-dokumentationspaket` | Nutze dies bei Fz Bescheidung Rechtsmittel, Fz Bsfz Bescheinigung Projektbeschreibung, Fz Dokumentationspaket Betriebspruefung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastba... |
| `fz-bescheidung-rechtsmittel` | Bescheidung Forschungszulage: Bescheinigungsbescheid BSFZ und Festsetzungsbescheid Finanzamt sind zwei getrennte Verwaltungsakte. Rechtsmittelketten: BSFZ-Widerspruch dann Verpflichtungsklage; Finanzamt-Einspruch dann Klage Finanzgericht... |
| `fz-betriebspruefung-fz-finanzamt-fz-historie` | Nutze dies bei Fz Betriebspruefung Strategie, Fz Finanzamt Festsetzung Auszahlung, Fz Historie Und Rechtsgrundlagen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeits... |
| `fz-betriebspruefung-strategie` | Strategie bei Betriebspruefung mit Schwerpunkt Forschungszulage: Vorbereitung, Selbstanzeige bei Fehlern (auch wenn keine Steuerstraftat), Argumentationspakete, Schlussbesprechung. Pruefraster: Stundennachweise, Auftragsforschungsvertrae... |
| `fz-bsfz-bescheinigung-projektbeschreibung` | BSFZ-Antrag und FuE-Projektbeschreibung praxistauglich erstellen: Portaltexte mit Zeichenbudgets, Ausgangsproblem, Stand der Technik, Neuheit, technisches Risiko, systematisches Vorgehen, Arbeitspakete, Prüferlogik, Anti-Floskel-Regeln u... |
| `fz-dokumentationspaket-betriebspruefung` | Dokumentationspaket Forschungszulage prüfungsfest aufbauen: Projektakte mit BSFZ-Antrag und Bescheid, Stundenaufzeichnung je Mitarbeiter Tag Vorhaben, Personalkostenbeleg aus Lohnabrechnung, Auftragsforschungsbeleg mit Vertrag und Rechnu... |
| `fz-finanzamt-festsetzung-auszahlung` | Forschungszulage beim Finanzamt beantragen, festsetzen und auszahlen lassen: ELSTER-Antrag, Vorlage der BSFZ-Bescheinigung, Forschungszulagenbescheid, Anrechnung auf Einkommen- oder Körperschaftsteuer, Auszahlung eines Überschusses, Vora... |
| `fz-foerdercheck-kaltstart` | Schneller Fördercheck Forschungszulage in zehn Minuten: Anspruchsberechtigung, FuE-Kategorie nach Frascati, KMU-Status, Personalkosten-Schwelle, Projektjahre, Kostenarten, BSFZ-/Finanzamt-Status, Kumulierung, Ausschlussrisiken und realis... |
| `fz-fue-abgrenzung-grenzfaelle` | FuE-Definition Grenzfaelle nach Frascati-Manual und FZulG: Neuheit und Unsicherheit, Routinearbeiten gegen Versuch und Irrtum. Beispielszenarien Software-Entwicklung, klinische Studien, Produktoptimierung, Reverse Engineering. Pruefraste... |
| `fz-fue-definition-frascati-abgrenzung` | FuE-Definition für die Forschungszulage praxisnah prüfen: Grundlagenforschung, industrielle Forschung, experimentelle Entwicklung, Frascati-Kriterien (Neuheit, Schöpferisch, Ungewissheit, Systematik, Reproduzierbarkeit), AGVO-Definitione... |
| `fz-fue-fz-fue-fz-konzern` | Nutze dies bei Fz Fue Abgrenzung Grenzfaelle, Fz Fue Definition Frascati Abgrenzung, Fz Konzern Und Organschaft Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arb... |
| `fz-historie-und-rechtsgrundlagen` | Historie und Rechtsgrundlagen der steuerlichen Forschungszulage einfuehrend: FZulG seit 2020, Wachstumschancengesetz 2024 mit Erhoehung auf 10 Mio. Euro Bemessungsgrundlage, KMU-Bonus 5 Mio. Euro. Verhaeltnis zu Projektfoerderung (Bund,... |
| `fz-insolvenz-forsch-konzernverbund` | Nutze dies bei Fz Insolvenz Verlust Liquiditaet, Forsch Konzernverbund Forschung Spezial, Forsch Projektbeschreibung Bauleiter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastba... |
| `fz-insolvenz-verlust-liquiditaet` | Forschungszulage in Verlust-, Krisen- und Insolvenzlagen als Liquiditätshebel nutzen: Auszahlung statt bloßer Steuerersparnis, Vorauszahlungssenkung, Massezugehörigkeit, Antragsbefugnis Geschäftsleitung oder Insolvenzverwaltung, Aufrechn... |
| `fz-konzern-und-organschaft-spezial` | Spezialfall Konzern und Organschaft: Zurechnung von FuE-Aktivitaeten zwischen Mutter und Tochter, Auftragsforschung im Konzernverbund, Verrechnungspreise mit Fremdvergleich, KMU-Status bei Konzernzugehoerigkeit nach KMU-Empfehlung 2003 3... |
| `fz-koordinierung-fz-kumulierung-fz` | Nutze dies bei Fz Koordinierung Zwei Foerderwege, Fz Kumulierung Beihilfen Agvo, Fz Personalkosten Und Stundennachweis: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbe... |
| `fz-koordinierung-zwei-foerderwege` | Koordinierung Forschungszulage mit anderen Foerderwegen: keine Doppelfoerderung derselben Kosten, aber Kombination ueber Modulgrenze hinweg (ZIM, IGF, Horizon Europe, Landesfoerderung). Pruefraster fuer Kostentrennung, Buchhaltung, Besch... |
| `fz-kumulierung-beihilfen-agvo` | Kumulierung Forschungszulage mit anderen Förderungen und Beihilfen sauber prüfen: AGVO Art. 25, EU/EWR-Auftragsforschung, ZIM, BMBF-Programme, Landesprogramme, De-minimis-Nähe, Horizon, Doppelförderung, Nachweis- und Abzugslogik. Mit Kum... |
| `fz-personalkosten-und-stundennachweis` | Foerderfaehige Personalkosten der Forschungszulage: Bruttoarbeitslohn plus Arbeitgeberanteile, Stundenpauschale 70 Euro Eigenunternehmer, Auftragsforschung 60 Prozent (KMU 70 Prozent). Stundennachweissystem: tagesgenau, Aufgabenbezug, Pl... |
| `fz-plaedoyer-begruendung-und-verteidigung` | Plädoyer, Begründung und Verteidigung der Forschungszulage: macht aus Technik, Belegen, Kosten und Behördenkritik einen überzeugenden Vortrag für BSFZ, Finanzamt, Einspruch, Mandantenmemo oder Geschäftsführungsentscheidung. Mit Argumenta... |
| `fz-plaedoyer-fz-roadmap-fz-start` | Nutze dies bei Fz Plaedoyer Begruendung Und Verteidigung, Fz Roadmap Mehrjahresantrag, Fz Start Up Und Personengesellschaft: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `fz-roadmap-mehrjahresantrag` | Mehrjahresstrategie Forschungszulage: BSFZ-Bescheinigung für mehrjährige Vorhaben, jährliche Aktualisierung der Stundenaufzeichnung und Projektakte, Folgeanträge knapp halten, Roadmap-Pflege, Liquiditätsplanung über Wirtschaftsjahre, rüc... |
| `fz-start-up-und-personengesellschaft` | Start-up- und Personengesellschafts-Konstellation Forschungszulage: GmbH und Co KG, atypisch stille Beteiligung, Mitunternehmerschaft, Verluste in Anfangsjahren mit Zulage als Liquiditaetshebel. Beispielrechnungen, typische Pruefpunkte.... |
| `fzulg` | Nutze dies bei FZulG: Fristen, Form, Zuständigkeit und Rechtsweg: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `fzulg-02` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Fzulg Fristen Form Und Zustaendigkeit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `insolvenzlage-fehlerkatalog` | Nutze dies als Fehlerbremse bei Insolvenzlage Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `mandantenentscheidung` | Nutze dies bei Dokumentation: Mandantenkommunikation und Entscheidungsvorlage: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `mandantenentscheidung-einspruch-sonderfall` | Nutze dies bei Dokumentation Mandantenentscheidung, Einspruch Sonderfall Und Edge Case, Foerdercheck Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bel... |
| `mandantenkommunikation` | Nutze dies bei Mandantenkommunikation: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `mehrjahresroadmap-fristennotiz-fz` | Nutze dies bei Mehrjahresroadmap Fristennotiz Und Naechster Schritt, Fz Auftragsforschung Vertragsgestaltung, Forsch Bsfz Prüfung Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächst... |
| `mehrjahresroadmap-fristennotiz-naechster` | Nutze dies bei Mehrjahresroadmap: Fristennotiz und nächster Schritt: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `portaltexte` | Nutze dies bei Portaltexte: Schriftsatz-, Brief-, Memo- und Plädoyer-Bausteine: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `redteam-qualitygate` | Nutze dies als Fehlerbremse bei Red-Team Qualitygate: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `verlust` | Nutze dies bei Verlust: Formular, Portal und Einreichungslogik: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `verlust-zeichenbudgets` | Nutze dies bei Verlust Formular Portal Und Einreichung, Zeichenbudgets Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `zeichenbudgets` | Nutze dies bei Zeichenbudgets: Verhandlung, Vergleich und Eskalation: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
