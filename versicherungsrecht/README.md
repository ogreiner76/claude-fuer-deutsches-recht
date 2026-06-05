# Versicherungsrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`versicherungsrecht`) | [`versicherungsrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/versicherungsrecht.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

Großes, praxisnahes Versicherungsrecht-Plugin für Deckung, Ablehnung, Vertragsgestaltung, Aufsicht und Prozess. Es ist bewusst nicht nur ein Fachanwalts-Lernplugin, sondern ein Arbeitswerkzeug für Kanzlei, Rechtsabteilung, Versicherungsnehmer, Vermittler und Versicherer.

## Was dieses Plugin gut kann

- Deckungsablehnungen und Leistungsprüfung nach VVG zerlegen.
- Lebensversicherung, BU, PKV, Unfall, Rechtsschutz, Kreditversicherung, D&O, Cyber und Sachversicherung mit eigenen Spezial-Skills prüfen.
- BaFin, Ombudsmann, Klage und Vergleich taktisch voneinander trennen.
- Europäische Aufsicht, IDD, Solvency II, DORA und grenzüberschreitenden Vertrieb einordnen.

## Startlogik

Beginne mit dem allgemeinen Skill. Er fragt Rolle, Ziel, Fristen, Unterlagen, Eskalationsniveau und gewünschten Output ab. Danach schlägt er nur die Spezial-Skills vor, die zum Fall passen.

## Quellenhygiene

