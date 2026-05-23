---
name: zirkelschluss-pruefen
description: "Pruefung auf Zirkelschluesse und kreisfreie Verweisketten im legistischen Entwurf. Eine Norm darf nicht ueber Umwege auf sich selbst verweisen. Auch indirekte Zirkel vermeiden A verweist B B verweist C C verweist A. Pruefung tautologischer Definitionen Vermutung der Vermutung. Pruefung Reichweite dynamischer Verweisungen auf EU-Recht. Pruefung statischer Verweisungen Datum der Fassung. Erstellt Verweisgraf und markiert problematische Kanten. Endet mit Liste der zu entzerrenden Stellen."
---

# Zirkelschluss pruefen

> Recht muss eindeutig sein. Wer im Kreis verweist, schafft Unbestimmtheit.

## Klassische Fallgruppen

### A - Direkter Zirkel
Paragraf 5 definiert X als das, was Paragraf 12 sagt - und Paragraf 12 definiert X als das, was Paragraf 5 sagt.

### B - Indirekter Zirkel
A -> B -> C -> A. Bei mehreren Stationen schwerer zu finden.

### C - Tautologische Definition
"Pflichtpostfach ist ein Postfach, das gemaess diesem Gesetz zur Pflicht gemacht wird." - leer.

### D - Vermutung der Vermutung
"Es wird vermutet, dass die Sache abgesandt ist, wenn die Vermutung der Abgabe besteht." - unzulaessig.

### E - Dynamische Verweisung auf eigene Norm
Eine Norm verweist auf "die jeweils gueltige Fassung" eines anderen Paragrafen derselben Norm - Vorsicht, das ist meist gewollt, kann aber zum verfassungsrechtlichen Problem werden (Bestimmtheitsgebot bei Strafnormen, Art. 103 Abs. 2 GG).

## Pruefverfahren

### Schritt 1 - Verweisgraf aufbauen

Alle Verweise im Entwurf erfassen: "Quelle-Paragraf X verweist auf Ziel-Paragraf Y". Tabellarisch oder als Mermaid-Graf.

### Schritt 2 - Schleifen detektieren

Algorithmisch (Tarjan / Kosaraju) oder per Hand bei kleinen Entwuerfen: gibt es eine Verweis-Kette, die zur Ausgangsnorm zurueckkehrt?

### Schritt 3 - Dynamik pruefen

Jeden Verweis klassifizieren:
- statisch (mit Datum: "Paragraf 15 in der Fassung vom 01.01.2025")
- dynamisch (ohne Datum: "Paragraf 15")
- gleitend auf EU-Recht (z.B. "Anhang I der RL 2020/2184")

Bei dynamischen Verweisen auf EU-Recht: Demokratieprinzip pruefen. Der nationale Gesetzgeber kann nicht beliebig auf jedes spaetere EU-Recht verweisen.

## Pruefliste fuer den Entwurf

- [ ] Alle Legaldefinitionen sind selbsterklaerend (keine Verweisung auf nicht definierte Begriffe)
- [ ] Keine Schleife im Verweisgraf
- [ ] Dynamische Verweise auf eigene Norm sind gewollt und klar
- [ ] Dynamische Verweise auf EU-Recht halten dem Demokratieprinzip stand

## Ausgabe

Verweisgraf, Liste detektierter Schleifen, Vorschlaege zur Entzerrung.

## Anschluss

`referentenentwurf-bauen`, dann `begruendung-allgemein-und-besonders`.
