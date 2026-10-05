<!-- ELUCENIA technical documentation · gleason-isup · de · no clinical/professional/rights approval -->

# Gleason und ISUP-Gradgruppe

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/gleason-isup)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Primäres Muster (größter Anteil)

`p`

- `3` — 3
- `4` — 4
- `5` — 5

### Sekundäres Muster

`s`

- `3` — 3
- `4` — 4
- `5` — 5

## Fassung der Methode

ISUP-Konsens 2014/Publikation 2016: 5 Gruppen, Unterscheidung 3+4/4+3

## Dokumentierte Formel

Gleason ≤ 6 = Gruppe 1 · 3 + 4 = 7 = Gruppe 2 · 4 + 3 = 7 = Gruppe 3 · 8 (4 + 4, 3 + 5, 5 + 3) = Gruppe 4 · 9–10 = Gruppe 5.

## Grenzen und Population

Die Umrechnung in ISUP-Gruppen setzt korrekt zugewiesene Gleason-Muster in der Prostatakarzinomhistologie voraus; 3+4 ist nicht gleich 4+3. Der Konsens 2014 empfiehlt keine Gleason-Graduierung intraduktalen Karzinoms ohne invasives Karzinom. Der Rechner bestimmt keine Muster und ersetzt keine histopathologische Beurteilung.

## Referenzen

- [Epstein JI et al. The 2014 International Society of Urological Pathology (ISUP) consensus conference on Gleason grading of prostatic carcinoma. Am J Surg Pathol, 2016.](https://doi.org/10.1097/PAS.0000000000000530)

- [Epstein JI et al. A contemporary prostate cancer grading system: a validated alternative to the Gleason score. Eur Urol, 2016.](https://doi.org/10.1016/j.eururo.2015.06.046)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
