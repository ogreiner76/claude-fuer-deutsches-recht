# Forderungsmanagement — Klagewerkstatt

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`forderungsmanagement-klagewerkstatt`) | [`forderungsmanagement-klagewerkstatt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/forderungsmanagement-klagewerkstatt.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Inkasso-Zahlungsklage ModeFuchs** (`inkasso-zahlungsklage-modefuchs`) | [Gesamt-PDF lesen](../testakten/inkasso-zahlungsklage-modefuchs/gesamt-pdf/inkasso-zahlungsklage-modefuchs_gesamt.pdf) | [`testakte-inkasso-zahlungsklage-modefuchs.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-inkasso-zahlungsklage-modefuchs.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

**Generalisierter Klage-Assistent für Inkasso- und Forderungsmanagement-Klagen mit eigenem Plugin-Generator.** Aus eigenen Mustern eine hauseigene Standardvorlage destillieren, online die Zuständigkeit prüfen, die Klage erzeugen und als sofort installierbares Mini-Plugin verpacken. Neu hinzu kommt ein direkter Inkasso-Zahlungsklage-Ersteller mit Mahnvorlauf, Anspruchs-Gatekeeper und der harten Regel: nur klare, fällige und belegte Ansprüche einklagen.

---

---

## Was ist drin

Drei Skills, gedacht als Lernlauf-+-Laufzeit-Paar plus direkter Inkasso-Klageassistent:

| Skill | Zweck |
| --- | --- |
| `klagevorlage-aus-eigenen-mustern` | **Lernlauf**: frisst eigene Klagemuster, Urteile, Kommentare, Aufsätze, Formatvorlagen; destilliert die hauseigene Standardklage-Vorlage; sammelt den Sachverhalt; **prüft online die Zuständigkeit** (justizadressen.nrw.de, justiz.de); liefert die Klage und erzeugt zusätzlich ein eigenes installierbares **Mini-Plugin als ZIP**. |
| `klage-aus-eigenem-skill` | **Laufzeit**: setzt voraus, dass das im Lernlauf erzeugte Mini-Plugin installiert ist. Nimmt nur noch Sachverhalt und Beklagtenadresse, prüft erneut online die Zuständigkeit, befüllt die Hausvorlage. Keine erneute Extraktion. |
| `inkasso-zahlungsklage-ersteller` | **Direktlauf**: liest Forderungsakte, Mahnungen, Abtretung, Inkassoschreiben, Teilzahlungen, Mahnbescheid/Widerspruch und vorhandene Klagen; erstellt Mahnchronologie, Anspruchsmatrix und Gerichtsortprüfung; nimmt nur grüne Positionen in den Klageentwurf. Bezahlte Hauptforderungen werden rot geblockt. |

Alle Klage-Skills führen **bei jedem Lauf** die Online-Zuständigkeitsprüfung über [justizadressen.nrw.de](https://www.justizadressen.nrw.de/de/justiz/suche) und das [bundesweite Justizportal](https://www.justiz.de/onlinedienste/gerichtsverzeichnis_und_orga/index.php) durch.

## Inkasso-Zahlungsklage-Ersteller

Der neue Direktlauf ist für Fälle gedacht, in denen eine Forderungsakte schon einen Mahn- oder Inkassoverlauf enthält. Er prüft vor der Klage:

- Rechnung, Fälligkeit, Lieferung/Leistung und Abtretung.
- Mahnvorlauf mit Zugang, Fristen und Beträgen.
- Zahlungseingänge, Teilzahlungen, Erfüllung und interne Kenntnis.
- Mahnkosten, Verzugszinsen, Inkassokosten und Mahnverfahrenskosten einzeln.
- Gerichtsort mit aktueller ladungsfähiger Anschrift.

Die ModeFuchs-Testakte unter [`testakten/inkasso-zahlungsklage-modefuchs/`](../testakten/inkasso-zahlungsklage-modefuchs/) ist der Referenzfall: Hauptforderung 698,00 EUR bezahlt vor Klageeinreichung, Nebenforderungen 99,84 EUR streitig. Erwartung: Hauptforderung rot, Nebenforderungen gelb, keine automatische Klage über 797,84 EUR. Direktdownload siehe Sofort-Download-Sektion oben.

## Plugin-Generator

Aus den extrahierten Hausregeln und der Standardvorlage packt der Skill ein eigenes, in Claude Code direkt installierbares ZIP:

```bash
python scripts/plugin_aus_hausregeln.py \
  --kanzlei "Kanzlei Mustermann" \
  --vorlage assets/vorlagen-leer/standardklage.md \
  --regeln  /pfad/hausregeln.json \
  --ziel    /pfad/klagewerkstatt-mustermann.zip
```

Layout des erzeugten Plugins:

```
klagewerkstatt-<slug>/
  .claude-plugin/plugin.json
  skills/klage-erstellen/SKILL.md
  assets/vorlage/standardklage.md
  references/hausregeln.json
  references/belegmuster.md
  references/anlagenliste.md
  references/zustaendigkeit-quellen.md
  README.md
```

Der erzeugte Skill enthält die Hausregeln fest verdrahtet und führt weiterhin die **Online-Zuständigkeitsprüfung** als Pflichtschritt aus.

## Ergebnisformate

- **DOCX** über `office/docx` (`Klage-<Beklagte>-<YYYYMMDD>.docx`) und **Markdown-Spiegel**.
- **Anlage Zuständigkeitsprüfung** mit Online-Quelle und Abrufdatum.
- **HTML-Padlet** (`assets/padlet/klage-padlet.html`) — single-file, autark, Live-Vorschau, speichert in `localStorage`, exportiert/importiert JSON.
- **Memo** im Gutachtenstil — nur auf ausdrückliche Anfrage.

## Online-Zuständigkeit (Pflicht in jedem Lauf)

1. **Sachlich** rechnerisch: ≤ 10.000 EUR → AG (§ 23 Nr. 1 GVG i. d. F. seit 1.1.2026); > 10.000 EUR → LG (§ 71 GVG); Sondertatbestände beachten (insbes. Wohnraummietsachen AG ohne Streitwertgrenze, § 23 Nr. 2a GVG).
2. **Örtlich** rechtlich: §§ 12, 13 ZPO Allgemeiner Gerichtsstand, § 29 ZPO Erfüllungsort, § 29c ZPO Verbraucherverträge, § 38 ZPO Gerichtsstandsvereinbarung; grenzüberschreitend Brüssel Ia VO 1215/2012.
3. **Online-Adressrecherche**: `justizadressen.nrw.de` (PLZ/Ort) und bundesweit `justiz.de`; Quelle und Abrufdatum dokumentieren.
4. BeA-SAFE-ID: aus dem beA-Adressbuch zu ergänzen.

## Leitentscheidungen (Auswahl, siehe `references/rechtsprechung/INDEX.md`)

- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 70 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Forderungsmanagement Klagewerkstatt-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Spezial-Skills aus diesem Plugin vor und führt in einen kl... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmat... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Forderungsmanagement Klagewerkstatt.; Welche Unterlagen brauchen Sie?; Welcher... |
| `anspruchs` | Nutze dies, wenn Anspruchs: Schriftsatz-, Brief- und Memo-Bausteine im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Anspruchs: Schriftsatz-, Brief- und Memo-Bausteine prüfen.; Erstelle eine A... |
| `belegte` | Nutze dies, wenn Belegte: Compliance-Dokumentation und Aktenvermerk im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `belegte-faellige-fmkw` | Nutze dies, wenn Spezial Belegte Compliance Dokumentation Und Akte, Spezial Faellige Zahlen Schwellen Und Berechnung, Spezial Fmkw Mandantenkommunikation Entscheidungsvorlage im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeit... |
| `bgb-zpo-fmkw-saumselig-fmkw-titulierung` | Nutze dies, wenn Bgb Zpo Forderungsnormcheck, Fmkw Saumselig Streitig Erfahrung Spezial, Fmkw Titulierung Streckung Leitfaden im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Bgb Zpo Forderung... |
| `chronologie-und-belegmatrix` | Nutze dies, wenn Chronologie und Belegmatrix im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Chronologie und Belegmatrix prüfen.; Erstelle eine Arbeitsfassung zu Chronologie und Belegmatrix.;... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Forderungsmanagement Klagewerkstatt.; Welche Unterlagen brauchen Sie?; Welc... |
| `faellige` | Nutze dies, wenn Faellige: Zahlen, Schwellenwerte und Berechnung im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Faellige: Zahlen, Schwellenwerte und Berechnung prüfen.; Erstelle eine Arbeits... |
| `fmkw` | Nutze dies, wenn Fmkw: Mandantenkommunikation und Entscheidungsvorlage im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Fmkw: Mandantenkommunikation und Entscheidungsvorlage prüfen.; Erstelle... |
| `fmkw-02` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Fmkw Mahnverfahren Bauleiter im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-te... |
| `fmkw-mahnverfahren-bauleiter` | Bauleiter automatisiertes Mahnverfahren §§ 688 ff. ZPO: Mahnbescheid, Widerspruch, Vollstreckungsbescheid. Pruefraster fuer Glaeubiger und Inkassodienstleister. |
| `fmkw-saumselig-streitig-erfahrung-spezial` | Spezialfall saeumiges Verfahren und streitiges Verfahren nach Widerspruch: prozessuale Weichen, Beweislast, Schriftsaetze. Pruefraster fuer Klaegeranwalt. |
| `fmkw-titulierung-streckung-leitfaden` | Leitfaden Titulierung mit Ratenzahlung und Streckung: Anerkenntnis, Schuldanerkenntnis, Ratenvereinbarung mit Vollstreckungsmoeglichkeit. Pruefraster fuer Inkassoanwalt. |
| `fmkw-verbraucherklage-cookies-rdg-spezial` | Spezialfall Verbraucherklageinkasso und RDG-Grenzen: Massenforderungen, Sammelklage als Modell, Anti-Claim-Klausel. Pruefraster fuer Legal-Tech und Anwaelte. |
| `fmkw-verbraucherklage-forderung` | Nutze dies, wenn Fmkw Verbraucherklage Cookies Rdg Spezial, Forderung Anwaltshonorar Rvg, Forderung Arzthonorar Goae im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Fmkw Verbraucherklage Cook... |
| `forderung-anwaltshonorar-rvg` | Anwaltshonorar nach RVG einklagen: Vereinbarung § 3a RVG, Vergleich, Streitwertfestsetzung, Honorartoleranz. Pruefraster: Wirksame Vergueltungsvereinbarung? Mandantenbeschwerde Rechtsanwaltskammer? Output: Klageschrift und Vorpruefung. |
| `forderung-arzthonorar-goae` | Arzthonorar nach GOAE/GOZ: Faelligkeit § 12 GOAE Rechnungserteilung mit Beschreibung der Leistungen, Wirksamkeit § 4 GOAE, Steigerungsfaktor. Streitige Punkte: angemessene Honorarsteigerung. Output: Klageschrift. |
| `forderung-aus-werkvertrag-bgb-bau` | Forderung aus Werk-/Bauvertrag: Faelligkeit § 641 BGB, Abnahme/Abnahmewirkungen, Schlussrechnungspruefung, Sicherungseinbehalt, Maengelrechte als Einwendung. Output: Pruefraster und Schriftsatz-Module. |
| `forderung-gegen-gesellschafter-13-gmbhg` | Forderung gegen GmbH-Gesellschafter: § 19 sowie § 31 GmbHG (Einlagepflicht, Rueckforderung), § 13 Abs. 2 GmbHG Trennungsprinzip, Durchgriffshaftung bei existenzvernichtendem Eingriff (BGH II ZR 78/06). Pruefraster. |
| `forderung-gegen-insolventen-schuldner` | Forderung gegen insolventen Schuldner: Anmeldung zur Tabelle § 174 InsO, Frist Pruefungstermin, abgesonderte Befriedigung pruefen, Aussonderungsrechte § 47 InsO. Strategische Bewertung Aussichten. |
| `forderung-gesellschafter-insolventen` | Nutze dies, wenn Forderung Gegen Gesellschafter 13 Gmbhg, Forderung Gegen Insolventen Schuldner, Forderung Im Ausland Vollstrecken im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Forderung Ge... |
| `forderung-im-ausland-vollstrecken` | Forderung im EU-Ausland vollstrecken: Brueessel Ia VO (EU 1215/2012), Europaeischer Vollstreckungstitel (EuVTVO), Europ. Mahnverfahren (EuMVVO), Europ. Bagatellverfahren (EuGFVO). Output: Verfahrenswahl-Memo. |
| `forderung-mietruckstand-zahlungsklage` | Mietrueckstand: Zahlungsklage parallel zu Raumungsklage § 543 BGB. Pflicht Mahnung? In der Regel nicht erforderlich (kalendermaessig bestimmt). Schonfristregelung § 569 Abs. 3 BGB. Output: Klageschrift Zahlungsklage + Raumungsklage. |
| `forderung-mietruckstand-zahlungsklage-02` | Nutze dies, wenn Forderung Mietruckstand Zahlungsklage, Forderung Verbraucher Erleichterungen, Forderung Zwangsvollstreckung Ueberblick im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Forderu... |
| `forderung-verbraucher-erleichterungen` | Forderung gegen Verbraucher: Verbraucherschutzregeln, AGB-Kontrolle §§ 305 ff. BGB, Belehrungspflichten Verzugskosten § 288 Abs. 4 BGB, Kostenausschluss § 91 ZPO bei Bagatellsachen. Pruefraster. |
| `forderung-zwangsvollstreckung-ueberblick` | Zwangsvollstreckung Ueberblick: Mobiliarvollstreckung Gerichtsvollzieher §§ 808 ff. ZPO, Forderungspfaendung § 829 ZPO, Lohnpfaendung mit Pfaendungstabelle, Immobiliarvollstreckung Zwangshypothek/Versteigerung. Output: Strategiememo Voll... |
| `forderungen-interessen` | Nutze dies, wenn Forderungen: Mehrparteienkonflikt und Interessenmatrix im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Forderungen: Mehrparteienkonflikt und Interessenmatrix prüfen.; Erstell... |
| `forderungen-interessen-forderungsmanagement` | Nutze dies, wenn Spezial Forderungen Mehrparteien Konflikt Und Interessen, Spezial Forderungsmanagement Tatbestand Beweis Und Belege, Spezial Gatekeeper Verhandlung Vergleich Und Eskalation im Plugin Forderungsmanagement Klagewerkstatt k... |
| `forderungsmanagement` | Nutze dies, wenn Forderungsmanagement: Tatbestandsmerkmale, Beweisfragen und Beleglage im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Forderungsmanagement: Tatbestandsmerkmale, Beweisfragen... |
| `forderungsmanagement-aufnahme` | Forderung systematisch aufnehmen: Glaeubiger, Schuldner, Rechtsgrund, Hauptforderung, Nebenforderungen (Zinsen § 288 BGB, vorgerichtliche Anwaltskosten, Mahngebuehren), Faelligkeit, Verjaehrungsbeginn. Output: vollstaendige Forderungsbes... |
| `forderungsmanagement-aufnahme-inkasso` | Nutze dies, wenn Forderungsmanagement Aufnahme, Inkasso Zahlungsklage Ersteller, Klagevorlage Aus Eigenen Mustern im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Forderungsmanagement Aufnahme... |
| `freigegeben-fehlerkatalog` | Nutze dies, wenn Freigegeben Fehlerkatalog im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `fristen-und-risikoampel` | Nutze dies, wenn Fristen- und Risikoampel im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Fristen- und Risikoampel prüfen.; Erstelle eine Arbeitsfassung zu Fristen- und Risikoampel.; Welche N... |
| `gatekeeper` | Nutze dies, wenn Gatekeeper: Verhandlung, Vergleich und Eskalation im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Gatekeeper: Verhandlung, Vergleich und Eskalation prüfen.; Erstelle eine Arb... |
| `inkasso` | Nutze dies, wenn Inkasso: Risikoampel, Gegenargumente und Verteidigungslinien im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Inkasso: Risikoampel, Gegenargumente und Verteidigungslinien prüf... |
| `inkasso-klage-klagefreigabe-belegte` | Nutze dies, wenn Spezial Inkasso Risikoampel Und Gegenargumente, Spezial Klage Formular Portal Und Einreichung, Spezial Klagefreigabe Belegte Forderung im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöse... |
| `inkasso-zahlungsklage-ersteller` | Gläubiger hat offene Forderung die er vor Gericht einklagen will. Zahlungsklage Forderungsmanagement §§ 286 ff. BGB ZPO. Prüfraster: Mahnvorlauf Anspruchs-Gatekeeper fällig belegt Teilzahlung Verzug Inkassokosten § 288 BGB Gerichtsortfin... |
| `klage` | Nutze dies, wenn Klage: Formular, Portal und Einreichungslogik im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Klage: Formular, Portal und Einreichungslogik prüfen.; Erstelle eine Arbeitsfass... |
| `klage-aus-eigenem-skill` | Kanzlei hat hauseigenes Klage-Plugin (klagewerkstatt-kanzlei) installiert und will damit Klagen aus eigenem Sachverhalt erstellen. Laufzeit-Variante Klagewerkstatt. Prüfraster: Sachverhalt Beklagtenadresse Zuständigkeit §§ 12 13 29 29c Z... |
| `klagefreigabe-belegte-forderung` | Klagefreigabe nur für fällige, belegte und prozessreife Forderungen: führt schnell durch Sachverhalt, Rechtsgrundlagen, Belege, Risiken und erzeugt einen verwertbaren nächsten Output. |
| `klagevorlage-aus-eigenen-mustern` | Kanzlei will einmalig ihre eigenen Klagemuster in ein wiederverwendbares Plugin destillieren. Lernlauf Klagewerkstatt. Prüfraster: Eigene Muster Urteile Kommentare hochladen Extraktion einer Standardklage-Vorlage Zuständigkeitsprüfung on... |
| `klagewerkstatt` | Nutze dies, wenn Klagewerkstatt: Erstprüfung, Rollenklärung und Mandatsziel im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Klagewerkstatt: Erstprüfung, Rollenklärung und Mandatsziel prüfen.;... |
| `klagewerkstatt-mahnvorlauf-saumselig` | Nutze dies, wenn Spezial Klagewerkstatt Erstpruefung Und Mandatsziel, Spezial Mahnvorlauf Dokumentenmatrix Und Lueckenliste, Spezial Saumselig Sonderfall Und Edge Case im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werd... |
| `klare-quellenkarte` | Nutze dies, wenn Klare Quellenkarte im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `mahnbescheid-online-mahnung-aussergerichtlich` | Nutze dies, wenn Mahnbescheid Online Mb, Mahnung Aussergerichtlich Stufenmodell, Spezial Anspruchs Schriftsatz Brief Und Memo Bausteine im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Mahnbes... |
| `mahnbescheid-online-mb` | Mahnbescheid Online-Mahnbescheid (Online-MB): wann sinnvoll, Voraussetzungen § 690 ZPO, zustaendiges Mahngericht (zentrales Online-Mahngericht), Online-Antrag, Zustellung an Schuldner, Folge Widerspruch fuehrt in streitiges Verfahren. Pr... |
| `mahnung-aussergerichtlich-stufenmodell` | Aussergerichtliches Mahnverfahren in Stufen: 1. Mahnung kostenfrei, 2. Mahnung mit Frist, 3. Mahnung mit Anwaltsandrohung. Beleg fuer Verzugseintritt § 286 BGB, Schwelle § 288 Abs. 2 BGB. Output: Mahnschreiben-Templates. |
| `mahnverfahren-beweislast` | Nutze dies, wenn Spezial Mahnverfahren Beweislast Und Darlegungslast, Spezial Zustaendigkeitspruefung Fristen Form Und Zustaendigkeit, Forderung Aus Werkvertrag Bgb Bau im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet wer... |
| `mahnverfahren-beweislast-darlegungslast` | Nutze dies, wenn Mahnverfahren: Beweislast, Darlegungslast und Substantiierung im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Mahnverfahren: Beweislast, Darlegungslast und Substantiierung pr... |
| `mahnvorlauf` | Nutze dies, wenn Mahnvorlauf: Dokumentenmatrix, Lückenliste und Nachforderung im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `mandantenkommunikation` | Nutze dies, wenn Mandantenkommunikation im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Mandantenkommunikation prüfen.; Erstelle eine Arbeitsfassung zu Mandantenkommunikation.; Welche Normen... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `redteam-qualitygate` | Nutze dies, wenn Red-Team Qualitygate im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `saumselig-sonderfall-edge-case` | Nutze dies, wenn Saumselig: Sonderfall und Edge-Case-Prüfung im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Saumselig: Sonderfall und Edge-Case-Prüfung prüfen.; Erstelle eine Arbeitsfassung... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `urkundenprozess-pruefen` | Urkundenprozess §§ 592-605 ZPO pruefen: Anspruch auf Zahlung auf Urkunden gestuetzt (Vertrag, Wechsel, Scheck). Vorteil: schnelles Vorbehaltsurteil. Pruefraster: passt der Fall? Output: Klageschrift im Urkundenprozess. |
| `verjaehrung-pruefen` | Verjaehrung pruefen: Regelverjaehrung § 195 BGB drei Jahre ab Schluss des Jahres, in dem Forderung entstanden ist. Sonderverjaehrungen (Werklohn 3 J., Kaufpreis 3 J., Schadensersatz §§ 199 ff. BGB). Hemmung § 203 BGB, Neubeginn § 212 BGB. |
| `verjaehrung-vollstreckungsbescheid-folgen` | Nutze dies, wenn Verjaehrung Prüfen, Vollstreckungsbescheid Und Folgen, Zahlungsklage Erstellen im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Verjaehrung Prüfen, Vollstreckungsbescheid Und... |
| `vollstreckungsbescheid-und-folgen` | Vollstreckungsbescheid §§ 699 und 700 ZPO: Voraussetzung kein Widerspruch innerhalb 2 Wochen, Vollstreckungstitel fuer 30 Jahre, Einspruch noch moeglich (gleicher Fristrahmen wie Widerspruch nach Zustellung). Strategische Hinweise. |
| `werden` | Nutze dies, wenn Werden: Internationaler Bezug und Schnittstellen im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Werden: Internationaler Bezug und Schnittstellen prüfen.; Erstelle eine Arbei... |
| `werden-zahlungsklage-urkundenprozess` | Nutze dies, wenn Spezial Werden Internationaler Bezug Und Schnittstellen, Spezial Zahlungsklage Behörden Gericht Und Registerweg, Urkundenprozess Prüfen im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslös... |
| `zahlungsklage` | Nutze dies, wenn Zahlungsklage: Behörden-, Gerichts- oder Registerweg im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Zahlungsklage: Behörden-, Gerichts- oder Registerweg prüfen.; Erstelle ei... |
| `zahlungsklage-erstellen` | Zahlungsklage erstellen: Klageschrift §§ 253 ff. ZPO, Klageantrag, Tatbestand, Beweismittel, Anlagenverzeichnis. Streitwertangabe, Belehrung Rechtsanwaltszwang, Anschrift Schuldner. Output: Klageschrift-Geruest fuer das LG/AG. |
| `zinsberechnung-288-bgb` | Zinsberechnung § 288 BGB: Verbraucherzinsen 5 Prozentpunkte ueber Basiszins, B2B 9 Prozentpunkte. Verzugseintritt § 286 BGB. Pauschale 40 EUR § 288 Abs. 5 BGB im B2B-Geschaeft. Output: Zinsberechnungs-Tabelle. |
| `zinsberechnung-bgb` | Nutze dies, wenn Zinsberechnung 288 Bgb im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Zinsberechnung 288 Bgb prüfen.; Erstelle eine Arbeitsfassung zu Zinsberechnung 288 Bgb.; Welche Normen... |
| `zustaendigkeitspruefung` | Nutze dies, wenn Zustaendigkeitspruefung: Fristen, Form, Zuständigkeit und Rechtsweg im Plugin Forderungsmanagement Klagewerkstatt konkret bearbeitet werden soll. Auslöser: Bitte Zustaendigkeitspruefung: Fristen, Form, Zuständigkeit und... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
