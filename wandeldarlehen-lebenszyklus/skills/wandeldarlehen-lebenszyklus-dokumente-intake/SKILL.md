---
name: wandeldarlehen-lebenszyklus-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Wandeldarlehen Lebenszyklus** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `bilingual-einsprachig` — Bilingual Einsprachig
- `cap-table-darlehenshoehe-konditionen` — Cap Table Darlehenshoehe Konditionen
- `dokumenten-upload-formfehler-heilungs` — Dokumenten Upload Formfehler Heilungs
- `einsprachige-vertragsfassung-vertragserstellung` — Einsprachige Vertragsfassung Vertragserstellung
- `gesellschafterbeschluss-kapitalerhoehung-vorbereiten` — Gesellschafterbeschluss Kapitalerhoehung Vorbereiten
- `gesellschafterliste-aktualisieren-gesellschafterversammlung` — Gesellschafterliste Aktualisieren Gesellschafterversammlung
- `gmbh-vollstaendigen` — Gmbh Vollstaendigen
- `handelsregisteranmeldung-kapitalerhoehung-kyc-aml` — Handelsregisteranmeldung Kapitalerhoehung Kyc Aml
- `lebenszyklus-bilinguale-vertragserstellung` — Lebenszyklus Bilinguale Vertragserstellung
- `mandat-triage-mehrere-parallel` — Mandat Triage Mehrere Parallel
- `notar-paket-parteien-erfassen` — Notar Paket Parteien Erfassen
- `post-eintragung-rangruecktritt-formulieren` — Post Eintragung Rangruecktritt Formulieren
- `sacheinlagebericht-werthaltigkeit-begleitet` — Sacheinlagebericht Werthaltigkeit Begleitet
- `unterzeichnung-elektronisch-wandelereignis-eingang` — Unterzeichnung Elektronisch Wandelereignis Eingang

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Wandeldarlehen-Lebenszyklus typisch: Wandeldarlehensvertrag, Term Sheet, Cap Table.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Wandlungsoption, Notarstrukturierung).
- **Beweiswert einordnen.** Bewertung Pre/Post-Money jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Investor.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
