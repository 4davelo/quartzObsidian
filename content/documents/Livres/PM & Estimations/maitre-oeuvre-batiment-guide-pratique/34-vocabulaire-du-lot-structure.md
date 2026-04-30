---
type: document-section
document_id: maitre-oeuvre-batiment-guide-pratique
section_id: "section:1"
ordre_document: 34
titre: "vocabulaire du lot structure"
aliases:
  - Maître d'oeuvre bâtiment — Hamburger 2023 — 34 vocabulaire du lot structure
resume_section: |-
  ### Vocabulaire du lot Structure
  
  Le domaine des études Structure inclut les structures métal, béton et bois. Le génie civil, plus large, englobe aussi des travaux non structurels. En anglais, ce domaine est appelé _Structural Engineering_.
  
  #### Concepts clés :
  - **Schéma statique** : représentation 3D simplifiée d'une structure, montrant les degrés de liberté des articulations. Toute modification nécessite une révision complète de l'étude.
  - **Descente de charges** : efforts transmis par la superstructure aux fondations.
  - **Noyau de contreventement** : structure résistante aux poussées horizontales, souvent intégrée aux cages d'escaliers ou trémies d'ascenseurs.
  
  #### Structures métalliques :
  - **Poutrelles** : IPN, IPE, HEA/HEB/HEM, PRS (soudées sur mesure), alvéolaires (légères).
  - **Aciers** : classés par nuances (ex. S235) et qualités (JR, JO, J2).
  - **Protection** : contre le feu (flocage, peinture intumescente) et corrosion (galvanisation).
  
  #### Structures bois :
  - Techniques : ossature bois, poteau-poutre, structure masse, panneaux CLT (lamellé-croisés).
  - Critères de choix : disponibilité, coût, provenance, durabilité, propriétés mécaniques, etc.
  - Points de vigilance : conformité réglementaire, sécurité incendie, acoustique, étanchéité.
  
  #### Fondations :
  - **Superficielles** : semelles filantes ou isolées, radiers.
  - **Profondeurs** : micropieux, pieux battus ou forés, parois moulées.
  - **Renforcement des sols** : colonnes ballastées, inclusions rigides, _jet grouting_.
  
  #### Réglementation :
  - **Eurocodes** : normes européennes unifiées pour le calcul des structures, remplaçant les règles nationales (ex. BAEL, CM66). Obligatoires en marchés publics.
  - **Construction parasismique** : basée sur le zonage sismique, la nature du sol et la catégorie du bâtiment. L'Eurocode 8 est la référence.
  
  #### Autres :
  - **Suspension antivibratile** : protection contre les vibrations (métro, voies ferrées) via tapis ou boîtes à ressorts.
  - **Recyclage des granulats** : favorisé pour réduire l'impact environnemental, avec des limites techniques.
  
  Pour approfondir, consulter les sites spécialisés mentionnés.
document_parent: "[[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/index|Maître d'oeuvre bâtiment — Hamburger 2023 — Index]]"
section_precedente: "[[33-les-bases-sur-les-lots-techniques|Les bases sur les lots techniques]]"
section_suivante: "[[35-vocabulaire-et-enjeux-des-courants-forts|vocabulaire et enjeux des courants forts]]"
tags: [document-section, ouvrage, gestion-projet, maitrise-oeuvre, estimation]
sources: ["34_1._vocabulaire_du_lot_structure.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [appel-doffres, execution-projet, technique]
autorite: [pratique, reference]
juridictions: [france, generique]
familles_sources: [ouvrage, gestion-projet]
---
### 1. Vocabulaire du lot Structure 

Le domaine des études Structure comporte les Structures métal, les Structures béton et les Structures bois. Le terme de génie civil a un sens plus large puisqu’il englobe des travaux sans caractère nécessairement structurel (routes par exemple). En anglais, le domaine des structures s’appelle _Structural Engineering_ . On trouvera ci-dessous quelques termes souvent rencontrés.

#### 1.1. Quelques termes génériques 

**Schéma statique** 

Le schéma statique d’une structure est la représentation schématique en trois dimensions de cette structure, sous forme de barres articulées ou encastrées. 

Pour mémoire :

- les liaisons articulées permettent une libre rotation et ne transmettent pas de moment fléchissant,

- les liaisons encastrées interdisent la rotation et transmettent un moment de réaction,

- les appuis glissants autorisent une translation, permettant ainsi la dilatation d’un ouvrage. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0467-04.png]]

Figure 78. Exemple de liaison articulée. 

Le schéma statique montre les degrés de liberté de chaque articulation, ou

nœud. C’est en quelque sorte le principe structurel du bâtiment, le cœur de l’étude Structure. Si une entreprise propose de modifier le schéma statique prévu au marché, il faut être extrêmement méfiant, car cela équivaut à ce qu’elle reprenne intégralement toute l’étude de maîtrise d’œuvre, y compris les interfaces avec les autres lots et les validations par le bureau de contrôle, le cas échéant. Les conséquences indirectes peuvent être considérables. 

On rencontre aussi le terme de _schéma structurel_ . 

Quels sont, en première approche, les ordres de grandeur des portées habituellement rencontrées dans les schémas statiques, pour les différents types de structure ? _« Les bâtiments à ossature bois ordinaires ont le plus souvent une ligne de poteaux ou un mur porteur tous les [3](85_3._les_opr.md) à [5](87_5._problématiques_liées_aux_lots_techniques.md),5 m ; les bâtiments de dimensions commerciales en acier ou béton, tous les [7](89_7._le_rôle_du_coordonnateur_sps_pour_la_réception_du_chantier.md),5 à [15](97_15._archivage_en_fin_de_chantier.md) mètres. Dans les halls d’exposition, les salles de spectacle, et autres espaces du même type, la portée peut atteindre 27 mètres voire plus. »_[[1](83_1._le_nettoyage_de_fin_de_chantier.md)] 

**Descente de charges** 

La descente de charges du bâtiment sur une fondation est le torseur des efforts appliqué par la superstructure, c’est-à-dire la force appliquée, avec trois coordonnées, et le moment appliqué, lui aussi avec trois coordonnées, soit un total de [6](88_6._les_dossiers_des_ouvrages_exécutés_doe.md) coordonnées. 

**Noyau de contreventement** 

Le contreventement est la structure qui résiste aux poussées horizontales que subit l’immeuble. Un cadre peut par exemple être contreventé par une croix de Saint-André. 

Dans les immeubles neufs, une manière courante d’assurer le contreventement de la structure est d’utiliser les cages d’escalier et trémies d’ascenseurs, en leur assurant une rigidité qui permet de résister aux efforts horizontaux. Les cages d’escalier assurant ce rôle de contreventement sont appelées _noyaux de contreventement_ .

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0469-00.png]]

Figure 79. Noyaux de contreventement. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0469-02.png]]

Figure 80. Dans ces immeubles, le noyau de contreventement est constitué par une trémie d’ascenseur en béton. 

#### 1.2. Vocabulaire des structures métalliques 

**Vocabulaire des poutrelles** Les poutrelles courantes sont désignées par un sigle : 

- IPN : poutrelles en I normales. L’épaisseur des ailes est variable.

- IPE : poutrelles en I européennes. Les ailes ont une épaisseur fixe. Elles sont beaucoup plus utilisées aujourd’hui que les IPN. Il existe aussi des variantes dites IPE-A et IPE-O.

- HEA, HEB et HEM : poutrelles HE, dite gamme européenne. La différence entre ces trois types réside dans l’épaisseur relative des ailes et de l’âme. Leur profil est de forme carrée. Les HEA sont les plus utilisées. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0470-01.png]]

Figure 81. Dénomination des poutrelles courantes. 

Les poutres reconstituées soudées (PRS) sont des poutrelles fabriquées _sur mesure_ par soudage de tôles et larges plats entre eux. Elles permettent de s’ajuster au besoin précis d’un projet. Elles peuvent prendre des formes classiques en I ou H, ou des profils particuliers : âme décentrée, âme cintrée, âme trapézoïdale, etc. Les poutrelles alvéolaires ou ajourées, créées par découpage de l’âme, sont plus légères (jusqu’à 30 % d’allègement), pour un même moment d’inertie.

**L’évidement peut être de forme circulaire, hexagonale, ou sinusoïdale.** 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0471-01.png]]

Figure 82. Poutrelles alvéolaires à évidement circulaire, sinusoïdal ou hexagonal (source : Construiracier). 

