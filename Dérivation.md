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
<!--SR:!2024-01-30,33,230-->
- Formule de la normale $N:y$=:: $\frac{-1}{f'(a)}(x-a)+f(a)$
<!--SR:!2024-02-07,38,230-->


## Identités
### Fondamentales
- $f(x)=c\rightarrow f'(x)=$::$0$
<!--SR:!2024-02-03,39,250-->
- $f(x)=x^{n}\rightarrow f'(x)=$::$nx^{n-1}$
<!--SR:!2024-03-08,62,250-->
- $f(x)=x^{-n}=\frac{1}{x^{n}}\rightarrow f'(x)=$::$\frac{-n}{x^{n+1}}$
<!--SR:!2024-02-02,31,225-->
- $f(x)=x^{1/n}=\sqrt[n]{x}\rightarrow f'(x)=$::$\frac{\sqrt[n]{x^{1-n}}}{n}$
<!--SR:!2024-01-22,19,225-->
- $f(x)=a^{x}\rightarrow f'(x)=$::$\ln(a)a^{x}$
<!--SR:!2024-02-16,33,190-->
- $f(x)=e^{x}\rightarrow f'(x)=$::$e^{x}$
<!--SR:!2024-03-03,59,250-->
- $f(x)=\log_{a}(x)\rightarrow f'(x)=$::$\frac{1}{\ln(a)x}$
<!--SR:!2024-01-29,12,170-->
- $f(x)=\ln(x)\rightarrow f'(x)=$::$\frac{1}{x}$
<!--SR:!2024-02-04,40,250-->
- $f(x)=\sin(x)\rightarrow f'(x)=$::$\cos(x)$
<!--SR:!2024-02-02,41,250-->
- $f(x)=\cos(x)\rightarrow f'(x)=$::$-\sin(x)$
<!--SR:!2024-03-01,57,250-->
- $f(x)=\tan(x)\rightarrow f'(x)=$::$\sec^{2}(x)$
<!--SR:!2024-02-01,39,250-->

### Opérations
- $g(x)=c\cdot f(x)\rightarrow g'(x)=$::$c\cdot f'(x)$
<!--SR:!2024-02-01,39,250-->
- $h(x)=f(x)\pm g(x)\rightarrow h'(x)=$::$f'(x)\pm g'(x)$
<!--SR:!2024-02-05,41,250-->
- $h(x)=f(x)g(x)\rightarrow h'(x)=$::$f'(x)g(x)+f(x)g'(x)$
<!--SR:!2024-01-30,38,250-->
- $h(x)=\frac{f(x)}{g(x)}\rightarrow h'(x)=$::$\frac{f'(x)g(x)-f(x)g'(x)}{g(x)^{2}}$
<!--SR:!2024-02-10,40,230-->
- $h(x)=f(g(x))\rightarrow h'(x)=$::$f'(g(x))g'(x)$
<!--SR:!2024-03-10,56,230-->

### Première et seconde dérivée
- Si $f'(x)=0$ alors ce point est:: un extremum local
<!--SR:!2024-01-25,23,240-->
- Si $f''(x)=0$ alors ce point est:: un point d'inflextion
<!--SR:!2024-02-17,37,240-->
- Si $f'(x)=0$ et $f''(x)<0$ alors ce point est:: un maximum local
<!--SR:!2024-03-01,42,240-->
- Si $f'(x)=0$ et $f''(x)>0$ alors ce point est:: un minimum local
<!--SR:!2024-02-13,36,240-->
- $f$ est concave haut si $f''(x)$::$>0$
<!--SR:!2024-01-24,9,199-->
- $f$ est concave bas si $f''(x)$::$<0$
<!--SR:!2024-01-23,13,239-->