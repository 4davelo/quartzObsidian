---
type: document-section
document_id: note-cti-hvac-sapc17-vase-expansion
section_id: section:1
ordre_document: 2
titre: Généralités
aliases:
  - Note CTI HVAC SAPC17 — Vases d'expansion — 02 Généralités
resume_section: |-
  ### Généralités sur les vases d'expansion

  #### Fonction et importance
  Les vases d'expansion assurent la sécurité des systèmes de chauffage central en absorbant les variations de volume dues aux changements de température. Un sous-dimensionnement peut entraîner des dysfonctionnements, des infiltrations d'air, de la corrosion et des pertes d'eau.

  #### Types de systèmes
  - **Pression variable** (air fixe, CC 105 Art. C5 § 1)
  - **Pression constante** (air variable, CC 105 Art. C5 § 2)

  #### Calculs essentiels
  1. **Contenu en eau ($C_i$)** : Dépend de la chaudière, des conduits et des radiateurs. Un calcul précis est requis.
  2. **Volume d'expansion physique ($V_{ep}$)** : Proportionnel au contenu en eau et au coefficient d'expansion ($c_e$), qui varie avec la température.
  3. **Réserve d'eau théorique ($R_t$)** : 1% du contenu total en eau.
  4. **Volume net ($V_n$)** : Somme de $V_{ep}$ et $R_t$.
  5. **Volume utile ($V_u$)** : Doit être au moins égal à $V_n$.
  6. **Réserve d'eau réelle ($R_r$)** : Différence entre $V_u$ et $V_{ep}$.

  #### Emplacement optimal
  Le vase d'expansion doit être installé sur le circuit de retour, côté aspiration du circulateur, pour limiter l'usure de la membrane et la diffusion d'air. Les tuyaux doivent être dimensionnés pour minimiser les pertes hydrauliques.
  - **1.1 introduction** — `section:1.1`, heading, profondeur 2, pages 3-3
  - **1.2 détermination générale du volume dexpansion** — `section:1.2`, heading, profondeur 2, pages 3-6
  - **1.2.1 le contenu en eau de linstallation: c_i [ \ell ]** — `section:1.2.1`, heading, profondeur 3, pages 3-4
  - **1.2.2 le volume dexpansion physique: v_{ep} [ \ell ]** — `section:1.2.2`, heading, profondeur 3, pages 5-5
  - **1.2.3 réserve deau théorique: r_t [ \ell ]** — `section:1.2.3`, heading, profondeur 3, pages 6-6
  - **1.2.4 le volume net: v_n [ \ell ]** — `section:1.2.4`, heading, profondeur 3, pages 6-6
  - **1.2.5 le volume utile: v_u [ \ell ]** — `section:1.2.5`, heading, profondeur 3, pages 6-6
  - **1.2.6 réserve deau réelle: r_r [ \ell ]** — `section:1.2.6`, heading, profondeur 3, pages 6-6
  - **1.3 emplacement du système dexpansion** — `section:1.3`, heading, profondeur 2, pages 7-7
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/index|Note CTI HVAC SAPC17 — Vases d'expansion — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/01-preface|Preface]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/03-determination-des-vases-d-expansion-a-pression-variable-quantite-d-air-fixe|Détermination des vases d'expansion à pression variable (quantité d'air fixe)]]"
tags:
  - document-section
  - cti
  - hvac
sources:
  - 02_1_généralités.md
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

## 1. Généralités

### 1.1. Introduction

Les vases d'expansion sont des dispositifs de sécurité pour les installations de chauffage central en circuit fermé. Ils sont destinés à absorber les changements de volume causés par le réchauffement ou le refroidissement de l'installation.

Les systèmes d'expansion sous-dimensionnés causent des perturbations du fonctionnement et endommagent l'installation. Lors du refroidissement, il se forme une dépression dans l'installation, ce qui entraîne une infiltration d'air par les joints, par les purgeurs automatiques installés à des points élevés etc.; lors du réchauffement, le système d'expansion ne peut plus accueillir d'eau, ce qui cause une perte d'eau d'installation par les soupapes de sécurité. L'infiltration d'air introduit de l'oxygène dans l'installation, d'où la possibilité d'une corrosion des surfaces d'acier non traitées. En outre, des bulles d'air empêchent une bonne circulation, elles peuvent endommager la pompe, etc.

Nous distinguons deux principes de fonctionnement:

- - un système d'expansion à pression variable  
  (quantité d'air fixe: CC 105 Art. C5 § 1)
- - un système d'expansion à pression constante  
  (quantité d'air variable: CC 105 Art. C5 § 2)

### 1.2. Détermination générale du volume d'expansion

#### 1.2.1. Le contenu en eau de l'installation : $C_i$ [ $\ell$ ]

Le contenu en eau de l'installation est déterminé par les composantes suivantes:

- - la chaudière: le contenu en eau dépend du modèle et de la marque. Tant pour les chaudières en acier que pour les chaudières en fonte, celui-ci est normalement compris entre 1,5  $\ell$  et 3,5  $\ell$ /kW de puissance de la chaudière.
- - les conduits de chauffage: le contenu en eau des conduits dépend du dimensionnement et du tracé. Celui-ci doit être calculé soigneusement au moyen du mètre de la tuyauterie.
- - les corps de chauffe: le contenu en eau dépend du modèle des corps de chauffe (con vecteurs, radiateurs en acier, radiateurs en tôle d'acier, radiateurs en fonte, batteries de chauffage, échangeurs de chaleur...) et de la marque.

Le diagramme ci-dessous (fig. 1) indique approximativement le contenu en eau d'une installation ordinaire avec un tracé moyen de conduits à circulation accélérée pour les différents modèles de radiateurs en fonction de la puissance calorifique en kW.

Pour la détermination des installations un calcul précis est exigé.

![A log-log graph showing the relationship between water volume (L) and heating power (kW) for different radiator types. The y-axis is labeled (L) and ranges from 50 to 100,000. The x-axis is labeled (kW) and ranges from 5 to 5,000. Four lines are plotted: 'Chauffage par le sol' (top), 'Radiateurs en acier DIN 4722' (second from top), 'Radiateurs en tôle d'acier' (third from top), and 'Convecateurs' (bottom). All lines show a positive linear relationship on the log-log scale.](documents/CCT/Cahier%20des%20charges%20et%20annexes%20–%20HVAC/note-cti-hvac-sapc17-vase-expansion/images/a87635782f64bc05c98e5bccd408d9f6_4_img.webp)

<table border="1"><caption>Approximate data points from the graph (Fig. 1)</caption><thead><tr><th>Power (kW)</th><th>Convecateurs (L)</th><th>Radiateurs en tôle d'acier (L)</th><th>Radiateurs en acier DIN 4722 (L)</th><th>Chauffage par le sol (L)</th></tr></thead><tbody><tr><td>5</td><td>50</td><td>75</td><td>100</td><td>125</td></tr><tr><td>10</td><td>100</td><td>150</td><td>200</td><td>250</td></tr><tr><td>20</td><td>200</td><td>300</td><td>400</td><td>500</td></tr><tr><td>50</td><td>500</td><td>750</td><td>1000</td><td>1250</td></tr><tr><td>100</td><td>1000</td><td>1500</td><td>2000</td><td>2500</td></tr><tr><td>200</td><td>2000</td><td>3000</td><td>4000</td><td>5000</td></tr><tr><td>500</td><td>5000</td><td>7500</td><td>10000</td><td>12500</td></tr><tr><td>1000</td><td>10000</td><td>15000</td><td>20000</td><td>25000</td></tr><tr><td>2000</td><td>20000</td><td>30000</td><td>40000</td><td>50000</td></tr><tr><td>5000</td><td>50000</td><td>75000</td><td>100000</td><td>125000</td></tr></tbody></table>

diagramme (fig. 1)

Contenance moyenne en eau d'une installation de chauffage central en fonction de la puissance.

(Attention: des radiateurs en acier DIN 4722 = radiateurs à colonne composés de colonnes en tôle d'acier  
des radiateurs en tôle d'acier = des radiateurs modernes avec lames à convection)

### 1.2.2. Le volume d'expansion physique : $V_{ep}$ [ $\ell$ ]

A une pression atmosphérique de 1013 mbar et à une température de 4° C, l'eau possède sa masse volumique la plus élevée, qui équivaut à 1 kg/dm<sup>3</sup> et se dilate de 4,31% lors du réchauffement de 4°C à 100°C. Le tableau 1 donne le coefficient d'expansion ( $c_e$ ) (en %) de l'eau, au départ de 4° C, en fonction des températures de service maximales (voir également la fig. 2).

Les vases d'expansion doivent au moins pouvoir absorber l'expansion lors du réchauffement complet de l'installation. Pour des installations de chauffage, la température de réchauffement est supposée être la température de départ (généralement 90°C). Pour les installations de refroidissement, la température de réchauffement maximale est égale à la température ambiante maximale (généralement 30°C).

$$V_{ep} = C_i \cdot \frac{c_e}{100}$$

$V_{ep}$  = volume d'expansion physique [ $\ell$ ]

$C_i$  = contenu en eau total de l'installation [ $\ell$ ]

$c_e$  = coefficient d'expansion en pourcentage d'eau à la température maximale de réchauffement (pour chauffage: température de départ) (pour les installations ordinaires 90° = 3,55%) (voir aussi appendice A)

<table border="1">
<thead>
<tr>
<th>[°C]</th>
<th><math>c_e</math> [%]</th>
</tr>
</thead>
<tbody>
<tr>
<td>30</td>
<td>0,44</td>
</tr>
<tr>
<td>40</td>
<td>0,75</td>
</tr>
<tr>
<td>50</td>
<td>1,17</td>
</tr>
<tr>
<td>60</td>
<td>1,67</td>
</tr>
<tr>
<td>70</td>
<td>2,24</td>
</tr>
<tr>
<td>80</td>
<td>2,86</td>
</tr>
<tr>
<td>90</td>
<td>3,55</td>
</tr>
<tr>
<td>100</td>
<td>4,31</td>
</tr>
<tr>
<td>110</td>
<td>5,11</td>
</tr>
<tr>
<td>120</td>
<td>5,99</td>
</tr>
</tbody>
</table>

tableau 1

![Graphique montrant l'expansion (%) en fonction de la température [°C]. La courbe montre une augmentation linéaire de l'expansion avec la température, passant de 0,44% à 30°C à 5,99% à 120°C.](documents/CCT/Cahier%20des%20charges%20et%20annexes%20–%20HVAC/note-cti-hvac-sapc17-vase-expansion/images/09cd7ee91fd16eb8baf23ffccc29f1e0_11_img.webp)

Détails du graphique : L'axe des ordonnées (Y) est étiqueté 'Expansion (%)' et va de 0 à 6. L'axe des abscisses (X) est étiqueté 'Température [°C]' et va de 40 à 120. La courbe de l'expansion est une droite linéaire qui commence à (40, 0,44) et finit à (120, 5,99). Des grilles sont présentes sur les deux axes.

figure 2

Attention: si des additifs, p.ex. des produits antigel, sont ajoutés à l'eau, ces coefficients d'expansion peuvent varier considérablement.

### 1.2.3. Réserve d'eau théorique : $R_t$ [ $\ell$ ]

Un vase d'expansion doit pouvoir absorber une quantité d'eau supérieure à la seule quantité d'expansion de l'installation. En effet, si l'on se limitait à la seule quantité de l'expansion, le vase ne contiendrait pas d'eau lorsque l'installation est refroidie.

Il s'agit en fait d'une situation abstraite: Il est impossible de remplir une installation avec une telle précision; d'éventuelles fuites et des pertes d'eau lors de la purge en fournissent la preuve.

On doit donc prévoir une réserve d'eau  $R_t$  qui – avec le volume d'expansion physique  $V_{ep}$  – sera également accueillie dans le vase d'expansion. Cette réserve d'eau représentera 1% du contenu total  $C_i$  de l'installation:

$$R_t = C_i \cdot 0,01$$

$R_t$  = réserve d'eau théorique

$C_i$  = contenu en eau de l'installation

### 1.2.4. Le volume net : $V_n$ [ $\ell$ ]

est obtenu par la somme du volume d'expansion physique et de la réserve d'eau théorique.

$$V_n = V_{ep} + R_t$$

$V_n$  = volume net

$V_{ep}$  = volume d'expansion physique

$R_t$  = réserve d'eau théorique

### 1.2.5. Le volume utile : $V_u$ [ $\ell$ ]

Selon l'offre du marché, il faut toujours choisir un vase d'expansion qui peut contenir un volume utile  $V_u$  équivalent au moins au volume net  $V_n$ , mais qui sera pourtant, dans beaucoup de cas, plus grand.

$$V_u \geq V_n$$

### 1.2.6. Réserve d'eau réelle : $R_r$ [ $\ell$ ]

La réserve d'eau réelle que peut contenir le vase d'expansion

$$R_r > R_t$$
$$R_r = V_u - V_{ep}$$

### 1.3. Emplacement du système d'expansion

Le point de raccordement du système d'expansion doit se trouver, de préférence, sur le circuit de retour de l'installation, car à cet endroit, la température est favorable à une durée de vie plus longue de la membrane et la diffusion d'air à travers la membrane diminue.

Le système d'expansion est toujours monté du côté aspiration du circulateur, parce qu'il forme le point zéro hydraulique de l'installation. En cas d'utilisation de plusieurs circulateurs à des endroits différents, on prendra toujours en considération ce qui suit:

tuyau d'aspiration (= partie vase d'expansion → circulateur):  
aussi court que possible

tuyau de pression (= partie circulateur → vase d'expansion):  
aussi long que possible
