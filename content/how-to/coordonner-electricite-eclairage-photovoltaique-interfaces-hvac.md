---
type: how-to
aliases: [Électricité éclairage photovoltaïque interfaces HVAC, Coordination électrique HVAC, How-to interfaces électriques HVAC]
tags: [how-to, electricite, eclairage, photovoltaique, interfaces-hvac]
sources: [La Technique du bâtiment – Tous corps d’état.epub]
created: 2026-04-29
updated: 2026-04-29
contextes: [appel-doffres, execution-projet, technique]
autorite: [pratique, reference, reglementaire, normatif]
juridictions: [france, generique, ue]
phases: [offre, mobilisation, chantier, mise-en-service, reception, exploitation]
familles_sources: [ouvrage, guide, norme, reglementation]
disciplines: [electricite, cvc, gtb, gestion-projet]
types_projet: [neuf, renovation, remplacement, maintenance]
---

# Coordonner électricité, éclairage, photovoltaïque et interfaces HVAC

## Problème traité

Coordonner les alimentations, protections, raccordements, éclairage, photovoltaïque, commandes et interfaces électriques nécessaires aux équipements techniques du bâtiment.

## Dossier d'entrée et pièces à vérifier

- Puissances, régime de neutre, branchement, tableaux, protections, cheminements, GTB, éclairage, photovoltaïque, schémas et contraintes de sécurité.
- Besoins HVAC : PAC, CTA, pompes, régulation, sondes, alarmes, désenfumage distinct, condensats et maintenance.

## Quand utiliser / quand éviter

- Utiliser dès qu’un lot HVAC dépend du lot électrique ou qu’un équipement technique nécessite alimentation, commande, protection, supervision ou secours.
- Ne pas chiffrer l’équipement seul sans confirmer câble, protection, attente, tableau, commande et essais.

## Options de solution et variantes

- Raccordement direct, tableau dédié, alimentation secourue, bus GTB, commande locale ou centralisée, comptage, photovoltaïque en toiture, éclairage intérieur/extérieur.
- Variantes selon puissance disponible, phasage, supervision, maintenance et exigences de performance.

## Fonctionnement technique

L’interface électrique assure l’énergie, la sécurité, la commande et la preuve de fonctionnement des équipements ; elle conditionne la mise en service HVAC autant que le matériel lui-même.

## Données d'entrée à collecter

- Puissance installée, courant, tension, démarrage, protections, schémas, distances, cheminements, locaux, niveaux d’éclairement, orientation PV, ombrage, intégration toiture.
- Points GTB : protocoles, adresses, alarmes, capteurs, scénarios et responsabilités.

## Dimensionnement et calculs

- Calculer puissance, section de câble, chute de tension, protection, sélectivité, court-circuit, éclairement, production PV et compatibilité démarrage moteur.
- Vérifier charges simultanées HVAC et marge tableau.

### Branchement et alimentation

| Sujet | Repère pratique extrait |
|---|---|
| Branchement < 36 kVA | Basse tension ; monophasé courant 3, 6, 9, 12 kVA. Triphasé si besoin > 12 kVA sans dépasser 36 kVA, ou si distance compteur-tableau principal > 100 m. |
| 36 à 250 kVA | Basse tension ou poste de distribution publique selon étude du gestionnaire ; puissance surveillée. |
| > 250 kVA | Raccordement haute tension/HTA avec transformateur privé à charge de l'usager. |
| Immeuble collectif | Un poste de distribution publique peut être imposé pour la chute de tension ; le promoteur fournit le local/génie civil, équipement par gestionnaire. |
| Chute de tension BT | Entre boîte de jonction et disjoncteur d'abonné via compteur : <= 1,5 % dans le contexte du livre. |
| Hauteur câbles aériens | 5 m au-dessus terrain ordinaire, 6 m au-dessus voiries. Sous voirie, protection mécanique renforcée des câbles enterrés. |

### Éclairage

