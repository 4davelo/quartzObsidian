---
type: document-section
document_id: cct-105
section_id: doc105-tech-0103
ordre_document: 126
titre: ARTICLE C8. PAR. 4. Modes de fonctionnement des pompes
aliases:
  - CCT 105 — HVAC FR 2023 — 126 ARTICLE C8. PAR. 4. Modes de fonctionnement des pompes
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/index|CCT 105 — HVAC FR 2023 — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/125-article-c8-par-3-pompes-pour-applications-particulieres|ARTICLE C8. PAR. 3. Pompes pour applications particulières]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/127-article-c9-echangeurs-de-chaleur-et-accumulateurs|ARTICLE C9. ECHANGEURS DE CHALEUR ET ACCUMULATEURS]]"
tags:
  - document-section
  - cct-105
  - hvac
sources:
  - 126_article_c8._par._4._modes_de_fonctionnement_des_pompes.md
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

#### ARTICLE C8. PAR. 4. MODES DE FONCTIONNEMENT DES POMPES 

La commande d’une pompe en vue d’adapter la puissance du groupe aux besoins réels peut être étagée (1.) ou progressive (2. et 3.) en agissant sur la vitesse de rotation. 

Lorsqu’une pompe est commandée par ARCP, il est prévu au moins un démarrage par 24 heures en vue d’éviter le grippage. Cette fonction peut cependant être réalisée de manière autonome par la pompe dans le cas des pompes électroniques (3.). 

**1. Pompe à vitesse constante** 

Dans ce cas, la pompe tourne toujours à vitesse constante lorsqu’elle est alimentée. Si la pompe possède plusieurs vitesses (en général 3), la sélection de la vitesse de rotation est réalisée à l’aide d’une commande locale sur la pompe. 

Lorsque les installations sont commandées par une régulation automatique avec ARCP, le cahier spécial des charges spécifie le cas échéant si la pompe doit être équipée d’un signal externe de défaut. 

**2. Pompe alimentée par un variateur de fréquence séparé** 

Cette solution permet une variation progressive de la vitesse de la pompe entre deux valeurs extrêmes déterminées par le constructeur. La régulation de la vitesse de rotation peut selon le cas être réalisée en fonction d’une pression différentielle, d’un débit mesuré, d’une différence de température, de la température extérieure,… 

Si le variateur de fréquence cause des pertes dans le moteur en raison d’une tension d’alimentation qui n’est pas parfaitement sinusoïdale (présence d’harmoniques, découpage électronique de la tension par un système PWM), les pompes ne peuvent être alimentées à leur fréquence maximale, qui devra être limitée par exemple à 95%. Si nécessaire, le variateur de fréquence doit être équipé de filtres de sortie adaptés en vue de protéger le moteur et/ou de réduire les interférences au réseau de distribution. 

Les roulements du moteur seront électriquement isolés ou de type hybride (à éléments roulants en matériau céramique), de manière à empêcher que des courants parasites à haute fréquence ne les traversent, source de corrosion réduisant leur durée de vie. 

L’entrepreneur vérifie si la pompe nécessite un débit minimum pour un fonctionnement sans défaut ; un fonctionnement à très faible débit ou même à débit nul pouvant endommager la pompe par surchauffe. Selon les prescriptions du fabricant, la pompe devra être protégée par un clapet de pression différentielle ; la fourniture et l’installation de ce clapet et les adaptations de tuyauteries et calorifuge sont dans ce cas compris dans le prix unitaire de la pompe. 

**3. Pompe avec variateur intégré ou pompe « électronique »** 

Dans ce cas, un module électronique intégré commande la pompe en vitesse variable de manière à s’adapter automatiquement à la courbe réelle de l’installation. La variation de vitesse est obtenue par variation de tension et/ou de fréquence en fonction du type de moteur. 

Le cahier spécial des charges précise le type de commande souhaité : 

- **commande de la vitesse ou de la consigne par ARCP** (pilotage externe), la pompe est alors équipée d’une interface de communication qui permet de régler les paramètres à distance.

- **commande locale sur le circulateur** , qui est alors autonome. Les différents paramètres sont réglés directement au niveau de la pompe, avec éventuellement un affichage digital ou une télécommande infrarouge ou à ondes radio. 

Plusieurs types de pilotages sont possibles au niveau du module électronique ; le cahier spécial des charges spécifie celui à sélectionner : 

- ∆ **p constant** : la pression différentielle produite par la pompe est maintenue à une valeur constante dans les limites d’utilisation de la pompe. 

- ∆ **p variable** : la pression différentielle produite par la pompe varie linéairement en fonction du débit : elle passe d’une valeur H au débit maximum (à vitesse maximale) à H/2 à débit nul. 

- **Vitesse constante** : la pompe tourne à vitesse constante ; la consigne de vitesse fixe pouvant être introduite localement sur la pompe, ou réglée à distance via ARCP selon le cas. 

