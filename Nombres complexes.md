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
<!--SR:!2025-03-02,407,250-->

---
$(a+bi)(c+di)$=
?
$$\Large{(ac-bd)+i(ad+bc)}$$
<!--SR:!2024-12-23,312,230-->

$(a+bi)^{2}$=
?
$$\Large{a^{2}-b^{2}+i2ab}$$
<!--SR:!2024-08-23,161,210-->

$(a-bi)^{2}$=
?
$$\Large{a^{2}-b^{2}-i2ab}$$
<!--SR:!2024-04-10,65,210-->

$(a+ib)(a-ib)$=
?
$$\Large{a^{2}+b^{2}}$$
<!--SR:!2024-05-02,88,230-->

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
<!--SR:!2024-04-25,48,150-->

---
$|z|$=
?
$$\Large{\sqrt{a^{2}+b^{2}}}$$
<!--SR:!2024-08-16,182,210-->

$|z|^{2}$=
?
$$\Large{zz^{*}}$$
<!--SR:!2024-04-07,13,130-->

Propriétés des sommes, soustractions, multiplication et division de deux conjuguées:
?
![[image-20230504104418313.png|299]]
<!--SR:!2025-04-12,429,250-->

Argument d'une multiplication/division de deux nombre complexes, argument d'un conjuguée, et argument d'un complexe divisé par un conjugué:
?
![[image-20240315061211047.png]]
<!--SR:!2024-04-13,14,220-->


## Forme polaire

Nombre complexe forme polaire et exponentielle::$$\large{z=r(\cos\theta+i\sin\theta)=re^{i\theta}}$$
<!--SR:!2024-07-07,93,141-->

- $\cos\theta$=::$\frac{a}{|z|}$
<!--SR:!2024-06-05,131,236-->
- $\sin\theta$=::$\frac{b}{|z|}$
<!--SR:!2024-05-31,96,216-->
- $|zw|$=::$|z||w|$
<!--SR:!2024-12-10,269,276-->
- $|\frac{z}{w}|$=::$\frac{|z|}{|w|}$
<!--SR:!2024-07-11,150,236-->
- $zw$=::$|z||w|[\cos(\theta+\alpha)+i\sin(\theta+\alpha)]$
<!--SR:!2024-04-16,23,176-->
- $\frac{z}{w}$=::$\frac{|z|}{|w|}[\cos(\theta-\alpha)+i\sin(\theta-\alpha)]$
<!--SR:!2024-10-13,207,236-->
- $z^{n}$=::$|z|^{n}(\cos n\theta+i\sin n\theta)$
<!--SR:!2024-05-16,43,176-->
- $\theta$=::$\tan^{-1}(\frac{b}{a})$
<!--SR:!2024-04-25,41,216-->
- $z_{k}$=::$\sqrt[n]{|z|}\text{cis}\left(\frac{\theta}{n}+\frac{2k\pi}{n}\right)=\sqrt[n]{|z|}\exp\left(\frac{i(\theta +2k\pi)}{n}\right),\,k=0,1,2,...,n-1$
<!--SR:!2024-04-12,11,130-->
- $z+z^{*}=$::$2\text{Re}(z)$
<!--SR:!2024-04-27,21,220-->
- $z-z^{*}=$::$2\text{Im}(z)$
<!--SR:!2024-04-18,12,180-->
- $(z-w)(z-w^{*})$=::$z^{2}-2z\text{Re}(w)+|w|^{2}$
<!--SR:!2024-05-09,49,174-->

## Formules d'Euler (module=1)
Si $|z|=1$ alors $z^{*}$=::$z^{-1}$
<!--SR:!2024-06-02,128,234-->
$e^{i\pi}$=::$-1$
<!--SR:!2024-09-15,189,234-->

- $z^{n}+z^{-n}$=::$2\cos(n\theta)$
<!--SR:!2024-07-20,154,234-->
- $z^{n}-z^{-n}$=::$2i\sin(n\theta)$
<!--SR:!2024-09-08,184,234-->
- $e^{in\theta}+e^{-in\theta}$=::$2\cos(n\theta)$
<!--SR:!2024-09-23,193,234-->
- $e^{in\theta}-e^{-in\theta}$=::$2i\sin(n\theta)$
<!--SR:!2024-08-18,172,234-->


## Fresnel formule complexe
$a\cos\theta+b\sin\theta$=::$\text{Re}[(a-ib)e^{i\theta}]$
<!--SR:!2024-04-11,10,130-->

