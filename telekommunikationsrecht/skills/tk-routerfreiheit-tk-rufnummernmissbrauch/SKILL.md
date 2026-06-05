---
name: tk-routerfreiheit-tk-rufnummernmissbrauch
description: "Nutze dies, wenn Tk Routerfreiheit Endgeraete, Tk Rufnummernmissbrauch Abschaltung im Plugin Telekommunikationsrecht konkret bearbeitet werden soll. Auslöser: Bitte Tk Routerfreiheit Endgeraete, Tk Rufnummernmissbrauch Abschaltung prüfen.; Erstelle eine Arbeitsfassung zu Tk Routerfreiheit Endgeraete, Tk Rufnummernmissbrauch Abschaltung.; Welche Normen und Nachweise brauche ich?."
---

# Tk Routerfreiheit Endgeraete, Tk Rufnummernmissbrauch Abschaltung

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-routerfreiheit-endgeraete` | Routerfreiheit, Netzabschlusspunkt, Endgerätefreiheit, Providerrouter, Konfigurationsdaten, Glasfaser-ONT und Gewährleistung/Sicherheit. |
| `tk-rufnummernmissbrauch-abschaltung` | Rufnummernmissbrauch, Ping-Anrufe, Spam, Mehrwertdienste, Abschaltung, Rechnungslegungs-/Inkassoverbot und Beschwerde. |

## Arbeitsweg

Für **Tk Routerfreiheit Endgeraete, Tk Rufnummernmissbrauch Abschaltung** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-routerfreiheit-endgeraete`

**Fokus:** Routerfreiheit, Netzabschlusspunkt, Endgerätefreiheit, Providerrouter, Konfigurationsdaten, Glasfaser-ONT und Gewährleistung/Sicherheit.

# Routerfreiheit und Endgeräte

## Einsatz

Für Streit, ob der Kunde eigenen Router/ONT nutzen darf oder Provider technische Vorgaben macht.

## Norm- und Quellenanker

TKG Endgerätefreiheit/Netzabschlusspunkt live prüfen; BGB; Produktsicherheits-/Cyberrecht; BNetzA-Festlegungen.

## Arbeitsfragen

1. Wo liegt der passive Netzabschlusspunkt?
2. Welche Zugangsdaten/Konfigurationsdaten muss Anbieter bereitstellen?
3. Welche Sicherheits- oder Supportargumente sind tragfähig?
4. Welche Folgen hat eigener Router für Störung/Gewährleistung?

## Output

Routerfreiheits-Memo, Providerbrief, technische Fragenliste und Verbraucher-/Businessvariante.

## Red Flags

- ONT als Providerhoheit behauptet
- Konfigurationsdaten fehlen
- Störung vorschnell dem Kundenrouter zugeschrieben
- Sicherheitsargument ohne Normbasis

## Anschluss-Skills

- tk-stoerung-minderung-ausfallentschaedigung
- tk-glasfaser-hausanschluss-wegerecht

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-rufnummernmissbrauch-abschaltung`

**Fokus:** Rufnummernmissbrauch, Ping-Anrufe, Spam, Mehrwertdienste, Abschaltung, Rechnungslegungs-/Inkassoverbot und Beschwerde.

# Rufnummernmissbrauch, Abschaltung und Inkassoverbot

## Einsatz

Für Verbraucherbeschwerden und Anbieterabwehr gegen Missbrauchsmaßnahmen.

## Norm- und Quellenanker

TKG Missbrauchsaufsicht/Nummerierung; UWG; BNetzA-Verbraucherschutz.

## Arbeitsfragen

1. Welche Nummer, Kampagne und Rechnung ist betroffen?
2. Welche Missbrauchstatsachen sind belegt?
3. Welche BNetzA-Maßnahme oder Beschwerde läuft?

## Output

Missbrauchsdossier, Beschwerde/Abwehr und Rechnungsprüfung.

## Red Flags

- Kundenbeschwerden nicht gesichert
- Inkasso trotz Verbot
- Callcenter-Kette unklar

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
