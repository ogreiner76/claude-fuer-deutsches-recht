---
name: produktrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Produktrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-anschluss-router-workflow-chronologie` — Allgemein Anschluss Router Chronologie
- `bewertungen-red-team-impressumspflicht` — Bewertungen Red Team Impressumspflicht
- `eu-produktsicherheitsverordnung-feature-risikobewertung` — Eu Produktsicherheitsverordnung Feature Risikobewertung
- `ist-ein-ki-act-marktueberwachung-kommunikation` — Ist Ein Ki Act Marktueberwachung Kommunikation
- `launch-livecheck-machinery` — Launch Livecheck Machinery
- `launch-pruefung` — Launch Prüfung
- `nachhaltigkeitsklage-werbeaussagen-preisangaben-prodr-gpsr` — Nachhaltigkeitsklage Werbeaussagen Preisangaben Prodr Gpsr
- `pangv-prodr-produktbeobachtung` — Pangv Prodr Produktbeobachtung
- `prodr-machinery-prodr-produktrueckruf-produktbeobachtung` — Prodr Machinery Prodr Produktrueckruf Produktbeobachtung
- `produktbeobachtung-software-produktrecht` — Produktbeobachtung Software Produktrecht
- `produkthaftung-grundlagen-produkthaftung-produktsicherheit` — Produkthaftung Grundlagen Produkthaftung Produktsicherheit
- `produktlaunch-beweislast-produktlaunch-rechtscheck` — Produktlaunch Beweislast Produktlaunch Rechtscheck
- `produktrecht-kaltstart-interview` — Produktrecht Kaltstart Interview
- `produktrecht-produktrechtliche-rechtscheck-sonderfall` — Produktrecht Produktrechtliche Rechtscheck Sonderfall

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Produktrecht (ProdSG/CE) typisch: Konformitätserklärung, Technisches Dossier, Risikobewertung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (RAPEX-Meldung unverzüglich, Rückrufpflicht unverzüglich).
- **Beweiswert einordnen.** Testberichte, CE-Zertifikate, Lieferketten-Doku jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Hersteller.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
