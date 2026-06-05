---
name: kartellrecht-marktabgrenzung-pruefung-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Kartellrecht Marktabgrenzung Prüfung** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `19a-gwb-gwb-relative-abuse-economic-algorithmic-collusion` — 19a Gwb Gwb Relative Abuse Economic Algorithmic Collusion
- `alleinvertrieb-kundengruppen-alternative-marktdefinition` — Alleinvertrieb Kundengruppen Alternative Marktdefinition
- `angebotsumstellung-evidenz-flags-red-kartellrechtliche` — Angebotsumstellung Evidenz Flags Red Kartellrechtliche
- `art-aeuv-auswirkungen-marktanteile` — Art Aeuv Auswirkungen Marktanteile
- `art-arbeitsmarkt-no-aeuv-kooperationspruefung-vereinbarung` — Art Arbeitsmarkt No Aeuv Kooperationspruefung Vereinbarung
- `bietergemeinschaft-vergabekartellrecht-bka-dgcomp-cartel` — Bietergemeinschaft Vergabekartellrecht Bka Dgcomp Cartel
- `competition-global-kaltstart` — Competition Global Kaltstart
- `competition-litigation-programm-mittelstand-schulung` — Competition Litigation Programm Mittelstand Schulung
- `cross-border-dawn-raid-gwb-kartellverbot-gwb-behinderungs` — Cross Border Dawn Raid Gwb Kartellverbot Gwb Behinderungs
- `dma-gatekeeper-einkaufskooperation-nachfragemacht-einstweiliger` — Dma Gatekeeper Einkaufskooperation Nachfragemacht Einstweiliger
- `essential-facilities-eu-bekanntmachung-evidenz-qualitaet` — Essential Facilities Eu Bekanntmachung Evidenz Qualitaet
- `eugh-rechtsprechung-rechtsprechung-beweislast-jurisdiktion` — Eugh Rechtsprechung Rechtsprechung Beweislast Jurisdiktion
- `foreign-direct-freistellung-art-fusionskontrolle-anmeldung` — Foreign Direct Freistellung Art Fusionskontrolle Anmeldung
- `fusionskontrolle-modus-geoblocking-kartellrecht-gesamtbewertung` — Fusionskontrolle Modus Geoblocking Kartellrecht Gesamtbewertung

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Kartellrecht-Marktabgrenzung typisch: Anmeldung, Marktstudien, Umsatzdaten, BKartA-Mitteilung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (FKVO 25 Arbeitstage Phase I, Beschwerdefrist BKartA-Beschluss 1 Monat).
- **Beweiswert einordnen.** SSNIP-Test, Marktbefragung, Internationale Preise/Wettbewerb jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Anmelder.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
