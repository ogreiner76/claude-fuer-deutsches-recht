---
name: tk-marktanalyse-tk-meldepflicht
description: "Nutze dies, wenn Tk Marktanalyse Betraechtliche Marktmacht, Tk Meldepflicht It Sicherheitsvorfall im Plugin Telekommunikationsrecht konkret bearbeitet werden soll. Auslöser: Bitte Tk Marktanalyse Betraechtliche Marktmacht, Tk Meldepflicht It Sicherheitsvorfall prüfen.; Erstelle eine Arbeitsfassung zu Tk Marktanalyse Betraechtliche Marktmacht, Tk Meldepflicht It Sicherheitsvorfall.; Welche Normen und Nachweise brauche ich?."
---

# Tk Marktanalyse Betraechtliche Marktmacht, Tk Meldepflicht It Sicherheitsvorfall

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-marktanalyse-betraechtliche-marktmacht` | Marktanalyse, Marktdefinition, SMP/beträchtliche Marktmacht, Konsultation, EU-Abstimmung und Regulierungsverfügung. |
| `tk-meldepflicht-it-sicherheitsvorfall` | Sicherheitsvorfälle bei TK-Anbietern: BNetzA/BSI/DSGVO-Meldungen, Kundenkommunikation, Ursachenanalyse und Abhilfe. |

## Arbeitsweg

Für **Tk Marktanalyse Betraechtliche Marktmacht, Tk Meldepflicht It Sicherheitsvorfall** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-marktanalyse-betraechtliche-marktmacht`

**Fokus:** Marktanalyse, Marktdefinition, SMP/beträchtliche Marktmacht, Konsultation, EU-Abstimmung und Regulierungsverfügung.

# Marktanalyse und beträchtliche Marktmacht

## Einsatz

Für regulierte Märkte, in denen Zugang/Entgelt nur nach Marktmachtanalyse angeordnet werden kann.

## Norm- und Quellenanker

TKG Marktregulierung; EECC; BNetzA/BEREC/EU-Kommission live prüfen.

## Arbeitsfragen

1. Welcher relevante Markt ist betroffen?
2. Welche Marktanteile, Kontrolle über Infrastruktur und Wettbewerbsparameter liegen vor?
3. Welche Konsultation/Notifizierung läuft?

## Output

Marktanalyse-Memo und Stellungnahme.

## Red Flags

- Marktabgrenzung zu grob
- alte Regulierungsverfügung verwendet
- EU-Konsultation übersehen

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-meldepflicht-it-sicherheitsvorfall`

**Fokus:** Sicherheitsvorfälle bei TK-Anbietern: BNetzA/BSI/DSGVO-Meldungen, Kundenkommunikation, Ursachenanalyse und Abhilfe.

# IT-Sicherheitsvorfall und Meldepflicht

## Einsatz

Für Incident Response im TK-Betrieb.

## Norm- und Quellenanker

TKG Sicherheitsvorschriften; BSI-Gesetz/NIS2; DSGVO Art. 33, 34.

## Arbeitsfragen

1. Was ist passiert und welche Dienste betroffen?
2. Welche Meldewege und Fristen?
3. Welche Sofortmaßnahmen?

## Output

Incident-Meldeplan und Vorstandsvorlage.

## Red Flags

- Meldung nur intern
- DSGVO und TKG nicht koordiniert
- Kundenkommunikation zu spät

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
