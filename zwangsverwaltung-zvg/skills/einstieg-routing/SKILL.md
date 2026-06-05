---
name: einstieg-routing
description: "Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Einstieg und Routing

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Zwangsverwaltung Zvg** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `berichte-beschlagnahme-mietverwaltung-besitz` — Berichte Beschlagnahme Mietverwaltung Besitz
- `betriebskosten-hausgeld-bieterangebot-bewertung-glaeubiger` — Betriebskosten Hausgeld Bieterangebot Bewertung Glaeubiger
- `bieterangebote-mieten-oeffentliche` — Bieterangebote Mieten Oeffentliche
- `insolvenz-schnittstelle-instandhaltung-sicherung-zvg` — Insolvenz Schnittstelle Instandhaltung Sicherung Zvg
- `konten-kassenfuehrung-miet-pachtverwaltung-mieteinzug` — Konten Kassenfuehrung Miet Pachtverwaltung Mieteinzug
- `quality-recherche-rechnungslegung` — Quality Recherche Rechnungslegung
- `treuhandkonto-versteigerung-versteigerungsteilnahme` — Treuhandkonto Versteigerung Versteigerungsteilnahme
- `versicherungen-gefahren-zvg-versteigerungsteilnahme-zvg` — Versicherungen Gefahren Zvg Versteigerungsteilnahme Zvg
- `verteilung-zwangsverwaltung-aktenanlage-objektcockpit` — Verteilung Zwangsverwaltung Aktenanlage Objektcockpit
- `zvg-berichtswesen-besitzuebernahme-bestellung-beschlagnahme` — Zvg Berichtswesen Besitzuebernahme Bestellung Beschlagnahme
- `zvg-recherche-quality-gate-raeumung-kuendigung` — Zvg Recherche Quality Gate Raeumung Kündigung
- `zvg-rechnungslegung-simulation-training-verkauf-versteigerung` — Zvg Rechnungslegung Simulation Training Verkauf Versteigerung
- `zwvw-anordnung-zwangsverwaltung-kostenrechnung-verwalter` — Zwvw Anordnung Zwangsverwaltung Kostenrechnung Verwalter

## Arbeitsweg

- **Rolle und Ziel klären.** Wer fragt aus welcher Position (Gläubiger, Schuldner Eigentümer, Zwangsverwalter) und welcher Output wird gebraucht?
- **Fristen zuerst.** Beschwerde gegen Anordnung; Rechnungslegung.
- **Normenanker.** ZVG §§ 146 ff., BGB §§ 1135 ff. Pflichten. Tragende Norm vor Detail prüfen.
- **Zuständigkeit.** Amtsgericht Vollstreckungsgericht / Zwangsverwalter — Verfahrens- und Verwaltungsweg trennen.
- **Eine Rückfrage maximal.** Nur fragen, was die nächste Weiche entscheidet.

## Output

Triage-Notiz mit Frist, Norm, Zuständigkeit, Anschluss-Skill-Vorschlag und konkret nächstem Schritt. Bei Zwangsverwaltung ZVG typische Eskalationsstufen: Anordnungsantrag, Verwalterbericht, Erinnerung gegen Anordnung.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
