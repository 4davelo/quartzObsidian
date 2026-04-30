---
aliases:
- Acoustique des Installations Techniques
tags:
- concept
- acoustique
- hvac
- bruit
- vibration
- conformité
sources:
- T6 HVAC - sanitaires CCTB 01.13_20260317.pdf
- T2 Superstructures CCTB 01.13_20260317.pdf
- T4 Fermetures _ Finitions extérieures CCTB 01.13_20260317.pdf
- T5 Fermetures _ Finitions intérieures CCTB 01.13_20260317.pdf
- CCT105TB FR 2023.pdf
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
- belgique
familles_sources:
- cctb
- contrat
disciplines:
- cvc
- enveloppe
---
# Acoustique des Installations Techniques

## Définition

Le tome T6 traite l'acoustique comme une exigence transversale applicable aux installations de ventilation, de chauffage, de froid, de climatisation et de sanitaires. L'objectif n'est pas seulement le confort intérieur, mais aussi le respect des impositions vis-à-vis du voisinage.

## Exigences générales du tome T6

Pour les installations techniques placées en extérieur, T6 impose de se référer à la `NBN S 01-400-1` pour les impositions acoustiques vis-à-vis du voisinage et de l'environnement.

Le document exige également :

- des dispositifs antivibratiles entre bloc moteur, châssis et socle ;
- un rendement d'absorption des vibrations d'au moins `90 %` pour les fréquences générées par l'équipement ;
- un capotage acoustique permettant de respecter les niveaux sonores extérieurs et intérieurs ;
- une note de calcul sur les éléments antivibratiles et leurs caractéristiques de charge et d'absorption.

## Normes contractuellement mobilisées

T6 renvoie notamment à :

- `NBN S 01-400-1` pour les immeubles d'habitation ;
- `NBN S 01-400-2` pour les bâtiments scolaires ;
- `NBN S 01-400` et `NBN S 01-401` pour les autres bâtiments ;
- `NBN EN ISO 16283-1` et `NBN EN ISO 10052` pour certains contrôles in situ ;
- [[entities/cct-105|CCT 105]] pour les silencieux, traitements acoustiques et implantations.

## Traduction pratique dans les lots HVAC

Dans le détail des postes, T6 impose ou favorise :

- des [[concepts/distribution-et-regulation-de-ventilation|silencieux]] dans les réseaux de ventilation ;
- des manchettes antivibratiles au raccordement des caissons ;
- des colliers résiliants et des détails d'exécution limitant la transmission des vibrations ;
- pour les installations sanitaires, le respect des critères acoustiques de l'immeuble.

Le tome précise aussi :

- les `OAR` et `OT` peuvent porter une performance acoustique propre `Dn,w` ;
- les hottes ont un niveau sonore maximal explicité ;
- les conduites de chauffage et d'évacuation imposent joints de traversée, colliers résiliants et dispositifs limitant la transmission solidienne ;
- la note de calcul des antivibratiles fait partie des pièces à fournir.

## Apport CCT 105

Le [[entities/cct-105|CCT 105]] donne une structure plus complète au traitement acoustique HVAC. Les articles [[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/258-article-d2-valeurs-limites-des-niveaux-de-bruit|D2]], [[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/266-article-d4-prescriptions-acoustiques-specifiques-pour-les-installations-hvac|D4]] et [[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/271-article-d5-specifications-pour-l-isolation-anti-vibrations|D5]] couvrent les niveaux de bruit, les prescriptions acoustiques HVAC, les silencieux, les traversées de parois et l'isolation antivibratoire. L'[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/304-article-e6-essais-acoustiques|article E6]] rattache ensuite ces exigences aux essais.

Pour une soumission, cette matière doit être lue avec [[concepts/essais-et-mise-au-point-hvac|Essais et Mise au Point HVAC]] : les silencieux, capotages et supports antivibratoires doivent être vérifiables par notes de calcul, fiches techniques et mesures lorsque le marché le demande.

## Support bâti côté T2

Le tome T2 rappelle que cette acoustique ne dépend pas seulement de la machine ou du réseau. Elle dépend aussi des parois et joints du bâtiment qui portent ou traversent l'installation.

Le document relie notamment :

- les murs à coulisse et autres compositions de parois aux exigences de `NBN S 01-400` ;
- certains blocs maçonnés acoustiques aux performances du support ;
- les joints de resserrage acoustique aux détails de superstructure ;
- les éléments de ventilation intégrés en façade ou en maçonnerie au maintien du niveau de performance attendu.

Pour un lot HVAC, cela signifie que l'acoustique doit être coordonnée avec [[concepts/superstructures|Superstructures]] et non traitée uniquement comme un accessoire de gaine ou de machine.

Le tome T4 pousse cette logique jusqu'à la façade :

- les fenêtres, portes et façades rideaux sont évaluées au regard du bruit extérieur et de l'isolement de façade ;
- T4 rappelle que les valeurs du vitrage seul ne suffisent pas à prédire la performance de la façade complète ;
- l'élément faible devient souvent la grille de ventilation, évaluée par un indicateur propre `Dne,w / Dne,Atr` et non par le seul `Rw` du vitrage ;
- pour les logements en zone bruyante, T4 fixe un affaiblissement minimal de `25 dB` en position ouverte et `40 dB` en position fermée pour les amenées d'air.

Pour le HVAC, cela veut dire qu'une prise d'air, une façade technique ou une amenée naturelle en baie doit être choisie avec la même rigueur acoustique qu'un silencieux de réseau.

Le tome T5 prolonge cette logique à l'intérieur du bâtiment :

- les [[concepts/cloisons-et-doublages-interieurs|Cloisons et Doublages Intérieurs]] peuvent viser des classes acoustiques `IIIa / IIa` et exigent parfois une continuité de performance au-dessus du faux-plafond ;
- les [[concepts/faux-plafonds-et-plafonds-climatiques|Faux-plafonds et Plafonds Climatiques]] comprennent baffles et dalles acoustiques déterminés par étude, en coordination avec gaines, luminaires et détection ;
- les grilles de transfert intérieures peuvent intégrer une isolation acoustique ;
- les [[concepts/planchers-interieurs-techniques|Planchers Intérieurs Techniques]] ajoutent leurs propres performances `Dnfw / Lnfw` et des dispositifs antivibratoires sur vérins.

L'acoustique des techniques ne dépend donc pas seulement des silencieux et capotages T6. Elle dépend aussi de la manière dont T5 ferme les locaux et traite les volumes de distribution.

## Importance en offre publique

Une offre HVAC ne peut pas se contenter d'une simple fiche constructeur sur le niveau sonore. Le marché peut exiger un traitement combiné du bruit aérien, du bruit solidien, des fixations, des traversées et des capotages. En pratique, l'acoustique doit être intégrée dès la réponse technique et non laissée à la mise au point chantier.

## Voir aussi

- [[concepts/distribution-et-regulation-de-ventilation|Distribution et Régulation de Ventilation]] — vitesses, silencieux et manchettes antivibratiles.
- [[concepts/essais-et-mise-au-point-hvac|Essais et Mise au Point HVAC]] — essais acoustiques et rapports.
- [[concepts/faux-plafonds-et-plafonds-climatiques|Faux-plafonds et Plafonds Climatiques]] — coordination acoustique en plénum.
- [[concepts/ouvertures-de-ventilation-en-facade|Ouvertures de Ventilation en Façade]] — performance acoustique des amenées d'air.
