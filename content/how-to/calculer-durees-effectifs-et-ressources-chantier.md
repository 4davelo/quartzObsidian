---
type: how-to
aliases:
- Calculer une durée de tâche
- Calculer crédit d’heures chantier
- How-to ressources chantier
tags:
- how-to
- planning
- estimation
- ressources
sources:
- Réussir la planification d'un chantier -- 2023 -- Le Moniteur.epub
created: '2026-04-30'
updated: '2026-04-30'
contextes:
- execution-projet
- appel-doffres
autorite:
- pratique
- reference
juridictions:
- generique
- france
phases:
- offre
- mobilisation
- chantier
- mise-en-service
- reception
- exploitation
familles_sources:
- ouvrage
- gestion-projet
disciplines:
- gestion-projet
- achats
- cvc
types_projet:
- neuf
- renovation
- remplacement
- maintenance
revision_requise: false
---
# Calculer durées, effectifs et ressources de chantier

## Problème traité

Transformer des quantités et rendements en durées, effectifs, besoins matériaux, besoins matériels et enveloppe de trésorerie utilisables dans un planning.

## Dossier d'entrée et pièces à vérifier

- Quantités issues du métré, descriptifs, plans, contraintes de pose, horaires, productivité attendue, disponibilité des équipes et matériels.
- Retours d’expérience internes, temps unitaires, cadences fournisseurs, restrictions d’accès, coactivité et conditions de chantier.

## Quand utiliser / quand éviter

- Utiliser pour valider un délai, comparer une stratégie d’équipe, préparer une soumission ou recalculer un planning après aléa.
- Éviter si les quantités ou méthodes d’exécution sont encore trop incertaines ; poser alors des hypothèses explicites.

## Options de solution et variantes

- Calcul par temps unitaire, rendement, crédit d’heures, expérience chantier, ratios ou simulation par zones.
- Variantes : augmenter l’effectif, travailler en parallèle, modifier la séquence, changer un moyen matériel ou externaliser une tâche spécialisée.

## Fonctionnement technique

La durée dépend de la charge totale et de la capacité quotidienne. Augmenter l’effectif ne réduit pas toujours proportionnellement la durée si l’espace, la coactivité, l’approvisionnement ou le maillon cadenceur limitent la cadence.

## Données d'entrée à collecter

- Quantité `Q`, temps unitaire `TU`, nombre d’ouvriers `N`, temps journalier `t`, rendement, calendrier, jours non travaillés, matériel disponible et contraintes d’interface.
- Pour les ressources : effectifs par compétence, matériaux par période, engins par durée, dépenses par jalon.

## Dimensionnement et calculs

- `TU = N × t / Q`.
- `R = 1 / TU`.
- `CH tâche = Quantité × TU`.
- `CH ouvrage = somme des CH des tâches`.
- `Durée = CH / (Effectif × temps de travail par jour)`.
- Contrôler ensuite la faisabilité spatiale et les dépendances : le calcul de charge ne suffit pas à valider le planning.

## Choix matériels, composants et critères fournisseurs

- Choisir les moyens qui tiennent la cadence : engins, levage, outillage, préfabrication, stocks, livraisons fractionnées, instruments de mesure.
- Vérifier délais fournisseurs et capacité de livraison avant d’inscrire une cadence au planning.

## Estimation, métrés et postes de prix

- Relier chaque poste de prix à une charge : main-d’œuvre, matériel, matériaux, sous-traitance, essais, déplacements et encadrement.
- Calculer les pics de ressources pour identifier heures supplémentaires, équipes additionnelles ou risques de sous-charge.

## Interfaces BTP et limites de prestations

- Les durées dépendent des prérequis d’autres lots : supports, réservations, alimentation, accès, fermetures, échafaudages, zones libérées et nettoyées.
- Chaque prérequis doit avoir un responsable et une date dans le planning.

## Exigences contractuelles, réglementaires et normatives

- Ne pas confondre méthode de calcul française et exigence contractuelle belge. Le calcul est pratique ; le délai opposable vient du marché.
- Documenter les hypothèses de productivité lorsqu’elles conditionnent le prix.

## Préparation d'exécution et coordination chantier

- Valider les rendements avec conducteur, chef d’équipe et sous-traitants.
- Construire courbes effectif-temps, besoins matériaux, besoins engins et courbe financière.

## Mise en œuvre

- Mesurer l’écart réel entre cadence prévue et cadence produite ; recalculer le reste à faire.
- Ajuster effectifs, zones ou séquences si le maillon cadenceur bloque.

## Contrôles, essais, réglages et mise en service

- Chiffrer et planifier les heures d’essais, réglages, contrôles et reprises comme de vraies tâches.
- Prévoir la disponibilité des spécialistes et instruments.

## Réception, dossier de clôture et as-built

- Inclure les heures de plans as-built, DOE, rapports d’essais, levée de réserves et formation.
- Ne pas les absorber implicitement dans la pose.

## Exploitation, maintenance, garantie

- Ajouter les interventions d’entretien initial ou garantie si elles sont dans le périmètre.
- Garder les hypothèses de charge pour comparer l’exécution réelle et alimenter le retour d’expérience.

## Risques, questions à poser et points de vigilance

- Temps unitaires non adaptés au chantier, effectif théorique trop élevé pour la zone, approvisionnement oublié, jours non travaillés ignorés, coactivité sous-estimée, tâches de contrôle non chiffrées.
- Poser une question si une quantité ou une limite de prestation ne permet pas de calculer la charge.

## Sources et sections liées

- [[documents/Livres/PM & Estimations/reussir-planification-chantier/17-calcul-des-durees-d-execution-des-taches|Calcul des durées d’exécution des tâches]]
- [[documents/Livres/PM & Estimations/reussir-planification-chantier/38-planification-de-main-d-oeuvre|Planification de main-d’œuvre]]
- [[documents/Livres/PM & Estimations/reussir-planification-chantier/39-planification-des-materiaux|Planification des matériaux]]
- [[documents/Livres/PM & Estimations/reussir-planification-chantier/40-planification-d-utilisation-du-materiel-et-des-engins|Planification d’utilisation du matériel et des engins]]
- [[documents/Livres/PM & Estimations/reussir-planification-chantier/41-planification-financiere|Planification financière]]
- [[documents/Livres/PM & Estimations/reussir-planification-chantier/52-le-calcul-des-effectifs-etp|Le calcul des effectifs ETP]]

## Voir aussi

- [[concepts/calcul-durees-credit-heures-rendement|Calcul des Durées, Crédit d’Heures et Rendement]]
- [[concepts/planification-des-ressources|Planification des Ressources]]
- [[concepts/metre-recapitulatif-et-inventaire|Métré Récapitulatif et Inventaire]]
- [[concepts/planification-de-chantier|Planification de Chantier]]
