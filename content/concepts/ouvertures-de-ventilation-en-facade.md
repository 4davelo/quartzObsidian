---
aliases:
- Ouvertures de Ventilation en Façade
tags:
- concept
- ventilation
- facade
- amenée-air
- enveloppe
- acoustique
sources:
- T4 Fermetures _ Finitions extérieures CCTB 01.13_20260317.pdf
- T6 HVAC - sanitaires CCTB 01.13_20260317.pdf
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
- enveloppe
---
# Ouvertures de Ventilation en Façade

## Définition

Dans le tome T4 du [[entities/cctb|CCTB]], les ouvertures de ventilation en façade correspondent principalement aux ouvertures d'amenée d'air réglables intégrées à l'enveloppe extérieure. Elles peuvent être réalisées dans le mur, dans la baie hors châssis, dans la quincaillerie, dans le vitrage ou dans le profil de châssis.

## Logique de système

T4 rappelle que ces ouvertures ne se lisent jamais isolément :

- amenée d'air frais dans les locaux secs ;
- transfert d'air via halls et couloirs ;
- extraction dans les locaux humides.

Autrement dit, l'amenée en façade traitée par T4 doit rester cohérente avec le transfert relevant du tome `T5` et l'extraction relevant du tome `T6`.

## Débits et base normative

Le chapitre `41.75` renvoie explicitement à `NBN D 50-001` et reprend les débits indicatifs de base :

- séjour : minimum `75 m³/h`, nominal `surface x 3,6`, maximal `150 m³/h` ;
- chambre : minimum `25 m³/h`, nominal `surface x 3,6`, maximal `36 m³/h` par personne ;
- cuisine fermée : minimum `50 m³/h`, nominal `75 m³/h` ;
- salle de bains, buanderie, WC : `25 à 75 m³/h` suivant le local.

L'aérateur est sélectionné sur son débit nominal sous `2 Pa`. Pour les grilles murales, T4 rappelle aussi qu'environ `3,6 m³/h` passent par `10 cm²` libres sous `2 Pa`.

## Variantes d'intégration

Le tome distingue cinq variantes principales :

- `41.75.1a` amenée d'air dans le mur ;
- `41.75.1b` amenée d'air dans baie hors châssis ;
- `41.75.1c` amenée d'air dans quincaillerie ;
- `41.75.1d` amenée d'air dans vitrage ;
- `41.75.1e` amenée d'air dans profil de châssis.

Cela montre que le choix du système de ventilation influence directement le type de fermeture extérieure retenu et la manière de détailler les baies.

Le chapitre `61.5` de T6 renforce cette lecture en traitant les `OAR` comme de vrais organes de système :

- ouverture réglable manuellement ou automatiquement ;
- au moins trois positions intermédiaires lorsqu'il n'y a pas de réglage continu ;
- débit nominal justifié sous `2 Pa` ;
- classe d'autoréglabilité `P0` à `P4` ;
- valeurs d'insonorisation distinctes en position ouverte et fermée ;
- exigences d'étanchéité à la pluie en position ouverte et fermée ;
- protection contre insectes et nuisibles.

## Exigences d'enveloppe

Même si l'organe sert à ventiler, T4 le traite comme un composant d'enveloppe :

- l'étanchéité des grilles extérieures doit répondre à `NBN EN 13030` ;
- les performances des grilles sont données suivant la série `NBN EN 13141` ;
- les ensembles comprennent grilles extérieures, grilles intérieures et fourreau de passage adaptés l'un à l'autre ;
- les grilles extérieures sont équipées d'un profil récupérateur d'eau ;
- une moustiquaire antistatique inox est prévue côté extérieur pour les solutions murales décrites ;
- le fourreau doit être jointif et dimensionné pour le débit utile.

Pour le lot HVAC, cela signifie qu'une amenée d'air naturelle n'est jamais seulement un "trou avec grille". C'est un assemblage complet façade + conduit court + acoustique + eau + finition.

## Acoustique

T4 est très explicite sur le bruit :

- en zone bruyante, il faut sélectionner des alimentations d'air avec une performance acoustique adaptée ;
- à proximité des aéroports wallons ou d'autres sources de bruit, la solution doit être discutée avec un acousticien ;
- le logement doit atteindre un affaiblissement acoustique minimal `Dne` de `25 dB` en position ouverte et `40 dB` en position fermée.

Ce point est important : la grille de ventilation peut devenir l'élément faible de la façade. Elle doit donc être choisie avec le même niveau d'exigence que le vitrage ou le châssis.

## Locaux techniques et non-habitables

Le tome ne limite pas cette logique aux seuls séjours et chambres. Il rappelle que certains locaux non résidentiels ou communs doivent aussi être ventilés par grilles ou extracteurs mécaniques :

- couloirs communs ;
- cages d'escalier ;
- cages et gaines d'ascenseur ;
- chaufferies ;
- caves ;
- garages.

Le partage exact entre lot façade et lot HVAC doit donc être clarifié dans le [[concepts/csc|CSC]].

## Importance pour un marché public

Dans un marché public, l'interface la plus fréquente entre ventilation et façade n'est pas la CTA mais l'organe d'amenée d'air. Si le type d'OAR, son débit sous `2 Pa`, son acoustique, son emplacement et son raccord à l'enveloppe ne sont pas traités, le lot ventilation reste mal défini même si le système `A`, `C` ou `D` est nommé.

## Pages liées

- [[concepts/ventilation-des-batiments|Ventilation des Bâtiments]]
- [[concepts/distribution-et-regulation-de-ventilation|Distribution et Régulation de Ventilation]]
- [[concepts/acoustique-des-installations-techniques|Acoustique des Installations Techniques]]
- [[concepts/fermetures-et-finitions-exterieures|Fermetures et Finitions Extérieures]]
- [[concepts/menuiseries-exterieures-et-facades|Menuiseries Extérieures et Façades]]

## Voir aussi

- [[meta/source-inventory|Inventaire des Sources]] — liste des documents sources disponibles
