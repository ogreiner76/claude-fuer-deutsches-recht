---
name: fachanwalt-verkehrsrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Verkehrsrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-verk-unfallregulierung-workflow-chronologie` — Allgemein Verk Unfallregulierung Chronologie
- `autonom-bezuege-fachanwalt` — Autonom Bezuege Fachanwalt
- `bussgeld-unfall-haftungsquote-vkr-totalschaden` — Bussgeld Unfall Haftungsquote Vkr Totalschaden
- `erstgespraech-mandatsannahme-verkehr-autonom-fahrerlaubnis` — Erstgespraech Mandatsannahme Verkehr Autonom Fahrerlaubnis
- `fahrerlaubnis-kanzlei-personen` — Fahrerlaubnis Kanzlei Personen
- `mandat-triage-schriftsatzkern-substantiierung-315c` — Mandat Triage Schriftsatzkern Substantiierung 315c
- `mpu-vorbereitung-orientierung-regulierungsanforderung` — Mpu Vorbereitung Orientierung Regulierungsanforderung
- `pflvg-quoten-sonderfall-stgb` — Pflvg Quoten Sonderfall Stgb
- `stvg-verkehr-fristennotiz-vkr-blitzer` — Stvg Verkehr Fristennotiz Vkr Blitzer
- `stvo-unfallregulierung-beweislast-verkehrsrecht` — Stvo Unfallregulierung Beweislast Verkehrsrecht
- `tempo-messung-unfallregulierung-quoten-versicherer` — Tempo Messung Unfallregulierung Quoten Versicherer
- `verk-fahrerlaubnisrecht-leitfaden-fahrtenbuch-anordnung` — Verk Fahrerlaubnisrecht Leitfaden Fahrtenbuch Anordnung
- `verkehrsstrafrecht-interessen-verkehrsunfall` — Verkehrsstrafrecht Interessen Verkehrsunfall
- `vkr-bussgeldverfahren-bussgeld-einspruch-bussgeldbescheid` — Vkr Bussgeldverfahren Bussgeld Einspruch Bussgeldbescheid

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Verkehrsrecht typisch: Bußgeldbescheid, Polizeiprotokoll, Anhörungsbogen, Messprotokoll.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 67 OWiG Einspruch 2 Wochen, Strafbefehl 2 Wochen § 410 StPO).
- **Beweiswert einordnen.** Messprotokoll, Eichschein, Rohmessdaten jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Betroffener/Geschädigter.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
