---
tags:
  - math
---
Created: 2023-12-19

# Statistiques I
En statistiques, $\sigma$ est noté:: $S$.
<!--SR:!2024-03-03,37,242-->

- $Q_{2}$ si $n$ est impair =:: $$\frac{x_{n+1}}{2}$$
<!--SR:!2024-02-02,16,210-->
- $Q_{2}$ si $n$ est pair =::$$\frac{x_{n/2}+x_{1+n/2}}{2}$$
<!--SR:!2024-02-04,16,210-->

## Données non groupées
- Le mode est:: la valeur qui a la fréquence la plus élevée
<!--SR:!2024-03-07,40,242-->
- La médiane est:: la valeur milieu
<!--SR:!2024-02-26,33,242-->
- $\mu=$::$$\frac{\sum\limits_{i=1}^{k}f_{i}x_{i}}{\sum\limits_{i=1}^{k}f_{i}}$$
<!--SR:!2024-02-03,14,202-->
- $\text{IQR}=$::$Q_{3}-Q_{1}$
<!--SR:!2024-02-29,35,242-->
- $S^{2}=$::$$\frac{\sum\limits_{i=1}^{k}f_{i}x_{i}^{2}}{\sum\limits_{i=1}^{k}f_{i}}-\mu^{2}$$
<!--SR:!2024-02-02,15,202-->
- $S=$::$$\sqrt{\frac{\sum\limits_{i=1}^{k}f_{i}x_{i}^{2}}{\sum\limits_{i=1}^{k}f_{i}}-\mu^{2}}$$
<!--SR:!2024-02-06,13,202-->

## Données groupées
- La classe modale est:: la classe dont la fréquence est la plus élevée. (Il s'agit uniquement d'intervalles de la classe de qualification)
<!--SR:!2024-02-20,23,202-->
- La médiane est la valeur milieu. La valeur exacte ne peut pas être calculée mais peut être estimée à l'aide d::'un graphique de fréquence cumulée.
<!--SR:!2024-02-18,22,202-->
- La moyenne exacte ne peut être calculée car:: on ne dispose pas des données de base.
<!--SR:!2024-02-15,26,242-->
- Pour les données groupées, $x_{i}$ est:: la valeur du milieu de l'intervalle (point médian) pour chaque classe.
<!--SR:!2024-02-07,19,222-->

## Transformations linéaires des données
- Si l'on ajoute ou soustrait une constante a à toutes les valeurs, la variance et l'écart-type:: restent les mêmes.
<!--SR:!2024-02-05,21,242-->
- $\text{E}(aX+b)=$::$a\text{E}(X)+b$
<!--SR:!2024-01-30,7,182-->
- $\text{Var}(aX+b)=$::$a^{2}\text{Var}(x)$
<!--SR:!2024-02-04,18,208-->
- $x$ est une valeur aberrante si:: $$x\notin [Q_{1}-1.5\times\text{IQR},\,Q_{3}+1.5\times\text{IQR}]$$
<!--SR:!2024-02-23,34,248-->

