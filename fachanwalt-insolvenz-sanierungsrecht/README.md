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
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `eroeffnung-fachanwalt-fao-glaeubigerantrag` | Nutze dies bei Eroeffnung Behörden Gericht Und Registerweg, Fachanwalt Erstpruefung Und Mandatsziel, Fao Dokumentenmatrix Und Lueckenliste, Glaeubigerantrag Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Mod... |
| `fa-schuldschein` | Nutze dies bei Fa Insolvenz Schuldschein Und Lma: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `glaeubigerantrag-insolvenzanfechtung` | Nutze dies bei Fachanwalt Insolvenz Sanierungsrecht Glaeubigerantrag, Fachanwalt Insolvenz Sanierungsrecht Insolvenzanfechtung, Fachanwalt Insolvenz Sanierungsrecht Orientierung, Fachanwalt Insolvenz Sanierungsrecht Restrukturierungsplan... |
| `glaeubigerverhandlung-sanierung-idw-s6-krypto` | Nutze dies bei Fachanwalt Insolvenz Glaeubigerverhandlung Sanierung, Fachanwalt Insolvenz Idw S6 Sanierungskonzept, Fachanwalt Insolvenz Krypto Verwertung, Fachanwalt Insolvenz Sanierung Starug Plan: führt durch diese fachlich verbundene... |
| `insanw-fortbestehensprognose` | Nutze dies bei Allgemein, Insanw Fortbestehensprognose Workflow, Chronologie Und Belegmatrix, Fristen Und Risikoampel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbei... |
| `inso-insanw-eigenverwaltung-konzerninsolvenz` | Nutze dies bei Insanw Eigenverwaltung Schutzschirm Spezial, Insanw Konzerninsolvenz Koordination Spezial, Inso Anfechtung Zahlungsstrom Banken, Inso Arbeitnehmer Und Betriebsuebergang: führt durch diese fachlich verbundenen Module, wählt... |
| `inso-kommunikation-glaeubiger-p002` | Nutze dies bei Inso Kommunikation Glaeubiger, Inso P002 Amtsgericht Als Insolvenzgericht, Inso P003 Ortliche Zustandigkeit, Inso P003a Gruppen Gerichtsstand: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `inso-livecheck-fristennotiz-sanierungsrecht` | Nutze dies bei Livecheck Fristennotiz Und Naechster Schritt, Sanierungsrecht Fristen Form Und Zustaendigkeit, Inso P104 Fixgeschafte Finanzleistungen Vertragliches Liquidatio, Inso P116 Erloschen Von Geschaftsbesorgungsvertragen: führt d... |
| `inso-p001-ziele-p003c-zustandigkeit-p004a` | Nutze dies bei Inso P001 Ziele Des Insolvenzverfahrens, Inso P003c Zustandigkeit Fur Gruppen Folgeverfahren, Inso P004a Stundung Der Kosten Des Insolvenzverfahrens, Inso P005 Verfahrensgrundsatze: führt durch diese fachlich verbundenen M... |
| `inso-p003d` | Nutze dies bei Inso P003d Verweisung An Den Gruppen Gerichtsstand: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `inso-p003e-unternehmensgruppe-p004b` | Nutze dies bei Inso P003e Unternehmensgruppe, Inso P004b Ruckzahlung Und Anpassung Der Gestundeten Betrage, Inso P004c Aufhebung Der Stundung, Inso P004d Rechtsmittel: führt durch diese fachlich verbundenen Module, wählt den passenden Pr... |
| `inso-p004-anwendbarkeit-p036-unpfandbare` | Nutze dies bei Redteam Qualitygate, Inso P004 Anwendbarkeit Der Zivilprozessordnung, Inso P036 Unpfandbare Gegenstande, Fachanwalt Insolvenz Sanierungsrecht Schutzschirmverfahren: führt durch diese fachlich verbundenen Module, wählt den... |
| `inso-p020-auskunfts-p021-anordnung-p022` | Nutze dies bei Inso P020 Auskunfts Und Mitwirkungspflicht Im Eroffnungsverfahre, Inso P021 Anordnung Vorlaufiger Massnahmen, Inso P022 Rechtsstellung Des Vorlaufigen Insolvenzverwalters, Inso P022a Bestellung Eines Vorlaufigen Glaubigera... |
| `inso-p040-unterhaltsanspruche-p041-nicht-p042` | Nutze dies bei Inso P040 Unterhaltsanspruche, Inso P041 Nicht Fallige Forderungen, Inso P042 Auflosend Bedingte Forderungen, Inso P044 Rechte Der Gesamtschuldner Und Burgen: führt durch diese fachlich verbundenen Module, wählt den passen... |
| `inso-p054-kosten-p088-vollstreckung-p095` | Nutze dies bei Inso P054 Kosten Des Insolvenzverfahrens, Inso P088 Vollstreckung Vor Verfahrenseroffnung, Inso P095 Eintritt Der Aufrechnungslage Im Verfahren, Inso P121 Betriebsanderungen Und Vermittlungsverfahren: führt durch diese fac... |
| `inso-p061-nichterfullung-p062-verjahrung-p063` | Nutze dies bei Inso P061 Nichterfullung Von Masseverbindlichkeiten, Inso P062 Verjahrung, Inso P063 Vergutung Des Insolvenzverwalters, Inso P064 Festsetzung Durch Das Gericht: führt durch diese fachlich verbundenen Module, wählt den pass... |
| `inso-p083-erbschaft-p084-auseinandersetzung` | Nutze dies bei Inso P083 Erbschaft Fortgesetzte Gutergemeinschaft, Inso P084 Auseinandersetzung Einer Gesellschaft Oder Gemeinschaf, Inso P085 Aufnahme Von Aktivprozessen, Inso P086 Aufnahme Bestimmter Passivprozesse: führt durch diese f... |
| `inso-p092-gesamtschaden-p093-personliche-p227` | Nutze dies bei Inso P092 Gesamtschaden, Inso P093 Personliche Haftung Der Gesellschafter, Inso P227 Haftung Des Schuldners, Inso P280 Haftung Insolvenzanfechtung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfa... |
| `inso-p109-schuldner-p110-p111-verausserung` | Nutze dies bei Inso P109 Schuldner Als Mieter Oder Pachter, Inso P110 Schuldner Als Vermieter Oder Verpachter, Inso P111 Verausserung Des Miet Oder Pachtobjekts, Inso P112 Kundigungssperre: führt durch diese fachlich verbundenen Module,... |
| `inso-p126` | Nutze dies bei Inso P126 Beschlussverfahren Zum Kundigungsschutz: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `inso-p134-unentgeltliche-p135` | Nutze dies bei Inso P134 Unentgeltliche Leistung, Inso P135 Gesellschafterdarlehen, Inso P136 Stille Gesellschaft, Inso P137 Wechsel Und Scheckzahlungen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `inso-p139-eroffnungsantrag-p147` | Nutze dies bei Inso P139 Berechnung Der Fristen Vor Dem Eroffnungsantrag, Inso P147 Rechtshandlungen Nach Verfahrenseroffnung, Inso P157 Entscheidung Uber Den Fortgang Des Verfahrens, Inso P200 Aufhebung Des Insolvenzverfahrens: führt du... |
| `inso-p155-steuerrecht-erstgespraech` | Nutze dies bei Inso P155 Handels Und Steuerrechtliche Rechnungslegung, Steuerrecht Formular Portal Und Einreichung, Erstgespraech Mandatsannahme, Fa Inso Drittstaaten Anerkennung Registervollzug: führt durch diese fachlich verbundenen Mo... |
| `inso-p159-verwertung-p160-besonders-p161` | Nutze dies bei Inso P159 Verwertung Der Insolvenzmasse, Inso P160 Besonders Bedeutsame Rechtshandlungen, Inso P161 Vorlaufige Untersagung Der Rechtshandlung, Inso P162 Betriebsverausserung An Besonders Interessierte: führt durch diese fa... |
| `inso-p180-zustandigkeit-p181-umfang-p182` | Nutze dies bei Inso P180 Zustandigkeit Fur Die Feststellung, Inso P181 Umfang Der Feststellung, Inso P182 Streitwert, Inso P183 Wirkung Der Entscheidung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `inso-p203-anordnung-p204-rechtsmittel-p205` | Nutze dies bei Inso P203 Anordnung Der Nachtragsverteilung, Inso P204 Rechtsmittel, Inso P205 Vollzug Der Nachtragsverteilung, Inso P206 Ausschluss Von Masseglaubigern: führt durch diese fachlich verbundenen Module, wählt den passenden P... |
| `inso-p223a-gruppeninterne-p224-rechte-p225` | Nutze dies bei Inso P223a Gruppeninterne Drittsicherheiten, Inso P224 Rechte Der Insolvenzglaubiger, Inso P225 Rechte Der Nachrangigen Insolvenzglaubiger, Inso P225a Rechte Der Anteilsinhaber: führt durch diese fachlich verbundenen Modul... |
| `inso-p242-schriftliche-p243-abstimmung-p244` | Nutze dies bei Inso P242 Schriftliche Abstimmung, Inso P243 Abstimmung In Gruppen, Inso P244 Erforderliche Mehrheiten, Inso P245 Obstruktionsverbot: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `inso-p260-uberwachung-p261-aufgaben-p262` | Nutze dies bei Inso P260 Uberwachung Der Planerfullung, Inso P261 Aufgaben Und Befugnisse Des Insolvenzverwalters, Inso P262 Anzeigepflicht Des Insolvenzverwalters, Inso P263 Zustimmungsbedurftige Geschafte: führt durch diese fachlich ve... |
| `inso-p270f-anordnung-p270g-eigenverwaltung` | Nutze dies bei Inso P270f Anordnung Der Eigenverwaltung, Inso P270g Eigenverwaltung Bei Gruppenangehorigen Schuldnern, Inso P271 Nachtragliche Anordnung, Inso P272 Aufhebung Der Anordnung: führt durch diese fachlich verbundenen Module, w... |
| `inso-p279-gegenseitige-p336-vertrag-p043` | Nutze dies bei Inso P279 Gegenseitige Vertrage, Inso P336 Vertrag Uber Einen Unbeweglichen Gegenstand, Inso P043 Haftung Mehrerer Personen, Inso P060 Haftung Des Insolvenzverwalters: führt durch diese fachlich verbundenen Module, wählt d... |
| `inso-p290-versagung-p291-weggefallen-p292` | Nutze dies bei Inso P290 Versagung Der Restschuldbefreiung, Inso P291 Weggefallen, Inso P292 Rechtsstellung Des Treuhanders, Inso P293 Vergutung Des Treuhanders: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `inso-p308-annahme-p309-ersetzung-p310-kosten` | Nutze dies bei Inso P308 Annahme Des Schuldenbereinigungsplans, Inso P309 Ersetzung Der Zustimmung, Inso P310 Kosten, Inso P312bis314 Weggefallen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert de... |
| `inso-p335-grundsatz-p337-arbeitsverhaltnis` | Nutze dies bei Inso P335 Grundsatz, Inso P337 Arbeitsverhaltnis, Inso P338 Aufrechnung, Inso P339 Insolvenzanfechtung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbei... |
| `inso-p359-schriftsatzkern-substantiierung` | Nutze dies bei Inso P359 Verweisung Auf Das Einfuhrungsgesetz, Schriftsatzkern Substantiierung, Antragspflicht Schriftsatz Brief Und Memo Bausteine, Berater Red Team Und Qualitaetskontrolle: führt durch diese fachlich verbundenen Module,... |
| `insolvenz-insolvenzanfechtung-insolvenzrecht` | Nutze dies bei Insolvenz Tatbestand Beweis Und Belege, Insolvenzanfechtung Compliance Dokumentation Und Akte, Insolvenzrecht Internationaler Bezug Und Schnittstellen, Krypto Mandantenkommunikation Entscheidungsvorlage: führt durch diese... |
| `interessen-verwertung-beweislast-starug` | Nutze dies bei Schnittstellen Mehrparteien Konflikt Und Interessen, Verwertung Beweislast Und Darlegungslast, Starug Restrukturierungsplan, Insolvenzanfechtung 129 Bis 147 Verteidigungsradar: führt durch diese fachlich verbundenen Module... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `rechtsquellen-sonderfall-edge-case` | Rechtsquellen: Sonderfall und Edge-Case-Prüfung im Insolvenz- und Sanierungsrecht: fachlich vertiefter Fachmodul mit Normenradar (InsO/StaRUG/IDW-S6), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbremse u... |
| `starug-quellenkarte` | Nutze dies zur Quellenprüfung bei Starug Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
