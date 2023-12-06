# Préproduction
> C'est ici qu'on dépose les éléments de la préproduction.

# Table des matières
1. [Intention ou concept](#Intention-ou-concept)
    - [Cartographie](#Cartographie)
    - [Intention de départ](#Intention-de-départ)
    - [Synopsis](#Synopsis)
    - [Moodboard](#Moodboard)
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

## Intention de départ
Par ce projet, nous souhaitons pousser l'intéracteur à lâcher prise en créant soi-même un environnement immersif.

## Synopsis
Sonalux est une expérience divisée en 3 chapitres qui se distinguent par leur intensité graduelle. Chaque chapitre comportera différents éléments sonores et visuels accompagnés d'une introduction au tout début.  
Le public est appelé à découvrir les différents chapitres du projet.

## Moodboard
> ![moodboard_ambiance](https://github.com/vince1887/Sonalux/assets/93718179/e7e38875-cabb-405f-8eb0-8fb7119f1d56)

> [Exemple d'art générative avec TouchDesigner](https://www.youtube.com/watch?v=lHsF-DKJZYc)

> [L'improvisation de l'eau avec TouchDesigner](https://www.youtube.com/watch?v=SbYtIiZdrew&t=1s)

> [Exemple d'art générative avec des particules dans TouchDesigner](https://www.youtube.com/watch?v=3snFQtLRJqs&t=2s)

> [Site de Maff](https://www.maff.tv/watch/infinity-room)

# Contenu multimédia à intégrer
## Inventaire du contenu multimédia

- 3 paysage visuel génératif (touchdesigner)
- 3 paysages sonores (vcv rack)
- 3 enregistrement de narration
- 6 modules multimédias (captation des données (kinect/boite son), interprétation des données, contrôle des tubes led, effets audiovisuels, contrôle vidéo/mapping projection, contrôle de la navigation utilisateur & des différents sous-modules).

# Planification technique d'un prototype (devis technique)
## Schémas ou plans techniques

### Plantation 

![exemple de plantation](images/schema_bvranchemant.png)

### Schéma de branchement 

![exemple de schema](images/schema_bvranchemant.png)

## Matériel de scénographie requis

* 4 toiles pour rétroprojection
* Système d'accrochage au sol pour subdiviser l'endroit de déploiement/faux mur en toile

## Équipements requis

* Audio
    * 4 haut-parleurs actifs de 4"
    * 4 fils XLR 3 conducteurs de 15' (M->F)
    * Interface audio USB disposant 8 sorties et au moins 1 entrée

* Vidéo
    * 5 projecteurs vidéo lentille standard
    * Kinect v1

* Lumière
    * 8 tubes leds

* Électricité
    * 4 cordon IEC (pour l'alimentation des haut-parleurs)
    * 2 extentions 3 fiches et 3 conducteurs 
    * 2 multiprise

* Réseau
    * 4 fils cat6a de 15"
    * Switch poe 5 ports

* Ordinateur
    * 1 ordinateur portable 
    
* Autre
    * boite sonore (à créer)

## Logiciels requis

* [TouchDesigner](https://derivative.ca/UserGuide/TouchDesigner)
* [VCV Rack](https://vcvrack.com/)
* [Arduino IDE](https://www.arduino.cc/en/software)
* [Kinect v1.8 studio](https://www.microsoft.com/en-us/download/details.aspx?id=40278)


## Ressources humaines requises

* TTP, location de matériel
  
## Ressources spatiales requises (rangement et locaux)

* Grand studio
    * Rétroprojection vidéo dans le grand studio

* Petit studio
    * Enregsitrement audio de la naration

## Contraintes techniques et potentiels problèmes de production

| Contrainte ou problème potentiel                 | Solution envisagée                                    | Commentaires                                                                                 |
|--------------------------------------------------|-------------------------------------------------------|----------------------------------------------------------------------------------------------|
| Apprendre et maîtriser un tout nouveau logiciel, soit TouchDesigner. | expérimentation durant la session |                                                                                              |
| Apprendre a utiliser la kinect pour la captation live                | expérimentation durant la session + documentation sur le web|                                                                    |
|Réaliser la boîte sonore et intégrer les différentes composantes, c’est-à-dire analogues (sortie audio) et électriques (microcontrôleurs). | acheter le matériels nécéssaire |
|Relier la boîte au reste de l’installation.  | faire plusieurs itération de visuel pour que le visuel et le son se complémente et intéragissent bien |

# Planification de la production d'un prototype (budget et étapes de réalisation)
## Budget prévisionnel
![Budget prévisionnel](medias/budget_capture_20210113.PNG)

[Lien vers document](https://cmontmorency365.sharepoint.com/:x:/s/TIM-58266B-Expriencemultimdiainteractive-Enseignants/ERS3zx4iKAlLn03N_0h3cyQBOV_nxNuKvrKnqmrXGcgDYg?e=Rjq9Uc)


## Échéancier global
Étapes importantes du projet visualisé dans GitHub (*milestones*):  
https://github.com/tim-montmorency/66B-modele_de_projet/milestones

## Liste des tâches à réaliser
Visualisation des tâches à réaliser dans GitHub selon la méthode Kanban:  
https://github.com/tim-montmorency/66B-modele_de_projet/projects/2?add_cards_query=is%3Aopen

Inventaire des tâches à réaliser dans GitHub selon le répertoire d'*issues*:  
https://github.com/tim-montmorency/66B-modele_de_projet/issues

## Rôles et responsabilités des membres de l'équipe

**Vincent Desjardins**
- Coordination générale du projet (coordination de l'échéancier, du budget, suivi de la liste des tâches à réaliser, s'assurer de la répartition du rôle et des responsabilités des membres de l'équipe);
- Création du module d'interprétation des données;
- Programmation du module Max de contrôle vidéo.

Liste des tâches dans Git Hub:  
https://github.com/tim-montmorency/66B-modele_de_projet/issues/assigned/DarylMomo  
https://github.com/tim-montmorency/66B-modele_de_projet/projects/2?card_filter_query=assignee%3Adarylmomo

**Camélie Laprise**
- Comité Technique et coordination technique (suivi du devis technique);
- Création des paysages sonores sonores;
- Programmation du module Max d'effet et de contrôle audio;
- Installation de l'équipement dans l'espace physique.

Liste des tâches dans Git Hub:  
https://github.com/tim-montmorency/66B-modele_de_projet/issues/assigned/gllmAR
https://github.com/tim-montmorency/66B-modele_de_projet/projects/2?card_filter_query=assignee%3Agllmar

**Ghita Alaoui**
- Installation et mise en place de la capture audiovidéo du projet en temps réel;
- Programmation du module de captation des données;
- Programmation du module de diffusion et d'interaction en ligne (page Web, diffusion vidéo dans Twitch via OBS, interface utilisateur dans Open Stage Control).

Liste des tâches dans Git Hub:  
https://github.com/tim-montmorency/66B-modele_de_projet/issues/assigned/DarylMomo  
https://github.com/tim-montmorency/66B-modele_de_projet/projects/2?card_filter_query=assignee%3Adarylmomo

**Antoine Haddad**
- Coordination artistique (attention plus particulière pour s'assurer que l'intention/concept artistique du projet initial reste, sinon consulter les membres de l'équipe);
- Création des textes poétiques;
- Création des vidéos d'animation 2D;
- Programmation du module Unity d'effets visuels et intégration dans Max.

Liste des tâches dans Git Hub:  
https://github.com/tim-montmorency/66B-modele_de_projet/issues/assigned/gllmAR
https://github.com/tim-montmorency/66B-modele_de_projet/projects/2?card_filter_query=assignee%3Agllmar


Liste des tâches dans Git Hub:  
https://github.com/tim-montmorency/66B-modele_de_projet/issues/assigned/DarylMomo  
https://github.com/tim-montmorency/66B-modele_de_projet/projects/2?card_filter_query=assignee%3Adarylmomo

**Tâches pas encore attribuées**  
https://github.com/tim-montmorency/66B-modele_de_projet/issues?q=is%3Aopen+is%3Aissue+no%3Aassignee

## Moments des rencontres d'équipe
Hebdomadaire
- lundi à 12h (1h-2h) : Rencontre de suivi de projet.

