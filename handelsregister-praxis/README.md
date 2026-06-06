# Handelsregister Praxis

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`handelsregister-praxis`) | [`handelsregister-praxis.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/handelsregister-praxis.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Rabenhof Sensorik GmbH - Registergericht Charlottenburg, HRB 246810 B** (`handelsregister-registergericht-rabenhof-gmbh-2026`) | [Gesamt-PDF lesen](../testakten/handelsregister-registergericht-rabenhof-gmbh-2026/gesamt-pdf/handelsregister-registergericht-rabenhof-gmbh-2026_gesamt.pdf) | [`testakte-handelsregister-registergericht-rabenhof-gmbh-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-handelsregister-registergericht-rabenhof-gmbh-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein Registergerichts-Cockpit für Gesellschaftsrechtler, Notariate, Kanzleien und Rechtsabteilungen. Es ordnet, was eingetragen werden soll, welche Urkunden nötig sind, wer beim Registergericht entscheidet, wie man Beanstandungen beantwortet und wann Beschwerde oder Eilrechtsschutz Sinn ergeben.

## Wofür dieses Plugin da ist

Dieses Plugin ist ein Praxiswerkzeug. Es fragt zuerst die Lage ab, baut dann eine Dokumenten- und Vollzugsmatrix und erzeugt schließlich das konkrete Arbeitsprodukt: Nachreichung, Beanstandungsantwort, Beschwerdegerüst, Mandantenbrief, Checkliste, Fristenlog oder Vertrags-/Urkundenreview. Es ersetzt keine Berufsträgerentscheidung, aber es verhindert, dass ein formeller Nachweis, ein Rang, eine Abteilung-II-Belastung oder eine Registerfolge in der Hektik untergeht.

## Kaltstart

Starte mit dem allgemeinen Skill `handelsregister-allgemeiner-kaltstart`. Lade danach möglichst den aktuellen Register- oder Grundbuchauszug, das Gerichtsschreiben, die Anmeldung/Bewilligung, den Vertragsentwurf und vorhandene Anlagen hoch. Das Plugin sortiert erst, dann prüft es.

## Quellen- und Halluzinationsschutz

- Normen werden als Prüfanker verwendet, nicht als Schmuck.
- Rechtsprechung wird nur ausgegeben, wenn Gericht, Datum, Aktenzeichen und ein frei zugänglicher Fundlink geprüft sind.
- Unsichere Register-/Grundbuchstände werden nicht geraten; das Plugin fordert aktuelle Auszüge oder Nachweise an.

## Amtliche Startquellen

- [HGB §§ 8 ff., § 15](https://www.gesetze-im-internet.de/hgb/)
- [FamFG Registersachen und Beschwerde](https://www.gesetze-im-internet.de/famfg/)
- [GmbHG Anmeldung, Gesellschafterliste, Kapitalmaßnahmen](https://www.gesetze-im-internet.de/gmbhg/)
- [Registerportal der Länder](https://www.handelsregister.de/)
- [Unternehmensregister](https://www.unternehmensregister.de/)

## Typische Ergebnisse

- Prüfmatrix und Vollzugsfahrplan
- Entwurf für Nachreichung oder Antwort an das Gericht/Amt
- Mandantenbrief in normalem Deutsch
- Fristen- und Ranglog
- Beschwerde- oder Eilrechtsschutz-Skizze
- Liste fehlender Originale, Nachweise und Formmängel

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 76 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `amtsloeschung-familienloeschung-registerblatt` | Prüft Löschungsandrohung, Anhörung, Unrichtigkeit, Vermögenslosigkeit, Gegenwehr und Dokumentationsstrategie: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `auslandsurkunden-apostille-legalisation-uebersetzung` | Prüft Apostille, Legalisation, beglaubigte Übersetzung, Existenznachweis und Vertretungsnachweis: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `beanstandung-zwischenverfuegung` | Analysiert Registerbeanstandungen, trennt behebbare Formmängel von Rechtsstreit, formuliert Nachreichung, Bitte um Fristverlängerung oder Beschwerdevorbereitung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbare... |
| `bekanntmachungen-monitoring` | Erstellt Monitoringplan für Bekanntmachungen, Friststart, Einspruchsfenster und Mandantenalerts: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `chronologischer-registerauszug` | Rekonstruiert Registergeschichte, kritische Umschlagpunkte und mögliche Inkonsistenzen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `closing-handelregister-einstweiliger` | Prüft CP/CS, Eintragungsabhängigkeiten, Vollzugsreihenfolge, Escrow, Notarbestätigung und Bring-down: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `einstweiliger-rechtsschutz-registerstreit` | Plant Schutz gegen drohende Eintragung, Verzögerung, Registersperre, Gesellschafterlistenstreit und Vollzugsschäden: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `eintragung-prozessvergleich-registerfolge` | Übersetzt gerichtliche Vergleiche in Beschluss, Anmeldung, Liste, Löschung oder Berichtigung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `erlaubnispflichtige-taetigkeit-famfg` | Prüft KWG, ZAG, GewO, Handwerk, Arbeitnehmerüberlassung und ob das Registergericht Nachweise verlangen kann: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `famfg-beschwerde-registersache` | Prüft Statthaftigkeit, Beschwer, Frist, Form, Abhilfe, Nichtabhilfe und Beschwerdebegründung gegen Registerentscheidungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `fehlerhafte-eintragung-berichtigung` | Prüft Schreibfehler, materiell falsche Eintragung, Amtskorrektur, Löschung, neue Anmeldung und Haftungsnotiz: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `firma-firmenbildung-formwechsel-registercheck` | Prüft Firmenkern, Unterscheidbarkeit, Irreführung, Rechtsformzusatz, IHK-Stellungnahme und Abgrenzung zu Marke/Domain: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `formwechsel-registercheck` | Prüft Formwechselbericht, Beschlüsse, Satzung, neue Firma, Registerwechsel und Identitätskontinuität: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `frist-und-vollzugslog-register` | Baut ein Log für Beanstandungsfristen, Eintragungsdatum, Bekanntmachung, Closing-Abhängigkeit und Mandantenbericht: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `genossenschaft-registerschnittstelle` | Prüft Vorstand, Aufsichtsrat, Prüfung, Satzung und Eintragungslogik bei eG: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gesellschafterlistenstreit-eilstrategie-gmbh` | Ordnet Anspruch, einstweilige Verfügung, Registersperre, materiellen Streit und Kommunikation mit Registergericht/Notar: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gmbh-co-kg-registerdoppelvollzug` | Koordiniert KG-Register, Komplementär-GmbH, Vertretung, Gesellschafterlisten und Firmenidentität: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gmbh-geschaeftsfuehrerbestellung-abberufung` | Prüft Beschluss, Anmeldung, Versicherung, Vertretungsregel, Amtsannahme, Abberufung und Handelsregistervollzug: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gmbh-gesellschafterliste-paragraph-gruendung` | Prüft Liste, Prozentangaben, Veränderungsspalte, Notarzuständigkeit, Legitimationswirkung und Streit über Unrichtigkeit: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gmbh-gruendung-erstanmeldung` | Checkt Stammkapital, Einzahlung, Geschäftsführer, Versicherung, Musterprotokoll, Gesellschaftsvertrag und Registereintragung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gmbh-kapitalerhoehung-bareinlage` | Prüft Satzungsänderung, Übernahme, Einzahlung, Anmeldung, Versicherung, Liste und Registervollzug: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gmbh-kapitalerhoehung-sacheinlage` | Prüft Sacheinlagebericht, Werthaltigkeit, verdeckte Sacheinlage, Anmeldung und Beanstandungsrisiko: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gmbh-kapitalherabsetzung-und-schutzjahr` | Prüft Gläubigerschutz, Sperrjahr, Bekanntmachungen, Versicherung und registerfeste Unterlagen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gmbh-liquidation-und-loeschung` | Führt durch Auflösung, Liquidatoren, Sperrjahr, Schlussbilanz, Löschung, Nachtragsliquidation und Registerkommunikation: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `gmbh-satzungsaenderung-handelsvollmacht-nicht` | Prüft Beschlussmehrheit, notarielle Beurkundung, vollständige Neufassung, Gegenstand, Firma, Sitz, Kapital und Anmeldung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `handelsregister-kaltstart-routing` | Führt durch das erste Registerproblem: Wer meldet was an, welche Gesellschaft, welches Registerblatt, welches Ziel, welcher Fristdruck, welche Urkunden, welche Entscheidungsperson und welches Eskalationsniveau. |
| `handelsvollmacht-nicht-eintragungsfaehig` | Erklärt, was nicht ins Register gehört und wie interne Vollmachten dennoch sicher dokumentiert werden: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `insolvenzvermerk-registereintrag` | Prüft Eintragung von Eröffnung, Eigenverwaltung, Aufhebung, Insolvenzplan, Freigabe und Wirkungen für Vertretung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `internationaler-registervergleich` | Vergleicht Companies House, irische/österreichische/schweizer Register und deutsche Nachweisanforderungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `kg-kommanditist-eintritt-austritt-haftsumme` | Prüft Einlage/Haftsumme, Sonderrechtsnachfolge, Austritt, Nachhaftung und Registerpublizität: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `ki-registerakte-nachlass` | Zwingt zu Belegpfad, Registerauszug, Aktenzeichen, Normenanker und klarer Kennzeichnung nicht verifizierter Annahmen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `nachlass-und-testamentsvollstrecker-register` | Prüft Erbschein, Europäisches Nachlasszeugnis, Testamentsvollstreckerzeugnis und Vertretungsmacht: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `notar-registergericht-kommunikation` | Erstellt klare Nachreichungslisten, Telefonnotizen, E-Mail-Entwürfe und Mandantenupdates ohne Schuldzuweisungschaos: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `ohg-kg-online-abruf-partg-partgmbb` | Prüft kaufmännischen Betrieb, Statuswechsel, Anmeldung, Gesellschafter, Vertretung und MoPeG-Schnittstellen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `online-abruf-registerportal-unternehmensregister` | Führt durch Handelsregister, Unternehmensregister, Bekanntmachungen, Chronologie, Ausdrucke, Screenshots und Beleglog: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `partg-partgmbb-register` | Prüft Partnerschaftsregister, Berufszulassung, Namensführung, Haftungsbeschränkung und Berufshaftpflichtnachweis: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `prokura-eintragung-rechtsabteilung` | Prüft Einzel-/Gesamtprokura, Filialprokura, Gesamtvertretung, Widerruf, Publizität und Unterschriftenmuster: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `rechtsabteilung-geschaeftsfuehrerbestellung-mit-auslandsbezug` | Rechtsabteilungs-Fachmodul für Geschäftsführerbestellung mit Auslandsbezug: Identität, Versicherung, Unterschrift und Übersetzung werden sauber vorbereitet. Mit Normen, Rechtsprechungsanker, Belegmatrix und schneller Handlungsoption: eig... |
| `rechtsabteilung-gesellschafterliste-nach-streit-und-ev` | Rechtsabteilungs-Fachmodul für Gesellschafterliste nach Streit und EV: Rechtsabteilungen bauen registertaugliche Listenpakete und Widerspruchsstrategien. Mit Normen, Rechtsprechungsanker, Belegmatrix und schneller Handlungsoption: eigens... |
| `rechtsabteilung-insolvenzvermerk` | Rechtsabteilungs-Fachmodul für Insolvenzvermerk und ausländischer Trustee: Vertretungsmacht ausländischer Insolvenzorgane wird registertauglich nachgewiesen. Mit Normen, Rechtsprechungsanker, Belegmatrix und schneller Handlungsoption: ei... |
| `rechtsabteilung-kapitalerhoehung-und-zwischenverfuegung` | Rechtsabteilungs-Fachmodul für Kapitalerhöhung und Zwischenverfügung: Zwischenverfügungen werden in heilbare Punkte, Streitpunkte und Beschwerde sortiert. Mit Normen, Rechtsprechungsanker, Belegmatrix und schneller Handlungsoption: eigen... |
| `rechtsabteilung-mopeg-gesellschaftsregister-und-ohg-sprung` | Rechtsabteilungs-Fachmodul für MoPeG-Gesellschaftsregister und OHG-Sprung: GbR, eGbR, OHG und Grundstücksfähigkeit werden registerlogisch abgegrenzt. Mit Normen, Rechtsprechungsanker, Belegmatrix und schneller Handlungsoption: eigenständ... |
| `rechtsprechung-register-frist-vollzugslog` | Legt fest, wie Entscheidungen in Registersachen nur mit Gericht, Datum, Aktenzeichen und freiem Fundlink ausgegeben werden: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `rechtsschein-innenstreit-register` | Trennt materielles Gesellschaftsrecht, Registerlage, Vertretungsmacht und Gutglaubensschutz: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `register-mandantenbrief` | Erstellt klare Mandantenupdates: Stand, Risiko, To-dos, Fristen, nächste Entscheidung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `register-qualitaetsgate-vor-einreichung` | Checkliste vor dem Absenden: Urkunden, Beschlüsse, Listen, Unterschriften, Kapital, Namen, Daten, Registerblatt: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerakte-schnellscan-registerauszug-lesen` | Erstellt eine Vollzugskarte aus Satzung, Beschluss, Anmeldung, Liste, Notarvermerk, Gerichtsschreiben und Fristenlog: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerauszug-lesen` | Erklärt Abteilungen/Spalten, Historie, Vertretung, Kapital, Firma, Prokura, Insolvenz und Bekanntmachungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerbeweis-im-prozess` | Bereitet Registerauszüge, Bekanntmachungen und Nachweise prozesstauglich auf: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registergericht-rollen-datenschutz` | Klärt Zuständigkeiten, Kommunikationsstil, Entscheidungswege und wann eine Sache richterlich, rechtspflegerisch oder rein vollzugstechnisch hängt: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registergericht-und-datenschutz` | Klärt öffentliche Registerdaten, sensible Anlagen, Schwärzungen, Anschriften und Löschungswünsche: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerkosten-und-notarkosten` | Ordnet Register- und Notarkosten grob, vermeidet Doppelvollzug und erklärt Mandanten die Kostenlogik: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerrecht-aktiengesellschaft-vorstand` | Prüft Bestellung, Vertretung, Satzungsänderungen, Kapitalmaßnahmen und Eintragung bei der AG: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerrecht-beschlussmaengel-und-registervollzug` | Prüft, ob das Registergericht bei Kapitalmaßnahme, Geschäftsführerbestellung oder Satzungsänderung Beschlussmängel beachten muss, wie weit die formelle Prüfung reicht und wann der materielle Streit auf Zivilprozess/Eilrechtsschutz verlag... |
| `registerrecht-digitalgruendung` | Prüft Online-Beurkundung/Beglaubigung, Identifizierung, digitale Einreichung und Medienbruch: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerrecht-fehlende-einzahlung-fehlerhafte` | Prüft Geschäftsführerversicherung, Kontoauszug, Hin- und Herzahlen, verdeckte Sacheinlage und Haftungsnotiz: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerrecht-fehlerhafte-geschaeftsfuehreradresse` | Prüft Anschriften, Geburtsdaten, Schutzinteressen, Schwärzungsmöglichkeiten und Auszugstypen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerrecht-kapitalgesellschaft-co-kg-komplementaerwechsel` | Koordiniert Ausscheiden/Eintritt der Komplementär-GmbH, Haftung, Vertretung und Registerreihenfolge: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerrecht-mandatsannahme-notarferne` | Klärt Rolle der anwaltlichen Beratung neben Notar, Verantwortungsgrenzen und Mandantensteuerung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerrecht-niederlassung-registergericht` | Prüft eintragungsfähige Zweigniederlassung, unselbständige Betriebsstätte und Adress-/Vertretungsangaben: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerrecht-registergericht-telefonat-protokoll` | Erstellt kurze Telefonnotiz mit Name, Aktenzeichen, Beanstandung, Frist, Zusage und Folgeschritt: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerrecht-registerzeichen-und-aktenzeichen` | Erklärt HRB, HRA, PR, GnR, VR, Registernummer, Gericht und Aktenzeichenlogik: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerrecht-scheinloeschung` | Prüft Restvermögen, Prozessfähigkeit, Bestellung Nachtragsliquidator und Registereintragung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerrecht-se-und-europaeische-gesellschaft` | Prüft SE-Firma, Sitz, monistisches/dualistisches System, Leitung, Verwaltungsrat und grenzüberschreitende Bezüge: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registerrecht-umbenennung-rebranding` | Prüft Firmenänderung, Satzung, IHK, Marken-/Domainkonflikte, Bekanntmachung und Mandantenkommunikation: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `registersperre-closing-sitz-inlandsanschrift` | Bewertet Sperrwirkung, einstweilige Verfügung, Gesellschafterlistenkonflikt und Alternativvollzug: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `sitz-inlandsanschrift-und-geschaeftsanschrift` | Prüft Satzungssitz, inländische Geschäftsanschrift, Empfangsbevollmächtigte, Briefkastenrisiken und Registereintragung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `todesfall-gesellschafter-register` | Prüft Erbnachweis, Sonderrechtsnachfolge, Testamentsvollstrecker, Liste und Registerkommunikation: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `transparenzregister-schnittstelle-umwandlung` | Verbindet Handelsregisterdaten mit wirtschaftlich Berechtigten, GwG-Risiken und Meldepflichten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `umwandlung-registervollzug` | Prüft Verschmelzung, Spaltung, Formwechsel, Registerreihenfolge, Schlussbilanz und Bekanntmachung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `umzug-registerbezirk-amtsloeschung` | Prüft innerörtlich/anderer Bezirk, Satzungsänderung, Registerabgabe, Bekanntmachung und Adresslogik: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `unternehmensgegenstand-beanstandung` | Formuliert eintragungsfähige Gegenstände ohne Erlaubnis-/Aufsichtsrechtsfalle und ohne zu enge Zukunftsfessel: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verein-registerschnittstelle-verschmelzung` | Klärt, wann Vereinsregisterlogik statt Handelsregisterlogik greift und welche Beschlüsse/Protokolle gebraucht werden: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verschmelzung-gmbh-registercheck` | Checkt Verschmelzungsvertrag, Zustimmungsbeschlüsse, Registeranmeldungen, Gläubigerschutz und Wirksamkeitszeitpunkt: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `vollmacht-und-anmeldung-oeffentliche-beglaubigung` | Prüft notarielle Beglaubigung, Vertreteranmeldung, Untervollmacht, Signatur und elektronische Einreichung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `zweigniederlassung-auslaendische` | Zweigniederlassung Auslaendische im Handelsregister-Praxis: fachlicher Arbeitsgang mit Prüffeldwahl, Norm-/Quellencheck, Risikoampel und verwertbarem Output. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
