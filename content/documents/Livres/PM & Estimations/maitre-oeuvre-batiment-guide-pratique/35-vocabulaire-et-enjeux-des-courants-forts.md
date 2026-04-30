---
type: document-section
document_id: maitre-oeuvre-batiment-guide-pratique
section_id: "section:2"
ordre_document: 35
titre: "vocabulaire et enjeux des courants forts"
aliases:
  - Maître d'oeuvre bâtiment — Hamburger 2023 — 35 vocabulaire et enjeux des courants forts
resume_section: |-
  ### Vocabulaire et enjeux des courants forts
  
  #### Locaux ATEX et risques d'explosion
  - Les locaux ATEX (atmosphères explosives) dans les bâtiments industriels doivent respecter des normes spécifiques pour prévenir les explosions, conformément aux directives européennes.
  - La construction près de sites industriels à risque d'explosion nécessite une expertise structurelle et le respect des prescriptions des PPRT et PLU.
  
  #### Électricité : tensions et points de livraison
  - Classification des tensions : TBT (<50 V), BTA (50-500 V), BTB (500-1 000 V), HTA (1-50 kV), HTB (>50 kV). Le terme "moyenne tension" est obsolète.
  - Points de livraison Enedis : puissance limitée (≤36 kVA, ex-tarif bleu), surveillée (36-250 kVA, ex-tarif jaune), haute tension (>250 kVA, ex-tarif vert).
  
  #### Installations électriques
  - Les tableaux divisionnaires distribuent l'énergie dans les bâtiments. Ils peuvent être alimentés par un point de livraison Enedis ou un TGBT (tableau général basse tension).
  - Les TGBT alimentent les tableaux divisionnaires et équipements lourds (ascenseurs, CVC). Dans les grands bâtiments, des armoires principales peuvent s'intercaler.
  
  #### Haute tension et postes privatifs
  - Les postes HT privatisés transforment la haute tension (HTA) en basse tension pour alimenter les bâtiments. Ils incluent des cellules HT, transformateurs et TGBT.
  - Les régimes de neutre (TT, TN, IT) définissent les connexions à la terre et influencent la conception des installations.
  
  #### Réglementation et sécurité
  - Normes clés : NF C13-100 (postes HT), NF C15-100 (basse tension), NF C14-100 (branchements Enedis).
  - Concepts de sécurité : sources normales, de remplacement et de sécurité (AES). Le TGS regroupe les alimentations de sécurité incendie.
  - Vérifications obligatoires : conformité initiale (Consuel) et vérifications périodiques.
  
  #### Éclairage
  - Critères : température de couleur (K), IRC (rendu des couleurs), flux lumineux (lm), efficacité (lm/W), éclairement (lx).
  - Sources lumineuses : LED (dominantes), lampes à décharges (fluorescentes, sodium, iodures métalliques).
  - Réglementations : niveaux d'éclairement selon les usages (ERP, ERT), optimisation de la lumière naturelle, automatismes (détecteurs, horloges).
  
  #### Sécurité des luminaires
  - Normes : NF EN 60598, indices IP (poussières, humidité) et IK (chocs).
  - Tests spécifiques : résistance au feu (fil incandescent).
  
  #### Points clés
  - Collaboration entre spécialités (CVC, courants forts) est essentielle pour répondre aux exigences réglementaires et techniques.
  - Les automatismes et la conception fine des installations permettent d'optimiser la sécurité, l'efficacité énergétique et le confort.
document_parent: "[[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/index|Maître d'oeuvre bâtiment — Hamburger 2023 — Index]]"
section_precedente: "[[34-vocabulaire-du-lot-structure|vocabulaire du lot structure]]"
section_suivante: "[[36-vocabulaire-et-enjeux-des-courants-faibles|vocabulaire et enjeux des courants faibles]]"
tags: [document-section, ouvrage, gestion-projet, maitrise-oeuvre, estimation]
sources: ["35_2._vocabulaire_et_enjeux_des_courants_forts.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [appel-doffres, execution-projet, technique]
autorite: [pratique, reference]
juridictions: [france, generique]
familles_sources: [ouvrage, gestion-projet]
---
### 2 vocabulaire et enjeux des courants forts

#### 1.10.1. Conception des locaux ATEX dans les établissements industriels 

Le sigle ATEX désigne ici les _atmosphères explosives_ . La _réglementation ATEX_ , issue de deux directives européennes, exige de maîtriser les risques d’explosion dans un établissement. Le programme d’un bâtiment industriel peut comporter des _locaux ATEX_ , avec des exigences particulières impactant les modes de construction. 

#### 1.10.2. Construire aux abords des sites industriels avec risque d’explosion 

La construction d’un bâtiment aux abords d’un site industriel présentant un risque d’explosion peut aussi nécessiter une expertise Structure. Un plan de prévention des risques technologiques (PPRT), auquel le PLU fait référence, fournit alors les prescriptions à respecter par les bâtiments dans la zone concernée. 

Les structures peuvent nécessiter un renforcement dans cette zone. Le plan du bâtiment et les lots de second œuvre sont aussi impactés par les prescriptions. 

**Pour en savoir plus sur le risque explosion** 

Consulter le site de l’Inspection des installations classées : www.ins​ tal​ lat​ ion​ scl​ ​ ass​ees.dev​ elo​ ppe​ ment-​ dur​ able.​ go​ uv.​ fr​ . Consulter le site de l’INERIS. 

Le domaine des Fluides, abordé dans les pages suivantes, regroupe principalement l’électricité courants forts et courants faibles et la CVC Plomberie. 

On rencontre aussi le terme anglais MEP : _mechanical_ , _electrical and plumbing_ ( _mechanical_ désignant ici les équipements techniques CVC).

Le domaine de l’électricité se décompose en deux spécialités : les courants forts et les courants faibles. Les courants forts servent à transporter de l’énergie électrique, contrairement aux courants faibles qui servent à transporter de l’information.[[16](98_16._les_assurances_en_phase_chantier.md)] L’objectif du présent chapitre est de donner quelques notions de base en courants forts qui permettront de dialoguer avec un BET électrique et de comprendre les enjeux des études courants forts, notamment dans leur lien avec les autres spécialités. 

## 2.1. Les domaines de tension, en courant alternatif 

Jusqu’à 50 V on parle de très basse tension (TBT), communément appelée « courants faibles ». De 50 à 500 V, on parle de basse tension A (BTA). De 500 à [1](83_1._le_nettoyage_de_fin_de_chantier.md) 000 V, on parle de basse tension B (BTB). De 1 kV à 50 kV, on parle de haute tension A (HTA). Au-delà de 50 kV, on parle de haute tension B (HTB). 

Le terme « moyenne tension » n’existe plus officiellement et ne doit donc plus être utilisé. 

Dans la plupart des installations électriques, l’origine de l’alimentation est un point de livraison Enedis. Concernant ces points de livraison, quelles sont les différentes situations susceptibles d’être rencontrées ? 

## 2.2. Connaître les puissances limites des points de livraison Enedis[17] 

- Jusqu’à 36 kVA compris, on parle d’un branchement à puissance limitée, anciennement appelé _« tarif bleu »_ ; la norme définit deux types de branchements[[18](100_18._après_la_réception_le_suivi_des_performances_énergétiques.md)] :

**on parle de branchement de type [1](83_1._le_nettoyage_de_fin_de_chantier.md) ;** 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0511-01.png]]

Figure 99. Branchement individuel de type1 à puissance limitée (d’après la norme NF C14-100). 

- si le point de livraison se situe en dehors des locaux de l’utilisateur (par exemple habitation individuelle avec compteur en limite de parcelle), on parle de branchement de type 2 ;

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0511-04.png]]

Figure 100. Branchement individuel de type 2 à puissance limitée (d’après la norme NF C14-100).

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0512-00.png]]

Figure 101. Exemples de compteurs de branchements à puissance limitée (ex-tarif bleu). 

- de 36 à 250 kVA, on parle d’un branchement à puissance surveillée, anciennement _« tarif jaune »_ ; 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0512-03.png]]

Figure 102. Branchement à puissance surveillée (d’après la norme NF C14-100).

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0513-00.png]]

Figure 103. Exemple de compteur de branchement à puissance surveillée (ex-tarif jaune). 

- à partir de 250 kVA, on parle de point de livraison haute tension, anciennement _« tarif vert »_ .[[19](101_19._le_commissioning.md)] 

On rencontre par exemple des tarifs verts dans les immeubles tertiaires, dans les grands restaurants, dans les centres commerciaux.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0514-00.png]]

