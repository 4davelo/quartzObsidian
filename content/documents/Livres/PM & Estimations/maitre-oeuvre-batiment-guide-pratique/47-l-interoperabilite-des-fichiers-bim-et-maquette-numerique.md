---
type: document-section
document_id: maitre-oeuvre-batiment-guide-pratique
section_id: "section:2"
ordre_document: 47
titre: "l’interopérabilité des fichiers : bim et maquette numérique"
aliases:
  - Maître d'oeuvre bâtiment — Hamburger 2023 — 47 l’interopérabilité des fichiers : bim et maquette numérique
resume_section: |-
  ### 2. L’interopérabilité des fichiers : BIM et maquette numérique
  
  Le BIM (_Building Information Modeling_) est une méthode collaborative révolutionnant le secteur du bâtiment. Il repose sur une maquette numérique 3D multidisciplinaire, centralisant les données des différents métiers (architectes, BET, etc.) et évitant les ressaisies. Cette approche améliore l’efficacité, facilite les simulations (thermiques, acoustiques, environnementales, etc.) et optimise la coordination.
  
  Deux modèles de travail existent :
  - **Closed BIM** : environnement fermé utilisant des logiciels d’un même éditeur (ex. Autodesk). Simple mais contraignant en termes de choix de partenaires.
  - **Open BIM** : environnement ouvert basé sur des formats interopérables comme l’IFC, permettant l’utilisation de logiciels variés. Cependant, des problèmes de compatibilité et de bugs persistent.
  
  Le BIM nécessite une organisation rigoureuse, formalisée dans une convention BIM définissant les logiciels, niveaux de développement (_LOD_), et responsabilités (BIM manager, référents BIM). Les niveaux de maturité BIM vont de l’échange de plans 2D (niveau 0) à une collaboration totale sur une maquette unique (niveau 3), bien que ce dernier soit rarement atteint.
  
  Le BIM impacte les phases d’étude, la gestion des fichiers, et les rôles des intervenants. Il est particulièrement utile pour l’exploitation et la maintenance des bâtiments, mais pose des défis pour les PME et la standardisation des formats. Les outils associés (viewers, _clash detection_, logiciels spécialisés) facilitent la gestion et la visualisation des maquettes.
  
  Enfin, le BIM s’étend au CIM (_City Information Modeling_) pour des projets à l’échelle urbaine, bien que cette technologie soit encore émergente.
document_parent: "[[documents/Livres/PM & Estimations/maitre-oeuvre-batiment-guide-pratique/index|Maître d'oeuvre bâtiment — Hamburger 2023 — Index]]"
section_precedente: "[[46-le-classement-informatique-des-documents|le classement informatique des documents]]"
section_suivante: "[[48-organiser-le-deroulement-des-etudes|organiser le déroulement des études]]"
tags: [document-section, ouvrage, gestion-projet, maitrise-oeuvre, estimation]
sources: ["47_2._linteropérabilité_des_fichiers_bim_et_maquette_numérique.md"]
created: 2026-04-30
updated: 2026-04-30
contextes: [appel-doffres, execution-projet, technique]
autorite: [pratique, reference]
juridictions: [france, generique]
familles_sources: [ouvrage, gestion-projet]
---
### 2. L’interopérabilité des fichiers : BIM et maquette numérique 

Le nombre de maîtres d’ouvrage convertis au BIM ne cesse de grandir et l’examen de la situation internationale pousse à penser que le BIM va devenir de plus en couramment exigé. 

Le BIM est un enjeu transverse qui concerne toutes les spécialités. Qu’on soit architecte, BET électricité, planificateur, contrôleur technique, acousticien, cuisiniste, BET bois, directeur travaux, on est concerné par le BIM : aucun métier du bâtiment n’échappe à cette révolution. Même les métiers des VRD, des aménagements extérieurs et des infrastructures sont maintenant concernés, avec de nombreuses recherches sur l’interopérabilité avec le BIM. 

Dans un marché concurrentiel, les compétences en BIM font la différence et ouvrent de nouveaux marchés. Des compétences en BIM peuvent même être très rémunératrices. _A contrario_ le manque de compétences en BIM ferme des marchés, ou oblige à s’entourer de sous-traitants à prix d’or.

L’inconvénient de l’utilisation des logiciels de dessin classiques, comme AutoCAD, c’est que chaque bureau d’étude doit ressaisir les plans architectes dans ses propres logiciels spécialisés : 

- logiciel de calcul thermique ;

- logiciel de calcul Structure ;

- logiciel d’étude de prix, etc. sans parler des prestations plus spécialisées utilisant des logiciels de simulation dynamique, d’acoustique, d’évaluation environnementale, de planification qui nécessitent elles aussi des ressaisies. À chaque modification du plan architecte, l’ensemble des spécialistes doit procéder à une reprise de saisie informatique dans son propre modèle, puis à une reprise de calcul : reprise de calcul thermique, reprise de calcul Structure, reprise de chiffrage, etc. 

Dans les années 80, le ministère de la Défense américain a initialisé une nouvelle méthode de travail, en demandant à ses prestataires de livrer leurs études Bâtiments sous forme d’un unique rendu numérique assemblant tous les métiers, comme c’était déjà le cas à l’époque pour la conception d’un avion. Cette initiative allait donner naissance à l’idée de l’« interopérabilité » des fichiers décrivant le bâtiment, c’est-à-dire la recherche de moyens permettant à tous les spécialistes de partager ou d’échanger des fichiers de travail. **2.2. Principes du BIM** La « maquette numérique » 3D, en anglais _BIM_ ( _Building Information Modeling_ ), est une méthode de travail qui permet à tous les membres de l’équipe de conception de partager les mêmes fichiers, en les enrichissant chacun des informations propres à leur spécialité, et ceci en 3D. 

Dans le travail en BIM, le support de l’étude n’est plus constitué d’un ensemble de plans, spécialité par spécialité (un plan architecte, un plan électrique, un plan Structure, etc.) mais d’un unique _modèle numérique_ multidisciplinaire, la _maquette numérique_ . On peut considérer la maquette numérique comme une grande base de données de l’ensemble des

**caractéristiques du bâtiment.** 

La maquette numérique rassemble des _informations structurées_ sur les composants du bâtiment. Elle est composée d’un ensemble d’ _objets_ (par exemple un mur), appartenant à des _classes d’objets_ . Chaque objet 3D composant le bâtiment n’est pas seulement un ensemble de traits, mais possède des _attributs_ , qui sont des caractéristiques physiques, thermiques, acoustiques, de comportement au feu, etc. : une fenêtre n’est plus représentée dans le fichier par un simple dessin en plan, mais elle est identifiée comme un objet fenêtre, avec des caractéristiques dimensionnelles, thermiques, acoustiques, un prix unitaire et une relation avec un objet mur. 

La base de plans se transforme en une base de données unique et commune. 

Les gains en efficacité sont très importants, en particulier pour l’économiste et les BET. En évitant les ressaisies, on permet aux BET de se consacrer aux vrais sujets de conception et d’optimisation. Un des intérêts du BIM est ainsi de faciliter les simulations métier, réalisées sur des logiciels spécialisés, sans nécessiter de ressaisie des données du projet par exemple : 

- simulations thermiques dynamiques ;

