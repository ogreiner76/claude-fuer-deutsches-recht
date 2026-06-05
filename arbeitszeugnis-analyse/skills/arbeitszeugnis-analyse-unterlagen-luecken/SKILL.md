---
name: arbeitszeugnis-analyse-unterlagen-luecken
description: "Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Arbeitszeugnis Analyse** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `ampelsystem-tabellenausgabe` — Ampelsystem Tabellenausgabe
- `aufforderungsschreiben-arbeitgeber` — Aufforderungsschreiben Arbeitgeber
- `azubi-zeugnis-analyse` — Azubi Zeugnis Analyse
- `bereichs-drift-detektor` — Bereichs Drift Detektor
- `branchen-spezifische-formulierungen` — Branchen Spezifische Formulierungen
- `erstgespraech-und-mandatsannahme` — Erstgespraech Und Mandatsannahme
- `geheimcode-katalog` — Geheimcode Katalog
- `gesamtnoten-aggregation` — Gesamtnoten Aggregation
- `gruen-flaggen-katalog` — Gruen Flaggen Katalog
- `klage-strategie-zeugnisberichtigung` — Klage Strategie Zeugnisberichtigung
- `leistungsbeurteilung-analyse` — Leistungsbeurteilung Analyse
- `leitende-positionen-zeugnisse` — Leitende Positionen Zeugnisse
- `mandantenbericht-zeugnisanalyse` — Mandantenbericht Zeugnisanalyse
- `muster-arbeitszeugnis-gemischte-noten` — Muster Arbeitszeugnis Gemischte Noten

## Arbeitsweg

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Arbeitszeugnis-Analyse oft fehlend: Erstes Zeugnis, Berichtigungszeugnis, Zwischenzeugnis.
- **Pro Lücke.** Beweisthema, Beweismittel (Leistungsbeurteilungen, E-Mail-Verkehr HR), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: BAG 5.7.2018 – 9 AZR 244/17 Anspruch entstehung.
- **Beschaffung extern.** Arbeitsgericht (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Arbeitszeugnis-Analyse typischerweise Erstes Zeugnis, Berichtigungszeugnis zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