Figure 104. Exemple de compteur pour point de livraison haute tension (ex-tarif vert, l’étiquette en façade est verte). 

## 2.3. Les installations – Les configurations courantes 

Quelles sont les principales installations électriques courants forts présentes dans un bâtiment ? Quel est leur rôle dans le réseau électrique du bâtiment ? Quelles sont les différentes configurations (on parle de _« synoptique »_ ) d’installations électriques susceptibles d’être rencontrées ? 

**Dans tous les cas, on trouvera :** 

- un (voire plusieurs) tableau divisionnaire (encore appelé tableau électrique, ou tableau basse tension, ou tableau de distribution, ou armoire électrique, ou tableau de répartition, ou encore coffret de distribution s’il est de petite taille). Le tableau divisionnaire regroupe l’ensemble des protections (les disjoncteurs) alimentant une zone. Un tableau peut aussi être dédié aux alimentations de certains équipements particuliers (par exemple armoire électrique dédiée aux équipements CVC). Outre les protections, les tableaux électriques peuvent comporter

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0515-01.png]]

Figure 105. Un exemple de tableau divisionnaire. 

- la distribution terminale, constituée par l’ensemble de tous les câbles allant du tableau divisionnaire aux équipements à alimenter (appareils d’éclairage, prises électriques, etc.). 

Suivant le cas, il existe deux types d’alimentation pour les tableaux de distribution.

- Premier cas, les tableaux divisionnaires sont alimentés par un point de livraison Enedis, avec un compteur. Cette configuration se rencontre par exemple pour un appartement, une maison individuelle, un petit bâtiment tertiaire, un petit commerce. Exemple : cette maison individuelle est équipée d’un unique tableau divisionnaire, alimenté par un branchement Enedis à puissance limitée ; en amont, l’alimentation Enedis provient d’un poste de distribution publique (poste haute tension Enedis) située dans le quartier.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0516-00.png]]

Figure 106. Exemple d’une maison individuelle. 

Dans un immeuble abritant plusieurs occupants, qu’il s’agisse d’habitation ou de bureaux, la configuration est analogue : Enedis assure la distribution à travers les parties communes jusqu’au compteur individuel (branchement) de chaque occupant.

- Deuxième cas, les tableaux divisionnaires sont alimentés par un TGBT (tableau général basse tension) qui alimente plusieurs tableaux divisionnaires, et qui peut aussi alimenter directement certains gros équipements : ascenseurs, escaliers mécaniques, moteurs de désenfumage dans certains cas.[20] Un TGBT regroupe les protections de départs alimentant les tableaux divisionnaires. 

**Point de vigilance** 

Il arrive qu’on appelle « TGBT » par abus de langage un simple tableau divisionnaire basse tension. Dans un bâtiment comportant un TGBT et des tableaux divisionnaires, seul mérite véritablement le terme de TGBT le tableau situé au sommet de l’architecture basse tension du bâtiment et alimentant différents tableaux divisionnaires. 

_Nota :_ dans certains grands bâtiments existants, entre les tableaux de distribution et le TGBT viennent s’insérer une strate supplémentaire, les armoires principales. Ces armoires principales sont alimentées par le TGBT et alimentent les tableaux divisionnaires, qu’on nomme alors parfois « armoires secondaires ».

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0517-00.png]]

Figure 107. Un exemple de TGBT. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0517-02.png]]

Figure 108. Un exemple de TGBT d’une ancienne génération. 

**En amont, d’où peut être alimenté ce TGBT ?** Il peut lui-même être alimenté :

- par un point de livraison Enedis basse tension (avec un compteur) ; on peut par exemple rencontrer cette configuration dans un petit bâtiment tertiaire, un commerce de moyenne surface, un petit hôtel.

Exemple : le petit immeuble de bureau de la Figure 109 comporte un TGBT qui alimente les tableaux divisionnaires situés à chaque étage, ainsi que l’ascenseur et un tableau dédié aux installations CVC ; ce TGBT est alimenté par un branchement Enedis à puissance surveillée ; en amont, ce branchement est alimenté par Enedis depuis un poste de distribution publique situé dans le quartier ; 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0518-01.png]]

Figure 109. Exemple d’un petit bâtiment de bureau. 

- ou par un poste haute tension privé, c’est-à-dire n’appartenant pas à Enedis mais au propriétaire du bâtiment. C’est le cas si le bâtiment nécessite plus de 250 kVA comme vu ci-dessus. Dans ce dernier cas, le poste haute tension privé est :

  - soit dans le cas général alimenté en haute tension par un point de livraison Enedis haute tension. Le poste Enedis origine de l’alimentation peut être situé :

  - dans un local Enedis attenant au poste privatif ;

  - ou dans le même local, derrière un grillage, on parle alors de poste mixte ou de poste partagé (ce cas se rencontre dans l’existant, mais pas dans le neuf) ;

  - ou dans le quartier. 

On peut par exemple trouver cette configuration avec poste haute tension privé dans un grand immeuble tertiaire, une usine, une clinique, un restaurant, un grand magasin. Exemple : le grand magasin de la Figure 110 possède un TGBT qui alimente l’ensemble de ses tableaux divisionnaires, de ses ascenseurs, de ses escaliers mécaniques et ses armoires CVC ; il possède aussi un poste HT privatif, qui alimente le TGBT ; ce poste comporte un point de livraison Enedis haute tension ; en amont, l’alimentation Enedis provient d’un poste de distribution publique que Enedis possédait dans le quartier (variante : le projet a dû intégrer un local pour accueillir le poste Enedis à côté du poste privatif) ; 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0519-02.png]]

Figure 110. Exemple d’un grand magasin.

alimenté par d’autres postes haute tension appartenant au même propriétaire. Un poste haute tension privatif peut être alimenté par un autre poste HT privatif de deux manières :

- en antenne ;

- en boucle ou en coupure d’artère. On peut rencontrer typiquement une boucle haute tension reliant les différents postes haute tension du site. Cette boucle facilite la maintenance en permettant la continuité d’exploitation lors d’un incident ou d’une opération de maintenance sur un câble. Cette configuration se rencontre par exemple dans un grand hôpital comportant plusieurs bâtiments, un site industriel, un aéroport. Exemple : ce site industriel comportant quatre bâtiments est alimenté par un point de livraison Enedis haute tension ; le site comporte quatre postes HT privatifs raccordés en boucle ; chaque poste HT privatif alimente un TGBT réservé à un bâtiment et alimentant les tableaux divisionnaires et les gros équipements de ce bâtiment.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0520-01.png]]

## 2.4. Le domaine de la haute tension 

### 2.4.1. Le réseau public de distribution 

Pour éviter les pertes d’énergie en ligne, le courant électrique est transporté à très haute tension (225 kV, 90 kV ou 63 kV) ; en France, c’est l’organisme RTE[21] qui assure ce transport. La tension est ensuite abaissée afin de permettre son utilisation. Si le courant était transporté sur de grandes distances à des tensions inférieures, les pertes en ligne par effet Joule seraient beaucoup trop importantes. Il faut cependant savoir que ces pertes en ligne sont déjà considérables, ce qui milite pour le développement des énergies renouvelables produites localement.[22] 

Afin de permettre le transport de l’électricité, des transformateurs sont disposés à la sortie des centrales de production, pour augmenter la tension. Inversement, la tension est abaissée par plusieurs transformateurs successifs pour permettre son utilisation par les différents types de clients. Le terme _« poste de distribution publique »_ désigne le poste Enedis qui alimente les clients. 

**Pour en savoir plus sur les postes de distribution publique** 

On peut consulter sur [www.enedis.fr](http://www.enedis.fr) les fiches SEQUELEC _Guide pratique à l’usage des maîtres d’ouvrage de construction

- Réalisation de postes HTA/BT de distribution publique_ .

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0522-00.png]]

Figure 112. Structure du réseau public de distribution. 

Comme on l’a vu ci-dessus, suivant la puissance nécessaire, un bâtiment sera alimenté par un branchement basse tension ou par un point de livraison haute tension. Dans ce second cas, le bâtiment comportera – en aval du point de livraison haute tension – des installations haute tension privatives, qui vont abaisser la tension pour permettre son utilisation. La haute tension utilisée dans les bâtiments s’appelle HTA – l’ancienne dénomination « moyenne tension » n’est plus officielle –, dénomination qui couvre le domaine allant de [1](83_1._le_nettoyage_de_fin_de_chantier.md) kV à 50 kV en courant alternatif.[23] La tension la plus usuelle de livraison Enedis est le 20 kV, mais il existe d’autres cas, par exemple 15 kV. 

