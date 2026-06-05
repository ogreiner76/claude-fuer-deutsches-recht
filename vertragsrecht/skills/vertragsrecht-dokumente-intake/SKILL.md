---
name: vertragsrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Vertragsrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `aenderungs-historie-agb-eskalations-marker` — Aenderungs Historie Agb Eskalations Marker
- `allgemein-anschluss-router-workflow-chronologie` — Allgemein Anschluss Router Chronologie
- `bgb-business-einzelabrufe-sonderfall` — Bgb Business Einzelabrufe Sonderfall
- `fernabsatz-lieferanten-red-team` — Fernabsatz Lieferanten Red Team
- `fristennotiz-naechster-vertriebsvertraege-lieferantenvertrag` — Fristennotiz Naechster Vertriebsvertraege Lieferantenvertrag
- `mandat-arbeitsbereich-vr-einfuehrung-abmahnung-uwg` — Mandat Arbeitsbereich Vr Einfuehrung Abmahnung Uwg
- `nda-durchsetzer` — Nda Durchsetzer
- `nda-pruefungsvorschlaege-saas-msa` — Nda Pruefungsvorschlaege Saas Msa
- `rahmenvertrag-beweislast-vertragsrecht-vert-rahmenvertrag` — Rahmenvertrag Beweislast Vertragsrecht Vert Rahmenvertrag
- `renewal-review-routing` — Renewal Review Routing
- `saas-tracking-vert` — Saas Tracking Vert
- `vert-agb-vert-leistungsstoerungen-vr-agb` — Vert Agb Vert Leistungsstoerungen Vr Agb
- `vert-vertragsschluss-vertragspruefung-vertragsrecht` — Vert Vertragsschluss Vertragspruefung Vertragsrecht
- `vertragsrecht-kaltstart-interview` — Vertragsrecht Kaltstart Interview

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Vertragsrecht (BGB-Vertragsrecht) typisch: Vertrag, AGB, Korrespondenz, Vorvertrag.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Verjährung 3 Jahre § 195 BGB, Mängelfristen).
- **Beweiswert einordnen.** Mailverkehr, Verhandlungsprotokolle, Erfüllungshandlungen jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Vertragsparteien.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
