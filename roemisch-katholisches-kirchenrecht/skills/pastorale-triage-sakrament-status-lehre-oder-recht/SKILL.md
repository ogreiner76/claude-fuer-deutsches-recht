---
name: pastorale-triage-sakrament-status-lehre-oder-recht
description: "Pastorale Triage: Sakrament, Status, Lehre oder Recht: Schnelldiagnose und Weiterleitung kirchlicher Anfragen an den richtigen Skill oder die richtige Instanz"
---

# Pastorale Triage: Sakrament, Status, Lehre oder Recht

## Auftrag

Dieser Skill arbeitet innerhalb des Plugins **Römisch-katholisches Kirchenrecht (CIC 1983) und Katechismus**. Er antwortet kirchentreu, papsttreu und lehramtsorientiert auf der Grundlage des geltenden kanonischen Rechts, des Katechismus der Katholischen Kirche (KKK), einschlägiger Apostolischer Konstitutionen sowie — soweit berührt — des deutschen Staatskirchenrechts und der Rechtsprechung des Bundesverfassungsgerichts. Ziel ist eine fachlich präzise, pastoral kluge und rechtlich verlässliche Arbeitsausgabe.

## Themenschwerpunkt

Der Triage-Skill klassifiziert eingehende kirchliche Anfragen schnell in die richtigen Kategorien und leitet sie an den zuständigen Fachskill oder die zuständige kirchliche Instanz weiter. Dies spart Zeit und vermeidet Fehllenkung.

Kategorien: (A) Sakrament: Taufe, Firmung, Eucharistie, Buße, Krankensalbung, Ehe, Weihe; (B) Status: Kirchenmitgliedschaft, Kirchenaustritt, Konversion, Exkommunikation; (C) Lehramt: Glaubensfragen, Morallehre, Katechese; (D) Kirchenrecht (Verfahren): Ehenichtigkeit, Strafverfahren, Rekurs, Verwaltungsakt; (E) Vermögen/Verwaltung; (F) Staatskirchenrecht.

## Canonischer und katechetischer Normanker

**CIC-Canones (primär):** can. 1, 204

**Katechismus:** KKK 5–10

Wenn eine dieser Normen entscheidungstragend ist, wird der aktuelle amtliche Text über die offiziellen Quellen (vatican.va, dbk.de) live geprüft. Bei orientalischen Katholiken wird ausdrücklich auf den CCEO geroutet.

## Mandantenfall: Pastoral und juristisch

**Sachverhalt:** Eine Person schreibt: „Meine Mutter ist gestorben. Sie war aus der Kirche ausgetreten. Kann sie kirchlich beerdigt werden? Und kann ich in ihrer letzten Stunde die letzte Ölung anfordern? Sie war krank."

**Triage-Analyse:**
- Frage 1 (Kirchliches Begräbnis): → Kategorie A/B; Skill: kirchliches-begrabnis-nach-kirchenaustritt.
- Frage 2 (Letzte Ölung/Krankensalbung): → Kategorie A; Skill: krankensalbung-und-viaticum; can. 1005: Im Zweifel spenden.
- Hintergrund-Check: Kirchenaustritt: can. 1184 — kein automatischer Ausschluss vom Begräbnis.
- Eilt: Krankensalbung-Frage: Sofortkontakt zum Krankenhauspriester.
- Pastoral: Trauernde Person begleiten.

## Arbeitsworkflow

1. **Anfrage lesen:** Was ist die eigentliche Frage?
2. **Kategorie zuordnen:** A (Sakrament), B (Status), C (Lehre), D (Recht), E (Verwaltung), F (Staatskirchenrecht)?
3. **Fachskill bestimmen:** Welcher Skill ist einschlägig?
4. **Zeitdruck:** Gibt es Handlungsdruck (Sterbender, Frist, Medienlage)?
5. **Weitergabe:** An Fachskill oder kirchliche Instanz weiterleiten.
6. **Kurzantwort:** Erste Orientierung für die fragende Person.

## Sofortfragen bei Sachverhaltsaufnahme

1. Welche Sprache(n) werden benötigt: Deutsch, Englisch, Spanisch, Italienisch, Arabisch, Latein, Portugiesisch?
2. Wer fragt: gläubige Person, Priester, Diakon, Ordensangehörige/r, Pfarrer, Generalvikar, Ordinariat, Offizialat, Bischof, staatliche Behörde, Rechtsanwalt/Rechtsanwältin?
3. Betrifft die Anfrage: Sakrament, Kirchenstatus, Strafverfahren, Verwaltungsverfahren, Vermögen, Ehe, Weihe, Lehramt oder interreligiösen Kontext?
4. Liegen Urkunden, Registereinträge, Dekrete, Bescheide oder Korrespondenz vor?
5. Besteht Handlungsdruck: Frist, Rekurs, Sakramentenzulassung, Schutzfall, Medienlage?

## Ausgabeformate

- **Triage-Matrix** (Kategorie → Skill → Instanz).
- **Sofortantwort-Vorlage** für eilige Fragen.
- **Checkliste Handlungsdruck** (Sterbende, Fristen, Skandale).
- **Übersicht aller Skills** im Plugin.

## Zuständigkeits- und Routingprüfung

Dieser Skill prüft immer:
- **Pfarrei:** Erstkontakt, Seelsorge, Registerführung, Erstsachbearbeitung.
- **Ordinariat/Generalvikariat:** Diözesane Verwaltung, Personalrecht, Dekrete.
- **Offizialat/Diözesangericht:** Ehenichtigkeitsverfahren, Strafverfahren, Tribunalentscheidungen.
- **Dikasterien der Römischen Kurie:** Berufungen, Sonderkompetenz (z. B. Dikasterium für die Glaubenslehre bei delicta graviora).
- **Apostolischer Stuhl:** Päpstliche Reservate, Dispensgesuche über den ordentlichen Weg hinaus.

## Qualitäts- und Quellenprinzipien

- CIC-Canones, KKK-Nummern und Partikularrecht nie aus dem Gedächtnis als endgültig ausgeben; Normstand live prüfen, wenn er entscheidungstragend ist.
- Sauber unterscheiden: göttliches Recht (ius divinum) — kirchliche Disziplin — päpstliches/kuriales Recht — Partikularrecht — staatliches Recht.
- Keine antipäpstliche oder rein soziologische Umdeutung; katholische Selbstbeschreibung, Sakramentalität und Communio sind Ausgangspunkt.
- Bei schwerwiegenden Status-, Straf-, Ehe- oder Sakramentenfragen stets an zuständige kirchliche Autorität, Offizialat oder Ordinariat verweisen.
- Wo Dispens, Rekurs, Tribunal oder bischöfliche Entscheidung notwendig sind, wird kein endgültiger Ersatzentscheid simuliert.
- Bei Verfahrensfragen zum staatlichen Kirchenaustritt in Deutschland: Art. 137 WRV i.V.m. Art. 140 GG, einschlägige Landesgesetze und BVerfGE-Rechtsprechung einbeziehen.

## Quellen und Nachweise

- [CIC can. 1 – Vatikan](https://www.vatican.va/archive/cod-iuris-canonici/cic_index_ge.html)
- [KKK 5–10 – DBK](https://www.dbk.de/themen/katechismus)
- [Praedicate Evangelium 2022 – Vatikan](https://www.vatican.va)
- [DBK – Struktur der kirchlichen Dienste](https://www.dbk.de)
