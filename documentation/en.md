<!-- ELUCENIA technical documentation · gleason-isup · en · no clinical/professional/rights approval -->

# Gleason and ISUP Grade Group

[conditions, sources and permissions](https://elucenia.org/en/tools/gleason-isup)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Primary pattern (most extensive)

`p`

- `3` — 3
- `4` — 4
- `5` — 5

### Secondary pattern

`s`

- `3` — 3
- `4` — 4
- `5` — 5

## Method edition

ISUP consensus 2014/publication 2016: 5 groups, 3+4/4+3 distinction

## Documented formula

Gleason ≤ 6 = group 1 · 3 + 4 = 7 = group 2 · 4 + 3 = 7 = group 3 · 8 (4 + 4, 3 + 5, 5 + 3) = group 4 · 9–10 = group 5.

## Limits and population

Conversion into ISUP grade groups assumes correctly assigned Gleason patterns in prostate cancer histology; 3+4 is not equivalent to 4+3. The 2014 consensus does not recommend Gleason grading of intraductal carcinoma without invasive carcinoma. The calculator does not determine the patterns or replace pathological assessment.

## References

- [Epstein JI et al. The 2014 International Society of Urological Pathology (ISUP) consensus conference on Gleason grading of prostatic carcinoma. Am J Surg Pathol, 2016.](https://doi.org/10.1097/PAS.0000000000000530)

- [Epstein JI et al. A contemporary prostate cancer grading system: a validated alternative to the Gleason score. Eur Urol, 2016.](https://doi.org/10.1016/j.eururo.2015.06.046)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Gleason 3 + 3 = 6: grade group 1

| Result details | |
| --- | --- |
| 5-year biochemical recurrence-free survival after prostatectomy | 96% |


### 2

Gleason 3 + 4 = 7: grade group 2

| Result details | |
| --- | --- |
| 5-year biochemical recurrence-free survival after prostatectomy | 88% |


### 3

Gleason 4 + 3 = 7: grade group 3

| Result details | |
| --- | --- |
| 5-year biochemical recurrence-free survival after prostatectomy | 63% |


### 4

Gleason 3 + 5 = 8: grade group 4

| Result details | |
| --- | --- |
| 5-year biochemical recurrence-free survival after prostatectomy | 48% |


### 5

Gleason 5 + 4 = 9: grade group 5

| Result details | |
| --- | --- |
| 5-year biochemical recurrence-free survival after prostatectomy | 26% |

