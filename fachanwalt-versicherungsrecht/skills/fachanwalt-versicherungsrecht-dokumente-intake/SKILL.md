---
name: fachanwalt-versicherungsrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Versicherungsrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `cyber-loesegeld-versr-cyber-deckungsanfrage` — Cyber Loesegeld Versr Cyber Deckungsanfrage
- `deckungsklage-interessen-deckungspruefung-obliegenheiten` — Deckungsklage Interessen Deckungspruefung Obliegenheiten
- `do-deckungsabwehr-lebensversicherung-rueckkauf` — Do Deckungsabwehr Lebensversicherung Rueckkauf
- `erstgespraech-mandatsannahme-berufsunfaehigkeit-klage` — Erstgespraech Mandatsannahme Berufsunfaehigkeit Klage
- `fachanwalt-kanzlei-krankenversicherung` — Fachanwalt Kanzlei Krankenversicherung
- `klage-versicherer-triage-versicherungsrecht-schriftsatzkern` — Klage Versicherer Triage Versicherungsrecht Schriftsatzkern
- `lebens-leistungsablehnung-international-obliegenheitsverletzung` — Lebens Leistungsablehnung International Obliegenheitsverletzung
- `ombudsmann-gdv-orientierung-regress-abwehr` — Ombudsmann Gdv Orientierung Regress Abwehr
- `private-spezial-pruefen-rechtsschutz-beweislast` — Private Prüfen Rechtsschutz Beweislast
- `rentenversicherung-sachversicherung-schnittstelle` — Rentenversicherung Sachversicherung Schnittstelle
- `themen-fristennotiz-versr-rechtsschutz-versr` — Themen Fristennotiz Versr Rechtsschutz Versr
- `versicherungsrecht-vergleichsverhandlung-strategie-versr-bafin` — Versicherungsrecht Vergleichsverhandlung Strategie Versr Bafin
- `versr-bu-anerkennt-leistungspruefung-nachpruefung-anerkenntnis` — Versr Bu Anerkennt Leistungspruefung Nachpruefung Anerkenntnis

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Versicherungsrecht typisch: Versicherungsschein, AVB, Schadensanzeige, Ablehnungsschreiben.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 12 VVG Klagefrist, Anzeigepflicht unverzüglich).
- **Beweiswert einordnen.** Schadensbilder, SV-Gutachten Schaden, Korrespondenz Schadensregulierung jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Versicherungsnehmer.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
