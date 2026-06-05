---
name: vertragsausfueller-einstieg-routing
description: "Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Einstieg und Routing

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

- **Rolle und Ziel klären.** Wer fragt aus welcher Position (Vertragsparteien, Berater) und welcher Output wird gebraucht?
- **Fristen zuerst.** Schriftform/Textform-Fristen.
- **Normenanker.** BGB AT, BGB BT, AGB-Recht §§ 305 ff. BGB. Tragende Norm vor Detail prüfen.
- **Eine Rückfrage maximal.** Nur fragen, was die nächste Weiche entscheidet.

## Output

Triage-Notiz mit Frist, Norm, Zuständigkeit, Anschluss-Skill-Vorschlag und konkret nächstem Schritt. Bei Vertragsausfüller typische Eskalationsstufen: Ausgefüllter Vertrag mit kommentierten Lücken, Issue List, Risikomemo.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
