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
| `675u-675w-banking` | Nutze dies bei 675u Verhandlung Vergleich Und Eskalation, 675w Zahlen Schwellen Und Berechnung, Banking Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächste... |
| `675v-quellenkarte` | Nutze dies zur Quellenprüfung bei 675v Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `arbeitnehmer-haftung-bgb-675u-phish-ceo` | Nutze dies bei Phishing Arbeitnehmer Haftung, Phishing Bgb 675u Haftung, Phish Ceo Fraud Konzern Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `aufsicht-bafin-bank-strategie-banking-app` | Nutze dies bei Phishing Aufsicht Bafin, Phishing Bank Strategie, Phishing Banking App Malware: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `bankpflichten-beweislast-beweislast-bgb` | Nutze dies bei Bankpflichten Beweislast Und Darlegungslast, Beweislast Mandantenkommunikation Entscheidungsvorlage, Bgb Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `bea-notfall-bgb-675v-erstkontakt-mandant` | Nutze dies bei Phishing Bea Notfall Anwalt, Phishing Bgb 675v Grobfahrlaessig, Phishing Erstkontakt Mandant: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `call-interessen-faelle-freistehender` | Nutze dies bei Call Mehrparteien Konflikt Und Interessen, Faelle Abschlussprodukt Und Uebergabe, Freistehender Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näch... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `fahrlaessigkeit-fehlerkatalog` | Nutze dies als Fehlerbremse bei Fahrlaessigkeit Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `grobe-online-phishing` | Nutze dies bei Grobe Formular Portal Und Einreichung, Online Risikoampel Und Gegenargumente, Phishing Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `klage-fristennotiz-vorfall-phish-banking` | Nutze dies bei Klage Fristennotiz Und Naechster Schritt, Vorfall Fristen Form Und Zustaendigkeit, Phish Banking Trojaner Haftung Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächste... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `phish-incident-meldepflichten-arten-erkennen` | Nutze dies bei Phish Incident Triage Bauleiter, Phish Meldepflichten Leitfaden, Phishing Arten Erkennen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `phishing-faelle-rentner-kryptowaehrung` | Nutze dies bei Phishing Faelle Rentner, Phishing Kryptowaehrung Recovery, Phishing Mit Geschaeftskonto: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `phishing-praeventionscheckliste-strafanzeige` | Nutze dies bei Phishing Praeventionscheckliste, Phishing Strafanzeige Vorbereiten, Phishing Supply Chain Bec: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `phishing-tan` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Phishing Tan Verfahren Vergleich: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `pushtan-schlichtung-sonderfall` | Nutze dies bei Prüfer Dokumentenmatrix Und Lueckenliste, Pushtan Compliance Dokumentation Und Akte, Schlichtung Sonderfall Und Edge Case: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächste... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `spoofing` | Nutze dies bei Spoofing Internationaler Bezug Und Schnittstellen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `versicherer-cyber-phishing-vorfall-zivilklage` | Nutze dies bei Phishing Versicherer Cyber, Phishing Vorfall Prüfen, Phishing Zivilklage Bank: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
