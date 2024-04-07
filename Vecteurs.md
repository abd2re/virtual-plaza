---
tags:
  - math
---
Created: 2024-03-22

# Vecteurs
## Introduction aux vecteurs
- Deux vecteurs sont parallèles si:: l'un est un multiple scalaire de l'autre.
<!--SR:!2024-04-23,17,250-->
- Le vecteur position du point A s'écrit avec la notation $\vec{a}=$::$\overrightarrow{OA}$
<!--SR:!2024-04-10,11,270-->
- La magnitude d'un vecteur $|\vec{v}|=$::$\sqrt{v_{x}^{2}+v_{y}^{2}+v_{z}^{2}}$
<!--SR:!2024-04-11,12,270-->
- Un vecteur unitaire dans la direction de $\vec{a}$ est noté::$\frac{\vec{a}}{|\vec{a}|}$
<!--SR:!2024-04-12,13,270-->


Le produit scalaire de deux vecteurs donne des informations sur:: l'angle entre les deux vecteurs.
<!--SR:!2024-04-08,9,250-->
- Si le produit scalaire est positif, l'angle entre les deux vecteurs est:: aigu (inférieur à 90°).
<!--SR:!2024-04-09,10,270-->
- Si le produit scalaire est négatif, l'angle entre les deux vecteurs est:: obtus (entre 90° et 180°).
<!--SR:!2024-04-10,11,270-->
- Si le produit scalaire est nul, l'angle entre les deux vecteurs est:: de 90° (les deux vecteurs sont perpendiculaires).
<!--SR:!2024-04-09,10,270-->
- Formule produit scalaire $\vec{v}\cdot\vec{w}=$(2)::$$\large{v_{x}w_{x}+v_{y}w_{y}+v_{z}w_{z}=|\vec{v}||\vec{w}|\cos\theta}$$ où $\theta$ est l'angle entre $\vec{v}$ et $\vec{w}$.
<!--SR:!2024-04-12,13,270-->
- $\vec{u}\cdot(\vec{v}+\vec{w})$=::$\vec{u}\cdot\vec{v}+\vec{u}\cdot\vec{w}$
<!--SR:!2024-04-11,12,270-->
- $k\vec{v}\cdot\vec{w}=$::$k(\vec{v}\cdot\vec{w})$
<!--SR:!2024-04-21,16,250-->
- $\vec{v}\cdot \vec{v}=$::$|\vec{v}|^{2}$
<!--SR:!2024-04-09,10,250-->
- Si deux vecteurs, $\vec{v}$ et $\vec{w}$, sont parallèles, alors $|\vec{v}\cdot\vec{w}|=$::$|\vec{v}||\vec{w}|$.
<!--SR:!2024-04-08,9,250-->
- Si deux vecteurs sont perpendiculaires, le produit scalaire est:: nul.
<!--SR:!2024-04-08,9,270-->
- L'angle angle entre $\vec{v}$ et $\vec{w}$, $\theta=$::$$\large{\cos^{-1}\left(\frac{v_{x}w_{x}+v_{y}w_{y}+v_{z}w_{z}}{|\vec{v}||\vec{w}|}\right)}$$
<!--SR:!2024-04-23,17,250-->
- Si un point $X$ divise un segment de droite $AB$ dans le rapport $p:q$, alors $\overrightarrow{AX}=$::$\frac{p}{p+q}\overrightarrow{AB}$
<!--SR:!2024-04-08,9,270-->
- Si le point $A$ a pour vecteur position $\vec{a}$ et le point $B$ a pour vecteur position $\vec{b}$, alors le vecteur position du milieu de $\overrightarrow{AB}$, $\overrightarrow{OM}=$::$\frac{1}{2}(\vec{a}+\vec{b})$
<!--SR:!2024-04-10,11,270-->
- Si le point $A$ a pour vecteur position $\vec{a}$ et le point $B$ a pour vecteur position $\vec{b}$, alors le vecteur de déplacement $\overrightarrow{AB}=$::$\vec{b}-\vec{a}$
<!--SR:!2024-04-16,10,230-->

## Equations vectorielles des droites
La formule permettant de trouver l'équation vectorielle d'une droite est la suivante (2) (avec explications des variables):
?
$$\large{\vec{r}=\vec{a}+\lambda \vec{b}=\begin{pmatrix}a_{1} \\ a_{2} \\ a_3 \\ \end{pmatrix}+\lambda\begin{pmatrix}b_{1} \\ b_{2} \\ b_3 \\ \end{pmatrix}}$$
- Où $\vec{r}$ est le vecteur de position de n'importe quel point de la ligne
- $\vec{a}$ est le vecteur de position d'un point connu sur la ligne
- $\vec{b}$ est un vecteur de direction (déplacement)
- $\lambda$ est un scalaire
<!--SR:!2024-04-07,8,250-->

