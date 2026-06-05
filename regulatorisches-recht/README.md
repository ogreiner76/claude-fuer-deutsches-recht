# Regulatorisches Recht – Plugin für deutsches Aufsichtsrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`regulatorisches-recht`) | [`regulatorisches-recht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/regulatorisches-recht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **BaFin-Sonderprüfung Thalvenia Bank AG — Kryptoverwahrung, AML-Pflichtverletzungen, MiCAR-Lizenzkrise** (`bafin-verfahren-kryptoverwahrung-thalvenia-bank-aufsichtsverletzung-stuttgart`) | [Gesamt-PDF lesen](../testakten/bafin-verfahren-kryptoverwahrung-thalvenia-bank-aufsichtsverletzung-stuttgart/gesamt-pdf/bafin-verfahren-kryptoverwahrung-thalvenia-bank-aufsichtsverletzung-stuttgart_gesamt.pdf) | [`testakte-bafin-verfahren-kryptoverwahrung-thalvenia-bank-aufsichtsverletzung-stuttgart.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bafin-verfahren-kryptoverwahrung-thalvenia-bank-aufsichtsverletzung-stuttgart.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Überwacht Aufsichts-Feeds, vergleicht neue Regulierungsakte gegen Ihre Richtlinienbibliothek und identifiziert Lücken. Lernt Ihre Materialitätsschwelle, damit keine Meldung bei jeder Pressemitteilung erfolgt. Ausgelegt für BaFin-Newsroom, Bundesgesetzblatt, EUR-Lex und direkte Behörden-Feeds.

**Jede Ausgabe ist ein Entwurf zur anwaltlichen Prüfung – zitiert, markiert und freigabepflichtig – keine Rechtsauskunft.** Das Plugin übernimmt die Arbeit: liest Dokumente, wendet Ihr Regelwerk an, findet Lücken, erstellt Vermerke. Ein Rechtsanwalt prüft, verifiziert und entscheidet. Zitate werden nach Quelle gekennzeichnet. Privilegierungsvermerke werden konservativ gesetzt, damit kein unbeabsichtigter Verzicht entsteht. Folgenreiche Handlungen – Einreichungen, Versendungen, Ausführungen – erfordern ausdrückliche Bestätigung.

## Für wen dieses Plugin gedacht ist

| Rolle | Primäre Abläufe |
|---|---|
| **Compliance-/Aufsichtsrechtler** | Beobachtungsliste, Gap-Triage, Richtlinienaktualisierung |
| **Datenschutz-/Produktjurist** | Gefilterte Alerts für das eigene Gebiet |
| **GC / Chefjustitiar** | Eskalationsempfänger bei wesentlichen Lücken mit Fristen |

## Erster Start: Kaltstart

Fragt ab, welche Behörden Sie beobachten, verbindet Ihren Richtlinienordner und erlernt, was "wesentlich" bedeutet. Erstellt eine Beobachtungsliste und indiziert Ihre Richtlinienbibliothek.

```
/regulatorisches-recht:regulatorisches-recht-kaltstart-interview
```

## Skills

| Skill | Funktion |
|---|---|
| `/regulatorisches-recht:regulatorisches-recht-kaltstart-interview` | Ersteinrichtung: Beobachtungsliste + Richtlinienindex + Materialitätsschwelle |
| `/regulatorisches-recht:aufsichts-feed-monitor` | Feeds jetzt prüfen, Neues melden |
| `/regulatorisches-recht:richtlinien-vergleich [Norm]` | Diff einer konkreten Rechtsänderung gegen die Richtlinienbibliothek |
| `/regulatorisches-recht:luecken` | Offener Gap-Tracker – was wurde gemeldet und noch nicht geschlossen? |
| `/regulatorisches-recht:stellungnahmen` | Offene Konsultationszeiträume prüfen, Entscheidungen protokollieren, Fristen verfolgen |
| `/regulatorisches-recht:richtlinien-neufassung` | Vorgeschlagene Richtlinienneufassung, die eine Lücke schließt – Erstentwurf zur internen Prüfung, kein direktes Bearbeiten von Quelldokumenten |
| `/regulatorisches-recht:regulatorisches-recht-mandat-arbeitsbereich` | Mandats-Workspaces verwalten (nur Multi-Mandantenpraxis) – neu, auflisten, wechseln, schließen, keiner |
| **luecken-aufzeiger** *(Referenz)* | Gemeinsames Gap- und Kommentar-Tracker-Framework, das von `/luecken` und `/stellungnahmen` geladen wird |

## Interaktive Skills vs. geplante Agenten

