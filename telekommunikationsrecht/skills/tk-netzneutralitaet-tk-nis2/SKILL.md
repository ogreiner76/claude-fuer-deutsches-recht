---
name: tk-netzneutralitaet-tk-nis2
description: "Nutze dies, wenn Tk Netzneutralitaet Zero Rating Throttling, Tk Nis2 Kritis Bsi Schnittstelle im Plugin Telekommunikationsrecht konkret bearbeitet werden soll. Auslöser: Bitte Tk Netzneutralitaet Zero Rating Throttling, Tk Nis2 Kritis Bsi Schnittstelle prüfen.; Erstelle eine Arbeitsfassung zu Tk Netzneutralitaet Zero Rating Throttling, Tk Nis2 Kritis Bsi Schnittstelle.; Welche Normen und Nachweise brauche ich?."
---

# Tk Netzneutralitaet Zero Rating Throttling, Tk Nis2 Kritis Bsi Schnittstelle

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-netzneutralitaet-zero-rating-throttling` | Netzneutralität: Zero-Rating, Priorisierung, Drosselung, Spezialdienste, Traffic Management und Beschwerde-/Abmahnrisiken. |
| `tk-nis2-kritis-bsi-schnittstelle` | NIS2/KRITIS/BSI-Anforderungen für TK-Unternehmen, Rechenzentren, Managed Services und kritische Kommunikation. |

## Arbeitsweg

Für **Tk Netzneutralitaet Zero Rating Throttling, Tk Nis2 Kritis Bsi Schnittstelle** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-netzneutralitaet-zero-rating-throttling`

**Fokus:** Netzneutralität: Zero-Rating, Priorisierung, Drosselung, Spezialdienste, Traffic Management und Beschwerde-/Abmahnrisiken.

# Netzneutralität, Zero-Rating und Drosselung

## Einsatz

Für Anbieterprodukte und Beschwerden, wenn Datenverkehr unterschiedlich behandelt wird.

## Norm- und Quellenanker

EU-Verordnung 2015/2120; TKG; BEREC-Leitlinien live prüfen; UWG/GWB-Schnittstelle.

## Arbeitsfragen

1. Welche Verkehrsbehandlung unterscheidet wen oder was?
2. Ist sie technisch notwendig, diskriminierend oder tariflich gesteuert?
3. Gibt es Spezialdienst oder Netzmanagement?
4. Welche BNetzA-/BEREC-Linie ist live zu prüfen?

## Output

Netzneutralitätsprüfung, Produkt-Redline, BNetzA-Risiko und Kundenkommunikation.

## Red Flags

- Marketingtarif vor Rechtsprüfung
- Drosselung nach App-Kategorie
- Spezialdienst ohne Kapazitätsnachweis
- BEREC-Leitlinien nicht geprüft

## Anschluss-Skills

- tk-eu-eecc-router
- tk-missbrauchsaufsicht-sonderkartellrecht

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-nis2-kritis-bsi-schnittstelle`

**Fokus:** NIS2/KRITIS/BSI-Anforderungen für TK-Unternehmen, Rechenzentren, Managed Services und kritische Kommunikation.

# NIS2, KRITIS und BSI-Schnittstelle

## Einsatz

Für Unternehmen, die TK- oder digitale Infrastruktur betreiben.

## Norm- und Quellenanker

NIS2; BSI-Gesetz; TKG; DORA bei Finanzkunden.

## Arbeitsfragen

1. Ist die Einheit erfasst?
2. Welche technischen und organisatorischen Maßnahmen?
3. Welche Leitungsorganpflichten?

## Output

NIS2-Gap-Analyse und Maßnahmenplan.

## Red Flags

- Schwellenwerte ungeprüft
- Geschäftsführung nicht eingebunden
- Lieferkette vergessen

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
