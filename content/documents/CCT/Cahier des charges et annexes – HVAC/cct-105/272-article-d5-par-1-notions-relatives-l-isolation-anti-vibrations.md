---
type: document-section
document_id: cct-105
section_id: doc105-tech-0250
ordre_document: 272
titre: ARTICLE D5. PAR. 1. NOTIONS RELATIVES L’ISOLATION ANTI VIBRATIONS
aliases:
  - CCT 105 — HVAC FR 2023 — 272 ARTICLE D5. PAR. 1. NOTIONS RELATIVES L’ISOLATION ANTI VIBRATIONS
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/index|CCT 105 — HVAC FR 2023 — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/271-article-d5-specifications-pour-l-isolation-anti-vibrations|ARTICLE D5. SPECIFICATIONS POUR L’ISOLATION ANTI VIBRATIONS]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/cct-105/273-article-d5-par-2-isolateurs-de-vibrations|ARTICLE D5. PAR. 2. ISOLATEURS DE VIBRATIONS]]"
tags:
  - document-section
  - cct-105
  - hvac
sources:
  - 272_article_d5._par._1._notions_relatives_lisolation_anti-vibrations.md
created: 2026-04-28
updated: 2026-04-28
contextes:
  - appel-doffres
  - execution-projet
  - technique
autorite:
  - contractuel
juridictions:
  - belgique
familles_sources:
  - contrat
---

#### ARTICLE D5. PAR. 1. NOTIONS RELATIVES L’ISOLATION ANTIVIBRATIONS 

**1. Définitions, grandeurs, symboles** 

- f n: fréquence propre, à savoir la fréquence propre du système (machine + isolateurs de vibrations)(Hz) 

- f e: fréquence d’excitation, à savoir la fréquence de la source de vibrations (machine)(Hz) 

_vitesse de rotation machine_ ( _t_ / min) = _fe_ 60 

- ω = 2πf : pulsation (rad/s) 

- f vl : la fréquence de résonance de la dalle de sol portante (Hz) 

- G : le poids ou la force statique sur le système d’isolation (système à ressort)  (N) 

- M : masse (masse à isoler) (kg) 

- T : transmittance ou facteur de transmission 

T désigne le rapport de la force transmise à la fondation (F) par rapport à la force générée par la machine (puisque F = M x a, T correspond également au rapport des accélérations) 

- η : rendement d’isolation ou pouvoir d’isolation η = 100 (1-T) 

- δst : affaissement statique du ressort (mm) 

- k : constante de ressort ou rigidité du ressort (N/m) 

- C : constante d’amortissement ou coefficient de résistance (Ns/m) 

- D : facteur d’amortissement (sans dimension) 


![](documents/CCT/Cahier%20des%20charges%20et%20annexes%20–%20HVAC/cct-105/images/CCT105TB_FR_2023.pdf-0729-17.png)


**----- Start of picture text -----**<br>
C<br>D =<br>4 kM<br>**----- End of picture text -----**<br>


**2. Formules de base** 

a. Isolateurs sans amortissement interne (ressorts en acier, laine minérale...) 

1 _k_ = _f n_ 2 π _M_ 15,8 = _[f] n_ δ _st_

![](documents/CCT/Cahier%20des%20charges%20et%20annexes%20–%20HVAC/cct-105/images/CCT105TB_FR_2023.pdf-0730-01.png)


**----- Start of picture text -----**<br>
1<br>T = 2 2<br>[ 1 − ( f e / f n ) ]<br>**----- End of picture text -----**<br>


Ce qui pour les fréquences supérieures à fn  peut se simplifier comme suit : 


![](documents/CCT/Cahier%20des%20charges%20et%20annexes%20–%20HVAC/cct-105/images/CCT105TB_FR_2023.pdf-0730-03.png)