À partir de 20 m de portée, les tubes ronds métalliques ont la réputation d’être plus performants que les poutrelles à profil ouvert (à vérifier au cas par cas). Enfin, les poutrelles IFB et SFB ont de larges âmes inférieures et sont utilisées comme structure métallique de plancher-dalle. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0471-04.png]]

Figure 83. Poutrelle IFB et poutrelle SFB (source : Construiracier). 

**Nuance et qualité d’acier** 

La classification des aciers couramment utilisée dans le bâtiment désigne les aciers par leur nuance et leur qualité.[[2](84_2._les_autocontrôles_et_essais.md)] La _nuance_ d’un acier (en anglais, _grade_ ) dépend de sa composition chimique et détermine sa résistance à la traction. La nuance la plus couramment utilisée dans la construction est le S235. La lettre « S » représente l’acier de construction, par opposition à d’autres types d’acier. La valeur 235 correspond à la limite d’élasticité minimale exprimée en MPa. On désigne également pour chaque nuance des classes de _qualité_ (qui vont de la basse qualité à la très haute qualité) : JR, JO, J2. Les qualités des aciers se distinguent notamment par leur degré de soudabilité. 

Il existe aussi une deuxième nomenclature des nuances d’acier, dite numérique, moins couramment utilisée.

**Facteur de massiveté** 

Pour une structure en acier, cette grandeur, exprimée en m[–[1](83_1._le_nettoyage_de_fin_de_chantier.md)] , exprime le rapport entre la surface exposée au feu et le volume de la structure. Le facteur de massiveté influence le comportement au feu des structures acier : plus une structure est massive et mieux elle résistera au feu. 

**Protection au feu des structures acier** 

Une structure en acier peut être protégée au feu, en vue d’obtenir la stabilité au feu exigée par la réglementation, grâce à plusieurs procédés : 

- flocage, si les contraintes esthétiques l’autorisent ;

- encoffrement ;

- peinture intumescente ;

- poteaux ronds remplis de béton. 

**Galvanisation** 

La galvanisation de l’acier est un procédé consistant à recouvrir l’acier d’une couche protectrice, par passage dans un bain de zinc. Il existe deux procédés : 

- la galvanisation en continu, qui produits des bobines d’acier galvanisé destiné à être prélaqué ;

- la galvanisation à chaud ou au trempé, qui consiste à tremper entièrement les pièces (poutre, garde-corps, etc.) dans un bain de zinc à 450° C. 

**Pour en savoir plus sur les structures métalliques** 

Consulter le site [http://www.construiracier.fr/](http://www.construiracier.fr/).

**Granulats** 

Les granulats (en anglais _aggregates_ ) sont les matériaux inertes rentrant dans la composition des bétons. Il peut s’agir de fragments de roches concassés, de galets résultant de l’érosion, ou d’un matériau artificiel (par exemple, laitiers sidérurgiques). 

Par ordre de dimensions croissantes, les granulats peuvent être des fillers, des sablons, des sables, des graves, des gravillons ou du ballast. 

**Sables utilisés pour la fabrication des bétons** 

Le béton peut être réalisé à partir de deux types de sables : 

- les sables alluvionnaires, provenant de rivières, dont les grains sont relativement ronds et lisses, pauvres en fines et peu adhérents au ciment ;

- les sables de carrière, dont les grains sont relativement anguleux et rugueux, riches en fines, adhérant mieux au ciment. Les sables alluvionnaires sont les plus couramment utilisés, mais on peut tout à fait faire des bétons à partir de sable de carrière en adaptant les formulations, comme c’est le cas dans certaines régions françaises. À long terme il n’y aura plus en France de sables alluvionnaires, et on devra nécessairement utiliser des sables de carrière. 

Pour les impacts écologiques de l’exploitation du sable, consulter le chapitre 4. 

**Classes d’exposition** 

Les dix-huit classes d’exposition du béton sont utilisées pour préciser à quels types d’agressions l’ouvrage sera soumis durant la vie du bâtiment, notamment vis-à-vis de la carbonatation et du gel[[3](85_3._les_opr.md)] ~~.~~ Un béton immergé en mer doit être plus résistant qu’un béton utilisé pour un simple voile intérieur en habitation ; ce sont ces conditions d’utilisation que précisent les classes d’exposition du béton. 

Les classes d’exposition sont désignées par des sigles : XF1, XC1, XC2, XS1, etc. Le choix de la classe d’exposition n’est pas sans incidence sur l’impact carbone du béton : les bétons plus performants ont un plus fort impact carbone.

- les « bétons de retour » (l’excédent qui reste dans une toupie après la livraison) ;

- les bétons issus de chantiers de déconstruction, qui constituent des volumes plus importants. On concasse les bétons de déconstruction à recycler, puis on extrait grâce à des aimants les armatures (déferraillage), qu’on recycle. On obtient alors des granulats de béton recyclé, de dimensions variables, et par criblage des sables recyclés. 

Actuellement, on traite ces granulats comme des « mauvais » granulats, utilisables uniquement pour des chaussées et remblais et peu utilisés dans le bâtiment pour des usages nobles. 

C’est le phénomène du _downcycling_ : les granulats recyclés sont utilisés pour un usage moins noble que les granulats naturels. Comment faire pour que ces granulats recyclés soient utilisés dans des bétons nobles, et économiser ainsi des granulats naturels « nobles » ? C’était l’objet du projet de recherche Recybéton (2012-2018). 

Le projet Recybéton a montré que l’utilisation de granulats recyclés était possible, avec certaines précautions en ce qui concerne les quantités mises en œuvre : 

Les granulats recyclés sont plus poreux que les granulats naturels, car ils contiennent du ciment en plus des granulats. Cette porosité va s’amplifier à long terme au cours des cycles successifs de recyclage. 

L’utilisation de 100 % de granulats recyclés est possible mais, pour obtenir les mêmes propriétés, on est obligé de mettre davantage de ciment, et on détériore le bilan carbone du béton (du fait du fort impact carbone du ciment). Cette contrainte oblige à limiter les proportions de granulats recyclés incorporés. 

On peut donc retenir que l’utilisation des granulats recyclés est à favoriser, tout en respectant des proportions limites. 

**Pour en savoir plus sur Recybéton** 

Consulter [www.pnrecybeton.fr](http://www.pnrecybeton.fr).

**Plancher collaborant** 

Un plancher collaborant est constitué d’un bac acier sur lequel est coulée une dalle en béton. Grâce à des connecteurs, le bac acier participe (collabore) à la résistance du béton. L’acier étant situé en sous-face, il travaille en traction, alors que le béton, situé au-dessus, travaille en compression. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0475-02.png]]

Figure 84. Principe d’un plancher collaborant. 

**Dalle** 

On confond souvent dalle, dallage et chape. Une dalle est un plancher béton porteur. 

**Dallage** 

Le dallage, au contraire, n’est pas porteur : il s’appuie de manière continue sur le sol. Il peut être en béton armé ou non armé. 

**Chape** 

Une chape est une couche de mortier destinée à aplanir ou niveler et à recevoir une couche supérieure. Elle n’est pas armée. 

**Cure du béton** 

La cure du béton consiste à protéger un béton qui vient d’être coulé contre les intempéries. La cure vise à limiter l’évaporation de l’eau à la surface du béton sous l’effet du vent et du soleil, pendant la phase de prise et de durcissement. Elle permet d’éviter le faïençage et la fissuration des bétons. Le béton jeune doit aussi être protégé de la pluie.

- pulvérisation fréquente d’eau,

- application de toiles imbibées d’eau,

- protection contre le soleil par des contreplaqués,

- ruissellement d’eau sur un mur ;

- par temps froid : protection du béton contre le gel par des matériaux isolants ;

- application d’un produit de cure au pulvérisateur. La cure est appliquée entre un et quinze jours suivant les cas. Cette étape clé, qui concerne aussi dallages et chapes, est souvent négligée dans les petits chantiers à faible technicité, entraînant de nombreux sinistres. 

**Boîte d’attente** 

Une boîte d’attente est une réservation dans un mur en béton, contenant des aciers en attente repliés. Ces aciers, une fois dépliés, sont utilisés pour être liaisonnés à un nouvel ouvrage : plancher ou voile béton perpendiculaire. Les aciers sont initialement pliés, pour permettre la mise en place du coffrage du mur. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0476-03.png]]

