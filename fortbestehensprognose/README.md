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
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflow... |
| `annahmen-sammeln-bilanzieller-status` | Nutze dies, wenn Annahmen Sammeln Fortfuehrung, Bilanzieller Status Aufnehmen, Comfortletter Weich Erzeugen im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Bitte Annahmen Sammeln Fortfuehrung, Bilanzieller Statu... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Fortbestehensprognose.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `comfortletter-sonderfall-edge` | Nutze dies, wenn Spezial Comfortletter Internationaler Bezug Und Schnittstellen, Spezial Eskalation Sonderfall Und Edge Case, Spezial Forderungsverzicht Mandantenentscheidung im Plugin Fortbestehensprognose konkret bearbeitet werden soll... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Fortbestehensprognose.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `fbp-bankenkommunikation-fbp-integrierte-fbp` | Nutze dies, wenn Fbp Bankenkommunikation Waiver Spezial, Fbp Integrierte Planung Bauleiter, Fbp Stresstest Szenarien Leitfaden im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Bitte Fbp Bankenkommunikation Waiver... |
| `fbp-zahlungsunfaehigkeit` | Nutze dies, wenn Fbp Zahlungsunfaehigkeit Ueberschuldungsabgrenzung Spezial, Fortbestehensprognose Zusammenfuehren, Fp Cash Flow Modell Spezial im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Bitte Fbp Zahlungsu... |
| `fortbestehensdokumentation-insolvenzrecht` | Nutze dies, wenn Spezial Fortbestehensdokumentation Insolvenzrecht, Spezial Fortbestehensprognose Erstpruefung Und Mandatsziel, Spezial Inso Tatbestand Beweis Und Belege im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Aus... |
| `fortbestehensprognose-kaltstart-interview` | Kaltstart-Interview für das Fortbestehensprognose-Plugin. Stellt fest wer das Plugin nutzt (Geschäftsführer / Vorstand / Gesellschafter mit Eigenverantwortung / Finanzleiter mit Mandat) wer der Anwaltliche und steuerliche Ansprechpartner... |
| `fp-gerichtsfaehigkeit-fp-einfuehrung-fp` | Nutze dies, wenn Fp Dokumentation Gerichtsfaehigkeit Spezial, Fp Einfuehrung Pflicht Und Zweck, Fp Zeitraum Und Szenarien Praxis im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Bitte Fp Dokumentation Gerichtsfae... |
| `gesellschafterdarlehen-rangruecktritt` | Nutze dies, wenn Gesellschafterdarlehen Rangruecktritt, Liquiditaet 12 Monate, Patronatserklaerung Extern Hart Erzeugen im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Bitte Gesellschafterdarlehen Rangruecktritt... |
| `liquiditaet-patronatserklaerung-interessen` | Nutze dies, wenn Spezial Liquiditaet Zahlen Schwellen Und Berechnung, Spezial Patronatserklaerung Mehrparteien Konflikt Und Interessen, Spezial Plausibilisierung Schriftsatz Brief Und Memo Bausteine im Plugin Fortbestehensprognose konkre... |
| `mandantenkommunikation-redteam` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Geschaeftsfuehrer Fristen Form Und Zustaendigkeit im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen... |
| `monats-quellenkarte` | Nutze dies, wenn Monats Quellenkarte im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `negativer-fristennotiz-ausloesendes-ereignis` | Nutze dies, wenn Spezial Negativer Fristennotiz Und Naechster Schritt, Ausloesendes Ereignis Erfassen, Forderungsverzicht Besserungsschein im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Bitte Spezial Negativer... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `prognose-stichtag-stundungsanfrage-glaeubiger` | Nutze dies, wenn Prognose Dokumentation Stichtag, Stundungsanfrage Glaeubiger, Annahmen Belastbarkeit Plausibilisieren im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Bitte Prognose Dokumentation Stichtag, Stund... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `rangruecktritt-sanierungsbausteine` | Nutze dies, wenn Spezial Rangruecktritt Formular Portal Und Einreichung, Spezial Sanierungsbausteine Compliance Dokumentation Und Akte, Spezial Selbstdokumentation Dokumentenmatrix Und Lueckenliste im Plugin Fortbestehensprognose konkret... |
| `sanierungsbausteine-vorschlagen-annahmen` | Nutze dies, wenn Sanierungsbausteine Vorschlagen, Spezial Annahmen Behörden Gericht Und Registerweg, Spezial Bilanzstatus Risikoampel Und Gegenargumente im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Bitte Sani... |
| `starug-beweislast-stundung-red-zwoelf` | Nutze dies, wenn Spezial Starug Beweislast Und Darlegungslast, Spezial Stundung Red Team Und Qualitaetskontrolle, Spezial Zwoelf Verhandlung Vergleich Und Eskalation im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöse... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `wenn-prognose` | Nutze dies, wenn Wenn Prognose Negativ Naechste Schritte im Plugin Fortbestehensprognose konkret bearbeitet werden soll. Auslöser: Bitte Wenn Prognose Negativ Naechste Schritte prüfen.; Erstelle eine Arbeitsfassung zu Wenn Prognose Negat... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
