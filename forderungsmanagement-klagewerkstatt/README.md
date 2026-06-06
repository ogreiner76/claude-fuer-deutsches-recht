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

Automatisch generierte Komplett-Liste aller 84 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `belegte-faellige-fmkw` | Belegte: Compliance-Dokumentation und Aktenvermerk im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenst... |
| `bgb-zpo-fmkw-saumselig-titulierung` | BGB/ZPO-Forderungsnormcheck: prüft Anspruch, Fälligkeit, Verzug, Zinsen, Verjährung, Mahnverfahren, Klage, Zustellung demnächst, Titel, Klausel, Zustellung und Vollstreckung anhand aktueller Normen: eigenständiges Prüffeld mit Norm-/Quel... |
| `erstpruefung-forderung-rollen-mandatsziel` | Klagewerkstatt: Erstprüfung, Rollenklärung und Mandatsziel im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3. We... |
| `fmkw-mahnverfahren-bauleiter` | Bauleiter automatisiertes Mahnverfahren §§ 688 ff. ZPO: Mahnbescheid, Widerspruch, Vollstreckungsbescheid. Pruefraster fuer Glaeubiger und Inkassodienstleister. |
| `fmkw-saumselig-streitig-erfahrung-spezial` | Spezialfall saeumiges Verfahren und streitiges Verfahren nach Widerspruch: prozessuale Weichen, Beweislast, Schriftsaetze. Pruefraster fuer Klaegeranwalt. |
| `fmkw-titulierung-streckung-leitfaden` | Leitfaden Titulierung mit Ratenzahlung und Streckung: Anerkenntnis, Schuldanerkenntnis, Ratenvereinbarung mit Vollstreckungsmoeglichkeit. Pruefraster fuer Inkassoanwalt. |
| `fmkw-verbraucherklage-cookies-rdg-spezial` | Spezialfall Verbraucherklageinkasso und RDG-Grenzen: Massenforderungen, Sammelklage als Modell, Anti-Claim-Klausel. Pruefraster fuer Legal-Tech und Anwaelte. |
| `fmkw-verbraucherklage-forderung` | Spezialfall Verbraucherklageinkasso und RDG-Grenzen: Massenforderungen, Sammelklage als Modell, Anti-Claim-Klausel. Pruefraster fuer Legal-Tech und Anwaelte: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Ou... |
| `forderung-anwaltshonorar-rvg` | Anwaltshonorar nach RVG einklagen: Vereinbarung § 3a RVG, Vergleich, Streitwertfestsetzung, Honorartoleranz. Pruefraster: Wirksame Vergueltungsvereinbarung? Mandantenbeschwerde Rechtsanwaltskammer? Output: Klageschrift und Vorpruefung. |
| `forderung-arzthonorar-goae` | Arzthonorar nach GOAE/GOZ: Faelligkeit § 12 GOAE Rechnungserteilung mit Beschreibung der Leistungen, Wirksamkeit § 4 GOAE, Steigerungsfaktor. Streitige Punkte: angemessene Honorarsteigerung. Output: Klageschrift. |
| `forderung-aus-werkvertrag-bgb-bau` | Forderung aus Werk-/Bauvertrag: Faelligkeit § 641 BGB, Abnahme/Abnahmewirkungen, Schlussrechnungspruefung, Sicherungseinbehalt, Maengelrechte als Einwendung. Output: Pruefraster und Schriftsatz-Module. |
| `forderung-gegen-gesellschafter-13-gmbhg` | Forderung gegen GmbH-Gesellschafter: § 19 sowie § 31 GmbHG (Einlagepflicht, Rueckforderung), § 13 Abs. 2 GmbHG Trennungsprinzip, Durchgriffshaftung bei existenzvernichtendem Eingriff (BGH II ZR 78/06). Pruefraster. |
| `forderung-gegen-insolventen-schuldner` | Forderung gegen insolventen Schuldner: Anmeldung zur Tabelle § 174 InsO, Frist Pruefungstermin, abgesonderte Befriedigung pruefen, Aussonderungsrechte § 47 InsO. Strategische Bewertung Aussichten. |
| `forderung-gesellschafter-insolventen` | Forderung gegen GmbH-Gesellschafter: § 19 sowie § 31 GmbHG (Einlagepflicht, Rueckforderung), § 13 Abs. 2 GmbHG Trennungsprinzip, Durchgriffshaftung bei existenzvernichtendem Eingriff (BGH II ZR 78/06). Pruefraster: eigenständiges Prüffel... |
| `forderung-im-ausland-vollstrecken` | Forderung im EU-Ausland vollstrecken: Brueessel Ia VO (EU 1215/2012), Europaeischer Vollstreckungstitel (EuVTVO), Europ. Mahnverfahren (EuMVVO), Europ. Bagatellverfahren (EuGFVO). Output: Verfahrenswahl-Memo. |
| `forderung-mietruckstand-zahlungsklage` | Mietrueckstand: Zahlungsklage parallel zu Raumungsklage § 543 BGB. Pflicht Mahnung? In der Regel nicht erforderlich (kalendermaessig bestimmt). Schonfristregelung § 569 Abs. 3 BGB. Output: Klageschrift Zahlungsklage + Raumungsklage. |
| `forderung-verbraucher-erleichterungen` | Forderung gegen Verbraucher: Verbraucherschutzregeln, AGB-Kontrolle §§ 305 ff. BGB, Belehrungspflichten Verzugskosten § 288 Abs. 4 BGB, Kostenausschluss § 91 ZPO bei Bagatellsachen. Pruefraster. |
| `forderung-zustaendigkeitspruefung-mahngericht` | Zustaendigkeitspruefung: Fristen, Form, Zuständigkeit und Rechtsweg im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werd... |
| `forderung-zwangsvollstreckung-ueberblick` | Zwangsvollstreckung Ueberblick: Mobiliarvollstreckung Gerichtsvollzieher §§ 808 ff. ZPO, Forderungspfaendung § 829 ZPO, Lohnpfaendung mit Pfaendungstabelle, Immobiliarvollstreckung Zwangshypothek/Versteigerung. Output: Strategiememo Voll... |
| `forderungen-interessen` | Forderungen: Mehrparteienkonflikt und Interessenmatrix im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3. Welche... |
| `forderungen-interessen-forderungsmanagement` | Forderungen: Mehrparteienkonflikt und Interessenmatrix im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eig... |
| `forderungen-klagewerkstatt-start-chronologie-fristen` | Einstieg, Schnelltriage und Fallrouting im Forderungsmanagement Klagewerkstatt-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Fachmodule aus diesem Plugin vor und führt in einen klaren Arbe... |
| `forderungsmanagement-aufnahme` | Forderung systematisch aufnehmen: Glaeubiger, Schuldner, Rechtsgrund, Hauptforderung, Nebenforderungen (Zinsen § 288 BGB, vorgerichtliche Anwaltskosten, Mahngebuehren), Faelligkeit, Verjaehrungsbeginn. Output: vollstaendige Forderungsbes... |
| `forderungsmanagement-aufnahme-inkasso` | Forderung systematisch aufnehmen: Glaeubiger, Schuldner, Rechtsgrund, Hauptforderung, Nebenforderungen (Zinsen § 288 BGB, vorgerichtliche Anwaltskosten, Mahngebuehren), Faelligkeit, Verjaehrungsbeginn. Output: vollstaendige Forderungsbes... |
| `forderungsmanagement-klagewerkstatt-anschluss-routing` | Anschluss-Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `forderungsmanagement-klagewerkstatt-anspruchs-schriftsatz-brief` | Anspruchs: Schriftsatz-, Brief- und Memo-Bausteine im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3. Welche Fri... |
| `forderungsmanagement-klagewerkstatt-belegte-compliance` | Belegte: Compliance-Dokumentation und Aktenvermerk im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3. Welche Fri... |
| `forderungsmanagement-klagewerkstatt-chronologie-und-belegmatrix` | Chronologie und Belegmatrix im Plugin Forderungsmanagement Klagewerkstatt: 1. Wer fragt in welcher Rolle? 2. Was ist das gewünschte Ergebnis? 3. Gibt es Fristen, Termine, Zustellungen, Zahlungen oder Sanktionen? 4. Welche Unterlagen, Dat... |
| `forderungsmanagement-klagewerkstatt-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `forderungsmanagement-klagewerkstatt-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `forderungsmanagement-klagewerkstatt-faellige-zahlen` | Faellige: Zahlen, Schwellenwerte und Berechnung im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3. Welche Frist,... |
| `forderungsmanagement-klagewerkstatt-fmkw-mandantenkommunikation` | Fmkw: Mandantenkommunikation und Entscheidungsvorlage im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3. Welche... |
| `forderungsmanagement-klagewerkstatt-forderung-mietruckstand` | Mietrueckstand: Zahlungsklage parallel zu Raumungsklage § 543 BGB. Pflicht Mahnung? In der Regel nicht erforderlich (kalendermaessig bestimmt). Schonfristregelung § 569 Abs. 3 BGB. Output: Klageschrift Zahlungsklage + Raumungsklage: eige... |
| `forderungsmanagement-klagewerkstatt-fristen-und-risikoampel` | Fristen- und Risikoampel im Plugin Forderungsmanagement Klagewerkstatt: 1. Wer fragt in welcher Rolle? 2. Was ist das gewünschte Ergebnis? 3. Gibt es Fristen, Termine, Zustellungen, Zahlungen oder Sanktionen? 4. Welche Unterlagen, Daten... |
| `forderungsmanagement-klagewerkstatt-gatekeeper-verhandlung` | Gatekeeper: Verhandlung, Vergleich und Eskalation im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3. Welche Fris... |
| `forderungsmanagement-klagewerkstatt-inkasso-risikoampel` | Inkasso: Risikoampel, Gegenargumente und Verteidigungslinien im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3.... |
| `forderungsmanagement-klagewerkstatt-kaltstart-triage` | Einstieg, Schnelltriage und Fallrouting im Forderungsmanagement Klagewerkstatt-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Fachmodule aus diesem Plugin vor und führt in einen klaren Arbe... |
| `forderungsmanagement-klagewerkstatt-klage` | Klage: Formular, Portal und Einreichungslogik im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3. Welche Frist, Z... |
| `forderungsmanagement-klagewerkstatt-mahnvorlauf-dokumentenmatrix` | Mahnvorlauf: Dokumentenmatrix, Lückenliste und Nachforderung im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3.... |
| `forderungsmanagement-klagewerkstatt-mandantenkommunikation` | Mandantenkommunikation im Plugin Forderungsmanagement Klagewerkstatt: 1. Wer fragt in welcher Rolle? 2. Was ist das gewünschte Ergebnis? 3. Gibt es Fristen, Termine, Zustellungen, Zahlungen oder Sanktionen? 4. Welche Unterlagen, Daten od... |
| `forderungsmanagement-klagewerkstatt-output-waehlen` | Output wählen im Plugin Forderungsmanagement Klagewerkstatt: Diese Output-Weiche für Forderungsmanagement Klagewerkstatt entscheidet, ob Memo, Antrag, Schriftsatz, Tabelle, Risikoampel, Fragenliste oder Mandantenbrief der richtige nächst... |
| `forderungsmanagement-klagewerkstatt-quellen-livecheck` | Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `forderungsmanagement-klagewerkstatt-redteam-qualitygate` | Red-Team Qualitygate: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `forderungsmanagement-klagewerkstatt-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `forderungsmanagement-klagewerkstatt-werden-internationaler-bezug` | Werden: Internationaler Bezug und Schnittstellen im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3. Welche Frist... |
| `forderungsmanagement-klagewerkstatt-workflow` | Mandantenkommunikation: übersetzt das Ergebnis in eine klare Nachricht mit Entscheidungspunkten, Risiken und nächsten Schritten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `forderungsmanagement-klagewerkstatt-zahlungsklage-behoerden` | Zahlungsklage: Behörden-, Gerichts- oder Registerweg im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3. Welche F... |
| `forderungsmanagement-mahnung-klage-vollstreckung` | Forderungsmanagement: Tatbestandsmerkmale, Beweisfragen und Beleglage im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert we... |
| `freigegeben-fehlerkatalog` | Freigegeben Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `inkasso-klage-klagefreigabe-belegte` | Inkasso: Risikoampel, Gegenargumente und Verteidigungslinien im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfun... |
| `inkasso-zahlungsklage-ersteller` | Gläubiger hat offene Forderung die er vor Gericht einklagen will. Zahlungsklage Forderungsmanagement §§ 286 ff. BGB ZPO. Prüfraster: Mahnvorlauf Anspruchs-Gatekeeper fällig belegt Teilzahlung Verzug Inkassokosten § 288 BGB Gerichtsortfin... |
| `klage-aus-eigenem-skill` | Kanzlei hat hauseigenes Klage-Plugin (klagewerkstatt-kanzlei) installiert und will damit Klagen aus eigenem Sachverhalt erstellen. Laufzeit-Variante Klagewerkstatt. Prüfraster: Sachverhalt Beklagtenadresse Zuständigkeit §§ 12 13 29 29c Z... |
| `klagefreigabe-belegte-forderung` | Klagefreigabe nur für fällige, belegte und prozessreife Forderungen: führt schnell durch Sachverhalt, Rechtsgrundlagen, Belege, Risiken und erzeugt einen verwertbaren nächsten Output. |
| `klagevorlage-aus-eigenen-mustern` | Kanzlei will einmalig ihre eigenen Klagemuster in ein wiederverwendbares Plugin destillieren. Lernlauf Klagewerkstatt. Prüfraster: Eigene Muster Urteile Kommentare hochladen Extraktion einer Standardklage-Vorlage Zuständigkeitsprüfung on... |
| `klagewerkstatt-mahnvorlauf-saumselig` | Klagewerkstatt: Erstprüfung, Rollenklärung und Mandatsziel im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung:... |
| `klare-quellenkarte` | Klare Quellenkarte: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `mahnbescheid-online-mahnung-aussergerichtlich` | Mahnbescheid Online-Mahnbescheid (Online-MB): wann sinnvoll, Voraussetzungen § 690 ZPO, zustaendiges Mahngericht (zentrales Online-Mahngericht), Online-Antrag, Zustellung an Schuldner, Folge Widerspruch fuehrt in streitiges Verfahren. Pr... |
| `mahnbescheid-online-mb` | Mahnbescheid Online-Mahnbescheid (Online-MB): wann sinnvoll, Voraussetzungen § 690 ZPO, zustaendiges Mahngericht (zentrales Online-Mahngericht), Online-Antrag, Zustellung an Schuldner, Folge Widerspruch fuehrt in streitiges Verfahren. Pr... |
| `mahnung-aussergerichtlich-stufenmodell` | Aussergerichtliches Mahnverfahren in Stufen: 1. Mahnung kostenfrei, 2. Mahnung mit Frist, 3. Mahnung mit Anwaltsandrohung. Beleg fuer Verzugseintritt § 286 BGB, Schwelle § 288 Abs. 2 BGB. Output: Mahnschreiben-Templates. |
| `mahnverfahren-beweislast` | Mahnverfahren: Beweislast, Darlegungslast und Substantiierung im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfu... |
| `mahnverfahren-beweislast-darlegungslast` | Mahnverfahren: Beweislast, Darlegungslast und Substantiierung im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3.... |
| `saumselig-sonderfall-edge-case` | Saumselig: Sonderfall und Edge-Case-Prüfung im Plugin Forderungsmanagement Klagewerkstatt: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3. Welche Frist, Zus... |
| `spezial-anspruchs-schriftsatz-brief-und-memo-bausteine` | Anspruchs: Schriftsatz-, Brief- und Memo-Bausteine im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenst... |
| `spezial-faellige-zahlen-schwellen-und-berechnung` | Faellige: Zahlen, Schwellenwerte und Berechnung im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständ... |
| `spezial-fmkw-mandantenkommunikation-entscheidungsvorlage` | Fmkw: Mandantenkommunikation und Entscheidungsvorlage im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eige... |
| `spezial-forderungsmanagement-tatbestand-beweis-und-belege` | Forderungsmanagement: Tatbestandsmerkmale, Beweisfragen und Beleglage im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Stand... |
| `spezial-gatekeeper-verhandlung-vergleich-und-eskalation` | Gatekeeper: Verhandlung, Vergleich und Eskalation im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenstä... |
| `spezial-klage-formular-portal-und-einreichung` | Klage: Formular, Portal und Einreichungslogik im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständig... |
| `spezial-klagefreigabe-belegte-forderung` | Klagefreigabe nur für fällige, belegte und prozessreife Forderungen: führt schnell durch Sachverhalt, Rechtsgrundlagen, Belege, Risiken und erzeugt einen verwertbaren nächsten Output: eigenständiges Prüffeld mit Norm-/Quellencheck, Risik... |
| `spezial-mahnvorlauf-dokumentenmatrix-und-lueckenliste` | Mahnvorlauf: Dokumentenmatrix, Lückenliste und Nachforderung im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfun... |
| `spezial-saumselig-sonderfall-und-edge-case` | Saumselig: Sonderfall und Edge-Case-Prüfung im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges... |
| `spezial-zahlungsklage-behoerden-gericht-und-registerweg` | Zahlungsklage: Behörden-, Gerichts- oder Registerweg im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigen... |
| `spezial-zustaendigkeitspruefung-fristen-form-und-zustaendigkeit` | Zustaendigkeitspruefung: Fristen, Form, Zuständigkeit und Rechtsweg im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standar... |
| `urkundenprozess-pruefen` | Urkundenprozess §§ 592-605 ZPO pruefen: Anspruch auf Zahlung auf Urkunden gestuetzt (Vertrag, Wechsel, Scheck). Vorteil: schnelles Vorbehaltsurteil. Pruefraster: passt der Fall? Output: Klageschrift im Urkundenprozess. |
| `verjaehrung-pruefen` | Verjaehrung pruefen: Regelverjaehrung § 195 BGB drei Jahre ab Schluss des Jahres, in dem Forderung entstanden ist. Sonderverjaehrungen (Werklohn 3 J., Kaufpreis 3 J., Schadensersatz §§ 199 ff. BGB). Hemmung § 203 BGB, Neubeginn § 212 BGB. |
| `verjaehrung-vollstreckungsbescheid-folgen` | Verjaehrung pruefen: Regelverjaehrung § 195 BGB drei Jahre ab Schluss des Jahres, in dem Forderung entstanden ist. Sonderverjaehrungen (Werklohn 3 J., Kaufpreis 3 J., Schadensersatz §§ 199 ff. BGB). Hemmung § 203 BGB, Neubeginn § 212 BGB... |
| `vollstreckungsbescheid-und-folgen` | Vollstreckungsbescheid §§ 699 und 700 ZPO: Voraussetzung kein Widerspruch innerhalb 2 Wochen, Vollstreckungstitel fuer 30 Jahre, Einspruch noch moeglich (gleicher Fristrahmen wie Widerspruch nach Zustellung). Strategische Hinweise. |
| `werden-zahlungsklage-urkundenprozess` | Werden: Internationaler Bezug und Schnittstellen im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenstän... |
| `workflow-chronologie-und-belegmatrix` | Chronologie und Belegmatrix: macht aus unordentlichem Material eine Timeline mit Belegstellen und offenen Widersprüchen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `workflow-fristen-und-risikoampel` | Fristen- und Risikoampel: macht eine Sofortampel für Frist, Zuständigkeit, Haftung, Eilbedarf und fehlende Unterlagen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `workflow-redteam-qualitygate` | Red-Team Qualitygate: prüft das Ergebnis auf Halluzinationen, Fristenfehler, Zuständigkeit, Quellen, Beweise und Ton: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `zahlungsklage-erstellen` | Zahlungsklage erstellen: Klageschrift §§ 253 ff. ZPO, Klageantrag, Tatbestand, Beweismittel, Anlagenverzeichnis. Streitwertangabe, Belehrung Rechtsanwaltszwang, Anschrift Schuldner. Output: Klageschrift-Geruest fuer das LG/AG. |
| `zinsberechnung-288-bgb` | Zinsberechnung § 288 BGB: Verbraucherzinsen 5 Prozentpunkte ueber Basiszins, B2B 9 Prozentpunkte. Verzugseintritt § 286 BGB. Pauschale 40 EUR § 288 Abs. 5 BGB im B2B-Geschaeft. Output: Zinsberechnungs-Tabelle. |
| `zinsberechnung-bgb` | Zinsberechnung BGB im Plugin Forderungsmanagement Klagewerkstatt: fachlicher Arbeitsgang mit Prüffeldwahl, Norm-/Quellencheck, Risikoampel und verwertbarem Output. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
