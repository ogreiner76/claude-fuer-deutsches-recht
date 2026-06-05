---
name: unterlagen-luecken
description: "Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Jveg Kostenpruefer** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `beschwerde-dolmetscher-sonderfall-dolmetscherkosten` — Beschwerde Dolmetscher Sonderfall Dolmetscherkosten
- `fahrtkosten-festsetzung-interessen-freistehender` — Fahrtkosten Festsetzung Interessen Freistehender
- `gate-beweislast-jveg-quality` — Gate Beweislast Jveg Quality
- `jveg-anspruchsberechtigung-antragsgenerator-dolmetscher` — Jveg Anspruchsberechtigung Antragsgenerator Dolmetscher
- `jveg-dolmetscher-uebersetzer-fahrtkosten-festsetzung-beschwerde` — Jveg Dolmetscher Uebersetzer Fahrtkosten Festsetzung Beschwerde
- `jveg-gate-rechenblatt-sachverstaendigenrechnung` — Jveg Gate Rechenblatt Sachverstaendigenrechnung
- `jveg-gerichtsschreiben-jveg-kuerzung-wegfall` — Jveg Gerichtsschreiben Jveg Kuerzung Wegfall
- `jveg-sonstige-aufwendungen-uebernachtung-aufwand` — Jveg Sonstige Aufwendungen Uebernachtung Aufwand
- `jveg-vorschuss-kostenrisiko-zeugenentschaedigung` — Jveg Vorschuss Kostenrisiko Zeugenentschaedigung
- `jveg-zeugenentschaedigung-sachverstaendigengutachten-ki` — Jveg Zeugenentschaedigung Sachverstaendigengutachten Ki
- `uebernachtung-verdienstausfall-vorschuss` — Uebernachtung Verdienstausfall Vorschuss
- `uebersetzer-fristennotiz-jveg-sachverstaendigenrechnung` — Uebersetzer Fristennotiz Jveg Sachverstaendigenrechnung
- `zeugenentschaedigung` — Zeugenentschaedigung

## Arbeitsweg

- **Fehlende Tatsache vs. fehlender Beleg.** Bei JVEG-Kostenprüfer oft fehlend: SV-Rechnung, Reisekostenabrechnung, Stundennachweise.
- **Pro Lücke.** Beweisthema, Beweismittel (Aktennotizen, Reiseplanung), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: Entschädigungsantrag binnen 3 Monaten.
- **Beschaffung extern.** Gericht (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat JVEG-Kostenprüfer typischerweise SV-Rechnung, Reisekostenabrechnung zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
