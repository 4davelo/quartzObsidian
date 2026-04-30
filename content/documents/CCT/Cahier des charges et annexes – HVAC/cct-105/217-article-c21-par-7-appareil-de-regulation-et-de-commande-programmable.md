---
type: document-section
document_id: cct-105
section_id: doc105-tech-0194
ordre_document: 217
titre: ARTICLE C21. PAR.7. APPAREIL DE REGULATION ET DE COMMANDE PROGRAMMABLE
aliases:
  - CCT 105 — HVAC FR 2023 — 217 ARTICLE C21. PAR.7. APPAREIL DE REGULATION ET DE COMMANDE PROGRAMMABLE
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/index|CCT 105 — HVAC FR 2023 — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/216-article-c21-par-6-optimaliseurs|ARTICLE C21. PAR.6. OPTIMALISEURS]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/218-article-c21-par-8-centrale-de-conduite-pour-a-r-c-p|ARTICLE C21. PAR.8. CENTRALE DE CONDUITE POUR A.R.C.P.]]"
tags:
  - document-section
  - cct-105
  - hvac
sources:
  - 217_article_c21._par.7._appareil_de_regulation_et_de_commande_programmable.md
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

#### ARTICLE C21. PAR.7. APPAREIL DE REGULATION ET DE COMMANDE PROGRAMMABLE 

**1.  Introduction et définitions** 

L'appareil de régulation et de commande programmable (A.R.C.P.) est un appareil qui assure la régulation et la commande des installations techniques du bâtiment. 

A cet effet, l'A.R.C.P. est raccordé à un certain nombre d'éléments et appareils des installations thermiques (les "points") : il reçoit ainsi, au moyen des sondes et capteurs, les données nécessaires afin de régler les vannes à trois voies et de commander le fonctionnement des brûleurs, pompes, ventilateurs, etc. 

L'A.R.C.P. comprend un microprocesseur et fonctionne de manière autonome, c.à.d. que toutes les régulations et commandes se font de façon digitale, sans intervention d'appareils de régulation supplémentaires, indépendants de l'A.R.C.P. ; toutefois, certains appareils des installations thermiques peuvent encore comporter des dispositifs internes de sécurité et de réglage indépendants de l'A.R.C.P., tels que, par exemple, les automates de brûleurs. 

Dans les bâtiments ou les installations importantes, plusieurs A.R.C.P. peuvent être prévus (par exemple un par chaufferie ou par local technique) qui, chacun séparément, commandent une partie des installations. L'A.R.C.P. peut également être intégré dans un système d'automatisation de bâtiment ou de télé-contrôle. 

**Définitions :** 

- Un point est une variable liée de façon univoque à un élément physique et dont la valeur est soit demandée, soit commandée par l'A.R.C.P. 

- Un point de mesure est un point dont la valeur est demandée par l'A.R.C.P. 

- Un point de commande est un point dont la valeur est commandée (réglée) par l'A.R.C.P. 

- Un point logique est un point qui peut adopter deux ou plusieurs valeurs discrètes. 

- Un point analogique est un point dont la valeur peut fluctuer de façon continue entre deux limites. 

**2. Composition** 

L'A.R.C.P. se compose des parties suivantes : 

- une partie de base 

- les modules d'interface 

- un appareil de commande 

Chacune de ces parties est décrite ci-après, ainsi que les dispositions applicables lorsqu'il y a plusieurs A.R.C.P., et les possibilités d'extensions. 

**2.1. Partie de base** 

La partie de base comprend l'unité d'alimentation, un micro-processeur et les mémoires. 

**2.1.1. Unité d'alimentation** 

Cette unité assure l'alimentation de l'A.R.C.P. ; elle convient pour une tension de 230 V (+ 10 - 15 %) 50 Hz (± 2%). 

En outre, il est prévu une batterie rechargeable qui assure en cas d'interruption d'alimentation la conservation de toute l'information stockée dans les mémoires. En dehors des programmes horaires,

les autres fonctions (mesures, commandes, etc.) ne doivent pas rester en fonctionnement pendant la coupure du courant. 

L'autonomie, en cas de coupure de courant, est de 72 heures au minimum. 

**2.1.2. Microprocesseur** 

Celui-ci exécute tous les calculs et commande le fonctionnement des mémoires, des modules d'interface et de l'appareil de commande. 

La capacité et la vitesse sont déterminées en fonction de la quantité d'informations à traiter. 

Cependant la durée d'un cycle (comprenant la demande des valeurs des points de mesure, l'exécution des opérations et calculs nécessaires partant de ces valeurs, la transmission des valeurs résultantes aux points de commande et le cas échéant, l'échange de données avec l'appareil de commande ou avec un autre système (voir 2.5.)) ne dépasse pas 5 secondes ; au moins un cycle est exécuté tous les 5 secondes. 

**2.1.3. Mémoires** 

Les mémoires sont du type ROM et RAM. Dans celles-ci sont stockés tous les programmes, paramètres et autres données dont l'A.R.C.P. a besoin pour pouvoir exécuter ses tâches. 

La capacité des mémoires est déterminée en conséquence ; en outre, les mémoires RAM ont une capacité de réserve représentant 30% de la capacité de mémoire occupée. Cette réserve peut être réduite à 10%, si les mémoires RAM sont extensibles. 

Il doit également être possible de raccorder une unité de mémoire externe, d'où on peut rapidement charger ou copier les mémoires de l’A.R.C.P. 

**2.2. Modules d'interface** 

Les modules d'interface assurent la transformation de l'information provenant des points de mesure vers une forme digitale appropriée, et de l'information destinée aux points de commande vers une forme appropriée. 

Ils assurent également une isolation galvanique entre l'A.R.C.P. et les installations desservies ; cette isolation doit pouvoir résister à une tension électrique de 1,5 KVeff

- 50 Hz pour les points logiques et de 0,5 KVeff

- 50 Hz pour les points analogiques. 

Il y a des modules pour les points de mesure et de commande logiques et analogiques ; les modules sont interchangeables, de sorte que l'on puisse adapter la configuration de l'A.R.C.P. aux exigences. Toutefois, une configuration fixe est admise, pour autant qu'il existe une réserve de 10% pour chaque type de point. 

**2.2.1. Entrées logiques** 

Ce module comprend l'interface permettant de traiter les signaux d'un certain nombre de points de mesure logiques. 

Un point de mesure logique peut se présenter comme suit : 

1. comme contact sans tension (ouvert ou fermé) 

2. comme tension électrique (présente ou non) 

3. comme grandeur physique 

4. comme état mécanique 

Selon la nature du point, une des possibilités se présentera. Ce n'est que dans les deux premiers cas que le point peut être directement raccordé au module d'interface, tandis que dans les cas 3 et 4, on doit prévoir les appareils nécessaires (par exemple thermostat, interrupteur) qui ramènent ces cas au cas 1 ou 2.

Le module d'interface doit donc pouvoir détecter l'état d'un contact sans tension ou la présence d'une tension ; si nécessaire, des relais sont utilisés en dehors du module. 

S'il s'agit d'un point de plus de deux états, il peut être considéré comme un point avec plusieurs états ou comme une combinaison de plusieurs points à deux états. 

**2.2.2. Sorties logiques** 

Ce module comprend l'interface permettant de commander les points de commande logiques. 

Un point de commande logique peut se présenter comme suit : 

- statique : un contact doit être ouvert ou fermé 

- dynamique : on doit fermer un contact (impulsion) pour l'enclenchement et un autre pour le déclenchement 

Les points seront le plus souvent statiques. 

Le module d'interface est conçu de façon à ce que, en cas de défaut à l'A.R.C.P., les points de commande prennent une position (marche ou arrêt) bien déterminée (position de sécurité). Les relais nécessaires pour réaliser ces fonctions doivent être prévus, éventuellement en dehors du module. Comme pour les points de mesure logiques, les points de commande logiques peuvent également comporter plus de deux positions. 

**2.2.3. Entrées analogiques** 

Ce module comprend l'interface pour les points de mesure analogiques. Les points de mesure analogiques ne sont pas disponibles comme des signaux électriques directement utilisables, mais comme des grandeurs physiques ou mécaniques à mesurer (voir 4.2. et suivants). 

Celles-ci sont converties par des capteurs en grandeurs mesurables. Le module comprend des relais et un convertisseur analogique/digital qui permet de convertir le signal analogique à chaque entrée en code digital. 

La quantification du convertisseur A/D comporte 12 bits (11 + signe) au minimum. 

Les points dont le signal de mesure se compose d'impulsions (par exemple un compteur), sont également considérés comme points de mesure analogiques. 

**2.2.4. Sorties analogiques** 

Le module comprend l'interface pour les points de commande analogiques. Il comprend un convertisseur digital/analogique (quantification minimale 8 bits) et un circuit de maintien par sortie. 

Le type de signal de sortie dépend de l'application (voir 4.2. et suivants) ; si cela est nécessaire, on utilise des convertisseurs supplémentaires ou amplificateurs. 

Remarque : 

Les convertisseurs destinés à convertir les grandeurs non-électriques en grandeurs électriques (ou mesurables de façon électrique) et inversement (par ex. sondes, thermostats, servomoteurs, etc.), mentionnés en 2.2.1., 2.2.3., et 2.2.4. ne font pas partie de l'A.R.C.P. 

**2.2.5. Réseau local** 

Ce module contient l’interface pour la commande d’un réseau local. 

Sur ce réseau local peuvent se raccorder des points (de mesure et de commande, aussi bien logique qu’analogique) fortement disséminés dans le bâtiment (comme des sondes de température, clapets coupe-feu, régulateurs autonomes pour ventilo-convecteurs, etc.), au lieu de les connecter individuellement sur des modules d'entrée et de sortie. 

Dans ce cas, les points concernés doivent évidemment être équipés de l’interface nécessaire pour la liaison avec ce réseau local.

L’entrepreneur peut choisir, à sa guise, s’il raccorde des points individuellement ou via un réseau local. 

**2.3. Appareil de commande** 

L'appareil de commande comprend un clavier avec touches numériques et touches de fonction, ainsi qu'un affichage alphanumérique de 10 caractères au moins. 

L'appareil peut être, soit incorporé dans l'A.R.C.P., soit indépendant. 

**2.4. Installations avec plusieurs A.R.C.P.** 

Si la distance entre les points est relativement grande (p.ex. dans deux locaux techniques différents), plusieurs solutions sont possibles : 

- Plusieurs A.R.C.P. sont placés (par exemple un par local technique). 

- Tous les points sont raccordés à un A.R.C.P. à l'aide de câbles. 

- Une ou plusieurs sous-stations sont prévues ; une sous-station comprend un certain nombre de modules d'interface, ainsi que l'appareillage nécessaire pour transmettre l'information vers l'A.R.C.P. de façon digitale, sur un câble unique (et inversement pour recevoir de l'information de l'A.R.C.P.). L'appareillage nécessaire pour la transmission des données avec les sous-stations est également prévu dans l'A.R.C.P. 

- On peut aussi appliquer une combinaison des trois méthodes mentionnées ci-dessus. 

Si le cahier spécial des charges n'indique pas la solution à utiliser, l'entrepreneur peut la choisir luimême. 

Si plusieurs A.R.C.P. sont placés, il existe deux possibilités pour l'appareil de commande : 

- Chaque A.R.C.P. a son propre appareil de commande incorporé. 

- Un appareil de commande indépendant est fourni, que l'on peut raccorder à chaque A.R.C.P. pour commander celui-ci localement. 

Le choix entre ces 2 possibilités est libre. 

**2.5. Extensions** 

