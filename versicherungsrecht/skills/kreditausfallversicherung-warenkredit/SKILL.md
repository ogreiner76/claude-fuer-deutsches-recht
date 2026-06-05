---
name: kreditausfallversicherung-warenkredit
description: "Nutze dies, wenn Kreditausfallversicherung Warenkredit Forderungsausfall, Kreditversicherung Obliegenheiten Limit Prüfung, Lebensversicherung Bezugsrecht Widerruf Aenderung im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?."
---

# Kreditausfallversicherung Warenkredit Forderungsausfall, Kreditversicherung Obliegenheiten Limit Prüfung, Lebensversicherung Bezugsrecht Widerruf Aenderung

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `kreditausfallversicherung-warenkredit-forderungsausfall` | Kreditausfall-/Warenkreditversicherung: Limit, Forderungsausfall, Insolvenztatbestand, Obliegenheiten, Selbstbehalt, Factoring-Schnittstelle und Regress. |
| `kreditversicherung-obliegenheiten-limit-pruefung` | Kreditversicherung im laufenden Debitorenmanagement: Limite, Überfälligkeiten, Risikoinformationen, Inkassostart, Meldungen und Streit um Leistungsfreiheit. |
| `lebensversicherung-bezugsrecht-widerruf-aenderung` | Bezugsrechte in Lebens- und Rentenversicherung: widerruflich/unwiderruflich, Scheidung, Erbfall, Sicherungsabtretung, Insolvenz, Änderungserklärung und Auszahlungsstreit. |

## Arbeitsweg

Für **Kreditausfallversicherung Warenkredit Forderungsausfall, Kreditversicherung Obliegenheiten Limit Prüfung, Lebensversicherung Bezugsrecht Widerruf Aenderung** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `versicherungsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `kreditausfallversicherung-warenkredit-forderungsausfall`

**Fokus:** Kreditausfall-/Warenkreditversicherung: Limit, Forderungsausfall, Insolvenztatbestand, Obliegenheiten, Selbstbehalt, Factoring-Schnittstelle und Regress.

# Kreditausfallversicherung und Warenkreditversicherung

## Einsatz

Für Lieferanten, die Zahlungsausfälle über Kreditversicherung absichern und bei Insolvenz des Kunden Deckung brauchen.

## Norm- und Quellenanker

VVG Schadenversicherung; AVB Warenkredit; InsO; HGB; Factoringvertrag.

## Arbeitsfragen

1. Welches Kreditlimit galt wann und für welchen Schuldner?
2. Ist der versicherte Forderungsausfall eingetreten?
3. Wurden Melde-, Mahn- und Inkassoobliegenheiten eingehalten?
4. Wie wirken Factoring, Abtretung und Eigentumsvorbehalt?

## Output

Limit-/Forderungsmatrix, Obliegenheitscheck, Insolvenznachweis und Deckungsantrag.

## Red Flags

- Lieferung nach Limitstreichung
- Mahnobliegenheiten verletzt
- Forderung abgetreten
- Ausfalltatbestand nicht erreicht

## Anschluss-Skills

- kreditversicherung-obliegenheiten-limit-pruefung
- restschuldversicherung-widerruf-kopplung-verbraucherdarlehen

## Qualitätsregel

Keine Rechtsprechung aus Modellwissen zitieren. Wenn eine Entscheidung gebraucht wird: Gericht, Entscheidungsform, Datum, Aktenzeichen und frei zugängliche Quelle verifizieren; sonst nur als Prüfpunkt formulieren.

## 2. `kreditversicherung-obliegenheiten-limit-pruefung`

**Fokus:** Kreditversicherung im laufenden Debitorenmanagement: Limite, Überfälligkeiten, Risikoinformationen, Inkassostart, Meldungen und Streit um Leistungsfreiheit.

# Kreditversicherung: Limitprüfung und Obliegenheiten

## Einsatz

Der Skill eignet sich für Unternehmen, die ihr Debitorenportfolio versichert führen und nicht durch Prozessfehler Deckung verlieren wollen.

## Norm- und Quellenanker

VVG §§ 28, 31; AVB Kreditversicherung; InsO; BGB/HGB.

## Arbeitsfragen

1. Welche Limite sind aktiv, reduziert, gestrichen oder still?
2. Welche Überfälligkeiten lösen Meldung oder Lieferstopp aus?
3. Welche Informationen über Bonität/Insolvenz lagen vor?
4. Welche Dokumentation braucht der Versicherer?

## Output

Debitoren-Ampel, Obliegenheitskalender, Lieferfreigabe-Check und Schadenanzeige.

## Red Flags

- Excel-Limitliste veraltet
- Bonitätswarnung nicht gemeldet
- Weiterlieferung trotz Ausfallanzeichen
- Inkasso ohne Versichererabstimmung

## Anschluss-Skills

- kreditausfallversicherung-warenkredit-forderungsausfall
- vvg-obliegenheit-28-quotelung-kausalitaet

## Qualitätsregel

Keine Rechtsprechung aus Modellwissen zitieren. Wenn eine Entscheidung gebraucht wird: Gericht, Entscheidungsform, Datum, Aktenzeichen und frei zugängliche Quelle verifizieren; sonst nur als Prüfpunkt formulieren.

## 3. `lebensversicherung-bezugsrecht-widerruf-aenderung`

**Fokus:** Bezugsrechte in Lebens- und Rentenversicherung: widerruflich/unwiderruflich, Scheidung, Erbfall, Sicherungsabtretung, Insolvenz, Änderungserklärung und Auszahlungsstreit.

# Lebensversicherung: Bezugsrecht, Widerruf, Änderung

## Einsatz

Der Skill klärt, wer bei Tod oder Ablauf wirklich Geld bekommt und wie Änderungen sauber dokumentiert werden.

## Norm- und Quellenanker

VVG §§ 150–171, besonders §§ 159, 160; BGB Erbrecht/Abtretung; InsO; FamFG/Nachlass.

## Arbeitsfragen

1. Ist das Bezugsrecht widerruflich oder unwiderruflich?
2. Wann und in welcher Form wurde geändert?
3. Gibt es Scheidung, Erbfall, Pfändung, Abtretung oder Insolvenz?
4. Welche Auszahlungsunterlagen fordert der Versicherer?

## Output

Bezugsrechtsgutachten, Unterlagenliste, Auszahlungsschreiben und Streitrisiko.

## Red Flags

- alte Ehegattenbezeichnung
- Sicherungsabtretung an Bank
- Erben verwechseln Nachlass und Bezugsrecht
- unwirksame Änderung kurz vor Tod

## Anschluss-Skills

- lebensversicherung-rueckkaufswert-abschlusskosten-widerspruch
- subrogation-regress-86-vvg

## Qualitätsregel

Keine Rechtsprechung aus Modellwissen zitieren. Wenn eine Entscheidung gebraucht wird: Gericht, Entscheidungsform, Datum, Aktenzeichen und frei zugängliche Quelle verifizieren; sonst nur als Prüfpunkt formulieren.
