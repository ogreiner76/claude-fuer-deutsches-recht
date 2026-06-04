---
name: bgb-zpo-forderungsnormcheck
description: "BGB/ZPO-Forderungsnormcheck: prüft Anspruch, Fälligkeit, Verzug, Zinsen, Verjährung, Mahnverfahren, Klage, Zustellung demnächst, Titel, Klausel, Zustellung und Vollstreckung anhand aktueller Normen."
---

# BGB/ZPO-Forderungsnormcheck

## Zweck

Dieser Skill ist der harte Gatekeeper vor Mahnung, Mahnbescheid, Zahlungsklage oder Vollstreckung. Er fragt nicht nur “besteht die Forderung?”, sondern: Ist sie fällig, beweisbar, nicht verjährt, prozessual richtig geltend gemacht und vollstreckbar?

## Prüfreihenfolge

1. Anspruchsgrundlage und Schuldner bestimmen.
2. Fälligkeit, Einreden, Zurückbehaltungsrechte und Verzug prüfen.
3. Zinsen und Nebenforderungen nach §§ 286, 288 BGB trennen.
4. Verjährung nach §§ 195, 199, 203, 204, 212 BGB prüfen.
5. Rechtsverfolgungsakt wählen: Mahnbescheid, Klage, Urkundenprozess, Eilverfahren.
6. ZPO-Durchsetzung prüfen: Zuständigkeit, Klageschrift, Mahnverfahren, Zustellung, Titel, Klausel, Vollstreckung.

## Normen

| Thema | Normen |
| --- | --- |
| Anspruch/Verzug | §§ 194, 241, 280, 286, 288 BGB |
| Verjährung | §§ 195, 199, 203, 204, 212 BGB |
| Zustellung demnächst | § 167 ZPO |
| Klage | §§ 253, 261 ZPO |
| Mahnverfahren | §§ 688-703d ZPO |
| Vollstreckungsvoraussetzungen | §§ 704, 724, 750 ZPO |
| Gerichtsvollzieher/Vermögensauskunft | §§ 753, 802a, 802c ZPO |
| Forderungspfändung | §§ 828, 829, 835 ZPO |

## Output

Erzeuge:

- Forderungsmatrix.
- Beleg- und Lückenliste.
- Verjährungs- und Fristenvermerk.
- Entscheidung: Mahnung, Mahnbescheid, Zahlungsklage, Vergleich, Vollstreckung oder Stop.
- Textbaustein für den nächsten Schritt.

## Referenz

Nutze `references/bgb-zpo-forderungskern.md`.
