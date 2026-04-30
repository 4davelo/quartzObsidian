---
type: document-section
document_id: note-cti-hvac-sapc17-vase-expansion
section_id: section:3
ordre_document: 4
titre: Détermination des vases d'expansion à pression constante (quantité d'air variable)
aliases:
  - Note CTI HVAC SAPC17 — Vases d'expansion — 04 Détermination des vases d'expansion à pression constante (quantité d'air variable)
resume_section: |-
  ### Résumé : Détermination des vases d'expansion à pression constante (quantité d'air variable)

  #### 3.1. Notions de base
  - **Pression réglée ($p_r$)** : Pression à laquelle le système est réglé, influencée par le chauffage/refroidissement. Calcul : $p_r = p_h + p_v + 0,5$ bar.
  - **Capacité du compresseur ($q_c$)** : Dépend de la variation de charge maximale ($Q$), de la température moyenne ($t$), et de la pression réglée ($p_r$). Calcul détaillé en 3.2.5.
  - **Capacité de décharge** : Raisonnement similaire au compresseur, mais en sens inverse.

  #### 3.2. Dimensionnement
  - **Volume total théorique ($V_{tt}$)** : $V_{tt} = V_n$, avec $V_{tr} \geq V_{tt}$ (choix selon le marché).
  - **Volume utile ($V_u$)** : $V_u = V_{tr}$.
  - **Réserve d'eau réelle ($R_r$)** : $R_r = V_{tr} - V_{op}$.

  #### Calculs
  - Exemple de calcul pour un système de 5000 L : $V_n = 227,5$ L, $V_{tr} = 300$ L, $R_r = 122,5$ L.
  - **Capacité du compresseur ($q_c$)** : $q_c = q \cdot Q$, où $q$ est déterminé par un graphique reliant température et débit de contraction par kW.

  #### Exemple
  - Puissance installée : 1500 kW, variation de charge maximale : 750 kW.
  - Débit de contraction à 80 °C : 0,56 L/h par kW.
  - Débit d'air comprimé requis : 420 L/h.

  #### Choix du matériel
  - Vase d'expansion type 300 pour $V_{tr}$.
  - Compresseur adapté selon les besoins, intégré ou monté séparément.
  - **3.1 notions de base** — `section:3.1`, heading, profondeur 2, pages 15-16
  - **3.1.1 pression réglée: p_r [bar]** — `section:3.1.1`, heading, profondeur 3, pages 15-15
  - **3.1.2 capacité du compresseur: q_c [ \ell/h ]** — `section:3.1.2`, heading, profondeur 3, pages 15-15
  - **3.1.3 capacité de décharge** — `section:3.1.3`, heading, profondeur 3, pages 16-16
  - **3.2 dimensionnement: équations** — `section:3.2`, heading, profondeur 2, pages 17-20
  - **3.2.1 volume total théorique et réel du système dexpansion: v_{tt} et v_{tr} [ \ell ]** — `section:3.2.1`, heading, profondeur 3, pages 17-17
  - **3.2.2 volume utile: v_u [ \ell ]** — `section:3.2.2`, heading, profondeur 3, pages 17-17
  - **3.2.3 réserve deau réelle: r_r [ \ell ]** — `section:3.2.3`, heading, profondeur 3, pages 17-17
  - **3.2.4 exemple** — `section:3.2.4`, heading, profondeur 3, pages 18-18
  - **3.2.5 détermination de la capacité du compresseur: q_c [l/h]** — `section:3.2.5`, heading, profondeur 3, pages 19-19
  - **3.2.6 exemple** — `section:3.2.6`, heading, profondeur 3, pages 20-20
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/index|Note CTI HVAC SAPC17 — Vases d'expansion — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/03-determination-des-vases-d-expansion-a-pression-variable-quantite-d-air-fixe|Détermination des vases d'expansion à pression variable (quantité d'air fixe)]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/05-autres-elements-et-conditions|Autres éléments et conditions]]"
tags:
  - document-section
  - cti
  - hvac
sources:
  - 04_3_détermination_des_vases_dexpansion_à_pression_constante_quantité_dair_variable.md
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

### 3. Détermination des vases d'expansion à pression constante (quantité d'air variable)

#### 3.1. Notions de base

Les termes mentionnés sous 2.1.4. ( $p_g$ ), 2.1.5. ( $p_i$ ) et 2.1.6 ( $p_f$ ) ne sont pas d'application et sont remplacés par une seule notion:  $p_r$

##### 3.1.1. Pression réglée : $p_r$ [bar]

La pression à laquelle le système d'expansion est réglé. En cas de chute de la pression régnant dans l'installation, p.ex. à cause d'un refroidissement, le compresseur se met en marche. Si la pression monte, p.ex. en cas de réchauffement, la soupape d'évacuation s'ouvrira.

$$p_r = p_h + p_v + 0,5 \text{ bar}$$

Remarque: les remarques faites sous 2.1.4. et 2.1.8. sont également d'application ici. (voir aussi appendice B)

##### 3.1.2. Capacité du compresseur : $q_c$ [ $\ell/h$ ]

Il est nécessaire de calculer la production d'air du compresseur en fonction des critères suivants:

Variation de charge maximale : Q [kW]

Par ce terme on entend la variation maximale des charges à laquelle on doit s'attendre pendant l'exploitation normale du chauffage. Cette variation peut résulter de l'enclenchement d'un ou plusieurs groupes consommateurs de grande puissance, ou du déclenchement d'un ou plusieurs groupes générateurs de chaleur. Dans le cas extrême, cette variation de charge correspond à la puissance calorifique totale de l'installation.

Exemple

- - Brûleurs à commande "marche-arrêt" au lieu de réglage modulant
- - Enclenchement à pleine puissance d'un aérotherme ou plusieurs unités simultanément
- - Enclenchement à pleine puissance de machines frigorifiques à absorption etc.

Le résultat est le même, qu'il s'agisse de l'arrêt d'une chaudière ou d'un brûleur, ou de l'enclenchement d'un groupe consommateur: la

température moyenne s'abaisse temporairement. Autrement dit, du fait du refroidissement le volume d'eau diminue immédiatement, le vase d'expansion doit restituer de l'eau à l'installation. Le débit d'air comprimé pour compenser le volume pendant cette phase détermine la puissance du compresseur. Celle-ci dépend du déficit momentanément dans le bilan thermique de l'installation. C'est pourquoi la variation maximale de charge attendue est une grandeur de référence à prendre en compte.

Température moyenne de l'installation : t [°C]

Alors que pour calculer la grandeur correcte du vase d'expansion on tiendra compte de la température maximum de l'installation, on peut se servir de la température moyenne pour calculer la puissance du compresseur. Cela est possible, puisque la puissance du compresseur n'est jamais nécessaire quand l'installation calorifique est en équilibre, mais toujours pendant la phase de refroidissement. Comme température moyenne on peut utiliser la moyenne des températures théoriques de retour et de départ, à pleine charge de l'installation.

Pression réglée au groupe de commande : p, [bar]

Le débit d'air comprimé diminue au fur et à mesure qu'augmente le niveau de compression demandée. D'une part le rendement du compresseur diminue, de l'autre le volume utile diminue en raison de la compression plus élevée. Pour cette raison il faut tenir compte de la pression de service à laquelle le groupe automatique doit être réglée.

Pour une détermination exacte de la capacité du compresseur voir 3.2.5.

### 3.1.3. Capacité de décharge

En principe le raisonnement est le même que pour le compresseur, mais dans le sens inverse.

### 3.2. Dimensionnement: équations

La capacité d'accueil d'eau du vase ne dépend pas de la pression réglée ( $p_r$ ). A cause du type de fonctionnement de ce système d'expansion (la pression ne peut jamais monter ou descendre), le calcul de la compression du gaz de pression n'est pas d'application.

#### 3.2.1. Volume total théorique et réel du système d'expansion : $V_{tt}$ et $V_{tr}$ [ $\ell$ ]

$$V_{tt} = V_n$$

Ensuite, on choisit  $V_{tr}$  selon l'offre du marché

$$V_{tr} \geq V_{tt}$$

#### 3.2.2. Volume utile : $V_u$ [ $\ell$ ]

$$V_u = V_{tr}$$

(Voir aussi appendice F)

#### 3.2.3. Réserve d'eau réelle : $R_r$ [ $\ell$ ]

$$R_r = V_{tr} - V_{op}$$

(Voir aussi appendice F)

3.2.4. Exemple

---

**CALCUL VOLUME D'EXPANSION:**

<table border="0">
<tr>
<td>Contenu du système <small>(calculé)</small></td>
<td>:</td>
<td>5000</td>
<td>[ℓ]</td>
<td><math>C_i</math></td>
</tr>
<tr>
<td><small>(estimé : kW x ℓ/kW)</small></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Coefficient d'expansion à 90 °C</td>
<td>:</td>
<td>x 3,55</td>
<td>[%]</td>
<td><math>x C_e</math></td>
</tr>
<tr>
<td></td>
<td></td>
<td>-----</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Volume d'expansion physique</td>
<td>:</td>
<td>177,5</td>
<td>[ℓ]</td>
<td><math>= V_{ep}</math></td>
</tr>
<tr>
<td></td>
<td></td>
<td>-----</td>
<td></td>
<td></td>
</tr>
<tr>
<td>1% réserve (<math>C_i \times 0,01</math>)</td>
<td>:</td>
<td>+ 50</td>
<td>[ℓ]</td>
<td><math>+ R_i</math></td>
</tr>
<tr>
<td></td>
<td></td>
<td>-----</td>
<td></td>
<td></td>
</tr>
<tr>
<td>VOLUME NET</td>
<td>:</td>
<td>227,5</td>
<td>[ℓ]</td>
<td><math>= V_n</math></td>
</tr>
</table>

---

**CALCUL VASE D'EXPANSION:**

VOLUME TOTAL THEORIQUE = VOLUME NET      230      [ℓ] =  $V_{tt}$

CAPACITE DU COMPRESSEUR      : voir feuille séparée

---

**CHOIX DU MATERIEL:**

VOLUME TOTAL REEL: 1 x vase d'expansion type 300 =  $V_{tr}$

Réserve réelle = ( $V_{tr} - V_{ep}$ ) = (300 - 177,5) = 122,5      [ℓ] =  $R_r$

Pression réglée=      [bar] =  $p_r$

### 3.2.5. Détermination de la capacité du compresseur : $q_c$ [l/h]

Les données suivantes sont déterminées au préalable:

- - la variation de charge maximale estimée  $Q$  [kW]  
  (le plus souvent la moitié de la puissance installée)
- - la température moyenne  $t$  [°C]
- - la pression réglée dans l'installation  $p_r$  [bar]
- - le débit de contraction  $q$  [l/hkW], déterminé au moyen du graphique 3 ci-dessous

![[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/images/b178f3d3f789024a97cf2b3f0883e855_5_img.webp]]

Graphique 3 est un graphique à grille montrant la relation entre la température (en °C) sur l'axe des ordonnées et le débit de contraction par kW (en L/hkW) sur l'axe des abscisses. L'axe des ordonnées va de 10 à 130 en increments de 10. L'axe des abscisses va de 0 à 0.7 en increments de 0.1. Une droite diagonale part de l'origine (0,0) et s'étend jusqu'à environ (0.75, 112.5). Une ligne horizontale est tracée à 80 °C sur l'axe des ordonnées. Une ligne verticale descend de l'intersection de la droite diagonale et de la ligne horizontale jusqu'à l'axe des abscisses, où elle est marquée avec la valeur 0,56. Le texte 'débit de contraction par kW 0,56' est placé sous l'axe des abscisses.

<table border="1"><thead><tr><th>Température (°C)</th><th>Débit de contraction par kW (L/hkW)</th></tr></thead><tbody><tr><td>0</td><td>0</td></tr><tr><td>10</td><td>0.05</td></tr><tr><td>20</td><td>0.10</td></tr><tr><td>30</td><td>0.15</td></tr><tr><td>40</td><td>0.20</td></tr><tr><td>50</td><td>0.25</td></tr><tr><td>60</td><td>0.30</td></tr><tr><td>70</td><td>0.35</td></tr><tr><td>80</td><td>0.40</td></tr><tr><td>90</td><td>0.45</td></tr><tr><td>100</td><td>0.50</td></tr><tr><td>110</td><td>0.55</td></tr><tr><td>120</td><td>0.60</td></tr><tr><td>130</td><td>0.65</td></tr></tbody></table>

Graphique 3

L'équation devient alors:

$$q_c = q \cdot Q$$

### 3.2.6. Exemple

---

#### CALCUL DE CAPACITE DU COMPRESSEUR

<table><tr><td>Puissance installé</td><td>:</td><td>1500</td><td>[kW]</td><td></td></tr><tr><td>Variation de charge maximale</td><td>:</td><td>750</td><td>[kW]</td><td>Q</td></tr><tr><td>Débit de contraction par kW à 80 °C</td><td>:</td><td>0,56</td><td>[l/h par kW]</td><td>x q</td></tr><tr><td>Débit air comprimé requis minimale</td><td>:</td><td>420</td><td>[l/h]</td><td>= q<sub>c</sub></td></tr><tr><td>Pression réglée</td><td>:</td><td>à une pression de</td><td>[bar]</td><td>p<sub>r</sub></td></tr></table>

---

#### CHOIX DU MATERIEL

Propos: x compresseur type

<sup>(1)</sup>Incorporé standard dans le coffret de commande type

<sup>(1)</sup>Montage séparée, commandé par coffret de commande type

<sup>(1)</sup> biffer ce qui ne convient pas
