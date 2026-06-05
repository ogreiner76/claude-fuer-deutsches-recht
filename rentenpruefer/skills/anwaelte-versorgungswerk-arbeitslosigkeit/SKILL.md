---
name: anwaelte-versorgungswerk-arbeitslosigkeit
description: "Nutze dies bei Anwaelte Versorgungswerk Spezial, Arbeitslosigkeit Bürgergeld Und Rente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt."
---

# Anwälte Versorgungswerk Spezial, Arbeitslosigkeit Buergergeld Und Rente

## Arbeitsbereich

Dieser Arbeitsbereich führt die Teilfragen zu **Anwälte Versorgungswerk Spezial, Arbeitslosigkeit Buergergeld Und Rente** in einem handhabbaren Prüfpfad zusammen. Beginne mit dem Modul, das die Akte wirklich trägt; kombiniere weitere Module nur, wenn Frist, Zuständigkeit, Beweislast oder Output dadurch konkret besser werden.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `anwaelte-versorgungswerk-spezial` | Anwälte und Versorgungswerk: Zulassung, Syndikus, Kanzleiwechsel, Befreiung, Nachversicherung und parallele DRV-Zeiten. |
| `arbeitslosigkeit-buergergeld-und-rente` | Arbeitslosigkeit, Bürgergeld und Rente: Meldungen, Pflichtbeiträge, Anrechnungszeiten, Sperrzeiten und Rentenbeginn. |

## Arbeitsweg

Für **Anwälte Versorgungswerk Spezial, Arbeitslosigkeit Buergergeld Und Rente** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `rentenpruefer` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `anwaelte-versorgungswerk-spezial`

**Fokus:** Anwälte und Versorgungswerk: Zulassung, Syndikus, Kanzleiwechsel, Befreiung, Nachversicherung und parallele DRV-Zeiten.

# anwaelte-versorgungswerk-spezial

## Aufgabe

Spezialroute für anwaltliche Erwerbsbiografien mit Kammer- und Tätigkeitswechseln.

## Pflichtfragen

- Welches Rentensystem oder welcher Träger ist betroffen: DRV, Knappschaft, Versorgungswerk, Zusatzversorgung, ausländischer Träger oder Mischfall?
- Gibt es einen Bescheid, eine Renteninformation, eine Rentenauskunft, einen Versicherungsverlauf oder nur Einzelunterlagen?
- Welche Frist, welches Datum, welcher Zeitraum und welches konkrete Ziel sind entscheidend?
- Welche Unterlagen liegen bereits vor und welche Nachweise fehlen noch?

## Spezifischer Intake

Zulassung, Kammer, Beschäftigung, Syndikusbescheid, Befreiungsbescheide, DRV-Verlauf.

## Prüfprogramm

1. **Systemroute klären:** gesetzliche Rente, Versorgungswerk, Ausland, Nachversicherung oder Rechtsbehelf trennen.
2. **Tatsachen sichern:** Zeiträume monatsgenau, Träger, Bescheide, Nachweise, Übersetzungen und Zustellungen erfassen.
3. **Norm- und Quellencheck:** SGB VI, SGB X, SGG, FRG, DRV-Informationen, Sozialversicherungsabkommen oder konkrete Satzung live prüfen.
4. **Beweiswert bewerten:** Original, beglaubigte Kopie, ausländische Urkunde, Arbeitsbuch, Zeuge, Arbeitgeberarchiv, Behördenauskunft.
5. **Handlung ableiten:** Antrag, Kontenklärung, Nachreichung, Widerspruch, Klage, Vergleich, Nachfassschreiben oder Mandantenbrief.

## Output

Anwaltsversorgungswerk-Check.

## Qualitäts-Hardening

- Keine nicht überprüfbaren Fundstellen, keine privaten Datenbankzitate, keine Kommentar- oder Aufsatzblindzitate.
- Bei ausländischen Zeiten nie pauschal anerkennen: EU/EWR/Schweiz, Abkommensstaat, vertragsloser Drittstaat und FRG strikt trennen.
- Bei Versorgungswerken immer Beruf, Kammer, Bundesland und aktuelle Satzung verlangen.
- Zahlen, Fristen und Altersgrenzen nur mit aktueller Quelle oder als ausdrücklich zu prüfenden Punkt ausgeben.

## 2. `arbeitslosigkeit-buergergeld-und-rente`

**Fokus:** Arbeitslosigkeit, Bürgergeld und Rente: Meldungen, Pflichtbeiträge, Anrechnungszeiten, Sperrzeiten und Rentenbeginn.

# arbeitslosigkeit-buergergeld-und-rente

## Aufgabe

Prüft, was Arbeitslosigkeitsphasen für Wartezeit und Rentenhöhe bedeuten.

## Pflichtfragen

- Welches Rentensystem oder welcher Träger ist betroffen: DRV, Knappschaft, Versorgungswerk, Zusatzversorgung, ausländischer Träger oder Mischfall?
- Gibt es einen Bescheid, eine Renteninformation, eine Rentenauskunft, einen Versicherungsverlauf oder nur Einzelunterlagen?
- Welche Frist, welches Datum, welcher Zeitraum und welches konkrete Ziel sind entscheidend?
- Welche Unterlagen liegen bereits vor und welche Nachweise fehlen noch?

## Spezifischer Intake

ALG-Zeiten, Bürgergeld, Sperrzeit, Meldungen, Bescheide, Versicherungsverlauf.

## Prüfprogramm

1. **Systemroute klären:** gesetzliche Rente, Versorgungswerk, Ausland, Nachversicherung oder Rechtsbehelf trennen.
2. **Tatsachen sichern:** Zeiträume monatsgenau, Träger, Bescheide, Nachweise, Übersetzungen und Zustellungen erfassen.
3. **Norm- und Quellencheck:** SGB VI, SGB X, SGG, FRG, DRV-Informationen, Sozialversicherungsabkommen oder konkrete Satzung live prüfen.
4. **Beweiswert bewerten:** Original, beglaubigte Kopie, ausländische Urkunde, Arbeitsbuch, Zeuge, Arbeitgeberarchiv, Behördenauskunft.
5. **Handlung ableiten:** Antrag, Kontenklärung, Nachreichung, Widerspruch, Klage, Vergleich, Nachfassschreiben oder Mandantenbrief.

## Output

Zeitenbewertung und Korrekturanfragen.

## Qualitäts-Hardening

- Keine nicht überprüfbaren Fundstellen, keine privaten Datenbankzitate, keine Kommentar- oder Aufsatzblindzitate.
- Bei ausländischen Zeiten nie pauschal anerkennen: EU/EWR/Schweiz, Abkommensstaat, vertragsloser Drittstaat und FRG strikt trennen.
- Bei Versorgungswerken immer Beruf, Kammer, Bundesland und aktuelle Satzung verlangen.
- Zahlen, Fristen und Altersgrenzen nur mit aktueller Quelle oder als ausdrücklich zu prüfenden Punkt ausgeben.
