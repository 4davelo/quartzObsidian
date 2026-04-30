---
aliases:
- Production de Chaleur
tags:
- concept
- chauffage
- chaleur
- chaudières
- pac
- solaire
- conformité
sources:
- T6 HVAC - sanitaires CCTB 01.13_20260317.pdf
- T7 Electricité CCTB 01.13_20260317.pdf
- T0 Entreprise _ Chantier CCTB 01.13_20260317.pdf
- T6 HVAC - sanitaires CCTB 01.13.pdf
- CCT105TB FR 2023.pdf
- Note info_CTI_HVAC_SAPC17-vase expansion.pdf
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
- belgique
familles_sources:
- cctb
- contrat
- guide
disciplines:
- cvc
---
# Production de Chaleur

## Définition

Le chapitre `63` du tome T6 couvre la production de chaleur au sens large : générateurs, études, raccordements, essais, garanties, documentation, exigences environnementales et coordination d'exécution. Pour un lot HVAC, c'est le coeur du volet chauffage.

## Ce que l'installation doit comprendre

Pour les installations individuelles, T6 considère comme faisant partie de l'installation complète :

- les chaudières ou autres générateurs et leurs accessoires ;
- les vases d'expansion, circulateurs, purgeurs et sécurités ;
- les réseaux de distribution et collecteurs ;
- les émetteurs ;
- les essais, contrôles et remplacements correctifs jusqu'au parfait fonctionnement ;
- une garantie complète jusqu'à la réception définitive, avec au moins un entretien ;
- les attestations, certificats, rapports de contrôle et plans as-built.

## Études, calculs et qualité d'eau

T6 insiste sur :

- le calcul des déperditions par local selon `NBN EN 12831-1` et son annexe nationale ;
- le dimensionnement hydraulique et la vérification des diamètres ;
- l'attention à la qualité de l'eau de remplissage et d'appoint ;
- la prévention des dépôts et de la corrosion selon `NIT 278`.

Pour les systèmes à très basse température, le tome recommande les chaudières à condensation. Pour le chauffage par le sol, il renvoie aux `NIT 273` et `NIT 181` et limite la température de surface à `29 °C` en zone d'usage et `34 °C` en zone périphérique.

Le chapitre introductif `63` rappelle aussi trois appuis de méthode souvent sous-estimés dans les offres :

- `NIT 235` pour la chaudière à condensation ;
- `NIT 278` pour la prévention des dépôts et de la corrosion ;
- `NIT 155` pour l'estimation des besoins nets en énergie de chauffage.

Le [[entities/cct-105|CCT 105]] renforce cette logique par le chapitre [[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/24-chapitre-a-calcul-des-installations|A Calcul des installations]] et par les articles relatifs aux chaudières, pompes à chaleur, systèmes d'expansion et essais sur place.

## Sécurités hydrauliques et expansion

Les [[concepts/vases-dexpansion|Vases d'expansion]] sont un point de sécurité de la production de chaleur. La note CTI SAPC17 montre que leur dimensionnement dépend du contenu en eau, du volume d'expansion, de la réserve d'eau, de la hauteur statique, de la pression de gonflage ou de réglage, de la pression finale et de la soupape de sécurité.

Dans une offre chauffage, il faut donc traiter le vase comme une donnée de calcul et de réception, pas comme un accessoire générique. Le CCT 105 rattache ce sujet à l'[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/33-article-a6-dimensionnement-des-vases-d-expansion|article A6]] pour le calcul et à l'[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/96-article-c5-systemes-d-expansion-et-de-securite|article C5]] pour les systèmes d'expansion et de sécurité.

## Cadre d'exécution et d'agréation

La production de chaleur est encadrée par un socle réglementaire large : [[concepts/rgie|RGIE]], `RGPT`, [[entities/cct-105|CCT 105]], normes NBN, prescriptions des distributeurs, règles de sécurité incendie, émissions polluantes et chantiers temporaires.

T6 ajoute un point important pour les marchés publics : pour les ouvrages sous-traités, l'entrepreneur principal s'adresse à des installateurs agréés dans les sous-catégories `D16`, `D17` ou `D18` selon le périmètre. Cela renforce directement l'importance de [[concepts/agrement-entrepreneurs|Agréation d'Entrepreneurs]] dans les lots HVAC.

