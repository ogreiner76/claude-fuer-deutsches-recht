# Verlagsredaktion

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`verlagsredaktion`) | [`verlagsredaktion.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/verlagsredaktion.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Auerbach Soundworks / Nordlicht in Beton** (`urheberrecht-musik-ki-songstreit-auerbach`) | [Gesamt-PDF lesen](../testakten/urheberrecht-musik-ki-songstreit-auerbach/gesamt-pdf/urheberrecht-musik-ki-songstreit-auerbach_gesamt.pdf) | [`testakte-urheberrecht-musik-ki-songstreit-auerbach.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-urheberrecht-musik-ki-songstreit-auerbach.zip) |
| **Akte Lilienfeld Verlag: Fachbuch, E-Book-Bundle, Remittenden und Preisbindungsabmahnung** (`verlagsrecht-buchpreisbindung-fachverlag-lilienfeld`) | [Gesamt-PDF lesen](../testakten/verlagsrecht-buchpreisbindung-fachverlag-lilienfeld/gesamt-pdf/verlagsrecht-buchpreisbindung-fachverlag-lilienfeld_gesamt.pdf) | [`testakte-verlagsrecht-buchpreisbindung-fachverlag-lilienfeld.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verlagsrecht-buchpreisbindung-fachverlag-lilienfeld.zip) |
| **Verlagsredaktion Morgenlage Fachverlag** (`verlagsredaktion-morgenlage-fachverlag`) | [Gesamt-PDF lesen](../testakten/verlagsredaktion-morgenlage-fachverlag/gesamt-pdf/verlagsredaktion-morgenlage-fachverlag_gesamt.pdf) | [`testakte-verlagsredaktion-morgenlage-fachverlag.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verlagsredaktion-morgenlage-fachverlag.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein Verlagsdesk für juristische und fachliche Verlage: Eingangskorb, Manuskriptaufnahme, Redaktion, Rechtecheck, Zitat- und Fundstellenkontrolle, Autor:innenkommunikation, Heftplanung, Buchprojektsteuerung, Satzfahnen, Metadaten, Marketingtexte, Produktionsübergabe und Qualitätstor.

Der erste Bildschirm soll sich für eine Sachbearbeiterin so anfühlen: Alles liegt durcheinander im Postfach, aber das Plugin macht daraus sofort eine Morgenlage, eine Prioritätenliste und den nächsten verwendbaren Arbeitsschritt.

## Installation

1. ZIP herunterladen.
2. Claude Code oder Claude Desktop/Cowork öffnen.
3. **Customize Plugins** bzw. **Personal plugins** öffnen.
4. **Install from .zip** wählen und `verlagsredaktion.zip` hochladen.

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json`, `skills/` und `references/` enthalten.

## Was das Plugin gut können soll

- Aus einer unordentlichen Inbox eine Tagesübersicht machen.
- Manuskripte, Diktate, Folien, Screenshots, Tabellen und Autor:innenmails inventarisieren.
- Rohmanuskripte als Anschubhilfe erstellen, ohne fremde Texte zu kopieren.
- Vorhandene Texte strukturieren, kürzen, glätten und auf Widersprüche prüfen.
- Zitate, Fundstellen, Randnummern und Quellenstatus transparent markieren.
- Rechtefragen zu UrhG, Verlagsgesetz, Bildrechten, Tabellen und Fremdmaterialien als Ampel vorbereiten.
- Autor:innen freundlich, knapp und verbindlich anschreiben.
- Heft-, Buch- und Online-First-Workflows in Aufgaben und Fristen übersetzen.
- Klappentexte, Vorschauen, Metadaten und Marketingtexte aus dem Manuskript ableiten.
- Satzfahnen und Korrekturläufe steuern.
- KI-Einsatz, Datenschutz und Vertraulichkeit konservativ dokumentieren.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `verlagsredaktion-allgemein` | Cooler Einstieg, stummer Upload, Morgenlage und Skill-Routing. |
| `sachbearbeiterinnen-cockpit` | Persönliches Arbeitscockpit für Sachbearbeitung, Redaktion und Herstellung. |
| `eingangskorb-triage` | Mails, Dateien, Screenshots und Fristen in Prioritäten verwandeln. |
| `projektplan-fristen-heftplanung` | Projektplan für Heft, Online-Beitrag, Buchkapitel oder Kommentarupdate. |
| `manuskriptaufnahme-materialinventar` | Materialinventar mit Herkunft, Nutzbarkeit, Lücken und Rechteampel. |
| `verlagsredaktion` | Klassischer Rohmanuskript-/Editionsassistent. |
| `rohmanuskript-anschubhilfe` | Aus Material ein erstes, klar markiertes Rohmanuskript bauen. |
| `lektorat-struktur-redaktion` | Gliederung, Dramaturgie, Kürzung, Redundanz- und Widerspruchsprüfung. |
| `sprachlektorat-stil-tonalitaet` | Ton, Satzbau, Lesbarkeit, Verlagssprache, Zielgruppe. |
| `quellen-zitate-fundstellencheck` | Zitat- und Quellenhygiene ohne erfundene Literatur. |
| `rechtecheck-urhg-verlg` | Urheberrecht, Verlagsgesetz, Nutzungsrechte, Zitatrecht und Zweitveröffentlichung. |
| `bildrechte-grafiken-tabellen` | Bilder, Screenshots, Tabellen, Grafiken, Diagramme und Credits prüfen. |
| `fremdtext-plagiat-uebernahmecheck` | Fremdtext, KI-Text, Copy-Paste und Paraphrase-Risiken markieren. |
| `autorenkommunikation-email` | Autor:innenmails, Erinnerungen, Freigaben, Nachforderungen. |
| `honorar-vertrag-royalties-triage` | Vertrags-/Honorar-/Royalty-Fragen für redaktionelle Vorprüfung. |
| `metadaten-seo-klappentext` | Titel, Untertitel, Abstract, Schlagworte, VLB-/Web-Metadaten, Klappentext. |
| `zeitschriften-heftplanung` | Hefte, Rubriken, Deadlines, Online-first, Fahnen und Umbruch koordinieren. |
| `buchprojekt-kapitelkoordination` | Kapitel, Autor:innen, Register, Abbildungen, Vorwort und Produktionsstand. |
| `kommentar-aktualisierung-randnummern` | Kommentarupdates, Randnummern, Nachweise, Rechtsstandsvermerk. |
| `entscheidungsmonitor-rechtsstand` | Entscheidungen und Gesetzesänderungen als Aktualisierungsanlass erfassen. |
| `satzfahne-korrekturlauf` | Fahnenprüfung, Korrekturzeichen, Umbruch, Freigabe und letzte Checks. |
| `barrierefreiheit-epub-pdf` | Alt-Texte, Überschriftenlogik, Tabellenzugänglichkeit, EPUB/PDF-Check. |
| `marketing-presse-social` | Vorschau, Newsletter, Social Copy, Presseinfo und Nutzenargumente. |
| `sales-katalog-vlb-buchhandel` | Vertriebskurztext, Katalogdaten, Buchhandelsargumente, Zielgruppen. |
| `knowledge-base-faq-kundenservice` | FAQ und interne Wissensbasis für Vertrieb, Support und Redaktion. |
| `ai-einsatz-transparenz-datenschutz` | KI-Einsatz, Vertraulichkeit, DSGVO, Rechte und Freigabe dokumentieren. |
| `produktionsuebergabe-checkliste` | Übergabe an Herstellung, Satz, Online, Marketing, Vertrieb und Archiv. |
| `qualitaetsgate-verlag` | Schlussprüfung vor Autor:innenversand, Satz, Onlinegang oder Druck. |

## Quellenregel

- Keine Kommentar-, Handbuch-, Aufsatz- oder Datenbankfundstellen aus Modellwissen.
- Literatur nur aus Nutzerquelle, frei zugänglicher Quelle oder lizenziertem Live-Zugriff.
- Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle.
- Fremdtexte niemals wörtlich übernehmen, außer der Nutzer verlangt ein zulässiges kurzes Zitat mit sauberer Quellenangabe und Zweck.
- Bei Verlagstexten immer trennen: Autor:innenmaterial, Redaktionstext, Fremdquelle, KI-Vorschlag und offene Lücke.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 104 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `ai-einsatz-transparenz-datenschutz` | Dokumentiert KI-Einsatz, Vertraulichkeit, Datenschutz, Autor:innenmaterial, Fremdrechte, Trainingsverbot, Freigaben und interne Verlagspolitik: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `autorenkommunikation-email` | Schreibt freundliche, klare Autor:innenkommunikation fuer Nachforderungen, Korrekturen, Freigaben, Rechtefragen, Fristen und Eskalationen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `barrierefreiheit-epub-pdf` | Prueft Verlagsoutputs auf Struktur, Alt-Texte, Tabellenlesbarkeit, Ueberschriftenlogik, PDF- und EPUB-Zugaenglichkeit: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `bildrechte-grafiken-tabellen` | Prueft Bilder, Screenshots, Grafiken, Tabellen, Diagramme, Credits, Alt-Texte, Bearbeitungen und Nutzungsumfang fuer Verlagspublikationen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `buchprojekt-kapitelkoordination` | Steuert Buchprojekte, Kapitel, Autor:innen, Herausgeber:innen, Register, Abbildungen, Vorwort, Fristen und Produktionsstand: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `eingangskorb-heftplanung-interessen` | Eingangskorb: Risikoampel, Gegenargumente und Verteidigungslinien; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quel... |
| `eingangskorb-triage-entscheidungsmonitor` | Sortiert einen Verlags-Eingangskorb aus Mails, Manuskripten, Fahnen, Bildern, Tabellen und Notizen nach Frist, Risiko, Projekt und naechster Aktion: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `entscheidungsmonitor-rechtsstand` | Erfasst neue Entscheidungen, Gesetze und Materialien als moegliche Aktualisierungsanlaesse fuer Zeitschrift, Kommentar, Newsletter oder Buchauflage: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `fremdtext-plagiat-uebernahmecheck` | Markiert Fremdtext-, Copy-Paste-, Plagiats-, KI-Text- und Paraphrase-Risiken und erstellt eine redaktionelle Klaerungsliste: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `honorar-vertrag-royalties-triage` | Triage fuer Autor:innenvertrag, Honorar, Tantiemen, Pauschale, Nebenrechte, Abrechnung, Nutzungsarten und Eskalation an Justiziariat: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `knowledge-base-faq-kundenservice` | Erstellt FAQ, interne Wissensbasis und Kundenservice-Antworten zu Verlagstiteln, Updates, Downloads, Errata, Lizenzen und Produktfragen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `kommentar-aktualisierung-randnummern` | Unterstuetzt Kommentarupdates mit Randnummernlogik, Rechtsstandsvermerk, Nachweisen, Aenderungsprotokoll und Autor:innenrueckfragen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `lektorat-struktur-manuskriptaufnahme` | Redigiert Struktur, Argumentationsgang, Gliederung, Kuerzung, Redundanzen, Widersprueche und Lesefuehrung von Verlagsmanuskripten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `manuskriptaufnahme-materialinventar` | Nimmt Manuskripte und Begleitmaterial auf, erstellt ein Materialinventar, trennt Autor:innenmaterial, Fremdquelle, Redaktionstext, Luecken und Rechtefragen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Out... |
| `marketing-presse-social` | Erstellt Verlagstexte fuer Vorschau, Newsletter, Presse, Website und Social Media aus Manuskript, Zielgruppe und Produktnutzen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `metadaten-fehlerkatalog` | Metadaten Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `metadaten-seo-klappentext` | Erstellt Titelvarianten, Untertitel, Abstract, Schlagworte, Klappentext, Webteaser, Kurzbeschreibung und Metadaten aus Manuskriptmaterial: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `produktionsuebergabe-checkliste` | Erstellt die Uebergabe an Herstellung, Satz, Online, Marketing, Vertrieb und Archiv mit Dateien, Freigaben, Rechten, Metadaten und offenen Punkten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `projektplan-fristen-heftplanung` | Erstellt Projektplaene fuer Heft, Onlinebeitrag, Buchkapitel, Kommentarupdate oder Sonderband mit Deadlines, Abhaengigkeiten und Verantwortlichen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `qualitaetsgate-verlag-quellen-zitate` | Schlusspruefung fuer Verlagsoutputs vor Autor:innenversand, Satz, Onlinegang oder Druck mit Rechte-, Quellen-, Stil-, Fristen- und Produktionsampel: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `quellen-zitate-fundstellencheck` | Prueft Quellen, Zitate, Randnummern, Fundstellen, Rechtsprechung und Literaturstatus mit strenger Regel gegen erfundene oder paywallige Blindzitate: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `rechtecheck-urhg-verlg` | Erstellt eine redaktionelle Rechteampel zu UrhG, Verlagsgesetz, Nutzungsrechten, Zitatrecht, Bearbeitung, Zweitveroeffentlichung und Freigaben: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `redaktion-satzfahnen-verlage-verlagsdesk` | Redaktion: Schriftsatz-, Brief- und Memo-Bausteine; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risik... |
| `rohmanuskript-anschubhilfe` | Baut aus Diktaten, Folien, Notizen und E-Mails ein klar markiertes Rohmanuskript als Anschubhilfe, ohne Autor:innenstimme und Redaktion zu vermischen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `sachbearbeiterinnen-cockpit` | Persoenliches Verlagscockpit fuer Sachbearbeitung und Redaktion: Tageslage, Prioritaeten, Fristen, Autor:innen, Rechteampel, Produktionsstand und naechste Aktionen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertb... |
| `sales-katalog-satzfahne-korrekturlauf` | Bereitet Vertriebs-, Katalog-, VLB- und Buchhandelsdaten mit Zielgruppen, Verkaufsargumenten, Warengruppe, Schlagworten und Vergleichstiteln vor: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `satzfahne-korrekturlauf` | Fuehrt durch Satzfahnen, Korrekturlaeufe, Umbruch, Seitenzahlen, Abbildungen, Fussnoten, Freigaben und letzte Produktionschecks: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `spezial-autorenkommunikation-compliance-dokumentation-und-akte` | Autorenkommunikation: Compliance-Dokumentation und Aktenvermerk; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quelle... |
| `spezial-bildrechte-zahlen-schwellen-und-berechnung` | Bildrechte: Zahlen, Schwellenwerte und Berechnung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risiko... |
| `spezial-buchprojekte-internationaler-bezug-und-schnittstellen` | Buchprojekte: Internationaler Bezug und Schnittstellen; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellencheck, R... |
| `spezial-fachliche-fristen-form-und-zustaendigkeit` | Fachliche: Fristen, Form, Zuständigkeit und Rechtsweg; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellencheck, Ri... |
| `spezial-heftplanung-mehrparteien-konflikt-und-interessen` | Heftplanung: Mehrparteienkonflikt und Interessenmatrix; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellencheck, R... |
| `spezial-juristische-tatbestand-beweis-und-belege` | Juristische: Tatbestandsmerkmale, Beweisfragen und Beleglage; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellench... |
| `spezial-manuskript-behoerden-gericht-und-registerweg` | Manuskript: Behörden-, Gerichts- oder Registerweg; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risiko... |
| `spezial-rechtecheck-verhandlung-vergleich-und-eskalation` | Rechtecheck: Verhandlung, Vergleich und Eskalation; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risik... |
| `spezial-satzfahnen-formular-portal-und-einreichung` | Satzfahnen: Formular, Portal und Einreichungslogik; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risik... |
| `spezial-verlage-dokumentenmatrix-und-lueckenliste` | Verlage: Dokumentenmatrix, Lückenliste und Nachforderung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `spezial-verlagsdesk-erstpruefung-und-mandatsziel` | Verlagsdesk: Erstprüfung, Rollenklärung und Mandatsziel; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `sprachlektorat-stil-tonalitaet` | Verbessert Sprache, Stil, Tonalitaet, Satzbau, Lesbarkeit, Gender- und Hausstilfragen fuer juristische und fachliche Verlagstexte: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-abstimmung` | Chronologie und Belegmatrix: macht aus unordentlichem Material eine Timeline mit Belegstellen und offenen Widersprüchen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-abstimmung-lektorat-produktion-satz` | Klaert Lektorats- und Redaktionsstandards: wer ist fuer welchen Pruefschritt zustaendig wie wird uebergeben Track-Changes Stand Versionierung Eskalationsregeln: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem... |
| `verl-abstimmung-mit-autor-feedback-kanal` | Strukturiert die laufende Kommunikation mit Autorin: Kanal Frequenz Dokumentation Eskalationswege bei Konflikten Lieferverzug und Manuskriptaenderungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-abstimmung-mit-produktion-satz-druck` | Klaert die Schnittstelle zur Produktion: Satzdaten Format Bildaufloesung Schriftrechte Fahnenlauf Druckfreigabe Online-Auslieferung und Reklamationswege: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-abstimmung-mit-rechtsabteilung-pruefung` | Inhouse-Legal-Check vor Veroeffentlichung: strukturierte Abstimmung mit Justiziariat zu Aeusserungsrecht, Persoenlichkeitsrecht, Urheberrecht, Wettbewerbsrecht und Datenschutz: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel... |
| `verl-abstimmung-mit-vertrieb-marketing` | Briefing fuer Vertrieb und Marketing zu einem Verlagsprodukt: Zielgruppe Kernnutzen Vergleichstitel Preisarchitektur und Material fuer Katalog Webseite Veranstaltungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verw... |
| `verl-audio-transkript-zu-fachbeitrag` | Destilliert einen Audio-Vortrag oder ein freies Diktat zu einem zitierfaehigen Fachbeitrag fuer juristische Fachzeitschriften und Sammelbaende: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-aussagensicherheit-buchprojekt-bauleiter` | Prueft im Manuskript jede tragende Aussage darauf ob sie so im Druck stehen darf: Belegtiefe Ehrenschutz Datenschutz Berufsrecht und Aussagewahrheit: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-buchprojekt-bauleiter` | Bauleiter juristisches Buchprojekt: Konzept, Autorenvertrag, Manuskripteinreichung, Lektorat, Druck. Pruefraster fuer Herausgeber und Verlag: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-email-konvolute-zu-fachbeitrag` | Verwertet einen E-Mail-Wechsel als Sachverhaltsquelle und Belegmaterial fuer eine Urteilsanmerkung oder einen Praxisbericht, mit Anonymisierung und Chronologie: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem... |
| `verl-eskalation-bei-deadline-konflikt` | Eskalation bei Deadline-Konflikt: strukturierte Hochstufung von Manuskript-, Druck-, Honorar- oder Auslieferungsterminen mit Mustermails fuer Autor, Programmleitung und Geschaeftsfuehrung: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `verl-formatvorlage-check-autor-manuskript` | Prueft strikt die Einhaltung der Verlagsformatvorlage in Autorenmanuskripten und meldet Abweichungen so, dass der Autor sie selbst beheben kann: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-fussnoten-quellen-glossar-konsistenz` | Konsolidiert den Fussnotenapparat eines Manuskripts: dedupliziert, vereinheitlicht, prueft Pinpoints und stellt die Reihenfolge nach Verlagsstandard her: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-glossar-konsistenz-pruefung` | Prueft Glossar und Begriffskonsistenz quer durch Reihen Loseblattwerke und Online-Kommentare: Lemma-Stamm Definitionen Synonyme Querverweise: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-grammatik-konsistenzcheck` | Prueft Grammatik und Stilkonsistenz im Manuskript: Tempus Genus Numerus Kasus Verweisbezug Zeitformwechsel und Hausstilkonsistenz quer durch den Text: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-haftungsfreistellung-autor-verlag` | Haftungsfreistellung zwischen Autor und Verlag: Klauselbaustein im Verlagsvertrag, Reichweite, AGB-Schranken, Versicherungsfragen, Praxis bei Abmahnung und Klage: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbar... |
| `verl-handschrift-und-altdoc-digitalisieren` | Digitalisiert handschriftliche Originalvorlagen und alte Dokumente fuer die Verlagsredaktion, mit Lesart-Markierung, Erhaltungsdokumentation und Auditfaehigkeit: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbare... |
| `verl-honorarrechnung-erstellen-pruefen` | Honorarrechnung erstellen und pruefen: Pflichtangaben, USt-Behandlung, Kleinunternehmer, Reverse Charge, Auslandsautoren, KSK. Mit Musterrechnungen fuer Aufsatz, Beitrag, Werk: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel... |
| `verl-honorarvertrag-templates-und-abweichungen` | Honorarvertragstemplates fuer juristische Werke: Standardvertrag Aufsatz, Buch, Kommentar, Herausgeberwerk. Abweichungspruefung gegen UrhG § 32 angemessene Verguetung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwe... |
| `verl-ideenpool-priorisierung-impressum` | Verwaltet einen Ideen-Backlog der Verlagsredaktion mit Priorisierungsmatrix, Zustandskategorien und Eskalationsregeln fuer entscheidungsreife Themen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-impressum-pflicht-und-pruefung` | Impressumspflicht und Pruefung im Verlag: DDG § 5, MStV § 18 V. i. S. d. P., Anforderungen Print/Online/Newsletter/Social-Media-Profile, Mustertexte und Pruefcheckliste: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und ver... |
| `verl-interview-roh-zu-magazinbeitrag` | Macht aus einem Interview-Transkript eine drucktaugliche Interview-Fassung fuer Fachmagazin oder Newsletter, mit Autorisierung und Tonalitaetskontrolle: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-jourfix-vorbereiten-protokoll` | Bereitet einen Jourfixe der Verlagsredaktion vor: knappe Agenda Statusliste Beschluesse mit Owner und Frist Protokoll innerhalb 24 Stunden: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-konferenzmitschnitt-zu-tagungsbericht` | Macht aus einem Tagungs- oder Konferenzmitschnitt einen Tagungsbericht fuer Fachzeitschrift, mit Vortragsuebersicht, Diskussionsskizze und Quellenpflicht: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-loeschpflicht-archivierung-loseblattwerk` | Loeschpflicht und Archivierung bei juristischer Fachzeitschrift: DSGVO Art. 17 Recht auf Vergessen, Online-Archiv, Aktenzeichen-Anonymisierung, Pressefreiheitsabwaegung, Versionierung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risi... |
| `verl-loseblattwerk-spezial` | Spezialfall Loseblattwerk: Ergaenzungslieferung, Stichtag, Hinweisapparat, Abonnentenpflege. Pruefraster fuer Verlag und Redaktion: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-mahnung-an-honorar-vertrag` | Mahnung an Autor bei Rueckforderung von Vorschuss oder ueberzahltem Honorar: Stufenmodell, Nachfrist gemaess BGB § 286 und § 323, Verjaehrungspruefung, Mustertexte und gerichtliche Geltendmachung: eigenständiges Prüffeld mit Norm-/Quelle... |
| `verl-manuskript-merkwuerdige-formate-rettung` | Rettet Manuskripte aus DOCX-/Markdown-/LaTeX-Mix, alten Word97-Dateien und KI-generiertem Wust; legt saubere Konvertierungspfade fuer die Verlagsredaktion: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-newsletter-redaktion-jur` | Newsletter-Redaktion juristisch: Konzept, Themenkasten, Empfaengerverwaltung nach DSGVO und UWG § 7, double opt-in, Mustertexte fuer wochen- und monatsweisen Versand: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwer... |
| `verl-online-kommentar-update-spezial` | Spezialfall Online-Kommentar und Update-Workflow: Versionierung, Rechtsprechungsmonitoring, Verlinkung. Pruefraster fuer Verlag und Hauptbearbeiter: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-podcast-zeitschriftenbeitrag-powerpoint` | Nutzt einen juristischen Podcast als Zitat- und Inhaltsquelle fuer einen Zeitschriftenbeitrag, klaert Verwertungsrechte und liefert ein zitierbares Belegformat: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem... |
| `verl-powerpoint-verwurstung-zu-text` | Macht aus einer schlechten Vortrags-PPT einen Fliesstextbeitrag fuer Fachzeitschrift oder Tagungsband, ohne Bullet-Wuesten und mit Quellenrekonstruktion: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-pressetext-rechtsthemen` | Pressetext zu Rechtsthemen: Schreibanleitung fuer Verlagspressemitteilung zu neuem Buch oder neuer Entscheidung. Mustertexte fuer Fachpresse und allgemeine Medien mit Sperrfrist: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampe... |
| `verl-rechtschreibung-amtlich-aktuell` | Prueft die amtliche deutsche Rechtschreibung in Verlagsmanuskripten nach dem aktuellen Duden-Stand und dem amtlichen Regelwerk inklusive Eigennamen und Sondereinrichtungen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und... |
| `verl-redaktionelle-rueckmeldung-formulieren` | Formuliert Autoren-Rueckmeldungen kollegial und praezise: trennt klar Stops von Wuenschen vermeidet Praedigtton und gibt der Autorin handhabbare Aufgaben: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-redaktionsmemo-jahresplanung` | Erstellt das Jahresheft-Planungsmemo einer juristischen Fachzeitschrift mit Themenarchitektur, Heftfolge, Autorenstrategie und Risikoreserven: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-redaktionssitzung-vorbereiten` | Bereitet eine juristische Redaktionssitzung vor: Agenda, Themenscoring, Beschlussvorlage, Protokollskelett und Anschlussaufgaben: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-relationslinien-pruefung-im-aufsatz` | Prueft die logischen Relationslinien eines juristischen Aufsatzes: traegt das Argumentationsgeruest die Hauptthese ohne Sprunglinien und ohne Zirkel?: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-richtigstellung-online-print` | Richtigstellung im Online- und Printmedium: Berichtigungsanspruch, Gegendarstellung nach MStV § 20, Erratum, Online-Korrekturhinweis. Mustertexte fuer alle drei Eskalationsstufen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoamp... |
| `verl-roh-research-zu-essay` | Verdichtet unstrukturierten Recherchewust einer Autorin zu einem zitierfaehigen Essay oder Diskussionsbeitrag fuer juristisches Fachformat: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-rueckruf-fehlerbeitrag-screenshot-pdf` | Rueckruf bei spaet erkanntem Fehlerbeitrag: Rechtsfolgenpruefung BGB § 824, UrhG § 14, Aeusserungsrecht. Eskalationsplan, Mustertexte fuer Print- und Online-Rueckruf, Kostenabwaegung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risik... |
| `verl-screenshot-pdf-ocr-redaktion` | Fuehrt einen sauberen OCR-fuer gescannte PDFs und Screenshots zu redaktionellem Manuskript, mit Fehlerquoten-Stichprobe und Pinpoint-Erhalt: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-social-media-rechtsfachzeitschrift` | Social-Media-Beitrag fuer juristische Fachzeitschrift: Konzept fuer LinkedIn, Bluesky, Mastodon. Texttemplates, Bildvorgaben, Disclaimer, Werbekennzeichnung nach UWG und DDG: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel un... |
| `verl-statusbericht-an-verlagsleitung` | Statusbericht an die Verlagsleitung: knappe Lagedarstellung zu Projekt, Frist, Kosten, Risiko und Eskalation. Mustertexte fuer monatliches Reporting und Ad-hoc-Alarm: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwer... |
| `verl-stilbruch-stilcheck-fachzeitschrift` | Spuert Stilbrueche im Fachzeitschriften-Manuskript auf: gemischte Stilebenen Ironie Umgangssprache Floskeln Marketingsprache und KI-typische Phrasen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-tantieme-abrechnung-themenscout` | Jaehrliche Tantieme-Abrechnung fuer Autoren juristischer Werke: Stueck- und Umsatzbeteiligung, Loseblatt-Ergaenzungslieferungen, Online-Nutzung, Verrechnung mit Vorschuss, Pflichten nach UrhG § 32d: eigenständiges Prüffeld mit Norm-/Quel... |
| `verl-themenscout-rechtsentwicklung` | Identifiziert Trends in BGH-/EuGH-/BVerfG-/BMF-Rechtsprechung und Gesetzgebungsverfahren als Themenkandidaten fuer Aufsaetze und Heftaufmacher: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-trend-radar-rechtsgebiete` | Beobachtet rechtsgebietsuebergreifende Trends (Digitalisierung, ESG, KI-Recht, EU-Reformen) als Themen-Frueherkennung fuer mehrere Zeitschriften und Reihen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Out... |
| `verl-vergleichsverhandlung-mit-autor` | Vergleichsverhandlung mit Autor: Aufbau einer Verhandlungslinie bei Honorar-, Tantieme- oder Rueckforderungsstreit, BATNA, Eskalationsstufen, schriftlicher Vergleich und Abgeltungsklausel: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `verl-vlb-katalog-pflege-jur` | VLB-Katalog (Verzeichnis lieferbarer Buecher) pflegen: ONIX-Metadaten, Schlagworte, Klappentext, Reihen, Preisbindung, Erscheinungstermin-Pflege. Konsistenz mit Webshop, beck-online und Buchhandel: eigenständiges Prüffeld mit Norm-/Quell... |
| `verl-vorschuss-ai-einsatz` | Vorschusspruefung fuer Buchprojekte: Bemessungsgrundlage, Auszahlungsstufen, Verrechnung mit Tantiemen, Rueckforderung bei Nichtablieferung, steuerliche und sozialversicherungsrechtliche Folgen: eigenständiges Prüffeld mit Norm-/Quellenc... |
| `verl-webinar-vorbereitung` | Webinar-Vorbereitung als Fachbeitrag-Sequel: Vom Aufsatz zur Onlineveranstaltung. Vertrag mit Autor, FAO-Fortbildungspunkte, Technik, Datenschutz, Aufzeichnung und Vermarktung: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel... |
| `verl-zeitschriftenartikel-leitfaden` | Leitfaden Zeitschriftenartikel: Auswahl Zeitschrift, Manuskriptregeln, Peer Review, Open Access. Pruefraster fuer Autorin und Verlag: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-zitierweise-pruefung-zeitschrift-jus-njw` | Prueft die Zitierweise in Manuskripten gegen die jeweiligen Hausnormen von NJW NZA JuS JZ und verwandten Fachzeitschriften ohne Halluzination: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `verl-zweitverwertungsrechte-pauschal` | Zweitverwertungsrechte und Nebenrechte pauschal vereinbaren: Lizenz an juris/beck-online, Open Access, Sonderdruck, Festschriftsuebernahme, Bearbeitungen. Honorarverteilung und § 38 UrhG: eigenständiges Prüffeld mit Norm-/Quellencheck, R... |
| `verlagsredaktion` | Kernskill fuer verlegerische Rohmanuskript- und Editionsarbeit: Material inventarisieren, strukturieren, redigieren, Luecken markieren, Quellen trennen und Autor:innenfreigaben vorbereiten: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `verlagsredaktion-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `verlagsredaktion-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `verlagsredaktion-kaltstart-triage` | Cooler Einstieg fuer das Verlagsredaktion-Plugin: stummer Upload, Morgenlage, Eingangskorb, Fristen, Rechteampel, Manuskriptstatus und Routing zu den Verlagsdesk-Skills. |
| `verlagsredaktion-output-waehlen` | Output wählen im Verlagsredaktion (Recht): Diese Output-Weiche für Verlagsredaktion entscheidet, ob Memo, Antrag, Schriftsatz, Tabelle, Risikoampel, Fragenliste oder Mandantenbrief der richtige nächste Schritt ist. |
| `verlagsredaktion-quellen-livecheck` | Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `verlagsredaktion-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `workflow-fristen-und-risikoampel` | Fristen- und Risikoampel: macht eine Sofortampel für Frist, Zuständigkeit, Haftung, Eilbedarf und fehlende Unterlagen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `zeitschriften-heftplanung` | Zeitschriften Heftplanung im Verlagsredaktion (Recht): fachlicher Arbeitsgang mit Prüffeldwahl, Norm-/Quellencheck, Risikoampel und verwertbarem Output. |
| `zitate-quellenkarte` | Zitate Quellenkarte: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
