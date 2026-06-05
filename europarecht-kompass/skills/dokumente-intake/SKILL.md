---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Europarecht Kompass** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-anschluss-router-workflow-chronologie` — Allgemein Anschluss Router Chronologie
- `beihilfen-drafting-europarecht` — Beihilfen Drafting Europarecht
- `er-vorlageverfahren-eur-kommissionsverfahren-eur-mandant` — Er Vorlageverfahren Eur Kommissionsverfahren Eur Mandant
- `eur-anrufung-eur-state-beihilfen-vergaben` — Eur Anrufung Eur State Beihilfen Vergaben
- `europarecht-delegierte-durchfuehrungsakte-deutscher-denkfehler` — Europarecht Delegierte Durchfuehrungsakte Deutscher Denkfehler
- `europarecht-europarecht-mandantenmemo-quality-gate` — Europarecht Europarecht Mandantenmemo Quality Gate
- `europarecht-grundfreiheiten-binnenmarkt-grundrechte-charta` — Europarecht Grundfreiheiten Binnenmarkt Grundrechte Charta
- `europarecht-richtlinie-umsetzung-simulation-behoerde-verordnung` — Europarecht Richtlinie Umsetzung Simulation Behörde Verordnung
- `gegen-grundfreiheiten-livecheck-sonderfall` — Gegen Grundfreiheiten Livecheck Sonderfall
- `kommissionsverfahren-vorlageverfahren-interessen` — Kommissionsverfahren Vorlageverfahren Interessen
- `nationales-verfahren-vorlageverfahren-art-denkfehler` — Nationales Verfahren Vorlageverfahren Art Denkfehler
- `petitionsausschuss-mandantenentscheidung-richtlinien` — Petitionsausschuss Mandantenentscheidung Richtlinien
- `verordnungen-vorrang-vorrang-unmittelbare` — Verordnungen Vorrang Vorrang Unmittelbare
- `vorrang-unmittelbare-wettbewerb-kartell-anrufung-red` — Vorrang Unmittelbare Wettbewerb Kartell Anrufung Red

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Europarecht-Kompass typisch: Klageschrift EuGH, Vorlagebeschluss nationaler Gerichte, Kommissions-Mitteilung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Nichtigkeitsklage 2 Monate Art. 263 AEUV, Vorabentscheidung jederzeit).
- **Beweiswert einordnen.** Marktstudien, Verwaltungspraxis, Folgenabschätzungen jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Nationale Gerichte.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
