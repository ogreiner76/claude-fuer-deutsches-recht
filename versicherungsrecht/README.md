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
| `bu-berufsbild-bu-nachpruefung-datenschutz` | Nutze dies, wenn Bu Berufsbild 50 Prozent Substantiierung, Bu Nachpruefung Anerkenntnis Leistungseinstellung, Datenschutz Schweigepflicht Gesundheitsdaten im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Bu Be... |
| `cyberversicherung-ransomware-d-o` | Nutze dies, wenn Cyberversicherung Ransomware Sanktionsrecht, D O Claims Made Innenhaftung 43 Gmbhg, Elementarschaden Starkregen Ueberschwemmung im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Cyberversicheru... |
| `deckungsprozess-vvg-rechtsabteilung` | Nutze dies, wenn Deckungsprozess Zustaendigkeit 215 Vvg, Rechtsabteilung Rechtsschutzversicherung Im Massenverfahren, Sachverstaendigenverfahren Versicherung im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte De... |
| `direktanspruch-pflichtversicherung-eiopa` | Nutze dies, wenn Direktanspruch Pflichtversicherung 115 Vvg, Eiopa Grenzueberschreitender Vertrieb, Gewerbe Betriebsschliessung Infektionsschutz im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Direktanspruch... |
| `dora-cyber-abfindung-entschaedigungsquittung` | Nutze dies, wenn Dora Cyber Ikt Versicherer, Vergleich Abfindung Entschaedigungsquittung, Bu Abstrakte Konkrete Verweisung im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Dora Cyber Ikt Versicherer, Vergleich... |
| `hausrat-einbruchdiebstahl-idd-vertrieb` | Nutze dies, wenn Hausrat Einbruchdiebstahl Entschaedigungsgrenze, Idd Vertrieb Beratung Dokumentation, Internationales Versicherungsprogramm Master Local Policy im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte... |
| `kfz-haftpflicht-kasko-grobe-krankentagegeld` | Nutze dies, wenn Kfz Haftpflicht Regress Alkohol Flucht, Kfz Kasko Grobe Fahrlaessigkeit Entwendung, Krankentagegeld Berufsunfaehigkeit Abgrenzung im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Kfz Haftpflic... |
| `kreditausfallversicherung-warenkredit` | Nutze dies, wenn Kreditausfallversicherung Warenkredit Forderungsausfall, Kreditversicherung Obliegenheiten Limit Prüfung, Lebensversicherung Bezugsrecht Widerruf Aenderung im Plugin Versicherungsrecht konkret bearbeitet werden soll. Aus... |
| `lebensversicherung-rueckkaufswert` | Nutze dies, wenn Lebensversicherung Rueckkaufswert Abschlusskosten Widerspruch, Lebensversicherung Ueberschussbeteiligung Bewertungsreserven, Nachhaltigkeit Taxonomie Sfdr Versicherungsprodukt im Plugin Versicherungsrecht konkret bearbei... |
| `pkv-kostenerstattung-private` | Nutze dies, wenn Pkv Kostenerstattung Medizinische Notwendigkeit, Private Krankenversicherung Beitragsanpassung Treuhaender, Produkthaftpflicht Rueckrufkosten im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte P... |
| `rechtsabteilung-betriebsunterbrechung` | Nutze dies, wenn Rechtsabteilung Betriebsunterbrechung Und Lieferkettenausfall, Rechtsabteilung Cyberversicherung Nach Ransomware, Rechtsabteilung Idd Vertrieb Und Provisionskonflikt im Plugin Versicherungsrecht konkret bearbeitet werden... |
| `rechtsabteilung-d-umwelthaftpflicht` | Nutze dies, wenn Rechtsabteilung D O Deckung Bei Organhaftung, Umwelthaftpflicht Umweltschadenversicherung, Versicherungsmakler Haftung Deckungsluecke im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Rechtsabt... |
| `rechtsschutz-deckungszusage-erfolgsaussicht` | Nutze dies, wenn Rechtsschutz Deckungszusage Stichentscheid, Rechtsschutz Erfolgsaussicht Mutwilligkeit, Reiseversicherung Rücktritt Abbruch Krankheit im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Rechtssch... |
| `restschuldversicherung-widerruf` | Nutze dies, wenn Restschuldversicherung Widerruf Kopplung Verbraucherdarlehen, Rueckversicherung Cut Through Und Fronting, Solvency Ii Scr Orsa Aufsichtsrecht im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte R... |
| `subrogation-regress-transportversicherung` | Nutze dies, wenn Subrogation Regress 86 Vvg, Transportversicherung Ware Lagerung, Vag Bafin Aufsicht Beschwerde Missstand im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Subrogation Regress 86 Vvg, Transportv... |
| `unfallversicherung-invaliditaet-vers` | Nutze dies, wenn Unfallversicherung Invaliditaet Fristen Gliedertaxe, Vers Fristen Verjaehrung Klagefrist Fallkalender, Rechtsschutz Vorvertraglichkeit Schadenereignis im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser... |
| `vers-allgemeiner-kaltstart` | Allgemeiner Einstieg ins Versicherungsrecht: Police, Bedingungen, Schadenereignis, Ablehnung, Fristen, Aufsicht, Ombudsmann und Klageweg strukturiert erfassen und passende Spezial-Skills vorschlagen. |
| `vers-deckungsablehnung-redteam` | Deckungsablehnung des Versicherers zerlegen: Risikoausschluss, Obliegenheit, Kausalität, grobe Fahrlässigkeit, Arglist, Beweislast und Vergleichsfenster systematisch prüfen. |
| `vers-dokumentenintake-police-avb-nachtraege` | Dokumentenintake für Versicherungsakten: Versicherungsschein, AVB, Nachträge, Beratungsdokumentation, Schadenanzeige, Gutachten, Korrespondenz und Ablehnung in eine Aktenmatrix überführen. |
| `vers-ombudsmann-versicherungsbetrug` | Nutze dies, wenn Vers Ombudsmann Bafin Beschwerde Klageweg, Versicherungsbetrug Verdachtsfall Kooperation Strafrecht, Versicherungssumme Unterversicherung Taxwert im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bit... |
| `versicherungsprodukt-agb-betriebshaftpflicht` | Nutze dies, wenn Versicherungsprodukt Agb Klauselkontrolle, Betriebshaftpflicht Versicherungsfall Serienschaden, Betriebsunterbrechung Sachschaden Trigger im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Versi... |
| `vvg-anzeigepflicht-vvg-arglist-vvg-falligkeit` | Nutze dies, wenn Vvg Anzeigepflicht 19 Rücktritt Kündigung Anpassung, Vvg Arglist Taeuschung Anfechtung, Vvg Falligkeit 14 Abschlagszahlung im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Vvg Anzeigepflicht 1... |
| `vvg-gefahrerhoehung-mehrfachversicherung` | Nutze dies, wenn Vvg Gefahrerhoehung 23 27, Vvg Mehrfachversicherung 78, Vvg Obliegenheit 28 Quotelung Kausalitaet im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Vvg Gefahrerhoehung 23 27, Vvg Mehrfachversic... |
| `vvg-versicherung-wohngebaeude-leitungswasser` | Nutze dies, wenn Vvg Versicherung Für Fremde 43 48, Wohngebaeude Leitungswasser Sturm Hagel Brand im Plugin Versicherungsrecht konkret bearbeitet werden soll. Auslöser: Bitte Vvg Versicherung Für Fremde 43 48, Wohngebaeude Leitungswasser... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
