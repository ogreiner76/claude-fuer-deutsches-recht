---
name: rentencheck-ein-steuer-krankenversicherung
description: "Nutze dies bei Rentencheck Ein Jahr Vorher, Steuer Krankenversicherung Pflegeversicherung Rente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt."
---

# Rentencheck Ein Jahr Vorher, Steuer Krankenversicherung Pflegeversicherung Rente

## Arbeitsbereich

Dieser Arbeitsbereich führt die Teilfragen zu **Rentencheck Ein Jahr Vorher, Steuer Krankenversicherung Pflegeversicherung Rente** in einem handhabbaren Prüfpfad zusammen. Beginne mit dem Modul, das die Akte wirklich trägt; kombiniere weitere Module nur, wenn Frist, Zuständigkeit, Beweislast oder Output dadurch konkret besser werden.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `rentencheck-ein-jahr-vorher` | Rentencheck ein Jahr vorher: Antragstiming, letzte Korrekturen, Arbeitgeber, Krankenkasse, Steuer, Ausland und Auszahlung. |
| `steuer-krankenversicherung-pflegeversicherung-rente` | Steuer, Kranken- und Pflegeversicherung der Rentner: KVdR, freiwillige Versicherung, PKV, Beitragszuschuss, Ausland und Nettorente. |

## Arbeitsweg

Für **Rentencheck Ein Jahr Vorher, Steuer Krankenversicherung Pflegeversicherung Rente** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `rentenpruefer` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `rentencheck-ein-jahr-vorher`

**Fokus:** Rentencheck ein Jahr vorher: Antragstiming, letzte Korrekturen, Arbeitgeber, Krankenkasse, Steuer, Ausland und Auszahlung.

# rentencheck-ein-jahr-vorher

## Aufgabe

Der operative Endspurt vor Rentenbeginn.

## Pflichtfragen

- Welches Rentensystem oder welcher Träger ist betroffen: DRV, Knappschaft, Versorgungswerk, Zusatzversorgung, ausländischer Träger oder Mischfall?
- Gibt es einen Bescheid, eine Renteninformation, eine Rentenauskunft, einen Versicherungsverlauf oder nur Einzelunterlagen?
- Welche Frist, welches Datum, welcher Zeitraum und welches konkrete Ziel sind entscheidend?
- Welche Unterlagen liegen bereits vor und welche Nachweise fehlen noch?

## Spezifischer Intake

Rentenbeginn, Unterlagen, Arbeitsende, Krankenkasse, Konto, Ausland, offene Bescheide.

## Prüfprogramm

1. **Systemroute klären:** gesetzliche Rente, Versorgungswerk, Ausland, Nachversicherung oder Rechtsbehelf trennen.
2. **Tatsachen sichern:** Zeiträume monatsgenau, Träger, Bescheide, Nachweise, Übersetzungen und Zustellungen erfassen.
3. **Norm- und Quellencheck:** SGB VI, SGB X, SGG, FRG, DRV-Informationen, Sozialversicherungsabkommen oder konkrete Satzung live prüfen.
4. **Beweiswert bewerten:** Original, beglaubigte Kopie, ausländische Urkunde, Arbeitsbuch, Zeuge, Arbeitgeberarchiv, Behördenauskunft.
5. **Handlung ableiten:** Antrag, Kontenklärung, Nachreichung, Widerspruch, Klage, Vergleich, Nachfassschreiben oder Mandantenbrief.

## Output

Zwölf-Monats-Checkliste.

## Qualitäts-Hardening

- Keine nicht überprüfbaren Fundstellen, keine privaten Datenbankzitate, keine Kommentar- oder Aufsatzblindzitate.
- Bei ausländischen Zeiten nie pauschal anerkennen: EU/EWR/Schweiz, Abkommensstaat, vertragsloser Drittstaat und FRG strikt trennen.
- Bei Versorgungswerken immer Beruf, Kammer, Bundesland und aktuelle Satzung verlangen.
- Zahlen, Fristen und Altersgrenzen nur mit aktueller Quelle oder als ausdrücklich zu prüfenden Punkt ausgeben.

## 2. `steuer-krankenversicherung-pflegeversicherung-rente`

**Fokus:** Steuer, Kranken- und Pflegeversicherung der Rentner: KVdR, freiwillige Versicherung, PKV, Beitragszuschuss, Ausland und Nettorente.

# steuer-krankenversicherung-pflegeversicherung-rente

## Aufgabe

Rechnet nicht nur Bruttorente, sondern die praktische Auszahlungsperspektive.

## Pflichtfragen

- Welches Rentensystem oder welcher Träger ist betroffen: DRV, Knappschaft, Versorgungswerk, Zusatzversorgung, ausländischer Träger oder Mischfall?
- Gibt es einen Bescheid, eine Renteninformation, eine Rentenauskunft, einen Versicherungsverlauf oder nur Einzelunterlagen?
- Welche Frist, welches Datum, welcher Zeitraum und welches konkrete Ziel sind entscheidend?
- Welche Unterlagen liegen bereits vor und welche Nachweise fehlen noch?

## Spezifischer Intake

Krankenkasse, Vorversicherungszeiten, weitere Einkünfte, Ausland, Versorgungsbezüge, Steuerstatus.

## Prüfprogramm

1. **Systemroute klären:** gesetzliche Rente, Versorgungswerk, Ausland, Nachversicherung oder Rechtsbehelf trennen.
2. **Tatsachen sichern:** Zeiträume monatsgenau, Träger, Bescheide, Nachweise, Übersetzungen und Zustellungen erfassen.
3. **Norm- und Quellencheck:** SGB VI, SGB X, SGG, FRG, DRV-Informationen, Sozialversicherungsabkommen oder konkrete Satzung live prüfen.
4. **Beweiswert bewerten:** Original, beglaubigte Kopie, ausländische Urkunde, Arbeitsbuch, Zeuge, Arbeitgeberarchiv, Behördenauskunft.
5. **Handlung ableiten:** Antrag, Kontenklärung, Nachreichung, Widerspruch, Klage, Vergleich, Nachfassschreiben oder Mandantenbrief.

## Output

Netto-Checkliste und Warnhinweise.

## Qualitäts-Hardening

- Keine nicht überprüfbaren Fundstellen, keine privaten Datenbankzitate, keine Kommentar- oder Aufsatzblindzitate.
- Bei ausländischen Zeiten nie pauschal anerkennen: EU/EWR/Schweiz, Abkommensstaat, vertragsloser Drittstaat und FRG strikt trennen.
- Bei Versorgungswerken immer Beruf, Kammer, Bundesland und aktuelle Satzung verlangen.
- Zahlen, Fristen und Altersgrenzen nur mit aktueller Quelle oder als ausdrücklich zu prüfenden Punkt ausgeben.
