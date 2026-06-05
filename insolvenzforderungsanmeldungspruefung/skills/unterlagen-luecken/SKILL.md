---
name: unterlagen-luecken
description: "Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

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

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Insolvenzforderungsanmeldung oft fehlend: Eröffnungsbeschluss, Forderungsanmeldung, Insolvenztabelle.
- **Pro Lücke.** Beweisthema, Beweismittel (Vertrag, Rechnungen), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: Anmeldefrist im Eröffnungsbeschluss.
- **Beschaffung extern.** Insolvenzgericht (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Insolvenzforderungsanmeldung typischerweise Eröffnungsbeschluss, Forderungsanmeldung zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
