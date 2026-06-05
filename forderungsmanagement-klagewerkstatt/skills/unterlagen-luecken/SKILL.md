---
name: unterlagen-luecken
description: "Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Forderungsmanagement Klagewerkstatt** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `belegte-faellige-fmkw` — Belegte Faellige Fmkw
- `bgb-zpo-fmkw-saumselig-fmkw-titulierung` — Bgb Zpo Fmkw Saumselig Fmkw Titulierung
- `fmkw-mahnverfahren-bauleiter` — Fmkw Mahnverfahren Bauleiter
- `fmkw-saumselig-streitig-erfahrung-spezial` — Fmkw Saumselig Streitig Erfahrung Spezial
- `fmkw-titulierung-streckung-leitfaden` — Fmkw Titulierung Streckung Leitfaden
- `fmkw-verbraucherklage-cookies-rdg-spezial` — Fmkw Verbraucherklage Cookies Rdg Spezial
- `fmkw-verbraucherklage-forderung-anwaltshonorar-forderung` — Fmkw Verbraucherklage Forderung Anwaltshonorar Forderung
- `forderung-anwaltshonorar-rvg` — Forderung Anwaltshonorar Rvg
- `forderung-arzthonorar-goae` — Forderung Arzthonorar Goae
- `forderung-aus-werkvertrag-bgb-bau` — Forderung Aus Werkvertrag Bgb Bau
- `forderung-gegen-gesellschafter-13-gmbhg` — Forderung Gegen Gesellschafter 13 Gmbhg
- `forderung-gegen-gesellschafter-insolventen-schuldner-ausland` — Forderung Gegen Gesellschafter Insolventen Schuldner Ausland
- `forderung-gegen-insolventen-schuldner` — Forderung Gegen Insolventen Schuldner

## Arbeitsweg

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Forderungsmanagement Klagewerkstatt oft fehlend: Mahnung, Mahnbescheid, Vollstreckungsbescheid.
- **Pro Lücke.** Beweisthema, Beweismittel (Vertrag, Rechnung), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: Mahnbescheid-Widerspruch 2 Wochen.
- **Beschaffung extern.** AG Mahngericht (zentral) (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Forderungsmanagement Klagewerkstatt typischerweise Mahnung, Mahnbescheid zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
