# Jour 12 : Révisions - Positions

## Exercice 1 :

> Pour cet exercice, vous aurez besoin d'utiliser les propriétés de [`positions`](https://developer.mozilla.org/fr/docs/Web/CSS/position), pas `display`, ni `transform`.

- Créez six carrés rouges à partir de `<div>` (avec ou sans texte, au choix)
- Placez ces six `<div>` dans un conteneur parent (au choix), et centrez-les horizontalement à l'intérieur
- Entourez le conteneur des six `<div>` d'une bordure noire
- Décalez légèrement les carrés pairs sur la droite à l'aide d'un positionnement relatif
- Décalez légèrement les carrés impairs sur la droite à l'aide d'un positionnement relatif

- Placez les trois `<div>` sur une seule ligne (horizontalement), dans un nouvel élément parent qui n'est pas directement `<body>`
- Entourez chaque `<div>` d'une fine bordure bleue
- Espacez chaque `<div>` avec un peu de marge

![resultat](https://i.imgur.com/WBNUUQN.png)

## Conseils

- `<main>`, `<section>` ou même `<body>` etc... sont autant de balises qui peuvent remplacer `<div>`
- N'utilisez pas de positionnements absolus ou fixes pour les six `<div>` ; seulement relatifs
- Utilisez `flexbox` pour centrer les six `<div>` dans le conteneur parent
- La largeur de la capture d'écran est volontairement réduite pour des raisons de visibilités ; vous n'avez pas besoin de changer la taille de votre navigateur.