**2.4.2. Que trouve-t-on dans un poste haute tension privatif ?** Un poste HT dans un bâtiment est constitué principalement des équipements suivants :

- des cellules HT (encore appelées tableaux HT) : ce sont des appareils qui assurent l’interface entre un câble HT et un appareillage. Elles permettent par exemple de raccorder des câbles HT entre eux, de réaliser un comptage, de raccorder un disjoncteur, d’assurer le rôle

d’interrupteur, de raccorder un transformateur, etc. – c’est un petit peu à la haute tension ce que la boîte de raccordement est à la basse tension. Alors que les anciennes cellules HT étaient « à coupure dans l’air » ou utilisaient de l’huile comme diélectrique, de nos jours elles utilisent comme diélectrique le gaz SF6 (hexafluoride), bien plus isolant que l’air. Pour éviter les manœuvres intempestives, les cellules HT peuvent comporter des enclenchements par clés. Les cellules sont accolées les unes aux autres dans le poste ; 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0523-01.png]]

Figure 113. Exemple d’un ensemble de cellules haute tension.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0524-00.png]]

Figure 114. Deuxième exemple de cellules haute tension. 

- un ou des transformateurs : alimentés depuis les cellules HT, ils abaissent la tension et alimentent ainsi le TGBT. Les transformateurs sont représentés sur les schémas électriques par le symbole : 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0524-03.png]]

Le dimensionnement d’un transformateur est donné en kVA.

- un (ou des) tableau général basse tension (TGBT) : comme on l’a vu, cette armoire est alimentée en basse tension par le transformateur, et alimente elle-même les tableaux divisionnaires répartis dans tout le bâtiment. Il peut aussi arriver que le TGBT ne soit pas situé dans le local du poste HT, mais dans un local séparé, ce qui permet à un électricien habilité seulement en basse tension d’accéder au local TGBT.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0525-00.png]]

Figure 115. Exemple de transformateur HT/BT. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0525-02.png]]

Figure 116. Troisième exemple de TGBT (ici, une ancienne génération de matériel). 

On peut aussi trouver dans un poste HT d’autres installations :

- un tarif vert Enedis, point de livraison haute tension, si le poste privatif est directement alimenté par Enedis ;

- une ventilation mécanique, si la ventilation naturelle – toujours préférable – n’a pu être mise en œuvre ;

- un PASA, c’est-à-dire un permutateur automatique de sources d’alimentations ; cette unité électronique assure automatiquement le basculement d’une source d’alimentation HT à une autre ;

- un raccordement à une GTB, ou à un autre dispositif de télésurveillance ;

- des équipements Enedis si le poste est mixte ou partagé : il existe en effet dans l’existant des postes HT séparés entre une partie appartenant à Enedis et une partie privative (cette situation est cependant interdite par Enedis dans le neuf). Les postes haute tension sont aussi appelés « HT/BT », pour désigner le fait qu’ils transforment la haute tension en basse tension. 

**Pour en savoir plus sur la haute tension** 

Consulter la norme NF C13-100 et la norme NF C13-200. Consulter les sites Internet de fabricants, comme [www.schneider-electric.fr](http://www.schneider-electric.fr), [www.abb.fr](http://www.abb.fr) (produit : Uniswitch par exemple) ou [www.ormazabal.fr](http://www.ormazabal.fr) 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0526-03.png]]

Figure 117. Exemple de poste HT mixte : partie Enedis à gauche et partie privative à droite.

Dans le domaine des courants forts, les normes sont des textes de référence fondamentaux auxquels les concepteurs se réfèrent constamment, plus encore que dans les autres spécialités (sauf le domaine des SSI, où les normes ont aussi un rôle prépondérant). Les principales normes utilisées pour la conception des installations courants forts dans les bâtiments sont : 

- pour le domaine des postes HT privatifs, les normes :

  - NF C13-100 _Poste de livraison établis à l’intérieur d’un bâtiment et alimentés par un réseau de distribution publique HTA_ ,

  - et NF C13-200 _Installations électriques à haute tension – Règles complémentaires pour les sites de production et les installations industrielles, tertiaires et agricoles_ ;

- pour la basse tension privative, la norme NF C15-100 _Installations électriques à basse tension_ , texte de base pour tout électricien ; cette norme était souvent critiquée par les professionnels du fait de la lourdeur de ses exigences ; dans le cadre des mesures de simplification des normes de construction, une petite révolution a eu lieu en 2016[24] : cette norme n’est maintenant plus applicable intégralement aux bâtiments d’habitation, seules les exigences relevant de la sécurité électrique et du bon fonctionnement sont exigibles, alors que les exigences relevant davantage du confort (par exemple le nombre de prises par pièce) ne sont maintenant plus exigibles ; 

**

- la norme NF C14-100 _Installation de branchement à basse tension_ pour les branchements basse tension Enedis, du point de raccordement au réseau Enedis jusqu’au point de livraison aux utilisateurs ; on y trouve notamment les directives pour la conception des branchements collectifs en habitation, ainsi que les directives pour le raccordement des installations photovoltaïques ; 

- la norme NF C17-200 _Installations d’éclairage extérieur – Règles_ pour les installations d’éclairage public extérieur ; elle concerne donc surtout la partie éclairage des études VRD.

Ces normes sont émises pour la France par l’UTE (Union technique de l’électricité), l’équivalent de l’Afnor pour le domaine électrique. 

## 2.6. Quelques concepts clés pour comprendre les études courants forts 

### 2.6.1. Concepts fondamentaux liés à la réglementation incendie 

Il est d’autant plus important de bien maîtriser ces concepts qu’ils sont couramment utilisés de manière abusive, avec des risques de confusion et de malentendu. Ainsi en est-il du concept de source de sécurité, souvent utilisé à tort pour désigner une source de remplacement, ce qui n’a rien à voir. 

**Source normale** 

Source constituée généralement par un raccordement au réseau électrique de distribution publique haute tension ou basse tension.[25] 

**Source de remplacement** 

Source délivrant l’énergie électrique permettant de poursuivre tout ou partie de l’exploitation de l’établissement en cas de défaillance de la source normale. Durant la période d’exploitation de l’établissement, l’énergie électrique provient soit de la source normale, soit de la source de remplacement (si cette dernière existe). Cet ensemble est appelé « source normal-remplacement ». 

**Source de sécurité** 

Source prévue pour maintenir le fonctionnement des matériels concourant à la sécurité contre les risques d’incendie et de panique en cas de défaillance de la source « normal-remplacement ».

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0529-00.png]]

**Alimentation normale** 

C’est l’alimentation électrique qui provient de la source normale, c’est-àdire qui ne provient pas d’une source de sécurité. 

**Alimentation de remplacement** 

C’est l’alimentation qui provient de la source de remplacement, source prévue pour permettre la continuité d’exploitation en cas de défaillance de la source normale. Ce qui est important dans cette notion, c’est que la source de remplacement alimente des équipements qui ne participent pas à la sécurité incendie, ce qui ne veut pas dire qu’ils ne sont pas importants. Ainsi dans un aéroport les panneaux d’affichage des avions au départ, ou dans un commerce les caisses, sont des équipements fondamentaux, mais qui ne relèvent pas de la sécurité incendie. On ne doit pas, pour des équipements de ce type, parler d’alimentation de sécurité.[26] Pour caractériser la fiabilité d’une installation dans le cadre de la conception d’une alimentation de remplacement, on utilise parfois les concepts suivants :

- temps moyen entre pannes (en anglais MTBF – _mean time between failures_ ),

- et moyenne des temps de réparation (en anglais MTTR – _mean time to repair_ ). 

**Alimentation électrique de sécurité (AES)** 

En électricité, le terme de « sécurité » doit être compris comme signifiant « sécurité incendie ». L’AES est la source qui fournit l’énergie électrique nécessaire au fonctionnement des installations concourant à la sécurité incendie (installations « de sécurité »). L’AES permet à ces installations d’assurer leur fonction aussi bien en marche normale, lorsque l’énergie provient de la source normal-remplacement, qu’en marche en sécurité lorsque l’énergie provient de la source de sécurité. Une AES peut par exemple être constituée par un groupe électrogène, ou par un ensemble de batteries.[27] Ces installations de sécurité à alimenter (sauf cas particulier) par AES sont : 

- le désenfumage ;

- les ascenseurs devant être utilisés pour l’évacuation (ce qui est rare) ;

- les secours en eau (sprinklage, surpresseurs de RIA, etc.) ;

- les pompes d’exhaure ;

