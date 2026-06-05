---
name: bgb-bt-pruefer-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Bgb Bt Prüfer** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `amtlicher-bgb-auftrag-unentgeltliche-bereicherungsrecht` — Amtlicher Bgb Auftrag Unentgeltliche Bereicherungsrecht
- `anfangercoach-schuldrecht-anspruchslandkarte-beweislast` — Anfangercoach Schuldrecht Anspruchslandkarte Beweislast
- `arbeitsnaher-dienstvertrag-bauvertrag-verbraucherbauvertrag` — Arbeitsnaher Dienstvertrag Bauvertrag Verbraucherbauvertrag
- `arbeitsnaher-dienstvertrag-bgb` — Arbeitsnaher Dienstvertrag Bgb
- `auftrag-und-unentgeltliche-taetigkeit` — Auftrag Und Unentgeltliche Taetigkeit
- `bauvertrag-und-verbraucherbauvertrag` — Bauvertrag Und Verbraucherbauvertrag
- `bereicherungsrecht-entreicherung-und-saldotheorie` — Bereicherungsrecht Entreicherung Und Saldotheorie
- `bereicherungsrecht-leistungskondiktion` — Bereicherungsrecht Leistungskondiktion
- `bereicherungsrecht-leistungskondiktion-bereicherungsrecht` — Bereicherungsrecht Leistungskondiktion Bereicherungsrecht
- `bereicherungsrecht-nichtleistungskondiktion` — Bereicherungsrecht Nichtleistungskondiktion
- `bt-fristen-erklaerungen-zugang` — Bt Fristen Erklaerungen Zugang
- `bt-vertragsentwurf-modellvertrag` — Bt Vertragsentwurf Modellvertrag
- `buergschaft-einreden-und-akzessorietaet` — Buergschaft Einreden Und Akzessorietaet
- `buergschaft-form-und-verbraucherbuerge` — Buergschaft Form Und Verbraucherbuerge

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei BGB Besonderer Teil — Prüfungsschemata typisch: Verträge, Lieferscheine, Rechnungen, Mängelrügen.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Verjährung 3 Jahre § 195 BGB, Werkvertrag 5 Jahre § 634a).
- **Beweiswert einordnen.** Urkunden, Zeugen, Sachverständige jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Vertragsparteien.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