Figure 85. Boîte d’attente, avant sa mise en œuvre. Les arceaux seront noyés dans le mur en béton.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0477-00.png]]

Figure 86. Après décoffrage du mur, les aciers repliés sur l’autre face de la boîte sont dépliés. 

**Plat carbone** 

Les plats carbone sont des plaques de très forte résistance, utilisées pour renforcer ponctuellement une structure béton en rénovation. Les plaques sont collées sur la structure béton, et sont équivalentes à l’ajout d’acier dans le béton. Cette solution de haute technologie, assez surprenante _a priori_ , est particulièrement simple d’utilisation. 

**Pour en savoir plus** 

Consulter le site d’un fabricant, comme [http://fra.sika.com](http://fra.sika.com), produit Sika CarboDur. 

#### 1.4. Vocabulaire des structures bois 

Il existe plusieurs manières de classer les systèmes constructifs bois. Une typologie couramment utilisée distingue quatre grandes familles : 

##### 1.4.1. La technique dite** _**structure à ossature bois**_ **, ou** _**ossature plateforme 

C’est la technique traditionnelle la plus utilisée en construction bois de petite et moyenne hauteur, héritière des colombages. Elle utilise de petites

- côté extérieur par une étanchéité à l’eau (pare-pluie) et un parement ;

- et côté intérieur par un pare-vapeur et un parement intérieur de finition. Entre les montants bois on insère une isolation thermique et acoustique (là où la construction traditionnelle utilisait différents types de torchis). La préfabrication de panneaux ou même de modules tridimensionnels est courante. 

##### 1.4.2. La technique dite** _**structure poteau-poutre 

Cette technique implique des pièces de fortes sections, souvent en lamellécollé, et des assemblages de charpentier. L’espacement entre les poteaux permet de libérer de l’espace au sol sans poteau intermédiaire. 

##### 1.4.3. La technique** _**structure masse 

Cette technique traditionnelle utilise des bois massifs empilés (madriers, fustes…), comme dans les chalets traditionnels. 

##### 1.4.4. Les** _**panneaux bois contrecollés**_ **, ou** _**panneaux bois lamellé-croisés 

En anglais CLT : _cross laminated timber_ , ces panneaux sont utilisables en planchers, murs ou supports de toiture en grandes dimensions et sont en plein développement. 

Ces panneaux sont constitués de planches en bois massif empilées en couches croisées à 90° et collées entre elles sur toute leur surface, ce qui leur confère de grandes qualités structurelles. Ils simplifient le chantier grâce à la préfabrication et à leurs grandes dimensions. 

Les panneaux CLT ont été créés en 1947 et utilisés dans les années 1950 par Jean Prouvé. Ils sont notamment fabriqués par l’entreprise autrichienne

**Binderholz.** 

Les panneaux fabriqués par l’entreprise autrichienne KLH bénéficient en France d’avis techniques du CSTB, ce qui permet de rester en « techniques courantes » vis-à-vis des assureurs, à conditions de respecter strictement les conditions d’utilisation prévues à l’avis technique. 

Les panneaux CLT et KLH sont maintenant couramment utilisés en France pour constituer la structure bois de bâtiments en R+[1](83_1._le_nettoyage_de_fin_de_chantier.md), R+[2](84_2._les_autocontrôles_et_essais.md) ou R+3. Certains pionniers ont même atteint [10](92_10._la_commission_de_sécurité_en_erp.md) étages (Angleterre et Australie). Il existe une production française de panneaux CLT, qui peut être préférée pour favoriser les circuits courts. 

**Pour en savoir plus sur les panneaux bois contrecollés** 

Pour une information sur les panneaux KLH, consulter [www.klh.at/fr](http://www.klh.at/fr) et [www.lignatec.fr](http://www.lignatec.fr). Pour une information sur les panneaux CLT, consulter [www.binderholz.com](http://www.binderholz.com). 

_Pour en savoir plus sur les structures bois, et pour trouver un BET Structure Bois_ 

Consulter le site du Comité national pour le développement du bois, [www.cndb.org](http://www.cndb.org). Les anglophones pourront consulter le passionnant _Masse timber building science primer_ du Mass Timber Institute de l’université de Toronto sur [https://](https://academic.daniels.utoronto.ca) [academic.daniels.utoronto.ca](https://academic.daniels.utoronto.ca), en gardant à l’esprit que tout le pan réglementaire du sujet diffère entre le Canada et la France. 

**Pour en savoir plus sur les critères environnementaux dans le choix des bois tropicaux** 

Consulter le site de l’Association technique internationale des bois tropicaux : [www.atibt.org/fr](http://www.atibt.org/fr), et notamment son _Guide pratique à l’usage des acheteurs publics – Concevoir et mettre en œuvre une politique d’achat bois responsable_ . 

_… les critères déterminants pour le choix d’une essence de bois_ Quelles sont les caractéristiques à prendre en compte lors du choix d’une essence de bois ? Elles sont extrêmement nombreuses :

- La disponibilité est bien entendu un critère de choix important.

- Le prix entre forcément en jeu ; ainsi en bois de structure les feuillus indigènes (chêne…) sont actuellement bien plus onéreux en prix de fourniture que les résineux, couramment utilisés

- La région de provenance est essentielle en termes d’impact carbone : bois indigènes (si possible du bois local) à préférer aux bois d’importation ; on consultera les FDES quand elles existent.

- Le mode de gestion des forêts et sa traçabilité : label PEFC ou le récent label Bois de France.

- Les propriétés physiques :

  - L’humidité du bois ou teneur en eau ;

  - La « stabilité du bois en service » et son retrait volumique, qui caractérisent son évolution dimensionnelle dans le temps ; on parle aussi de rétractabilité (à titre d’exemple, le pin maritime et le hêtre sont peu stables alors qu’à l’opposé le noyer est très stable) ;

  - La masse volumique peut être importante si l’on souhaite limiter le poids d’un élément ; elle varie du balsa (160 kg/m[[3](85_3._les_opr.md)] ) à l’azobé ([1](83_1._le_nettoyage_de_fin_de_chantier.md) 070 kg/m[3] ).

- Les caractéristiques de résistance mécanique sont essentielles, on distingue :

  - La contrainte de rupture en compression axiale (de [9](91_9._la_prononciation_de_la_réception.md) MPa pour le balsa à 110 MPa pour l’ipé) ;

  - La contrainte de rupture en flexion parallèle aux fibres (de [15](97_15._archivage_en_fin_de_chantier.md) MPa pour le balsa à 227 MPa pour l’azobé) ;

  - Le module d’élasticité longitudinale en flexion (de [5](87_5._problématiques_liées_aux_lots_techniques.md) 140 MPa pour le balsa à 26 610 MPa pour le cumaru), qui caractérise la déformation des éléments travaillant en flexion (poutres, solives, etc.) ;

  - La résistance aux chocs en flexion dynamique ;

  - La dureté Brinell parallèle aux fibres, qui mesure la résistance à la pénétration d’une bille d’acier ;

  - La dureté Monnin, qui mesure la résistance à la pénétration d’un cylindre d’acier (du balsa à l’ipé). Ces caractéristiques permettent de classer les bois en bois durs (par exemple le chêne), bois mi-durs (par exemple le hêtre), bois tendres ou blancs (par exemple le peuplier), bois résineux et bois fruitiers (par exemple le noyer).

- Le type d’emploi de l’essence : charpente et structure, parquet ou parquet à lourd trafic, mobilier urbain, bardage, menuiserie extérieure, menuiserie intérieure, lambris, meubles et ébénisterie, contreplaqué, moulure, placage décoratif.

- Le pH du bois peut être important si le bois est en contact avec un métal dont il risque d’entraîner la corrosion (par exemple le douglas, de pH 2.9, donc acide, peut entraîner la corrosion d’une couverture zinc qu’il supporterait ; à l’opposé le frêne a un pH de [6](88_6._les_dossiers_des_ouvrages_exécutés_doe.md)).

- La durabilité du bois, naturelle ou conférée par traitement, qui caractérise la résistance du bois aux champignons et aux insectes lignivores. La norme NF EN 335 distingue différentes _classes d’emploi_ du bois, en fonction des risques d’exposition à l’humidité : 

||**Classe d’emploi des bois (simplifié)**|**Classe d’emploi des bois (simplifié)**||
|---|---|---|---|
|**[1](83_1._le_nettoyage_de_fin_de_chantier.md)**|**[2](84_2._les_autocontrôles_et_essais.md)**|**[3](85_3._les_opr.md)**|**[4](86_4._le_rôle_du_bureau_de_contrôle_pour_la_réception_du_chantier.md)**|
|Intérieur,<br>entièrement<br>protégé<br>des<br>intempéries.|Intérieur ou sous<br>abri protégé des<br>intempéries, hum​<br>ifica​tion occ​asio​<br>nne​lle<br>(con​den​<br>sat​ion).|Sans<br>contact<br>avec<br>le<br>sol,<br>soumis<br>à<br>une<br>hum​idif​ica​tion<br>fréquente.<br>Séchage complet<br>entre<br>deux<br>périodes<br>d’hu​<br>mifi​cat​ion.|Extérieur<br>en<br>contact avec le<br>sol ou support à<br>hum​idif​icat​ion<br>récurrente<br>ou<br>immersion dans<br>l’eau douce, hum​<br>idif​icat​ion<br>très<br>prononcée.|

Il est préférable d’éviter les résineux traités en autoclave, car ce traitement utilise des produits chimiques, injectés sous pression

dans le bois. Préférer, lorsque la classe d’emploi le nécessite, des résineux naturellement résistants, comme le douglas, qu’on utilise sans traitement chimique. Les spécialistes utilisent le Fascicule de documentation FD P20-651 _Durabilité des éléments et ouvrages en bois_ , qui donne la liste des essences utilisables pour chaque durabilité, dans la classe d’emploi. En bâtiment, on vise souvent la durabilité « L2 ». 

- La facilité d’usinage (sciage, perçage, etc.).

- La réaction au feu ; suivant la stabilité au feu attendue, les assemblages nécessitent une attention particulière, et peuvent faire l’objet de justifications par le calcul, sans nécessiter forcément d’ATex ; même une stabilité R60 peut sans problème être obtenue si nécessaire, en protégeant les assemblages bois/bois par un encoffrement en panneaux de bois et en traitant les ferrures de pied à la peinture intumescente.

- La résistance thermique. 

##### 1.4.5. Quelques points de vigilance pour les projets bois 

Le projet bois nécessite plus de matière grise en conception, mais le chantier est plus rapide qu’un projet béton. Du fait des contraintes incendie, pour les immeubles de belle hauteur les spécialistes recommandent maintenant souvent des structures mixtes plutôt que tout bois. 

Les retours d’expérience[[4](86_4._le_rôle_du_bureau_de_contrôle_pour_la_réception_du_chantier.md)] menés par l’AQC sur les projets bois de plus de [8](90_8._consignes_de_sécurité_incendie_et_plans_associés.md) m de hauteur (typiquement des immeubles d’habitation de [3](85_3._les_opr.md)[e] famille) ont permis d’identifier des recommandations intéressantes, notamment : 

- s’entourer, dès le début des études, de compétences spécialisées en construction bois, capables de justifier la conformité réglementaire des procédés auprès du contrôleur technique grâce à une bonne connaissance du champ réglementaire (DTU, avis techniques disponibles…) ; ces compétences arrivent souvent trop tard sur les projets, et il y a un réel risque de se trouver en dehors du champ des techniques courantes, et donc non assuré, sans même en avoir conscience ; 

- s’entourer d’un spécialiste en sécurité incendie des structures bois ; une étude d’ingénierie feu peut en outre s’avérer nécessaire ;

- s’entourer d’un acousticien doté d’un logiciel adapté aux projets bois ; du fait de sa plus faible inertie, le bois est moins favorable acoustiquement que le béton ; un soin particulier doit donc être accordé aux aspects vibratoires et acoustiques ;

- demander au maître d’ouvrage de choisir un bureau de contrôle ayant un référent bois dans ses équipes ;

- éviter au maximum en phase conception de sortir du champ des techniques courantes. En cas de nécessité, prévoir un ou au maximum deux procédés sortant des techniques courantes (ATEx), pas davantage ;

- associer les assureurs aux éventuelles dérogations aux techniques courantes (déclaration et accord préalable), pour éviter les surprimes, voire les non-couvertures ;

- si l’on sort du champ des techniques courantes, prévoir dans le planning le délai nécessaire à l’ATEx ;

- optimiser les épaisseurs de planchers, qui peuvent être supérieures à celles des projets béton, et recourir si nécessaire au bonus de constructibilité pour compenser la hauteur supérieure du bâtiment ;

- vérifier que la conception assure une bonne étanchéité à l’eau et une bonne gestion des transferts de vapeur d’eau à travers les parois ;

- pour limiter les interfaces qui peuvent complexifier les études d’exécution, préférer des macrolots (ou une entreprise générale) aux corps d’état séparés ;

- éviter les variantes des entreprises ou les faire valider par tous les BET, y compris acoustique et sécurité incendie ;

- demander au CCTP un prototype, de bonnes dimensions ;

- **Pour en savoir plus sur la construction bois** 

Utiliser les trois ouvrages fondamentaux suivants, disponibles sur [www.codifab.fr](http://www.codifab.fr) :

- le _Guide de conception des ouvrages bois exposés aux intempéries_ , 2022 ;

- le Guide pratique _Construction bois et gestion de l’humidité en phase chantier_ , 2020 ;

- l’Appréciation de laboratoire « Bois Construction et propagation du feu par les façades », 2020. 

#### 1.5. Vocabulaire des fondations 

##### 1.5.1. Les fondations superficielles, ou ordinaires 

Elles sont utilisées quand le « bon sol » est peu profond, pour les petits bâtiments présentant de faibles descentes de charges : au maximum deux étages sur rez-de-chaussée. Elles sont généralement constituées par une semelle en béton armé, posée sur un béton de propreté et sur laquelle s’appuie le soubassement du bâtiment. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0484-06.png]]

Figure 87. Constitution d’une fondation superficielle.[[5](87_5._problématiques_liées_aux_lots_techniques.md)] 

Les _semelles_ peuvent être :

- des semelles _filantes_ , c’est-à-dire disposées linéairement sous un mur, encore appelées semelles continues ;

- des semelles _isolées_ ou _ponctuelles_ placées sous un poteau ou sous un mur, circulaires, carrées ou rectangulaires. La _hauteur d’encastrement_ est l’épaisseur minimale des terres au-dessus du point bas de la fondation. Si elle est surmontée d’un dallage, il est pris en compte dans la hauteur d’encastrement. L’ _ancrage_ est la profondeur de la semelle dans la couche porteuse du « bon » sol. 

Les fondations superficielles doivent respecter une profondeur minimale d’encastrement pour éviter l’influence du gel. C’est la notion de _protection contre le gel_ des fondations. En effet, le sol superficiel subit des déformations lors du gel et du dégel, déformations qui endommageraient les ouvrages s’ils n’étaient pas fondés hors gel. La profondeur minimale des fondations vis-à-vis de ce critère va de 50 cm en zone tempérée à [1](83_1._le_nettoyage_de_fin_de_chantier.md) m en zone montagneuse.[[6](88_6._les_dossiers_des_ouvrages_exécutés_doe.md)] Le type de sol est aussi à prendre en compte : certaines argiles présentent des risques de retrait et de gonflement, ce qui nécessite un enfouissement plus important. 

Un _radier général_ est une semelle de béton armé de grandes dimensions, qui porte tout ou une partie d’un ouvrage. Il est bien adapté aux cas des sols de faible portance et exempts de points durs (anciennes fondations). Un _puits de fondation_ est un massif de gros béton sur lequel vient se poser la semelle sous poteau ou sous mur. 

Les _longrines_ sont des poutres béton pouvant relier des fondations, qui servent de semelle et sur lesquelles on élève les maçonneries. Les _dés_ de fondations sont de petites fondations cubiques qui portent un élément (poteau) et l’isolent de la terre. 

**Problématique de l’interaction entre fondations** 

La proximité d’un projet avec des fondations existantes est à prendre en compte dans le choix du type de fondations, les fondations à créer peuvent provoquer des poussées et des désordres sur des fondations existantes, si elles sont trop proches.

Si l’on n’est pas familiarisé avec les Eurocodes, consulter le DTU 13.1 Fondations superficielles, ou Ménad Chenaf et Nicolas Ruaux, _Fondations – Conception, dimensionnement et réalisation – Maisons individuelles et bâtiments assimilés_ , CSTB. 

##### 1.5.2. Les fondations profondes et semi-profondes 

**Les fondations par micropieux** 

Les micropieux sont des fondations très courantes, de diamètre de forage inférieur à 25 cm. Ils sont extrêmement élancés (une longueur de 20 m est courante) et travaillent grâce à leur frottement latéral, en compression ou en traction. Ils ont été introduits en France dans les années 1960 par une entreprise italienne. 

Ils sont par exemple utilisés :

- dans les locaux difficiles d’accès dans l’existant, car le matériel nécessaire est peu encombrant : on peut même travailler dans un soussol de [2](84_2._les_autocontrôles_et_essais.md) m sous plafond ;

- pour des reprises en sous-œuvre ;

- pour les confortements de fondations existantes ;

- pour des fondations de petits ouvrages : fosses d’ascenseurs, pylônes, poteaux (par exemple de mezzanines), voiles ;

- pour des fondations de petits bâtiments ;

- pour les fondations de radiers soumis à des sous-pressions. 

Pour les réaliser, on pratique un forage tubé, dans lequel on insère une armature qui est ensuite scellée par injection de coulis de ciment. Puis le micropieu est solidarisé avec la superstructure qu’il supportera.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0487-00.png]]

Figure 88. Exemple de groupe de micropieux. 

Il existe plusieurs types de micropieux[[7](89_7._le_rôle_du_coordonnateur_sps_pour_la_réception_du_chantier.md)] (outre le type I qui n’est plus utilisé en France) :

- pour réaliser les micropieux de type II, le coulis de ciment est injecté de manière gravitaire ;

- pour les types III, il est injecté sous pression depuis la tête du micropieu, comme pour un tirant ;

- pour les types IV, il est injecté à une pression supérieure, en commençant par le bas et en remontant de manière répétitive. Il existe de nombreuses autres variantes. Les micropieux ne pouvant pas reprendre de moments fléchissants, ils sont souvent implantés par groupes de deux (sous un voile) ou trois (sous un poteau), ce qui résout le problème de la reprise des moments. 

**Pour en savoir plus sur les micropieux** 

Consulter la norme NF EN 14199 Exécution des travaux géotechniques spécieux

- Micropieux.

**Les fondations par pieux** 

Ces fondations de diamètre plus important peuvent être battues (avec refoulement du sol) ou forées (sans refoulement du sol). Elles sont utilisées pour les bâtiments de plusieurs niveaux ou des ouvrages divers, sur des terrains de mauvaise qualité. 

**Pieux mis en place avec refoulement du sol** 

Les _pieux battus_ sont des pieux en bois (dans le passé), en béton, en coulis, en fonte ou en acier, mis en place par battage, avec refoulement du sol. Leur mise en place comprime le sol le long du fût, ce qui permet de bénéficier d’un frottement maximal. On les appelle aussi _pieux façonnés à l’avance_ ou _préfabriqués_ . 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0488-04.png]]

