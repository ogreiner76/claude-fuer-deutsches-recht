---
name: fachanwalt-familienrecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Familienrecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-famr-trennungsfolgen-vermoegensauseinandersetzung` — Allgemein Famr Trennungsfolgen Vermoegensauseinandersetzung
- `anpassung-wegen-anwartschaft-dynamisch-ausgleich-nach` — Anpassung Wegen Anwartschaft Dynamisch Ausgleich Nach
- `anrechte-dokumentenintake` — Anrechte Dokumentenintake
- `beamtenrechtliche-kuerzung-beamtenversorgung` — Beamtenrechtliche Kuerzung Beamtenversorgung
- `erstgespraech-mandatsannahme-eu-auslandsrenten-excel-pruefmatrix` — Erstgespraech Mandatsannahme Eu Auslandsrenten Excel Pruefmatrix
- `fachanwalt-familienrecht-kindeswohlgefaehrdung-mediation-famfg` — Fachanwalt Familienrecht Kindeswohlgefaehrdung Mediation Famfg
- `fachanwalt-familienrecht-unterhaltsberechnung-zugewinnausgleich` — Fachanwalt Familienrecht Unterhaltsberechnung Zugewinnausgleich
- `familiengericht-familienrecht-lebenspartnerschaft-beweislast` — Familiengericht Familienrecht Lebenspartnerschaft Beweislast
- `famr-mandantenaufnahme-regenbogenfamilien-versorgungsausgleich` — Famr Mandantenaufnahme Regenbogenfamilien Versorgungsausgleich
- `geringfuegigkeit-versausglg-gesetzliche-rentenversicherung` — Geringfuegigkeit Versausglg Gesetzliche Rentenversicherung
- `kanzlei-fristennotiz-orientierung-ehevertrag` — Kanzlei Fristennotiz Orientierung Ehevertrag
- `kapitalwert-korrespondierender-kindeswohl-hochkonflikt` — Kapitalwert Korrespondierender Kindeswohl Hochkonflikt
- `lebensversicherung-abgrenzung-mandantenblatt` — Lebensversicherung Abgrenzung Mandantenblatt
- `nicht-ausgleichsreife-notarielle-scheidungsfolgenvereinbarung` — Nicht Ausgleichsreife Notarielle Scheidungsfolgenvereinbarung

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Familienrecht typisch: Heiratsurkunde, Scheidungsantrag, Vermögensauseinandersetzung, Unterhaltsberechnung.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (Trennungsjahr § 1565 BGB, Beschwerde 1 Monat § 63 FamFG).
- **Beweiswert einordnen.** Einkommensnachweise, Vermögensauskunft, Sozialberichte Jugendamt jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Ehegatten.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
