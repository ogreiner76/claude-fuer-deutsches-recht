---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Schriftform Und Textform Bgb** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `anspruchsformulierungen-formverstoss-buergschaft` — Anspruchsformulierungen Formverstoss Buergschaft
- `arbeitsrecht-befristung-schriftform-checker-vertrag` — Arbeitsrecht Befristung Schriftform Checker Vertrag
- `elektronische-paragraph-formerfordernisse-ueberblick` — Elektronische Paragraph Formerfordernisse Ueberblick
- `formwahl-zugang-live-prozessablauf-mandantenentscheidung` — Formwahl Zugang Live Prozessablauf Mandantenentscheidung
- `klauselgenerator-formvorbehalt-maklervertrag-paragraph-amtlicher` — Klauselgenerator Formvorbehalt Maklervertrag Paragraph Amtlicher
- `kuendigung-per-mandantenkorrespondenz-zugang-mandantenwarnung` — Kündigung Per Mandantenkorrespondenz Zugang Mandantenwarnung
- `notarielle-beurkundung-prozessablauf-papier-paragraph` — Notarielle Beurkundung Prozessablauf Papier Paragraph
- `prozessordnungen-textform-verifikation` — Prozessordnungen Textform Verifikation
- `sftf-arbeitsvertraege-nachweisgesetz-doppelschriftform-aufhebung` — Sftf Arbeitsvertraege Nachweisgesetz Doppelschriftform Aufhebung
- `sftf-formvorgaben-bgb-interessen-checklisten` — Sftf Formvorgaben Bgb Interessen Checklisten
- `textform-paragraph-verteidigungsstrategie-formangriff` — Textform Paragraph Verteidigungsstrategie Formangriff
- `willenserklaerung-zivilrecht-zugang` — Willenserklaerung Zivilrecht Zugang
- `zugang-empfangsbeduerftiger-zugang-formgerechter` — Zugang Empfangsbeduerftiger Zugang Formgerechter

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Schriftform/Textform BGB typisch: Vertrag, Unterschrift, qualifizierte e-Signatur, E-Mail/Text.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Form vor Wirksamkeit).
- **Beweiswert einordnen.** Empfangsbestätigung, Versandbeleg, qSig-Zertifikat jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Vertragsparteien.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
