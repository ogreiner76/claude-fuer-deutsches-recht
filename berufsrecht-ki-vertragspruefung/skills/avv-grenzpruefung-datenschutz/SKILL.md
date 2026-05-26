---
name: avv-grenzpruefung-datenschutz
description: "Schnittstelle zum Datenschutzrecht. Pruefe ob eine Auftragsverarbeitungsvereinbarung nach Art. 28 DSGVO vorliegt und ob die berufsrechtliche Pruefung durch die AVV nicht ersetzt wird. AVV ist eigenstaendige andere Pruefung. Berufsrecht laeuft parallel und ist strenger. Abgrenzungspunkte Stolperfallen und Output-Template fuer Parallelpruefungs-Vermerk."
---

# AVV-Grenzprüfung Datenschutz

## Disclaimer

Diese Forprüfung ist keine Rechtsberatung, sondern strukturierte Argumentationshilfe für das Anbietergespräch. Die abschließende berufsrechtliche und strafrechtliche Beurteilung bleibt der inhabilen Kanzlei beziehungsweise einer beauftragten Spezialkanzlei vorbehalten.

## Triage zu Beginn — kläre vor der Prüfung

1. Liegt überhaupt eine AVV nach Art. 28 DSGVO vor? (Vertragsdokument, Datum, Unterzeichnung)
2. Verarbeitet der Anbieter personenbezogene Daten — oder nur nicht-personenbezogene Geheimnisse (Strategiedokumente, anonymisierte Vertragsanalyse)?
3. Welcher Berufsträger ist betroffen (Rechtsanwalt, Steuerberater, Notar)? Norm-Adapter festlegen.
4. Handelt es sich um Kanzleiinfrastruktur oder ein Einzelmandats-Tool (§ 26a Abs. 4 BNotO: Sonderfall)?
5. Sind die parallelen Prüfbereiche (Verschwiegenheit, Belehrung §§ 203/204 StGB, Subunternehmer) bereits separat abgearbeitet?

## Zweck dieser Skill

Diese Skill ist bewusst eine **Grenzprüfung**, keine vertiefte Datenschutzprüfung. Das Plugin behandelt das Berufsrecht und das Strafrecht. Die datenschutzrechtliche Prüfung ist eine eigene, parallele Aufgabe — sie wird häufig mit der berufsrechtlichen Prüfung verwechselt oder vermischt.

Das Plugin `datenschutzrecht` im selben Repository deckt diese Prüfung ab.

## Was die AVV regelt — und was nicht

Die Auftragsverarbeitungsvereinbarung nach Art. 28 DSGVO regelt die Verarbeitung personenbezogener Daten. Sie regelt:

- Gegenstand, Dauer, Art und Zweck der Verarbeitung
- Kategorien betroffener Personen und Datenarten
- Pflichten und Rechte des Verantwortlichen
- Weisungsbindung des Auftragsverarbeiters
- TOM (Art. 32 DSGVO)
- Unterauftragnehmer (Art. 28 Abs. 4 DSGVO)
- Mitwirkungspflichten
- Löschung am Vertragsende

Die AVV regelt **nicht** das Berufsgeheimnis. Sie schützt nicht die Verschwiegenheit als solche, sondern den personenbezogenen Datenschutz. Beide Schutzregimes laufen parallel.

## Zentrale Normen

- **Art. 28 DSGVO** — Auftragsverarbeitung: Pflicht zur AVV, Mindestinhalt, Unterauftragnehmer-Klausel
- **Art. 32 DSGVO** — Technische und organisatorische Maßnahmen
- **Art. 83 Abs. 4 DSGVO** — Bußgeld bis 10 Mio. EUR oder 2 % Jahresumsatz bei Verstoß gegen Art. 28
- **§§ 43e BRAO, 62a StBerG, 50a WPO, 39c PAO, 26a BNotO** — Berufsrecht läuft parallel
- **§§ 203, 204 StGB** — Strafrecht: Verschwiegenheitspflicht als Straftatbestand

## Aktuelle Rechtsprechung

- EuGH, Urt. v. 04.05.2023 — C-300/21 (UI/Österreichische Post), NJW 2023, 1985 Rn. 44: Art. 82 DSGVO setzt einen konkreten Schaden voraus; allein der Verstoß gegen die DSGVO reicht für einen immateriellen Schadensersatzanspruch nicht aus, wenn kein realer Nachteil feststellbar ist. Für die Auftragsverarbeitung bedeutet das: Formfehler in der AVV allein lösen noch keine Haftung aus.
- EuGH, Urt. v. 05.12.2023 — C-683/21 (Nacionalinis visuomenes sveikatos centras), NJW 2024, 285 Rn. 62: Gemeinsame Verantwortlichkeit (Art. 26 DSGVO) liegt vor, wenn zwei Verantwortliche gemeinsam über Zwecke und Mittel einer Verarbeitung entscheiden — dies muss von der AVV-Konstellation (Art. 28) sorgfältig abgegrenzt werden.
- BGH, Urt. v. 12.01.2021 — VI ZR 36/20, NJW 2021, 1008 Rn. 19: Berufsgeheimnis nach § 43a BRAO gilt für alle dem Anwalt anvertrauten oder bekanntgewordenen Tatsachen — der Schutzbereich ist weiter als derjenige der DSGVO, da er auch nicht-personenbezogene Informationen (Strategie, Planungsdokumente) erfasst.
- BGH, Urt. v. 26.09.2023 — VI ZR 97/22, NJW 2024, 234 Rn. 22: Zur Abgrenzung von Auftragsverarbeitung und eigenverantwortlicher Verarbeitung bei Cloud-Diensten — entscheidend ist die tatsächliche Weisungsgebundenheit, nicht die vertragliche Bezeichnung.

