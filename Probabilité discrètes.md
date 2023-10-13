---
tags:
  - math
---
Created: 2023-09-23

# Probabilité discrètes
## Experience aléatoire-événements
Une expérience aléatoire est une expérience dont l'issue dépend du:: hasard.
<!--SR:!2023-11-22,45,290-->
L'ensemble des résultats possibles d'une expérience aléatoire est appelé:: univers.
<!--SR:!2023-10-27,22,250-->
On appelle événement:: toute partie de l'univers (sous-ensemble)
<!--SR:!2023-10-16,14,230-->

### Définitions
- Evénement élémentaire:: a une seule issue
<!--SR:!2023-10-31,25,250-->
- Evénement composé:: a plusieurs issues
<!--SR:!2023-11-17,38,270-->
- Evénement A et B (conjonction d'événement):: événement constitué des issues communes aux deux événements
<!--SR:!2023-11-01,26,250-->
- Evénement contraire a A noté A':: événement dont les issues n'appartiennent pas a A
<!--SR:!2023-10-29,24,250-->
- Evénement A ou B (disjonction d'événement):: événement constitué de toutes les issues des deux événements
<!--SR:!2023-10-22,19,250-->
- Evénement incompatible (mutuellement exclusif):: conjonction des deux événements avec aucune issue
<!--SR:!2023-11-03,28,250-->
- Evénement certain:: toutes les issues
<!--SR:!2023-10-21,18,250-->
- Evénement impossible:: aucune issue
<!--SR:!2023-11-12,34,270-->

## Calcul de probabilité
- La probabilité d'un événement est la somme:: des éléments élémentaires qui le compose.
<!--SR:!2023-11-02,27,250-->
- Lorsque les événements élémentaires ont meme probabilité, on dit qu'il y a:: équiprobabilité ou équi-répartition.
<!--SR:!2023-10-26,22,250-->

### Propriété
- $P(U)$=::1 
<!--SR:!2023-10-25,21,250-->
- $P(0)$=::0
<!--SR:!2023-11-18,39,270-->
- $P(A)+P(A')$=::1 
<!--SR:!2023-10-28,23,250-->
- $P(A\cup B)$ (2)=::$P(A)+P(B)-P(A\cap B)=P(A\cup B')+P(A\cup B)+P(A'\cup B)$
<!--SR:!2023-10-18,16,230-->

## Événements indépendants
Deux événements sont indépendants si: : l'occurrence de chacun d'eux n'affecte pas la probabilité que l'autre se produise. Un exemple de ceci est l'échantillonnage à 1s avec remplacement.

Pour des événements indépendants A et B, $P(A\cap B)$=:: $P(A)P(B)$
<!--SR:!2023-10-13,10,252-->

## Événements dépendants
Deux événements sont dépendants si:: la survenance de l'un d'entre eux affecte la probabilité que l'autre se produise. L'échantillonnage sans remplacement en est un exemple.
<!--SR:!2023-10-13,10,252-->

Pour les événements dépendants A et B, $P(A\cap B)$=::$P(A)\times P(B/A)$
<!--SR:!2023-10-25,16,232-->

## Probabilité conditionnelle
Pour deux événements A et B, $A/B$ représente l'événement "A sachant B", et $P(A/B)$=::$\frac{P(A\cap B)}{P(B)}$
<!--SR:!2023-11-06,25,252-->

Pour des événements indépendants, $P(A)$=::$P(A/B)=P(A/B')$
<!--SR:!2023-10-13,10,252-->

Axiom des probabilités totales, pour événement secondaire : $P(B)$=::$P(A\cap B)+P(A'\cap B)$
<!--SR:!2023-11-05,24,252-->

$P(A\cap B')$=::$P(A)-P(A\cap B)$
<!--SR:!2023-10-25,13,231-->

