---
tags:
  - math
---
Created: 2024-01-30

# Equations différentielles

Une équation homogène s'écrit sous la forme::$$\frac{dy}{dx}=f\left(\frac{y}{x}\right)$$
<!--SR:!2024-02-06,1,190-->
Une équation homogène peut être résolu par la substitution suivante:: $v=\frac{y}{x}\Leftrightarrow y=vx$
<!--SR:!2024-02-08,5,248-->

Dans ce contexte, on entend par homogène une fonction de $x$ et $y$ ($f(x,y)$) qui reste inchangée si:: l'on multiplie les deux arguments par une constante ($f(kx,ky)$).
<!--SR:!2024-02-08,5,248-->

Un facteur d'intégration peut être utilisé pour résoudre une équation différentielle qui peut être écrite sous la forme::$$\frac{dy}{dx}+P(x)y=Q(x)$$
<!--SR:!2024-02-06,2,228-->
Le facteur d'intégration est $I$:: $I=e^{\int P(x)\,dx}$
<!--SR:!2024-02-07,4,248-->

L'équation différentielle $I\frac{dy}{dx}+IP(x)y=IQ(x)$ où $I=e^{\int P(x)\,dx}$ devient comment après l'intégration des deux cotés ?
?
$$\int\left(I\frac{dy}{dx}+IP(x)y\right)\,dx=\int IQ(x)\,dx$$
$$Iy=\int IQ\,dx$$
<!--SR:!2024-02-08,5,248-->


Etapes pour utiliser la méthode d'Euler avec une équation différentielle du premier ordre:
?
- S'assurer que l'équation différentielle est sous la forme $\frac{dy}{dx}=f(x,y)$
- Ecrire les équations de récurrence à l'aide des formules $y_{n+1}=y_{n}+h\times f(x_{n},y_{n})$ et $x_{n+1}=x_{n}+h$ ($h$ est la taille de l'étape qui est donnée)
- Utiliser la fonction de récursivité du GDC pour calculer l'approximation de la méthode d'Euler sur le nombre correct d'étapes. (les valeurs de $x_{0}$ et $y_{0}$ sont données)
<!--SR:!2024-02-07,2,226-->