---
name: patentrecherche-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Patentrecherche** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `dpmaregister-epue-beweislast-erfinderische-sonderfall` — Dpmaregister Epue Beweislast Erfinderische Sonderfall
- `erfinderische-taetigkeit-freedom-to-ki-patent` — Erfinderische Taetigkeit Freedom To Ki Patent
- `espacenet-google-neuheit-red` — Espacenet Google Neuheit Red
- `klassifikation-cpc-neuheit-patentfamilien-analyse` — Klassifikation Cpc Neuheit Patentfamilien Analyse
- `patentanwaelte-patentrecherche-patents` — Patentanwaelte Patentrecherche Patents
- `patentrecherche-kaltstart-interview` — Patentrecherche Kaltstart Interview
- `patg-problem-register` — Patg Problem Register
- `patr-fto-bericht-patentfamilie-priodatum-recherchestrategie` — Patr Fto Bericht Patentfamilie Priodatum Recherchestrategie
- `patr-software-pr-einfuehrung-pruefungsbescheid-vorbereiten` — Patr Software Pr Einfuehrung Pruefungsbescheid Vorbereiten
- `recherche-strategie-tools-marktuebersicht-recherchebericht` — Recherche Strategie Tools Marktuebersicht Recherchebericht
- `rechtsstand-pruefen-rueckfragen-mandant-depatisnet` — Rechtsstand Prüfen Rueckfragen Mandant Depatisnet
- `stand-technik-uspto-interessen` — Stand Technik Uspto Interessen
- `taetigkeit-fristennotiz-agentische-datenbank-epo-opposition` — Taetigkeit Fristennotiz Agentische Datenbank Epo Opposition

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Patentrecherche (FTO, Validity, Family-Watch) typisch: Erfindungsmeldung, Anspruchssatz, Recherche-Report, FTO-Memo.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Prioritätsjahr 12 Monate, Recherche bei Anmeldung).
- **Beweiswert einordnen.** Espacenet/DEPATISnet-Treffer, USPTO Patent Family, Standards (ETSI/ISO) jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Anmelder.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
