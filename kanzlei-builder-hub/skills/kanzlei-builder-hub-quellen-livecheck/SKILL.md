---
name: kanzlei-builder-hub-quellen-livecheck
description: "Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert."
---

# Rechtsquellen-Livecheck

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

- **Tragende Normen amtlich.** Bei Kanzlei-Builder-Hub (Plugins/Skills): BRAO § 43e KI-Einsatz, DSGVO, KI-VO — gesetze-im-internet, Eur-Lex oder amtliche Datenbank.
- **Behördenpraxis.** RAK (Bescheide, Auslegungserlasse, FAQ); Stand-Datum prüfen.
- **Rechtsprechung.** Gericht, Entscheidungsform, Datum, Az, Rn, frei prüfbare Fundstelle. Keine BeckRS-/juris-Blindzitate aus Modellwissen.
- **Kommentare/Literatur** nur mit Nutzerquelle oder lizenziertem Live-Zugriff; alte Auflage explizit markieren.
- **Quellenstand und Unsicherheit** im Output sichtbar machen — keine Scheinpräzision.

## Output

Quellenkarte mit Primärnormen, Rechtsprechungssuche (Gericht/Datum/Az/Rn), Behördenstand und Zitierform nach `references/zitierweise.md`.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
