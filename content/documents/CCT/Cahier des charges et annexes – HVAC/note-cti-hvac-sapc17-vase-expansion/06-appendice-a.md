---
type: document-section
document_id: note-cti-hvac-sapc17-vase-expansion
section_id: section:appendice-a
ordre_document: 6
titre: APPENDICE A
aliases:
  - Note CTI HVAC SAPC17 — Vases d'expansion — 06 APPENDICE A
resume_section: |-
  ## Résumé APPENDICE A:

  Les lois de Gay-Lussac et Boyle-Mariotte sont utilisées pour analyser les variations de pression et de volume dans un vase d'expansion. Une augmentation de température du gaz de pression entraîne une hausse de pression d'environ 10%, souvent négligée. Pour compenser cet effet, le calcul du volume d'expansion utilise un coefficient d'expansion basé sur la température de départ (3,55% à 90°C) plutôt que sur la température moyenne maximale (2,9% à 80°C). Cela conduit à un vase d'expansion environ 20% plus grand, intégrant un volume supplémentaire pour éviter une pression excessive due au réchauffement du gaz.
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/index|Note CTI HVAC SAPC17 — Vases d'expansion — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/05-autres-elements-et-conditions|Autres éléments et conditions]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/07-appendice-b|APPENDICE B]]"
tags:
  - document-section
  - cti
  - hvac
sources:
  - 06_appendice-a_appendice_a.md
created: 2026-04-28
updated: 2026-04-28
contextes:
  - technique
  - execution-projet
autorite:
  - reference
juridictions:
  - belgique
familles_sources:
  - guide
---

## APPENDICE A:

Pour un gaz bien déterminé:

$$\frac{p \cdot V}{T} = \text{constant (Gay-Lussac)}$$

Si l'on suppose que la température de l'air dans le vase est constante, on obtient:

$$p \cdot V = \text{constant (Boyle-Mariotte)}$$

Toutefois, étant donné que l'eau dans la vessie est soumise à des variations de température, la température du gaz de pression dans le vase ne restera pas constante:

$$\text{Expansion} \Leftrightarrow T \uparrow$$

Examinons l'effet de ce phénomène à l'aide d'un exemple simple:

Supposons que la température du gaz de pression augmente jusqu'à 50 °C.

Ce changement de situation est exprimé par la formule suivante:

$$\frac{p_1 \cdot V_1}{(20 + 273)K} = \frac{p_2 \cdot V_2}{(50 + 273)K}$$

Les deux dénominateurs présentent une différence d'environ 10%. Etant donné que  $V_2$  reste constant, la pression  $p_2$  a augmenté d'environ 10%. Cette augmentation de pression, qui est uniquement due à la hausse de température du gaz de pression dans le vase d'expansion, est négligée à tort.

Pour déterminer le volume d'expansion dans un régime normal de 90°/70°C, on prendrait, normalement, le coefficient de la température moyenne maximale, soit 2,9% à 80°C.

Pour tenir compte du phénomène susmentionné, on prend toutefois le coefficient d'expansion de la température de départ, à savoir 3,55% à 90°C. Ainsi, on tient compte dans le calcul d'un volume d'expansion physique  $V_{ep}$  qui est supérieur d'environ 20% au volume réel.

Le vase d'expansion calculé de cette façon sera donc environ 20% plus grand que celui que l'on aurait calculé en tenant compte du coefficient d'expansion de la température moyenne maximale.

On tient donc implicitement compte, et de façon très simple, du volume supplémentaire dont on a besoin pour compenser une augmentation de pression indésirée suite au réchauffement du gaz de pression.
