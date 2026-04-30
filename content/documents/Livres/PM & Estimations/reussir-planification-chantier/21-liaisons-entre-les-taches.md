---
type: document-section
document_id: reussir-planification-chantier
section_id: "section:3.9"
ordre_document: 21
titre: "Liaisons entre les tâches"
aliases:
  - Réussir la planification d'un chantier — Le Moniteur 2023 — 21 Liaisons entre les tâches
resume_section: |-
  Les tâches sont liées selon un ordre logique, principalement par des liaisons Fin-Début (FD). D'autres types de liaisons (Début-Début, Début-Fin, Fin-Fin) permettent des chevauchements pour optimiser le temps. Ces liaisons n'affectent pas la structure du réseau, mais influencent les calculs de durées, marges et chemins critiques.
document_parent: "[[documents/Livres/PM & Estimations/reussir-planification-chantier/index|Réussir la planification d'un chantier — Le Moniteur 2023 — Index]]"
section_precedente: "[[20-representation-matricielle|Représentation matricielle]]"
section_suivante: "[[22-construction-des-graphes|Construction des graphes]]"
tags: [document-section, ouvrage, gestion-projet, planification, estimation]
sources: ["21_3.9_liaisons_entre_les_tâches.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [execution-projet, appel-doffres]
autorite: [pratique, reference]
juridictions: [generique, france]
familles_sources: [ouvrage, gestion-projet]
---
## 3.9 Liaisons entre les tâches 

L’exécution des travaux se fait selon un enchaînement logique des tâches. Les différentes liaisons sont donc déterminées en suivant l’ordre séquentiel d’exécution des travaux. La liaison la plus courante est du type Fin-Début (FD), c’est-à-dire qu’elle dépend de la fin du prédécesseur et du début du successeur. Afin de gagner du temps et d’éviter d’attendre la fin d’une tâche pour en commencer une nouvelle, on peut prévoir des chevauchements logiques dans les liaisons. Ces chevauchements peuvent être représentés par trois autres types de liaison, avec ou sans décalage dans l’exécution : liaison Début-Début (DD), liaison Début-Fin (DF) et liaison Fin-Fin (FF). 

Le type de liaison entre les tâches n’entre pas dans la construction de la matrice, la détermination des rangs des tâches et la construction du réseau. Il influe seulement sur les calculs des durées, des marges et la détermination des chemins critiques.
