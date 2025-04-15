# Jour 10 : Positions

---

## Exercice 0 : Testez vos connaissances !

Répondez aux questions ci-dessous, en supprimant les réponses qui vous semblent incorrectes pour ne laissez que l'unique bonne réponse.

---

**Quelle est la valeur par défaut de la position d'un élément HTML ?**

1. `static`

---

**Quelle valeur d'une position permet à un élément de rester au même endroit, même lorsqu'on fera défiler la page ?**

4. `fixed`

---

**Où se place un élément avec la position `absolute` qui n'a pas de parent positionné ?**

2. Par rapport au `body`

---

**De quoi a-t-on besoin pour déplacer un élément avec une position `relative` ?**

1. Au moins une direction comme "top", "bottom", "left" ou "right"

---

**Comment rendre le footer ci-dessous figé et en bas de la page ?**

```css
footer {
  position: ???;
  ???: 0px;
}
```

4. `fixed` et `bottom`

---

**Quelles positions utiliser pour placer ".enfant" en haut à droite de ".parent" ?**

```html
<div class="parent">
  <div class="enfant">Lorem</div>
</div>
```

```css
.parent {
  position: ???;
  height: 200px;
  width: 200px;
}

.enfant {
  position: ???;
}
```

(Ordre ".parent" et ".enfant" ci-après)

2. `relative` et `absolute`
