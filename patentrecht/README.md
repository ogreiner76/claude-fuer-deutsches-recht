# patentrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`patentrecht`) | [`patentrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/patentrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Schnellverschluss S-14: Sensorhalter, Gebrauchsmusterabzweigung und Messeoffenbarung** (`gebrauchsmusterrecht-schnellverschluss-sensorhalter`) | [Gesamt-PDF lesen](../testakten/gebrauchsmusterrecht-schnellverschluss-sensorhalter/gesamt-pdf/gebrauchsmusterrecht-schnellverschluss-sensorhalter_gesamt.pdf) | [`testakte-gebrauchsmusterrecht-schnellverschluss-sensorhalter.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-gebrauchsmusterrecht-schnellverschluss-sensorhalter.zip) |
| **Patentrecht — Erfindungsakten Ravenstein & Moll** (`patentrecht-erfindungsakten-ravenstein-moll`) | [Gesamt-PDF lesen](../testakten/patentrecht-erfindungsakten-ravenstein-moll/gesamt-pdf/patentrecht-erfindungsakten-ravenstein-moll_gesamt.pdf) | [`testakte-patentrecht-erfindungsakten-ravenstein-moll.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-patentrecht-erfindungsakten-ravenstein-moll.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

> Großes Arbeitsplugin für Patentanwältinnen, Rechtsanwälte, Patentabteilungen und technische Gründerteams. Es führt vom rohen Erfindungsgedanken über Anspruchsentwurf, Recherche, Anmeldung, Prüfung, Freedom-to-Operate, Abmahnung, Lizenzvertrag, Einspruch und Nichtigkeit bis zur belastbaren Mandantenkommunikation.

## Wofür dieses Plugin gedacht ist

Das Plugin ist nicht nur eine Recherchehilfe. Es ist der Mandatsarbeitsplatz für Patentrecht:

- **Erfindung aufnehmen:** technische Lehre, Problem, Lösung, Ausführungsformen, Offenbarungsrisiken und fehlende Zeichnungen sauber einsammeln.
- **Anmeldung vorbereiten:** Anspruch 1, Unteransprüche, Beschreibung, Bezugszeichenliste, Figurenlogik, Alternativausführungen und Rückfragen strukturieren.
- **Patentfähigkeit prüfen:** Neuheit und erfinderische Tätigkeit nach PatG und EPÜ mit Merkmalsgliederung, nächstliegendem Stand der Technik und Aufgaben-Lösungs-Ansatz.
- **Recherche steuern:** gezielte Übergabe an das Spezialplugin [`patentrecherche`](../patentrecherche) für Espacenet, DPMAregister, DEPATISnet, EPO Register, WIPO PATENTSCOPE und weitere Datenbanken.
- **Verletzung und FTO prüfen:** Schutzbereich, wortsinngemäße Verwirklichung, Äquivalenz, Registerstand, Territory, Rechtsbestand und Design-around.
- **Abmahnung verteidigen:** Fristen, Unterlassung, Auskunft, Rückruf, Schadensersatz, negative Feststellung, Schutzschrift, Vergleichsfenster.
- **Verträge prüfen:** Patentlizenz, Exclusivity, Territory, Field of Use, Sublicensing, Improvements, Know-how, Royalties, Audit, Termination und DE/EN-Klauselrisiken.
- **Bestand angreifen oder verteidigen:** EPA-Einspruch, deutsche Nichtigkeitsklage, Beschränkung, Hilfsanträge, Fristen und Beweismittel.

## Arbeitsstil

Der Einstiegsskill fragt nicht lehrbuchartig alles ab, sondern sortiert den Fall sofort nach Dringlichkeit, Materiallage und Ziel. Bei Dokumentenupload ohne Begleittext erkennt er Fristen, Aktenart und Primärpfad. Danach schlägt er die passenden Spezialskills vor oder arbeitet direkt weiter.

## Quellen- und Zitierhygiene

- Normen und Behördeninformationen werden bevorzugt aus offiziellen Quellen geprüft: Patentgesetz auf Gesetze-im-Internet, DPMA-Informationen, DPMAregister/DEPATISnet, EPO/EPA Legal Texts, EPO Register, Espacenet, WIPO PATENTSCOPE und amtliche Gerichtsquellen.
- Rechtsprechung wird nur ausgegeben, wenn Gericht, Entscheidungsdatum, Aktenzeichen und eine frei zugängliche oder amtliche Fundstelle verifiziert sind.
- Keine BeckRS-/juris-/Paywall-Fundstellen erfinden oder als eigene Quelle verwenden.
- Wenn eine Bewertung von aktueller Amts- oder Registerlage abhängt, muss live nachgesehen werden.

## Verhältnis zu anderen Plugins

- [`patentrecherche`](../patentrecherche): tiefe Datenbankrecherche, CPC/IPC, Patentfamilien, Registerstand, Recherchebericht.
- [`gewerblicher-rechtsschutz`](../gewerblicher-rechtsschutz) und [`fachanwalt-gewerblicher-rechtsschutz`](../fachanwalt-gewerblicher-rechtsschutz): Marken, Designs, UWG, Verletzungsprozess und IP-Kollisionslagen.
- [`zitierweise-deutsches-recht`](../zitierweise-deutsches-recht): saubere Nachweise und Rechtsprechungszitate.
- [`word-legal-ai-plugin-and-skill-for-german-lawyers`](../word-legal-ai-plugin-and-skill-for-german-lawyers): Schriftsatz-, Gutachten-, Vertrags- und Mandantenbriefstil.

## Kern-Workflow

1. **Material erfassen:** Upload, Fristen, Beteiligte, Schutzrechte, Produkt/Verfahren, Technikfeld, Zielterritorien.
2. **Primärfrage festlegen:** Anmeldung, Recherche, FTO, Verletzung, Lizenz, Prüfungsbescheid, Einspruch/Nichtigkeit.
3. **Technische Lehre zerlegen:** Merkmale, Varianten, Wirkungen, Problem, Lösung, Zeichnungen, Bezugszeichen.
4. **Rechts- und Registerlage sichern:** Anmeldetag, Priorität, Veröffentlichung, Erteilung, Einspruch, Jahresgebühren, Validierungen, Rechtsstand.
5. **Spezialskill starten:** passende Skills aus diesem Plugin und bei Recherchebedarf aus `patentrecherche`.
6. **Output bauen:** Claim Draft, Merkmalsgliederung, Rechercheauftrag, Claim Chart, Risikomemo, Antwortentwurf, Lizenz-Redline oder Fristenplan.
7. **Red Team:** offene Tatsachen, technische Unschärfen, Fristen, Quellen, Gegenargumente, Mandantenrückfragen.

## Kernskills und neue internationale Module

Die folgende Tabelle nennt die ursprünglichen Kernskills. Die vollständige, automatisch generierte Liste steht direkt darunter und enthält jetzt auch UPC, PCT, USA, Kanada, Japan, Schweiz, UK, Türkei, Israel sowie Patentprozess/Eilrechtsschutz/Revocation.

| Skill | Funktion |
| --- | --- |
| `patentrecht-allgemein` | Einstieg, Triage und Workflow-Routing für jedes Patentrechtsmandat |
| `patentrecht-kaltstart-interview` | kurzes Mandatsprofil und wiederverwendbare Fallarchitektur |
| `erfindungsmeldung-aufnahme-und-rueckfragen` | rohe Erfindung, Offenbarung, technische Lehre und Rückfragen erfassen |
| `patentanmeldung-anspruchsentwurf` | Anspruch 1, Unteransprüche und Varianten vorbereiten |
| `beschreibung-und-zeichnungen-pruefen` | Beschreibung, Figuren, Bezugszeichen und Offenbarungsstütze prüfen |
| `neuheit-und-erfinderische-taetigkeit` | Merkmalsanalyse, Einzeldokumentprüfung, Aufgaben-Lösungs-Ansatz |
| `stand-der-technik-recherche-workflow` | Rechercheauftrag und Übergabe an `patentrecherche` |
| `gebrauchsmuster-oder-patent-route` | Patent, Gebrauchsmuster, EP/PCT, Geheimhaltung oder defensive Veröffentlichung abwägen |
| `pruefungsbescheid-dpma-epa-erwiderung` | Beanstandungen zerlegen und Erwiderung vorbereiten |
| `freedom-to-operate-und-schutzbereich` | FTO, Schutzbereich, Rechtsstand und Design-around |
| `abmahnung-patentverletzung-verteidigung` | Abmahnung, Fristen, Unterlassung, Schutzschrift, Vergleich |
| `patentverletzung-claim-chart` | claim chart für Verletzung oder Nichtverletzung |
| `vorbenutzungsrecht-paragraph-12-patg` | Vorbenutzungsrecht, Beweisführung und Risikostrategie |
| `patentlizenzvertrag-review` | Lizenzvertragsprüfung, Red Flags und Verhandlungspositionen |
| `patentlizenzvertrag-de-en-drafting` | zweisprachige Lizenzklauseln und Term-Sheet-Umsetzung |
| `erfinderbenennung-und-arbeitnehmererfindung` | Erfinderstatus, Arbeitnehmererfindung und Vergütungsschnittstellen |
| `einspruch-epa-und-nichtigkeit-bpatg` | EPA-Einspruch und Nichtigkeitsklage strategisch vorbereiten |
| `rechtsstand-register-und-fristen` | Register, Fristen, Jahresgebühren, Validierung, Einspruchs- und Klagefenster |
| `patentportfolio-und-technikstrategie` | Portfolio, Schutzzaun, Wettbewerbsmonitoring und Produktroadmap |
| `patentrecht-redteam-qualitygate` | Qualitätskontrolle für alle patentrechtlichen Outputs |

## Internationaler und prozessualer Ausbau

Neu hinzugekommen sind Skills für internationale Patentstrategie und Patentstreitigkeiten: UPC-Verletzung und Revocation, UPC-Eilverfahren, EPO-Einspruch/Beschwerde, PCT-Nationalphasen, US/UK/Kanada/Japan/Schweiz/Türkei/Israel, globale Rechtsbestandsangriffe, Schutzschrift/Protective Letter, Besichtigung, Auskunft/Rechnungslegung, Claim Construction DE/EN, Patentvergleich/Cross-License, Expertenarbeit und Prozessbudget.

Jeder dieser Skills arbeitet mit derselben Grundregel: Registerstand und lokale Verfahrensfragen live prüfen; ausländisches Recht als Arbeitsstruktur und Counsel-Briefing behandeln, nicht als scheinbar endgültige lokale Rechtsauskunft.

## Pflicht-Disclaimer im Output

Jedes externe Ergebnis enthält knapp: KI-gestützte Vorprüfung; keine amtliche Recherche; Register- und Rechtsstand sind live zu verifizieren; technische Bewertung setzt vollständige Unterlagen voraus.

## Lizenz

Apache-2.0 OR MIT. Siehe Repository-Stammverzeichnis.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 59 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `abmahnung-patentverletzung-verteidigung` | Verteidigt gegen Patentabmahnungen: Fristen, Unterlassungserklärung, Registerstand, Anspruchsfassung, Nichtverletzung, Rechtsbestand, Vorbenutzungsrecht, Schutzschrift, Vergleich und Mandantenkommunikation: eigenständiges Prüffeld mit No... |
| `beschreibung-zeichnungen-einspruch-epa-epo` | Prüft Beschreibung, Zeichnungen, Bezugszeichenliste und Ausführungsbeispiele einer Patentanmeldung auf Offenbarungsstütze, Verständlichkeit, Anspruchskonsistenz, Varianten und formale Lücken: eigenständiges Prüffeld mit Norm-/Quellenchec... |
| `einspruch-epa-und-nichtigkeit-bpatg` | Bereitet EPA-Einspruch und deutsche Nichtigkeitsklage vor: Fristen, Zuständigkeit, Angriffsmittel, Stand der Technik, unzulässige Erweiterung, Ausführbarkeit, Priorität, Hilfsanträge und Prozessstrategie: eigenständiges Prüffeld mit Norm... |
| `epo-epue-einspruch-beschwerde-beschraenkung` | Vertieft EPA/EPO-Verfahren: Einspruch, Beschwerde, zentrale Beschränkung, Hilfsanträge, Verfahrenssprache, mündliche Verhandlung und Übergang zu UPC/nationaler Durchsetzung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und... |
| `erfinderbenennung-arbeitnehmererfindung` | Prüft Erfinderbenennung, Rechtekette und Arbeitnehmererfindungs-Schnittstellen: wer ist Erfinder, wer ist Anmelder, Diensterfindung, freie Erfindung, Inanspruchnahme, Vergütung und Dokumentationsrisiken: eigenständiges Prüffeld mit Norm-... |
| `erfindungsmeldung-aufnahme-und-rueckfragen` | Nimmt rohe Erfindungsideen, Skizzen, Mandantenmails und Prototypnotizen auf; trennt technische Lehre von bloßer Idee, erkennt Offenbarungsrisiken und erstellt Rückfragen für eine patentfähige Anmeldung: eigenständiges Prüffeld mit Norm-/... |
| `freedom-to-operate-und-schutzbereich` | Prüft Freedom-to-Operate und Schutzbereich: Zielprodukt, Territory, Registerstand, Anspruchsmerkmale, wortsinngemäße Verwirklichung, Äquivalenz, Design-around und Risikomemo: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel un... |
| `gebrauchsmuster-patent-patentrechts` | Prüft strategisch Patent, Gebrauchsmuster, EP/PCT, Geheimhaltung, defensive Veröffentlichung oder keine Anmeldung; berücksichtigt Offenbarung, Geschwindigkeit, Kosten, Technikart und Zielmärkte: eigenständiges Prüffeld mit Norm-/Quellenc... |
| `internationaler-patentrechts-und-laendercheck` | Routet grenzüberschreitende Patentmandate nach DE, EP, UPC, PCT, USA, Kanada, Japan, Schweiz, UK, Türkei und Israel; trennt Recherche, Anmeldung, Rechtsstand, Verletzung, Rechtsbestand und lokale Counsel-Fragen: eigenständiges Prüffeld m... |
| `israel-patentrecht-ilpo-opposition-revocation` | Prüft israelische Patentfragen: ILPO-Register, Examination, Opposition vor Erteilung, Revocation/Cancellation, Verletzung, einstweilige Maßnahmen und technologiebezogene Counsel-Fragen: eigenständiges Prüffeld mit Norm-/Quellencheck, Ris... |
| `japan-jpo-kanada-cipo-loeschung-widerruf` | Strukturiert japanische Patentfragen: J-PlatPat, JPO-Prüfung, Opposition/Invalidation Trial, Korrektur, IP High Court, Übersetzung und lokale Vertretung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `kanada-patentrecht-cipo-federal-court` | Prüft kanadische Patentfragen: CIPO-Recherche und Prosecution, Patent Appeal Board, Re-examination, Federal Court, PM(NOC)-Schnittstellen und bilinguale Local-Counsel-Fragen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel un... |
| `loeschung-widerruf-nichtigkeit-global-route` | Koordiniert Rechtsbestandsangriffe international: EPA-Einspruch, UPC-Revocation, deutsche Nichtigkeit, UK revocation, US PTAB, Kanada, Japan, Schweiz, Türkei und Israel: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und ver... |
| `neuheit-erfinderische-patentprozess` | Prüft Patentfähigkeit mit Merkmalsgliederung, Neuheit nach § 3 PatG/Art. 54 EPÜ und erfinderischer Tätigkeit nach § 4 PatG/Art. 56 EPÜ; nutzt Einzeldokumentprüfung und Aufgaben-Lösungs-Ansatz: eigenständiges Prüffeld mit Norm-/Quellenche... |
| `patentanmeldung-anspruchsentwurf` | Bereitet Patentansprüche vor: Anspruch 1, Unteransprüche, Alternativausführungen, Vorrichtung/Verfahren/System/Computerprogramm, Stütze in Beschreibung und Rückfragen zur Anspruchsbreite: eigenständiges Prüffeld mit Norm-/Quellencheck, R... |
| `patentlizenzvertrag-drafting-review` | Setzt Patentlizenz-Term-Sheets in deutsch-englische Vertragsklauseln um; erklärt Legal-English-Begriffe im deutschen Rechtskontext und vermeidet unklare Transaktionssprache: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und... |
| `patentlizenzvertrag-review` | Prüft Patentlizenzverträge: Schutzrechte, Territory, Field of Use, Exklusivität, Unterlizenzen, Royalties, Milestones, Improvements, Inhaberschaft, Gewährleistung, Durchsetzung, Kündigung und Insolvenzrisiken: eigenständiges Prüffeld mit... |
| `patentportfolio-und-technikstrategie` | Unterstützt Patentportfolio- und Technikstrategie: Schutzzaun, Roadmap, Wettbewerbsmonitoring, defensive Veröffentlichungen, Anmeldepriorisierung, Länderstrategie und Budgetsteuerung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risik... |
| `patentprozess-auskunft-patentportfolio` | Bereitet Folgeansprüche nach Patentverletzung vor: Auskunft, Rechnungslegung, Rückruf, Vernichtung, Schadensberechnung, Lizenzanalogie, Verletzergewinn und Daten-/Geheimnisschutz: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoamp... |
| `patentprozess-besichtigung-beweissicherung` | Strukturiert Besichtigung, Beweissicherung und technische Dokumentation in Patentstreitigkeiten: Produktzugang, Geheimnisschutz, Sachverständige, Testkäufe, Reverse Engineering und chain of custody: eigenständiges Prüffeld mit Norm-/Quel... |
| `patentprozess-claim-construction-de-en` | Übersetzt Patentansprüche prozessfest zwischen Deutsch und Englisch: Merkmalsgliederung, claim construction, Äquivalenz, Prosecution History, technische Begriffe und gerichtstaugliche Argumentation: eigenständiges Prüffeld mit Norm-/Quel... |
| `patentprozess-einstweilige-verfuegung` | Plant einstweiligen Rechtsschutz in Patentverletzungssachen vor deutschen Gerichten und UPC: Dringlichkeit, Schutzrechtsbestand, Verletzungsnachweis, Schutzschrift, Sicherheitsleistung und Vollziehung: eigenständiges Prüffeld mit Norm-/Q... |
| `patentprozess-experten-und-sachverstaendige` | Plant technische Expertenarbeit in Patentverfahren: Privatgutachten, gerichtliche Sachverständige, Parteigutachten, Experimente, Reproduzierbarkeit, Befragung und Schwachstellenanalyse: eigenständiges Prüffeld mit Norm-/Quellencheck, Ris... |
| `patentprozess-kostensicherheit-und-budget` | Erstellt Kosten- und Risikoüberblick für Patentstreitigkeiten: Gerichtskosten, Anwalt, Patentanwalt, Sachverständige, Übersetzungen, Sicherheitsleistung, UPC-/Auslandsbudget und Vergleichswert: eigenständiges Prüffeld mit Norm-/Quellench... |
| `patentprozess-negative-schutzschrift` | Prüft negative Feststellungsklagen, Nichtverletzungserklärungen, Forum-Risiken, Abmahnreaktionen und grenzüberschreitende Koordination bei Patentstreitigkeiten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem... |
| `patentprozess-schutzschrift-und-caveat` | Erstellt Schutzschrift-/Protective-Letter-Strategien für deutsche Patentgerichte, UPC und ausländische Eilrisiken, inklusive Nichtverletzung, Rechtsbestand, Dringlichkeit und Geheimhaltungsanträgen: eigenständiges Prüffeld mit Norm-/Quel... |
| `patentrecht-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `patentrecht-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `patentrecht-kaltstart-interview` | Kaltstart-Interview für Patentrechtsmandate. Erstellt ein kurzes Profil zu Mandant, Technik, Ziel, Territorien, Fristen, Dokumentenlage, Risiko und gewünschtem Output; speichert keine Geheimnisse, sondern strukturiert die nächsten Skills. |
| `patentrecht-kaltstart-triage` | Einstieg, Schnelltriage und Fallrouting im Patentrecht-Plugin. Erkennt Patentanmeldung, Erfindungsmeldung, Recherche, FTO, Abmahnung, Lizenz, Einspruch, Nichtigkeit, Register- und Fristenfragen; schlägt passende Fachmodule aus diesem Plu... |
| `patentrecht-redteam-qualitygate` | Red-Team- und Qualitätsgate für patentrechtliche Outputs: prüft Fristen, Registerstand, Anspruchsfassung, technische Annahmen, Quellen, Beweise, Zitierhygiene, offene Tatsachen und Mandantenrisiken. |
| `patentrecht-upc-einstweilige-massnahmen-verletzung-rechtsbestand` | Bereitet einstweilige Maßnahmen vor dem UPC vor: Dringlichkeit, Schutzbereich, Rechtsbestand, Beweislast, Schutzschrift, Geheimnisschutz, Vollziehung und Vergleichsfenster: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und... |
| `patentrechts-tuerkei-turkpatent-uk-patents` | Patentrechts: Erstprüfung, Rollenklärung und Mandatsziel; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `patentsettlement-und-cross-license-litigation` | Unterstützt Patentvergleiche: Cross-License, Covenant not to sue, Territory, Field of Use, Release, Rückruf, Kosten, Kartellrecht, Geheimhaltung und Vollstreckbarkeit: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwe... |
| `patentverletzung-claim-patr2` | Erstellt Claim Charts für Patentverletzung oder Nichtverletzung: Anspruchsmerkmale, Produkt-/Verfahrensbelege, Fundstellen, Beweisqualität, Lücken, Äquivalenz und Ergebnisampel: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel... |
| `patr2-anmeldeverfahren-bauleiter` | Bauleiter Patentanmeldeverfahren DPMA und EPA: Pruefverfahren, Einspruch, Beschwerde. Pruefraster fuer Erfinder und Patentanwalt: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `patr2-arbeitnehmererfindung-leitfaden` | Leitfaden Arbeitnehmererfindergesetz ArbnErfG: Meldepflicht, Inanspruchnahme, Verguetung, Schiedsstelle. Pruefraster fuer Arbeitgeber und Erfinder: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `patr2-patentverletzungsklage-spezial` | Spezialfall Patentverletzungsklage: aequivalente Verletzung, Unterlassung, Auskunft, Schadensersatz, Anspruchsberechnung Lizenzanalogie. Pruefraster fuer Klaeger und Beklagter: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel... |
| `patr2-zwangslizenz-pct-laenderstrategie` | Spezialfall Zwangslizenz § 24 PatG und FRAND-Verteidigung: Voraussetzungen, EuGH Huawei / ZTE, kartellrechtliche Aspekte. Pruefraster fuer SEP-Inhaber und Implementer: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwe... |
| `pct-laenderstrategie-und-nationalphasen` | Plant PCT-Anmeldungen und Nationalphasen: Priorität, ISA/IPEA-Bericht, Länderbudget, Übersetzungen, Eintrittsfristen, Schutzrechtsmix und Abbruchentscheidungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem... |
| `pruefungsbescheid-dpma-epa-erwiderung` | Bereitet Erwiderungen auf Prüfungsbescheide von DPMA oder EPA vor: Beanstandungen, Entgegenhaltungen, Anspruchsänderungen, Argumentation zu Neuheit/erfinderischer Tätigkeit und Mandantenrückfragen: eigenständiges Prüffeld mit Norm-/Quell... |
| `rechtsabteilung-employee-invention-frand` | Rechtsabteilungs-Fachmodul für Employee Invention im Konzernprojekt: Meldung, Inanspruchnahme, Vergütung und ausländische R&D-Beiträge werden aufgesetzt. Mit Normen, Rechtsprechungsanker, Belegmatrix und schneller Handlungsoption: eigens... |
| `rechtsabteilung-frand-verteidigung-bei-sep-abmahnung` | Rechtsabteilungs-Fachmodul für FRAND-Verteidigung bei SEP-Abmahnung: Lizenzbereitschaft, Vergleichbarkeit und Hold-out/Hold-up werden dokumentiert. Mit Normen, Rechtsprechungsanker, Belegmatrix und schneller Handlungsoption: eigenständig... |
| `rechtsabteilung-freedom-to-operate-vor-product-launch` | Rechtsabteilungs-Fachmodul für Freedom-to-Operate vor Product Launch: FTO wird mit Claim Chart, Länderpriorität und Design-Around-Entscheidung ausgegeben. Mit Normen, Rechtsprechungsanker, Belegmatrix und schneller Handlungsoption: eigen... |
| `rechtsabteilung-proportionalitaet-schweiz` | Rechtsabteilungs-Fachmodul für Proportionalität der Unterlassung § 139 PatG: Injunction-Risiken werden für komplexe Produkte und Supply Chain bewertet. Mit Normen, Rechtsprechungsanker, Belegmatrix und schneller Handlungsoption: eigenstä... |
| `rechtsabteilung-upc-eilverfahren-und-deutsche-parallelstrategie` | Rechtsabteilungs-Fachmodul für UPC-Eilverfahren und deutsche Parallelstrategie: PI-Antrag, Schutzschrift, Bifurcation und Forumstrategie werden abgewogen. Mit Normen, Rechtsprechungsanker, Belegmatrix und schneller Handlungsoption: eigen... |
| `register-patentanmeldung-anspruchsentwurf` | Prüft Patentregister und Fristen: DPMAregister, EPO Register, nationale Validierungen, Einheitspatent, Jahresgebühren, Priorität, Veröffentlichung, Erteilung, Einspruch, Beschränkung, Nichtigkeit und Verlängerungen: eigenständiges Prüffe... |
| `schweiz-patentrecht-bundespatentgericht` | Prüft Schweizer Patentrecht: Swissreg/IGE, nationale Patente, EP-Validierung, Bundespatentgericht, Verletzung, Nichtigkeit, vorsorgliche Maßnahmen und DACH-Abgrenzung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwe... |
| `spezial-anspruchsentwurf-dokumentenmatrix-und-lueckenliste` | Anspruchsentwurf: Dokumentenmatrix, Lückenliste und Nachforderung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quel... |
| `spezial-erfindungsaufnahme-tatbestand-beweis-und-belege` | Erfindungsaufnahme: Tatbestandsmerkmale, Beweisfragen und Beleglage; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Qu... |
| `spezial-patentanmeldung-fristen-form-und-zustaendigkeit` | Patentanmeldung: Fristen, Form, Zuständigkeit und Rechtsweg; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellenche... |
| `stand-technik-patr2-anmeldeverfahren` | Plant eine Stand-der-Technik-Recherche: Suchbegriffe, CPC/IPC-Klassen, Datenbanken, Suchstrings, Trefferbewertung und Übergabe an das Patentrecherche-Plugin: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Ou... |
| `tuerkei-patentrecht-turkpatent-ip-courts` | Orientiert in türkischen Patentfragen: TURKPATENT-Register, nationale Phase/EP-Validierung, Opposition/Invalidity, Verletzung, einstweilige Maßnahmen, Zoll und lokale Counsel-Schnittstelle: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `uk-patentrecht-patents-court-ipec-ukipo` | Routet UK-Patentfragen: UKIPO Register, Patents Court, IPEC, opinions service, revocation, declaration of non-infringement, quia timet injunction und Kostenrisiko: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertba... |
| `upc-verletzung-und-rechtsbestand` | Prüft Einheitliches Patentgericht UPC: Verletzungsklage, Zentral-/Lokal-/Regionalkammer, Widerklage auf Nichtigerklärung, Opt-out, Einheitspatent und klassische europäische Patente: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoa... |
| `upc-widerruf-und-widerklage-revocation` | Plant isolierte Widerrufsklage und Widerklage auf Nichtigerklärung vor dem UPC, inklusive zentraler Kammer, Verletzungsverfahren, Hilfsanträgen und Koordination mit EPA-Einspruch: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoamp... |
| `us-patent-litigation-district-court-itc` | Bereitet US-Patentlitigation aus deutscher Sicht vor: complaint, answer, claim construction, discovery, Markman, damages, injunction, ITC exclusion order und Settlement-Druck: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel u... |
| `us-patent-us-vorbenutzungsrecht-paragraph` | Orientiert deutsche Teams im US-Patentrecht: Patentability, claim drafting, IDS, office action, continuation, reissue, reexamination, IPR/PGR vor PTAB und Local-Counsel-Briefing: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampe... |
| `vorbenutzungsrecht-paragraph-12-patg` | Prüft Vorbenutzungsrecht nach § 12 PatG: Besitzstand vor Anmeldung/Priorität, Benutzung oder ernsthafte Veranstaltungen, Inland, Redlichkeit, Umfang, Beweisführung und Prozessstrategie: eigenständiges Prüffeld mit Norm-/Quellencheck, Ris... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
