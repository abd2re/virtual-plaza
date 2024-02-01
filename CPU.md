---
tags: [computer_science] 
---
Created: 2023-01-06

# CPU
?
L'unité centrale de traitement (CPU) est un composant matériel d'un système informatique et peut effectuer des opérations arithmétiques, logiques ou d'entrée/sortie de base, afin de transformer les données provenant des dispositifs d'entrée en informations utiles.
Le CPU peut également être appelé processeur ou puce.
<!--SR:!2024-02-19,19,130-->

*C'est quoi le role du CPU ?*
?
L'unité centrale fonctionne dans la phase de traitement du modèle entrée, traitement, sortie et stockage.
Son rôle est de récupérer, de décoder et d'exécuter des instructions de programme depuis et vers la mémoire principale (RAM).
<!--SR:!2024-05-14,142,190-->

## Elements du CPU et représentation (avec RAM/IO)
?
1. l'[[Unité de contrôle]] / Control Unit (UC)
2. l'[[Unité arithmétique et logique]] / Arithmetic Logic Unit (ALU)
3. le [[Registre d'adresses mémoire]] / Memory Address Register (MAR)
4. le registre de données mémoire / Memory Data Register (MDR)
![[CPU-7.png]]
![[CPU-8.png]]
![[CPU-9.png]]
<!--SR:!2024-03-11,63,205-->




Le "machine cycle" dans le CPU:
?
![[CPU.png]]
<!--SR:!2024-02-10,228,230-->


## Registres
?
La seule fonction de MAR est de contenir l'adresse RAM de l'instruction que le CPU doit exécuter. 
<!--SR:!2024-05-18,300,250-->

Il existe de nombreux registres, mais les trois plus importants sont les suivants:
?
- Registre d'adresses mémoire(MAR)
- Registre des données en mémoire (MDR)
- Accumulateur
<!--SR:!2024-02-14,142,230-->