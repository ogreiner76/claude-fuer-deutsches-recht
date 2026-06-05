---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Meinungspruefer** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `abwaegung-art-arbeitgeber-betrieb` — Abwaegung Art Arbeitgeber Betrieb
- `beleglage-tatsachenbehauptung-beweissicherung-screenshots` — Beleglage Tatsachenbehauptung Beweissicherung Screenshots
- `beleidigung-meinungspruefer` — Beleidigung Meinungspruefer
- `egmr-art-eugh-grch` — Egmr Art Eugh Grch
- `europarecht-emrk-gegendarstellung-entschuldigung` — Europarecht Emrk Gegendarstellung Entschuldigung
- `kommunalrecht-buergermeister-machtkritik-amtstraeger` — Kommunalrecht Buergermeister Machtkritik Amtstraeger
- `mehrdeutigkeit-sinnermittlung-meinung-tatsache` — Mehrdeutigkeit Sinnermittlung Meinung Tatsache
- `meinung-strafantrag-verfahren` — Meinung Strafantrag Verfahren
- `nachrede-tatsache` — Nachrede Tatsache
- `olg-kg-rechtsprechungsbank-verifiziert` — Olg Kg Rechtsprechungsbank Verifiziert
- `output-memo-pruefvermerk` — Output Memo Pruefvermerk
- `personen-politisches-presserecht-plattformen` — Personen Politisches Presserecht Plattformen
- `rechtsvergleich-usa-risikomatrix-ampel` — Rechtsvergleich Usa Risikomatrix Ampel
- `satire-ironisierung-schimpfwort-lackaffe` — Satire Ironisierung Schimpfwort Lackaffe

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Meinungsfreiheit/Persönlichkeitsrecht-Prüfer typisch: Beanstandetes Statement (Print/Online), Gegendarstellungsverlangen, Unterlassungserklärung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Antrag eA wegen Eile, Frist Privatklage Beleidigung).
- **Beweiswert einordnen.** Screenshots mit Zeitstempel, Zeugen, Veröffentlichungs-URL jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Betroffener.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
