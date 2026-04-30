---
type: document-section
document_id: maitre-oeuvre-batiment-guide-pratique
section_id: "section:2"
ordre_document: 17
titre: "le relevé de géomètre"
aliases:
  - Maître d'oeuvre bâtiment — Hamburger 2023 — 17 le relevé de géomètre
resume_section: |-
  ### 2. Le relevé de géomètre
  
  Le maître d’ouvrage doit fournir les plans du site existant. Le maître d’œuvre, dans son devoir de conseil, peut recommander un relevé de géomètre, essentiel pour éviter des erreurs aux conséquences graves (accessibilité, structure, évacuation, etc.). Les plans cadastraux ne remplacent pas un relevé topographique précis.
  
  Pour des projets simples, les architectes peuvent réaliser eux-mêmes les relevés, mais cela engage leur responsabilité. Les géomètres utilisent des technologies avancées (scan 3D, drones) pour produire des relevés adaptés aux besoins BIM, souvent sous formats REVIT ou AutoCAD. Le cahier des charges des relevés est généralement rédigé par l’AMO BIM et doit préciser le niveau de détail requis.
  
  Les systèmes géodésiques et de nivellement modernes (RGF93, Lambert 93, IGN69) sont obligatoires depuis 2009 pour les échanges publics en France. Leur adoption garantit précision et compatibilité, bien que des systèmes anciens soient encore utilisés, notamment à Paris. Il est crucial de vérifier et documenter les systèmes utilisés pour éviter des erreurs coûteuses.
