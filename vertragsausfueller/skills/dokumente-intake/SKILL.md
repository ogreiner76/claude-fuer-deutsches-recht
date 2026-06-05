---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Vertragsausfueller** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `changes-beweislast-docx-erkennen` — Changes Beweislast Docx Erkennen
- `erzeugen-red-fassungen-sonderfall-felder` — Erzeugen Red Fassungen Sonderfall Felder
- `fuehren-interessen-mappen-nachfrage` — Fuehren Interessen Mappen Nachfrage
- `term-track-vertraege` — Term Track Vertraege
- `vaf-batch-vaf-docx-vaf-einfuehrung` — Vaf Batch Vaf Docx Vaf Einfuehrung
- `vaf-bsag-vaf-klauselentscheidung-vaf-konzern` — Vaf Bsag Vaf Klauselentscheidung Vaf Konzern
- `vaf-clean-output` — Vaf Clean Output
- `vaf-feldinventar-vaf-fragebogen-vaf-fremdsprachige` — Vaf Feldinventar Vaf Fragebogen Vaf Fremdsprachige
- `vaf-plausibilitaetscheck-vaf-termsheet-altvertraege` — Vaf Plausibilitaetscheck Vaf Termsheet Altvertraege
- `vaf-quality-vaf-redline-vaf-rueckfrageninterview` — Vaf Quality Vaf Redline Vaf Rueckfrageninterview
- `vaf-template-vaf-template-vaf-track` — Vaf Template Vaf Template Vaf Track
- `vaf-vaf-mehrsprachige-vaf-platzhalterlogik` — Vaf Vaf Mehrsprachige Vaf Platzhalterlogik
- `vaf-versionierung` — Vaf Versionierung

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Vertragsausfüller typisch: Vertragsentwurf, Mustervertrag, Anlagen.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Schriftform/Textform-Fristen).
- **Beweiswert einordnen.** Verhandlungs-Korrespondenz jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Vertragsparteien.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