La possibilité de raccorder l'A.R.C.P. à un autre système doit exister; à cette fin, chaque A.R.C.P. est toujours équipé d'une entrée/sortie qui permet la transmission digitale de données. 

Cet autre système peut être par exemple une centrale de conduite qui contrôle plusieurs A.R.C.P. dans un bâtiment (ou plusieurs bâtiments). Dans ce cas, les A.R.C.P. continuent à remplir leurs fonctions de manière autonome, mais ils peuvent être commandés à partir de l'autre système. Les prescriptions concernant la commande locale (voir 2.3. et 2.4.) restent cependant d'application. 

Dans le cas de liaisons à grande distance les appareils nécessaires à la télétransmission sont également fournis. 

Enfin, la possibilité de raccorder localement à l'A.R.C.P. une imprimante pour imprimer les alarmes, les états de points, etc. (voir 3.2.) doit exister. 

**3. Programmes de base** 

Ces programmes sont destinés à l'usage général de l'A.R.C.P.

**3.1. Généralités** 

**3.1.1. Accès à l'appareil** 

On n'a accès à l'appareil qu'après l'introduction d'un code. 

Il y a deux niveaux différents, avec chacun leur code propre : 

1. demande d'information, modification de consignes 

2. modification de paramètres, de programmes 

Le code pour le deuxième niveau donne également accès au premier niveau. 

**3.1.2. Adressage** 

Chaque point a une adresse composée de caractères (alpha) numériques. 

Il n'est pas exigé que l'adresse puisse être choisie librement par l'utilisateur. 

**3.1.3. Programmation** 

L'établissement des programmes se fait en un langage spécialement étudié pour les applications en question, utilisable par un non-spécialiste. 

A cet effet, un certain nombre d'instructions sont disponibles, telles que des opérateurs logiques et arithmétiques, des fonctions conditionnelles et de branchement, la mise en mémoire et rappel, etc. Il n'est cependant pas exigé que l'établissement des programmes puisse être fait à partir de l'appareil de commande. 

**3.1.4. Commande** 

La commande se fait à partir du clavier ; pour les fonctions les plus utilisées, il existe des touches préprogrammées, pour les autres fonctions, on utilise un code numérique. 

**3.2. Programmes de base pour la commande de l'A.R.C.P.** 

**3.2.1. Demande d'états** 

Cette fonction permet de représenter à l'affichage les états, tant des points de mesure que des points de commande. 

Pour les points logiques, cela comprend l'adresse du point et la mention 0 ou I (éventuellement II, III, ...) pour l'état. 

Pour les points de mesure analogiques, cela comprend l'adresse et la valeur du point, ainsi que l'unité dans laquelle cette valeur est exprimée. 

Pour les points de commande analogiques, cela comprend l'adresse et la valeur du point exprimée en pourcentage (ou de 0 à 1). 

**3.2.2. Verrouillage des points** 

Chaque point peut être verrouillé par l'opérateur, ce qui bloque l'échange entre les installations desservies et l'A.R.C.P. 

Cela signifie que pour les points de mesure (logiques et analogiques), ce n'est pas la valeur de mesure proprement dite, mais la valeur imposée par l'opérateur qui est transmise au microprocesseur. 

Pour les points de commande (logiques et analogiques), ce n'est pas la valeur calculée par le microprocesseur, mais une valeur imposée par l'opérateur qui est transmise aux modules d'interface. 

Le verrouillage se fait par une commande simple, sans qu'il soit nécessaire de modifier des paramètres ou des valeurs de consigne.

**3.2.3. Alarme** 

Une alarme est une fonction qui avertit l'opérateur d'un changement d'état d'une variable logique. Cette variable peut être ou bien un point ordinaire, ou bien toute autre variable logique qui intervient dans les programmes, telle que par exemple le dépassement de seuil d'une variable analogique. 

Lorsque le changement d'état se présente, le nouvel état est visualisé sur l'affichage (voir 3.2.1.), accompagné d'un signal acoustique ou visuel. 

Le signal disparaît après qu'on ait appuyé sur une touche d'acquittement prévue à cet effet ; s'il y a plusieurs alarmes, l'alarme suivante apparaît. 

Une alarme est liée d'office aux variables suivantes : 

- toutes les signalisations de sécurité et de défaut pour autant qu'elles soient transmises à l'A.R.C.P. (par exemple sécurité de brûleurs, contrôle de débit, protection thermique pour moteur, contrôle de niveau d'eau, etc.) 

- si l'état réel de fonctionnement d'un élément (par exemple pompe, brûleur, etc.) ne correspond pas avec l'état qui est commandé par l'A.R.C.P., pour autant que cet état soit connu par l'A.R.C.P. (c'est-à-dire qu'un point de mesure indépendant doit être ajouté au point de commande afin de relever l'état réel). 

Il doit être possible de programmer, par après, des alarmes supplémentaires. 

**3.2.4. Sauvegarde régulière des valeurs** 

Les changements de valeur de chaque point de mesure et de commande logique sont sauvegardés, avec l’heure où le changement s’est produit. 

La valeur de chaque point de mesure et de commande analogique est sauvegardée tous les quarts d’heure. 

Les données sauvegardées (tant des points logiques qu’analogiques) sont mémorisées pendant au moins un jour. 

**3.3. Programmes de base pour les fonctions de régulation** 

L'A.R.C.P. dispose d'un certain nombre de programmes nécessaires à l'exécution des fonctions de régulation. Ces programmes sont utilisés comme sous-programmes dans les programmes d'application proprement dits (voir chapitre 4). 

Des programmes pour les fonctions suivantes sont notamment disponibles : 

- régulateur : il est du type P.I.D., les actions P, I et D étant réglables individuellement 

- comparateur à hystérésis 

- approche d'une fonction non linéaire par droites 

- retardement 

- horloge et calendrier : en ce qui concerne la date, le programme précise le jour, le mois et l'année (par exemple mardi 19 août 2014) ; une autre manière (par exemple la numérotation continue des jours et/ou des semaines dans l'année) n'est pas admise. La commutation de l'heure d'été vers l'heure d'hiver, et inversement, peut être programmée. 

- 

- totalisateur (compte le temps qu'un point logique est enclenché ou déclenché) 

Tous les paramètres et constantes utilisés dans ces programmes, sont modifiables.

**3.4. Programmes pour la transmission de données** 

Dans le cas où l'A.R.C.P. est raccordé à un autre système, comme décrit au 2.5., les programmes nécessaires à l'échange de données (c.à.d. pour la rédaction et la transmission de messages, ainsi que leur réception et leur traitement) avec l'autre système sont prévus. 

Cette transmission de données peut se faire à l'initiative de l'autre système (par exemple pour demander des données) ou à l'initiative de l'A.R.C.P. (par exemple pour transmettre une alarme). 

**4. Programmes d'application** 

Il s'agit des programmes de régulation et de commande des installations de chauffage, de ventilation et de conditionnement d'air. 

**4.1. Programmes généraux** 

**4.1.1. Régulation en fonction de la température extérieure** 

Cette régulation assure une valeur de sortie inversement proportionnelle au signal d'entrée représentant la température extérieure. La relation entre les deux est linéaire et réglable et est appelée la "courbe de chauffe". 

Il est possible de programmer trois courbes différentes (pour le régime de jour, de nuit et accéléré) ; la courbe de chauffe de jour peut être déplacée en fonction de la valeur de l'intensité du rayonnement solaire, si cette mesure est prévue. 

En outre, si l'on dispose de la température intérieure comme signal de réaction, la courbe de chauffe peut être corrigée automatiquement pour obtenir la valeur désirée de la température intérieure. 

Cette correction ne s'effectue que très lentement, afin que la régulation ne soit pas perturbée par des influences de courte durée ni par des influences temporaires (qui s'étendent sur quelques jours par exemple). En outre, le fonctionnement de cette auto-adaptation est déclenchable ; en général, l'autoadaptation ne sera pas utilisée lorsque le système de chauffage réglé dessert des locaux avec orientation différente ou avec des gains internes différents, ou encore lorsqu'il y a une post-régulation indépendante (p.ex. des robinets de radiateur thermostatiques). 

**4.1.2. Programme horaire** 

Ce programme indique à d'autres programmes (tant programmes d'optimalisation que programmes d'heures fixes) les périodes pendant lesquelles les locaux sont occupés. 

La période d'occupation est définie comme suit : pour chaque jour de la semaine, l'heure de début et de fin de la période d'occupation est indiquée ; les jours sans occupation sont indiqués tels quels. Le programme ainsi déterminé se répète chaque semaine. 

Il est également possible d'établir des dérogations pour un jour bien déterminé : une fois ce jour passé, on suit à nouveau le programme normal. 

En outre, pour une période d'un an, vingt jours supplémentaires sans occupation peuvent être indiqués. 

Il est possible d'établir un programme d'occupation distinct pour tout circuit de chauffe ou groupe de traitement d'air. 

**4.1.3. Programme d'optimalisation** 

Le programme d'optimalisation veille à ce que les installations thermiques fonctionnent toujours selon le régime adapté aux besoins de façon optimale. 

Le programme dispose de quatre régimes :

- régime normal : celui-ci est d'application pendant la plus grande partie de la période d'occupation 

- régime de nuit : idem, en dehors de la période d'occupation 

- régime de sécurité : ce régime a pour but d'éviter, pendant le régime de nuit, que les conditions climatiques ne franchissent pas certaines limites dans les locaux 

- régime accéléré : quelques temps avant le début de la période d'occupation, on passe au régime accéléré afin d'atteindre les conditions climatiques exigées au début de la période d'occupation 

Remarques : 

- Dans certains cas, deux régimes peuvent coïncider (voir applications spécifiques : 4.2. et suivants). 

- Les "conditions climatiques" dépendent du type d'installation thermique ; pour le chauffage il s'agit de la température minimale et pour le conditionnement d'air de la température et éventuellement l'humidité relative, etc. La température minimale dépend aussi de la température extérieure. 

La commutation entre les différents régimes est déterminée comme suit : 

- Commutation normale vers nuit : Cette commutation a lieu quelques temps avant la fin de la période d'occupation, le plus tôt possible, mais néanmoins de telle façon qu'on obtienne à la fin de cette période dans les locaux des conditions climatiques ne franchissant pas des valeurs limites réglables ; l'intervalle de temps entre cette commutation et la fin de la période d'occupation a des limites minimale et maximale réglables. 

- Commutation nuit vers sécurité : Cette commutation a lieu si les conditions climatiques dans les locaux franchissent des limites réglables ; si les conditions climatiques reviennent suffisamment dans les limites, on repasse au régime de nuit. 

- Commutation nuit vers accéléré : Cette commutation a lieu avant le début de la période d'occupation aussi tard que possible mais néanmoins de telle façon qu'on obtienne au début de cette période des conditions climatiques dans les locaux ne franchissant pas les valeurs limites réglables ; l'intervalle de temps entre cette commutation et le début de la période d'occupation a des limites minimale et maximale réglables. 

- Commutation accéléré vers normal : Cette commutation a lieu dès que la période d'occupation est commencée ou que les conditions climatiques souhaitées sont atteintes ; une combinaison de ces deux conditions doit être également possible. 

Les moments de commutation aux régimes nuit et accéléré sont calculés à l'aide des températures intérieure et extérieure, des valeurs limites réglables pour les conditions climatiques, des propriétés du bâtiment et de l'installation, du nombre de générateurs de chaleur en service et des résultats des calculs précédents (c.à.d. auto-adaptation). Cette auto-adaptation ne peut cependant pas avoir une influence trop rapide ; en particulier, il faut éviter que des conditions temporaires ne perturbent les calculs ultérieurs. Lorsque le système optimalisé est équipé d'une post-régulation indépendante, l'écart entre les points de consigne de l'optimalisation et de la post-régulation doit être suffisamment grand, pour éviter l'influence mutuelle. En outre, le fonctionnement de l'auto-adaptation est déclenchable. 

