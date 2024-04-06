---
tags:
  - computer_science
---
Created: 2024-01-27

# Arbres
- Elles appartiennent à la catégorie des:: graphes
<!--SR:!2024-07-03,94,250-->
- Elles se composent de:: nœuds reliés par des arêtes.
<!--SR:!2024-04-07,44,250-->

## Terminologie relative à l'arbre binaire
- Feuille:: Un nœud qui n'a pas d'enfant est appelé feuille.
<!--SR:!2024-05-26,77,270-->
- Niveau:: Le niveau d'un nœud particulier correspond au nombre de générations du nœud à partir de la racine. Si nous supposons que la racine est de niveau 1, ses enfants seront de niveau 2, ses petits-enfants de niveau 3, etc.
<!--SR:!2024-04-09,44,250-->
- Hauteur:: Nombre d'arêtes entre le nœud supérieur et la feuille la plus profonde (c'est-à-dire la plus éloignée).
<!--SR:!2024-04-08,40,230-->
- Racine:: Le nœud situé au sommet de l'arbre est appelé la racine.
<!--SR:!2024-06-04,83,270-->
- Profondeur d'un nœud:: La longueur du chemin menant à sa racine.
<!--SR:!2024-04-13,47,250-->
- Sous-arbre:: Tout nœud peut être considéré comme la racine d'un sous-arbre sauf la racine.
<!--SR:!2024-05-02,59,250-->

## Traversée d'un arbre
- Préfixe:: Traiter le nœud, visiter le nœud gauche, visiter le nœud droit.
<!--SR:!2024-06-16,84,250-->
- Infixe:: Visite du nœud gauche, traitement du nœud, visite du nœud droit.
<!--SR:!2024-04-08,44,250-->
- Suffixe:: Visite du nœud gauche, visite du nœud droit, traitement du nœud.
<!--SR:!2024-07-17,104,250-->