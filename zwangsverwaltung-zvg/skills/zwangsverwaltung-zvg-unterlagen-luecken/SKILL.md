---
name: zwangsverwaltung-zvg-unterlagen-luecken
description: "Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

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

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Zwangsverwaltung ZVG oft fehlend: Anordnungsbeschluss, Verwalterbericht, Mietsachen-Akte.
- **Pro Lücke.** Beweisthema, Beweismittel (Mieteinnahmen, Reparaturen-Belege), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: Beschwerde gegen Anordnung.
- **Beschaffung extern.** Amtsgericht Vollstreckungsgericht (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Zwangsverwaltung ZVG typischerweise Anordnungsbeschluss, Verwalterbericht zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