Normtexte werden aus amtlichen Quellen geprüft. Rechtsprechung wird nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle verwendet. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. Nicht das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `bu-berufsbild-bu-nachpruefung-datenschutz` | BU Berufsbild BU Nachpruefung Datenschutz im Plugin Versicherungsrecht: prüft konkret Berufsunfähigkeitsversicherung, BU-Nachprüfung, Gesundheitsdaten im Versicherungsmandat. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel u... |
| `cyberversicherung-ransomware-d-o` | Cyberversicherung Ransomware D O im Plugin Versicherungsrecht: prüft konkret Cyberversicherung bei Ransomware, Datenabfluss, Betriebsunterbrechung, Lösegeld. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `deckungsprozess-vvg-rechtsabteilung` | Deckungsprozess VVG Rechtsabteilung im Plugin Versicherungsrecht: prüft konkret Deckungsprozess gegen Versicherer, Rechtsabteilungs-Fachmodul für Rechtsschutzversicherung im, Sachverständigenverfahren. Liefert priorisierten Output mit No... |
| `direktanspruch-pflichtversicherung-eiopa` | Direktanspruch Pflichtversicherung Eiopa im Plugin Versicherungsrecht: prüft konkret Direktanspruch gegen Haftpflichtversicherer, Grenzüberschreitender Versicherungsvertrieb, Betriebsschließungsversicherung. Liefert priorisierten Output... |
| `dora-cyber-abfindung-entschaedigungsquittung` | Dora Cyber Abfindung Entschaedigungsquittung im Plugin Versicherungsrecht: prüft konkret DORA-Compliance für Versicherer/Vermittler, Vergleich mit Versicherern, Abstrakte/konkrete Verweisung in der BU. Liefert priorisierten Output mit No... |
| `hausrat-einbruchdiebstahl-idd-vertrieb` | Hausrat Einbruchdiebstahl IDD Vertrieb im Plugin Versicherungsrecht: prüft konkret Hausratversicherung bei Einbruchdiebstahl, Raub, Trickdiebstahl, Wertsachen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Sch... |
| `kfz-haftpflicht-kasko-grobe-krankentagegeld` | KFZ Haftpflicht Kasko Grobe Krankentagegeld im Plugin Versicherungsrecht: prüft konkret Kfz-Haftpflichtversicherung, Kfz-Kaskoversicherung, Krankentagegeldversicherung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näc... |
| `kreditausfallversicherung-warenkredit` | Kreditausfallversicherung Warenkredit im Plugin Versicherungsrecht: prüft konkret Kreditausfall-/Warenkreditversicherung, Kreditversicherung im laufenden Debitorenmanagement, Bezugsrechte in Lebens- und Rentenversicherung. Liefert priori... |
| `lebensversicherung-rueckkaufswert` | Lebensversicherung Rueckkaufswert im Plugin Versicherungsrecht: prüft konkret Rückkaufswert, Abschlusskosten, Kündigung, Beitragsfreistellung und Altvertrags-. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Sch... |
| `pkv-kostenerstattung-private` | PKV Kostenerstattung Private im Plugin Versicherungsrecht: prüft konkret PKV-Leistungsprüfung, Private Krankenversicherung, Produkthaftpflichtversicherung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `rechtsabteilung-betriebsunterbrechung` | Rechtsabteilung Betriebsunterbrechung im Plugin Versicherungsrecht: prüft konkret Rechtsabteilungs-Fachmodul für Betriebsunterbrechung und, Rechtsabteilungs-Fachmodul für Cyberversicherung nach, Rechtsabteilungs-Fachmodul für IDD-Vertrie... |
| `rechtsabteilung-d-umwelthaftpflicht` | Rechtsabteilung D Umwelthaftpflicht im Plugin Versicherungsrecht: prüft konkret Rechtsabteilungs-Fachmodul für D&O-Deckung bei Organhaftung, Umwelthaftpflichtversicherung und Umweltschadenversicherung, Maklerhaftung wegen fehlerhafter Ri... |
| `rechtsschutz-deckungszusage-erfolgsaussicht` | Rechtsschutz Deckungszusage Erfolgsaussicht im Plugin Versicherungsrecht: prüft konkret Rechtsschutzversicherung, Reiserücktritts- und Reiseabbruchversicherung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Sc... |
| `restschuldversicherung-widerruf` | Restschuldversicherung Widerruf im Plugin Versicherungsrecht: prüft konkret Restschuldversicherung bei Verbraucherdarlehen, Rückversicherung, Fronting-Strukturen, Captives. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und... |
| `subrogation-regress-transportversicherung` | Subrogation Regress Transportversicherung im Plugin Versicherungsrecht: prüft konkret Legalzession und Regress des Versicherers, Transportversicherung, Versicherungsaufsicht nach VAG. Liefert priorisierten Output mit Norm-Pinpoints, Risi... |
| `unfallversicherung-invaliditaet-vers` | Unfallversicherung Invaliditaet Vers im Plugin Versicherungsrecht: prüft konkret Private Unfallversicherung, Fristen und Ausschlussrisiken im Versicherungsrecht, Rechtsschutzversicherung. Liefert priorisierten Output mit Norm-Pinpoints,... |
| `vers-deckungsablehnung-redteam` | Deckungsablehnung des Versicherers zerlegen: Risikoausschluss, Obliegenheit, Kausalität, grobe Fahrlässigkeit, Arglist, Beweislast und Vergleichsfenster systematisch prüfen. |
| `vers-dokumentenintake-police-avb-nachtraege` | Dokumentenintake für Versicherungsakten: Versicherungsschein, AVB, Nachträge, Beratungsdokumentation, Schadenanzeige, Gutachten, Korrespondenz und Ablehnung in eine Aktenmatrix überführen. |
| `vers-kaltstart-routing` | Allgemeiner Einstieg ins Versicherungsrecht: Police, Bedingungen, Schadenereignis, Ablehnung, Fristen, Aufsicht, Ombudsmann und Klageweg strukturiert erfassen und passende Fachmodule vorschlagen. |
| `vers-ombudsmann-versicherungsbetrug` | Vers Ombudsmann Versicherungsbetrug im Plugin Versicherungsrecht: prüft konkret Eskalationsrouting im Versicherungsrecht, Versicherungsrechtlicher Umgang mit Betrugsverdacht, Versicherungssumme, Unterversicherung. Liefert priorisierten O... |
| `versicherungsprodukt-agb-betriebshaftpflicht` | Versicherungsprodukt AGB Betriebshaftpflicht im Plugin Versicherungsrecht: prüft konkret AVB-Klauseln nach Transparenz, Überraschung, unangemessener Benachteiligung und, Betriebshaftpflichtversicherung. Liefert priorisierten Output mit N... |
| `versicherungsrecht-vvg-anzeigepflicht-ruecktritt-arglist` | VVG Anzeigepflicht Ruecktritt Arglist im Plugin Versicherungsrecht: prüft konkret § 19 VVG in Leben, PKV und Unfallversicherung, Arglistanfechtung nach § 22 VVG/BGB § 123, Fälligkeit des Versicherungsanspruchs. Liefert priorisierten Outp... |
| `vvg-gefahrerhoehung-mehrfachversicherung` | VVG Gefahrerhoehung Mehrfachversicherung im Plugin Versicherungsrecht: prüft konkret Gefahrerhöhung vor und nach Vertragsschluss, Mehrfachversicherung und Doppelversicherung, § 28 VVG nach Eintritt des Versicherungsfalls. Liefert prioris... |
| `vvg-versicherung-wohngebaeude-leitungswasser` | VVG Versicherung Wohngebaeude Leitungswasser im Plugin Versicherungsrecht: prüft konkret Versicherung für fremde Rechnung, Wohngebäudeversicherung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
