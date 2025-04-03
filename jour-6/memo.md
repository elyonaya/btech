# ↕ Flexbox ↔️ :

## Concepts de base

- **Flex container** : élément parent avec `display: flex`
- **Flex item** : enfants directs du conteneur flex

```css
.container {
  display: flex;
}
```

## Axes dans flexbox

- **Axe principal** ("_Main axis_") : horizontal par défaut avec `flex-direction: row`, sinon vertical avec `flex-direction: column`
- **Axe secondaire** ("_Cross axis_") : vertical par défaut avec `flex-direction: row`, sinon horizontal avec `flex-direction: column`

## Propriétés de flexbox

### `flex-direction` : direction des items sur l'axe principal

- `row` (par défaut) : de gauche à droite
- `row-reverse` : de droite à gauche
- `column` : de haut en bas
- `column-reverse` : de bas en haut

```css
.container {
  flex-direction: row | row-reverse | column | column-reverse;
}
```

> Ne recopiez le code ci-dessous : il s'agit d'un exemple pour montrer les valeurs possibles.
> "En vrai", on utilisera qu'une seule, comme par exemple `flex-direction: row-reverse;`

### `justify-content` : alignement sur l'axe principal

- `flex-start` (par défaut) : aligné à gauche/haut
- `flex-end` : aligné à droite/bas
- `center` : centré
- `space-between` : espacement égal entre les items
- `space-around` : espacement égal autour des items
- `space-evenly` : espacement uniformément réparti

```css
.container {
  justify-content: flex-start | flex-end | center | space-between | space-around
    | space-evenly;
}
```

> Ne recopiez le code ci-dessous : il s'agit d'un exemple pour montrer les valeurs possibles.
> "En vrai", on utilisera qu'une seule, comme par exemple `justify-content: center;`

### `align-items` : alignement sur l'axe secondaire

- `flex-start` : en haut/à gauche
- `flex-end` : en bas/à droite
- `center` : aligné au centre
- `stretch` (par défaut) : étiré pour remplir l'espace disponible
- `baseline` : aligné sur la ligne de base du texte

```css
.container {
  align-items: flex-start | flex-end | center | stretch | baseline;
}
```

> Ne recopiez le code ci-dessous : il s'agit d'un exemple pour montrer les valeurs possibles.
> "En vrai", on utilisera qu'une seule, comme par exemple `align-items: stretch;`

---

## Ressources utiles

- [CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) : le guide ultime 🇬🇧
- [W3Schools](https://www.w3schools.com/css/css3_flexbox.asp) : avec de vrais morceaux de code _live_ dedans 🇬🇧
- [Believemy](https://believemy.com/r/le-guide-complet-sur-flexbox-css) : plus académique, mais aussi plus poussé 🇫🇷
- [Flexbox Froggy](https://flexboxfroggy.com/#fr) : un petit jeu pour appliquer les différentes propriétés associées à `flexbox` (je vous conseille au moins les 13 premiers niveaux) 🇫🇷🇬🇧
