---
name: ki-richtlinie-kanzleien-quellen-livecheck
description: "Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert."
---

# Rechtsquellen-Livecheck

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

- **Tragende Normen amtlich.** Bei KI-Richtlinie für Kanzleien: BRAO § 43e, BORA, DSGVO Art. 28 — gesetze-im-internet, Eur-Lex oder amtliche Datenbank.
- **Behördenpraxis.** RAK (Bescheide, Auslegungserlasse, FAQ); Stand-Datum prüfen.
- **Rechtsprechung.** Gericht, Entscheidungsform, Datum, Az, Rn, frei prüfbare Fundstelle. Keine BeckRS-/juris-Blindzitate aus Modellwissen.
- **Kommentare/Literatur** nur mit Nutzerquelle oder lizenziertem Live-Zugriff; alte Auflage explizit markieren.
- **Quellenstand und Unsicherheit** im Output sichtbar machen — keine Scheinpräzision.

## Output

Quellenkarte mit Primärnormen, Rechtsprechungssuche (Gericht/Datum/Az/Rn), Behördenstand und Zitierform nach `references/zitierweise.md`.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