Figure 89. Pieux en bois (d’après _Dico TP_ ). 

Jusqu’au XIX[e] siècle, les pieux étaient en bois et battus grâce à la force humaine : une trentaine d’hommes pouvait être nécessaire. Les pieux étaient battus jusqu’à refus, c’est-à-dire jusqu’à ce que l’enfoncement soit presque nul.

Les pieux en bois (notamment en robinier, bois indigène parmi les plus durs) sont actuellement l’objet d’un regain d’intérêt dans le monde de la construction écologique du fait de leur faible empreinte carbone. Les pieux en bois sont notamment utilisés pour des bâtiments de faible hauteur (édicules, bâtiment en rez-de-chaussée). La contrainte majeure limitant leur utilisation est l’alternance eau/air dans la zone de variation annuelle de la nappe phréatique : les pieux en bois sont pérennes à sec ou immergés en permanence comme à Venise, mais ils finissent par se dégrader sous l’action des variations de niveau de nappe. Ils sont donc à réserver aux terrains hors nappe phréatique. Les _pieux foncés_ sont mis en place par vérinage et bénéficient eux aussi de la compression du sol refoulé. 

Les _pieux à tube battu exécutés en place_ sont constitués de tubes épais d’acier, obturés à leur base, battus à refus dans le sol, puis remplis de béton. Le tube est retiré au fur et à mesure du bétonnage. Ils sont considérés comme pieux battus car il n’y a pas d’extraction de terrain. En termes de disposition, on peut rencontrer des pieux isolés, des groupes de pieux, ou des palplanches en béton. 