- **pilotage en température** : l’électronique fait varier la consigne de pression différentielle en fonction de la température du fluide. En général, la pression différentielle est réduite lorsque la température diminue (une loi inverse est utilisée pour les pompes de bouclage pour [[concepts/eau-chaude-sanitaire|Eau Chaude Sanitaire]]). 

La pression différentielle produite par la pompe est soit mesurée directement à l’aide de capteurs, soit calculée à l’aide d’un algorithme intégrant des valeurs telles que la vitesse de rotation, l’intensité du courant,… en fonction des caractéristiques programmées de la pompe. 

En mode ∆p constant, le cahier spécial des charges peut imposer que la pression différentielle soit mesurée en d’autres points du réseau que juste entre l’aspiration et le refoulement de la pompe (par exemple entre le départ et le retour du circuit, ou entre 2 collecteurs). Dans ce cas, si la pompe ne permet pas le raccordement de sondes externes à cet effet, l’entrepreneur installera un système de régulation externe (par ex via ARPC) permettant de commander la pompe en mode ∆p constant sur base de sondes de pression placées indépendamment. 

Toutes les pompes électroniques de puissance absorbée par le groupe motopompe Pgr ≥ 200 W sont équipées de contacts libres de potentiel pour indication externe de fonctionnement et de panne. 

Le cahier spécial des charges spécifie si la pompe doit être équipée d’un programme automatique de ralenti nocturne basé sur une mesure de la température du fluide, image des besoins de l’installation : dans ce cas, la vitesse est réduite automatiquement à sa valeur minimale lorsque la température du fluide descend par exemple de 15°C en 2 h de temps ; la pompe repasse en mode automatique dès que la température du fluide remonte de 10°C. 

L’entrepreneur vérifie si la pompe nécessite un débit minimum pour un fonctionnement sans défaut ; un fonctionnement à très faible débit ou même à débit nul pouvant endommager la pompe par surchauffe. Selon les prescriptions du fabricant, la pompe devra protégée par un clapet de pression différentielle ; la fourniture et l’installation de ce clapet et les adaptations de tuyauteries et calorifuge sont dans ce cas compris dans le prix unitaire de la pompe. 

En fonction des exigences du constructeur, l’entrepreneur place sur l’alimentation électrique de la pompe les protections nécessaires contre les risques de surcharges ou les coupures réseau. 

Les pompes ‘électroniques’ sont munies d’un dispositif de commande et de contrôle du paramétrage (vitesse de rotation, hauteur totale de charge différentielle, mode sélectionné,…). Si la commande et/ou le contrôle de la pompe ne sont pas intégrés au module de régulation de la pompe (aisément accessible à l’utilisateur) ou au tableau de commande du local technique considéré mais sont réalisés par une télécommande, l’entrepreneur devra fournir sans supplément de prix une télécommande compatible avec chaque type de pompe fournie pour un même chantier, pour autant que le marché comprenne au minimum 5 pompes électroniques ayant recours à ce type de télécommande. Pour les plus petits marchés, le cahier spécial des charges précisera si une telle télécommande doit ou non être fournie.

La télécommande communique par infra-rouge ou ondes radio avec les pompes. Il est autorisé de remplacer une télécommande autonome par un module USB pour ordinateur portable qui offre au moins les mêmes fonctionnalités sans nécessiter l’installation de programmes lourds ni de licences d’utilisation spécifiques. 

**4. Pilotage des pompes doubles** 

Dans le cas de pompes prévues pour une marche parallèle, le pilotage en cascade de pompes doubles à vitesse variable permet d’obtenir une grande plage de variation de débit tout en optimisant le rendement. 

La commande des pompes doubles peut être réalisée par un module électronique autonome, ou directement par l’ARCP selon les cas. Le principe reste le même, que l’on ait une pompe double monocorps ou 2 pompes raccordées en parallèle avec chacune un clapet anti-retour (cette deuxième solution peut être justifiée par des impératifs de sécurité de fonctionnement en cas de panne d’une des 2 pompes, ou lorsqu’on veut utiliser 2 pompes de caractéristiques différentes, optimisées en fonction de 2 régimes différents : par ex jour/nuit). 

Le cahier spécial des charges peut imposer l’un des deux systèmes suivants : 

- cascade simple : une des pompes est pilotée par variateur de fréquence, l’autre fonctionnant en marche-arrêt lors de demandes de puissance plus importantes. 

- Cascade optimisée avec les 2 pompes à vitesse variable : à faible charge une seule pompe fonctionne. Lorsque la charge augmente, les 2 pompes travaillent en parallèle. Ce système est conçu de telle manière que les pompes travaillent toujours dans leur plage de meilleur rendement, la puissance consommée est donc minimisée à chaque moment, ce qui permet de réduire la consommation électrique.
