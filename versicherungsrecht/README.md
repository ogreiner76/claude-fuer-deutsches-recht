# Versicherungsrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`versicherungsrecht`) | [`versicherungsrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/versicherungsrecht.zip) |

### Demonstrations-Akten

Dieses Plugin hat derzeit keine eigene Demonstrations-Akte. Es arbeitet mit hochgeladenen Policen, Bescheiden, Verträgen, Messprotokollen, Behördenbriefen und Aktenauszügen.

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
| `bu-berufsbild-bu-nachpruefung-datenschutz` | Nutze dies bei Bu Berufsbild 50 Prozent Substantiierung, Bu Nachpruefung Anerkenntnis Leistungseinstellung, Datenschutz Schweigepflicht Gesundheitsdaten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `cyberversicherung-ransomware-d-o` | Nutze dies bei Cyberversicherung Ransomware Sanktionsrecht, D O Claims Made Innenhaftung 43 Gmbhg, Elementarschaden Starkregen Ueberschwemmung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den n... |
| `deckungsprozess-vvg-rechtsabteilung` | Nutze dies bei Deckungsprozess Zustaendigkeit 215 Vvg, Rechtsabteilung Rechtsschutzversicherung Im Massenverfahren, Sachverstaendigenverfahren Versicherung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `direktanspruch-pflichtversicherung-eiopa` | Nutze dies bei Direktanspruch Pflichtversicherung 115 Vvg, Eiopa Grenzueberschreitender Vertrieb, Gewerbe Betriebsschliessung Infektionsschutz: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den n... |
| `dora-cyber-abfindung-entschaedigungsquittung` | Nutze dies bei Dora Cyber Ikt Versicherer, Vergleich Abfindung Entschaedigungsquittung, Bu Abstrakte Konkrete Verweisung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Ar... |
| `hausrat-einbruchdiebstahl-idd-vertrieb` | Nutze dies bei Hausrat Einbruchdiebstahl Entschaedigungsgrenze, Idd Vertrieb Beratung Dokumentation, Internationales Versicherungsprogramm Master Local Policy: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad u... |
| `kfz-haftpflicht-kasko-grobe-krankentagegeld` | Nutze dies bei Kfz Haftpflicht Regress Alkohol Flucht, Kfz Kasko Grobe Fahrlaessigkeit Entwendung, Krankentagegeld Berufsunfaehigkeit Abgrenzung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `kreditausfallversicherung-warenkredit` | Nutze dies bei Kreditausfallversicherung Warenkredit Forderungsausfall, Kreditversicherung Obliegenheiten Limit Prüfung, Lebensversicherung Bezugsrecht Widerruf Aenderung: führt durch diese fachlich verbundenen Module, wählt den passende... |
| `lebensversicherung-rueckkaufswert` | Nutze dies bei Lebensversicherung Rueckkaufswert Abschlusskosten Widerspruch, Lebensversicherung Ueberschussbeteiligung Bewertungsreserven, Nachhaltigkeit Taxonomie Sfdr Versicherungsprodukt: führt durch diese fachlich verbundenen Module... |
| `pkv-kostenerstattung-private` | Nutze dies bei Pkv Kostenerstattung Medizinische Notwendigkeit, Private Krankenversicherung Beitragsanpassung Treuhaender, Produkthaftpflicht Rueckrufkosten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `rechtsabteilung-betriebsunterbrechung` | Nutze dies bei Rechtsabteilung Betriebsunterbrechung Und Lieferkettenausfall, Rechtsabteilung Cyberversicherung Nach Ransomware, Rechtsabteilung Idd Vertrieb Und Provisionskonflikt: führt durch diese fachlich verbundenen Module, wählt de... |
| `rechtsabteilung-d-umwelthaftpflicht` | Nutze dies bei Rechtsabteilung D O Deckung Bei Organhaftung, Umwelthaftpflicht Umweltschadenversicherung, Versicherungsmakler Haftung Deckungsluecke: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `rechtsschutz-deckungszusage-erfolgsaussicht` | Nutze dies bei Rechtsschutz Deckungszusage Stichentscheid, Rechtsschutz Erfolgsaussicht Mutwilligkeit, Reiseversicherung Rücktritt Abbruch Krankheit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `restschuldversicherung-widerruf` | Nutze dies bei Restschuldversicherung Widerruf Kopplung Verbraucherdarlehen, Rueckversicherung Cut Through Und Fronting, Solvency Ii Scr Orsa Aufsichtsrecht: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `subrogation-regress-transportversicherung` | Nutze dies bei Subrogation Regress 86 Vvg, Transportversicherung Ware Lagerung, Vag Bafin Aufsicht Beschwerde Missstand: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arb... |
| `unfallversicherung-invaliditaet-vers` | Nutze dies bei Unfallversicherung Invaliditaet Fristen Gliedertaxe, Vers Fristen Verjaehrung Klagefrist Fallkalender, Rechtsschutz Vorvertraglichkeit Schadenereignis: führt durch diese fachlich verbundenen Module, wählt den passenden Prü... |
| `vers-allgemeiner-kaltstart` | Allgemeiner Einstieg ins Versicherungsrecht: Police, Bedingungen, Schadenereignis, Ablehnung, Fristen, Aufsicht, Ombudsmann und Klageweg strukturiert erfassen und passende Fachmodule vorschlagen. |
| `vers-deckungsablehnung-redteam` | Deckungsablehnung des Versicherers zerlegen: Risikoausschluss, Obliegenheit, Kausalität, grobe Fahrlässigkeit, Arglist, Beweislast und Vergleichsfenster systematisch prüfen. |
| `vers-dokumentenintake-police-avb-nachtraege` | Dokumentenintake für Versicherungsakten: Versicherungsschein, AVB, Nachträge, Beratungsdokumentation, Schadenanzeige, Gutachten, Korrespondenz und Ablehnung in eine Aktenmatrix überführen. |
| `vers-ombudsmann-versicherungsbetrug` | Nutze dies bei Vers Ombudsmann Bafin Beschwerde Klageweg, Versicherungsbetrug Verdachtsfall Kooperation Strafrecht, Versicherungssumme Unterversicherung Taxwert: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `versicherungsprodukt-agb-betriebshaftpflicht` | Nutze dies bei Versicherungsprodukt Agb Klauselkontrolle, Betriebshaftpflicht Versicherungsfall Serienschaden, Betriebsunterbrechung Sachschaden Trigger: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `vvg-anzeigepflicht-vvg-arglist-vvg-falligkeit` | Nutze dies bei Vvg Anzeigepflicht 19 Rücktritt Kündigung Anpassung, Vvg Arglist Taeuschung Anfechtung, Vvg Falligkeit 14 Abschlagszahlung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächst... |
| `vvg-gefahrerhoehung-mehrfachversicherung` | Nutze dies bei Vvg Gefahrerhoehung 23 27, Vvg Mehrfachversicherung 78, Vvg Obliegenheit 28 Quotelung Kausalitaet: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitssch... |
| `vvg-versicherung-wohngebaeude-leitungswasser` | Nutze dies bei Vvg Versicherung Für Fremde 43 48, Wohngebaeude Leitungswasser Sturm Hagel Brand: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
