---
tags: [physics] 
---
Created: 2022-12-12

# Résistance électrique
?
Tout les matériaux ne conduisent pas le courant électrique de la meme manière, on définit la résistance électrique comme étant la formule::$$R=\frac{\Delta V}{I}$$
<!--SR:!2024-10-14,382,230-->

La résistance d'un fil conducteur a comme formule:
?
$$R=\frac{\rho l}{A}$$
- $R$ est la résistance en Ohm ($\Omega$)
- $\rho$ est la résistivité du matériau en ohm-metre
- $l$ est la longueur du fil
- $A$ est la surface du fil
<!--SR:!2024-04-27,159,210-->

## Loi d'Ohm et conducteur ohmique

Caractéristique intensité-tension du resistor a comme graphe::![[Résistance électrique.png]]
<!--SR:!2024-04-12,154,210-->
- Formule de la loi d'Ohm::$$U=RI$$ car $U$ et $I$ sont proportionnelles.
<!--SR:!2024-01-20,90,210-->

- Loi d'Ohm:: A [[température]] constante la tension et l'intensité aux bornes d'un conducteurs sont proportionnelles
<!--SR:!2023-12-24,210,263-->

<!--SR:!2023-02-11,17,170-->
- Un conducteur ohmique:: est un conducteur qui obéit a la loi d'Ohm ($R$ est constant)![[Résistance électrique-1.png]]
<!--SR:!2024-05-14,313,250-->

## Association de résistors
- Association en série formule::$$R_{eqs}=R_1+R_2+\text{...}$$ l'association en série de plusieurs résistors est équivalent a un résistor $R_{eqs}$ dont la résistance est égale a la somme des résistances
<!--SR:!2025-02-28,476,242-->
- Association en parallèle formule::$$\frac{1}{R_{eqp}}=\frac{1}{R_{1}}+\frac{1}{R_{2}}+\text{...}$$ $$R_{eqp}=\frac{R_{1}R_{2}}{R_{1}+R_{2}}$$
<!--SR:!2023-12-17,83,221-->

## Dissipation d'énergie électrique dans un resistor (effet joule)
?
Lorsque qu'un conducteur est parcouru par un courant électrique il y a un dégagement de [[chaleur]]: c'est l'effet joule. 
Pour lutter contre l'effet joule on prévoit des dispositifs d'aération ou de ventilation. L'effet joule est utilisé avantageusement dans les plaques chauffantes, les fusibles, les chauffe-eau.
<!--SR:!2023-12-09,199,222-->

La puissance dissipé par effet joule est proportionnelle:: au carré de l'intensité.
<!--SR:!2024-02-18,116,182-->

3 formules de puissance dissipé::$$P=UI=RI^2=\frac{U^{2}}{R}$$
<!--SR:!2025-03-05,478,242-->

## Utilisation des appareils de mesure
Un appareil de mesure modifie le circuit et a un effet sur la mesure. 

- Utilisation d'un ampèremètre: un ampèremètre idéal:: a une résistance interne nulle
<!--SR:!2023-12-20,207,263-->

<!--SR:!2023-03-31,65,242-->
- Utilisation d'un voltmètre: un voltmètre idéal:: a une résistance interne infinie
<!--SR:!2024-03-15,104,222-->

## Diviseur de tension et montage potentiométrique
Formule et circuit
?
![[image-20221220093220947.png]]
$$U=(R_{1}+R_{2})\times I$$
donc
$$I=\frac{U}{R_{1}+R_{2}}$$
On sait que
$$U_{1}=R_{1}\times I$$
donc
$$U_{1}=R_{1}\times \frac{U}{R_{1}+R_{2}}=\boxed{\frac{R_1}{R_{1}+R_{2}}\times U}$$
<!--SR:!2023-12-25,84,220-->

## Montage potentiométrique
Un potentiomètre est:: un conducteur ohmique ayant trois bornes, deux bornes fixe A et B et une borne mobile C appelé curseur. Si l'on branche le potentiomètre par les deux bornes fixes A et B, ce dernier se comporte comme une résistance fixe. ![[image-20230116161558430.png|400]]
<!--SR:!2024-01-05,36,223-->

<!--SR:!2023-02-03,9,198-->

### Rhéostat
Le rhéostat est:: un potentiomètre branché avec les bornes A et C ou C et B. Le montage rheostat serre a faire varier l'intensité dans un circuit car la résistance varie selon la position du curseur.![[image-20230116161818037.png|275]]
<!--SR:!2024-05-09,172,243-->


**Montage potentiométrique** branchement, formule de base et formules pour les 3 cas:
?
![[image-20230116164137567.png|450]]$$U_{AC}=\frac{R_{AC}}{R_{AC}+R_{CB}}U_{AB}=\frac{R_{AC}}{R_{AB}} \hspace2mm U_{AB}$$
- si C est en A $$R_{AC}=R_{AA}=0,\;U_{AC}=0$$
- si C est en B $$R_{AC}=R_{AB},\;U_{AC}=\frac{R_{AB}}{R_{AB}}U_{AB}=U_{AB}$$
- si C est entre A et B $$0<U_{S}<U_{AB}$$
<!--SR:!2023-12-27,70,178-->











