# patentrecherche

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`patentrecherche`) | [`patentrecherche.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/patentrecherche.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **FTO-Recherche Rotorblattheizung — Windsysteme Norderhof AG vs. Vellbruck Energietechnik / EP 3 218 922 B1** (`fto-recherche-windkraft-rotorblattheizung-windsysteme-norderhof-eppendorfer-stadter`) | [Gesamt-PDF lesen](../testakten/fto-recherche-windkraft-rotorblattheizung-windsysteme-norderhof-eppendorfer-stadter/gesamt-pdf/fto-recherche-windkraft-rotorblattheizung-windsysteme-norderhof-eppendorfer-stadter_gesamt.pdf) | [`testakte-fto-recherche-windkraft-rotorblattheizung-windsysteme-norderhof-eppendorfer-stadter.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-fto-recherche-windkraft-rotorblattheizung-windsysteme-norderhof-eppendorfer-stadter.zip) |
| **Patentrecht — Erfindungsakten Ravenstein & Moll** (`patentrecht-erfindungsakten-ravenstein-moll`) | [Gesamt-PDF lesen](../testakten/patentrecht-erfindungsakten-ravenstein-moll/gesamt-pdf/patentrecht-erfindungsakten-ravenstein-moll_gesamt.pdf) | [`testakte-patentrecht-erfindungsakten-ravenstein-moll.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-patentrecht-erfindungsakten-ravenstein-moll.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

> Plugin für **Patentanwältinnen und Patentanwälte**, das Claude Cowork agentisch durch die klassischen Patentdatenbanken führt — Espacenet, Google Patents, DPMAregister, DEPATISnet, EPO Register, WIPO PATENTSCOPE, USPTO. Vorrecherche, **keine amtliche Recherche**.

## Hinweis vorab

Dieses Plugin ist **Vorrecherche-Werkzeug** für die Patentanwaltspraxis. Es ersetzt nicht die amtliche Recherche durch DPMA oder EPA und nicht die finale Bewertung durch die Patentanwältin. Treffer können unvollständig sein, falsch klassifiziert sein, in nicht maschinenlesbaren Volltexten verborgen sein oder durch Patentfamilien-Verbindungen verfehlt werden. Die abschließende Recherche muss durch eigene Nachrecherche oder durch Überprüfung der Treffer abgesichert werden.

Das Plugin ist Teil des Repositories [`claude-fuer-deutsches-recht`](../) und wurde mit Hilfe eines KI-Code-Assistenten erstellt; die inhaltliche Verantwortung trägt der Autor (Klotzkette).

## Inhalt

14 Skills, 3 References. Die methodische Grundlage stammt aus den Querschnitts-Plugins [`methodenlehre-buergerliches-recht`](../methodenlehre-buergerliches-recht) und [`zitierweise-deutsches-recht`](../zitierweise-deutsches-recht), die parallel aktiviert sein sollten.

### Skills

| Skill | Funktion |
| --- | --- |
| `patentrecherche-kaltstart-interview` | Setup: Patentanwältin, Mandant, Erfindung, Recherchezweck, Rechtsraum |
| `klassifikation-cpc-ipc` | CPC- und IPC-Klassen für die Recherche bestimmen |
| `agentische-datenbank-recherche` | Master-Skill: agentische Bedienung von Espacenet, Google Patents, DPMAregister, DEPATISnet, EPO Register, WIPO PATENTSCOPE, USPTO |
| `stand-der-technik-recherche` | Vorrecherche für Neuheitsbewertung vor eigener Anmeldung |
| `neuheit-pruefen` | § 3 PatG / Art. 54 EPÜ — Einzeldokument-Vorwegnahme aller Merkmale |
| `erfinderische-taetigkeit-pruefen` | § 4 PatG / Art. 56 EPÜ — Problem-Solution-Approach (EPA-Beschwerdekammern) |
| `freedom-to-operate-recherche` | FTO — Patentverletzungsrisiko aus Drittpatenten vor Markteintritt |
| `patentfamilien-analyse` | INPADOC-Familie — weltweite Patente mit gleichem Prioritätstag |
| `rechtsstand-pruefen` | Anmeldetag, Erteilung, Erlöschen, Einspruch, Nichtigkeit |
| `ueberwachung-konkurrenten` | Monitoring neuer Anmeldungen bestimmter Anmelder oder Klassen |
| `pruefungsbescheid-vorbereiten` | EPA- oder DPMA-Bescheid systematisch entgegnen, Stand-der-Technik-Entgegenhaltungen einordnen |
| `recherchebericht-erstellen` | Formaler Output mit Treffern, Bewertung, Disclaimer |
| `rueckfragen-mandant` | Erfindungsabgrenzung klären — Was ist der wesentliche Lösungsbeitrag |

### References

- `cpc-ipc-klassen-uebersicht.md` — CPC- und IPC-Hauptsektionen, Querverweis-Logik
- `patentdatenbanken-quellen.md` — Datenbanken im Detail (URL, Abdeckung, Stärken, Schwächen, agentische Bedienung)
- `bpatg-und-epa-rspr-leitentscheidungen.md` — Leitentscheidungen Patentanwaltspraxis (BGH X. Senat, BPatG, EPA G-Entscheidungen)

## Setup

Nach Aktivierung des Plugins wird beim ersten Lauf von `patentrecherche-kaltstart-interview` ein Profil unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/patentrecherche/CLAUDE.md` angelegt (Kanzlei, Patentanwält:innen, Schwerpunktklassen, typische Mandantenstruktur).

## Pflichtdisclaimer

Jedes Recherche-Ergebnis enthält am Anfang den Disclaimer "**Hinweis zur Recherche** — KI-gestützte Vorrecherche, keine amtliche Recherche, finale Bewertung muss eigenständig abgesichert werden". Skills lassen den Disclaimer nicht weg.

## Verhältnis zum Berufsrecht

Patentanwältinnen sind Berufsgeheimnisträger nach § 203 Abs. 1 Nr. 3 StGB; § 39a PAO regelt die Verschwiegenheit, § 39c PAO regelt die Inanspruchnahme von Dienstleistern. Vor produktivem Einsatz eines KI-Dienstleisters: berufsrechtliche Vorprüfung mit dem Schwester-Plugin [`berufsrecht-ki-vertragspruefung`](../berufsrecht-ki-vertragspruefung) durchführen.

## Lizenz

Apache-2.0 OR MIT. Siehe Repository-Stammverzeichnis.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `agentisch` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Agentisch Fristen Form Und Zustaendigkeit im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-t... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Friste... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Patentrecherche.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `dpmaregister-epue-beweislast-erfinderische` | Nutze dies, wenn Spezial Dpmaregister Schriftsatz Brief Und Memo Bausteine, Spezial Epue Beweislast Und Darlegungslast, Spezial Erfinderische Sonderfall Und Edge Case im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Bi... |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Patentrecherche.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `epo-quellenkarte` | Nutze dies, wenn Epo Quellenkarte im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `erfinderische-taetigkeit-freedom-to-ki-patent` | Nutze dies, wenn Erfinderische Taetigkeit Prüfen, Freedom To Operate Recherche, Ki Und Patent Strategie im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Bitte Erfinderische Taetigkeit Prüfen, Freedom To Operate Recherc... |
| `espacenet-google-neuheit-red` | Nutze dies, wenn Spezial Espacenet Dokumentenmatrix Und Lueckenliste, Spezial Google Risikoampel Und Gegenargumente, Spezial Neuheit Red Team Und Qualitaetskontrolle im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Was... |
| `klassifikation-cpc-neuheit-patentfamilien` | Nutze dies, wenn Klassifikation Cpc Ipc, Neuheit Prüfen, Patentfamilien Analyse im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Bitte Klassifikation Cpc Ipc, Neuheit Prüfen, Patentfamilien Analyse prüfen.; Erstelle ei... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `patentanwaelte-patentrecherche-patents` | Nutze dies, wenn Spezial Patentanwaelte Tatbestand Beweis Und Belege, Spezial Patentrecherche Erstpruefung Und Mandatsziel, Spezial Patents Behörden Gericht Und Registerweg im Plugin Patentrecherche konkret bearbeitet werden soll. Auslös... |
| `patentrecherche-kaltstart-interview` | Kaltstart-Interview für das Patentrecherche-Plugin. Stellt fest wer recherchiert (Patentanwaeltin Patentanwalt Patentassessor Patentingenieur Recherchekraft) welche Kanzlei und welche Technikgebiete (Mechanik Elektrotechnik Chemie Biotec... |
| `patg-problem-register` | Nutze dies, wenn Spezial Patg Mandantenkommunikation Entscheidungsvorlage, Spezial Problem Abschlussprodukt Und Übergabe, Spezial Register Zahlen Schwellen Und Berechnung im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser... |
| `patr-fto-bericht-patentfamilie-priodatum` | Nutze dies, wenn Patr Fto Bericht Leitfaden, Patr Patentfamilie Priodatum Spezial, Patr Recherchestrategie Bauleiter im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Bitte Patr Fto Bericht Leitfaden, Patr Patentfamilie... |
| `patr-software-pr-einfuehrung` | Nutze dies, wenn Patr Software Ki Patentierbarkeit Spezial, Pr Einfuehrung Recherchearten, Pruefungsbescheid Vorbereiten im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Bitte Patr Software Ki Patentierbarkeit Spezial,... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `recherche-strategie-tools-marktuebersicht` | Nutze dies, wenn Recherche Strategie Keywords Und Klassen, Recherche Tools Marktuebersicht, Recherchebericht Erstellen im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Bitte Recherche Strategie Keywords Und Klassen, Re... |
| `rueckfragen-mandant-depatisnet` | Nutze dies, wenn Rechtsstand Prüfen, Rueckfragen Mandant, Spezial Depatisnet Verhandlung Vergleich Und Eskalation im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Bitte Rechtsstand Prüfen, Rueckfragen Mandant, Spezial... |
| `stand-technik-uspto-interessen` | Nutze dies, wenn Spezial Stand Internationaler Bezug Und Schnittstellen, Spezial Technik Formular Portal Und Einreichung, Spezial Uspto Mehrparteien Konflikt Und Interessen im Plugin Patentrecherche konkret bearbeitet werden soll. Auslös... |
| `taetigkeit-fristennotiz-agentische-datenbank` | Nutze dies, wenn Spezial Taetigkeit Fristennotiz Und Naechster Schritt, Agentische Datenbank Recherche, Epo Opposition Strategie im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Bitte Spezial Taetigkeit Fristennotiz Un... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `upc-unified` | Nutze dies, wenn Upc Unified Patent Court Spezial im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Bitte Upc Unified Patent Court Spezial prüfen.; Erstelle eine Arbeitsfassung zu Upc Unified Patent Court Spezial.; Welc... |
| `wipo-stand-technik-ueberwachung-konkurrenten` | Nutze dies, wenn Spezial Wipo Compliance Dokumentation Und Akte, Stand Der Technik Recherche, Ueberwachung Konkurrenten im Plugin Patentrecherche konkret bearbeitet werden soll. Auslöser: Bitte Spezial Wipo Compliance Dokumentation Und A... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
