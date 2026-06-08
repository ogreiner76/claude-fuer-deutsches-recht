---
name: kaltstart-triage
description: "Einstieg, Schnelltriage und Workflow-Steuerung für das Arbeitszeugnis-Analyse-Plugin. Erkennt Zeugnisart, Ziel, Fristen, Rollen und Streitniveau, schlägt passende Fachmodule aus diesem Plugin vor und führt vom ersten Upload bis zu Mandantenbericht, Berichtigungsverlangen oder Klagestrategie."
---

## Wenn nur ein Zeugnis hochgeladen wird

Wenn der Nutzer nur ein PDF, Foto, Screenshot oder Textauszug hochlädt, beginne direkt. Keine generische Empfangsbestätigung, keine lange Intake-Liste.

**Erste Antwort:**

- **Erkannt:** Zeugnisart, Arbeitgeber, Arbeitnehmer, Zeitraum, Datum, Seitenumfang, soweit sichtbar.
- **Eilt:** Verjährung, Ausschlussfrist, laufende Bewerbung, Vergleichsfrist, bevorstehender Gerichtstermin oder `keine Eilfrist erkennbar`.
- **Erster Eindruck:** nicht als Endnote, sondern als Arbeitshypothese: freundlich-glatt, auffällig knapp, gemischt, streitig, lückenhaft, auffällig codiert.
- **Primärer Pfad:** ein passender Fachmodul aus diesem Plugin mit einem Satz, warum gerade dieser Skill jetzt trägt.
- **Nächster Schritt:** direkt weiterarbeiten oder genau eine konkrete Rückfrage stellen.

## Intake in 60 Sekunden

Frage nur, was den Weg ändert. Wenn die Information schon im Material steht, fasse sie zusammen und frage nicht erneut.

| Punkt | Frage |
|---|---|
| Rolle | Arbeitnehmer, Anwalt/Kanzlei, Betriebsrat, Arbeitgeber, Personalabteilung oder Rechtsabteilung? |
| Ziel | Nur verstehen, nachverhandeln, Arbeitgeber anschreiben, Klage prüfen, Vergleichstext bauen oder Schulungsfall analysieren? |
| Zeugnisart | Einfaches Zeugnis, qualifiziertes Endzeugnis, Zwischenzeugnis, Ausbildungszeugnis oder Entwurf? |
| Zeitpunkt | Wann ausgestellt, wann erhalten, gibt es Bewerbungs- oder Vergleichsdruck? |
| Kontext | Kündigung, Aufhebungsvertrag, Eigenkündigung, Elternzeit, Wechsel, Ruhestand, Streit oder gute Trennung? |
| Vergleichsmaterial | Vorzeugnis, Zwischenzeugnis, Beurteilungen, Zielvereinbarungen, Bonusunterlagen, E-Mails mit Lob, Vergleichstext? |

## Fünf Arbeitswege

Wähle einen dieser Wege und sage dem Nutzer, welchen Weg du nimmst.

1. **Schnellscan:** Für eine erste Einschätzung. Nutze `zeugnisart-erkennung`, `zeugnis-ueberblick-extraktion`, `zufriedenheitsformel-decodierung` und `schlussformel-bewertung`.
2. **Vollanalyse:** Für belastbare Mandatsarbeit. Nutze zusätzlich `notenrelevante-saetze-identifizieren`, `satzweise-notenmatrix`, `leistungsbeurteilung-analyse`, `verhaltensbeurteilung-analyse`, `steigerungsadverbien-katalog`, `bereichs-drift-detektor`, `widerspruechliche-bewertungen` und `gesamtnoten-aggregation`.
3. **Verhandlung:** Wenn ein besseres Zeugnis erreicht werden soll. Nutze `verbesserungsvorschlaege-formulieren`, `mandantenbericht-zeugnisanalyse` und danach `aufforderungsschreiben-arbeitgeber`.
4. **Klageprüfung:** Wenn der Arbeitgeber nicht korrigiert oder ein Vergleich gescheitert ist. Nutze `rechtliche-bewertung-bag-rechtsprechung` und `klage-strategie-zeugnisberichtigung`.
5. **Sonderfall:** Bei Führungskräften, Ausbildung oder branchentypischen Codes nutze früh `leitende-positionen-zeugnisse`, `azubi-zeugnis-analyse` oder `branchen-spezifische-formulierungen`.

## Routing nach Befund

