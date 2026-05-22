# Schriftform und Textform im BGB

**Plugin-Slug:** `schriftform-und-textform-bgb`  
**Version:** 3.2.1  
**Autor:** Klotzkette

## Direkt-Download

| Plugin | Direkt-Download |
| --- | --- |
| Schriftform und Textform im BGB (`schriftform-und-textform-bgb`) | [schriftform-und-textform-bgb.zip](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/schriftform-und-textform-bgb.zip) |

## Installation

1. ZIP aus dem Release herunterladen.
2. Claude Code oder Claude Desktop/Cowork öffnen.
3. **Customize Plugins** bzw. **Personal plugins** öffnen.
4. **Install from .zip** wählen und `schriftform-und-textform-bgb.zip` hochladen.
5. Mit einem konkreten Auftrag starten, zum Beispiel: `Prüfe ob unser Maklervertrag der Textform § 126b BGB genügt.`

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json` und `skills/` enthalten.

## Testakten

Zwei fiktive Mandatsakten, die jeweils eine BGH-Leitentscheidung lebbar machen:

- Maklervertrag München (Eheleute Haspelbeck-Türkenfeld ./. Bechtholdsmeier-Schongau e.K., lehnt sich an BGH I ZR 202/25): [testakten/schriftform-maklervertrag-muenchen-eheleute-haspelbeck/](../testakten/schriftform-maklervertrag-muenchen-eheleute-haspelbeck/) -> [testakte-schriftform-maklervertrag-muenchen-eheleute-haspelbeck.zip](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-schriftform-maklervertrag-muenchen-eheleute-haspelbeck.zip)
- Mietkündigung Bielefeld online (Pferdedrescher-Riesenstein ./. Eberhart-Wolframshausen, WhatsApp + qES, lehnt sich an BGH VIII ZR 159/23): [testakten/schriftform-mietkuendigung-bielefeld-online-pferdedrescher/](../testakten/schriftform-mietkuendigung-bielefeld-online-pferdedrescher/) -> [testakte-schriftform-mietkuendigung-bielefeld-online-pferdedrescher.zip](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-schriftform-mietkuendigung-bielefeld-online-pferdedrescher.zip)

## Überblick

Umfassender Workflow-Organisator für Schriftform- und Textform-Erfordernisse im deutschen Zivilrecht. Das Plugin lernt aus zwei aktuellen BGH-Leitentscheidungen und bietet kanzleitaugliche Orientierung für alle wesentlichen Formerfordernisse des BGB.

### Leitentscheidungen

- **BGH I ZR 202/25 vom 11. März 2026** — Maklervertrag § 656a BGB / Textform § 126b BGB: E-Mail-Austausch ausreichend, Erklärungen auf getrennten Datenträgern, konkludenter Abschluss möglich; Bereicherungsanspruch entfällt bei Textformverstoß (Schutzzweckargument).
- **BGH VIII ZR 159/23 vom 27. November 2024** — Wohnraummiete-Kündigung § 568 Abs. 1 BGB: qES als Schriftformersatz (§ 126a Abs. 1 BGB) grundsätzlich zulässig, ABER empfangsbedürftige Willenserklärung muss formgerecht zugehen — Ausdruck eines qES-Dokuments durch Gericht mit Transfervermerk § 298 Abs. 3 ZPO genügt nicht.

## Skill-Verzeichnis

### Block A — Formvorschriften-Grundlagen

| Skill | Inhalt |
|-------|--------|
| `formerfordernisse-im-bgb-ueberblick` | Systematik §§ 125-129 BGB, Nichtigkeit § 125 BGB, Heilung |
| `schriftform-paragraph-126-bgb-eigenhaendige-unterschrift` | Originalunterschrift, Namenszeichnung, Faksimile, BGH-Linie |
| `elektronische-form-paragraph-126a-bgb-qes` | qES, eIDAS, Zertifikatskette, technische Anforderungen |
| `textform-paragraph-126b-bgb-dauerhafter-datentraeger` | E-Mail, WhatsApp, SMS, PDF als dauerhafter Datenträger |
| `notarielle-beurkundung-und-oeffentliche-beglaubigung` | § 128, § 129 BGB, BeurkG, GmbH, Grundstück, Erbvertrag |

### Block B — Zugang der formgerechten Erklärung

| Skill | Inhalt |
|-------|--------|
| `zugang-empfangsbeduerftiger-willenserklaerung-paragraph-130-bgb` | Zugangslehre, Machtbereich, Annahmeverweigerung |
| `zugang-formgerechter-erklaerung-bgh-viii-zr-159-23` | qES-Zugang, Transfervermerk § 298 Abs. 3 ZPO, Lehrsatz |
| `kuendigung-per-schriftsatz-zustellung-formfragen` | § 169 Abs. 2 ZPO, § 130e ZPO, RA-Beglaubigung |
| `mandantenwarnung-qes-per-email-whatsapp-und-zugang` | Mandantenmemo: Mail-Anhänge prüfen, IT-Hinweise |

### Block C — Spezielle Formerfordernisse

| Skill | Inhalt |
|-------|--------|
| `maklervertrag-paragraph-656a-bgb-textform-bgh-i-zr-202-25` | I ZR 202/25: E-Mail-Austausch, Bereicherungssperre |
| `wohnraummiete-kuendigung-paragraph-568-bgb` | § 568, qES-Zugang, Begründungspflicht, Praxisempfehlung |
| `gewerberaummiete-paragraph-550-bgb-langzeitform` | Langzeitform, Heilung, ordentliche Kündigung bei Verstoß |
| `buergschaft-verbraucherdarlehen-und-andere-strenge-formen` | § 766, § 492, § 311b BGB, strenge Formen |
| `arbeitsrecht-befristung-und-aufhebung-paragraph-14-tzbfg-623-bgb` | § 14 Abs. 4 TzBfG, § 623 BGB, Aufhebungsvertrag |

### Block D — Workflow-Organisator

| Skill | Inhalt |
|-------|--------|
| `form-checker-fuer-vertrag-oder-willenserklaerung` | Entscheidungsbaum, Konsequenzen, Klausel-Vorschlag |
| `klauselgenerator-formvorbehalt-und-aenderungsvorbehalt` | Schriftformklausel, doppelte Schriftformklausel, AGB-Falle |
| `prozessablauf-papier-vs-elektronisch` | Workflow-Schritte, Originalunterschrift vs. qES vs. Textform |
| `dokumentations-und-beweisarchitektur` | Zugangsnachweis, qES-Validierung, TR-RESISCAN |

### Block E — Anspruchsgrundlagen-Modul

| Skill | Inhalt |
|-------|--------|
| `anspruchsformulierungen-bei-formverstoss` | § 812 BGB, Räumungsklage, Feststellungsklage, c.i.c. |
| `verteidigungsstrategie-bei-formangriff` | Heilung, § 242 BGB, Beweislast, Treuwidrigkeit |
| `mandantenkorrespondenz-form-und-zugang-templates` | Mandantenbriefe, Checklisten, Warnmemos |

## Hinweis

Alle Skills sind kanzleitauglich formuliert und enthalten vollständige Klauseltexte, Mandantenmemos und Querverweise auf aktuelle BGH-Rechtsprechung. Das Plugin ersetzt keine individuelle Rechtsberatung.
