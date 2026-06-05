---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Bau Architektenrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-bau-abnahme-nachtrag-workflow-chronologie` — Allgemein Bau Abnahme Nachtrag Chronologie
- `bauordnungsrecht-einfuehrung-fachanwalt-hoai` — Bauordnungsrecht Einfuehrung Fachanwalt Hoai
- `bautraeger-abnahme-formgerecht-abnahmefiktion-clause-anlagen` — Bautraeger Abnahme Formgerecht Abnahmefiktion Clause Anlagen
- `bautraeger-belehrungspflicht-bautraeger-bonitaetspruefung` — Bautraeger Belehrungspflicht Bautraeger Bonitaetspruefung
- `bautraeger-gemeinschaftliche-maengelverfolgung-insolvenz` — Bautraeger Gemeinschaftliche Maengelverfolgung Insolvenz
- `bautraeger-leistungsbeschreibung-baubeschreibung-mabv-erweiterte` — Bautraeger Leistungsbeschreibung Baubeschreibung Mabv Erweiterte
- `bautraeger-mabv-grundlagen-ratenplan-sicherheit-buergschaft` — Bautraeger Mabv Grundlagen Ratenplan Sicherheit Buergschaft
- `bautraeger-mabv-vollstaendigkeitserklaerung-maengelruegen` — Bautraeger Mabv Vollstaendigkeitserklaerung Maengelruegen
- `bautraeger-rechtswidrige-bauvertrag-vertragstypen-red` — Bautraeger Rechtswidrige Bauvertrag Vertragstypen Red
- `bautraeger-rueckabwicklung-insolvenz-selbstvornahme-typische` — Bautraeger Rueckabwicklung Insolvenz Selbstvornahme Typische
- `bautraeger-typische-notar-weg-abgeschlossenheitsbescheinigung` — Bautraeger Typische Notar Weg Abgeschlossenheitsbescheinigung
- `bautraeger-weg-bautraeger-weg-erstgespraech-mandatsannahme` — Bautraeger Weg Bautraeger Weg Erstgespraech Mandatsannahme
- `bgb-bau-einfuehrung-bautraeger-eigenkapital-notarvertrag` — Bgb Bau Einfuehrung Bautraeger Eigenkapital Notarvertrag
- `fachanwalt-bau-architektenrecht-bauablauf-vbg-bautraeger-hoai` — Fachanwalt Bau Architektenrecht Bauablauf Vbg Bautraeger Hoai

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Bau- und Architektenrecht typisch: Bauvertrag, Pläne, Bautagebuch, Abnahmeprotokoll.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Verjährung 5 Jahre § 634a BGB, Abnahme förmlich).
- **Beweiswert einordnen.** SV-Gutachten Mängel, Bautagebuch, Lichtbilder jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Bauherr.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