**Pour en savoir plus sur les pieux avec refoulement du sol** 

Consulter la norme NF EN 12699 Exécution des travaux géotechniques spécieux

- Pieux avec refoulement du sol. 

**Pieux mis en place sans refoulement des sols** 

Les _pieux forés_ sont réalisés en béton, coulé dans un forage.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0490-00.png]]

Figure 90. Pieu foré : principe d’exécution (d’après _Dico TP_ ). 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0490-02.png]]

Figure 91. Réalisation d’un pieu foré, fondation d’un immeuble.

**Pour en savoir plus sur les pieux forés** 

Consulter la norme NF EN 1536 Exécution des travaux géotechniques spécieux

- Pieux forés. 

Les _puits de fondations_ , méthode ancienne, consistent à creuser le sol pour y couler une fondation en gros béton (ou, dans le passé, en pierres). Pieux forés et puits sont réalisés par substitution, en creusant le sol, qui a donc tendance à se décomprimer. Les frottements obtenus sont donc moins importants, mais certaines méthodologies de réalisation des pieux forés permettent d’augmenter la rugosité, par exemple pour les pieux vissésmoulés. 

Dans cette même « famille », on classe les barrettes et les parois moulées, en béton, qui peuvent jouer le rôle de fondations, de soutènement et d’étanchéité. 

Les _barrettes_ sont utilisées pour reprendre des charges importantes, avec des efforts horizontaux ou des moments à reprendre, par exemple pour un grand immeuble. Elles peuvent avoir une section rectangulaire, ou en T, ou en croix (+). 

Les _parois moulées_ sont des ouvrages linéaires directement bétonnés dans un sol excavé, après mise en place dans une tranchée d’une cage d’armature. La stabilité provisoire de la tranchée est assurée par l’injection de boues spéciales. Les parois moulées sont notamment utilisées pour réaliser des sous-sols, typiquement des parkings, dans la nappe phréatique. Elles sont alors aussi utilisables comme fondations pour des étages de superstructure. 

**Pour en savoir plus sur les parois moulées** 

Consulter la norme NF EN 1538 Exécution des travaux géotechniques spécieux

- Parois moulées.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0492-00.png]]

Figure 92. Principe de réalisation d’une paroi moulée. 

Dans les milieux urbains à proximité d’avoisinants, les sous-sols sont réalisés suivant la technique dite en _down_ ou en taupe permettant d’assurer en permanence le butonnage des parois, et donc d’éviter tout risque pour les immeubles voisins. 

On appelle _recépage_ des pieux ou micropieux l’opération qui consiste à éliminer le béton de mauvaise qualité qu’on trouve en tête des pieux en béton. En effet, au fur et à mesure qu’on coule le béton des pieux, un mélange d’eau, de boue, de béton et d’éboulis se forme, qui est refoulé vers la surface. Ce mélange ne présente pas les qualités mécaniques requises et il doit être éliminé : c’est l’opération de recépage. Cette étape, qui nécessite des méthodes destructrices, n’est pas toujours facile à réaliser sur le terrain. Dans le cas des pieux métalliques battus, l’opération de recépage consiste cette fois à couper la partie supérieure du pieux, qui a été fissurée par le battage.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0493-00.png]]

Figure 93. Réalisation d’une paroi moulée :

- excavation.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0493-02.png]]

Figure 94. Réalisation d’une paroi moulée :

- pose des armatures.

##### 1.5.3. Les soutènements 

Les _parois berlinoises_ sont des ouvrages de soutènement réalisés par des profilés métalliques mis en place dans des forages et scellés en pied. Des planches en bois ou des plaques métalliques sont mises en place au fur et à mesure entre les profilés supports (variante béton possible, dite _paroi parisienne_ ). Les profilés sont maintenus par des tirants ou des butons. 

Elles peuvent être utilisées en phases provisoires ou plus rarement en définitive, pour participer aux fondations ou servir d’écrans étanches, mais généralement hors de la nappe phréatique, contrairement aux parois moulées. 

