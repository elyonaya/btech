# Jour 4 : CSS Selectors

## Exercice 6 :

Vous avez déjà rencontré des "**conteneurs**" sans le savoir : **des balises qui regroupent d'autres balises**.

Par exemple :
- un `<p>` qui contient des `<a>`
- un `<ul>` qui contient des `<li>`
- et d'autres !

La balise [`<div>`](https://developer.mozilla.org/fr/docs/Web/HTML/Element/div) est également un **conteneur**, mais sans signification spécifique en HTML. C’est une simple "boîte" utilisée pour regrouper des éléments et leur appliquer du style commun. Ce n'est pas un paragraphe, ce n'est pas un titre, ... c'est juste "une boîte".

> Cet exercice est en fait plus un guide, mais il est important pour les prochains exercices (et futurs cours) : prenez le temps de le faire, demandez de l'aide si besoin !

### Consignes

Créez un fichier "index.html" avec :

- son **boilerplate**
- deux **paragraphes** avec chacun la classe `bordure-paragraphe`
- une balise **`<div>`** avec un id `container` contenant :
  - deux autres **paragraphes** avec aussi la classe `bordure-paragraphe`

Créez un fichier "styles.css" avec :

- une **bordure** "continue" bleue à la classe "bordure-paragraphe"
- une **bordure** "en pointillée" rouge et une **couleur de fond** orange à l'id "container"

👉 Observez le résultat :

![résultat](https://i.imgur.com/TSZhjXQ.png)

- chaque paragraphe est entouré d'une bordure bleue
- mais la `<div>` entoure les deux autres paragraphes en rouge, autour des deux en même temps !
- on voit d'ailleurs toute la zone que représente la `<div>`, en orange

### Rappels

- Ne faîtes pas attention à la largeur des listes sur la capture d'écran ; inutile d'essayer de changer la largeur des vôtres.
- Pensez néanmoins à tester sur votre navigateur !
