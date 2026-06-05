---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Erbrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `berater-interessen-beweislast-darlegungslast` — Berater Interessen Beweislast Darlegungslast
- `erb-einfuehrung-erb-erstgespraech-erb-internationales` — Erb Einfuehrung Erb Erstgespraech Erb Internationales
- `erb-nachlassinventar-erb-pflichtteilsanspruch-erb` — Erb Nachlassinventar Erb Pflichtteilsanspruch Erb
- `erbengemeinschaft-blockade-erstgespraech-mandatsannahme` — Erbengemeinschaft Blockade Erstgespraech Mandatsannahme
- `erbfall-eu-mandat-triage-pflichtteil-auskunft` — Erbfall Eu Mandat Triage Pflichtteil Auskunft
- `erbfall-intake-erbrecht-erbschein` — Erbfall Intake Erbrecht Erbschein
- `erbschein-antrag-orientierung-pflichtteilsberechnung` — Erbschein Antrag Orientierung Pflichtteilsberechnung
- `fachanwalt-kanzlei-livecheck` — Fachanwalt Kanzlei Livecheck
- `krypto-wallet-erbschaftsteuer-steuerrecht` — Krypto Wallet Erbschaftsteuer Steuerrecht
- `pflichtteil-berechnen-schriftsatzkern-substantiierung-sonderfall` — Pflichtteil Berechnen Schriftsatzkern Substantiierung Sonderfall
- `pflichtteil-progressionsoptimierung-spezial-schnittstellen` — Pflichtteil Progressionsoptimierung Schnittstellen
- `pflichtteilsergaenzung-frist-fachanwalt-erbrecht` — Pflichtteilsergaenzung Frist Fachanwalt Erbrecht
- `pflichtteilsergaenzung-testamentsvollstreckung-mediation` — Pflichtteilsergaenzung Testamentsvollstreckung Mediation

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Erbrecht typisch: Testament/Erbvertrag, Erbschein-Antrag, Nachlassverzeichnis, ErbSt-Erklärung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Ausschlagung 6 Wochen § 1944 BGB, Pflichtteil 3 Jahre § 2332).
- **Beweiswert einordnen.** Originaltestament, Eröffnungsprotokoll, Wertgutachten Immobilie jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Erblasser (Beratung).

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
