---
name: tk-callcenter-tk-campusnetze
description: "Nutze dies bei Tk Callcenter Einwilligung Werbeanrufe, Tk Campusnetze Private 5g: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt."
---

# Tk Callcenter Einwilligung Werbeanrufe, Tk Campusnetze Private 5G

## Arbeitsbereich

Dieser Arbeitsbereich führt die Teilfragen zu **Tk Callcenter Einwilligung Werbeanrufe, Tk Campusnetze Private 5G** in einem handhabbaren Prüfpfad zusammen. Beginne mit dem Modul, das die Akte wirklich trägt; kombiniere weitere Module nur, wenn Frist, Zuständigkeit, Beweislast oder Output dadurch konkret besser werden.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-callcenter-einwilligung-werbeanrufe` | Telefonwerbung, Einwilligung, Rufnummernanzeige, Dokumentation, Bußgeldrisiko und Callcenter-Verträge. |
| `tk-campusnetze-private-5g` | Campusnetze/private 5G: lokale Frequenzen, Betreiberrolle, Sicherheit, SLA, Industrieanwendung und Drittzugang. |

## Arbeitsweg

Für **Tk Callcenter Einwilligung Werbeanrufe, Tk Campusnetze Private 5G** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-callcenter-einwilligung-werbeanrufe`

**Fokus:** Telefonwerbung, Einwilligung, Rufnummernanzeige, Dokumentation, Bußgeldrisiko und Callcenter-Verträge.

# Werbeanrufe und Callcenter

## Einsatz

Für Anbieter, Callcenter und Beschwerdefälle.

## Norm- und Quellenanker

UWG; TKG Nummerierung/Missbrauch; DSGVO; BNetzA-Bußgeldpraxis live prüfen.

## Arbeitsfragen

1. Welche Einwilligung liegt vor?
2. Welche Rufnummer und Kampagne?
3. Wie wird Widerruf dokumentiert?

## Output

Callcenter-Compliance-Check und Beschwerdeabwehr.

## Red Flags

- Einwilligung nicht nachweisbar
- gekaufte Leads ohne Kette
- Rufnummernunterdrückung

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-campusnetze-private-5g`

**Fokus:** Campusnetze/private 5G: lokale Frequenzen, Betreiberrolle, Sicherheit, SLA, Industrieanwendung und Drittzugang.

# Campusnetze und private 5G-Netze

## Einsatz

Für Industrie, Häfen, Krankenhäuser und Forschungscampus.

## Norm- und Quellenanker

- TKG §§ 87 ff. und besonders TKG § 91 zur Frequenzzuteilung; Nutzungsbestimmungen und Nebenbestimmungen aus dem konkreten BNetzA-Bescheid sind entscheidend.
- BNetzA-Praxis zu lokalen/regionalen Netzen live prüfen: insbesondere 3,7-3,8 GHz für lokale Campusnetze und 26-GHz-Anwendungen für sehr hohe Kapazität/kurze Reichweite.
- Betreiberrolle abgrenzen: rein privates Werksnetz, öffentlich zugänglicher Telekommunikationsdienst, Managed-Service-Modell, Roaming/Drittzugang, MVNO-/Provider-Konstellation.
- NIS2, BSIG, KRITIS-DachG/BSI-KritisV und branchenspezifische Sicherheitsstandards nur ziehen, wenn Sektor, Schwelle, Kritikalität oder Lieferkettenrolle betroffen sind.
- Datenschutz: DSGVO/BDSG bei Standortdaten, Nutzungsdaten, Mitarbeitertracking, Video/IoT-Sensorik und Zugriff auf Geräte-Logs.

## Arbeitsfragen

1. Welche Fläche, Gebäude, Außenbereiche, Funkzellen und Frequenznutzung sollen abgedeckt werden?
2. Wer hält die Frequenzzuteilung, wer baut, wer betreibt, wer wartet, wer verarbeitet Betriebs- und Nutzungsdaten?
3. Gibt es Drittnutzer: Mieter, Subunternehmer, Besucher, Logistikpartner, Forschungspartner oder öffentliche Kunden?
4. Welche SLA sind geschäftskritisch: Latenz, Verfügbarkeit, Priorisierung, Notfallbetrieb, Redundanz, Incident Response?
5. Welche Nebenbestimmungen enthält der BNetzA-Bescheid: Standort, Sendeleistung, Laufzeit, Gebühren, Störungskoordination, Dokumentationspflicht?
6. Welche Sicherheitsarchitektur ist belegt: SIM/eSIM, Zertifikate, Netzsegmentierung, Patchmanagement, Logging, Adminrechte, Lieferanten-Remotezugriff?

## Output

- Campusnetz-Antragscheck mit Frequenz, Fläche, technischer Begründung, Betreiberrolle und Nebenbestimmungsrisiken.
- Vertragsmatrix für Betreiber, Systemintegrator, Host, Nutzer und Sicherheitsdienstleister.
- Compliance-Memo zu TKG/BNetzA, Datenschutz, IT-Sicherheit, KRITIS/NIS2 und zivilrechtlichen Haftungsfragen.

## Red Flags

- Frequenzzuteilung nicht beantragt
- Betreiberpflichten unklar
- Sicherheitskonzept fehlt
- "Privat" genannt, aber faktisch Drittzugang oder kommerzielle Telekommunikationsdienste angeboten
- BNetzA-Nebenbestimmungen nicht in SLA, Betriebshandbuch und Lieferantenverträge gespiegelt
- Standort-/Mitarbeiterdaten werden für HR- oder Leistungszwecke mitgenutzt, ohne Rechtsgrundlage und Betriebsratslogik

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
