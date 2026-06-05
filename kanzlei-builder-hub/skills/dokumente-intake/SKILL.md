---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Kanzlei Builder Hub** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-anschluss-router-workflow-chronologie` — Allgemein Anschluss Router Chronologie
- `community-leistungsmatrix-fristennotiz-automatischer` — Community Leistungsmatrix Fristennotiz Automatischer
- `deployment-eigenen-einsteiger` — Deployment Eigenen Einsteiger
- `findet-gate-installiert` — Findet Gate Installiert
- `fundstellenglattzieher` — Fundstellenglattzieher
- `grosskanzlei-rollout-thema-prozesse-abbilden` — Grosskanzlei Rollout Thema Prozesse Abbilden
- `kanzlei-builder-hub-kaltstart-interview` — Kanzlei Builder Hub Kaltstart Interview
- `kanzleiumgebung-khub-sonderfall-livecheck-interessen` — Kanzleiumgebung Khub Sonderfall Livecheck Interessen
- `khub-kanzlei-coi-onboarding-bauleiter-leistungsmatrix-mandanten` — Khub Kanzlei Coi Onboarding Bauleiter Leistungsmatrix Mandanten
- `khub-mandantenkonferenz-paralegal-rollen-rentier-rechtsanwalt` — Khub Mandantenkonferenz Paralegal Rollen Rentier Rechtsanwalt
- `playbook-aus-eigenen-daten` — Playbook Aus Eigenen Daten
- `playbook-qualitaetspruefung-beweislast-review` — Playbook Qualitaetspruefung Beweislast Review
- `qa-kanzleiweit-templating-praxis-verwalter` — Qa Kanzleiweit Templating Praxis Verwalter
- `qualitaetspruefung-builder-daten-red` — Qualitaetspruefung Builder Daten Red

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Kanzlei-Builder-Hub (Plugins/Skills) typisch: Plugin-Konfiguration, Skill-Definitionen, Mandanten-AVV.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (materielle und prozessuale Fristen).
- **Beweiswert einordnen.** Urkunden, Zeugen, Sachverständige jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Kanzleiinhaber.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
