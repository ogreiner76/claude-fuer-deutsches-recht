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
| `agentisch` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Agentisch Fristen Form Und Zustaendigkeit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `dpmaregister-epue-beweislast-erfinderische` | Nutze dies bei Dpmaregister Schriftsatz Brief Und Memo Bausteine, Epue Beweislast Und Darlegungslast, Erfinderische Sonderfall Und Edge Case: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näc... |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `epo-quellenkarte` | Nutze dies zur Quellenprüfung bei Epo Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `erfinderische-taetigkeit-freedom-to-ki-patent` | Nutze dies bei Erfinderische Taetigkeit Prüfen, Freedom To Operate Recherche, Ki Und Patent Strategie: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `espacenet-google-neuheit-red` | Nutze dies bei Espacenet Dokumentenmatrix Und Lueckenliste, Google Risikoampel Und Gegenargumente, Neuheit Red Team Und Qualitaetskontrolle: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näch... |
| `klassifikation-cpc-neuheit-patentfamilien` | Nutze dies bei Klassifikation Cpc Ipc, Neuheit Prüfen, Patentfamilien Analyse: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `patentanwaelte-patentrecherche-patents` | Nutze dies bei Patentanwaelte Tatbestand Beweis Und Belege, Patentrecherche Erstpruefung Und Mandatsziel, Patents Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert d... |
| `patentrecherche-kaltstart-interview` | Kaltstart-Interview für das Patentrecherche-Plugin. Stellt fest wer recherchiert (Patentanwaeltin Patentanwalt Patentassessor Patentingenieur Recherchekraft) welche Kanzlei und welche Technikgebiete (Mechanik Elektrotechnik Chemie Biotec... |
| `patg-problem-register` | Nutze dies bei Patg Mandantenkommunikation Entscheidungsvorlage, Problem Abschlussprodukt Und Uebergabe, Register Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert de... |
| `patr-fto-bericht-patentfamilie-priodatum` | Nutze dies bei Patr Fto Bericht Leitfaden, Patr Patentfamilie Priodatum Spezial, Patr Recherchestrategie Bauleiter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitss... |
| `patr-software-pr-einfuehrung` | Nutze dies bei Patr Software Ki Patentierbarkeit Spezial, Pr Einfuehrung Recherchearten, Pruefungsbescheid Vorbereiten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbe... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `recherche-strategie-tools-marktuebersicht` | Nutze dies bei Recherche Strategie Keywords Und Klassen, Recherche Tools Marktuebersicht, Recherchebericht Erstellen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `rueckfragen-mandant-depatisnet` | Nutze dies bei Rechtsstand Prüfen, Rueckfragen Mandant, Depatisnet Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `stand-technik-uspto-interessen` | Nutze dies bei Stand Internationaler Bezug Und Schnittstellen, Technik Formular Portal Und Einreichung, Uspto Mehrparteien Konflikt Und Interessen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert d... |
| `taetigkeit-fristennotiz-agentische-datenbank` | Nutze dies bei Taetigkeit Fristennotiz Und Naechster Schritt, Agentische Datenbank Recherche, Epo Opposition Strategie: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbe... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `upc-unified` | Nutze dies bei Upc Unified Patent Court Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `wipo-stand-technik-ueberwachung-konkurrenten` | Nutze dies bei Wipo Compliance Dokumentation Und Akte, Stand Der Technik Recherche, Ueberwachung Konkurrenten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
