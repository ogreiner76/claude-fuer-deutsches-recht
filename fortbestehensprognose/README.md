# Fortbestehensprognose

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`fortbestehensprognose`) | [`fortbestehensprognose.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/fortbestehensprognose.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Fortbestehensprognose Paragrafix GmbH** (`fortbestehensprognose-paragrafix-gmbh`) | [Gesamt-PDF lesen](../testakten/fortbestehensprognose-paragrafix-gmbh/gesamt-pdf/fortbestehensprognose-paragrafix-gmbh_gesamt.pdf) | [`testakte-fortbestehensprognose-paragrafix-gmbh.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-fortbestehensprognose-paragrafix-gmbh.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Fortbestehensprognose nach § 19 Abs. 2 InsO als Geschäftsführer-Selbstdokumentation. Prüfablauf Bilanzstatus Annahmen Plausibilisierung 12-Monats-Liquidität. Sanierungsbausteine harte Patronatserklärung Comfortletter Gesellschafterdarlehen Rangrücktritt Stundung Forderungsverzicht. IDW S 11 S 6 StaRUG. Funktioniert allein; empfohlene Begleitplugins liquiditätsplanung (wochenbasierte Liquidität) und insolvenzrecht (§ 17 § 18 InsO Antragspflicht).

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `annahmen-belastbarkeit-plausibilisieren` | Plausibilisiert die in `annahmen-sammeln-fortfuehrung` gesammelten Annahmen. Prüfraster Konsistenz mit Vergangenheit (BWA SuSa Jahresabschluss) Marktentwicklung (Branche makroekonomisch) Konsistenz untereinander (Ums… |
| `annahmen-sammeln-fortfuehrung` | Sammelt die Annahmen die der Geschäftsführer der Fortbestehensprognose zu Grunde legt. Umsatzentwicklung Kostenentwicklung Personalkostenentwicklung Investitionen Working-Capital Saisonalität Auftragsbestand Kunden… |
| `ausloesendes-ereignis-erfassen` | Erfasst den Anlass der Fortbestehensprognose. Typische Auslöser sind Hinweis des Steuerberaters nach § 102 StaRUG Hinweis des Wirtschaftsprüfers Bekanntwerden negativen Eigenkapitals Bilanzaufstellung mit negativem … |
| `bilanzieller-status-aufnehmen` | Nimmt die bilanzielle Ausgangslage auf — Aktiva Passiva Eigenkapital nach HGB-Stichtagsbilanz. Prüfraster bilanzielle Überschuldung (Aktiva kleiner als Passiva). Erfasst stille Reserven und stille Lasten Sonderposte… |
| `comfortletter-weich-erzeugen` | Erzeugt einen Comfortletter — eine weiche Erklärung des Patrons oder Mutterunternehmens das Tochterunternehmen zu unterstützen. Im Gegensatz zur harten externen Patronatserklärung ist der Comfortletter nicht rechts… |
| `forderungsverzicht-besserungsschein` | Erzeugt eine Forderungsverzichtsvereinbarung mit Besserungsschein. Gläubiger verzichtet auf Forderung — bei Wiedererstarken der Zahlungsfähigkeit der Schuldnerin lebt die Forderung wieder auf. Effekt im insolvenzrec… |
| `fortbestehensprognose-zusammenfuehren` | Führt alle Bausteine zusammen — bilanzieller Status Annahmen Plausibilisierung 12-Monats-Liquidität Sensitivitätsszenarien — und bewertet ob die Fortbestehensprognose nach § 19 Abs. 2 InsO positiv ist. Massstab ueb… |
| Rechtsprechung live prüfen | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| `fortbestehensprognose-kaltstart-interview` | Kaltstart-Interview für das Fortbestehensprognose-Plugin. Stellt fest wer das Plugin nutzt (Geschäftsführer / Vorstand / Gesellschafter mit Eigenverantwortung / Finanzleiter mit Mandat) wer der Anwaltliche und steu… |
| `liquiditaet-12-monate` | Erstellt die rollierende Zwölf-Monats-Liquiditätsvorschau auf Basis der plausibilisierten Annahmen. Pro Woche oder pro Monat Aufstellung der Einzahlungen und Auszahlungen Anfangsbestand Endbestand Linieverbleib. Pru… |
| `patronatserklaerung-extern-hart-erzeugen` | Erzeugt eine harte externe Patronatserklärung des Gesellschafters (oder eines Dritten) zugunsten der Gesellschaft. Erfasst Patron Begueneten Höhe Bedingungen Laufzeit Insolvenzfeste Klausel. Zur Berücksichtigung im… |
| `prognose-dokumentation-stichtag` | Abschließende Selbstdokumentation der Fortbestehensprognose zum konkreten Stichtag. Enthält Ausgangslage Annahmen Plausibilisierung Liquidität Szenarien Sanierungsbausteine mit Belegen Gesamtergebnis. Dient als Bel… |
| `sanierungsbausteine-vorschlagen` | Wenn die Fortbestehensprognose ohne Maßnahmen negativ oder knapp positiv ist schlägt dieser Skill konkrete Sanierungsbausteine vor. Auswahl Patronatserklärung hart Comfortletter Gesellschafterdarlehen mit Rangrück… |
| `stundungsanfrage-glaeubiger` | Erzeugt Stundungsanfragen an Gläubiger (Lieferanten Bank Vermieter Steueramt Sozialversicherungsträger). Erfasst pro Gläubiger Forderungshöhe Fälligkeit Stundungswunsch (neue Fälligkeit Ratenzahlung Tilgungspaus… |
| `wenn-prognose-negativ-naechste-schritte` | Wenn die Fortbestehensprognose negativ ausfällt — Eskalations- und Pflichtenkatalog für den Geschäftsleiter. Antragspflicht § 15a InsO sechs Wochen bei Überschuldung drei Wochen bei Zahlungsunfähigkeit. Zahlungsv… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `annahmen-sammeln-bilanzieller-status` | Nutze dies bei Annahmen Sammeln Fortfuehrung, Bilanzieller Status Aufnehmen, Comfortletter Weich Erzeugen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `comfortletter-sonderfall-edge` | Nutze dies bei Comfortletter Internationaler Bezug Und Schnittstellen, Eskalation Sonderfall Und Edge Case, Forderungsverzicht Mandantenentscheidung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `fbp-bankenkommunikation-fbp-integrierte-fbp` | Nutze dies bei Fbp Bankenkommunikation Waiver Spezial, Fbp Integrierte Planung Bauleiter, Fbp Stresstest Szenarien Leitfaden: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbare... |
| `fbp-zahlungsunfaehigkeit` | Nutze dies bei Fbp Zahlungsunfaehigkeit Ueberschuldungsabgrenzung Spezial, Fortbestehensprognose Zusammenfuehren, Fp Cash Flow Modell Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nä... |
| `fortbestehensdokumentation-insolvenzrecht` | Nutze dies bei Fortbestehensdokumentation Insolvenzrecht, Fortbestehensprognose Erstpruefung Und Mandatsziel, Inso Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `fortbestehensprognose-kaltstart-interview` | Kaltstart-Interview für das Fortbestehensprognose-Plugin. Stellt fest wer das Plugin nutzt (Geschäftsführer / Vorstand / Gesellschafter mit Eigenverantwortung / Finanzleiter mit Mandat) wer der Anwaltliche und steuerliche Ansprechpartner... |
| `fp-gerichtsfaehigkeit-fp-einfuehrung-fp` | Nutze dies bei Fp Dokumentation Gerichtsfaehigkeit Spezial, Fp Einfuehrung Pflicht Und Zweck, Fp Zeitraum Und Szenarien Praxis: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastba... |
| `gesellschafterdarlehen-rangruecktritt` | Nutze dies bei Gesellschafterdarlehen Rangruecktritt, Liquiditaet 12 Monate, Patronatserklaerung Extern Hart Erzeugen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbei... |
| `liquiditaet-patronatserklaerung-interessen` | Nutze dies bei Liquiditaet Zahlen Schwellen Und Berechnung, Patronatserklaerung Mehrparteien Konflikt Und Interessen, Plausibilisierung Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passen... |
| `mandantenkommunikation-redteam` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Geschaeftsfuehrer Fristen Form Und Zustaendigkeit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `monats-quellenkarte` | Nutze dies zur Quellenprüfung bei Monats Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `negativer-fristennotiz-ausloesendes-ereignis` | Nutze dies bei Negativer Fristennotiz Und Naechster Schritt, Ausloesendes Ereignis Erfassen, Forderungsverzicht Besserungsschein: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belast... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `prognose-stichtag-stundungsanfrage-glaeubiger` | Nutze dies bei Prognose Dokumentation Stichtag, Stundungsanfrage Glaeubiger, Annahmen Belastbarkeit Plausibilisieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `rangruecktritt-sanierungsbausteine` | Nutze dies bei Rangruecktritt Formular Portal Und Einreichung, Sanierungsbausteine Compliance Dokumentation Und Akte, Selbstdokumentation Dokumentenmatrix Und Lueckenliste: führt durch diese fachlich verbundenen Module, wählt den passend... |
| `sanierungsbausteine-vorschlagen-annahmen` | Nutze dies bei Sanierungsbausteine Vorschlagen, Annahmen Behörden Gericht Und Registerweg, Bilanzstatus Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `starug-beweislast-stundung-red-zwoelf` | Nutze dies bei Starug Beweislast Und Darlegungslast, Stundung Red Team Und Qualitaetskontrolle, Zwoelf Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näch... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `wenn-prognose` | Nutze dies bei Wenn Prognose Negativ Naechste Schritte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
