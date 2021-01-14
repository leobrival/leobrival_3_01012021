# Ohmyfood
Troisième projet du parcours "Développeur Front-End" d'OpenClassrooms. L'objectif de ce projet est de dynamiser une page web avec des animations CSS.

![Maquette de Ohmyfood](https://user.oc-static.com/upload/2020/08/24/15982605908418_Maquettes%20Ohmyfood.jpg)

## Cahier des charges
- L'intégration doit se faire uniquement en HTML5 et CSS3 sans JavaScript.
- Le site doit être fait sans framework, mais l'utilisation de SASS est un plus.
- Le HTML et le CSS doivent être séparés et le fichier doit être organisé.
- L'approche utilisée doit être mibile-first, toutefois le site doit être responvise sur tablette et desktop.
- Le code doit être sémantiquement correct et ne doit contenir aucune erreur au validateur W3C.
- Le site doit être compatible avec les dernières versions de Chrome et Firefox.
- Le code doit être versionné avec Git et doit avoir un dépôt sur GitHub  ou GitLab.
- Le site doit être déployé.

## Livrables attendus
### Contenu des pages
#### Page d'accueil (x1)
- Affichage de la localisation des restaurants (à terme, il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu).
- Une courte présentation de l’entreprise.
- Une section contenant les 4 menus sous forme cartes ( au clic sur la carte,
l’utilisateur est redirigé vers la page du menu).

#### Pages de menu (x4)
- 4 pages contenant chacune le menu d’un restaurant.

#### Header
- Le header est présent sur toutes les pages.
  - Sur la page d’accueil, il contient le logo du site.
  - Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.


#### Footer
-  Le footer est identique sur toutes les pages.
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

### Effets graphiques et animations
Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils doivent utiliser les animations ou transitions CSS, sans JavaScript ni de librairie.

- Au survol sur les boutons principaux, la couleur de fond doit légèrement s’éclaircir.
- Au survol, un remplissage progressif doit être présent sur le bouton "j'aime".

- Quand l'application démarre un exemple de "loading spinner" doit être présent.
- Les plats doivent apparaître progressivement avec un léger décalage dans le temps (exemple de l'effet fourni).
- Faire coulisser une coche de validation au survol pour que le visiteur ajoute les plats à sa commande (exemple de l'effet fourni).


## Éléments fournis pour le projet
- Les [maquettes](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/DW_P3/Maquettes%20Ohmyfood.zip) à intégrer au format téléphone.
- Les vidéos d'illustration des animations.
- Les images présentes dans les maquettes.
- La liste des différents menus proposée par restaurants.
- Le [brief](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/DW_P3/Brief%20cre%CC%81atif%20-%20Ohmyfood!.pdf) du projet.
 - Les polices [Roboto](https://fonts.google.com/specimen/Roboto) et [Shrikhand](https://fonts.google.com/specimen/Shrikhand?query=Shrikhand).
 - Les couleurs de la charte :
  - Primaire : #9356DC
  - Secondaire : #FF79DA
  - Tertiaire : #99E2D0

## Note du projet
- L'intégration de la maquette à été réalisée sur l'éditeur [Brackets](http://brackets.io/) sans plugins.
- La convention de nommage utilisée est BEM.
- Le workflow Git utilisé est Gitflow.
- Les fichiers Sass sont morcelés pour une codebase plus organiser.
- Les iconographies utilisées viennent du site [Font Awesome](https://fontawesome.com/).
