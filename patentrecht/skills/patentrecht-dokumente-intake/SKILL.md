---
name: patentrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Patentrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `beschreibung-zeichnungen-einspruch-epa-epo-epue` — Beschreibung Zeichnungen Einspruch Epa Epo Epue
- `erfinderbenennung-arbeitnehmererfindung-erfindungsmeldung` — Erfinderbenennung Arbeitnehmererfindung Erfindungsmeldung
- `gebrauchsmuster-patent-patentrechts-laendercheck-israel` — Gebrauchsmuster Patent Patentrechts Laendercheck Israel
- `japan-jpo-kanada-cipo-loeschung-widerruf` — Japan Jpo Kanada Cipo Löschung Widerruf
- `neuheit-erfinderische-patentprozess-besichtigung-claim` — Neuheit Erfinderische Patentprozess Besichtigung Claim
- `patentlizenzvertrag-drafting-patentlizenzvertrag-review` — Patentlizenzvertrag Drafting Patentlizenzvertrag Review
- `patentprozess-auskunft-patentportfolio-technikstrategie` — Patentprozess Auskunft Patentportfolio Technikstrategie
- `patentprozess-einstweilige-verfuegung-experten-sachverstaendige` — Patentprozess Einstweilige Verfuegung Experten Sachverstaendige
- `patentprozess-negative-patentprozess-schutzschrift` — Patentprozess Negative Patentprozess Schutzschrift
- `patentrecht-kaltstart-interview` — Patentrecht Kaltstart Interview
- `patentrecht-redteam-qualitygate` — Patentrecht Redteam Qualitygate
- `patentrechts-tuerkei-turkpatent-uk-patents` — Patentrechts Tuerkei Turkpatent Uk Patents
- `patentverletzung-claim-patr2-arbeitnehmererfindung-patr2` — Patentverletzung Claim Patr2 Arbeitnehmererfindung Patr2
- `patr2-zwangslizenz-pct-laenderstrategie-pruefungsbescheid-dpma` — Patr2 Zwangslizenz Pct Laenderstrategie Pruefungsbescheid Dpma

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Patentrecht (Verfahren, Verletzung) typisch: Patentschrift, Einspruchsschrift, Verletzungsanalyse, Lizenzvertrag.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Einspruch EPA 9 Monate, Beschwerde 4 Monate § 73 PatG).
- **Beweiswert einordnen.** Stand-der-Technik-Dokumente, FTO-Analyse, SV-Gutachten Technik jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Patentinhaber.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
