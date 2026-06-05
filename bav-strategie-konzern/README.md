# BAV Strategie Konzern — Treuenfels Yamamoto Rechtsanwälte Partnerschaft mbB

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`bav-strategie-konzern`) | [`bav-strategie-konzern.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/bav-strategie-konzern.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Betriebliche Altersversorgung – MEISSNER RHEINWERK AG** (`bav-strategie-konzern-meissner-rheinwerk-ag`) | [Gesamt-PDF lesen](../testakten/bav-strategie-konzern-meissner-rheinwerk-ag/gesamt-pdf/bav-strategie-konzern-meissner-rheinwerk-ag_gesamt.pdf) | [`testakte-bav-strategie-konzern-meissner-rheinwerk-ag.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bav-strategie-konzern-meissner-rheinwerk-ag.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin stellt 21 spezialisierte Skills für die strategische Beratung zur betrieblichen Altersversorgung (BAV) in Konzernen bereit. Es spiegelt den Beratungsansatz der Boutique-Großkanzlei **Treuenfels Yamamoto Rechtsanwälte Partnerschaft mbB**, Königsallee 92, 40212 Düsseldorf (Zweigbüro: Gion-Higashi, Shijō-dōri, Kyoto).

**Namens-Partner:**
- Dr. Dr. Hartwig Treuenfels-Ostermann, LL.M. (Cambridge), Of Counsel, Honorarprofessor Düsseldorf für Arbeits- und Vergütungsrecht
- Yuki Yamamoto-Brennecke, bengoshi + Rechtsanwältin (Tokyo Bar), Leiterin Kyoto-Büro

**Federführender Partner BAV/Versorgung:**
Prof. Dr. Adalbert von Sompeh-Ostermann, LL.M. (Oxford), Versorgungs- und Transaktionsspezialist

---

## Installation

1. ZIP aus dem Release herunterladen.
2. Claude Code oder Claude Desktop/Cowork öffnen.
3. **Customize Plugins** bzw. **Personal plugins** öffnen.
4. **Install from .zip** wählen und `bav-strategie-konzern.zip` hochladen.
5. Mit einem konkreten Auftrag starten, zum Beispiel: `Prüfe unsere Konzern-Versorgungsordnung und schlage eine Harmonisierungsstrategie vor.`

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json` und `skills/` enthalten.

## Block A — Pensionsmodelle & Versorgungsarchitektur

| # | Skill-Name | Kurzbeschreibung |
|---|-----------|-----------------|
| 1 | `pensionsmodelle-fuenf-durchfuehrungswege` | Direktzusage vs. Unterstützungskasse vs. Pensionskasse vs. Pensionsfonds vs. Direktversicherung; Entscheidungsmatrix, Bilanz- und Risiko-Tradeoffs, IFRS/HGB |
| 2 | `versorgungsordnung-und-betriebsvereinbarung-drafting` | Volltext-Templates Versorgungsordnung und Betriebsvereinbarung (Düsseldorfer Schule), Anpassungsklauseln § 16 BetrAVG, Spätehenklauseln, Hinterbliebenenversorgung |
| 3 | `governance-und-anpassungsmechanismen` | Pension Committee Charter, Trustee-Boards, Anpassungsentscheidungen § 16 BetrAVG, sachlich-billige Ermessensausübung |
| Rechtsprechung live prüfen | Live-Verifikation erforderlich | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| 5 | `internationale-harmonisierung-konzern-bav` | Konzernweite Plan-Inventory, Country-by-Country Matrix DE/UK/USA/FR/SG/JP, Global Benefits Policy, Local-vs-Group Governance |

## Block B — Pension Buyouts

| # | Skill-Name | Kurzbeschreibung |
|---|-----------|-----------------|
| 6 | `pension-buyout-strukturierung-und-de-risking` | Buy-in vs. Buy-out vs. Longevity Swap, Versichererauswahl, Term Sheets, BaFin-Genehmigung |
| Rechtsprechung live prüfen | Live-Verifikation erforderlich | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| Rechtsprechung live prüfen | Live-Verifikation erforderlich | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| 9 | `buyout-im-ma-deal-asset-vs-share` | Pension Liabilities in Carve-outs, § 613a BGB, ABC-Klauseln, Garantien/Indemnities, W&I-Versicherung |
| 10 | `internationale-buyout-datenflows-und-datenschutz` | Art. 9 DSGVO, Drittlandtransfer Art. 46 SCC, APPI/PIPC Japan, Schrems II Workaround |

## Block C — Komplexe Versorgungssysteme

| # | Skill-Name | Kurzbeschreibung |
|---|-----------|-----------------|
| 11 | `historisch-gewachsene-altsysteme-due-diligence` | Inventory-Methodik, Altzusagen 1970er/1980er, Versorgungstarifverträge, Sonderzusagen Führungskräfte, Risk Map |
| Rechtsprechung live prüfen | Live-Verifikation erforderlich | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| 13 | `mitbestimmung-betriebsrat-einigungsstelle-bav` | § 87 Abs. 1 Nr. 8/10 BetrVG, Initiativrecht, Einigungsstellenverfahren, Spruch-Templates |
| 14 | `kollektivrechtliche-loesungen-und-sozialplan` | § 112 BetrVG, pensionsspezifische Sozialplanbestandteile, Abfindungsmodelle vs. Versorgungserhalt |

## Block D — Internationale Benefits-Strukturen

| # | Skill-Name | Kurzbeschreibung |
|---|-----------|-----------------|
| 15 | `country-by-country-benefits-matrix-konzern` | Standardisierte Tabelle DE/UK/US/FR/SG/JP/NL/CH, lokale zwingende Vorschriften, Expat-Behandlung |
| 16 | `expatriate-pensionsplanung-und-totalization` | Sozialversicherungsabkommen, A1-Bescheinigung, Doppelbesteuerungsabkommen, Stranded Pensions |
| 17 | `japan-bav-und-corporate-pension-iorp` | Kakutei-kyuufu kigyou nenkin, Tax-Qualified Pension Plan Sunset, japanische DC-Pläne, Düsseldorf-Kyoto-Kollaboration |
| 18 | `post-merger-bav-integration-global` | HR-Transformation, Global-Mobility-Bezug, Reward-Harmonisierung, Day-1/Day-100/Day-365-Plan |

## Block E — Restrukturierungen & Kanzlei-Werkzeuge

| # | Skill-Name | Kurzbeschreibung |
|---|-----------|-----------------|
| 19 | `db-zu-dc-umstellung-mit-besitzstand` | DB-Schließung mit Past-Service-Schutz und Future-Service-DC, BAG-konforme Umstellung |
| 20 | `anpassungspruefung-paragraph-16-betravg` | Drei-Jahres-Rhythmus, wirtschaftliche Lage des Arbeitgebers, Reallohn-Bezugsgrößen-Verfahren |
| 21 | `mandantenkorrespondenz-bav-grosskanzlei-stil` | Briefkopf-Templates Treuenfels Yamamoto (deutsch/japanisch/englisch), Engagement Letter mit Stundensätzen, KYC |

---

*Alle Mandantennamen und Beratungsbeispiele in den Skills sind fiktiv. Die zitierten Gerichtsentscheidungen und Gesetze sind reale Quellen.*

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-design-workflow-chronologie` | Nutze dies bei Allgemein, Bav Konzern Design Workflow, Chronologie Und Belegmatrix, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `altersversorgung-boutique-fristennotiz-psv` | Nutze dies bei Altersversorgung Fristen Form Und Zustaendigkeit, Boutique Fristennotiz Und Naechster Schritt, Psv Pensionssicherungsverein Und Haftungsketten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad un... |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `betrieblichen-drei-duesseldorfer-sonderfall` | Nutze dies bei Betrieblichen Tatbestand Beweis Und Belege, Drei Zahlen Schwellen Und Berechnung, Duesseldorfer Sonderfall Und Edge Case: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `buyout-ma-country-by-cta-contractual` | Nutze dies bei Buyout Im Ma Deal Asset Vs Share, Country By Country Benefits Matrix Konzern, Cta Contractual Trust Arrangement Strukturierung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nä... |
| `buyouts-quellenkarte` | Nutze dies zur Quellenprüfung bei Buyouts Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `drei-stufen-expatriate-pensionsplanung` | Nutze dies bei Drei Stufen Theorie Eingriffsanalyse, Expatriate Pensionsplanung Und Totalization, Governance Und Anpassungsmechanismen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `durchfuehrungswege-fuenf-harmonisierung` | Nutze dies bei Durchfuehrungswege Schriftsatz Brief Und Memo Bausteine, Fuenf Behörden Gericht Und Registerweg, Harmonisierung Formular Portal Und Einreichung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad u... |
| `einfuehrung-durchfuehrungswege-erstattung` | Nutze dies bei Bav Einfuehrung Durchfuehrungswege, Bav Erstattung Fuenftelregelung, Bav Grenzueberschreitend Mobil Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies bei Fristen Und Risikoampel, Mandantenkommunikation, Redteam Qualitygate: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `harmonisierung-migration-historisch` | Nutze dies bei Harmonisierung Und Migration Rechtssicher, Historisch Gewachsene Altsysteme Due Diligence, Internationale Buyout Datenflows Und Datenschutz: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und l... |
| `internationale-fehlerkatalog` | Nutze dies als Fehlerbremse bei Internationale Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `internationale-harmonisierung-japan-corporate` | Nutze dies bei Internationale Harmonisierung Konzern Bav, Japan Bav Und Corporate Pension Iorp, Kollektivrechtliche Loesungen Und Sozialplan: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näc... |
| `konzernen-pension-pensionsmodelle` | Nutze dies bei Konzernen Dokumentenmatrix Und Lueckenliste, Pension Verhandlung Vergleich Und Eskalation, Pensionsmodelle Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `mitbestimmung-betriebsrat-pension-buyout` | Nutze dies bei Mitbestimmung Betriebsrat Einigungsstelle Bav, Pension Buyout Strukturierung Und De Risking, Benefits Mandantenkommunikation Entscheidungsvorlage: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `pensionsmodelle-fuenf-bav-cta-pensionsfond` | Nutze dies bei Pensionsmodelle Fuenf Durchfuehrungswege, Bav Cta Treuhand Spezial, Bav Pensionsfond Rueckdeckung Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Ar... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `restrukturierung-beweislast-stil-strategische` | Nutze dies bei Restrukturierung Beweislast Und Darlegungslast, Stil Abschlussprodukt Und Uebergabe, Strategische Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nä... |
| `stufen-theorie-interessen-versorgungssystem` | Nutze dies bei Stufen Compliance Dokumentation Und Akte, Theorie Mehrparteien Konflikt Und Interessen, Versorgungssystem International Schnittstellen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefer... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `versorgungsordnung-betriebsvereinbarung` | Nutze dies bei Versorgungsordnung Und Betriebsvereinbarung Drafting: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
