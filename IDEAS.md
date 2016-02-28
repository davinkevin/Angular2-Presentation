# Présentation Angular2 


Liste des iédes de slides :

* Myth Busters :
 * NG-Europe 2014
 * @tScript
 * Directive automatiquement gérées

* Reprendre Une partie de la présentation Angular2 de Brad Green fait à AngularConnect (https://www.youtube.com/watch?v=UxjgUjVpe24)

* Expliquer le découpage :
 * di.js
 * Zone.js (proposition au TC39 le 5 février 2016)
 * Moteur de template pas que HTML (XML / WebGL...)
 * Basé sur SystemJS et la spécification es2015

* Le langage
 * Typescript conseillé
 * ES6 (stage 4 ou stage 0)
 * Plain Old Javascript 
 * DART
=> Reprendre le slide de Brad Green sur le choix du langage

* Focus sur le typescrypt:
 * Support par les IDE
 * Erreur durant la transpilation et non au runtime

* Au dela du browser :
 * Les services workers peuvent etre géré par le framework angular2
 * Le code front-end peut etre utilisé coté backend afin de favoriser l'isomorphisme
 le rendu de la 1er page peut etre effectuée coté backend afin de favoriser le loading et pour améliorer le seo (minime)

Angular2 par rapport à Angular 1 :
* Plus proche du dom
* hautement basé sur les observable et Rx
* plus de dépendences à jquery, simplement basé sur l'api du navigateur
Migration angular1 vers angular2 :
* Conseillé ? 
* ngUpgrade, ngForward ?
* Remplacement petit à petit... ou pas !
* Cout d'une migration 1 vers 2 : Simple si bien codé.

Etat d'angular et ANgular2 aujourd'hui
* La version 1.5 vient de sortir amenant la syntaxe "component" et le multi-transclude
* sortie de la version Beta 3 

Lecture : 
* Ninja-Squad : Angular2
* Nouveau styleGuide
* ng-book 2