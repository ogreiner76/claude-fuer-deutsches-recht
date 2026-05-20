---
name: wenn-prognose-negativ-naechste-schritte
description: Wenn die Fortbestehensprognose negativ ausfaellt — Eskalations- und Pflichtenkatalog fuer den Geschaeftsleiter. Antragspflicht § 15a InsO sechs Wochen bei Ueberschuldung drei Wochen bei Zahlungsunfaehigkeit. Zahlungsverbot § 15b InsO. Pruefung der drohenden Zahlungsunfaehigkeit § 18 InsO mit StaRUG-Option. Einbindung Insolvenzanwalt zwingend. Pruefung Selbstantrag oder Eigenverwaltung oder Schutzschirmverfahren oder StaRUG-Restrukturierungsplan.
---

# Wenn die Prognose negativ ist — naechste Schritte

## Disclaimer (Schluesselstelle)

Wenn die Fortbestehensprognose negativ ausfaellt liegt **insolvenzrechtliche Ueberschuldung** nach § 19 InsO vor. Die Antragspflicht beginnt zu laufen. **Ohne Insolvenzanwalt** sollte ab diesem Punkt nicht weitergearbeitet werden. Jede Tagesverzoegerung kann zur **strafrechtlichen Haftung** nach § 15a Abs. 4 InsO und zur **zivilrechtlichen Haftung** nach § 15b InsO fuehren.

## Sofortmassnahmen — innerhalb 24 Stunden

### 1. Insolvenzanwalt einschalten

- Insolvenzanwalt aus dem Profil (Skill `kaltstart-interview`).
- Termin innerhalb der naechsten 48 Stunden.
- Vorlage: vollstaendige Prognosedokumentation aus Skill `prognose-dokumentation-stichtag`.

### 2. Zahlungsverhalten anpassen — § 15b InsO

Mit Eintritt der Insolvenzreife duerfen **keine Zahlungen** mehr geleistet werden die nicht mit der Sorgfalt eines ordentlichen und gewissenhaften Geschaeftsleiters vereinbar sind.

Ausnahmen (§ 15b Abs. 1 InsO):

- Zahlungen die zur Erhaltung des Geschaeftsbetriebs erforderlich sind.
- Zahlungen die im Rahmen ordentlicher Geschaeftstaetigkeit unvermeidbar sind.
- Zahlungen aus zweckgebundener Treuhand (Sozialversicherungsbeitraege Lohnsteuer).

**Praktisch**:

- Sozialversicherungsbeitraege Arbeitnehmer-Anteil: **weiter abfuehren** (§ 266a StGB Pflicht zur Abfuehrung).
- Lohn- und Gehaltszahlung: weiter (sonst gefaehrden der Betrieb).
- Lohnsteuer abfuehren.
- Umsatzsteuer Voranmeldungen abgeben (auch wenn keine Zahlung erfolgt).
- Bezahlung von Lieferanten nur nach Abstimmung mit Insolvenzanwalt — Risiko § 15b InsO.

### 3. Frist § 15a InsO

| Insolvenzgrund | Frist nach Eintritt |
|---|---|
| Zahlungsunfaehigkeit § 17 InsO | drei Wochen (§ 15a Abs. 1 S. 2 InsO) |
| Ueberschuldung § 19 InsO | sechs Wochen (§ 15a Abs. 1 S. 2 InsO seit SanInsFoG 2021) |
| Drohende Zahlungsunfaehigkeit § 18 InsO | **keine Antragspflicht** — aber Antragsoption |

**Achtung**: Die Frist beginnt mit **Eintritt** des Insolvenzgrunds — nicht mit Kenntnis. Im Streit ist das objektive Datum massgeblich.

## Mittelfristige Optionen (zusammen mit Insolvenzanwalt)

### Option A — Regelinsolvenzantrag

- Selbstantrag § 15 InsO.
- Antrag durch Insolvenzanwalt vorbereitet.
- Bei Eroeffnung: Insolvenzverwalter uebernimmt.

### Option B — Eigenverwaltungsantrag (§ 270 ff. InsO)

- Geschaeftsleitung bleibt im Amt (Sachwalter wird bestellt).
- Voraussetzungen Eigenverwaltungsplan strenge Bonitaetsanforderung.

### Option C — Schutzschirmverfahren (§ 270d InsO)

