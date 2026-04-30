---
aliases: ["Électricité et Interfaces HVAC"]
tags: [concept, electricite, hvac, bt, tbt, regulation, incendie]
sources: [T7 Electricité CCTB 01.13_20260317.pdf, La Technique du bâtiment – Tous corps d’état.epub]
created: 2026-04-22
updated: 2026-04-29
contextes: [technique, appel-doffres]
autorite: [contractuel]
juridictions: [wallonie, bruxelles]
familles_sources: [cctb]
disciplines: [cvc, electricite]
---
# Électricité et Interfaces HVAC

## Définition

Cette notion résume la lecture du tome T7 du [[entities/cctb|CCTB]] depuis le point de vue d'un lot HVAC. T7 ne dimensionne pas les débits, puissances thermiques ou réseaux fluides à la place de T6, mais il définit la façon dont ces systèmes sont alimentés, protégés, câblés, supervisés, mis à la terre et asservis au reste du bâtiment.

## Ce que T7 apporte réellement à un lot HVAC

Pour un lot HVAC, T7 couvre surtout :

- l'alimentation électrique des équipements techniques ;
- les tableaux, protections, parafoudres et différentiels ;
- les cheminements de câbles, traversées, calfeutrements et modules coupe-feu ;
- la commande, la mesure et certains automatismes ;
- les asservissements avec incendie, gaz, extinction, éclairage de secours et sûreté ;
- la mise à la terre, l'équipotentialité et la protection foudre ;
- le couplage énergétique avec le photovoltaïque et, selon les cas, le stockage batterie ;
- le cadre du [[concepts/chauffage-electrique|Chauffage Électrique]].

## Interfaces HVAC structurantes

### Production et alimentation électrique

T7 prévoit des postes dédiés pour le raccordement des groupes frigorifiques, des pompes à chaleur, de la cogénération, des panneaux photovoltaïques, de la pompe sprinkler, de la détection incendie et de l'éclairage de secours.

Le message de fond est clair : l'interface électrique des techniques n'est pas un détail de chantier. Elle fait partie du lot et doit être spécifiée comme telle dans le [[concepts/csc|CSC]], avec protections, sections, schémas, coordination tableaux et modalités de réception.

### Commande, mesure et supervision

Les modules domotiques, thermostats et centrales de mesure donnent une base électrique concrète aux fonctions de régulation et de suivi énergétique.

T7 traite notamment :

- des modules domotiques sur rail `DIN` ;
- des thermostats comme organes de contrôle et de mesure ;
- des centrales de mesure avec `Modbus / RTU` et `RS485` ;
- des détecteurs `TBT`, notamment capteurs de mouvement et capteurs de température ;
- des signaux possibles vers `BMS/GTC` dans certains systèmes de sécurité.

Autrement dit, T6 décrit la logique HVAC, tandis que T7 fournit une partie de l'ossature électrique qui permet de l'exécuter et de la superviser.

### Cheminements, traversées et coordination inter-lots

Le chapitre `71.24.5` est décisif parce qu'il ne traite pas seulement de câbles, mais aussi :

- des tranchées, percements et traversées ;
- de la fermeture des saignées ;
- du maintien de la résistance au feu des parois traversées ;
- de la coordination aux croisements avec les conduites sanitaires, de chauffage et de ventilation ;
- de l'éloignement par rapport aux cheminées et aux installations de chauffage.

Pour un lot HVAC, cela veut dire que la coordination des réseaux n'est pas seulement géométrique. Elle est aussi réglementaire, feu, maintenance et réception.

### Sécurité incendie, gaz et exploitation de crise

T7 ajoute à la lecture feu de T6 une couche active :

- détection incendie ;
- détection gaz ;
- extinction au gaz ;
- alarmes et évacuation vocale ;
- éclairage de sécurité ;
- raccordements dédiés de pompe sprinkler et de détection incendie.

Cette matière touche directement le HVAC dès qu'il faut arrêter ou piloter une ventilation, fermer des clapets, assurer la tenue du câblage, maintenir un local technique exploitable en urgence ou coordonner une extinction gaz avec ses surpressions.

### Terre, équipotentialité et foudre

Le tome impose la chaîne complète de mise à la terre et d'équipotentialité, jusqu'au conducteur de protection individuel pour chaque circuit.

Pour le HVAC, cela concerne directement :

- les PAC et groupes frigorifiques ;
- les châssis et supports métalliques ;
- les cadres de modules photovoltaïques ;
- les réseaux métalliques fixes accessibles ;
- les chauffe-eau, radiateurs et conduites en locaux humides ;
- les protections surtension et l'articulation avec le paratonnerre.

## Résumé du reste du lot

Le reste du tome ne relève pas du HVAC au sens strict, mais borne le périmètre du lot :

- la BT générale couvre aussi transformateurs, UPS, tableaux, prises et recharge de véhicules ;
- la TBT englobe interphonie, data, téléphonie, contrôle d'accès et vidéosurveillance ;
- l'éclairage couvre les études photométriques, la gestion par présence et lumière du jour, ainsi que les luminaires intérieurs et extérieurs ;
- les ascenseurs ont leur propre périmètre technique ;
- le chauffage électrique forme un sous-ensemble complet, distinct du chauffage hydronique du tome T6.

Ce contexte évite de réduire le lot électricité à un simple sous-traitant d'alimentation du lot HVAC. Dans le CCTB, il s'agit d'un lot transversal qui porte l'infrastructure électrique complète du bâtiment.

## Pages liées

- [[sources/cctb-t7-electricite|CCTB T7 - Électricité]]
- [[concepts/climatisation-et-froid|Climatisation et Froid]]
- [[concepts/production-de-chaleur|Production de Chaleur]]
- [[concepts/distribution-et-regulation-de-ventilation|Distribution et Régulation de Ventilation]]
- [[concepts/lutte-contre-lincendie-hvac|Lutte contre l'Incendie HVAC]]
- [[concepts/mise-a-la-terre-et-equipotentialite|Mise à la Terre et Équipotentialité]]
- [[concepts/chauffage-electrique|Chauffage Électrique]]

## Voir aussi

- [[meta/source-inventory|Inventaire des Sources]] — liste des documents sources disponibles
