---
name: quellen-livecheck
description: "Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert."
---

# Rechtsquellen-Livecheck

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

- **Tragende Normen amtlich.** Bei Patentrecherche (FTO, Validity, Family-Watch): PatG § 3 Neuheit, § 4 Erfinderischer Schritt, EPÜ Art. 54, 56, PCT — gesetze-im-internet, Eur-Lex oder amtliche Datenbank.
- **Behördenpraxis.** DPMA (Bescheide, Auslegungserlasse, FAQ); Stand-Datum prüfen.
- **Rechtsprechung.** Gericht, Entscheidungsform, Datum, Az, Rn, frei prüfbare Fundstelle. Keine BeckRS-/juris-Blindzitate aus Modellwissen.
- **Kommentare/Literatur** nur mit Nutzerquelle oder lizenziertem Live-Zugriff; alte Auflage explizit markieren.
- **Quellenstand und Unsicherheit** im Output sichtbar machen — keine Scheinpräzision.

## Output

Quellenkarte mit Primärnormen, Rechtsprechungssuche (Gericht/Datum/Az/Rn), Behördenstand und Zitierform nach `references/zitierweise.md`.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
