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
| `allgemein` | Cooler Einstieg, stummer Upload, Morgenlage und Skill-Routing. |
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

Automatisch generierte Komplett-Liste aller 28 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Cooler Einstieg fuer das Verlagsredaktion-Plugin: stummer Upload, Morgenlage, Eingangskorb, Fristen, Rechteampel, Manuskriptstatus und Routing zu den Verlagsdesk-Skills. |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Verlagsredaktion konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `eingangskorb-heftplanung-interessen` | Nutze dies, wenn Spezial Eingangskorb Risikoampel Und Gegenargumente, Spezial Heftplanung Mehrparteien Konflikt Und Interessen, Spezial Juristische Tatbestand Beweis Und Belege, Spezial Manuskript Behörden Gericht Und Registerweg, Spezia... |
| `eingangskorb-triage-entscheidungsmonitor` | Nutze dies, wenn Eingangskorb Triage, Entscheidungsmonitor Rechtsstand, Fremdtext Plagiat Uebernahmecheck, Knowledge Base Faq Kundenservice, Kommentar Aktualisierung Randnummern im Plugin Verlagsredaktion konkret bearbeitet werden soll.... |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Verlagsredaktion konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Verlagsredaktion.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `lektorat-struktur-manuskriptaufnahme` | Nutze dies, wenn Lektorat Struktur Redaktion, Manuskriptaufnahme Materialinventar, Marketing Presse Social, Metadaten Seo Klappentext, Produktionsuebergabe Checkliste im Plugin Verlagsredaktion konkret bearbeitet werden soll. Auslöser: B... |
| `metadaten-fehlerkatalog` | Nutze dies, wenn Metadaten Fehlerkatalog im Plugin Verlagsredaktion konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Verlagsredaktion konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `qualitaetsgate-verlag-quellen-zitate` | Nutze dies, wenn Qualitaetsgate Verlag, Quellen Zitate Fundstellencheck, Rechtecheck Urhg Verlg, Rohmanuskript Anschubhilfe, Sachbearbeiterinnen Cockpit im Plugin Verlagsredaktion konkret bearbeitet werden soll. Auslöser: Welche amtliche... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Verlagsredaktion konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `redaktion-satzfahnen-verlage-verlagsdesk` | Nutze dies, wenn Spezial Redaktion Schriftsatz Brief Und Memo Bausteine, Spezial Satzfahnen Formular Portal Und Einreichung, Spezial Verlage Dokumentenmatrix Und Lueckenliste, Spezial Verlagsdesk Erstpruefung Und Mandatsziel, Sprachlekto... |
| `sales-katalog-satzfahne-korrekturlauf` | Nutze dies, wenn Sales Katalog Vlb Buchhandel, Satzfahne Korrekturlauf, Spezial Autorenkommunikation Compliance Dokumentation Und Akte, Spezial Bildrechte Zahlen Schwellen Und Berechnung, Spezial Buchprojekte Internationaler Bezug Und Sc... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Verlagsredaktion konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `verl-abstimmung` | Nutze dies, wenn Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel, Verl Abstimmung Mit Autor Feedback Kanal, Projektplan Fristen Heftplanung, Spezial Fachliche Fristen Form Und Zustaendigkeit im Plugin Verlagsredakt... |
| `verl-abstimmung-lektorat-produktion-satz` | Nutze dies, wenn Verl Abstimmung Mit Lektorat Format, Verl Abstimmung Mit Produktion Satz Druck, Verl Abstimmung Mit Rechtsabteilung Prüfung, Verl Abstimmung Mit Vertrieb Marketing, Verl Audio Transkript Zu Fachbeitrag im Plugin Verlagsr... |
| `verl-aussagensicherheit-buchprojekt-bauleiter` | Nutze dies, wenn Verl Aussagensicherheit Prüfung, Verl Buchprojekt Bauleiter, Verl Email Konvolute Zu Fachbeitrag, Verl Eskalation Bei Deadline Konflikt, Verl Formatvorlage Check Autor Manuskript im Plugin Verlagsredaktion konkret bearbe... |
| `verl-fussnoten-quellen-glossar-konsistenz` | Nutze dies, wenn Verl Fussnoten Quellen Konsolidierung, Verl Glossar Konsistenz Prüfung, Verl Grammatik Konsistenzcheck, Verl Handschrift Und Altdoc Digitalisieren, Verl Honorarrechnung Erstellen Prüfen im Plugin Verlagsredaktion konkret... |
| `verl-ideenpool-priorisierung-impressum` | Nutze dies, wenn Verl Ideenpool Und Priorisierung, Verl Impressum Pflicht Und Prüfung, Verl Interview Roh Zu Magazinbeitrag, Verl Jourfix Vorbereiten Protokoll, Verl Konferenzmitschnitt Zu Tagungsbericht im Plugin Verlagsredaktion konkre... |
| `verl-loeschpflicht-archivierung-loseblattwerk` | Nutze dies, wenn Verl Loeschpflicht Und Archivierung Fachzs, Verl Loseblattwerk Spezial, Verl Manuskript Merkwuerdige Formate Rettung, Verl Newsletter Redaktion Jur, Verl Online Kommentar Update Spezial im Plugin Verlagsredaktion konkret... |
| `verl-mahnung-an-honorar-vertrag` | Nutze dies, wenn Verl Mahnung An Autor Zahlung Frist, Honorar Vertrag Royalties Triage, Verl Honorarvertrag Templates Und Abweichungen, Verl Haftungsfreistellung Autor Verlag, Buchprojekt Kapitelkoordination im Plugin Verlagsredaktion ko... |
| `verl-podcast-zeitschriftenbeitrag-powerpoint` | Nutze dies, wenn Verl Podcast Zu Zeitschriftenbeitrag, Verl Powerpoint Verwurstung Zu Text, Verl Pressetext Rechtsthemen, Verl Rechtschreibung Amtlich Aktuell, Verl Redaktionelle Rueckmeldung Formulieren im Plugin Verlagsredaktion konkre... |
| `verl-redaktionsmemo-jahresplanung` | Nutze dies, wenn Verl Redaktionsmemo Jahresplanung, Verl Redaktionssitzung Vorbereiten, Verl Relationslinien Prüfung Im Aufsatz, Verl Richtigstellung Online Print, Verl Roh Research Zu Essay im Plugin Verlagsredaktion konkret bearbeitet... |
| `verl-rueckruf-fehlerbeitrag-screenshot-pdf` | Nutze dies, wenn Verl Rueckruf Fehlerbeitrag Spaet Erkannt, Verl Screenshot Pdf Ocr Redaktion, Verl Social Media Rechtsfachzeitschrift, Verl Statusbericht An Verlagsleitung, Verl Stilbruch Stilcheck Fachzeitschrift im Plugin Verlagsredak... |
| `verl-tantieme-abrechnung-themenscout` | Nutze dies, wenn Verl Tantieme Abrechnung Jaehrlich, Verl Themenscout Rechtsentwicklung, Verl Trend Radar Rechtsgebiete, Verl Vergleichsverhandlung Mit Autor, Verl Vlb Katalog Pflege Jur im Plugin Verlagsredaktion konkret bearbeitet werd... |
| `verl-vorschuss-ai-einsatz` | Nutze dies, wenn Verl Vorschuss Prüfung Buecher, Ai Einsatz Transparenz Datenschutz, Autorenkommunikation Email, Barrierefreiheit Epub Pdf, Bildrechte Grafiken Tabellen im Plugin Verlagsredaktion konkret bearbeitet werden soll. Auslöser:... |
| `verl-webinar-vorbereitung` | Nutze dies, wenn Verl Webinar Vorbereitung Fachbeitrag, Verl Zeitschriftenartikel Leitfaden, Verl Zitierweise Prüfung Zeitschrift Jus Njw, Verl Zweitverwertungsrechte Pauschal, Verlagsredaktion im Plugin Verlagsredaktion konkret bearbeit... |
| `zeitschriften-heftplanung` | Nutze dies, wenn Zeitschriften Heftplanung im Plugin Verlagsredaktion konkret bearbeitet werden soll. Auslöser: Bitte Zeitschriften Heftplanung prüfen.; Erstelle eine Arbeitsfassung zu Zeitschriften Heftplanung.; Welche Normen und Nachwe... |
| `zitate-quellenkarte` | Nutze dies, wenn Zitate Quellenkarte im Plugin Verlagsredaktion konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
