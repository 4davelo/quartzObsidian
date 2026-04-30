---
type: how-to
aliases: [Réseaux enterrés et infrastructures techniques, VRD et interfaces techniques, How-to réseaux enterrés]
tags: [how-to, btp, reseaux-enterres, vrd, interfaces]
sources: [La Technique du bâtiment – Tous corps d’état.epub]
created: 2026-04-29
updated: 2026-04-29
contextes: [appel-doffres, execution-projet, technique]
autorite: [pratique, reference, reglementaire, normatif]
juridictions: [france, generique, ue]
phases: [offre, mobilisation, chantier, mise-en-service, reception, exploitation]
familles_sources: [ouvrage, guide, norme, reglementation]
disciplines: [cvc, sanitaire, electricite, gestion-projet]
types_projet: [neuf, renovation, remplacement, maintenance]
---

# Coordonner les réseaux enterrés et infrastructures techniques

## Problème traité

Organiser les réseaux enterrés et infrastructures d’accueil pour éviter conflits de tracé, profondeurs incompatibles, attentes manquantes et reprises coûteuses.

## Dossier d'entrée et pièces à vérifier

- Plans VRD, nivellement, réseaux existants, branchements concessionnaires, exigences EP/EU, eau, gaz, électricité, courants faibles, éclairage extérieur et locaux techniques.
- Contraintes de voirie, accessibilité, zones piétonnes, biodiversité et gestion des eaux pluviales.

## Quand utiliser / quand éviter

- Utiliser dès l’offre et les études d’exécution lorsque le lot HVAC/sanitaire/électricité dépend de tranchées, attentes, chambres, traversées ou branchements.
- Éviter de valider un tracé sans altimétrie, croisement réseaux et exutoires confirmés.

## Options de solution et variantes

- Tranchées séparées ou communes, fourreaux, chambres de tirage, regards, noues, bassins, réseaux gravitaires ou pompés, rétention/infiltration.
- Déplacer un réseau, augmenter une profondeur ou prévoir protection mécanique lorsque les croisements l’imposent.

## Fonctionnement technique

Les réseaux enterrés fonctionnent comme système spatial autant que technique : pente, profondeur, protection, accessibilité, distances et ordre de pose conditionnent la maintenabilité.

## Données d'entrée à collecter

- Débits EP/EU, niveaux d’exutoires, diamètres, pente, profondeur hors gel, réservations, rayons de courbure, alimentation, puissance, fibres, compteurs et chambres.
- Exigences de compactage, remblais, protection, repérage, essais et récolements.

## Dimensionnement et calculs

- Calculer diamètres, pentes, pertes, débits, volumes de rétention, sections de fourreaux, tirage des câbles et profondeurs minimales.
- Vérifier croisement altimétrique entre EU, EP, eau, gaz, électricité, courants faibles et techniques HVAC.

### Valeurs et formules à garder dans la note

| Réseau | Repères pratiques extraits |
|---|---|
| EU séparatif | Débit instantané simplifié : `Q = 0,019 x N` l/s, avec `N` = nombre d'habitations desservies. Pour opérations de faible ou moyenne densité, diamètre 200 mm souvent adapté. |
| Pentes EU | La pente du réseau suit le terrain si elle reste entre 0,3 % et 15 %. Branchement : pente souhaitable 3 % pour limiter stagnation et dépôts. |
| EP | Choisir entre évacuation rapide, rétention et infiltration. L'évacuation rapide vers l'aval est coûteuse et peut aggraver l'inondation ; elle n'est en principe plus admise dans le contexte du livre. |
| EP calcul | Déterminer soit le débit maximal à évacuer, soit le volume maximal à stocker/infiltrer selon la période de retour retenue avec le maître d'ouvrage et la collectivité. |
| Collecteurs EP/unitaires | Ne pas descendre sous 300 mm pour permettre l'entretien. Dimensionner le diamètre selon débit et pente. |
| Regards EU/EP | Tracé rectiligne recherché ; chaque changement de direction appelle un regard. Distance courante entre regards : 50 à 100 m. |
| Regards de visite | Section intérieure indicative : 0,80 m jusqu'à 1 m de profondeur, puis 1 m au-delà. |
| Canalisations EU/EP | EP ou unitaire : béton comprimé jusqu'à 400 mm, béton centrifugé armé à partir de 300 mm. EU : PVC. Pose sur lit de sable ; enrobage béton si couverture sous chaussée insuffisante. |
| Branchements | Canalisation de branchement minimum 150 mm, toujours inférieure au collecteur ; diamètres fréquents 150 à 300 mm. Culottes de branchement réservées aux collecteurs <= 400 mm. |
| Bouches/avaloirs | Bouches sélectives seulement si entretien permanent ; bouches à passage direct si pente >= 7 mm/m. Réseaux correctement ventilés. |

