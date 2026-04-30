---
type: document-section
document_id: note-cti-hvac-sapc17-vase-expansion
section_id: section:2
ordre_document: 3
titre: Détermination des vases d'expansion à pression variable (quantité d'air fixe)
aliases:
  - Note CTI HVAC SAPC17 — Vases d'expansion — 03 Détermination des vases d'expansion à pression variable (quantité d'air fixe)
resume_section: |-
  ### Détermination des vases d'expansion à pression variable (quantité d'air fixe)

  #### Notions de base
  - **Loi de Boyle-Mariotte** : $p \cdot V = \text{constant}$ (température constante). En pratique, la variation de température est corrigée via le coefficient d'expansion de la température de départ.
  - **Pression colonne d'eau** ($p_h$) : dépend de la hauteur entre le vase et le point le plus élevé de l'installation ($p_h \approx h/10$ en bar).
  - **Pression de vaporisation** ($p_v$) : empêche la vaporisation de l'eau à haute température (ex. 110 °C : $p_v \approx 0,5$ bar).
  - **Pression de gonflage** ($p_g$) : $p_g = p_h + p_v + 0,3$ bar (min. 0,5 bar). Doit tenir compte de la NPSH du circulateur et de la pression minimale de la chaudière.
  - **Pression initiale** ($p_i$) : pression à froid, vase rempli avec réserve d'eau réelle.
  - **Pression finale** ($p_f$) : pression à chaud, vase contenant le volume utile ($V_u$).
  - **Pression maximale** ($p_m$) : admissible au vase, liée à la pression d'ouverture des soupapes de sécurité ($p_s$).
  - **Volume utile** ($V_u$) : eau maximale accueillie par le vase entre $p_g$ et $p_f$.

  #### Dimensionnement
  1. **Rendement de volume** ($F_p$) : dépend de $p_g$ et $p_f$.
     $$F_p = \frac{(p_f + 1) - (p_g + 1)}{(p_f + 1)}$$
  2. **Volume total théorique** ($V_{tt}$) :
     $$V_{tt} = \frac{V_n}{F_p}$$
     Choix du volume réel ($V_{tr}$) selon le marché : $V_{tr} \geq V_{tt}$.
  3. **Volume utile** ($V_u$) :
     $$V_u = V_{tr} \cdot F_p$$

  #### Exemple de calcul
  - Données : $C_i = 200$ ℓ, $p_s = 3$ bar, $p_h = 7$ m.
  - Résultats :
    - $p_g = 1$ bar, $p_f = 2,5$ bar.
    - $F_p = 0,428$, $V_{tt} = 21,3$ ℓ.
    - Choix : vase type 25 ℓ ($V_{tr}$).
    - Réserve réelle : $R_r = 3,6$ ℓ.
    - $p_i = 1,3$ bar.
  - **2.1 notions de base** — `section:2.1`, heading, profondeur 2, pages 8-11
  - **2.1.1 loi de boyle - mariotte** — `section:2.1.1`, heading, profondeur 3, pages 8-8
  - **2.1.2 colonne deau dune installation: p_h [bar]** — `section:2.1.2`, heading, profondeur 3, pages 8-8
  - **2.1.3 pression de vaporisation: p_v [bar]** — `section:2.1.3`, heading, profondeur 3, pages 8-8
  - **2.1.4 pression de gonflage: p_g [bar]** — `section:2.1.4`, heading, profondeur 3, pages 8-8
  - **2.1.5 pression initiale: p_i [bar]** — `section:2.1.5`, heading, profondeur 3, pages 9-9
  - **2.1.6 pression finale: p_f [bar]** — `section:2.1.6`, heading, profondeur 3, pages 9-9
  - **2.1.7 pression maximale: p_m [bar]** — `section:2.1.7`, heading, profondeur 3, pages 10-10
  - **2.1.8 pression douverture des soupapes de sécurité: p_s [bar]** — `section:2.1.8`, heading, profondeur 3, pages 10-10
  - **2.1.9 volume total théorique et réel: v_{tt} et v_{tr} [ \ell ]** — `section:2.1.9`, heading, profondeur 3, pages 10-10
  - **2.1.10 volume initial: v_i [ \ell ]** — `section:2.1.10`, heading, profondeur 3, pages 11-11
  - **2.1.11 volume final: v_f [ \ell ]** — `section:2.1.11`, heading, profondeur 3, pages 11-11
  - **2.1.12 volume utile: v_u [ \ell ]** — `section:2.1.12`, heading, profondeur 3, pages 11-11
  - **2.2 dimensionnement: équations** — `section:2.2`, heading, profondeur 2, pages 12-14
  - **2.2.1 rendement de volume ou facteur de pression: f_p** — `section:2.2.1`, heading, profondeur 3, pages 12-12
  - **2.2.2 volume total théorique et réel du vase dexpansion: v_{tt} et v_{tr} [ \ell ]** — `section:2.2.2`, heading, profondeur 3, pages 12-12
  - **2.2.3 volume utile: v_u [ \ell ]** — `section:2.2.3`, heading, profondeur 3, pages 12-12
  - **2.2.4 réserve deau réelle: r_r [ \ell ]** — `section:2.2.4`, heading, profondeur 3, pages 12-12
  - **2.2.5 pression initiale: p_i [bar]** — `section:2.2.5`, heading, profondeur 3, pages 13-13
  - **2.2.6 exemples** — `section:2.2.6`, heading, profondeur 3, pages 13-14
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/index|Note CTI HVAC SAPC17 — Vases d'expansion — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/02-generalites|Généralités]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/04-determination-des-vases-d-expansion-a-pression-constante-quantite-d-air-variable|Détermination des vases d'expansion à pression constante (quantité d'air variable)]]"
tags:
  - document-section
  - cti
  - hvac
sources:
  - 03_2_détermination_des_vases_dexpansion_à_pression_variable_quantité_dair_fixe.md
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

## 2. Détermination des vases d'expansion à pression variable (quantité d'air fixe)

### 2.1. Notions de base

On notera que toutes les pressions (bar) indiquées sont des pressions relatives, excepté sous 2.1.1..

#### 2.1.1. Loi de Boyle–Mariotte

$$p \cdot V = \text{constant (à température constante)}$$

Cette loi du gaz est valable lorsque la température est constante. Par contre, en réalité, la température du gaz de pression dans le vase peut changer. Cette déviation est corrigée de façon indirecte en utilisant le coefficient d'expansion de la température de départ au lieu de celui de la température moyenne de l'installation (voir aussi appendice A).

#### 2.1.2. Colonne d'eau d'une installation : $p_h$ [bar]

La pression produite par la différence en hauteur entre le point de raccordement du vase d'expansion et le point le plus élevé de l'installation.

$$p_h = \rho \cdot g \cdot h \quad [\text{Pa}]$$
$$p_h = 1 \cdot 9,81 \cdot h \quad [\text{Pa}]$$
$$\text{ou simplement } p_h [\text{bar}] \approx \frac{h [\text{m}]}{10}$$

#### 2.1.3. Pression de vaporisation : $p_v$ [bar]

La pression nécessaire pour éviter que l'eau ne se vaporise (bouillonnement) à des températures de départ au-dessus de 100°. (p.ex.: 110 °C:  $p_v \approx 0,5$  bar)

#### 2.1.4. Pression de gonflage : $p_g$ [bar]

La pression du vase d'expansion n'ayant pas encore accueilli d'eau, p.ex. avant le raccordement à l'installation

$$p_g = p_h + p_v + 0,3 \text{ bar (} p_g = \text{minimum } 0,5 \text{ bar)}$$

Remarque: ceci est surtout important pour des installations en toiture et pour des bâtiments à un seul niveau:

1) dans certaines situations le danger se présente que la pression du côté aspiration du circulateur ( $P_{circ}$ ) soit inférieure à la NPSH (Net Positive Suction Height) de ce dernier ; c'est pourquoi  $p_g$  doit être également choisi en fonction de ce qui suit:

$$\begin{array}{ll} \text{NPSH} & < p_{circ} +/ - \Delta p \text{ (pointzéro-circ)} \\ p_g & \geq p_{circ} \end{array}$$

$p_{circ}$  = pression à hauteur du côté aspiration du circulateur (circ)

$\Delta p(\text{pointzéro-circ})$  = différence de pression entre le point de raccordement au vase d'expansion (pointzéro) et le côté aspiration du circulateur (circ)

2) étant donné que la pression dans la chaudière ne peut jamais être inférieure à la valeur indiquée par le fabricant,  $p_g$  doit être choisi également en fonction de ce qui suit:

