---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:2.4"
ordre_document: 11
titre: "Différentes techniques de planification"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 11 Différentes techniques de planification
resume_section: |-
  Les techniques de planification se divisent en deux catégories principales : les méthodes linéaires et les méthodes par réseau.
  
  **Méthodes linéaires :**
  - **Diagramme de GANTT :** Représentation graphique des tâches et ressources sur une échelle temporelle. Simple et largement utilisée.
  - **Planning chemin de fer :** Adapté aux travaux linéaires ou répétitifs, avec un axe pour le temps et un autre pour les zones ou quantités.
  
  **Méthodes par réseau :**
  - **Méthode potentiel-étape :** Inclut PERT (chemin critique, tâches représentées par des flèches) et PERL (inspiré de GANTT et PERT).
  - **Méthode potentiel-tâche :** Inclut MPM et PDM, basées sur les relations entre tâches, avec des boîtes pour les activités et des flèches pour les dépendances. PDM est la plus utilisée.
  
  **Logiciels de planification :**
  Exemples : MS-Project, Primavera P6, GANTT Project, Teamoty, Leanco, etc. Ces outils facilitent la gestion des tâches et ressources.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[10-planification|Planification]]"
section_suivante: "[[12-methodes-de-construction-des-plannings|Méthodes de construction des plannings]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["11_2.4_différentes_techniques_de_planification.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 2.4 Différentes techniques de planification 

L’élaboration d’un planning repose sur une décomposition chronologique et structurée du projet. On passe d’une division sommaire (phase, lot ou corps d’état) à un niveau de division plus détaillé (tâche ou activité) et on affecte ainsi les différentes ressources utilisées pour sa réalisation. Il existe plusieurs techniques de planification des projets, qui sont rassemblées en deux grandes catégories (voir **fg. 2.11** ) : les méthodes linéaires et les méthodes par réseau.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0038-00.png]]

_**Figure 2.11 Techniques de planification[(][2][)]**_ 

**Méthodes linéaires**

**Diagramme de GANTT** 

Le diagramme de GANTT, conçu en 1917 par Henry Laurence Gantt, est une représentation graphique du déroulement chronologique d’un projet. Ce tableau permet de situer dans le temps les activités et les ressources d’un projet. 

On liste les tâches et les ressources en lignes et le temps (mois, semaines ou jours) en colonnes. Les tâches sont représentées par des barres dont la longueur est proportionnelle à la durée. Elles peuvent se succéder ou se réaliser entièrement ou partiellement en parallèle (voir **fg. 2.12** ). Le planning GANNT est une représentation pratique, et bien qu’elle soit la plus ancienne, elle est encore la technique la plus utilisée aujourd’hui.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0040-00.png]]

_**Figure 2.12 Méthode linéaire : diagramme de GANTT**_ 

**Planning chemin de fer** 

Le planning d’exécution des travaux peut être tracé sous la forme dite du « chemin de fer ». On l’utilise pour planifier des travaux à caractère linéaire, séquentiel ou répétitif, par étages ou zones, comme pour des routes, tunnels, bâtiments élevés, de terrassement, travaux intérieurs répétitifs, etc. L’évolution des tâches est rapportée sur deux axes : l’axe des abscisses représente l’axe du temps, l’axe des ordonnées représente généralement les zones de travail et les quantités réalisées (voir **fg. 2.13** ).

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0041-00.png]]

_**Figure 2.13 Méthode linéaire : planning chemin de fer**_ 

**Méthodes des réseaux** 

Elles mettent en évidence les relations de dépendance entre tâches, appelées aussi méthodes à chemin critique. La méthode de potentieltâche met l’accent sur l’activité, la méthode de potentiel-étape est basée sur les événements. Les sommets des réseaux représentent soit les tâches (voir **fg. 2.12a** ) soit les événements (voir **fg. 2.12b** ).

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0042-00.png]]

_**Figure 2.14 Méthodes des réseaux : graphe des tâches et graphe des événements**_ 

**Méthode potentiel-étape**

le PERT, le PERL et le CPM. La méthode PERT ( _Program Evaluation and Review Technique_ ) est une technique de modélisation de projet développée par la marine américaine en 1958. Elle s’appuie sur la méthode du chemin critique CPM ( _Critical Path Method_ ). Cette technique représente les activités sous forme d’un réseau de dépendances. Dans le réseau PERT, les tâches sont représentées par des flèches orientées et des étapes qui marquent le début et la fin de chaque tâche. Le diagramme de PERL (planning d’ensemble par réseaux linéaires) est une représentation proche du diagramme GANTT et du réseau PERT, d’où son nom GANTT fléché. Dans cette représentation, plusieurs tâches sont affichées sur une même ligne. La méthode PERL a été développée en 1957 par Charles Auguste Villemain pour EDF. 

**Méthode potentiel-tâche** 

La méthode de potentiel-tâche est une technique d’ordonnancement basée sur la théorie des réseaux. Elle est déclinée en deux modèles, le MPM et le PDM. Cette méthode, appelée méthode des potentiels métra (MPM), utilise les relations entre les tâches du type (Début– Début). Par la suite, elle a été améliorée pour tenir compte des différentes liaisons possibles entre les tâches. Cette méthode du réseau des antécédents PDM ( _Precedence Diagram Method_ ) est la plus utilisée aujourd’hui. Les méthodes MPM et PDM sont relativement similaires. Elles se présentent sous la forme d’un réseau dans lequel chaque activité est représentée par une boîte rectangulaire. Des flèches représentent les liaisons de dépendances entre les tâches. 

**Logiciels de planification** 

À la suite du développement des outils informatiques, de nombreux programmes et logiciels ont été développés. Ils offrent des outils permettant aux concepteurs du domaine de la construction de planifier et gérer les tâches et les ressources au sein du projet. 

Parmi ces logiciels, on peut citer : 

- MS-Project (Microsoft Project), 

- PSN « _Project Scheduler Network_ » 

- Turbo Project 

- Primavera P6

- GANTT PROJECT **[(3)]** 

- MindView 7 **[(4)]** 

- Project Planner 

- MR Project Management 

- X Project 

- Teamoty 

- Leanco 

- Addlean 

**(2)** _Le grand livre de la gestion de projet._ 

**(3) [https://www.ganttproject.biz/](https://www.ganttproject.biz/)** 

**(4) [https://www.matchware.com/fr/logiciel-de-mind-mapping](https://www.matchware.com/fr/logiciel-de-mind-mapping)**
