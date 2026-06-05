---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

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

- **Sortieren nach Dokumenttyp.** Bei Zwangsvollstreckung typisch: Vollstreckungstitel, Pfändungs- und Überweisungsbeschluss (PfÜB), Gerichtsvollzieher-Protokoll.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Erinnerung § 766 ZPO 2 Wochen, PfÜB-Zustellung Drittschuldner).
- **Beweiswert einordnen.** Titel mit Klausel, Zustellungsnachweis, Drittschuldner-Erklärung jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Gläubiger.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
