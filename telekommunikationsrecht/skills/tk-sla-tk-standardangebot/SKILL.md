---
name: tk-sla-tk-standardangebot
description: "Tk Sla Business Kunden Ausfall, Tk Standardangebot Reference Offer: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output."
---

# Tk Sla Business Kunden Ausfall, Tk Standardangebot Reference Offer

## Arbeitsbereich

Dieser Skill bündelt **Tk Sla Business Kunden Ausfall, Tk Standardangebot Reference Offer** zu einem konkreten Arbeitsgang. Starte mit dem Modul, das die Tatsachen der Akte trägt; weitere Module nur hinzunehmen, wenn sie dieselbe Frist, Zuständigkeit, Beweislast oder denselben Output betreffen.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-sla-business-kunden-ausfall` | Geschäftskunden-SLA: Verfügbarkeit, Reaktions-/Entstörzeiten, Credits, Schadensersatz, Haftungsbegrenzung und Force Majeure. |
| `tk-standardangebot-reference-offer` | Standardangebotspflichten, Prüfung von Klauseln, Änderungsanordnung, Zugangsnachfrage und Nichtdiskriminierung. |

## Arbeitsweg

Für **Tk Sla Business Kunden Ausfall, Tk Standardangebot Reference Offer** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-sla-business-kunden-ausfall`

**Fokus:** Geschäftskunden-SLA: Verfügbarkeit, Reaktions-/Entstörzeiten, Credits, Schadensersatz, Haftungsbegrenzung und Force Majeure.

# Business-SLA und Ausfall

## Einsatz

Für Unternehmen, deren Geschäft an Konnektivität hängt.

## Norm- und Quellenanker

BGB; TKG; AGB-Recht §§ 305 ff. BGB; ZPO.

## Arbeitsfragen

1. Welche SLA-Kennzahl gilt?
2. Wie wird Ausfall gemessen?
3. Welche Haftung ist begrenzt?

## Output

SLA-Claim und Vertrags-Redline.

## Red Flags

- Credit ersetzt Schaden angeblich vollständig
- Messpunkte fehlen
- AGB-Haftung zu weit beschränkt

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-standardangebot-reference-offer`

**Fokus:** Standardangebotspflichten, Prüfung von Klauseln, Änderungsanordnung, Zugangsnachfrage und Nichtdiskriminierung.

# Standardangebot und Reference Offer

## Einsatz

Für Vorleistungsangebote, die reguliert, genehmigt oder angegriffen werden.

## Norm- und Quellenanker

TKG; BNetzA-Standardangebotsverfahren; AGB-Recht.

## Arbeitsfragen

1. Welche Klausel behindert Zugang?
2. Welche BNetzA-Festlegung gilt?
3. Ist die Klausel diskriminierend oder unpraktikabel?

## Output

Klausel-Redline und BNetzA-Stellungnahme.

## Red Flags

- SLA zu niedrig
- Kündigungsrechte asymmetrisch
- Bestellprozesse praktisch blockierend

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
