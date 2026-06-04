---
name: dora-art16-finanzunternehmen-simplified-framework
description: "DORA-Artikel-16-Spezialskill für Cyber- und Compliance-Teams: prüft, ob ein Finanzunternehmen den vereinfachten IKT-Risikomanagementrahmen nutzen kann, und baut Governance-, Asset-, IAM-, BCP-, Drittparteien- und Nachweisplan."
---

# DORA Artikel 16 für Finanzunternehmen

## Zweck

Dieser Skill sitzt zwischen NIS2-/Cybersecurity-Compliance und Finanzaufsicht. Er klärt, ob DORA als Spezialregime vorgeht, ob Artikel 16 DORA den vereinfachten Rahmen eröffnet, und welche technischen und organisatorischen Mindestnachweise trotzdem erforderlich sind.

## Scope-Check

| Frage | Prüfung |
| --- | --- |
| Finanzunternehmen? | Bank, Zahlungsinstitut, E-Geld, Wertpapierinstitut, Versicherer, KVG, CASP oder anderer DORA-Scope |
| Artikel 16? | Institutstyp, Größe und Dienstleistungsumfang gegen aktuelle DORA-/BaFin-Quellen prüfen |
| NIS2 daneben? | Sektor, Rolle, nationale Umsetzung, Meldewege und Vorstandspflichten abgrenzen |
| Drittanbieter? | ICT third-party risk nach Art. 28 bis 30 DORA prüfen, auch bei vereinfachtem Rahmen |

## Mindestarbeitsprogramm

1. Asset-Inventar mit Kritikalität und Datenarten.
2. IKT-Risikoanalyse mit Maßnahmen und Rest-Risiken.
3. IAM nach Need-to-use, Adminrechte, Rezertifizierung.
4. Schwachstellen-, Patch- und Change-Management.
5. Backup, Restore, Business Continuity, Krisenkommunikation.
6. Incident-Klassifizierung und Melderoute.
7. Drittparteienregister, Due Diligence, Vertragsklauseln, Subdienstleister, Exit.
8. Nachweisordner für Geschäftsleitung, Revision, BaFin/Bundesbank.

## Output

Erzeuge eine `DORA-Art.-16-Note`:

- Scope-Entscheidung.
- Ampel für Governance, Assets, IAM, Betrieb, BCP, Drittparteien, Nachweise.
- 30-/60-/90-Tage-Maßnahmenplan.
- Vertragslücken für kritische IKT-Dienstleister.
- Liste der Live-Checks auf BaFin, EUR-Lex und nationalen Umsetzungsseiten.

## Stolperstellen

- Artikel 16 wird fälschlich als Minimalpflicht verstanden.
- DORA und NIS2 werden doppelt oder widersprüchlich gemeldet.
- Drittparteien werden nur in Procurement erfasst, aber nicht im IKT-Risikomanagement.
- Exit-Pläne sind Papier, aber nicht testbar.
- Geschäftsleitung sieht Reports, entscheidet aber keine Prioritäten.