Die obigen Skills werden bei Aufruf ausgeführt – für die aktive Arbeit an einem Mandat. Die folgenden Agenten laufen planmäßig – für das, was sich bewegt, wenn Sie nicht hinsehen:

| Agent | Was er beobachtet | Standardrhythmus |
|---|---|---|
| **regulierungs-aenderungs-monitor** | Aufsichts-Feeds – filtert nach der bei der Ersteinrichtung erlernten Materialitätsschwelle und erstellt ein Digest aus Signal statt Rauschen | Wöchentlich (täglich bei aktivem regulatorischen Umfeld) |

## Konnektoren und Zitatverifizierung

**Zuerst ein Recherchewerkzeug verbinden – die Zitier-Schutzregeln bauen darauf auf.** Ohne eines wird jedes Zitat mit `[prüfen]` versehen und die Prüfernotiz über jedem Ergebnis hält fest, dass Quellen nicht verifiziert wurden. Das Plugin arbeitet in beiden Fällen; es übernimmt nur mehr der Verifizierung, wenn ein Recherchewerkzeug verbunden ist.

Die Rechtsrecherche-Konnektoren in diesem Plugin sind nicht nur Datenquellen – sie sind der Unterschied zwischen einem verifizierten Zitat und einem, das Sie prüfen müssen. Ein über einen verbundenen Recherche-Konnektor abgerufenes Zitat ist mit seiner Quelle markiert und rückverfolgbar. Zitate aus Modellwissen oder bloßer Web-Suche werden nicht als zitierfähige Fundstelle ausgegeben, bis Norm, Entscheidung, Randnummer oder Seite gegen eine Primärquelle geprüft sind.

## Integrationsmöglichkeiten

Enthält die allgemeinen Konnektoren in `.mcp.json`:

- **Slack** – Nachrichten suchen, Kanäle lesen, Diskussionen finden
- **Google Drive** – Dokumente suchen, lesen und abrufen

BaFin-Newsroom-RSS, Bundesgesetzblatt-Feed und EUR-Lex-Alerts können als direkte Behörden-Feeds eingebunden werden.

## Voraussetzungen

Eigentümer-Benachrichtigungen (Gap-Zuweisungen, Fristenerinnerungen, Konsultationsalerts) erfordern einen Slack-MCP-Server in Ihrer Umgebung. Ohne einen solchen funktionieren Gap-Tracker und Kommentar-Tracker weiterhin – Benachrichtigungen werden jedoch nicht gepostet, und die Skills markieren ungegatedete Einträge stattdessen im Statusbericht.

## Wie das Plugin lernt

