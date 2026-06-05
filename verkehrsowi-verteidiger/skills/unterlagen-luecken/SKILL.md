---
name: unterlagen-luecken
description: "Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Verkehrsowi Verteidiger** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `alkohol-drogen-beweisverwertung-standardisiert-verkehrsowi` — Alkohol Drogen Beweisverwertung Standardisiert Verkehrsowi
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `amtsgericht-drogen-interessen-einspruch` — Amtsgericht Drogen Interessen Einspruch
- `anhoerung-verkehrsowi-einspruch-messverfahren-geschwindigkeit` — Anhoerung Verkehrsowi Einspruch Messverfahren Geschwindigkeit
- `fahrverbot-geschwindigkeit-handy` — Fahrverbot Geschwindigkeit Handy
- `hauptverhandlung-sonderfall-messakte-messung-fahrverbot` — Hauptverhandlung Sonderfall Messakte Messung Fahrverbot
- `punkte-rotlicht-verkehrsowi` — Punkte Rotlicht Verkehrsowi
- `simulation-training-verjaehrung-zustellung-zeugen-polizei` — Simulation Training Verjaehrung Zustellung Zeugen Polizei
- `verkehrsowi-haertefall-fahrverbot-hauptverhandlung-amtsgericht` — Verkehrsowi Haertefall Fahrverbot Hauptverhandlung Amtsgericht
- `verkehrsowi-punkte-fahrverbot-rechtsbeschwerde-rotlicht-abstand` — Verkehrsowi Punkte Fahrverbot Rechtsbeschwerde Rotlicht Abstand
- `verteidiger-beweislast-verkehrsowi-aktenanlage-akteneinsicht` — Verteidiger Beweislast Verkehrsowi Aktenanlage Akteneinsicht
- `vowi-akteneinsicht` — Vowi Akteneinsicht
- `vowi-bussgeldbescheid-verkehrsowi-quality-gate` — Vowi Bussgeldbescheid Verkehrsowi Quality Gate
- `vowi-handyverstoss-akteneinsicht-alkohol` — Vowi Handyverstoss Akteneinsicht Alkohol

## Arbeitsweg

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Verkehrs-OWi-Verteidigung oft fehlend: Bußgeldbescheid, Anhörungsbogen, Messprotokoll.
- **Pro Lücke.** Beweisthema, Beweismittel (Messprotokoll, Rohmessdaten), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: Einspruch 2 Wochen § 67 OWiG.
- **Beschaffung extern.** Bußgeldbehörde (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Verkehrs-OWi-Verteidigung typischerweise Bußgeldbescheid, Anhörungsbogen zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
