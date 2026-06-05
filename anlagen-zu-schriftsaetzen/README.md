# Anlagen zu Schriftsätzen

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`anlagen-zu-schriftsaetzen`) | [`anlagen-zu-schriftsaetzen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/anlagen-zu-schriftsaetzen.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Werkmann ./. K+B — Werklohnklage Lackieranlage Eschweiler — Anlagenkonvolut-Verfahren** (`anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler`) | [Gesamt-PDF lesen](../testakten/anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler/gesamt-pdf/anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler_gesamt.pdf) | [`testakte-anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist die Anlagenkanzlei im Kleinen: Es nimmt einen Schriftsatz, einen chaotischen Mandantenordner oder ein schon halb nummeriertes Anlagenpaket und macht daraus eine nachvollziehbare, gerichtstaugliche Anlagenstruktur.

Es hilft besonders dann, wenn nicht einfach „Anlage K1 bis K12“ vorliegt, sondern wenn eine echte Akte lebt: E-Mails mit Anhängen, Scans ohne OCR, Excel-Tabellen, Fotos, Chat-Screenshots, mehrere Vertragsfassungen, fremdsprachige Unterlagen, doppelte Dateien, geschwärzte Drittunterlagen, beA-Grenzen, Verfahrenswechsel und Richterhinweise. Das Plugin führt dann nicht nur eine Nummerierung aus, sondern baut eine Arbeitslogik: Welche Tatsache soll durch welche Anlage belegt werden? Welche Datei gehört wirklich zu K1? Welche Unterlagen sind nur Konvolutbestandteil? Welche Anlage ist zu groß, unleserlich, falsch benannt, doppelt oder im Schriftsatz nicht eingeführt?

## Wofür es gedacht ist

| Situation | Was das Plugin macht | Ergebnis |
| --- | --- | --- |
| Klage/Replik liegt vor, Anlagen sind noch ungeordnet | Schriftsatz lesen, Beweisanker erkennen, K-Nummern vorschlagen, Dateien zuordnen | K1/K2/K3-Reihenfolge, Anlagenverzeichnis, Lückenliste |
| Anlagen sind schon nummeriert, aber niemand traut dem Paket | Prüfmodus: Nummern, Zitate, Dateien, Stempel, Namen, Lesbarkeit und beA-Fähigkeit prüfen | Fehlerprotokoll mit Korrekturplan |
| Mandant liefert Datenraum/ZIP/USB-Stick | Duplikate, Fassungen, Hashes, Dateitypen, Zeitfolge und Relevanz sortieren | Belegmatrix und Nachforderungsliste |
| Eine Anlage ist ein Konvolut | Deckblatt, Untergliederung, interne Seiten-/Dokumentlogik, kurze Erläuterung für Gericht | `Anlage K1` mit `K1.1`, `K1.2`, `K1.3` |
| Elektronische Einreichung steht bevor | Dateinamen, PDF/OCR, Paketgrößen, Anlagenverzeichnis, Prüfvermerk | beA-/ERV-taugliches Versandpaket |

## Der K1-Gedanke

Die erste Anlage ist fast nie nur eine Datei. In großen Verfahren ist `K1` häufig der Orientierungspunkt für das Gericht: Vertrag, Auftrag, Rahmenvereinbarung, Nachtrag, Bestätigungsmail, Protokoll oder Dokumentenfamilie. Das Plugin behandelt `K1` deshalb als Sortierproblem:

1. **Was soll K1 beweisen?** Nicht „alles zum Vertrag“, sondern eine konkrete Tatsache.
2. **Ist K1 Einzelanlage oder Konvolut?** Bei Konvolut: Deckblatt, Reihenfolge, interne Kurzbezeichnungen.
3. **Welche Fassungen gibt es?** Entwurf, unterschriebene Fassung, Scan, OCR-PDF, E-Mail-Anhang, spätere Ergänzung.
4. **Welche Datei ist die gerichtliche Fassung?** Die anderen Fassungen wandern in den internen Hash-/Versionenlog.
5. **Wie wird K1 im Schriftsatz eingeführt?** Der Schriftsatz muss den Tatsachenkern selbst tragen; die Anlage belegt ihn nur.

## Drei Arbeitsmodi

**Auto-Benennung:** Der Schriftsatz enthält noch keine Nummern. Das Plugin liest die Beweisstellen und schlägt die Reihenfolge vor.

**Schriftsatz folgt:** Der Schriftsatz enthält bereits `Anlage K...`-Verweise. Das Plugin sucht die passenden Dateien, erkennt Lücken und meldet Überschüsse.

**Prüfmodus:** Ein fertiges Anlagenpaket wird gegengeprüft: `K7` fehlt, `K12` ist doppelt, `K18` wird im Schriftsatz nie erwähnt, `K23` hat keinen OCR-Text, `K31` enthält ungeschwärzte Drittinformationen.

## Typische Outputs

- Anlagenverzeichnis für Gericht und Kanzleiakte.
- K/B/AST/AG-Nummerierung mit eindeutiger Dateinamenkonvention.
- Konvolutdeckblätter für Sammelanlagen.
- Belegmatrix: Tatsachenbehauptung ↔ Schriftsatzstelle ↔ Anlage ↔ Datei ↔ Status.
- Hash-/Duplikat-/Fassungslog für interne Kontrolle.
- beA-Versandliste mit Paketgrößen, Dateinamen und letzten Prüfpunkten.
- Nachforderungsliste an Mandant oder Sachbearbeitung.
- Berichtigungs- oder Nachreichungsplan nach gerichtlichem Hinweis.

## Wichtig

Anlagen ersetzen keinen Tatsachenvortrag. Wenn eine Behauptung entscheidungserheblich ist, muss sie im Schriftsatz stehen. Die Anlage belegt, erläutert oder vertieft; sie darf nicht der Ort sein, an dem der eigentliche Vortrag versteckt wird.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Besonders wichtige Skills

| Skill | Zweck |
| --- | --- |
| `allgemein` | Kaltstart, Triage, Nummernkreis, Ziel-Schriftsatz, K1-Frage und Routing in die passenden Spezial-Skills. |
| `anlagen-zu-schriftsaetzen` | Hauptworkflow für Auto-Benennung, Schriftsatz-folgt-Modus, Prüfmodus und Reparatur nach Hinweis. |
| `k1-sortierwerkstatt` | Baut aus Vertrag, Nachtrag, Mail, Scan und OCR-Fassung eine klare Leit-Anlage `K1` oder ein K1-Konvolut. |
| `schriftsatz-anlagen-mapping` | Verknüpft Tatsachenvortrag, Schriftsatzstelle, Beweisangebot, Anlage und Datei in einer Belegmatrix. |
| `anlagen-duplikate-versionen-hashlog` | Erkennt Dubletten, Versionen, OCR-Kopien und die maßgebliche gerichtliche Fassung. |
| `bea-paketierung-groessen-und-versandplan` | Plant Dateinamen, Paketgrößen, Teilpakete, Begleitvermerk und Eingangskontrolle. |
| `anlagen-qualitygate-finalcheck` | Letzter strenger Check vor Versand: Nummern, Zitate, Dateien, OCR, Schwärzung, Stempel, Paket. |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 97 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Anlagen Zu Schriftsaetzen-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Spezial-Skills aus diesem Plugin vor und führt in einen klaren Arbei... |
| `allgemein-chronologie-belegmatrix-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow C... |
| `anlage-fehlerkatalog` | Nutze dies, wenn Anlage Fehlerkatalog im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `anlage-red-anlagen-anlagenkonvolut-sonderfall` | Nutze dies, wenn Spezial Anlage Red Team Und Qualitaetskontrolle, Spezial Anlagen Tatbestand Beweis Und Belege, Spezial Anlagenkonvolut Sonderfall Und Edge Case, Spezial Arial Mandantenkommunikation Entscheidungsvorlage im Plugin Anlagen... |
| `anlagen` | Nutze dies, wenn Anlagen: Tatbestandsmerkmale, Beweisfragen und Beleglage im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Anlagen: Tatbestandsmerkmale, Beweisfragen und Beleglage prüfen.; Erstelle eine... |
| `anlagen-an-assistenz-uebersetzungspflicht` | Nutze dies, wenn Anlagen Übergabe An Assistenz Und Legal Tech, Anlagen Uebersetzungspflicht, Anlagen Vorlagepflicht 141 Zpo, Anlagen Zur Substantiierung Pflicht im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser... |
| `anlagen-aus-datenraum-und-sharepoint` | Überführt Datenraum-/SharePoint-/DMS-Exporte in Anlagenlogik: Pfade, Versionen, Berechtigungen, Exportzeitpunkt, Index und gerichtliche Fassung. |
| `anlagen-aus-edv-systemen` | Anlagen aus IT-Systemen (ERP-Auszuege, Datenbankexporte, Logdateien): Beweiskraft, Manipulationsschutz, Hashverfahren, Begleitvermerk Erstellung. Empfehlung: Export mit Zeitstempel, Hashprotokoll, ggf. Sachverstaendigenanhoerung Authenti... |
| `anlagen-aus-mandantenmaterial` | Mandantenmaterial in Anlagen umwandeln: Posteingang, E-Mails, PDFs, Vertraege, Rechnungen, Korrespondenz. Markiert geschwaerzte Stellen, prueft Vollstaendigkeit, schlaegt sinnvolle Kuerzungen vor. Erkennt vertrauliche Inhalte, die fuer d... |
| `anlagen-bei-berufung-revision` | Anlagen in Berufung und Revision: bisheriges Anlagenverzeichnis uebernehmen oder neu nummerieren? Empfehlung: Berufungsklaegeranlagen als BK1, BK2 ..., Berufungsbeklagter BB1, BB2 ... Revisionsanlagen sind ueblich nur ergaenzend; Schwerp... |
| `anlagen-bei-eilantrag-eu-arrest` | Anlagen fuer einstweilige Verfuegung und Arrest: Glaubhaftmachung § 294 ZPO durch Anlagen, eidesstattliche Versicherung als Anlage, parate Beweismittel. Hohe Anforderungen Vollstaendigkeit. Output Standard-Anlagensatz fuer wettbewerbsrec... |
| `anlagen-berufung-revision-eilantrag-eu-bilder` | Nutze dies, wenn Anlagen Bei Berufung Revision, Anlagen Bei Eilantrag Eu Arrest, Anlagen Bilder Screenshots, Anlagen Duplikate Versionen Hashlog im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Anlagen... |
| `anlagen-bilder-screenshots` | Bilder und Screenshots als Anlagen: Beweiskraft, Manipulationsanfaelligkeit, EXIF-Daten, Metadaten. Empfehlung: Original und Vergroesserung beifuegen, EXIF-Export anhaengen, Standortdaten transparent machen. Bei Screenshots: voller Brows... |
| `anlagen-check-zustellung-redaktion-dsgvo` | Nutze dies, wenn Anlagen Quality Check Vor Zustellung, Anlagen Redaktion Dsgvo Geschgehg, Anlagen Schwaerzen Anonymisieren, Anlagen Stempel Und Deckblattlogik im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser:... |
| `anlagen-duplikate-versionen-hashlog` | Erkennt doppelte Dateien, verschiedene Fassungen desselben Dokuments, OCR-Kopien, E-Mail-Anhänge und manipulativ wirkende Metadatenbrüche; erzeugt ein Hash- und Versionenprotokoll. |
| `anlagen-elektronische-dokumente-format` | Nutze dies, wenn Anlagen Elektronische Dokumente Spezial, Anlagen Format Und Dateinamen, Anlagen Für Bea Versand, Anlagen Für Glaubhaftmachung im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Ich lade Unterla... |
| `anlagen-elektronische-dokumente-spezial` | Spezialfall elektronische Dokumente als Anlage: ERVV-Vorgaben, qualifizierte elektronische Signatur, Datei-Format-Whitelist nach ERVV, maximale Groesse, beA-Vorgaben, Container-PDF. Pruefraster und Mustertexte fuer Eingang bei Gericht. |
| `anlagen-format-und-dateinamen` | Format und Dateinamen fuer Anlagen: K-01_2024-03-12_Mietvertrag.pdf. Maschinenlesbar, sortierbar, beA-kompatibel. Maximal 3 Ebenen Unterordner, keine Sonderzeichen, keine Umlaute in Dateinamen, durchgehend kleingeschrieben. |
| `anlagen-fuer-bea-versand` | Anlagen fuer beA-Versand vorbereiten: PDF/A-konform, max. zulaessige Dateigroesse beachten, OCR ueber Scans laufen lassen, korrekt strukturiertes XJustiz-Begleitformular. Liste der Anlagen pro Schriftsatz mit Pruefsumme. Verhindert wiede... |
| `anlagen-fuer-glaubhaftmachung` | Spezialworkflow für Eilverfahren: Anlagen, eidesstattliche Versicherung, Screenshots, E-Mails, Fotos und Glaubhaftmachungsdichte nach § 294 ZPO ordnen. |
| `anlagen-haftpflicht-versicherer` | Anlagen-Pflicht gegenueber Haftpflichtversicherer (Berufshaftpflicht, Hausratversicherung, KFZ): welche Anlagen muessen mit Schadenanzeige eingereicht werden, was der Versicherer im Regulierungsverfahren erwartet. Pruefraster aus § 31 VV... |
| `anlagen-konvention-k-b-erlaeutert` | Konvention erklaert und korrekt eingesetzt: K-Anlagen Klaeger, B-Anlagen Beklagter, ZN-Anlagen Zeugen, GA-Anlagen Gutachten, AS-Anlagen Anlagenband. Wann Klein-/Grosschreibung, wann Bindestrich. Wechselt sauber, wenn der Mandant im Vorpr... |
| `anlagen-konvention-mandantenfreundlich` | Anlagen-Konvention mandantenfreundlich: durchlaufende Nummerierung K1 / K2 / K3 ff. fuer Klaegerseite, B1 / B2 / B3 ff. fuer Beklagtenseite, Anlagenbaender, Inhaltsverzeichnis, beA-konforme PDF-Bezeichnung. Mustertext fuer Anlagenverzeic... |
| `anlagen-prozessual-pruefung-spezial` | Spezialfall prozessuale Anlagenpruefung: keine Substantiierung durch blossen Anlagenverweis (BGH-Linie), eigener Vortrag noch im Schriftsatz erforderlich, Tatsachenkern aus Anlage in den Text uebernehmen. Pruefraster und Korrektur-Bauste... |
| `anlagen-quality-check-vor-zustellung` | Quality-Check fuer Anlagenpaket vor Zustellung: Vollstaendigkeit (alle Bezuege im Schriftsatz haben passende Anlage), Lesbarkeit (OCR, kein Schwarzbalken), Schwaerzung (DSGVO und Mandantengeheimnisse), Format (PDF/A wo gefordert). Pruefl... |
| `anlagen-qualitygate-finalcheck` | Finaler Red-Team-Check vor Einreichung: Nummern, Schriftsatzverweise, Dateien, Stempel, OCR, Schwärzung, Dateinamen, beA-Paket, Lücken und Begleitvermerk. |
| `anlagen-redaktion-dsgvo-geschgehg` | Prüft Anlagen vor Einreichung auf personenbezogene Daten, Geschäftsgeheimnisse, Drittmandate, Schwärzungsbedarf und Redaktionsprotokoll. |
| `anlagen-schwaerzen-anonymisieren` | Anlagen schwaerzen und anonymisieren: personenbezogene Daten unbeteiligter Dritter (Mitarbeiter, Kunden, Patienten) entfernen, Kontonummern bis auf letzte 3 Ziffern schwaerzen, Geburtsdaten redigieren, soweit nicht streitrelevant. Mat2-... |
| `anlagen-stempel-und-deckblattlogik` | Legt fest, wie Anlagenstempel, Konvolutdeckblätter, Unteranlagen und Seiten-/Dokumentbezeichnungen aussehen müssen, damit Gericht und Gegner nicht suchen müssen. |
| `anlagen-uebergabe-an-assistenz-und-legal-tech` | Erzeugt klare Arbeitsanweisungen für Kanzleiteam, Assistenz, Legal Tech oder externen Dienstleister: was umbenennen, scannen, stempeln, schwärzen, prüfen. |
| `anlagen-uebersetzungspflicht` | Fremdsprachige Anlagen: Uebersetzungspflicht § 184 GVG. Beglaubigte oder einfache Uebersetzung? Gericht kann Uebersetzung verlangen oder Ablehnung der Beruecksichtigung androhen. Empfehlung: bei zentralen Urkunden beglaubigte Uebersetzun... |
| `anlagen-vorlagepflicht-141-zpo` | Anordnung der Urkundenvorlage nach § 142 ZPO und § 421 ZPO: wann kann das Gericht die Vorlage einer Urkunde anordnen, wann hat ein Beweisfuehrer Anspruch auf Vorlage durch den Gegner. Pruefraster, Antragsformulierung und Folgen Nichtvorl... |
| `anlagen-zu-schriftsaetzen` | Anwalt hat Schriftsatz fertig und muss Anlagen korrekt benennen nummerieren und als PDF-Konvolut aufbereiten. Anlagemanagement gerichtliche Schriftsaetze. Prüfraster: Schriftsatz lesen Beweisstuecke erkennen sortieren beA-konforme Benenn... |
| `anlagen-zur-substantiierung-pflicht` | Anlagen ersetzen keine Substantiierung im Schriftsatz: 'wegen der weiteren Einzelheiten wird auf Anlage K5 verwiesen' ist nicht ausreichend (BGH X ZR 39/16). Pruefraster: Welche Behauptung wird substanziiert, welche durch Anlage nur bele... |
| `anlagenband-strukturieren` | Anlagenband strukturieren: Trennblaetter, Inhaltsverzeichnis, Reihenfolge nach Schriftsatzbezug, durchgehende Foliierung. Anweisung fuer Kanzleimitarbeiter zur physischen oder elektronischen Erstellung. Fuer beA-Versand zusaetzlich ein d... |
| `anlagenband-strukturieren-anlagenbezug` | Nutze dies, wenn Anlagenband Strukturieren, Anlagenbezug Im Schriftsatz, Anlagenkonvolut Konsolidieren, Anlagenmatrix Csv Xlsx Aufbau im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Anlagenband Struktu... |
| `anlagenbezug-im-schriftsatz` | Wie Anlagen im Schriftsatz richtig eingefuehrt werden: 'Beweis: Vorlage der Anlage K1' oder 'wie sich aus Anlage K3 ergibt'. Erste Erwaehnung mit Kurztitel und Datum, danach nur K1, K2 ... Vermeidet sprachliche Fehler bei mehrfachem Bezug. |
| `anlagenkonvolut-konsolidieren` | Anlagenkonvolut aus Mandanten-ZIP konsolidieren: Duplikate ueber Hashvergleich erkennen, gleiche Vertraege in unterschiedlichen Fassungen identifizieren, sortieren nach Datum und Thema, Lueckenanalyse (welcher Vertrag wird im Schriftsatz... |
| `anlagenkonvolut-sonderfall-edge-case` | Nutze dies, wenn Anlagenkonvolut: Sonderfall und Edge-Case-Prüfung im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Anlagenkonvolut: Sonderfall und Edge-Case-Prüfung prüfen.; Erstelle eine Arbeitsfassun... |
| `anlagenmatrix-csv-xlsx-aufbau` | Entwirft eine robuste Anlagenmatrix für große Verfahren mit Dok-ID, Nummernkreisen, Schriftsatzstelle, Beweiszweck, Quelle, Hash, Status, Datenschutz und Nachreichung. |
| `anlagenverzeichnis-gericht-kanzlei-und-intern` | Erstellt getrennte Anlagenverzeichnisse: schlank für Gericht, ausführlicher für Kanzlei und technisch mit Dateipfad, Hash, Quelle und Bearbeitungsstatus. |
| `anlagenverzeichnis-grundaufbau` | Anlagenverzeichnis nach deutscher Anwaltsuebung aufbauen: K1, K2, K3 ... fuer Klaegerseite, B1, B2 ... fuer Beklagtenseite. Kurztitel, Datum, Funktion (Beweismittel zu welcher Behauptung), Fundstelle im Schriftsatz. Loest Doppel-Nummerie... |
| `anlagenverzeichnis-kanzlei-grundaufbau-bea` | Nutze dies, wenn Anlagenverzeichnis Gericht Kanzlei Und Intern, Anlagenverzeichnis Grundaufbau, Bea Paketierung Groessen Und Versandplan, Berufung Beschwerde Und Neue Anlagen im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Anlagen Zu Schriftsaetzen.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `arial` | Entscheidet Stempelbild, Deckblatt, Anlagenverzeichnis und Mandantenfreigabe so, dass die Anlage optisch und logisch eindeutig ist. |
| `baut-beweislast-benennt-bereits-excel` | Nutze dies, wenn Spezial Baut Beweislast Und Darlegungslast, Spezial Benennt Compliance Dokumentation Und Akte, Spezial Bereits Abschlussprodukt Und Übergabe, Spezial Excel Schriftsatz Brief Und Memo Bausteine im Plugin Anlagen Zu Schrif... |
| `baut-beweislast-darlegungslast` | Prüft, ob die Anlage eine konkrete Darlegung trägt oder nur einen pauschalen Anlagenverweis kaschiert; trennt Tatsachenvortrag, Beweisangebot und bloße Hintergrundunterlage. |
| `bea-paketierung-groessen-und-versandplan` | Plant elektronische Anlagenpakete für beA/ERV: Dateinamen, Reihenfolge, Paketgrößen, PDF/OCR, Nachsendungen, Begleitvermerk und finaler Versandcheck. |
| `benennt` | Nutze dies, wenn Benennt: Compliance-Dokumentation und Aktenvermerk im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `bereits` | Nutze dies, wenn Bereits: Abschlussprodukt und Übergabe im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Bereits: Abschlussprodukt und Übergabe prüfen.; Erstelle eine Arbeitsfassung zu Bereits: Abschlus... |
| `berufung-beschwerde-und-neue-anlagen` | Prüft Anlagen in Rechtsmittelverfahren: Übernahme alter Nummern, neue Anlagen, § 531 ZPO-Risiken, Verweis auf Vorinstanz und Synchronisation. |
| `beweisangebot-anlage-emails-chats-excel` | Nutze dies, wenn Beweisangebot Anlage Zeugen, Emails Chats Screenshots Als Anlagen, Excel Tabellen Und Zahlenbeweis, Fremdsprachige Anlagen Uebersetzung im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte... |
| `beweisangebot-anlage-zeugen` | Zeugenbeweis korrekt ueber Anlagen unterstuetzen: schriftliche Zeugenaussagen sind keine Anlagen-Beweismittel im Strengbeweis, koennen aber als praeprozessuale Information dienen. Anlagen, die die Glaubhaftigkeit stuetzen (Chatverlauf, E... |
| `chronologie-und-belegmatrix` | Nutze dies, wenn Chronologie und Belegmatrix im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Chronologie und Belegmatrix prüfen.; Erstelle eine Arbeitsfassung zu Chronologie und Belegmatrix.; Welche No... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Anlagen Zu Schriftsaetzen.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill pas... |
| `emails-chats-screenshots-als-anlagen` | Macht aus EML/MSG, Chatverläufen und Screenshots gerichtstaugliche Anlagen mit Headern, Kontext, Exportlogik, Vollständigkeitswarnung und Beweiszweck. |
| `excel` | Macht Tabellenanlagen im Schriftsatz verständlich: Zahlenkern, Rechenweg, PDF-Ausdruck, Anlagenzitat und kurze Erläuterung. |
| `excel-tabellen-und-zahlenbeweis` | Bereitet XLSX/CSV als Anlage auf: Ausdruck, Summenlogik, Formelrisiko, Quelldaten, Rechenweg, PDF-Fassung und Anlagenbezug im Schriftsatz. |
| `fremdsprachige-anlagen-uebersetzung` | Prüft fremdsprachige Anlagen: Relevanz, Übersetzungsbedarf, beglaubigte oder Arbeitsübersetzung, Auszug statt Vollübersetzung, Kosten und Schriftsatzanker. |
| `frist-eilversand-schiedsverfahren-anlagenband` | Nutze dies, wenn Workflow Redteam Qualitygate, Frist Und Eilversand Anlagenpaket, Schiedsverfahren Anlagenband Und Datentraeger, Spezial Gerichtlichen Fristen Form Und Zustaendigkeit im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet... |
| `frist-und-eilversand-anlagenpaket` | Minimalpfad bei drohender Frist: welche Anlagen müssen jetzt mit, welche können nachgereicht, welche Risiken müssen im Schriftsatz offen gehalten werden. |
| `fristen-und-risikoampel` | Nutze dies, wenn Fristen- und Risikoampel im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Fristen- und Risikoampel prüfen.; Erstelle eine Arbeitsfassung zu Fristen- und Risikoampel.; Welche Normen und... |
| `gerichtlichen` | Nutze dies, wenn Gerichtlichen: Fristen, Form, Zuständigkeit und Rechtsweg im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Gerichtlichen: Fristen, Form, Zuständigkeit und Rechtsweg prüfen.; Erstelle ei... |
| `haftpflicht-versicherer-konvention-k` | Nutze dies, wenn Anlagen Haftpflicht Versicherer, Anlagen Konvention K B Erlaeutert, Anlagen Konvention Mandantenfreundlich, Anlagen Prozessual Prüfung Spezial im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser:... |
| `k1-anlagenpaket-aus-chaosordner` | Aus einem Mandantenordner mit beliebigen Dateinamen die erste Anlagenstaffel K1 bis K20 bilden: priorisieren, umbenennen, Lücken markieren, Rückfragen ausgeben. |
| `k1-anlagenpaket-k1-sortierwerkstatt` | Nutze dies, wenn K1 Anlagenpaket Aus Chaosordner, K1 Sortierwerkstatt, Massenanlagen Sampling Und Repraesentativitaet, Mehrparteien Rollen Und Praefixe im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte K... |
| `k1-sortierwerkstatt` | K1-Leitanlage sortieren: Vertrag, Auftrag, Nachtrag, E-Mail-Anhang, Scan, OCR-Fassung und spätere Ergänzungen zu einer gerichtstauglichen Anlage K1 oder einem K1-Konvolut ordnen. |
| `konform-interessen` | Nutze dies, wenn Konform: Mehrparteienkonflikt und Interessenmatrix im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Konform: Mehrparteienkonflikt und Interessenmatrix prüfen.; Erstelle eine Arbeitsfass... |
| `konform-interessen-konvertiert-oben` | Nutze dies, wenn Spezial Konform Mehrparteien Konflikt Und Interessen, Spezial Konvertiert Zahlen Schwellen Und Berechnung, Spezial Oben Formular Portal Und Einreichung, Spezial Schriftsaetzen Dokumentenmatrix Und Lueckenliste im Plugin... |
| `konvertiert` | Prüft PDF-Konvertierung, Dateigrößen, Seitenzahlen, OCR und technische Schwellen vor Versand. |
| `logik-quellenkarte` | Nutze dies, wenn Logik Quellenkarte im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `mandantenkommunikation` | Nutze dies, wenn Mandantenkommunikation im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Mandantenkommunikation prüfen.; Erstelle eine Arbeitsfassung zu Mandantenkommunikation.; Welche Normen und Nachwe... |
| `massenanlagen-sampling-repraesentativitaet` | Hilft bei Tausenden gleichartiger Dokumente: Auswahl, repräsentative Beispiele, Nachreichungsvorbehalt, Anlagenband und Substantiierungsgrenze. |
| `mehrparteien-rollen-und-praefixe` | Entwirft Nummernkreise bei Streitgenossen, Nebenintervention, Widerklage, Drittwiderklage, selbständigem Beweisverfahren und parallelen Verfahren. |
| `nachreichung-berichtigung-ocr-scan-original` | Nutze dies, wenn Nachreichung Berichtigung Und Gerichtshinweis, Ocr Scan Lesbarkeit Und Beweiswert, Original Abschrift Kopie Und Elektronische Fassung, Schriftsatz Anlagen Mapping im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet we... |
| `nachreichung-berichtigung-und-gerichtshinweis` | Plant die Reparatur eines Anlagenpakets nach gerichtlichem Hinweis, Rüge der Gegenseite, falscher Anlage, fehlender Datei oder versehentlicher Einreichung. |
| `oben` | Prüft, wie Anlagen technisch eingereicht werden: beA, ERV, Portal, Datenträger, mehrere Teilpakete, Begleitvermerk und Eingangsprüfung. |
| `ocr-scan-lesbarkeit-und-beweiswert` | Prüft gescannte Anlagen auf Lesbarkeit, OCR-Durchsuchbarkeit, Seitenreihenfolge, abgeschnittene Ränder, schiefe Scans und Beweiswertprobleme. |
| `original-abschrift-kopie-elektronische` | Klären, wann Original, beglaubigte Abschrift, einfache Kopie, Scan, elektronisches Dokument oder Ausdruck als Anlage sinnvoll oder erforderlich ist. |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `pruefmodus-fristennotiz-datenraum-sharepoint` | Nutze dies, wenn Spezial Pruefmodus Fristennotiz Und Naechster Schritt, Anlagen Aus Datenraum Und Sharepoint, Anlagen Aus Edv Systemen, Anlagen Aus Mandantenmaterial im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Aus... |
| `pruefmodus-fristennotiz-naechster-schritt` | Validiert ein vorhandenes Anlagenpaket und gibt eine kurze Fristennotiz plus nächste Handlung aus. |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `redteam-qualitygate` | Nutze dies, wenn Red-Team Qualitygate im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `schiedsverfahren-anlagenband-und-datentraeger` | Plant Anlagenbände im Schiedsverfahren: mehrere Originale, USB-Sticks, PDF-Bundles, Index, Hashliste, Verfahrensanordnung und parallele elektronische Struktur. |
| `schriftsaetzen` | Baut aus Schriftsatz und Dateiliste eine Matrix mit Tatsachen, Belegen, fehlenden Anlagen und Nachforderungen. |
| `schriftsatz-anlagen-mapping` | Schriftsatzstellen, Tatsachenbehauptungen, Beweisangebote und Anlagen in eine Matrix bringen; erkennt fehlende, doppelte und nur scheinbar belegte Anlagen. |
| `schriftsatz-verhandlung-vergleich-und` | Nutze dies, wenn Schriftsatz: Verhandlung, Vergleich und Eskalation im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Schriftsatz: Verhandlung, Vergleich und Eskalation prüfen.; Erstelle eine Arbeitsfass... |
| `sortiert` | Nutze dies, wenn Sortiert: Risikoampel, Gegenargumente und Verteidigungslinien im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Sortiert: Risikoampel, Gegenargumente und Verteidigungslinien prüfen.; Ers... |
| `sortiert-stempelt-word` | Nutze dies, wenn Spezial Schriftsatz Verhandlung Vergleich Und Eskalation, Spezial Sortiert Risikoampel Und Gegenargumente, Spezial Stempelt Internationaler Bezug Und Schnittstellen, Spezial Word Behörden Gericht Und Registerweg im Plugi... |
| `stempelt` | Nutze dies, wenn Stempelt: Internationaler Bezug und Schnittstellen im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Stempelt: Internationaler Bezug und Schnittstellen prüfen.; Erstelle eine Arbeitsfass... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `word` | Bereitet Word-, PDF- und Scan-Anlagen für Gerichts- oder Behördenwege vor: Konvertierung, Lesezeichen, PDF/A, Dateiname, Deckblatt. |
| `zeitleiste-und-belegkette` | Baut aus Anlagen eine Chronologie und zeigt zu jedem Ereignis, welcher Beleg trägt, welcher nur plausibilisiert und welcher fehlt. |
| `zuordnung` | Nutze dies, wenn Zuordnung: Erstprüfung, Rollenklärung und Mandatsziel im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Zuordnung: Erstprüfung, Rollenklärung und Mandatsziel prüfen.; Erstelle eine Arbei... |
| `zuordnung-zeitleiste-belegkette` | Nutze dies, wenn Spezial Zuordnung Erstpruefung Und Mandatsziel, Zeitleiste Und Belegkette im Plugin Anlagen Zu Schriftsaetzen konkret bearbeitet werden soll. Auslöser: Bitte Spezial Zuordnung Erstpruefung Und Mandatsziel, Zeitleiste Und... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