Ihr Praxisprofil unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/regulatorisches-recht/CLAUDE.md` ist nicht statisch – es verbessert sich mit der Nutzung. Skills informieren Sie, wenn eine Ausgabe eine Standardeinstellung verwendet, die Sie anpassen sollten. Der `regulierungs-aenderungs-monitor`-Agent beobachtet die Aufsichts-Feeds und markiert Änderungen gegen Ihre Richtlinienbibliothek. Sie können die Einrichtung erneut ausführen, die Datei direkt bearbeiten oder einem Skill mitteilen, eine neue Position aufzuzeichnen.

## Abgedeckte Normen und Behörden

**Aufsichtsbehörden:** BaFin, Deutsche Bundesbank, BMF, Bundesnetzagentur (BNetzA), BMG, BAFA, BMJ, BMWi/BMWK, EBA, ESMA, EZB/SSM

**Finanzmarktrecht:** KWG, ZAG, WpHG, WpIG, GwG, KAG/KAGB, MaRisk (BaFin-RS 09/2017 i.d.F. 2023), MaBV, BörsG

**Energie- und Telekommunikationsrecht:** EnWG, TKG, MessZV

**Heilmittel-/Gesundheitsrecht:** HeilMWerbG, AMG, MPG/MDR-EU, PatDSG

**Steuerrecht (Verfahren):** UStG, AO, FGO

## Hinweise

- Materialitätsfilterung ist der Mehrwert. Alles ist "technisch eine Regulierungsänderung" – das Plugin lernt, was hier tatsächlich wichtig ist.
- Policy-Diff vergleicht gegen indizierte Richtlinien. Wenn die Richtlinienbibliothek nicht verbunden ist, laufen Diffs gegen eingefügte Inhalte.
- Dies ist die automatisierte Version von `datenschutzrecht/regulierungs-luecken-analyse`. Kombination empfohlen: dieses beobachtet, jenes taucht tiefer ein.

## Konfiguration

Ihre Konfiguration wird unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/regulatorisches-recht/CLAUDE.md` gespeichert und überlebt Plugin-Updates – die Einrichtung wird nur einmal durchgeführt.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 26 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anschluss-router` | Nutze dies bei Allgemein, Anschluss Skills Router, Chronologie Und Belegmatrix, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `aufsichts-feed-monitor` | Aufsichtsbehoerden-Mitteilungen und regulatorische Feeds monitoren und relevante Aenderungen für Mandanten identifizieren. KWG WpHG DORA VAG BaFin-Rundschreiben. Prüfraster: Relevanz für Mandant Umsetzungsfrist Handlungsbedarf Meldepflic... |
| `aufsichtsverfahren-anhoerung-gwg` | Nutze dies bei Aufsichtsverfahren Anhoerung Massnahme, Aufsichtsverfahren Formular Portal Und Einreichung, Gwg Fristen Form Und Zustaendigkeit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den n... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `dora-ikt-vertragspruefung` | IKT-Drittanbietervertraege auf DORA-Konformität prüfen wenn Finanzunternehmen digitale Dienstleistungen einkaufen. Art. 28 30 DORA VO (EU) 2022/2554. Prüfraster: Pflichtklauseln Art. 30 DORA Ausstiegsstrategien Aufsichtsrechte Subdienstl... |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `enwg-feeds-heilmwerbg` | Nutze dies bei Enwg Dokumentenmatrix Und Lueckenliste, Feeds Compliance Dokumentation Und Akte, Heilmwerbg Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächst... |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies bei Fristen Und Risikoampel, Mandantenkommunikation, Redteam Qualitygate: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `inkasso-massnahme-regulator` | Nutze dies bei Inkasso Verhandlung Vergleich Und Eskalation, Massnahme Mandantenkommunikation Entscheidungsvorlage, Regulator Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad un... |
| `inkasso-rdg-luecken-mar-mifid` | Nutze dies bei Inkasso Rdg, Luecken, Mar Mifid Eltif Uebergreifend: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `interview-fristennotiz-aufsichtssanktion` | Nutze dies bei Interview Fristennotiz Und Naechster Schritt, Aufsichtssanktion Revision Spezial, Umsatzsteuer Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den n... |
| `luecken-aufzeiger` | Regulatorische Luecken und Inkonsistenzen in Gesetzentwuerfen oder Regulierungsvorhaben aus Mandantensicht aufzeigen. GG Art. 12 80 AEUV Art. 107. Prüfraster: Normtext Regelungsziele Luecken unbeabsichtigte Folgen Verbesserungsvorschlaeg... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `rdg-quellenkarte` | Nutze dies zur Quellenprüfung bei Rdg Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `regr-dora-resilienz` | Nutze dies bei Regr Dora Resilienz Spezial, Regr Finanzdienstleistungsregulierung Bauleiter, Regr Mica Kryptoassets Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `regr-mifid2-regrecht-einfuehrung-internal` | Nutze dies bei Regr Mifid2 Mar Leitfaden, Regrecht Einfuehrung Sektoren, Regrecht Internal Policies Design: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `regulatorisches-recht-kaltstart-interview` | Neues regulatorisches Mandat durch strukturiertes Erstgespraech aufnehmen. KWG WpHG DORA VAG GwG. Prüfraster: Branche Regulierungsrahmen Sachverhalt Fristen Pflichten Risiko. Output: Mandatssteckbrief Normenkarte fehlende Informationen.... |
| `regulatorisches-richtlinien-neufassung` | Nutze dies bei Regulatorisches Recht Anpassen, Regulatorisches Recht Mandat Arbeitsbereich, Richtlinien Neufassung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitss... |
| `regulatorisches-stellungnahmen-beweislast` | Nutze dies bei Regulatorisches Internationaler Bezug Und Schnittstellen, Stellungnahmen Beweislast Und Darlegungslast, Voranmeldung Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `richtlinien-anhoerung-red-aufsichtsrecht` | Nutze dies bei Richtlinien Vergleich, Anhoerung Red Team Und Qualitaetskontrolle, Aufsichtsrecht Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbar... |
| `sonderfall-edge-case` | Nutze dies bei Kaltstart: Sonderfall und Edge-Case-Prüfung: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `ustva-aufsichtskommunikation-grundregeln-dora` | Nutze dies bei Ustva, Aufsichtskommunikation Grundregeln, Dora Stellvertreter Und Konzern: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `wochendigest-interessen-wphg-stellungnahmen` | Nutze dies bei Wochendigest Mehrparteien Konflikt Und Interessen, Wphg Tatbestand Beweis Und Belege, Stellungnahmen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeits... |
| `wpig-zag` | Nutze dies bei Wpig Und Zag Prüfung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