## Sources de production couvertes

Le tome détaille des productions à partir :

- du gaz ;
- du mazout ;
- du bois et des végétaux ;
- du chauffage urbain ;
- de la cogénération ;
- des pompes à chaleur au sens large ;
- du soleil ;
- de l'électricité ;
- plus marginalement du charbon et de la géothermie.

## [[concepts/peb|PEB]] et permis

T6 rappelle que les données de performance du générateur doivent être transmises pour les calculs PEB :

- `η30%` et température de retour de conception pour certaines chaudières ;
- `COPtest` et performance saisonnière pour les PAC.

Le tome rappelle aussi les classes de permis ou déclarations environnementales selon la puissance des installations de combustion.

L'introduction `63` rattache en plus explicitement les installations au cadre `AGW 2009-01-29` sur la pollution atmosphérique et la consommation énergétique des installations de chauffage central.

## Focus PAC

Le chapitre `63.26` donne un niveau de détail élevé sur les PAC :

- distinction entre PAC air/eau, air/air, eau glycolée/eau et eau/eau ;
- objectifs de SPF recommandés par `NBN EN 15450` ;
- seuils de classement environnemental pour les cycles frigorifiques ;
- bruit mesuré à `3,5 m` de la façade avec une cible `<= 40 dB` ;
- documents minimums à fournir : fiches techniques et environnementales, ACV, manuels, dossier technique complet et certification du technicien frigorifique ;
- vigilance sur le choix des fluides frigorigènes au regard du `Règlement (UE) 2024/573`.

## Complément électrique du tome T7

Le tome T7 complète directement cette page sur quatre points.

### Raccordements de production

T7 prévoit des postes dédiés pour :

- le raccordement avec la pompe à chaleur ;
- le raccordement avec la cogénération ;
- le raccordement avec les panneaux photovoltaïques ;
- plus largement, les tableaux, protections, conducteurs et cheminements nécessaires au raccordement des générateurs.

### Gestion énergétique

Le chapitre photovoltaïque de T7 couvre monitoring, alarmes de panne, stockage batterie et systèmes de gestion capables d'optimiser l'usage de l'électricité produite. Cela intéresse directement les stratégies de [[concepts/production-de-chaleur|Production de Chaleur]] fondées sur PAC, appoint électrique, ECS électrique ou arbitrage autoconsommation / injection.

### Chauffage électrique

T7 ajoute aussi un chapitre `75` complet sur le [[concepts/chauffage-electrique|Chauffage Électrique]]. Il ne remplace pas les générateurs hydroniques décrits dans T6, mais il encadre les cas où une production ou un appoint thermique est directement électrique : chaudières électriques, aérothermes, rideaux d'air chaud, accumulation ou appoints locaux.

### Terre et protections

La mise à la terre, l'équipotentialité, les parafoudres et le raccordement `BT` de T7 sont essentiels pour les générateurs, en particulier PAC, onduleurs et équipements de production hybrides. La production de chaleur ne peut donc pas être lue uniquement comme une affaire hydraulique ou thermodynamique.

## Importance en marché public

Une offre chauffage recevable ne peut pas se limiter au générateur. T6 attend une réponse globale : calculs, qualité d'eau, documents, sécurité, gestion des rejets, compatibilité réglementaire, maintenance et articulation avec les autres chapitres techniques du [[concepts/csc|CSC]].

## Voir aussi

- [[concepts/distribution-et-emission-de-chaleur|Distribution et Émission de Chaleur]] — réseaux, émetteurs et accessoires hydrauliques.
- [[concepts/vases-dexpansion|Vases d'expansion]] — calcul et sécurité hydraulique.
- [[concepts/dimensionnement-hvac|Dimensionnement HVAC]] — pertes, puissances et volumes.
- [[concepts/essais-et-mise-au-point-hvac|Essais et Mise au Point HVAC]] — essais chaudières, réglages et rapports.
