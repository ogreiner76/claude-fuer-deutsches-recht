# Vertragsausfüller

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`vertragsausfueller`) | [`vertragsausfueller.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/vertragsausfueller.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Vertragsausfueller - BSAG Kiosk Huckelriede** (`vertragsausfueller-bsag-kiosk-huckelriede`) | [Gesamt-PDF lesen](../testakten/vertragsausfueller-bsag-kiosk-huckelriede/gesamt-pdf/vertragsausfueller-bsag-kiosk-huckelriede_gesamt.pdf) | [`testakte-vertragsausfueller-bsag-kiosk-huckelriede.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-vertragsausfueller-bsag-kiosk-huckelriede.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Cowork-Plugin für workflowgestütztes Ausfüllen von Vertragsvorlagen und Altverträgen. Ein Nutzer lädt eine Word-Vorlage, einen alten Vertrag, ein Term Sheet oder Freitextdaten hoch. Das Plugin strippt das Dokument, erkennt Felder und Klauseln, fragt fehlende Daten ab, mappt Term-Sheet-Daten auf Vertragsfelder und erstellt daraus einen neuen Vertragsentwurf.

Der BSAG-Mietvertrag und das Term Sheet Kiosk Huckelriede sind als Beispielakte eingebunden.

## Installation

1. Claude Code oder Claude Desktop/Cowork öffnen.
2. **Customize Plugins** bzw. **Personal plugins** wählen.
3. **Install from .zip** und `vertragsausfueller.zip` hochladen.
4. Mit einem konkreten Auftrag starten, zum Beispiel: `Fülle diesen Mietvertrag mit den Daten aus dem Term Sheet aus.`

Alternativ via Marketplace:

```
/plugin marketplace add Klotzkette/claude-fuer-deutsches-recht
/plugin install vertragsausfueller@claude-fuer-deutsches-recht
```

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json`, `skills/` und `assets/` enthalten.

## Workflow

1. Vorlage oder alten Vertrag hochladen.
2. Dokument strippen: Absätze, Tabellen, Platzhalter, Klauseln, Anlagen und Signaturen erkennen.
3. Term Sheet, E-Mail oder Freitextdaten danebenlegen.
4. Feldinventar und Mapping erzeugen.
5. Fehlende Daten freundlich abfragen oder als offene Platzhalter markieren.
6. Clean-Vertrag erstellen.
7. Nur auf ausdrückliche Nachfrage zusätzlich Track Changes oder Redline vorbereiten.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| vaf-kommandocenter | steuert den gesamten Workflow von Upload bis neuem Vertragsentwurf. |
| vaf-docx-stripper | macht aus Word-Dokumenten ein bearbeitbares Vertragsmodell. |
| vaf-template-erkennung | klassifiziert den Vertrag und trennt Fixtext von Variablen. |
| vaf-feldinventar | baut die zentrale Datenmatrix für den Vertrag. |
| vaf-termsheet-mapping | überführt wirtschaftliche Eckdaten in Vertragsklauseln. |
| vaf-rueckfrageninterview | füllt Datenlücken ohne den Nutzer zu überfordern. |
| vaf-bsag-mietvertrag | setzt den Huckelriede-Term-Sheet-Fall in die BSAG-Vorlage um. |
| vaf-klauselentscheidung | verhindert stilles Auswählen riskanter Optionen. |
| vaf-plausibilitaetscheck | härtet den Entwurf vor Versand oder Verhandlung. |
| vaf-clean-output | liefert den ersten belastbaren Vertragsentwurf. |
| vaf-track-changes-nur-nach-frage | setzt die ausdrückliche Nachfragepflicht durch. |
| vaf-redline-qa | kontrolliert Änderungsfassungen vor Herausgabe. |
| vaf-altvertrag-nachziehen | macht aus alten Verträgen neue Entwürfe. |
| vaf-quality-gate | ist die letzte Schleuse vor Vertragserzeugung. |

## BSAG-Beispiel

Die Beispielakte enthält die Word-Vorlage `BSAG-Mietvertrag-Vorlage.docx` und das Term Sheet `BSAG-TermSheet-Kiosk-Huckelriede - Kopie.docx`. Der Spezialskill `vaf-bsag-mietvertrag` mappt daraus insbesondere Mieter, Mietobjekt, Nutzung, Fläche, Miete, Nebenkosten, Kaution, Mietbeginn, Laufzeit, Optionen, Indexierung, Umsatzsteuer, Öffnungszeiten, Konkurrenzschutz, Sortiment, Fettabscheider, Werbung und Versicherung.

## Track-Changes-Regel

Das Plugin erzeugt keine Track-Changes- oder Redline-Fassung stillschweigend. Es fragt immer ausdrücklich: Soll zusätzlich eine Track-Changes- oder Redline-Fassung erstellt werden? Ohne Bestätigung bleibt es bei Clean-Entwurf, Änderungslog und Ausfüllprotokoll.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fri... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Vertragsausfueller.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `changes-beweislast-docx-erkennen` | Nutze dies, wenn Spezial Changes Beweislast Und Darlegungslast, Spezial Docx Tatbestand Beweis Und Belege, Spezial Erkennen Schriftsatz Brief Und Memo Bausteine im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Bitte... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Vertragsausfueller.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `erzeugen-red-fassungen-sonderfall-felder` | Nutze dies, wenn Spezial Erzeugen Red Team Und Qualitaetskontrolle, Spezial Fassungen Sonderfall Und Edge Case, Spezial Felder Behörden Gericht Und Registerweg im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Was ka... |
| `fuehren-interessen-mappen-nachfrage` | Nutze dies, wenn Spezial Fuehren Mehrparteien Konflikt Und Interessen, Spezial Mappen Zahlen Schwellen Und Berechnung, Spezial Nachfrage Abschlussprodukt Und Übergabe im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser:... |
| `mandantenkommunikation-redteam-qualitygate` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Ausdruecklicher Fristennotiz Und Naechster Schritt im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?;... |
| `neue-rueckfragen-strippen` | Nutze dies, wenn Spezial Neue Internationaler Bezug Und Schnittstellen, Spezial Rueckfragen Compliance Dokumentation Und Akte, Spezial Strippen Risikoampel Und Gegenargumente im Plugin Vertragsausfueller konkret bearbeitet werden soll. A... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `sheets-quellenkarte` | Nutze dies, wenn Sheets Quellenkarte im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `term-track-vertraege` | Nutze dies, wenn Spezial Term Verhandlung Vergleich Und Eskalation, Spezial Track Mandantenkommunikation Entscheidungsvorlage, Spezial Vertraege Formular Portal Und Einreichung im Plugin Vertragsausfueller konkret bearbeitet werden soll.... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `vaf-batch-vaf-docx-vaf-einfuehrung` | Nutze dies, wenn Vaf Batch Modus Konzern, Vaf Docx Stripper, Vaf Einfuehrung Prozess im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Bitte Vaf Batch Modus Konzern, Vaf Docx Stripper, Vaf Einfuehrung Prozess prüfen.... |
| `vaf-bsag-vaf-klauselentscheidung-vaf-konzern` | Nutze dies, wenn Vaf Bsag Mietvertrag, Vaf Klauselentscheidung, Vaf Konzern Rahmenvertrag Anpassen im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Bitte Vaf Bsag Mietvertrag, Vaf Klauselentscheidung, Vaf Konzern Ra... |
| `vaf-clean-output` | Sauberen finalen Vertragsentwurf mit Ausfüllprotokoll erstellen: Anwendungsfall alle Felder sind ausgefüllt und Quality Gate hat grüne Ampel ergeben; nun wird bereinigte Clean-Version für Unterschrift oder Versand erstellt. §§ 125 ff. BG... |
| `vaf-feldinventar-vaf-fragebogen-vaf` | Nutze dies, wenn Vaf Feldinventar, Vaf Fragebogen Input Leitfaden, Vaf Fremdsprachige Vertraege Bilingual im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Bitte Vaf Feldinventar, Vaf Fragebogen Input Leitfaden, Vaf... |
| `vaf-plausibilitaetscheck-vaf-termsheet` | Nutze dies, wenn Vaf Plausibilitaetscheck, Vaf Termsheet Mapping, Spezial Altvertraege Dokumentenmatrix Und Lueckenliste im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Bitte Vaf Plausibilitaetscheck, Vaf Termsheet... |
| `vaf-quality-vaf-redline-vaf` | Nutze dies, wenn Vaf Quality Gate, Vaf Redline Qa, Vaf Rueckfrageninterview im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe... |
| `vaf-template-vaf-template-vaf-track` | Nutze dies, wenn Vaf Template Erkennung, Vaf Template Format Und Source, Vaf Track Changes Nur Nach Frage im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Bitte Vaf Template Erkennung, Vaf Template Format Und Source... |
| `vaf-vaf-mehrsprachige-vaf-platzhalterlogik` | Nutze dies, wenn Vaf Kommandocenter, Vaf Mehrsprachige Vertraege Spezial, Vaf Platzhalterlogik Bauleiter im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Bitte Vaf Kommandocenter, Vaf Mehrsprachige Vertraege Spezial... |
| `vaf-versionierung` | Nutze dies, wenn Vaf Versionierung Aenderungsverfolgung Spezial im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Bitte Vaf Versionierung Aenderungsverfolgung Spezial prüfen.; Erstelle eine Arbeitsfassung zu Vaf Vers... |
| `vorlagen-vertragsausfueller-vaf-altvertrag` | Nutze dies, wenn Spezial Vorlagen Fristen Form Und Zustaendigkeit, Spezial Vertragsausfueller Erstpruefung Und Mandatsziel, Vaf Altvertrag Nachziehen im Plugin Vertragsausfueller konkret bearbeitet werden soll. Auslöser: Bitte Spezial Vo... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
