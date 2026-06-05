---
name: unterlagen-luecken
description: "Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Rechtsberatungsstelle** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-anschluss-router-workflow-chronologie` — Allgemein Anschluss Router Chronologie
- `anlaufstellen-beweislast-anleiter-bono` — Anlaufstellen Beweislast Anleiter Bono
- `anleiter-pruefwarteschlange` — Anleiter Pruefwarteschlange
- `briefe-erstberatung-rdg-konform` — Briefe Erstberatung Rdg Konform
- `entwurf-einarbeitung-einfache-sprache` — Entwurf Einarbeitung Einfache Sprache
- `erzeugung-leitfaden-erstellen-mandanten-kommunikations` — Erzeugung Leitfaden Erstellen Mandanten Kommunikations
- `fristen-fristenkontrolle-rdg` — Fristen Fristenkontrolle Rdg
- `mandant-aufnahme` — Mandant Aufnahme
- `mandantenbrief-memo-rbs-beratungshilfe` — Mandantenbrief Memo Rbs Beratungshilfe
- `mandantenintake-mandatsuebergabe-international-pro-bono` — Mandantenintake Mandatsuebergabe International Pro Bono
- `pruefwarteschlange-red-rbst-recherche-interessen` — Pruefwarteschlange Red Rbst Recherche Interessen
- `rbs-einfuehrung-rbs-rdg-rbst-anlaufstellen` — Rbs Einfuehrung Rbs Rdg Rbst Anlaufstellen
- `rbst-beratungshilfe-prozesskostenhilfe-niedrigschwellige-rdg` — Rbst Beratungshilfe Prozesskostenhilfe Niedrigschwellige Rdg
- `recherche-start-rechtsberatungsstelle-semester` — Recherche Start Rechtsberatungsstelle Semester

## Arbeitsweg

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Rechtsberatungsstelle (RDG) oft fehlend: Beratungshilfeschein, Vermögenserklärung, Bescheide Sozialleistungen.
- **Pro Lücke.** Beweisthema, Beweismittel (Einkommensnachweise, Bescheide), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: Beratungshilfe-Antrag vor Tätigkeit.
- **Beschaffung extern.** Amtsgericht (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Rechtsberatungsstelle (RDG) typischerweise Beratungshilfeschein, Vermögenserklärung zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
