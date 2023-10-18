Abdoul Wahab Touré - Tle IB - 17/10/2023
**Exercice 1**
```pascal
input n1, n2
if n2>n1 then
	n1=n2
end if
output n1
```
**Exercice 2**
1. Diagramme de Gantt est un diagramme qui permet de représenter des événements et des étapes dans des intervalles de temps définis.
2. .
	1. La recherche séquentielle est un algorithme de recherche qui commence à une début d'une liste et parcourt chaque élément d'une liste jusqu'à ce que l'élément souhaité soit trouvé, sinon la recherche se poursuit jusqu'à la fin.
	2. La recherche binaire est un algorithme de recherche qui consiste à diviser plusieurs fois en deux la partie de la liste susceptible de contenir l'élément, jusqu'à ce qu'on réduit les emplacements possibles à un seul élément.
	3. Un algorithme de tri à bulles parcourt une liste de données un certain nombre de fois, en comparant deux éléments côte à côte pour voir lequel est hors d'ordre. Il continue à parcourir la liste de données jusqu'à ce que toutes les données soient triées dans l'ordre.
3. Les langages de haut niveau doivent être traduits en code exécutable par la machine car l'ordinateur ne peut comprendre que le langage machine donc un processus de traduction est nécessaire.
4. La traduction d'un langage de haut niveau en code exécutable par la machine peut se faire de deux manières:
	1. Avec un compilateur qui est un traducteur qui n'exécute le processus de traduction qu'une seule fois. Il traduit normalement l'ensemble du programme source en programme objet.
	2. Ou avec un interprète est qui un traducteur qui effectue le processus de traduction à chaque fois que le programme est exécuté.

**Exercice 3**

| | val | found | maxpos | minpos | minpos<=maxpos and not found | midpos | arr[midpos] | Output | 
|---:|------:|:--------|---------:|---------:|:-----------------|---------:|--------------:|:---------| 
| 0 | 11 | False | 12 | 0 | True | 6 | 13 | | 
| 1 | 11 | False | 5 | 0 | True | 2 | 3 | | 
| 2 | 11 | False | 5 | 3 | True | 4 | 7 | | 
| 3 | 11 | True | 5 | 5 | False | 5 | 11 | 11 trouvé|
**Exercice 4**
a. L'algorithme suivant n'est par correcte.
b. Remplacer la ligne:
```pascal  
loop while STUDENTS.hasNext() and FOUND = true
```  
par:
```pascal  
loop while STUDENTS.hasNext() and FOUND = false
```
**Exercice 5**
a. $101101_{2}=2_{10}^{0}+2_{10}^{2}+2_{10}^{3}+2_{10}^{5}=45_{10}$
b. $55_{10}=32_{10}+16_{10}+4_{10}+2_{10}+1_{10}=110111_{2}$
**Exercice 6**
x = not c, y = a AND b, z = x OR y


|a|b|c|x|y|z|
|-|-|-|-|-|-|
|0|0|0|1|0|1|
|0|0|1|0|0|0|
|0|1|0|1|0|1|
|0|1|1|0|0|0|
|1|0|0|1|0|1|
|1|0|1|0|0|0|
|1|1|0|1|1|1|
|1|1|1|0|1|1|
![[diagramme logique]]
**Exercice 7**
```pascal
NOTES.resetNext()
MAX = NOTES.getNext()
MIN = MAX
SUM = MAX
I = 1
loop while NOTES.hasNext()
	NOTE = NOTES.getNext()
	if NOTE > MAX then
		MAX = NOTE
	end if
	if NOTE < MIN then
		MIN = NOTE
	end if
	SUM = SUM + NOTE
	I = I +1
end loop
output "Valeur minimale:", MIN
output "Valeur maximale:", MAX
output "Valeur moyenne:", SUM/I
```


