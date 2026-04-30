---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:4.10"
ordre_document: 35
titre: "Application 4-6"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 35 Application 4-6
resume_section: |-
  **Résumé :**
  
  L'application 4-6 analyse le cycle de fabrication, pose et stockage de 150 acrotères.
  
  - **Fabrication :** Cadence de 2 unités/jour, début à J40, fin à J114, durée totale de 75 jours.
  - **Pose :** Prévue de J91 à J120, cadence de 5 unités/jour, durée de 30 jours.
  - **Stockage :**
    - Début du stock à J41.
    - Stock initial avant pose : 100 unités (S1).
    - Stock intermédiaire : 28 unités (S2).
    - Stock final : 25 unités (S3).
  
  Les courbes et calculs détaillés sont présentés dans le tableau 4.24 et la figure 4.62.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[34-planning-chemin-de-fer-genie-civil|Planning chemin de fer (génie civil)]]"
section_suivante: "[[36-application-4-7|Application 4-7]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["35_4.10_application_4-6.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 4.10 Application 4-6 

**Énoncé de l’application 4-6** 

On se propose d’étudier le cycle de pose, de préfabrication et de stockage de 150 acrotères préfabriqués pour un bâtiment. Les données techniques sont les suivantes : 

Cadence de fabrication des acrotères : 2 unités par jour. 

Délai de pose : J91 à J120. Durée de durcissement avant pose : 5 j. Duré de séchage : 1 j. Le début de pose est prévu pour J18.

On demande de calculer les dates et de tracer les courbes de pose, de fabrication et de stockage. 

**Corrigé de l’application 4-6** 

**Courbe de pose** 

Délai de pose : J91 à J120 → Durée de pose = 120 – 91 + 1 = 30 jours 

On ajoute (+ 1 j) pour tenir compte du décalage du soir et du matin 

Cadence de pose=Nombre d’élément à poser Nombre de jour=15030=5 u/ j 

**Courbe de fabrication** 

**Durée de fabrication :** 

On a une cadence de fabrication (2 u/j) inférieure à la cadence de pose (5 u/j). 

Fin de fabrication = fin de pose – durée de pose (1 j) – durée de séchage 

→ J + (120 – 1 – 5) = J + 114 

Début de fabrication = fin de fabrication + 1 – durée de fabrication 

→ J + (114 + 1 – 75) = J + 40 

**Courbe de stocks** 

**Stock S1** 

S1 = (début de pose – début de stock) × cadence de fabrication Cadence de fabrication 2 u/j 

→ [J + (91 – 40 + 1)] * 2 = 100 u

**Stock S2** 

→ 100 – [J + (114 + 1 – 91) * (5 – 2)] = 28u 

**Stock S3** 

S3 = S2 + (cadence de fabrication – cadence de pose) 

→ 28 + (2 – 5) = 25u 

Le **tableau 4.24** et la **fgure 4.62** présentent les calculs et les courbes étudiés. 

_**Tableau 4.24 Tableau des résultats de production de l’application 4-6**_ 

|**Courbes de production**|**Dates et cadences**|
|---|---|
|_Courbe de pose_<br>_Date de début de pose (au matin)_<br>_Date de fn de pose (au matin)_<br>_Nombre de regards (u)_<br>_Cadence de pose par jour (u/j)_|_J + 91_<br>_J + 120_<br>_150_<br>_5_|
|_Courbe de fabrication_<br>_Délai de durcissement avant la pose (j)_<br>_Cadence de fabrication (u/j)_<br>_Durée de fabrication (j)_<br>_Date de fn de fabrication (soir)_<br>_Date de début de fabrication (matin)_|_5_<br>_2_<br>_75_<br>_J + 114_<br>_J + 40_|
|_Courbe de stocks_<br>_Délai de durcissement (j)_<br>_Date de début de stock_<br>_Nombre d’éléments en stock en début de pose_<br>_S1 (u)_<br>_Nombre d’éléments en stock en début de pose_<br>_S2 (u)_<br>_Nombre d’éléments en stock en début de pose_<br>_S3 (u)_|_1_<br>_J + 41_<br>_100_<br>_28_<br>_25_|

![[documents/Livres/PM & Estimations/reussir-planification-chantier/images/Réussir_la_planification_d'un_chantier_--_2023_--_Le_Moniteur.epub-0191-00.png]]
