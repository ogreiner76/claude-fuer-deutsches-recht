---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Gewerblicher Rechtsschutz** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `abmahnung-urheberrecht-erfindungsmeldung-aufnahme-evvollzug` — Abmahnung Urheberrecht Erfindungsmeldung Aufnahme Evvollzug
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `anmeldung-spezial-compliance-euipo` — Anmeldung Compliance Euipo
- `evvollzug-auslandszustellung-ev-abmahnung-abschlussschreiben` — Evvollzug Auslandszustellung Ev Abmahnung Abschlussschreiben
- `evvollzug-zustellung-durch-bea-einstweiliger` — Evvollzug Zustellung Durch Bea Einstweiliger
- `freedom-gewerblicher-markenrecherche` — Freedom Gewerblicher Markenrecherche
- `fto-triage-gewerblicher-rechtsschutz-mandat-arbeitsbereich` — Fto Triage Gewerblicher Rechtsschutz Mandat Arbeitsbereich
- `gewerblicher-rechtsschutz-kaltstart-interview` — Gewerblicher Rechtsschutz Kaltstart Interview
- `gewr-einstweilige-dpma-spezial-fristen` — Gewr Einstweilige Dpma Fristen
- `gewr-geschaeftsgeheimnisgesetz-markenanmeldung-bauleiter-uwg` — Gewr Geschaeftsgeheimnisgesetz Markenanmeldung Bauleiter Uwg
- `gw-einfuehrung-gw-einstweilige-mandat-triage` — Gw Einfuehrung Gw Einstweilige Mandat Triage
- `markenanmeldung-dpma-markenrecherche-open-source` — Markenanmeldung Dpma Markenrecherche Open Source
- `open-operate-reaktion` — Open Operate Reaktion
- `rechtsschutz-review-sonderfall-source-red` — Rechtsschutz Review Sonderfall Source Red

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Gewerblicher Rechtsschutz (allgemein) typisch: Markenregisterauszug, Patentschrift, Geschmacksmusterurkunde.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Markenwiderspruch 3 Monate, Patentbeschwerde EPA 4 Monate).
- **Beweiswert einordnen.** Verkehrsbefragung, Kennzeichnungsstärke, Stand der Technik jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Schutzrechtsinhaber.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
