---
tags:
  - math
---
Created: 2023-11-28

# Nombre dérivée
- $f'(a)$=::$$\lim_{h\rightarrow 0}\frac{f(a+h)-f(a)}{h}$$
<!--SR:!2023-12-15,9,230-->
- Autre notation de $f'(x)$::$\frac{dy}{dx}$
<!--SR:!2023-12-10,8,250-->
- Autre notation de $f''(x)$::$\frac{d^{2}y}{dx^{2}}$
<!--SR:!2023-12-08,2,245-->

Tangente et normale pour une fonction représente:
?
![[image-20231128163111952.png|500]]
<!--SR:!2023-12-09,7,250-->

- Formule de la tangente $T:y$=:: $f'(a)(x-a)+f(a)$
<!--SR:!2023-12-13,7,230-->
- Formule de la normale $N:y$=:: $\frac{-1}{f'(a)}(x-a)+f(a)$
<!--SR:!2023-12-14,8,230-->


## Identités
### Fondamentales
- $f(x)=c\rightarrow f'(x)=$::$0$
<!--SR:!2023-12-09,7,250-->
- $g(x)=c\cdot f(x)\rightarrow g'(x)=$::$c\cdot f'(x)$
<!--SR:!2023-12-08,6,250-->
- $f(x)=x^{n}\rightarrow f'(x)=$::$nx^{n-1}$
<!--SR:!2023-12-12,10,250-->
- $f(x)=x^{-n}=\frac{1}{x^{n}}\rightarrow f'(x)=$::$\frac{-n}{x^{n+1}}$
<!--SR:!2023-12-11,6,245-->
- $f(x)=x^{1/n}=\sqrt[n]{x}\rightarrow f'(x)=$::$\frac{\sqrt[n]{x^{1-n}}}{n}$
<!--SR:!2023-12-11,6,245-->
- $f(x)=a^{x}\rightarrow f'(x)=$::$\ln(a)a^{x}$
<!--SR:!2023-12-10,6,230-->
- $f(x)=e^{x}\rightarrow f'(x)=$::$e^{x}$
<!--SR:!2023-12-11,9,250-->
- $f(x)=\log_{a}(x)\rightarrow f'(x)=$::$\frac{1}{\ln(a)x}$
<!--SR:!2023-12-09,5,230-->
- $f(x)=\ln(x)\rightarrow f'(x)=$::$\frac{1}{x}$
<!--SR:!2023-12-09,7,250-->
- $f(x)=\sin(x)\rightarrow f'(x)=$::$\cos(x)$
<!--SR:!2023-12-08,6,250-->
- $f(x)=\cos(x)\rightarrow f'(x)=$::$-\sin(x)$
<!--SR:!2023-12-12,10,250-->
- $f(x)=\tan(x)\rightarrow f'(x)=$::$\sec^{2}(x)$
<!--SR:!2023-12-08,6,250-->

### Opérations
- $h(x)=f(x)\pm g(x)\rightarrow h'(x)=$::$f'(x)\pm g'(x)$
<!--SR:!2023-12-09,7,250-->
- $h(x)=f(x)g(x)\rightarrow h'(x)=$::$f'(x)g(x)+f(x)g'(x)$
<!--SR:!2023-12-08,6,250-->
- $h(x)=\frac{f(x)}{g(x)}\rightarrow h'(x)=$::$\frac{f'(x)g(x)-f(x)g'(x)}{g(x)^{2}}$
<!--SR:!2023-12-14,8,230-->
- $h(x)=f(g(x))\rightarrow h'(x)=$::$f'(g(x))g'(x)$
<!--SR:!2023-12-09,5,230-->

