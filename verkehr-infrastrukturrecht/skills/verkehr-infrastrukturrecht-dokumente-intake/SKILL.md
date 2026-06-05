---
name: verkehr-infrastrukturrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Verkehr Infrastrukturrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-anschluss-router-workflow-chronologie` — Allgemein Anschluss Router Chronologie
- `autonomous-driving-interessen-grossprojekt` — Autonomous Driving Interessen Grossprojekt
- `foerderung-vergabe-ladeinfrastruktur-planfeststellung` — Foerderung Vergabe Ladeinfrastruktur Planfeststellung
- `infrastruktur-foerderung-nachhaltige-bahninfrastruktur` — Infrastruktur Foerderung Nachhaltige Bahninfrastruktur
- `infrastrukturrecht-intake-ladeinfrastruktur` — Infrastrukturrecht Intake Ladeinfrastruktur
- `livecheck-sonderfall-mobilitaetsprojekt-intake` — Livecheck Sonderfall Mobilitaetsprojekt Intake
- `parkraum-planfeststellung-strassenbahn` — Parkraum Planfeststellung Strassenbahn
- `parkraumbewirtschaftung-verkehr-infrastrukturrecht` — Parkraumbewirtschaftung Verkehr Infrastrukturrecht
- `schulwegsicherheit-sondernutzung-strassenbahn` — Schulwegsicherheit Sondernutzung Strassenbahn
- `strassenrecht-verkehrs-verkehrswende` — Strassenrecht Verkehrs Verkehrswende
- `verkehr-infrastrukturrecht-autonomous-driving-buergerentscheid` — Verkehr Infrastrukturrecht Autonomous Driving Buergerentscheid
- `verkehrsplanung-verfahren-vertragsmodell-strasse` — Verkehrsplanung Verfahren Vertragsmodell Strasse
- `verkehrsplanung-verkehrswende-wirtschaftsverkehr` — Verkehrsplanung Verkehrswende Wirtschaftsverkehr
- `vi-rechtsquellen-uebersicht` — Vi Rechtsquellen Uebersicht

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Verkehr-Infrastrukturrecht typisch: Planfeststellungsbeschluss, Erörterungstermin-Protokoll.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Klagefrist Planfeststellung, Anhörungsverfahren).
- **Beweiswert einordnen.** Verkehrsprognose, Lärmgutachten, Umweltgutachten jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Träger Planungshoheit.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
