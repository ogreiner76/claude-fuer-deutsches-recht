---
name: tk-zugangsregulierung-tk-zusammenschaltung
description: "Nutze dies, wenn Tk Zugangsregulierung Vorleistung, Tk Zusammenschaltung Interconnection im Plugin Telekommunikationsrecht konkret bearbeitet werden soll. Auslöser: Bitte Tk Zugangsregulierung Vorleistung, Tk Zusammenschaltung Interconnection prüfen.; Erstelle eine Arbeitsfassung zu Tk Zugangsregulierung Vorleistung, Tk Zusammenschaltung Interconnection.; Welche Normen und Nachweise brauche ich?."
---

# Tk Zugangsregulierung Vorleistung, Tk Zusammenschaltung Interconnection

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-zugangsregulierung-vorleistung` | Zugang zu Netzen, Vorleistungsprodukten, TAL/Bitstrom, Glasfaser, Nichtdiskriminierung und technische Schnittstellen. |
| `tk-zusammenschaltung-interconnection` | Zusammenschaltung, Terminierung, IP-Interconnection, Qualität, Entgelte und Streitbeilegung. |

## Arbeitsweg

Für **Tk Zugangsregulierung Vorleistung, Tk Zusammenschaltung Interconnection** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-zugangsregulierung-vorleistung`

**Fokus:** Zugang zu Netzen, Vorleistungsprodukten, TAL/Bitstrom, Glasfaser, Nichtdiskriminierung und technische Schnittstellen.

# Zugangsregulierung und Vorleistungen

## Einsatz

Für Wettbewerber, die Zugang brauchen, oder Netzbetreiber, die Zugangspflichten erfüllen müssen.

## Norm- und Quellenanker

TKG Zugangsregulierung; BNetzA-Standardangebote; GWB/AEUV.

## Arbeitsfragen

1. Welcher Zugang wird verlangt?
2. Ist Pflicht, freiwilliger Open Access oder Vertrag betroffen?
3. Welche technischen/kommerziellen Bedingungen sind streitig?

## Output

Zugangsantrag/Stellungnahme und Konditionenmatrix.

## Red Flags

- Nichtdiskriminierung nicht belegt
- technische Schnittstelle unklar
- Vertraulichkeit überdehnt

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-zusammenschaltung-interconnection`

**Fokus:** Zusammenschaltung, Terminierung, IP-Interconnection, Qualität, Entgelte und Streitbeilegung.

# Zusammenschaltung und Interconnection

## Einsatz

Für Netzbetreiber, MVNOs und Diensteanbieter bei Interconnection-Konflikten.

## Norm- und Quellenanker

TKG Zusammenschaltung; EECC; BNetzA-Streitbeilegung.

## Arbeitsfragen

1. Welche Netze/Dienste werden verbunden?
2. Welche technischen Spezifikationen und Entgelte gelten?
3. Welche Störung/Verweigerung liegt vor?

## Output

Interconnection-Matrix, Streitbeilegungsantrag und SLA-Check.

## Red Flags

- technische und rechtliche Ebene vermischt
- Terminierungsentgelt veraltet
- QoS nicht gemessen

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
