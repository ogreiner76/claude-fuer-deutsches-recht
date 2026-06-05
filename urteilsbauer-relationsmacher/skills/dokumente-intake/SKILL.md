---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Urteilsbauer Relationsmacher** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `aktenintake-zivil` — Aktenintake Zivil
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `amts-aktenintake-zivil-anspruchsgrundlagen` — Amts Aktenintake Zivil Anspruchsgrundlagen
- `anspruchsgrundlagen-pruefen` — Anspruchsgrundlagen Prüfen
- `berufungsfest-beschluss-bauen-beweisbeschluss-vorbereiten` — Berufungsfest Beschluss Bauen Beweisbeschluss Vorbereiten
- `berufungsfest-pruefen` — Berufungsfest Prüfen
- `beschluss-bauen-zpo` — Beschluss Bauen Zpo
- `beweisbeschluss-vorbereiten` — Beweisbeschluss Vorbereiten
- `beweiswuerdigung-mit-richter-input` — Beweiswuerdigung Mit Richter Input
- `beweiswuerdigung-richter-cisg-dsgvo-rechtswidriges` — Beweiswuerdigung Richter Cisg Dsgvo Rechtswidriges
- `cisg-pruefen` — Cisg Prüfen
- `dokumente-rendern-urteil-docx` — Dokumente Rendern Urteil Docx
- `dsgvo-rechtswidriges-produkt` — Dsgvo Rechtswidriges Produkt
- `entscheidungsgruende-redaktion-familienrichter-input` — Entscheidungsgruende Redaktion Familienrichter Input

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Urteilsbauer/Relationsmacher typisch: Klage, Klageerwiderung, Beweisaufnahme, Plädoyer.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Verkündung, Absetzungsfrist).
- **Beweiswert einordnen.** Beweisaufnahme-Ergebnis jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Richter.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