- Pour chaque circuit, on peut obtenir les données suivantes sur l'affichage de l'appareil de commande :

- le régime actuel 

   - le moment et la nature des deux dernières commutations de régime, ainsi que la température intérieure au moment des commutations

**4.1.4. Commande des pompes** 

Toutes les pompes et tous les circulateurs commandés par l'A.R.C.P. sont démarrés pour quelques minutes au moins une fois toutes les 24 heures, afin d'éviter le grippage. 

Pour toutes les pompes et tous les circulateurs commandés en relation avec d'autres éléments (tels que brûleurs, robinets à trois voies), il est prévu une temporisation réglable à l'arrêt. 

Les pompes de réserve sont enclenchées en cas de panne des autres pompes. 

**4.1.5. Généralités relatives aux programmes d'application** 

- Dans les programmes d'application ci-après sont utilisés les références (1), (2), (3), (4) et (x/y). 

La signification en est la suivante : 

- (1) : On doit prévoir un point par élément. Par ex. : Pour le point "fonctionnement brûleur, marche/arrêt", il y a lieu de prévoir un point distinct pour chaque brûleur. 

- (2) : Ce point ne doit être prévu que s'il est d'application. Par ex. : Il est évident que le point "fonctionnement brûleur, petite flamme/grande flamme" ne sera pas prévu pour un brûleur à réglage tout ou rien. 

- (3) : Ce point nécessite la présence d'un "convertisseur" (p.ex. sonde, thermostat, servomoteur) ne faisant pas partie de l'A.R.C.P. 

- (4) : Ce point ne doit être prévu que si l'élément contrôlé ou le convertisseur nécessaire est prévu. 

   - P.ex. : le point "détecteur de débit" n'est prévu qu'en cas de présence de pareil élément dans l'installation. 

(x/y) : il s’agit d’une référence locale, dont la signification est donnée à la page concernée 

- Il y a deux possibilités pour la commande des robinets à deux et à trois voies et des registres d'air, et ce suivant que cette commande est classée parmi : 

   - les points de commande logiques : en l'occurrence, le robinet ou le registre peut prendre deux positions (ouvert ou fermé) 

   - les points de commande analogiques : en l'occurrence, la commande est proportionnelle, c.à.d. que le robinet ou le registre prend une position proportionnelle à la valeur de commande donnée par l'A.R.C.P. 

- Dans certains cas, un point de commande analogique peut être remplacé par plusieurs points logiques. 

