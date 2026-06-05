---
name: aktenauszug-gerichtsverfahren-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

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

- **Sortieren nach Dokumenttyp.** Bei Aktenauszüge zivilgerichtlicher Verfahren typisch: Klageschrift, Klageerwiderung, Schriftsätze, Protokoll.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Akteneinsicht im laufenden Verfahren jederzeit, Sofortige Beschwerde 2 Wochen § 569 ZPO).
- **Beweiswert einordnen.** Urkunden, Zeugenprotokolle, SV-Gutachten jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Mandant.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