Des _palplanches_ métalliques peuvent constituer une alternative pour assurer un soutènement en phase chantier. L’expression « par passes alternées » (parfois aussi désigné « reprise en touches de piano ») désigne un terrassement réalisé par tranches verticales d’une largeur d’un mètre ou plus, pour que les efforts de poussée des terres puissent se reporter sur le terrain non excavé de part et d’autre de l’excavation réalisée. Dans une deuxième phase d’intervention, après avoir renforcé la zone déjà excavée, on traite les zones non excavées. 

**Les tirants, provisoires ou définitifs** 

Ils sont constitués de câbles sous tension ancrés dans le terrain. Les tirants provisoires ne posent pas de problème particulier, mais les tirants définitifs sont sources de problèmes de maintenance à long terme. Ils sont donc à éviter dans les bâtiments. 

##### 1.5.4. Les techniques de renforcement des sols 

Les sols de qualité médiocre peuvent être renforcés par des _colonnes ballastées_ , des _inclusions rigides_ (préfabriquées ou réalisées _in situ_ ), des _géotextiles_ ou du _jet grouting_ . 

**Le** _**jet grouting** 

Ce procédé de renforcement des sols utilise un jet de fluide projeté à haute vitesse pour déstructurer un terrain et le mélanger avec un coulis liquide. Il ne s’agit pas exactement d’une technique d’injection, mais plutôt d’un

procédé de mélange terrain-coulis visant à former un « béton de sol » in situ dans la masse du terrain. L’idée du _jet grouting_ est née au Royaume-Uni à la fin des années 1950. Ce procédé est encore assez peu courant en France et ne peut être mis en œuvre que par des sociétés très spécialisées. 

#### 1.6. Les Eurocodes 

Avant les Eurocodes, les calculs des structures étaient régis en France principalement :

- par le règlement BAEL 91 pour le béton armé ;

- par les règles CM66 pour les structures métalliques, avec leur additif de 1980 ;

- en marchés publics par des fascicules du Cahier des clauses techniques générales (CCTG) de l’État ;

- par les règles de calcul DTU relatives aux structures ;

- par les règles N 84 Action de la neige ;

- par les règles NV 65 Action du vent ;

- par les règles PS92 de construction parasismique. 

Afin de faciliter l’accès des bureaux d’études de chaque pays au marché européen, la Commission européenne a uniformisé les règles de calcul Structure en créant les Eurocodes, normes Structure unifiées s’appliquant aux bâtiments et au génie civil. Ce travail de normalisation avait commencé dans les années 1970 au sein de diverses associations professionnelles, et fut développé dans les années 1980 par la Commission. 

Le programme de rédaction et d’approbation des Eurocodes s’est achevé en 2005 ; ils sont donc maintenant tous opérationnels et leur utilisation est obligatoire dans les marchés publics.[[8](90_8._consignes_de_sécurité_incendie_et_plans_associés.md)] 

Les Eurocodes ont remplacé les anciennes règles de calcul nationales, par

**Point de vigilance** 

En pratique, les Règles de calculs neige et vent sont encore souvent utilisées par les professionnels pour certains éléments non structurels, comme le lot Couverture, par soucis de simplicité. 

Certains paramètres, dits paramètres déterminés nationalement (PDN), sont fixés par chaque pays et constituent l’annexe nationale des Eurocodes pour le pays. Ces annexes nationales comprennent notamment les paramètres de sécurité, les sollicitations climatiques, le choix des méthodes de calcul, etc. Les Eurocodes comportent des annexes informatives, qui présentent des méthodes d’application facultative, pas toujours pleinement validées. En France, c’est le CSTB qui publie les Eurocodes avec l’annexe nationale française. Il existe au total 58 Eurocodes, comprenant près de [5](87_5._problématiques_liées_aux_lots_techniques.md) 000 pages, regroupés en [10](92_10._la_commission_de_sécurité_en_erp.md) familles :

- Eurocode 0 : Bases de calcul des structures (NF EN 1990, [2](84_2._les_autocontrôles_et_essais.md) normes) ;

- Eurocode [1](83_1._le_nettoyage_de_fin_de_chantier.md) : Actions sur les structures (NF EN 1991, 10 normes) ;

- Eurocode 2 : Calcul des structures en béton (NF EN 1992, [4](86_4._le_rôle_du_bureau_de_contrôle_pour_la_réception_du_chantier.md) normes) ;

- Eurocode [3](85_3._les_opr.md) : Calcul des structures en acier (NF EN 1993, 20 normes) ;

- Eurocode 4 : Calcul des structures mixtes acier-béton (NF EN 1994, 3 normes) ;

- Eurocode 5 : Conception et calcul des structures en bois (NF EN 1995, 3 normes) ;

- Eurocode [6](88_6._les_dossiers_des_ouvrages_exécutés_doe.md) : Calcul des ouvrages en maçonnerie (NF EN 1996, 4 normes) ;

- Eurocode [7](89_7._le_rôle_du_coordonnateur_sps_pour_la_réception_du_chantier.md) : Calcul géotechnique (NF EN 1997, 2 normes) ;

- Eurocode [8](90_8._consignes_de_sécurité_incendie_et_plans_associés.md) : Calcul des structures pour leur résistance aux séismes (NF EN 1998, [6](88_6._les_dossiers_des_ouvrages_exécutés_doe.md) normes) ;

- Eurocode [9](91_9._la_prononciation_de_la_réception.md) : Calcul des structures en aluminium (NF EN 1999, [5](87_5._problématiques_liées_aux_lots_techniques.md) normes). Chaque famille d’Eurocode est constituée d’une partie générale (partie [1](83_1._le_nettoyage_de_fin_de_chantier.md)-1), d’une partie concernant le comportement au feu (partie 1-[2](84_2._les_autocontrôles_et_essais.md)), d’une partie 2 concernant les ponts (le cas échéant) et d’autres parties spécifiques. Chaque Eurocode est référencé par un nom du type NF EN 19- -, par exemple NF EN 1992-1-1 pour les règles générales du calcul des structures en béton. La liste à jour des Eurocodes peut être consultée sur le site Internet de l’Afnor, mais leur téléchargement est payant. 

**Point de vigilance** 

Ce corpus constitue un ensemble cohérent, avec des méthodes unifiées pour tous les ouvrages. Ces textes ne doivent jamais être « panachés » avec les règles antérieures. On ne doit notamment jamais citer dans un même CCTP à la fois un Eurocode et une règle de calcul antérieure, comme le BAEL 91. 

#### 1.7. Qu’est-ce qui a changé avec les Eurocodes ? 

La création des Eurocodes aura été une entreprise de longue haleine, rendue complexe par le poids des traditions nationales dans un domaine de forte technicité. 

La transition vers l’utilisation par tous des Eurocodes ne va pas non plus sans difficulté, tant sont grandes les habitudes. 

Les lignes qui suivent présentent les enjeux des modifications essentielles introduites par les Eurocodes dans les principaux domaines.[[9](91_9._la_prononciation_de_la_réception.md)] 

**L’Eurocode 0 et la durée d’utilisation du projet** 

L’Eurocode 0 – _Bases des calculs des structures_ a introduit une notion nouvelle, la durée d’utilisation du projet. Il distingue des catégories de durée d’utilisation de projet :

|**Catégorie de durée**<br>**d’utilisation de projet**|**Durée indicative**<br>**d’utilisation de projet**<br>**(années)**|**Exemples**|
|---|---|---|
|||Structures provisoires|
|[1](83_1._le_nettoyage_de_fin_de_chantier.md)|||
||[10](92_10._la_commission_de_sécurité_en_erp.md)||
|[2](84_2._les_autocontrôles_et_essais.md)|[10](92_10._la_commission_de_sécurité_en_erp.md) à 25|Éléments structuraux<br>remplaçables (poutres de<br>roulement, appareils<br>d’appui)|
|[3](85_3._les_opr.md)|[15](97_15._archivage_en_fin_de_chantier.md) à 30|Structures agricoles et<br>assimilées|
|[4](86_4._le_rôle_du_bureau_de_contrôle_pour_la_réception_du_chantier.md)|50|Structures de bâtiments et<br>autres structures<br>courantes|
|[5](87_5._problématiques_liées_aux_lots_techniques.md)|100|Structures monumentales<br>de bâtiments, ponts et<br>autres ouvrages de génie<br>civil|

**En général, on retient la catégorie [4](86_4._le_rôle_du_bureau_de_contrôle_pour_la_réception_du_chantier.md) pour le Bâtiment.** 

