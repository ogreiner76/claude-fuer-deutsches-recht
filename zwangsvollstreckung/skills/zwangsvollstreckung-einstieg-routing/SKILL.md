---
name: zwangsvollstreckung-einstieg-routing
description: "Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Einstieg und Routing

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Zwangsvollstreckung** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `bank-haertefall-inso` — Bank Haertefall Inso
- `kontenpfaendung-notar-interessen-online` — Kontenpfaendung Notar Interessen Online
- `mahnbescheid-fristennotiz-zv-titel-zv-kontensuche` — Mahnbescheid Fristennotiz Zv Titel Zv Kontensuche
- `pfueb-raeumung-schuldnerschutz-beweislast` — Pfueb Raeumung Schuldnerschutz Beweislast
- `vermoegensauskunft-vollstreckungsbescheid-vollstreckungstitel` — Vermoegensauskunft Vollstreckungsbescheid Vollstreckungstitel
- `zpo-zwangsvollstreckung-zv-abwehr` — Zpo Zwangsvollstreckung Zv Abwehr
- `zv-elektronische-zv-eu-zv` — Zv Elektronische Zv Eu Zv
- `zv-mahnbescheid-zv-mobiliar-zv-notarielle` — Zv Mahnbescheid Zv Mobiliar Zv Notarielle
- `zv-pfaendungstabelle-zv-pfueb-zv-pfueb` — Zv Pfaendungstabelle Zv Pfueb Zv Pfueb
- `zv-pfueb-802l-arbeit` — Zv Pfueb 802l Arbeit
- `zv-raeumung-zv-tabellenauszug-zv-vermoegensauskunft` — Zv Raeumung Zv Tabellenauszug Zv Vermoegensauskunft
- `zv-vollstreckungsbescheid-zv-vollstreckungsschutz-zv-zvg` — Zv Vollstreckungsbescheid Zv Vollstreckungsschutz Zv Zvg
- `zwv-pfaendung-konto-vollstreckungsschutz-billigkeit` — Zwv Pfaendung Konto Vollstreckungsschutz Billigkeit

## Arbeitsweg

- **Rolle und Ziel klären.** Wer fragt aus welcher Position (Gläubiger, Schuldner, Drittschuldner (Arbeitgeber, Bank)) und welcher Output wird gebraucht?
- **Fristen zuerst.** Erinnerung § 766 ZPO 2 Wochen; PfÜB-Zustellung Drittschuldner.
- **Normenanker.** ZPO §§ 704-945 (Vollstreckung), GVGA, InsO. Tragende Norm vor Detail prüfen.
- **Zuständigkeit.** Vollstreckungsgericht / Gerichtsvollzieher — Verfahrens- und Verwaltungsweg trennen.
- **Eine Rückfrage maximal.** Nur fragen, was die nächste Weiche entscheidet.

## Output

Triage-Notiz mit Frist, Norm, Zuständigkeit, Anschluss-Skill-Vorschlag und konkret nächstem Schritt. Bei Zwangsvollstreckung typische Eskalationsstufen: Vollstreckungsantrag, PfÜB, Erinnerung § 766 ZPO.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
