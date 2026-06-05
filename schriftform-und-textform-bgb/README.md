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
| `anspruchsformulierungen-formverstoss` | Anspruchsformulierungen Formverstoss im Plugin Schriftform Und Textform Bgb: prüft konkret Prüffeld für anspruchsformulierungen bei formverstoss, Mandant hat Buergschaft oder Darlehensvertrag, Anwalt oder Kanzlei muss sicherstellen dass... |
| `arbeitsrecht-befristung-schriftform-checker` | Arbeitsrecht Befristung Schriftform Checker im Plugin Schriftform Und Textform Bgb: prüft konkret Arbeitgeber oder Arbeitnehmer fragt, ob Befristung, Kündigung oder Aufhebungsver, Schriftform. Liefert priorisierten Output mit Norm-Pinpoi... |
| `befristungsabrede-qes-rechtsprechung` | Befristungsabrede QES Rechtsprechung im Plugin Schriftform Und Textform Bgb: prüft konkret Red-Team Qualitygate im Plugin schriftform-und-textform-bgb, Aktuelle Rechtsprechung zur elektronischen Signatur bei, Livecheck verifizierter Rech... |
| `elektronische-paragraph-formerfordernisse` | Elektronische Paragraph Formerfordernisse im Plugin Schriftform Und Textform Bgb: prüft konkret Prüffeld für elektronische form paragraph 126a bgb qes, Systematik der Formerfordernisse im BGB, Gewerbemieter oder Vermieter fragt. Liefert... |
| `empfangsbeduerftiger-international` | Empfangsbeduerftiger International im Plugin Schriftform Und Textform Bgb: prüft konkret Dokumentation, Empfangsbeduerftiger, Formerfordernisse. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `formwahl-zugang-live-prozessablauf` | Formwahl Zugang Live Prozessablauf im Plugin Schriftform Und Textform Bgb: prüft konkret Formwahl, Zugang und Beweisrisiko im BGB und Prozessrecht, Live, Prozessablauf. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näc... |
| `klauselgenerator-formvorbehalt-maklervertrag` | Klauselgenerator Formvorbehalt Maklervertrag im Plugin Schriftform Und Textform Bgb: prüft konkret Prüffeld für klauselgenerator formvorbehalt und, Prüffeld für Maklervertrag, § 656a BGB und Textform, Nutzerangab. Liefert priorisierten O... |
| `kuendigung-per-mandantenkorrespondenz-zugang` | Kuendigung PER Mandantenkorrespondenz Zugang im Plugin Schriftform Und Textform Bgb: prüft konkret Anwalt versendet oder empfängt eine Kündigung per, Prüffeld für mandantenkorrespondenz form und zugang, Prüffeld für mandantenwarnung qes... |
| `notarielle-beurkundung-prozessablauf-papier` | Notarielle Beurkundung Prozessablauf Papier im Plugin Schriftform Und Textform Bgb: prüft konkret Mandant muss einen Vertrag notar-beurkunden lassen, Kanzlei oder Mandant muss zwischen Papier, qES, Textform. Liefert priorisierten Output... |
| `paragraph-fehlerkatalog` | Paragraph Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `prozessordnungen-textform-verifikation` | Prozessordnungen Textform Verifikation im Plugin Schriftform Und Textform Bgb: prüft konkret Prozessordnungen, Textform, Verifikation. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `rechtsprechung-quellenkarte` | Rechtsprechung Quellenkarte: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `schriftform-textform-bgb-start-chronologie-fristen` | Start Chronologie Fristen im Plugin Schriftform Und Textform Bgb: prüft konkret Einstieg, Schnelltriage und Fallrouting im Schriftform Und Textform, Chronologie und Belegmatrix im Plugin, Fristen- und Risikoampel im Plugin. Liefert prior... |
| `schriftform-und-textform-bgb-anschluss-routing` | Anschluss-Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `schriftform-und-textform-bgb-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `schriftform-und-textform-bgb-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `schriftform-und-textform-bgb-output-waehlen` | Output wählen im Plugin Schriftform Und Textform Bgb: Diese Output-Weiche für Schriftform Und Textform Bgb entscheidet, ob Memo, Antrag, Schriftsatz, Tabelle, Risikoampel, Fragenliste oder Mandantenbrief der richtige nächste Schritt ist. |
| `schriftform-und-textform-bgb-quellen-livecheck` | Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `schriftform-und-textform-bgb-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `sftf-arbeitsvertraege-nachweisgesetz` | Sftf Arbeitsvertraege Nachweisgesetz im Plugin Schriftform Und Textform Bgb: prüft konkret Spezialfall Schriftform im Arbeitsverhaeltnis nach, Spezialfall Aufhebung der doppelten Schriftform durch, Leitfaden qualifizierte elektronische S... |
| `sftf-formvorgaben-bgb-interessen-checklisten` | Sftf Formvorgaben BGB Interessen Checklisten im Plugin Schriftform Und Textform Bgb: prüft konkret Bauleiter Formvorgaben BGB § 126 sowie § 126a sowie § 126b, BGB, Checklisten. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel... |
| `textform-paragraph-verteidigungsstrategie` | Paragraph Verteidigungsstrategie im Plugin Schriftform Und Textform Bgb: prüft konkret Prüffeld für textform paragraph 126b bgb dauerhafter, Mandant wird von Vertragspartner mit Formmangel-Einwand, Prüffeld für wohnraummiete kuendigung p... |
| `willenserklaerung-zivilrecht-zugang` | Willenserklaerung Zivilrecht Zugang im Plugin Schriftform Und Textform Bgb: prüft konkret Willenserklaerung, Zivilrecht, Zugang. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `zugang-empfangsbeduerftiger-formgerechter` | Zugang Empfangsbeduerftiger Formgerechter im Plugin Schriftform Und Textform Bgb: prüft konkret Mandant fragt, Prüffeld für zugang formgerechter erklaerung bgh viii zr. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näc... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
