<!-- ELUCENIA technical documentation · gleason-isup · es · no clinical/professional/rights approval -->

# Gleason y grupo de grado ISUP

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/gleason-isup)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Patrón primario (más extenso)

`p`

- `3` — 3
- `4` — 4
- `5` — 5

### Patrón secundario

`s`

- `3` — 3
- `4` — 4
- `5` — 5

## Edición del método

Consenso ISUP 2014/publicación 2016: 5 grupos, distinción 3+4/4+3

## Fórmula documentada

Gleason ≤ 6 = grupo 1 · 3 + 4 = 7 = grupo 2 · 4 + 3 = 7 = grupo 3 · 8 (4 + 4, 3 + 5, 5 + 3) = grupo 4 · 9–10 = grupo 5.

## Límites y población

La conversión a grupos ISUP presupone patrones Gleason correctamente asignados en la histología del cáncer de próstata; 3+4 no equivale a 4+3. El consenso 2014 no recomienda graduar mediante Gleason el carcinoma intraductal sin carcinoma invasivo. La calculadora no determina los patrones ni sustituye la evaluación anatomopatológica.

## Referencias

- [Epstein JI et al. The 2014 International Society of Urological Pathology (ISUP) consensus conference on Gleason grading of prostatic carcinoma. Am J Surg Pathol, 2016.](https://doi.org/10.1097/PAS.0000000000000530)

- [Epstein JI et al. A contemporary prostate cancer grading system: a validated alternative to the Gleason score. Eur Urol, 2016.](https://doi.org/10.1016/j.eururo.2015.06.046)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
