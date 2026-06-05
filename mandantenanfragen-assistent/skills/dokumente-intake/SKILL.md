---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Mandantenanfragen Assistent** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `anrede-anwaltskanzleien-bittet` — Anrede Anwaltskanzleien Bittet
- `dankt-dsgvo-sonderfall-e-mail` — Dankt Dsgvo Sonderfall E Mail
- `dringlichkeitsmarker-einwilligung-hinweis-erstantwort-generator` — Dringlichkeitsmarker Einwilligung Hinweis Erstantwort Generator
- `erstantwort-foermlich-mail` — Erstantwort Foermlich Mail
- `folgekorrespondenz-vorbereiten-konfliktcheck-vorab-ma` — Folgekorrespondenz Vorbereiten Konfliktcheck Vorab Ma
- `ma-einfuehrung-ma-erstvermerk-ma-konfliktcheck` — Ma Einfuehrung Ma Erstvermerk Ma Konfliktcheck
- `ma-mandant-manda-erstgespraechsleitfaden-manda-erstkontakt` — Ma Mandant Manda Erstgespraechsleitfaden Manda Erstkontakt
- `manda-mandatsablehnung-rechtsschutz-eintrittsanfrage` — Manda Mandatsablehnung Rechtsschutz Eintrittsanfrage
- `mandantenanfragen-anfrage-eingang-anrede-uebernehmen` — Mandantenanfragen Anfrage Eingang Anrede Uebernehmen
- `mehrsprachige-antwort-muster-erstantwort-spam-massen` — Mehrsprachige Antwort Muster Erstantwort Spam Massen
- `nennt-sachverhalt-telefon` — Nennt Sachverhalt Telefon
- `telefonische-terminvergabe-interessen-transkription-beweislast` — Telefonische Terminvergabe Interessen Transkription Beweislast
- `uebernimmt-telefon-konfiguration-transkriptionsdienst-erklaerung` — Uebernimmt Telefon Konfiguration Transkriptionsdienst Erklaerung

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Mandantenanfragen-Assistent typisch: Mandantenmail, Kanzleiprofil, Honorarinfo.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Unverzügliche Antwort).
- **Beweiswert einordnen.** Urkunden, Zeugen, Sachverständige jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Mandant.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