- les autres équipements, spécifiques à l’établissement, concourant à la sécurité incendie et les moyens de communication destinés à donner l’alerte interne (sonorisation de sécurité par exemple) et externe. Dernière installation de sécurité : l’éclairage de sécurité, qui n’est – contrairement aux autres – pas alimenté par l’AES.[28] 

**Tableau général de sécurité (TGS)** 

Cette notion découle des réglementations ERP[29] et IGH[30] ~~.~~ 

Le tableau général de sécurité regroupe l’alimentation des installations concourant à la sécurité incendie (citée ci-dessus), sauf l’éclairage de sécurité. En pratique, c’est souvent le désenfumage qui constitue l’essentiel des départs du TGS. 

L’important à retenir est que ce TGS doit être installé dans un _local dédié_ et coupe-feu.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0531-00.png]]

Figure 118. Exemple de TGS, dans un local dédié. 

Les articles EL du règlement ERP permettent à l’électricien de déterminer si le projet nécessite un local TGS ou non. Les dérogations, qui consistent à raccorder les installations de sécurité au TGBT en se dispensant d’un TGS, dépendent notamment de la puissance du désenfumage et de la catégorie de l’établissement, on est donc ici face à une problématique qui nécessite une collaboration entre le lot CVC et le lot courants forts. Le règlement précise : 

_« dans les cas où l’absence de groupe électrogène est admise dans la suite du présent règlement, les installations électriques suivantes peuvent être alimentées par une dérivation issue directement du tableau principal du bâtiment ou de l’établissement :_

- _installation de désenfumage mécanique des établissements de [1](83_1._le_nettoyage_de_fin_de_chantier.md)[re] et 2[e] catégories dont la puissance totale des moteurs des ventilateurs d’extraction des deux zones de désenfumage les plus contraignantes est inférieure à 10 kW ;_

- _installation de désenfumage mécanique des établissements de 3[e] et 4[e] catégories ;_

- _les secours en eau et les pompes d’exhaure, sauf dispositions aggravantes prévues dans la suite du présent règlement. »_[31] 

**Éclairage normal** 

C’est l’éclairage alimenté par la source normale, par opposition à l’éclairage de sécurité. 

**Éclairage de sécurité** 

C’est l’éclairage qui est alimenté par une source de sécurité en cas de disparition de la source normale. En temps normal, il doit être à l’état de veille. Il se déclenche en cas de défaillance de la source normale et doit pouvoir fonctionner pendant une heure. 

**Il a deux fonctions :** 

- l’éclairage de sécurité d’évacuation, constitué par les panneaux ou blocs[32] éclairant les cheminements, les changements de direction et les issues de secours. Les indications de balisage ne sont pas forcément des appareils lumineux, elles peuvent être des panneaux opaques éclairés par des blocs situés à proximité et remplissant le rôle d’éclairage de sécurité ;

- l’éclairage de sécurité d’ambiance ou d’anti-panique, qui a pour fonction de donner un niveau minimum d’éclairage. Pour assurer ces deux fonctions, l’éclairage de sécurité est basé sur deux solutions techniques[33] :

- la source centrale composée d’une batterie d’accumulateurs ;

- ou des blocs autonomes, solution la plus courante ; ces blocs disposant de leur propre batterie, ils n’ont pas besoin d’être alimentés par des câbles CR1. 

Attention : dans certaines configurations et grands établissements, le règlement impose la source centrale.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0533-00.png]]

**Figure 119. Exemple de bloc autonome d’éclairage de secours.** 

L’éclairage de sécurité nécessite dans les ERP du premier groupe (catégories [1](83_1._le_nettoyage_de_fin_de_chantier.md) à 4) ainsi qu’en ERT une maintenance assez lourde[34] (vérifications périodiques), qui peut être automatisée avec certains modèles (système SATI, qui réalise automatiquement les tests et représente maintenant 70 % du parc installé). 

Certains fabricants proposent maintenant des appareils d’éclairage normal jouant aussi le rôle d’éclairage de sécurité. En habitation, quand le règlement exige un éclairage de sécurité (voir le chapitre [1](83_1._le_nettoyage_de_fin_de_chantier.md)) on utilise des blocs autonomes d’éclairage de sécurité pour habitation (BAEH), dotés d’une autonomie de 5 h. Cette autonomie longue permet d’assurer un éclairage en cas de panne durant la nuit, jusqu’au dépannage le lendemain. 

**Pour en savoir plus sur l’éclairage de sécurité** 

Pour les ERP du premier groupe, consulter les articles EC7 à EC15 du règlement de sécurité dans les ERP. Pour les ERP de 5[e] catégorie, consulter l’article PE24 et pour ceux avec locaux de sommeil l’article PE36. Pour les ERT, consulter l’arrêté du 14 décembre 2011 relatif aux installations d’éclairage de sécurité. 

### 2.6.2. Un peu de vocabulaire technique en courants forts 

**Les groupes électrogènes** 

Il existe des normes à respecter pour qu’un groupe électrogène soit considéré « de sécurité ». Les groupes électrogènes qui ne respectent pas ces normes n’assurent pas une alimentation concourant à la sécurité incendie (AES), mais une alimentation « de remplacement » (par exemple continuité de fonctionnement de chambres froides, de baies informatiques, etc.).

Penser, lors de la conception, aux cheminées de rejet des gaz et aux procédures de dépotage des carburants. On rencontre couramment des groupes électrogènes dans les hôpitaux. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0534-01.png]]

Figure 120. Exemple de groupes électrogènes de forte puissance. 

**Les onduleurs** 

Comme les groupes électrogènes, les onduleurs peuvent être soit des alimentations électriques de sécurité, soit des alimentations de remplacement. Les systèmes d’alimentation sans interruption (ASI) utilisent des onduleurs.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0535-00.png]]

Figure 121. Quelques exemples d’onduleurs (source : Eaton). 

**Batteries de condensateurs** 

L’ _énergie réactive_ est un phénomène électrique, lié au concept de cosϕ, qui engendre une surconsommation électrique. Les batteries de condensateurs sont des équipements qui permettent, en tarif vert et en tarif jaune, d’optimiser le fonctionnement des installations en compensant ce phénomène d’énergie réactive, sans toutefois le supprimer. La compensation de l’énergie réactive permet donc de diminuer le coût de la facture d’électricité. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0535-04.png]]

Figure 122. Exemple de batterie de condensateurs (source : Legrand). 

**Gaine technique logement (GTL)** 

Dans les logements neufs ou totalement rénovés, tant collectifs qu’individuels, la norme NF C15-100[35] impose que le tableau divisionnaire soit unique et soit implanté dans une « gaine technique logement », dont les caractéristiques, notamment les dimensions et l’altimétrie, sont imposées.

Cette gaine accueille aussi le compteur Enedis et son « disjoncteur d’abonné » (le disjoncteur général de l’installation privative) ainsi que les arrivées courants faibles du logement. 

**Pour en savoir plus** 

