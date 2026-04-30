---
type: document-section
document_id: cct-105
section_id: doc105-tech-0130
ordre_document: 153
titre: ARTICLE C11. PAR. 7. Humidificateur à vapeur électrique autonome
aliases:
  - CCT 105 — HVAC FR 2023 — 153 ARTICLE C11. PAR. 7. Humidificateur à vapeur électrique autonome
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/index|CCT 105 — HVAC FR 2023 — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/152-article-c11-par-6-humidificateur-a-vapeur-non-autonome|ARTICLE C11. PAR. 6. Humidificateur à vapeur non autonome]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/154-article-c12-caissons-de-traitement-d-air|ARTICLE C12. CAISSONS DE TRAITEMENT D’AIR]]"
tags:
  - document-section
  - cct-105
  - hvac
sources:
  - 153_article_c11._par._7._humidificateur_à_vapeur_électrique_autonome.md
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

#### ARTICLE C11. PAR. 7.  HUMIDIFICATEUR À VAPEUR ÉLECTRIQUE AUTONOME 

**1. Exigences constructives** 

**1.1. Principes techniques** 

Les humidificateurs à vapeur sont du type générateur autonome à résistances électriques. Dans ce type d'humidificateurs, la mise en température et la vaporisation de l'eau s'effectuent soit à la pression atmosphérique, soit en légère surpression au moyen de résistances immergées du type barre ou serpentin. 

La vapeur est générée dans une cuve à vapeur en acier inoxydable, équipée d'un système d'alimentation en eau automatique. 

**1.2. Alimentation en eau** 

La tuyauterie d'alimentation en eau de l'appareil doit être équipée d'un filtre et d'un robinet d'arrêt (ou d'un élément combiné filtre – robinet d'arrêt). 

Le niveau d'eau dans la cuve à vapeur est continuellement surveillé par une unité de régulation automatique de niveau. 

Cette unité est équipée d'un interrupteur de niveau de sécurité qui interrompt l'alimentation des résistances et active une alarme en cas de niveau insuffisant. 

**1.3. Drainage automatique** 

Suite au phénomène d'évaporation la teneur en minéraux de l'eau de la cuve à vapeur s'accroit. Pour limiter cette concentration une partie de l'eau contenue dans la cuve à vapeur doit être évacuée automatiquement et remplacée par de l'eau fraîche avec des intervalles qui varient automatiquement en fonction de la production de vapeur et de la contenance en minéraux de l'eau d'alimentation (p. ex. mesurée au moyen d'électrodes de mesure de la conductivité). 

Indépendamment de la concentration des minéraux dans l'eau d'alimentation, le module de contrôle du système de drainage automatique prévoit au moins un cycle de drainage sur base d'un délai maximum, basé sur la quantité de vapeur produite ; ceci est valable également dans le cas de l'alimentation de l'appareil en eau déminéralisée. 

**1.4. Evacuation des dépôts de calcaire** 

Quand les appareils sont alimentés en eau de ville non traitée – même avec le système de drainage automatique – il se forme des dépôts de sels minéraux dans le fond de la cuve à vapeur. Cette cuve est à équiper d'éléments permettant d'éliminer et d'évacuer ces dépôts (p. ex. collecteur de calcaire placé en-dessous de la cuve à vapeur). 

**1.5. Régulation** 

La production de vapeur doit pouvoir être réglée de façon modulante de 0% à 100% de la puissance nominale. 

A cette fin l'humidificateur est doté d'un module de régulation et de contrôle équipé de microprocesseurs, qui permet les deux modes de régulation suivants : 

- Soit une régulation modulante "autonome" sur base d'une sonde de régulation de l'humidité relative (HR) et d'une sonde HR "limite haute" ; ce régulateur interne doit être de type PI. 

- Soit la liaison avec un signal de régulation provenant d'un régulateur externe (sous un mode standard, tel que 0-5 V, 0-10 V, 4-20 mA, …) 

Le module de régulation et de contrôle doit pouvoir maintenir l'eau de la cuve à une température minimale, afin de réduire le temps de réponse de l'humidificateur après une période sans demande. 

Toutes les fonctions de contrôle et de régulation doivent être rassemblées sur un panneau frontal comprenant : 

- Un compteur horaire d'exploitation pour gérer la programmation des opérations de maintenance ;

- Les lampes-témoins pour affichage de production de vapeur ou d'un éventuel dérangement et les touches marche/arrêt et rinçage manuel ; 

- Un portillon qui donne accès aux éléments électroniques de l'appareil pour le réglage des différents microprocesseurs et contient les bornes de raccordement pour un circuit de sécurité externe (un asservissement à la ventilation et un hygrostat à maxima) 

- Un système de diagnostic de dérangement donnant le code référant l'explication du dérangement ; 

- Une sécurité "manque d'eau" ; 

- Une sécurité de débordement et un système de régulation de niveau d'eau auto-adaptif comportant des contacts ; 

- Un contact d'alarme "général" pour le report à distance ; 

- Si le cahier spécial des charges le demande, toutes les fonctionnalités du régulateur doivent être accessibles à distance à l'aide des protocoles MODBUS, BACnet ou LonWorks. 

**1.6.  Armoire** 

L'ensemble des éléments constituants de l'humidificateur doit être intégré dans une armoire métallique, revêtue d'une peinture adéquate et équipée de portes avec clef, pour éviter tout accès par des personnes non qualifiées. 

**2. Distance libre d'humidification** 

Les exigences sont identiques à celles reprises sous le point 3 du PAR 6. ci-dessus pour les humidificateurs à vapeur non autonomes. 

**3. Montage** 

**3.1. Généralités** 

La distribution de vapeur en conduit d'air ou en caisson de traitement d'air se fait à l'aide d'une (de) rampe(s) d'injection en acier inoxydable, conçue(s) pour une diffusion uniforme sur toute la longueur de la rampe. 

Les rampes doivent être disponibles en diverses longueurs pour reprendre toute la largeur du conduit d'air dans lequel elles sont placées. 

La liaison entre l'humidificateur et la (les) rampes(s) d'injection doit être réalisée avec des tuyaux flexibles conçus à cet effet. Le tracé de cette tuyauterie doit se faire de manière à éviter toute accumulation de condensats. Il est nécessaire d'éviter la formation de points bas ou de siphons dans lesquels les condensats pourraient stagner. 

Les condensats qui se forment dans le tuyau de transport de vapeur et dans la rampe d'injection doivent être évacués. Cela se fait par gravité à l'aide d'un tuyau flexible conçu à cet effet. Pour éviter tout échappement de vapeur non condensée à travers le tuyau d'évacuation des condensats, il est nécessaire de réaliser un siphon dans celui-ci (p. ex. en créant une boucle sur une partie du tuyau de drainage). 

Tous les accessoires de distribution de la vapeur (rampes, tuyaux flexibles pour vapeur et pour condensats, …) doivent provenir du fournisseur de l'humidificateur et être placés selon ses recommandations. 

**3.2. Emplacement des rampes d'injection** 

Pour l'emplacement de montage des rampes d'injection dans les conduits d'air ou dans les caissons de traitement d'air, il est renvoyé aux points 5.1. et 5.2. du PAR 6. ci-dessus. 

**4. Exigences pour l'eau d'alimentation** 

Les humidificateurs à vapeur du type générateur autonome à résistances sont à alimenter : 

- Soit avec de l'eau potable non traitée 

- Soit avec de l'eau totalement déminéralisée.
