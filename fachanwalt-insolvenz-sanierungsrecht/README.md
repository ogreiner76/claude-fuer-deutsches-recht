# Fachanwalt Insolvenz- und Sanierungsrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`fachanwalt-insolvenz-sanierungsrecht`) | [`fachanwalt-insolvenz-sanierungsrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/fachanwalt-insolvenz-sanierungsrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Großbach Druckguss & Präzision GmbH & Co. KG — Schutzschirm und StaRUG-Optionen** (`starug-schutzschirm-grossbach-druckguss-erfurt`) | [Gesamt-PDF lesen](../testakten/starug-schutzschirm-grossbach-druckguss-erfurt/gesamt-pdf/starug-schutzschirm-grossbach-druckguss-erfurt_gesamt.pdf) | [`testakte-starug-schutzschirm-grossbach-druckguss-erfurt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-starug-schutzschirm-grossbach-druckguss-erfurt.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Plugin Fachanwalt für Insolvenz- und Sanierungsrecht nach FAO § 14 (idF nach Aufnahme StaRUG-Bereiche). Orientierung, Gläubigerantrag, Restrukturierungsplan StaRUG, Insolvenzanfechtung. Schnittstellen zum Plugin `insolvenzrecht` (operativ) und `steuerrecht-anwalt-und-berater`.

## InsO-Paragraphen-Navigator

Dieses Plugin enthält nun zu jedem aktuell im amtlichen InsO-Wortlaut geführten Paragraphen einen eigenen `inso-p...`-Skill. Der Navigator ist für die tägliche Fachanwaltsarbeit gedacht: Er führt nicht abstrakt durch die Insolvenzordnung, sondern fragt pro Norm nach Rolle, Verfahrensstand, Belegen, Fristen, Rechtsfolge, Gegenargumenten und dem nächsten verwertbaren Arbeitsergebnis.

Besonders hilfreich ist das bei Akten, in denen viele Ebenen gleichzeitig laufen: Eröffnungsantrag, Sicherungsmaßnahmen, Massezuordnung, Anfechtung, Forderungsprüfung, Insolvenzplan, Eigenverwaltung, Verbraucherinsolvenz, Nachlassinsolvenz oder internationales Insolvenzrecht. Weggefallene Vorschriften sind bewusst als Altfassungs- und Übergangsrechtsanker enthalten, damit alte Akten und ältere Rechtsprechung nicht versehentlich auf heutige Fälle übertragen werden.