**Les bétons et l’Eurocode [2](84_2._les_autocontrôles_et_essais.md)** 

Quelles sont les principales différences introduites par l’Eurocode [2](84_2._les_autocontrôles_et_essais.md) pour le calcul des bétons ? Le fonctionnement du béton reste bien sûr le même, et les quantités de béton et d’acier sont peu modifiées, mais le formalisme de justification change un peu par rapport au BAEL. Le volume des études permettant de justifier l’ouvrage augmente un peu dans de nombreux cas, d’où la nécessité de se faire confirmer l’utilisation des Eurocodes quand on missionne un bureau d’étude. 

Le clivage entre béton armé et précontraint disparaît : l’Eurocode [2](84_2._les_autocontrôles_et_essais.md) traite des deux cas. Une nouveauté introduite par les Eurocodes est la plus grande attention à l’exigence de _durabilité_ des bétons en fonction de la catégorie de durée d’utilisation de projet. Cette catégorie a des conséquences sur les enrobages et sur le contrôle de l’ouverture des fissures, ce qui peut conduire à une légère réduction des coûts. La durabilité souhaitée pour le béton peut influer sur le choix du type de béton, d’où la nécessité de préciser les hypothèses retenues.

**La construction acier et l’Eurocode [3](85_3._les_opr.md)** 

Pour la construction en acier, l’Eurocode [3](85_3._les_opr.md) est beaucoup plus « moderne », novateur, complet, mais aussi plus complexe que les règles antérieures CM66. Il représente un corpus énorme de près de 900 pages. 

Par rapport aux CM66, l’Eurocode [3](85_3._les_opr.md) comprend de très nombreuses règles détaillées et expliquées. Il définit de nombreuses classifications, qui permettent de choisir la meilleure méthode pour chaque cas. Il traite une grande quantité de cas qui étaient absents des CM66. Sur beaucoup de points, l’Eurocode 3 est également plus précis que les CM66. Par ailleurs, il propose dans de nombreux cas des variantes de calcul intéressantes. 

**Les structures bois suivant l’Eurocode [5](87_5._problématiques_liées_aux_lots_techniques.md)** 

Contrairement au béton et à l’acier, les structures bois n’étaient pas auparavant calculées suivant l’approche « semi-probabiliste » utilisée dans les Eurocodes et caractérisée par l’étude d’états limites (ELS et ELU). C’est donc une approche radicalement nouvelle pour la filière bois massif et lamellé-collé, approche dont le but est d’optimiser les structures. Jusqu’à présent, la conception des structures bois était basée sur le concept de contrainte admissible. Il n’existait pas de texte de référence unique, mais un ensemble de règles un peu éparpillées, autour des règles dites CB 71. 

La vocation de l’Eurocode [5](87_5._problématiques_liées_aux_lots_techniques.md) est de remplacer les règles de calcul antérieures ; il n’a pas pour vocation d’être utilisé par les artisans utilisant le bois de manière traditionnelle en maison individuelle ou pour de petits ouvrages, sans calculs de justification et grâce à un surdimensionnement sécuritaire. Ce sont bien les bureaux d’études bois qui effectuaient _déjà_ des calculs qui doivent s’adapter aux nouvelles règles de calcul. 

A priori, l’introduction des concepts d’états limites dans le domaine de la conception bois peut paraître fastidieuse aux BET. Elle présente cependant des avantages : 

- elle prend mieux en compte les paramètres pouvant jouer sur la solidité et sur la pérennité des structures bois et devrait donc limiter les pathologies ;

- elle permet de choisir entre une approche optimisée et une approche simple et robuste ;

- **L’Eurocode [6](88_6._les_dossiers_des_ouvrages_exécutés_doe.md) et les structures en maçonneries** 

Cet Eurocode restera d’une utilisation marginale, comme le DTU 20.1 qu’il remplace, car il est rare qu’on calcule des maçonneries de manière réellement structurelle. 

**L’Eurocode [8](90_8._consignes_de_sécurité_incendie_et_plans_associés.md) et les études parasismiques** 

Pour les calculs sismiques, il y a beaucoup d’analogie avec les règles de calcul antérieures. Mais l’Eurocode est plus détaillé ; il permet de choisir entre plusieurs options et de calculer des coefficients pour coller au plus près à la situation réelle. 

Ce sont surtout les données d’entrée du calcul qui ont été bouleversées (voir ce qui suit). 

#### 1.8. Enjeux de la construction parasismique 

**Une discipline bouleversée en 2010 par l’arrivée d’un nouveau zonage** La réglementation française a évolué en 2010, en parallèle de l’introduction de l’Eurocode 8. Le nombre de communes concernées par les règles parasismiques est passé de [5](87_5._problématiques_liées_aux_lots_techniques.md) 000 à 20 000 : le calcul parasismique est donc devenu obligatoire pour certains bâtiments dans des régions à faible sismicité où les BET n’avaient pas l’habitude de l’appliquer, par exemple en Bretagne. 

Le nouveau zonage[[10](92_10._la_commission_de_sécurité_en_erp.md)] définit cinq zones de sismicité, de la zone [1](83_1._le_nettoyage_de_fin_de_chantier.md) de très faible sismicité à la zone [5](87_5._problématiques_liées_aux_lots_techniques.md) particulièrement exposée (Antilles). Ce n’est pas l’Eurocode qui a introduit le nouveau zonage : l’Eurocode est une méthode de calcul, qui utilise le zonage comme donnée d’entrée. Pour chaque zone de sismicité, l’arrêté définit l’accélération maximale de référence à prendre en compte dans les calculs, agr.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0501-00.png]]

Figure 95. Zonage sismique de la France. 

Il est important d’être sensibilisé à cette évolution de la réglementation, car il arrive qu’elle soit négligée par certains BET par manque d’habitude, dans les zones à faible sismicité. Trois critères entrent en jeu pour définir les actions sismiques à prendre en

**compte :** 

- la zone de sismicité ;

- le type de sol ;

- le type de bâtiment. 

**L’impact de la nature du sol** 

La nouvelle approche est basée sur des retours d’expérience, qui ont montré l’impact de la nature du sol, prise en compte par un nouveau coefficient S (paramètre de sol) dans l’Eurocode : le risque sismique est diminué sur les bons sols (rocheux) alors que les mauvais sols (meubles) sont pénalisés. L’Eurocode [8](90_8._consignes_de_sécurité_incendie_et_plans_associés.md) distingue ainsi cinq classes de sol, de A à E. 

**Les catégories d’importance de bâtiments** 

La réglementation[[11](93_11._la_levée_des_réserves.md)] a introduit des catégories d’importance de bâtiment, en fonction de leur vulnérabilité. 

|**Catégorie d’importance des**<br>**bâtiments**|**Description**|
|---|---|
|I|Bâtiments dans lesquels il n’y a aucune<br>activité humaine nécessitant un séjour<br>de longue durée.|
|II|–<br>Habitations individuelles.<br>–<br>ERP de catégories [4](86_4._le_rôle_du_bureau_de_contrôle_pour_la_réception_du_chantier.md) et [5](87_5._problématiques_liées_aux_lots_techniques.md) hors<br>établissements scolaires.<br>–<br>Habitations collectives de hauteur<br>inférieure à 28 m.<br>–<br>ERT de hauteur inférieure à 28 m et<br>de moins de 300 personnes.<br>–<br>Parcs de stationnements ouverts au<br>public.|

|III|–<br>ERP de catégories [1](83_1._le_nettoyage_de_fin_de_chantier.md), [2](84_2._les_autocontrôles_et_essais.md) et 3.<br>–<br>Habitations collectives et bureaux de<br>hauteur supérieure à 28 m.<br>–<br>Bâtiments pouvant accueillir plus de<br>300 personnes.<br>–<br>Établissements sanitaires et sociaux.<br>–<br>Centres de production collective<br>d’énergie (à partir de certains seuils).<br>–<br>Établissements scolaires.|
|---|---|
|IV||
||–<br>Bâtiments indispensables à la sécurité<br>civile, la défense nationale et le<br>maintien de l’ordre public.<br>–<br>Bâtiments assurant le maintien des<br>communications, la production et le<br>stockage d’eau potable, la<br>distribution publique de l’énergie.<br>–<br>Bâtiments assurant le contrôle de la<br>sécurité aérienne.<br>–<br>Établissements de santé nécessaires à<br>la gestion de crise.<br>–<br>Centres météorologiques.|