### Réseaux concessionnaires et techniques

| Sujet | Repère pratique |
|---|---|
| Eau potable | Réseau ramifié ou maillé ; le maillage facilite isolement et réalimentation. Diamètre minimal de distribution cité : 40 mm. |
| Défense incendie | Débit repère 60 m³/h pendant 2 h ; pression de service 1 bar, exceptionnellement 0,6 bar ; logement à moins de 200 m d'un point d'eau par chemin praticable. |
| Calcul eau | Débit de pointe simplifié : 0,5 l/s par logement ; exemples cités : 1,32 l/s pour 20 logements, 2,21 l/s pour 50 logements, 17 l/s pour la défense incendie. |
| Vitesse eau | Si pression < 2 bar, réduire pertes et augmenter diamètres, mais éviter une vitesse < 0,5 m/s au débit de pointe ; éviter > 2,5 m/s y compris en débit incendie. |
| Pose eau | Lit de sable, pente 2 à 3 mm/m vers points hauts pour évacuation d'air ; purges en points bas et vannes d'isolement. |
| Gaz | Moyenne pression B : 0,4 à 4 bar. Branchement souvent PE calibre 15 ; ne pas réaliser le branchement gaz avant construction du bâtiment. |
| Électricité BT | Estimation initiale fréquente : 9 kVA appartement, 12 kVA maison individuelle. Au-delà de 12 kVA et jusqu'à 36 kVA, triphasé fréquent ; triphasé aussi si distance compteur-tableau principal > 100 m. |
| Câbles électriques | Sections réseau citées : 50, 95, 150, 240 mm² ; branchements : 16, 25, 35 mm². Chute de tension branchement BT entre boîte de jonction et disjoncteur d'abonné via compteur <= 1,5 %. |
| Télécom | Transport en PVC 80 mm ; fourreaux 28/45/60 mm ; chambres de tirage espacées de 300 m maximum. |
| Fibre | Prévoir 1 à 2 fourreaux en attente. Rayon de courbure minimal environ 100 x rayon du fourreau ; pour diamètre 40 mm, rayon de courbure de l'ordre de 2 m. Ajouter une chambre si trop de changements de direction. |

Figures sources utiles pour contrôle visuel :

## Choix matériels, composants et critères fournisseurs

- Choisir tuyaux, fourreaux, regards, chambres, avaloirs, dispositifs d’infiltration, protections et repérage selon charges, profondeur et entretien.
- Vérifier disponibilité concessionnaire et prescriptions de raccordement.

## Estimation, métrés et postes de prix

- Métrer tranchées, blindages, remblais, évacuations, canalisations, regards, chambres, fourreaux, grillage avertisseur, essais, plans as-built et raccordements.
- Prévoir reprises d’enrobé, espaces verts, signalisation et maintien d’accès.

## Interfaces BTP et limites de prestations

- Clarifier qui réalise fouille, pose, lit de pose, raccordement, essais, remblai, compactage, traversées, chambres et récolement.
- Interfaces HVAC : arrivées gaz/eau, évacuation condensats, rejets, alimentation PAC extérieure, liaisons GTB et accès maintenance.

## Exigences contractuelles, réglementaires et normatives

Les références françaises de l’ouvrage sont informatives ; les raccordements belges se vérifient auprès du gestionnaire, du CSC et des textes régionaux applicables.

## Préparation d'exécution et coordination chantier

Produire synthèse réseaux, coupes de tranchées, planning de pose, demandes concessionnaires, plans de croisement et validation des niveaux avant terrassement.

La synthèse doit sortir des plans 2D : produire au minimum des coupes aux croisements critiques, les fils d'eau EU/EP, les profondeurs de fourreaux, les points hauts/bas eau, les chambres de tirage et les réserves de rayon pour fibre. Sans altimétrie, un plan de réseaux n'est pas coordonné.