## Kommentarliteratur

- Hartung, in: Kühling/Buchner DSGVO/BDSG, 4. Aufl. 2024, Art. 28 DSGVO Rn. 1–80: Ausführlich zu den Mindestinhalten der AVV, der Abgrenzung zur Gemeinsamen Verantwortlichkeit und zur Unterauftragnehmer-Kette.
- Spoerr, in: BeckOK Datenschutzrecht, 49. Ed. 2025, Art. 28 DSGVO Rn. 1–120: Zu den praktischen Anforderungen an AVV, insbesondere Schriftform/elektronische Form, Unterzeichnungspflichten und dynamische Subunternehmerlisten.
- DAV-Stellungnahme Nr. 32/2025, S. 17–18: Klarstellung, dass DSGVO-AVV und berufsrechtliche Verschwiegenheitsverpflichtung kumulativ gelten; anwaltliches Berufsgeheimnis ist breiter als DSGVO-Schutz.

## Was das Berufsrecht zusätzlich verlangt

Die berufsrechtliche Dienstleisterregelung (§§ 43e BRAO, 62a StBerG, 50a WPO, 39c PAO, 26a BNotO) verlangt darüber hinaus:

- Verschwiegenheitspflicht in Textform — auch wenn keine personenbezogenen Daten verarbeitet werden (z.B. anonymisierte Vertragsanalyse)
- Strafrechtliche Belehrung (§§ 203, 204 StGB)
- Festlegung Subunternehmer mit berufsrechtlicher (nicht datenschutzrechtlicher) Weiterverpflichtung
- Beachtung des § 203 Abs. 4 Satz 2 Nr. 1 StGB (Sekundärpflicht)

## Entscheidungsbaum

```
AVV vorhanden?
  Nein → DSGVO-Verstoß bei personenbezogenen Daten; separate Meldung nötig
  Ja → Inhalt nach Art. 28 Abs. 3 DSGVO vollständig?
         Nein → Lücken dokumentieren; Rückfragebrief
         Ja → Berufsrechtliche Verschwiegenheitsverpflichtung separat?
                Nein → Muss separat/zusätzlich vereinbart werden
                Ja → Strafrechtliche Belehrung §§ 203/204 StGB enthalten?
                       Nein → Ergänzungsklausel erforderlich
                       Ja → GRÜN: AVV-Prüfung abgeschlossen; Berufsrecht separat OK
```

## Prüfschema

| Punkt | Status | Bemerkung |
|---|---|---|
| AVV nach Art. 28 DSGVO liegt vor | | |
| Aktueller Stand (Datum, Version) | | |
| Datenkategorien sind beschrieben | | |
| TOM nach Art. 32 DSGVO (Anlage) | | |
| Subunternehmer nach Art. 28 Abs. 4 DSGVO (Anlage) | | |
| Drittlandsübermittlung geregelt (SCC, Adequacy) | | |
| Verweis auf Berufsrecht im Vertrag | | |
| Verschwiegenheitsverpflichtung separat | | |
| Strafrechtliche Belehrung §§ 203/204 StGB | | |

## Typische Stolperfallen

- Anbieter argumentiert, die AVV decke alles ab — sie deckt das Berufsrecht nicht ab
- AVV verweist auf US-Datenschutzstandards — DSGVO-konform fraglich
- Pseudonymisierung wird angepriesen als "berufsrechtlich notwendig" — sie ist es nach DAV S. 11 nicht
- Trennung von Verschwiegenheit und Datenschutz fehlt
- Berufsrechtliche Verpflichtung in der AVV "versteckt" — sollte eigenständig erfolgen

## Output-Template — Parallelpruefungs-Vermerk

**Adressat:** Kanzlei intern — Tonfall: sachlich-juristisch

```
Interner Compliance-Vermerk — Schnittstelle AVV/Berufsrecht
Datum: [DATUM]
Anbieter: [NAME ANBIETER]
Produkt: [PRODUKTNAME]
Berufsgruppe: [BERUF]

A) AVV-Befund (Art. 28 DSGVO)
AVV vorhanden: ja / nein
Inhalt vollstaendig: ja / teilweise / nein
Luecken: [BESCHREIBUNG]

B) Berufsrechtlicher Befund (§§ 43e BRAO / 62a StBerG / ...)
Verschwiegenheitsklausel in Textform: ja / nein
Strafrechtliche Belehrung §§ 203/204 StGB: ja / nein
Subunternehmer-Weiterverpflichtung: ja / nein

C) Ergebnis
AVV-Status: GRUEN / GELB / ROT
Berufsrecht-Status: GRUEN / GELB / ROT
Empfehlung: [Vertragsnutzung freigegeben / Nachverhandlung / Ablehnung]

Unterschrift: [SACHBEARBEITER]
```
