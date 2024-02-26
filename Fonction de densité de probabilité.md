---
tags:
  - math
---
Created: 2024-02-23

# Fonction de densité de probabilité

- Pour toute valeur de $x$, $f(x)$::$\geq 0$
- L'aire en dessous du graphe est égale à:: 1.$$\int_{-\infty}^{\infty}f(x)\,dx=1$$
- $P(a\leq X\leq B)=P(a<X<b)=$::$$\int_{b}^{a}f(x)\,dx$$
- $P(x=n)=$::$0$
- La médiane, $m$, d'une variable aléatoire continue $X$ avec une fonction de densité de probabilité $f(x)$ est définie comme la valeur de $X$ telle que::$$P(X<m)=P(X>m)=0.5$$$$\int_{-\infty}^{m}f(x)\,dx=\int_{m}^{\infty}f(x)\,dx=\frac{1}{2}$$
- Si le graphique est une courbe avec un point maximum, le mode peut être trouvé en:: différenciant et en résolvant $f'(x)=0$
- $\mu=E(X)=$::$$\int_{-\infty}^{\infty}xf(x)\,dx$$
- $\sigma^{2}=\text{Var}(X)=$(2)::$$E(X^{2})-E(X)^{2}=\int_{-\infty}^{\infty}x^{2}f(x)\,dx-\mu^{2}$$$$\int_{-\infty}^{\infty}(x-\mu^{2})f(x)\,dx$$
