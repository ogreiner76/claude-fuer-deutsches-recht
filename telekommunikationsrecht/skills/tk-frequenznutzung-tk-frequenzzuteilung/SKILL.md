---
name: tk-frequenznutzung-tk-frequenzzuteilung
description: "Nutze dies bei Tk Frequenznutzung Stoerungen, Tk Frequenzzuteilung Auktionsdesign: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt."
---

# Tk Frequenznutzung Stoerungen, Tk Frequenzzuteilung Auktionsdesign

## Arbeitsbereich

Dieser Arbeitsbereich führt die Teilfragen zu **Tk Frequenznutzung Stoerungen, Tk Frequenzzuteilung Auktionsdesign** in einem handhabbaren Prüfpfad zusammen. Beginne mit dem Modul, das die Akte wirklich trägt; kombiniere weitere Module nur, wenn Frist, Zuständigkeit, Beweislast oder Output dadurch konkret besser werden.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-frequenznutzung-stoerungen` | Funkstörungen, EMV, Störungsmeldung, Messung, Unterlassung und BNetzA-Eingriff. |
| `tk-frequenzzuteilung-auktionsdesign` | Frequenzzuteilung, Vergabeverfahren, Auktionsdesign, Versorgungsauflagen, Nebenbestimmungen und Rechtsschutz. |

## Arbeitsweg

Für **Tk Frequenznutzung Stoerungen, Tk Frequenzzuteilung Auktionsdesign** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-frequenznutzung-stoerungen`

**Fokus:** Funkstörungen, EMV, Störungsmeldung, Messung, Unterlassung und BNetzA-Eingriff.

# Frequenzstörungen und Funkverträglichkeit

## Einsatz

Für Betreiber, Nachbarn und Hersteller bei gestörter oder störender Funknutzung.

## Norm- und Quellenanker

TKG Frequenznutzung; EMVG; BNetzA-Funkstörungsdienst.

## Arbeitsfragen

1. Welche Frequenz/Anlage stört?
2. Welche Messdaten und Genehmigungen liegen vor?
3. Welche Sofortmaßnahmen sind möglich?

## Output

Störungsdossier, BNetzA-Meldung und Abwehr-/Unterlassungsstrategie.

## Red Flags

- Messung unsauber
- zulässige Anlage als illegal bezeichnet
- Sofortabschaltung ohne Bescheid geprüft

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-frequenzzuteilung-auktionsdesign`

**Fokus:** Frequenzzuteilung, Vergabeverfahren, Auktionsdesign, Versorgungsauflagen, Nebenbestimmungen und Rechtsschutz.

# Frequenzzuteilung und Auktionen

## Einsatz

Für Mobilfunk, Campusnetze, Richtfunk, Satellit und Spezialnetze.

## Norm- und Quellenanker

TKG Frequenzordnung; BNetzA-Frequenzpläne/Vergaberegeln; VwGO.

## Arbeitsfragen

1. Welche Frequenz, Nutzung und Zuteilungsform?
2. Welche Auflagen und Zahlungs-/Ausbaupflichten?
3. Welche Rechtsschutzfrist?

## Output

Frequenzstrategie, Auflagenmatrix und Rechtsmittelcheck.

## Red Flags

- Nebenbestimmung unterschätzt
- Versorgungsauflage nicht kalkuliert
- Auktionsregel falsch gelesen

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