| Sujet | Repère pratique extrait |
|---|---|
| Méthode | Définir niveau d'éclairement du plan utile, choisir luminaires, calculer flux, puis répartir les foyers selon uniformité. |
| Utilance `U` | Rapport du flux utile au flux total sortant des luminaires ; dépend de la classe du luminaire, des réflexions et de l'indice local `K` compris entre 0,6 et 5. |
| Facteur d'utilisation `u` | `u = eta x U`, avec `eta` rendement du luminaire. |
| Uniformité | Rapport `Emin / Emoy`. |
| Dépréciation | Après un an, poussières et vieillissement peuvent réduire le flux vers 0,9 à 0,7 selon occupation ; coefficient de dépréciation courant cité 1,25 à 1,6. |
| Parois latérales | Acceptable si `0,5 < E3 / E4 < 0,8` selon le critère cité. |

### Photovoltaïque

| Sujet | Repère pratique extrait |
|---|---|
| STC | 1 000 W/m², 25 °C, spectre AM 1,5, soleil à 41,8°. |
| Courbe I/V | `Icc` = courant de court-circuit ; `Vco` = tension de circuit ouvert ; `Pmax` = rectangle maximal de puissance sur la courbe. |
| Facteur de forme | `FF = Pmax / (Icc x Vco)`. |
| Rendement | `eta = Pmax / E`, avec `E` énergie incidente. |
| Puissance cellule | Ordre de grandeur cité : 60 à 200 W électriques pour 1 000 W lumineux selon technologie et pertes. |
| Température | Exemple : cellule monocristalline à 1 000 W/m², `Pmax` de 1,6 W à 10 °C et 1,1 W à 75 °C ; intégrer la température réelle de panneau. |

### Matrice d'interface HVAC à produire

| Équipement HVAC | Données électriques à verrouiller |
|---|---|
| PAC | puissance absorbée, intensité nominale/démarrage, appoint, protection, commande, dégivrage, condensats, coupure extérieure. |
| CTA/VMC | alimentation, puissance ventilateurs, régulation vitesse, sondes, alarmes, clapets, sécurité incendie si concernée. |
| Pompes/circulateurs | alimentation, commande, secours éventuel, vitesse variable, report défaut, protection thermique. |
| Régulation/GTB | protocole, adresses, câbles bus, alimentation sondes, responsabilités de programmation, scénarios et tests. |

Figures sources utiles pour l'éclairage et le photovoltaïque :

## Choix matériels, composants et critères fournisseurs

- Sélectionner protections, câbles, chemins, tableaux, luminaires, onduleurs, modules PV, sondes, automates et compteurs selon données vérifiables.
- Exiger schémas, notices, certificats, paramètres et compatibilité GTB.

## Estimation, métrés et postes de prix

- Inclure câbles, protections, tableaux, chemins, raccordements, commandes, sondes, essais, programmation, repérage, schémas et as-built.
- Pour PV : supports, intégration toiture, étanchéité, câblage DC/AC, onduleur, protections, monitoring et réception.

## Interfaces BTP et limites de prestations

- Clarifier attente électrique, raccordement final, commande, GTB, alimentation secourue, coupure d’urgence, câblage de sondes, traversées et rebouchages.
- Interfaces toiture/façade pour PV, luminaires extérieurs, prises d’air/rejets, supports et étanchéité.

## Exigences contractuelles, réglementaires et normatives

Les références françaises du livre sont informatives. En Belgique, vérifier RGIE, CSC, normes activées, réception électrique et exigences de gestionnaire réseau.

## Préparation d'exécution et coordination chantier

Produire matrice équipements/puissances, plans de cheminement, synoptiques, schémas, réservations, liste signaux GTB et responsabilités de câblage.

## Mise en œuvre

- Poser chemins, câbles, tableaux, protections, luminaires, capteurs et équipements PV selon plans validés.
- Repérer circuits, protéger traversées, maintenir accès et documenter modifications.
- Ne pas laisser l'alimentation HVAC au stade “attente à proximité” : définir raccordement final, câble, protection, sectionneur, commande et essais.
- Poser les chemins de câbles et bus GTB avec réserves d'accès et séparation des courants si exigée.
- Pour PV, coordonner support, étanchéité, cheminement DC, onduleur, ventilation, coupure et accès maintenance avant pose toiture.
- Pour éclairage, contrôler implantation réelle avec faux-plafond, grilles, détecteurs, sprinklage et maintenance.

## Contrôles, essais, réglages et mise en service

Tester continuité, isolement, protections, sens de rotation, commandes, alarmes, scénarios GTB, niveaux d’éclairement, production PV et coupures de sécurité.

