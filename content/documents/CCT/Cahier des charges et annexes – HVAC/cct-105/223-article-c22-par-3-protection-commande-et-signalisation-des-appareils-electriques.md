---
type: document-section
document_id: cct-105
section_id: doc105-tech-0200
ordre_document: 223
titre: ARTICLE C22. PAR. 3. PROTECTION, COMMANDE ET SIGNALISATION DES APPAREILS ELECTRIQUES
aliases:
  - CCT 105 — HVAC FR 2023 — 223 ARTICLE C22. PAR. 3. PROTECTION, COMMANDE ET SIGNALISATION DES APPAREILS ELECTRIQUES
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/index|CCT 105 — HVAC FR 2023 — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/222-article-c22-par-2-systemes-d-entrainement|ARTICLE C22. PAR. 2. SYSTEMES D’ENTRAÎNEMENT]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/224-article-c22-par-4-tableaux-electriques|ARTICLE C22. PAR. 4. TABLEAUX ELECTRIQUES]]"
tags:
  - document-section
  - cct-105
  - hvac
sources:
  - 223_article_c22._par._3._protection_commande_et_signalisation_des_appareils_electriques.md
created: 2026-04-28
updated: 2026-04-28
contextes:
  - appel-doffres
  - execution-projet
  - technique
autorite:
  - contractuel
juridictions:
  - belgique
familles_sources:
  - contrat
---

#### ARTICLE C22. PAR. 3.  PROTECTION, COMMANDE ET SIGNALISATION DES APPAREILS ELECTRIQUES 

**1. Moteurs** 

**1.1. Moteurs asynchrones triphasés alimentés directement** 

Ce paragraphe s'applique à tous les moteurs asynchrones triphasés sans variateur de vitesse électronique. 

**1.1.1. Protection** 

Les moteurs sont protégés par des disjoncteurs munis de déclencheurs à maximum de courant. 

Les disjoncteurs et les déclencheurs satisfont à la norme NBN EN 60947-2 et /A1/A2. La tension nominale est de 400 V au moins, la tension nominale d'isolation est de 500 V. L'intensité nominale est d'au moins 1,2 fois le courant nominal du moteur, avec un minimum de 9 A. Le pouvoir de fermeture et de coupure est déterminé en fonction des caractéristiques de l'installation desservie et des prescriptions de la norme. 

Sur chacune des phases ou chacun des pôles du disjoncteur sont placés deux déclencheurs à maximum de courant: 

   - l'un à fonctionnement instantané (par. ex. électromagnétique), pour la protection contre les courts-circuits. Il est réglable ou réglé pour s'ouvrir lorsque l'intensité atteint entre 8 et 12 fois la valeur de réglage du déclencheur à temps inverse dépendant 

- l'autre, à fonctionnement à temps inverse dépendant (par ex. thermique), pour la protection contre les surcharges. Il est réglable pour s'ouvrir lorsque l'intensité atteint 0,8 à 1 fois l'intensité nominale du moteur. Le retard est suffisant pour permettre le démarrage du moteur sans que l'on doive régler le déclencheur à une intensité qui dépasse l'intensité nominale du moteur. 

- Les deux déclencheurs peuvent être combinés dans un seul appareil (éventuellement avec le disjoncteur), mais doivent être ou pouvoir être réglés suivant les conditions précitées. 

**1.1.2. Commande** 

**1.1.2.1. Contacteur** 

La commande des moteurs est assurée par des contacteurs, à commande électromagnétique. 

Ceux-ci répondent aux prescriptions de la norme NBN EN 60947-4-1 et /A1. Les grandeurs nominales sont déterminées comme pour les disjoncteurs (voir point 1.1.1. ci-dessus). 

Le disjoncteur et le contacteur peuvent constituer un seul appareil. 

Pour les moteurs ayant une puissance inférieure à 1 kW, les disjoncteurs peuvent être remplacés par de petits disjoncteurs selon NBN EN 60898-1 et /A1à4. Dans ce cas, les contacteurs sont munis sur chaque pôle d'un relais à maximum de courant à temps inverse dépendant tel que décrit au point 1.1.1. ci-avant. 

