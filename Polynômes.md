---
tags:
  - math
---
Created: 2023-10-27

# Polynômes
## Théorème des facteurs
- $(x - k)$ est un facteur de $P(x)$ si:: $P(k)= 0$
<!--SR:!2024-01-19,51,250-->
- $P(k)=0$ si:: $(x-k)$ est un facteur de $P(x)$
<!--SR:!2023-12-24,24,190-->
- $P(x)$=::$(x-k)\times Q(x)$, où $Q(x)$ est un polynôme qui est un facteur de $P(x)$
<!--SR:!2024-01-14,46,250-->
- $\frac{P(x)}{x-k}$=::$Q(x)$
<!--SR:!2024-01-11,44,250-->
- Si le facteur linéaire est $(ax-b)=a\left(x-\frac{b}{a}\right)$, alors il faut que:: $P\left(\frac{b}{a}\right)=0$
<!--SR:!2023-12-19,29,230-->
## Théorème des restes
- Lorsqu'un polynôme quelconque $P(x)$ est divisé par une fonction linéaire quelconque $(x - k)$, la valeur du reste $R$ est donnée par:: $P(k) =R$
<!--SR:!2024-02-16,69,250-->
- Remarque : lorsque $P(k) =0$, $(x - k)$ est:: un facteur de $P(x)$.
<!--SR:!2023-12-30,37,250-->
- $P(x)$=::$(x-k)\times Q(x)+R$ où $Q(x)$ est un polynôme
<!--SR:!2024-01-06,32,210-->
- $\frac{P(x)}{x-k}$=::$Q(x)+\frac{R}{x-k}$ où $R$ est le reste
<!--SR:!2023-12-10,28,250-->
- Si le facteur linéaire est $(ax-b)=a\left(x-\frac{b}{a}\right)$, alors $P\left(\frac{b}{a}\right)$=::$R$
<!--SR:!2023-12-11,10,190-->

## Division polynomiale
Formule générale::$$\frac{P(x)}{D(x)}=Q(x)+\frac{R(x)}{D(x)}$$
<!--SR:!2024-01-27,50,230-->

- Cette méthode n'est généralement utile que lorsque le degré du dénominateur est:: inférieur ou égal au degré du numérateur.
<!--SR:!2024-01-06,42,250-->

Soit deux polynômes: $P(x)=a_{n}x^{n}+a_{n-1}x^{n-1}+\dots+a_{1}x+a_{0}$ qu'on divise par $D(x)=b_{k}x^{k}+b_{k-1}b^{k-1}+\dots+b_{1}x+b_{0}$ avec $n\geq k$. Les étapes sont:
?
1. Diviser le premier terme du polynôme $P(x)$ par le premier terme du diviseur $D(x)$. $$\frac{a_{n}x^{n}}{b_{k}x^{k}}=q_{m}x^{m}$$
2. Multiplier le diviseur par ce terme. $$D(x)\times q_{m}x^{m}$$
3. Soustraire ce résultat du polynôme d'origine. $$R(x)=P(x)-D(x)\times q_{m}x^{m}$$
4. Répétez les étapes 1 à 3 en utilisant le nouveau polynôme $R(x)$ à la place de $P(x)$ jusqu'à ce que la soustraction aboutisse à une expression pour $R(x)$ dont le degré est inférieur à celui du diviseur.
<!--SR:!2024-01-29,57,250-->

### Division par des fonctions linéaires

$$\frac{P(x)}{ax+b}=$$
?
$$Q(x)+\frac{R}{ax+b}$$
- $ax+b$ est le diviseur ($\deg 1$)
- $Q(x)$ est le quotient ($\deg n-1$)
- $R$ est le reste ($\deg 0$)
<!--SR:!2024-01-05,42,250-->

### Division par des fonctions quadratiques

$$\frac{P(x)}{ax^{2}+bx+c}=$$
?
$$Q(x)+\frac{ex+f}{ax^{2}+bx+c}$$
- $ax^{2}+bx+c$ est le diviseur ($\deg 2$)
- $Q(x)$ est le quotient ($\deg n-2$)
- $ex+f$ est le reste ($\deg <2$)
<!--SR:!2024-01-15,47,250-->

### Résolution d'équations polynomiales
- Tout polynôme réel peut être exprimé comme un produit:: de facteurs linéaires réels et de facteurs quadratiques irréductibles réels.
<!--SR:!2024-02-09,63,250-->
- Une quadratique irréductible est une quadratique qui n'a pas de:: racines réelles.
<!--SR:!2024-02-02,59,250-->
- Si $a+bi\,(b\neq0)$ est un zéro d'un polynôme réel, alors son complexe conjugué $a-bi$ est:: également un zéro si les coefficients sont réels.
<!--SR:!2024-01-30,57,250-->
- Tout polynôme réel de degré impair possède:: au moins un zéro réel.
<!--SR:!2023-12-17,15,230-->

## Somme et produit des racines
Soit $P(x)=a_{n}x^{n}+a_{n-1}x^{n-1}+\dots+a_{1}x+a_{0}$, donc la forme factorisée sera dont les racines sont $r_{1}\,,r_{2}\,,\dots\,,r_{n}$::$$P(x)=a_{n}(x-r_{1})(x-r_{2})\dots(x-r_{n})$$
<!--SR:!2024-02-08,64,250-->
- La somme des racines est égale à:: $$r_{1}+r_{2}+\dots+r_{n-1}+r_{n}=-\frac{a_{n-1}}{a_{n}}$$
<!--SR:!2024-01-07,42,250-->
- Le produit des racines est égale à::$$r_{1}\times r_{2}\times\dots\times r_{n-1}\times r_{n}=\frac{(-1)^{n}a_{0}}{a_{n}}$$
<!--SR:!2023-12-18,29,230-->
- La somme de toutes les pairs de racines est égale à::$$\sum r_{i}r_{j}=-\frac{a_{n-2}}{a_{n}}$$
<!--SR:!2024-01-06,41,250-->
- La somme de toutes les triplets de racines est égale à::$$\sum r_{i}r_{j}r_{k}=-\frac{a_{n-3}}{a_{n}}$$
<!--SR:!2024-01-01,33,210-->

## Formules
- $x^{3}-1$=::$(x-1)(x^{2}+x+1)$
<!--SR:!2023-12-25,20,262-->
- $x^{3}+1$=::$(x+1)(x^{2}-x+1)$
<!--SR:!2023-12-17,14,242-->