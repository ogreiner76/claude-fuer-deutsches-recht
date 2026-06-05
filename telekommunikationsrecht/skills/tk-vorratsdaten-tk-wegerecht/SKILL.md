---
name: tk-vorratsdaten-tk-wegerecht
description: "Tk Vorratsdaten Speicherung Eugh Bverfg, Tk Wegerecht Oeffentliche Wege: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output."
---

# Tk Vorratsdaten Speicherung Eugh Bverfg, Tk Wegerecht Oeffentliche Wege

## Arbeitsbereich

Dieser Skill bündelt **Tk Vorratsdaten Speicherung Eugh Bverfg, Tk Wegerecht Oeffentliche Wege** zu einem konkreten Arbeitsgang. Starte mit dem Modul, das die Tatsachen der Akte trägt; weitere Module nur hinzunehmen, wenn sie dieselbe Frist, Zuständigkeit, Beweislast oder denselben Output betreffen.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-vorratsdaten-speicherung-eugh-bverfg` | Vorratsdatenspeicherung, Quick Freeze, Sicherheitsbehördenanfragen und EuGH/BVerfG-Linie live prüfen. |
| `tk-wegerecht-oeffentliche-wege` | Wegerecht, Mitverlegung, Baustellenkoordination, Zustimmung, Wiederherstellung und Streit mit Straßenbaulastträgern. |

## Arbeitsweg

Für **Tk Vorratsdaten Speicherung Eugh Bverfg, Tk Wegerecht Oeffentliche Wege** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `telekommunikationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `tk-vorratsdaten-speicherung-eugh-bverfg`

**Fokus:** Vorratsdatenspeicherung, Quick Freeze, Sicherheitsbehördenanfragen und EuGH/BVerfG-Linie live prüfen.

# Vorratsdaten und Speicherpflichten

## Einsatz

Für Provider und Betroffene bei Speicher-/Auskunftspflichten.

## Norm- und Quellenanker

TKG/TTDSG/TDDDG; DSGVO; GRCh; GG; EuGH/BVerfG nur verifiziert zitieren.

## Arbeitsfragen

1. Welche Pflicht oder Anfrage liegt vor?
2. Welche Datenart und Eingriffsintensität?
3. Welche aktuelle EuGH/BVerfG-Rechtsprechung ist einschlägig?

## Output

Speicherpflichten-Memo und Behördenantwort.

## Red Flags

- alte Vorratsdatenlage verwendet
- Bestandsdaten/Verkehrsdaten verwechselt
- Richtervorbehalt ungeprüft

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-wegerecht-oeffentliche-wege`

**Fokus:** Wegerecht, Mitverlegung, Baustellenkoordination, Zustimmung, Wiederherstellung und Streit mit Straßenbaulastträgern.

# Wegerecht für öffentliche Wege

## Einsatz

Für Netzbau auf öffentlichen Wegen.

## Norm- und Quellenanker

TKG Wegerechte live prüfen; Straßenrecht Bund/Länder; VwVfG/VwGO.

## Arbeitsfragen

1. Welche Straße/Fläche und welcher Träger?
2. Welche Zustimmung/Anzeige?
3. Welche Nebenbestimmungen und Wiederherstellungspflichten?

## Output

Wegerechtsantrag, Nebenbestimmungscheck und Bauzeitenplan.

## Red Flags

- falscher Straßenbaulastträger
- kommunale Sondernutzung überdehnt
- Wiederherstellungskosten ungeklärt

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
