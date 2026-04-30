---
aliases:
- Climatisation et Froid
tags:
- concept
- climatisation
- froid
- hvac
- eau-glacee
- pac
sources:
- T6 HVAC - sanitaires CCTB 01.13_20260317.pdf
- T5 Fermetures _ Finitions intérieures CCTB 01.13_20260317.pdf
- T7 Electricité CCTB 01.13_20260317.pdf
- La Technique du bâtiment – Tous corps d’état.epub
created: 2026-04-22
updated: 2026-04-29
contextes:
- technique
- appel-doffres
autorite:
- contractuel
juridictions:
- wallonie
- bruxelles
familles_sources:
- cctb
disciplines:
- cvc
- gtb
---
# Climatisation et Froid

## Définition

Dans le tome T6, les chapitres `62 Climatisation` et `64 Froid` couvrent les systèmes de traitement d'air, les équipements réversibles chaud/froid, les groupes de froid et certaines prescriptions de distribution en eau glacée.

## Portée réelle dans cette édition

La structure `62` et `64` est présente et exploitable, mais elle est moins développée que les chapitres ventilation, chaleur ou sanitaires. T6 y donne surtout :

- un cadre normatif complet ;
- une liste des familles d'équipements admissibles ;
- quelques prescriptions techniques détaillées sur l'isolation, les traversées feu et la protection antigel.

## Climatisation

Le chapitre `62` mentionne notamment :

- les centrales de traitement d'air ;
- les caissons de mélange, filtres, batteries chaudes et froides ;
- les humidificateurs et laveurs ;
- les splits systems ;
- les ventilo-convecteurs ;
- les poutres froides ;
- les régulations primaires et secondaires associées.

Le chapitre `62` rend toutefois la structure plus nette :

- `CTA` avec caissons de mélange, filtres, batteries chaudes et froides, humidificateurs et laveurs ;
- systèmes réversibles de type `split` ;
- ventilo-convecteurs carrossés ou non carrossés ;
- poutres froides passives ou actives ;
- régulations primaires, secondaires et supervision.

Le cadre normatif mobilise notamment `NBN EN 1886`, `NBN EN 12102-1`, la série `NBN EN 14511`, `NBN EN 16798-*` et l'annexe `C4` de la PEB.

## Froid

Le chapitre `64` traite surtout :

- les groupes de froid ;
- les conduites et accessoires ;
- le calorifugeage des conduites ;
- les traversées ignifuges ;
- les rubans chauffants antigel ;
- les circulateurs, pompes et échangeurs ;
- les plafonds froids ;
- les régulations et gestions techniques centralisées.

## Points techniques utiles

T6 insiste particulièrement sur trois points en froid :

- l'isolation des conduites doit éviter toute condensation superficielle ;
- les traversées de parois résistantes au feu doivent être traitées selon l'[AR 1994-07-07] et la [NIT 254] ;
- dans les zones à risque de gel, un ruban chauffant autorégulant peut être requis sur les tronçons exposés.

Les pompes véhiculant un fluide dont la température peut être inférieure à l'ambiante doivent aussi être conçues pour résister à la condensation et, si nécessaire, évacuer cette eau sans dégrader les composants électriques.

Le chapitre `64` ajoute plusieurs précisions utiles au marché :

- le calorifugeage vise explicitement à maintenir la température de surface au-dessus du point de rosée ;
- en certaines conditions, l'épaisseur d'isolant doit être justifiée par note de calcul selon [[entities/cct-105|CCT 105]] ;
- des rubans chauffants autorégulants peuvent être exigés sur les tronçons exposés au gel ;
- les composants hydrauliques doivent rester compatibles avec les additifs antigel ;
- les plafonds froids et les régulations `GTC` font partie du périmètre contractuel, pas seulement des options de confort.

Le tome T5 complète directement cette matière sur deux interfaces intérieures :

- les [[concepts/faux-plafonds-et-plafonds-climatiques|Faux-plafonds et Plafonds Climatiques]] décrivent les plafonds rayonnants ou convectifs intégrés, leur partage de responsabilité entre T5 et T6, la coordination des plans, l'intégration des bouches et luminaires, ainsi que l'exigence explicite d'éviter toute condensation ;
- les [[concepts/cloisons-et-doublages-interieurs|Cloisons et Doublages Intérieurs]] couvrent les cloisons frigorifiques, avec isolation intégrée, joint pare-vapeur, coupure thermique, portes techniques et exigences éventuelles d'usage alimentaire.

Autrement dit, T6 dimensionne le système de froid ou de climatisation, tandis que T5 décrit comment ce système s'incarne dans le second oeuvre intérieur.

## Complément électrique du tome T7

Le tome T7 apporte le socle électrique qui manque à T6 pour rendre ces systèmes réellement raccordables et réceptionnables.

Il prévoit notamment :

- un poste spécifique pour l'[[concepts/electricite-et-interfaces-hvac|alimentation des groupes frigorifiques]] ;
- les règles générales de distribution `BT`, de protections, de tableaux et de choix de câbles ;
- les canalisations, traversées, saignées, calfeutrements et modules coupe-feu autour des câbles d'alimentation et de commande ;
- l'obligation de coordonner les croisements entre conduites électriques et conduites sanitaires, de chauffage et de ventilation ;
- l'obligation de tenir les conduites électriques à distance des cheminées et des installations de chauffage ;
- la possibilité d'intégrer mesure, communication `Modbus / RTU` et transmission `RS485` via les centrales de mesure ;
- les modules domotiques et thermostats comme éléments de commande et de supervision.

Pour un groupe froid, une unité extérieure ou un système de climatisation en toiture ou en façade, T7 devient donc le tome de la réalité électrique : alimentation, protection, cheminement, feu, terre et supervision.

## Importance pour l'offre

Pour un lot HVAC, il ne faut pas sous-estimer ces chapitres sous prétexte qu'ils sont plus courts. Ils fixent tout de même le cadre de recevabilité pour les équipements de climatisation et les réseaux de froid, surtout en matière de performances, d'isolation, de sécurité incendie et de coordination avec les autres systèmes techniques.

## Voir aussi

- [[meta/source-inventory|Inventaire des Sources]] — liste des documents sources disponibles