Consulter la fiche SEQUELEC sur la gaine technique logement sur [www.enedis.fr](http://www.enedis.fr). Consulter les normes NF C15-100-07 et NF C14-100. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0536-03.png]]

Figure 123. Exemple de gaine technique logement. 

**Schéma unifilaire** 

Ce terme désigne simplement les schémas sur lesquels les câbles sont représentés par un unique trait. 

**Câble CR1 C1** 

Les câbles CR1 C1 sont les câbles résistant au feu. Ils existent en courants forts et en courants faibles. Ils sont utilisés pour l’alimentation des installations de sécurité en ERP[36] ~~,~~ par exemple l’éclairage de sécurité. Ces câbles sont de couleur orange. Leur prix est évidemment supérieur à celui des câbles standards. 

**Canalisations préfabriquées**

La distribution électrique est parfois réalisée sous forme de canalisations préfabriquées. 

En basse tension, les « gaines canalis » préfabriquées jouent le double rôle de câble d’alimentation et de chemin de câble. Elles sont notamment utilisées dans les bâtiments industriels et commerciaux afin de permettre une grande souplesse de déplacement des appareils à alimenter (en particulier l’éclairage). 

**L’intensité de court-circuit** 

L’intensité de court-circuit (abrégée Icc) est une grandeur théorique qui correspond au courant mesurable en un point de l’installation électrique si ce point était relié directement à la terre. 

La connaissance du courant de court-circuit est très importante pour le dimensionnement des organes de sécurité (disjoncteurs). La connaissance de la valeur du courant de court-circuit Icc à tous les endroits d’une installation où l’on veut placer un dispositif de protection (fusible ou disjoncteur) chargé de l’interrompre permet de s’assurer que le pouvoir de coupure du fusible ou du disjoncteur est bien supérieur au courant de courtcircuit à cet endroit, l’incapacité d’un fusible ou d’un disjoncteur à interrompre un courant de court-circuit pouvant produire des résultats nuisibles. 

**Pour en savoir plus sur les calculs des intensités de court-circuit** 

Consulter le site d’un éditeur de logiciels de calcul, par exemple [www.alpi.fr/](http://www.alpi.fr/logiciels.html) [logiciels.html](http://www.alpi.fr/logiciels.html) pour le logiciel _Caneco_ . 

**La vérification initiale des installations électriques** 

La vérification initiale des installations électriques est une procédure de vérification détaillée instituée par le Code du travail et décrite par des arrêtés[37] ~~,~~ ainsi que dans la norme C15-100. Le maître d’ouvrage a l’obligation de la faire réaliser à la fin des travaux, avant la livraison du bâtiment à ses utilisateurs. 

Étant imposée par le Code du travail, elle a donc un champ d’application extrêmement large et s’applique quasiment à tous les types d’établissements, hors habitations. Cette vérification, qui est spécifique aux installations courants forts, comporte un examen visuel et des essais, qui sont décrits en détail dans l’arrêté. Cette vérification est ensuite suivie de vérifications périodiques. Elle permet de s’assurer que les installations ne

comportent pas de risques électriques pour les travailleurs (et par extension pour le public). Par exemple, la vérification permettra de garantir qu’il n’existe pas de câble dénudé accessible, ou dans un ERP qu’aucun équipement n’est dangereux pour un enfant. 

**Point de vigilance** 

Cette réglementation ne doit pas être confondue avec l’article GE 8 du règlement de sécurité incendie dans les ERP, qui prescrit les vérifications techniques exigibles dans les ERP (lesquelles vérifications portent sur toutes les installations et pas seulement courants forts, et se traduisent à la fin du chantier par le RVRAT du bureau de contrôle). 

**Consuel** 

Le Consuel (Comité national pour la sécurité des usagers de l’électricité) est une association reconnue d’utilité publique chargée de certifier la conformité des installations électriques neuves avant leur raccordement au réseau Enedis. 

**Dans quel cas le passage du Consuel est-il obligatoire ?[38]** 

Tant en logement que pour les ERT et ERP, le Consuel est obligatoire pour :

- toute nouvelle installation électrique raccordée au réseau ENEDIS ;

- installations de production d’électricité jusqu’à 250 kVA raccordées au réseau ENEDIS et requérant une modification de l’installation intérieure d’électricité ;

- toute installation électrique entièrement rénovée alimentée sous une tension inférieure à 50 kV, quand il y a eu mise hors tension de l’installation par le distributeur à la demande de son client afin de permettre de procéder à cette rénovation. 

Les installations électriques non entièrement rénovées ou dont la rénovation n’a pas donné lieu à mise hors tension par un distributeur d’électricité peuvent faire l’objet d’une attestation de conformité par le Consuel sur la demande du maître d’ouvrage. 

C’est généralement l’entreprise du lot Courants forts (« l’installateur ») qui

demande le passage du Consuel, le maître d’œuvre ayant veillé à inclure cette prestation à son marché. La visite conduit à la délivrance d’une attestation de conformité. 

**Pour en savoir plus en courants forts** 

- [www.legrand.fr](http://www.legrand.fr) avec notamment un Guide de l’électricité, centré surtout sur l’habitat.

- Norme NF C15-100 : c’est véritablement le texte fondamental, à tel point qu’on peut dire qu’« être un électricien » est synonyme de maîtriser ce texte.

- Les articles EL et EC du Règlement ERP.

- Décret n° 88-1056 du 14 novembre 1988, en particulier son art. 2 comportant un ensemble de définitions.

- Pour le chantier : norme UTE C18-510, qui regroupe un ensemble de prescriptions relatives à la sécurité concernant les manœuvres et actions sur ou à proximité des installations électriques. 

### 2.6.3. Mise à la terre et régime de neutre 

**Les régimes de neutre** 

Le régime de neutre, ou schéma de mise à la terre, est une notion complexe, qui caractérise le type de courant électrique, dans son rapport avec les circuits de mise à la terre. Un livre entier pourrait être consacré aux subtilités de ces notions. (Voir le zoom ci-dessous.) 

La barrette de connexion des neutres permet aux électriciens de savoir de quel régime de neutre relève un poste HT.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0540-00.png]]

Figure 124. Connexion des neutres (les câbles sont vert et jaune). 

**… les régimes de neutre** 

En résumé, le schéma de mise à la terre caractérise : 

- d’une part, le mode de raccordement à la terre du secondaire du transformateur HT/BT (le secondaire est la partie basse tension du transformateur) ;

- d’autre part, la manière de relier les masses des installations à la terre (conducteur vert et jaune). Chaque régime de neutre est désigné par deux lettres :

- La première lettre indique la situation du neutre du secondaire du transformateur par rapport à la terre :

  - T pour neutre raccordé à la terre ;

  - I pour neutre isolé de la terre.

- La deuxième lettre indique la situation des masses des récepteurs :

  - T pour masse reliée à la terre ;

  - N pour masse reliée au neutre. En combinant ces deux lettres, trois cas sont possibles :

- TT : neutre du transformateur raccordé à la terre, masses des récepteurs raccordées à la terre ;

- TN : neutre du transformateur raccordé à la terre, masses des récepteurs raccordées au neutre ;

- IT : neutre du transformateur isolé ou impédant, masses des récepteurs raccordées à la terre. 

Le régime TN comprend des variantes : TNC et TNS. 

Ce qu’il faut savoir, c’est qu’une installation fonctionnant dans un certain régime de neutre ne pourra pas être raccordée à une installation d’un autre régime de neutre sans passer par un transformateur d’isolement ; il est donc indispensable de se montrer vigilant pour les projets dans l’existant. Mais, même pour les maîtres d’œuvre travaillant dans le neuf, une vigilance est nécessaire car les installations concourant à la sécurité incendie relèvent dans certains cas d’un régime de neutre particulier, le régime IT. 

Il existe donc principalement trois régimes de neutre : 

**Le schéma TT** 

C’est le régime de neutre courant, présent dans toutes les petites installations (habitation par exemple, et livraison Enedis basse tension). Il présente l’avantage, dans les sites existants, de permettre à l’exploitant de procéder à de petites modifications (ajout d’un départ, etc.) sans avoir besoin d’en justifier la conformité par une note de calcul. 

**Les schémas TN, TNS et TNC** 

C’est le régime de neutre « moderne » des installations optimisées économiquement (en présence d’un poste HT privatif). Pour un projet neuf, il revient moins cher qu’un régime TT et est donc souvent prescrit. 

**Le schéma IT** 

Ce régime de neutre est utilisé dans certaines installations qui ne doivent pas subir de disjonction générale à cause d’un défaut local. C’est par exemple le régime de neutre des installations de sécurité comme les TGS, dans certains cas. Dans ces installations, un contrôleur permanent d’isolement (CPI) signale l’apparition du premier défaut d’isolement. Ce régime de neutre nécessite la disponibilité d’un agent de maintenance. On essaie donc de l’éviter au maximum, et il est par conséquent de moins en moins utilisé.

**Pour en savoir plus sur les régimes de neutre** 

On peut consulter notamment la norme NF C15-100-04, ainsi que la norme UTE C15-106, §3. 

**La mise à la terre des immeubles d’habitation collectifs existants** 

De nombreux immeubles anciens ne comportent pas de véritable mise à la terre. Pour assurer la sécurité, on crée un _conducteur de protection_ qui distribue tous les étages. La prise de terre est généralement réalisée par des _piquets verticaux_ , plantés dans le sol à 2 m de profondeur dans la cave. On peut aussi utiliser la méthode des conducteurs en fond de fouille, qui peuvent être réalisés sous forme d’une boucle enterrée ou de conducteurs enterrés dans une tranchée. 

**Pour en savoir plus sur la mise à la terre des immeubles d’habitation existants**_ Consulter [https://professionnels.promotelec.com](https://professionnels.promotelec.com).** 

## 2.7. Quelques notions dans le domaine de l’éclairage 

Le but du présent chapitre est de permettre aux maîtres d’œuvre (architectes et électriciens notamment) travaillant avec un éclairagiste de comprendre les problématiques et les enjeux de sa discipline. C’est là un domaine au premier abord simple, mais en vérité assez complexe quand on s’y plonge. Un peu de vocabulaire facilite le dialogue entre spécialités. 

### 2.7.1. Principales grandeurs physiques et concepts 

**Autrement appelées _grandeurs photométriques_ .** 

**Température de couleur** 

La lumière est caractérisée par sa température de couleur, exprimée en kelvin (K), qui traduit l’ _ambiance_ donnée par l’éclairage. Les lumières

**chaudes donnent une ambiance plus chaleureuse que les lumières froides.** 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0543-01.png]]

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0543-02.png]]

