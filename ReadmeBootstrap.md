#BOOT STRAP

##Présentation

Bootstrap est un framework CSS, mais pas seulement, puisqu'il embarque également des composants HTML et JavaScript. Il comporte un système de grille simple et efficace pour mettre en ordre l'aspect visuel d'une page web. Il apporte du style pour les boutons, les formulaires, la navigation… Il permet ainsi de concevoir un site web rapidement et avec peu de lignes de code ajoutées. Le framework le plus proche de Bootstrap est sans doute Foundation qui est présenté comme « The most advanced responsive front-end framework in the world ». Cette absence de modestie est-elle de mise ? Je pense que c'est surtout une affaire de goût et de préférence personnelle. En tout cas en terme de popularité c'est Bootstrap qui l'emporte haut la main.

###Les intêrets

Les navigateurs sont pleins de fantaisies et ont des comportements très différents malgré leur lente convergence vers les standards. Les frameworks sont cross-browser, c'est à dire que la présentation est similaire quel que soit le navigateur utilisé et d'une parfaite compatibilité .
Les frameworks CSS font gagner du temps de développement parce qu'ils nous proposent les fondations de la présentation.
Les frameworks CSS normalisent la présentation en proposant un ensemble homogène de styles.
Les frameworks CSS proposent en général une grille pour faciliter le positionnement des éléments.
Les frameworks CSS offrent souvent des éléments complémentaires : boutons esthétiques, barres de navigation, etc...
La grande diffusion de nouveaux moyens de visualisation du web (smartphones, tablettes…) impose désormais la prise en compte de tailles d'écran très variées ; les frameworks CSS prennent généralement en compte cette contrainte.

###Les inconvénients

Pour utiliser efficacement un framework il faut bien le connaître, ce qui implique un temps d'apprentissage.
La normalisation de la présentation peut devenir lassante en lissant les effets visuels.

##Les valeurs de références :

* Smartphone : < 768 px
* Tablette : >= 768 px
* Pc portable : >= 992 px
* Desktop : >= 1200 px

####Exemple :

	@media (min-width: 992px) {
	.container {
    width: 970px;
	}
	}

Du plus étroit vers le plus large 
## Les codes à connaître

	.row {
	margin-right: -15px;
	margin-left: -15px;
	}

Pour selectionner un type de colonne en particulier

	.row [class^="col-"]{
	
	}


### Batteries de 12 classes
	col-xs-1 ou col-sm-1 ou col-md-1 ou col-lg-1
	col-xs-2 ou col-sm-2 ou col-md-2 ou col-lg-2
	...
	col-xs-12 ou col-sm-12 ou col-md-12 ou col-lg-12

Exemple : 
	
	col-md-6
	col ==> colonne
	md ==> type medium
	6 ==> de taille 6

###Sauter des colonnes
	col-*-offset-1