Cette équation vectorielle peut ensuite être divisée en trois formes distinctes (formules des équations paramétriques):
?
- $r_{1}=a_{1}+\lambda b_{1}$
- $r_{2}=a_{2}+\lambda b_{2}$
- $r_{3}=a_{3}+\lambda b_{3}$
<!--SR:!2024-04-07,4,210-->

En 3 dimensions l'equasion cartésienne d'un droite est::$$\frac{r_{1}-a_{1}}{b_{1}}=\frac{r_{2}-a_{2}}{b_{2}}=\frac{r_{3}-a_{3}}{b_{3}}$$
<!--SR:!2024-04-12,10,250-->

Si l'une des variables ne dépend pas de $\lambda$, cette partie peut être écrite comme:: une équation séparée.
<!--SR:!2024-04-09,7,250-->


Deux lignes sont parallèles si, et seulement si:: leurs vecteurs direction $\vec{b}$ sont parallèles/les vecteurs direction seront des multiples de l'un à l'autre.
<!--SR:!2024-04-07,3,255-->

Si deux lignes parallèles partagent un point, alors:: elles partagent tous les points et sont coïncidentes.
<!--SR:!2024-04-08,4,275-->

Les lignes qui ne sont pas parallèles et qui ne se croisent pas sont appelées:: lignes non co-planaires.
<!--SR:!2024-04-07,3,255-->

L'angle entre deux lignes est égal à:: l'angle entre leurs vecteurs de direction.
<!--SR:!2024-04-07,2,235-->

La formule de l'angle $\theta$ de deux lignes sous la forme $\vec{r}=\vec{a} +\lambda\vec{b}$ est::$$\large{\theta=\cos^{-1}\left(\frac{\vec{b_{1}}\cdot\vec{b_{2}}}{|\vec{b_{1}}||\vec{b_{2}}|}\right)}$$
<!--SR:!2024-04-07,2,235-->


Le produit vectoriel est un vecteur dans un plan qui est:: perpendiculaire aux deux vecteurs à partir desquels il a été calculé.
<!--SR:!2024-04-07,3,255-->

Le produit vectoriel des deux vecteurs $\vec{v}\times\vec{w}$ peut être écrit sous forme de composantes comme suit::$$\large{\vec{v}\times\vec{w}=\begin{pmatrix}v_{2}w_{3}-v_{3}w_{2} \\ v_{3}w_{1}-v_{1}w_{3} \\ v_{1}w_{2}-v_{2}w_{1}\end{pmatrix}}$$
<!--SR:!2024-04-08,2,215-->
La magnitude du produit vectoriel $|\vec{v}\times\vec{w}|$ est égale à::$$\large{|\vec{v}\times\vec{w}|=|\vec{v}||\vec{w}|\sin\theta}$$
<!--SR:!2024-04-07,3,255-->

- L'équivalent de $\vec{v}\times\vec{w}$ est::$-\vec{w}\times\vec{v}$
<!--SR:!2024-04-08,3,255-->
- Si deux vecteurs sont parallèles, le produit vectoriel est:: nul.
<!--SR:!2024-04-07,3,255-->
- L'aire d'un parallélogramme $A$ dont les deux côtés adjacents sont formés par les vecteurs $\vec{v}$ et $\vec{w}$ est égale à::$A=|\vec{v}\times\vec{w}|$
<!--SR:!2024-04-07,3,255-->
- L'aire du triangle à deux côtés formé par les vecteurs $v$ et $w$ est égale à::$A=\frac{1}{2}|\vec{v}\times\vec{w}|$
<!--SR:!2024-04-07,3,255-->

Étant donné un point $P$ et une ligne $\vec{r}=\vec{a} +\lambda \vec{b}$, la distance la plus courte entre $P$ et la ligne sera::$$\frac{|\overrightarrow{RP}\times \vec{b}|}{|\vec{b}|}$$ où $R$ est un point sur la ligne.
<!--SR:!2024-04-07,3,255-->

Le produit scalaire du vecteur direction $b$ et du vecteur dans la direction de la plus courte distance sera:: nul (perpendicularité).
<!--SR:!2024-04-07,3,255-->

La distance la plus courte entre deux lignes parallèles $\vec{r_{1}}=\vec{a_{1}}+\lambda \vec{b_{1}}$ et $\vec{r_{2}}=\vec{a_{2}}+\mu \vec{b_{2}}$ peut être donné avec la formule est:
?
$$\frac{|\overrightarrow{A_{1}A_{2}}\times \vec{b}|}{|\vec{b}|}$$
- Où $\overrightarrow{A_{1}A_{2}}$ est le vecteur reliant les deux coordonnées données $\vec{a_{1}}$ et $\vec{a_{2}}$
- $\vec{b}$ est le vecteur simplifié dans la direction de $\vec{b_{1}}$ et $\vec{b_{2}}$.
<!--SR:!2024-04-07,3,255--> 

