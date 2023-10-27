---
tags:
  - math
---
Created: 2023-10-27

# Polynômes
## Théorème des facteurs
- $(x - k)$ est un facteur de $P(x)$ si:: $P(k)= 0$
- $P(k)=0$ si:: $(x-k)$ est un facteur de $P(x)$
- $P(x)$=::$(x-k)\times Q(x)$, où $Q(x)$ est un polynôme qui est un facteur de $P(x)$ 
- $\frac{P(x)}{x-k}$=::$Q(x)$
- Si le facteur linéaire est $(ax-b)=a\left(x-\frac{b}{a}\right)$, alors il faut que:: $P\left(\frac{b}{a}\right)=0$
## Théorème des restes
- Lorsqu'un polynôme quelconque $P(x)$ est divisé par une fonction linéaire quelconque $(x - k)$, la valeur du reste $R$ est donnée par:: $P(k) =R$
- Remarque : lorsque $P(k) =0$, $(x - k)$ est:: un facteur de $P(x)$.
- $P(x)$=::$(x-k)\times Q(x)+R$ où $Q(x)$ est un polynôme
- $\frac{P(x)}{x-k}$=::$Q(x)+\frac{R}{x-k}$ où $R$ est le reste
- Si le facteur linéaire est $(ax-b)=a\left(x-\frac{b}{a}\right)$, alors $P\left(\frac{b}{a}\right)$=::$R$

## Division polynomiale
Formule générale::$$\frac{P(x)}{D(x)}=Q(x)+\frac{R(x)}{D(x)}$$

- Cette méthode n'est généralement utile que lorsque le degré du dénominateur est:: inférieur ou égal au degré du numérateur.

Soit deux polynômes: $P(x)=a_{n}x^{n}+a_{n-1}x^{n-1}+\dots+a_{1}x+a_{0}$ qu'on divise par $D(x)=b_{k}x^{k}+b_{k-1}b^{k-1}+\dots+b_{1}x+b_{0}$ avec $n\geq k$. Les étapes sont:
?
1. Diviser le premier terme du polynôme $P(x)$ par le premier terme du diviseur $D(x)$. $$\frac{a_{n}x^{n}}{b_{k}x^{k}}=q_{m}x^{m}$$
2. Multiplier le diviseur par ce terme. $$D(x)\times q_{m}x^{m}$$
3. Soustraire ce résultat du polynôme d'origine. $$R(x)=P(x)-D(x)\times q_{m}x^{m}$$
4. Répétez les étapes 1 à 3 en utilisant le nouveau polynôme $R(x)$ à la place de $P(x)$ jusqu'à ce que la soustraction aboutisse à une expression pour $R(x)$ dont le degré est inférieur à celui du diviseur.

### Division par des fonctions linéaires

$$\frac{P(x)}{ax+b}=$$
?
$$Q(x)+\frac{R}{ax+b}$$
- $ax+b$ est le diviseur ($\deg 1$)
- $Q(x)$ est le quotient ($\deg n-1$)
- $R$ est le reste ($\deg 0$)

### Division par des fonctions quadratiques

$$\frac{P(x)}{ax^{2}+bx+c}=$$
?
$$Q(x)+\frac{ex+f}{ax^{2}+bx+c}$$
- $ax^{2}+bx+c$ est le diviseur ($\deg 2$)
- $Q(x)$ est le quotient ($\deg n-2$)
- $ex+f$ est le reste ($\deg <2$)
- 