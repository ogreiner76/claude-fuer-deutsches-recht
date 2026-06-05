# Berufsrecht Anwälte

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`berufsrecht-anwaelte`) | [`berufsrecht-anwaelte.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/berufsrecht-anwaelte.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Falkenried & Partner mbB — Managementakte Q2/2026** (`kanzlei-management-falkenried-partnerkreis-q2-2026`) | [Gesamt-PDF lesen](../testakten/kanzlei-management-falkenried-partnerkreis-q2-2026/gesamt-pdf/kanzlei-management-falkenried-partnerkreis-q2-2026_gesamt.pdf) | [`testakte-kanzlei-management-falkenried-partnerkreis-q2-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kanzlei-management-falkenried-partnerkreis-q2-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Plugin für anwaltliches Berufsrecht: BRAO, BORA, FAO, beA, Kanzleisitz, Werbung, Interessenkollision, Verschwiegenheit, KI-/Cloud-Outsourcing, Fremdbesitz, Berufsausübungsgesellschaft, Gebühren, Kammeraufsicht und anwaltsgerichtliche Risiken.

## Worum es geht

Dieses Plugin ist ein experimentelles Arbeits- und Lernwerkzeug. Es soll keine echten Amts-, Mandats-, Steuer-, Prüfungs- oder Berufsgeheimnisse aufnehmen, solange die technische und rechtliche Umgebung dafür nicht ausdrücklich freigegeben ist. Es arbeitet am besten mit anonymisierten, abstrahierten oder synthetischen Fällen und mit Dokumenten, die vor der Nutzung datenschutz- und geheimnisschutzrechtlich geprüft wurden.

## Arbeitsweise

Der Allgemein-Skill startet kurz, sortiert Rolle, Verfahrensstand, Frist, Unterlagen und gewünschtes Arbeitsprodukt und routet dann in die passenden Spezial-Skills. Jeder Skill verlangt Quellenhygiene: Normen, Behördenhinweise, Formulare und Rechtsprechung werden vor tragenden Aussagen live aus amtlichen oder frei zugänglichen Quellen geprüft; keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate.

## Typische Outputs

- Kurzvermerk und Risikoampel
- Checkliste für den nächsten Arbeitstag
- Fragenliste an Behörde, Gericht, Kammer, Mandant, Partei oder Zeugen
- Entwurf für Verfügung, Vermerk, Schriftsatz, Antrag, E-Mail oder Gesprächsleitfaden
- Red-Team-Check gegen Fristenfehler, Zuständigkeitsfehler und Scheingenauigkeit
- KI-/Outsourcing-Freigabevermerk nach § 43e BRAO mit Consumer-Tool-Abgrenzung, No-Training, Drittstaat, Schatten-KI-Policy, KI-VO-Transparenz und anwaltlicher Endkontrolle

## Installation

ZIP aus dem aktuellen Release laden und in Claude Code oder Cowork über Customize Plugins installieren.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 51 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `ai-act-aktenherausgabe-zurueckbehaltung` | AI ACT Aktenherausgabe Zurueckbehaltung im Berufsrecht der Anwälte: prüft konkret AI-Act-Transparenz in der Kanzlei prüfen, Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-aktenherausgabe-zurueckbehaltung-fak` | Anwälte: aktenherausgabe und zurueckbehaltung - Kaltstart mit Faktenmatrix, Risikoampel und fehlenden Unterlagen; mit Live-Normencheck, Kammerlogik, Verhältnismäßigkeit, Belegplan und nächstem Schritt. |
| `anwaelte-anwaltliche-nebentaetigkeit` | Anwälte: anwaltliche nebentaetigkeit - Kaltstart mit Faktenmatrix, Risikoampel und fehlenden Unterlagen; mit Live-Normencheck, Kammerlogik, Verhältnismäßigkeit, Belegplan und nächstem Schritt. |
| `anwaelte-anwaltsgerichtliche-anschuldigung` | Anwälte: anwaltsgerichtliche anschuldigung - Kaltstart mit Faktenmatrix, Risikoampel und fehlenden Unterlagen; mit Live-Normencheck, Kammerlogik, Verhältnismäßigkeit, Belegplan und nächstem Schritt. |
| `anwaelte-bea-passive-nutzung` | Anwälte: bea passive nutzung und empfangsbekenntnis - Kaltstart mit Faktenmatrix, Risikoampel und fehlenden Unterlagen; mit Live-Normencheck, Kammerlogik, Verhältnismäßigkeit, Belegplan und nächstem Schritt. |
| `anwaelte-berufsausuebungsgesellschaft` | Anwälte: berufsausuebungsgesellschaft und fremdbesitz - Kaltstart mit Faktenmatrix, Risikoampel und fehlenden Unterlagen; mit Live-Normencheck, Kammerlogik, Verhältnismäßigkeit, Belegplan und nächstem Schritt. |
| `anwaelte-berufsrechtliche` | Anwälte: berufsrechtliche notfallkommunikation - Kaltstart mit Faktenmatrix, Risikoampel und fehlenden Unterlagen; mit Live-Normencheck, Kammerlogik, Verhältnismäßigkeit, Belegplan und nächstem Schritt. |
| `anwaelte-beschwerde-rechtsanwaltskammer-fakte` | Anwälte: beschwerde bei rechtsanwaltskammer - Kaltstart mit Faktenmatrix, Risikoampel und fehlenden Unterlagen; mit Live-Normencheck, Kammerlogik, Verhältnismäßigkeit, Belegplan und nächstem Schritt. |
| `anwaelte-datenschutzpanne-kanzlei` | Datenschutzpanne Kanzlei im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-fristversaeumnis-wiedereinsetzung` | Fristversaeumnis Wiedereinsetzung im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-geldwaesche-risikoanalyse` | Geldwaesche Risikoanalyse im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-honorarvereinbarung-rvg` | Honorarvereinbarung RVG im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-internationales-geheimnisschutz` | Internationales Geheimnisschutz im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-kammeraufsicht-kammerantwort` | Kammeraufsicht Kammerantwort im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-ki-tool-legal-tech-mandatsgeheimnis` | KI Tool Legal Tech Mandatsgeheimnis im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-legal-tech-mandatskuendigung-unzeit` | Legal Tech Mandatskuendigung Unzeit im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-qualitaetsmanagement-vier-robe` | Qualitaetsmanagement Vier Robe im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-ruege-gegenvorstellung-sanktionen` | Ruege Gegenvorstellung Sanktionen im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-ruege-gegenvorstellung-schatten-ki` | Ruege Gegenvorstellung Schatten KI im Berufsrecht der Anwälte: prüft konkret Anwälte, Schatten-KI in der Kanzlei verhindern. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-syndikusrechtsanwalt-abgrenzung` | Syndikusrechtsanwalt Abgrenzung im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-umgehung-berufsgericht` | Umgehung Berufsgericht im Berufsrecht der Anwälte: prüft konkret Anwälte, Berufsgericht und Disziplinarverfahren, Fristen- und Zuständigkeitscockpit, Fristenkontrolle. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näch... |
| `anwaelte-verschwiegenheit-cloud-outsourcing` | Verschwiegenheit Cloud Outsourcing im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaelte-werbung-google-aktenherausgabe` | Werbung Google Aktenherausgabe im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anwaltsgerichtliche-anschuldigung` | Anwaltsgerichtliche Anschuldigung im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `bea-passive-berufsausuebungsgesellschaft` | BEA Passive Berufsausuebungsgesellschaft im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `berufsrecht-anwaelte-kaltstart-routing` | Allgemeiner Kaltstart und Routing: vertiefter Berufsrechts-Skill für Anwälte; führt vom ersten Satz oder Dokument in den richtigen Arbeitsmodus, typische Rechtsprechungslinien nur nach Live-Verifikation, Kammerpraxis, Verteidigung und nä... |
| `berufsrecht-bag-zulassung-haftung` | BAG Zulassung Haftung im Berufsrecht der Anwälte: prüft konkret Berufsausübungsgesellschaft, Berufshaftpflicht, Berufspflichtverletzung, Beschwerdemanagement. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schr... |
| `berufsrechtliche-notfallkommunikation` | Berufsrechtliche Notfallkommunikation im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `beweisfuehrung-berufsverfahren` | Beweisfuehrung Berufsverfahren im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `beweisfuehrung-berufsverfahren-fremdgeld` | Beweisfuehrung Berufsverfahren Fremdgeld im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `datenraum-dokumentenintake-aktenlog` | Datenraum Dokumentenintake Aktenlog im Berufsrecht der Anwälte: prüft konkret Datenraum, Dokumentenintake und Aktenlog, Entscheidungsvorlage, Fachbezeichnung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schr... |
| `fachanwaltstitel-fortbildung-fremdgeld` | Fachanwaltstitel Fortbildung Fremdgeld im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `fortbildung-geldwaesche-kyc-homeoffice` | Fortbildung Geldwaesche KYC Homeoffice im Berufsrecht der Anwälte: prüft konkret Fortbildung, Geldwäsche und KYC, Homeoffice, Honorar. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `fremdgeld-anderkonto-gebuehrenunterschreitung` | Fremdgeld Anderkonto Gebuehrenunterschreitung im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `geldwaesche-risikoanalyse` | Geldwaesche Risikoanalyse im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `interessenkollision-mehrfachvertretung` | Interessenkollision Mehrfachvertretung im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `it-cloud-kammeraufsicht-ruege` | IT Cloud Kammeraufsicht Ruege im Berufsrecht der Anwälte: prüft konkret Cloud, KI und Outsourcing, Kammeraufsicht und Rüge, Kanzleiorganisation. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `kammeraufsicht-rechtsprechungscheck` | Kammeraufsicht Rechtsprechungscheck im Berufsrecht der Anwälte: prüft konkret Anwälte, Quellen- und Rechtsprechungscheck. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `ki-tool-legal-tech-mandatsgeheimnis` | KI Tool Legal Tech Mandatsgeheimnis im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `ki-tool-legal-tech-mandatskuendigung-unzeit` | KI Tool Legal Tech Mandatskuendigung Unzeit im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `mandanten-beteiligtenkommunikation` | Mandanten Beteiligtenkommunikation im Berufsrecht der Anwälte: prüft konkret Beteiligtenkommunikation, Mandatsannahme, Mandatsbeendigung, Mitarbeiter. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `notfallkommunikation-rak-beschwerde-berufsverfahren` | Notfallkommunikation RAK Beschwerde Berufsverfahren im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `protokoll-nachbereitung-rechnungseinzug-red` | Protokoll Nachbereitung Rechnungseinzug RED im Berufsrecht der Anwälte: prüft konkret Protokoll und Nachbereitung, Rechnungseinzug, Red-Team-Qualitygate, Remote Work. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächs... |
| `qualitaetsmanagement-vier` | Qualitaetsmanagement Vier im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `sanktionen-mandatsannahme-steuerliche` | Sanktionen Mandatsannahme Steuerliche im Berufsrecht der Anwälte: prüft konkret Anwälte, Aktenführung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `sozietaetswechsel-mandantenmitnahme` | Sozietaetswechsel Mandantenmitnahme im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `sozietaetswechsel-syndikus-terminsvertretung` | Sozietaetswechsel Syndikus Terminsvertretung im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `terminsvertreter-untervollmacht-umgehung` | Terminsvertreter Untervollmacht Umgehung im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `umgehung-gegenanwalts-unsachlichkeit` | Umgehung Gegenanwalts Unsachlichkeit im Berufsrecht der Anwälte: prüft konkret Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `vermerk-mustertext-sitzungs` | Vermerk Mustertext Sitzungs im Berufsrecht der Anwälte: prüft konkret Schriftsatz, Vermerk und Mustertext, Sitzungs- und Terminvorbereitung, Syndikus oder Inhouse. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem... |
| `verschwiegenheit-geheimnisschutz-werbung` | Verschwiegenheit Geheimnisschutz Werbung im Berufsrecht der Anwälte: prüft konkret Verschwiegenheit und Geheimnisschutz, Werbung und Außenauftritt, Zulassung, Bestellung und Register. Liefert priorisierten Output mit Norm-Pinpoints, Risi... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