**----- Start of picture text -----**<br>
Figure 125. Ordres de grandeur de températures de couleur de la lumière<br>naturelle.<br>**----- End of picture text -----**<br>

**Quelques ordres de grandeur :** 

- 2 500-3 500 K : coucher de soleil, lampe à incandescence ; lumière « chaude », riche en radiations rouges ;

- 4 000-5 000 K : lumière du jour par temps clair ; blanc neutre ;

- 6 000-8 000 K : ciel nuageux ; lumière « froide » riche en radiations bleues. Cette valeur figure sur les fiches techniques et emballages des sources lumineuses. 

**Point de vigilance** 

Cette notion est trompeuse, car en vérité une source de couleur froide (par exemple une flamme de gaz bleue) a une température (thermique) réelle plus chaude qu’une source de couleur chaude (par exemple une flamme de feu de cheminée orangée). 

**Rendu des couleurs** 

L’indice de rendu des couleurs caractérise la propension d’une source lumineuse à déformer ou non les couleurs. Il est mesuré par le sigle IRC ou en anglais _Ra_ , sans unité, avec IRC = 100 pour la lumière du jour, dotée

d’un excellent rendu des couleurs. Typiquement, l’éclairage jaune souvent rencontré dans les tunnels (lampes à sodium) a un mauvais rendu des couleurs, de l’ordre de 25 : il ne permet pas de distinguer toutes les couleurs de l’arc-en-ciel. 

Un IRC > 80 est considéré comme bon ; entre 60 et 80, il est considéré comme moyen ; en dessous de 60, il est considéré comme médiocre. Cette notion joue un rôle important dans le choix des sources lumineuses, et figure sur leur fiche technique. Certains programmes exigent un très bon IRC, par exemple les musées et les restaurants d’un certain niveau. 

**Qu’est-ce que le code couleur ?** 

Les fabricants utilisent un code couleur a priori énigmatique à trois chiffres pour caractériser les sources lumineuses. Le premier chiffre désigne l’IRC, les deux suivants désignent la température de couleur. Par exemple : une lampe fluocompacte « de code couleur 827 » signifie que son IRC est compris entre 80 et 89, et que sa température de couleur est de 2 700 K ; une lampe au sodium haute pression « de code couleur 621 » signifie que son IRC est compris entre 60 et 69, et que sa température de couleur est de 2 100 K. 

Le code couleur WH ( _white_ ) désigne une lumière blanche, d’IRC supérieur à 95, utilisée pour des applications spécialisées. 

**Flux lumineux d’une source** 

Il est mesuré en lumen (symbole : lm). Cette grandeur caractérise la « quantité » de lumière émise par seconde dans un cône (pour être précis : dans un angle solide d’une valeur de [1](83_1._le_nettoyage_de_fin_de_chantier.md) stéradian). Elle figure sur les fiches techniques des sources lumineuses. 

**Pour fixer quelques exemples d’ordres de grandeur :** 

- dans les ERP des quatre premières catégories, le règlement exige que les sources d’éclairage de sécurité d’évacuation assurent un flux de 45 lumens[39] ;

- une lampe fluocompacte de 36 W émet autour de 3 000 lm ;

- une lampe à halogénures métalliques autour de 200 000 lm.

**Efficacité d’une source** 

L’efficacité lumineuse est le quotient du flux lumineux par la puissance électrique utilisée par l’appareil d’éclairage : Φ/P. Mesurée en lumens par watt (lm/W), elle caractérise le rendement énergétique de la source lumineuse, en prenant en compte la consommation de la lampe et de ses appareillages annexes. C’est donc un critère fondamental de choix des appareils. 

**Point de vigilance** 

Certains spécialistes jugent plus pertinent, pour évaluer l’efficacité énergétique d’un projet de mise en lumière, d’utiliser un critère basé sur des watts par lux et par mètre carré : W/(lx.m[2] ). 

**Éclairement** 

Il est mesuré en lux (symbole : lx). Cette grandeur caractérise la lumière reçue par une surface, par mètre carré. C’est donc le flux lumineux, divisé par la surface : E = Φ/S, c’est-à-dire une densité de flux lumineux tombant sur une surface. 

L’éclairement dépend donc à la fois de l’appareil d’éclairage et de sa position ; ce n’est pas une caractéristique pouvant figurer sur la fiche technique d’un produit, mais le résultat d’une « mise en lumière ». Cette valeur jour un rôle important pour vérifier l’adéquation d’un projet d’éclairage par rapport à l’activité prévue dans les locaux et par rapport aux réglementations, en particulier les réglementations accessibilité (voir plus bas le § relatif aux contraintes réglementaires dans les projets d’éclairage). Quelques ordres de grandeurs : 

- espace extérieur en plein soleil : 100 000 lx ;

- espace extérieur à l’ombre ou temps nuageux : 5 000 à 10 000 lx ;

- bureau : 200 à 400 lx ;

- espace intérieur : 100 à 300 lx ;

- rue la nuit : 5 à 30 lx ;

- **nuit de pleine lune : 0,25 lx.** 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0546-01.png]]

Figure 126. Ordres de grandeurs de niveaux d’éclairement. 

**Luminance** 

Les objets éclairés renvoient à l’œil de la lumière, généralement en la modifiant. Ils se comportent donc comme des sources lumineuses secondaires – c’est le principe de l’éclairage indirect. La luminance caractérise la lumière émise par une surface éclairée, et visible par l’œil humain. Cette grandeur est mesurée en candela par mètre carré (symbole : cd/m2). Dans le cas simple où la surface S émettrice est perpendiculaire au regard, la luminance est l’intensité lumineuse divisée par la surface S. Ce n’est donc pas une grandeur associée à une lampe ou à un luminaire, mais un concept intervenant dans les calculs d’éblouissement. L’UGR ( _Unified Glare Rating_ ) est une méthode d’évaluation de l’éblouissement engendré par un projet d’éclairage.

### Les sources lumineuses 

Il existe trois grandes familles de sources lumineuses :

- les lampes à incandescence ;

- les lampes à décharges ;

- les LED. 

#### 2.7.2.1. Lampes à incandescence** Maintenant remplacées par les LED, elles comprenaient les lampes à filament et les halogènes. **2.7.2.2. Lampes à décharges, ou fluorescentes 

Le principe de la fluorescence est utilisé dans les lampes à décharges. Les inconvénients des lampes à décharges sont leur moins bon indice de rendu des couleurs, et leur délai d’allumage. On peut diviser ces lampes en basse pression et haute pression. Les lampes à décharges à _basse pression_ comprennent (en se limitant aux cas les plus courants) : 

- les lampes _à vapeur de sodium basse pression_ : lampes de couleur orangée monochromatique, dotées d’un mauvais indice de rendu des couleurs mais d’une très bonne efficacité lumineuse ; inventées en 1932, elles sont utilisées quand le rendu des couleurs n’est pas exigé : autoroutes, routes, tunnels, ports ;

- les _tubes fluorescents_ classiques (« néons »), couramment utilisés, commercialisés pour la première fois en 1937, et basés sur l’excitation d’atomes de mercure ; les plus courants sont les T8 et T5 ; 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0547-05.png]]

- les lampes _fluocompactes_ courantes, apparues initialement en 1979, et basées sur la miniaturisation des tubes fluorescents ; 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0548-02.png]]

Figure 128. Lampes fluocompactes. 

- les lampes _à induction_ , apparues sur le marché en 1990, dans lesquelles un mélange de gaz et de vapeurs métalliques constitue la boucle d’induction d’un générateur à haute fréquence. Les atomes excités par l’échange d’énergie génèrent un rayonnement UV qui est alors converti en lumière visible par des matériaux fluorescents. Leur durée de vie étant très longue, elles sont utilisées dans les endroits d’accès difficile (tunnels, tours). 

Les lampes à décharge à _haute pression_ (en anglais HID – _High Intensity Discharge_ ) sont principalement constituées par les lampes :

- _à vapeur de sodium haute pression_ (ou SHP, pour sodium haute pression), inventées en 1964, notamment utilisées en éclairage public, routier et industriel, du fait de leur bonne efficacité lumineuse et malgré leur faible indice de rendu des couleurs ; elles nécessitent un temps de mise en route de plusieurs minutes ; elles utilisent un ballast et un starter ; 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0548-06.png]]

