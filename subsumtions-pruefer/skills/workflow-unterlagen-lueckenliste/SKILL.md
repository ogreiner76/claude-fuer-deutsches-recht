---
name: workflow-unterlagen-lueckenliste
description: "Unterlagen- und Lückenliste im Plugin subsumtions-pruefer: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen."
---

# Unterlagen- und Lückenliste

## Aufgabe

Dieser Workflow-Skill erstellt eine präzise Unterlagen- und Lückenliste statt allgemeiner Fragebögen. Er ordnet jedem Tatbestandsmerkmal die erforderlichen Unterlagen zu und zeigt, was vorhanden, was fehlend und was beschaffbar ist.

## Systematik: Unterlagenarten und ihre Funktion

| Unterlagenart | Funktion für Subsumtion | Beweismitteltyp ZPO |
|---|---|---|
| Vertrag, Kaufvertrag, AGB | Schuldverhältnis; Pflichten | Urkunde §§ 415 ff. ZPO |
| Rechnung, Quittung, Zahlungsbeleg | Leistung; Gegenleistung; Zahlung | Urkunde §§ 415 ff. ZPO |
| E-Mail-Korrespondenz, Chat | Willenserklärungen; Angebot/Annahme; Mängelrüge | Augenschein § 371 ZPO; ggf. Urkunde |
| Fotos, Videos | Mangel; Zustand; Ort | Augenschein § 371 ZPO |
| Ärztliche Atteste, Sachverständigengutachten | Schaden; Kausalität | Sachverständigengutachten §§ 402 ff. ZPO; Urkunde |
| Behördenbescheide, Urteile, Vollstreckungstitel | Rechtsverhältnis; Bestandskraft | Öffentliche Urkunde § 415 ZPO |
| Zeugenaussagen (vorauss.) | Tatsachen ohne Urkunde | Zeuge §§ 373 ff. ZPO |
| Kontoauszüge, Buchhaltung | Zahlung; Schaden; Höhe | Urkunde / Augenschein |
| Registereintragungen | Rechtsverhältnisse (GbR, GmbH, etc.) | Öffentliche Urkunde § 415 ZPO |

## Lückenliste-Erstellung

### Schritt 1 — TBM und erforderliche Unterlagen

Für jede Anspruchsgrundlage: Welches TBM braucht welchen Beweis?

Beispiel § 437 Nr. 3 i.V.m. §§ 280, 281 BGB (Schadensersatz statt der Leistung wegen Mangel):

| TBM | Benötigte Unterlage | Status |
|---|---|---|
| Kaufvertrag | Kaufvertrag (schriftlich / mündlich: Zeuge) | vorhanden: Anlage K1 |
| Mangel bei Übergabe | Abnahmeprotokoll; Fotos; SV-Gutachten | fehlend: Abnahmeprotokoll |
| Fristsetzung | Schreiben mit Datum und Frist | vorhanden: Anlage K2 |
| Fristablauf | Datum + Beweis für Zustellung | Zustellungsnachweis fehlt |
| Schaden | Kostenvoranschlag; Nachunternehmerrechnung | teilweise vorhanden: Anlage K3 |

### Schritt 2 — Prioritäten setzen

- **Rot:** Fehlt und ohne dieses Beweismittel ist die Anspruchsdurchsetzung nicht möglich
- **Gelb:** Fehlt, aber alternativ durch Zeuge oder Sachverständigen ersetzbar
- **Grün:** Vorhanden; ausreichend belegt

### Schritt 3 — Nachforderungsbrief strukturieren

Muster:

```
Betreff: Benötigte Unterlagen für Ihr Verfahren

Für die Prüfung und Durchsetzung Ihres Anspruchs aus § [Norm] benötigen wir:

DRINGEND (bis [Datum]):
1. [Unterlage A] — belegt [TBM X]; ohne diese Unterlage ist die Klage nicht empfehlenswert
2. [Unterlage B] — belegt [TBM Y]; Original oder beglaubigte Kopie

HILFREICH (bis [Datum]):
3. [Unterlage C] — stärkt [TBM Z]; alternativ Zeuge [Name] möglich

OPTIONAL:
4. [Unterlage D] — verbessert Beweislage; nicht zwingend
```

## Kaltstart

Wenn Material vorliegt, arbeite zuerst mit dem Material. Stelle nur Rückfragen, die für die nächste Weiche nötig sind:

1. Wer fragt in welcher Rolle?
2. Was ist das gewünschte Ergebnis?
3. Gibt es Fristen, Termine, Zustellungen, Zahlungen oder Sanktionen?
4. Welche Unterlagen, Daten oder Belege liegen bereits vor?

## Arbeitsworkflow

1. Rolle, Ziel, Frist und Unterlagenlage in höchstens fünf Fragen klären.
2. Unterlagenarten-Matrix erstellen: TBM → benötigte Unterlage → Status.
3. Lücken priorisieren (Rot/Gelb/Grün).
4. Nachforderungsbrief oder interne Checkliste erstellen.
5. Passende Spezialskills vorschlagen (z. B. spezial-tatbestandsmerkmale-dokumentenmatrix-und-lueckenliste).

## Output-Standard

- Kurzbild: worum es geht, was gesichert ist, was offen ist.
- Unterlagen-Matrix: TBM, Unterlage, Status, Priorität.
- Nachforderungstext: präzise Formulierung, nicht allgemein.
- Konkreter nächster Schritt mit Frist, Zuständigkeit und Unterlagen.

## Quellenregel

- Normen live prüfen: gesetze-im-internet.de (ZPO §§ 371, 373 ff., 402 ff., 415 ff.; BGB §§ 280, 437 ff.).
- Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle.
- Keine Blindzitate. Paywall-Literatur nur mit Nutzerquelle.
- Unsicherheiten und Annahmen ausdrücklich markieren.

## Qualitäts-Hardening

- Arbeite aktennah: Tatsachen, Belege, Fristen, Zuständigkeit und gewünschtes Arbeitsprodukt zuerst klären.
- Keine Rechtsprechung aus Modellwissen zitieren. Jede Entscheidung vor Ausgabe absichern.
- Wenn eine Quelle, Randnummer, Behördenpraxis oder Frist nicht sicher geprüft ist, sichtbar als Prüfpunkt markieren.
- Ergebnisse so liefern, dass sie sofort weiterverwendbar sind: Kurzbild, Prüfpfad, Risikoampel, Lückenliste und konkrete nächste Schritte.
