# Ordnungswidrigkeitenrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`ordnungswidrigkeitenrecht`) | [`ordnungswidrigkeitenrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/ordnungswidrigkeitenrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **OWiG-Akte** (`ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier`) | [Gesamt-PDF lesen](../testakten/ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier/gesamt-pdf/ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier_gesamt.pdf) | [`testakte-ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist das allgemeine Betriebssystem für Bußgeldsachen, nicht nur Verkehr: OWiG-Verfahren, Fachordnungswidrigkeiten, Anhörung, Bußgeldbescheid, Einspruch, Akteneinsicht, Amtsgericht und Rechtsbeschwerde.

## Start

Beginne mit `ordnungswidrigkeitenrecht-allgemein`. Das Plugin fragt zuerst nach Rolle, Ziel, Frist, Behörde/Gericht/Register, vorhandenen Unterlagen und gewünschtem Output. Danach schlägt es die passenden Spezialskills aus diesem Plugin vor.

## Arbeitsweise

- Es arbeitet mit Akten- und Fristenlogik statt mit Bauchgefühl.
- Es trennt Rechtsgrundlage, Verfahren, Beweis, Kosten, Kommunikation und Eskalation.
- Es soll Nutzerinnen und Nutzer befähigen: verständliche Erklärung, präzise Rückfragen, dann belastbarer Entwurf.
- Rechtsprechung und Gesetzesstände werden nicht halluziniert, sondern als Live-Check über amtliche oder frei zugängliche Quellen markiert.

## Typische Outputs

- Kaltstart-Interview und Aktenlandkarte
- Behörden-, Gerichts- oder Gegneranschreiben
- Widerspruchs-/Klage-/Eilantragsbausteine
- Kosten-, Fristen- und Zuständigkeitsmatrix
- Dashboard/Tracker für laufende Vorgänge
- Kurzfassung für Mandant, Vorstand, Verband, Redaktion oder Bürgerin

## Quellenhygiene

