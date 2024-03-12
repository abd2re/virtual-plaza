---
tags:
  - math
---
Created: 2024-02-23

# Fonction de densité de probabilité

- Pour toute valeur de $x$, $f(x)$::$\geq 0$
<!--SR:!2024-03-13,6,250-->
- L'aire en dessous du graphe est égale à:: 1.$$\int_{-\infty}^{\infty}f(x)\,dx=1$$
<!--SR:!2024-03-21,11,230-->
- $P(a\leq X\leq B)=P(a<X<b)=$::$$\int_{b}^{a}f(x)\,dx$$
<!--SR:!2024-03-16,10,250-->
- $P(x=n)=$::$0$
<!--SR:!2024-03-18,11,270-->
- La médiane, $m$, d'une variable aléatoire continue $X$ avec une fonction de densité de probabilité $f(x)$ est définie comme la valeur de $X$ telle que::$$P(X<m)=P(X>m)=0.5$$$$\int_{-\infty}^{m}f(x)\,dx=\int_{m}^{\infty}f(x)\,dx=\frac{1}{2}$$
<!--SR:!2024-03-16,10,250-->
- Si le graphique est une courbe avec un point maximum, le mode peut être trouvé en:: différenciant et en résolvant $f'(x)=0$
<!--SR:!2024-03-15,9,250-->
- $\mu=E(X)=$::$$\int_{-\infty}^{\infty}xf(x)\,dx$$
<!--SR:!2024-03-22,11,230-->
- $\sigma^{2}=\text{Var}(X)=$(2)::$$E(X^{2})-E(X)^{2}=\int_{-\infty}^{\infty}x^{2}f(x)\,dx-\mu^{2}$$$$\int_{-\infty}^{\infty}(x-\mu^{2})f(x)\,dx$$
<!--SR:!2024-03-15,9,250-->
