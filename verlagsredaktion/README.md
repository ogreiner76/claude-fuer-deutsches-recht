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
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `eingangskorb-heftplanung-interessen` | Nutze dies bei Eingangskorb Risikoampel Und Gegenargumente, Heftplanung Mehrparteien Konflikt Und Interessen, Juristische Tatbestand Beweis Und Belege, Manuskript Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen M... |
| `eingangskorb-triage-entscheidungsmonitor` | Nutze dies bei Eingangskorb Triage, Entscheidungsmonitor Rechtsstand, Fremdtext Plagiat Uebernahmecheck, Knowledge Base Faq Kundenservice: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächst... |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `lektorat-struktur-manuskriptaufnahme` | Nutze dies bei Lektorat Struktur Redaktion, Manuskriptaufnahme Materialinventar, Marketing Presse Social, Metadaten Seo Klappentext: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bel... |
| `metadaten-fehlerkatalog` | Nutze dies als Fehlerbremse bei Metadaten Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `qualitaetsgate-verlag-quellen-zitate` | Nutze dies bei Qualitaetsgate Verlag, Quellen Zitate Fundstellencheck, Rechtecheck Urhg Verlg, Rohmanuskript Anschubhilfe: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren A... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `redaktion-satzfahnen-verlage-verlagsdesk` | Nutze dies bei Redaktion Schriftsatz Brief Und Memo Bausteine, Satzfahnen Formular Portal Und Einreichung, Verlage Dokumentenmatrix Und Lueckenliste, Verlagsdesk Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module... |
| `sales-katalog-satzfahne-korrekturlauf` | Nutze dies bei Sales Katalog Vlb Buchhandel, Satzfahne Korrekturlauf, Autorenkommunikation Compliance Dokumentation Und Akte, Bildrechte Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `verl-abstimmung` | Nutze dies bei Chronologie Und Belegmatrix, Fristen Und Risikoampel, Verl Abstimmung Mit Autor Feedback Kanal, Projektplan Fristen Heftplanung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den n... |
| `verl-abstimmung-lektorat-produktion-satz` | Nutze dies bei Verl Abstimmung Mit Lektorat Format, Verl Abstimmung Mit Produktion Satz Druck, Verl Abstimmung Mit Rechtsabteilung Prüfung, Verl Abstimmung Mit Vertrieb Marketing: führt durch diese fachlich verbundenen Module, wählt den... |
| `verl-aussagensicherheit-buchprojekt-bauleiter` | Nutze dies bei Verl Aussagensicherheit Prüfung, Verl Buchprojekt Bauleiter, Verl Email Konvolute Zu Fachbeitrag, Verl Eskalation Bei Deadline Konflikt: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefe... |
| `verl-fussnoten-quellen-glossar-konsistenz` | Nutze dies bei Verl Fussnoten Quellen Konsolidierung, Verl Glossar Konsistenz Prüfung, Verl Grammatik Konsistenzcheck, Verl Handschrift Und Altdoc Digitalisieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfa... |
| `verl-ideenpool-priorisierung-impressum` | Nutze dies bei Verl Ideenpool Und Priorisierung, Verl Impressum Pflicht Und Prüfung, Verl Interview Roh Zu Magazinbeitrag, Verl Jourfix Vorbereiten Protokoll: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad un... |
| `verl-loeschpflicht-archivierung-loseblattwerk` | Nutze dies bei Verl Loeschpflicht Und Archivierung Fachzs, Verl Loseblattwerk Spezial, Verl Manuskript Merkwuerdige Formate Rettung, Verl Newsletter Redaktion Jur: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpf... |
| `verl-mahnung-an-honorar-vertrag` | Nutze dies bei Verl Mahnung An Autor Zahlung Frist, Honorar Vertrag Royalties Triage, Verl Honorarvertrag Templates Und Abweichungen, Verl Haftungsfreistellung Autor Verlag: führt durch diese fachlich verbundenen Module, wählt den passen... |
| `verl-podcast-zeitschriftenbeitrag-powerpoint` | Nutze dies bei Verl Podcast Zu Zeitschriftenbeitrag, Verl Powerpoint Verwurstung Zu Text, Verl Pressetext Rechtsthemen, Verl Rechtschreibung Amtlich Aktuell: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `verl-redaktionsmemo-jahresplanung` | Nutze dies bei Verl Redaktionsmemo Jahresplanung, Verl Redaktionssitzung Vorbereiten, Verl Relationslinien Prüfung Im Aufsatz, Verl Richtigstellung Online Print: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `verl-rueckruf-fehlerbeitrag-screenshot-pdf` | Nutze dies bei Verl Rueckruf Fehlerbeitrag Spaet Erkannt, Verl Screenshot Pdf Ocr Redaktion, Verl Social Media Rechtsfachzeitschrift, Verl Statusbericht An Verlagsleitung: führt durch diese fachlich verbundenen Module, wählt den passende... |
| `verl-tantieme-abrechnung-themenscout` | Nutze dies bei Verl Tantieme Abrechnung Jaehrlich, Verl Themenscout Rechtsentwicklung, Verl Trend Radar Rechtsgebiete, Verl Vergleichsverhandlung Mit Autor: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `verl-vorschuss-ai-einsatz` | Nutze dies bei Verl Vorschuss Prüfung Buecher, Ai Einsatz Transparenz Datenschutz, Autorenkommunikation Email, Barrierefreiheit Epub Pdf: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächste... |
| `verl-webinar-vorbereitung` | Nutze dies bei Verl Webinar Vorbereitung Fachbeitrag, Verl Zeitschriftenartikel Leitfaden, Verl Zitierweise Prüfung Zeitschrift Jus Njw, Verl Zweitverwertungsrechte Pauschal: führt durch diese fachlich verbundenen Module, wählt den passe... |
| `zeitschriften-heftplanung` | Nutze dies bei Zeitschriften Heftplanung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `zitate-quellenkarte` | Nutze dies zur Quellenprüfung bei Zitate Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
