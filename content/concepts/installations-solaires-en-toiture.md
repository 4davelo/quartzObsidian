---
aliases: ["Installations Solaires en Toiture"]
tags: [concept, toiture, solaire, photovoltaïque, thermique, interfaces]
sources: [T3 Travaux de toiture CCTB 01.13_20260317.pdf, T6 HVAC - sanitaires CCTB 01.13_20260317.pdf, T7 Electricité CCTB 01.13_20260317.pdf]
created: 2026-04-22
updated: 2026-04-29
contextes: [technique, appel-doffres]
autorite: [contractuel]
juridictions: [wallonie, bruxelles]
familles_sources: [cctb]
disciplines: [cvc, electricite, enveloppe]
---
# Installations Solaires en Toiture

## Définition

Le tome T3 traite les installations solaires comme des équipements de toiture. Il signale l'interface du solaire thermique avec le tome T6 et décrit en détail les panneaux photovoltaïques en toiture inclinée, en toiture plate et, selon les cas, intégrés à la membrane d'étanchéité.

## Articulation des tomes

- T3 traite les interfaces de toiture : support, fixation, charges, étanchéité, traversées, sécurité et dossier as-built.
- T6 reste la référence pour les installations solaires thermiques comme système HVAC.
- T7 est mobilisé pour les parties électriques, le raccordement au réseau, le parafoudre et la compatibilité avec l'installation électrique.

## Complément électrique du tome T7

Le tome T7 donne un contenu bien plus précis à cette phrase de principe.

Il impose notamment :

- conformité [[concepts/rgie|RGIE]] section `7.112` et `9.1.2` ;
- prescriptions `Synergrid` et `GRD` pour le raccordement ;
- installateur disposant d'au moins un installateur certifié `Qualiwall` ;
- système de monitoring et d'alarme en cas de panne ;
- note de dimensionnement représentative de la situation wallonne moyenne ou issue d'un outil géoréférencé ;
- documents nécessaires à la déclaration au `GRD`, à la réception provisoire et au `DIU`.

Le chapitre photovoltaïque de T7 détaille aussi :

- onduleurs repris sur la liste `C10/26` de `Synergrid` ;
- protections contre courants inverses, surintensités et surtensions `AC/DC` ;
- sectionneur `DC` ;
- câbles `DC` extérieurs résistants `UV`, sans halogène, à chute de tension `<= 2 %` ;
- compteurs du système propres à l'installation et, selon les cas, éligibilité `CWAPE` / certificats verts ;
- signalétique conforme au [[concepts/rgie|RGIE]] ;
- stockage électrique sur batteries `LFP` ;
- système de gestion capable de communiquer les flux énergétiques et de permettre le déclenchement intelligent de charges ou le stockage batterie ;
- mise à la terre des cadres métalliques et structures des modules suivant le [[concepts/rgie|RGIE]].

Pour un marché HVAC, cette couche T7 est décisive dès qu'il faut articuler photovoltaïque, PAC, appoint électrique, ECS, autoconsommation et équipements techniques implantés en toiture ou en local technique.

## Ce que T3 impose

Pour les panneaux photovoltaïques, T3 demande notamment :

- la vérification de stabilité du support ;
- un plan d'implantation détaillé ;
- la note de calcul de production annuelle réelle ;
- les adaptations de couverture, de sous-toiture, d'isolation et de pare-vapeur ;
- le contrôle par organisme agréé ;
- la déclaration au gestionnaire de réseau ;
- la mise en service et le contrôle de bon fonctionnement ;
- le dossier as-built.

Le tome impose aussi :

- une analyse du risque incendie ;
- une analyse du risque foudre ;
- la prise en compte des charges de vent et de neige ;
- la compatibilité électrochimique des fixations ;
- le traitement étanche des traversées de câbles ;
- l'attention à la ventilation et à l'accessibilité du local onduleur.

T3 distingue aussi plusieurs cas d'exécution qui changent réellement l'interface toiture :

