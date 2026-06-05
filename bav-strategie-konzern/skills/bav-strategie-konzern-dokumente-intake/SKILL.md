---
name: bav-strategie-konzern-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Bav Strategie Konzern** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `bav-strategie-konzern-allgemein-design-workflow-chronologie` — Allgemein Design Chronologie
- `altersversorgung-boutique-fristennotiz-psv` — Altersversorgung Boutique Fristennotiz Psv
- `betrieblichen-drei-duesseldorfer-sonderfall` — Betrieblichen Drei Duesseldorfer Sonderfall
- `buyout-ma-country-by-cta-contractual` — Buyout Ma Country By Cta Contractual
- `drei-stufen-expatriate-pensionsplanung-governance` — Drei Stufen Expatriate Pensionsplanung Governance
- `durchfuehrungswege-fuenf-harmonisierung` — Durchfuehrungswege Fuenf Harmonisierung
- `einfuehrung-durchfuehrungswege-erstattung-fuenftelregelung` — Einfuehrung Durchfuehrungswege Erstattung Fuenftelregelung
- `harmonisierung-migration-historisch-gewachsene-internationale` — Harmonisierung Migration Historisch Gewachsene Internationale
- `internationale-harmonisierung-japan-corporate` — Internationale Harmonisierung Japan Corporate
- `konzernen-pension-pensionsmodelle` — Konzernen Pension Pensionsmodelle
- `mitbestimmung-betriebsrat-pension-buyout-benefits` — Mitbestimmung Betriebsrat Pension Buyout Benefits
- `pensionsmodelle-fuenf-bav-cta-pensionsfond-rueckdeckung` — Pensionsmodelle Fuenf Bav Cta Pensionsfond Rueckdeckung
- `restrukturierung-beweislast-stil-strategische` — Restrukturierung Beweislast Stil Strategische
- `stufen-theorie-interessen-versorgungssystem-international` — Stufen Theorie Interessen Versorgungssystem International

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Betriebliche Altersversorgung im Konzern typisch: Versorgungsordnung, Pensionsfonds-Vereinbarung, Gutachten Pensionsverpflichtungen.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Anpassungsprüfung alle 3 Jahre § 16 BetrAVG, Insolvenzsicherung PSV).
- **Beweiswert einordnen.** Aktuarisches Gutachten, Tarifverträge, BetrV-Vereinbarungen jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Arbeitgeber/Konzern.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
