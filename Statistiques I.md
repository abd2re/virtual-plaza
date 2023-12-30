---
tags:
  - math
---
Created: 2023-12-19

# Statistiques I
En statistiques, $\sigma$ est noté:: $S$.

- $Q_{2}$ si $n$ est impair =:: $$\frac{x_{n+1}}{2}$$
<!--SR:!2023-12-31,8,250-->
- $Q_{2}$ si $n$ est pair =::$$\frac{x_{n/2}+x_{1+n/2}}{2}$$
<!--SR:!2023-12-30,5,230-->

## Données non groupées
- Le mode est:: la valeur qui a la fréquence la plus élevée
- La médiane est:: la valeur milieu
- $\mu=$::$$\frac{\sum\limits_{i=1}^{k}f_{i}x_{i}}{\sum\limits_{i=1}^{k}f_{i}}$$
- $\text{IQR}=$::$Q_{3}-Q_{1}$
- $S^{2}=$::$$\frac{\sum\limits_{i=1}^{k}f_{i}x_{i}^{2}}{\sum\limits_{i=1}^{k}f_{i}}-\mu^{2}$$
- $S=$::$$\sqrt{\frac{\sum\limits_{i=1}^{k}f_{i}x_{i}^{2}}{\sum\limits_{i=1}^{k}f_{i}}-\mu^{2}}$$

## Données groupées
- La classe modale est:: la classe dont la fréquence est la plus élevée. (Il s'agit uniquement d'intervalles de la classe de qualification)
- La médiane est la valeur milieu. La valeur exacte ne peut pas être calculée mais peut être estimée à l'aide d::'un graphique de fréquence cumulée.
- La moyenne exacte ne peut être calculée car:: on ne dispose pas des données de base.
- Pour les données groupées, $x_{i}$ est:: la valeur du milieu de l'intervalle (point médian) pour chaque classe.

## Transformations linéaires des données
- Si l'on ajoute ou soustrait une constante a à toutes les valeurs, la variance et l'écart-type:: restent les mêmes.
- $\text{E}(aX+b)=$::$a\text{E}(X)+b$
- $\text{Var}(aX+b)=$::$a^{2}\text{Var}(x)$
- $x$ est une valeur aberrante si:: $$x\notin [Q_{1}-1.5\times\text{IQR},\,Q_{3}+1.5\times\text{IQR}]$$
<!--SR:!2023-12-31,2,248-->

