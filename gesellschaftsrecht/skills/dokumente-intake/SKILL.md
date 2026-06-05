---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Gesellschaftsrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `arbeitsbereich-mandantenentscheidung-checklists-spezial` — Arbeitsbereich Mandantenentscheidung Checklists Spezial
- `beirat-beratungsfunktion-beschlussfassung-beschlussmaengel` — Beirat Beratungsfunktion Beschlussfassung Beschlussmaengel
- `beirat-familiengesellschaft-geschaeftsfuehrerabberufung` — Beirat Familiengesellschaft Geschaeftsfuehrerabberufung
- `beirat-informationsrechte-insolvenznaehe-interessenkonflikte` — Beirat Informationsrechte Insolvenznaehe Interessenkonflikte
- `beirat-internal-investigation-datenschutz-ki-deadlock-mechanik` — Beirat Internal Investigation Datenschutz Ki Deadlock Mechanik
- `beirat-kaltstart-und-zielbild` — Beirat Kaltstart Und Zielbild
- `beirat-mitbestimmung-abgrenzung-nachfolge-private-equity-red` — Beirat Mitbestimmung Abgrenzung Nachfolge Private Equity Red
- `beirat-musterklauseln-haftung-geschaeftsfuehrer-gmbhg-agio` — Beirat Musterklauseln Haftung Geschaeftsfuehrer Gmbhg Agio
- `beirat-satzungsgrundlage-sitzung-protokoll-startup-investor` — Beirat Satzungsgrundlage Sitzung Protokoll Startup Investor
- `beirat-verguetung-verschwiegenheit-veto-rechte-dd-findings` — Beirat Vergütung Verschwiegenheit Veto Rechte Dd Findings
- `dealteam-zusammenfassung-gesellschafterbeschluss` — Dealteam Zusammenfassung Gesellschafterbeschluss
- `discovery-gesellschafterbeschluesse-textbausteine` — Discovery Gesellschafterbeschluesse Textbausteine
- `gesellschaftsrecht-kaltstart-interview` — Gesellschaftsrecht Kaltstart Interview
- `gesr-gesellschaftsformwahl-aufsichtsrat-protokoll-beirat` — Gesr Gesellschaftsformwahl Aufsichtsrat Protokoll Beirat

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Gesellschaftsrecht typisch: Satzung, Geschäftsführerdienstvertrag, Hauptversammlungsprotokoll, Jahresabschluss.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Anfechtungsklage 1 Monat § 246 AktG, Bilanzpublizität § 325 HGB).
- **Beweiswert einordnen.** HR-Auszug, Gesellschafterbeschluss, Protokoll jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Gesellschafter/Aktionäre.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
