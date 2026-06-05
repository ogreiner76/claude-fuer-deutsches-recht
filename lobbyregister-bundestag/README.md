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
| `account-rollen-regelungsvorhaben-erfassen` | Nutze dies bei Portal Account Rollen, Regelungsvorhaben Erfassen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `aktualisierung-unverzueglich-adressatenkreis` | Nutze dies bei Aktualisierung Unverzueglich, Adressatenkreis Bundestag Bundesregierung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `allgemein` | Einstieg, Schnelltriage und Fallrouting im Lobbyregister Bundestag-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Fachmodule aus diesem Plugin vor und führt in einen klaren Arbeitsplan. Bei... |
| `anonymisierung-schutzantrag-auftraggeber` | Nutze dies bei Anonymisierung Schutzantrag, Auftraggeber Ermitteln: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ausnahmen-bundesregierung-ausnahmen-bundestag` | Nutze dies bei Ausnahmen Bundesregierung, Ausnahmen Bundestag: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `benachrichtigungskonto-monitor` | Nutze dies bei Benachrichtigungskonto Monitor, Bestaetigungsdokument Freigabe: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `betraute-personen-datenschutz` | Nutze dies bei Betraute Personen, Datenschutz Nichtoeffentliche Angaben: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `bussgeld-pruefverfahren-quartalsmonitor` | Nutze dies bei Bussgeld Und Pruefverfahren, Fristen Und Quartalsmonitor: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `dokumentationsakte-revisionsspur-drehtuer` | Nutze dies bei Dokumentationsakte Revisionsspur, Drehtuer Angaben: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `end-to-erstkontakt-offenlegung` | Nutze dies bei End To End Registrierungswizard, Erstkontakt Offenlegung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `erstregistrierung-ausfuellen` | Nutze dies bei Erstregistrierung Ausfuellen, Finanzaufwendungen Berechnen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `freiwillige-registrierung-fremdmandat` | Nutze dies bei Freiwillige Registrierung, Fremdmandat Agenturfall: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `fruehere-interessenvertretung` | Nutze dies bei Fruehere Interessenvertretung Exit, Geschaeftsjahresaktualisierung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `hauptfinanzierungsquellen` | Nutze dies bei Hauptfinanzierungsquellen, Hauptstadtrepraesentanz: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `hausausweis-anhoerung-interessen` | Nutze dies bei Hausausweis Und Anhoerung, Interessen Und Vorhabenbereiche: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `intake-mandat-lobbyregister` | Nutze dies bei Lobbyregister Intake Mandat, Lobbyregister Kommandocenter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `interessenvertretung-begriff-interne` | Nutze dies bei Interessenvertretung Begriff, Interne Lobbyregister Richtlinie: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `jahresabschluss-rechenschaftsbericht-konzern` | Nutze dies bei Jahresabschluss Rechenschaftsbericht, Konzern Netzwerk Plattform: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `mitgliedschaften-mitgliederzahl-nicht` | Nutze dies bei Mitgliedschaften Mitgliederzahl, Nicht Aktualisiert Risiko: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `oeffentliche-zuwendungen-personen` | Nutze dies bei Oeffentliche Zuwendungen, Personen Organisationstyp: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `registereintrag-finalcheck-registerfuehrende` | Nutze dies bei Registereintrag Finalcheck, Registerfuehrende Stelle Kontakt: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `registrierungspflicht-schenkungen-sponsoring` | Nutze dies bei Registrierungspflicht Schwellen, Schenkungen Sponsoring: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `stellungnahmen-gutachten-suche-open` | Nutze dies bei Stellungnahmen Gutachten Upload, Suche Open Data Monitor: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `taetigkeitsbeschreibung-unterauftragnehmer` | Nutze dies bei Taetigkeitsbeschreibung, Unterauftragnehmer Erfassen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `verhaltenskodex-integritaet-verstoesse-melden` | Nutze dies bei Verhaltenskodex Integritaet, Verstoesse Melden: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vertretungsberechtigte-personen-visitenkarte` | Nutze dies bei Vertretungsberechtigte Personen, Visitenkarte Und Nachweise: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
