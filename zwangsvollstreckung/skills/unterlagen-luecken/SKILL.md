---
name: unterlagen-luecken
description: "Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

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

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Zwangsvollstreckung oft fehlend: Vollstreckungstitel, Pfändungs- und Überweisungsbeschluss (PfÜB), Gerichtsvollzieher-Protokoll.
- **Pro Lücke.** Beweisthema, Beweismittel (Titel mit Klausel, Zustellungsnachweis), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: Erinnerung § 766 ZPO 2 Wochen.
- **Beschaffung extern.** Vollstreckungsgericht (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Zwangsvollstreckung typischerweise Vollstreckungstitel, Pfändungs- und Überweisungsbeschluss (PfÜB) zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