## Mise en œuvre

- Poser selon pentes, profondeurs, supports et protections validés.
- Relever chaque réseau avant remblai avec photos, altimétrie, coordonnées et repérage.
- Préférer les tracés rectilignes pour limiter regards, pertes de charge et points de blocage.
- Poser les canalisations sur lit adapté, sans appui ponctuel dur sous les tuyaux.
- Ne remblayer qu'après contrôle de pente, alignement, accessoires, grillage avertisseur, repérage et photos.
- Préserver les rayons de courbure des câbles et fourreaux ; ne pas “forcer” une fibre dans un tracé trop sinueux.

## Contrôles, essais, réglages et mise en service

Contrôler pente, étanchéité, continuité, tirage, compactage, inspection caméra si demandée, raccordement et fonctionnement des ouvrages d’eaux pluviales.

Contrôles par famille :

- EU/EP : fil d'eau, pente, regards, cunettes, étanchéité, curabilité, ventilation, inspection caméra si prescrite.
- Eau/gaz : pression, vannes, purges, repérage, séparation et conformité concessionnaire.
- Électricité/télécom/fibre : continuité des fourreaux, tirage, rayons, chambres, repérage, essais de câble selon gestionnaire.
- Voirie : compactage, réfection, tampons à niveau fini et maintien des accès.

## Réception, dossier de clôture et as-built

Remettre plans de récolement, profils, fiches matériaux, résultats d’essais, photos avant remblai, coordonnées des regards et attestations concessionnaires.

## Exploitation, maintenance, garantie

Prévoir accès aux regards, chambres, avaloirs, filtres, ouvrages de rétention et points de curage.

## Risques, questions à poser et points de vigilance

- Réseaux trop hauts/bas, conflits sous dallage, pente impossible, raccordement concessionnaire tardif, fourreau oublié, plan as-built absent.
- Demander arbitrage écrit dès qu’un conflit de tracé touche structure, fondations, égouttage ou alimentation technique.

## Sources et sections liées

Sections sources utilisées pour extraire les valeurs, procédures et points de vigilance ci-dessus :

- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/26-4-1-implantation-et-execution-des-reseaux-enterres|La Technique du bâtiment – Tous corps d’état — 26 4.1 Implantation et exécution des réseaux enterrés]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/28-4-2-assainissement-et-epuration|La Technique du bâtiment – Tous corps d’état — 28 4.2 Assainissement et épuration]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/29-4-3-evacuation-des-eaux-pluviales|La Technique du bâtiment – Tous corps d’état — 29 4.3 Évacuation des eaux pluviales]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/30-4-4-mise-en-place-des-reseaux-eu-et-ep|La Technique du bâtiment – Tous corps d’état — 30 4.4 Mise en place des réseaux EU et EP]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/31-4-5-branchements|La Technique du bâtiment – Tous corps d’état — 31 4.5 Branchements]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/32-4-6-distribution-d-eau-de-gaz-d-electricite-de-courants-faibles-telephone-fibre|La Technique du bâtiment – Tous corps d’état — 32 4.6 Distribution d’eau, de gaz, d’électricité, de courants faibles (téléphone, fibre)]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/33-4-7-eclairage-public|La Technique du bâtiment – Tous corps d’état — 33 4.7 Éclairage public]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/23-3-3-voies-de-distribution|La Technique du bâtiment – Tous corps d’état — 23 3.3 Voies de distribution]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/24-3-4-voies-et-aires-pietonnes|La Technique du bâtiment – Tous corps d’état — 24 3.4 Voies et aires piétonnes]]
- [[documents/Livres/BTP/la-technique-du-batiment-tous-corps-detat/25-3-5-espaces-exterieurs-et-biodiversite-le-coefficient-de-biotope-par-surface-cbs|La Technique du bâtiment – Tous corps d’état — 25 3.5 Espaces extérieurs et biodiversité : le coefficient de biotope par surface ( CBS )]]

## Voir aussi

- [[concepts/assainissement-et-reseaux-enterres|Assainissement et Réseaux Enterrés]]
- [[concepts/interfaces-et-limites-de-prestations|Interfaces et Limites de Prestations]]
- [[concepts/certibeau|CertIBEau]]
- [[concepts/electricite-et-interfaces-hvac|Électricité et Interfaces HVAC]]
