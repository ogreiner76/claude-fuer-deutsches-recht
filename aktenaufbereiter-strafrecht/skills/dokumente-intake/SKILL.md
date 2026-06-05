---
name: dokumente-intake
description: "Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Aktenaufbereiter Strafrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `aktenaufbereiter-strafrecht` — Aktenaufbereiter Strafrecht
- `akteneinsicht-uebersicht-aktenvorblatt-erstellen-anklageschrift` — Akteneinsicht Uebersicht Aktenvorblatt Erstellen Anklageschrift
- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `beweismittel-katalog-beweisverwertungsverbote-beziehungsmatrix` — Beweismittel Katalog Beweisverwertungsverbote Beziehungsmatrix
- `beziehungen-spezial-chronologie-ergaenzbar` — Beziehungen Chronologie Ergaenzbar
- `ersatz-sonderfall-excel-faehige` — Ersatz Sonderfall Excel Faehige
- `fortlaufend-luecken-personenverzeichnis` — Fortlaufend Luecken Personenverzeichnis
- `fristenliste-strafverfahren-aktenlektuere-fristennotiz` — Fristenliste Strafverfahren Aktenlektuere Fristennotiz
- `kronzeugen-regelung-opferzeugen-besondere-personenverzeichnis` — Kronzeugen Regelung Opferzeugen Besondere Personenverzeichnis
- `revision-rechtsfehler-aktenaufbereiter-aktenvorblatt` — Revision Rechtsfehler Aktenaufbereiter Aktenvorblatt
- `sechs-u-haft-aussageanalyse-aussagepsychologie` — Sechs U Haft Aussageanalyse Aussagepsychologie
- `strafbefehl-einspruchsstrategie-strafzumessung-deutsches` — Strafbefehl Einspruchsstrategie Strafzumessung Deutsches
- `strafrecht-strafverteidigung-uebersichten` — Strafrecht Strafverteidigung Uebersichten
- `vermoegensabschoepfung-dritt-einziehung-verstaendigung-deal` — Vermoegensabschoepfung Dritt Einziehung Verstaendigung Deal

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Strafrechtliche Aktenaufbereitung typisch: Ermittlungsakte, Anklageschrift, Hauptverhandlungsprotokoll, Vernehmungsprotokoll.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Anklage-Erwiderungsfrist, Beweisantrag bis Schluss der Beweisaufnahme).
- **Beweiswert einordnen.** Zeugenaussagen, Tatortfotos, Spurensicherung jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Mandant/Beschuldigter.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