- Bei drohender Zahlungsunfaehigkeit oder Ueberschuldung **vor** Eintritt der Zahlungsunfaehigkeit.
- Bescheinigung eines erfahrenen Sanierungsanwalts oder WPs erforderlich (Aussichten auf Sanierung).
- Antrag auf Schutzschirm zur Erarbeitung eines Insolvenzplans.

### Option D — StaRUG-Restrukturierungsrahmen

- Nur bei **drohender** Zahlungsunfaehigkeit § 18 InsO (24-Monats-Prognose) — **nicht** bei akuter Zahlungsunfaehigkeit oder Ueberschuldung.
- Restrukturierungsplan mit Glaeubiger-Mehrheiten.
- Restrukturierungsbeauftragter durch Restrukturierungsgericht.
- Bescheinigung nach §§ 50 51 StaRUG (IDW S 9) wird empfohlen.

## Pruefraster Auswahl Verfahren

```yaml
verfahren-pruefraster:
  zahlungsunfaehigkeit-eingetreten:
    frist: drei-Wochen
    optionen:
      - Regelinsolvenzantrag (Selbstantrag)
      - Eigenverwaltung (wenn Voraussetzungen erfuellt)
      - Schutzschirmverfahren nur bei drohender Zahlungsunfaehigkeit
        BEVOR Zahlungsunfaehigkeit eintrat
    ausgeschlossen: StaRUG (zu spaet)
    
  ueberschuldung-eingetreten-aber-zahlungsfaehig:
    frist: sechs-Wochen
    optionen:
      - Regelinsolvenzantrag
      - Eigenverwaltung
      - Schutzschirmverfahren
    pruefung-staerug: nur wenn drohende Zahlungsunfaehigkeit
      separat festgestellt werden kann (Prognose 24 Monate negativ)
    
  drohende-zahlungsunfaehigkeit:
    frist: keine
    optionen:
      - StaRUG-Restrukturierungsrahmen (bevorzugt)
      - Eigenantrag § 18 InsO mit Eigenverwaltung
      - Schutzschirmverfahren
```

## Beratungsbedarf

In jedem Fall:

- **Insolvenzanwalt** (Skill `insolvenzrecht` aus dem entsprechenden Plugin)
- **Wirtschaftspruefer** bei IDW S 11 / S 9 Bescheinigung
- **Sanierungsberater** wenn Sanierungskonzept IDW S 6 erforderlich

## Eskalation an Insolvenzanwalt

Schreiben an Insolvenzanwalt:

```
Sehr geehrte Damen und Herren,

ich bin Geschaeftsfuehrer der [Firma]. Nach Erstellung der
Fortbestehensprognose nach § 19 Abs. 2 InsO zum Stichtag [Datum] habe ich
das Ergebnis dass die Prognose negativ ausfaellt. Damit liegt
insolvenzrechtliche Ueberschuldung vor.

Stichtag: [Datum]
Anlass: [siehe Fortbestehensprognose Anlage]
Ergebnis: insolvenzrechtliche Ueberschuldung
Frist § 15a InsO: bis [Datum + sechs Wochen]

Ich bitte um umgehende Terminvereinbarung zur Pruefung des weiteren Vorgehens
(Regelinsolvenz / Eigenverwaltung / Schutzschirmverfahren / ggf. StaRUG).

Anlagen:
  - Fortbestehensprognose mit allen Anlagen (Datum [...])
  - Bilanz [Jahr]
  - Aktuelle BWA SuSa
  - 12-Monats-Liquiditaetsplan
  - Sanierungsbausteine-Empfehlung

Mit freundlichen Gruessen
[Geschaeftsfuehrer]
```

## Auch im Zweifel

Wenn nicht klar ist ob die Prognose negativ ist (Grenzfall): **lieber Anwalt einschalten** als die Frist verstreichen lassen. Die Anwaltsgebuehr ist deutlich geringer als die persoenliche Haftung.

## Ausgabe

- `eskalation-an-insolvenzanwalt-<datum>.docx` als Mitteilung.
- Termin im Kalender innerhalb 24 Stunden.
- Status-Eintrag im Sanierungsbausteine-Tracker: „Pruefung negativ — Eskalation eingeleitet".
- Ende dieses Plugin-Workflows; Fortfuehrung im Plugin `insolvenzrecht` durch Insolvenzanwalt.