- simulations aérauliques (impact du vent, par exemple au pied d’un IGH) ;

- évaluations environnementales ;

- simulations acoustiques ;

- calculs d’éclairement ;

- ingénierie de désenfumage ;

- simulations de trafic routier en aménagements extérieurs ;

- simulations sismiques ; etc. En plus des données renseignées dans le fichier BIM lui-même, on peut insérer un lien vers un document extérieur, par exemple le pdf de la

documentation fabricant d’un équipement, une fiche technique, une photo. Le BIM peut même gérer le phasage et la planification du chantier, en important un planning et en associant une phase à chaque objet de la maquette numérique. 

La pratique du BIM a révolutionné la manière de travailler dans le bâtiment. De nombreuses fonctionnalités informatiques émergent et les recherches sont en plein boom dans ce domaine. 

Les méthodes BIM ont fait l’objet d’un vaste travail de normalisation internationale, inspiré des normes anglaises. Ce travail a débouché sur la norme ISO 19650. Le vocabulaire utilisé dans cette norme pour désigner les intervenants, les documents et les processus BIM est un peu déroutant au premier abord. Il ne sera pas abordé ici, car il diffère pour l’instant du vocabulaire utilisé en France en matière de BIM. 

Les pays les plus en pointe en matière de BIM sont la Finlande, la Corée du Sud, Singapour (qui a imposé dès 2002 le dépôt d’un fichier ifc avec tout dossier permis de construire), le Royaume-Uni, l’Irlande et les États-Unis (où plus de 80 % des projets sont réalisés en BIM). 

#### 2.3. Les usages du BIM 

Initié par plusieurs organisations professionnelles, le projet _BIM FOR VALUE_ s’est donné pour ambition de formaliser les usages les plus courants du BIM, c’est-à-dire de répondre à la question : le BIM pour quoi faire ? 

Le _Cadre de référence_ BIM FOR VALUE est une boîte à outils méthodologique pour définir les usages du BIM appropriés au type de projet et aux priorités du maître d’ouvrage. C’est donc l’outil idéal de l’AMO BIM. 

En résumé, la méthode propose :

- dans un premier temps d’identifier les _valeurs_ attendues par le maître d’ouvrage :

  - meilleure appropriation du projet ?

  - maîtrise des délais ?

- maîtrise des risques ?

- performance économique accrue ?

- meilleurs services aux usagers ?

- amélioration de la qualité environnementale ?

- dans un second temps la méthode propose de choisir, en fonction de ces valeurs, une liste de _cas d’usages_ possibles du BIM ; pour chacun de ces cas d’usage, la méthode indique les phases du projet concernées, les prérequis, les niveaux d’exigence possibles, les modes de preuve et les moyens nécessaires. Ces cas d’usage proposés par BIM FOR VALUE sont :

  - la définition et la vérification du programme,

  - l’analyse du site – les données d’entrées numérisées du site,

  - la modélisation du site – les données existantes,

  - la communication,

  - les revues de projet,

  - la production des livrables,

  - les études analytiques,

  - l’extraction des quantités et valeurs significatives,

  - la gestion des conflits,

  - le contrôle de conformité aux exigences réglementaires,

  - la modélisation de conception,

- la modélisation des objets,

- la passation des marchés,

- la planification 4D – visualisation de l’avancement,

- l’organisation et coordination TCE,

- le support logistique,

- la modélisation de la constructibilité de l’ouvrage,

- la sécurité sur le chantier,

- le traitement des modifications par rapport aux marchés de travaux,

- l’analyse des performances de l’ouvrage – réception _in situ_ – exploitation,

- les OPR,

- la consolidation du DOE et du DIUO,

- la constitution de l’environnement BIM gestion exploitation maintenance (BIM GEM),

- la gestion des ouvrages et équipements dans l’environnement BIM GEM,

- la constitution de l’environnement BIM pour un ouvrage existant.

**Pour en savoir plus BIM FOR VALUE** 

Consulter le Cadre de référence et son Guide méthodologique sur : www.sma​ rtb​ uil​ din​ gsa​ lli​ ance.​ org/​ pro​ ject/​ cad​ re-​ de-​ ref​ ere​ nce-​ b4v​ .

#### 2.4. Les deux grandes familles de méthodes de travail en BIM : modèle centralisé et modèle de synthèse 

Sous le terme de BIM, on trouve en fait deux méthodes de travail différentes (ainsi que des situations intermédiaires) :

- le modèle centralisé ou _closed BIM_ ,

- et le modèle de synthèse ou _Open BIM_ . 

**2.4.1. Le modèle centralisé ou closed BIM** On désigne par-là l’organisation projet BIM dans laquelle tous les membres de l’équipe de maîtrise d’œuvre utilisent des logiciels d’un même éditeur, logiciels conçus pour permettre le partage de fichiers BIM multidisciplinaires. Dans ce modèle, l’interopérabilité des fichiers est le résultat du travail de recherche-développement de l’éditeur des logiciels. On parle d’environnement fermé. 

La situation la plus courante en France correspond à l’utilisation de logiciels de la sphère Autodesk, c’est-à-dire REVIT et les autres logiciels Autodesk associés. 

Différentes organisations du travail sont possibles :

- soit le projet est découpé en maquettes par métier : une maquette architecte, une maquette structure, une maquette fluides, qui sont assemblées par le BIM manager,

- soit les différents métiers interviennent sur la même maquette, les utilisateurs recevant des autorisations associées à des familles d’objets, suivant leur spécialité (BIM de niveau 3). 

Dans ce modèle de travail fermé, certains spécialistes peuvent être amenés à utiliser un logiciel sortant de la sphère Autodesk. Dans ce cas, ils devront ressaisir les caractéristiques du projet sur leur propre logiciel, à moins qu’un export ne soit possible.

Outre Autodesk, il existe d’autres éditeurs de logiciels qui permettent de travailler de même en BIM en « modèle centralisé », par exemple le logiciel allemand Allplan de Nemetschek (ces éditeurs utilisent le terme d’« Open BIM » pour des raisons commerciales). Dans le cas d’un groupement de maîtrise d’œuvre, travailler en « modèle centralisé » oblige à choisir ses partenaires en fonction des logiciels sur lesquels ils travaillent, ce qui peut être contraignant : si un architecte travaille en BIM sous REVIT, il ne pourra s’associer qu’avec des BET travaillant aussi sous environnement Autodesk. 

