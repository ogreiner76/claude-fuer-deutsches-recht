---
name: tk-datacenter-tk-eilrechtsschutz
description: "Nutze dies, wenn Tk Datacenter Connectivity, Tk Eilrechtsschutz Bnetza Beschluss im Plugin Telekommunikationsrecht konkret bearbeitet werden soll. Auslöser: Bitte Tk Datacenter Connectivity, Tk Eilrechtsschutz Bnetza Beschluss prüfen.; Erstelle eine Arbeitsfassung zu Tk Datacenter Connectivity, Tk Eilrechtsschutz Bnetza Beschluss.; Welche Normen und Nachweise brauche ich?."
---

# Tk Datacenter Connectivity, Tk Eilrechtsschutz Bnetza Beschluss

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-datacenter-connectivity` | Rechenzentrumskonnektivität: Carrier Meet-Me, Cross-Connects, SLA, Wegerecht im Gebäude, Datenschutz/Sicherheit und Ausfallhaftung. |
| `tk-eilrechtsschutz-bnetza-beschluss` | Eilrechtsschutz bei Frequenz-, Entgelt-, Zugang-, Nummerierungs- oder Missbrauchsmaßnahmen. |

## Arbeitsweg

Für **Tk Datacenter Connectivity, Tk Eilrechtsschutz Bnetza Beschluss** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-datacenter-connectivity`

**Fokus:** Rechenzentrumskonnektivität: Carrier Meet-Me, Cross-Connects, SLA, Wegerecht im Gebäude, Datenschutz/Sicherheit und Ausfallhaftung.

# Datacenter Connectivity und Carrier Meet-Me

## Einsatz

Für Rechenzentren, Carrier und Unternehmenskunden.

## Norm- und Quellenanker

BGB; TKG; NIS2/BSI; AGB-Recht.

## Arbeitsfragen

1. Welche Connects und Carrier?
2. Welche Verfügbarkeit und Wartungsfenster?
3. Welche Sicherheitszonen?

## Output

Connectivity-Vertragscheck und Ausfallplan.

## Red Flags

- Cross-Connect ohne klare Verantwortung
- Wartungsfenster zu breit
- Security-Zutritt ungeklärt

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-eilrechtsschutz-bnetza-beschluss`

**Fokus:** Eilrechtsschutz bei Frequenz-, Entgelt-, Zugang-, Nummerierungs- oder Missbrauchsmaßnahmen.

# Eilrechtsschutz gegen BNetzA-Beschluss

## Einsatz

Wenn ein BNetzA-Beschluss sofort wirtschaftlich wirkt.

## Norm- und Quellenanker

VwGO §§ 80, 80a, 123; TKG; VwVfG.

## Arbeitsfragen

1. Hat der Rechtsbehelf aufschiebende Wirkung?
2. Welche irreversiblen Nachteile drohen?
3. Wie wird Interessenabwägung belegt?

## Output

Eilantragsskizze und Anlagenliste.

## Red Flags

- Eilbedürftigkeit nicht belegt
- Hauptsachechancen fehlen
- Dritte nicht beigeladen

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
