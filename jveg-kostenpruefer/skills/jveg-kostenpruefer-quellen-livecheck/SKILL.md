---
name: jveg-kostenpruefer-quellen-livecheck
description: "Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert."
---

# Rechtsquellen-Livecheck

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

- **Tragende Normen amtlich.** Bei JVEG-Kostenprüfer: JVEG, ZPO §§ 91 ff. — gesetze-im-internet, Eur-Lex oder amtliche Datenbank.
- **Behördenpraxis.** Gericht (Bescheide, Auslegungserlasse, FAQ); Stand-Datum prüfen.
- **Rechtsprechung.** Gericht, Entscheidungsform, Datum, Az, Rn, frei prüfbare Fundstelle. Keine BeckRS-/juris-Blindzitate aus Modellwissen.
- **Kommentare/Literatur** nur mit Nutzerquelle oder lizenziertem Live-Zugriff; alte Auflage explizit markieren.
- **Quellenstand und Unsicherheit** im Output sichtbar machen — keine Scheinpräzision.

## Output

Quellenkarte mit Primärnormen, Rechtsprechungssuche (Gericht/Datum/Az/Rn), Behördenstand und Zitierform nach `references/zitierweise.md`.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
