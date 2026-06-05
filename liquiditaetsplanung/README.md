# Liquiditätsplanung — Power-Plugin

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`liquiditaetsplanung`) | [`liquiditaetsplanung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/liquiditaetsplanung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Edelholz Manufaktur Berlin GmbH — Liquiditäts- und Steuerakte** (`beispielakte-edelholz-berlin`) | [Gesamt-PDF lesen](../testakten/beispielakte-edelholz-berlin/gesamt-pdf/beispielakte-edelholz-berlin_gesamt.pdf) | [`testakte-beispielakte-edelholz-berlin.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-beispielakte-edelholz-berlin.zip) |
| **Forschungszulage Riedblick Sensorik GmbH** (`forschungszulage-sensorik-startup-taunus`) | [Gesamt-PDF lesen](../testakten/forschungszulage-sensorik-startup-taunus/gesamt-pdf/forschungszulage-sensorik-startup-taunus_gesamt.pdf) | [`testakte-forschungszulage-sensorik-startup-taunus.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-forschungszulage-sensorik-startup-taunus.zip) |
| **Fortbestehensprognose Paragrafix GmbH** (`fortbestehensprognose-paragrafix-gmbh`) | [Gesamt-PDF lesen](../testakten/fortbestehensprognose-paragrafix-gmbh/gesamt-pdf/fortbestehensprognose-paragrafix-gmbh_gesamt.pdf) | [`testakte-fortbestehensprognose-paragrafix-gmbh.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-fortbestehensprognose-paragrafix-gmbh.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

**Eigenständiges Power-Plugin** für wochenaktuelle Liquiditätsvorschauen nach deutschem Recht (§§ 17, 18, 19 InsO; § 1 StaRUG; BGH-Schema Passiva II). Funktioniert allein. Ergänzt sich optional mit `insolvenzrecht` und `steuerrecht-anwalt-und-berater`, hängt aber nicht von ihnen ab.

---

## Was ist drin

Vier Fachskills plus Allgemein-Skill, alle fachlich autark:

| Skill | Zweck | Horizont |
| --- | --- | --- |
| `idw-s6-integrierte-sanierungsplanung` | Brücke von Liquiditätsvorschau zu Sanierungskonzept: GuV, Planbilanz, Maßnahmenlog, Annahmenregister, Sensitivitäten und Sanierungsfähigkeits-Ampel. | 12-24 Monate |
| `liquiditaetsvorschau-3wochen` | Wochenaktuelle Vorprüfung § 17 InsO (Freitag-Stichtag), Verhältnis zu offenen Forderungen, Ampel. | 3 Wochen |
| `liquiditaetsvorschau-3-6-12-monate` | Rollierende Planung mit Sensitivität (Best/Base/Worst), Fortbestehensprognose nach § 19 InsO und Übergabe in die Sanierungsplanung. | 13 / 26 / 52 Wochen |
| `liquiditaetsvorschau-insolvenzrechtlich` | Gerichtsfeste Liquiditätsbilanz nach BGH-Schema (Passiva II zwingend, Volumeneffekt der Quote, titulierte Forderungen mit Nennwert). | Stichtagsbezogen |

## Ergebnisformate

Jeder Skill liefert standardmäßig eine **Excel-Tabelle** nach der hinterlegten Vorlage (`assets/excel/Liquiditaetsplan-Wochenbasis.xlsx`, KW-Spalten × Kategorien-Zeilen, Freitag als Wochenstichtag). Zusätzlich auf Wahl:

- **Interaktives HTML-Padlet** (`assets/padlet/liquiditaets-padlet.html`) — single-file, autark, rechnet die Ampel live nach BGH-Schema, speichert in `localStorage`, exportiert/importiert JSON.
- **Markdown-Artefakt** (`assets/markdown/liquiditaets-artefakt-vorlage.md`) — Tabellen, Indizienliste, Kurzfazit; wird bei jeder Folgemeldung neu geschrieben.
- **Memo** im Gutachtenstil (DOCX oder Markdown) — **nur auf ausdrückliche Anfrage**.

Die Skills fragen einmal am Anfang nach Format und merken sich die Antwort.

## Banking

Jeder Skill fragt einmal nach der Datenquelle:

1. **Manuell** im Padlet/Artefakt/Chat.
2. **Datei-Import** — CAMT.053, MT940, CSV-Bankexport, DATEV-OPOS.
3. **Connector** — PSD2/FinTS oder verfügbare Anbieter (per `list_external_tools`).

Mandatsgeheimnis (§§ 203/204 StGB, § 43e BRAO) und Drittlandtransfer (DSGVO Art. 44 ff.) werden adressiert.

## BGH-Schema (Passiva II)

```
Aktiva I   = Bank + Kasse + freier zugesagter Kontokorrent (Stichtag)
Aktiva II  = Σ Einzahlungen KW t..t+2
Passiva I  = am Stichtag fällig, eingefordert, nicht echt gestundet
Passiva II = binnen 3 Wochen fällig (KW t+1 + KW t+2)

Lücke abs. = max(0, (Passiva I + Passiva II) − (Aktiva I + Aktiva II))
Quote      = Lücke abs. ÷ (Passiva I + Passiva II)   (Volumeneffekt
             Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
```

**Ampel**: 🟢 Quote < 10 % und Liquidität KW t+2 ≥ 0 und < 2 Indizien. 🟡 Quote ≥ 10 %, KW t+2 ≥ 0, < 2 Indizien (schließbar). 🔴 sonst — § 17 InsO indiziert.

## Leitentscheidungen (Volltexte: `references/rechtsprechung/`)

1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.

Berufsständischer Hintergrund: Methodenrahmen zu Insolvenzeröffnungsgründen und Sanierungskonzepten; nicht als Ersatz für Gesetz, Rechtsprechung und konkrete Subsumtion zitieren.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 69 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Liquiditaetsplanung-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Spezial-Skills aus diesem Plugin vor und führt in einen klaren Arbeitsplan... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fr... |
| `ampel` | Nutze dies, wenn Ampel: Zahlen, Schwellenwerte und Berechnung im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Ampel: Zahlen, Schwellenwerte und Berechnung prüfen.; Erstelle eine Arbeitsfassung zu Ampel: Zahl... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Liquiditaetsplanung.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `ausgabengruppen-fristennotiz-naechster` | Nutze dies, wenn Ausgabengruppen: Fristennotiz und nächster Schritt im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Ausgabengruppen: Fristennotiz und nächster Schritt prüfen.; Erstelle eine Arbeitsfassung zu... |
| `chronologie-und-belegmatrix` | Nutze dies, wenn Chronologie und Belegmatrix im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Chronologie und Belegmatrix prüfen.; Erstelle eine Arbeitsfassung zu Chronologie und Belegmatrix.; Welche Normen u... |
| `deutschem` | Nutze dies, wenn Deutschem: Tatbestandsmerkmale, Beweisfragen und Beleglage im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Deutschem: Tatbestandsmerkmale, Beweisfragen und Beleglage prüfen.; Erstelle eine A... |
| `deutschem-dokumentationspaket-excel` | Nutze dies, wenn Spezial Deutschem Tatbestand Beweis Und Belege, Spezial Dokumentationspaket Compliance Dokumentation Und Akte, Spezial Excel Behörden Gericht Und Registerweg im Plugin Liquiditaetsplanung konkret bearbeitet werden soll.... |
| `dokumentationspaket` | Nutze dies, wenn Dokumentationspaket: Compliance-Dokumentation und Aktenvermerk im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Liquiditaetsplanung.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `excel` | Nutze dies, wenn Excel: Behörden-, Gerichts- oder Registerweg im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Excel: Behörden-, Gerichts- oder Registerweg prüfen.; Erstelle eine Arbeitsfassung zu Excel: Behö... |
| `export` | Nutze dies, wenn Export: Schriftsatz-, Brief- und Memo-Bausteine im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Export: Schriftsatz-, Brief- und Memo-Bausteine prüfen.; Erstelle eine Arbeitsfassung zu Expor... |
| `export-forecast-fortbestehensprognose` | Nutze dies, wenn Spezial Export Schriftsatz Brief Und Memo Bausteine, Spezial Forecast Risikoampel Und Gegenargumente, Spezial Fortbestehensprognose International Schnittstellen im Plugin Liquiditaetsplanung konkret bearbeitet werden sol... |
| `forecast` | Nutze dies, wenn Forecast: Risikoampel, Gegenargumente und Verteidigungslinien im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Forecast: Risikoampel, Gegenargumente und Verteidigungslinien prüfen.; Erstelle... |
| `fortbestehensprognose-international` | Nutze dies, wenn Fortbestehensprognose: Internationaler Bezug und Schnittstellen im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Fortbestehensprognose: Internationaler Bezug und Schnittstellen prüfen.; Erste... |
| `fristen-und-risikoampel` | Nutze dies, wenn Fristen- und Risikoampel im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Fristen- und Risikoampel prüfen.; Erstelle eine Arbeitsfassung zu Fristen- und Risikoampel.; Welche Normen und Nachwe... |
| `idw-s6-integrierte-sanierungsplanung` | Verbindet Liquiditätsvorschau, GuV-Planung und Planbilanz zu einer Sanierungsplanung auf IDW-S-6-Niveau. Prüft Maßnahmenwirkung, Fortbestehensprognose, Sanierungsfähigkeit, Szenarien, Planungsannahmen, Belegregister, kleinere Unternehmen... |
| `insolvenzrecht` | Nutze dies, wenn Insolvenzrecht: Formular, Portal und Einreichungslogik im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Insolvenzrecht: Formular, Portal und Einreichungslogik prüfen.; Erstelle eine Arbeitsfa... |
| `insolvenzrecht-liqui-sonderfall` | Nutze dies, wenn Spezial Insolvenzrecht Formular Portal Und Einreichung, Spezial Liqui Sonderfall Und Edge Case, Spezial Liquiditaetsplanung Erstpruefung Und Mandatsziel im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslö... |
| `interessen` | Nutze dies, wenn Schnittstellen: Mehrparteienkonflikt und Interessenmatrix im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Schnittstellen: Mehrparteienkonflikt und Interessenmatrix prüfen.; Erstelle eine Arb... |
| `interessen-verifikation-beweislast-vorschau` | Nutze dies, wenn Spezial Schnittstellen Mehrparteien Konflikt Und Interessen, Spezial Verifikation Beweislast Und Darlegungslast, Spezial Vorschau Dokumentenmatrix Und Lueckenliste im Plugin Liquiditaetsplanung konkret bearbeitet werden... |
| `liqp-bankenreporting-leitfaden` | Leitfaden Bankenreporting bei Krise: Anforderungen Hausbank, Konsortium, KfW, Reportingfrequenz, Covenant-Reporting. Pruefraster fuer CFO und Berater. |
| `liqp-liquiditaetspool-cash-pooling-spezial` | Spezialfall Liquiditaetspool und Cash-Pooling im Konzern: § 30 GmbHG, BGH-Rechtsprechung, vollwertiger Rueckzahlungsanspruch. Pruefraster fuer Konzernmutter und Tochter. |
| `liqp-liquiditaetspool-cash-rollende-13wochen` | Nutze dies, wenn Liqp Liquiditaetspool Cash Pooling Spezial, Liqp Rollende 13Wochen Bauleiter, Liqp Warenkredit Skonto Szenarien Spezial im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?;... |
| `liqp-rollende-13wochen-bauleiter` | Bauleiter rollende 13-Wochen-Liquiditaetsplanung: Einnahmen / Ausgaben / Saldo / kumulierter Saldo, Granularitaet, Update-Zyklen. Pruefraster Mittelstand und Konzerntochter. |
| `liqp-warenkredit-skonto-szenarien-spezial` | Spezialfall Warenkredit und Skontostrategien in der Krise: Lieferantenverhandlung, Vorkasse, verlaengerter Eigentumsvorbehalt, Factoring. Pruefraster fuer Treasury. |
| `liqui-ausgabengruppen-systematik` | Ausgabengruppen systematisch erfassen: Personal (Lohn, SV, LSt), Material/Wareneinsatz, Miete, Energie, Versicherungen, Beratungs-/Anwaltskosten, Steuerzahlungen, Investitionen, Zinsen, Tilgung. Vorlage Tabelle. |
| `liqui-bei-drohender-zahlungsunfaehigkeit` | Liquiditaetsplanung bei drohender Zahlungsunfaehigkeit § 18 InsO: 24-Monats-Planung, Zugang StaRUG-Restrukturierung, Geschaeftsleiterpflichten. Pruefraster und Schnittstelle Insolvenzantrag. |
| `liqui-bei-eingetretener-zahlungsunfaehigkeit` | Liquiditaetsplanung bei eingetretener Zahlungsunfaehigkeit § 17 InsO: 3-Wochen-Vorschau zur Pruefung Insolvenzantragspflicht, Liquiditaetsluecke kleiner 10 Prozent + Schliessung binnen 3 Wochen waere Liquiditaetsstockung. Pruefraster BGH... |
| `liqui-cash-pooling-konzern` | Cash-Pooling im Konzern: rechtliche Risiken Existenzvernichtung BGH II ZR 78/06, Sanierungstauglichkeit, Pruefung Avale gegen Konzerngesellschaften, Steuerrisiken § 8b KStG. Output: Cash-Pool-Risiko-Memo. |
| `liqui-drohender-zahlungsunfaehigkeit` | Nutze dies, wenn Liqui Bei Drohender Zahlungsunfaehigkeit, Liqui Bei Eingetretener Zahlungsunfaehigkeit, Liqui Für Bankgespraech im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Liqui Bei Drohender Zahlungsun... |
| `liqui-eingangsdaten-checkliste` | Eingangsdaten-Checkliste fuer Liquiditaetsplanung: BWA, OPOS Debitoren/Kreditoren, Kontoauszuege, Steuerkonten, SV-Konten, Personalkosten, Investitionsplanung. Pruefliste Quellen und Vollstaendigkeit. Output: standardisiertes Datentemplate. |
| `liqui-eingangsdaten-idw-s6-liqp` | Nutze dies, wenn Liqui Eingangsdaten Checkliste, Idw S6 Integrierte Sanierungsplanung, Liqp Bankenreporting Leitfaden im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Liqui Eingangsdaten Checkliste, Idw S6 In... |
| `liqui-fuer-bankgespraech` | Liquiditaetsplanung fuer Bankgespraech: kompakte Vorlage 13 Wochen + Jahresansicht, Annahmen-Block, Sensitivitaet, Kreditlinien-Ausnutzung, Begleittext. Empfehlung: realistisch, nicht zu optimistisch, mit Fallback-Hebeln. |
| `liqui-grundbegriffe-cashflow` | Liquiditaetsplanung Grundbegriffe: Cashflow vs. Gewinn, indirekte vs. direkte Methode, Liquiditaet 1./2./3. Grades, Working Capital. Abgrenzung zur GuV-Planung. Empfehlung: direkte Methode fuer 13-Wochen-Forecast, indirekte fuer Jahrespl... |
| `liqui-grundbegriffe-cashflow-kreditlinien` | Nutze dies, wenn Liqui Grundbegriffe Cashflow, Liqui Kreditlinien Prüfen, Liqui Mahnstufen Debitoren im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist... |
| `liqui-kreditlinien-pruefen` | Kreditlinien pruefen: Kontokorrent, Investitionskredit, Avalkredit, Factoring-Linie, Lieferantenkredit. Ausnutzungsgrade, Tilgungsplaene, Sicherheiten, Covenants. Pruefraster fuer Bankgespraech. |
| `liqui-leasing-lp-restrukturierungsplan-starug` | Nutze dies, wenn Liqui Mit Leasing Und Lp, Liqui Restrukturierungsplan Starug, Liqui Saisonalitaet Erkennen im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Liqui Mit Leasing Und Lp, Liqui Restrukturierungspl... |
| `liqui-mahnstufen-debitoren` | Debitorenseite optimieren: DSO-Kennzahl, Mahnstufen, Skontostrategie, Factoring-Optionen, Forderungsausfallversicherung. Empfehlung: 3-Wochen-Forecast getrennt nach Kategorie 'sicher / wahrscheinlich / fraglich'. |
| `liqui-mit-leasing-und-lp` | Leasing- und Lebenspartnerzahlungen in Liquiditaetsplan: operate lease als opex, finance lease wirkt sich auf Bilanz aus, vorzeitige Aufloesung kostenpflichtig. Empfehlung: Aufnahme nach Faelligkeit, Pruefung Beendigungskosten. |
| `liqui-restrukturierungsplan-starug` | Liquiditaetsplanung im Restrukturierungsplan StaRUG: Plan-Liquiditaet, Sanierungsbeitraege Glaeubiger, Working-Capital-Plan, Cash-Out-Termine. Output: integrierter Plan und Glaeubigerverteilungsschema. |
| `liqui-saisonalitaet-erkennen` | Saisonalitaet erkennen: Vorjahres-Kontodaten gegen Liquiditaetsplan abgleichen, Monats- und Wochenmuster, Sondereffekte (Inventur, Jahresabschluss, Ferien). Empfehlung: saisonale Korrekturfaktoren je Branche. |
| `liqui-sondereffekt-grossauftrag` | Sondereffekt Grossauftrag in Liquiditaetsplanung: Vorfinanzierung Material, Abschlagsrechnungen, Sicherheitseinbehalt § 17 VOB-B, MaBV-Raten bei Bauauftraegen. Liquiditaetsspitze pruefen, Zwischenfinanzierung organisieren. |
| `liqui-sondereffekt-grossauftrag-stundungs` | Nutze dies, wenn Liqui Sondereffekt Grossauftrag, Liqui Stundungs Strategie, Liqui Szenarien Aufbauen im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Liqui Sondereffekt Grossauftrag, Liqui Stundungs Strategi... |
| `liqui-sonderfall-edge-case` | Nutze dies, wenn Liqui: Sonderfall und Edge-Case-Prüfung im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Liqui: Sonderfall und Edge-Case-Prüfung prüfen.; Erstelle eine Arbeitsfassung zu Liqui: Sonderfall und... |
| `liqui-stundungs-strategie` | Stundungs-Strategie mit Finanzamt, Krankenkassen, Lieferanten: § 222 AO Stundung, Ratenzahlungsvereinbarung Krankenkasse, Lieferantenstundung. Pruefraster: wann beantragen, Mindestanforderungen Antrag, Reichweite (keine Glaeubigerbenacht... |
| `liqui-szenarien-aufbauen` | Szenarien aufbauen: Base Case, Best Case, Worst Case (mit Stresshebel: Umsatzeinbruch, Forderungsausfaelle, Lieferantenforderungen). Empfehlung: drei Szenarien mit dokumentierten Annahmen, Sensitivitaeten in Excel. |
| `liquiditaetsplanung` | Nutze dies, wenn Liquiditaetsplanung: Erstprüfung, Rollenklärung und Mandatsziel im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Liquiditaetsplanung: Erstprüfung, Rollenklärung und Mandatsziel prüfen.; Erste... |
| `liquiditaetsstatus-quellenbelege` | Liquiditätsstatus nur aus belastbaren Quellenbelegen: führt schnell durch Sachverhalt, Rechtsgrundlagen, Belege, Risiken und erzeugt einen verwertbaren nächsten Output. |
| `liquiditaetsstatus-quellenbelege-live-quote` | Nutze dies, wenn Spezial Liquiditaetsstatus Quellenbelege, Spezial Live Mandantenkommunikation Entscheidungsvorlage, Spezial Quote Verhandlung Vergleich Und Eskalation im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöse... |
| `liquiditaetsvorschau-3-6-12-monate` | Rollierende Liquiditaetsvorschau fuer 3/6/12 Monate mit Fortfuehrungsprognose, Wochenraster, Excel-Export und Quellenhygiene. Rechtsprechung nur nach Live-Pruefung. |
| `liquiditaetsvorschau-3wochen` | Drei-Wochen-Liquiditaetsvorschau nach § 17 InsO mit Wochenraster, Excel-Export, Quote/Luecken-Ampel und Dokumentation. Rechtsprechung nur nach Live-Pruefung. |
| `liquiditaetsvorschau-3wochen-02` | Nutze dies, wenn Liquiditaetsvorschau 3Wochen, Liquiditaetsvorschau Insolvenzrechtlich, Spezial Ampel Zahlen Schwellen Und Berechnung im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Liquiditaetsvorschau 3Woc... |
| `liquiditaetsvorschau-insolvenzrechtlich` | Workflow-Skill zu liquiditaetsvorschau insolvenzrechtlich. Nutzt Normtext, Nutzerangaben und verifizierte Quellen; Rechtsprechung nur nach Live-Pruefung mit Gericht, Datum und Aktenzeichen. |
| `live` | Nutze dies, wenn Live: Mandantenkommunikation und Entscheidungsvorlage im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Live: Mandantenkommunikation und Entscheidungsvorlage prüfen.; Erstelle eine Arbeitsfass... |
| `luecken-quellenkarte` | Nutze dies, wenn Luecken Quellenkarte im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `mandantenkommunikation` | Nutze dies, wenn Mandantenkommunikation im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Mandantenkommunikation prüfen.; Erstelle eine Arbeitsfassung zu Mandantenkommunikation.; Welche Normen und Nachweise br... |
| `mandantenkommunikation-redteam-qualitygate` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Ausgabengruppen Fristennotiz Und Naechster Schritt im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `quote` | Nutze dies, wenn Quote: Verhandlung, Vergleich und Eskalation im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Quote: Verhandlung, Vergleich und Eskalation prüfen.; Erstelle eine Arbeitsfassung zu Quote: Verh... |
| `rechtsprechung-fehlerkatalog` | Nutze dies, wenn Rechtsprechung Fehlerkatalog im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `redteam-qualitygate` | Nutze dies, wenn Red-Team Qualitygate im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `verifikation-beweislast-darlegungslast` | Nutze dies, wenn Verifikation: Beweislast, Darlegungslast und Substantiierung im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Verifikation: Beweislast, Darlegungslast und Substantiierung prüfen.; Erstelle ei... |
| `vorschau` | Nutze dies, wenn Vorschau: Dokumentenmatrix, Lückenliste und Nachforderung im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `wochen` | Nutze dies, wenn Wochen: Fristen, Form, Zuständigkeit und Rechtsweg im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Wochen: Fristen, Form, Zuständigkeit und Rechtsweg prüfen.; Erstelle eine Arbeitsfassung zu... |
| `wochen-liqui-ausgabengruppen-liqui-cash` | Nutze dies, wenn Spezial Wochen Fristen Form Und Zustaendigkeit, Liqui Ausgabengruppen Systematik, Liqui Cash Pooling Konzern im Plugin Liquiditaetsplanung konkret bearbeitet werden soll. Auslöser: Bitte Spezial Wochen Fristen Form Und Z... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