document_parent: "[[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/index|Maître d'oeuvre bâtiment — Hamburger 2023 — Index]]"
section_precedente: "[[16-le-programme|le programme]]"
section_suivante: "[[18-les-diagnostics-amiante-et-plomb|les diagnostics amiante et plomb]]"
tags: [document-section, ouvrage, gestion-projet, maitrise-oeuvre, estimation]
sources: ["17_2._le_relevé_de_géomètre.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [appel-doffres, execution-projet, technique]
autorite: [pratique, reference]
juridictions: [france, generique]
familles_sources: [ouvrage, gestion-projet]
---
### 2. Le relevé de géomètre 

La fourniture d’un fond de plan du site et en rénovation, de plans, coupes et élévations de l’existant, est une obligation du maître d’ouvrage. Demander un relevé de géomètre de l’existant fait partie des _devoirs de conseil_ du maître d’œuvre. 

Les conséquences pour un projet d’une erreur de plan de géomètre peuvent être catastrophiques financièrement : une erreur de géométrie peut remettre en cause l’accessibilité aux personnes en situation de handicap, les calculs structurels du projet, les dégagements d’évacuation incendie, etc. La surface de plancher du projet peut être directement ou indirectement impactée. 

Les plans cadastraux ne peuvent en aucun cas pallier l’absence de relevé topographique d’un terrain, car ils sont bien souvent inexacts outre leur très faible niveau de précision. 

Néanmoins, pour les opérations les moins complexes (rénovation d’un appartement ou d’une maison), il est d’usage que les architectes réalisent eux-mêmes, dans le cadre de leur mission, le tracé des existants, soit manuellement comme dans le passé, soit grâce à des outils numériques. La difficulté est de savoir jusqu’où peut aller le maître d’œuvre dans ce sens, car la prise en charge du relevé des existants, outre la charge de travail qu’elle représente, constitue une prise de responsabilité importante, qui peut avoir de graves conséquences juridiques.

Consulter le site d’un prestataire, comme [www.measurix.com](http://www.measurix.com). Un télémètre laser est connecté à une tablette graphique. Le fichier obtenu peut servir de base à une maquette numérique BIM. 

Le maître d’œuvre ne doit pas prendre un géomètre en sous-traitance, le relevé des existants étant du ressort du maître d’ouvrage. Mais il peut être amené à préparer pour son client le cahier des charges des relevés de géomètre, ce qui lui permet d’obtenir des relevés conformes à ses besoins. Les cabinets de géomètre utilisent des technologies modernes de relevés de nuages de points par scan 3D. Il existe même des techniques de relevé des espaces extérieurs par drone. 

**Pour en savoir plus sur les outils des géomètres** 

Consulter le site d’un des fabricants les plus en pointe, Viametris, qui conçoit des appareils intégrant un système de cartographie mobile, scanner laser et traitement de la donnée : [www.viametris.com](http://www.viametris.com). 

#### 2.1. Monter le cahier des charges des relevés de géomètre dans un projet BIM 2.1.1. La consistance des relevés 

En projet neuf sans démolitions, le géomètre relèvera la topographie du site avec, le cas échéant, la volumétrie des avoisinants. Dans le cas d’un projet dans l’existant, le géomètre relèvera tout ou partie du bâtiment tous niveaux ainsi que les élévations extérieures si nécessaire. Dans le cas de bâtiments à démolir, le niveau de détail des relevés est plus faible. 

##### 2.1.2. Quel format informatique pour les livrables du géomètre ? 

Le géomètre peut fournir un fichier nuage de points ; mais il est très difficilement exploitable par la majorité des maîtres d’œuvre.

**Le format informatique attendu du géomètre dépend du type de projet :** 

**

- Pour un projet dans l’existant, le livrable attendu du géomètre est typiquement une maquette numérique de l’existant, généralement sous forme de fichier REVIT et ifc.

- Pour un projet neuf sur un terrain nu, le plan topographique pourra être livré sous la forme d’un fichier AutoCAD, il n’est pas indispensable que le géomètre établisse un fichier REVIT et ifc ; la maquette numérique du projet neuf viendra ensuite « s’inscrire » sur ce relevé topographique en le plaçant dans un fichier « container ».

- Pour un projet neuf dans un environnement d’avoisinants, il peut être intéressant de demander au géomètre de fournir une maquette numérique volumétrique des avoisinants, en plus de la topographie du terrain à construire.

- Enfin dernière configuration possible, plus rarement rencontrée : le géomètre peut fournir le nuage de point et le maître d’œuvre peut assurer en mission complémentaire la création de la maquette numérique des existants. Cette prestation un peu technique, qui sort bien sûr de la mission de base, est réalisable par certains maîtres d’œuvre formés à cet exercice. 

**Point de vigilance** 

Actuellement tous les cabinets d’experts géomètres n’ont pas la compétence de créer la maquette numérique de l’existant. Certains refusent de réaliser cette prestation ; d’autres, insuffisamment expérimentés, proposent cette prestation puis livrent des maquettes mal structurées et inexploitables. 

##### 2.1.3. Qui rédige le cahier des charges géomètre dans les projets BIM ? 

Dans les projets BIM, le cahier des charges du géomètre est souvent rédigé par l’AMO BIM du maître d’ouvrage.

Le cahier des charges doit veiller à lister le degré de détail des relevés souhaités. Par exemple dans l’existant, il convient de préciser si le géomètre doit relever les radiateurs, les sens d’ouverture des portes, les corniches en coupe, les chéneaux, ou pour un bâtiment historique de préciser s’il doit relever les modénatures des façades, les statues, etc. Penser aussi à demander le relevé des poutraisons apparentes et, en extérieur, des regards, des plaques d’égouts et autres émergences de réseaux enterrés. 

##### 2.1.4. Autres missions du géomètre 

Outre les relevés classiques, un géomètre peut se voir confier d’autres missions, par exemple :

- état de division en volume, pour officialiser la limite entre plusieurs propriétaires ou concessionnaires ;

- bornage de terrain, pour matérialiser sur le terrain les limites cadastrales ;

- relevé des émergences de réseaux existants, avec leur direction, par ouverture des regards, tampons et chambres de tirage existants ;

- relevé de réseaux enterrés par différents procédés de détection, avec indication des classes de précision au sens de la réglementation DT/ DICT ;

- relevé complémentaire après déposes, dans les projets dans l’existant : la géométrie est relevée après les déposes de second œuvre ;

- contrôle de l’absence de mouvement des existants ou des avoisinants lors de chantiers sensibles (auscultation). 

##### 2.1.5. Vers l’automatisation des maquettes de l’existant

Le processus qui permet de passer d’un nuage de points brut à la maquette numérique intelligente d’un bâtiment existant est complexe ; à ce jour, il n’existe pas de logiciel le réalisant automatiquement de manière satisfaisante. Il est clair que dans les prochaines années les progrès en intelligence artificielle permettront d’automatiser cette prestation dite _scanto-BIM_ . Les enjeux sont énormes et une telle automatisation révolutionnerait les projets dans l’existant. 

La question est, à partir du nuage de points : 

- d’identifier la _géométrie_ des constituants du bâtiment : quelle est la forme de cette fenêtre ?

- d’attribuer une _catégorie d’objets_ et des _propriétés_ à chaque élément : cet objet est une fenêtre à deux vantaux (on ne pourra cependant pas identifier toutes les caractéristiques : fabricant, référence, etc.) ;

- d’identifier les _relations_ entre les objets : cette fenêtre est connectée à ce mur sur tout son pourtour.[[3](85_3._les_opr.md)] Même dans le meilleur des cas, les structures et réseaux non visibles ne pourront cependant pas être modélisés automatiquement. 

###### 2.1.5.2. Le** _**scan-vs-BIM 

Une technologie connexe en plein développement elle aussi consiste à comparer un nuage de points scanné avec une maquette numérique BIM. Cette technologie émergente, quand elle sera mûre, présentera plusieurs intérêts majeurs : 

- caractériser l’avancement physique d’un chantier lot par lot, en comparant les ouvrages en cours de construction à la maquette numérique d’exécution : des automates sur chenilles pourront parcourir le chantier et des drones le survoler, puis transmettre directement l’avancement physique pour chaque ligne de la DPGF ; 

- vérifier la cohérence de la maquette numérique DOE au bâtiment livré, et corriger si nécessaire la maquette DOE.

#### 2.2. Les systèmes de coordonnées des relevés de géomètre – Vocabulaire de topographie 

L’intérêt de connaître quelques notions de base en topographie est :

- de bien renseigner ses cartouches, en évitant d’y faire figurer des indications fantaisistes, comme c’est fréquemment le cas ;

- de comprendre et maîtriser les problèmes de SCU AutoCAD ;

- d’éviter des confusions entre systèmes de nivellement, confusions qui peuvent être catastrophiques dans un projet si elles ne sont pas détectées rapidement. 

Exemple : le maître d’œuvre reçoit en donnée d’entrée un plan issu d’un ancien système de nivellement sans avoir conscience de cette particularité. Dans le cadre de son projet, il prend en compte le plan de prévention des risques d’inondation localement applicable. Ce PPRI comporte des cotes dans le système de nivellement moderne, IGN69. Le maître d’œuvre réalise esquisse, APS, APD et PC sans se rendre compte de la confusion. Lorsqu’il s’en aperçoit, ce peut être tout un pan du projet qui est à réadapter pour mise en conformité au PPRI ! 

##### 2.2.1. Connaître le système RGF93 et les projections associées 

Les plans de géomètre, de même que les cartes géographiques, utilisent un système géodésique et un système de projection. Le _système géodésique_ est le repère orthonormé tridimensionnel utilisé. En France, le système géodésique officiel est le « RGF93 » (réseau géodésique français). Il a remplacé l’ancien système géodésique NTF (nouvelle triangulation de la France) utilisé de la fin du XIX[e] siècle à la fin du XX[e] siècle. Le RGF93 est cohérent avec le système européen officiel, le _European Terrestrial Reference System_ – ETRS89. 

Des plans AutoCAD sont _géoréférencés_ s’ils sont rattachés au même système de coordonnées dans le plan, ce qui les rend aisément superposables (par insertion en référence externe).

Le _système de projection_ permet de représenter sur une surface plane le relief tridimensionnel de la Terre. Il existe différents types de projections, en particulier les projections cylindriques et les projections coniques. _Lambert 93_ est le système moderne de projection associé au système géodésique RGF93. Il a remplacé les anciens systèmes de projection Lambert, c’est-à-dire : 

- les anciennes projections « Lambert zones » (I : Nord, II : Centre, III : Sud et IV : Corse) ;

- et une projection unique pour la France entière qui était appelée « Lambert II étendu » ou « Lambert II cartographique ». Outre Lambert 93, il existe un autre ensemble de projections modernes dites « coniques conformes 9 zones », pouvant être associées au système géodésique RGF93. Ces projections sont couramment utilisées en bâtiment. (Voir ci-dessous le zoom sur ce sujet.) 

Le nouveau système géodésique RGF93 présente un certain nombre d’avantages :

- il est directement compatible avec les observations GPS, sans calculs de conversion ;

- il permet une plus grande précision des mesures, grâce à l’exploitation des données GPS, et en évitant les sources d’imprécisions qui provenaient des conversions dans les anciens systèmes de coordonnées ;

- il est cohérent avec les systèmes géodésiques des autres pays européens (dit ETRS), ce qui facilite notamment les projets transfrontaliers ;

- il couvre toute la France, alors que l’ancien système la divisait en neuf zones, ce qui posait des problèmes de discontinuité aux frontières entre les zones. 

Depuis 2009[[4](86_4._le_rôle_du_bureau_de_contrôle_pour_la_réception_du_chantier.md)] ~~,~~ l’utilisation de ce système de coordonnées moderne est obligatoire pour tous les échanges de données dans la « sphère publique » en France métropolitaine. Il doit être utilisé par l’État, les collectivités locales et les entreprises chargées d’une mission de service public.

Par extension, tous les maîtres d’ouvrage et maîtres d’œuvre ont très fortement intérêt à travailler eux aussi dans ce nouveau système de coordonnées légal. 

Il existe des formules et des logiciels de conversion permettant de transformer un ancien fichier dans le nouveau système de repérage. Il est cependant conseillé de confier cette conversion à un géomètre. 

**Point de vigilance** 

À Paris, les services de la Ville continuent souvent à utiliser l’ancien système de coordonnées, malgré son caractère « illégal », car la transformation de tous les plans de l’existant est complexe. Ils empirent ainsi le problème, en créant de nouveaux fichiers non conformes aux nouvelles règles. 

**Savoir reconnaître dans quel système géodésique a été établi un plan AutoCAD** 

Normalement le cartouche du fichier donne la réponse, mais en cas de doute, une indication intéressante est donnée par le nombre de chiffres des coordonnées X et Y des points du fichier AutoCAD : 

- si les coordonnées X et Y ont sept chiffres avant la virgule, on est dans le nouveau système RGF93 ;

- si les coordonnées X et Y ont six chiffres avant la virgule, on est dans un système de coordonnées antérieur au décret de 2006 ; l’ancien système nécessitait de diviser la France en un certain nombre de zones (d’où le nom Lambert zones) du fait de cette limitation à six chiffres, alors que le nouveau système couvre toute la France métropolitaine ;

- si les coordonnées X et Y ont trois, quatre ou cinq chiffres avant la virgule, on est dans un système local de coordonnées. 

**Pour en savoir plus** 

Consulter la rubrique Réseaux matérialisés / Géodésie / RGF 93 sur le site Internet de l’IGN, [https://geodesie.ign.fr/](https://geodesie.ign.fr/).

**projections coniques conformes 9 zones** 

Le décret autorise, outre l’usage de la projection Lambert 93, l’utilisation d’autres projections, dites coniques conformes 9 zones, elles aussi associées au système géodésique moderne RGF93. Qu’est-ce que ce système de projection alternatif et à quels usages estil destiné ? Dans les deux systèmes de projection, les objets sont localisés au même endroit, mais le système de projection officiel Lambert 93 introduit une _altération linéaire_ des longueurs dans certains départements, particulièrement en Corse, dans les Pyrénées-Orientales, dans le Nord et le Pas-de-Calais. Cette altération linéaire peut atteindre dans ces départements 1 m/km, donc 10 cm sur un bâtiment de 100 m de longueur. Les systèmes de projection coniques conformes 9 zones permettent d’éviter cette altération linéaire, raison pour laquelle ils restent tolérés officiellement malgré les réticences de l’IGN, qui encourage l’utilisation de la projection Lambert 93, standard officiel. Comment choisir entre les deux systèmes ? La projection Lambert 93 est parfaite pour les cartographes, les géographes et les travaux VRD. Pour les projets bâtiment, l’altération linéaire qu’elle entraîne est gênante dans de nombreux départements. La décision est normalement du ressort du maître d’ouvrage, car elle impacte la cohérence de ses fichiers à long terme, surtout s’il s’agit d’un maître d’ouvrage gérant plusieurs sites. On peut cependant retenir que le standard est Lambert 93 mais que, dans de nombreuses régions, les coniques conformes sont mieux adaptées aux projets bâtiments. Demander conseil à son géomètre et, en cas de doute, utiliser les coniques conformes. 

**Pour en savoir plus** 

Voir les articles sur ce sujet sur [http://geodesie.ign.fr](http://geodesie.ign.fr).

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0427-00.png]]

Figure 72. L’altération linéaire en Lambert 93 aux chefs-lieux de départements (source : Certu). 

##### 2.2.2. Les systèmes de nivellement 

Les systèmes de nivellement, ou systèmes altimétriques, permettent de donner l’altimétrie d’un point du plan. Historiquement, le niveau 0 a d’abord été au XIX[e] siècle le niveau de la Méditerranée, choisie pour ses faibles marées, dans l’anse Calvo à Marseille. Le premier nivellement général de la France a été réalisé par Paul Adrien Bourdalouë (1798-1868) de 1857 à 1864. Le second nivellement général a été établi de 1884 à 1922 par Charles Lallemand (1857-1938), avec un « zéro » basé sur l’observation du « maréographe » sur l’échelle du fort Saint-Jean de Marseille. Le système de nivellement légal est actuellement le système IGN 1969 en France métropolitaine, parfois appelé « NGF IGN 69 » (comme « nivellement général de la France »), dont le « zéro » est toujours basé sur le maréographe de Marseille.

En Corse, on utilise le NGF IGN 78, basé sur le maréographe d’Ajaccio. Attention, on pourra encore rencontrer les systèmes de nivellement antérieurs lors des consultations de plans d’archive : 

- le système de nivellement _orthométrique Lallemand_ , aussi appelé _nivellement Ville de Paris_ , utilisé notamment sur tout le territoire français pendant la première moitié du XX[e] siècle, diffère d’environ 33 cm du nivellement IGN 69 ;

- le système de nivellement _Bourdalouë_ , utilisé à partir de 1857. 

**Point de vigilance** 

À Paris, de nombreux acteurs publics utilisent toujours le système de nivellement orthométrique Lallemand/Ville de Paris, et il est courant qu’un projet, même dans le neuf, soit traité dans ce système de nivellement. 

![[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0428-04.png]]

Figure 73. Systèmes de nivellement. 

Les différences à prendre en compte pour Paris pour un même point sont environ :

- 30 cm pour obtenir IGN 69 ;

- système Bourdalouë : + 33 cm pour obtenir IGN 69 ;

- + 64 cm pour obtenir Bourdalouë. système Ville de Paris : 

**En résumé :** 

**Système Système de Système de géodésique projection nivellement**

|**Ancien**|NTF|Lambert zones et<br>Lambert II étendu<br>ou cartographique|Orthométrique<br>Lallemand, aussi<br>appelé Ville de<br>Paris|
|---|---|---|---|
|**Actuel, et légal**<br>**depuis décret de**<br>**2006**|RGF93|||
|||Lambert 93 ou<br>coniques<br>conformes||
||||IGN 69|

En conclusion, **cinq recommandations fondamentales pour éviter les erreurs** : 

- Il faut normalement utiliser le nouveau système géodésique RGF93 projection Lambert 93 ou projections coniques conformes (CC), mais on peut être amené à travailler avec des fichiers existants établis dans les anciens systèmes de coordonnées.

- En altimétrie, il faut normalement utiliser le nivellement IGN 69, mais à Paris on peut être amené à travailler avec des fichiers existants dans l’ancien système de nivellement.

- Toujours vérifier avec soin dans quels systèmes sont établies les données d’entrée, à la fois en coordonnées et en nivellement.

- Veiller à _toujours_ citer précisément le système de coordonnées et le système de nivellement utilisés sur ses propres _cartouches_ .

- Alerter cotraitants, sous-traitants et maître d’ouvrage sur les particularités éventuelles des coordonnées et du nivellement pour éviter toute confusion. 

**Exemples réellement rencontrés de cartouches mal renseignés** 

- « Coordonnées Lambert, nivellement NGF » : Lambert ne signifie rien en soi et on ne sait pas quel est le système de projection utilisé.

- « Coordonnées Lallemand, nivellement normal » : Lallemand est un système de nivellement et non de coordonnées et nivellement normal ne veut rien dire.

- « RGF Lambert 93 CC49 » : Lambert 93 et CC49 sont deux systèmes de projection incompatibles, on ne peut pas être à la fois en projection Lambert 93 et conique conforme. 

**