- surimposition en toiture inclinée ;
- intégration en toiture inclinée ;
- modules et panneaux sur toiture plate ;
- modules intégrés dans la membrane d'étanchéité.

## Interfaces techniques détaillées

### Toitures inclinées

Pour les toitures inclinées, T3 impose notamment :

- les découpes et resserrages dans sous-toiture, isolation et pare-vapeur ;
- les traversées de câbles avec accessoires assurant l'étanchéité au vent et à l'eau ;
- la fermeture complète de l'isolation autour de la traversée ;
- les manchettes souples adaptées au diamètre du câble au droit du pare-vapeur ;
- la compatibilité des fixations avec la charpente et la couverture ;
- le maintien de la position et de l'inclinaison des éléments de couverture malgré les raccords d'étanchéité.

### Toitures plates

Pour les toitures plates, T3 ajoute des contraintes très proches des préoccupations HVAC de toiture technique :

- fixation, lestage ou ancrage selon justification ;
- compatibilité chimique des couches de désolidarisation avec l'étanchéité ;
- vérification du poinçonnement statique et dynamique de la membrane ;
- vérification du fluage de l'isolation sous charge ;
- traversée de l'étanchéité au moyen d'un fourreau avec bavette ;
- raccord de l'entrée de câbles à l'isolation thermique et au pare-vapeur ;
- positionnement des cadres pour laisser l'eau s'écouler librement ;
- prise en compte des obstacles tels que lanterneaux, cheminées et sorties d'équipements techniques.

### Modules intégrés à la membrane

Quand les modules photovoltaïques sont intégrés dans la membrane :

- la compatibilité avec `34.2 Étanchéités` doit être vérifiée ;
- les zones d'ombre, de circulation et de vent doivent être analysées ;
- une distance minimale par rapport aux relevés, lanterneaux et émergences est explicitement demandée ;
- la pente minimale et les conditions de pose sont encadrées.

## Lien avec le HVAC

Même si le photovoltaïque ne relève pas à lui seul du lot HVAC, cette matière devient utile au lot lorsque le marché comprend :

- solaire thermique ;
- ECS solaire ;
- PAC et stratégie d'autoconsommation ;
- équipements techniques multiples en toiture ;
- coordination des passages, socles et charges sur le toit.

T3 montre alors que le solaire ne se limite pas à la performance énergétique. C'est aussi un sujet d'enveloppe, d'étanchéité, de feu, de foudre et de maintenance.

## Point particulier pour les marchés HVAC

Dans un marché HVAC, ces prescriptions deviennent déterminantes lorsque le lot combine :

- [[concepts/production-de-chaleur|Production de Chaleur]] et solaire thermique ;
- PAC, ventilation et production photovoltaïque en toiture ;
- onduleurs ou équipements thermiques en local technique avec contraintes de chaleur et de bruit ;
- cohabitation entre solaire, [[concepts/ouvertures-de-toiture-et-exutoires|Ouvertures de Toiture et Exutoires]] et traversées de réseaux.

Le chapitre `75` de T7 renforce encore cette lecture en envisageant explicitement certaines combinaisons entre photovoltaïque et [[concepts/chauffage-electrique|Chauffage Électrique]] d'appoint ou d'autoconsommation.

## Importance pour un marché public

Une offre qui mentionne du solaire sans traiter support, traversées, étanchéité, protection incendie, documents réseau et as-built laisse une partie essentielle du lot non décrite. T3 sert précisément à combler cette zone d'interface.

## Pages liées

- [[concepts/travaux-de-toiture|Travaux de Toiture]]
- [[concepts/etancheite-et-isolation-en-toiture|Étanchéité et Isolation en Toiture]]
- [[concepts/production-de-chaleur|Production de Chaleur]]
- [[concepts/dossier-de-cloture|Dossier de Clôture]]
- [[concepts/mise-a-la-terre-et-equipotentialite|Mise à la Terre et Équipotentialité]]

## Voir aussi

- [[meta/source-inventory|Inventaire des Sources]] — liste des documents sources disponibles
