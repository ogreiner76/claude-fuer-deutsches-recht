# Lobbyregister Bundestag

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`lobbyregister-bundestag`) | [`lobbyregister-bundestag.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/lobbyregister-bundestag.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Lobbyregister: Bürgerinitiative Waldmoor 2030** (`lobbyregister-buergerinitiative-waldmoor`) | [Gesamt-PDF lesen](../testakten/lobbyregister-buergerinitiative-waldmoor/gesamt-pdf/lobbyregister-buergerinitiative-waldmoor_gesamt.pdf) | [`testakte-lobbyregister-buergerinitiative-waldmoor.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-lobbyregister-buergerinitiative-waldmoor.zip) |
| **Akte Lobbyregister: Emerald Liffey Bank plc / Zweigniederlassung Frankfurt** (`lobbyregister-dublin-bank-frankfurt-branch`) | [Gesamt-PDF lesen](../testakten/lobbyregister-dublin-bank-frankfurt-branch/gesamt-pdf/lobbyregister-dublin-bank-frankfurt-branch_gesamt.pdf) | [`testakte-lobbyregister-dublin-bank-frankfurt-branch.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-lobbyregister-dublin-bank-frankfurt-branch.zip) |
| **Akte Lobbyregister: Spreebogen Regulatory GmbH / Wasserstoffpaket** (`lobbyregister-public-affairs-agentur-wasserstoff`) | [Gesamt-PDF lesen](../testakten/lobbyregister-public-affairs-agentur-wasserstoff/gesamt-pdf/lobbyregister-public-affairs-agentur-wasserstoff_gesamt.pdf) | [`testakte-lobbyregister-public-affairs-agentur-wasserstoff.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-lobbyregister-public-affairs-agentur-wasserstoff.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Superplugin fuer Meldungen, Registrierung, Aktualisierung, oeffentliche API-Abfragen und laufende Compliance im Lobbyregister fuer die Interessenvertretung gegenueber dem Deutschen Bundestag und der Bundesregierung. Es fuehrt Nutzerinnen und Nutzer von der Frage "Muss ich ueberhaupt?" bis zur prueffaehigen Registrierungsmappe, zum Portal-Eingabeplan, zu Quartals-Uploads, Jahresaktualisierung, Verhaltenskodex, Open-Data-Monitoring und Meldung moeglicher Verstoesse.

Dieses Plugin ist **vollstaendig freistehend**. Es erwartet keine anderen Plugins, keine Portal-API und keine Kanzleisoftware. Wenn kein Zugang zum Lobbyregisterportal, DMS, CRM, Public-Affairs-Tool oder Finanzsystem vorhanden ist, arbeitet es mit manuellen Uploads oder einem ausdruecklich markierten Simulationsmodus.

## Schnellstart

1. Plugin aktivieren oder ZIP aus dem Release installieren.
2. Neue Sache mit `lobbyregister-kommandocenter` oder `end-to-end-registrierungswizard` starten.
3. Organisation, geplante Kontakte, Auftraggeber, Regelungsvorhaben, Fristen, Portalstatus und vorhandene Unterlagen nennen.
4. Das Plugin routet zu Pflichtcheck, Ausnahmen, Portalangaben, Finanzdaten, Stellungnahmen, Updates, Verhaltenskodex oder Meldung.
5. Am Ende immer das Qualitaetsgate verlangen: Pflichtgrund, Ausnahmen, Datenfelder, Fristen, Freigaben, offene Annahmen und naechste Portalaktion.

## Enthaltene Skills

- `lobbyregister-kommandocenter` - Lobbyregister-Kommandocenter
- `lobbyregister-intake-mandat` - Mandats- und Projekt-Intake
- `interessenvertretung-begriff` - Begriff der Interessenvertretung
- `adressatenkreis-bundestag-bundesregierung` - Adressatenkreis Bundestag und Bundesregierung
- `registrierungspflicht-schwellen` - Registrierungspflicht und Schwellen
- `ausnahmen-bundestag` - Ausnahmen Bundestag
- `ausnahmen-bundesregierung` - Ausnahmen Bundesregierung
- `freiwillige-registrierung` - Freiwillige Registrierung
- `personen-organisationstyp` - Personen- und Organisationstyp
- `konzern-netzwerk-plattform` - Konzern, Netzwerk und Plattform
- `hauptstadtrepraesentanz` - Hauptstadtrepraesentanz
- `vertretungsberechtigte-personen` - Vertretungsberechtigte Personen
- `betraute-personen` - Betraute Personen
- `drehtuer-angaben` - Drehtuer-Angaben
- `taetigkeitsbeschreibung` - Taetigkeitsbeschreibung
- `interessen-und-vorhabenbereiche` - Interessen- und Vorhabenbereiche
- `regelungsvorhaben-erfassen` - Regelungsvorhaben erfassen
- `stellungnahmen-gutachten-upload` - Stellungnahmen und Gutachten Upload
- `auftraggeber-ermitteln` - Auftraggeber ermitteln
- `unterauftragnehmer-erfassen` - Unterauftragnehmer erfassen
- `fremdmandat-agenturfall` - Fremdmandat und Agenturfall
- `finanzaufwendungen-berechnen` - Finanzaufwendungen berechnen
- `hauptfinanzierungsquellen` - Hauptfinanzierungsquellen
- `oeffentliche-zuwendungen` - Oeffentliche Zuwendungen
- `schenkungen-sponsoring` - Schenkungen und Sponsoring
- `mitgliedschaften-mitgliederzahl` - Mitgliedschaften und Mitgliederzahl
- `jahresabschluss-rechenschaftsbericht` - Jahresabschluss und Rechenschaftsbericht
- `anonymisierung-schutzantrag` - Anonymisierung und Schutzantrag
- `datenschutz-nichtoeffentliche-angaben` - Datenschutz und nicht oeffentliche Angaben
- `portal-account-rollen` - Portal-Account und Rollen
- `erstregistrierung-ausfuellen` - Erstregistrierung ausfuellen
- `bestaetigungsdokument-freigabe` - Bestaetigungsdokument und Freigabe
- `registereintrag-finalcheck` - Registereintrag Finalcheck
- `aktualisierung-unverzueglich` - Unverzuegliche Aktualisierung
- `geschaeftsjahresaktualisierung` - Geschaeftsjahresaktualisierung
- `fristen-und-quartalsmonitor` - Fristen- und Quartalsmonitor
- `verhaltenskodex-integritaet` - Verhaltenskodex und Integritaet
- `erstkontakt-offenlegung` - Erstkontakt Offenlegung
- `visitenkarte-und-nachweise` - Visitenkarte und Nachweise
- `hausausweis-und-anhoerung` - Hausausweis und Anhoerung
- `registerfuehrende-stelle-kontakt` - Registerfuehrende Stelle Kontakt
- `verstoesse-melden` - Verstoesse melden
- `bussgeld-und-pruefverfahren` - Bussgeld und Pruefverfahren
- `nicht-aktualisiert-risiko` - Nicht-aktualisiert Risiko
- `fruehere-interessenvertretung-exit` - Exit und fruehere Interessenvertretung
- `suche-open-data-monitor` - Suche und Open-Data-Monitor
- `benachrichtigungskonto-monitor` - Benachrichtigungskonto Monitor
- `interne-lobbyregister-richtlinie` - Interne Lobbyregister-Richtlinie
- `dokumentationsakte-revisionsspur` - Dokumentationsakte und Revisionsspur
- `end-to-end-registrierungswizard` - End-to-End Registrierungswizard

## Vorlagen

- `assets/templates/registrierungspflicht-check.md` - Pflicht- und Ausnahmepruefung
- `assets/templates/registereintrag-datenraum.md` - Datenraum fuer Erstregistrierung und Update
- `assets/templates/regelungsvorhaben-matrix.md` - Regelungsvorhaben, Stellungnahmen und Uploadfristen
- `assets/templates/auftraggeber-und-unterauftrag.md` - Auftraggeber, Unterauftrag und eingesetzte Personen
- `assets/templates/finanzdaten-check.md` - Finanzaufwendungen, Zuwendungen, Schenkungen und Abschluss
- `assets/templates/aktualisierungskalender.md` - Fristen, Quartale und Geschaeftsjahresupdate
- `assets/templates/verhaltenskodex-kontaktkarte.md` - Offenlegung und Kodex-Check fuer Kontakte
- `assets/templates/qualitaetsgate.md` - Finaler Freigabe- und Risiko-Check
- `assets/templates/auslandsrechtstraeger-zweigniederlassung-check.md` - Spezialcheck auslaendischer Rechtstraeger mit deutscher Zweigniederlassung
- `assets/templates/streitvermerk-doppelregistrierung.md` - Variantenvermerk einmalige oder doppelte Registrierung
- `assets/templates/rfs-anfrage-zweigniederlassung.md` - Anfrageentwurf an die registerfuehrende Stelle
- `assets/templates/api-abfrageplan.md` - API-Such- und Abfrageplan fuer oeffentliche Registerdaten
- `assets/templates/registerdaten-json-mapping.md` - JSON-nahes Mapping interner Registerdaten auf den oeffentlichen Export
- `assets/templates/registerexport-diff.md` - Diff zwischen interner Freigabeakte und API/API-Export
- `assets/templates/open-data-monitoring-plan.md` - Watchlist, Alarmregeln und API-Cursor-Protokoll

## Offizielle Startquellen

- [Lobbyregister FAQ fuer Interessenvertreter](https://www.lobbyregister.bundestag.de/informationen-und-hilfe/informationen-fuer-interessenvertreter-863572)
- [Lobbyregister A-Z](https://www.lobbyregister.bundestag.de/informationen-und-hilfe/lobbyregister-a-z-863568)
- [Handbuch zur Eintragung Version 2.0](https://www.lobbyregister.bundestag.de/informationen-und-hilfe/handbuch)
- [LobbyRG bei gesetze-im-internet](https://www.gesetze-im-internet.de/lobbyrg/BJNR081800021.html)
- [Verhaltenskodex Anlage 6 BTGO](https://www.gesetze-im-internet.de/btgo2025anl_6/BJNR0FA0I0025BJNE000100000.html)
- [Sanktionen bei Verstoessen](https://www.lobbyregister.bundestag.de/informationen-und-hilfe/sanktionen-bei-verstoessen-1014438)
- [Inhalte der Interessenvertretung](https://www.lobbyregister.bundestag.de/inhalte-der-interessenvertretung?lang=de)
- [Registerfuehrende Stelle](https://www.lobbyregister.bundestag.de/informationen-und-hilfe/registerfuehrende-stelle-rfs--863578)
- [Open Data/API](https://www.lobbyregister.bundestag.de/informationen-und-hilfe/open-data-1049716)
- [API V2 YAML](https://api.lobbyregister.bundestag.de/rest/v2/R2.21-de.yaml)
- [API V2 Swagger UI](https://api.lobbyregister.bundestag.de/rest/v2/swagger-ui/)
- [JSON-Schema Registereintrag](https://www.lobbyregister.bundestag.de/json-schemas/current/Lobbyregister-Registereintrag-schema.json)

## Open Data und API V2

Das Plugin nutzt die offizielle API als **lesende Kontrollschicht**: Suche nach Organisationen, Abfrage veroeffentlichter Registereintraege, Versionen, Statistikdaten, Dublettenpruefung, Export-Diff und Monitoring. Registrierung, Aktualisierung, Bestaetigung, Stellungnahmen-Upload und sonstige Portalhandlungen bleiben Portalaktionen und duerfen nicht als API-Einreichung ausgegeben werden.

Technische Arbeitsregel:

1. Vor der Portalaktion: interne Daten mit `assets/templates/registerdaten-json-mapping.md` JSON-nah strukturieren.
2. Nach der Veroeffentlichung: oeffentlichen Eintrag mit API V2 abfragen und mit `assets/templates/registerexport-diff.md` gegen die Freigabeakte pruefen.
3. Fuer laufende Compliance: `assets/templates/api-abfrageplan.md` und `assets/templates/open-data-monitoring-plan.md` nutzen, Cursor und `sourceDate` archivieren.
4. Bei Zweigniederlassungen, Auftraggebern, Unterauftragnehmern und Namensvarianten immer eine Freitextsuche auf Dubletten dokumentieren.

Details stehen in [references/open-data-api-v2.md](references/open-data-api-v2.md).

## Freistehende Leitplanken

- Keine Aussage "nicht registrierungspflichtig" ohne dokumentierte Pruefung von Interessenvertretung, Adressat, Schwelle und Ausnahme.
- Keine Registrierung oder Aktualisierung ohne Verantwortliche, Freigabe und Bestaetigungsdokument.
- Keine Behauptung einer API-Einreichung ohne offizielle Dokumentation. Die bekannte API V2 ist fuer oeffentliche Registerdaten als lesender Zugriff zu behandeln.
- Keine Regelungsvorhaben- oder Stellungnahme-Bewertung ohne Datum der Kontaktaufnahme und Quartals-/Updatefrist.
- Keine Finanzangaben ohne Geschaeftsjahr, Berechnungsmethode, Belege und Plausibilitaetscheck.
- Keine Kontaktaufnahme ohne Offenlegung von Identitaet, Anliegen und gegebenenfalls Auftraggeber.
- Keine Meldung moeglicher Verstoesse ohne konkrete Registernummer, Sachverhalt, Belege und Unsicherheiten.
- Keine echten Mandats-, Lobbying- oder Personaldaten in ungepruefte Cloud- oder KI-Umgebungen.

## Verwendungsbeispiel

```
Wir sind ein mittelstaendisches Unternehmen und wollen in den naechsten Wochen
mit Bundestagsabgeordneten und einem Bundesministerium zu einem geplanten
Bundesgesetz sprechen. Bitte starte mit lobbyregister-kommandocenter, pruefe
Registrierungspflicht und Ausnahmen, lege die Datenanforderung an, formuliere
die Regelungsvorhaben und erstelle am Ende eine Registrierungsmappe mit
Fristenkalender und Offenlegungsbausteinen fuer Erstkontakte.
```

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 26 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `account-rollen-regelungsvorhaben-erfassen` | Account Rollen Regelungsvorhaben Erfassen im Lobbyregister Bundestag: prüft konkret Plant Administrationskonto, Rollen, Zugriffsschutz, Zwei-Personen-Freigabe und P. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächst... |
| `aktualisierung-unverzueglich-adressatenkreis` | Aktualisierung Unverzueglich Adressatenkreis im Lobbyregister Bundestag: prüft konkret Steuert unverzuegliche Updates bei Stammdaten, Personen, Tätigkeitsbeschreibung, Kartiert Adressatinnen und Adressaten nach § 1 LobbyRG. Liefert prior... |
| `anonymisierung-schutzantrag-auftraggeber` | Anonymisierung Schutzantrag Auftraggeber im Lobbyregister Bundestag: prüft konkret Prüft Beschraenkung der Veröffentlichung bei schutzwürdigen, Erfasst Auftraggeberinnen und Auftraggeber bei. Liefert priorisierten Output mit Norm-Pinpoin... |
| `ausnahmen-bundesregierung-bundestag` | Ausnahmen Bundesregierung Bundestag im Lobbyregister Bundestag: prüft konkret Prüft Ausnahmen bei Interessenvertretung gegenüber, Prüft die Ausnahmen von der Registrierungspflicht bei. Liefert priorisierten Output mit Norm-Pinpoints, Ris... |
| `benachrichtigungskonto-monitor` | Benachrichtigungskonto Monitor im Lobbyregister Bundestag: prüft konkret Richtet Beobachtung von Registereintraegen, Aktualisierungen und Entwicklungen ü, Bestimmt Unterzeichner, Leitungsperson. Liefert priorisierten Output mit Norm-Pinp... |
| `betraute-personen-datenschutz` | Betraute Personen Datenschutz im Lobbyregister Bundestag: prüft konkret Ermittelt Personen, die mit Interessenvertretung nicht nur bei Gelegenheit betra, Ordnet öffentliche und nicht öffentliche Registerangaben, personenbezogene Daten. L... |
| `bussgeld-pruefverfahren-quartalsmonitor` | Bussgeld Pruefverfahren Quartalsmonitor im Lobbyregister Bundestag: prüft konkret Reaktionsbei RfS-Prüfung, Anhoerung, Bußgeldrisiko nach § 7 LobbyRG und Kodexver, Baut Fristenkalender für unverzuegliche Updates. Liefert priorisierten Ou... |
| `dokumentationsakte-revisionsspur-drehtuer` | Dokumentationsakte Revisionsspur Drehtuer im Lobbyregister Bundestag: prüft konkret Baut Aktenstruktur für Belege, Freigaben, Portal-Screenshots, Kontaktlogs. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schr... |
| `end-to-erstkontakt-offenlegung` | END TO Erstkontakt Offenlegung im Lobbyregister Bundestag: prüft konkret Geführter Gesamtmit 50-Skill-Routing, Formuliert Offenlegung beim erstmaligen Kontakt. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Sch... |
| `erstregistrierung-ausfuellen` | Erstregistrierung Ausfuellen im Lobbyregister Bundestag: prüft konkret Führt Schritt für Schritt durch den Portal-Ersteintrag, Berechnet finanzielle Aufwendungen im Bereich, Personal- un. Liefert priorisierten Output mit Norm-Pinpoints,... |
| `freiwillige-registrierung-fremdmandat` | Freiwillige Registrierung Fremdmandat im Lobbyregister Bundestag: prüft konkret Berät zu freiwilliger Eintragung nach § 2 Abs, Spezialfür Public-Affairs-Agenturen, Kanzleien, Beratungen und Dienstleister mit. Liefert priorisierten Output... |
| `fruehere-interessenvertretung` | Fruehere Interessenvertretung im Lobbyregister Bundestag: prüft konkret Führt durch Anzeige, dass keine registrierungspflichtige Interessenvertretung me, Führt durch die mindestens jaehrliche vollständige. Liefert priorisierten Output mi... |
| `hausausweis-anhoerung-interessen` | Hausausweis Anhoerung Interessen im Lobbyregister Bundestag: prüft konkret Prüft Auswirkungen des Registerstatus auf Tagesausweis, Gebaeudezutritt und Teil, Ordnet Interessen- und Vorhabenbereiche im Register zu und, ob Themen brei. Lief... |
| `intake-mandat-lobbyregister` | Intake Mandat Lobbyregister im Lobbyregister Bundestag: prüft konkret Erfasst Ausgangslage, Organisation, Kontaktplaene, Auftraggeber. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `interessenvertretung-begriff-interne` | Interessenvertretung Begriff Interne im Lobbyregister Bundestag: prüft konkret Prüft, ob eine Kontaktaufnahme unmittelbare oder mittelbare, Erstellt interne Richtlinie für Rollen, Meldewege. Liefert priorisierten Output mit Norm-Pinpoint... |
| `jahresabschluss-rechenschaftsbericht-konzern` | Jahresabschluss Rechenschaftsbericht Konzern im Lobbyregister Bundestag: prüft konkret Prüft Bereitstellung von Jahresabschluss oder, Umgang mit n, Strukturiert Lobbyregisterfragen bei Konzernen, Verbaenden. Liefert priorisierten Output... |
| `lobbyregister-bundestag-kaltstart-triage` | Einstieg, Schnelltriage und Fallrouting im Lobbyregister Bundestag-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Fachmodule aus diesem Plugin vor und führt in einen klaren Arbeitsplan. Bei... |
| `lobbyregister-hauptfinanzierungsquellen-angaben` | Hauptfinanzierungsquellen Angaben im Lobbyregister Bundestag: prüft konkret Strukturiert Hauptfinanzierungsquellen nach § 3 LobbyRG und, Bei, Prüft, ob eine Geschäftsstelle am Sitz von Bundestag und. Liefert priorisierten Output mit Norm... |
| `mitgliedschaften-mitgliederzahl-nicht` | Mitgliedschaften Mitgliederzahl Nicht im Lobbyregister Bundestag: prüft konkret Erfasst Mitgliederzahl, mitgliedschaftliche Organisation und relevante Mitglieds, Prüft Kennzeichnung nicht aktualisiert, Nachholfristen. Liefert priorisiert... |
| `oeffentliche-zuwendungen-personen` | Oeffentliche Zuwendungen Personen im Lobbyregister Bundestag: prüft konkret Prüft Zuwendungen und Zuschuesse der deutschen öffentlichen, Mitgliedst, Bestimmt, ob natuerliche Person. Liefert priorisierten Output mit Norm-Pinpoints, Risiko... |
| `registereintrag-finalcheck-registerfuehrende` | Registereintrag Finalcheck Registerfuehrende im Lobbyregister Bundestag: prüft konkret Prüft vor Freigabe Vollständigkeit, Richtigkeit, Aktualitaet, Irreführungsfreihe. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näc... |
| `registrierungspflicht-schenkungen-sponsoring` | Registrierungspflicht Schenkungen Sponsoring im Lobbyregister Bundestag: prüft konkret Prüft § 2 Abs, Prüft Schenkungen und sonstige lebzeitige Zuwendungen, Gesamtstufe, Einz. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel... |
| `stellungnahmen-gutachten-suche-open` | Stellungnahmen Gutachten Suche Open im Lobbyregister Bundestag: prüft konkret Prüft Bereitstellungspflicht für grundlegende, Nutzt Suche, Standardlisten, Open Data und API zur Markt-. Liefert priorisierten Output mit Norm-Pinpoints, Risi... |
| `taetigkeitsbeschreibung-unterauftragnehmer` | Taetigkeitsbeschreibung Unterauftragnehmer im Lobbyregister Bundestag: prüft konkret Formuliert die allgemeine Tätigkeit der, nicht irrefüh, Prüft Unterauftragsverhältnisse, eingesetzte Organisationen und natuerliche Pers. Liefert priori... |
| `verhaltenskodex-integritaet-verstoesse-melden` | Verhaltenskodex Integritaet Verstoesse Melden im Lobbyregister Bundestag: prüft konkret Operationalisiert Offenheit, Transparenz, Ehrlichkeit und Integritaet nach § 5 L, Führt durch Meldung möglicher Verstoesse gegen. Liefert priorisiert... |
| `vertretungsberechtigte-personen-visitenkarte` | Vertretungsberechtigte Personen Visitenkarte im Lobbyregister Bundestag: prüft konkret Ermittelt gesetzliche Vertretungen, Leitungspersonen und Zeichnungsberechtigte f, Nutzt die Lobbyregister-Visitenkarte, Registerauszug und interne Nac... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
