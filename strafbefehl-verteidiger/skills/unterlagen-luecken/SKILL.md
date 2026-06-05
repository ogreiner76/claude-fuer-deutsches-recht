---
name: unterlagen-luecken
description: "Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Strafbefehl Verteidiger** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `deal-beweislast-einspruch-einspruchsentscheidung-folgen` — Deal Beweislast Einspruch Einspruchsentscheidung Folgen
- `einstellung-153a-hauptverhandlung-vorbereitung-strafbefehl` — Einstellung 153a Hauptverhandlung Vorbereitung Strafbefehl
- `einstellung-fahrerlaubnis-mandantenentscheidung-hauptverhandlung` — Einstellung Fahrerlaubnis Mandantenentscheidung Hauptverhandlung
- `gegen-strafbefehl-einspruch-strafbefehl-aktenanlage` — Gegen Strafbefehl Einspruch Strafbefehl Aktenanlage
- `nebenfolgen-fahrerlaubnis-strafbefehl-pflichtverteidiger` — Nebenfolgen Fahrerlaubnis Strafbefehl Pflichtverteidiger
- `nebenfolgen-strafbefehl-strafbefehls` — Nebenfolgen Strafbefehl Strafbefehls
- `rechtsmittel-nach-tagessaetze-geldstrafe-strafbefehl` — Rechtsmittel Nach Tagessaetze Geldstrafe Strafbefehl
- `stbv-einspruch-strafbefehl-fahrerlaubnis-auslaendischer-mandant` — Stbv Einspruch Strafbefehl Fahrerlaubnis Auslaendischer Mandant
- `stbv-strafbefehl-abwesenheit-vertretung-akteneinsicht` — Stbv Strafbefehl Abwesenheit Vertretung Akteneinsicht
- `strafbefehl-einlassung-deal-verstaendigung-einspruch` — Strafbefehl Einlassung Deal Verstaendigung Einspruch
- `strafbefehl-quality-gate-akteneinsicht` — Strafbefehl Quality Gate Akteneinsicht
- `tagessaetze-verstaendigung-sonderfall-verteidiger` — Tagessaetze Verstaendigung Sonderfall Verteidiger
- `verteidigung-wiedereinsetzung-zeugenstrategie-interessen` — Verteidigung Wiedereinsetzung Zeugenstrategie Interessen

## Arbeitsweg

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Strafbefehl-Verteidigung oft fehlend: Strafbefehl, Ermittlungsakte, Einspruchsschrift.
- **Pro Lücke.** Beweisthema, Beweismittel (Vernehmungen, Zeugen), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: § 410 StPO Einspruch 2 Wochen.
- **Beschaffung extern.** Amtsgericht (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Strafbefehl-Verteidigung typischerweise Strafbefehl, Ermittlungsakte zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
