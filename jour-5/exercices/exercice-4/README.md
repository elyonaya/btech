# Jour 5 : Box-model

Découvrez la **sémantique HTML** : certaines balises ont un style CSS identique, mais ont un sens différent en HTML, ou même visuellement sur une page.
Par exemple :
- un menu pour naviguer d'une page à une autre sera contenu dans une balise `<nav>`
- une barre sur le coté de l'écran sera dans une balise `<aside>`
- etc...

> Vous pouvez découvrir le reste de cette liste sur [la documentation sur la sémantique](https://www.w3schools.com/html/html5_semantic_elements.asp) !

## Exercice 4 :

1. Créez un fichier "index.html" avec un **container** qui aura :
  - un **en-tête**
  - un **contenu principal**
  - un **pied-de-page**

2. Créez un fichier "styles.css" avec :
  - pour le **container** :
    - une largeur totale de 500 pixels
    - une bordure de 2 pixels
  - pour l'**en-tête** :
    - centré et gras
    - une bordure de 2 pixels
    - un padding (espace entre son contenu et sa bordure) de 20 pixels
  - pour le **contenu principal** :
    - centré et italique
    - une bordure de 3 pixels
    - un padding de 16 pixels en haut et en bas, et de 8 pixels à gauche et à droite
  - pour le **pied-de-page** :
    - centré
    - une bordure de 2 pixels
    - un padding de 8 pixels

Voici à quoi doit ressembler le résulat : ![résultat](https://i.imgur.com/etGCfNd.png)

### Conseils

- Le résultat sur la capture d'écran est une approximation ; inutile d'essayer de faire "parfait" !
- Codez petit à petit, et testez sur votre navigateur régulièrement.
- On ne verra normalement pas la bordure du **container** une fois les autres éléments ajoutés ; c'est normal, et ça aura son importance dans l'exercice suivant.
