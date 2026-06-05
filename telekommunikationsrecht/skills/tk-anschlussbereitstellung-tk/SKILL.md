---
name: tk-anschlussbereitstellung-tk
description: "Nutze dies, wenn Tk Anschlussbereitstellung Verzug, Tk Behoerdenkommunikation Kooperationsstrategie im Plugin Telekommunikationsrecht konkret bearbeitet werden soll. Auslöser: Bitte Tk Anschlussbereitstellung Verzug, Tk Behoerdenkommunikation Kooperationsstrategie prüfen.; Erstelle eine Arbeitsfassung zu Tk Anschlussbereitstellung Verzug, Tk Behoerdenkommunikation Kooperationsstrategie.; Welche Normen und Nachweise brauche ich?."
---

# Tk Anschlussbereitstellung Verzug, Tk Behoerdenkommunikation Kooperationsstrategie

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-anschlussbereitstellung-verzug` | Bereitstellung von Festnetz-, Glasfaser-, Mobilfunk- oder Business-Anschluss: Terminversäumnis, Verzug, Entschädigung, Rücktritt, Ersatzlösung und Beweis. |
| `tk-behoerdenkommunikation-kooperationsstrategie` | Kommunikationsstrategie gegenüber der Bundesnetzagentur: kooperativ, präzise, aktenfest, geheimnisschonend und entscheidungsorientiert. |

## Arbeitsweg

Für **Tk Anschlussbereitstellung Verzug, Tk Behoerdenkommunikation Kooperationsstrategie** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-anschlussbereitstellung-verzug`

**Fokus:** Bereitstellung von Festnetz-, Glasfaser-, Mobilfunk- oder Business-Anschluss: Terminversäumnis, Verzug, Entschädigung, Rücktritt, Ersatzlösung und Beweis.

# Anschlussbereitstellung und Verzug

## Einsatz

Für Fälle, in denen ein Anschluss nicht kommt, Technikertermine platzen oder der Anbieter zwischen Tiefbau, Hausverwaltung und Netzbetreiber verweist.

## Norm- und Quellenanker

TKG Kundenschutz §§ 51 ff. live prüfen; BGB §§ 280, 286, 323; ZPO; BNetzA-Verbraucherinformationen.

## Arbeitsfragen

1. Was wurde vertraglich zugesagt und bis wann?
2. Welche Termine wurden versäumt und wer hat sie bestätigt?
3. Ist Verbraucher- oder Geschäftskundenrecht betroffen?
4. Welche Ersatzkosten sind entstanden?

## Output

Verzugsfahrplan, Entschädigungsforderung, Rücktrittsoption und Belegmatrix.

## Red Flags

- Termin nur telefonisch vereinbart
- Hausanschluss/Tarifaktivierung verwechselt
- Verbraucherentschädigung und SLA nicht getrennt
- Mitwirkungspflicht des Kunden unklar

## Anschluss-Skills

- tk-stoerung-minderung-ausfallentschaedigung
- tk-glasfaser-hausanschluss-wegerecht

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-behoerdenkommunikation-kooperationsstrategie`

**Fokus:** Kommunikationsstrategie gegenüber der Bundesnetzagentur: kooperativ, präzise, aktenfest, geheimnisschonend und entscheidungsorientiert.

# Behördenkommunikation mit BNetzA

## Einsatz

Für regulierte Unternehmen und Beschwerdegegner.

## Norm- und Quellenanker

VwVfG; TKG; Geschäftsgeheimnisgesetz; Compliance-Dokumentation.

## Arbeitsfragen

1. Was ist Ziel der Kommunikation?
2. Welche Fakten sind gesichert?
3. Welche Geheimnisse sind zu markieren?

## Output

Kommunikationsleitfaden und Antwortentwurf.

## Red Flags

- zu viel freiwillige Information
- unklare Zusagen
- keine Aktennotiz

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
