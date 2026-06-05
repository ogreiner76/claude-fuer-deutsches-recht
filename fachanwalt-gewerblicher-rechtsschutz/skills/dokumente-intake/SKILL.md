---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Gewerblicher Rechtsschutz** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `abmahnung-bezuege-designg` — Abmahnung Bezuege Designg
- `allgemein-gr-abmahnung-gr-portfolio` — Allgemein Gr Abmahnung Gr Portfolio
- `designverletzung-marken-widerspruch-markenanmeldung` — Designverletzung Marken Widerspruch Markenanmeldung
- `dpma-interessen-einstweilige-euipo` — Dpma Interessen Einstweilige Euipo
- `erstgespraech-mandatsannahme-abmahnung-uwg-abmahnung-wipo` — Erstgespraech Mandatsannahme Abmahnung Uwg Abmahnung Wipo
- `fachanwalt-fao-gebrmg` — Fachanwalt Fao Gebrmg
- `faevvollzug-gegnerische-faevvollzug-grenzueberschreitende` — Faevvollzug Gegnerische Faevvollzug Grenzueberschreitende
- `faevvollzug-parteibetrieb-gerichtsvollzieher-bea-elektronischer` — Faevvollzug Parteibetrieb Gerichtsvollzieher Bea Elektronischer
- `gewerblichen-markenanmeldung-markeng` — Gewerblichen Markenanmeldung Markeng
- `gewrechts-geschgehg-gewrechts-ki-faevvollzug-ev` — Gewrechts Geschgehg Gewrechts Ki Faevvollzug Ev
- `gr-einfuehrung-gr-mitbewerberabmahnung-gr-uebersetzung` — Gr Einfuehrung Gr Mitbewerberabmahnung Gr Uebersetzung
- `influencer-marketing-ki-trainingsdaten-schriftsatzkern` — Influencer Marketing Ki Trainingsdaten Schriftsatzkern
- `orientierung-patent-nichtigkeitsklage-uwg-einstweilige` — Orientierung Patent Nichtigkeitsklage Uwg Einstweilige
- `patg-verfuegung-beweislast-verletzungsklage-sonderfall` — Patg Verfuegung Beweislast Verletzungsklage Sonderfall

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Gewerblicher Rechtsschutz typisch: Registerauszug, Abmahnung, Unterlassungserklärung, Lizenzvertrag.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Widerspruch Marke 3 Mon., UWG Verjährung 6 Mon. § 11).
- **Beweiswert einordnen.** Benutzungsnachweis, Verkehrsbefragung, Verwechslungsgefahr-Analyse jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Schutzrechtsinhaber.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