_**Pour en savoir plus le modèle centralisé**_ Consulter le site d’Autodesk, [www.autodesk.fr](http://www.autodesk.fr), ou celui de l’éditeur Nemetschek : [www.allplan.com/fr](http://www.allplan.com/fr). 

##### 2.4.2. Le modèle de synthèse ou Open BIM 

**Le principe** 

Dans cette méthode de travail, encore appelée BIM non propriétaire, chaque métier utilise son propre logiciel métier, qui peut appartenir à divers éditeurs. Par exemple l’architecte peut travailler sur Archicad, le BET Structure sur Tekla et Robot, etc. Une fois leur étude réalisée, les intervenants l’exportent sous un format d’échange, dont le plus courant est le format. ifc ( _Industry Foundation Classes_ ). Ils le mettent à disposition du BIM manager (qui peut être l’architecte, un ingénieur coordonnateur, ou un prestataire spécialisé), qui « assemble » ces fichiers grâce à un logiciel appelé _outil de synthèse_ ou _viewer_ . 

**Cycle courant d’étude en open BIM** 

Une fois le travail de chacun réunit en un fichier de données unique, le BIM manager vérifie la compatibilité entre les données fournies par chaque intervenant, et demande aux équipes de corriger toutes les incompatibilités. Par exemple, si le BET Structure a été amené à modifier le dimensionnement d’une poutre, le dessin architecte est mis à jour. Si le thermicien a besoin d’une réservation dans un mur, elle est prise en compte. Si deux « objets » ont une géométrie incompatible, ils sont redessinés. Le BIM manager n’intervient pas lui-même sur les données produites par les équipes de chaque métier, de même qu’à l’époque d’AutoCAD

l’animateur de la cellule de synthèse ne corrigeait pas lui-même le dessin de chaque spécialité. Chaque métier reste responsable des données qu’il produit. 

Une fois ce travail de synthèse des données effectué, le BIM manager exporte la maquette numérique à jour sous forme d’ifc et la remet à disposition de tous les intervenants. Chaque métier importe alors les mises à jour dans son propre logiciel métier et finalise son étude. De nouvelles itérations ont lieu jusqu’à ce que l’étude soit terminée. 

**Le format ifc** 

Le format ifc est un format « libre », géré par l’association internationale BuildingSmart, représentée en France par l’association Mediaconstruct. Ce format est au cœur du modèle du BIM non propriétaire. 

Le format ifc n’est pas un format de travail, c’est un format normé d’échange de fichiers ou plus précisément c’est le standard ISO pour l’interopérabilité des fichiers. Le format ifc est le format interopérable le plus courant, mais ce n’est pas le seul. 

Tous les logiciels de conception ne peuvent pas exporter ou importer des ifc ; on trouve sur le site de Mediaconstruct la liste des logiciels certifiés pour leur capacité à exporter ou à importer correctement des ifc. Ce format promeut la liberté des utilisateurs d’utiliser des codes « ouverts ». 

Revers de la médaille, l’association a de très faibles moyens de recherche développement par comparaison à ceux d’Autodesk et des autres grands éditeurs de logiciels qui, eux, sont énormes. Résultat, actuellement l’utilisation des ifc butte encore souvent sur des bugs très gênants et ceci surtout dans le cas des maquettes de grande taille ; il suffit d’exporter une maquette REVIT en ifc, puis de l’importer dans un autre logiciel BIM pour s’apercevoir qu’on a généralement perdu certaines propriétés et informations. 

**Pour en savoir plus sur l’Open BIM et les ifc** 

Consulter le site [www.buildingsmartfrance-mediaconstruct.fr](http://www.buildingsmartfrance-mediaconstruct.fr), mais en gardant à l’esprit que ce site défend la solution ifc, et a donc tendance à réduire le BIM à l’utilisation des ifc. 

Les anglophones pourront consulter le site [www.buildingsmart.org](http://www.buildingsmart.org).

![](images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0779-00.png)

Figure 212. Le cycle courant en Open BIM. 

#### 2.5. Open BIM ou closed BIM ? 

Lequel des deux modèles de travail préférer ? Le débat fait rage entre les lobbyistes des deux camps. Les partisans de l’open BIM accusent les grands éditeurs, Autodesk en tête, de saboter volontairement l’interopérabilité ifc. 

Le fait qu’Autodesk affiche son indéfectible soutien aux ifc ne trompe personne. Il est indéniable que l’impossibilité d’exporter sans déboires une maquette REVIT via des ifc arrange bien Autodesk, puisque la solution naturelle à ces problèmes d’interopérabilité est de rester dans la sphère Autodesk en closed BIM ! 

De leur côté, les partisans du closed BIM considèrent l’ifc comme une norme « administrative » dont les évolutions suivent un pas de sénateur totalement incompatible avec les exigences d’efficacité. Enfin, pour couronner le tout, les pouvoirs publics exigent toujours des ifc et veillent à ne jamais imposer un format propriétaire. 

Que penser de ce débat ? On ne peut que se féliciter de l’existence du format ifc qui permet d’élargir le champ de l’interopérabilité à un nombre important de logiciels. Mais on est forcé de reconnaître que tant qu’un mécanisme de financement de la recherche & développement en Open BIM ne sera pas trouvé, les dysfonctionnements des ifc resteront problématiques et conduiront nécessairement de nombreux professionnels à préférer l’environnement efficace du closed BIM d’un grand éditeur (quitte à utiliser les ifc pour échanger avec certains spécialistes de l’équipe de maîtrise d’œuvre).

**Conseil pratique** 

Dans l’état actuel de développement des ifc, on est malheureusement obligé de reconnaître que le modèle centralisé du closed BIM est pour l’instant plus simple d’utilisation. 

#### 2.6. Conséquences du BIM sur l’organisation de la production 

##### 2.6.1. Le rôle des intervenants 

Le rôle de chaque intervenant au sein de l’équipe de maîtrise d’œuvre n’est pas modifié lors du travail en BIM, chacun reste dans son métier ; ce qui est modifié, ce sont les modalités de formalisation des caractéristiques du projet et les modalités d’échange des données au sein de l’équipe. 

Lorsqu’on travaille en BIM, il est indispensable de définir par écrit les règles à respecter par chacun au sein de la maîtrise d’œuvre. Ces règles sont formalisées dans une _convention BIM_ (ou un protocole BIM), qui peut être annexée à la convention de groupement si elle existe. 

Cette convention BIM est rédigée, dès le début des études BIM, par le BIM manager de l’équipe de maîtrise d’œuvre, puis enrichie au fil de l’eau. La convention BIM, document propre à la maîtrise d’œuvre, ne doit pas être confondue avec le _cahier des charges BIM_ du maître d’ouvrage, qui décrit ses exigences et ses besoins en matière de BIM. 

La convention BIM doit notamment définir : 

- les logiciels utilisés par chaque métier, en précisant la version du logiciel ;

- l’organisation des échanges de fichiers entre les membres de l’équipe de maîtrise d’œuvre : périodicité et modalité des échanges de maquettes numériques ; 

- **l’identité et le rôle du BIM Manager et des référents BIM ;** 

- le niveau de développement à respecter à chaque phase. 

Le niveau de développement renseigné dans les fichiers est crucial ; le niveau de développement de chaque phase doit donc être acté entre les intervenants :

- le maître d’ouvrage a fortement intérêt à imposer un niveau de développement au maître d’œuvre dans son contrat, phase par phase ;

- l’équipe de maîtrise d’œuvre doit s’entendre en son sein sur le niveau de développement de chaque phase ; ces dispositions figurent dans la convention BIM ;

- le maître d’œuvre doit imposer contractuellement aux entreprises un niveau de développement des études d’exécution numériques ;

- les entreprises doivent s’assurer que leurs sous-traitants respectent ces mêmes niveaux de développement ; ce point mérite une vigilance toute particulière, car il est courant que certains sous-traitants n’aient pas les compétences étude nécessaires ; préciser au marché que le titulaire est responsable de la bonne application des règles BIM par ses soustraitants. 

Aussi, il est nécessaire qu’un membre de l’équipe soit responsable de la vérification de la structuration des données. Si on ne procède pas à des contrôles, il y a un risque que certains membres de l’équipe, par soucis de simplicité ou dans l’urgence, ne renseignent pas toutes les caractéristiques qui relèvent de leur spécialité. 

Un unique membre de l’équipe de maîtrise d’œuvre doit assurer le rôle de BIM manager, en charge de la gestion et de la coordination des maquettes numériques, dès le début de l’APS. 

Au sein de chaque société de l’équipe de maîtrise d’œuvre, un _référent BIM_ (on parle parfois de _coordinateur BIM_ ) doit être désigné. Le référent BIM est chargé de répercuter au sein de son équipe les prescriptions relatives au BIM. 

Alors que BIM manager est réellement un nouveau métier, référent BIM est plutôt une nouvelle mission assurée au sein des équipes.

**Pour en savoir plus sur les conventions BIM** 

Consulter le « guide méthodologique pour des conventions de projet en BIM » proposé par Mediaconstruct ([https://](https://bim360.autodesk.com)bui​ ldi​ ngs​ mar​ tfr​ ance-​ med​ iac​ ons​ tru​ ct.​ fr​ ). 

##### 2.6.2. Le BIM pour quelles phases d’étude ? 

Le BIM est particulièrement recommandé pour l’APS, l’APD et le PRO, mais peut-on réaliser des esquisses ou des concours en BIM ? Oui tout à fait, à condition de bien définir le niveau de détail afin de ne pas se perdre dans des détails inadéquats par rapport à ces phases. Si le niveau de détail de la maquette numérique est trop lourd, les modifications de projet, bien évidemment nombreuses dans ces phases amont, seront trop lourdes à gérer du fait des relations entre objets à mettre à jour. 

##### 2.6.3. Niveau de développement des maquettes numériques 

Quand on travaille en BIM, la définition du niveau de développement de la maquette est essentielle pour le bon déroulement des études. Le niveau de développement d’une maquette numérique comporte deux aspects : 

- le niveau de détail du graphisme 3D ( _level of geometry_ ),

- le niveau de renseignement de la base de données ( _level of information_ ). Le texte de référence à l’international pour la normalisation des niveaux de développement de la maquette numérique est le _Level of development specification guide_ publié par BIM Forum, le représentant américain de l’association internationale _buildingSMART International_ . Ce guide de référence est le fruit du travail de l’ _American Institute of Architects_ et de diverses associations professionnelles américaines. Le guide distingue : 

«

- LOD 100 : estimate it ;

- LOD 200 : specify it ;

- LOD 300 : buy it ;

- LOD 400 : build it ;

- LOD 500 : operate it. » 

![](images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0783-01.png)

Figure 213. Exemple de différents LOD pour un mur maçonné. 

Ces LOD ne sont pas des échelles, et ils ne correspondent pas non plus à nos phases françaises, bien qu’on puisse assimiler LOD 100 à une esquisse, LOD 200 à un avant-projet, LOD 300 à un PRO, LOD 400 aux EXE et LOD 500 au DOE. La différence porte principalement sur le fait que les phases amont (LOD 100 et 200) sont beaucoup plus détaillées qu’en France.

**On rencontre aussi parfois :** 

- le terme LOD 000 pour désigner la maquette numérique en phase de programmation et de préparation des données du projet ;

- le terme LOD 600 pour désigner la maquette numérique en phase exploitation et maintenance (dite MNEM). En 2014, Syntec a publié un cahier pratique proposant des niveaux de développement français, allant de ND [1](83_1._le_nettoyage_de_fin_de_chantier.md) à ND 6. De son côté, le CSTB prépare pour le contexte français une charte type qui définira des niveaux de détail type. On peut se demander s’il n’aurait pas été plus simple d’adopter tels quels les LOD utilisés à l’international, plutôt que d’inventer une nouvelle nomenclature franco-française. 

**Pour en savoir plus sur les LOD** 

Consulter les _LOD Specification_ américains sur [https://](https://bim360.autodesk.com)bimforum.org/lod. 

##### 2.6.4. La gestion des fichiers 

**Les niveaux de maturité BIM** 

Il existe de nombreuses manières de travailler en BIM. Le gouvernement britannique a défini des _niveaux de maturité BIM_ pour désigner l’organisation d’échange des fichiers mise en place sur un projet : 

- le BIM de niveau 0 correspond à l’absence totale de collaboration : des plans pdf ou papier sont échangés au sein de l’équipe de maîtrise d’œuvre ;

- en BIM de niveau [1](83_1._le_nettoyage_de_fin_de_chantier.md), chaque intervenant a ses propres fichiers 2D et 3D ; des échanges de fichiers peuvent avoir lieu sur une armoire à plans informatique : c’est la pratique la plus courante en France actuellement et cela n’est pas à proprement parler du BIM ;

- en BIM de niveau [2](84_2._les_autocontrôles_et_essais.md), chaque intervenant a ses propres fichiers BIM et ces fichiers sont interopérables, c’est-à-dire qu’ils peuvent être

échangés grâce à un format comme l’ifc (ou le format COBie si l’on parle de la phase exploitation) ou parce que les intervenants utilisent des logiciels du même éditeur, par exemple des logiciels de la sphère Autodesk : c’est ce qu’on appelle communément « travailler en BIM » et c’est ce que fait déjà en France une petite minorité des maîtres d’œuvre ;

- en BIM de niveau 3, tous les intervenants travaillent en même temps sur la même maquette numérique, située sur une plateforme commune ; des systèmes d’autorisations contrôlent les accès aux différents objets de la maquette numérique unique (ou divisée géographiquement) ; on ne passe donc pas par des ifc ; cette collaboration totale est extrêmement rare. 

**Le BIM de niveau 3, but suprême ?** 

Le BIM de niveau 3 est-il l’objectif ? les avis sont partagés. Pour certains, comme l’organisme britannique _National BIM Strategy_ , le BIM de niveau 3 est « le saint Graal » vers lequel on devrait tendre, le BIM de niveau [2](84_2._les_autocontrôles_et_essais.md) n’étant qu’une étape dans la maturation des process. 

Pour d’autres, et notamment pour de nombreux professionnels français, l’objectif devrait plutôt être le BIM de niveau [2](84_2._les_autocontrôles_et_essais.md), et le BIM de niveau 3 est plutôt un mythe, aucunement souhaitable. En effet, faire partager le même fichier à tous les métiers nécessite une discipline extrêmement forte des intervenants : la conception doit aller toujours plus dans le détail, mais sans jamais modifier le projet. 

Tous les maîtres d’œuvre savent que la conception passe par des tâtonnements, des itérations, des variantes, des pistes envisagées puis écartées, des avancées et des reculades. Pour bien imaginer ce que représente le BIM 3, même sans avoir pratiqué le BIM, il suffit d’imaginer un projet où BET et architectes travailleraient sur le même fichier 2D : on imagine bien que cela exigerait que les architectes n’utilisent ce fichier qu’une fois leur travail de conception stabilisé. 

On peut imaginer la faisabilité du BIM de niveau 3 à partir de l’APD, avec des équipes extrêmement disciplinées, mais cela paraît impensable en esquisse et en APS. 

**Pour en savoir plus sur les niveaux de maturité BIM**

**Intérêt du contenu des maquettes** 

Quand le projet est conçu sous forme de maquette numérique, le rendu en plan n’est qu’une des formes de rendu possible pouvant être extraite des fichiers de travail. On peut aussi extraire de la maquette des vues 3D grâce à un _viewer_ , mais il ne faut pas croire que la maquette numérique donnera des vues perspectives « rendues ». La vraie richesse de la maquette numérique est dans la pluridisciplinarité des données stockées dans le modèle. Elle ne remplacera jamais un aquarelliste talentueux ! 

Il ne faut pas croire non plus que les spécialistes pourront exploiter le fichier BIM tel quel. Ils n’y trouveront dans un premier temps que les données renseignées par l’architecte, avec un niveau de détail qui peut être très variable. Chaque spécialiste devra compléter le fichier en ajoutant les caractéristiques techniques qui lui sont utiles. 

Exemple : 

- l’architecte renseigne la géométrie d’un objet « mur », précise que le matériau est un béton, et indique une teinte ;

- l’ingénieur Structure va choisir un type précis de béton parmi les très nombreux types de béton possibles, il vérifie que les données techniques associées par le logiciel à ce type de béton sont cohérentes ;

- la personne en charge du chiffrage ajoutera le prix de ce béton. 

##### 2.6.5. Le cas des grands projets : le découpage en modèles 

La question de la vitesse de traitement des données par les postes informatiques est cruciale quand on travaille en BIM ; cela peut même être un critère de choix entre plusieurs logiciels. 

Du fait du grand nombre de données, les fichiers BIM peuvent prendre une taille importante. 200 Mo est généralement considéré comme la taille maximale de la maquette numérique ; au-delà, il faut diviser le projet en plusieurs maquettes, soit géographiquement (typiquement au niveau des joints de dilatation) soit par métier, pour réduire la taille des fichiers. Le _plan BIM_ formalise ce découpage du projet en modèles, découpage qui est décidé au moment de la création de la maquette numérique.

**La convention BIM en phase chantier** 

Les entreprises sont liées contractuellement par le cahier des charges BIM de l’AMO BIM, qui précise les exigences en termes de niveau de développement des maquettes numériques en phase EXE. Le BIM manager de la phase chantier, qui peut appartenir à l’une des entreprises, met au point la convention BIM d’exécution, document vivant qui précise les modalités de partage des maquettes numériques d’exécution entre les entreprises. 

**Le découpage du projet en maquettes** 

Pour les chantiers en corps d’état séparés, on demande généralement dans le DCE que chaque entreprise produise une maquette numérique de son lot. On a donc en études d’exécution une maquette numérique _par corps d’état_ . Pour les chantiers en entreprise générale, de la même manière, le découpage par corps d’état paraît le plus cohérent. Il arrive que les entreprises préfèrent recréer une nouvelle maquette numérique conforme à leurs habitudes, plutôt que de repartir de celle du maître d’œuvre, et ce afin d’éviter d’endosser la responsabilité du contenu de la maquette du maître d’œuvre. 

**Synthèse et BIM management** 

Durant le chantier, le BIM manager de la maîtrise d’œuvre peut garder son rôle (rôle qui sort bien entendu de la mission de base). Il peut aussi passer la main à un BIM manager appartenant à l’entreprise ou à une autre entreprise. 

Pour les projets dotés d’une cellule de synthèse, il peut aussi être pertinent de considérer en phase chantier que l’animateur de la cellule de synthèse prend le relais et devient BIM manager. En effet, les tâches de la cellule de synthèse et du BIM manager présentent de fortes similitudes : dans les deux cas, on assemble des données fournies par différents intervenants et on s’assure de leur compatibilité. À tel point qu’une fois le BIM arrivé à un certain degré de maturité, on peut se demander si les missions de cellule de synthèse et de BIM management ne vont pas un jour fusionner. 

**BIM et VISA**

Sur les chantiers en BIM, on pourrait imaginer que les documents d’exécution soient constitués par la maquette numérique de l’entreprise. Mais, pour une question de responsabilité, il est nécessaire d’exiger des versions pdf de chaque document d’exécution, comme on le faisait avant l’arrivée du BIM. 

Quant aux avis délivrés par le maître d’œuvre dans le cadre de ses visas, il ne semble pour l’instant pas encore souhaitable qu’ils soient intégrés directement dans la maquette numérique. Le maître d’œuvre émet toujours un avis formalisé, qui peut être rédigé et diffusé via une armoire à plans informatique. Il est en effet important de conserver une bonne traçabilité des visas en cas de sinistre. 

**Processus de validation des maquettes** 

Les armoires PLM permettent de tracer le processus de validation des maquettes numériques par le BIM manager désigné en phase chantier. 

**Point de vigilance** 

Ce processus de validation des maquettes numériques par le BIM manager ne doit pas être confondu avec les visas du maître d’œuvre. Ces deux processus, validation BIM et validation métier, sont distincts, de même qu’avant le BIM il y avait une distinction entre le visa du maître d’œuvre et la validation par la cellule de synthèse. 

**BIM et PME** 

La problématique de l’accès des PME au BIM n’est pas sans susciter d’inquiétudes. La plateforme collaborative KROQI[[1](83_1._le_nettoyage_de_fin_de_chantier.md)] créée par le CSTB pour le Ministère vise à faciliter l’accès des PME au BIM. Son utilisation s’est très vite imposée pour les partages de maquettes au sein de l’équipe de maîtrise d’œuvre, puis pour la transmission des rendus au client, surtout grâce à sa gratuité initiale. Étant maintenant payante, elle cède des parts de marchés à d’autres plateformes. 

#### 2.7. Les outils associés au travail en BIM 

**Outils de synthèse,** _**viewers**_ **et** _**model checkers** 

L’outil de synthèse (ou _viewer_ ) n’est pas un logiciel de dessin ; il ne permet

pas non plus de réaliser des calculs. Il est utilisé pour visualiser la maquette numérique et consulter les données (les caractéristiques des objets). La visualisation dans un _viewer_ est beaucoup plus rapide et fluide que dans un logiciel de conception comme REVIT. On peut aisément naviguer grâce à un _viewer_ dans un assemblage de plusieurs grosses maquettes numériques, ce qui est serait très difficile dans REVIT. On peut de plus dans un _viewer_ annoter les maquettes et établir des listes de problèmes à traiter, zone par zone. 

La plupart des _viewers_ ont de plus une fonction _model checker_ : ils permettent de tester les conflits entre les modèles de chaque intervenant. L’informatique permet de détecter les interférences entres les objets (on parle de collisions, en anglais _clashes_ ). Une tolérance peut être paramétrée, par exemple 5 cm, pour cette détection des _clashes_ . Les outils de _clash detection_ constituent une remarquable avancée pour le travail de synthèse en phase EXE, ou de présynthèse en phases APD et PRO. Un travail de tri et de priorisation des _clashes_ est cependant nécessaire, ce qui représente une charge de travail non négligeable. 

Il faut de plus bien choisir les catégories d’objets à analyser : par exemple il est utile de détecter les _clashes_ entre structures et réseaux, mais pas avec les murs, car on ne modélise pas les murs en détourant les réseaux, donc une détection incluant les murs créerait de très nombreux _clashes_ . 

En phase APS, il est trop tôt pour utiliser les outils _model checkers_ , car, à ce stade d’avancement des études, ces outils conduiraient à la détection de milliers d’erreurs impossibles à analyser. En phase APS, la synthèse entre les maquettes métier relève plutôt de réunions de coordination (on parle de « revues de maquettes ») : architectes et ingénieurs se réunissent dans une salle et projettent sur un grand écran la maquette de synthèse que le BIM manager a analysée. 

Les avancées apportées par les outils de _clash detection_ conduisent dans certains pays les maîtres d’ouvrage à exiger des maquettes _0 clashes_ , ce qui nécessite un niveau de détail poussé. La notion de marge de tolérance est alors essentielle. 

**Pour en savoir plus sur les outils de synthèse** 

**Consulter des sites d’éditeurs, comme :** 

- Solibri permet d’analyser une maquette sur la base de règles définies, par exemple pour comparer une maquette architecte et une maquette structure,

- Solibri permet de vérifier des maquettes sur la base de règles simples de sécurité incendie et d’accessibilité des locaux,

- Solibri permet de visualiser facilement les liens des maquettes numériques vers des pièces jointes (fiches techniques, notes de calcul…) ; 

**

- Trimble Connect, outil de synthèse de Tekla, qui permet de faire de la _clash detection :_ [www.tekla.com/fr/produits/trimble-connect](http://www.tekla.com/fr/produits/trimble-connect) ;

- dans la sphère Autodesk, on trouve l’outil de synthèse Navisworks, très couramment utilisé ; il existe sous trois formes :

  - Navisworks freedom, _viewer_ gratuit,

  - Navisworks Simulate, typiquement utilisé pour faire des revues de maquettes ; grâce à ce viewer on peut assembler des maquettes de différents formats BIM, visualiser les propriétés des objets, visualiser en temps réel des coupes en déplaçant le trait de coupe, ou encore monter des vidéos 4D montrant le déroulement d’un phasage chantier, avec toutes les granulométries possibles ;

  - et Navisworks Manage, plus cher, qui permet en outre de réaliser de la détection de conflits et d’interférences (présynthèse) ; Navisworks optimise la taille du fichier, en créant un fichier beaucoup plus petit que le fichier Revit d’origine.

**

- toujours chez Autodesk, il est aussi possible d’utiliser Revit en mode _viewer_ , par exemple pour ne pas risquer d’endommager une maquette en l’examinant.

- eveBIM est un outil de synthèse gratuit créé par le CSTB ; il permet de visualiser uniquement des exports ifc et pas des maquettes Revit ; disponible sur : [www.evebim.fr](http://www.evebim.fr).

Pour les grands chantiers s’étalant sur une certaine durée, des armoires à plans informatiques sophistiquées permettent l’enregistrement au fil de l’eau des évolutions des versions successives de la maquette numérique. On parle de _plateforme PLM_ ( _Product lifecycle management_ ). Ces plateformes comportent généralement des outils de visualisation de la maquette numérique. 

_**Pour en savoir plus sur les PLM**_ [Consulter par exemple www.thinkproject-plm.com](http://www.thinkproject-plm.com). 

**BIM et logiciels d’étude** 

En France, une trentaine de logiciels utilisent le format .IFC. Il s’agit de logiciels destinés aux architectes, de logiciels destinés aux thermiciens, de logiciels destinés au calcul des structures, aux économistes, aux gestionnaires de patrimoine, etc. Les trois éditeurs généralistes leaders dans ce domaine dans le monde sont Autodesk, Nemetschek et Bentley. On trouvera ci-dessous un panorama sans prétention à l’exhaustivité des logiciels phares et des logiciels complémentaires associés. 

**Logiciels de la sphère Autodesk** 

- **REVIT d’Autodesk** est bien entendu le logiciel phare, le plus utilisé par de très nombreux architectes. REVIT intègre les spécialités Structure et MEP, ce qui permet aux architectes et ingénieurs de travailler sur les mêmes fichiers, sans avoir à passer par des ifc. Parmi les très nombreuses fonctionnalités, on peut citer : 

  - la mise à jour automatique des coupes lors des modifications de plans ;

  - l’édition de nomenclatures paramétrables librement et exportables vers Excel (par exemple, tableaux des portes, liste de locaux avec leurs surfaces, liste des tableaux électriques, etc.) ;

  - la présence d’un outil de vérification de maquette, qui produit un rapport d’anomalies très utile.

**Dynamo** est un logiciel qui permet d’automatiser des tâches répétitives grâce à une interface de programmation visuelle : il permet notamment de tester rapidement des options de conception, d’importer et d’exporter des données Excel, d’écrire du code de programmation grâce à une interface ergonomique.

- **REVIT Live** est un logiciel de rendu qui permet de transformer les modèles REVIT en vues immersives du projet et des espaces intérieurs.

- **Autodesk Rendering** est un logiciel de rendu haute définition, qui permet de faire des images photoréalistes grâce à la puissance de calcul du cloud ; il permet aussi des études d’ensoleillement et d’éclairement. Il nécessite néanmoins un abonnement.

- **3ds Max** est le logiciel Autodesk de référence pour les rendus en animation 3D, de qualité cinématographique.

- **Infraworks** et **AutoCAD civil 3D** sont des logiciels Autodesk dédiés aux projets d’infrastructure/travaux publics et de VRD : ponts, routes, aménagements urbains, etc.

- **Covadis** est un logiciel d’études VRD édité par Géomédia, partenaire d’Autodesk. 

**Logiciels de la sphère Nemetschek** 

- **Archicad** est un logiciel spécialement destiné aux architectes, édité par la société hongroise Graphisoft, du groupe allemand Nemetschek.

- **Allplan** est un logiciel d’architecture très utilisé en Allemagne par les architectes et les bureaux d’étude, moins en France. Un des atouts de ce logiciel est sa bonne interopérabilité avec les autres logiciels de son éditeur, Nemetschek : Scia Engineer, logiciel destiné aux études Structure et DDS–CAD, logiciel destiné aux études CVC Plomberie et électricité. 

**Logiciels d’autres éditeurs** 

- **Tekla Structures** , logiciel finlandais, est couramment utilisé par les ingénieurs Structure. Tekla permet de représenter des structures métalliques. Il est en particulier beaucoup utilisé par les entreprises pour faire les études d’exécution Structure, par exemple des plans de ferraillage. 

Sur Tekla, les spécialistes Structure vont dessiner la structure et créer le _modèle analytique_ , c’est-à-dire les liaisons entre les éléments structurels, et leurs degrés de liberté, conformément au schéma statique de la structure. Tekla ne permet pas de réaliser les notes de calcul, les ingénieurs utilisent un logiciel de calcul de structure, comme Robot, qui exploite directement le fichier Tekla, sans passer par des ifc. Dans Robot on paramétrera les hypothèses de calcul, les charges, les combinaisons, les conditions d’appui et on réalisera les notes de calcul.

- **Digital project** est un logiciel développé par Franck Gehry et issu du logiciel de conception aéronautique Catia. Ce logiciel est basé sur une _paramétrisation de la géométrie_ ( _parametric design_ ) : il permet de caractériser un bâtiment par un ensemble de paramètres et de modifier la géométrie en faisant varier ces paramètres. Tout le bâtiment évolue, en conservant les liaisons entre les objets. Cette technique permet de concevoir des projets d’une géométrie très complexe. Digital project utilise de plus un grand nombre de petits fichiers peu volumineux. On peut faire des exports ifc depuis Digital project. Mais c’est un logiciel assez onéreux.

- **DesignBuilder** est un logiciel thermique, qui permet de réaliser les études thermiques réglementaires mais aussi des simulations thermiques dynamiques, des études de ventilation et des études d’éclairement naturel. Entre REVIT et DesignBuilder, on n’utilise pas le format d’échange ifc mais le format GbXML (green building XML), format d’échange dédié à la thermique. Actuellement, le format ifc ne porte pas les informations dont les logiciels thermiques ont besoin. Le format GbXML est utilisé par de nombreux logiciels de calcul énergétique et thermique. 

Les logiciels n’utilisant pas des « objets » ne peuvent pas être utilisés directement en BIM. Ainsi, un logiciel de conception 3D qui définit des volumes, mais sans préciser par exemple qu’un poteau joue un rôle de poteau, ne permet pas la réutilisation de ses données sous la forme d’ifc. Un tel logiciel n’est donc pas certifié ifc.

**Pour en savoir plus les logiciels compatibles ifc** 

Consulter la liste des logiciels certifiés ifc sur le site de l’association Buildingsmart : www.bui​ ldi​ ngs​ mart.​ org/​ com​ pli​ ance/​ red​ eve​ lop​ ment/​ cer​ tif​ ied-​ ​ sof​tware. 

**Programmation et plugins** 

De nombreux logiciels de programmation, notamment REVIT, permettent à l’utilisateur de programmer de petites applications pour automatiser certaines tâches. Ces applications sont particulièrement intéressantes : 

- pour traiter des tâches répétitives avec de grands volumes de données (par exemple pour la conception d’une tour de bureaux),

- ou pour améliorer l’interopérabilité entre logiciels en simplifiant les échanges de données. On parle d’ _API_ : interface de programmation applicative. 

**Grasshopper** 

Grasshopper est un plugin gratuit du logiciel de dessin 3d Rhino, qui fait de plus en plus d’adeptes du fait de son caractère très novateur et très ergonomique. Grasshopper est une application de programmation visuelle, c’est-à-dire qu’elle permet, sans nécessiter de compétences en programmation, de modifier et complexifier très facilement des formes géométriques, courbes ou surfaces. 

Rhino n’est pas certifié ifc, mais des exports restent possibles et on peut associer des éléments dessinés dans Rhino à des classes ifc, par exemple : « ces éléments sont des poutres porteuses IPE ». Mais Rhino est peu pratique pour extraire des plans 2d. 

Grasshopper permet de produire des surfaces courbes complexes qu’on pourrait très difficilement produire sur REVIT.

![](images/Maître_d'oeuvre_bâtiment,_9e_édition-_Guide_pratique,_--_Leonard_Hamburger_--_2023_--_Eyrolles.epub-0795-00.png)

Figure 214. Exemple de programmation visuelle (source : [www.grasshopper3d.com](http://www.grasshopper3d.com)) 

**Enscape** 

Enscape est un plugin pour REVIT (et accessoirement SketchUp) permettant de réaliser des vues 3D d’une qualité graphique excellente. Il est de plus très simple d’utilisation. 

On peut, grâce à cet outil, visualiser en temps réel (sans délai de calcul) l’impact en termes de rendu de modifications de la maquette numérique REVIT. 

Enscape permet de plus de créer des fichiers autonomes ( _standalone files_ ) à partir desquels on peut naviguer dans les modèles rendus comme dans un jeu vidéo. Cette fonctionnalité est particulièrement puissante, et particulièrement pratique pour présenter un rendu dans les locaux du client sans accès réseau. L’exécutable Enscape peut être remis au client comme un livrable complémentaire au rendu pdf. 

**V-Ray** 

V-Ray est un autre outil de rendu aux fonctionnalités impressionnantes, notamment par les possibilités de gestion de la lumière qu’il offre. Il est notamment compatible avec REVIT. 

**Twinmotion** 

Twinmotion est un logiciel de visualisation, qui permet de réaliser des films immersifs à partir des maquettes REVIT. On peut y paramétrer la lumière du soleil, des reflets, des effets de brouillard, des mouvements sur la surface de l’eau, l’impact du vent, des flux de véhicules et de piétons, et régler la profondeur de champ. Une bibliothèque permet d’ajouter dans les films des arbres, des véhicules, des personnages pour enrichir les rendus.

Outre les films, Twinmotion permet aussi de générer des vues immersives dynamiques et interactives pour des casques de réalité virtuelle. 

**Logiciels de vidéo 4D** 

Synchro de l’éditeur Bentley permet de réaliser des vidéos des phasages chantier, avec toutes les nuances possibles de granulométrie. Naviswork manage, évoqué plus haut, permet aussi la réalisation de telles vidéos. 

**Parametric design**_ **et** _**generative design** 

Le terme de _parametric design_ désigne la conception basée sur un ensemble de paramètres, que le concepteur peut faire varier. Ainsi un mur ne sera pas décrit dans la maquette numérique avec sa position, son épaisseur, sa longueur et sa hauteur précises, mais ces grandeurs seront remplacées par des paramètres, que le concepteur pourra faire varier dans un domaine de définition pour tester différentes solutions. Le _generative design_ a été défini comme une méthode de conception qui emploie des algorithmes plus autonomes que le _parametric design_ . En _generative design_ , le logiciel va exécuter des lignes de codes pour tester différentes configurations, jusqu’à ce qu’un critère d’arrêt soit satisfait. Par exemple le logiciel peut tester différentes largeurs d’immeuble et évaluer l’impact sur le besoin en éclairage artificiel, ou encore déplacer des locaux en plan et tester le respect de règles d’évacuation incendie. 

On parle aussi de _performance generative design_ quand le concepteur définit un objectif de performance et un algorithme trouve les solutions de conception qui se rapprochent le mieux de l’objectif souhaité. Ces domaines en pointe font l’objet de nombreuses recherches universitaires dans le monde.[[2](84_2._les_autocontrôles_et_essais.md)] 

#### 2.8. BIM et honoraires 

Travailler en BIM, en renseignant de nombreuses caractéristiques des « objets » informatiques tout au long du projet représente une charge pour l’équipe de maîtrise d’œuvre. Une organisation rigoureuse et des habitudes de travail peuvent réduire cette charge, mais elle existe néanmoins.

Comment rémunérer cette charge, qui finalement profitera au maître d’ouvrage s’il bénéficie d’un DOE numérique utile pendant toute la vie du bâtiment ? C’est là une question cruciale pour la faisabilité réelle du travail en BIM : travailler en BIM implique de prendre en charge un surcroit de tâches, pour un bénéfice futur qui apparaîtra aux phases suivantes et profitera à d’autres intervenants. 

Il est difficile d’augmenter le taux de MOE sous prétexte qu’on travaille en BIM. Mais une piste intéressante a été proposée : le maître d’œuvre pourrait, en fin de chantier, « vendre » la constitution du DOE numérique comme une prestation AMO. Ce DOE numérique est un dossier de récolement numérique, assemblant toutes les caractéristiques que les entreprises ont ajoutées au fur et à mesure de leurs études d’exécution. Dans cette optique, il est important de préciser au contrat de base que le DOE numérique n’est pas compris dans la mission de base et à condition du moins que le maître d’ouvrage n’ait pas inclus cette prestation dans son cahier des charges. 

L’idée de fournir en fin de chantier un DOE en maquette numérique peut aussi être un atout dans un concours, et contribuer à faire la différence. 

#### 2.9. L’impact du BIM sur la MOA professionnelle 

**Le travail en BIM a plusieurs conséquences pour la MOA :** 

- Les données supplémentaires obtenues par le travail de renseignement de la maquette BIM peuvent être très utiles pour la maintenance du bâtiment. La maquette numérique devient un outil de base de l’exploitation/maintenance ; la maquette peut s’enrichir des données en temps réel issues de capteurs situés dans tout le bâtiment, permettant ainsi l’optimisation de la maintenance. 

Si la MOA souhaite que le travail en BIM lui soit utile lors de la phase ultérieure d’exploitation du bâtiment, elle a intérêt à faire appel à un AMO BIM qui assurera pour son compte tout le pilotage technique du BIM : 

- définition du niveau d’exigence à l’égard des maîtres d’œuvre à travers la rédaction d’un _cahier des charges BIM_ ,

- analyse des propositions d’organisation BIM des maîtres d’œuvre en phase concours,

- validation de la convention BIM de la MOE retenue,

- contrôle tout au long de la vie du projet du niveau de détail respecté par les entreprises, jusqu’au DOE numérique. L’objectif de l’AMO BIM est _in fine_ de permettre au maître d’ouvrage de récupérer des maquettes numériques DOE facilitant l’exploitation et la maintenance du bâtiment. Attention toutefois : le niveau de détail idéal pour l’exploitation/maintenance n’est souvent pas le niveau de détail des études d’exécution. Les mainteneurs ont certes besoin des caractéristiques détaillées des équipements à entretenir, mais ils n’ont généralement pas besoin d’avoir un jumeau numérique allant jusqu’au boulon, ni d’un fichier très volumineux et peu pratique d’utilisation. Actuellement les maquettes numériques ifc sont souvent difficilement exploitables telles quelles par les logiciels de gestion de patrimoine des maîtres d’ouvrage. Un fichier d’échange est souvent nécessaire, pour rendre les données de la maquette numérique exploitables. L’AMO BIM peut être chargé de cette manipulation.

- Dans certains projets, la MOA a accès directement aux fichiers interopérables, et peut même aller jusqu’à annoter les fichiers en y faisant figurer ses remarques ; cette méthode est à aborder avec beaucoup de réserves car elle peut risquer de perturber la production si elle est mal encadrée ; se pose aussi le problème de la traçabilité des remarques de la MOA.

- La livraison du DOE sous format de maquette numérique est un atout important pour le MOA, s’il a la capacité de tenir à jour ce modèle numérique pendant toute la vie du bâtiment. Pour ce faire, il devra mettre en place une organisation solide permettant de garantir la mise à jour régulière sur le long terme de la maquette numérique. Que les mises à jour soient réalisées par un salarié du maître d’ouvrage ou par un prestataire, la tâche est certainement lourde.

Consulter le site d’éditeurs de logiciels spécialisés en gestion de patrimoine, comme :

- Archibus, un des leaders en matière de logiciels de gestion de patrimoine immobilier, sur [https://](https://bim360.autodesk.com)archibus.com ;

- AS-TECH sur [www.astech-solutions.com](http://www.astech-solutions.com) ;

- ALLFA Web, de Nemetschek, sur www.all​ plan.​ com/​ fr/​ sof​ twa​ re/​ fac​ ili​ ty-​ man​ ​ agement/​ all​ fa-​ web.​ html​ ;

- Active3d, sur [https://active3d.soprasteria.com/](https://active3d.soprasteria.com/). 

##### 2.10. Les problèmes actuels du BIM et les pistes de progrès 

**Difficultés liées aux ifc** 

Comme nous l’avons vu, l’utilisation des ifc pose encore actuellement de nombreux problèmes, par exemple pour la gestion des formes courbes. Il suffit d’exporter une maquette REVIT en ifc et de la réimporter en fichier REVIT pour voir que des informations ont été perturbées. Aussi, comme vu plus haut, de nombreux professionnels préfèrent utiliser la suite de logiciels compatibles entre eux d’un éditeur ( _closed BIM_ ). 

**Les fausses promesses de l’interopérabilité** 

La promesse de l’interopérabilité n’est hélas pas toujours tenue : lorsque les spécialistes métiers (thermiciens, acousticiens, ingénieurs structure, éclairagistes, etc.) tentent d’utiliser les maquettes numériques architecte pour réaliser leur simulations ou calculs, il arrive couramment que ces maquettes s’avèrent inexploitables car trop volumineuses, trop détaillées et ne comportant pas les caractéristiques nécessaires à l’analyse métier. 

Le travail nécessaire pour adapter les maquettes architecte aux besoins réels des logiciels métiers peut parfois être malheureusement plus important que la création d’un nouveau modèle métier ! Il arrive ainsi souvent qu’un spécialiste soit contraint de re-modéliser la volumétrie du projet pour disposer d’une maquette simple, dans laquelle seules les données géométriques réellement utiles à son métier figurent.

Prenons l’exemple d’un thermicien réalisant une simulation thermique dynamique. La maquette architecte est souvent inexploitable pour lui, car trop détaillée, et il doit alors monter une maquette à la géométrie simplifiée, exploitable pour ses calculs. 

De même, les ingénieurs Structure doivent couramment ressaisir la géométrie du projet dans leur logiciel de calcul. Il faut espérer que ce problème sera résolu dans les prochaines années par les versions futures des logiciels. 

**Discipline des acteurs et critères de vérification des prestations** 

Mais la difficulté principale du travail en BIM réside probablement dans la difficulté qu’il peut y avoir à imposer une « discipline » au sein d’une équipe de cotraitants, puis d’entreprises et de sous-traitants. Inévitablement, certains intervenants respectent inégalement les consignes de niveau de détail de la maquette numérique. 

Actuellement, dire qu’on travaille en BIM, est une affirmation très vague, car un maître d’œuvre peut travailler en BIM en utilisant seulement l’outil 3D sans rentrer aucune autre donnée, ou à l’autre extrême rentrer des centaines de caractéristiques pour chaque objet. L’utilisation des LOD américains dans les cahiers des charges BIM des maîtres d’ouvrage et dans les conventions BIM entre maîtres d’œuvre permet de disposer de critères objectifs d’évaluation de la qualité des maquettes. 

**Pour en savoir plus sur le BIM** 

Consulter le site de l’association Mediaconstruct : www.bui​ ldi​ ngs​ mar​ tfr​ ance-​ ​ mediac​ ons​ tru​ ct.​ fr​ . Les anglophones pourront consulter le très complet [www.bimforum.org](http://www.bimforum.org). Consulter le site suisse [https://](https://bim360.autodesk.com)objectif-bim.com. 

##### 2.11. CIM et SIG 

On utilise le terme de _city information modeling_ ou CIM pour désigner l’utilisation des méthodes du BIM à l’échelle du quartier, de la ville ou du territoire. Alors que les systèmes d’information géographiques ou SIG, représentation cartographiques de bases de données, existent depuis la fin des années 1960, le CIM est une technologie encore nouvelle et en plein progrès.
