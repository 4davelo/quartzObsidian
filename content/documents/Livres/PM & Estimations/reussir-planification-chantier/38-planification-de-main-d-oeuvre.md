---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:5.1"
ordre_document: 38
titre: "Planification de main-d’œuvre"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 38 Planification de main-d’œuvre
resume_section: |-
  La planification de la main-d’œuvre implique le calcul des besoins en personnel pour réaliser les ouvrages. Cela inclut :
  
  1. **Quantité d’ouvrage** : calculée via l’avant-métré et le devis quantitatif.
  2. **Crédit d’heures (CH)** : obtenu en multipliant la quantité d’ouvrage par le temps unitaire d’exécution.
  3. **Durée d’exécution** : estimée à partir du planning général.
  4. **Effectif nécessaire** : calculé avec la formule CH / (horaire journalier × durée d’exécution).
  5. **Composition des équipes** : basée sur le nombre et la qualification nécessaires.
  
  Une courbe d’effectif-temps, tracée à partir du diagramme GANTT, permet de visualiser l’effectif global et de pointe sur le chantier. L’exemple donné montre un effectif de pointe de 12 ouvriers entre le 9ᵉ et le 23ᵉ jour.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[37-planification-des-ressources|Planification des ressources]]"
section_suivante: "[[39-planification-des-materiaux|Planification des matériaux]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["38_5.1_planification_de_main-dœuvre.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 5.1 Planification de main-d’œuvre

La main-d’œuvre productive désigne le personnel du chantier directement affecté à la réalisation des ouvrages. La détermination des besoins totaux en main-d’œuvre nécessite de calculer des quantités d’ouvrage, et de déterminer le crédit d’heure, la durée d’exécution des tâches et l’effectif nécessaire pour effectuer ce travail. 

**Quantité d’ouvrage à réaliser** 

Pour estimer la quantité d’ouvrage à réaliser, on calcule l’avantmétré de chaque ouvrage élémentaire à partir des plans d’exécution et des détails, puis on établit le devis quantitatif de l’ouvrage à réaliser. 

**Crédit d’heures « CH » ou budget d’heures** 

Pour chaque tâche élémentaire, on détermine le budget d’heures par le produit de la quantité à réaliser et le temps unitaire d’exécution : Crédits d’heures=Quantité×TU 

**Durée d’exécution des tâches** 

La durée de réalisation des différents éléments d’ouvrage est estimée à partir du planning général fourni par le maître d’œuvre. 

**Effectif nécessaire** 

L’effectif représente le nombre d’ouvriers nécessaire à l’exécution d’une tâche. Il est calculé à partir du crédit d’heures, de l’horaire journalier et de la durée d’exécution : 

Effectif=Crédits d’heures Horaire journalier×Durée d’éxecution 

**Composition de chaque équipe** 

La composition d’une équipe est déterminée en fonction du nombre et de la qualification de la main-d’œuvre nécessaire pour réaliser la

**quantité d’ouvrage élémentaire.** 

Les calculs des durées et des temps unitaires ont été présentés dans le chapitre 2. 

**Courbes d’effectif-temps** 

Une fois que l’on connaît l’effectif général attribué à chaque tâche, on peut tracer la courbe d’effectif-temps en s’appuyant sur le diagramme GANTT. On reporte, pour chaque jour du planning GANTT réalisé, le nombre d’ouvriers nécessaire à la réalisation de chaque tâche. On cumule par la suite les effectifs de toutes les tâches en cours à une date donnée, sous la forme d’un histogramme. 

La courbe d’effectif-temps permet de connaître l’effectif global présent sur le chantier suivant l’avancement des travaux, ainsi que l’effectif de pointe pour dimensionner les cantonnements nécessaires dans l’étude du plan d’installation de chantier. 

Pour expliquer le traçage de cette courbe, on reprend l’exemple n° 1 du chapitre 3, dans lequel on ajoute l’effectif nécessaire pour la réalisation de chaque tâche (voir **tab. 5.1** ). En suivant le diagramme GANTT de la **fgure 4.42** , on trace l’histogramme de main-d’œuvre en cumulant jour par jour la main-d’œuvre nécessaire. 

Cet histogramme est présenté dans la **fgure 5.1** . On en déduit que l’effectif de pointe est de 12 ouvriers et se trouve du 9[e] au 23[e] jour. 

_**Tableau 5.1 Données d’effectif de l’exemple N° 1**_ 

|**Activité**|**Prédécesseur**|**Rang**|**Durée (j)**|**Efectifs**|
|---|---|---|---|---|
|_A_<br>_B_<br>_C_<br>_D_<br>_E_<br>_F_<br>_G_<br>_H_<br>_I_|_Néant_<br>_A_<br>_B_<br>_C ; F_<br>_A_<br>_E_<br>_E_<br>_G_<br>_D ; H_|_1_<br>_2_<br>_3_<br>_4_<br>_2_<br>_3_<br>_3_<br>_4_<br>_5_|_5_<br>_3_<br>_15_<br>_6_<br>_4_<br>_18_<br>_14_<br>_14_<br>_5_|_4_<br>_6_<br>_3_<br>_8_<br>_5_<br>_4_<br>_5_<br>_2_<br>_7_|

![](images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0202-00.png)

_**Figure 5.1 Histogramme d’utilisation de la main-d’œuvre**_
