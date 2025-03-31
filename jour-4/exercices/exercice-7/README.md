# Jour 4 : CSS Selectors

## Exercice 7 :

Une [**card**](https://developer.mozilla.org/fr/docs/Web/CSS/Layout_cookbook/Card) est un ensemble d'élément très couramment utilisé sur le web. Pensez à un profil sur un réseau social avec photo, nom, adresse, etc... ou à un produit dans un catalogue avec image, prix, taille, etc...

Dans cet exercice, apprenez à faire vos premières **cards** !

### Consignes

Créez un fichier HTML "index.html" avec :

- un **titre**
- un **paragraphe**
- un **bouton**

Puis créez un fichier "styles.css" avec :

- pour toute une card :
  - une **bordure**
  - une **largeur** de 200 pixels
  - tous les **textes** au centre
- le **titre** en italique
- le **paragraphe** avec une **taille de police** de 14 pixels
- le **bouton** avec :
  - une **couleur de fond** gris foncé
  - une **couleur de texte** gris clair
  - une **bordure** arrondie

> ⚠️ N'utilisez que des classes et des ids pour appliquer le style.

Le résultat devrait ressembler à ceci :

![résultat](https://i.imgur.com/vSLSDMn.png)

Une fois ce résulat atteint, **dupliquez votre card** en ajoutant à chacune d'entre-elles un **id** qui permettra de :

- mettre une **police d'écriture unique**
- donner une **couleur de texte unique** (sauf au texte du bouton)

![résultat-2](https://i.imgur.com/ZXdlXp0.png)

### Conseils

- Une **card** n'est pas directement une balise : `<card>` n'existe pas ! En revanche, `<div>` (vue dans l'exercice précédent) serait très utile ici pour regrouper plusieurs éléments ensemble.
- Inutile de copier/coller le code-exemple de la documentation donné ci-dessus : il est bien trop complexe pour ce qui est demandé ici dans cet exercice.
- Pensez toujours à tester dans votre navigateur !
