---
tags:
  - computer_science
---
Created: 2024-03-17

# Terminologie de modèle de base de données relationnelle

Une table est:: un ensemble de données organisées sous forme d'un tableau où les colonnes correspondent à des catégories d'information et les lignes à des enregistrements, également appelés entrées.
<!--SR:!2024-04-18,19,250-->

Un enregistrement correspond à:: une entrée d’une table.
<!--SR:!2024-04-21,22,250-->

Un enregistrement est composé de plusieurs données, réparties dans plusieurs colonnes. Chaque donnée correspond à un champ. Un enregistrement est donc composé de:: plusieurs champs.
<!--SR:!2024-04-04,12,270-->

Une clé primaire permet:: d’identifier de manière unique les enregistrements d’une table et facilite la mise en relation d’une table avec une autre.
<!--SR:!2024-04-22,22,250-->

La clé étrangère permet:: d'accéder à l’enregistrement parent ou cible d'une relation.
<!--SR:!2024-04-11,14,250-->

On appelle clés candidates:: l'ensemble des clés d'une relation qui n'ont pas été choisies comme clé primaire(elles étaient candidates à cette fonction).
<!--SR:!2024-04-20,20,250-->

Une clé primaire composite est:: une clé primaire composée de plusieurs champs.
<!--SR:!2024-04-22,22,250-->

Les tables d’une base de données relationnelles sont mises en relation à l’aide d’une clé primaire et d’une clé étrangère. Pour associer les données des différentes tables mises en relation, on doit utiliser:: une jointure. ![[image-20240317161935460.png]]
<!--SR:!2024-04-04,10,230-->



