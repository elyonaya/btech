# Jour 11 : Responsive

## Exercice 6 :

Réalisez votre premier **menu burger** qui s'affichera lorsque l'on passe la souris dessus !

En quelques mots, un **menu burger** en HTML et CSS est un autre composant de Material Design. Il s'agit d'un menu de navigation compact, souvent affiché par trois barres empilées (comme un burger!). On l'utilise sur les sites web pour économiser de l’espace, surtout sur mobile.

1. Créez un fichier "index.html" avec :
  - un **conteneur** (eg. `<div>`) pour le menu burger
  - à l'intérieur du **conteneur**, de quoi représenter les trois barres du menu burger (par exemple trois `<span>`)
  - plusieurs **liens**

2. Créez un fichier "styles.css" avec :
  - le menu qui doit être **fixé** en haut à gauche de la page
  - l’icône burger qui doit être composée de trois barres horizontales
  - la liste de **liens** doit être cachée par défaut
  - lorsqu'on passera la souris sur le menu burger, la liste doit "glisser" vers la droite pour devenir visible :
    - ajouter un effet de **transition** pour l'apparition du menu
    - changer le fond ou la couleur de texte des liens lorsque l'on passe la souris dessus ainsi que changer son curseur ; pour toujours savoir qu'il s'agit de liens

Par la suite, c'est à vous d'améliorer le style comme bon vous semble ! Par exemple, avec un menu burger, on retrouve souvent :
  - une navbar classique en mode desktop, et le menu burger en mode mobile
  - les trois barres horizontales qui se "croisent" avant de faire apparaître le menu
  - le fait que le menu soit "activable" plutôt qu'avec un hover ; on pourrait déplacer la souris en dehors de la zone sans le faire disparaître
  - etc...

![resultat](https://i.imgur.com/sT9ukZs.gif)

### Conseils

- Faîtes d'abord simple, ne cherchez pas à tout de suite faire les choses parfaitement. Il vaut mieux avoir un menu burger "moche" mais fonctionnel plutôt que quelque chose de joli mais qui ne s'affiche pas par un hover
- Les trois barres horizontales sont simplement des rectangles vides mais remplis de couleurs, comme vous avez vu avec le cours sur les Transformations et la Géométrie.
