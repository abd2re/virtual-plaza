---
tags:
  - math
---
Created: 2023-09-23

# Probabilité discrètes
## Experience aléatoire-événements
Une expérience aléatoire est une expérience dont l'issue dépend du:: hasard.
<!--SR:!2025-09-05,523,310-->
L'ensemble des résultats possibles d'une expérience aléatoire est appelé:: univers.
<!--SR:!2024-05-15,144,250-->
On appelle événement:: toute partie de l'univers (sous-ensemble)
<!--SR:!2024-07-07,107,190-->

### Définitions
- Evénement élémentaire:: a une seule issue
<!--SR:!2024-06-08,157,250-->
- Evénement composé:: a plusieurs issues
<!--SR:!2024-11-27,274,270-->
- Evénement A et B (conjonction d'événement):: événement constitué des issues communes aux deux événements
<!--SR:!2024-06-29,172,250-->
- Evénement contraire a A noté A':: événement dont les issues n'appartiennent pas a A
<!--SR:!2024-06-05,157,250-->
- Evénement A ou B (disjonction d'événement):: événement constitué de toutes les issues des deux événements
<!--SR:!2024-04-20,129,250-->
- Evénement incompatible (mutuellement exclusif):: conjonction des deux événements avec aucune issue
<!--SR:!2024-07-04,174,250-->
- Evénement certain:: toutes les issues
<!--SR:!2024-12-30,279,250-->
- Evénement impossible:: aucune issue
<!--SR:!2024-10-13,245,270-->

## Calcul de probabilité
- La probabilité d'un événement est la somme:: des éléments élémentaires qui le compose.
<!--SR:!2024-09-19,188,230-->
- Lorsque les événements élémentaires ont meme probabilité, on dit qu'il y a:: équiprobabilité ou équi-répartition.
<!--SR:!2024-05-08,139,250-->

### Propriété
- $\frac{n(X)}{n(U)}$=::$P(X)$
<!--SR:!2024-06-17,139,250-->
- $P(U)$=::1
<!--SR:!2024-05-07,139,250-->
- $P(0)$=::0
<!--SR:!2025-03-27,391,290-->
- $P(A)+P(A')$=::1
<!--SR:!2024-05-14,142,250-->
- $P(A\cup B)$ (2)=::$P(A)+P(B)-P(A\cap B)=P(A\cap B')+P(A\cap B)+P(A'\cap B)$
<!--SR:!2024-09-13,161,210-->
- $P(A\Delta B)$=::$P(A\cap B')\cup P(A'\cap B)$
<!--SR:!2024-05-09,66,230-->

## Événements indépendants
Deux événements sont indépendants si: : l'occurrence de chacun d'eux n'affecte pas la probabilité que l'autre se produise. Un exemple de ceci est l'échantillonnage à 1s avec remplacement.

Pour des événements indépendants A et B, $P(A\cap B)$=:: $P(A)P(B)$
<!--SR:!2024-06-23,163,252-->

## Événements dépendants
Deux événements sont dépendants si:: la survenance de l'un d'entre eux affecte la probabilité que l'autre se produise. L'échantillonnage sans remplacement en est un exemple.
<!--SR:!2024-07-08,173,252-->

Pour les événements dépendants A et B, $P(A\cap B)$=::$P(A)\times P(B/A)$
<!--SR:!2024-04-14,44,212-->

## Probabilité conditionnelle
Pour deux événements A et B, $A/B$ représente l'événement "A sachant B", et $P(A/B)$=::$\frac{P(A\cap B)}{P(B)}$
<!--SR:!2024-04-22,71,232-->

Pour des événements indépendants, $P(A)$=::$P(A/B)=P(A/B')$
<!--SR:!2024-04-29,78,232-->

Axiom des probabilités totales, pour événement secondaire : $P(B)$=::$P(A\cap B)+P(A'\cap B)$
<!--SR:!2024-05-01,32,172-->

$P(A\cap B')$=::$P(A)-P(A\cap B)$
<!--SR:!2024-05-06,67,211-->


Arbre de probabilité conditionnelle avec $P(A)$ et $P(B)$:
?
![[image-20240326090516255.png|center]]
<!--SR:!2024-04-11,8,224-->


