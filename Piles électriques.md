---
tags: [physics] 
---
Created: 2022-12-20

# Piles électriques
?
Une pile convertit l'énergie chimique en énergie électrique avec dissipation/perte d'énergie sous forme de [[chaleur]].
<!--SR:!2024-02-06,33,130-->

- Une pile est caractérisée par:: sa fem $e$ et sa résistance interne $r$. $e$ en volt et $r$ en ohm.
<!--SR:!2024-06-05,326,286-->

- $e$ fem =>:: force électromotrice; travail par unité de charge pour faire circular les charges
<!--SR:!2024-04-20,113,226-->

Formule de la tension aux bornes d'une pile est:
?
$$U=e-rI$$- $U$ = tension dans la puissance électrique
- $e$ = fem de la puissance chimique
- $r$ = résistance interne 
- $I$ = intensité
- ![[Piles électriques-6.png]]
<!--SR:!2024-02-01,225,226-->

Caractéristique intensité-tension d'une pile (graphe)::![[Piles électriques.png]]
<!--SR:!2024-03-24,105,226-->

On peut retrouver la formule $U=e-rI$ en effectuant le montage suivant::![[circuit caractéristique d'une pile]]
<!--SR:!2024-03-11,103,226-->

- $U=e$ si:: $I=0$
<!--SR:!2025-01-31,460,246-->
- $e$ c'est la tension aux bornes de la pile quand:: elle ne fournit pas de courant
<!--SR:!2024-05-07,117,226-->
- Un pile idéale est une pile qui:: n'a pas de résistance interne $r=0$ (le graphe intensité-tension est constante en $e$)
<!--SR:!2024-02-24,98,226-->

circuit équivalent d'une pile réel::![[equivalent e;r]]
<!--SR:!2024-03-19,79,206-->

## Circuits avec des piles
formule emf::$$e=(r+R)I$$
<!--SR:!2024-02-07,11,130-->


## Circuits simples comportant des piles, récepteurs et resistors

**Tension aux bornes d'un récepteur**:
?
Un récepteur (ex un moteur, un électrolyseur) est un appareil qui consomme plus d'énergie que n'a besoin l'effet joule.
Le récepteur est caractérisé oar 1 fcem $e'$ (force contre électromotrice) et par sa résistance interne.
<!--SR:!2024-02-16,92,220-->

Formule de la tension  d'un récepteur::$$U_{recept}=e'+rI$$
<!--SR:!2024-05-19,114,220-->
- Une pile branchée en opposition se comporte comme:: un récepteur
<!--SR:!2024-05-24,114,220-->


Formule des fem et fcem dans un circuit avec piles et récepteurs (+branchement):
?
![[image-20230109163848957.png]]
$$\Sigma{e} - \Sigma{e'}=\Sigma{R}\times I$$
<!--SR:!2024-02-04,89,220-->

## Circuit avec des nœuds comportant des générateurs

Schema du sens de parcours (rouge) et sens du courant (bleu) pour les piles et les résistances:
?
![[image-20230109170117486.png]]
<!--SR:!2024-02-22,242,240-->

## Association de piles
**En série** (Avantage, branchement et formule)
?
Pour avoir plus de tension.
![[image-20230110091918045.png]]$$V_{PN}=V_{PA}+V_{AB}+V_{BN}$$
$$V_{PN}=e_{1}-r_{1}I+e_{2}-r_{2}I+e_{3}-r_{3}I$$
$$V_{PN}=e_{1}+e_{2}+e_{3}-(r_{1}+r_{2}+r_{3})I$$
$$e_s=\sum{e}$$$$r_s=\sum\limits{r}$$
<!--SR:!2024-03-28,100,220-->

**En parallèle** (Avantage, branchement et formule)
?
Pour avoir plus d'intensité
![[image-20230110093433182.png]]
$$U_{PN}=e-r\frac{I}{n}=e-r\frac{I}{n}=e-r\frac{I}{n}$$
$$e_{//}=e,\;r_{//}=\frac{r}{n}$$
<!--SR:!2024-02-17,92,220-->








