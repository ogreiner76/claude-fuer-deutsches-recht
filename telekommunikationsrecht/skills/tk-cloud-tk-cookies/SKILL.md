---
name: tk-cloud-tk-cookies
description: "Nutze dies, wenn Tk Cloud Telefonie Voip Compliance, Tk Cookies Telemedien Ttdsg Tdddg im Plugin Telekommunikationsrecht konkret bearbeitet werden soll. Auslöser: Bitte Tk Cloud Telefonie Voip Compliance, Tk Cookies Telemedien Ttdsg Tdddg prüfen.; Erstelle eine Arbeitsfassung zu Tk Cloud Telefonie Voip Compliance, Tk Cookies Telemedien Ttdsg Tdddg.; Welche Normen und Nachweise brauche ich?."
---

# Tk Cloud Telefonie Voip Compliance, Tk Cookies Telemedien Ttdsg Tdddg

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-cloud-telefonie-voip-compliance` | Cloud-PBX/VoIP: Notruf, Standort, Datenschutz, Aufzeichnung, Ausfallsicherheit, Rufnummern und internationale Nutzer. |
| `tk-cookies-telemedien-ttdsg-tdddg` | Telemedien-/TK-Schnittstelle: Cookies, Einwilligung, Endgerätezugriff, Consent-Banner und Telekommunikationsdienste. |

## Arbeitsweg

Für **Tk Cloud Telefonie Voip Compliance, Tk Cookies Telemedien Ttdsg Tdddg** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-cloud-telefonie-voip-compliance`

**Fokus:** Cloud-PBX/VoIP: Notruf, Standort, Datenschutz, Aufzeichnung, Ausfallsicherheit, Rufnummern und internationale Nutzer.

# Cloud-Telefonie und VoIP

## Einsatz

Für Unternehmen und Provider mit Teams-/Zoom-/Cloud-Telefonie.

## Norm- und Quellenanker

TKG; TDDDG; DSGVO; Notrufvorschriften; BGB.

## Arbeitsfragen

1. Wer ist Anbieter/Reseller?
2. Wie funktionieren Notruf und Standort?
3. Welche Aufzeichnungen/Logs?

## Output

VoIP-Compliance-Check und Nutzerinformation.

## Red Flags

- Notruf bei Homeoffice falsch
- Aufzeichnung ohne Rechtsgrund
- Rufnummernmissbrauch

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-cookies-telemedien-ttdsg-tdddg`

**Fokus:** Telemedien-/TK-Schnittstelle: Cookies, Einwilligung, Endgerätezugriff, Consent-Banner und Telekommunikationsdienste.

# Cookies, Telemedien und TDDDG-Schnittstelle

## Einsatz

Für Anbieter, die TK-Dienste und Web-/App-Dienste kombinieren.

## Norm- und Quellenanker

TDDDG; DSGVO; ePrivacy; TKG.

## Arbeitsfragen

1. Ist Zugriff auf Endeinrichtung betroffen?
2. Welche Einwilligung ist erforderlich?
3. Wie passt das zu TK-Daten?

## Output

Consent- und Datenflusscheck.

## Red Flags

- Cookie und Verkehrsdaten vermischt
- berechtigtes Interesse überdehnt
- CMP falsch konfiguriert

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
