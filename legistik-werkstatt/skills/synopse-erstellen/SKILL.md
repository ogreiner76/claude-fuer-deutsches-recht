---
name: synopse-erstellen
description: "Synopse als Tabelle mit drei Spalten bisheriges Recht neues Recht Aenderungsbefehl. Pro geaendertem Paragrafen eine Zeile oder ein Block. Pro Stammgesetz eine eigene Synopsen-Tabelle. Lesefassung ergaenzend in einer eigenen Datei. Hilfreich fuer Ressortabstimmung Bundestag Bundesrat. Aufbau Spalten gleich breit gut druckbar A4 quer oder Landscape A3 wenn lange Saetze. Endet mit Synopsen-Tabelle als Markdown plus DOCX-Vorlage. Anschluss `lesefassung-konsolidiert`."
---

# Synopse erstellen

> Drei Spalten: vorher, nachher, Aenderungsbefehl. Hilft Allen.

## Aufbau einer Synopse

### Tabelle (Format Markdown / DOCX / PDF Landscape)

| Bisheriges Recht | Neues Recht | Aenderungsbefehl |
|---|---|---|
| Paragraf 33 HGB (alte Fassung) Wortlaut ... | Paragraf 33 HGB (neue Fassung) Wortlaut ... | Paragraf 33 wird wie folgt gefasst ... |

### Pro Stammgesetz eine eigene Datei

- Synopse_HGB.md
- Synopse_ZPO.md
- Synopse_FamFG.md

### Spaltenbreite

DOCX: ca. 33 Prozent / 33 Prozent / 34 Prozent. Bei langen Saetzen A3 Landscape oder DIN A4 mit kleiner Schrift.

## Kennzeichnung von Aenderungen

- Eingefuegte Worte: **fett** oder Doppelunterstreichung
- Gestrichene Worte: ~~Durchstreichung~~ oder kursiv mit Hinweis "entfaellt"
- Bei voelliger Neufassung: Spalte "Bisheriges Recht" "Aufgehoben (alte Fassung in Anlage)"

## Lesefassung in separater Datei

Synopse ist gut fuer den Vergleich. Eine **Lesefassung** zeigt die geaenderte Norm in einer einheitlich gelesenen Fassung.

Beispiel "Lesefassung_HGB_Paragraf_33.md" - das ist der Paragraf, wie er nach Inkrafttreten lautet.

## Anschluss

`lesefassung-konsolidiert`.