Contrôles à documenter :

- électrique : continuité PE, isolement, déclenchements, sens de rotation, sélectivité si demandée, repérage tableau/circuit ;
- HVAC : marche/arrêt local et distant, reports défaut, alarmes, sécurités, interverrouillages et reprise après coupure ;
- éclairage : niveaux mesurés, uniformité, scénarios de commande, détecteurs et maintenance ;
- PV : polarités DC, protections, onduleur, monitoring, mise à la terre/équipotentialité, étanchéité toiture et réception gestionnaire si applicable.

## Réception, dossier de clôture et as-built

Remettre schémas as-built, plans, rapports de contrôle, fiches, certificats, paramètres GTB, notices, garanties et attestations de réception.

## Exploitation, maintenance, garantie

Prévoir accès tableaux, onduleurs, luminaires, capteurs, protections, pièces de rechange et procédure d’intervention.

## Risques, questions à poser et points de vigilance

- Alimentation oubliée, puissance insuffisante, GTB non coordonnée, protection mal dimensionnée, réception électrique tardive, PV sans interface toiture claire.
- Poser question si la limite entre fourniture HVAC et alimentation électrique n’est pas écrite.

## Sources et sections liées

Sections sources utilisées pour extraire les valeurs, procédures et points de vigilance ci-dessus :

- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/317-47-1-production-distribution-et-fourniture-d-electricite|La Technique du bâtiment – Tous corps d’état — 317 47.1 Production, distribution et fourniture d’électricité]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/318-47-2-branchement-de-l-usager-en-fonction-de-la-puissance|La Technique du bâtiment – Tous corps d’état — 318 47.2 Branchement de l’usager en fonction de la puissance]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/319-47-3-modalites-techniques-de-raccordement|La Technique du bâtiment – Tous corps d’état — 319 47.3 Modalités techniques de raccordement]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/320-48-1-protection-contre-les-dangers-du-courant-electrique|La Technique du bâtiment – Tous corps d’état — 320 48.1 Protection contre les dangers du courant électrique]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/323-49-1-origine-de-l-installation|La Technique du bâtiment – Tous corps d’état — 323 49.1 Origine de l’installation]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/325-49-2-tableau-d-abonne|La Technique du bâtiment – Tous corps d’état — 325 49.2 Tableau d’abonné]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/326-49-3-petit-equipement|La Technique du bâtiment – Tous corps d’état — 326 49.3 Petit équipement]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/327-49-4-detection-de-fumee|La Technique du bâtiment – Tous corps d’état — 327 49.4 Détection de fumée]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/328-49-5-types-de-courants-et-distribution-adaptee|La Technique du bâtiment – Tous corps d’état — 328 49.5 Types de courants et distribution adaptée]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/329-49-6-connexions|La Technique du bâtiment – Tous corps d’état — 329 49.6 Connexions]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/334-50-1-realisation-des-niveaux-d-eclairement|La Technique du bâtiment – Tous corps d’état — 334 50.1 Réalisation des niveaux d’éclairement]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/336-50-2-appreciation-des-quantites-de-lumiere|La Technique du bâtiment – Tous corps d’état — 336 50.2 Appréciation des quantités de lumière]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/339-51-1-photons-semi-conducteurs-et-electricite|La Technique du bâtiment – Tous corps d’état — 339 51.1 Photons, semi conducteurs et électricité]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/340-51-2-generation-du-flux-electrique|La Technique du bâtiment – Tous corps d’état — 340 51.2 Génération du flux électrique]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/341-51-3-cellules-photovoltaiques-et-silicium|La Technique du bâtiment – Tous corps d’état — 341 51.3 Cellules photovoltaïques et silicium]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/342-51-4-performances-des-cellules-photovoltaiques|La Technique du bâtiment – Tous corps d’état — 342 51.4 Performances des cellules photovoltaïques]]

## Voir aussi

- [[concepts/electricite-et-interfaces-hvac|Électricité et Interfaces HVAC]]
- [[concepts/gtb-et-regulation-hvac|GTB et Régulation HVAC]]
- [[concepts/installations-solaires-en-toiture|Installations Solaires en Toiture]]
- [[concepts/interfaces-et-limites-de-prestations|Interfaces et Limites de Prestations]]
