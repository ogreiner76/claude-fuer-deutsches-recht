---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Hausarbeitenmacher** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-hausarbeit-start-workflow-chronologie` — Allgemein Hausarbeit Start Chronologie
- `aufgabenstellung-erfassen-fachgebiet-routing-gliederung` — Aufgabenstellung Erfassen Fachgebiet Routing Gliederung
- `ausfluegen-didaktisches-durch` — Ausfluegen Didaktisches Durch
- `behutsame-frech-haeufige-fehler-selbstkontrolle-abgabe` — Behutsame Frech Haeufige Fehler Selbstkontrolle Abgabe
- `europarecht-anwendbarkeit-hausarbeiten-bearbeitungsplan` — Europarecht Anwendbarkeit Hausarbeiten Bearbeitungsplan
- `europarecht-interessen-fertigen-sonderfall-fuehrt` — Europarecht Interessen Fertigen Sonderfall Fuehrt
- `gutachtenstil-vs-haus-fussnotenstil-literaturrecherche-leitfaden` — Gutachtenstil Vs Haus Fussnotenstil Literaturrecherche Leitfaden
- `haus-plagiatscheck-haus-themaeingrenzung-meinungsstreit` — Haus Plagiatscheck Haus Themaeingrenzung Meinungsstreit
- `juristische-liefert-beweislast-rechtstheorie` — Juristische Liefert Beweislast Rechtstheorie
- `methodenlehre-auslegung-oeffentliches-statthaft-professor` — Methodenlehre Auslegung Oeffentliches Statthaft Professor
- `rechtstheorie-rechtsphilosophie-seminararbeit-modus-adressaten` — Rechtstheorie Rechtsphilosophie Seminararbeit Modus Adressaten
- `schleimerei-seminararbeiten-sokratisch` — Schleimerei Seminararbeiten Sokratisch
- `strafrecht-zivilrecht-strafrecht-rechtswidrigkeit` — Strafrecht Zivilrecht Strafrecht Rechtswidrigkeit
- `subsumtion-schritt-verfassungsrecht-grundrechtspruefung` — Subsumtion Schritt Verfassungsrecht Grundrechtspruefung

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Jura-Hausarbeiten typisch: Sachverhalt, Literaturverzeichnis, Gliederung, Reinschrift.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Hausarbeits-Abgabefrist, Zitiernachweise).
- **Beweiswert einordnen.** Urkunden, Zeugen, Sachverständige jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Studierender.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
