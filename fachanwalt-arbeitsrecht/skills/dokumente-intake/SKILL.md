---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Arbeitsrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-ar-kuendigungspruefung-fazugang-arbeitgeber` — Allgemein Ar Kuendigungspruefung Fazugang Arbeitgeber
- `ar-aufhebungsvertrag-konkurrenzklausel-fachanwalt-arbeitsrecht` — Ar Aufhebungsvertrag Konkurrenzklausel Fachanwalt Arbeitsrecht
- `ar-betriebsuebergang-ar-einfuehrung-ar-leiharbeit` — Ar Betriebsuebergang Ar Einfuehrung Ar Leiharbeit
- `arbeitsgericht-abrechnung-vergleichsverhandlung-strategie-zugang` — Arbeitsgericht Abrechnung Vergleichsverhandlung Strategie Zugang
- `befristung-fao-unwirksam-fristennotiz` — Befristung Fao Unwirksam Fristennotiz
- `befristung-tzbfg-bem-verfahren-fazugang-kuendigungsfrist` — Befristung Tzbfg Bem Verfahren Fazugang Kuendigungsfrist
- `beteiligung-betriebsrat-erstgespraech-mandatsannahme-fachanwalt` — Beteiligung Betriebsrat Erstgespraech Mandatsannahme Fachanwalt
- `betriebsrat-betrvg-datum` — Betriebsrat Betrvg Datum
- `entgtranspg-fachanwalt-kschg` — Entgtranspg Fachanwalt Kschg
- `fachanwalt-arbeitsrecht-bag-betriebsratsanhoerung` — Fachanwalt Arbeitsrecht Bag Betriebsratsanhoerung
- `fachanwalt-arbeitsrecht-freistellungsklausel-sonderfall-ar` — Fachanwalt Arbeitsrecht Freistellungsklausel Sonderfall Ar
- `fachanwalt-arbeitsrecht-hinschg-kuendigungsschutzklage` — Fachanwalt Arbeitsrecht Hinschg Kuendigungsschutzklage
- `fazugang-arbeitnehmerverteidigung-fazugang-schriftform` — Fazugang Arbeitnehmerverteidigung Fazugang Schriftform
- `fazugang-einwurf-einschreiben-zugang-urlaub-inhalt-umschlags` — Fazugang Einwurf Einschreiben Zugang Urlaub Inhalt Umschlags

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Arbeitsrecht typisch: Arbeitsvertrag, Kündigung, Aufhebungsvertrag, Arbeitszeugnis.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 4 KSchG 3 Wochen Kündigungsschutzklage, § 7 KSchG Wirksamkeitsfiktion).
- **Beweiswert einordnen.** Zugangs-Nachweis Kündigung, Lohnzettel, Zeugen (Kollegen) jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Arbeitnehmer.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
