---
type: how-to
aliases: [Chauffage ECS PAC solaire thermique, Dimensionnement chauffage ECS, How-to chauffage ECS PAC]
tags: [how-to, hvac, chauffage, ecs, pac, solaire-thermique]
sources: [La Technique du bâtiment – Tous corps d’état.epub]
created: 2026-04-29
updated: 2026-04-29
contextes: [appel-doffres, execution-projet, technique]
autorite: [pratique, reference, reglementaire, normatif]
juridictions: [france, generique, ue]
phases: [offre, mobilisation, chantier, mise-en-service, reception, exploitation]
familles_sources: [ouvrage, guide, norme, reglementation]
disciplines: [cvc, sanitaire, electricite, gtb]
types_projet: [neuf, renovation, remplacement, maintenance]
---

# Concevoir et dimensionner chauffage, ECS, PAC et solaire thermique

## Problème traité

Structurer le choix et le dimensionnement des systèmes de chauffage, ECS, pompes à chaleur et solaire thermique en reliant besoin, production, distribution, émission, régulation et réception.

## Dossier d'entrée et pièces à vérifier

- Besoins chauffage/ECS, occupation, profils de puisage, enveloppe, régime d’eau, émetteurs, énergie disponible, local technique, évacuation, acoustique, PEB et maintenance.
- Contraintes de RE 2020/RT/DTU dans le livre à considérer comme françaises, puis à recaler sur le contexte belge du projet.

## Quand utiliser / quand éviter

- Utiliser en étude d’offre, variante, remplacement générateur, rénovation énergétique, création ECS ou intégration PAC/solaire.
- Ne pas choisir le générateur sans vérifier régime d’émission, puissance électrique, stockage ECS, pertes de distribution et conditions de mise en service.

## Options de solution et variantes

- Effet Joule, chauffage central combustible, biomasse, PAC, solaire thermique, ECS indépendante ou couplée, distribution radiateurs, plancher chauffant ou tubes incorporés.
- Comparer coût complet, performance saisonnière, maintenance, encombrement, bruit, sécurité, énergie et disponibilité.

## Fonctionnement technique

Le système transforme une énergie primaire ou renouvelable en chaleur utile, la stocke ou la distribue, puis l’émet selon un régime de température et une régulation adaptés au bâtiment.

## Données d'entrée à collecter

- Déperditions, températures de base, régime départ/retour, puissance, volume ECS, simultanéité, longueur réseaux, pertes, isolation, source froide PAC, surface capteurs, orientation, ombrage et stockage.
- Contraintes gaz, fumées, ventilation local, condensats, bruit, électricité, accès et garanties.

## Dimensionnement et calculs

- Calculer puissance de production, émetteurs, pertes de charge, diamètres, pompes, vase d’expansion, sécurité, stockage ECS, bouclage et appoint.
- Pour PAC : vérifier puissance aux conditions réelles, COP/SCOP, appoint, dégivrage, bruit et température de départ.
- Pour solaire : vérifier orientation, surface, volume, appoint, surchauffe, sécurité et maintenance.

### Chauffage et émetteurs

| Sujet | Repère pratique extrait |
|---|---|
| Corps de chauffe | Les puissances catalogue sont valables pour des raccordements normalisés ; contrôler le mode de raccordement réel avant de reprendre la puissance indiquée. |
| Radiateurs fonte | Épreuve hydraulique usine citée à 14 bar pour pression maximale de service 8 bar. Au-delà de 14 éléments, livraison en tronçons et assemblage sur place. |
| Raccordement radiateur | Pour des radiateurs de dimensions courantes, certains raccordements donnent une puissance légèrement supérieure de 1 à 2 %. Pour des radiateurs très longs, une perte de puissance mesurée de 2,3 % est citée. |
| Débit radiateur | Pour les trois raccordements expérimentés dans le livre, au-dessus de 50 l/h la chute d'émission reste de l'ordre de 5 %. |

### PAC

