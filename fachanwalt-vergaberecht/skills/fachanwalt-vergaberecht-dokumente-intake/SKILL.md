---
name: fachanwalt-vergaberecht-dokumente-intake
description: "Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Dokumentenintake

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Fachanwalt Vergaberecht** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `bieterstrategie-go-eforms-ted-eignung-referenzen-erstgespraech` — Bieterstrategie Go Eforms Ted Eignung Referenzen Erstgespraech
- `fachanwalt-vergaberecht-aufklaerung-nachforderung-ruege-zuschlag` — Fachanwalt Vergaberecht Aufklaerung Nachforderung Ruege Zuschlag
- `fachanwalt-vergaberecht-facto-eignungspruefung-freiberufliche` — Fachanwalt Vergaberecht Facto Eignungspruefung Freiberufliche
- `fachanwalt-vergaberecht-olg-orientierung-ruegeschriftsatz-gwb` — Fachanwalt Vergaberecht Olg Orientierung Ruegeschriftsatz Gwb
- `it-sicherheits-konzessionsvergabe-konzvgv-losbildung` — It Sicherheits Konzessionsvergabe Konzvgv Losbildung
- `konzvgv-rahmenvereinbarung-international-schnittstelle-sektvo` — Konzvgv Rahmenvereinbarung International Schnittstelle Sektvo
- `mandantenpadlet-vergabe-triage-vergaberecht-nachhaltigkeit` — Mandantenpadlet Vergabe Triage Vergaberecht Nachhaltigkeit
- `olg-vergabesenat-resilienz-sicherheit-ruegeschriftsatz-erstellen` — Olg Vergabesenat Resilienz Sicherheit Ruegeschriftsatz Erstellen
- `rahmenvereinbarung-abrufe-angebotsoeffnung-formfehler` — Rahmenvereinbarung Abrufe Angebotsoeffnung Formfehler
- `schwellenwerte-livecheck-architektenrecht-fachanwalt-konzession` — Schwellenwerte Livecheck Architektenrecht Fachanwalt Konzession
- `ungewoehnlich-niedriges-unterschwellen-rechtsschutz-verg` — Ungewoehnlich Niedriges Unterschwellen Rechtsschutz Verg
- `uvgo-unterschwellenvergabe-vergabesperre-korruption-vk` — Uvgo Unterschwellenvergabe Vergabesperre Korruption Vk
- `verg-interessen-vergabe-vergabekammer-vergaberecht` — Verg Interessen Vergabe Vergabekammer Vergaberecht
- `verg-nachpruefungsverfahren-vergabeverfahren-bauleiter` — Verg Nachpruefungsverfahren Vergabeverfahren Bauleiter

## Arbeitsweg

- **Sortieren nach Dokumenttyp.** Bei Fachanwalt Vergaberecht typisch: Vergabeunterlagen, Angebot, Wertungsvermerk, Rüge.
- **Datum, Absender, Empfänger, Aktenzeichen** je Dokument; Fristwirkung markieren (§ 160 III GWB Rüge unverzüglich (10 Tage), Nachprüfungsantrag 15 Tage).
- **Beweiswert einordnen.** Submissionsprotokoll, Vergabeakten, E-Vergabe-Plattform-Logs jeweils mit Tatsachenbezug.
- **Berufsrecht.** Mandatsgeheimnis (§ 43a BRAO, § 203 StGB), DSGVO bei externer Verarbeitung; keine sensiblen Klartextdaten in Tools ohne AVV.
- **Lücken markieren** — nicht still überlesen; jede Lücke wird Arbeitsauftrag.

## Output

Dokumentenregister mit K/B-Nummerierung, Chronologie, Beweiswerttabelle und Rückfrageliste an Bieter.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
