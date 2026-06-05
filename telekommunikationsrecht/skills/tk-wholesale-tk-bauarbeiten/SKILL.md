---
name: tk-wholesale-tk-bauarbeiten
description: "Tk Wholesale Reseller Mvno Vertrag, Tk Bauarbeiten Kabelschaden: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output."
---

# Tk Wholesale Reseller Mvno Vertrag, Tk Bauarbeiten Kabelschaden

## Arbeitsbereich

Dieser Skill bündelt **Tk Wholesale Reseller Mvno Vertrag, Tk Bauarbeiten Kabelschaden** zu einem konkreten Arbeitsgang. Starte mit dem Modul, das die Tatsachen der Akte trägt; weitere Module nur hinzunehmen, wenn sie dieselbe Frist, Zuständigkeit, Beweislast oder denselben Output betreffen.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-wholesale-reseller-mvno-vertrag` | Wholesale-, Reseller- und MVNO-Verträge: Zugang, SLA, Entgelt, Nummerierung, Kundenschutz, Datenschutz und Exit. |
| `tk-bauarbeiten-kabelschaden` | Kabelschäden: Leitungsauskunft, Verkehrssicherung, Tiefbau, Schadensersatz, Betriebsunterbrechung und Beweissicherung. |

## Arbeitsweg

Für **Tk Wholesale Reseller Mvno Vertrag, Tk Bauarbeiten Kabelschaden** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-wholesale-reseller-mvno-vertrag`

**Fokus:** Wholesale-, Reseller- und MVNO-Verträge: Zugang, SLA, Entgelt, Nummerierung, Kundenschutz, Datenschutz und Exit.

# Wholesale, Reseller und MVNO-Verträge

## Einsatz

Für Anbieterketten im Mobilfunk/Festnetz.

## Norm- und Quellenanker

TKG; BGB/HGB; GWB; DSGVO/TKG-Datenschutz.

## Arbeitsfragen

1. Wer schuldet Endkundenleistung?
2. Welche Vorleistungen/SLA?
3. Welche Daten- und Nummernverantwortung?

## Output

Vertrags-Redline und Risikoampel.

## Red Flags

- Endkundenpflichten fehlen
- Nummernportierung ungeklärt
- SLA ohne Sanktion

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-bauarbeiten-kabelschaden`

**Fokus:** Kabelschäden: Leitungsauskunft, Verkehrssicherung, Tiefbau, Schadensersatz, Betriebsunterbrechung und Beweissicherung.

# Kabelschaden durch Bauarbeiten

## Einsatz

Für Netzbetreiber, Bauunternehmen und Versicherer.

## Norm- und Quellenanker

BGB §§ 823, 280; TKG Infrastruktur; Straßen-/Baurecht; ZPO.

## Arbeitsfragen

1. Wurde Leitungsauskunft eingeholt?
2. Welche Pläne und Markierungen?
3. Welcher Schaden und Folgeschaden?

## Output

Kabelschaden-Dossier und Anspruchsschreiben.

## Red Flags

- Leitungspläne veraltet
- Folgeschäden unbelegt
- Subunternehmerkette unklar

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