À chaque catégorie d’importance de bâtiment est associé un coefficient qui vient moduler l’action sismique.[[12](94_12._les_modalités_financières_de_lachèvement_des_travaux.md)] 

**Les données d’entrée des calculs** 

En zone sismique, les bâtiments doivent être en mesure d’encaisser des actions sismiques, qui sont principalement des mouvements brusques horizontaux (accélérations du sol rocheux).[[13](95_13._la_déclaration_attestant_lachèvement_et_la_conformité_des_travaux_daact.md)] Ceci peut obliger à prévoir des appuis glissants capables d’encaisser ces

**mouvements.** 

**Les règles de calcul dans le neuf** 

L’Eurocode [8](90_8._consignes_de_sécurité_incendie_et_plans_associés.md) est la règle de calcul de base pour les BET. Mais pour certaines constructions simples, les BET ont le droit d’utiliser des règles simplifiées, les règles PS-MI « Construction parasismique des maisons individuelles et bâtiments assimilés »[[14](96_14._synthèse_des_principaux_documents_liés_à_lachèvement_du_chantier.md)] ~~,~~ basées sur des règles forfaitaires. L’arrêté précise, et c’est là l’essentiel, dans quel cas un calcul sismique doit être effectué, et suivant quelles règles : 

|**Zone de**<br>**sismicité**|**Catégories d’importance des bâtiments**|**Catégories d’importance des bâtiments**|**Catégories d’importance des bâtiments**|**Catégories d’importance des bâtiments**|
|---|---|---|---|---|
||I||||
|||II|III|IV|
|Zone [1](83_1._le_nettoyage_de_fin_de_chantier.md)||Aucune|exigence||
|Zone [2](84_2._les_autocontrôles_et_essais.md)|Aucune|exigence|Eurocode [8](90_8._consignes_de_sécurité_incendie_et_plans_associés.md) et<br>annexes<br>nationales<br>obligatoires|Eurocode 8 et<br>annexes<br>nationales<br>obligatoires|
|Zone [3](85_3._les_opr.md)|Aucune<br>exigence|Règles PS-MI<br>possibles|Eurocode [8](90_8._consignes_de_sécurité_incendie_et_plans_associés.md) et<br>annexes<br>nationales<br>obligatoires|Eurocode 8 et<br>annexes<br>nationales<br>obligatoires|
|Zone [4](86_4._le_rôle_du_bureau_de_contrôle_pour_la_réception_du_chantier.md)||Règles PS-MI<br>possibles|Eurocode [8](90_8._consignes_de_sécurité_incendie_et_plans_associés.md) et<br>annexes<br>nationales<br>obligatoires|Eurocode 8 et<br>annexes<br>nationales<br>obligatoires|
|Zone [5](87_5._problématiques_liées_aux_lots_techniques.md)||Règles CP-MI<br>possibles|Eurocode [8](90_8._consignes_de_sécurité_incendie_et_plans_associés.md) et<br>annexes<br>nationales<br>obligatoires|Eurocode 8 et<br>annexes<br>nationales<br>obligatoires|

Les étapes successives de l’étude parasismique, qui consistent dans un premier temps à déterminer des paramètres puis à les utiliser dans le calcul, peuvent se résumer par le schéma suivant.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0505-00.png]]

Figure 96. Paramètres de l’étude parasismique. 

**Qu’en est-il des bâtiments existants ?** 

Si des travaux importants sont réalisés sur l’existant, il peut être nécessaire de prendre en compte les actions sismiques, avec toutefois une minoration de l’action sismique par rapport au cas du neuf. Les cas d’application dans l’existant dépendent notamment[[15](97_15._archivage_en_fin_de_chantier.md)] :

- de la zone de sismicité ;

- de la catégorie d’importance du bâtiment ;

- de la surface de plancher éventuellement créée ;

- de la surface de plancher éventuellement supprimée ;

- et de l’éventuel souhait du maître d’ouvrage d’améliorer son niveau de sécurité. L’arrêté distingue les éléments structuraux du bâti existant (murs, planchers, etc.) et les éléments non structuraux (cheminées, cloisons, éléments de façade, plafonds suspendus, etc.). 

**… la liquéfaction des sols** 

Dans certaines conditions, les vibrations provoquées par un séisme conduisent à la perte totale de la résistance du sol, qui se comporte alors comme un liquide. C’est ce qu’on appelle le phénomène de

**liquéfaction des sols, bête noire des BET Structure.** 

Ce phénomène a des effets ravageurs : glissement de terrain, rupture de barrage, basculement d’immeubles. Un des objectifs du calcul parasismique est de se prémunir contre ces phénomènes. Toutefois, la liquéfaction ne peut être provoquée par un séisme que dans certains types de sols sableux ou argileux. 

**Pour en savoir plus sur la construction parasismique** 

Le site [planseisme.fr](http://planseisme.fr) ayant été supprimé, on se rabattra sur le site du BRGM ([www.brgm.fr](http://www.brgm.fr)), qui renvoie lui-même vers tout un ensemble de sites plus détaillés. Consulter sur le site du Ministère ([www.ecologie.gouv.fr](http://www.ecologie.gouv.fr)) :

- le guide _Dimensionnement parasismique des éléments non structuraux du cadre bâti_ , édition 2014,

- le guide _Diagnostic et renforcement du bâti existant vis-à-vis du séisme_ , édition 2013. 

#### 1.9. Zoom sur la suspension antivibratile des bâtiments 

La suspension antivibratile est une méthode permettant de protéger les locaux des vibrations. 

**Dans quels cas faut-il se poser la question de l’éventuelle nécessité d’une suspension antivibratile ?** 

Pour tout projet situé à proximité d’une ligne de métro, d’une voie ferrée ou d’une autre source potentielle de vibrations importantes (voie rapide routière par exemple). En effet, ces vibrations risquent de générer un inconfort pour les usagers. Cet inconfort est tout particulièrement à éviter pour certains types de programmes : habitations, hôtels, bureaux, salles de spectacles, et certains locaux sensibles comme des salles informatiques. Ces vibrations qu’on cherche à éviter ne sont pas forcément bruyantes, et elles ne doivent pas être confondues avec la problématique des nuisances sonores.

Pour tout projet comportant un tel risque de nuisances vibratoires, la première étape consiste à lancer un diagnostic par un acousticien, afin de quantifier les risques de nuisances. Ce diagnostic consiste à réaliser des mesures vibratoires sur le site, et à en déduire le niveau vibratoire qui sera subi par le futur bâtiment. 

**Choisir la technologie antivibratile** 

Pour éviter la transmission au futur bâtiment des vibrations du site, la solution consiste à le « mettre sur ressorts », ce qui le désolidarise de l’infrastructure vibrante, en atténuant les vibrations sur une zone de fréquences vibratoires. Cette mise sur ressorts est réalisée grâce à plusieurs technologies :

- les tapis en polyuréthane ;

- les boîtes à ressorts. 

La coupure acoustique, qui est la surface séparant les locaux « nobles » (habitations, hôtels, bureaux,…), à protéger, et les locaux non protégés (commerces, locaux techniques, parkings, fondations), est décrite par le BET Structure suivant les préconisations de l’acousticien. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0507-04.png]]

Figure 97. Exemple de délimitation d’une coupure acoustique entre une zone de parking souterrain et une zone de bureaux.

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0508-00.png]]

Figure 98. Exemple de coupure acoustique réalisée par des boîtes à ressort insérées entre un rez-de-chaussée et un premier étage. Cette coupure présente un certain encombrement : on pourra retenir qu’en amont de l’étude acoustique il faut réserver à titre de mesure conservatoire [1](83_1._le_nettoyage_de_fin_de_chantier.md) m verticalement et [15](97_15._archivage_en_fin_de_chantier.md) cm horizontalement sur tout le pourtour du bâtiment. Aussi étonnant que cela puisse paraître, les boîtes à ressorts peuvent nécessiter un remplacement à long terme. Cette opération est réalisée en positionnant des vérins de part et d’autre de la boîte, et en « soulevant » le bâtiment pendant le remplacement de la boîte à ressorts. 

**Pour en savoir plus** 

Consulter le site du principal fabricant de boîtes à ressorts : [www.gerb.com](http://www.gerb.com), et pour les tapis antivibratiles : [www.angst-pfister.com](http://www.angst-pfister.com) 

**1.10. Construction et risque d’explosion** Un autre cas où une expertise Structure spécialisée peut être nécessaire est**
