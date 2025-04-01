# Jour 5 : Box model

## Exercice 0 : Testez vos connaissances !

Répondez aux questions ci-dessous, en supprimant les réponses qui vous semblent incorrectes pour ne laissez que l'unique bonne réponse.

---

### `display`

**Quel est le display par défaut de la plupart des éléments HTML ?**

2. `block` ou `inline`

---

**Lequel de ces éléments est `inline` par défaut ?**

2. `<a>`

---

**Comment mettre ces paragraphes en ligne ?**

```html
<p>Paragraphe A</p>
<p>Paragraphe B</p>
<p>Paragraphe C</p>
```

2. `p { display: inline; }`

---

**Comment mettre ces éléments de liste en ligne ?**

```html
<ul>
  <li>Element A</li>
  <li>Element B</li>
  <li>Element C</li>
</ul>
```

1. `li { display: inline; }`

---

**Comment mettre la balise `<em>` seule sur toute une ligne ?**

```html
<p>Lorem ipsum <em>dolor</em> sit</p>
```

2. `em { display: block }`

---

**Inversez les display par défaut des balises ci-dessous :**

```html
<h1>Mon <span>titre</span></h1>
```

3. `h1 { display: inline } span { display: block }`

---

### `margin` et `padding`

**Laquelle de ces propriétés permet de changer l'espace entre la bordure et les autres éléments HTML ?**

4. `margin`

---

**Laquelle de ces propriétés permet de changer l'espace entre le contenu et la bordure ?**

2. `padding`

---

**Laquelle de ces propriétés représente le texte ?**

1. `content`

---

**Si on utilise `padding: 30px`, combien il y aura-t-il d'espace à droite ?**

3. 30px

---

**Si on utilise `margin: 10px 20px`, combien il y aura-t-il d'espace à gauche ?**

2. 20px

---

### `height` et `width`

**Donnez une largeur de 500px au contenu d'une `<div>` :**

1. `div { width: 500px }`

---

**Quelle propriété devrait-on utiliser pour définir la taille totale d'un élément, sans prendre en compte le padding, la border ou le margin ?**
`
3. `box-sizing: border-box`
