# berufsrecht-ki-vertragspruefung — Arbeitsanweisungen

## Tonalität und Disclaimer

Vor jeder neuen Skill-Ausgabe diesen Disclaimer mitführen, mindestens in der Eröffnung des Gutachtens und in jedem Brief:

> Diese Forprüfung ist keine Rechtsberatung. Sie ist eine strukturierte Argumentationshilfe für das Anbietergespräch. Die abschließende berufsrechtliche und strafrechtliche Beurteilung im konkreten Einzelfall bleibt der inhabilen Kanzlei bzw. einer beauftragten Spezialkanzlei vorbehalten.

## Quellenpolitik

- Goldstandard: DAV-Initiativstellungnahme Nr. 32/2025 (Juli 2025).
- Memorandum einer Spezialkanzlei zu § 43e BRAO und § 203 StGB.
- BT-Drs. 18/12940 für die Genese des § 43e BRAO.
- BRAK-Leitfaden Dezember 2024 wird kurz und kritisch eingeordnet, **nicht als maßgeblich behandelt**.
- BGH-Pinpoint immer mit Aktenzeichen und Randnummer (etwa: BGH NJW 2024, 123 Rn. 14). Bei Unsicherheit live recherchieren oder als Lücke kennzeichnen.
- Kommentarliteratur: **Grüneberg** statt Palandt; **MüKo BGB / MüKo StGB**; **Erbs/Kohlhaas** für Nebenstrafrecht.
- Larenz NICHT zitieren.

## Methodik

- Pro Skill: zuerst Norm zitieren, dann Auslegung nach DAV, dann konkrete Prüfpunkte am Vertrag.
- Pro Prüfpunkt: Ampel grün / gelb / rot mit kurzer Begründung.
- Gelbe und rote Punkte fließen in den Rückfragebrief und in die Klauselvorschläge ein.
- Berufsrechtlich-strafrechtliche Perspektive klar von datenschutzrechtlicher Perspektive (Art. 28 DS-GVO) trennen. Letzteres nur als Schnittstelle, ausdrücklich nicht im Hauptfokus.

## Norm-Adapter

Pro Berufsgruppe stehen folgende Normen in der jeweiligen Skill-Ausgabe:

| Beruf | Verschwiegenheit | Dienstleister | § 203 StGB |
|---|---|---|---|
| Rechtsanwalt | § 43a Abs. 2 BRAO | § 43e BRAO | Abs. 1 Nr. 3 |
| Steuerberater | § 57 Abs. 1 StBerG | § 62a StBerG | Abs. 1 Nr. 3 |
| Wirtschaftsprüfer | § 43 WPO | § 50a WPO (§ 59c bei Berufsgesellschaft) | Abs. 1 Nr. 3 |
| Patentanwalt | § 39a Abs. 2 PAO | § 39c PAO | Abs. 1 Nr. 3 |
| Notar | § 18 BNotO | § 26a BNotO | Abs. 1 Nr. 1 |

Beim Notar ist die Eröffnung gegenüber Dienstleistern ohne Einwilligung des Beteiligten ausdrücklich zulässig (§ 26a Abs. 1 BNotO); bei Dienstleistungen, die unmittelbar einem einzelnen Amtsgeschäft dienen, ist die Einwilligung nach Abs. 4 erforderlich.

## Workflow

1. `kaltstart-interview` — Beruf, Anbieter, Datenarten erfassen.
2. Materielle Prüfungen — Erforderlichkeit, Verschwiegenheit, Belehrung, Subunternehmer, StPO, Ausland.
3. Technische Prüfung — TOM, Zertifizierungen, Cloud Act.
4. Datenschutz-Schnittstelle (kurz).
5. Output — Gutachten, Rückfragebrief, Klauselvorschläge.

## Validator-Anforderungen

- Skill-Description maximal 300 Zeichen.
- Keine Kommazahlen in der Description (kein `42,5` etc.). Größenangaben als Worte ("Vier-Stufen-Prüfung") oder mit Punkt ("42.5").
- Umlaute (ä ö ü ß) in eigens für dieses Plugin geschriebenen Texten erlaubt. In Skill-Description trotzdem vorsichtig — der Validator akzeptiert Umlaute, aber Konsistenz mit Schwesterplugins beachten.
