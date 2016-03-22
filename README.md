# NS-FrontGuide

## JS

### Best practice

* Pour classes qui sont utilisée par le JS, ajouter un préfixe `js-*`
* Il vaut mieux manipuler le template que le DOM
* En JS, utiliser append/prepend si possible, after/before si on n’a pas le choix.

## HTML

### Best practice
* Le développeur doit avoir en tête qu’une classe non-préfixe par js- peut changer de nom par l’intégrateur.
* Faire le moins d’élément possible :
** eviter les élements sans id ou classe



### Best practice

* ID unique sur une page

## CSS

### Conventions de nommage

* Pas de majuscule
* Linters jscs ou travailler sans outils ?
* Références : airbnb ?
* On respecte la convention de nommage du projet

### Tools

* [less](http://lesscss.org/)
* (grunt task)

### Best practices

* Privilégier les classes du framework
* Pas de css sur des id mais sur des classes
* Pour ajouter du contenu (nontextuel) privilégier after/before




## Architecture 


### Modules

* Un module == (js) + (templates) + (css)
* Proposition : Mettre le less dans les modules.
* Fichier < 300 lignes


### Coding style

* Ecrire code et commentaires en anglais


## Autre

 * Dans le README=> mettre pour chaque règle un exemple bien + un exemple pas bien