Pour trouver la distance la plus courte entre deux lignes non co-plainaires $\vec{r_{1}}=\vec{a_{1}}+\lambda \vec{b_{1}}$ et $\vec{r_{2}}=\vec{a_{2}}+\mu \vec{b_{2}}$, on peut résoudre l'équation suivante:
?
$$\vec{r_{2}}-\vec{r_{1}}=k(\vec{b_{1}}\times\vec{b_{2}})$$ après calculer $|\vec{r_{2}}-\vec{r_{1}}|$.
<!--SR:!2024-04-07,3,255-->


## Plans vectoriels
La forme vectorielle de l'équation d'un plan peut être trouvée à partir de deux vecteurs de direction sur le plan, les vecteurs de direction doivent être (2):: parallèle au plan et non parallèles l'un à l'autre.
<!--SR:!2024-04-07,3,255-->


La formule permettant de trouver l'équation vectorielle d'un plan est (2):
?
$$\large{\vec{r}=\vec{a}+\lambda\vec{b}+\mu\vec{c}=\begin{pmatrix}a_{1} \\ a_{2} \\ a_3 \\ \end{pmatrix}+\lambda\begin{pmatrix}b_{1} \\ b_{2} \\ b_3 \\ \end{pmatrix}+\mu\begin{pmatrix}c_{1} \\ c_{2} \\ c_3 \\ \end{pmatrix}}$$
- Où $\vec{r}$ est le vecteur de position de n'importe quel point sur le plan
- $\vec{a}$ est le vecteur position d'un point connu sur le plan
- $\vec{b}$ et $\vec{c}$ sont des vecteurs de direction (déplacement) parallèles au plan
- $\lambda$ et $\mu$ sont des scalaires
<!--SR:!2024-04-07,3,255-->

Le produit scalaire du vecteur normal et de n'importe quel vecteur de direction sur le plan sera:: zéro.
<!--SR:!2024-04-07,3,255-->

L'équation d'un plan utilisant le vecteur normal est:
?
$$\large{\vec{n}\cdot\vec{r}=\vec{a}\cdot\vec{n}}$$
- Où $\vec{r}$ est le vecteur de position de n'importe quel point sur le plan
- $\vec{a}$ est le vecteur position d'un point connu sur le plan
- $n$ est un vecteur normal au plan
<!--SR:!2024-04-07,3,255-->

L'équation cartésienne d'un plan est donnée sous la forme suivante::$$ar_{1}+br_{2}+cr_{3}=d$$ où $a$, $b$, $c$ et $d$ sont des coefficients.
<!--SR:!2024-04-07,3,255-->
- Dans une équation cartésienne d'un plan $ar_{1}+br_{2}+cr_{3}=d$, $\begin{pmatrix}a \\ b \\ c\end{pmatrix}=$(2)::$\vec{n}=\vec{b}\times\vec{c}$.
<!--SR:!2024-04-07,3,255-->
- Dans une équation cartésienne d'un plan $ar_{1}+br_{2}+cr_{3}=d$, $d=$::$\vec{n}\cdot\vec{a}$.
<!--SR:!2024-04-07,3,255-->
- Une nouvelle formule pour l'équation cartésienne en utilisant les vecteurs positions et vecteurs directeurs est::$$n_{1}r_{1}+n_{2}r_{2}+n_{3}r_{3}=\vec{n}\cdot\vec{a}$$ où $\vec{n}=\vec{b}\times\vec{c}$
<!--SR:!2024-04-07,3,255-->

Une ligne est parallèle à un plan si son vecteur directeur est:: perpendiculaire à la normale du plan.
<!--SR:!2024-04-07,2,235-->

Si une ligne n'est pas parallèle à un plan, elle l'intersectera en un seul point, ce point peut être trouvé en:: remplaçant les composantes $\vec{r}$ du plan par les composantes $\vec{r}$ de la ligne dans l'équation cartésienne du plan pour trouver $\lambda$ pour ensuite pouvoir trouver $\vec{r}$.
<!--SR:!2024-04-07,3,255-->

Si nous avons les formes cartésiennes des deux plans, l'équation de la ligne d'intersection peut être trouvée en résolvant simultanément les deux équations et en exprimant deux autres variables (comme $y$ et $z$) par rapport à une (comme $x$) qu'on va remplacer par $\lambda$ 