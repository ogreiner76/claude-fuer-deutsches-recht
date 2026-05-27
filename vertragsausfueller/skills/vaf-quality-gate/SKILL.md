---
name: vaf-quality-gate
description: "Letzte Pruefschleuse vor Ausgabe eines Vertragsentwurfs. Sucht fehlende Werte, ungeklaerte Wahlklauseln, Rechenfehler, Normierungsprobleme, Anlagenluecken, Freigabehindernisse, Track-Changes-Konflikte. Mit Pruefraster Stop-Kriterien Eskalations-Matrix Beispielprotokollen. Originaldateien nie ueberschrieben. Track Changes nur nach ausdruecklicher Bestaetigung."
---

# Quality Gate — Vertragsausfueller


## Triage zu Beginn

1. Wurde das Feldinventar vollständig ausgefüllt (vaf-feldinventar) und der Plausibilitätscheck durchgeführt (vaf-plausibilitaetscheck)?
2. Sind alle Klauselentscheidungen getroffen und protokolliert (vaf-klauselentscheidung)?
3. Ist die Ampel des Quality Gate grün oder gibt es offene No-go-Kriterien?
4. Hat der Mandant ausdrücklich Track Changes / Redline bestätigt?

## Aktuelle Rechtsprechung

- BGH, Urt. v. 06.04.2016 - VIII ZR 79/15, NJW 2016, 2645 — AGB-Klauselverstoß nach § 307 BGB: Verstoß führt zur Gesamtnichtigkeit der Klausel, nicht zur geltungserhaltenden Reduktion; Ersatz durch dispositives Recht.
- BGH, Urt. v. 14.11.2018 - IV ZR 141/17, NJW 2019, 293 — Qualitätssicherungsklausel in Verträgen: wirksam, wenn klar und transparent (§ 307 Abs. 1 S. 2 BGB Transparenzgebot).
- BGH, Urt. v. 25.11.2015 - VIII ZR 360/14, NJW 2016, 934 — Vertragsstrafe: muss bei Abschluss klar und bestimmt sein; nachträgliche Anpassung nur im Rahmen der Inhaltskontrolle.
- BGH, Urt. v. 09.05.2018 - III ZR 67/17, NJW 2018, 2401 — Transparenzgebot: unklare Klausel geht zu Lasten des Verwenders; Quality Gate muss auf Unklarheiten prüfen.

## Zentrale Normen

- § 307 Abs. 1 S. 2 BGB — Transparenzgebot (Klausel muss klar und verständlich sein)
- § 139 BGB — Teilnichtigkeit (unwirksame Klausel → Gesamtvertrag nur bei separabler Klausel)
- § 306 BGB — Rechtsfolge unwirksamer AGB (dispositives Recht tritt ein)

## Kommentarliteratur

- Grüneberg, BGB, 83. Aufl. 2024, § 307 Rn. 30-60 (Transparenzgebot)
- MüKo-BGB/Basedow, 9. Aufl. 2022, § 306 Rn. 1-20 (Rechtsfolgen unwirksamer AGB)

## Zweck

Letzte Schleuse, bevor ein Vertragsentwurf, eine Redline oder ein Track-Changes-Dokument an den Mandanten oder die Gegenseite herausgeht. Verhindert sechs typische Fehlerklassen: leere Pflichtfelder, ungeklärte Wahlklauseln, Rechenfehler, normwidrige Formulierungen, fehlende Anlagen, fehlende Freigaben. Liefert ein Pruefprotokoll mit Go / Go mit Warnungen / No-go.

Arbeitet freistehend im Vertragsausfueller-Plugin, setzt keine anderen Plugins voraus.

## 1) Eingangs-Trigger

Der Quality Gate startet automatisch oder auf Anfrage, wenn vorliegt:

- hochgeladene Word-Vorlage oder alter Vertrag
- Term Sheet, E-Mail, Tabelle oder Freitext mit Eckdaten
- Wunsch nach neuem Vertragsentwurf
- Wunsch nach Redline / Track Changes
- Wunsch nach Bilingual-Fassung (DE/EN)

## 2) Sechs-stufiges Prüfraster

### Stufe 1 — Pflichtfeld-Vollständigkeit

Prüfen, ob alle Pflichtfelder belegt sind:

| Pflichtfeld | Typisch | Stopper-Frage |
|---|---|---|
| Parteien | Name, Anschrift, Vertretungsbefugnis | Ist die Vertretung dokumentiert? |
| Vertragsgegenstand | konkrete Leistung | Eindeutig im Wortlaut? |
| Hauptleistungspflichten | Lieferung, Zahlung, Frist | Konkret und vollstreckbar? |
| Zeitliche Geltung | Anfang, Ende, Verlängerung | Datum und Dauer im Wortlaut? |
| Vertragsstrafe / Sicherheiten | falls vereinbart | Höhe und Voraussetzung? |
| Anwendbares Recht / Gerichtsstand | bei B2B blank lassen oder DE | Wahl getroffen? |
| Schriftform / elektronische Signatur | je nach Norm | Form gewahrt? |
| Unterschrift / Datum | Pflichtfeld | Leerzeichen markiert? |

**Stopper-Kriterium**: Ein leeres Pflichtfeld -> No-go.

### Stufe 2 — Platzhalter-Reste

Prüfen, ob alle `[...]`, `XXX`, `TBD`, `noch zu klaeren`, `tba`, `t.b.a.`, `‹...›` aufgeloest sind. Auch in Fußnoten, Anlagen-Verweisen und unterschriftsblocken.

**Stopper-Kriterium**: Ein Platzhalter im Hauptteil -> No-go. In Anlagen-Verweis -> Warnung mit Hinweis.

### Stufe 3 — Zahlen- und Fristenlogik

Prüfen:

- Sind alle Zahlen mathematisch konsistent (Hauptsumme = Summe der Teilbetraege)?
- Sind Prozentsätze konsistent (z.B. Mwst. + Brutto = Netto + Mwst.)?
- Sind alle Fristen kalendermaessig korrekt (z.B. „14 Tage ab Rechnungsdatum" konsistent mit „Fälligkeit 14 Tage nach Rechnung")?
- Sind die Fristen rechtswirksam (Verbraucher: Mindestlaufzeiten? Widerrufsrecht?)?
- Stimmt das Schluss-Datum mit der Vertragsdauer?

**Stopper-Kriterium**: Rechenfehler -> No-go. Frist juristisch problematisch -> Warnung mit Klauselvorschlag.

### Stufe 4 — Normwidrige Formulierungen

Prüfen gegen typische AGB-Fallen und Klauselverbote:

| Typ | Norm | Beispiel-Fall |
|---|---|---|
| Verzugszinsen über Basis + 9 % bei B2C | Paragraf 288 IV BGB | „12 % Verzugszinsen" -> Verstoß |
| Schadensersatzbeschraenkung auf Eigenleistung | Paragraf 309 Nr. 7a, b BGB | Ausschluss für Personenschäden -> nichtig |
| Schiedsgerichtsklausel ohne Klarheit | Paragraf 1031 ZPO | Verbraucher ohne Sondervereinbarung -> nichtig |
| Lange Bindungsfrist bei Verbrauchern | Paragraf 309 Nr. 9 BGB | Verlängerung > 1 Jahr automatisch -> Risiko |
| Salvatorische Klausel als Lückenfueller | BGH NJW 2009, 2671 Rn. 13 | wirkt nicht heilend bei AGB |

**Stopper-Kriterium**: Bei klarem Klauselverstoß B2C -> No-go. Bei B2B-Streitfall -> Warnung mit Risiko-Hinweis.

### Stufe 5 — Anlagen-Lücken

Prüfen:

- Sind alle im Vertragstext genannten Anlagen vorhanden?
- Sind die Anlagen mit derselben Bezeichnung versehen (Anlage 1, Annex 1, A1)?
- Sind die Anlagen vom Auftraggeber bestätigt?
- Bei AGB als Anlage: sind die AGB einbezogen (Bezugnahme im Vertragstext)?

**Stopper-Kriterium**: Genannte Anlage fehlt -> Warnung mit Auflistung. Bei AGB-Bezugnahmemangel -> No-go.

### Stufe 6 — Freigabe-Hindernisse

Prüfen:

- Ist die Vertragsart vom Mandanten freigegeben (z.B. „Generalvollmacht" benoetigt Sonderfreigabe)?
- Ist die Vertretungsbefugnis dokumentiert?
- Bei Höhen-Schwellen (z.B. Streitwert > 100.000 EUR): Gesellschafterbeschluss?
- Bei sensiblen Klauseln (z.B. Wettbewerbsverbot, Geheimhaltung mit Vertragsstrafe): explizite Freigabe?

**Stopper-Kriterium**: Fehlende Freigabe -> No-go.

## 3) Track-Changes-Vorprüfung

Bei Wunsch nach Redline / Track Changes:

- [ ] Ist die Ausgangsfassung eindeutig (welcher Vertragsstand wird als Basis genommen)?
- [ ] Ist die Vergleichsfassung freigegeben (kein Entwurfsstand)?
- [ ] Sind Track Changes vom Mandanten **ausdruecklich** bestätigt?
- [ ] Ist die Track-Changes-Funktion konsistent eingesetzt (keine Mischung Hand-Markierungen + Word-Tracker)?

**Stopper-Kriterium**: Keine ausdrueckliche Bestätigung -> No-go.

## 4) Ausgabe-Format Quality-Gate-Protokoll

```
QUALITY-GATE-PROTOKOLL
======================
Vertrag: [Bezeichnung]
Stand: [Datum, Uhrzeit]
Vorpruefer: [Plugin]

PFLICHTFELDER
[Ergebnis: OK / Lueckend]
Luecken: ...

PLATZHALTER
[Ergebnis: OK / Reste vorhanden]
Reste: Zeile XX [Text]

ZAHLENLOGIK
[Ergebnis: OK / Fehler]
Fehler: Hauptsumme = X EUR, Summe Teilbetraege = Y EUR

NORMWIDRIGE FORMULIERUNGEN
[Ergebnis: OK / Risiko / Verstoss]
Hinweise: ...

ANLAGEN
[Ergebnis: OK / Lueckend]
Fehlend: Anlage 3 (im Vertragstext genannt)

FREIGABE
[Ergebnis: OK / Fehlend]
Offen: ...

GESAMT-AMPEL: GRUEN / GELB / ROT
Empfehlung: Go / Go mit Warnungen / No-go
```

## 5) Eskalations-Matrix

| Ampel | Konsequenz | Nächster Schritt |
|---|---|---|
| GRUEN (Go) | Vertrag bereit zur Ausgabe | Bei Wunsch: Track Changes auf Bestätigung |
| GELB (Go mit Warnungen) | Vertrag ausgebbar, aber Risiko | Mandanten über Warnung informieren, Bestätigung |
| ROT (No-go) | Vertrag nicht ausgebbar | Rueckfrage an Mandanten, Klauselvorschlag |

## 6) Leitplanken

- **Originaldateien werden nie überschrieben.** Es entsteht stets eine neue Datei mit Suffix `_qg_yyyymmdd` o.ae.
- **Track Changes, Redline oder Vergleichsfassung nur nach ausdruecklicher Rueckfrage und Bestätigung.** Nicht eigenmaechtig.
- **Offene Werte bleiben sichtbar** in der ausgegebenen Datei (z.B. als `[noch zu klaeren: ...]`); sie werden nicht erfunden.
- **Juristische Wahlentscheidungen werden erklärt und protokolliert** in der Vertragsdatenmatrix und im Rückfragen-Protokoll.
- **Risiken werden konkret benannt** (Norm, Folge, Vorschlag), nicht pauschalisiert.

## 7) Typische Fehler beim Quality-Gate

1. **Platzhalter im Footer übersehen.** Pruefe explizit auch Kopf-/Fußzeilen.
2. **Anlagen-Verzeichnis unvollständig.** Bei AGB-Bezug ist auch die Empfangsbestätigung Anlage.
3. **Track Changes ohne Bestätigung.** Klassischer Compliance-Fehler.
4. **Mwst.-Klausel übersehen** (B2C: Brutto, B2B: Netto + Mwst.).
5. **Schriftform Paragraf 126 BGB nicht beachtet.** Bei langfristigen Verträgen sicherheitshalber Schriftform.

## 8) Schnittstellen

- `vaf-feldinventar` — extrahiert das Pflichtfeld-Inventar aus der Vorlage
- `vaf-termsheet-mapping` — mappt Term-Sheet-Werte auf die Feldliste
- `vaf-rueckfrageninterview` — klärt offene Punkte mit dem Mandanten
- `vaf-plausibilitaetscheck` — pre-Quality-Gate-Prüfung der Zahlenlogik
- `vaf-redline-qa` — Review von Track-Changes-Fassungen
- `vaf-clean-output` — finaler Clean-Entwurf nach GRUEN-Ampel
- `vaf-track-changes-nur-nach-frage` — Track Changes nur nach Bestätigung
