---
name: amtlicher-bgb-bt-normcheck
description: "Amtlicher Normcheck für BGB-BT-Fälle: prüft Vertragstypen, Leistungsstörung, AGB, Verbraucherrecht, digitale Produkte, Kauf, Miete, Dienst, Werk, Auftrag, GoA, Bürgschaft, Bereicherung und Delikt gegen die aktuelle BGB-Fassung."
---

# Amtlicher BGB-BT-Normcheck

## Zweck

Dieser Skill verhindert, dass BGB-BT-Fälle mit veralteten Normgruppen oder zu groben Anspruchsformeln gelöst werden. Er zwingt den Fall in die aktuelle BGB-Struktur und trennt Vertragstyp, Anspruchsgrundlage, Rechtsfolge, Frist und Beweis.

## Prüfroute

1. Vertragliche Beziehung bestimmen: Kauf, Miete, Darlehen, Dienst, Werk, Auftrag/Geschäftsbesorgung, Bürgschaft, Vergleich oder Mischvertrag.
2. Gesetzliche Beziehung bestimmen: GoA, Bereicherung, Delikt, Gesamtschuld/Regress.
3. BGB AT als Vorfrage prüfen: Vertragsschluss, Form, Stellvertretung, Anfechtung, Verjährung.
4. Aktuelle Norm live prüfen, wenn sie trägt.
5. ZPO-Durchsetzung prüfen, wenn ein Schriftsatz, Mahnbescheid, Eilantrag oder Beweisverfahren entstehen soll.

## Normlandkarte

| Bereich | Normen | Typischer Output |
| --- | --- | --- |
| Leistungsstörung | §§ 241, 249, 253, 275-304 BGB | Pflichtverletzungs- und Schadensmatrix |
| AGB | §§ 305-310 BGB | Klauselampel |
| Verbraucher/Fernabsatz | §§ 312 ff. BGB | Informations-/Widerrufscheck |
| Digitale Produkte | §§ 327 ff. BGB | Bereitstellungs- und Updateprüfung |
| Kauf | §§ 433-479 BGB | Mängelrechte, Nacherfüllung, Rücktritt, Minderung, Schadensersatz |
| Ware mit digitalen Elementen | §§ 475b, 475c, 476, 477 BGB | Update-, Beweislast- und Abweichungsvereinbarung |
| Miete/Pacht | §§ 535 ff., 581 ff. BGB | Gebrauch, Mangel, Minderung, Kündigung, § 550 BGB |
| Dienst/Behandlung | §§ 611, 611a, 630a ff. BGB | Dienstpflicht, Arbeitnehmerabgrenzung, Behandlungsvertrag |
| Werk/Bau | §§ 631 ff. BGB | Abnahme, Mängelrechte, Kündigung, Vergütung |
| Auftrag/Geschäftsbesorgung | §§ 662 ff., 675 ff. BGB | unentgeltlich/entgeltlich, Geschäftsbesorgung, Zahlungsschnittstelle |
| GoA | §§ 677-687 BGB | berechtigte/unberechtigte/unechte GoA |
| Bürgschaft | §§ 765 ff. BGB | Akzessorietät, Schriftform, Einreden |
| Bereicherung | §§ 812-822 BGB | Leistung/Nichtleistung, Rechtsgrund, Entreicherung |
| Delikt | §§ 823-853 BGB | Rechtsgut, Schutzgesetz, § 826, Verrichtungsgehilfe, Gefährdungsnähe |

## Output

Erzeuge:

- Anspruchslandkarte.
- Normenmatrix mit aktueller Normprüfung.
- Rechtsfolgenbaum.
- Fristen- und Verjährungsmatrix.
- ZPO-Durchsetzungspfad, falls der Nutzer ein Prozessprodukt braucht.

## Referenz

Nutze `references/amtlicher-bgb-bt-normkern.md`.