Vor verbindlichen Aussagen prüft der jeweilige Skill den aktuellen Gesetzeswortlaut und verlangt für Rechtsprechung Gericht, Datum, Aktenzeichen und möglichst eine frei zugängliche amtliche oder gerichtliche Quelle. Literatur- und Datenbankfundstellen werden nicht aus Modellwissen behauptet.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `fachanwalt-insolvenz-sanierungsrecht-orientierung` | FAO § 14, InsO, StaRUG, EuInsVO, Quellenprüfung. |
| `fachanwalt-insolvenz-sanierungsrecht-glaeubigerantrag` | Gläubigerantrag § 14 InsO, Forderungs- und Insolvenzgrundsglaubhaftmachung. |
| `fachanwalt-insolvenz-sanierungsrecht-restrukturierungsplan` | Restrukturierungsplan StaRUG, Gruppenbildung, gerichtliche Planbestätigung. |
| `fachanwalt-insolvenz-sanierungsrecht-insolvenzanfechtung` | Anfechtungstatbestände §§ 129 ff. InsO (Schenkungs-, Vorsatz-, Deckungsanfechtung). |
| `inso-p001-...` bis `inso-p359-...` | Paragraphen-Navigator zur aktuellen Insolvenzordnung: pro InsO-Norm ein eigener Workflow mit Beleg-, Fristen-, Risiko- und Quellenprüfung. |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 45 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `eroeffnung-fachanwalt-fao-glaeubigerantrag` | Eroeffnung Behörden Gericht Und Registerweg, Fachanwalt Erstpruefung Und Mandatsziel, Fao Dokumentenmatrix Und Lueckenliste, Glaeubigerantrag Verhandlung Vergleich Und Eskalation: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit... |
| `fa-inso-sanierung-quellen-edge-case` | Rechtsquellen: Sonderfall und Edge-Case-Prüfung im Insolvenz- und Sanierungsrecht: fachlich vertiefter Fachmodul mit Normenradar (InsO/StaRUG/IDW-S6), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbremse u... |
| `fa-schuldschein` | Fa Insolvenz Schuldschein Und Lma: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `fachanwalt-insolvenz-sanierungsrecht-anschluss-routing` | Anschluss-Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `fachanwalt-insolvenz-sanierungsrecht-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `fachanwalt-insolvenz-sanierungsrecht-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `fachanwalt-insolvenz-sanierungsrecht-output-waehlen` | Output wählen: prüft Normen, Belege, Risiken, Gegenargumente und erzeugt ein verwertbares Arbeitsergebnis. |
| `fachanwalt-insolvenz-sanierungsrecht-quellen-livecheck` | Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `fachanwalt-insolvenz-sanierungsrecht-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `glaeubigerantrag-insolvenzanfechtung` | Fachanwalt Insolvenz Sanierungsrecht Glaeubigerantrag, Fachanwalt Insolvenz Sanierungsrecht Insolvenzanfechtung, Fachanwalt Insolvenz Sanierungsrecht Orientierung, Fachanwalt Insolvenz Sanierungsrecht Restrukturierungsplan: wählt den kon... |
| `glaeubigerverhandlung-sanierung-idw-s6-krypto` | Fachanwalt Insolvenz Glaeubigerverhandlung Sanierung, Fachanwalt Insolvenz Idw S6 Sanierungskonzept, Fachanwalt Insolvenz Krypto Verwertung, Fachanwalt Insolvenz Sanierung Starug Plan: wählt den konkreten Prüfpfad, trennt Frist, Zuständi... |
| `insanw-fortbestehensprognose` | Allgemein, Insanw Fortbestehensprognose Workflow, Chronologie Und Belegmatrix, Fristen Und Risikoampel: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `inso-insanw-eigenverwaltung-konzerninsolvenz` | Insanw Eigenverwaltung Schutzschirm Spezial, Insanw Konzerninsolvenz Koordination Spezial, Inso Anfechtung Zahlungsstrom Banken, Inso Arbeitnehmer Und Betriebsuebergang: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege u... |
| `inso-kommunikation-glaeubiger-p002` | Inso Kommunikation Glaeubiger, Inso P002 Amtsgericht Als Insolvenzgericht, Inso P003 Ortliche Zustandigkeit, Inso P003a Gruppen Gerichtsstand: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und lief... |
| `inso-livecheck-fristennotiz-sanierungsrecht` | Livecheck Fristennotiz Und Naechster Schritt, Sanierungsrecht Fristen Form Und Zustaendigkeit, Inso P104 Fixgeschafte Finanzleistungen Vertragliches Liquidatio, Inso P116 Erloschen Von Geschaftsbesorgungsvertragen: wählt den konkreten Pr... |
| `inso-p001-ziele-p003c-zustandigkeit-p004a` | Inso P001 Ziele Des Insolvenzverfahrens, Inso P003c Zustandigkeit Fur Gruppen Folgeverfahren, Inso P004a Stundung Der Kosten Des Insolvenzverfahrens, Inso P005 Verfahrensgrundsatze: wählt den konkreten Prüfpfad, trennt Frist, Zuständigke... |
| `inso-p003d` | Inso P003d Verweisung An Den Gruppen Gerichtsstand: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `inso-p003e-unternehmensgruppe-p004b` | Inso P003e Unternehmensgruppe, Inso P004b Ruckzahlung Und Anpassung Der Gestundeten Betrage, Inso P004c Aufhebung Der Stundung, Inso P004d Rechtsmittel: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlag... |
| `inso-p004-anwendbarkeit-p036-unpfandbare` | Redteam Qualitygate, Inso P004 Anwendbarkeit Der Zivilprozessordnung, Inso P036 Unpfandbare Gegenstande, Fachanwalt Insolvenz Sanierungsrecht Schutzschirmverfahren: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Re... |
| `inso-p020-auskunfts-p021-anordnung-p022` | Inso P020 Auskunfts Und Mitwirkungspflicht Im Eroffnungsverfahre, Inso P021 Anordnung Vorlaufiger Massnahmen, Inso P022 Rechtsstellung Des Vorlaufigen Insolvenzverwalters, Inso P022a Bestellung Eines Vorlaufigen Glaubigerausschusses: wäh... |
| `inso-p040-unterhaltsanspruche-p041-nicht-p042` | Inso P040 Unterhaltsanspruche, Inso P041 Nicht Fallige Forderungen, Inso P042 Auflosend Bedingte Forderungen, Inso P044 Rechte Der Gesamtschuldner Und Burgen: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgr... |
| `inso-p054-kosten-p088-vollstreckung-p095` | Inso P054 Kosten Des Insolvenzverfahrens, Inso P088 Vollstreckung Vor Verfahrenseroffnung, Inso P095 Eintritt Der Aufrechnungslage Im Verfahren, Inso P121 Betriebsanderungen Und Vermittlungsverfahren: wählt den konkreten Prüfpfad, trennt... |
| `inso-p061-nichterfullung-p062-verjahrung-p063` | Inso P061 Nichterfullung Von Masseverbindlichkeiten, Inso P062 Verjahrung, Inso P063 Vergutung Des Insolvenzverwalters, Inso P064 Festsetzung Durch Das Gericht: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechts... |
| `inso-p083-erbschaft-p084-auseinandersetzung` | Inso P083 Erbschaft Fortgesetzte Gutergemeinschaft, Inso P084 Auseinandersetzung Einer Gesellschaft Oder Gemeinschaf, Inso P085 Aufnahme Von Aktivprozessen, Inso P086 Aufnahme Bestimmter Passivprozesse: wählt den konkreten Prüfpfad, tren... |
| `inso-p092-gesamtschaden-p093-personliche-p227` | Inso P092 Gesamtschaden, Inso P093 Personliche Haftung Der Gesellschafter, Inso P227 Haftung Des Schuldners, Inso P280 Haftung Insolvenzanfechtung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und... |
| `inso-p109-schuldner-p110-p111-verausserung` | Inso P109 Schuldner Als Mieter Oder Pachter, Inso P110 Schuldner Als Vermieter Oder Verpachter, Inso P111 Verausserung Des Miet Oder Pachtobjekts, Inso P112 Kundigungssperre: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Bel... |
| `inso-p126` | Inso P126 Beschlussverfahren Zum Kundigungsschutz: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `inso-p134-unentgeltliche-p135` | Inso P134 Unentgeltliche Leistung, Inso P135 Gesellschafterdarlehen, Inso P136 Stille Gesellschaft, Inso P137 Wechsel Und Scheckzahlungen: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert... |
| `inso-p139-eroffnungsantrag-p147` | Inso P139 Berechnung Der Fristen Vor Dem Eroffnungsantrag, Inso P147 Rechtshandlungen Nach Verfahrenseroffnung, Inso P157 Entscheidung Uber Den Fortgang Des Verfahrens, Inso P200 Aufhebung Des Insolvenzverfahrens: wählt den konkreten Prü... |
| `inso-p155-steuerrecht-erstgespraech` | Inso P155 Handels Und Steuerrechtliche Rechnungslegung, Steuerrecht Formular Portal Und Einreichung, Erstgespraech Mandatsannahme, Fa Inso Drittstaaten Anerkennung Registervollzug: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkei... |
| `inso-p159-verwertung-p160-besonders-p161` | Inso P159 Verwertung Der Insolvenzmasse, Inso P160 Besonders Bedeutsame Rechtshandlungen, Inso P161 Vorlaufige Untersagung Der Rechtshandlung, Inso P162 Betriebsverausserung An Besonders Interessierte: wählt den konkreten Prüfpfad, trenn... |
| `inso-p180-zustandigkeit-p181-umfang-p182` | Inso P180 Zustandigkeit Fur Die Feststellung, Inso P181 Umfang Der Feststellung, Inso P182 Streitwert, Inso P183 Wirkung Der Entscheidung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert... |
| `inso-p203-anordnung-p204-rechtsmittel-p205` | Inso P203 Anordnung Der Nachtragsverteilung, Inso P204 Rechtsmittel, Inso P205 Vollzug Der Nachtragsverteilung, Inso P206 Ausschluss Von Masseglaubigern: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundla... |
| `inso-p223a-gruppeninterne-p224-rechte-p225` | Inso P223a Gruppeninterne Drittsicherheiten, Inso P224 Rechte Der Insolvenzglaubiger, Inso P225 Rechte Der Nachrangigen Insolvenzglaubiger, Inso P225a Rechte Der Anteilsinhaber: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit,... |
| `inso-p242-schriftliche-p243-abstimmung-p244` | Inso P242 Schriftliche Abstimmung, Inso P243 Abstimmung In Gruppen, Inso P244 Erforderliche Mehrheiten, Inso P245 Obstruktionsverbot: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den n... |
| `inso-p260-uberwachung-p261-aufgaben-p262` | Inso P260 Uberwachung Der Planerfullung, Inso P261 Aufgaben Und Befugnisse Des Insolvenzverwalters, Inso P262 Anzeigepflicht Des Insolvenzverwalters, Inso P263 Zustimmungsbedurftige Geschafte: wählt den konkreten Prüfpfad, trennt Frist,... |
| `inso-p270f-anordnung-p270g-eigenverwaltung` | Inso P270f Anordnung Der Eigenverwaltung, Inso P270g Eigenverwaltung Bei Gruppenangehorigen Schuldnern, Inso P271 Nachtragliche Anordnung, Inso P272 Aufhebung Der Anordnung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Bele... |
| `inso-p279-gegenseitige-p336-vertrag-p043` | Inso P279 Gegenseitige Vertrage, Inso P336 Vertrag Uber Einen Unbeweglichen Gegenstand, Inso P043 Haftung Mehrerer Personen, Inso P060 Haftung Des Insolvenzverwalters: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und... |
| `inso-p290-versagung-p291-weggefallen-p292` | Inso P290 Versagung Der Restschuldbefreiung, Inso P291 Weggefallen, Inso P292 Rechtsstellung Des Treuhanders, Inso P293 Vergutung Des Treuhanders: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und... |
| `inso-p308-annahme-p309-ersetzung-p310-kosten` | Inso P308 Annahme Des Schuldenbereinigungsplans, Inso P309 Ersetzung Der Zustimmung, Inso P310 Kosten, Inso P312bis314 Weggefallen: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den näc... |
| `inso-p335-grundsatz-p337-arbeitsverhaltnis` | Inso P335 Grundsatz, Inso P337 Arbeitsverhaltnis, Inso P338 Aufrechnung, Inso P339 Insolvenzanfechtung: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Belege und Rechtsgrundlage und liefert den nächsten belastbaren Output. |
| `inso-p359-schriftsatzkern-substantiierung` | Inso P359 Verweisung Auf Das Einfuhrungsgesetz, Schriftsatzkern Substantiierung, Antragspflicht Schriftsatz Brief Und Memo Bausteine, Berater Red Team Und Qualitaetskontrolle: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, Be... |
| `insolvenz-insolvenzanfechtung-insolvenzrecht` | Insolvenz Tatbestand Beweis Und Belege, Insolvenzanfechtung Compliance Dokumentation Und Akte, Insolvenzrecht Internationaler Bezug Und Schnittstellen, Krypto Mandantenkommunikation Entscheidungsvorlage: wählt den konkreten Prüfpfad, tre... |
| `interessen-verwertung-beweislast-starug` | Schnittstellen Mehrparteien Konflikt Und Interessen, Verwertung Beweislast Und Darlegungslast, Starug Restrukturierungsplan, Insolvenzanfechtung 129 Bis 147 Verteidigungsradar: wählt den konkreten Prüfpfad, trennt Frist, Zuständigkeit, B... |
| `starug-quellenkarte` | Starug Quellenkarte: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