Figure 129. Lampe à vapeur de sodium haute pression. 

- _à vapeur de mercure_ , inventées en 1935, lesquelles ne sont plus prescrites aujourd’hui car leur efficacité lumineuse est faible, leur rendu des couleurs est pauvre et leur durée de vie est courte ; elles sont courantes dans l’existant, en éclairage public ;

- ou _à iodures métalliques_ (ou _halogénures_ , et en anglais _metal halide_ ), lampes de forte puissance inventées en 1960, d’une température proche de la lumière naturelle, utilisées dans l’industrie cinématographique, la photographie, l’éclairage scénique, les musées, les commerces, l’éclairage des places publiques et monuments, etc. ; elles sont utilisées quand la priorité est donnée à la _qualité chromatique_ et au rendu des couleurs (attention toutefois, certains modèle possèdent un IRC relativement médiocre, pouvant aller jusqu’à 65) ; elles existent dans une large palette de couleurs, permettant de varier les effets ; l’ampoule contient de la vapeur de mercure haute pression dans laquelle on a ajouté des halogénures métalliques (le plus souvent des iodures) ; elles nécessitent un ballast et un système d’allumage. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0549-01.png]]

Figure 130. Lampes aux halogénures métalliques. 

**Point de vigilance** 

Pour des raisons commerciales, les fabricants ne mettent souvent pas en avant la véritable composition des sources lumineuses. Ainsi, une ampoule fluocompacte n’est pas désignée sur les emballages comme « à vapeurs de mercure », car cela est perçu comme moins commercial. Ce manque de transparence ne facilite pas toujours la compréhension immédiate du sujet. **2.7.2.3. Lampes à LED** Après avoir été pendant des années les lampes de l’avenir, elles sont maintenant les lampes les plus couramment utilisées. Leur avantage est double : faible consommation et très longue durée de vie.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0550-00.png]]

Figure 131. Détail de LED. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0550-02.png]]

Figure 132. En éclairage public extérieur les LED sont maintenant omniprésentes. 

**Pour quels usages les LED sont-elles adaptées ?** 

Pendant des années le syndicat de l’éclairage a publié tous les six mois une grille de maturité des LED, montrant l’évolution des techniques et les taux de pénétration du marché usage par usage. Aujourd’hui, les sources LED sont si universellement utilisées que cette analyse n’est plus d’actualité : les LED sont adaptées à quasiment tous les usages. 

#### 2.7.2.4. Critères de choix 

Il faut garder à l’esprit que l’efficacité énergétique ne peut pas être le seul critère de choix pour certains types de programmes. Par exemple pour un musée ou un restaurant d’un certain niveau, les critères chromatiques (IRC) sont fondamentaux, et l’efficacité énergétique ne suffit pas à choisir une lampe. 

### 2.7.3. Les luminaires 

Les luminaires qui accueillent les lampes comportent un _système optique_

destiné à modifier le flux lumineux émis par la lampe. Ce système optique peut être constitué de réflecteurs, de réfracteurs, de diffuseurs, filtres, etc. Un des objectifs de ces optiques est d’empêcher la dispersion de la lumière ; par exemple en éclairage extérieur, éviter d’envoyer une partie du flux lumineux vers ciel. 

L’optique est caractérisée par un schéma de répartition du flux lumineux, appelé sur les fiches techniques _données photométriques_ . On parle par exemple pour les spots de faisceau intensif, semi-intensif, extensif, etc. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0551-02.png]]

Figure 133. Exemple de schéma photométrique figurant sur la fiche technique d’un luminaire. 

Tout l’art de l’éclairagiste est de choisir les emplacements, les combinaisons et les orientations des luminaires pour optimiser leur utilisation (on parle de _facteur d’utilisation_ ) et éviter les risques d’éblouissement. 

On classe[40] les luminaires en : 

- éclairage diffus : dirigé dans toutes les directions ;

- éclairage direct : dirigé vers le bas ;

- éclairage semi-direct : dirigé principalement vers le bas et partiellement vers le haut ;

- éclairage direct/indirect : dirigé à la fois vers le bas et vers le haut ;

- **éclairage semi-indirect : dirigé principalement vers le haut et partiellement vers le bas ;

- éclairage indirect : dirigé vers le haut.** 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0552-01.png]]

Figure 134. Types de luminaires. 

### 2.7.4. Optimiser l’utilisation de l’éclairage naturel dans les projets 

**Quelques concepts** 

Le _facteur lumière du jour_ (FLJ) est le rapport entre l’éclairement reçu grâce à la lumière naturelle à l’intérieur du bâtiment en un point et l’éclairement reçu à l’extérieur du bâtiment, par temps couvert (sous un ciel normalisé). Le facteur lumière du jour est généralement calculé à la hauteur d’un plan de travail, dans une zone « de premier rang » proche des fenêtres. En termes d’ordre de grandeur : 

|Facteur<br>lumière du<br>jour|< [1](83_1._le_nettoyage_de_fin_de_chantier.md) %|1 à 2 %|2 à 5 %|5 à 10 %|> 10 %|ent|
|---|---|---|---|---|---|---|
||Trop<br>sombre|FLJ faible|Bon FLJ|Très bon<br>FLJ|Risque<br>d’éblouissem||

Le FLJ étant un concept lié à un ciel couvert normalisé, il ne tient compte ni de l’orientation du bâtiment (pas de soleil) ni du climat local. Il est basé sur un ciel couvert ; or, dans le Sud de la France cela ne concerne que 30 % des jours de l’année. Son utilisation peut donc conduire à concevoir des ouvertures identiques sur toutes les façades et à surdimensionner les fenêtres puisqu’on prend un ciel couvert comme référence, avec un risque de surchauffe et d’éblouissement. C’est donc un concept limité. 

L’ _autonomie en lumière du jour_ ( _Daylight Autonomy_ , ou DA) est la proportion d’heures d’occupation des locaux sur l’année où la lumière naturelle suffit à assurer le niveau d’éclairement nécessaire. Ce concept prend en compte l’évolution de l’éclairage naturel au fil des saisons. On considère généralement qu’une DA de 50-60 % est satisfaisante pour des bureaux occupés de 8 h à [18](100_18._après_la_réception_le_suivi_des_performances_énergétiques.md) h. 

**La conception des bâtiments doit permettre :** 

- dans un premier temps de profiter au maximum de la lumière naturelle ;

- dans un deuxième temps de compléter l’éclairage naturel par un éclairage artificiel nécessaire et suffisant, commandé par des automatismes qui optimisent les consommations électriques. 

**Optimiser les apports en lumière naturelle** 

La _largeur_ du bâtiment est définie en esquisse. Au-delà de 4,5 m de profondeur, les locaux bénéficient peu de la lumière naturelle. Il est donc essentiel pour l’utilisation de la lumière naturelle de ne pas concevoir des bâtiments trop profonds. Pour donner un ordre de grandeur, 20 m de profondeur est un maximum jamais dépassé (une profondeur inférieure est hautement souhaitable). 

Le _dimensionnement des ouvertures_ est un équilibre entre utilisation de la lumière naturelle et isolation thermique. 

La _disposition des locaux_ en plan et en fonction de l’orientation des façades joue un rôle important : les locaux de vie ont davantage besoin de lumière naturelle que les circulations et les locaux techniques (attention toutefois sur ce point : les locaux techniques CVC ont besoin de surfaces d’échange avec l’extérieur).

Les _protections solaires_ sont à prévoir pour préserver le confort d’été et limiter l’éblouissement. Pour mémoire, toujours préférer des protections solaires extérieures, meilleures en termes thermiques. 

**Les automatismes de commande de l’éclairage** Les dispositifs de conduite de l’éclairage peuvent donc être de plusieurs types : 

- commande marche/arrêt ;

- asservissement à des détecteurs de présence ;

- asservissement à une horloge ;

- asservissement à la luminosité naturelle. 

Les horloges, détecteurs de présence, capteurs de luminosité (cellule photoélectrique) permettent de réaliser d’importantes économies d’énergie, et sont complémentaires de luminaires efficaces. 

Ces automatismes, ou dispositifs de conduite, peuvent commander l’allumage et l’extinction mais ils peuvent aussi commander le réglage de la lumière émise. Certains tubes fluorescents, ou des lampes à LED, peuvent ainsi être associés à un système de modulation du flux lumineux basé sur des détecteurs de luminosité ambiante (on parle de source graduable), ce qui augmente considérablement l’efficacité énergétique. Grâce à ces systèmes, la disponibilité de l’éclairage naturel peut être prise en compte automatiquement, tout en laissant toujours aux utilisateurs la possibilité du réglage manuel. 

