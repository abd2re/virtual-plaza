---
tags: [math] 
---
Created: 2023-04-28

# Nombres complexes
$\sqrt{-1}$=::$i$
<!--SR:!2024-12-25,414,270-->

$$\LARGE{z=a+bi}$$
- Re($z$) =:: $a$
<!--SR:!2024-11-02,334,250-->
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
<!--SR:!2024-03-15,77,210-->

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
<!--SR:!2024-12-23,366,250-->

$z+z^*$=
?
$$\Large{2a}$$
<!--SR:!2024-06-12,190,230-->

$z-z^{*}$=
?
$$\Large{2bi}$$
<!--SR:!2024-06-20,188,230-->

$zz^{*}$=
?
$$\Large{a^{2}+b^{2}}$$
<!--SR:!2024-01-05,8,150-->

---
$|z|$=
?
$$\Large{\sqrt{a^{2}+b^{2}}}$$
<!--SR:!2024-02-16,87,210-->

$|z|^{2}$=
?
$$\Large{zz^{*}}$$
<!--SR:!2024-01-07,16,150-->

Propriétés des sommes, soustractions, multiplication et division de deux conjuguées:
?
![[image-20230504104418313.png|299]]
<!--SR:!2024-02-08,172,250-->

## Forme polaire

Nombre complexe forme polaire et exponentielle::$$\large{z=r(\cos\theta+i\sin\theta)=re^{i\theta}}$$
<!--SR:!2024-01-29,47,141-->

- $\cos\theta$=::$\frac{a}{|z|}$
<!--SR:!2024-01-26,56,236-->
- $\sin\theta$=::$\frac{b}{|z|}$
<!--SR:!2024-01-12,21,216-->
- $|zw|$=::$|z||w|$
<!--SR:!2024-03-16,98,276-->
- $|\frac{z}{w}|$=::$\frac{|z|}{|w|}$
<!--SR:!2024-02-12,65,236-->
- $zw$=::$|z||w|[\cos(\theta+\alpha)+i\sin(\theta+\alpha)]$
<!--SR:!2024-02-11,57,216-->
- $\frac{z}{w}$=::$\frac{|z|}{|w|}[\cos(\theta-\alpha)+i\sin(\theta-\alpha)]$
<!--SR:!2024-03-20,88,236-->
- $z^{n}$=::$|z|^{n}(\cos n\theta+i\sin n\theta)$
<!--SR:!2024-01-27,53,216-->
- $\theta$=::$\tan^{-1}(\frac{b}{a})$
<!--SR:!2024-03-15,84,236-->
- $z_{k}$=::$\sqrt[n]{|z|}\text{cis}\left(\frac{\theta}{n}+\frac{2k\pi}{n}\right)=\sqrt[n]{|z|}\exp\left(\frac{i(\theta +2k\pi)}{n}\right),\,k=0,1,2,...,n-1$
<!--SR:!2024-01-15,40,196-->
- $(z-w)(z-w^{*})$=::$z^{2}-z\text{Re}(w)+|w|^{2}$
<!--SR:!2024-01-09,17,214-->

## Formules d'Euler (module=1)
Si $|z|=1$ alors $z^{*}$=::$z^{-1}$
<!--SR:!2024-01-26,55,234-->
$e^{i\pi}$=::$-1$
<!--SR:!2024-03-10,81,234-->

- $z^{n}+z^{-n}$=::$2\cos(n\theta)$
<!--SR:!2024-02-17,67,234-->
- $z^{n}-z^{-n}$=::$2i\sin(n\theta)$
<!--SR:!2024-03-08,79,234-->
- $e^{in\theta}+e^{-in\theta}$=::$2\cos(n\theta)$
<!--SR:!2024-03-14,83,234-->
- $e^{in\theta}-e^{-in\theta}$=::$2i\sin(n\theta)$
<!--SR:!2024-02-28,74,234-->


## Fresnel formule complexe
$a\cos\theta+b\sin\theta$=::$\text{Re}[(a-ib)e^{i\theta}]$
<!--SR:!2024-01-06,15,150-->

