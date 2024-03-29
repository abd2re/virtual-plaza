---
tags:
  - math
---
Created: 2023-12-19

# Statistiques I
En statistiques, $\sigma$ est noté:: $S$.
<!--SR:!2024-05-31,89,242-->

- $Q_{2}$ si $n$ est impair =:: $$\frac{x_{n+1}}{2}$$
<!--SR:!2024-04-03,33,190-->
- $Q_{2}$ si $n$ est pair =::$$\frac{x_{n/2}+x_{1+n/2}}{2}$$
<!--SR:!2024-05-21,72,210-->

## Données non groupées
- Le mode est:: la valeur qui a la fréquence la plus élevée
<!--SR:!2024-06-11,96,242-->
- La médiane est:: la valeur milieu
<!--SR:!2024-05-15,79,242-->
- $\mu=$::$$\frac{\sum\limits_{i=1}^{k}f_{i}x_{i}}{\sum\limits_{i=1}^{k}f_{i}}$$
<!--SR:!2024-04-23,53,202-->
- $\text{IQR}=$::$Q_{3}-Q_{1}$
<!--SR:!2024-05-23,84,242-->
- $S^{2}=$::$$\frac{\sum\limits_{i=1}^{k}f_{i}x_{i}^{2}}{\sum\limits_{i=1}^{k}f_{i}}-\mu^{2}$$
<!--SR:!2024-05-11,66,202-->
- $S=$::$$\sqrt{\frac{\sum\limits_{i=1}^{k}f_{i}x_{i}^{2}}{\sum\limits_{i=1}^{k}f_{i}}-\mu^{2}}$$
<!--SR:!2024-04-21,50,202-->

## Données groupées
- La classe modale est:: la classe dont la fréquence est la plus élevée. (Il s'agit uniquement d'intervalles de la classe de qualification)
<!--SR:!2024-03-27,23,182-->
- La médiane est la valeur milieu. La valeur exacte ne peut pas être calculée mais peut être estimée à l'aide d::'un graphique de fréquence cumulée.
<!--SR:!2024-04-03,45,202-->
- La moyenne exacte ne peut être calculée car:: on ne dispose pas des données de base.
<!--SR:!2024-04-19,64,242-->
- Pour les données groupées, $x_{i}$ est:: la valeur du milieu de l'intervalle (point médian) pour chaque classe.
<!--SR:!2024-03-19,41,222-->

## Transformations linéaires des données
- Si l'on ajoute ou soustrait une constante a à toutes les valeurs, la variance et l'écart-type:: restent les mêmes.
<!--SR:!2024-03-26,50,242-->
- $\text{E}(aX+b)=$::$a\text{E}(X)+b$
<!--SR:!2024-04-11,37,182-->
- $\text{Var}(aX+b)=$::$a^{2}\text{Var}(x)$
<!--SR:!2024-03-29,29,188-->
- $x$ est une valeur aberrante si:: $$x\notin [Q_{1}-1.5\times\text{IQR},\,Q_{3}+1.5\times\text{IQR}]$$
<!--SR:!2024-05-16,83,248-->

