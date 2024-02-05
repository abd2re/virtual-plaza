---
tags:
  - math
---
Created: 2023-11-28

# Nombre dérivée
- $f'(a)$=::$$\lim_{h\rightarrow 0}\frac{f(a+h)-f(a)}{h}$$
<!--SR:!2024-02-11,40,230-->
- Autre notation de $f'(x)$::$\frac{dy}{dx}$
<!--SR:!2024-02-20,51,250-->
- Autre notation de $f''(x)$::$\frac{d^{2}y}{dx^{2}}$
<!--SR:!2024-02-10,25,185-->

Tangente et normale pour une fonction représente:
?
![[image-20231128163111952.png|500]]
<!--SR:!2024-02-18,51,250-->

- Formule de la tangente $T:y$=:: $f'(a)(x-a)+f(a)$
<!--SR:!2024-04-14,75,230-->
- Formule de la normale $N:y$=:: $\frac{-1}{f'(a)}(x-a)+f(a)$
<!--SR:!2024-02-07,38,230-->


## Identités
### Fondamentales
- $f(x)=c\rightarrow f'(x)=$::$0$
<!--SR:!2024-05-10,97,250-->
- $f(x)=x^{n}\rightarrow f'(x)=$::$nx^{n-1}$
<!--SR:!2024-03-08,62,250-->
- $f(x)=x^{-n}=\frac{1}{x^{n}}\rightarrow f'(x)=$::$\frac{-n}{x^{n+1}}$
<!--SR:!2024-04-11,69,225-->
- $f(x)=x^{1/n}=\sqrt[n]{x}\rightarrow f'(x)=$::$\frac{\sqrt[n]{x^{1-n}}}{n}$
<!--SR:!2024-03-06,44,225-->
- $f(x)=a^{x}\rightarrow f'(x)=$::$\ln(a)a^{x}$
<!--SR:!2024-02-16,33,190-->
- $f(x)=e^{x}\rightarrow f'(x)=$::$e^{x}$
<!--SR:!2024-03-03,59,250-->
- $f(x)=\log_{a}(x)\rightarrow f'(x)=$::$\frac{1}{\ln(a)x}$
<!--SR:!2024-02-07,3,130-->
- $f(x)=\ln(x)\rightarrow f'(x)=$::$\frac{1}{x}$
<!--SR:!2024-05-13,99,250-->
- $f(x)=\sin(x)\rightarrow f'(x)=$::$\cos(x)$
<!--SR:!2024-05-14,102,250-->
- $f(x)=\cos(x)\rightarrow f'(x)=$::$-\sin(x)$
<!--SR:!2024-03-01,57,250-->
- $f(x)=\tan(x)\rightarrow f'(x)=$::$\sec^{2}(x)$
<!--SR:!2024-05-07,96,250-->
- $f(x)=\sec(x)\rightarrow f'(x)=$::$\sec(x)\tan(x)$
<!--SR:!2024-02-10,8,177-->
- $f(x)=\csc(x)\rightarrow f'(x)=$::$-\csc(x)\cot(x)$
<!--SR:!2024-02-06,3,157-->
- $f(x)=\cot(x)\rightarrow f'(x)=$::$-\csc^{2}(x)$
<!--SR:!2024-02-06,2,137-->
- $f(x)=\sin^{-1}(\frac{x}{a})\rightarrow f'(x)=$::$\frac{1}{\sqrt{a-x^{2}}}$
<!--SR:!2024-02-14,13,237-->
- $f(x)=\cos^{-1}(\frac{x}{a})\rightarrow f'(x)=$::$\frac{-1}{\sqrt{a-x^{2}}}$
<!--SR:!2024-02-15,14,237-->
- $f(x)=\tan^{-1}(x)\rightarrow f'(x)=$::$\frac{1}{1+x^{2}}$
<!--SR:!2024-02-16,15,237-->
### Opérations
- $g(x)=c\cdot f(x)\rightarrow g'(x)=$::$c\cdot f'(x)$
<!--SR:!2024-05-08,97,250-->
- $h(x)=f(x)\pm g(x)\rightarrow h'(x)=$::$f'(x)\pm g'(x)$
<!--SR:!2024-02-05,41,250-->
- $h(x)=f(x)g(x)\rightarrow h'(x)=$::$f'(x)g(x)+f(x)g'(x)$
<!--SR:!2024-05-03,94,250-->
- $h(x)=\frac{f(x)}{g(x)}\rightarrow h'(x)=$::$\frac{f'(x)g(x)-f(x)g'(x)}{g(x)^{2}}$
<!--SR:!2024-02-10,40,230-->
- $h(x)=f(g(x))\rightarrow h'(x)=$::$f'(g(x))g'(x)$
<!--SR:!2024-03-10,56,230-->

### Première et seconde dérivée
- Si $f'(x)=0$ alors ce point est:: un extremum local
<!--SR:!2024-03-21,56,240-->
- Si $f''(x)=0$ alors ce point est:: un point d'inflextion
<!--SR:!2024-02-17,37,240-->
- Si $f'(x)=0$ et $f''(x)<0$ alors ce point est:: un maximum local
<!--SR:!2024-03-01,42,240-->
- Si $f'(x)=0$ et $f''(x)>0$ alors ce point est:: un minimum local
<!--SR:!2024-02-13,36,240-->
- $f$ est concave haut si $f''(x)$::$>0$
<!--SR:!2024-02-09,16,199-->
- $f$ est concave bas si $f''(x)$::$<0$
<!--SR:!2024-02-22,30,239-->

## Dérivation implicite
$\frac{df(y)}{dx}=$::$\frac{df(y)}{dy}\cdot \frac{dy}{dx}=f'(y)\frac{dy}{dx}$
<!--SR:!2024-02-09,10,237-->
$\frac{d}{dx}(f(x)g(y))=$::$g(y)\frac{df(x)}{dx}+f(x)\frac{dg(y)}{dx}=g(y)f'(x)+f(x)g'(y)\frac{dy}{dx}$
<!--SR:!2024-02-14,14,237-->

Si on a $f(x,\,y)$ et on veut $\frac{dy}{dx}$ alors les étapes sont :
?
- Appliquer $\frac{d}{dx}$ pour chaque terme
- Appliquer la règle en chaîne pour les termes avec une variable $y$ pour obtenir $\frac{dy}{dx}$ en facteur
- Factoriser par $\frac{dy}{dx}$ et l'isoler
ou
- Appliquer la dérivée pour chaque terme
- Factoriser par $dy$ et $dx$
- Diviser $dy$ par $dx$
<!--SR:!2024-02-13,12,237-->

$df(x)=$::$f'(x)dx$
<!--SR:!2024-02-10,11,237-->

$\frac{d(xy)}{dx}=$::$y+x\frac{dy}{dx}$
<!--SR:!2024-02-08,5,231-->


