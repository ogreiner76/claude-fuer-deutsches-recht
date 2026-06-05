---
name: tk-nummerierung-tk-open
description: "Nutze dies bei Tk Nummerierung Rufnummernzuteilung, Tk Open Ran Lieferketten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt."
---

# Tk Nummerierung Rufnummernzuteilung, Tk Open Ran Lieferketten

## Arbeitsbereich

Dieser Arbeitsbereich führt die Teilfragen zu **Tk Nummerierung Rufnummernzuteilung, Tk Open Ran Lieferketten** in einem handhabbaren Prüfpfad zusammen. Beginne mit dem Modul, das die Akte wirklich trägt; kombiniere weitere Module nur, wenn Frist, Zuständigkeit, Beweislast oder Output dadurch konkret besser werden.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-nummerierung-rufnummernzuteilung` | Rufnummernzuteilung, Nutzung, Entzug, Mehrwertdienste, geografische Nummern, 0800/0900, M2M und Nummernportierung. |
| `tk-open-ran-lieferketten` | Open-RAN-/Netzkomponenten: Lieferkette, Sicherheit, Interoperabilität, Ausfall, Exportkontrolle und kritische Komponenten. |

## Arbeitsweg

Für **Tk Nummerierung Rufnummernzuteilung, Tk Open Ran Lieferketten** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-nummerierung-rufnummernzuteilung`

**Fokus:** Rufnummernzuteilung, Nutzung, Entzug, Mehrwertdienste, geografische Nummern, 0800/0900, M2M und Nummernportierung.

# Nummerierung und Rufnummernzuteilung

## Einsatz

Für Anbieter und Dienste, deren Geschäftsmodell an Rufnummern hängt.

## Norm- und Quellenanker

TKG Nummerierungsrecht; BNetzA-Nummernpläne/Verfügungen live prüfen.

## Arbeitsfragen

1. Welche Nummernart und Nutzungsbedingung?
2. Ist Nutzung zweckgerecht?
3. Droht Entzug oder Abschaltung?

## Output

Nummernrechtsmemo und BNetzA-Antrag/Antwort.

## Red Flags

- Nummernart falsch
- Werbung/Missbrauch droht
- Zuteilungsinhaber und Nutzer verwechselt

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-open-ran-lieferketten`

**Fokus:** Open-RAN-/Netzkomponenten: Lieferkette, Sicherheit, Interoperabilität, Ausfall, Exportkontrolle und kritische Komponenten.

# Open RAN und Lieferketten

## Einsatz

Für Netzmodernisierung und Vendor-Management.

## Norm- und Quellenanker

TKG; NIS2/BSI; IT-Sicherheitsgesetz; Außenwirtschaftsrecht; Vertragsrecht.

## Arbeitsfragen

1. Welche Komponenten und Lieferanten?
2. Welche Sicherheits-/Zertifizierungsanforderungen?
3. Welche Exit- und Interoperabilitätsrechte?

## Output

Lieferketten-Risikomemo und Vertragsklauseln.

## Red Flags

- Vendor Lock-in trotz Open RAN
- Sicherheitsnachweise fehlen
- Exportkontrollrisiko

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
