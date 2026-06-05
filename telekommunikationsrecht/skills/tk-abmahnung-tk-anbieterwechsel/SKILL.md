---
name: tk-abmahnung-tk-anbieterwechsel
description: "Nutze dies, wenn Tk Abmahnung Uwg Tkg, Tk Anbieterwechsel Rufnummernmitnahme im Plugin Telekommunikationsrecht konkret bearbeitet werden soll. Auslöser: Bitte Tk Abmahnung Uwg Tkg, Tk Anbieterwechsel Rufnummernmitnahme prüfen.; Erstelle eine Arbeitsfassung zu Tk Abmahnung Uwg Tkg, Tk Anbieterwechsel Rufnummernmitnahme.; Welche Normen und Nachweise brauche ich?."
---

# Tk Abmahnung Uwg Tkg, Tk Anbieterwechsel Rufnummernmitnahme

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-abmahnung-uwg-tkg` | Abmahnungen bei TK-Marketing, Preiswerbung, Rufnummernmissbrauch, Vergleichsportalen und Informationspflichten. |
| `tk-anbieterwechsel-rufnummernmitnahme` | Anbieterwechsel, Versorgungslücke, Rufnummernportierung, Entschädigung, Weiterversorgungspflicht und BNetzA-Beschwerde. |

## Arbeitsweg

Für **Tk Abmahnung Uwg Tkg, Tk Anbieterwechsel Rufnummernmitnahme** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-abmahnung-uwg-tkg`

**Fokus:** Abmahnungen bei TK-Marketing, Preiswerbung, Rufnummernmissbrauch, Vergleichsportalen und Informationspflichten.

# Abmahnung nach UWG/TKG

## Einsatz

Für Wettbewerber, Verbände und Anbieter.

## Norm- und Quellenanker

UWG; TKG; PAngV; TDDDG/DSGVO; BGB.

## Arbeitsfragen

1. Welche Marktverhaltensregel?
2. Welche Werbung/Information ist falsch?
3. Welche Unterlassung und Vertragsstrafe?

## Output

Abmahnungs-/Verteidigungsschreiben und Beweisplan.

## Red Flags

- TKG-Norm keine Marktverhaltensregel geprüft
- Screenshot fehlt
- Unterlassung zu weit

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-anbieterwechsel-rufnummernmitnahme`

**Fokus:** Anbieterwechsel, Versorgungslücke, Rufnummernportierung, Entschädigung, Weiterversorgungspflicht und BNetzA-Beschwerde.

# Anbieterwechsel und Rufnummernmitnahme

## Einsatz

Für Verbraucher und Unternehmen, die beim Wechsel ohne Telefon/Internet oder ohne Rufnummer dastehen.

## Norm- und Quellenanker

TKG §§ 59 und Kundenschutzvorschriften live prüfen; BNetzA-Anbieterwechselinformationen; BGB.

## Arbeitsfragen

1. Wann wurde Wechsel/Portierung beauftragt?
2. Wer ist abgebender und aufnehmender Anbieter?
3. Welche Verzögerung ist wem zurechenbar?
4. Welche Entschädigung oder Beschwerde ist möglich?

## Output

Portierungszeitstrahl, Entschädigungsforderung, BNetzA-Beschwerde und Eskalationsmail.

## Red Flags

- Altanbieter schaltet ab
- Portierungsdatum unklar
- Rufnummer gehört Firma statt Mitarbeiter
- Entschädigung falsch berechnet

## Anschluss-Skills

- tk-schlichtung-verbraucher
- tk-output-beschwerde-antrag-klage

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
