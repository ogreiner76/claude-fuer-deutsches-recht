---
name: anschluss-routing
description: "Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Anschluss-Routing

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

- **Engpass zuerst.** Bei Zwangsverwaltung ZVG typischer Engpass: Beschwerde gegen Anordnung oder Anordnungsbeschluss.
- **Skill-Auswahl** nach Sachverhalt, Rolle (Gläubiger, Schuldner Eigentümer), Frist und gewünschtem Output.
- **Nicht parallel aufblasen.** Erst den Engpass lösen, dann den nächsten Pfad öffnen.
- **Grenzfall.** Zwei Skills kurz gegenüberstellen mit Vor-/Nachteil und einer Empfehlung.
- **Akten-Spur.** Router-Entscheidung dokumentieren mit Begründung und Verworfenem.

## Output

Routing-Entscheidung mit Anschluss-Skill, Reihenfolge, Abbruchkriterien und nächster Aktion innerhalb von Zwangsverwaltung ZVG.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
