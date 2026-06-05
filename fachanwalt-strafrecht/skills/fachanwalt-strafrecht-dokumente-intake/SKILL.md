---
name: fachanwalt-strafrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Strafrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `aussagepsychologie-staatsanwaltschaft-aussagepsychologie` — Aussagepsychologie Staatsanwaltschaft Aussagepsychologie
- `chatcontrol-csam-einlassung-vorbereiten-hauptverhandlung` — Chatcontrol Csam Einlassung Vorbereiten Hauptverhandlung
- `ergaenzt-fachanwalt-insolvenzantrag-red-kanzlei-sonderfall` — Ergaenzt Fachanwalt Insolvenzantrag Red Kanzlei Sonderfall
- `fachanwalt-strafrecht-orientierung-untersuchungshaft` — Fachanwalt Strafrecht Orientierung Untersuchungshaft
- `koerperverletzung-stgb-koerperverletzung-todesfolge` — Koerperverletzung Stgb Koerperverletzung Todesfolge
- `mandat-triage-plaedoyer-vorbereitung-schriftsatzkern` — Mandat Triage Plaedoyer Vorbereitung Schriftsatzkern
- `nebenklage-nebenstrafrecht-opfervertretung-interessen-revision` — Nebenklage Nebenstrafrecht Opfervertretung Interessen Revision
- `raub-stgb-raub-todesfolge-rechtsbeugung-stgb` — Raub Stgb Raub Todesfolge Rechtsbeugung Stgb
- `steuerstrafrecht-ao-akteneinsicht-auswerten-erstgespraech` — Steuerstrafrecht Ao Akteneinsicht Auswerten Erstgespraech
- `stpo-strafrecht-strafverteidigung-zeugenbeistand-strafprozess` — Stpo Strafrecht Strafverteidigung Zeugenbeistand Strafprozess
- `strafprozess-antragslog-beweisantraege-biometrischer-cockpit` — Strafprozess Antragslog Beweisantraege Biometrischer Cockpit
- `strafprozess-instruktionen-pflichtverteidigung-beiordnung-strafr` — Strafprozess Instruktionen Pflichtverteidigung Beiordnung Strafr
- `strafr-dysfunk-befangenheitsantrag-beistandsleistung-stpo` — Strafr Dysfunk Befangenheitsantrag Beistandsleistung Stpo
- `strafr-dysfunk-darlegungslast-empirie-nutzen-erklaerungsrecht` — Strafr Dysfunk Darlegungslast Empirie Nutzen Erklaerungsrecht

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Strafrecht typisch: Anklageschrift, Strafbefehl, Ermittlungsakte, BZR-Auszug.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Revision 1 Woche/1 Mon. § 341 StPO, Berufung 1 Woche § 314 StPO).
- **Beweiswert einordnen.** Vernehmungsprotokolle, Spurenakte, DNA-/Fingerabdruck-Gutachten jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Beschuldigter/Angeklagter.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
