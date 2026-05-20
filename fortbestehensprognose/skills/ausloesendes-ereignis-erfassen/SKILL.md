---
name: ausloesendes-ereignis-erfassen
description: Erfasst den Anlass der Fortbestehensprognose. Typische Ausloeser sind Hinweis des Steuerberaters nach § 102 StaRUG Hinweis des Wirtschaftspruefers Bekanntwerden negativen Eigenkapitals Bilanzaufstellung mit negativem EK Liquiditaetsengpass Gesellschafterhinweis eigene Sorge des Geschaeftsfuehrers. Dokumentiert Anlass Datum Hinweisgeber Mitteilungsform. Wichtig fuer spaeteren Nachweis dass der Geschaeftsfuehrer auf Insolvenzanzeichen rechtzeitig reagiert hat (Haftungsfrage § 15b InsO).
---

# Ausloesendes Ereignis erfassen

## Zweck

Die Fortbestehensprognose ist kein Selbstzweck — sie ist die Antwort auf einen konkreten Anlass. Der Anlass wird dokumentiert weil **er Beweis ist**: bei spaeteren Haftungsfragen (§ 15b InsO, § 43 GmbHG, § 826 BGB ggue Glaeubigern) zeigt die Dokumentation dass der Geschaeftsfuehrer **zeitnah** auf Anzeichen reagiert hat.

## Typische Ausloeser

### 1. Hinweis des Steuerberaters nach § 102 StaRUG

Seit 01.01.2021 hat der Steuerberater eine **Hinweispflicht**: wenn ihm bei der Bilanzaufstellung Anhaltspunkte fuer einen moeglichen Insolvenzeroeffnungsgrund auffallen muss er den Mandanten darauf hinweisen.

- Datum des Hinweises (schriftlich / mündlich / im Gespraech)
- Wortlaut wenn schriftlich
- Konkrete Anhaltspunkte die der StB genannt hat
- Quittierung des Hinweises durch den Mandanten

### 2. Hinweis des Wirtschaftspruefers

Bei pruefungspflichtigen Gesellschaften (mittelgrosse oder grosse KapGes nach § 267 HGB) kann der Pruefer im Rahmen des Jahresabschlusses einen **Hinweis zur Going-Concern-Annahme** geben oder den Bestaetigungsvermerk einschraenken oder versagen.

### 3. Eigene Feststellung bei der Bilanzaufstellung

- **Eigenkapital negativ** (Aktiva kleiner als Passiva).
- **Wesentliche stille Lasten** im Status (z. B. Pensionsrueckstellungen ausserbilanziell).
- **Erhebliche aussergewoehnliche Verluste** im laufenden Geschaeftsjahr.

### 4. Liquiditaetsengpass

- Mahnungen Gerichtsbeschluesse oder Zahlungsverzug bei wesentlichen Glaeubigern.
- Kreditlinie ausgeschoepft Kontoueberziehung.
- Lohn- und Gehaltszahlungen knapp.
- Steuer- und Sozialversicherungsabgaben nicht puenktlich.

### 5. Gesellschafterhinweis

- Brief oder E-Mail des Gesellschafters mit Sorge ueber Lage.
- Gesellschafterbeschluss zur Pruefung der Fortbestehensprognose.

### 6. Eigene Sorge des Geschaeftsfuehrers

- Subjektive Wahrnehmung dass die Lage kritisch wird.
- Wichtig: auch ohne externen Hinweis muss der Geschaeftsfuehrer aktiv pruefen — Sorgfaltspflicht § 43 GmbHG, § 93 AktG.

### 7. Externes Ereignis

- Wegfall Hauptkunde.
- Kreditlinien-Kuendigung der Bank.
- Markteinbruch.
- Insolvenz eines wesentlichen Lieferanten / Abnehmers.

## Dokumentation

```yaml
fall-id: FP-2026-0001
stichtag-pruefung: 2026-05-20
ausloeser:
  typ: hinweis-steuerberater  # hinweis-steuerberater / hinweis-wp / eigene-feststellung-bilanz / liquiditaetsengpass / gesellschafterhinweis / eigene-sorge / externes-ereignis
  datum: 2026-05-15
  hinweisgeber: Steuerberater Mueller, Kanzlei XYZ
  mitteilungsform: schriftlich  # schriftlich / muendlich / e-mail
  wortlaut: |
    "Nach Aufstellung des Jahresabschlusses 2025 ergibt sich ein negatives 
    Eigenkapital von 82.000 EUR. Wir weisen Sie nach § 102 StaRUG auf die 
    Pflicht zur Pruefung einer Fortbestehensprognose nach § 19 Abs. 2 InsO 
    hin."
  konkrete-anhaltspunkte:
    - Eigenkapital negativ 82.000 EUR Stichtag 31.12.2025
    - SuSa weist Lieferantenverbindlichkeiten 410.000 EUR (Vorjahr 180.000)
    - Sozialversicherungsbeitraege drei Monate offen 45.000 EUR
  reaktion-geschaeftsfuehrung:
    erste-reaktion-am: 2026-05-20
    schritte:
      - Beauftragung Erstellung Fortbestehensprognose
      - Aktivierung Plugin fortbestehensprognose
      - Termin mit Insolvenzanwalt vereinbart fuer 2026-05-27 als Sicherheit
```

## Pflichthinweis Frist

Mit Eintritt der **Insolvenzreife** (Zahlungsunfaehigkeit § 17 oder Ueberschuldung § 19 InsO) beginnen die Antragsfristen des § 15a InsO. **Die Fortbestehensprognose ist nicht zu verwechseln mit dieser Frist** — sie ist die Pruefung **ob** Ueberschuldung trotz negativen Bilanzbildes verneint werden kann.

- Frist Zahlungsunfaehigkeit: **drei Wochen** (§ 15a Abs. 1 S. 2 InsO).
- Frist Ueberschuldung: **sechs Wochen** (§ 15a Abs. 1 S. 2 InsO seit SanInsFoG 2021).

Im Zweifel **vor Ablauf der Frist** Insolvenzanwalt zu Rate ziehen.

## Ausgabe

- `ausloesendes-ereignis.yaml` mit allen Pflichtfeldern.
- Erste Risikobewertung (gruen / gelb / rot).
- Empfehlung: bei rot direkt zu `wenn-prognose-negativ-naechste-schritte` und Insolvenzanwalt einschalten — diese Pruefung kann fortgesetzt werden aber nicht ohne anwaltliche Begleitung.