- Dans le cas de pompes dédoublées (dont l'une est en réserve ou non), on prévoit des points séparés pour chaque pompe. 

- L'état de fonctionnement (marche ou arrêt) des moteurs de ventilateurs et pompes est déterminé par un contrat auxiliaire sur le contacteur, pour autant que le déclenchement de la protection du moteur contre les courts-circuits et les surcharges provoque également le déclenchement du contacteur. Dans les autres cas, l'état de fonctionnement est déterminé par le contrôle de la tension aux bornes du moteur. 

- Dans le cas où un moteur est alimenté par un convertisseur de fréquence, le signal de dérangement de ce dernier est prévu comme point de mesure logique, même s’il ne figure pas dans les listes de points, telles que reprises ci-après.

- Si un point identique est mentionné dans plusieurs programmes, il ne doit être prévu qu'une seule fois. 

- Lorsque le cahier spécial des charges prescrit plusieurs sondes pour la température intérieure d'un circuit ou d'un groupe de traitement d'air, il y a lieu de prévoir un point particulier par sonde. 

   - Dans les calculs, on tient compte de la température moyenne pondérée de ces points ; les points restent cependant indépendants, c.à.d. qu'on peut demander la température de chaque sonde séparément. 

**4.1.6. Contrôle des commutateurs manuels** 

Ceci concerne le contrôle des commutateurs manuels (pour pompes, ventilateurs, brûleurs) qui se trouvent sur les tableaux électriques (voir l'art. C22. par. 3. point 1.2.2. et 2.2.2.). 

Pour chaque commutateur à contrôler, il y a un point de mesure logique, qui indique si le commutateur se trouve ou non dans la position "automatique", c.à.d. si la commande par l'A.R.C.P. est oui ou non possible. Dans ce dernier cas, une alarme est donnée sur l'appareil de commande de l'A.R.C.P. 

Si la pompe, le ventilateur, etc., à commander possède en plus un interrupteur de sécurité (voir l'art. C22. par. 3. point 1.5.), la position de celui-ci est également incluse dans le contrôle. 

Le cahier spécial des charges détermine les commutateurs à contrôler. 

**4.2. Commande des chaudières** 

Ce programme s'applique à un ensemble de chaudières raccordées hydrauliquement. 

**4.2.1. Points** 

Les points suivants sont prévus. 

- Points de mesure logiques : 

   - fonctionnement brûleur, marche/arrêt (1) * fonctionnement brûleur, petite flamme/grande flamme (1) (2) * mise en sécurité brûleur (1) * fonctionnement pompe primaire, marche/arrêt (1) (x) * détecteur de débit, côté hydraulique (1) (3) (4) (x) * niveau d'eau trop bas (à ne prévoir qu'en cas de système d'expansion sous pression d'air, ou si des interrupteurs de niveau sont prévus dans les chaudières) 

- Points de commande logiques : 

|-|Points de commande logiques :||
|---|---|---|
||* fonctionnement brûleur, marche/arrêt|(1)|
||(Cette commande est subordonnée à l'aquastat de||
||sécurité et, éventuellement, à d'autres dispositifs de sécurité)||
||* fonctionnement brûleur, petite flamme/grande flamme|(1) (2)|
||* fonctionnement pompe primaire, marche/arrêt|(1) (x)|
||* commande robinet d'arrêt motorisé de chaudière, ouvert/fermé|(1) (3) (4)|
|-|Points de mesure analogiques :||
||* température générale d'eau de départ des chaudières|(3)|
||* température générale d'eau de retour vers les chaudières|(3) (4)|
||* température de départ, condenseur des gaz de combustion|(3) (4)|
||(ou chaudière à condensation)||
||* température de retour, condenseur des gaz de combustion|(3) (4)|
||(ou chaudière à condensation)||
||* température générale d'eau de départ après bouteille casse-pression|(3) (4)|
||* température générale d'eau de retour avant bouteille casse-pression|(3) (4)|

* température extérieure 

* chaleur produite (compteur de chaleur) 

* combustible consommé (compteur gaz ou fuel) 

(3) (1) (3) (4) (y) (1) (3) (4) 

- Points de commande analogiques 

* modulation brûleur (1) (2) 

Référence (x) : ce point doit également être prévu pour le condenseur des gaz de combustion (si présent) Référence (y) : si le compteur de chaleur a des sorties séparées pour les températures mesurées et les débits, ces données sont également à prévoir comme points de mesure analogiques. 

**4.2.2. Fonctionnement** 

Le programme détermine en premier lieu la consigne pour la température d'eau de départ. A cet effet, il reçoit de chaque programme de régulation des circuits de distribution de chaleur la température d'eau exigée par ces circuits (voir programmes 4.3. et suivants). Si une régulation de circuit de distribution ne peut pas transmettre de consigne (p.ex. parce qu'elle n'est pas raccordée à l'A.R.C.P.), ladite consigne est alors simulée par une régulation en fonction de la température extérieure. 

La plus grande de ces consignes, majorée de 5°C est considérée comme la consigne pour la température d'eau de départ. Eventuellement (selon le choix de l'utilisateur), cette dernière consigne ne descendra jamais sous une limite réglable, ou ne descendra jamais sous une telle limite tant que l'un des circuits de distribution demande de la chaleur. Il y a également une limite supérieure. 

Ensuite, cette consigne est comparée à la valeur mesurée de la température d'eau de départ. L'écart est transmis à un régulateur commandant le fonctionnement des brûleurs (marche/arrêt ainsi que, le cas échéant, le réglage de la puissance). 

L'enclenchement des différents brûleurs ou des allures des brûleurs se fait en cascade. Le démarrage se fait à l'allure la plus réduite de la première chaudière. Ensuite la puissance de celle-ci est augmentée ; quand la première chaudière fonctionne à pleine puissance, la deuxième peut être mise en route. Idem pour les suivantes. 

Le déclenchement se fait par contre dans un ordre différent. Lors d'une demande de chaleur décroissante, la puissance des chaudières en fonctionnement est diminuée à commencer par la dernière. Seulement quand toutes les chaudières fonctionnent à l'allure la plus réduite, la dernière chaudière est déclenchée, ensuite l'avant-dernière, etc. 

Si la possibilité existe, au moyen d'un robinet d'isolement motorisé ou par l'arrêt d'une pompe (individuelle par chaudière), la circulation d'eau dans les chaudières hors fonctionnement est arrêtée. Cependant, avec des chaudières avec régulation tout ou rien, dans le cas d'une demande de chaleur décroissante, la circulation d'eau dans une chaudière qui a été déclenchée n'est arrêtée qu'au moment où la chaudière suivante est également déclenchée : ceci afin d'éviter que la circulation d'eau dans une chaudière ne soit sans cesse enclenchée et déclenchée. 

En outre, la circulation d'eau dans la première chaudière n'est jamais arrêtée. 

Le programme tient également compte des prescriptions suivantes : 

- Entre la mise à pleine puissance d'une chaudière et le démarrage de la suivante s'écoule une période réglable (celle-ci peut être différente pour chaque chaudière) afin d'éviter que toutes les chaudières ne soient toujours enclenchées pour le démarrage matinal. 

- A chaque chaudière est également attribuée une limite : la chaudière ne peut démarrer que si la température extérieure est au-dessous de cette limite. 

- Lorsqu'une chaudière ne démarre pas (p.ex. parce qu'elle est arrêtée manuellement ou parce que le débit d'eau est insuffisant, etc.) ou lorsqu'elle est en sécurité, on prend immédiatement la suivante.

- En ce qui concerne l'ordre dans lequel les chaudières sont mises en route, le programme prévoit deux possibilités : 

   - l'ordre est régulièrement alterné, par ex. une fois par semaine (cas normal) 

   - l'ordre est fixe (d'application si les chaudières ont un rendement différent ; par exemple chaudière à condensation et chaudière normale) 

Enfin, le programme commande également les pompes primaires. Cela implique qu'en cas de consigne de la température d'eau de départ inférieure à 20°C, les pompes sont arrêtées. Dans les autres cas, elles fonctionnent. Si aucune pompe ne fonctionne, les brûleurs sont arrêtés. 

Il est également prévu un totalisateur du temps de fonctionnement de chaque brûleur séparément (pour les brûleurs "tout ou peu", totalisation séparée pour la petite ou la grande flamme). 

**4.3. Circuits de chauffage** 

Ce programme s'applique à tout circuit de chauffage équipé de corps de chauffe statiques dont la régulation s'opère au moyen d'un robinet modulant. 

**4.3.1. Régulation avec sonde intérieure** 

**4.3.1.1. Points** 

Les points suivants sont prévus. 

- Points de mesure logiques : 

* fonctionnement circulateur, marche/arrêt 

- Points de commande logiques : 

   - fonctionnement circulateur, marche/arrêt 

- Points de mesure analogiques : 

* température intérieure (3) 

- Points de commande analogiques : 

* robinet modulant (3) 

**4.3.1.2. Fonctionnement** 

Il y a deux régimes : régime de jour et de nuit. 

La commutation se fait comme suit (sans optimalisation) : 

- commutation de nuit vers jour : à un intervalle de temps fixe (mais réglable) avant le début de la période d'occupation 

-

- commutation de jour vers nuit : à un intervalle de temps fixe (mais réglable) avant la fin de la période d'occupation 

A chaque régime est liée une consigne pour la température intérieure. Cette consigne est comparée à la valeur mesurée. L'écart est transmis à un régulateur commandant le robinet modulant. A partir de ce signal est également déterminée la température d'eau de départ envoyée au programme de chaudière. 

**4.3.2. Régulation avec sonde extérieure**

**4.3.2.1. Points** 

Les points suivants sont prévus. 

- Points de mesure logiques : 

   - fonctionnement circulateur, marche/arrêt 

- Points de commande logiques : 

   - fonctionnement circulateur, marche/arrêt 

- Points de mesure analogiques : 

* température extérieure (3) * température d'eau de départ (3) * intensité du rayonnement solaire (3) (4) 

- Points de commande analogiques : 

* robinet modulant 

(3) 

**4.3.2.2. Fonctionnement** 

Il y a trois régimes : jour, nuit et accéléré. 

La commutation se fait comme suit (sans optimalisation) : 

- commutation de nuit vers accéléré : 

à un intervalle de temps fixe (mais réglable) avant le début de la période d'occupation 

- commutation d'accéléré vers jour : au début de la période d'occupation 

- commutation de jour vers nuit : 

à un intervalle de temps fixe (mais réglable) avant la fin de la période d'occupation 

A chaque régime correspond une courbe de chauffe d'un régulateur en fonction de la température extérieure. Le signal de sortie de celui-ci est comparé à la température d'eau de départ mesurée. L'écart entre les deux valeurs est transmis à un régulateur commandant le robinet modulant. 

**4.3.3. Régulation avec sondes intérieure et extérieure - optimalisation** 

**4.3.3.1. Points** 

Les points mentionnés sous 4.3.2.1. sont prévus, avec comme point de mesure analogique supplémentaire la température intérieure. (3) 

**4.3.3.2. Fonctionnement** 

Il y a quatre régimes à commutation optimalisée décrite sous le point 4.1.3. 

Les régimes correspondent comme suit aux courbes de chauffe d'un régulateur en fonction de la température extérieure : 

|<br>es correspondent comme suit<br>ure extérieure :|<br>aux courbes de chauffe d'un rég|
|---|---|
|**régime**|**courbe de chauffe**|
|normal|jour|
|nuit|pas de chauffage|
|sécurité|nuit|
|accéléré|accéléré|



Le signal de sortie du régulateur en fonction de la température extérieure est comparé à la température d'eau de départ. L'écart entre les deux valeurs est transmis à un régulateur commandant le robinet modulant.

**4.4. Production d'[[concepts/eau-chaude-sanitaire|Eau Chaude Sanitaire]]** 

**4.4.1. Echangeur-accumulateur** 

Ce programme s'applique à tout échangeur-accumulateur. 

**4.4.1.1. Points** 

Les points suivants sont prévus. 

- Points de mesure logiques : 

* fonctionnement circulateur "primaire", marche/arrêt 

* fonctionnement circulateur circuit de circulation d'[[concepts/eau-chaude-sanitaire|Eau Chaude Sanitaire]], marche/arrêt (1) (4) 

- Points de commande logiques : 

   - fonctionnement du circulateur "primaire", marche/arrêt 

* fonctionnement du circulateur circuit de circulation d'[[concepts/eau-chaude-sanitaire|Eau Chaude Sanitaire]], marche/arrêt (1) (4) * fonctionnement de l’élément de chauffe électrique, marche/arrêt (4) 

- Points de mesure analogiques : 

* température de l'eau distribuée (3) 

* température de retour de l'eau de la boucle de circulation (1) (3) (4) 

- 

- Points de commande analogiques : 

* robinet modulant (3) 

**4.4.1.2. Fonctionnement** 

La valeur mesurée de la température d'eau est comparée à la consigne. L'écart est transmis à un régulateur commandant le robinet modulant et déterminant également la température d'eau de départ envoyée au programme de chaudière. 

Lorsque la [[concepts/production-de-chaleur|Production de Chaleur]] est hors service, le régulateur commande un élément de chauffe électrique marche/arrêt (si celui-ci existe) au lieu du robinet modulant. 

Il est prévu un programme horaire ; en dehors des heures d'occupation, l'accumulateur n'est pas maintenu à température, et le circulateur du circuit de circulation est hors service. Un programme de désinfection commandé manuellement permet de rehausser la température de l’eau de distribution temporairement. 

**4.4.2. Appareil de production d'eau chaude par accumulation, à gaz** 

Ce programme s'applique à un appareil de production d'eau chaude par accumulation, à gaz. 

**4.4.2.1. Points** 

Les points suivants sont prévus. 

- Points de mesure logiques : 

   - fonctionnement brûleur, marche/arrêt 

   - mise en sécurité brûleur 

   - fonctionnement circulateur du circuit de circulation, marche/arrêt (1) (4) 

- Points de commande logiques : 

   - fonctionnement brûleur, automatique/arrêt 

   - fonctionnement circulateur du circuit de circulation, marche/arrêt (4)

- Points de mesure analogiques : 

* température de l’eau distribuée (3) * température de retour de l'eau de la boucle de circulation (1) (3) (4) 

**4.4.2.2. Fonctionnement** 

Le thermostat de l'appareil commande directement le brûleur, sans intervention de l'A.R.C.P. 

Un programme horaire interdit cependant le fonctionnement du brûleur en dehors des heures d'occupation, et arrête également le circulateur du circuit de circulation. 

Une totalisation du temps de fonctionnement du brûleur est prévue. 

**4.5. Groupe de traitement d'air

- 100 % d'air neuf

- Température de pulsion fixe** 

Ce programme s'applique aux groupes de ventilation, fonctionnant en air neuf exclusivement. 

En dehors de la batterie de chauffe, le groupe peut également comprendre : 

- un système de récupération de chaleur 

- une batterie de refroidissement (à eau glacée) 

-

- un système d'humidification (éventuellement à batterie de préchauffe) 

La régulation est du type à température de pulsion fixe. Elle commande également l'humidification, mais pas la déshumidification. 

Le programme s'applique également : 

- aux groupes qui desservent plusieurs zones. Chaque zone possède des registres d'air sur la pulsion et l'extraction, qui sont fermés lorsque la zone n'est pas utilisée. 

-

- aux ventilateurs-extracteurs séparés (p.ex. pour des sanitaires) 

Les éléments qui font partie du circuit aéraulique du groupe de traitement d’air (comme les clapets coupe-feu) sont également concernés par les dispositions suivantes. 

**4.5.1. Points** 

Les points suivants sont prévus. 

- Points de mesure logiques : 

* thermostat antigel (3) * fonctionnement ventilateur de pulsion, marche/arrêt * fonctionnement ventilateur d'extraction, marche/arrêt * fonctionnement circulateur batterie de chauffe, marche/arrêt * fonctionnement circulateur batterie de préchauffe, marche/arrêt (4) * fonctionnement circulateur batterie de refroidissement (4) * pressostat filtre à air (1) (3) (4) * détecteur de débit (côté aéraulique) ou pressostat différentiel (1) (3) (4) * commutateur ou boutons-poussoirs de commande à distance (4) * détecteur de présence (3) (4) * position clapet coupe-feu type B, ouvert/position intermédiaire/fermé (1) (3) (4) * alarme incendie (x) * commande prioritaire fonctionnement ventilateur de pulsion (marche / automatique) (y) * commande prioritaire fonctionnement ventilateur de pulsion (arrêt / automatique) (y) * commande prioritaire fonctionnement ventilateur d’extraction (marche / automatique) (y) * commande prioritaire fonctionnement ventilateur d’extraction (arrêt / automatique) (y)

- Points de commande logiques 

* fonctionnement ventilateur de pulsion, marche/arrêt (3) * fonctionnement ventilateur d'extraction, marche/arrêt (3) * registres d'air, ouvert/fermé (3) * fonctionnement ventilateur de pulsion et d'extraction, (2) petite/grande vitesse (éventuellement plus de deux vitesses) * fonctionnement circulateur batterie de chauffe, marche/arrêt * fonctionnement circulateur batterie de préchauffe, marche/arrêt (4) * fonctionnement circulateur batterie de refroidissement, marche/arrêt (4) * fonctionnement récupérateur de chaleur, marche/arrêt (4) (p. ex. circulateur de batteries, moteur d'un échangeur rotatif, registres by-pass) * fonctionnement humidification, marche/arrêt (4) (p. ex. pompe de laveur d'air) * régulation de l'humidification par paliers (2) (4) * registres d'air (sur la pulsion et l'extraction) d'une zone, ouvert/fermé (3) (4) (un point par zone) * clapet coupe-feu de type B, ouvert/fermé (1) (3) (4) 

- Points de mesure analogiques : 

* température air pulsé (3) * température intérieure (3) (4) * humidité relative air repris (3) (4) * humidité relative air pulsé (3) (4) * consommation électrique ventilateur (1) (3) (4) 

- Points de commande analogiques : 

* robinet modulant batterie de chauffe (3) * robinet modulant batterie de préchauffe (3) (4) * robinet modulant batterie de refroidissement (3) (4) * régulation de l'humidification (2) (3) (4) 

- (p. ex. registres by-pass, robinet modulant pour laveur d'air ou pour humidificateur à vapeur) 

**Remarques :** 

- Référence (x) : cette alarme provient de la centrale de détection incendie (cette centrale ne fait pas partie de l’entreprise) ; il faut prévoir un point par compartiment incendie (même s’il n’y a pas de centrale de détection incendie) 

- Référence (y) : cette commande provient d’un tableau « pompiers » central ; s’il n’y a pas de tableau « pompiers » central, ou dans le cas où la commande « incendie » se fait à partir de la centrale de conduite (voir art. C21 par. 8 point 4.5.), ces points ne sont pas à prévoir (cas le plus courant). 

- Pour les ventilateurs-extracteurs séparés, seuls les points relatifs au ventilateur et à ses accessoires (tels que clapets coupe-feu, etc.) doivent être prévus. 

**4.5.2. Fonctionnement** 

**4.5.2.1. Programme de base** 

Ce programme s'applique à un groupe de ventilation équipé uniquement d'une batterie de chauffe. 

La valeur mesurée de la température de l'air pulsé est comparée à la consigne. L'écart est transmis à un régulateur qui commande le robinet modulant de la batterie de chauffe. 

En dehors de la période d'occupation, les ventilateurs sont arrêtés, les registres d'air sont fermés, le circulateur est arrêté et le robinet modulant est fermé. Il est également possible de programmer pendant la période d'occupation des périodes plus courtes durant lesquelles le groupe est également arrêté.

Lors du fonctionnement du thermostat antigel, le robinet modulant de la batterie de chauffe est entièrement ouvert, le circulateur est mis en marche et les registres d'air sont fermés. En outre les ventilateurs sont arrêtés en agissant directement sur les circuits de commande des moteurs, donc sans intervention de l'A.R.C.P. 

Lorsqu’aucun débit n’est détecté au cas où un ventilateur devrait être en marche, ce ventilateur est mis à l’arrêt et une alarme est transmise. 

Lorsque la température de l'air pulsé dépasse une limite réglable, ou dans le cas d'une alarme incendie, les ventilateurs sont arrêtés et les registres d'air sont fermés ; tous les clapets coupe-feu de type B sont également fermés. 

Une alarme est également transmise à l'appareil de commande. Le groupe ne peut être remis en route après la disparition de la température trop élevée ou de l'alarme incendie, que par une commande manuelle à partir de l'appareil de commande. Pour les groupes de traitement d’air qui alimentent plusieurs compartiments incendie la possibilité existe de ne fermer que les clapets coupefeu de type B du compartiment sinistré et tandis que le groupe de traitement d’air reste en fonctionnement; ce mode de commande n’est appliqué que pour des cas spéciaux, c’est-à-dire si le cahier spécial des charges ou le [[concepts/fonctionnaire-dirigeant|Fonctionnaire Dirigeant]] l’impose. 

**4.5.2.2. Extensions** 

Si le groupe de ventilation est équipé de refroidissement, d'humidification, d'une commande à distance, commande prioritaire en cas d’incendie etc., le programme de base est étendu aux programmes correspondants qui sont décrits ci-dessous. 

- Refroidissement, récupération de chaleur, préchauffe 

Le régulateur de température de l'air pulsé opère en cascade les actions suivantes lors d'une demande de chaleur décroissant : 

- fermeture progressive du robinet modulant de la batterie de chauffe 

- mise à zéro progressive de la limitation de l'ouverture du robinet modulant de la batterie de préchauffe (rem. : la commande proprement dite est réalisée par un autre régulateur) 

- déclenchement du système de récupération de chaleur 

- ouverture progressive du robinet modulant de la batterie de refroidissement 

- Lors d'une demande de chaleur croissante, on suit le chemin inverse. 

Dans le cas où certains éléments ne sont pas prévus (p.ex. refroidissement), le programme ne commande évidemment que ceux qui sont présents. 

- Humidification 

   - Sans batterie de préchauffe 

L'humidification est commandée (modulante, par paliers ou marche/arrêt suivant le cas) par un régulateur en fonction de l'humidité relative de l'air repris, sans que l'humidité de l'air pulsé ne dépasse pour autant une certaine limite. 

- Avec batterie de préchauffe 

Idem. La batterie de préchauffe est commandée par un régulateur en fonction de l'humidité absolue de l'air pulsé (celle-ci est calculée au moyen de l'humidité relative et de la température), tenant compte de la limitation mentionnée ci-dessus (voir le point "refroidissement, récupération de chaleur, préchauffe").

- Balayage nocturne 

Ce programme est prévu lorsqu'il y a une sonde de température intérieure (éventuellement appartenant à une autre régulation) dans un des locaux desservis. 

Ce programme met le groupe en marche à débit maximal, sans chauffage, refroidissement, humidification, récupération de chaleur ou air recyclé, dès que les conditions suivantes sont réunies : 

- On se trouve en dehors de la période d'occupation. 

- La température intérieure dépasse une limite réglable (p.ex. 25°C). 

- La température extérieure est d'au moins 3°C plus basse que la température intérieure. 

- La température extérieure n'est pas au-dessous d'une limite réglable (p.ex. 10°C). 

Le groupe est arrêté lorsque la température intérieure descend en-dessous d'une limite réglable (p.ex. 20°C) 

- 

- Ventilateurs à deux ou plusieurs vitesses 

Il existe un programme horaire indépendant pour chaque vitesse. 

- 

- Commutateur de commande à distance 

Le groupe ne fonctionnera que si la programmation horaire de l'A.R.C.P. ainsi que le commutateur se trouvent dans la position "fonctionnement". Idem pour le fonctionnement à grande vitesse pour des groupes à deux vitesses. 

- 

- Commande à distance à boutons-poussoirs 

Le groupe ne fonctionnera que lorsqu'on a poussé sur un bouton-poussoir "fonctionnement" (en cas de deux vitesses : petite vitesse ou grande vitesse selon le bouton-poussoir). 

Le groupe s'arrête si on pousse sur le bouton "arrêt". En outre, on peut programmer un nombre de moments auxquels le groupe s'arrête (c.à.d. équivalent du bouton "arrêt"). A l'aide du bouton "fonctionnement", le groupe peut à nouveau être mis en marche. 

- 

**Détecteur de présence** 

Le groupe est enclenché quelques minutes après qu'on ait détecté la présence de personnes dans le local. Le groupe est déclenché lorsqu'il n'y a plus de présence depuis une dizaine de minutes. En dehors de la période d'occupation programmée (voir ci-dessus), le groupe ne peut jamais fonctionner. 

- 

- Commande prioritaire en cas d’incendie 

Ces commandes ont priorité sur tous les autres programmes et commandes de l’A.R.C.P. La commande prioritaire en cas d’incendie peut se faire de deux façons : 

- Par une centrale de conduite : voir art. C21 par. 8 point 4.5. 

- Par un tableau pompiers central : 

   - Lorsqu’un ventilateur (soit de pulsion, soit d’extraction) est mis à l’arrêt à partir de ce tableau de commande, tous les clapets coupe-feu de type B du réseau aéraulique correspondant sont également fermés. 

   - Lorsqu’un ventilateur (soit de pulsion, soit d’extraction) est remis en marche à partir de ce tableau de commande en cas d’alarme incendie, tous les

clapets coupe-feu de type B du réseau aéraulique correspondant sont réouverts dans les compartiments non sinistrés; les ventilateurs à plusieurs vitesses fonctionnent à la vitesse supérieure. 

**4.5.2.3. Système multizone** 

La régulation se fait comme décrit dans 4.5.2.1. et 4.5.2.2. Chaque zone possède cependant son propre programme horaire indépendant. 

Le débit d'air du groupe est ajusté au mieux suivant le nombre de zones en fonctionnement. Exemple : un groupe avec des ventilateurs à deux vitesses dessert deux zones à débit d'air égal. Dès que les registres d'air d'une zone sont ouverts (commandés par le programme horaire), le groupe démarre à petite vitesse. Lorsque les deux zones sont en service, le groupe fonctionne à grande vitesse. 

Chaque zone peut en plus être munie d'une commande à distance ou d'une détection de présence. Le fonctionnement se fait comme décrit dans 4.5.2.2. 

**4.5.2.4. Ventilateurs-extracteurs séparés** 

Il y a deux possibilités : 

- Le ventilateur fonctionne toujours simultanément avec un autre groupe de ventilation ou de traitement d'air, et il est donc commandé par le programme de ce groupe. 

- Le ventilateur fonctionne indépendamment et il a son propre programme de commande. Celui-ci répond à toutes les prescriptions mentionnées ci-dessus qui concernent la commande du ventilateur-extracteur. 

**4.6. Groupe de traitement d'air

- Air neuf et repris

- Température de pulsion variable** 

Ce programme s'applique aux groupes de traitement d'air, à air neuf et repris. 

En dehors de la batterie de chauffe et des registres de mélange d'air, le groupe peut également comprendre : 

- un système de récupération de chaleur 

- une batterie de refroidissement (à eau glacée) 

- un système d'humidification (éventuellement à batterie de préchauffe) 

La régulation se fait en fonction de la température et de l'humidité intérieures. Cependant une déshumidification contrôlée n'est pas possible. 

Le programme ne s'applique pas aux installations à volume variable, aux boîtes de mélange, aux éjecto-convecteurs, etc. 

Les éléments qui font partie du circuit aéraulique du groupe de traitement d’air (comme les clapets coupe-feu) sont également concernés par les dispositions suivantes. 

**4.6.1. Points** 

Les points suivants sont prévus. 

- Points de mesure logiques : voir 4.5.1., complété par 

* détecteur de fumée dans l’air repris (3) (4) 

- Points de commande logiques : voir 4.5.1. 

- Points de commande analogiques : voir 4.5.1., complété par :

* température air frais (3) * température air repris (3) * température intérieure (3) * qualité de l'air repris (3) (4) 

- Points de commande analogiques : voir 4.5.1., complété par : 

* registres d'air frais /repris/refoulé (3) * régulation du récupérateur de chaleur (3) (4) (p.ex.robinet modulant de batteries, vitesse d'un échangeur rotatif, registres by-pass) 

**4.6.2. Fonctionnement** 

_4.6.2.1. Programme de base_ 

Ce programme s'applique à un groupe de traitement d'air équipé d'une batterie de chauffe et de registres de mélange d'air. 

Le groupe peut fonctionner selon quatre régimes différents (voir 4.1.3.). La commutation se fait par le programme d'optimalisation. 

Le fonctionnement est le suivant : 

- Régime normal 

La température de l'air repris (ou de l'air ambiant) est comparée à la consigne. L'écart est transmis à un régulateur donnant la consigne pour la température de l'air pulsé et transmettant la température d'eau de départ exigée au programme de la chaudière. La consigne pour la température de l'air (avec limite basse), est comparée à la valeur mesurée. L'écart est transmis à un second régulateur. 

Ce régulateur opère en cascade les actions suivantes lors d'une demande de chaleur décroissante : 

- Fermeture progressive du robinet modulant de la batterie de chauffe. Dans cette phase, les registres d'air se trouvent dans la position d'air frais minimale (celle-ci est réglable). 

- Ouverture progressive des registres d'air. Lorsque la température de l'air frais est supérieure à celle de l'air repris, les registres d'air reprennent la position minimale. 

Lors d'une demande de chaleur croissante, on suit le chemin inverse. 

Le fonctionnement de la surveillance de la température de l'air pulsé, de l'alarme incendie et du thermostat antigel se fait comme décrit dans 4.5.2.1. 

Lorsque le groupe de traitement d’air reste en fonctionnement en cas d’alarme incendie (voir 4.5.2.1 dernière phrase) ou en cas de détection de fumées dans l’air repris, le groupe fonctionne avec 100% d’air frais. 

- Régime de nuit 

Le groupe est tout à fait arrêté. 

Cependant, le programme pour balayage nocturne (voir 4.5.2.2.) est d'application. 

- Régime de sécurité 

Idem régime normal, mais le débit d'air frais minimal est de zéro.

- Régime accéléré 

Idem régime de sécurité. 

**4.6.2.2. Extensions** 

Si le groupe de traitement d'air est équipé de refroidissement, d'humidification, d'une commande à distance, etc., le programme de base est étendu aux programmes correspondants qui sont décrits cidessous. 

- 

**Refroidissement, récupération de chaleur, préchauffe** 

Le régulateur de température de l'air pulsé opère en cascade les actions suivantes lors d'une demande de chaleur décroissante : 

- Fermeture progressive du robinet modulant de la batterie de chauffe. 

- Mise à zéro progressive de la limitation de l'ouverture du robinet modulant de la batterie de préchauffe (rem. : la commande proprement dite est réalisée par un autre régulateur). 

- Déclenchement progressif du système de récupération de chaleur; dans les trois phases mentionnées ci-dessus, les registres d'air se trouvent dans la position d'air frais minimale (celle-ci est réglable). 

- Ouverture progressive des registres d'air. Lorsque la température de l'air frais est supérieure à celle de l'air repris, les registres d'air reprennent la position minimale. 

- Augmentation progressive de la limitation de l'ouverture du robinet modulant de la batterie de refroidissement (rem. : la commande proprement dite est réalisée par un autre régulateur). 

Lors d'une demande de chaleur croissante, on suit le chemin inverse. 

La commande de la batterie de refroidissement est réalisée par la régulation suivante. 

D'abord on détermine la valeur de consigne pour la température de l'air repris. Celle-ci dépend de la température extérieure, et elle est la plus haute des deux valeurs suivantes : 

- une température fixe (réglable, p.ex. 24°C) 

- une température qui est la température extérieure moins une valeur fixe (réglable, p.ex. 5°C) 

La valeur de consigne ainsi obtenue est comparée à la valeur mesurée de l'air repris. L'écart est transmis à un régulateur qui commande le robinet modulant de la batterie de refroidissement, tenant compte de la limitation mentionnée ci-dessus. 

- Humidification 

Celle-ci se fait comme décrite dans 4.5.2.2. Pendant le régime de sécurité et accéléré, l'humidification est hors service. 

- 

**Mesure de la qualité de l'air repris** 

Cette mesure est transmise à un régulateur qui détermine la position minimale des registres d'air frais. Cette position minimale a cependant une limite supérieure fixe. 

- 

**Commande à distance et détection de présence** 

Le fonctionnement se fait comme décrit dans 4.5.2.2., complété comme suit :

- Le fonctionnement des régimes de nuit, de sécurité et accéléré ne peut pas être influencé. 

   - Pendant le régime normal, lorsque le groupe est arrêté par la commande à distance ou s'il n'y a pas de présence, le groupe est commuté en régime de nuit. Les limites pour la commutation vers le régime de sécurité (voir 4.1.3.) sont cependant différentes de ces limites pour le vrai régime de nuit (durant le vrai régime de nuit la commutation vers le régime de sécurité se fait si la température intérieure descend au-dessous de p. ex. 12°C. Si le groupe est arrêté pendant la période d'occupation, la commutation se fait si la température descend au-dessous de p.ex. 18°C). 

- 

**Ventilateurs à deux vitesses** 

La grande vitesse est utilisée dans le cas de refroidissement (free-cooling, balayage nocturne ou refroidissement normal). Si une commande à distance est prévue (voir cidessus), le choix des vitesses est déterminé par la commande à distance. 

- 

**Commande prioritaire en cas d’incendie** 

Le fonctionnement est tel que décrit au point 4.5.2.2., mais lorsqu’un ventilateur est mis en marche par la commande prioritaire, le groupe de traitement d’air fonctionne avec 100% d’air frais. 

**4.7. Aérothermes** 

Ces programmes s'appliquent aux aérothermes. 

**4.7.1.  Circuit d'aérothermes à air repris** 

Ce programme s'applique à tout ensemble d'aérothermes sans apport d'air frais. 

**4.7.1.1.  Points** 

Les points suivants sont prévus. 

- Points de mesure logiques : 

* fonctionnement circulateur, marche/arrêt 

- Points de commande logiques : 

   - fonctionnement circulateur, marche/arrêt 

   - fonctionnement ventilateurs des aérothermes, marche/arrêt 

(un point pour l'ensemble des ventilateurs) 

* commande robinet d'arrêt motorisé du circuit, ouvert/fermé (3) (4) 

- Points de mesure analogiques : 

* température intérieure (3) 

**4.7.1.2. Fonctionnement** 

Il y a deux régimes : régime de jour et de nuit. 

La commutation se fait comme suit (sans optimalisation) : 

- commutation de nuit vers jour : 

   - à un intervalle de temps fixe (mais réglable) avant le début de la période d'occupation

- commutation de jour vers nuit : à un intervalle de temps fixe (mais réglable) avant la fin de la période d'occupation 

A chaque régime est liée une consigne pour la température intérieure. Cette valeur est comparée à la valeur mesurée. Si la valeur mesurée est inférieure à la consigne, les ventilateurs se mettent en marche, une hystérésis réglable est prévue entre l'enclenchement et le déclenchement. 

Lorsque les ventilateurs sont arrêtés, le circulateur du circuit est arrêté également. Si un robinet d'arrêt motorisé est prévu sur le circuit, il est fermé. Au démarrage, les ventilateurs sont mis en marche quelques minutes après le circulateur. 

Si la température intérieure est inférieure à 5°C, le robinet s'ouvre toujours et le circulateur démarre pour éviter le risque de gel. 

**4.7.2. Circuit d'aérothermes à air frais (et repris)** 

Ce programme s'applique à tout ensemble d'aérothermes, dont un ou plusieurs fonctionnent à air frais, total ou partiel. 

**4.7.2.1. Points** 

Les points suivants sont prévus. 

- Points de mesure logiques : 

   - fonctionnement circulateur, marche/arrêt 


![](documents/CCT/Cahier%20des%20charges%20et%20annexes%20–%20HVAC/cct-105/images/CCT105TB_FR_2023.pdf-0570-11.png)


**----- Start of picture text -----**<br>
 * thermostat antigel   (3)<br>(s'il y en a plusieurs, ceux-ci sont raccordés en série)<br> * commutateur ou boutons-poussoirs de commande à distance    (4)<br> * détecteur de présence    (3) (4)<br>-  Points de commande logiques :<br> * fonctionnement circulateur, marche/arrêt<br> * fonctionnement ventilateurs des aérothermes qui peuvent fonctionner<br> uniquement avec de l'air repris, marche/arrêt<br>(un point pour l'ensemble des ventilateurs)<br> * fonctionnement ventilateur d'un aérotherme qui peut fonctionner<br>avec de l'air frais, marche/arrêt  (1)<br> * fonctionnement ventilateur d'extraction, marche/ arrêt   (1)<br> * registres d'air d'un aérotherme qui peut fonctionner avec de l'air frais,<br>air frais (+ repris)/air repris   (1) (3)<br> * fonctionnement ventilateur d'extraction, petite/ grande vitesse    (1) (2)<br>-  Points de mesure analogiques<br>* température intérieure    (3)<br>* température air pulsé d'un aérotherme à air frais   (1) (3) (4)<br>-  Points de commande analogiques<br> * robinet modulant   (3)<br>**----- End of picture text -----**<br>


**4.7.2.2. Fonctionnement** 

Il y a quatre régimes à commutation optimalisée comme décrit sous le point 4.1.3. 

**Régime normal** 

La consigne pour la température intérieure est comparée à la valeur mesurée. L'écart est transmis à un régulateur commandant le robinet modulant. A partir de ce signal est également déterminée la température d'eau de départ envoyée au programme de chaudière.

Si les aérothermes à air frais sont équipés d'une sonde de température d'air pulsé (indiqué dans le cas où certains aérothermes sont alimentés en air frais et d'autres non), la régulation du robinet se fait de manière à ce que la température de l'air pulsé ne descende pas au-dessous d'une limite réglable. Lorsque la température intérieure dépasse suffisamment la consigne, les ventilateurs des aérothermes à air repris sont arrêtés. 

Les aérothermes qui ont cette possibilité fonctionnent avec de l'air frais (ou avec un rapport fixe air frais/repris). S'il y en a plusieurs de ce type, il doit être possible (au moyen d'un programme horaire, ou d'un commutateur de commande à distance) de commander le nombre d’aérothermes qui fonctionnent avec de l'air frais. Les autres fonctionnent alors avec de l'air repris. Le fonctionnement des ventilateurs d'extraction est commandé en conséquence. 

Le fonctionnement du thermostat antigel, de la commande à distance et de la détection de présence (si celles-ci existent) se fait comme décrit au 4.6.2. 

**Autres régimes** 

En régime de sécurité et en régime accéléré, le fonctionnement est identique au régime normal mais tous les aérothermes fonctionnent avec de l'air repris. Pendant le régime de nuit, tous les ventilateurs et le circulateur sont arrêtés (le programme pour balayage de nuit (voir 4.5.1.2.) est d'application). 

**4.8. Circuit haute température** 

Ce programme s'applique à tout circuit à "haute température", c.à.d. un circuit sans régulation de température propre, par exemple pour l'alimentation d'une sous-station (éventuellement avec régulation de pression différentielle), de batteries pour groupes de traitement d'air, etc. 

Il n'est cependant pas d'application lorsque le circuit n'alimente qu'une seule batterie ou qu'un seul échangeur. En l'occurrence, le circuit appartient à la batterie ou à l'échangeur de chaleur. 

**4.8.1. Points** 

Les points suivants sont prévus : 

- Points de mesure logiques : 

   - fonctionnement circulateur ou pompe, marche/arrêt (1) * dérangement régulateur de vitesse de la pompe, normal/dérangement (1) (4) 

- Points de commande logiques : 

|-|Points de commande logiques :||
|---|---|---|
||* fonctionnement circulateur ou pompe, marche/arrêt|(1)|
|-|Points de mesure analogiques :||
||* pression différentielle collecteur|(3) (4)|
||* température collecteur de départ|(1) (3) (4)|
|-|Points de commande analogiques||
||* régulateur de vitesse de la pompe|(3) (4)|



**4.8.2. Fonctionnement** 

Le circulateur ou la pompe fonctionne en permanence. Il (elle) est arrêté (e) simultanément avec les pompes primaires (voir 4.2.2.). 

Si tous les robinets trois ou deux voies sur le collecteur sont fermés, la pompe est également mise à l’arrêt.

Au « départ froid » de l’installation les pompes sont mises en marche avec une temporisation par rapport aux pompes principales pour permettre que la température de retour vers les chaudières ne descende pas sous une valeur minimale. 

Dans le cas d’une régulation de pression différentielle d’un collecteur, la régulation se fait comme suit : la valeur de la pression différentielle entre le collecteur départ et le collecteur retour est transmis à un régulateur commandant la variation de vitesse de la pompe qui alimente le collecteur, afin de maintenir cette pression différentielle à une valeur préétablie. 

**4.9. Circuit ventilo-convecteurs avec batterie chaude et froide** 

Ce programme s’applique à chaque ensemble (c’est-à-dire relié hydrauliquement) de ventiloconvecteurs avec batterie chaude et froide. Il peut toutefois également être utilisé (mutatis mutandis) au cas où les ventilo-convecteurs n’ont qu’une batterie chaude ou froide. 

**4.9.1. Points** 

Les points suivants sont prévus: 

- Points de mesure logiques 

   - fonctionnement circulateur du circuit d'eau chaude, marche/arrêt 

   - fonctionnement circulateur du circuit d'eau glacée, marche/arrêt 

- 

   - Points de commande logiques 

      - fonctionnement circulateur du circuit d'eau chaude, marche/arrêt 

      - fonctionnement circulateur du circuit d'eau glacée, marche/arrêt 

      - autorisation de fonctionnement des ventilateurs des ventilo-convecteurs 

      - (1 seul point pour commande commune de tous les ventilateurs) 

- Points de mesure analogiques 

* température d'eau de départ du circuit d'eau chaude (3) * température d'eau de départ du circuit d'eau glacée (3) * température intérieure (3) 

- Points de commande analogiques 

   - robinet modulant circuit d'eau chaude (3) * robinet modulant circuit d'eau glacée (3) 

**4.9.2. Fonctionnement** 

Le circuit d'eau chaude est commandé comme décrit au point 4.3.3.2. 

Le circuit d'eau glacée est commandé pour une température constante de l'eau de départ (p.ex. 13°C); en régime de nuit et lorsque la production d'eau glacée est hors service, le robinet à trois voies est fermé et le circulateur est mis à l'arrêt. 

La commande des robinets de régulation sur les batteries des ventilo-convecteurs est assurée par des régulateurs autonomes locaux, indépendamment de l'A.R.C.P. 

En régime de nuit, les ventilateurs des ventilo-convecteurs sont mis à l'arrêt avec priorité sur la commande locale. 

**4.10. Production d’eau glacée** 

Ce programme s’applique à chaque ensemble (c’est-à-dire relié hydrauliquement) de machines frigorifiques.

**4.10.1. Machine frigorifique à condenseur refroidi par eau** 

**4.10.1.1. Points** 

Les points suivants sont prévus. 

- Points de mesure logiques 

|-|Points de mesure logiques||
|---|---|---|
||* machine frigorifique sous tension|(1)|
||* fonctionnement machine frigorifique, marche/arrêt|(1)|
||* fonctionnement machine frigorifique à pleine puissance|(1)|
||* alarme machine frigorifique, normal/dérangement|(1)|
||* manque d'eau dans le circuit d'expansion d'eau glacée||
||(à ne prévoir qu'en cas de système d'expansion à pression constante)||
||* fonctionnement pompe primaire d'eau glacée, marche/arrêt|(1)|
||* fonctionnement pompe d'eau de refroidissement, marche/arrêt|(1)|
||* fonctionnement ventilateur tour de refroidissement, marche/arrêt|(1)|
||* fonctionnement ventilateur tour de refroidissement, petite/grande vitesse|(1)|
||* fonctionnement système de traitement d'eau de refroidissement,||
||normal/dérangement|(4)|
||* manque d'eau dans tour de refroidissement|(1) (3)|
|-|Points de commande logiques||
||* fonctionnement machine frigorifique, automatique/arrêt|(1)|
||* fonctionnement pompe primaire d'eau glacée, marche/arrêt|(1)|
||* fonctionnement pompe d'eau de refroidissement, marche/arrêt|(1)|
||* fonctionnement ventilateur tour de refroidissement, marche/arrêt|(1)|
||* fonctionnement ventilateur tour de refroidissement, petite/grande vitesse|(1)|
||* commande de robinet d'arrêt motorisé sur eau de refroidissement, ouvert/fermé|(1) (3)|



|-|Points de mesure analogiques|||
|---|---|---|---|
||* température d'eau glacée à la sortie de machine frigorifique||(1) (3)|
||* température d'eau glacée à l'entrée du collecteur de départ|||
||des circuits de distribution||(3) (x)|
||* température d'eau glacée au départ général des machines frigorifiques||(3) (x)|
||* température d'eau glacée au retour général vers les machines frigorifiques||(3)|
||* température d'eau de refroidissement à la sortie de machine frigorifique||(1) (3)|
||* température d'eau de refroidissement au retour général|||
||vers les machines frigorifiques||(3)|
||* température extérieure||(3)|
||* froid produit (compteur d’énergie)|(1) (3) (4) (y)||
||* consommation électrique (compteur d’électricité)|(1) (3) (4)||



Référence (x) : ce point ne doit être prévu que lorsqu'il y a plusieurs machines frigorifiques. 

Référence (y) : si le compteur de chaleur a des sorties séparées pour les températures mesurées et les débits, ces données sont également à prévoir comme points de mesure analogiques 

**4.10.1.2. Fonctionnement** 

Le programme détermine d'abord si la production de froid est nécessaire et possible; à cet effet, il examine si les conditions suivantes sont remplies: 

- la température extérieure doit se situer au-dessus d'une certaine limite; 

- un programme horaire (voir 4.1.2.) ne peut entraver le fonctionnement (p.ex. le week-end ou la nuit); 

- les machines frigorifiques doivent être sous tension pendant un temps suffisamment long; 

- le niveau d'eau dans les tours de refroidissement doit être suffisant. 

Si ces conditions sont remplies, la production de froid est mise en marche; ceci comprend:

- l'ouverture du robinet motorisé sur le by-pass des tours de refroidissement 

- le démarrage d'une pompe d'eau de refroidissement 

- le démarrage d'une pompe d'eau glacée 

- l'autorisation de fonctionnement de la machine frigorifique correspondante; la régulation du fonctionnement de cette machine se fait via son propre thermostat ou régulation automatique, indépendamment de l'A.R.C.P. 

Dès que la température de l'eau de refroidissement est suffisamment élevée (mesurée sur le retour général vers les machines frigorifiques), les robinets d'arrêt motorisés sur les tuyauteries de l'eau de refroidissement vers une tour de refroidissement sont ouverts, et ceux du by-pass fermés. Les ventilateurs de la tour de refroidissement sont commandés (arrêt/petite/grande vitesse) de manière à maintenir une température constante de l'eau de refroidissement. 

Le fonctionnement d'une machine frigorifique suivante est autorisé (selon la procédure ci-dessus) lorsque les conditions suivantes sont remplies : 

- la température de l'eau glacée se situe au-dessus d'une certaine limite; 

- la température extérieure se situe au-dessus d'une certaine limite; 

- la machine frigorifique précédente fonctionne depuis suffisamment longtemps à pleine puissance. 

Si la différence de température entre le départ et le retour général d'eau glacée se trouve au-dessous d'une certaine limite, une machine frigorifique est arrêtée (le fonctionnement d'au moins une machine reste toujours autorisé). La pompe d'eau glacée correspondante reste en fonctionnement pendant un certain temps pour éviter le gel de l'évaporateur. 

Remarques : 

- l'ordre dans lequel sont commandées les machines est, au choix de l'utilisateur, fixe (réglable manuellement) ou alterné automatiquement; 

- lorsqu'une machine frigorifique (ou l'un de ses accessoires) est en dérangement, une machine suivante est libérée; 

- lorsqu'une pompe d'eau de refroidissement est mise en marche ou qu'un robinet est ouvert ou fermé, il n'est pas tenu compte pendant une courte période de l'alarme de manque d'eau dans les tours de refroidissement, ceci pour compenser des variations temporaires de niveau. 

**4.10.2. Machine frigorifique à condenseur refroidi par air** 

Voir 4.10.1., mais les points et les actions concernant les tours de refroidissement et le circuit d'eau de refroidissement ne sont pas d'application. 

La régulation du condenseur fait partie de la machine frigorifique et est indépendante de l'A.R.C.P 

**4.10.3. Appareil de refroidissement de type split (multisplit)** 

Ce programma s’applique à chaque appareil de type split (multisplit). 

**4.10.3.1. Points** 

Les points suivants sont prévus. 

- Points de mesure logiques 

* signal de dérangement de l’unité intérieure et extérieure du système (multi)split (1) 

**4.10.3.2. Fonctionnement** 

Les points de mesure logiques servent uniquement à la signalisation et l’alarme. La régulation se fait de façon autonome par l’appareil lui-même.

**4.11. Ventilation et désenfumage de parking** 

Ce programme s’applique à chaque ensemble de ventilation de parking, qui réalise ou non également l’évacuation des fumées et de la chaleur du parking selon la NBN S21-208-2. 

Ce désenfumage peut être réalisé suivant le principe horizontal ou vertical. 

Si l’installation n’assure pas l’évacuation des fumées et de la chaleur, alors les dispositions et points qui concernent cet aspect ne sont pas d’application. 

**4.11.1. Points** 

Les points suivants sont prévus : 

- Points de mesure logiques 

   - tableau d’alimentation sous tension 

   - tableau de commande sous tension 

   - défaillance alimentation batterie tableau de commande 

|* tableau d’alimentation sous tension<br>* tableau de commande sous tension<br>* défaillance alimentation batterie tableau de commande||
|---|---|
|* état circuit de commande des ventilateurs (y) (comprend le contrôle||
|en série des protections contre les surcharges||
|et de l’interrupteur manuel), normal/dérogation|(1)|
|* fonctionnement ventilateur (y)||
|(par mesure de la tension sur les bornes), marche/arrêt|(1)|
|* détecteur de débit dans conduit ventilateur, marche/arrêt|(1) (3) (4)|
|* clapet antiretour, ouvert/non ouvert|(1) (4)|
|* clapet antiretour, fermé/non fermé|(1) (4)|
|* clapet motorisé, ouvert/non ouvert|(1) (4)|
|* clapet motorisé, fermé/non fermé|(1) (4)|
|* détection incendie dans zone EFC, normal/alarme|(x)|
|* écran de fumée, ouvert/non ouvert|(1) (4)|
|* écran de fumée, fermé/non fermé|(1) (4)|
|* commutateur à clé dérogation désenfumage, en service/hors service||
|* commutateur dérogation zone EFC, arrêt/automatique/manuel|(x)|
|* défaillance centrale de détection incendie, normal/défaillant||
|* premier seuil détection CO, normal/franchi|(4)|
|* deuxième seuil détection CO, normal/franchi|(4)|
|* troisième seuil détection CO, normal/franchi|(4)|
|* quatrième seuil détection CO, normal/franchi|(4)|
|* défaillance centrale de détection CO, normal/défaillant||
|nts de commande logiques :||
|* fonctionnement ventilateur (y), marche/arrêt|(1)|
|* fonctionnement ventilateur (y), petite vitesse/grande vitesse|(1) (2)|
|* écran antifumée, ouvert/fermé|(1) (4)|
|* clapet motorisé, ouvert/fermé|(1) (4)|
|* témoin lumineux (blanc) tension tableau d’alimentation, allumé/éteint||
|* témoin lumineux (blanc) tension tableau de commande, allumé/éteint||
|* témoin lumineux (vert) fonctionnement ventilation, allumé/éteint||



- Points de commande logiques : 

   - témoin lumineux (rouge) défaillance ventilation, allumé/éteint 

   - témoin lumineux (rouge) défaillance centrale de détection incendie, allumé/éteint * témoin lumineux (rouge) détection incendie dans zone EFC, allumé/éteint (x) * témoin lumineux (vert) fonctionnement désenfumage zone EFC, allumé/éteint  (x) * témoin lumineux (rouge) défaillance zone EFC, allumé/éteint (x) * témoin lumineux (orange) dérogation zone EFC, allumé/éteint (x) 

Remarques : 

- Remarque (y) : par ventilateurs il faut comprendre tout ventilateur de pulsion/extraction et accélérateur. 

- Référence (x) : un point par zone EFC 

**4.11.2. Fonctionnement**

- La ventilation du parking peut s’opérer suivant quatre modes de fonctionnement, par ordre de priorité :

- désenfumage 

   - fonctionnement suivant détection CO 

   - fonctionnement suivant horaire 

   - stand-by 

- Dès qu’un mode de fonctionnement donné est activé, les modes de fonctionnement inférieurs sont neutralisés. 

**4.11.2.1. Désenfumage** 

Ce mode de fonctionnement est activé dès qu’il y a une détection incendie dans l’une des zones EFC ou que le commutateur à clé de la dérogation est enclenché. 

En cas de détection incendie, les ventilateurs, clapets, et écrans sont commandés suivant le scénario incendie de la zone EFC concernée. 

Chaque ventilateur est mis en marche avec une certaine temporisation par rapport au précédent. En cas de désenfumage horizontal l’installation démarre 2 minutes après l’activation du scénario incendie. 

Les ventilateurs qui ne servent qu’à la ventilation normale sont mis à l’arrêt. 

Lorsque le commutateur à clé sur le tableau de commande est enclenché, les commutateurs de dérogation des différentes zones sont opérationnels : 

- en position "automatique”, la zone sinistrée est désenfumée (en l'absence de détection, les ventilateurs ne sont pas mis en marche) 

- en position "manuel", la zone concernée est désenfumée : démarrage des ventilateurs, commande des clapets et écrans selon le cas (prioritaire sur la commande automatique) 

- en position "arrêt", les ventilateurs sont arrêtés, s’il n’y a pas désenfumage d’une autre zone. 

**Fonctionnement des témoins lumineux :** 

- témoin lumineux (vert) fonctionnement ventilation : s’allume dès qu’un débit d’extraction est détecté (via détecteur de débit ou position du clapet anti-retour) dans le cas où cela constitue un état commandé 

- témoin lumineux (rouge) défaillance ventilation : s’allume lorsque 

      - l’état du circuit de commande des ventilateurs n’est pas normal 

      - l'état de fonctionnement ordonné ne correspond pas à la réalité (tension sur les bornes) 

      - aucun débit d’extraction n’est détecté (via détecteur de débit ou position du clapet anti-retour) tandis que le ventilateur correspondant devrait être en marche 

      - un clapet antiretour n’est pas fermé alors que le ventilateur correspondant devrait être à l’arrêt 

   - (cette signalisation est à reporter comme alarme sur la centrale de conduite) 

- témoin lumineux (vert) fonctionnement désenfumage zone EFC x : est allumé, lorsqu'il y a détection ou activation manuelle dans la zone concernée, dès que le témoin lumineux vert du fonctionnement de la ventilation s'allume et que les écrans de fumée/clapets anti-retour se trouvent dans la position demandée 

- témoin lumineux (rouge) défaillance zone EFC x : est allumé, lorsqu'il y a détection ou activation manuelle dans la zone concernée, dès que le témoin lumineux rouge défaillance ventilation s'allume ou que les écrans de fumée/clapets anti-retour ne se trouvent pas dans la position demandée 

- témoin lumineux (orange) dérogation zone EFC x : est allumé lorsque l’interrupteur de dérogation de la zone n'est pas en mode "automatique" ou lorsque la zone objet de la détection n'est pas désenfumée parce qu'une autre zone se trouve en "manuel" 

- autres témoins lumineux : fonctionnent conformément à leur dénomination. 

**4.11.2.2. Fonctionnement sous détection CO** 

Ce mode de fonctionnement est activé dès qu’un seuil de détection CO est franchi. 

En fonction du deuil dépassé, un ou plusieurs ventilateurs sont mis en marche (et, le cas échéant, leurs clapets ouverts).

Lorsque les troisième et quatrième seuils de la détection CO sont franchis, une alarme est donnée à la centrale de conduite. 

**4.11.2.3. Fonctionnement suivant horaire** 

Ce mode de fonctionnement est activé par un programme horaire, pour autant que la température extérieure ne soit pas inférieure à une valeur minimale réglable. 

Deux périodes (pic au matin et pic au soir) sont à programmer par jour, celles-ci peuvent différer pour chaque jour de la semaine. 

Dans ce mode un nombre de ventilateurs est mis en marche (et, le cas échéant, leurs clapets ouverts) afin d’obtenir le débit minimal requis. 

**4.11.2.4. Standby** 

Ce mode de fonctionnement est activé lorsqu’aucun autre mode n’est actif. 

Tous les ventilateurs sont à l’arrêt et tous les clapets sont fermés. 

**5. Dispositions diverses** 

**5.1. Pose et raccordement** 

L'A.R.C.P. est monté dans un tableau électrique séparé, conforme à l'art. C22. par. 4. Ce tableau est placé à côté du tableau électrique desservant les installations régulées et contrôlées par l'A.R.C.P. 

Si l'A.R.C.P. n'a pas d'appareil de commande incorporé, il peut être monté dans le tableau électrique des installations, pour autant qu'il n'y ait pas de danger de perturbations par induction. L’appareil de commande indépendant est placé suivant les directives du [[concepts/fonctionnaire-dirigeant|Fonctionnaire Dirigeant]]. 

Toutes les parties de l'A.R.C.P. sont réalisées sur cartes ou modules enfichables. Les raccords électriques se font par connecteurs, ce qui permet d'enlever les cartes ou modules sans devoir dévisser ou souder aucun raccord électrique. 

Les connecteurs sont reliés à des borniers auxquels sont raccordés tous les câbles entrants ou sortants. A ces borniers sont raccordés d'une part les sondes, servomoteurs e. a. et d'autre part les raccordements au tableau électrique de l'appareillage de commande. 

Les raccordements pour la commande des brûleurs, moteurs de pompes et ventilateurs, éléments de [[concepts/chauffage-electrique|Chauffage Électrique]] e. a. passent par le tableau électrique desservant ces éléments. Ces raccordements sont effectués de façon à ce que la commande par l'A.R.C.P. ne fonctionne que si le commutateur manuel à trois positions arrêt/automatique/continu (voir art. C22. par. 3. point 1.2.2. et 2.2.2.) du brûleur, moteur etc. desservi se trouve dans la position automatique. 

Le cahier spécial des charges peut cependant prescrire que certains moteurs (lorsque le commutateur manuel se trouve dans la position automatique) ou servomoteurs puissent également être commandés avec priorité, sans intervention de l'A.R.C.P. (p.ex. commande par pompiers). 

L'A.R.C.P. est alimenté à partir du tableau desservant les installations. 

Les sous-stations pour ARCP (voir 2.4.) sont placées de la même manière que les ARCP. 

Le placement des modules locaux d'un réseau local et les régulateurs locaux (voir 2.2.5 ci-dessus) est réalisé comme suit : 

- dans un local technique : de la même manière que les ARCP 

- dans d'autres locaux : dans les tableaux ou coffrets électriques, ou en des endroits facilement accessibles via portillons ou trappes (trémies techniques, faux planchers,…)

- si un seul élément doit être connecté au module (p.ex. clapet coupe-feu), ils peuvent être placés à proximité immédiate de cet élément (dans un coffret) dans les mêmes conditions d’accès que l’élément en question. 

- le placement des modules dans les tableaux électriques d'une autre partie (p. ex. Electricité) n’est pas admis. 

**5.2. Mise en service** 

La mise en service comprend l'introduction des consignes, périodes d'occupation, limites pour les conditions climatiques et autres choix de programmes selon les besoins de l'occupant. 

En outre, les paramètres nécessaires relatifs aux caractéristiques des bâtiments et des installations sont déterminés et introduits. Ensuite, ces valeurs sont corrigées suivant les expériences acquises au cours du fonctionnement de l’A.R.C.P. On réalise une copie, sur unité de mémoire externe (voir 2.1.3.), du contenu complet de toutes les mémoires RAM (comprenant programmes, paramètres, etc.).Cette copie est mise à la disposition de l'administration. En cas de corrections aux programmes ou paramètres, cette copie est actualisée. 

**5.3. Documentation** 

L'entrepreneur fournit les documents suivants, en trois exemplaires : 

- un manuel d'utilisation succinct 

Celui-ci traite de l'introduction des périodes d'occupation et dérogations à celles-ci ainsi que de la demande de données. Les opérations nécessaires sont décrites de façon claire et simple, accompagnées d'exemples, de manière à ce que du personnel non-technique puisse les exécuter. 

- un manuel d'utilisation détaillé 

Celui-ci traite de toutes les opérations exécutées par l'utilisateur, c.à.d. non seulement la demande de données, l'introduction et le changement des périodes d'occupation, mais également les consignes et alarmes, dérogations manuelles, etc. 

- une documentation technique 

Celle-ci comprend une description du matériel, de la programmation et des programmes fournis. 

- un manuel d'entretien 

Celui-ci traite de la vérification du bon fonctionnement de l'appareil et de l'entretien préventif à effectuer. 

**5.4. Essais** 

**5.4.1. Essais avant la première réception provisoire** 

Les essais suivants sont effectués, afin de vérifier le fonctionnement correct de l'A.R.C.P. : 

- le contrôle du fonctionnement des points de mesure (on utilise le programme 3.2.1.) 

- le contrôle du fonctionnement des points de commande. On impose de façon manuelle certains états (programme 3.2.2.) 

- le contrôle des alarmes (cela peut se faire par exemple par la coupure de la tension d'alimentation des pompes, brûleurs, etc.) 

- le contrôle du comportement de l'A.R.C.P. lors d'une coupure de courant. A cette fin, on coupe la tension d'alimentation

- le contrôle du fonctionnement des programmes horaires (4.1.2.), par exemple par l'introduction de dérogations 

- le contrôle du fonctionnement des programmes de régulation. A cette fin, on impose des valeurs fictives pour des valeurs de mesure (p.ex. température extérieure) au moyen du programme 3.2.2., et on vérifie si les régulations réagissent de façon correcte (c.à.d. l'action des brûleurs, robinets modulants clapets d'air, etc.) 

Les essais sont effectués par l'entrepreneur, en présence du représentant de l'administration, qui choisit les points, alarmes, régulations à contrôler et qui peut également imposer d'autres contrôles. 

**5.4.2. Essais préalables à la seconde réception provisoire** 

Avant la seconde réception provisoire, l'A.R.C.P. subit un essai de fonctionnement. Cet essai est effectué par l'entrepreneur. A cette fin, il fournit temporairement une imprimante à raccorder à l'A.R.C.P. (voir 2.5.), le papier nécessaire, le logiciel et d'autres accessoires. 

Pendant cinq jours consécutifs, dont un week-end, les valeurs suivantes sont imprimées chaque demiheure, pour au moins un circuit de chauffe et un groupe de traitement d'air (s'il en existe) : 

- l'heure 

- la température extérieure 

- la température de l'eau du départ général 

- la température de l'eau au départ du circuit (ou température de pulsion du groupe) 

- la température intérieure pour le circuit (ou groupe) concerné 

Pendant l'essai, le [[concepts/fonctionnaire-dirigeant|Fonctionnaire Dirigeant]] doit pouvoir vérifier à chaque moment les valeurs qui sont déjà imprimées. Après l'essai, les résultats sont transmis au fonctionnaire dirigeant, pour vérifier si les régulations satisfont aux prescriptions du chapitre 4. 

Lorsque le délai prévu pour les essais de fonctionnement tombe en dehors de la saison de chauffe, la seconde réception provisoire est accordée suivant les modalités de point 4.3.3.3. des clauses administratives du présent cahier des charges-type. L'entrepreneur doit alors faire l'essai dans l'année qui suit la seconde réception provisoire. 

Si une imprimante est incluse dans le marché, elle peut être utilisée pour l'essai de fonctionnement. L'entrepreneur fournit le papier. 

**5.5. Ecolage** 

L’entrepreneur assure l'écolage du personnel chargé de la commande des ARCP. 

Cet écolage comprend : 

- écolage préalable général (au moins un jour) : celui-ci traite de toutes les opérations telles que décrites dans le manuel d'utilisation détaillé (voir 5.3). Cet écolage est donné dans les locaux de l'entrepreneur ou du fabricant du système ; un appareil individuel permettant de s’exercer à l'utilisation est mis à la disposition de chaque personne à former. 

- écolage spécifique (au moins un jour) : celui-ci traite des mêmes opérations, mais il est orienté spécifiquement sur la commande de l'installation concernée. Il est dispensé sur place. 

- l'écolage après la mise en service (au moins deux demi-journées) : celui-ci comprend une répétition de l’écolage préalable, ainsi que le traitement des problèmes rencontrés. 

Le [[concepts/fonctionnaire-dirigeant|Fonctionnaire Dirigeant]] désigne les personnes à former (au moins trois) et définit les dates de l'écolage.

**5.6. Obligations de l’entrepreneur jusqu’à la réception définitive** 

Jusqu’à la réception définitive l’entrepreneur contrôle régulièrement le fonctionnement des installations; ceci comprend : 

- Le contrôle des alarmes, et la prise de mesures pour y remédier à l’avenir 

- Donner au pouvoir adjudicateur des conseils pour mieux gérer les installations 

- Au fur et à mesure de l’expérience acquise pendant le fonctionnement des installations, les réglages et les paramètres des ARCP et de la centrale de conduite sont adaptés afin de : 

   - mieux aligner le fonctionnement des installations sur les besoins de l’occupant 

   - augmenter le confort 

   - minimaliser la consommation énergétique 

   - minimaliser l’usure des installations
