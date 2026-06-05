---
name: vertragsrecht-unterlagen-luecken
description: "Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

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

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Vertragsrecht (BGB-Vertragsrecht) oft fehlend: Vertrag, AGB, Korrespondenz.
- **Pro Lücke.** Beweisthema, Beweismittel (Mailverkehr, Verhandlungsprotokolle), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: Verjährung 3 Jahre § 195 BGB.
- **Beschaffung extern.** Zivilgerichte (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Vertragsrecht (BGB-Vertragsrecht) typischerweise Vertrag, AGB zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
