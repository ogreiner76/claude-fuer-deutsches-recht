---
name: forschungszulage-antragstellung-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Forschungszulage Antragstellung** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `abgrenzung-adaptiver-antrag` — Abgrenzung Adaptiver Antrag
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `antragstellung-auszahlung-beihilfen-beweislast` — Antragstellung Auszahlung Beihilfen Beweislast
- `bemessungsgrundlage-interessen-bsfz-definition` — Bemessungsgrundlage Interessen Bsfz Definition
- `forsch-bsfz-pruefung-spezial` — Forsch Bsfz Prüfung Spezial
- `forsch-konzernverbund-forschung-spezial` — Forsch Konzernverbund Forschung Spezial
- `forsch-projektbeschreibung-bauleiter` — Forsch Projektbeschreibung Bauleiter
- `forsch-stundenaufzeichnung-fz-ablehnung-bemessungsgrundlage` — Forsch Stundenaufzeichnung Fz Ablehnung Bemessungsgrundlage
- `forsch-stundenaufzeichnung-leitfaden` — Forsch Stundenaufzeichnung Leitfaden
- `forschungszulage-insolvenzlage-red-portaltexte` — Forschungszulage Insolvenzlage Red Portaltexte
- `fz-ablehnung-nachbesserung-einspruch` — Fz Ablehnung Nachbesserung Einspruch
- `fz-auftragsforschung-vertragsgestaltung` — Fz Auftragsforschung Vertragsgestaltung
- `fz-bemessungsgrundlage-2026` — Fz Bemessungsgrundlage 2026
- `fz-bescheidung-fz-bsfz-fz-dokumentationspaket` — Fz Bescheidung Fz Bsfz Fz Dokumentationspaket

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Forschungszulage FZulG typisch: Projektbeschreibung, BSFZ-Bescheinigung, Stundennachweise, Personalkosten.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Antrag jederzeit, Festsetzung mit ESt/KSt-Erklärung).
- **Beweiswert einordnen.** F&E-Stundenaufzeichnungen, Projektdokumentation jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Unternehmen F&E.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
