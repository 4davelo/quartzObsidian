---
type: document-section
document_id: note-cti-hvac-sapc17-vase-expansion
section_id: section:appendice-b
ordre_document: 7
titre: APPENDICE B
aliases:
  - Note CTI HVAC SAPC17 — Vases d'expansion — 07 APPENDICE B
resume_section: |-
  **APPENDICE B :**

  - Respecter le NPSH d'une pompe de circulation pour éviter la cavitation : la pression d'aspiration ($P_{circ}$) doit toujours dépasser le NPSH.
  - Maintenir la pression de service minimale d'une chaudière pour éviter des conditions anormales (bouillonnement, bruits, dommages) : la pression à la chaudière ($P_{ch}$) doit rester supérieure à cette valeur.

  Ces exigences sont cruciales pour les installations à basse pression, comme celles en toiture ou à un seul niveau, où la colonne d'eau ($p_h$) est nulle. Dans ces cas, la pression de gonflement ($p_g$ ou $p_i$) peut être de 0,5 bar si la pression restante est suffisante. Sinon, une pression plus élevée est nécessaire.

  Formules :
  - $p_g \geq p_{circ} \pm \Delta p(\text{pointzéro-circ})$
  - $p_g \geq p_{ch} \pm \Delta p(\text{pointzéro-ch})$

  Un schéma illustre la disposition du système (pompe, chaudière, vase d'expansion) et les pertes de pression ($\Delta p$).
document_parent: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/index|Note CTI HVAC SAPC17 — Vases d'expansion — Index]]"
section_precedente: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/06-appendice-a|APPENDICE A]]"
section_suivante: "[[documents/CCT/Cahier des charges et annexes – HVAC/note-cti-hvac-sapc17-vase-expansion/08-appendice-c|APPENDICE C]]"
tags:
  - document-section
  - cti
  - hvac
sources:
  - 07_appendice-b_appendice_b.md
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

APPENDICE B:

- - Il convient de respecter le NPSH (Net Positive Suction Height = hauteur d'aspiration nette) d'une pompe de circulation pour éviter des phénomènes de cavitation. La pression au droit du côté aspiration d'une pompe de circulation ( $P_{circ}$ ) doit donc à tout moment être supérieure à la valeur NPSH.
- - Il convient de respecter la pression de service minimale d'une chaudière pour éviter que la chaudière ne soit exposée à des conditions de fonctionnement anormales. En effet, la température de la paroi de chaudière du côté du foyer est beaucoup plus élevée que la température de départ de l'eau vers l'installation. Si la pression est trop basse dans la chaudière, des phénomènes de bouillonnement peuvent se produire localement avec, comme conséquence directe, des bruits de chaudière et, indirectement, des dégâts à la chaudière. La pression à hauteur de la chaudière ( $P_{ch}$ ) doit donc à tout moment être supérieure à la pression de service minimale de celle-ci.

Ces prescriptions sont évidemment surtout importantes pour les installations où la chaudière et la pompe de circulation peuvent fonctionner à basse pression. Un exemple typique de ce genre d'installations sont lesdites installations en toiture ou les systèmes à un seul niveau. Etant donné que la colonne d'eau ( $p_h$ ) est égale à 0 dans de tels systèmes, la pression de gonflement ( $p_g$ ) du système d'expansion ne devrait normalement s'élever qu'à 0,5 bar (idem pour  $p_i$ , en cas de système d'expansion à pression constante)

Si la pression restante à hauteur de la chaudière ou de la pompe de circulation est suffisamment élevée, la valeur 0,5 bar peut suffire pour  $p_g$  (ou  $p_i$ ).

Si ce n'est pas le cas, il faudra choisir une pression proportionnellement plus élevée pour  $p_g$  (ou  $p_i$ ).

$$p_g \geq p_{circ} \pm \Delta p(\text{pointzéro-circ})$$

(voir, p. ex., l'appendice E 4)

$$p_g \geq p_{ch} \pm \Delta p(\text{pointzéro-ch})$$

(voir, p. ex., l'appendice E 3)

The diagram illustrates a heating system layout. A pump (represented by a circle with a triangle) is connected to a boiler (represented by a rectangle). An expansion tank (represented by a circle with a wavy line) is also connected to the system. A vertical dashed line extends from the pump's suction point up to the top of the boiler, labeled  $\Delta p(\text{pointzéro-circ})$ . Another vertical dashed line extends from the top of the boiler up to the top of the expansion tank, labeled  $\Delta p(\text{pointzéro-ch})$ . A horizontal dimension line at the bottom indicates the distance between the pump and the expansion tank, also labeled  $\Delta p(\text{pointzéro-circ})$ .