Chaque moteur a son propre circuit d'alimentation avec les appareils de protection et de commande. 

Les bobines de commande des appareils sont protégées sur les deux phases par de petits disjoncteurs selon NBN EN 60898-1 et /A1à4. Il est fourni une bobine de réserve pour chaque type d'appareil repris dans la fourniture.

**1.1.2.2. Commande manuelle** 

Chaque moteur peut être commandé de façon manuelle. La commande manuelle se fait au fronton (ou sur la face extérieure de la porte) d'un tableau électrique, par un commutateur multipolaire, propre à chaque moteur. 

Ce commutateur possède trois positions : arrêt/automatique (ou distance)/continu. 

Ces positions ont les fonctions suivantes: 

- arrêt : dans cette position, le moteur est toujours hors tension 

- automatique (ou distance) : dans cette position, le fonctionnement du moteur est commandé par une régulation automatique (par ex. : thermostat, horloge à programme, etc.), ou bien le moteur est commandé d'un autre lieu situé à distance 

- continu : dans cette position, le moteur fonctionne de façon continue, indépendamment des commandes de la régulation automatique ou de la commande à distance. Toutefois, si certains appareils de sécurité sont prévus (tel que l'interrupteur de sécurité, voir point 1.1.5.), ceux-ci ont priorité et peuvent arrêter le moteur. 

La position automatique (ou distance) ne doit pas être prévue s'il n'y a pas de régulation automatique ou de commande à distance. 

S'il y a à proximité du tableau électrique ou du moteur des appareils locaux pour la régulation ou la commande à partir desquels on peut commander le moteur manuellement et automatiquement (ne pas confondre avec la commande à distance), les positions "automatique" et "continu" sont remplacées par une position unique (marche), qui met sous tension l'ensemble des appareils locaux de réglage et de commande, et le moteur. 

Pour les moteurs à deux vitesses, il y a deux positions "continu" : continu petite vitesse et continu grande vitesse. 

Si plusieurs possibilités pour la régulation automatique ou la commande sont prévues (par ex. commande normale et commande par pompiers), le cahier spécial des charges détermine l'ordre de priorité entre ces régulations et commandes à distance. En tout cas, ils ne sont actifs que si le commutateur mentionné ci-dessus se trouve dans la position "automatique", et les positions "arrêt" et "continu" ont toujours priorité. 

Le cahier spécial des charges peut aussi prescrire qu'un contact supplémentaire soit monté sur le commutateur de façon qu'on puisse surveiller à distance la position du commutateur. 

**1.1.3. Démarrage et réglage de la vitesse** 

Le démarrage direct des moteurs est admis dans la mesure où il n'a pas de conséquences néfastes pour le système d'entraînement et pour le fonctionnement de l'installation électrique. De toute façon, il est interdit de faire démarrer directement des moteurs d'une puissance supérieure à 20 kVA. 

En général, le courant maximal de démarrage est limité aux valeurs suivantes selon la puissance nominale du moteur: 

   - puissance nominale ≤ 3 kVA : 4 x courant nominal 

   - 3 kVA < puissance nominale ≤ 5 kVA : 3 x courant nominal 

   - 5 kVA < puissance nominale ≤ 10 kVA : 2 x courant nominal 

- 10 kVA < puissance nominale : 1,5 x courant nominal 

- Dans certains cas, un courant de démarrage moins élevé peut être exigé, par exemple pour des moteurs alimentés par un groupe électrogène. 

Afin de satisfaire aux impositions concernant le courant de démarrage, l'on fait usage : 

- de démarreurs étoile-triangle avec contacteurs selon la norme NBN EN 60947-4-1 et /A1 

- de démarreurs avec semi-conducteurs (soft-starter) selon la norme NBN EN 60947-4-2 (dans ce cas, le démarreur peut également remplir la fonction de contacteur); le temps et le couple ou le courant de démarrage sont réglables

Pour la variation de la vitesse de rotation, l'on fait usage : 

- de moteurs à plusieurs vitesses, avec enroulement Dhalander ou avec plusieurs enroulements; la commutation des pôles se fait au moyen de contacteurs. 

- de variateurs de vitesse électroniques: voir point 1.2. 

Il y a lieu de prendre les précautions nécessaires pour qu'au cours de la commutation des pôles, ou du passage étoile-triangle, l'axe du moteur ne subisse pas de chocs trop violents susceptibles d'endommager la transmission ou la charge entraînée ou d'en réduire la durée de vie. 

**1.1.4. Signalisation** 

La marche des moteurs est signalée au fronton (ou sur la face extérieure de la porte) du tableau de commande par une lampe-témoin verte. Cette lampe doit indiquer la présence de tension aux bornes du moteur et non seulement la fermeture du contacteur. 

Si la section des conducteurs du câble de signalisation est inférieure à celle du câble d'alimentation du moteur, le câble de signalisation doit être protégé par un petit disjoncteur multipolaire, placé près du point où le câble de signalisation est raccordé au câble d'alimentation. 

Cependant, lorsque le déclenchement par la protection contre les courts-circuits et contre les surcharges, et l'ouverture de l'éventuel interrupteur de sécurité (voir 1.1.5.), ont également pour suite le déclenchement du contacteur, la signalisation peut se faire par un contact auxiliaire sur le contacteur. 

Pour les moteurs d'une puissance supérieure à 1 kW, toute mise en sécurité est signalisée par une lampe-témoin rouge et toute dérogation à la régulation automatique par une lampe-témoin orange. 

**1.1.5. Interrupteur de sécurité** 

Lorsque l'interrupteur de commande sur le tableau n'est pas visible de l'endroit où se trouve le moteur, il est placé, à proximité immédiate du moteur, un interrupteur verrouillable qui coupe toutes les phases d'alimentation. 

Un contact auxiliaire de cet interrupteur signale le déclenchement au moyen d'une lampe-témoin orange (dérogation) sur le tableau de commande. 

Lorsque le moteur ne démarre pas directement, l'ouverture de l'interrupteur doit avoir pour conséquence que le démarreur revient dans la position de démarrage. 

**1.2. Moteurs alimentés par variateur de vitesse électronique** 

Les ensembles variateur-moteur sont protégés par des disjoncteurs munis de déclencheurs à maximum de courant à fonctionnement instantané, tels que décrit dans le point 1.1.1. ci-dessus. 

La protection contre les surcharges, la commande, le démarrage et le réglage de la vitesse sont réalisés par le variateur de vitesse. 

Pour la commande manuelle il y a un commutateur à deux positions arrêt/automatique tel que décrit dans le point 1.1.2.2. ci-dessus. 

Les exigences de signalisation du point 1.1.4 sont d’application, toutefois les lampes-témoin sont alimentées par des contacts auxiliaires du variateur. 

Le point 1.1.5 concernant l’interrupteur de sécurité est d’application.

**1.3. Moteurs monophasés** 

Les moteurs monophasés sont protégés sur les deux phases par des petits disjoncteurs selon NBN EN 60898-1 et /A1à4. 

La tension nominale est de 400 V. Le courant nominal et le pouvoir de coupure sont déterminés en fonction des caractéristiques de l'installation à protéger. Les petits disjoncteurs monopolaires ne sont pas admis. 

Les moteurs sont munis d'une protection contre les surcharges. Cependant, celle-ci peut être incorporée dans le moteur. 

La marche des moteurs est signalée au fronton (ou sur la face extérieure de la porte) du tableau de commande par une lampe-témoin verte. 

Les prescriptions des points 1.1.2.2. et 1.1.5. ci-dessus sont d'application. 

**2. Autres appareils** 

**2.1. Pompes** 

**2.1.1. Pompes alimentées directement par le réseau** 

Les prescriptions du point 1.1 (moteurs triphasés) et 1.3 (moteurs monophasés) sont d’application 

**2.1.2. Pompes alimentées par variateur de vitesse** 

Les prescriptions du point 1.2 sont d’application 

**2.1.3. Pompes avec variateur de vitesse intégré** 

Les prescriptions du point 1.2 sont d’application ; la commande, le réglage de la vitesse et le type de pilotage sont réalisés par le variateur de vitesse, voir art. C8 par. 4 point 3. 

**2.2. Brûleurs** 

**2.2.1. Protection et commande** 

Les points précités sont d'application: 

- brûleurs à ventilateur, triphasés : 1.1.1. et 1.1.2. 

- brûleurs à ventilateur, monophasés : 1.3. 

- brûleurs atmosphériques : 1.3. 

**2.2.2. Commande manuelle** 

La commande manuelle se fait au fronton (ou sur la face extérieure de la porte) d'un tableau électrique par un commutateur multipolaire, propre à chaque brûleur. 

Ce commutateur possède trois positions : arrêt/automatique/continu. 

Ces positions ont les fonctions suivantes: 

- arrêt : dans cette position, le brûleur est entièrement hors tension (y compris les appareils de sécurité) 

- automatique : dans cette position, le fonctionnement du brûleur est commandé par la régulation automatique (par ex. l'aquastat de réglage) 

- continu : dans cette position, le brûleur fonctionne de façon continue, indépendamment des commandes de la régulation automatique, mais cependant sous contrôle des divers appareils de sécurité (par ex. l'aquastat de sécurité)

Pour les brûleurs à réglage "tout ou peu", le commutateur possède quatre positions: arrêt/automatique/continu petite flamme/continu grande flamme. 

Pour les brûleurs à réglage modulant, le commutateur possède trois positions, et il y a un deuxième commutateur qui permet de régler la modulation dans le cas "continu". 

**2.2.3. Signalisation** 

La signalisation se fait au fronton (ou sur la face extérieure de la porte) du tableau de commande au moyen des lampes-témoin suivantes: 

- blanche : brûleur sous tension (lorsque certains dispositifs de sécurité coupent directement l'alimentation du brûleur, la lampe est raccordée en aval de ces dispositifs) 

- verte : brûleur en fonctionnement 

- orange : dérogation à la régulation automatique 

- rouge : brûleur en dérangement 

Pour les brûleurs à réglage "tout ou peu", "modulant", il y a une lampe supplémentaire qui indique le fonctionnement à puissance maximale. Cette lampe n'est cependant pas requise lorsque le brûleur est équipé d'un indicateur de position visible. 

Pour les brûleurs à gaz atmosphériques d'un débit calorifique nominal inférieur ou égal à 120 kW, les lampes-témoin rouge et verte ne sont pas exigées au fronton (ou sur la face extérieure de la porte) du tableau de commande. 

**2.3. Ventilateurs et groupes de traitement d’air** 

Les prescriptions du point 1. – moteurs sont d’application; lorsqu’un ventilateur est arrêté/démarré par le commutateur manuel (voir point 1.1.2.2.), les registres d’air neuf ou vicié associés au ventilateur sont également fermés/ouverts. 

**2.4. Ventilo-convecteurs et aérothermes** 

L'alimentation des moteurs de ventilateur des ventilo-convecteurs et des aérothermes est protégée par des petits disjoncteurs. 

Cette alimentation peut être commune pour tous les moteurs de ventilo-convecteurs et d'aérothermes raccordés au même circuit hydraulique, excepté: 

- lorsque la commande des moteurs par la régulation automatique est divisée en plusieurs groupes, l'alimentation est divisée en correspondance; 

- lorsque la puissance électrique totale des moteurs est supérieure à 5 kW, l'alimentation doit être divisée en plusieurs circuits de moins de 5 kW ; cette division est réalisée de façon logique, par exemple un circuit par étage. 

Le circuit d'alimentation a une commande manuelle comme il est décrit au point 1.1.2.2. ci-dessus, laquelle est cependant commune pour tous les moteurs du circuit d'alimentation. 

Chaque moteur est muni d'une protection contre les surcharges incorporée et d'un interrupteur manuel individuel permettant de couper la tension, avec priorité sur la régulation automatique. 

**2.5. Servomoteurs** 

L'alimentation des servomoteurs (pour robinets, régulateurs de débit, clapets coupe-feu, …) est protégée par des petits disjoncteurs. 

Cette protection peut être commune pour plusieurs servomoteurs, mais il y a des circuits séparés par technique (hydraulique, aéraulique, protection incendie, …).

**2.6. Appareils programmables** 

Les horloges à programme et les appareils électroniques programmables sont raccordés avant l'interrupteur général du tableau électrique, de façon qu'ils restent sous tension lors du déclenchement de cet interrupteur. 

Un interrupteur général supplémentaire permettant de déclencher tous ces appareils est prévu. La protection se fait par des petits disjoncteurs (voir 1.3.). 

**2.7. Appareils avec tableau de commande propre** 

Les appareils qui disposent d’un tableau de commande propre, tels que machines frigorifiques, pompes à chaleur etc., sont protégés par des disjoncteurs munis de déclencheurs à maximum de courant à fonctionnement instantané, tels que décrit dans le point 1.1.1. ci-dessus. 

Les autres fonctions de protection, de commande et de signalisation sont intégrées dans le tableau de commande propre (voir par ex. art. C4.). 

**2.8. Autres appareils** 

Pour les autres appareils tels que les éléments de chauffe électriques d'une puissance supérieure à 5 kW, les générateurs de vapeur électriques, etc., la protection, la commande et la signalisation se font comme il est décrit aux points 1.1.1., 1.1.2., 1.1.4. et 1.1.5. ci-dessus. 

Toutefois, la protection contre les surcharges par un déclencheur à maximum de courant à fonctionnement à temps inverse dépendant ne doit être prévue que si la nature de l'appareil à protéger l'exige. 

Les appareils tels que les éléments électriques de chauffe d'une puissance inférieure à 5 kW, les petits ventilateurs avec commande locale, les adoucisseurs d'eau, les systèmes d'expansion pneumatiques, l'appareillage de mesure et de régulation, etc., sont protégés par de petits disjoncteurs (voir 1.3.). 

**3. Tableaux électriques** 

A l'entrée du tableau est placé un interrupteur général tétrapolaire. Si le tableau est raccordé directement au réseau électrique, on place après l'interrupteur général un disjoncteur répondant aux prescriptions du point 1.1. ci-avant, mais sans déclencheur à maximum de courant à fonctionnement à temps inverse dépendant. 

Il faut également respecter les exigences supplémentaires éventuelles du fournisseur de courant. 

Chaque tableau doit être pourvu à l’entrée de parafoudres du type secondaire correspondants au type III de la norme NBN EN 61643-11. Ces appareils doivent être coordonnés avec les parafoudres du type primaire se trouvant dans le TGBT. 

Les parafoudres sont du type débrochable avec dispositif détrompeur, et sont munis d’un dispositif de visualisation permettant de vérifier l’état. 

Ils sont protégés par des fusibles ou des disjoncteurs, selon les recommandations du constructeur. 

La mise sous tension du tableau est signalée par une lampe-témoin blanche sur chaque phase. 

Lorsque certains appareils sont raccordés en amont de l'interrupteur général, la mise sous tension de ces appareils est signalée par une lampe-témoin blanche supplémentaire. 

Toute sortie vers les moteurs et appareils est protégée comme il est indiqué ci-dessus. Une sortie alimentant un autre tableau est également protégée par un disjoncteur tel que décrit au point 1.1.1. ciavant, mais sans déclencheur à maximum de courant à fonctionnement à temps inverse dépendant.

**4. Installations commandées par ARCP** 

Pour les installations commandées par ARCP, il est possible de remplacer les commutateurs de commande manuelle (voir point 1.1.2.2., 2.2.2., …) et les lampes-témoin (voir point 1.1.4., 2.2.3., …) par des micro-switch et des LED sur les modules d’interface des ARCP (art. C22. Par. 7 point 2.2.), à ’ condition que le cahier spécial des charges l autorise explicitement. 

Dans ce cas chaque moteur, pompe, ventilateur etc. est toujours pourvu d’un interrupteur de sécurité selon les prescriptions du point 1.1.5. 

La position des micro-switch doit être signalée sur l’ARCP et la centrale de conduite.
