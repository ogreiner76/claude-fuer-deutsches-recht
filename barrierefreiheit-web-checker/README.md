# Barrierefreiheit Web Checker

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`barrierefreiheit-web-checker`) | [`barrierefreiheit-web-checker.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/barrierefreiheit-web-checker.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **BFSG-Verstoß Tannenkamp Mode-Versand GmbH — Online-Shop Barrierefreiheit Osnabrück** (`bfsg-online-shop-tannenkamp-mode-versand-osnabrueck`) | [Gesamt-PDF lesen](../testakten/bfsg-online-shop-tannenkamp-mode-versand-osnabrueck/gesamt-pdf/bfsg-online-shop-tannenkamp-mode-versand-osnabrueck_gesamt.pdf) | [`testakte-bfsg-online-shop-tannenkamp-mode-versand-osnabrueck.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bfsg-online-shop-tannenkamp-mode-versand-osnabrueck.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Prüf- und Dokumentationsplugin für digitale Barrierefreiheit von Websites, Webshops, Portalen, Apps und eingebetteten Dokumenten. Es verbindet den rechtlichen Scope-Check mit praktischer Webprüfung: BFSG/BFSGV, BITV 2.0, Web Accessibility Directive, European Accessibility Act, EN 301 549, WCAG, Tastaturbedienung, Screenreader, Formulare, Checkout, PDFs, Barrierefreiheitserklärung und Remediation-Roadmap.

## Was das Plugin gut kann

- Ermitteln, ob eine Website öffentlich-rechtlich, BFSG-relevant, rein intern oder freiwillig zu prüfen ist.
- Einen Audit nach EN 301 549/WCAG-Prüflogik vorbereiten und dokumentieren.
- Tastatur, Fokus, Semantik, Screenreader, Kontrast, Formulare, Checkout und Downloads prüfen.
- Barrierefreiheitserklärung, Feedbackmechanismus und Maßnahmenplan formulieren.
- Agenturen, Entwicklerteams und Compliance-Verantwortliche mit klaren Abnahmekriterien führen.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `allgemein` | Kaltstart, Scope, Ziel, Rolle, Prüfobjekt und Workflow-Routing. |
| `scope-bfsg-bitv-wad` | Prüft, welcher Rechtsrahmen einschlägig ist: BFSG/BFSGV, BITV 2.0, EU-WAD, freiwilliger Standard. |
| `en301549-wcag-pruefplan` | Baut einen Prüfkatalog nach EN 301 549 und WCAG mit A/AA-Prioritäten. |
| `automatisierter-audit-axe-lighthouse` | Ordnet automatisierte Checks ein und warnt vor falscher Sicherheit. |
| `tastatur-fokus-navigation` | Prüft Tastaturbedienbarkeit, Fokusreihenfolge, Skiplinks, Menüs, Modale und Overlays. |
| `screenreader-semantik-aria` | Prüft Struktur, HTML-Semantik, Labels, ARIA, Überschriften, Live-Regionen und Fehlermeldungen. |
| `kontrast-farbe-motion-responsive` | Prüft Kontrast, Farbe ohne Farbcodierung, Reflow, Zoom, Animationen und Bewegung. |
| `formulare-checkout-ecommerce` | Prüft Webshop, Login, Warenkorb, Checkout, Fehlertexte, Zahlung und elektronische Verträge. |
| `pdf-downloads-dokumente` | Prüft PDFs, Downloads, eingebettete Dokumente und Alternativen. |
| `erklaerung-feedback-durchsetzung` | Erstellt Barrierefreiheitserklärung, Feedbackweg und Behörden-/Marktüberwachungsreaktion. |
| `remediation-roadmap-dokumentation` | Baut Maßnahmenplan, Priorisierung, Nachweise, Risikoampel und Re-Test-Protokoll. |
| `agentur-abnahme-vergabe` | Formuliert Lastenheft, Abnahmekriterien und Nachbesserungsanforderungen an Agenturen. |

## Quellenstand

Stand: Mai 2026. Rechtsprechung und Behördenpraxis werden nicht aus Modellwissen zitiert. Technische Standards ändern sich; insbesondere ist zwischen fachlich sinnvoller WCAG-2.2-Prüfung und rechtlich harmonisierten EN-301-549-Anforderungen zu unterscheiden.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `audit-barrierefreiheits-bfsg` | Nutze dies bei Audit Schriftsatz Brief Und Memo Bausteine, Barrierefreiheits Erstpruefung Und Mandatsziel, Bfsg Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näc... |
| `barrierefreiheit-fehlerkatalog` | Nutze dies als Fehlerbremse bei Barrierefreiheit Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `bf-kiosk-bf-mediendienste-bf-pdf` | Nutze dies bei Bf Kiosk Und Selbstbedienung Spezial, Bf Mediendienste Untertitel Spezial, Bf Pdf Schriftsaetze Versand: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbe... |
| `bfsg-zeitleiste-ecommerce-checkout-en301549` | Nutze dies bei Bfsg Zeitleiste Und Pflichten, Ecommerce Checkout Prüfung Spezial, En301549 Wcag Pruefplan: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `bfsgv-schulung-fristennotiz-agentur-abnahme` | Nutze dies bei Bfsgv Fristen Form Und Zustaendigkeit, Schulung Fristennotiz Und Naechster Schritt, Agentur Abnahme Vergabe: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `bitv-checkout-beweislast-ecommerce` | Nutze dies bei Bitv Dokumentenmatrix Und Lueckenliste, Checkout Beweislast Und Darlegungslast, Ecommerce Mandantenkommunikation Entscheidungsvorlage: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `erklaerung` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Erklaerung Feedback Durchsetzung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `erklaerung-interessen-formulare-pdfs` | Nutze dies bei Erklaerung Mehrparteien Konflikt Und Interessen, Formulare Zahlen Schwellen Und Berechnung, Pdfs Compliance Dokumentation Und Akte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert de... |
| `formulare-checkout-kontrast-farbe-native-apps` | Nutze dies bei Formulare Checkout Ecommerce, Kontrast Farbe Motion Responsive, Native Apps Ios Android Prüfung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `pdf-downloads-remediation-roadmap-schulung` | Nutze dies bei Pdf Downloads Dokumente, Remediation Roadmap Dokumentation, Schulung Und Rolle Accessibility Champion: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `pdf-formulare-automatisierter-audit-bf` | Nutze dies bei Pdf Formulare Und Formulare Barrierefrei, Automatisierter Audit Axe Lighthouse, Bf Kanzleiwebsite Konkret: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Ar... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `scope-bfsg-screenreader-semantik-abnahme` | Nutze dies bei Scope Bfsg Bitv Wad, Screenreader Semantik Aria, Abnahme Formular Portal Und Einreichung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `scope-tastatur-wcag` | Nutze dies bei Scope Behörden Gericht Und Registerweg, Tastatur Verhandlung Vergleich Und Eskalation, Wcag Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächst... |
| `screenreader-quellenkarte` | Nutze dies zur Quellenprüfung bei Screenreader Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `sonderfall-edge-roadmap-rolle` | Nutze dies bei Prüfung Sonderfall Und Edge Case, Roadmap Internationaler Bezug Und Schnittstellen, Rolle Abschlussprodukt Und Uebergabe: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `tastatur-fokus-ueberwachungsstelle` | Nutze dies bei Tastatur Fokus Navigation, Ueberwachungsstelle Und Rechtsfolgen, Usability Test Mit Betroffenen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `wcag-vs` | Nutze dies bei Wcag Vs En 301 549 Mapping: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
