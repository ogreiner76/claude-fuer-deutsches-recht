---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Internationales Wirtschaftsrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `bruessel-cisg-sonderfall-edge` — Bruessel Cisg Sonderfall Edge
- `embargo-fristennotiz-schiedsverfahren-wirtschaftsrecht` — Embargo Fristennotiz Schiedsverfahren Wirtschaftsrecht
- `fachanwalt-internationales-intwr-red` — Fachanwalt Internationales Intwr Red
- `gerichtsstand-rechtswahl-intwr-cisg-intwr-rom` — Gerichtsstand Rechtswahl Intwr Cisg Intwr Rom
- `investitionsschutz-kanzlei-lksg` — Investitionsschutz Kanzlei Lksg
- `iwr-arbitration-iwr-cisg-iwr-rechtswahl` — Iwr Arbitration Iwr Cisg Iwr Rechtswahl
- `iwr-cisg-iwr-brussels-iwr-icc` — Iwr Cisg Iwr Brussels Iwr Icc
- `iwr-einfuehrung-rechtsquellen` — Iwr Einfuehrung Rechtsquellen
- `mandat-triage-schriftsatzkern-substantiierung-aussenhandel` — Mandat Triage Schriftsatzkern Substantiierung Aussenhandel
- `orientierung-iwr-embargo-iwr-eu` — Orientierung Iwr Embargo Iwr Eu
- `sanktionen-erstgespraech-mandatsannahme-cisg` — Sanktionen Erstgespraech Mandatsannahme Cisg
- `schiedsklausel-intwr-eu-sanktions` — Schiedsklausel Intwr Eu Sanktions
- `schiedsklausel-intwr-schiedsklausel-grenzueberschreitender` — Schiedsklausel Intwr Schiedsklausel Grenzueberschreitender

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Internationales Wirtschaftsrecht typisch: Internationaler Vertrag, Schiedsklage, Choice-of-law-Klausel.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Schiedsklage-Fristen je Regelwerk, CISG-Mängelrüge angemessen).
- **Beweiswert einordnen.** Dokumentenkontrolle, Witness statements, Expert evidence jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Internationale Vertragspartner.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
