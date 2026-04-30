---
type: document-section
document_id: note-cti-hvac-sapc17-vase-expansion
section_id: section:appendice-e
ordre_document: 10
titre: APPENDICE E
aliases:
  - Note CTI HVAC SAPC17 — Vases d'expansion — 10 APPENDICE E
resume_section: |-
  ## APPENDICE E : Résumé des exemples particuliers

  ### 1) Vase d'expansion en hauteur, chaudière en bas
  - **Données clés** : $C_l = 200\ell$, $p_s = 3\text{ bar}$, $p_h = 0,1\text{ bar}$, $\Delta p = 0,7\text{ bar}$.
  - **Calculs** :
    - Volume net : $V_n = 9,1\ell$.
    - Volume total théorique : $V_{tr} = 19,6\ell$.
    - Matériel : Vase d'expansion de $25\ell$.

  ### 2) Pompe de circulation sur conduite retour
  - **Données clés** : $C_l = 2000\ell$, $p_s = 3\text{ bar}$, $p_h = 0,7\text{ bar}$, $\Delta p = 0,4\text{ bar}$.
  - **Calculs** :
    - Volume net : $V_n = 91\ell$.
    - Volume total théorique : $V_{tr} = 256\ell$.
    - Matériel : Vase d'expansion de $300\ell$.

  ### 3) Chaudière en toiture
  - **Données clés** : $C_l = 2000\ell$, $p_s = 3\text{ bar}$, $p_h = 0,1\text{ bar}$, pression minimale chaudière $= 1\text{ bar}$.
  - **Calculs** :
    - Volume net : $V_n = 91\ell$.
    - Volume total théorique : $V_{tr} = 212,6\ell$.
    - Matériel : Vase d'expansion de $300\ell$.

  ### 4) Construction basse, pompe avec NPSH
  - **Données clés** : $C_l = 2000\ell$, $p_s = 3\text{ bar}$, $p_h = 0,2\text{ bar}$, NPSH pompe $= 0,9\text{ bar}$.
  - **Calculs** :
    - Volume net : $V_n = 91\ell$.
    - Volume total théorique : $V_{tr} = 265\ell$.
    - Matériel : Vase d'expansion de $300\ell$.
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/index|Note CTI HVAC SAPC17 — Vases d'expansion — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/09-appendice-d|APPENDICE D]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/11-appendice-f|APPENDICE F]]"
tags:
  - document-section
  - cti
  - hvac
sources:
  - 10_appendice-e_appendice_e.md
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

## APPENDICE E:

Exemples particuliers:

1. 1) vase d'expansion au point le plus élevé alors que la chaudière se trouve en bas:

Données de base:

- - Contenu en eau de l'installation  $C_l = 200\ell$
- - Régime de température:  $90/70^\circ\text{C}$
- - Pression d'ouverture soupape de sécurité:  $p_s = 3\text{bar}$
- - Hauteur de la colonne d'eau:  $p_h = 1\text{ m} = 0,1\text{ bar}$
- - Différence de pression statique entre le point zéro et la chaudière  $0,7\text{ bar}$
- - Différence de pression dynamique entre ... idem  $0,2\text{ bar}$
- - Différence de pression totale à prendre en compte entre le point zéro et la chaudière  $0,7\text{ bar}$   
  (en effet, la baisse de pression que la pompe engendrera dans la chaudière dans cette position, quand elle démarre, ne peut pas être prise en compte; en cas d'arrêt de la pompe, la pression sur la soupape de sécurité augmenterait au-dessus de la valeur prévue)

Schéma simplifié de cette installation:

$$\begin{aligned}\text{Calcul } p_m &= p_s \pm \Delta p(\text{point zéro-ch}) \\ &= 3\text{ bar} - 0,7\text{ bar} \\ &= 2,3\text{ bar}\end{aligned}$$

### CALCUL VOLUME D'EXPANSION:

<table border="0">
<tr>
<td>Contenu du système</td>
<td>(calculé)</td>
<td>:</td>
<td>200</td>
<td>[ℓ]</td>
<td><math>C_i</math></td>
</tr>
<tr>
<td>Coefficient d'expansion</td>
<td>(estimé : <math>\frac{\text{kW} \times \text{ℓ/KW}}{\text{°C}}</math>)</td>
<td>:</td>
<td><math>x</math> 3,55</td>
<td>[%]</td>
<td><math>x C_e</math></td>
</tr>
<tr>
<td>Volume d'expansion physique</td>
<td></td>
<td>:</td>
<td>7,1</td>
<td>[ℓ]</td>
<td><math>= V_{ep}</math></td>
</tr>
<tr>
<td>1% réserve (<math>C_i \times 0,01</math>)</td>
<td></td>
<td>:</td>
<td>2</td>
<td>[ℓ]</td>
<td><math>+ R_i</math></td>
</tr>
<tr>
<td><b>VOLUME NET</b></td>
<td></td>
<td>:</td>
<td>9,1</td>
<td>[ℓ]</td>
<td><math>= V_n</math></td>
</tr>
</table>

### CALCUL VASE D'EXPANSION:

<table border="0">
<tr>
<td>Pression gonflage</td>
<td><math>= \text{colonne d'eau } p_n \left( = \frac{h \text{ [m]}}{10} \right) + 0,3 \text{ bar}</math></td>
<td>(<math>p_g = \min 0,5 \text{ bar}</math>)</td>
<td>(attention à la NPSH du circulateur et à la pression de service minimale de la chaudière: adapter éventuellement <math>p_g</math>)</td>
</tr>
<tr>
<td></td>
<td><math>= \frac{\text{[m]}}{10} [\text{bar}] + 0,3 \text{ bar}</math></td>
<td><math>= 0,5 \text{ [bar]} = p_g</math></td>
<td></td>
</tr>
<tr>
<td>Pression finale</td>
<td><math>= \text{pression maximale } p_m - 0,5 \text{ bar}</math></td>
<td colspan="2" rowspan="2">
<math>\left( \text{att. à } \Delta p \text{ entre point zéro et chaudière, s.i. d'une différence de hauteur ou d'un circulateur présent p.ex.; prendre en compte la différence entre } p_m \text{ et } p_i \right)</math>
</td>
</tr>
<tr>
<td></td>
<td><math>(p_m = 3 \text{ bar} - 0,7 \text{ bar} = 2,3 \text{ bar})</math></td>
</tr>
<tr>
<td></td>
<td><math>= 2,3 \text{ [bar]} - 0,5 \text{ bar}</math></td>
<td><math>= 1,8 \text{ [bar]} = p_i</math></td>
<td>!</td>
</tr>
<tr>
<td>Rendement de volume</td>
<td><math>= \frac{(p_i+1)-(p_g+1)}{(p_i+1)} = \frac{(1,8+1)-(0,5+1)}{(1,8+1)} = 0,464</math></td>
<td><math>= F_p</math></td>
<td></td>
</tr>
<tr>
<td>Volume Total Théorique</td>
<td><math>= \frac{\text{VOLUME NET } V_n}{\text{rendement volume } F_p} = \frac{9,1}{0,464} = 19,6</math></td>
<td>[ℓ]</td>
<td><math>= V_{tr}</math></td>
</tr>
</table>

### CHOIX DU MATERIEL:

<table border="0">
<tr>
<td>Volume Total Réel</td>
<td>1 x vase d'expansion type</td>
<td>25</td>
<td><math>= V_{tr}</math></td>
</tr>
<tr>
<td>Réserve réelle</td>
<td><math>= (V_{tr} \times F_p) - V_{ep} = (25 \times 0,464) - 7,1 = 4,5</math></td>
<td>[ℓ]</td>
<td><math>= R_r</math></td>
</tr>
<tr>
<td>Pression initiale</td>
<td><math>= \frac{V_{tr} \times (p_g + 1)}{V_{tr} - R_r} - 1 = \frac{25 \times (0,5 + 1)}{25 - 4,5} - 1 = 0,8</math></td>
<td>[bar]</td>
<td><math>= p_i</math></td>
</tr>
</table>

2) pompe de circulation dans la conduite retour entre le vase d'expansion et la chaudière:

Données de base:

- - Contenu en eau de l'installation:  $C_l = 2000\ell$
- - Régime de température:  $90/70\text{ }^\circ\text{C}$
- - Pression d'ouverture soupape de sécurité:  $p_s = 3\text{ bar}$
- - Hauteur de la colonne d'eau:  $p_h = 7\text{ m} = 0,7\text{ bar}$
- - Différence de pression dynamique (pompe) entre le point zéro et la chaudière  $0,4\text{ bar}$
- - Différence de pression totale entre le point zéro et la chaudière  $0,4\text{ bar}$

Schéma simplifié de cette installation:

The diagram illustrates a simplified heating system loop. At the top is a boiler (represented by a rectangle). A pipe leads from the boiler to a pump (represented by a circle with an arrow). The pump is connected to a return pipe that descends to a vertical column of water. A pressure gauge (represented by a triangle symbol) is connected to the top of this column. A horizontal dimension line at the bottom indicates the pressure difference  $\Delta p(\text{point zéro-ch})$  between the gauge and the boiler. A vertical dimension line on the right indicates the height of the water column.

$$\begin{aligned}\text{Calcul } p_m &= p_s \pm \Delta p(\text{point zéro-ch}) \\ &= 3\text{ bar} - 0,4\text{ bar} \\ &= 2,6\text{ bar}\end{aligned}$$

### CALCUL VOLUME D'EXPANSION:

<table border="0">
<tr>
<td>Contenu du système</td>
<td>(calculé)</td>
<td>:</td>
<td>2000</td>
<td>[ℓ]</td>
<td><math>C_i</math></td>
</tr>
<tr>
<td>Coefficient d'expansion à 90 °C</td>
<td>(estimé : <math>\frac{\text{KW} \times \text{ℓ/KW}}{\text{°C}}</math>)</td>
<td>:</td>
<td>x 3,55</td>
<td>[%]</td>
<td><math>x C_e</math></td>
</tr>
<tr>
<td>Volume d'expansion physique</td>
<td></td>
<td>:</td>
<td>71</td>
<td>[ℓ]</td>
<td><math>= V_{ep}</math></td>
</tr>
<tr>
<td>1% réserve (<math>C_i \times 0,01</math>)</td>
<td></td>
<td>:</td>
<td>+ 20</td>
<td>[ℓ]</td>
<td><math>+ R_i</math></td>
</tr>
<tr>
<td>VOLUME NET</td>
<td></td>
<td>:</td>
<td>91</td>
<td>[ℓ]</td>
<td><math>= V_n</math></td>
</tr>
</table>

### CALCUL VASE D'EXPANSION:

Pression gonflage = colonne d'eau  $p_h = \left( \frac{h \text{ [m]}}{10} \right) + 0,3 \text{ bar}$  ( $p_g = \min 0,5 \text{ bar}$ )  
(attention à la NPSH du circulateur et à la pression de service minimale de la chaudière: adapter éventuellement  $p_g$ )

$$= \frac{7 \text{ [m]}}{10} \text{ [bar]} + 0,3 \text{ bar} = 1 \text{ [bar]} = p_g$$

Pression finale = pression maximale  $p_m - 0,5 \text{ bar}$   
(att. à  $\Delta p$  entre pointzéro et chaudière, s.i. d'une différence de hauteur ou d'un circulateur présent p.ex.; prendre en compte la différence entre  $p_m$  et  $p_i$ )

$$= 2,6 \text{ [bar]} - 0,5 \text{ bar} = 2,1 \text{ [bar]} = p_f$$

$$\text{Rendement de volume} = \frac{(p_f+1)-(p_g+1)}{(p_f+1)} = \frac{(2,1+1)-(1+1)}{(2,1+1)} = 0,355 = F_p$$

$$\text{Volume Total Théorique} = \frac{\text{VOLUME NET } V_n}{\text{rendement volume } F_p} = \frac{91}{0,355} = 256 \text{ [ℓ]} = V_{tr}$$

### CHOIX DU MATERIEL:

Volume Total Réel  $1 \times \text{vase d'expansion type } 300 = V_{tr}$

$$\text{Réserve réelle} = (V_{tr} \times F_p) - V_{ep} = (300 \times 0,355) - 71 = 35,5 \text{ [ℓ]} = R_r$$

$$\text{Pression initiale} = \frac{V_{tr} \times (p_g + 1)}{V_{tr} - R_r} - 1 = \frac{300 \times (1 + 1)}{300 - 35,5} - 1 = 1,3 \text{ [bar]} = p_i$$

3) Installation de la chaudière en toiture : respecter la pression de service minimale de la chaudière

Données de base:

- - Contenu en eau de l'installation:  $C_l = 2000\ell$
- - Régime de température:  $90/70^\circ\text{C}$
- - Pression d'ouverture soupape de sécurité:  $p_s = 3\text{bar}$
- - Hauteur de la colonne d'eau:  $p_h = 1\text{ m} = 0,1\text{ bar}$
- - Pression de service minimale de la chaudière  $1\text{ bar}$

Schéma simplifié de cette installation:

The diagram illustrates a simplified boiler installation. A boiler is shown as a square box. A safety valve, represented by a wavy line with an upward arrow, is mounted on its top. A pipe extends from the boiler to the right, then turns 90 degrees downward. A pressure gauge, depicted as a circle with a horizontal line, is connected to this horizontal pipe. The pipe then continues downward to a rectangular tank. A vertical dashed line is drawn from the horizontal pipe level to the top of the vertical section, with a double-headed arrow labeled  $p_h$  indicating the height of the water column.

$$\begin{aligned}\text{Calcul } p_g &= p_{ch} \pm \Delta p(\text{point zéro-ch}) \\ &= 1\text{ bar} \pm 0\text{ bar} \\ &= 1\text{ bar}\end{aligned}$$

### CALCUL VOLUME D'EXPANSION:

<table border="0">
<tr>
<td>Contenu du système</td>
<td>(calculé)</td>
<td>:</td>
<td>2000</td>
<td>[l]</td>
<td><math>C_i</math></td>
</tr>
<tr>
<td>Coefficient d'expansion à 90 °C</td>
<td>(estimé : <math>\frac{\text{kW} \times \text{l/kW}}{\text{°C}}</math>)</td>
<td>:</td>
<td>x 3,55</td>
<td>[%]</td>
<td><math>x C_e</math></td>
</tr>
<tr>
<td>Volume d'expansion physique</td>
<td></td>
<td>:</td>
<td>71</td>
<td>[l]</td>
<td><math>= V_{ep}</math></td>
</tr>
<tr>
<td>1% réserve (<math>C_i \times 0,01</math>)</td>
<td></td>
<td>:</td>
<td>+ 20</td>
<td>[l]</td>
<td><math>+ R_i</math></td>
</tr>
<tr>
<td><b>VOLUME NET</b></td>
<td></td>
<td>:</td>
<td>91</td>
<td>[l]</td>
<td><math>= V_n</math></td>
</tr>
</table>

### CALCUL VASE D'EXPANSION:

Pression gonflage = colonne d'eau  $p_h$  ( $= \frac{h \text{ [m]}}{10}$ ) + 0,3 bar ( $p_g = \min 0,5 \text{ bar}$ )

(attention à la NPSH du circulateur et à la pression de service minimale de la chaudière: adapter éventuellement  $p_g$ ) !

$$= \frac{1 \text{ [m]}}{10} \text{ [bar]} + 0,3 \text{ bar} = 1 \text{ [bar]} = p_g$$

Pression finale = pression maximale  $p_m$  - 0,5 bar

(att. à  $\Delta p$  entre pointzéro et chaudière, s.l. d'une différence de hauteur ou d'un circulateur présent p.ex.; prendre en compte la différence entre  $p_m$  et  $p_i$ )

$$= 3 \text{ [bar]} - 0,5 \text{ bar} = 2,5 \text{ [bar]} = p_f$$

Rendement de volume =  $\frac{(p_f+1)-(p_g+1)}{(p_f+1)} = \frac{(2,5+1)-(1+1)}{(2,5+1)} = 0,428 = F_p$

Volume Total Théorique =  $\frac{\text{VOLUME NET } V_n}{\text{rendement volume } F_p} = \frac{91}{0,428} = 212,6 \text{ [l]} = V_{tr}$

### CHOIX DU MATERIEL:

Volume Total Réel = 1 x vase d'expansion type 300 =  $V_{tr}$

Réservé réelle =  $(V_{tr} \times F_p) - V_{ep} = (300 \times 0,428) - 71 = 57,4 \text{ [l]} = R_r$

Pression initiale =  $\frac{V_{tr} \times (p_g + 1)}{V_{tr} - R_r} - 1 = \frac{300 \times (1 + 1)}{300 - 57,4} - 1 = 1,5 \text{ [bar]} = p_i$

4) Construction basse à un seul niveau: respecter la NPSH de la pompe

