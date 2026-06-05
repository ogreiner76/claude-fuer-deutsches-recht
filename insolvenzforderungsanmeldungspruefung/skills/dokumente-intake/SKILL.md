---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Insolvenzforderungsanmeldungspruefung** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `feststellung-forderungsgrund-rang-grund` — Feststellung Forderungsgrund Rang Grund
- `iap-anmeldepruefung-bauleiter-aussonderung-absonderung` — Iap Anmeldepruefung Bauleiter Aussonderung Absonderung
- `iap-rangordnung-ifap-aktenanlage-ifap-beleg` — Iap Rangordnung Ifap Aktenanlage Ifap Beleg
- `ifap-dubletten-serienforderungen-formalpruefung-grund-betrag` — Ifap Dubletten Serienforderungen Formalpruefung Grund Betrag
- `ifap-insolvenzforderungsanmeldungspruefung-intake` — Ifap Insolvenzforderungsanmeldungspruefung Intake
- `ifap-intake-kanalcheck-masseverbindlichkeit-abgrenzen` — Ifap Intake Kanalcheck Masseverbindlichkeit Abgrenzen
- `ifap-nachtraegliche-anmeldung-pruefungstermin-gate` — Ifap Nachtraegliche Anmeldung Pruefungstermin Gate
- `ifap-pruefentscheidung-vbuh` — Ifap Pruefentscheidung Vbuh
- `ifap-rang-nachrang-schuldnerwiderspruch-streitige-forderung` — Ifap Rang Nachrang Schuldnerwiderspruch Streitige Forderung
- `ifap-tabellenauszug-tabellenimport-verteilung-bestrittene` — Ifap Tabellenauszug Tabellenimport Verteilung Bestrittene
- `kanalcheck-beweislast-masseverbindlichkeit-sonderfall` — Kanalcheck Beweislast Masseverbindlichkeit Sonderfall
- `rang-tabellenauszug-tabellenimport` — Rang Tabellenauszug Tabellenimport
- `vbuh` — Vbuh

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Insolvenzforderungsanmeldung typisch: Eröffnungsbeschluss, Forderungsanmeldung, Insolvenztabelle, Schlussverzeichnis.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Anmeldefrist im Eröffnungsbeschluss, Prüfungstermin).
- **Beweiswert einordnen.** Vertrag, Rechnungen, Mahnungen jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Gläubiger.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
