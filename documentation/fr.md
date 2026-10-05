<!-- ELUCENIA technical documentation · gleason-isup · fr · no clinical/professional/rights approval -->

# Gleason et groupe de grade ISUP

[conditions, sources et autorisations](https://elucenia.org/fr/outils/gleason-isup)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Grade principal (le plus étendu)

`p`

- `3` — 3
- `4` — 4
- `5` — 5

### Grade secondaire

`s`

- `3` — 3
- `4` — 4
- `5` — 5

## Édition de la méthode

Consensus ISUP 2014/publication 2016 : 5 groupes, distinction 3+4/4+3

## Formule documentée

Gleason ≤ 6 = groupe 1 · 3 + 4 = 7 = groupe 2 · 4 + 3 = 7 = groupe 3 · 8 (4 + 4, 3 + 5, 5 + 3) = groupe 4 · 9–10 = groupe 5.

## Limites et population

La conversion en groupes ISUP suppose que les architectures de Gleason aient été correctement attribuées en histologie du cancer de la prostate ; 3+4 n’équivaut pas à 4+3. Le consensus 2014 ne recommande pas de grader selon Gleason un carcinome intracanalaire sans carcinome invasif. Le calculateur ne détermine pas les architectures et ne remplace pas l’évaluation anatomopathologique.

## Références

- [Epstein JI et al. The 2014 International Society of Urological Pathology (ISUP) consensus conference on Gleason grading of prostatic carcinoma. Am J Surg Pathol, 2016.](https://doi.org/10.1097/PAS.0000000000000530)

- [Epstein JI et al. A contemporary prostate cancer grading system: a validated alternative to the Gleason score. Eur Urol, 2016.](https://doi.org/10.1016/j.eururo.2015.06.046)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