| Sujet | Repère pratique extrait |
|---|---|
| Sources froides | Air extérieur ou extrait, eau souterraine/surface, sol horizontal ou vertical. |
| Couplages | Air/air, air/eau, eau/eau, sol/eau, eau glycolée/eau, sol/sol. |
| Circuits | Détente directe = un seul circuit frigorigène ; PAC mixte = circuit frigorigène + eau chaude ; fluides intermédiaires = circuit frigorifique + capteurs antigel + émetteurs eau chaude. |
| COP | Ordre de grandeur cité : COP 3 à 5, mais valable aux conditions d'essai ; utiliser le SCOP pour la lecture saisonnière. |
| Air/air | Exemple cité : COP 3,4 à 7 °C et 2 à -7 °C. |
| Air/eau | Exemple cité : COP 3,4 à 7 °C et 2,1 à -7 °C avec eau à 35 °C. |
| Géothermie horizontale | Capteurs enterrés à 0,6 à 1,2 m ; surface de capteurs de l'ordre de 1,5 à 2 fois la surface à chauffer. |

### ECS

| Sujet | Repère pratique extrait |
|---|---|
| Production instantanée | Puissance dimensionnée sur la consommation de pointe courte ; temps d'attente avant eau chaude, donc risque de gaspillage eau/énergie. |
| Semi-accumulation | Petite réserve pour amortir la pointe sur 10 min ou 1 h selon configuration. |
| Accumulation | Ballon couvrant les besoins importants ; plus de confort mais plus de maintien en température et vigilance sanitaire. |
| Temps d'attente ECS | `Ts = somme(EEu x L) / Dv`, avec `EEu` en l/m, `L` longueur en m et `Dv` débit volumique. |
| Bouclage ECS | À prévoir si les longueurs maximales de puisage sont dépassées ; retour vers générateur avec circulateur spécifique, diamètre intérieur minimum 10 mm. |
| Isolation boucle | Limiter les pertes à 10 W/m ; en hydrocâblé avec recyclage, aquastat de circulateur cité à 35 °C et isolation `k < 0,3 W/m.°C`. |

### Solaire thermique

| Sujet | Repère pratique extrait |
|---|---|
| Bonnes pratiques | Choisir de préférence des capteurs avec avis technique ; réaliser une étude précise des besoins ECS/chauffage/appoint. |
| Toiture | Traiter soigneusement jonctions, percements et raccords pour ne pas dégrader la couverture. |
| Coût global | Comparer investissement, remplacement des équipements, entretien et exploitation selon potentiel local. |
| Capteurs | Les fiches doivent distinguer surface hors tout, surface d'entrée, dimensions, masse, raccords et intégration. |

Figures sources utiles pour vérifier les raccordements et l'ECS :

## Choix matériels, composants et critères fournisseurs

- Exiger fiches générateur, émetteurs, circulateurs, régulation, ballons, échangeurs, capteurs, soupapes, disconnecteurs, vases et calorifuge.
- Vérifier garanties, disponibilité, certificats, notice, mise en service fabricant et pièces d’usure.
- Pour une PAC, refuser une fiche qui ne donne que le COP nominal : demander conditions d'essai, puissance utile à basse température extérieure, puissance absorbée, niveau sonore, fluide, dégivrage et plage de départ eau.
- Pour l'ECS, exiger les tableaux ou calculs reliant profil de puisage, puissance, stockage, longueur de distribution et besoin éventuel de bouclage.
- Pour le solaire thermique, vérifier avis technique, compatibilité couverture, dilatation, fluide, protection gel/surchauffe, ballon, appoint et accès maintenance.

## Estimation, métrés et postes de prix

- Inclure générateur, stockage, distribution, émission, régulation, alimentation, évacuations, supports, calorifuge, remplissage, traitement d’eau, essais, mise en service et dossier de clôture.
- Prévoir accessoires et interfaces : socles, percements, conduits, protections, condensation, rejet, GTB et acoustique.

## Interfaces BTP et limites de prestations

- Gros oeuvre/toiture/façade : socles, traversées, capteurs, prises/rejets, étanchéité.
- Électricité/GTB : alimentation, protections, régulation, sondes, supervision.
- Sanitaire : stockage ECS, bouclage, protection réseau, évacuations et anti-brûlure.

## Exigences contractuelles, réglementaires et normatives

Les références françaises du livre encadrent son contexte. Pour un marché belge, transformer ces repères en questions de conformité au CSC, au CCTB/CCT applicable, à la PEB et aux normes belges activées.

