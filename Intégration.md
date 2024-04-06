---
tags:
  - math
---
Created: 2024-01-11

# Intégration
Autre notation de $\int f(x)\,dx$=::$F(x)$
<!--SR:!2024-04-08,33,230-->
Si $g(x)$ = $u$ alors $g'(x)\,dx$=::$u'dx=du$
<!--SR:!2024-05-09,65,227-->
## Identités
### Fondamentales
- $\int a\,dx=$::$ax+C$
<!--SR:!2024-05-24,79,250-->
- $\int x^{n}\,dx=$::$\frac{x^{n+1}}{n+1}+C;\;n\neq-1$
<!--SR:!2024-07-11,108,250-->
- $\int x^{-n}\,dx=\int \frac{1}{x^{n}}\,dx=$::$\frac{x^{1-n}}{1-n}+C;\;n\neq1$
<!--SR:!2024-04-26,25,230-->
- $\int x^{1/n}\,dx=\int \sqrt{x^{n}}\,dx=$::$\frac{nx^{\frac{n+1}{n}}}{n+1}+C;\;n\neq-1$
<!--SR:!2024-04-12,20,190-->
- $\int x^{-1}\,dx=\int \frac{1}{x}\,dx=$::$\ln|x|+C$
<!--SR:!2024-06-16,73,210-->
- $\int a^{x}\,dx=$::$\frac{a^{x}}{\ln(a)}+C$
<!--SR:!2024-04-10,13,130-->
- $\int e^{x}\,dx=$::$e^{x}+C$
<!--SR:!2024-07-10,109,250-->
- $\int \log_{a}(x)\,dx=$::$\frac{x}{\ln a}(\ln x-1)+C$
<!--SR:!2024-04-19,16,130-->
- $\int \ln x\,dx=$::$x(\ln x -1)+C$
<!--SR:!2024-04-12,8,170-->
- $\int \sin x\,dx=$::$-\cos x +C$
<!--SR:!2024-04-14,40,230-->
- $\int \cos x\,dx=$::$\sin x +C$
<!--SR:!2024-04-12,38,230-->
- $\int \sec^{2} x\,dx=$::$\tan x +C$
<!--SR:!2024-06-22,97,250-->

### Opérations
- $\int af(x)\,dx=$::$a\int f(x)\,dx=aF(x)$
<!--SR:!2024-07-29,119,250-->
- $\int f(x)\pm g(x)\,=$::$F(x)\pm G(x)$
<!--SR:!2024-06-14,92,250-->
- $\int f(x)g(x)\,dx=$::$F(x)g(x)-\int F(x)g'(x)\,dx$
<!--SR:!2024-04-29,67,250-->
- $\int f'(x)g(x)\,dx=$::$f(x)g(x)-\int f(x)g'(x)\,dx$
<!--SR:!2024-05-18,60,204-->
- $\int f'(g(x))g'(x)\,dx=$::$\int f'(u)\,du$ avec $u=g(x)$
<!--SR:!2024-06-10,87,244-->
- $\int f(ax+b)\,dx=$::$\frac{1}{a}F(ax+b)$
<!--SR:!2024-05-05,62,241-->

### Intégration définies
- $\int_{a}^{b}f(x)\,dx=$::$[F(x)]_{a}^{b}=F(b)-F(a)$
<!--SR:!2024-05-11,67,243-->
- $[-F(x)]_{a}^{b}$=::$[F(x)]_{b}^{a}$
<!--SR:!2024-04-22,55,243-->
- $\int_{a}^{b}f'(g(x))g'(x)\,dx=$::$\int_{g(a)}^{g(b)}f'(u)\,du$ avec $u=g(x)$
<!--SR:!2024-06-05,84,243-->
- $\int_{a}^{c}f(x)\,dx+\int_{c}^{b}f(x)\,dx=$::$\int_{a}^{b}f(x)\,dx$
<!--SR:!2024-05-30,79,243-->



