---
name: versand-vor-check
description: Pflicht-Pre-Check vor jedem ausgehenden Versand — prueft Dokumentidentitaet (das richtige PDF? Stand vom richtigen Datum? Aktenzeichen passt?) Unterschrift (durch berechtigte Person? eigenhaendig oder qualifizierte elektronische Signatur?) Adressat (richtiges Gericht / Behoerde / Mandant? richtige Adresse beA-SAFE-ID EGVP-Adresse?) Anlagen (vollstaendig? im Inhaltsverzeichnis aufgefuehrt? Sigel richtig?) Versandweg (Post / beA / EGVP / E-Mail / De-Mail). Versandquittung sichern. Audit-Eintrag. Bei Mangel Versand sperren.
---

# Versand-Vor-Check (Pflicht vor jedem Versand)

## Pflicht

Jeder ausgehende Versand der Kanzlei muss diesen Check durchlaufen. Fehlversand ist anwaltliche Pflichtverletzung mit Haftungsrisiko.

## Pruefraster

### 1. Dokumentidentitaet

- [ ] Ist es das richtige PDF / DOCX?
- [ ] Hat das Dokument den aktuellen Stand (Datum im Briefkopf passt zum Versand)?
- [ ] Aktenzeichen der Kanzlei korrekt?
- [ ] Aktenzeichen / Az des Empfangsgerichts / der Empfangsbehoerde korrekt?
- [ ] Streitwert / Gegenstandswert korrekt?

### 2. Unterschrift

- [ ] Eigenhaendige Unterschrift (Original) bei Papierversand?
- [ ] Bei beA-Versand: qualifizierte elektronische Signatur (qeS) **oder** sicherer Uebermittlungsweg (sUW) durch persoenliches Versenden des beA-Inhabers?
- [ ] Ist die unterzeichnende Person berechtigt (Anwalt der Kanzlei mit Vollmacht in der Akte)?
- [ ] Bei Sozietaet: korrekt fuer die Sozietaet unterzeichnet oder mit "i. A." / "i. V."?

### 3. Adressat

- [ ] Richtige Behoerde / Gericht?
- [ ] Korrekte Anschrift?
- [ ] beA-SAFE-ID des Empfaengers korrekt (RA-zu-RA-Versand und Gericht)?
- [ ] EGVP-Adresse der Behoerde korrekt?
- [ ] Aktenzeichen des Empfaengers im Schreiben?

### 4. Anlagen

- [ ] Anlagenverzeichnis vorhanden mit Sigel (K1 K2 ...)?
- [ ] Jede Anlage im Schriftsatz zitiert?
- [ ] Jede Anlage tatsaechlich im Konvolut?
- [ ] Reihenfolge richtig?
- [ ] Sigel-Stempel auf erster Seite jeder Anlage?
- [ ] Schwaerzungen Dritter-Daten erfolgt wo erforderlich (DSGVO Datenminimierung)?

### 5. Versandweg und Form

- [ ] **beA** fuer Versand an Gericht und Behoerde durch RA (Pflicht § 31a BRAO § 130d ZPO und entsprechend in den anderen Verfahrensordnungen).
- [ ] **EGVP** als alternative Schnittstelle fuer Behoerde.
- [ ] **Post** als Rueckfalloption (Mandantenkommunikation; wenn Empfaenger kein beA hat).
- [ ] **E-Mail** an Mandant — Verschluesselung Schutz der Mandanteninhalte (BRAO Berufsrecht).

### 6. Versandquittung

- [ ] beA-Eingangsbestaetigung gesichert (PDF speichern unter `mandate/<az>/03_schriftsaetze/<datum>-versand-quittung.pdf`)?
- [ ] EGVP-Eingangsbestaetigung gesichert?
- [ ] Post: Einschreiben mit Rueckschein oder Bote-Protokoll?

### 7. Fristenbuch

- [ ] Fristerledigung im Fristenbuch eingetragen?
- [ ] Folge-Fristen (z. B. Reaktionsfrist Gegenseite) eingetragen?

### 8. Postausgangsbuch

- [ ] Eintrag im Postausgangsbuch (Skill `posteingang-ausgang`)?

## Sperrregel

Wenn ein Pflicht-Pruefpunkt offen ist: Versand sperren. Eskalation an zustaendigen Anwalt.

## Audit-Eintrag

Pro Versand ein Audit-Eintrag:

```yaml
versand-id: V-2026-00123
mandat-az: 2026/0042
datum: 2026-05-20
empfaenger: Amtsgericht Muenchen
versandweg: beA
dokument: klage-2026-0042.pdf
unterzeichnet-von: RA Mueller
checks-bestanden:
  - dokumentidentitaet: ok
  - unterschrift: ok-qes
  - adressat: ok-bea-safe-id-bestaetigt
  - anlagen: ok-vollstaendig
  - versandweg: bea
  - quittung: gesichert
freigegeben-von: RA Mueller
versand-zeit: 2026-05-20T11:23:45
quittung-pdf: mandate/2026-0042/03_schriftsaetze/2026-05-20-versand-quittung.pdf
```

## Sonderfaelle

### beA-Stoerung

- Bei Stoerung des beA-Systems: Glaubhaftmachung der Stoerung mit Screenshot + Fehlermeldung; Ersatzeinreichung schriftlich + qeS.
- Stoerungsdokumentation in Audit.

### Wochenende / Feiertag

- Pruefung der Fristen vor Versand (auf naechsten Werktag verschoben?).

### Eilversand

- Bei Eilversand am Tag der Fristerledigung: zusaetzlich telefonische Kontrolle des Eingangs beim Gericht.

## Ausgabe

- Versand-Audit-Eintrag in `versand-audit.jsonl` (append-only).
- Quittungs-PDF unter Mandatsakte.
- Bestaetigung an Anwalt und Sekretariat.
