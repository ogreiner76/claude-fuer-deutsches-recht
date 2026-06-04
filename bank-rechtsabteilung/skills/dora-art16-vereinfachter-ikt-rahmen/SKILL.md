---
name: dora-art16-vereinfachter-ikt-rahmen
description: "DORA Artikel 16 für kleinere oder privilegierte Finanzunternehmen: vereinfachten IKT-Risikomanagementrahmen, Governance, Asset-Inventar, Need-to-use, Business Continuity, Drittparteienrisiko, Vertragslücken und Nachweisordner prüfbar machen."
---

# DORA Artikel 16: Vereinfachter IKT-Rahmen

## Zweck

Dieser Skill prüft, ob ein Finanzunternehmen den vereinfachten IKT-Risikomanagementrahmen nach Artikel 16 DORA nutzen kann und welche Pflichten trotzdem bleiben. Er verhindert zwei Fehler: erstens kleine Institute so zu behandeln, als müssten sie den vollen Konzernapparat bauen; zweitens Artikel 16 als Freibrief zu missverstehen.

## Erste Weiche

| Frage | Wenn ja | Wenn nein |
| --- | --- | --- |
| Fällt das Unternehmen überhaupt unter DORA? | Finanzsektor-Scope und Institutstyp bestimmen | NIS2/BSIG, DSGVO Art. 32, Vertrags- und Organpflichten prüfen |
| Ist Artikel 16 einschlägig? | vereinfachten Rahmen prüfen | regulären Rahmen nach Art. 5 bis 15 DORA prüfen |
| Gibt es kritische oder wichtige Funktionen? | Drittparteien, BCP, Exit und Tests vertiefen | Grundrahmen trotzdem dokumentieren |
| Ist ein IKT-Drittanbieter beteiligt? | Art. 28 bis 30 DORA plus Vertrag prüfen | interne IKT-Governance reicht nicht automatisch |

## Prüfprogramm

| Baustein | Was der Skill abfragt | Output |
| --- | --- | --- |
| Governance | Leitungsorgan, Verantwortlichkeiten, Kontrollfunktionen, Ressourcen | Governance-Map und Beschlussbedarf |
| IKT-Risiko | Risikoidentifikation, Bewertung, Maßnahmen, Rest-Risiko | Risiko- und Maßnahmenregister |
| Assets | Systeme, Daten, Schnittstellen, Kritikalität, Eigentümer | Asset-Inventar-Lückenliste |
| Zugriff | Need-to-use, Adminrechte, Rezertifizierung, Segregation of Duties | IAM-Kontrollplan |
| Betrieb | Change, Patch, Schwachstellen, Logging, Backup | Betriebs-Checkliste |
| Kontinuität | Szenarien, Wiederanlauf, Tests, Krisenkommunikation | BCP/DR-Testplan |
| Drittparteien | Due Diligence, Vertrag, Subdienstleister, Monitoring, Exit | DORA-Klausel- und Registercheck |
| Nachweis | Protokolle, Reports, Schulungen, Vorfälle, Findings | Aufsichtsordner |

## Vertragscheck IKT-Drittparteien

Prüfe mindestens:

- Leistungsbeschreibung, Standorte, Datenarten, Kritikalität.
- Sicherheitsanforderungen, Schwachstellenmanagement, Incident-Meldung, Unterstützungsfristen.
- Audit-, Informations- und Zugangsrechte für Institut, Prüfer und Aufsicht.
- Unterauslagerung/Subcontracting, Informationspflichten und Widerspruchs-/Kündigungsmechanik.
- Exit, Datenrückgabe, Datenlöschung, Portabilität, Übergangsleistungen.
- Register-of-Information-Fähigkeit: Vertrag muss die DORA-Registerdaten praktisch hergeben.

## Typische Fehler

- Das Unternehmen hat ein allgemeines ISMS, aber kein DORA-taugliches IKT-Risikobild.
- Asset-Liste und Vertragsregister sprechen nicht dieselbe Sprache.
- Cloud-Vertrag enthält schöne Security-Anhänge, aber keinen realistischen Exit.
- Subdienstleister werden nur pauschal erlaubt.
- Geschäftsleitung wird informiert, aber nicht entscheidungsfähig eingebunden.
- Tests finden statt, aber Lessons Learned und Maßnahmenabschluss fehlen.

## Output

Erzeuge:

1. Scope-Entscheidung: DORA ja/nein, Art. 16 ja/nein, NIS2-Schnittstelle.
2. Management Summary für Vorstand/Geschäftsleitung.
3. Maßnahmenmatrix mit Owner, Frist, Nachweis.
4. Vertragslückenliste für IKT-Drittanbieter.
5. Nachweisordner-Index für Aufsicht/Revision.
6. Drei Sofortmaßnahmen für die nächsten zehn Arbeitstage.

## Anschluss

Bei Bankauslagerungen `marisk-auslagerungen-at9-dora` zuschalten. Bei Cyber-Gesamtcompliance `nis2-cybersecurity-compliance:dora-finanzsektor-abgrenzung` oder `nis2-cybersecurity-compliance:dora-art16-finanzunternehmen-simplified-framework` verwenden.
