---
layout: default
title: Assemblage
parent: Fabriquer un Rover RTK
nav_order: 3
has_children: true
---

## Assemblage du Rover

### Préparer son matériel

Vérifier que vous diposez de tous les composants:

* Module F9P
* Antenne GNSS
* Batterie
* Câble USB renforcé
* option Bluetooth:
    * Module Bluetooth
    * Câble 6 pins préparé et connecté au F9P

### Adaptation du câble 6-pins si Bluetooth

Tout d'abord il faut bien repérer l'ordre des brins du câble pour la  connexion entre le récepteur F9P et le module bluetooth HC-05. 

>Il est préférable, pour simplifier le branchement, d'utiliser un connecteur 6 broches.

![cable](https://jancelin.github.io/docs-centipedeRTK/assets/images/montage_rover/branchement.jpg)

Connecter ensuite sur le UART1 du récepteur F9P

### Assemblage impression 3D

[source](https://www.prusaprinters.org/fr/prints/47974-gnss-rtk-f9p-drotek-bt-hc-05)

<iframe width="100%" height="1000" frameborder="0" style="border:0" src="https://www.prusaprinters.org/fr/prints/47974-gnss-rtk-f9p-drotek-bt-hc-05" allowfullscreen></iframe>

### Assemblage scratch

J'utilise du scratch 3M Dual-lock pour l'assemblage des composants, cela permet un démontage et une adaptation aisés du positionnement en fonction des besoins. 

>J'espère vous proposer prochainement une boîte étanche à imprimer.

* Découper des bandes scratch 3M Dual-lock à la bonne taille et les coller.

![assemblage](https://jancelin.github.io/docs-centipedeRTK/assets/images/montage_rover/assemblage1.jpg)

* Assembler les modules

![assemblage](https://jancelin.github.io/docs-centipedeRTK/assets/images/montage_rover/assemblage2.jpg)

* Connecter une antenne

![RTKrover](https://jancelin.github.io/docs-centipedeRTK/assets/images/montage_rover/rover_1.jpg)

![RTKrover](https://jancelin.github.io/docs-centipedeRTK/assets/images/montage_rover/rover_pied_2.jpg)