Siehe [`references/QUELLEN.md`](./references/QUELLEN.md). Dieses Plugin gibt keine endgültige Rechtsberatung, sondern robuste Arbeitsfassungen, Prüfpfade und Dokumentationshilfen.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 100 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `ordnungswidrigkeitenrecht-kaltstart-triage` | Ordnungswidrigkeitenrecht: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Fachmodul-Routing und erste Ausgabe. |
| `ordnungswidrigkeitenrecht-owi-akteneinsicht-beantragen` | Ordnungswidrigkeitenrecht: Akteneinsicht beantragen. Akteneinsicht beantragen im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Q... |
| `ordnungswidrigkeitenrecht-owi-aussenwirtschaft-gerichtstermin` | Ordnungswidrigkeitenrecht: Außenwirtschaft: Gerichtstermin vorbereiten. Gerichtstermin vorbereiten für Außenwirtschaft im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen... |
| `ordnungswidrigkeitenrecht-owi-baurecht-frist-strassenverkehr` | Ordnungswidrigkeitenrecht: Baurecht: Frist prüfen. Frist prüfen für Baurecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quelle... |
| `ordnungswidrigkeitenrecht-owi-baurecht-mandantenbrief` | Ordnungswidrigkeitenrecht: Baurecht: Mandantenbrief schreiben. Mandantenbrief schreiben für Baurecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges P... |
| `ordnungswidrigkeitenrecht-owi-datenschutzbussgeld-beweis` | Ordnungswidrigkeitenrecht: Datenschutzbußgeld: Beweis rügen. Beweis rügen für Datenschutzbußgeld im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüff... |
| `ordnungswidrigkeitenrecht-owi-datenschutzbussgeld-tatbestand` | Ordnungswidrigkeitenrecht: Datenschutzbußgeld: Tatbestand zerlegen. Tatbestand zerlegen für Datenschutzbußgeld im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigens... |
| `ordnungswidrigkeitenrecht-owi-einspruch-fristgerecht` | Ordnungswidrigkeitenrecht: Einspruch fristgerecht einlegen. Einspruch fristgerecht einlegen im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffe... |
| `ordnungswidrigkeitenrecht-owi-lebensmittelrecht-einspruch` | Ordnungswidrigkeitenrecht: Lebensmittelrecht: Einspruch begründen. Einspruch begründen für Lebensmittelrecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenstä... |
| `ordnungswidrigkeitenrecht-owi-lebensmittelrecht-gerichtstermin` | Ordnungswidrigkeitenrecht: Lebensmittelrecht: Gerichtstermin vorbereiten. Gerichtstermin vorbereiten für Lebensmittelrecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt tre... |
| `ordnungswidrigkeitenrecht-owi-umwelt-rechtsbeschwerde` | Ordnungswidrigkeitenrecht: Umwelt-OWi: Rechtsbeschwerde prüfen. Rechtsbeschwerde prüfen für Umwelt-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges... |
| `owi-001-kaltstart-bussgeldverfahren` | Ordnungswidrigkeitenrecht: Kaltstart Bußgeldverfahren. Kaltstart Bußgeldverfahren im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `owi-002-tatbestand-fachgesetz-finden` | Ordnungswidrigkeitenrecht: Tatbestand Fachgesetz finden. Tatbestand Fachgesetz finden im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit... |
| `owi-003-anhoerung-richtig-behandeln` | Ordnungswidrigkeitenrecht: Anhörung richtig behandeln. Anhörung richtig behandeln im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Nor... |
| `owi-004-bussgeldbescheid-pruefen` | Ordnungswidrigkeitenrecht: Bußgeldbescheid prüfen. Bußgeldbescheid prüfen im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quell... |
| `owi-007-verjaehrung-und-unterbrechung` | Ordnungswidrigkeitenrecht: Verjährung und Unterbrechung. Verjährung und Unterbrechung im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit... |
| `owi-008-zustaendige-verwaltungsbehoerde` | Ordnungswidrigkeitenrecht: Zuständige Verwaltungsbehörde. Zuständige Verwaltungsbehörde im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld m... |
| `owi-009-opportunitaet-und-einstellung` | Ordnungswidrigkeitenrecht: Opportunität und Einstellung. Opportunität und Einstellung im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit... |
| `owi-011-aufsichtspflichtverletzung-130-owig` | Ordnungswidrigkeitenrecht: Aufsichtspflichtverletzung § 130 OWiG. Aufsichtspflichtverletzung § 130 OWiG im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenstän... |
| `owi-012-einziehung-und-verfall-pruefen` | Ordnungswidrigkeitenrecht: Einziehung und Verfall prüfen. Einziehung und Verfall prüfen im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld m... |
| `owi-013-nebenfolgen-und-register` | Ordnungswidrigkeitenrecht: Nebenfolgen und Register. Nebenfolgen und Register im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Q... |
| `owi-014-abgabe-an-staatsanwaltschaft` | Ordnungswidrigkeitenrecht: Abgabe an Staatsanwaltschaft. Abgabe an Staatsanwaltschaft im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit... |
| `owi-016-beschlussverfahren-72-owig` | Ordnungswidrigkeitenrecht: Beschlussverfahren § 72 OWiG. Beschlussverfahren § 72 OWiG im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit... |
| `owi-017-rechtsbeschwerde-pruefen` | Ordnungswidrigkeitenrecht: Rechtsbeschwerde prüfen. Rechtsbeschwerde prüfen im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Que... |
| `owi-018-kostenentscheidung-angreifen` | Ordnungswidrigkeitenrecht: Kostenentscheidung angreifen. Kostenentscheidung angreifen im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit... |
| `owi-019-jugendliche-im-owi-verfahren` | Ordnungswidrigkeitenrecht: Jugendliche im OWi-Verfahren. Jugendliche im OWi-Verfahren im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit... |
| `owi-020-owig-in-einfacher-sprache` | Ordnungswidrigkeitenrecht: OWiG in einfacher Sprache. OWiG in einfacher Sprache im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-... |
| `owi-022-datenschutzbussgeld-frist-pruefen` | Ordnungswidrigkeitenrecht: Datenschutzbußgeld: Frist prüfen. Frist prüfen für Datenschutzbußgeld im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüff... |
| `owi-023-datenschutzbussgeld-akteneinsicht-schr` | Ordnungswidrigkeitenrecht: Datenschutzbußgeld: Akteneinsicht schreiben. Akteneinsicht schreiben für Datenschutzbußgeld im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen... |
| `owi-024-datenschutzbussgeld-einspruch-begruend` | Ordnungswidrigkeitenrecht: Datenschutzbußgeld: Einspruch begründen. Einspruch begründen für Datenschutzbußgeld im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigens... |
| `owi-025-datenschutzbussgeld-einstellung-anrege` | Ordnungswidrigkeitenrecht: Datenschutzbußgeld: Einstellung anregen. Einstellung anregen für Datenschutzbußgeld im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigens... |
| `owi-027-datenschutzbussgeld-verjaehrung-berech` | Ordnungswidrigkeitenrecht: Datenschutzbußgeld: Verjährung berechnen. Verjährung berechnen für Datenschutzbußgeld im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eige... |
| `owi-028-datenschutzbussgeld-gerichtstermin-vor` | Ordnungswidrigkeitenrecht: Datenschutzbußgeld: Gerichtstermin vorbereiten. Gerichtstermin vorbereiten für Datenschutzbußgeld im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt t... |
| `owi-029-datenschutzbussgeld-rechtsbeschwerde-p` | Ordnungswidrigkeitenrecht: Datenschutzbußgeld: Rechtsbeschwerde prüfen. Rechtsbeschwerde prüfen für Datenschutzbußgeld im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen... |
| `owi-033-gewerberecht-akteneinsicht-schreiben` | Ordnungswidrigkeitenrecht: Gewerberecht: Akteneinsicht schreiben. Akteneinsicht schreiben für Gewerberecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständ... |
| `owi-034-gewerberecht-einspruch-begruenden` | Ordnungswidrigkeitenrecht: Gewerberecht: Einspruch begründen. Einspruch begründen für Gewerberecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prü... |
| `owi-035-gewerberecht-einstellung-anregen` | Ordnungswidrigkeitenrecht: Gewerberecht: Einstellung anregen. Einstellung anregen für Gewerberecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prü... |
| `owi-037-gewerberecht-verjaehrung-berechnen` | Ordnungswidrigkeitenrecht: Gewerberecht: Verjährung berechnen. Verjährung berechnen für Gewerberecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges P... |
| `owi-038-gewerberecht-gerichtstermin-vorbereite` | Ordnungswidrigkeitenrecht: Gewerberecht: Gerichtstermin vorbereiten. Gerichtstermin vorbereiten für Gewerberecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eige... |
| `owi-039-gewerberecht-rechtsbeschwerde-pruefen` | Ordnungswidrigkeitenrecht: Gewerberecht: Rechtsbeschwerde prüfen. Rechtsbeschwerde prüfen für Gewerberecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständ... |
| `owi-041-umwelt-owi-tatbestand-zerlegen` | Ordnungswidrigkeitenrecht: Umwelt-OWi: Tatbestand zerlegen. Tatbestand zerlegen für Umwelt-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffel... |
| `owi-042-umwelt-owi-frist-pruefen` | Ordnungswidrigkeitenrecht: Umwelt-OWi: Frist prüfen. Frist prüfen für Umwelt-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `owi-043-umwelt-owi-akteneinsicht-schreiben` | Ordnungswidrigkeitenrecht: Umwelt-OWi: Akteneinsicht schreiben. Akteneinsicht schreiben für Umwelt-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges... |
| `owi-044-umwelt-owi-einspruch-begruenden` | Ordnungswidrigkeitenrecht: Umwelt-OWi: Einspruch begründen. Einspruch begründen für Umwelt-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffel... |
| `owi-046-umwelt-owi-beweis-ruegen` | Ordnungswidrigkeitenrecht: Umwelt-OWi: Beweis rügen. Beweis rügen für Umwelt-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `owi-047-umwelt-owi-verjaehrung-berechnen` | Ordnungswidrigkeitenrecht: Umwelt-OWi: Verjährung berechnen. Verjährung berechnen für Umwelt-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüff... |
| `owi-048-umwelt-owi-gerichtstermin-vorbereiten` | Ordnungswidrigkeitenrecht: Umwelt-OWi: Gerichtstermin vorbereiten. Gerichtstermin vorbereiten für Umwelt-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenstä... |
| `owi-050-umwelt-owi-mandantenbrief-schreiben` | Ordnungswidrigkeitenrecht: Umwelt-OWi: Mandantenbrief schreiben. Mandantenbrief schreiben für Umwelt-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständig... |
| `owi-051-lebensmittelrecht-tatbestand-zerlegen` | Ordnungswidrigkeitenrecht: Lebensmittelrecht: Tatbestand zerlegen. Tatbestand zerlegen für Lebensmittelrecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenstä... |
| `owi-052-lebensmittelrecht-frist-pruefen` | Ordnungswidrigkeitenrecht: Lebensmittelrecht: Frist prüfen. Frist prüfen für Lebensmittelrecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffel... |
| `owi-053-lebensmittelrecht-akteneinsicht-schrei` | Ordnungswidrigkeitenrecht: Lebensmittelrecht: Akteneinsicht schreiben. Akteneinsicht schreiben für Lebensmittelrecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen:... |
| `owi-055-lebensmittelrecht-einstellung-anregen` | Ordnungswidrigkeitenrecht: Lebensmittelrecht: Einstellung anregen. Einstellung anregen für Lebensmittelrecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenstä... |
| `owi-056-lebensmittelrecht-beweis-ruegen` | Ordnungswidrigkeitenrecht: Lebensmittelrecht: Beweis rügen. Beweis rügen für Lebensmittelrecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffel... |
| `owi-057-lebensmittelrecht-verjaehrung-berechne` | Ordnungswidrigkeitenrecht: Lebensmittelrecht: Verjährung berechnen. Verjährung berechnen für Lebensmittelrecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigens... |
| `owi-059-lebensmittelrecht-rechtsbeschwerde-pru` | Ordnungswidrigkeitenrecht: Lebensmittelrecht: Rechtsbeschwerde prüfen. Rechtsbeschwerde prüfen für Lebensmittelrecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen:... |
| `owi-060-lebensmittelrecht-mandantenbrief-schre` | Ordnungswidrigkeitenrecht: Lebensmittelrecht: Mandantenbrief schreiben. Mandantenbrief schreiben für Lebensmittelrecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen... |
| `owi-061-tierschutz-owi-tatbestand-zerlegen` | Ordnungswidrigkeitenrecht: Tierschutz-OWi: Tatbestand zerlegen. Tatbestand zerlegen für Tierschutz-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges... |
| `owi-062-tierschutz-owi-frist-pruefen` | Ordnungswidrigkeitenrecht: Tierschutz-OWi: Frist prüfen. Frist prüfen für Tierschutz-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit... |
| `owi-064-tierschutz-owi-einspruch-begruenden` | Ordnungswidrigkeitenrecht: Tierschutz-OWi: Einspruch begründen. Einspruch begründen für Tierschutz-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges... |
| `owi-065-tierschutz-owi-einstellung-anregen` | Ordnungswidrigkeitenrecht: Tierschutz-OWi: Einstellung anregen. Einstellung anregen für Tierschutz-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges... |
| `owi-066-tierschutz-owi-beweis-ruegen` | Ordnungswidrigkeitenrecht: Tierschutz-OWi: Beweis rügen. Beweis rügen für Tierschutz-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit... |
| `owi-068-tierschutz-owi-gerichtstermin-vorberei` | Ordnungswidrigkeitenrecht: Tierschutz-OWi: Gerichtstermin vorbereiten. Gerichtstermin vorbereiten für Tierschutz-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen:... |
| `owi-069-tierschutz-owi-rechtsbeschwerde-pruefe` | Ordnungswidrigkeitenrecht: Tierschutz-OWi: Rechtsbeschwerde prüfen. Rechtsbeschwerde prüfen für Tierschutz-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigens... |
| `owi-070-tierschutz-owi-mandantenbrief-schreibe` | Ordnungswidrigkeitenrecht: Tierschutz-OWi: Mandantenbrief schreiben. Mandantenbrief schreiben für Tierschutz-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eige... |
| `owi-073-baurecht-akteneinsicht-schreiben` | Ordnungswidrigkeitenrecht: Baurecht: Akteneinsicht schreiben. Akteneinsicht schreiben für Baurecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prü... |
| `owi-074-baurecht-einspruch-begruenden` | Ordnungswidrigkeitenrecht: Baurecht: Einspruch begründen. Einspruch begründen für Baurecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mi... |
| `owi-075-baurecht-einstellung-anregen` | Ordnungswidrigkeitenrecht: Baurecht: Einstellung anregen. Einstellung anregen für Baurecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mi... |
| `owi-077-baurecht-verjaehrung-berechnen` | Ordnungswidrigkeitenrecht: Baurecht: Verjährung berechnen. Verjährung berechnen für Baurecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld... |
| `owi-078-baurecht-gerichtstermin-vorbereiten` | Ordnungswidrigkeitenrecht: Baurecht: Gerichtstermin vorbereiten. Gerichtstermin vorbereiten für Baurecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständig... |
| `owi-079-baurecht-rechtsbeschwerde-pruefen` | Ordnungswidrigkeitenrecht: Baurecht: Rechtsbeschwerde prüfen. Rechtsbeschwerde prüfen für Baurecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prü... |
| `owi-081-strassenverkehr-tatbestand-zerlegen` | Ordnungswidrigkeitenrecht: Straßenverkehr: Tatbestand zerlegen. Tatbestand zerlegen für Straßenverkehr im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges... |
| `owi-082-strassenverkehr-frist-pruefen` | Ordnungswidrigkeitenrecht: Straßenverkehr: Frist prüfen. Frist prüfen für Straßenverkehr im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit... |
| `owi-083-strassenverkehr-akteneinsicht-schreibe` | Ordnungswidrigkeitenrecht: Straßenverkehr: Akteneinsicht schreiben. Akteneinsicht schreiben für Straßenverkehr im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigens... |
| `owi-084-strassenverkehr-einspruch-begruenden` | Ordnungswidrigkeitenrecht: Straßenverkehr: Einspruch begründen. Einspruch begründen für Straßenverkehr im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges... |
| `owi-086-strassenverkehr-beweis-ruegen` | Ordnungswidrigkeitenrecht: Straßenverkehr: Beweis rügen. Beweis rügen für Straßenverkehr im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit... |
| `owi-087-strassenverkehr-verjaehrung-berechnen` | Ordnungswidrigkeitenrecht: Straßenverkehr: Verjährung berechnen. Verjährung berechnen für Straßenverkehr im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständig... |
| `owi-088-strassenverkehr-gerichtstermin-vorbere` | Ordnungswidrigkeitenrecht: Straßenverkehr: Gerichtstermin vorbereiten. Gerichtstermin vorbereiten für Straßenverkehr im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen:... |
| `owi-090-strassenverkehr-mandantenbrief-schreib` | Ordnungswidrigkeitenrecht: Straßenverkehr: Mandantenbrief schreiben. Mandantenbrief schreiben für Straßenverkehr im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eige... |
| `owi-091-aussenwirtschaft-tatbestand-zerlegen` | Ordnungswidrigkeitenrecht: Außenwirtschaft: Tatbestand zerlegen. Tatbestand zerlegen für Außenwirtschaft im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständig... |
| `owi-092-aussenwirtschaft-frist-pruefen` | Ordnungswidrigkeitenrecht: Außenwirtschaft: Frist prüfen. Frist prüfen für Außenwirtschaft im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mi... |
| `owi-093-aussenwirtschaft-akteneinsicht-schreib` | Ordnungswidrigkeitenrecht: Außenwirtschaft: Akteneinsicht schreiben. Akteneinsicht schreiben für Außenwirtschaft im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eige... |
| `owi-095-aussenwirtschaft-einstellung-anregen` | Ordnungswidrigkeitenrecht: Außenwirtschaft: Einstellung anregen. Einstellung anregen für Außenwirtschaft im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständig... |
| `owi-096-aussenwirtschaft-beweis-ruegen` | Ordnungswidrigkeitenrecht: Außenwirtschaft: Beweis rügen. Beweis rügen für Außenwirtschaft im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mi... |
| `owi-097-aussenwirtschaft-verjaehrung-berechnen` | Ordnungswidrigkeitenrecht: Außenwirtschaft: Verjährung berechnen. Verjährung berechnen für Außenwirtschaft im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständ... |
| `owi-099-aussenwirtschaft-rechtsbeschwerde-prue` | Ordnungswidrigkeitenrecht: Außenwirtschaft: Rechtsbeschwerde prüfen. Rechtsbeschwerde prüfen für Außenwirtschaft im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eige... |
| `owi-amtsgericht-hauptverhandlung` | Ordnungswidrigkeitenrecht: Amtsgericht Hauptverhandlung. Amtsgericht Hauptverhandlung im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit... |
| `owi-aussenwirtschaft-einspruch-einstellung` | Ordnungswidrigkeitenrecht: Außenwirtschaft: Einspruch begründen. Einspruch begründen für Außenwirtschaft im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständig... |
| `owi-baurecht-ruegen-verjaehrung-berechnen` | Ordnungswidrigkeitenrecht: Baurecht: Beweis rügen. Beweis rügen für Baurecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quelle... |
| `owi-baurecht-zerlegen-akteneinsicht-schreiben` | Ordnungswidrigkeitenrecht: Baurecht: Tatbestand zerlegen. Tatbestand zerlegen für Baurecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mi... |
| `owi-datenschutzbussgeld-mandantenbrief-abgabe` | Ordnungswidrigkeitenrecht: Datenschutzbußgeld: Mandantenbrief schreiben. Mandantenbrief schreiben für Datenschutzbußgeld im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trenn... |
| `owi-gewerberecht-frist-umwelt` | Ordnungswidrigkeitenrecht: Gewerberecht: Frist prüfen. Frist prüfen für Gewerberecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm... |
| `owi-gewerberecht-mandantenbrief-umwelt` | Ordnungswidrigkeitenrecht: Gewerberecht: Mandantenbrief schreiben. Mandantenbrief schreiben für Gewerberecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenstä... |
| `owi-gewerberecht-ruegen-verjaehrung-berechnen` | Ordnungswidrigkeitenrecht: Gewerberecht: Beweis rügen. Beweis rügen für Gewerberecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm... |
| `owi-gewerberecht-zerlegen-akteneinsicht` | Ordnungswidrigkeitenrecht: Gewerberecht: Tatbestand zerlegen. Tatbestand zerlegen für Gewerberecht im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prü... |
| `owi-strassenverkehr-einstellung-ruegen` | Ordnungswidrigkeitenrecht: Straßenverkehr: Einstellung anregen. Einstellung anregen für Straßenverkehr im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges... |
| `owi-strassenverkehr-rechtsbeschwerde` | Ordnungswidrigkeitenrecht: Straßenverkehr: Rechtsbeschwerde prüfen. Rechtsbeschwerde prüfen für Straßenverkehr im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigens... |
| `owi-tierschutz-akteneinsicht-einspruch` | Ordnungswidrigkeitenrecht: Tierschutz-OWi: Akteneinsicht schreiben. Akteneinsicht schreiben für Tierschutz-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigens... |
| `owi-tierschutz-verjaehrung-gerichtstermin` | Ordnungswidrigkeitenrecht: Tierschutz-OWi: Verjährung berechnen. Verjährung berechnen für Tierschutz-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständig... |
| `owi-umwelt-einstellung-ruegen-verjaehrung` | Ordnungswidrigkeitenrecht: Umwelt-OWi: Einstellung anregen. Einstellung anregen für Umwelt-OWi im Rahmen von Ordnungswidrigkeitenrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffel... |
| `owi-unternehmen-verbandsgeldbusse` | Ordnungswidrigkeitenrecht: Unternehmen und Verbandsgeldbuße. Unternehmen und Verbandsgeldbuße im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüf... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