## Préparation d'exécution et coordination chantier

Soumettre schémas, notes de calcul, fiches, implantation, détails de traversées, plans de régulation, accès maintenance et stratégie de mise en service.

## Mise en œuvre

- Poser réseaux, générateurs, émetteurs, capteurs, ballons, organes de sécurité, calorifuge et régulation selon plans approuvés.
- Nettoyer, rincer, remplir, purger, protéger contre corrosion/gel et repérer les organes.
- Placer les émetteurs et radiateurs selon le raccordement retenu dans le calcul, pas seulement selon facilité de chantier.
- Sur réseaux ECS bouclés, limiter les longueurs inutiles, isoler la boucle et rendre le circulateur accessible.
- Sur PAC extérieure, traiter socle, acoustique, dégivrage, condensats, accès maintenance et puissance électrique avant livraison.
- Sur capteurs solaires, contrôler étanchéité toiture, pente, fixation, traversées et protection des raccords avant fermeture.

## Contrôles, essais, réglages et mise en service

Essais pression, étanchéité, circulation, purge, température, régulation, sécurité, combustion ou fluide, bruit, équilibrage, performances et rapports fabricant.

Contrôles minimaux :

- chauffage : rinçage, remplissage, purge, pression, vase, soupape, circulateurs, équilibrage, régulation, températures départ/retour ;
- ECS : temps d'attente, température, boucle, pertes, sécurité anti-brûlure, purge, clapets, protection réseau ;
- PAC : sens de circulation, débit, delta T, dégivrage, appoint, bruit, paramètres, consignation fluide si concernée ;
- solaire : pression, fluide, purge, vase, soupape, appoint, régulation, sonde, absence de fuite en toiture.

## Réception, dossier de clôture et as-built

Remettre as-built, schémas, notes, fiches, garanties, PV, paramètres, notices, écolage et consignes d’entretien.

## Exploitation, maintenance, garantie

Documenter périodicités, traitement d’eau, filtres, capteurs, fluide, organes de sécurité, contrats d’entretien et conditions de garantie.

## Risques, questions à poser et points de vigilance

- Régime trop élevé pour PAC, ECS sous-dimensionnée, bouclage oublié, bruit extérieur, vase d’expansion inadéquat, condensats non traités, capteurs ombragés.
- Questionner si puissance, énergie, appoint, stockage ou limites de prestation sont absents du dossier.

## Sources et sections liées

Sections sources utilisées pour extraire les valeurs, procédures et points de vigilance ci-dessus :

- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/250-35-1-generalites-sur-la-production|La Technique du bâtiment – Tous corps d’état — 250 35.1 Généralités sur la production]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/251-35-2-generalites-sur-les-emetteurs|La Technique du bâtiment – Tous corps d’état — 251 35.2 Généralités sur les émetteurs]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/252-36-1-convecteurs-electriques|La Technique du bâtiment – Tous corps d’état — 252 36.1 Convecteurs électriques]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/254-36-2-panneaux-radiants|La Technique du bâtiment – Tous corps d’état — 254 36.2 Panneaux radiants]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/255-36-3-panneaux-rayonnants|La Technique du bâtiment – Tous corps d’état — 255 36.3 Panneaux rayonnants]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/262-37-1-production-individuelle-au-fuel|La Technique du bâtiment – Tous corps d’état — 262 37.1 Production individuelle au fuel]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/264-37-2-production-individuelle-au-gaz|La Technique du bâtiment – Tous corps d’état — 264 37.2 Production individuelle au gaz]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/265-37-3-production-individuelle-au-bois-biomasse|La Technique du bâtiment – Tous corps d’état — 265 37.3 Production individuelle au bois /biomasse]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/267-38-1-distribution-principale-en-immeuble-collectif|La Technique du bâtiment – Tous corps d’état — 267 38.1 Distribution principale en immeuble collectif]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/269-38-2-distribution-individuelle|La Technique du bâtiment – Tous corps d’état — 269 38.2 Distribution individuelle]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/270-39-1-corps-de-chauffe|La Technique du bâtiment – Tous corps d’état — 270 39.1 Corps de chauffe]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/272-39-2-reseau-de-distribution|La Technique du bâtiment – Tous corps d’état — 272 39.2 Réseau de distribution]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/273-39-3-tubes-incorpores-dans-la-dalle-de-plancher|La Technique du bâtiment – Tous corps d’état — 273 39.3 Tubes incorporés dans la dalle de plancher]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/274-39-4-regulation-du-chauffage|La Technique du bâtiment – Tous corps d’état — 274 39.4 Régulation du chauffage]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/275-40-1-principes-de-fonctionnement|La Technique du bâtiment – Tous corps d’état — 275 40.1 Principes de fonctionnement]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/277-40-2-composants-d-une-pompe-a-chaleur|La Technique du bâtiment – Tous corps d’état — 277 40.2 Composants d’une pompe à chaleur]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/278-40-3-differents-types-de-pac|La Technique du bâtiment – Tous corps d’état — 278 40.3 Différents types de PAC]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/279-40-4-pac-geothermiques|La Technique du bâtiment – Tous corps d’état — 279 40.4 PAC géothermiques]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/280-40-5-pac-aerothermiques|La Technique du bâtiment – Tous corps d’état — 280 40.5 PAC aérothermiques]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/281-40-6-pompes-a-chaleur-traditionnelles-synthese|La Technique du bâtiment – Tous corps d’état — 281 40.6 Pompes à chaleur traditionnelles : synthèse]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/282-40-7-pompes-a-chaleur-utilisant-les-energies-renouvelables|La Technique du bâtiment – Tous corps d’état — 282 40.7 Pompes à chaleur utilisant les énergies renouvelables]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/284-41-1-puissance-installee-pour-l-eau-chaude-sanitaire|La Technique du bâtiment – Tous corps d’état — 284 41.1 Puissance installée pour l’eau chaude sanitaire]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/286-41-2-production-d-eau-chaude-sanitaire-par-appareils-electriques|La Technique du bâtiment – Tous corps d’état — 286 41.2 Production d’eau chaude sanitaire par appareils électriques]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/287-41-3-production-d-eau-chaude-sanitaire-par-appareils-a-gaz|La Technique du bâtiment – Tous corps d’état — 287 41.3 Production d’eau chaude sanitaire par appareils à gaz]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/288-41-4-production-d-eau-chaude-sanitaire-par-couplage-avec-le-chauffage-central|La Technique du bâtiment – Tous corps d’état — 288 41.4 Production d’eau chaude sanitaire par couplage avec le chauffage central]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/289-41-5-distribution-d-eau-chaude-sanitaire|La Technique du bâtiment – Tous corps d’état — 289 41.5 Distribution d’eau chaude sanitaire]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/290-42-1-bref-historique-du-solaire|La Technique du bâtiment – Tous corps d’état — 290 42.1 Bref historique du solaire]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/292-42-2-etat-des-lieux-du-solaire|La Technique du bâtiment – Tous corps d’état — 292 42.2 État des lieux du solaire]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/293-42-3-le-chauffe-eau-solaire-individuel-cesi|La Technique du bâtiment – Tous corps d’état — 293 42.3 Le chauffe eau solaire individuel (CESI)]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/294-42-4-qualisol-charte-de-qualite-pour-la-mise-en-oeuvre-des-installations-solaires|La Technique du bâtiment – Tous corps d’état — 294 42.4 Qualisol, charte de qualité pour la mise en œuvre des installations solaires]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/295-42-5-apercu-du-dimensionnement-des-installations-de-cesi|La Technique du bâtiment – Tous corps d’état — 295 42.5 Aperçu du dimensionnement des installations de CESI]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/296-42-6-capteurs-solaires|La Technique du bâtiment – Tous corps d’état — 296 42.6 Capteurs solaires]]

## Voir aussi

- [[concepts/production-de-chaleur|Production de Chaleur]]
- [[concepts/distribution-et-emission-de-chaleur|Distribution et Émission de Chaleur]]
- [[concepts/eau-chaude-sanitaire|Eau Chaude Sanitaire]]
- [[concepts/dimensionnement-hvac|Dimensionnement HVAC]]
- [[concepts/essais-et-mise-au-point-hvac|Essais et Mise au Point HVAC]]
