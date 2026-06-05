---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Strafzumessung** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `153a-stpo-iii-stpo-bewaehrung-stgb` — 153a Stpo Iii Stpo Bewaehrung Stgb
- `bewaehrung-auflagen-bewaehrungswiderruf-56f-freiheitsstrafe-ohne` — Bewaehrung Auflagen Bewaehrungswiderruf 56f Freiheitsstrafe Ohne
- `bewaehrung-interessen-deutschem-freiheitsstrafe` — Bewaehrung Interessen Deutschem Freiheitsstrafe
- `freiheitsstrafe-strafmass-geldstrafe-tagessatzanzahl-vs-stgb` — Freiheitsstrafe Strafmass Geldstrafe Tagessatzanzahl Vs Stgb
- `geldstrafe-grossen-rechtsmittel-gesamtstrafenfolgen` — Geldstrafe Grossen Rechtsmittel Gesamtstrafenfolgen
- `gesamtstrafenbildung-stgb-gestaendnis-strafmilderung` — Gesamtstrafenbildung Stgb Gestaendnis Strafmilderung
- `jgg-jugendstrafe-minder-schwerer-nachtraegliche` — Jgg Jugendstrafe Minder Schwerer Nachtraegliche
- `orientierung-triage-paragraph-stgb-besonders` — Orientierung Triage Paragraph Stgb Besonders
- `regelbeispiele-stgb-strafbefehl` — Regelbeispiele Stgb Strafbefehl
- `strafbefehl-stpo-strafmilderung-stgb-strafrahmen` — Strafbefehl Stpo Strafmilderung Stgb Strafrahmen
- `strafkammer-strafzumessung-strafzumessungstatsachen` — Strafkammer Strafzumessung Strafzumessungstatsachen
- `strafrecht-verfahrensstadium-strafbefehl-taeter-opfer` — Strafrecht Verfahrensstadium Strafbefehl Taeter Opfer
- `strafz-aufklaerungshilfe-kronzeuge-sicherungsverwahrung` — Strafz Aufklaerungshilfe Kronzeuge Sicherungsverwahrung
- `strafz-strafzumessungstatsachen-strafzumessungs-tatsachen` — Strafz Strafzumessungstatsachen Strafzumessungs Tatsachen

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Strafzumessung typisch: Anklageschrift, Urteilsentwurf, Vorverurteilungen BZR.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Revision 1 Woche/1 Monat § 341 StPO, Strafvollstreckung).
- **Beweiswert einordnen.** BZR-Auszug, Persönlichkeitsgutachten, Geständnis-Protokoll jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Angeklagter.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
