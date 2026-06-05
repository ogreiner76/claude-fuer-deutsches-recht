---
name: anschluss-routing
description: "Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Anschluss-Routing

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

- **Engpass zuerst.** Bei JVEG-Kostenprüfer typischer Engpass: Entschädigungsantrag binnen 3 Monaten oder SV-Rechnung.
- **Skill-Auswahl** nach Sachverhalt, Rolle (Sachverständiger, Gericht), Frist und gewünschtem Output.
- **Nicht parallel aufblasen.** Erst den Engpass lösen, dann den nächsten Pfad öffnen.
- **Grenzfall.** Zwei Skills kurz gegenüberstellen mit Vor-/Nachteil und einer Empfehlung.
- **Akten-Spur.** Router-Entscheidung dokumentieren mit Begründung und Verworfenem.

## Output

Routing-Entscheidung mit Anschluss-Skill, Reihenfolge, Abbruchkriterien und nächster Aktion innerhalb von JVEG-Kostenprüfer.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
