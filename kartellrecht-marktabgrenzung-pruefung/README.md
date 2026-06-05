# Kartellrecht — Marktabgrenzungsprüfung

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`kartellrecht-marktabgrenzung-pruefung`) | [`kartellrecht-marktabgrenzung-pruefung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/kartellrecht-marktabgrenzung-pruefung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Nordstern MedTech Vertrieb - Provision, Buchauszug und Ausgleich** (`handelsvertreterrecht-provisionsausgleich-nordstern-medtech`) | [Gesamt-PDF lesen](../testakten/handelsvertreterrecht-provisionsausgleich-nordstern-medtech/gesamt-pdf/handelsvertreterrecht-provisionsausgleich-nordstern-medtech_gesamt.pdf) | [`testakte-handelsvertreterrecht-provisionsausgleich-nordstern-medtech.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-handelsvertreterrecht-provisionsausgleich-nordstern-medtech.zip) |
| **Zusammenschlusskontrolle GBW / Tannenheim — Bahnbetonschwellen, Bußgeld, ECN+** (`kartell-zusammenschlusskontrolle-bahnbetonschwellen-grosskopf-westfalen`) | [Gesamt-PDF lesen](../testakten/kartell-zusammenschlusskontrolle-bahnbetonschwellen-grosskopf-westfalen/gesamt-pdf/kartell-zusammenschlusskontrolle-bahnbetonschwellen-grosskopf-westfalen_gesamt.pdf) | [`testakte-kartell-zusammenschlusskontrolle-bahnbetonschwellen-grosskopf-westfalen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kartell-zusammenschlusskontrolle-bahnbetonschwellen-grosskopf-westfalen.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Globales Kartellrechts- und Competition-Law-Plugin mit Marktabgrenzung als harter Kernachse: GWB, Art. 101 und Art. 102 AEUV, EU-Fusionskontrolle, Bundeskartellamt, DG Competition, FTC/DOJ, Dawn Raids, Leniency, Private Enforcement, sektorale Deep Dives und vorsichtige Jurisdiktionschecks weltweit.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Zweck

Dieses Prüfwerkzeug analysiert kartellrechtliche Fälle auf juristischer, ökonomischer und methodischer Ebene. Es unterstützt bei:

- **Fusionskontrolle:** FKVO-Verfahren Phase I/II, BKartA-Verfahren, SIEC-Test.
- **Missbrauchsverfahren:** Art. 102 AEUV / §§ 19–20 GWB; Marktbeherrschungsnachweis.
- **Kartellverbot:** Art. 101 AEUV / § 1 GWB; Spürbarkeit, Bagatell-Ausnahme.
- **Globalen Behördenverfahren:** BKartA, Europäische Kommission, FTC/DOJ und nationale Wettbewerbsbehörden mit Local-Counsel-Fragen.
- **Sektorfällen:** Cloud, KI-Foundation-Models, App Stores, AdTech, Pharma, Energie, Telekom, Zahlungsverkehr, Automotive, Logistik, Sport und öffentliche Beschaffung.
- **Behördliche Stellungnahmen:** Stellungnahmen in BKartA- und Kommissionsverfahren.
- **Parteigutachten:** Kritische Würdigung gegnerischer Marktdefinitionen.

## Referenzen

| Datei | Inhalt |
| --- | --- |
| `references/methodik-marktdefinition.md` | Umfassende Darstellung der Marktdefinitions-Methodik (SSNIP, Elastizitäten, Supply-Side, räumlicher Markt, Evidenz) |
| `references/eugh-leitentscheidungen.md` | Chronologische Entscheidungssammlung EuGH/EuG/BGH/BKartA mit Kernsätzen zur Marktdefinition |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Tragende Aussagen müssen vor der Ausgabe anhand amtlicher Normfassungen, Behördenquellen oder frei zugänglicher Rechtsprechung geprüft werden. Das Prüfwerkzeug ersetzt keine eigene anwaltliche Prüfung im Einzelfall. Kartellrechtliche Marktdefinitionen und Behördenzuständigkeiten sind fallabhängig und können sich nach Markt, Transaktionsstruktur und Jurisdiktion ändern.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 59 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `19a-gwb-relative-abuse-economic` | 19A GWB Relative Abuse Economic im Kartellrecht (Marktabgrenzung): prüft konkret § 19a GWB überragende marktübergreifende Bedeutung, § 20 GWB relative Marktmacht, Relative Marktmacht und Economic Dependence, Algorithmic Collusion und AI... |
| `alleinvertrieb-kundengruppen-alternative` | Alleinvertrieb Kundengruppen Alternative im Kartellrecht (Marktabgrenzung): prüft konkret Alleinvertrieb Kundengruppen Gebietsschutz, Mandant will eine engere Marktabgrenzung argumentieren um, Mandant will eine weitere Marktabgrenzung ar... |
| `angebotsumstellung-evidenz-flags-red` | Angebotsumstellung Evidenz Flags RED im Kartellrecht (Marktabgrenzung): prüft konkret Angebotsumstellung, Evidenz, Flags, Kartellrechtliche. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `art-aeuv-auswirkungen-marktanteile` | ART Aeuv Auswirkungen Marktanteile im Kartellrecht (Marktabgrenzung): prüft konkret zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Art 102 AEUV Mis, Wie aendert sich der Marktanteil des Mandanten je nachdem. Liefert prio... |
| `art-arbeitsmarkt-no-aeuv-kooperationspruefung` | ART Arbeitsmarkt NO Aeuv Kooperationspruefung im Kartellrecht (Marktabgrenzung): prüft konkret Arbeitsmarkt No-Poach Wage-Fixing, zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Art 101 AEUV Koo, Art 101 AEUV Tatbestand V... |
| `bietergemeinschaft-vergabekartellrecht-bka` | Bietergemeinschaft Vergabekartellrecht BKA im Kartellrecht (Marktabgrenzung): prüft konkret Bietergemeinschaft Vergabekartellrecht, BKartA DG Competition FTC DOJ Routing, Settlement in Kartellverfahren, Organhaftung und Kartellrecht. Lie... |
| `competition-global-kaltstart` | Global Competition Kaltstart: Fachmodul für großes Kartellrecht mit BKartA, DG Competition, FTC/DOJ und internationalen Behörden; prüft welche Jurisdiktionen, Produkte, Märkte, Umsätze, Behörden, Deadlines und Verfahrensarten sofort rele... |
| `competition-litigation-programm-mittelstand` | Competition Litigation Programm Mittelstand im Kartellrecht (Marktabgrenzung): prüft konkret Kartellprozess Strategie, Compliance-Programm Kartellrecht Mittelstand, zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Complian... |
| `cross-border-dawn-raid-gwb-kartellverbot` | Cross Border Dawn Raid GWB Kartellverbot im Kartellrecht (Marktabgrenzung): prüft konkret Cross-Border Evidence Sharing, Global Dawn Raid War Room, § 1 GWB Kartellverbot nationale Prüfung, § 19 GWB Behinderungs Ausbeutungsmissbrauch. Lie... |
| `dma-gatekeeper-einkaufskooperation` | DMA Gatekeeper Einkaufskooperation im Kartellrecht (Marktabgrenzung): prüft konkret Digital Markets Act (VO 2022/1925), Einkaufskooperation Nachfragemacht, Einstweiliger Rechtsschutz Kartellrecht, Oekonomischer Gutachter oder Mandant leg... |
| `essential-facilities-eu-bekanntmachung` | Essential Facilities EU Bekanntmachung im Kartellrecht (Marktabgrenzung): prüft konkret Essential Facilities und Refusal to Deal, Skill zur neuen EU-Kommissions-Bekanntmachung zur, Bewertet die Qualitaet und Belastbarkeit der vorgelegten... |
| `eugh-rechtsprechung-beweislast-jurisdiktion` | Eugh Rechtsprechung Beweislast Jurisdiktion im Kartellrecht (Marktabgrenzung): prüft konkret Prüffeld für eugh rechtsprechung leitentscheidungen, Rechtsprechung, Jurisdiktionsskill Ägypten, Jurisdiktionsskill Albanien. Liefert priorisier... |
| `foreign-direct-freistellung-art` | Foreign Direct Freistellung ART im Kartellrecht (Marktabgrenzung): prüft konkret FDI und Antitrust Schnittstelle, Freistellung Art 101 Abs 3 AEUV Effizienz Verbraucheranteil, zur strukturierten Aufnahme, Priorisierung und Ausgabe im Them... |
| `fusionskontrolle-modus-geoblocking` | Fusionskontrolle Modus Geoblocking im Kartellrecht (Marktabgrenzung): prüft konkret Prüft Marktabgrenzung im Kontext der EU-Fusionskontrolle, Geoblocking und Kartellrecht Schnittstelle, Gesamturteil zur Tragfähigkeit einer Marktabgrenzun... |
| `healthcare-kartellrecht-horizontal-gvo` | Healthcare Kartellrecht Horizontal GVO im Kartellrecht (Marktabgrenzung): prüft konkret Healthcare Kartellrecht Kooperation Kliniken, Horizontal-GVO Forschung und Entwicklung, Horizontal-GVO Spezialisierung, Hub-and-Spoke-Kartelle. Liefe... |
| `information-exchange-informationsaustausch` | Information Exchange Informationsaustausch im Kartellrecht (Marktabgrenzung): prüft konkret Informationsaustausch Safe Harbor, Informationsaustausch Wettbewerber, Marktabgrenzung in dynamischen Technologiemaerkten wo, Joint Venture Full... |
| `jurisdiktion-algerien-competition-andorra` | Jurisdiktion Algerien Competition Andorra im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Algerien, Jurisdiktionsskill Andorra, Jurisdiktionsskill Angola, Jurisdiktionsskill Argentinien. Liefert priorisierten Output m... |
| `jurisdiktion-armenien-aserbaidschan` | Jurisdiktion Armenien Aserbaidschan im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Armenien, Jurisdiktionsskill Aserbaidschan. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `jurisdiktion-australien-competition-bahrain` | Jurisdiktion Australien Competition Bahrain im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Australien, Jurisdiktionsskill Bahrain, Jurisdiktionsskill Bangladesch, Jurisdiktionsskill Barbados. Liefert priorisierten Ou... |
| `jurisdiktion-costa-rica-daenemark-competition` | Jurisdiktion Costa Rica Daenemark Competition im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Costa Rica, Jurisdiktionsskill Dänemark, Jurisdiktionsskill Deutschland, Jurisdiktionsskill Dominikanische Republik. Liefer... |
| `jurisdiktion-guatemala-competition-honduras` | Jurisdiktion Guatemala Competition Honduras im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Guatemala, Jurisdiktionsskill Honduras, Jurisdiktionsskill Hongkong, Jurisdiktionsskill Indien. Liefert priorisierten Output... |
| `jurisdiktion-kasachstan-competition-katar` | Jurisdiktion Kasachstan Competition Katar im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Kasachstan, Jurisdiktionsskill Katar, Jurisdiktionsskill Kenia, Jurisdiktionsskill Kirgisistan. Liefert priorisierten Output mi... |
| `jurisdiktion-luxemburg-competition-macau` | Jurisdiktion Luxemburg Competition Macau im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Luxemburg, Jurisdiktionsskill Macau, Jurisdiktionsskill Madagaskar, Jurisdiktionsskill Malawi. Liefert priorisierten Output mit... |
| `jurisdiktion-nepal-competition-neuseeland` | Jurisdiktion Nepal Competition Neuseeland im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Nepal, Jurisdiktionsskill Neuseeland, Jurisdiktionsskill Nicaragua, Jurisdiktionsskill Niederlande. Liefert priorisierten Outpu... |
| `jurisdiktion-peru-competition-philippinen` | Jurisdiktion Peru Competition Philippinen im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Peru, Jurisdiktionsskill Philippinen, Jurisdiktionsskill Polen, Jurisdiktionsskill Portugal. Liefert priorisierten Output mit N... |
| `jurisdiktion-slowakei-competition-slowenien` | Jurisdiktion Slowakei Competition Slowenien im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Slowakei, Jurisdiktionsskill Slowenien, Jurisdiktionsskill Spanien, Jurisdiktionsskill Sri Lanka. Liefert priorisierten Outpu... |
| `jurisdiktion-ungarn-competition-uruguay` | Jurisdiktion Ungarn Competition Uruguay im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Ungarn, Jurisdiktionsskill Uruguay, Jurisdiktionsskill USA, Jurisdiktionsskill Usbekistan. Liefert priorisierten Output mit Norm-... |
| `jurisdiktion-venezuela-competition-vereinigte` | Jurisdiktion Venezuela Competition Vereinigte im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Venezuela, Jurisdiktionsskill Vereinigte Arabische Emirate, Jurisdiktionsskill Vereinigtes Königreich, Jurisdiktionsskill V... |
| `jurisdiktion-zimbabwe-zypern-competition-eu` | Jurisdiktion Zimbabwe Zypern Competition EU im Kartellrecht (Marktabgrenzung): prüft konkret Jurisdiktionsskill Zimbabwe, Jurisdiktionsskill Zypern, EU-Fusionskontrolle FKVO Zuständigkeit, Schiedsverfahren Kartellrecht Einwand Nichtigkei... |
| `kart-innovationswettbewerb` | Kart Innovationswettbewerb im Kartellrecht (Marktabgrenzung): prüft konkret Spezialfall Innovationswettbewerb und Killer Acquisitions, Leitfaden Marktanteilsanalyse, Bauleiter Marktdefinition, Spezialfall zweiseitige Plattformen / Mehrse... |
| `kartellrecht-kaltstart-mandat-neu` | Kartellrecht Kaltstart Mandat neu: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `kartellrecht-marktabgrenzung-pruefung-anschluss` | Anschluss im Kartellrecht (Marktabgrenzung): prüft konkret Einstieg, Schnelltriage und Fallrouting im Kartellrecht, Anschluss-Skills Router im Plugin, Chronologie und Belegmatrix im Plugin. Liefert priorisierten Output mit Norm-Pinpoints... |
| `kartellrecht-marktabgrenzung-pruefung-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `kartellrecht-marktabgrenzung-pruefung-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `kartellrecht-marktabgrenzung-pruefung-output-waehlen` | Output wählen im Kartellrecht (Marktabgrenzung): Diese Output-Weiche für Kartellrecht Marktabgrenzung Prüfung entscheidet, ob Memo, Antrag, Schriftsatz, Tabelle, Risikoampel, Fragenliste oder Mandantenbrief der richtige nächste Schritt ist. |
| `kartellrecht-marktabgrenzung-pruefung-quellen-livecheck` | Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `kartellrecht-marktabgrenzung-pruefung-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `kartellrechtliche-vertragsklausel` | Kartellrechtliche Vertragsklausel im Kartellrecht (Marktabgrenzung): prüft konkret Kartellrechtliche Vertragsklausel-Redline, Bußgeldbemessung Unternehmen Verband, Geschäftsleiterhaftung Kartellverstoß, Kartellschadensersatz § 33a GWB. L... |
| `ki-preisgestaltung-konsistenzpruefung` | KI Preisgestaltung Konsistenzpruefung im Kartellrecht (Marktabgrenzung): prüft konkret KI Preisgestaltung Kartellrecht, Prüft die interne Widerspruchsfreiheit einer Marktabgrenzung, Kronzeugenprogramm Bonusregelung, Labor Antitrust No-Po... |
| `kritische-markt-interessen-marktabgrenzungen` | Kritische Markt Interessen Marktabgrenzungen im Kartellrecht (Marktabgrenzung): prüft konkret Kritische, Markt, Marktabgrenzungen, Marktbeherrschung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `leniency-marker-margin-squeeze-telekom` | Leniency Marker Margin Squeeze Telekom im Kartellrecht (Marktabgrenzung): prüft konkret Leniency und Marker global, Margin Squeeze und Predatory Pricing, Margin Squeeze Telekom Energie Plattform, EU Marktdefinitionsbekanntmachung 2024. L... |
| `marktabgrenzung-kontextanalyse-mehrseitige` | Kontextanalyse Mehrseitige im Kartellrecht (Marktabgrenzung): prüft konkret Verfahren beginnt und Verfahrensart und Parteistellung, Prüffeld für mehrseitige maerkte plattformen, Merger Remedies global, Ministererlaubnis § 42 GWB. Liefert... |
| `minimis-inlandsauswirkung-digital-platforms` | Minimis Inlandsauswirkung Digital Platforms im Kartellrecht (Marktabgrenzung): prüft konkret De-minimis Inlandsauswirkung Fusionskontrolle, Digitale Plattformen Self-Preferencing, Disclosure § 33g GWB Akteneinsicht, DMA Schnittstelle Kar... |
| `missbrauchsverbot-modus` | Missbrauchsverbot Modus im Kartellrecht (Marktabgrenzung): prüft konkret Unternehmen in marktbeherrschender Stellung soll auf, Nachhaltigkeitskooperation Wettbewerbsrecht, Nicht-horizontale Fusion vertikal konglomerat, Prüft Marktbeherrs... |
| `nachfrage-quellenkarte` | Nachfrage Quellenkarte: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `paragraf-raeumlicher-ssnip-test` | Paragraf Raeumlicher Ssnip Test im Kartellrecht (Marktabgrenzung): prüft konkret Paragraf, Raeumlicher, Ssnip, Test. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `predatory-pricing-preisalgorithmen-kollusives` | Predatory Pricing Preisalgorithmen Kollusives im Kartellrecht (Marktabgrenzung): prüft konkret Predatory Pricing Kampfpreise, Preisalgorithmen kollusives Risiko, Preisbindung der zweiten Hand RPM, Presseverlage Plattformen Leistungsschut... |
| `private-enforcement-produktmarkt` | Private Enforcement Produktmarkt im Kartellrecht (Marktabgrenzung): prüft konkret Private Enforcement und Kartellschaden, Prüft angebotsseitige Substitution (Supply-Side, Kernschritt jeder Marktabgrenzung, Bid Rigging und Vergabe. Liefer... |
| `private-enforcement-rechtsabteilung` | Private Enforcement Rechtsabteilung im Kartellrecht (Marktabgrenzung): prüft konkret zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Private Enforcem, Rechtsabteilungs-Fachmodul für Kartellschadenersatz nach, Sammelklagen... |
| `pruefinstanz-franchise-vertrag` | Pruefinstanz Franchise Vertrag im Kartellrecht (Marktabgrenzung): prüft konkret Pruefinstanz, Franchise-Vertrag Kartellrecht. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `rechtsabteilung-gun-informationsaustausch` | Rechtsabteilung GUN Informationsaustausch im Kartellrecht (Marktabgrenzung): prüft konkret Rechtsabteilungs-Fachmodul für Gun-Jumping im, Rechtsabteilungs-Fachmodul für Informationsaustausch im, Rechtsabteilungs-Fachmodul für Meta-Plattf... |
| `refusal-to-remedies-zusagen-section-19a` | Refusal TO Remedies Zusagen Section 19A im Kartellrecht (Marktabgrenzung): prüft konkret Refusal to Supply Essential Facilities, Remedies Zusagen Veräußerung Zugang, § 19a GWB Big Tech, Sektor AdTech und digitale Werbung. Liefert prioris... |
| `sektor-app-stores-automotive-zulieferketten` | Sektor APP Stores Automotive Zulieferketten im Kartellrecht (Marktabgrenzung): prüft konkret Sektor App-Stores und mobile Ökosysteme, Sektor Automotive, Zulieferketten und OEMs, Sektor Cloud-Infrastruktur und Hyperscaler. Liefert prioris... |
| `sektor-krankenhaus-gesundheitsplattformen` | Sektor Krankenhaus Gesundheitsplattformen im Kartellrecht (Marktabgrenzung): prüft konkret Sektor Krankenhaus, Gesundheitsplattformen und Versorgung, Sektor Lebensmittelhandel und Einkaufsallianzen, Sektor Logistik. Liefert priorisierten... |
| `sektor-sportligen-medienrechte` | Sektor Sportligen Medienrechte im Kartellrecht (Marktabgrenzung): prüft konkret Sektor Sportligen, Medienrechte und Ticketing, Sektor Telekommunikation und Infrastructure Sharing, Sektor Zahlungsverkehr. Liefert priorisierten Output mit... |
| `self-preferencing-sep-frand-siec-test-aeuv` | Self Preferencing SEP Frand Siec Test Aeuv im Kartellrecht (Marktabgrenzung): prüft konkret Self-Preferencing Plattformen, SEP FRAND Kartellrecht, SIEC-Test EU Fusionskontrolle, SIEC-Test horizontale Fusion. Liefert priorisierten Output... |
| `spuerbarkeit-zwischenstaatlichkeit-ssnip-test` | Spuerbarkeit Zwischenstaatlichkeit Ssnip Test im Kartellrecht (Marktabgrenzung): prüft konkret Spürbarkeit und Zwischenstaatlichkeit, Sachlichen Markt mit dem SSNIP-Test abgrenzen ob ein, EU State Aid Schnittstelle, Verbände und Kartellr... |
| `verbandsarbeit-informationsaustausch` | Verbandsarbeit Informationsaustausch im Kartellrecht (Marktabgrenzung): prüft konkret Verbandsarbeit Informationsaustausch Grenzen, Vergleichsvereinbarung Patent Settlement Pay-for-delay, Vertical Restraints und VBER, Vertikal-GVO 2022/7... |
| `vertikale-leitlinien-verweisung-art` | Vertikale Leitlinien Verweisung ART im Kartellrecht (Marktabgrenzung): prüft konkret Vertikale Leitlinien EU selektiver Vertrieb Plattformverbote, Verweisung Art 4 9 22 FKVO, Vollzugsverbot Gun Jumping. Liefert priorisierten Output mit N... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
