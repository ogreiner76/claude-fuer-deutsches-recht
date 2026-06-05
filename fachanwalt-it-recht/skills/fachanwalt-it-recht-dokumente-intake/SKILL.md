---
name: fachanwalt-it-recht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt It Recht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `dma-dsa-dsgvo-fachanwalt-governance` — Dma Dsa Dsgvo Fachanwalt Governance
- `dsv-aufnahme-dsv-benachrichtigung-dsv-benachrichtigung-dsv` — Dsv Aufnahme Dsv Benachrichtigung Dsv Benachrichtigung Dsv
- `dsv-dsfa-update-erstgespraech-vorfallmeldung-eskalationsmatrix` — Dsv Dsfa Update Erstgespraech Vorfallmeldung Eskalationsmatrix
- `dsv-kinderdaten-besondere-kommunikationssperre-lead-authority` — Dsv Kinderdaten Besondere Kommunikationssperre Lead Authority
- `dsv-massenbenachrichtigung-dsv-meldekette-dsv-meldung-dsv` — Dsv Massenbenachrichtigung Dsv Meldekette Dsv Meldung Dsv
- `dsv-meldung-baylda-bfdi-bln-bdi-hbdi-hmbbfdi` — Dsv Meldung Baylda Bfdi Bln Bdi Hbdi Hmbbfdi
- `dsv-meldung-lda-ldi-nrw-lfd-niedersachsen-sachsen-anhalt-lfdi` — Dsv Meldung Lda Ldi Nrw Lfd Niedersachsen Sachsen Anhalt Lfdi
- `dsv-meldung-lfdi-mv-rlp-saarland-saechsdsb` — Dsv Meldung Lfdi Mv Rlp Saarland Saechsdsb
- `dsv-meldung-tlfdi-uld-sh-nachmeldung-aktualisierung-enisa` — Dsv Meldung Tlfdi Uld Sh Nachmeldung Aktualisierung Enisa
- `dsv-pressemitteilung-krisenkommunikation-sammelklagen-vvt-update` — Dsv Pressemitteilung Krisenkommunikation Sammelklagen Vvt Update
- `dsv-rechtsprechung-saas-vertrag-fristennotiz-fachanwalt-it` — Dsv Rechtsprechung Saas Vertrag Fristennotiz Fachanwalt It
- `dsv-risikobewertung-art-schnelltriage-risiko-sofortmassnahmen` — Dsv Risikobewertung Art Schnelltriage Risiko Sofortmassnahmen
- `dsv-stakeholder-dsv-tonfall-dsv-verdacht-dsv-zeitleiste` — Dsv Stakeholder Dsv Tonfall Dsv Verdacht Dsv Zeitleiste
- `fachanwalt-it-cloud-vertrag-datenschutz-itr-ki-saas-bauleiter` — Fachanwalt It Cloud Vertrag Datenschutz Itr Ki Saas Bauleiter

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt IT-Recht typisch: Softwarevertrag, SLA, Pflichtenheft, Source-Code-Hinterlegung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Mängelfristen Software, AGB-Schriftform).
- **Beweiswert einordnen.** Source Code, Lieferprotokoll, Testberichte jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Auftraggeber.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
