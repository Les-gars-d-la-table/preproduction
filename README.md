# Préproduction

# Table des matières
1. [Intention ou concept](#Intention-ou-concept)
    - [Cartographie](#Cartographie)
    - [Intention de départ](#Intention-de-départ)
    - [Synopsis](#Synopsis)
    - [Tableau d'ambiance (*moodboard*)](#Tableau-d'ambiance-(*moodboard*))
    - [Scénario, scénarimage ou document audio/visuel](#Scénario,-scénarimage-ou-document-audio/visuel)
2. [Contenu multimédia à intégrer](#Contenu-multimédia-à-intégrer)
    - [Inventaire du contenu multimédia](#Inventaire-du-contenu-multimédia)
    - [Univers artistique des éléments](#Univers-artistique-des-éléments-centraux)
3. [Planification technique d'un prototype (devis technique)](#Planification-technique-(devis-technique))
    - [Schémas ou plans techniques](#Schémas-ou-plans-techniques)
    - [Matériaux requis](#Matériaux-de-scénographie-requis)
    - [Équipements requis](#Équipements-requis)
    - [Logiciels requis](#Logiciels-requis)
    - [Ressources humaines requises](#Ressources-humaines-requises)
    - [Ressources spatiales requises (rangement et locaux)](#Ressources-spatiales-requises-(rangement-et-locaux))
    - [Contraintes techniques et potentiels problèmes de production](#Contraintes-techniques-et-potentiels-problèmes-de-production)
4. [Planification de la production d'un prototype (budget et étapes de réalisation)](#Planification-de-la-production-(budget-et-étapes-de-réalisation))
    - [Budget prévisionnel](#Budget-prévisionnel)
    - [Échéancier global](#Échéancier-global)
    - [Liste des tâches à réaliser](#Liste-des-tâches-à-réaliser)
    - [Rôles et responsabilités des membres de l'équipe](#Rôles-et-responsabilités-des-membres-de-l'équipe))
    - [Moments des rencontres d'équipe](#Moments-des-rencontres-d'équipe)

# Intention ou concept
## Cartographie

![cartographie](assets/images/brainstorm.png)

## Intention de départ
L'idée originale de ce projet est partie de l'idée de la table, on voulait créer quelque chose qui serait intéressant à intéragir avec, et qui pourrait intéresser n'importe-qui, notre projet donne beaucoup de pouvoir à l'intéracteur, et c'est ce qui d'après nous le rend différent, l'intéracteur peut créer des combinaisons que nous-mêmes n'avont pas fait.

## Synopsis
L'utilisateur intéragit avec en déplaçant une statuette avec un *fiducial* en bas pour faire apparaître et bouger des planètes et/ou d'autres objets astronomiques autour de l'orbite d'un soleil, représenté par la table elle même. Essentiellement, on construit notre propre système solaire! 

## Tableau d'ambiance (*moodboard*)
![Unity Moodboard](assets/images/moodboardUnity.png)


## Scénario, scénarimage ou document audio/visuel 
![scenarimage](assets/images/scenarigmage_bon.pdf)


# Contenu multimédia à intégrer
## Inventaire du contenu multimédia

-  statuettes (pour les utilisateur-trices)
-  sons
-  paysages sonores
-  vfx d'animation 3D
-  source lumineuse



## Univers artistique des éléments
univers contemplatif d'éléments relié a l'espace avec plusieurs formes et couleurs qui pourront se mélanger entre eux.
# Planification technique d'un prototype (devis technique)
## Schémas ou plans techniques

![Table de devant](assets/images/table/tableModele1.png)
> Table modélisée dans Blender

![Table de l'arrière](assets/images/table/tableModele2.png)
> Angle différent de la table

![Fente](assets/images/table/tableModele3.png)
> Fente pour glisser le panneau d'acrylique dans la table.

![y-axis table](assets/images/table/tableModele4.png)
> table sur l'angle Y

![x-axis table](assets/images/table/tableModele5.png)
> table sur l'angle X

#### Légende
* Rouge: Carte de son
* Jaune: Raspberry PI
* Rose: Projecteur
* Vert: Haut-Parleur
* Bleu: Caméra

### Plantation 

![cartographie](assets/images/plantationGrandStudio.png)
![cartographie](assets/images/plantationTable.png)

### Schéma de branchement 

![schema_branchement](assets/images/schema_branchement_final.drawio.png)

## Matériel de scénographie requis

* Table
    * Matériaux: Bois, Aluminium, Acrylique, Spandex
    * dimensions de la table n'ont pas encore été déterminées
* grand studio avec les murs amovibles

## Équipements requis

* Audio
    * 4 haut-parleurs
    * 4 fils XLR 3 conducteurs de 15' (M->F)
    * 1 carte de son

* Vidéo
    * 4 projecteurs vidéo shortrow
    * 3 système d'acrochage
    * 1 caméra

* Lumière
    * 4 lumière LED RGBAW DMX
    * 4 fils XLR 3 conducteurs de 20'
    * Console DMX
    * Interface DMX USB

* Électricité
    * 4 cordon IEC (pour l'alimentation des haut-parleurs)
    * 5 multiprise

* Réseau
    * Switch poe 5 ports
    * 10 Cables Ethernet
    * 8 Cables HDMI
    * 3 Receivers HDMI
    * 3 Sender HDMI
    * 1 Capture card

* Ordinateur
    * 1 ordinateur

* micro ordinateur
    * 4 raspberry pi    
    

## Logiciels requis

* [Cycling 74' Max 8](https://cycling74.com/products/max)   
* [Unity 2019 lts](https://unity.com/)
* [Open stage control](https://openstagecontrol.ammd.net/)
* [Autodesk Maya](https://www.autodesk.com/ca-fr)
* [HyperHDR](https://github.com/awawa-dev/HyperHDR)
* [VCV Rack](https://vcvrack.com/)
* [Cardinal](https://cardinal.kx.studio/)
* [OBS](https://obsproject.com)
* [reacTIVision](https://reactivision.sourceforge.net)
* [Sonobus](https://www.sonobus.net/)

## Ressources humaines requises

* Guillaume Arsenault.
* TTP
* Possiblement un soudeur

## Ressources spatiales requises

* Grand studio
  * Espace avec faux murs pour projection autours de la table.
* Salle des matrices
  * Accès à plusieurs ports ethernet, possibilité de pouvoir avoir notre ordinateur dans cette salle. Possiblement également l'espace de rangement pour les statues de remplacement.

## Contraintes techniques et potentiels problèmes de production (Jacob - en cours)

| Contrainte ou problème potentiel                     | Solution envisagée                                    | Commentaires                                                                                 |
|------------------------------------------------------|-------------------------------------------------------|----------------------------------------------------------------------------------------------|
| Nous n'avons pas testé la caméra avec ReacTIVision    | Tester différentes caméras. | Dans le pire des Cas, c'est toujours possible d'utiliser une webcam, ou encore d'utiliser la librairie javascript que guillaume a trouvé|
| Notre ordinateur doit pouvoir communiquer avec trop de choses en HDMI ou DisplayPort | Expérimenter des façons d'éviter d'avoir trop de choses connectées à l'ordinateur à la fois.| Travailler avec Guillaume pour faire en sorte que NDI fonctionne sur PI, cela économiserait un port.|
|Nous ne pouvons pas faire la table nous-même. | Nous connaissons des soudeurs qui pourraient faire les parties métaliques pour nous.| Si ce n'est pas possible, on pourrait faire la table en bois complètement nous-même. |

# Planification de la production d'un prototype (budget et étapes de réalisation)
## Budget prévisionnel



## Échéancier global
Étapes importantes du projet visualisé dans GitHub (*milestones*):  

*Dates importantes :*
- Table terminer : Jeudi 15 février
- Tous terminer les assets : Mardi 20 février
- Fonctionnement total de tous les logiciels entre eux : Jeudi 29 Février
- Projet final test : Lundi 18 mars
- Présentation des projets devant public : jeudi 25 mars (soir)

## Liste des tâches à réaliser
Visualisation des tâches à réaliser dans GitHub selon la méthode kanban:  
https://github.com/orgs/Les-gars-d-la-table/projects/1/views/2

Inventaire des tâches à réaliser dans GitHub selon le répertoire d'*issues*:  
https://github.com/Les-gars-d-la-table/preproduction/issues

## Rôles et responsabilités des membres de l'équipe 

**Mikaël Tourangeau**
- Modélisation et impression 3D des statuettes. 

**Étienne Charron**
- Comité Technique et coordination technique (suivi du devis technique);
- Programmation du module Max d'effet et de contrôle audio;
- Construction de la table

**Quoc huy Do**
- S'assure du bon fonctionnement de Unity;
- Coordination artistique;
- Installation et mise en place de la capture audiovidéo du projet en temps réel;
- Programmation du module Unity d'effets visuels et intégration dans Max.

**Jérémy Cholette**
- Création des paysages sonores
- Installation de l'équipement dans l'espace physique.

**Jacob Alarie-Brousseau**
- Coordination générale du projet (coordination de l'échéancier, du budget, suivi de la liste des tâches à réaliser, s'assurer de la répartition des rôles et des responsabilités des membres de l'équipe);
- Programmation du module Max en lien avec le fonctionnement de la détection des statuettes et de leur position;
- Construction de la table

## Moments des rencontres d'équipe
Hebdomadaire
- **lundi "9:30"h (1h)** : Rencontre de suivi de projet.
- **Vendredi "17h" (1h)** : Rencontre du suivi de ce qu'on a réaliser pendant la semaine
