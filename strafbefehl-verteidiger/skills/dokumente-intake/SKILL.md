---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Strafbefehl Verteidiger** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `deal-beweislast-einspruch-einspruchsentscheidung-folgen` — Deal Beweislast Einspruch Einspruchsentscheidung Folgen
- `einstellung-153a-hauptverhandlung-vorbereitung-strafbefehl` — Einstellung 153a Hauptverhandlung Vorbereitung Strafbefehl
- `einstellung-fahrerlaubnis-mandantenentscheidung-hauptverhandlung` — Einstellung Fahrerlaubnis Mandantenentscheidung Hauptverhandlung
- `gegen-strafbefehl-einspruch-strafbefehl-aktenanlage` — Gegen Strafbefehl Einspruch Strafbefehl Aktenanlage
- `nebenfolgen-fahrerlaubnis-strafbefehl-pflichtverteidiger` — Nebenfolgen Fahrerlaubnis Strafbefehl Pflichtverteidiger
- `nebenfolgen-strafbefehl-strafbefehls` — Nebenfolgen Strafbefehl Strafbefehls
- `rechtsmittel-nach-tagessaetze-geldstrafe-strafbefehl` — Rechtsmittel Nach Tagessaetze Geldstrafe Strafbefehl
- `stbv-einspruch-strafbefehl-fahrerlaubnis-auslaendischer-mandant` — Stbv Einspruch Strafbefehl Fahrerlaubnis Auslaendischer Mandant
- `stbv-strafbefehl-abwesenheit-vertretung-akteneinsicht` — Stbv Strafbefehl Abwesenheit Vertretung Akteneinsicht
- `strafbefehl-einlassung-deal-verstaendigung-einspruch` — Strafbefehl Einlassung Deal Verstaendigung Einspruch
- `strafbefehl-quality-gate-akteneinsicht` — Strafbefehl Quality Gate Akteneinsicht
- `tagessaetze-verstaendigung-sonderfall-verteidiger` — Tagessaetze Verstaendigung Sonderfall Verteidiger
- `verteidigung-wiedereinsetzung-zeugenstrategie-interessen` — Verteidigung Wiedereinsetzung Zeugenstrategie Interessen

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Strafbefehl-Verteidigung typisch: Strafbefehl, Ermittlungsakte, Einspruchsschrift.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 410 StPO Einspruch 2 Wochen, Hauptverhandlung Antrag).
- **Beweiswert einordnen.** Vernehmungen, Zeugen, Polizeibericht jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Beschuldigter.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
