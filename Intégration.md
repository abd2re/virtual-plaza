---
tags:
  - math
---
Created: 2024-01-11

# Intégration
Autre notation de $\int f(x)\,dx$=::$F(x)$
<!--SR:!2024-03-06,14,230-->
Si $g(x)$ = $u$ alors $g'(x)\,dx$=::$u'dx=du$
<!--SR:!2024-03-05,29,227-->
## Identités
### Fondamentales
- $\int a\,dx=$::$ax+C$
<!--SR:!2024-03-06,31,250-->
- $\int x^{n}\,dx=$::$\frac{x^{n+1}}{n+1}+C;\;n\neq-1$
<!--SR:!2024-03-25,44,250-->
- $\int x^{-n}\,dx=\int \frac{1}{x^{n}}\,dx=$::$\frac{x^{1-n}}{1-n}+C;\;n\neq1$
<!--SR:!2024-04-01,49,250-->
- $\int x^{1/n}\,dx=\int \sqrt{x^{n}}\,dx=$::$\frac{nx^{\frac{n+1}{n}}}{n+1}+C;\;n\neq-1$
<!--SR:!2024-03-05,6,210-->
- $\int x^{-1}\,dx=\int \frac{1}{x}\,dx=$::$\ln|x|+C$
<!--SR:!2024-04-04,35,210-->
- $\int a^{x}\,dx=$::$\frac{a^{x}}{\ln(a)}+C$
<!--SR:!2024-03-09,7,130-->
- $\int e^{x}\,dx=$::$e^{x}+C$
<!--SR:!2024-03-23,44,250-->
- $\int \log_{a}(x)\,dx=$::$\frac{x}{\ln a}(\ln x-1)+C$
<!--SR:!2024-03-10,9,130-->
- $\int \ln x\,dx=$::$x(\ln x -1)+C$
<!--SR:!2024-03-08,6,190-->
- $\int \sin x\,dx=$::$-\cos x +C$
<!--SR:!2024-03-05,18,230-->
- $\int \cos x\,dx=$::$\sin x +C$
<!--SR:!2024-03-05,17,230-->
- $\int \sec^{2} x\,dx=$::$\tan x +C$
<!--SR:!2024-03-17,39,250-->

### Opérations
- $\int af(x)\,dx=$::$a\int f(x)\,dx=aF(x)$
<!--SR:!2024-04-01,48,250-->
- $\int f(x)\pm g(x)\,=$::$F(x)\pm G(x)$
<!--SR:!2024-03-14,37,250-->
- $\int f(x)g(x)\,dx=$::$F(x)g(x)-\int F(x)g'(x)\,dx$
<!--SR:!2024-04-29,67,250-->
- $\int f'(x)g(x)\,dx=$::$f(x)g(x)-\int f(x)g'(x)\,dx$
<!--SR:!2024-03-19,30,204-->
- $\int f'(g(x))g'(x)\,dx=$::$\int f'(u)\,du$ avec $u=g(x)$
<!--SR:!2024-03-15,36,244-->
- $\int f(ax+b)\,dx=$::$\frac{1}{a}F(ax+b)$
<!--SR:!2024-03-04,26,241-->

### Intégration définies
- $\int_{a}^{b}f(x)\,dx=$::$[F(x)]_{a}^{b}=F(b)-F(a)$
<!--SR:!2024-03-05,28,243-->
- $[-F(x)]_{a}^{b}$=::$[F(x)]_{b}^{a}$
<!--SR:!2024-04-22,55,243-->
- $\int_{a}^{b}f'(g(x))g'(x)\,dx=$::$\int_{g(a)}^{g(b)}f'(u)\,du$ avec $u=g(x)$
<!--SR:!2024-03-13,35,243-->
- $\int_{a}^{c}f(x)\,dx+\int_{c}^{b}f(x)\,dx=$::$\int_{a}^{b}f(x)\,dx$
<!--SR:!2024-03-12,33,243-->



