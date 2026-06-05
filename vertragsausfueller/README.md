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
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `changes-beweislast-docx-erkennen` | Nutze dies bei Changes Beweislast Und Darlegungslast, Docx Tatbestand Beweis Und Belege, Erkennen Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `erzeugen-red-fassungen-sonderfall-felder` | Nutze dies bei Erzeugen Red Team Und Qualitaetskontrolle, Fassungen Sonderfall Und Edge Case, Felder Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten b... |
| `fuehren-interessen-mappen-nachfrage` | Nutze dies bei Fuehren Mehrparteien Konflikt Und Interessen, Mappen Zahlen Schwellen Und Berechnung, Nachfrage Abschlussprodukt Und Uebergabe: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nä... |
| `mandantenkommunikation-redteam-qualitygate` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Ausdruecklicher Fristennotiz Und Naechster Schritt: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `neue-rueckfragen-strippen` | Nutze dies bei Neue Internationaler Bezug Und Schnittstellen, Rueckfragen Compliance Dokumentation Und Akte, Strippen Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `sheets-quellenkarte` | Nutze dies zur Quellenprüfung bei Sheets Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `term-track-vertraege` | Nutze dies bei Term Verhandlung Vergleich Und Eskalation, Track Mandantenkommunikation Entscheidungsvorlage, Vertraege Formular Portal Und Einreichung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefe... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `vaf-batch-vaf-docx-vaf-einfuehrung` | Nutze dies bei Vaf Batch Modus Konzern, Vaf Docx Stripper, Vaf Einfuehrung Prozess: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vaf-bsag-vaf-klauselentscheidung-vaf-konzern` | Nutze dies bei Vaf Bsag Mietvertrag, Vaf Klauselentscheidung, Vaf Konzern Rahmenvertrag Anpassen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vaf-clean-output` | Sauberen finalen Vertragsentwurf mit Ausfüllprotokoll erstellen: Anwendungsfall alle Felder sind ausgefüllt und Quality Gate hat grüne Ampel ergeben; nun wird bereinigte Clean-Version für Unterschrift oder Versand erstellt. §§ 125 ff. BG... |
| `vaf-feldinventar-vaf-fragebogen-vaf` | Nutze dies bei Vaf Feldinventar, Vaf Fragebogen Input Leitfaden, Vaf Fremdsprachige Vertraege Bilingual: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vaf-plausibilitaetscheck-vaf-termsheet` | Nutze dies bei Vaf Plausibilitaetscheck, Vaf Termsheet Mapping, Altvertraege Dokumentenmatrix Und Lueckenliste: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vaf-quality-vaf-redline-vaf` | Nutze dies bei Vaf Quality Gate, Vaf Redline Qa, Vaf Rueckfrageninterview: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vaf-template-vaf-template-vaf-track` | Nutze dies bei Vaf Template Erkennung, Vaf Template Format Und Source, Vaf Track Changes Nur Nach Frage: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vaf-vaf-mehrsprachige-vaf-platzhalterlogik` | Nutze dies bei Vaf Kommandocenter, Vaf Mehrsprachige Vertraege Spezial, Vaf Platzhalterlogik Bauleiter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vaf-versionierung` | Nutze dies bei Vaf Versionierung Aenderungsverfolgung Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vorlagen-vertragsausfueller-vaf-altvertrag` | Nutze dies bei Vorlagen Fristen Form Und Zustaendigkeit, Vertragsausfueller Erstpruefung Und Mandatsziel, Vaf Altvertrag Nachziehen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bel... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