Données de base:

- - Contenu en eau de l'installation:  $C_i = 2000\ell$
- - Régime de température:  $90/70\text{ }^\circ\text{C}$
- - Pression d'ouverture soupape de sécurité:  $p_s = 3\text{bar}$
- - Hauteur de la colonne d'eau:  $p_h = 2\text{ m} = 0,2\text{ bar}$
- - Différence de pression dynamique (perte dans la conduite) entre le point zéro et la pompe de circulation  $0,3\text{ bar}$
- - Différence de pression statique entre le point zéro et la pompe de circulation  $0,1\text{ bar}$
- - NPSH de la pompe de circulation  $0,9\text{ bar}$

Schéma simplifié de cette installation:

$$\begin{aligned}\text{Calcul } p_g &= p_{\text{circ}} \pm \Delta p(\text{point zéro-circ}) \\ &= 0,9\text{ bar} + 0,3\text{ bar} + 0,1\text{ bar} \\ &= 1,3\text{ bar}\end{aligned}$$

### CALCUL VOLUME D'EXPANSION:

<table border="0">
<tr>
<td>Contenu du système <small>(calculé)</small></td>
<td>:</td>
<td>2000</td>
<td>[l]</td>
<td><math>C_i</math></td>
</tr>
<tr>
<td><small>(estimé : <math>\frac{\text{kW} \times \ell(\text{kW})}{80 \text{ °C}}</math>)</small></td>
<td>:</td>
<td>3,55</td>
<td>[%]</td>
<td><math>x C_e</math></td>
</tr>
<tr>
<td>Coefficient d'expansion à 80 °C</td>
<td>:</td>
<td>x</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Volume d'expansion physique</td>
<td>:</td>
<td>71</td>
<td>[l]</td>
<td><math>= V_{ep}</math></td>
</tr>
<tr>
<td>1% réserve (<math>C_i \times 0,01</math>)</td>
<td>:</td>
<td>+ 20</td>
<td>[l]</td>
<td><math>+ R_i</math></td>
</tr>
<tr>
<td>VOLUME NET</td>
<td>:</td>
<td>91</td>
<td>[l]</td>
<td><math>= V_n</math></td>
</tr>
</table>

