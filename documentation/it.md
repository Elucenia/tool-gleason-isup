<!-- ELUCENIA technical documentation · gleason-isup · it · no clinical/professional/rights approval -->

# Gleason e gruppo di grado ISUP

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/gleason-isup)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Pattern primario (più esteso)

`p`

- `3` — 3
- `4` — 4
- `5` — 5

### Pattern secondario

`s`

- `3` — 3
- `4` — 4
- `5` — 5

## Edizione del metodo

Consenso ISUP 2014/pubblicazione 2016: 5 gruppi, distinzione 3+4/4+3

## Formula documentata

Gleason ≤ 6 = gruppo 1 · 3 + 4 = 7 = gruppo 2 · 4 + 3 = 7 = gruppo 3 · 8 (4 + 4, 3 + 5, 5 + 3) = gruppo 4 · 9–10 = gruppo 5.

## Limiti e popolazione

La conversione nei gruppi ISUP presuppone pattern di Gleason correttamente assegnati nell’istologia del carcinoma prostatico; 3+4 non equivale a 4+3. Il consenso 2014 non raccomanda la graduazione secondo Gleason del carcinoma intraduttale senza carcinoma invasivo. Il calcolatore non determina i pattern e non sostituisce la valutazione anatomopatologica.

## Riferimenti

- [Epstein JI et al. The 2014 International Society of Urological Pathology (ISUP) consensus conference on Gleason grading of prostatic carcinoma. Am J Surg Pathol, 2016.](https://doi.org/10.1097/PAS.0000000000000530)

- [Epstein JI et al. A contemporary prostate cancer grading system: a validated alternative to the Gleason score. Eur Urol, 2016.](https://doi.org/10.1016/j.eururo.2015.06.046)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
