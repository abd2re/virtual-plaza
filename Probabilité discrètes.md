---
tags:
  - math
---
Created: 2023-09-23

# Probabilité discrètes
## Experience aléatoire-événements
Une expérience aléatoire est une expérience dont l'issue dépend du:: hasard.
<!--SR:!2024-03-31,130,290-->
L'ensemble des résultats possibles d'une expérience aléatoire est appelé:: univers.
<!--SR:!2023-12-23,57,250-->
On appelle événement:: toute partie de l'univers (sous-ensemble)
<!--SR:!2023-12-11,33,210-->

### Définitions
- Evénement élémentaire:: a une seule issue
<!--SR:!2024-01-03,63,250-->
- Evénement composé:: a plusieurs issues
<!--SR:!2024-02-27,102,270-->
- Evénement A et B (conjonction d'événement):: événement constitué des issues communes aux deux événements
<!--SR:!2024-01-09,69,250-->
- Evénement contraire a A noté A':: événement dont les issues n'appartiennent pas a A
<!--SR:!2023-12-31,63,250-->
- Evénement A ou B (disjonction d'événement):: événement constitué de toutes les issues des deux événements
<!--SR:!2023-12-13,52,250-->
- Evénement incompatible (mutuellement exclusif):: conjonction des deux événements avec aucune issue
<!--SR:!2024-01-12,70,250-->
- Evénement certain:: toutes les issues
<!--SR:!2024-03-26,112,250-->
- Evénement impossible:: aucune issue
<!--SR:!2024-02-11,91,270-->

## Calcul de probabilité
- La probabilité d'un événement est la somme:: des éléments élémentaires qui le compose.
<!--SR:!2023-12-24,36,230-->
- Lorsque les événements élémentaires ont meme probabilité, on dit qu'il y a:: équiprobabilité ou équi-répartition.
<!--SR:!2023-12-21,56,250-->

### Propriété
- $\frac{n(X)}{n(U)}$=::$P(X)$
<!--SR:!2024-01-30,56,250-->
- $P(U)$=::1 
<!--SR:!2023-12-20,56,250-->
- $P(0)$=::0
<!--SR:!2024-03-01,104,270-->
- $P(A)+P(A')$=::1 
<!--SR:!2023-12-24,57,250-->
- $P(A\cup B)$ (2)=::$P(A)+P(B)-P(A\cap B)=P(A\cap B')+P(A\cap B)+P(A'\cap B)$
<!--SR:!2023-12-13,18,210-->
- $P(A\Delta B)$=::$P(A\cap B')\cup P(A'\cap B)$
<!--SR:!2024-02-04,59,250-->

## Événements indépendants
Deux événements sont indépendants si: : l'occurrence de chacun d'eux n'affecte pas la probabilité que l'autre se produise. Un exemple de ceci est l'échantillonnage à 1s avec remplacement.

Pour des événements indépendants A et B, $P(A\cap B)$=:: $P(A)P(B)$
<!--SR:!2024-01-12,65,252-->

## Événements dépendants
Deux événements sont dépendants si:: la survenance de l'un d'entre eux affecte la probabilité que l'autre se produise. L'échantillonnage sans remplacement en est un exemple.
<!--SR:!2024-01-17,69,252-->

Pour les événements dépendants A et B, $P(A\cap B)$=::$P(A)\times P(B/A)$
<!--SR:!2024-03-01,89,232-->

## Probabilité conditionnelle
Pour deux événements A et B, $A/B$ représente l'événement "A sachant B", et $P(A/B)$=::$\frac{P(A\cap B)}{P(B)}$
<!--SR:!2024-01-11,66,252-->

Pour des événements indépendants, $P(A)$=::$P(A/B)=P(A/B')$
<!--SR:!2024-01-09,63,252-->

Axiom des probabilités totales, pour événement secondaire : $P(B)$=::$P(A\cap B)+P(A'\cap B)$
<!--SR:!2024-01-04,60,252-->

$P(A\cap B')$=::$P(A)-P(A\cap B)$
<!--SR:!2024-01-28,66,231-->

