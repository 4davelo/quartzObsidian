---
aliases:
- Eau Chaude Sanitaire
tags:
- concept
- ecs
- sanitaires
- eau-chaude
- solaire
- pac
sources:
- T6 HVAC - sanitaires CCTB 01.13_20260317.pdf
- T0 Entreprise _ Chantier CCTB 01.13_20260317.pdf
- T6 HVAC - sanitaires CCTB 01.13.pdf
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
- sanitaire
---
# Eau Chaude Sanitaire

## Définition

Le chapitre `65.23` du tome T6 couvre la fourniture, l'installation, le raccordement et la mise en service des appareils individuels de production d'eau chaude sanitaire. Il traite les systèmes gaz, électriques, solaires et les chauffe-eau avec pompe à chaleur.

## Exigences transversales

T6 impose notamment :

- la compatibilité mutuelle des matériaux ;
- l'application de [[entities/belgaqua|Belgaqua]] et de [[concepts/certibeau|CertIBEau]] pour les protections et accessoires ;
- une température d'écoulement limitée à `60 °C` ;
- la coordination avec les installations sanitaires, chauffage et électricité ;
- des raccordements proches pour l'eau froide, l'eau chaude, le gaz et l'alimentation électrique.

Le chapitre `65.2` complète cette logique avec les dispositifs de raccordement réglementaire au réseau d'eau, les traitements de l'eau, les adoucisseurs, filtres et dispositifs anti-calcaire lorsque le projet les impose.

## Appareils au gaz

Le tome distingue :

- les chauffe-eau instantanés ;
- les accumulateurs au gaz ;
- les appareils à combustion ouverte ou fermée ;
- les appareils livrés par le maître d'ouvrage.

T6 conseille les appareils à circuit de combustion étanche pour préserver l'étanchéité de l'enveloppe. Pour certains appareils ouverts, une amenée d'air non obturable de `150 cm²` minimum est requise, voire `13 cm²/kW` selon le type d'appareil.

Le chapitre `65.2` rend aussi la typologie plus lisible :

- chauffe-bains `B11BS` à combustion ouverte ;
- chauffe-bains `C13-C33` à ventouse ;
- petits chauffe-eau de cuisine de type `A1AS` ;
- appareils livrés par le maître d'ouvrage et posés par l'entreprise.

## Chauffe-eau électriques

T6 couvre :

- les petits bouilleurs `5 L` ;
- les modèles encastrés sous évier ;
- les chauffe-eau électriques à accumulation plus importants.

Le raccordement doit rester conforme au [[concepts/rgie|RGIE]], avec groupe de sécurité, thermostat, limitation de température, résistance remplaçable et garanties sur cuve et ensemble selon le type d'appareil.

T6 ajoute aussi les modèles économiques avec régulation intelligente et les variantes encastrées de cuisine.

## Chauffe-eau solaires

Le chauffe-eau solaire est très structuré dans T6 :

- un seul fournisseur doit couvrir l'ensemble du système ;
- les systèmes expérimentaux ou ouverts à remplissage régulier par l'occupant sont exclus ;
- le système comprend capteurs, ballons, modules de pompage, vase d'expansion, régulation et raccordements ;
- les essais, la mise en service et les contrôles suivent la `NIT 212` et les séries `NBN EN 12976` / `12977`.

T6 détaille aussi les capteurs, les débits, les isolations de conduites, les systèmes d'expansion, la régulation solaire, l'antigel, la protection contre la surchauffe et la limitation de température via vanne mélangeuse.

Le chapitre `65.2` rend visible la structure complète du système :

- collecteurs ;
- ballons de stockage et de vidange ;
- circuits et accessoires ;
- circulateurs ;
- vases d'expansion ;
- réglage, protection, contrôles et essais.

## Chauffe-eau avec pompe à chaleur

Le chapitre `65.23.6` renvoie explicitement au cadre PAC du chapitre `63.26`. Les points clés sont :

- capacités typiques de `100` à `300 L` ;
- température maximale d'ECS produite par la PAC ;
- `COP ECS` suivant `EN 16147` ;
- sécurité antigel et anti-légionnelle ;
- éventuelle compatibilité photovoltaïque ;
- règles de prise d'air et de rejet d'air.

T6 confirme que ces appareils doivent être lus comme systèmes hybrides, à l'interface entre ECS, ventilation, électricité et production de chaleur.

## Importance pour un lot HVAC

L'ECS n'est pas un simple accessoire du lot chauffage ou sanitaire. T6 en fait un sous-système autonome, avec ses propres contraintes de sécurité, de conformité eau, de rendement, de régulation, de maintenance et de réception. Dans un [[concepts/csc|CSC]], il faut donc en expliciter le mode de production et toutes ses interfaces.

## Voir aussi

- [[meta/source-inventory|Inventaire des Sources]] — liste des documents sources disponibles