Pour une fréquence d’excitation donnée, on remarque également la relation univoque entre l’affaissement statique δst (= (15,8/fn)[2] ) et le rendement d’isolation, indépendamment du poids (M) de la machine (mais le poids détermine la rigidité requise des ressorts k = (2πfn)[2] M). L’affaissement statique est donc une bonne mesure pour évaluer le rendement d’isolation. 

b. Isolateurs à amortissement interne (caoutchouc, liège) 


![](documents/CCT/Cahier%20des%20charges%20et%20annexes%20–%20HVAC/cct-105/images/CCT105TB_FR_2023.pdf-0730-06.png)


A noter que lorsque le facteur d’amortissement D = 0, l’on retrouve la formule pour les ressorts en acier. 

**3. Niveau de vibration et rendement d’isolation** 

Le niveau de vibration peut s’exprimer en tant que niveau d’accélération et/ou niveau de vitesse. 

Pour le niveau d’accélération : 

La = 20 log a/a0   (dB), le niveau de référence étant : a0 = 1 x 10[ –6] m/s²  = 10[ –3] mm/s² 

Pour le niveau de vitesse : 

Lv = 20 log v/v0    (dB), le niveau de référence étant : v0 = 1 x 10[ –9] m/s  = 10[ –6] mm/s 

Lorsqu’il est question d’un écart de niveau d’accélération en dB, la formule suivante peut s’appliquer : 20 log (1/T) = écart de niveau d’accélération en dB. 

**4. Mise en série d’isolateurs de vibrations** 

Comme la dalle de sol portante n’est jamais infiniment rigide, il est en pratique toujours question de montage en série d’isolateurs de vibrations. Une dalle de sol portante peut en effet en termes de vibrations être considérée comme une dalle infiniment rigide, supportée par des isolateurs de vibrations (ressorts).  Ces isolateurs de vibrations (ressorts) sont alors montés « en série » avec les isolateurs de vibrations proprement dits sous la machine. 

Afin d’éviter que la dalle de sol soit le ressort le plus faible et encaisse donc la plupart des vibrations, la fréquence propre de l’isolateur de vibrations directement sous la source de vibrations doit être inférieure à la moitié de la fréquence de résonance de la dalle de sol portante.

Pour les fréquences de résonance d’une dalle de sol en béton _**de masse surfacique d’au moins 200 kg/m²**_ , les valeurs approximatives suivantes peuvent s'appliquer en fonction de la portée (= la plus petite dimension entre deux poutres ou points d’appui de la dalle de sol) : 

|Portée en mètres|Fréquence de résonance<br>présumée Hz|
|---|---|
|3<br>6<br>9<br>12<br>15<br>18|11 à 14<br>8 à 10<br>6 à 8<br>5,5 à 7<br>5 à 6,5<br>4,5 à 6|



Pour d’autres types de constructions de sol (bois, acier, béton de masse surfacique < 200 kg/m²) le tableau ci-dessus ne s’applique pas et la fréquence de résonance doit être calculée cas par cas. 

**5. Bloc d’inertie** 

Le bloc d’inertie est une dalle en béton sur lequel la machine est fixée; entre le bloc d’inertie et la structure portante (dalle de sol) des isolateurs de vibrations sont prévus. 

Le bloc d’inertie a pour but: 

- de limiter le déplacement de la machine sous l’effet des vibrations 

- de limiter l’écartement de la machine suite aux forces internes et externes (par ex. pression de ventilateur, action du vent), sans détérioration du rendement d’isolation ƞ: vu le poids plus important de l’ensemble machine + bloc d’inertie, on peut prévoir des isolateurs de vibrations avec une rigidité (k) plus importante (voir formules pour ƞ, T et fn) 

- de maintenir au plus bas le centre de gravité de l’ensemble machine + bloc d’inertie 

Si le cahier spécial des charges ne stipule pas la masse requise pour le bloc d’inertie, la masse doit au moins être égale à la masse de la machine opérationnelle : machine + remplissage (liquide dans les tuyauteries de raccordement dans le cas d’une pompe).
