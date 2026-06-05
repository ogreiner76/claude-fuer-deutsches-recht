---
name: einstieg-routing
description: "Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Einstieg und Routing

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

- **Rolle und Ziel klären.** Wer fragt aus welcher Position (Beschuldigter, Staatsanwaltschaft, Amtsrichter) und welcher Output wird gebraucht?
- **Fristen zuerst.** § 410 StPO Einspruch 2 Wochen; Hauptverhandlung Antrag.
- **Normenanker.** §§ 407 ff. StPO, § 410 StPO Einspruch 2 Wochen. Tragende Norm vor Detail prüfen.
- **Zuständigkeit.** Amtsgericht / Staatsanwaltschaft — Verfahrens- und Verwaltungsweg trennen.
- **Eine Rückfrage maximal.** Nur fragen, was die nächste Weiche entscheidet.

## Output

Triage-Notiz mit Frist, Norm, Zuständigkeit, Anschluss-Skill-Vorschlag und konkret nächstem Schritt. Bei Strafbefehl-Verteidigung typische Eskalationsstufen: Einspruch, Akteneinsicht-Antrag, Verteidigungsstrategie-Memo.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
