# Phishing-Vorfall-Prüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`phishing-vorfall-pruefer`) | [`phishing-vorfall-pruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/phishing-vorfall-pruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Phishing-Vorfall Mayer ./. Sparkasse Berlin** (`phishing-vorfall-mayer-sparkasse-berlin`) | [Gesamt-PDF lesen](../testakten/phishing-vorfall-mayer-sparkasse-berlin/gesamt-pdf/phishing-vorfall-mayer-sparkasse-berlin_gesamt.pdf) | [`testakte-phishing-vorfall-mayer-sparkasse-berlin.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-phishing-vorfall-mayer-sparkasse-berlin.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Plugin für anwaltliche Prüfung von Online-Banking-Phishing, pushTAN-/photoTAN-Vorfällen, Call-ID-Spoofing, gefälschten Bankhotlines, Social Engineering und streitigen Erstattungsansprüchen gegen Zahlungsdienstleister.

Das Plugin arbeitet entlang des typischen Mandats:

1. Intake: Konto, Zahlungsinstrument, Schaden, Autorisierung, Sperr- und Anzeigeverlauf.
2. Rechtsrahmen: § 675u BGB, § 675v BGB, § 675w BGB, § 675l BGB, § 676b BGB und § 55 ZAG.
3. Beweisprüfung: TAN-Dialog, App-Screens, Banklogs, IP-Adressen, Device-Binding, SCA, Transaktionsmonitoring, Warnhinweise.
4. Risikomatrix: nicht autorisierter Zahlungsvorgang, grobe Fahrlässigkeit, Bankpflichtverletzung, Mitverschulden/Quotelung, Ombudsmann oder Klage.
5. Output: Erstbewertung, Bankaufforderung, Ombudsmann-Antrag, Klagegerüst, Beweisantritts- und Log-Anforderung.

## Inhalt

- `skills/phishing-vorfall-pruefen/SKILL.md` - geführter Hauptworkflow.
- `references/rechtsrahmen.md` - Arbeitsrahmen mit amtlichen Normlinks.
- `assets/checklisten/` - Intake, Beweis- und Logmatrix, grobe-Fahrlässigkeit-Ampel.
- `assets/vorlagen/` - Bankaufforderung, Ombudsmann-Antrag, Klagegerüst.
- `scripts/phishing_case_gate.py` - kleines Offline-Gate für strukturierte Fallbewertung.

## Arbeitsprinzip

Das Plugin entscheidet keinen Fall automatisch. Es zwingt zur sauberen Trennung:

- Hat der Kunde den konkreten Zahlungsvorgang autorisiert?
- Liegt ein Einwand aus § 675v BGB vor?
- Was ist bewiesen, was nur behauptet?
- Welche Banklogs müssen verlangt werden?
- Ist Schlichtung, Teilvergleich oder Klage der bessere nächste Schritt?

Alle rechtlichen Bewertungen sind Arbeitsentwürfe und müssen durch eine qualifizierte Person geprüft werden.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `675u-675w-banking` | Nutze dies, wenn Spezial 675U Verhandlung Vergleich Und Eskalation, Spezial 675W Zahlen Schwellen Und Berechnung, Spezial Banking Behörden Gericht Und Registerweg im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser... |
| `675v-quellenkarte` | Nutze dies, wenn 675v Quellenkarte im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflo... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Phishing Vorfall Prüfer.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `arbeitnehmer-haftung-bgb-675u-phish-ceo` | Nutze dies, wenn Phishing Arbeitnehmer Haftung, Phishing Bgb 675U Haftung, Phish Ceo Fraud Konzern Spezial im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Phishing Arbeitnehmer Haftung, Phishing Bgb 675U... |
| `aufsicht-bafin-bank-strategie-banking-app` | Nutze dies, wenn Phishing Aufsicht Bafin, Phishing Bank Strategie, Phishing Banking App Malware im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Phishing Aufsicht Bafin, Phishing Bank Strategie, Phishing... |
| `bankpflichten-beweislast-beweislast-bgb` | Nutze dies, wenn Spezial Bankpflichten Beweislast Und Darlegungslast, Spezial Beweislast Mandantenkommunikation Entscheidungsvorlage, Spezial Bgb Schriftsatz Brief Und Memo Bausteine im Plugin Phishing Vorfall Prüfer konkret bearbeitet w... |
| `bea-notfall-bgb-675v-erstkontakt-mandant` | Nutze dies, wenn Phishing Bea Notfall Anwalt, Phishing Bgb 675V Grobfahrlaessig, Phishing Erstkontakt Mandant im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Phishing Bea Notfall Anwalt, Phishing Bgb 675... |
| `call-interessen-faelle-freistehender` | Nutze dies, wenn Spezial Call Mehrparteien Konflikt Und Interessen, Spezial Faelle Abschlussprodukt Und Übergabe, Spezial Freistehender Erstpruefung Und Mandatsziel im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslös... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Phishing Vorfall Prüfer.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `fahrlaessigkeit-fehlerkatalog` | Nutze dies, wenn Fahrlaessigkeit Fehlerkatalog im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `grobe-online-phishing` | Nutze dies, wenn Spezial Grobe Formular Portal Und Einreichung, Spezial Online Risikoampel Und Gegenargumente, Spezial Phishing Tatbestand Beweis Und Belege im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Bitt... |
| `klage-fristennotiz-vorfall-phish-banking` | Nutze dies, wenn Spezial Klage Fristennotiz Und Naechster Schritt, Spezial Vorfall Fristen Form Und Zustaendigkeit, Phish Banking Trojaner Haftung Spezial im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Bitte... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `phish-incident-meldepflichten-arten-erkennen` | Nutze dies, wenn Phish Incident Triage Bauleiter, Phish Meldepflichten Leitfaden, Phishing Arten Erkennen im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Phish Incident Triage Bauleiter, Phish Meldepflic... |
| `phishing-faelle-rentner-kryptowaehrung` | Nutze dies, wenn Phishing Faelle Rentner, Phishing Kryptowaehrung Recovery, Phishing Mit Geschaeftskonto im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Phishing Faelle Rentner, Phishing Kryptowaehrung R... |
| `phishing-praeventionscheckliste-strafanzeige` | Nutze dies, wenn Phishing Praeventionscheckliste, Phishing Strafanzeige Vorbereiten, Phishing Supply Chain Bec im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Phishing Praeventionscheckliste, Phishing St... |
| `phishing-tan` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Phishing Tan Verfahren Vergleich im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfe... |
| `pushtan-schlichtung-sonderfall` | Nutze dies, wenn Spezial Prüfer Dokumentenmatrix Und Lueckenliste, Spezial Pushtan Compliance Dokumentation Und Akte, Spezial Schlichtung Sonderfall Und Edge Case im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `spoofing` | Nutze dies, wenn Spezial Spoofing Internationaler Bezug Und Schnittstellen im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Spezial Spoofing Internationaler Bezug Und Schnittstellen prüfen.; Erstelle eine... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `versicherer-cyber-phishing-vorfall-zivilklage` | Nutze dies, wenn Phishing Versicherer Cyber, Phishing Vorfall Prüfen, Phishing Zivilklage Bank im Plugin Phishing Vorfall Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Phishing Versicherer Cyber, Phishing Vorfall Prüfen, Phishin... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
