<!-- ELUCENIA technical documentation · gleason-isup · pt-BR · no clinical/professional/rights approval -->

# Gleason e grupo de grau ISUP

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/gleason-isup)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Padrão primário (mais extenso)

`p`

- `3` — 3
- `4` — 4
- `5` — 5

### Padrão secundário

`s`

- `3` — 3
- `4` — 4
- `5` — 5

## Edição do método

ISUPconsenso 2014/publicação 2016:5 grupos, distinção 3+4/4+3

## Fórmula documentada

Gleason ≤ 6 = grupo 1 · 3 + 4 = 7 = grupo 2 · 4 + 3 = 7 = grupo 3 · 8 (4 + 4, 3 + 5, 5 + 3) = grupo 4 · 9 a 10 = grupo 5.

## Limites e população

A conversão em grupos ISUP pressupõe padrões Gleason corretamente atribuídos na histologia de câncer de próstata; 3+4 não equivale a 4+3. O consenso 2014 não recomenda graduar pelo Gleason o carcinoma intraductal sem carcinoma invasivo. A calculadora não determina os padrões nem substitui avaliação anatomopatológica.

## Referências

- [Epstein JI et al. The 2014 International Society of Urological Pathology (ISUP) consensus conference on Gleason grading of prostatic carcinoma. Am J Surg Pathol, 2016.](https://doi.org/10.1097/PAS.0000000000000530)

- [Epstein JI et al. A contemporary prostate cancer grading system: a validated alternative to the Gleason score. Eur Urol, 2016.](https://doi.org/10.1016/j.eururo.2015.06.046)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Gleason 3 + 3 = 6: grupo de grau 1

| Detalhes do resultado | |
| --- | --- |
| Sobrevida livre de recidiva bioquímica em 5 anos após prostatectomia | 96% |


### 2

Gleason 3 + 4 = 7: grupo de grau 2

| Detalhes do resultado | |
| --- | --- |
| Sobrevida livre de recidiva bioquímica em 5 anos após prostatectomia | 88% |


### 3

Gleason 4 + 3 = 7: grupo de grau 3

| Detalhes do resultado | |
| --- | --- |
| Sobrevida livre de recidiva bioquímica em 5 anos após prostatectomia | 63% |


### 4

Gleason 3 + 5 = 8: grupo de grau 4

| Detalhes do resultado | |
| --- | --- |
| Sobrevida livre de recidiva bioquímica em 5 anos após prostatectomia | 48% |


### 5

Gleason 5 + 4 = 9: grupo de grau 5

| Detalhes do resultado | |
| --- | --- |
| Sobrevida livre de recidiva bioquímica em 5 anos após prostatectomia | 26% |

