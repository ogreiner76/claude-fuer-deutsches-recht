---
name: aktenauszug-gerichtsverfahren-unterlagen-luecken
description: "Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Aktenauszug Gerichtsverfahren** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `aktenauszug-strukturpruefung-akzg-bauleiter-vertraulichkeit` — Aktenauszug Strukturpruefung Akzg Bauleiter Vertraulichkeit
- `akzg-zeitstrahl-anlagenverzeichnis-extrakt-anwaltsschriftsatz` — Akzg Zeitstrahl Anlagenverzeichnis Extrakt Anwaltsschriftsatz
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `anwaltsschriftsatz-beweislast-beweismittel-interessen` — Anwaltsschriftsatz Beweislast Beweismittel Interessen
- `arbeitsgerichtsverfahren-modus-terminkalender` — Arbeitsgerichtsverfahren Modus Terminkalender
- `beweismittel-gegenueberstellung-einleitungssatz-generator` — Beweismittel Gegenueberstellung Einleitungssatz Generator
- `erstellen-fristennotiz-gerichtsverfahren-verfahrensgeschichte` — Erstellen Fristennotiz Gerichtsverfahren Verfahrensgeschichte
- `gegenueberstellung-parteivortraege-rechtsargumente` — Gegenueberstellung Parteivortraege Rechtsargumente
- `parteivortrag-gegenueberstellung-rechtsargumente` — Parteivortrag Gegenueberstellung Rechtsargumente
- `sachverhaltschronologie-textbausteine-schnelle-stilrichtlinie` — Sachverhaltschronologie Textbausteine Schnelle Stilrichtlinie
- `schwerpunktthemen-identifikation-akten-aktenauszug` — Schwerpunktthemen Identifikation Akten Aktenauszug
- `strukturierter-strafprozess-modus-verwaltungsprozess-modus` — Strukturierter Strafprozess Modus Verwaltungsprozess Modus
- `verfahrensidentifikation-verfahrenszusammenfassung-absatz` — Verfahrensidentifikation Verfahrenszusammenfassung Absatz
- `verfahrensidentifikation-verfahrenszusammenfassung-rechtsweg` — Verfahrensidentifikation Verfahrenszusammenfassung Rechtsweg

## Arbeitsweg

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Aktenauszüge zivilgerichtlicher Verfahren oft fehlend: Klageschrift, Klageerwiderung, Schriftsätze.
- **Pro Lücke.** Beweisthema, Beweismittel (Urkunden, Zeugenprotokolle), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: Akteneinsicht im laufenden Verfahren jederzeit.
- **Beschaffung extern.** AG/LG/OLG (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Aktenauszüge zivilgerichtlicher Verfahren typischerweise Klageschrift, Klageerwiderung zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
