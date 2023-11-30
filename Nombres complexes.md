---
tags: [math] 
---
Created: 2023-04-28

# Nombres complexes
$\sqrt{-1}$=::$i$
<!--SR:!2024-12-25,414,270-->

$$\LARGE{z=a+bi}$$
- Re($z$) =:: $a$
<!--SR:!2023-12-04,134,250-->
- Im($z$) =:: $b$
<!--SR:!2024-01-20,163,250-->

--- 
$(a+bi)(c+di)$=
?
$$\Large{(ac-bd)+i(ad+bc)}$$
<!--SR:!2024-02-15,136,230-->

$(a+bi)^{2}$=
?
$$\Large{a^{2}-b^{2}+i2ab}$$
<!--SR:!2023-12-29,37,210-->

$(a-bi)^{2}$=
?
$$\Large{a^{2}-b^{2}-i2ab}$$
<!--SR:!2024-02-05,131,230-->

$(a+ib)(a-ib)$=
?
$$\Large{a^{2}+b^{2}}$$
<!--SR:!2024-02-04,173,250-->

---

$z^{*}$=
?
$$\Large{a-ib}$$
<!--SR:!2023-12-23,146,250-->

$z+z^*$=
?
$$\Large{2a}$$
<!--SR:!2023-12-05,83,230-->

$z-z^{*}$=
?
$$\Large{2bi}$$
<!--SR:!2023-12-15,82,230-->

$zz^{*}$=
?
$$\Large{a^{2}+b^{2}}$$
<!--SR:!2023-12-13,15,190-->

---
$|z|$=
?
$$\Large{\sqrt{a^{2}+b^{2}}}$$
<!--SR:!2024-02-16,87,210-->

$|z|^{2}$=
?
$$\Large{zz^{*}}$$
<!--SR:!2023-12-22,29,170-->

Propriétés des sommes, soustractions, multiplication et division de deux conjuguées:
?
![[image-20230504104418313.png|299]]
<!--SR:!2024-02-08,172,250-->

## Forme polaire

Nombre complexe forme polaire et exponentielle::$$\large{z=r(\cos\theta+i\sin\theta)=re^{i\theta}}$$
<!--SR:!2023-12-13,31,141-->

- $\cos\theta$=::$\frac{a}{|z|}$
<!--SR:!2023-12-01,24,236-->
- $\sin\theta$=::$\frac{b}{|z|}$
<!--SR:!2023-12-22,37,236-->
- $|zw|$=::$|z||w|$
<!--SR:!2023-12-09,36,276-->
- $|\frac{z}{w}|$=::$\frac{|z|}{|w|}$
<!--SR:!2023-12-09,28,236-->
- $zw$=::$|z||w|[\cos(\theta+\alpha)+i\sin(\theta+\alpha)]$
<!--SR:!2023-12-16,27,216-->
- $\frac{z}{w}$=::$\frac{|z|}{|w|}[\cos(\theta-\alpha)+i\sin(\theta-\alpha)]$
<!--SR:!2023-12-23,37,236-->
- $z^{n}$=::$|z|^{n}(\cos n\theta+i\sin n\theta)$
<!--SR:!2023-12-05,25,216-->
- $\theta$=::$\tan^{-1}(\frac{b}{a})$
<!--SR:!2023-12-22,36,236-->
- $z_{k}$=::$\sqrt[n]{|z|}\text{cis}\left(\frac{\theta}{n}+\frac{2k\pi}{n}\right)=\sqrt[n]{|z|}\exp\left(\frac{i(\theta +2k\pi)}{n}\right),\,k=0,1,2,...,n-1$
<!--SR:!2023-12-06,21,196-->
- $(z-w)(z-w^{*})$=::$z^{2}-z\text{Re}(w)+|w|^{2}$
<!--SR:!2023-12-23,36,234-->

## Formules d'Euler (module=1)
Si $|z|=1$ alors $z^{*}$=::$z^{-1}$
<!--SR:!2023-12-02,24,234-->
$e^{i\pi}$=::$-1$
<!--SR:!2023-12-20,35,234-->

- $z^{n}+z^{-n}$=::$2\cos(n\theta)$
<!--SR:!2023-12-12,29,234-->
- $z^{n}-z^{-n}$=::$2i\sin(n\theta)$
<!--SR:!2023-12-20,34,234-->
- $e^{in\theta}+e^{-in\theta}$=::$2\cos(n\theta)$
<!--SR:!2023-12-22,35,234-->
- $e^{in\theta}-e^{-in\theta}$=::$2i\sin(n\theta)$
<!--SR:!2023-12-16,32,234-->


## Fresnel formule complexe
$a\cos\theta+b\sin\theta$=::$\text{Re}[(a-ib)e^{i\theta}]$
<!--SR:!2023-12-05,5,150-->

