---
tags:
  - math
---
Created: 2023-11-28

# Nombre dérivée
- $f'(a)$=::$$\lim_{h\rightarrow 0}\frac{f(a+h)-f(a)}{h}$$
<!--SR:!2024-01-02,18,230-->
- Autre notation de $f'(x)$::$\frac{dy}{dx}$
<!--SR:!2023-12-31,21,250-->
- Autre notation de $f''(x)$::$\frac{d^{2}y}{dx^{2}}$
<!--SR:!2023-12-22,2,185-->

Tangente et normale pour une fonction représente:
?
![[image-20231128163111952.png|500]]
<!--SR:!2023-12-29,20,250-->

- Formule de la tangente $T:y$=:: $f'(a)(x-a)+f(a)$
<!--SR:!2023-12-28,15,230-->
- Formule de la normale $N:y$=:: $\frac{-1}{f'(a)}(x-a)+f(a)$
<!--SR:!2023-12-31,17,230-->


## Identités
### Fondamentales
- $f(x)=c\rightarrow f'(x)=$::$0$
<!--SR:!2023-12-26,17,250-->
- $g(x)=c\cdot f(x)\rightarrow g'(x)=$::$c\cdot f'(x)$
<!--SR:!2023-12-24,16,250-->
- $f(x)=x^{n}\rightarrow f'(x)=$::$nx^{n-1}$
<!--SR:!2024-01-06,25,250-->
- $f(x)=x^{-n}=\frac{1}{x^{n}}\rightarrow f'(x)=$::$\frac{-n}{x^{n+1}}$
<!--SR:!2024-01-02,13,225-->
- $f(x)=x^{1/n}=\sqrt[n]{x}\rightarrow f'(x)=$::$\frac{\sqrt[n]{x^{1-n}}}{n}$
<!--SR:!2023-12-25,14,245-->
- $f(x)=a^{x}\rightarrow f'(x)=$::$\ln(a)a^{x}$
<!--SR:!2023-12-28,9,190-->
- $f(x)=e^{x}\rightarrow f'(x)=$::$e^{x}$
<!--SR:!2024-01-04,24,250-->
- $f(x)=\log_{a}(x)\rightarrow f'(x)=$::$\frac{1}{\ln(a)x}$
<!--SR:!2023-12-28,10,190-->
- $f(x)=\ln(x)\rightarrow f'(x)=$::$\frac{1}{x}$
<!--SR:!2023-12-26,17,250-->
- $f(x)=\sin(x)\rightarrow f'(x)=$::$\cos(x)$
<!--SR:!2023-12-23,15,250-->
- $f(x)=\cos(x)\rightarrow f'(x)=$::$-\sin(x)$
<!--SR:!2024-01-04,23,250-->
- $f(x)=\tan(x)\rightarrow f'(x)=$::$\sec^{2}(x)$
<!--SR:!2023-12-24,16,250-->

### Opérations
- $h(x)=f(x)\pm g(x)\rightarrow h'(x)=$::$f'(x)\pm g'(x)$
<!--SR:!2023-12-26,17,250-->
- $h(x)=f(x)g(x)\rightarrow h'(x)=$::$f'(x)g(x)+f(x)g'(x)$
<!--SR:!2023-12-23,15,250-->
- $h(x)=\frac{f(x)}{g(x)}\rightarrow h'(x)=$::$\frac{f'(x)g(x)-f(x)g'(x)}{g(x)^{2}}$
<!--SR:!2024-01-01,18,230-->
- $h(x)=f(g(x))\rightarrow h'(x)=$::$f'(g(x))g'(x)$
<!--SR:!2024-01-14,25,230-->

### Première et seconde dérivée
- Si $f'(x)=0$ alors ce point est:: un extremum local
<!--SR:!2023-12-24,4,240-->
- Si $f''(x)=0$ alors ce point est:: un point d'inflextion
<!--SR:!2023-12-26,6,240-->
- Si $f'(x)=0$ et $f''(x)<0$ alors ce point est:: un maximum local
<!--SR:!2023-12-24,4,240-->
- Si $f'(x)=0$ et $f''(x)>0$ alors ce point est:: un minimum local
<!--SR:!2023-12-25,5,240-->