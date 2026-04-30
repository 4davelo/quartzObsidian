---
type: document-section
document_id: cct-105
section_id: doc105-tech-0193
ordre_document: 216
titre: ARTICLE C21. PAR.6. OPTIMALISEURS
aliases:
  - CCT 105 — HVAC FR 2023 — 216 ARTICLE C21. PAR.6. OPTIMALISEURS
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/index|CCT 105 — HVAC FR 2023 — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/215-article-c21-par-5-appareils-auxiliaires|ARTICLE C21. PAR.5. APPAREILS AUXILIAIRES]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/217-article-c21-par-7-appareil-de-regulation-et-de-commande-programmable|ARTICLE C21. PAR.7. APPAREIL DE REGULATION ET DE COMMANDE PROGRAMMABLE]]"
tags:
  - document-section
  - cct-105
  - hvac
sources:
  - 216_article_c21._par.6._optimaliseurs.md
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

#### ARTICLE C21. PAR.6. OPTIMALISEURS 

L'optimaliseur est un appareil qui réduit les temps de fonctionnement d'une installation de chauffe le plus possible, en conservant les conditions de confort exigées. 

Le cahier spécial des charges peut demander que l'appareil optimalise plusieurs éléments de l'installation de chauffe (p.ex. vannes à trois voies, chaudières, groupes de traitement d'air, etc.) de façon indépendante ; dans ce cas, on peut cependant placer plusieurs optimaliseurs, qui commandent chacun par exemple un élément. 

Le nombre d’éléments qui peuvent être optimalisés de façon indépendante, est appelé le nombre de "canaux" de l'optimaliseur. 

**1. Composition** 

L'optimaliseur est constitué des parties suivantes. 

**1.1. Microprocesseur avec accessoires** 

Cette partie comprend : 

- un microprocesseur, qui fait les calculs nécessaires 

- les mémoires, où sont stockés les programmes et paramètres 

- une unité d'alimentation, pour l'alimentation du microprocesseur, qui convient pour une tension de 230 V (+10

- 15%) 50 Hz (± 2%) 

- une batterie, qui assure la conservation de toute l'information stockée dans les mémoires, en cas d'interruption de l'alimentation. En dehors des programmes horaires, les autres fonctions (c.à.d. commande des vannes, pompes, etc.) ne doivent pas rester en fonctionnement pendant l'interruption de leur alimentation. Après la fin de l'interruption, l'optimaliseur reprend automatiquement son fonctionnement normal. L'autonomie est d'au moins 72 heures pour une batterie rechargeable et 2 années pour une batterie qui n'est pas rechargeable. 

**1.2. Entrées et sorties** 

Pour chaque canal, l'optimaliseur comprend les entrées et sorties suivantes : 

- une entrée pour le raccordement d'une sonde de température extérieure 

- une entrée pour le raccordement d'une sonde de température intérieure 

- un relais de sortie avec contact de commutation arrêt/marche 

- un relais de sortie avec contact de commutation normal/accéléré 

Remarques : 

- La sonde de température extérieure peut être commune pour plusieurs canaux. 

- Les relais de sorties conviennent pour 250 V

- 2 A. On peut placer éventuellement des relais supplémentaires hors de l'optimaliseur. 

**1.3. Panneau de commande** 

Le panneau de commande comprend les éléments suivants : 

- un clavier avec des touches de programme et des touches numériques

- un affichage numérique 

Tous les éléments mentionnés ci-dessus sont montés dans un coffret solide. 

**2. Fonctionnement** 

**2.1. Détermination de la période d'occupation** 

Pour chaque jour de la semaine, l'heure de début et de fin de la période d'occupation est indiquée. Les jours sans occupation sont également indiqués. Le programme ainsi déterminé se répète chaque semaine. 

Il est également possible d'établir des dérogations pour un jour bien déterminé : une fois ce jour passé, on suit à nouveau le programme normal. 

En outre, pour une période d'un an, vingt jours particuliers sans occupation peuvent être indiqués. Toutes ces données peuvent être différentes pour chaque canal. 

**2.2. Régimes** 

L'optimaliseur dispose de quatre régimes, qui peuvent être différents pour chaque canal : 

- régime normal : celui-ci est d'application pendant la plus grande partie de la période d'occupation 

- 

   - régime de nuit : idem, en dehors de la période d'occupation 

- régime de sécurité : ce régime a pour but d'éviter, pendant le régime de nuit, que la température dans les locaux ne descende trop bas 

- régime accéléré : peu de temps avant le début de la période d'occupation, on passe au régime accéléré afin d'atteindre la température exigée au début de la période d'occupation 

Les relais de sortie occupent les positions suivantes selon les différents régimes : 

|régime|relais 1<br>(arrêt/marche)|relais 2<br>(normal/accéléré)|
|---|---|---|
|normal|marche|normal|
|nuit|arrêt|normal|
|sécurité|marche|accéléré|
|accéléré|marche|accéléré|



**2.3. Calcul des moments de commutation** 

Les commutations se font compte tenu des règles générales suivantes : 

- Commutation normal vers nuit : Cette commutation a lieu quelques temps avant la fin de la période d'occupation, le plus tôt possible mais néanmoins de telle façon qu'à la fin de cette période la température dans les locaux ne soit pas en dessous d'une valeur limite réglable. 

- Commutation nuit vers sécurité : Cette commutation a lieu si la température dans les locaux descend en dessous d'une limite réglable ; dès que la température est remontée suffisamment au-dessus de la limite, on repasse au régime de nuit. 

- Commutation nuit vers accéléré : Cette commutation a lieu avant le début de la période d'occupation aussi tard que possible, mais néanmoins de telle façon qu'au début de cette période la température dans les locaux ne soit pas en dessous d'une valeur limite réglable.

- Commutation accéléré vers normal : Cette commutation a lieu dès qu'une des conditions suivantes est remplie : la période d'occupation est commencée, ou bien la température désirée est atteinte. 

Les moments de commutation sont calculés à l'aide des températures intérieures et extérieures, les valeurs limites pour la température intérieure, les caractéristiques du bâtiment et de l'installation, et des résultats des calculs précédents (c.à.d. auto-adaptation). Cette auto-adaptation ne peut cependant pas avoir une influence trop grande ou trop rapide ; en particulier, il faut éviter que des circonstances temporaires ne perturbent les calculs ultérieurs. 

L'utilisateur peut également programmer le passage au régime de nuit pendant la période d'occupation, si la température dans les locaux dépasse une certaine limite. 

**2.4. Application dans une installation de chauffage** 

Sauf prescriptions contraires du cahier spécial des charges, l'optimaliseur commande un circuit de chauffage (avec régulation par vanne à trois voies et sonde extérieure) comme suit : 

|relais de sortie|1|arrêt|marche||
|---|---|---|---|---|
||2|(normal ou accéléré)|normal|accéléré|
|élément de chauffage|||||
|vanne à trois voies||complètement fermée|commandée par<br>régulateur|complètement<br>ouverte|
|circulateur||arrêt|marche|marche|



Si le cahier spécial des charges le demande, l'optimaliseur commande aussi la chaudière, c.à.d. que celle-ci et les pompes primaires éventuelles sont arrêtées lorsque tous les canaux sont dans la position arrêt (cette commande de chaudière ne constitue donc pas un canal supplémentaire). Les relais supplémentaires, nécessaires pour l'exécution de cette fonction, seront placés. 

**3. Commande** 

**3.1. Demande des données** 

Les données suivantes peuvent être obtenues sur l'affichage au moyen des touches : 

- l'heure et la date 

- la température des sondes intérieures et extérieures 

- le régime actuel 

- nature et moment de la dernière commutation 

- la période d'occupation indiquée, par jour 

- tous les paramètres, les possibilités de programmation, etc. 

Toutes ces informations sont données par canal. 

**3.2. Commande** 

Les commandes suivantes sont possibles de façon simple : 

- l'introduction de l'heure et de la date 

- le changement de l'heure été/hiver 

- l'introduction des heures d'occupation 

- la programmation des dérogations temporaires aux heures d'occupation 

- l'introduction des paramètres, des possibilités de programmation, etc. ; toutefois, ces introductions ne peuvent se faire que par les personnes qui disposent de la clé ou du code d'accès.

**4. Stipulations diverses** 

**4.1. Montage** 

L'optimaliseur est placé contre une paroi, à côté du tableau électrique où se trouvent les contacteurs, disjoncteurs etc. de l'installation commandée. 

Le montage se fait de telle façon que l'optimaliseur ne soit pas perturbé par les contacteurs, moteurs, etc. proches. 

Le raccordement des sondes est réalisé au moyen de câbles selon les indications du constructeur. 

**4.2. Mise en service** 

La mise en service comprend l'introduction des heures d'occupation selon les besoins de l'occupant, ainsi que l'introduction de tous les paramètres et possibilités de programmation selon les caractéristiques de l'installation et du bâtiment. 

Tous ces éléments sont ensuite écrits sur une fiche, qui est conservée dans un emplacement réservé à cette fin (p.ex. l'intérieur d'un couvercle, etc.). 

Pendant la période de garantie, l'optimaliseur est affiné, c.à.d. que les paramètres sont ajustés si le fonctionnement ne donne pas satisfaction.