| Befund | Nächster Skill | Warum |
|---|---|---|
| Zeugnisart oder Kopfdaten unklar | `zeugnisart-erkennung`, `zeugnis-ueberblick-extraktion` | Erst wissen, welches Dokument geprüft wird. |
| Hauptnote unklar | `zufriedenheitsformel-decodierung`, `satzweise-notenmatrix` | Die Kernformel allein reicht oft nicht. |
| Viele scheinbar gute Sätze, aber komisches Gefühl | `bereichs-drift-detektor`, `widerspruechliche-bewertungen` | Schaufenster-Sätze und Brüche im Gesamtbild erkennen. |
| Fehlendes Bedauern, knapper Dank, kalter Schluss | `schlussformel-bewertung` | Signalwirkung und rechtliche Durchsetzbarkeit getrennt bewerten. |
| Wörter wie "bemüht", "korrekt", "gesellig", "im Großen und Ganzen" | `rote-flaggen-katalog`, `negative-codeworte-katalog` | Kodierte Abwertung herausarbeiten. |
| Zeugnis einer Führungskraft | `leitende-positionen-zeugnisse` | Führung, Budget, Strategie und Loyalität gesondert prüfen. |
| Zeugnis soll verbessert werden | `verbesserungsvorschlaege-formulieren` | Konkrete Ersatzformulierungen bauen, aber nur soweit belegbar. |
| Arbeitgeber soll angeschrieben werden | `aufforderungsschreiben-arbeitgeber` | Beanstandungen in verwertbare Korrespondenz übersetzen. |
| Gerichtliche Durchsetzung steht im Raum | `rechtliche-bewertung-bag-rechtsprechung`, `klage-strategie-zeugnisberichtigung` | Beweislast, Antrag und Kostenrisiko sauber trennen. |

## Juristische Leitplanken

- **§ 109 GewO:** Anspruch auf einfaches oder qualifiziertes Zeugnis; bei qualifiziertem Zeugnis Angaben zu Leistung und Verhalten.
- **§ 16 BBiG:** Ausbildungszeugnis; auf Verlangen auch Angaben zu Verhalten und Leistung.
- **Wahrheit vor Wohlwollen:** Ein gutes Zeugnis darf nicht unwahr sein. Wohlwollen steuert die Ausdrucksweise, ersetzt aber keine Tatsachen.
- Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
- Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
- **Geheimcode:** Nicht jede unglückliche Formulierung ist automatisch ein unzulässiger Code. Prüfe den objektiven Empfängerhorizont und den Gesamtzusammenhang.
- **Keine Mathematik-Illusion:** Ampel, Note und Drift sind Arbeitsinstrumente. Die Ausgabe muss als begründete Spanne erscheinen, nicht als Scheingenauigkeit.

## Antwortformate

### Kurzscan

**Kurzbild**
- Zeugnisart:
- Erste Notentendenz:
- Kritische Stellen:
- Eilt wegen:

**Nächster sinnvoller Skill**
`skill-name` - kurzer Grund.

### Vollanalyse

**Arbeitsplan**
1. Kopfdaten und Zeugnisart sichern.
2. Notenrelevante Sätze markieren.
3. Leistung, Verhalten, Schluss und Auslassungen getrennt bewerten.
4. Drift und Widersprüche prüfen.
5. Gesamtnotenspanne bilden.
6. Handlungsoptionen und konkrete Ersatzformulierungen ausgeben.

**Fachmodule**
Nenne zwei bis fünf Skills, nicht die ganze Plugin-Liste. Zu jedem Skill: Input, Zweck, Output.

### Mandatsoutput

Wenn der Nutzer anwaltliche Weiterverarbeitung will, liefere:

- Zusammenfassung für Mandant oder Mandantin.
- Streitstellen mit Originalwortlaut und gewünschter Neufassung.
- Beweislast und Belegbedarf pro Streitstelle.
- Empfehlung: akzeptieren, nachverhandeln, auffordern, klagen oder Vergleich nutzen.

## Qualitätsgate

Vor jeder abschließenden Antwort prüfe:

- Sind Umlaute, ß, Namen, Daten und Zitate sauber übernommen?
- Ist die Zeugnisart korrekt bestimmt?
- Sind Schlussformel-Signal und Schlussformel-Anspruch getrennt?
- Ist die Beweislast richtig herum dargestellt?
- Gibt es keine erfundenen Fundstellen, Zeugnisinhalte oder Noten?
- Sind die vorgeschlagenen Skills wirklich aus diesem Plugin?
- Wirkt das Ergebnis wie eine verwendbare anwaltliche Arbeitsfassung und nicht wie ein Schema?

## Testakten nutzen

Für Schulung und Regression eignet sich die Arbeitsakte `arbeitszeugnis-analyse-bluehendes-leben`. Nutze sie nicht als vorgefertigte Lösung, sondern als lebendiges Material: erst lesen, dann Hypothese bilden, dann mit den Fachmodule absichern. Die Fälle sollen zeigen, dass Arbeitszeugnisse oft höflich aussehen und trotzdem in einzelnen Abschnitten hart abwerten.

