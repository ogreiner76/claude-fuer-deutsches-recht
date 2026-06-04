---
name: tk-campusnetze-private-5g
description: "Campusnetze/private 5G: lokale Frequenzen, Betreiberrolle, Sicherheit, SLA, Industrieanwendung und Drittzugang."
---

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
