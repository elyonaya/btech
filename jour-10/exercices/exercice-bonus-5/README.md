# Jour 10 : Positions

## Mini-cours bonus : créer un bouton interactif sans JavaScript

Observez le code dans les fichiers "demo.html" et "demo.css" : il s'agit du code de l'exercice 5 avec quelques modifications. Désormais, quand on clique sur le badge, la card disparaît. Et on peut le faire sans JavaScript, avec uniquement avec HTML et CSS !

Détaillons le code ensemble (vous trouverez des commentaires numérotés : il s'agit des étapes ci-dessous) :

1. `<input type="checkbox" id="close-card" hidden>` :
  - c'est une **case à cocher**, à qui on donne un id (`id="close-card"`) pour pouvoir la retrouver plus tard et qu'on cache grâce à `hidden` pour qu'elle ne s'affiche pas à l’écran
  - pourquoi une **checkbox** ? Parce qu’elle a deux états : cochée ✅ ou pas cochée ⬜. On peut utiliser cet état pour changer l'apparence d’un autre élément en CSS, comme faire disparaître la carte quand elle est cochée.

2. `<label for="close-card" class="badge">X</label>` :
  - le badge avec la croix ("X") est un **label** : c’est un bouton cliquable qui est lié à la checkbox grâce à `for="close-card"`. Donc quand on clique dessus, ça coche la case cachée !

3. `#close-card:checked + .container` :
  - si la checkbox est cochée (`:checked`), alors l’élément juste après (avec `+ .container`) doit être masqué (`display: none`)

## Exercice bonus 5 :

Maintenant, à vous d'utiliser ce principe pour un nouvel élément de Material Design : la **modale** !

1. Créez un fichier "index.html" avec :
  - un premier **label** ressemblant à un bouton permettant de faire apparaître la div détaillée ci-après
  - une **div** contenant un **paragraphe** et un second **label** (le **badge**) permettant de faire disparaître cette div (avec son paragraphe et son badge)

2. Créez un fichier "styles.css" :
  - le premier label aura :
    - un **fond de couleur** et/ou une **bordure**
    - des **angles arrondis**
    - un **effet de zoom** lorsqu'on passe la souris par dessus ; avec une **transition**
    - un **changement de curseur** lorsqu'on passe la souris par dessus
  - la div aura :
    - un **fond de couleur** et/ou une **bordure**
    - son badge **positionné** au même endroit que dans l'exercice 5

![resultat](https://i.imgur.com/4wHc1lu.gif)

### Conseils

- Voici un autre [exemple de modale](https://getbootstrap.com/docs/5.3/components/modal/#static-backdrop) ; faîtes la par vos propres moyens, sans frameworks et uniquement avec HTML et CSS.
- Vous pouvez reprendre le style du badge de l'exercice 5 ou celui fournait dans "demo.html".
- Cet exercice est probablement le plus complexe que vous ayez rencontré : prenez votre temps pour le réaliser petit à petit, étape par étape.
