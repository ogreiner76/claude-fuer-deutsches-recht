---
name: fachanwalt-urheber-medienrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Urheber Medienrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `abmahnung-sonderfall-bild-eigenen` — Abmahnung Sonderfall Bild Eigenen
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `erstgespraech-mandatsannahme-fachanwalt-urheber-medienrecht` — Erstgespraech Mandatsannahme Fachanwalt Urheber Medienrecht
- `fachanwalt-gewerblicher-kanzlei` — Fachanwalt Gewerblicher Kanzlei
- `gegendarstellung-presse-mandat-triage-schriftsatzkern` — Gegendarstellung Presse Mandat Triage Schriftsatzkern
- `gegendarstellung-presse-mod-erklaerung-orientierung` — Gegendarstellung Presse Mod Erklaerung Orientierung
- `medienrecht-lizenzvertrag-urhmr-urhebervertrag` — Medienrecht Lizenzvertrag Urhmr Urhebervertrag
- `medienverfuegung-beweislast-persoenlichkeitsrecht` — Medienverfuegung Beweislast Persoenlichkeitsrecht
- `presse-gegendarstellung-schiedsstelle-dpma-tdm-44b` — Presse Gegendarstellung Schiedsstelle Dpma Tdm 44b
- `presse-presserecht-rechtsschutz-interessen` — Presse Presserecht Rechtsschutz Interessen
- `urhmr-einfuehrung-rechtsfelder-ki-generierter` — Urhmr Einfuehrung Rechtsfelder Ki Generierter
- `urhmr-presserecht-gegendarstellung-presserechtsbrief-leitfaden` — Urhmr Presserecht Gegendarstellung Presserechtsbrief Leitfaden
- `vergleichsverhandlung-strategie` — Vergleichsverhandlung Strategie
- `verlagsredaktion-international-urheber-abmahnung-urhmr-deepfake` — Verlagsredaktion International Urheber Abmahnung Urhmr Deepfake

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Urheber- und Medienrecht typisch: Lizenzvertrag, Verlagsvertrag, Abmahnung, Sperranordnung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Verjährung 3 Jahre § 102 UrhG, Schutzdauer 70 Jahre p.m.a.).
- **Beweiswert einordnen.** Werknachweis, Lizenzkette, Nutzungs-Beleg jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Urheber/Rechteinhaber.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