$$\begin{array}{ll} \text{press. min chaud.} & < p_{ch} \\ p_g & \geq p_{ch} +/ - \Delta p(\text{pointzéro-ch}) \\ p_{ch} & = \text{pression à hauteur de la chaudière} \\ \Delta p(\text{pointzéro-ch}) & = \text{différence de pression entre le point de raccordement du vase d'expansion (pointzéro) et la chaudière (ch)} \end{array}$$

(voir aussi appendice B)

#### 2.1.5. Pression initiale : $p_i$ [bar]

La pression à hauteur du vase d'expansion dans une installation qui est encore froide et complètement remplie, alors que le vase d'expansion a accueilli la réserve d'eau réelle ( $R_i$ ). Il règne alors une surpression à tous les points de l'installation.

#### 2.1.6. Pression finale : $p_f$ [bar]

La pression à hauteur du vase d'expansion dans une installation complètement réchauffée. Le vase d'expansion a accueilli le volume utile ( $V_u$ ).

### 2.1.7. Pression maximale : $p_m$ [bar]

La pression maximale admissible au vase d'expansion; la pression d'ouverture des soupapes de sécurité aux chaudières est atteinte (voir 2.1.8.).

$$P_m > P_f$$

### 2.1.8. Pression d'ouverture des soupapes de sécurité : $p_s$ [bar]

La pression d'ouverture des soupapes de sécurité doit donc être choisie de telle façon qu'une pression supérieure à la pression maximale admissible à ce point soit impossible en tout point pour l'ensemble de l'installation.

Remarque:

Etant donné qu'en raison d'une différence dans la colonne d'eau, de pertes dans les tuyaux etc... une différence de pression importante peut se produire entre le point de montage des soupapes de sécurité et le point de raccordement du système d'expansion, on tiendra compte de:

$$P_m \leq p_s \pm \Delta p(\text{point zéro-chaudière})$$

(voir aussi appendice C)

Aucune soupape de sécurité ne se ferme à la même pression que la pression à laquelle elle s'ouvre (hystérèse).

Il est donc à conseiller de tenir compte de ce fait afin de prévenir un déclenchement inutile des soupapes de sécurité. On en tiendra donc compte au moment de choisir la pression finale du vase d'expansion:

$$P_f = P_m - 0,5 \text{ bar}$$

### 2.1.9. Volume total théorique et réel : $V_{tt}$ et $V_{tr}$ [ $\ell$ ]

$V_{tt}$  = le volume d'air dans le vase d'expansion vide, calculé théoriquement

$V_{tr}$  = idem, mais choix pratique selon l'offre du marché

2.1.10. Volume initial :  $V_i$  [ $\ell$ ]

Le volume d'air dans le vase d'expansion alors qu'il a accueilli la réserve d'eau, à une pression égale à  $p_i$

2.1.11. Volume final :  $V_f$  [ $\ell$ ]

Le volume d'air du vase d'expansion dans une installation complètement réchauffée. Le vase d'expansion a accueilli le volume utile  $V_u$  à une pression  $p_f$ .

2.1.12. Volume utile :  $V_u$  [ $\ell$ ]

Le volume d'eau maximal que le vase peut accueillir entre  $p_g$  et  $p_f$ .

$$V_u = V_{tr} - V_f$$
$$V_u \geq V_n$$

## 2.2. Dimensionnement: équations

Les équations ci-dessous seront explicitées par après au moyen d'un exemple simple. Le calcul se déroule en trois phases:

- - détermination du volume net  $V_n$  (voir 1.2.4.)
- - détermination du rendement de volume  $F_p$  (voir 2.2.1.)
- - détermination du volume total théorique  $V_{tt}$  et du volume total réel  $V_{tr}$  (voir 2.2.2.)

### 2.2.1. Rendement de volume ou facteur de pression : $F_p$

Le rendement de volume est déterminé en fonction de la pression de gonflage ( $p_g$ ) et de la pression finale ( $p_f$ ) de l'installation.

$$F_p = \frac{(p_f + 1) - (p_g + 1)}{(p_f + 1)}$$

Dans le cas où le type choisi a un rendement de volume restreint à cause des limites de construction, on tiendra compte de cette valeur limitée lors du calcul définitif (voir appendice D)

### 2.2.2. Volume total théorique et réel du vase d'expansion : $V_{tt}$ et $V_{tr}$ [ $\ell$ ]

$$V_{tt} = \frac{V_e}{F_p}$$

ensuite, on choisit  $V_{tr}$  suivant l'offre du marché:

$$V_{tr} \geq V_{tt}$$

### 2.2.3. Volume utile : $V_u$ [ $\ell$ ]

$$V_u = V_{tr} \cdot F_p$$

### 2.2.4. Réserve d'eau réelle : $R_r$ [ $\ell$ ]

$$R_r = V_u - V_{ep}$$

### 2.2.5. Pression initiale : $p_i$ [bar]

$$p_i = \frac{V_{tr} \cdot (p_g + 1)}{V_{tr} - R_r} - 1$$

### 2.2.6. Exemples

premier exemple: calculé à la page 14

attention: il s'agit d'un exemple, élaboré au moyen d'une feuille de calcul simplifiée.

Données de base:

<table><tbody><tr><td>- Contenu en eau de l'installation</td><td><math>C_i = 200\ell</math></td></tr><tr><td>- Régime de température:</td><td>90/70 °C</td></tr><tr><td>- Pression d'ouverture soupape de sécurité:</td><td><math>p_s = 3\text{bar}</math></td></tr><tr><td>- Hauteur de la colonne d'eau</td><td><math>p_h = 7\text{ m}</math></td></tr></tbody></table>

Schéma simplifié de cette installation:

The diagram illustrates a simplified water system. At the top is a rectangular water tank. A pipe leads from the tank down to a boiler, represented by a square with a wavy line on top. A pressure gauge, shown as a circle with a triangle, is connected to the boiler. A safety valve, depicted as a wavy line with an upward arrow, is also connected to the boiler. A water meter, represented by a circle with a wavy line, is located at the bottom of the system. A vertical dimension line on the right side, labeled  $p_h$ , indicates the height of the water column from the level of the water meter to the top of the water tank.

exemples de cas spéciaux: voir appendice E

### CALCUL VOLUME D'EXPANSION:

<table border="0">
<tr>
<td>Contenu du système</td>
<td>(calculé)</td>
<td>:</td>
<td>200</td>
<td>[ℓ]</td>
<td>C<sub>i</sub></td>
</tr>
<tr>
<td>Coefficient d'expansion à 80 °C</td>
<td>(estimé : kW x ℓ/kW)</td>
<td>:</td>
<td>x 3,55</td>
<td>[%]</td>
<td>x C<sub>e</sub></td>
</tr>
<tr>
<td colspan="6"><hr/></td>
</tr>
<tr>
<td>Volume d'expansion physique</td>
<td></td>
<td>:</td>
<td>7,1</td>
<td>[ℓ]</td>
<td>= V<sub>ep</sub></td>
</tr>
<tr>
<td>1% réserve (C<sub>i</sub> x 0,01)</td>
<td></td>
<td>:</td>
<td>+ 2</td>
<td>[ℓ]</td>
<td>+ R<sub>t</sub></td>
</tr>
<tr>
<td colspan="6"><hr/></td>
</tr>
<tr>
<td>VOLUME NET</td>
<td></td>
<td>:</td>
<td>9,1</td>
<td>[ℓ]</td>
<td>= V<sub>n</sub></td>
</tr>
</table>

### CALCUL VASE D'EXPANSION:

<table border="0">
<tr>
<td>Pression gonflage</td>
<td>= colonne d'eau p<sub>h</sub> (<math>= \frac{h [m]}{10}</math>) + 0,3 bar</td>
<td>(I p<sub>g</sub>=min 0,5 bar)</td>
</tr>
<tr>
<td></td>
<td></td>
<td>(attention à la NPSH du circulateur et à la pression de service minimale de la chaudière: adapter éventuellement p<sub>g</sub>)</td>
</tr>
<tr>
<td></td>
<td><math>= \frac{7 [m]}{10} [\text{bar}] + 0,3 \text{ bar}</math></td>
<td><math>= 1 [\text{bar}] = p_g</math></td>
</tr>
<tr>
<td>Pression finale</td>
<td>= pression maximale p<sub>m</sub> - 0,5 bar</td>
<td>(att. à Δp entre pointzéro et chaudière, s.l. d'une différence de hauteur ou d'un circulateur présent p.ex.; prendre en compte la différence entre p<sub>m</sub> et p<sub>i</sub>)</td>
</tr>
<tr>
<td></td>
<td><math>= 3 [\text{bar}] - 0,5 \text{ bar}</math></td>
<td><math>= 2,5 [\text{bar}] = p_f</math></td>
</tr>
<tr>
<td>Rendement de volume</td>
<td><math>= \frac{(p_f+1)-(p_g+1)}{(p_f+1)} = \frac{(2,5+1)-(1+1)}{(2,5+1)} = 0,428</math></td>
<td>= F<sub>p</sub></td>
</tr>
<tr>
<td>Volume Total Théorique</td>
<td><math>= \frac{\text{VOLUME NET } V_n}{\text{rendement volume } F_p} = \frac{9,1}{0,428} = 21,3 [\ell]</math></td>
<td>= V<sub>tt</sub></td>
</tr>
</table>

### CHOIX DU MATERIEL:

<table border="0">
<tr>
<td>Volume Total Réel</td>
<td>1 x vase d'expansion type 25</td>
<td>= V<sub>tr</sub></td>
</tr>
<tr>
<td>Réserve réelle</td>
<td><math>= (V_{tr} \times F_p) - V_{ep} = (25 \times 0,428) - 7,1 = 3,6 [\ell]</math></td>
<td>= R<sub>r</sub></td>
</tr>
<tr>
<td>Pression initiale</td>
<td><math>= \frac{V_{tr} \times (p_g + 1)}{V_{tr} - R_r} - 1 = \frac{25 \times (1+1)}{25 - 3,6} - 1 = 1,3 [\text{bar}] = p_i</math></td>
<td></td>
</tr>
</table>
