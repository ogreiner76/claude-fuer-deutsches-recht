---
name: annahmen-belastbarkeit-plausibilisieren
description: Plausibilisiert die in `annahmen-sammeln-fortfuehrung` gesammelten Annahmen. Pruefraster Konsistenz mit Vergangenheit (BWA SuSa Jahresabschluss) Marktentwicklung (Branche makroekonomisch) Konsistenz untereinander (Umsatz vs Material vs Personal) und Risikokategorisierung. Plausibilitaetsband fuer jede Annahme. Erzeugt Plausibilitaetsprotokoll. Annahmen mit niedriger Belastbarkeit werden als Modellannahme markiert und im Sensitivitaetsszenario gegengerechnet.
---

# Annahmen plausibilisieren

## Pruefraster pro Annahme

### 1. Vergangenheits-Vergleich

- Stimmt die Annahme mit den **letzten drei Jahren** der BWA / SuSa / Jahresabschluss ueberein?
- Bei Abweichung: ist die Veraenderung **konkret begruendet** (neuer Kunde Standortschliessung Tariferhoehung)?
- Bei stark abweichender Optimismus-Annahme **ohne neuen Anlass**: Reduktion auf historisches Niveau im Plausi-Szenario.

### 2. Markt- und Branchenentwicklung

- **Branchenindex** vorhanden? (z. B. ifo Geschaeftsklimaindex DESTATIS Branchenkennzahlen).
- **Auftragsbestand der Branche** rueckschau.
- **Makro-Indikatoren** Konjunktur Zinsen Energiepreise.

### 3. Interne Konsistenz

- Umsatz steigt, aber Materialkosten bleiben gleich? Konsistenz pruefen.
- Personalkosten steigen, aber Personalstand sinkt? Begruendung erforderlich (Tariferhoehung + Reduzierung gleichzeitig).
- Working Capital verbessert sich rapide? Begruendung notwendig.

### 4. Belegbarkeit der Massnahmen

- Sanierungsmassnahmen mit Effekt — ist der Effekt **belegt** (Vergleichswerte historisch Kostenrechnung)?
- Zeitplan realistisch (z. B. Standortschliessung in 60 Tagen)?
- Einmalkosten realistisch erfasst?

### 5. Drittvereinbarungen

- Patronatserklaerungen / Comfortletter: bereits unterzeichnet oder nur in Verhandlung?
- Gesellschafterdarlehen mit Rangruecktritt: notarielle Urkunde vorhanden?
- Bankenzusage: schriftlich oder mundlich?

## Plausibilitaetsband pro Annahme

```yaml
plausibilisierung:
  - annahme-id: umsatz-hauptsegment
    band: realistisch  # konservativ / realistisch / ambitioniert / nicht-belastbar
    begruendung: |
      Auftragsbestand bis 09/2026 belegt; ab 10/2026 Modellfortschreibung
      auf Basis Vorjahr +3%
    risiko: mittel
    sensitivitaet-szenario:
      negativ: 10% Umsatzrueckgang ab 10/2026
      effekt-eur: -190000 (kumuliert)
      
  - annahme-id: kostensenkung-standort
    band: ambitioniert
    begruendung: |
      Kuendigung Standortmietvertrag erfordert 9-Monats-Kuendigungsfrist;
      Schliessung bis 08/2026 nur moeglich wenn Mieter Aufhebung akzeptiert.
      Aktuell in Verhandlung — nicht belegt.
    risiko: hoch
    sensitivitaet-szenario:
      negativ: Schliessung gelingt nicht im Planhorizont
      effekt-eur: 50000 monatliche Mehrkosten

  - annahme-id: bankenzusage-erhoehung-kreditlinie
    band: nicht-belastbar
    begruendung: |
      Verhandlung mit Bank laeuft. Bisher keine schriftliche Zusage.
      Bank verweist auf laufendes Rating-Verfahren.
    risiko: hoch
    sensitivitaet-szenario:
      negativ: Kreditlinie wird nicht erhoeht
      effekt-eur: keine zusaetzliche Liquiditaet 80000 EUR
```

## Konservativer Massstab

Eine Fortbestehensprognose ist nicht der Ort fuer Optimismus. **IDW S 11** und **BGH-Rspr.** verlangen einen vorsichtigen objektiven Massstab.

- Bei Zweifeln: **konservative** Annahmen waehlen.
- Wenn eine Annahme **ambitioniert** oder **nicht-belastbar** ist und entscheidend fuer das Prognoseergebnis ist: das Ergebnis ist **nicht verwertbar** als positive Fortbestehensprognose. Massnahme: entweder Belegbarkeit nachholen oder Annahme entfernen.

## Sensitivitaetsszenarien

```yaml
szenarien:
  basisszenario:
    annahmen: alle wie in annahmen.yaml
    ergebnis-12-monate-liquiditaet: positiv
    bemerkung: Plan-Szenario
    
  negativ-szenario:
    annahmen: alle ambitioniert-Annahmen reduziert auf konservativ
    ergebnis-12-monate-liquiditaet: knapp positiv  # vor Massnahmen
    bemerkung: Risiko-Szenario; bei Eintritt sind Zusatzmassnahmen erforderlich
    
  stress-szenario:
    annahmen: zusaetzlich Wegfall Top-Kunde
    ergebnis-12-monate-liquiditaet: negativ
    bemerkung: Reines Stress-Szenario; in der Plausibilisierung
      als unwahrscheinlich eingeschaetzt
```

## Sonderfaelle

### Stille Reserven die zur Plausibilisierung herangezogen werden

Wenn der Status stille Reserven enthaelt (Skill `bilanzieller-status-aufnehmen`) muss die Liquiditaet auch realistisch ueber Verkauf erzielbar sein:

- Verkehrswert-Gutachten vorhanden?
- Realistisch verkaufbar im Planhorizont?
- Auswirkung auf den Betrieb (z. B. Verkauf einer Maschine fuehrt zu Produktionsausfall)?

### Comfortletter

- **Weicher Comfortletter** (Best Effort) ist im Status **nicht** zu beruecksichtigen.
- **Harte externe Patronatserklaerung** mit Forderungsverzicht im Insolvenzfall ist beruecksichtigungsfaehig — siehe Skill `patronatserklaerung-extern-hart-erzeugen`.

## Ausgabe

- `plausibilisierung.md` mit jeder Annahme bewertet (Band Risiko Sensitivitaet).
- Drei Szenarien (Basis Negativ Stress) mit Endergebnis.
- Empfehlung: bei mehr als zwei nicht-belastbaren oder ambitionierten Annahmen die das Ergebnis tragen ist die Prognose **nicht positiv** zu werten.
- Liste konkreter Massnahmen zur Verbesserung der Belastbarkeit (Belegnachholung Verhandlungsabschluss Drittvereinbarung).
