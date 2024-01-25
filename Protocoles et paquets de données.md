---
tags: [computer_science] 
---
Created: 2023-03-22

# Protocoles et paquets de données

Définition de protocole:
?
**Ensemble de règles pour la communication de données sur un réseau.** Un protocole définit le format et l'ordre des messages échangés entre deux ou plusieurs entités communicantes, ainsi que les actions entreprises lors de la transmission et/ou de la réception d'un message ou d'un autre événement.
- Un protocole reconnu comme la norme pour un type de transfert spécifique est appelé protocole standard. *Exemple : le protocole TCP/IP*
<!--SR:!2024-07-09,170,204-->

Définition de paquet de donnée:
?
**Petite unité de données utilisée dans la communication en réseau.** Un paquet est une unité de base de la communication sur un réseau numérique. *Un paquet est également appelé datagramme, segment, bloc, cellule ou trame, selon le protocole utilisé pour la transmission des données.*
- Un paquet est également appelé datagramme, segment, bloc, cellule ou trame, selon le protocole utilisé pour la transmission des données.
- Lorsque des données doivent être transmises, elles sont décomposées en structures de données similaires avant la transmission (les paquets) qui sont réassemblées en morceaux de données d'origine une fois qu'elles atteignent leur destination.
<!--SR:!2024-03-27,193,210-->

## Composition d'un paquet de données
Normalement, un paquet comporte un en-tête et une charge utile. La structure d'un paquet dépend du type de paquet et du protocole. 

Composition d'un paquet de données (représentation):
?
![[image-20230322085123660.png]]
- L'en-tête contient des informations générales sur le paquet, le service et d'autres données liées à la transmission.
- La charge utile, qui représente l'essentiel du paquet (tout ce qui précède est considéré comme de l'overhead), et qui constitue en fait les données transportées.
<!--SR:!2024-03-09,183,210-->

Par exemple, le transfert de données sur internet nécessite la décomposition des données en paquets IP, ce qui est défini dans IP (Internet Protocol), et un paquet IP comprend:
?
- L'adresse IP source, qui est l'adresse IP de la machine qui envoie les données.
- L'adresse IP de destination, qui est la machine ou l'appareil auquel les données sont envoyées.
- Le numéro de séquence des paquets, un numéro qui place les paquets dans un ordre tel qu'ils sont réassemblés de manière à retrouver les données originales telles qu'elles étaient avant la transmission.
- Le type de service, les drapeaux et d'autres données techniques
<!--SR:!2024-02-23,29,150-->