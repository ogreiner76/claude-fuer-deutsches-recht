---
name: ki-richtlinie-kanzleien-unterlagen-luecken
description: "Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Ki Richtlinie Kanzleien** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `anonymisierung-pseudonymisierung-automatisierte-entscheidungen` — Anonymisierung Pseudonymisierung Automatisierte Entscheidungen
- `anwaelten-berufsrechtskonforme-beruht` — Anwaelten Berufsrechtskonforme Beruht
- `bias-diskriminierung-regelsatz-erstellen-dienstleister-due` — Bias Diskriminierung Regelsatz Erstellen Dienstleister Due
- `bora-brak-dsgvo` — Bora Brak Dsgvo
- `dokumentationspflichten-protokoll-dsgvo-executive-summary` — Dokumentationspflichten Protokoll Dsgvo Executive Summary
- `geschgehg-halluzinations-handhabung-kanzlei-kontext` — Geschgehg Halluzinations Handhabung Kanzlei Kontext
- `hinweisen-kanzleien-pflegt` — Hinweisen Kanzleien Pflegt
- `kennzeichnungspflichten-veroeffentlichungen-ki-kompetenz-vo` — Kennzeichnungspflichten Veroeffentlichungen Ki Kompetenz Vo
- `kirk-leitfaden-kirk-prompts-kr-executive` — Kirk Leitfaden Kirk Prompts Kr Executive
- `literatur-quellen-prompting-leitfaden-rdg-chatbot` — Literatur Quellen Prompting Leitfaden Rdg Chatbot
- `nutzungsrichtlinie-auftragsverarbeitungsvertrag-musterklauseln` — Nutzungsrichtlinie Auftragsverarbeitungsvertrag Musterklauseln
- `rechtsabteilungen-syndikus-verordnung-interessen` — Rechtsabteilungen Syndikus Verordnung Interessen
- `richtlinien-skelett-richtlinien-update-schatten-aufdeckung` — Richtlinien Skelett Richtlinien Update Schatten Aufdeckung

## Arbeitsweg

- **Fehlende Tatsache vs. fehlender Beleg.** Bei KI-Richtlinie für Kanzleien oft fehlend: KI-Richtlinie intern, AVV-Mustertext, Mandantenhinweis.
- **Pro Lücke.** Beweisthema, Beweismittel (Tool-Bewertung, AVV-Dokumentation), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: erste Frist.
- **Beschaffung extern.** RAK (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat KI-Richtlinie für Kanzleien typischerweise KI-Richtlinie intern, AVV-Mustertext zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
