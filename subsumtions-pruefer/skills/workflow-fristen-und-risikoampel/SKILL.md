---
name: workflow-fristen-und-risikoampel
description: "Fristen- und Risikoampel im Plugin subsumtions-pruefer: macht eine Sofortampel für Frist, Zuständigkeit, Haftung, Eilbedarf und fehlende Unterlagen."
---

# Fristen- und Risikoampel

## Aufgabe

Dieser Workflow-Skill erstellt eine Sofortampel für Fristen, Subsumtionsrisiken, Beweislage und Eilbedarf. Er markiert kritische Punkte in drei Farben und gibt konkrete Heilungsmaßnahmen.

## Risikoampel Subsumtion

- **Rot:** Sprung-Subsumtion (Tatsache wird direkt unter die Norm gesetzt, ohne Definition). Heilung: Definition mit Quelle einsetzen, dann unter Definition subsumieren.
- **Rot:** Definition ohne Quelle (BGH, h.M., Kommentar; nur mit Nutzerquelle). Heilung: Quelle ergänzen oder als Prüfpunkt markieren.
- **Rot:** Zirkelschluss. Heilung: Tatsachen aus dem Sachverhalt zitieren, dann erst werten.
- **Gelb:** Streitstand übersehen, obwohl tragend. Heilung: h.M., Mindermeinung, Argumente, Stellungnahme.
- **Gelb:** Konjunktiv im Schluss ("könnte vorliegen"). Heilung: Schluss soll Indikativ ("liegt vor").
- **Gelb:** Zwischenergebnis je Tatbestandsmerkmal fehlt. Heilung: Je TBM abschließen.
- **Grün:** Vollständige Subsumtion mit Quelle, klarer Sprache, Zwischenergebnis.

## Risikoampel Fristen

| Frist | Norm | Ampel-Regel |
|---|---|---|
| Verjährung < 30 Tage | §§ 195 ff. BGB | Rot — sofortige Klageerhebung oder Hemmungshandlung (§ 204 BGB) |
| Verjährung 30–90 Tage | §§ 195 ff. BGB | Gelb — Risikoprotokoll; Mandant informieren |
| Verjährung > 90 Tage | §§ 195 ff. BGB | Grün — Fristenkontrolle einrichten |
| Widerspruchsfrist (VA) | § 70 VwGO | Rot wenn < 7 Tage; Gelb wenn 7–20 Tage |
| Klagefrist (VA) | § 74 VwGO | Rot wenn < 7 Tage |
| Anfechtungsfrist § 121 BGB | § 121 BGB | Rot wenn unverzügliche Anfechtung überfällig |
| Berufungsfrist | § 517 ZPO | Rot wenn < 7 Tage; Gelb wenn 7–14 Tage |

## Diagnose-Schritte

1. Jeden Satz markieren als "Norm", "Definition", "Tatsache", "Subsumtion" oder "Schluss".
2. Reihenfolge prüfen: Norm → Definition → Tatsache → Subsumtion → Schluss.
3. Lücken anzeigen.
4. Quellen zur Definition verlangen oder als Prüfpunkt setzen.

## Fristenkontrolle-Checkliste

**Bei jedem Mandat sofort prüfen:**

1. Regelmäßige Verjährungsfrist (§ 195 BGB: 3 Jahre; Beginn § 199 BGB: Ende Entstehungsjahr)
2. Besondere Verjährungsfristen (§ 438 BGB Kauf: 2 Jahre; § 548 BGB Miete: 6 Monate)
3. Prozessuale Fristen (§§ 517, 548 ZPO Berufung: 1 Monat; § 74 VwGO Klage: 1 Monat)
4. Fristhemmung bereits eingetreten? (§§ 203–213 BGB)
5. Eilbedarf für einstweiligen Rechtsschutz? (Zeitnähe nach Kenntniserlangung; OLG-Rechtsprechung variiert)

## Kaltstart

Wenn Material vorliegt, arbeite zuerst mit dem Material. Stelle nur Rückfragen, die für die nächste Weiche nötig sind:

1. Wer fragt in welcher Rolle?
2. Was ist das gewünschte Ergebnis?
3. Gibt es Fristen, Termine, Zustellungen, Zahlungen oder Sanktionen?
4. Welche Unterlagen, Daten oder Belege liegen bereits vor?

## Arbeitsworkflow

1. Rolle, Ziel, Frist und Unterlagenlage in höchstens fünf Fragen klären.
2. Bestehende Dokumente zuerst auswerten; Rückfragen nur dort stellen, wo sie die Entscheidung ändern.
3. Risikoampel für Subsumtion und Fristen erstellen.
4. Passende Spezialskills vorschlagen.
5. Ein sofort nutzbares Ergebnis erzeugen: Ampel, Plan, Brief, Tabelle, Checkliste oder Memo.

## Output-Standard

- Kurzbild: worum es geht, was gesichert ist, was offen ist.
- Subsumtions-Risikoampel (Rot/Gelb/Grün je Fehlertyp).
- Fristen-Risikoampel (Rot/Gelb/Grün je Frist).
- Konkreter nächster Schritt mit Frist, Zuständigkeit und Unterlagen.

## Quellenregel

- Normen live prüfen: gesetze-im-internet.de (BGB §§ 195, 199, 203 ff., 438, 548; ZPO §§ 294, 517, 548; VwGO §§ 70, 74).
- Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle.
- Keine Blindzitate. Paywall-Literatur nur mit Nutzerquelle.
- Unsicherheiten und Annahmen ausdrücklich markieren.

## Qualitäts-Hardening

- Arbeite aktennah: Tatsachen, Belege, Fristen, Zuständigkeit und gewünschtes Arbeitsprodukt zuerst klären.
- Keine Rechtsprechung aus Modellwissen zitieren. Jede Entscheidung vor Ausgabe absichern.
- Wenn eine Quelle, Randnummer, Behördenpraxis oder Frist nicht sicher geprüft ist, sichtbar als Prüfpunkt markieren.
- Ergebnisse so liefern, dass sie sofort weiterverwendbar sind: Kurzbild, Prüfpfad, Risikoampel, Lückenliste und konkrete nächste Schritte.
