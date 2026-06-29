# Maquette pédagogique pour TP sur convertisseur Buck

***1. Présentation***

L'objectif de cette maquette est de pouvoir réaliser des mesures autour d'un convertisseur Buck afin d'expliquer aux étudiants le fonctionnement et les caractéristiques d'un tel convertisseur. Le niveau pédagogique visé est un niveau école d'ingénieur (L3/M1).

***2. Caractéristiques techniques***

Cette maquette est développée autour du LT1959, controleur de Buck avec transistor intégré. Voici les caractéristiques :

- Tension d'entrée : 5 - 15V
- Tension de sortie : 3.3 V
- Inductance de lissage modifiable parmi 3 valeurs
- Condensateur de lissage de sortie modifiable parmi 3 valeurs
- Charge en sortie (résistance) modifiable parmi 3 valeurs
- Courant d'entrée max possible pour le LT1959 : 4 A
- Sécurité contre l'inversion de la tension en entrée, contre les surtensions en entrée, ainsi que les court-circuit

La maquette telle qu'elle est développée, permet d'étudier le mode de conduction continu et discontinu d'un tel convertisseur (CCM et DCM).


Il est possible de changer certaines valeurs de composants afin de l'adapter à l'objectif pédagogique visé. Entre autre, la tension de sortie peut être changée en modifiant les valeurs des résistances *R2* et *R3*. Attention cependant à prendre des résistances de sortie *R5*, *R6* et *R7* tenant la puissance.

