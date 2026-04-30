---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:3.12"
ordre_document: 24
titre: "Application 3-3"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 24 Application 3-3
resume_section: |-
  L'application 3-3 analyse la planification de 11 tâches d'un corps d'état, avec leurs durées et dépendances listées dans le tableau 3.15. Les objectifs incluent la détermination des rangs des tâches, l'élaboration de la matrice d'antériorité (figure 3.19) et le tracé du réseau des antécédents (figure 3.20). Le tableau 3.16 présente les rangs des tâches, allant de 1 (_A_) à 7 (_K_), en fonction des dépendances.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[23-application-3-2|Application 3-2]]"
section_suivante: "[[25-techniques-de-planification|Techniques de planification]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["24_3.12_application_3-3.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 3.12 Application 3-3 

**Énoncé de l’application 3-3** 

On se propose d’étudier la planification d’exécution des travaux d’un corps d’état formés de 11 tâches dont les caractéristiques sont présentées dans le **tableau 3.15** . 

_**Tableau 3.15 Données des tâches de l’application 3-3**_ 

|**Désignation des tâches**|**Durée en jours**|**Tâche antérieure**|
|---|---|---|
|_A_|_4_|_Néant_|

|_B_|_6_|_A_|
|---|---|---|
|_C_|_10_|_A_|
|_D_|_6_|_B_|
|_E_|_3_|_C_|
|_F_|_7_|_E_|
|_G_|_5_|_B_|
|_H_|_9_|_D_|
|_I_|_5_|_F-G_|
|_J_|_7_|_H-I_|
|_K_|_7_|_J_|

On demande de déterminer le rang des différentes tâches, d’élaborer la matrice d’antériorité et de tracer le réseau des antécédents. 

**Corrigé de l’application 3-3** 

Les rangs des différentes tâches sont présentés dans le **tableau 3.16** . Les **fgures 3.19** et **3.20** représentent respectivement la matrice d’antériorité et le réseau des antécédents. 

_**Tableau 3.16 Détermination des rangs des tâches de l’application 3-3**_ 

|**Désignation des**<br>**tâches**|**Désignation des**<br>**tâches**||**Durée en jours**|**Durée en jours**|**Tâche antérieure**|**Tâche antérieure**|**Tâche antérieure**|**Rang**|**Rang**|
|---|---|---|---|---|---|---|---|---|---|
|_A_|||_3_|||_Néant_|||_1_|
|_B_|||_6_|||_A_|||_2_|
|_C_|||_10_|||_A_|||_2_|
|_D_|||_6_|||_B_|||_3_|
|_E_|||_3_|||_C_|||_3_|
|_F_|||_7_|||_E_|||_4_|
|_G_|||_5_|||_B_|||_3_|
|_H_|||_9_|||_D_|||_4_|
|_I_|||_15_|||_F-G_|||_5_|
|_J_|||_7_|||_H – I_|||_6_|
|_K_|||_7_|||_J_|||_7_|
|||||||||||
|**Rang 1**|**Rang 2**||**Rang 3**|**Rang 4**||**Rang 5**||**Rang 6**|**Rang 7**|
|_A_|_B – C_||_D – E – G_|_F – H_||_I_||_J_|_K_|

![](images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0088-00.png)

_**Figure 3.19 Matrice d’antériorité de l’application 3-3**_

![](images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0089-00.png)

_**Figure 3.20 Réseau des antécédents de l’application 3-3**_
