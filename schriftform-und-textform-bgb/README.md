# Schriftform und Textform im BGB

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`schriftform-und-textform-bgb`) | [`schriftform-und-textform-bgb.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/schriftform-und-textform-bgb.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Schriftform-Maklervertrag – Eheleute Haspelbeck-Türkenfeld** (`schriftform-maklervertrag-muenchen-eheleute-haspelbeck`) | [Gesamt-PDF lesen](../testakten/schriftform-maklervertrag-muenchen-eheleute-haspelbeck/gesamt-pdf/schriftform-maklervertrag-muenchen-eheleute-haspelbeck_gesamt.pdf) | [`testakte-schriftform-maklervertrag-muenchen-eheleute-haspelbeck.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-schriftform-maklervertrag-muenchen-eheleute-haspelbeck.zip) |
| **Schriftform der Wohnraumkündigung — Pferdedrescher-Riesenstein ./. Eberhart-Wolframshausen** (`schriftform-mietkuendigung-bielefeld-online-pferdedrescher`) | [Gesamt-PDF lesen](../testakten/schriftform-mietkuendigung-bielefeld-online-pferdedrescher/gesamt-pdf/schriftform-mietkuendigung-bielefeld-online-pferdedrescher_gesamt.pdf) | [`testakte-schriftform-mietkuendigung-bielefeld-online-pferdedrescher.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-schriftform-mietkuendigung-bielefeld-online-pferdedrescher.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

**Plugin-Slug:** `schriftform-und-textform-bgb`
**Version:** 3.2.1
**Autor:** Klotzkette

## Installation

1. ZIP aus dem Release herunterladen.
2. Claude Code oder Claude Desktop/Cowork öffnen.
3. **Customize Plugins** bzw. **Personal plugins** öffnen.
4. **Install from .zip** wählen und `schriftform-und-textform-bgb.zip` hochladen.
5. Mit einem konkreten Auftrag starten, zum Beispiel: `Prüfe ob unser Maklervertrag der Textform § 126b BGB genügt.`

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json` und `skills/` enthalten.

## Überblick

Umfassender Workflow-Organisator für Schriftform- und Textform-Erfordernisse im deutschen Zivilrecht. Das Plugin trennt Papierform, qES, Textform, beA/ERV, gerichtliche Zustellung und prozessuale Formfiktion und bietet kanzleitaugliche Orientierung für alle wesentlichen Formerfordernisse des BGB.

### Leitentscheidungen

- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
- **§ 130e ZPO und § 46h ArbGG seit 17.07.2024** — Formfiktion für klar erkennbare Willenserklärungen in elektronischen vorbereitenden Schriftsätzen, auch wenn elektronische Form materiell eigentlich ausgeschlossen ist.

## Skill-Verzeichnis

### Block A — Formvorschriften-Grundlagen

| Skill | Inhalt |
|-------|--------|
| `formerfordernisse-im-bgb-ueberblick` | Systematik §§ 125-129 BGB, Nichtigkeit § 125 BGB, Heilung |
| `schriftform-paragraph-126-bgb-eigenhaendige-unterschrift` | Originalunterschrift, Namenszeichnung, Faksimile, BGH-Linie |
| `elektronische-form-paragraph-126a-bgb-qes` | qES, eIDAS, Zertifikatskette, Zugang, beA-Abgrenzung, § 130e ZPO und § 46h ArbGG |
| `textform-paragraph-126b-bgb-dauerhafter-datentraeger` | E-Mail, WhatsApp, SMS, PDF als dauerhafter Datenträger |
| `notarielle-beurkundung-und-oeffentliche-beglaubigung` | § 128, § 129 BGB, BeurkG, GmbH, Grundstück, Erbvertrag |

### Block B — Zugang der formgerechten Erklärung

| Skill | Inhalt |
|-------|--------|
| `zugang-empfangsbeduerftiger-willenserklaerung-paragraph-130-bgb` | Zugangslehre, Machtbereich, Annahmeverweigerung |
| `zugang-formgerechter-erklaerung-bgh-viii-zr-159-23` | qES-Zugang, Transfervermerk § 298 Abs. 3 ZPO, Lehrsatz |
| `kuendigung-per-schriftsatz-zustellung-formfragen` | beA, qES, § 130a ZPO, § 130e ZPO, § 46h ArbGG, Zustellung, Vollmacht und § 174 BGB |
| `mandantenwarnung-qes-per-email-whatsapp-und-zugang` | Mandantenmemo: Mail-Anhänge prüfen, IT-Hinweise |

### Block C — Spezielle Formerfordernisse

| Skill | Inhalt |
|-------|--------|
| `maklervertrag-paragraph-656a-bgb-textform-bgh-i-zr-202-25` | § 656a BGB: E-Mail, Signaturhinweis, Textform und Verifizierungspflicht |
| `wohnraummiete-kuendigung-paragraph-568-bgb` | § 568, qES-Zugang, Begründungspflicht, Praxisempfehlung |
| `gewerberaummiete-paragraph-550-bgb-langzeitform` | Langzeitform, Heilung, ordentliche Kündigung bei Verstoß |
| `buergschaft-verbraucherdarlehen-und-andere-strenge-formen` | § 766, § 492, § 311b BGB, strenge Formen |
| `arbeitsrecht-befristung-und-aufhebung-paragraph-14-tzbfg-623-bgb` | § 14 Abs. 4 TzBfG, § 623 BGB, Aufhebungsvertrag |

### Block D — Workflow-Organisator

| Skill | Inhalt |
|-------|--------|
| `form-checker-fuer-vertrag-oder-willenserklaerung` | Entscheidungsbaum, Konsequenzen, Klausel-Vorschlag |
| `klauselgenerator-formvorbehalt-und-aenderungsvorbehalt` | Schriftformklausel, doppelte Schriftformklausel, AGB-Falle |
| `prozessablauf-papier-vs-elektronisch` | Workflow-Schritte: Papier, qES-Direktversand, beA-Schriftsatz mit Formfiktion und Textform |
| `dokumentations-und-beweisarchitektur` | Zugangsnachweis, qES-Validierung, TR-RESISCAN |

### Block E — Anspruchsgrundlagen-Modul

| Skill | Inhalt |
|-------|--------|
| `anspruchsformulierungen-bei-formverstoss` | § 812 BGB, Räumungsklage, Feststellungsklage, c.i.c. |
| `verteidigungsstrategie-bei-formangriff` | Heilung, § 242 BGB, Beweislast, Treuwidrigkeit |
| `mandantenkorrespondenz-form-und-zugang-templates` | Mandantenbriefe, Checklisten, Warnmemos |

## Hinweis

Alle Skills sind kanzleitauglich formuliert und enthalten vollständige Klauseltexte, Mandantenmemos und Querverweise auf aktuelle BGH-Rechtsprechung. Das Plugin ersetzt keine individuelle Rechtsberatung.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `anspruchsformulierungen-formverstoss` | Nutze dies bei Anspruchsformulierungen Bei Formverstoss, Buergschaft Verbraucherdarlehen Und Andere Strenge Formen, Dokumentations Und Beweisarchitektur: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `arbeitsrecht-befristung-schriftform-checker` | Nutze dies bei Arbeitsrecht Befristung Und Aufhebung Paragraph 14 Tzbfg 623 Bgb, Schriftform Fristen Form Und Zustaendigkeit, Form Checker Für Vertrag Oder Willenserklaerung: führt durch diese fachlich verbundenen Module, wählt den passe... |
| `befristungsabrede-qes-rechtsprechung` | Nutze dies bei Redteam Qualitygate, Befristungsabrede Qes Rechtsprechung Stand 2026, Rechtsprechung Livecheck Formfragen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Ar... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `elektronische-paragraph-formerfordernisse` | Nutze dies bei Elektronische Form Paragraph 126a Bgb Qes, Formerfordernisse Im Bgb Ueberblick, Gewerberaummiete Paragraph 550 Bgb Langzeitform: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den n... |
| `empfangsbeduerftiger-international` | Nutze dies bei Dokumentation Verhandlung Vergleich Und Eskalation, Empfangsbeduerftiger International Schnittstellen, Formerfordernisse Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüf... |
| `formwahl-zugang-live-prozessablauf` | Nutze dies bei Formwahl Zugang Und Beweis, Live Zahlen Schwellen Und Berechnung, Prozessablauf Mandantenentscheidung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `klauselgenerator-formvorbehalt-maklervertrag` | Nutze dies bei Klauselgenerator Formvorbehalt Und Aenderungsvorbehalt, Maklervertrag Paragraph 656a Bgb Textform Bgh I Zr 202 25, Amtlicher Formkern Bgb Zpo Check: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpf... |
| `kuendigung-per-mandantenkorrespondenz-zugang` | Nutze dies bei Kündigung Per Schriftsatz Zustellung Formfragen, Mandantenkorrespondenz Form Und Zugang Templates, Mandantenwarnung Qes Per Email Whatsapp Und Zugang: führt durch diese fachlich verbundenen Module, wählt den passenden Prüf... |
| `notarielle-beurkundung-prozessablauf-papier` | Nutze dies bei Notarielle Beurkundung Und Oeffentliche Beglaubigung, Prozessablauf Papier Vs Elektronisch, Schriftform Paragraph 126 Bgb Eigenhaendige Unterschrift: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfp... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `paragraph-fehlerkatalog` | Nutze dies als Fehlerbremse bei Paragraph Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `prozessordnungen-textform-verifikation` | Nutze dies bei Prozessordnungen Behörden Gericht Und Registerweg, Textform Dokumentenmatrix Und Lueckenliste, Verifikation Compliance Dokumentation Und Akte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `rechtsprechung-quellenkarte` | Nutze dies zur Quellenprüfung bei Rechtsprechung Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `sftf-arbeitsvertraege-nachweisgesetz` | Nutze dies bei Sftf Arbeitsvertraege Nachweisgesetz Spezial, Sftf Doppelschriftform Aufhebung Spezial, Sftf Elektronische Signatur Leitfaden: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näc... |
| `sftf-formvorgaben-bgb-interessen-checklisten` | Nutze dies bei Sftf Formvorgaben Bauleiter, Bgb Mehrparteien Konflikt Und Interessen, Checklisten Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `textform-paragraph-verteidigungsstrategie` | Nutze dies bei Textform Paragraph 126b Bgb Dauerhafter Datentraeger, Verteidigungsstrategie Bei Formangriff, Wohnraummiete Kündigung Paragraph 568 Bgb: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefe... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `willenserklaerung-zivilrecht-zugang` | Nutze dies bei Willenserklaerung Formular Portal Und Einreichung, Zivilrecht Tatbestand Beweis Und Belege, Zugang Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `zugang-empfangsbeduerftiger-formgerechter` | Nutze dies bei Zugang Empfangsbeduerftiger Willenserklaerung Paragraph 130 Bgb, Zugang Formgerechter Erklaerung Bgh Viii Zr 159 23: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
