---
tags:
  - computer_science
---
Created: 2024-03-23

# Formes de normalisation 1NF, 2NF, 3NF

La normalisation est:: un processus par lequel les grandes tables d'une base de données sont divisées en tables plus petites tout en assurant l'intégrité des données et en réduisant la redondance des données.
<!--SR:!2024-04-12,8,250-->

La normalisation permet d’éliminer les attributs.. (4):
?
- à valeurs multiples
- qui se répètent ou qui contiennent les mêmes données
- non liés ou non descriptifs
- contenant des informations redondantes
<!--SR:!2024-04-08,4,230-->

## 1ère forme normale (1NF)
Une relation est en première forme normale si:: chaque attribut de cette relation est un attribut à valeur unique.
<!--SR:!2024-04-11,7,250-->

La première forme de normalisation est obtenue en (2):
?
- éliminant les colonnes en double et les colonnes comportant plusieurs types de valeurs
- en créant des tables distinctes pour chaque groupe de données liées (avec des clés primaires uniques)
<!--SR:!2024-04-14,10,250-->

## 2ème forme normale (2NF)
Pour être dans la deuxième forme normale, une relation doit:: être dans la première forme normale et la relation ne doit pas contenir de dépendance partielle.
<!--SR:!2024-04-12,8,250-->

Une dépendance partielle sont:: des colonnes dépendant d'un attribut d'une clé primaire composite.
<!--SR:!2024-04-08,4,230-->

## 3ème forme normale (3NF)
Pour être dans la troisième forme normale, une relation doit:: être dans la deuxième forme normale et la relation ne doit pas contenir de dépendance transitive.
<!--SR:!2024-04-09,5,230-->
