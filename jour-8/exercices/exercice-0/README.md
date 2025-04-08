# Jour 8 : Transitions et Animations

---

## Exercice 0 : Testez vos connaissances !

Répondez aux questions ci-dessous, en supprimant les réponses qui vous semblent incorrectes pour ne laissez que l'unique bonne réponse.

---

**Quelle est la propriété qui effectuera une transition pendant un certain nombre de secondes ?**

3. `transition-duration`

---

**Quelle est la propriété qui démarrera une transition après un certain nombre de secondes ?**

2. `transition-delay`

---

**Quelle est la propriété qui gère l'accélération ou la décélération d'une transition ?**

4. `transition-timing-function`

---

**Quelle réponse est incorrecte ?**

3. `transition-duration: 1000000`

---

**Quelle propriété d'une animation n'existe pas pour une transition ?**

1. `transition|animation-property`

---

**Quelle est la propriété nécessaire à une animation pour retrouver une keyframe ?**

4. `animation-name`

---

**Que manque-t-il à la keyframe 'my-anim' ci-dessous ?**

```css
??? {
  from {
    color: blue;
  }
  to {
    color: red;
  }
}
```

3. `@keyframes my-anim`

---

**Combien de fois l'animation "pulsating" va-t-elle se répéter ?**

```css
div {
  animation-name: pulsating;
  animation-delay: 0.3s;
  animation-duration: 1.7s;
  animation-timing-function: ease-in;
}
```

2. 1 fois

---

**Combien de fois l'animation "wobbling" va-t-elle se répéter ?**

```css
div {
  animation-name: wobbling;
  animation-delay: 0.3s;
  animation-duration: 1.7s;
  animation-timing-function: ease-in;
  animation-iteration-count: 1;
}
```

2. 1 fois