Les détecteurs de présence, à infrarouges ou ultrasons, qui commandent l’allumage et l’extinction, sont adaptés pour les circulations, les sanitaires, les lieux souvent inoccupés.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0555-00.png]]

Figure 135. Un exemple de détecteur de présence infrarouge pour lieu de passage sans luminosité naturelle (source : Legrand). On appelle _horloges astronomiques_ des horloges programmables (très bon marché) de gestion de l’éclairage, capables de s’adapter aux horaires quotidiens de lever et coucher du soleil. Elles peuvent être synchronisées par GPS, par radio, etc. et sont bien adaptées aux grands sites et à l’éclairage public. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0555-02.png]]

Figure 136. Un exemple d’horloge astronomique, ou interrupteur horaire programmable (source : Legrand). 

**Conseil pratique** 

Ce domaine des commandes d’éclairage est souvent négligé lors de la conception et constitue certainement un enjeu de progrès futurs. Même les maîtres d’œuvre les plus attentifs aux économies d’énergie peuvent malgré eux concevoir des locaux dont l’éclairage restera allumé en plein jour, du fait d’une conception pas assez fine des commandes d’éclairage. 

Prendre le temps d’examiner en détail avec la personne en charge du lot courants forts les commandes d’éclairage prévues, et s’interroger sur leur pertinence en fonction de la nature de chaque local.

**Pour en savoir plus sur les automatismes de commande d’éclairage** 

Voir par exemple sur le site Internet d’Osram la _Dali Box DayLight_ , qui gère l’éclairage à la fois en fonction de la présence des personnes et en fonction de la disponibilité de l’éclairage naturel, ou voir le site de Legrand, rubrique professionnel/tertiaire/inter éco. 

### 2.7.5. Les aspects sécurité et la robustesse des luminaires 

Le texte de base pour la sécurité électrique des luminaires est la norme NF EN 60598. Son respect est imposé dans les ERP des quatre premières catégories par l’article EC 5 du règlement de sécurité des ERP. La marque « NF Luminaire » en garantit le respect. 

**Classe électrique – protection contre les chocs électriques** 

Cette notion définit la résistance des luminaires à un choc électrique. Les luminaires sont répartis en classes :

- classe I : luminaires avec mise à la terre des parties métalliques accessibles ;

- classe II : double isolation ou isolation renforcée, c’est le cas le plus courant pour les luminaires professionnels ;

- classe III : luminaires alimentés en très basse tension de sécurité (inférieure à 50 V), destinés aux lieux très humides. Figure 137. Symboles des classes I, II et III. 

**Indice de protection (IP)** 

Cette notion, qui s’applique à bien d’autres appareils que les luminaires, caractérise le degré de protection procuré par les enveloppes des appareils. Le premier chiffre caractérise la protection contre les corps solides et les poussières, le deuxième la _protection contre l’humidité_ . C’est un critère de choix en fonction de l’implantation prévue pour les luminaires. Cette

problématique est bien connue pour la résistance à l’humidité, mais peutêtre moins pour la résistance aux poussières ; or, cet aspect est fondamental lui aussi pour la pérennité de l’installation : un luminaire peu résistant aux poussières et placé dans un environnement poussiéreux (parking par exemple) aura de moins bonnes performances photométriques dans le temps. 

Quelques exemples courants pour des luminaires : 

- IP20 : convient en intérieur ;

- IP66 : convient aussi en extérieur. On considère qu’un luminaire peut être implanté en extérieur, avec projection d’eau, à partir d’IP44. 

**Indice de protection (IK)** 

Cet indice caractérise le degré de protection contre les chocs physiques ; c’est un critère de choix pour les luminaires _antivandalisme_ notamment. IK00 caractérise les appareils les moins résistants, et IK10 les plus résistants. 

Exemples courants pour les luminaires : IK05, IK 07, IK08, IK09 et IK10. Il existe aussi un indice VK, qui caractérise la résistance antivandalisme. Il intègre la résistance mécanique au-delà de IK10, ainsi que les autres caractéristiques de résistance au vandalisme. 

**Test au fil incandescent[41]** 

Ce test, exigible dans certains cas, évalue la capacité d’un luminaire à résister à un incendie. Durant 30 secondes, un fil incandescent est appliqué sur les différentes parties du luminaire. La température du fil incandescent pour le test est de 960 °C, 850 °C, 750 °C ou 650 °C. 

**Pour en savoir plus sur les lampes** 

Consulter le site Internet de fabricants, comme [www.lighting.philips.fr](http://www.lighting.philips.fr), [www.osram.fr](http://www.osram.fr), [www.thornlighting.fr](http://www.thornlighting.fr) ou [www.gelighting.com/eu](http://www.gelighting.com/eu)

On rappelle ici pour mémoire les principales réglementations impactant la conception de l’éclairage _normal_ . Pour quelques rappels sur l’éclairage de sécurité, se référer au chapitre 1. Les valeurs d’éclairement citées dans la réglementation doivent s’entendre comme un niveau _moyen_ à garantir au sol, et non comme une valeur minimale en tout point.[42] 

**Niveaux d’éclairement en ERP neuf** 

La réglementation sur l’accessibilité PMR des ERP neufs est très exigeante sur les niveaux d’éclairement. Dans la plupart des cas, les valeurs qu’elle impose sont dimensionnantes pour les installations d’éclairage en ERP, à tel point qu’on peut se demander s’il ne serait pas pertinent de revoir ce texte pour plus de sobriété énergétique dans certains types d’ERP : 

_«_

- _20 lux pour le cheminement extérieur accessible ainsi que les parcs de stationnement extérieurs et leurs circulations piétonnes accessibles ;_

- _20 lux pour les parcs de stationnement intérieurs et leurs circulations piétonnes accessibles ;_

- _200 lux au droit des postes d’accueil ou des mobiliers en faisant office ;_

- _100 lux pour les circulations intérieures horizontales ;_

- _150 lux pour chaque escalier et équipement mobile. »_ en intérieur[43] Il est intéressant, à titre de benchmark, de constater qu’aux Pays-Bas de nombreux restaurants se contentent de quelques lux, de même que les pubs au Royaume-Uni. 

Cette même liste de niveaux d’éclairement est aussi applicable pour les parties communes des immeubles d’habitation neufs[44] ~~,~~ avec comme précision supplémentaire : _100 lux à l’intérieur des locaux collectifs_ (et avec suppression de la mention des postes d’accueil). 

**Niveaux d’éclairement en ERP existant** 

Là encore c’est la réglementation accessibilité qui est dimensionnante[45] ~~,~~ en exigeant : _«_

- _20 lux pour le cheminement extérieur accessible ainsi que les parcs de stationnement extérieurs et leurs circulations piétonnes accessibles ;_

- _20 lux pour les parcs de stationnement intérieurs et leurs circulations piétonnes accessibles ;_

- _200 lux au droit des postes d’accueil ;_

- _100 lux pour les circulations intérieures horizontales ;_

- _150 lux pour chaque escalier et équipement mobile. »_ en intérieur. 

**Niveaux d’éclairement en ERT** 

Le Code du travail impose aux ERT des valeurs différentes[46] : 

|**Locaux affectés au travail et leurs**<br>**dépendances**|**Valeurs minimales d’éclairement**|
|---|---|
|Voies de circulation intérieures|40 lux|
|Escaliers et entrepôts|60 lux|
|Locaux de travail, vestiaires, sanitaires|120 lux|
|Locaux aveugles affectés à un travail<br>permanent|200 lux|
|**Espaces extérieurs**||
|Zones et voies de circulation<br>extérieures|10 lux|
|Espaces extérieurs où sont effectués des<br>travaux à caractère permanent|40 lux|

Le texte de référence pour les locaux professionnels est la norme sur l’éclairage des lieux de travail, qui fournit des prescriptions beaucoup plus détaillées, profession par profession.[47] 

**Réglementation sur l’éclairage nocturne** 

Afin de préserver la biodiversité l’éclairage nocturne des espaces publics extérieurs, des façades et des vitrines commerciales est règlementé. Les prescriptions portent sur les horaires et sur les caractéristiques de l’éclairage.[48]

**Règles issues du Règlement ERP** 

Pour mémoire, les articles EC (comme éclairage) du Règlement ERP sont applicables aux ERP du premier groupe (catégorie [1](83_1._le_nettoyage_de_fin_de_chantier.md) à 4). Consulter le chapitre 1 pour plus de détails.
