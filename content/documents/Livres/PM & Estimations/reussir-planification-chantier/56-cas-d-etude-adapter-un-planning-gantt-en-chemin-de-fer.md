---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:6.13"
ordre_document: 56
titre: "Cas d’étude : adapter un planning GANTT en chemin de fer"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 56 Cas d’étude : adapter un planning GANTT en chemin de fer
resume_section: |-
  ### 6.13 Cas d’étude : adapter un planning GANTT en chemin de fer
  
  #### Application 6-5
  1. Convertir un planning GANTT en planning chemin de fer en prenant un niveau (10 logements) comme unité de zone.
  2. Les travaux d’un étage (10 logements) seront terminés à la fin de la semaine 17 (S17).
  
  #### Application 6-6
  1. Créer un planning chemin de fer avec une échelle temporelle en semaines (abscisses) et des niveaux respectant la physique du bâtiment (ordonnées).
  2. Remplir le planning avec les séquences du tableau récapitulatif, en respectant l’ordre d’exécution et les dépendances entre tâches.
  3. Indiquer les jalons de fin de travaux pour chaque niveau.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[55-les-optimisations|Les optimisations]]"
section_suivante: "[[57-bibliographie|Bibliographie]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["56_6.13_cas_détude_adapter_un_planning_gantt_en_chemin_de_fer.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 6.13 Cas d’étude : adapter un planning GANTT en chemin de fer 

**Application 6-5** 

**Énoncé de l’application 6-5** 

Vous venez d’intégrer, en tant que pilote, un projet de construction de 30 logements. Lors de votre premier entretien, la maîtrise d’ouvrage vous donne le planning GANTT de l’opération conçu pendant la conception du projet. L’opération comprend trois niveaux et chaque niveau possède 10 logements. 

On demande de : 

1. Tracer le planning chemin de fer à partir du planning GANTT cidessous ( **fg. 6.38** ) en prenant comme unité de zone un niveau (10 logements). 

2. Indiquer à la fin de quelle semaine (en numéro de semaine) les travaux d’un étage de 10 logements seront entièrement terminés.

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0262-00.png]]

_**Figure 6.38 Données d’entrée de l’application 6-5**_ 

**Corrigé de l’application 6-5** 

**1.** 

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0262-04.png]]

_**Figure 6.39 Correction du planning chemin de fer de l’application 6-5**_ 

2. À la fin de la semaine 17 (S17) les travaux d’un étage seront entièrement terminés.

**Énoncé de l’application 6-6** 

Un directeur de travaux d’une entreprise de CVC (chauffage, ventilation, climatisation) vous contacte car son projet de construction s’écarte de plus en plus de sa planification GANTT initiale. Il cherche à obtenir un nouveau point de vue sur les travaux à réaliser par ses équipes et l’enchaînement des grandes séquences de son projet. Pour cela, il vous transfère un tableau récapitulatif comprenant les principales séquences du projet ( **tab. [6.1](44_6.1_la_planification_globale_en_chemin_de_fer.md)** ). 

On demande de : 

1. Créer la trame du planning chemin de fer en indiquant des semaines comme échelle temporelle (abscisses). Concernant les zones (en ordonnées), elles devront respecter la physique du bâtiment (niveaux les plus élevés en haut du planning). 

2. Remplir la trame du planning chemin de fer créé avec les séquences indiquées dans le tableau récapitulatif (les niveaux s’enchaînent en début/fin entre les différents niveaux concernés). 

3. Indiquer les jalons de fin de travaux des niveaux dans la zone dédiée aux jalons. 

_**Tableau [6.1](44_6.1_la_planification_globale_en_chemin_de_fer.md) Données d’entrée de l’application 6-6**_ 

|**Séquence par**<br>**équipe**|**Niveaux concernés**<br>**dans l’ordre**<br>**d’exécution**|**Durée de la**<br>**séquence par**<br>**niveau**|**Tâche précédente**|
|---|---|---|---|
|Bureaux équipe 1|R+5, R+4, R+3|8 semaines|Aucune|
|Bureaux équipe 2|R+2, R+1|8 semaines|Aucune|
|Locaux technique|SS1, SS2, R+6, R+6|6 semaines|Aucune|
|Restaurant|R+5, R+3, R+1|5 semaines|Fin Séquence<br>Bureaux R+5|
|Cuisine|R+5, R+3, R+1|6 semaines|La séquence du<br>dernier niveau (R+1)<br>devra se terminer<br>avant le début de la<br>séquence restaurant<br>de la zone concernée.<br>Les séquences<br>précédentes de<br>cuisine seront<br>planifées en<br>rétroactif|

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0264-01.png]]