### CALCUL VASE D'EXPANSION:

<table border="0">
<tr>
<td>Pression gonflage</td>
<td>= colonne d'eau <math>p_n \left( - \frac{h \text{ [m]}}{10} \right) + 0,3 \text{ bar}</math> (<math>p_g = \min 0,5 \text{ bar}</math>)</td>
<td>(attention à la NPSH du circulateur et à la pression de service minimale de la chaudière: adapter éventuellement <math>p_g</math>) !</td>
</tr>
<tr>
<td></td>
<td><math>= 0,9 \text{ bar} + 0,3 \text{ bar} + 0,1 \text{ bar}</math></td>
<td></td>
</tr>
<tr>
<td></td>
<td><math>= \frac{\text{[m]}}{10} \text{ [bar]} + 0,3 \text{ bar}</math></td>
<td><math>= 1,3 \text{ [bar]} = p_g</math></td>
</tr>
<tr>
<td>Pression finale</td>
<td>= pression maximale <math>p_m - 0,5 \text{ bar}</math></td>
<td>(att. à <math>\Delta p</math> entre pointzéro et chaudière, s.i. d'une différence de hauteur ou d'un circulateur présent p.ex.; prendre en compte la différence entre <math>p_m</math> et <math>p_i</math>)</td>
</tr>
<tr>
<td></td>
<td><math>= 3 \text{ [bar]} - 0,5 \text{ bar}</math></td>
<td><math>= 2,5 \text{ [bar]} = p_i</math></td>
</tr>
<tr>
<td>Rendement de volume</td>
<td><math>= \frac{(p_i+1)-(p_g+1)}{(p_i+1)} = \frac{(2,5+1)-(1,3+1)}{(2,5+1)} = 0,343 = F_p</math></td>
<td></td>
</tr>
<tr>
<td>Volume Total Théorique</td>
<td><math>= \frac{\text{VOLUME NET } V_n}{\text{rendement volume } F_p} = \frac{91}{0,343} = 265 \text{ [l]} = V_{tr}</math></td>
<td></td>
</tr>
</table>

### CHOIX DU MATERIEL:

<table border="0">
<tr>
<td>Volume Total Réel</td>
<td>1 x vase d'expansion type</td>
<td>300</td>
<td><math>= V_{tr}</math></td>
</tr>
<tr>
<td>Réserve réelle</td>
<td><math>= (V_{tr} \times F_p) - V_{ep} = (300 \times 0,343) - 71 = 32</math></td>
<td>[l]</td>
<td><math>= R_r</math></td>
</tr>
<tr>
<td>Pression initiale</td>
<td><math>= \frac{V_{tr} \times (p_g + 1)}{V_{tr} - R_r} - 1 = \frac{300 \times (1,3 + 1)}{300 - 32} - 1 = 1,6</math></td>
<td>[bar]</td>
<td><math>= p_i</math></td>
</tr>
</table>
