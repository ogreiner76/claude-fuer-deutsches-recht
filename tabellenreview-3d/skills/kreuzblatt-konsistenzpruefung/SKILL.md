---
name: kreuzblatt-konsistenzpruefung
description: "Prueft die dritte Wuerfel-Dimension auf innere Konsistenz — laeuft NACH `review-durchfuehren` ueber alle Arbeitsblaetter und sucht Widersprueche zwischen Perspektiven (z. B. ein Vertrag rechtlich gruen aber datenschutzrechtlich rot; ein Vertragsvolumen das wirtschaftlich gross aber steuerlich nicht erfasst ist; ein Service-Level betrieblich passabel aber rechtlich unwirksam). Erzeugt `widerspruchsbericht.md` mit pro Widerspruch der Zeile dem widersprechenden Arbeitsblatt der Spalte und der Konflikt-Klassifikation (echter Widerspruch / legitime perspektivische Abweichung / Datenfehler)."
---

# /tabellenreview-3d:kreuzblatt-konsistenzpruefung

## Zweck

Eine Zelle die rechtlich gruen aber datenschutzrechtlich rot ist ist nicht automatisch ein Fehler — sie ist eine perspektivische Abweichung. Oft aber ist sie ein Fehler: dieselbe Tatsache wurde in zwei Arbeitsblaettern unterschiedlich erfasst. Dieser Skill findet beides.

## Methodik

1. **Achsen-Match:** dieselbe Zeile dieselbe Spalte aber unterschiedliches Arbeitsblatt: vergleichen.
2. **Faktischer Widerspruch:** beide Arbeitsblaetter haben das Vertragsdatum extrahiert; das eine sagt 2021-03-15, das andere 2021-03-25. Das ist ein Datenfehler — Pruefer-Flag.
3. **Perspektivischer Widerspruch:** ein Arbeitsblatt sagt 'wirksam' das andere 'unwirksam'. Wenn beide Arbeitsblaetter dieselbe Norm benutzen ist es Datenfehler; wenn unterschiedliche Normen (Recht vs Steuer) ist es legitime Abweichung — als `legitim` markieren.
4. **Ampel-Inkonsistenz:** dieselbe Zeile in einem Arbeitsblatt rot in einem gelb in einem gruen — Konsolidierungsempfehlung an `risikoampel-aggregation`.
5. **Norm-Bezugs-Widerspruch:** ein Arbeitsblatt verweist auf BGB Paragraph 307, ein anderes auf BGB Paragraph 305c bei derselben Klausel. Beides moeglich — Pruefer-Hinweis.

## Konflikt-Klassifikation

- **echter Widerspruch:** beide Antworten beanspruchen dieselbe Tatsache aber unterscheiden sich. Pruefer-Flag rot.
- **legitime perspektivische Abweichung:** Arbeitsblaetter haben unterschiedliche Pruefmassstaebe. Vermerk gelb.
- **Datenfehler:** OCR-Konfidenz schwach in einem der Arbeitsblaetter — Re-Run dieser Zelle.
- **Klassifikationsfehler:** Dokumenttyp falsch erkannt — Zeile neu klassifizieren.

## Ausgabe

- `widerspruchsbericht.md` mit pro Widerspruch:
  - Zeile (Dokument)
  - Spalte (Datenpunkt)
  - Arbeitsblatt-A und Arbeitsblatt-B mit jeweiliger Antwort
  - Konflikt-Klassifikation
  - Empfohlene Aktion (Re-Run / Pruefer / Konsolidierung)

## Beispiele

- **echter Widerspruch:** Kundenvertrag-042. Spalte 'Laufzeit'. Recht: '3 Jahre + 1 Jahr Verlaengerung'. Wirtschaft: '4 Jahre Festlaufzeit'. Echter Widerspruch — Wirtschaft hat den Vertrag verkuerzt gelesen.
- **legitime Abweichung:** Lizenzvertrag-018. Spalte 'Haftung'. Recht: 'unwirksam BGB Paragraph 309 Nr 7'. Steuer: 'irrelevant — Pauschalhaftungs-Aufwand absetzbar'. Legitim — unterschiedliche Pruefmassstaebe.
