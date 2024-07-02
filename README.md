## Contexte & Objectifs

Jouez avec le modèle de boîte (`margin/border/padding/width/height`) en divisant vos informations de profil en différents `<div>`.

## Spécifications

Voici [votre objectif](https://lewagon.github.io/html-css-challenges/03-box-model/).

- Vous devriez commencer avec la structure suivante pour votre page :

```html
<div id="container">
  <div class="card"></div>
  <div class="card"></div>
  <div class="card"></div>
  <div class="card"></div>
</div>
```

- Le `<div id="container">` est là pour centrer son contenu afin que vous n'ayez pas une page en plein écran (ce qui est très moche).
- Les `<div class="card"></div>` sont là pour afficher joliment chaque groupe d'informations qui vont ensemble.
- Ajoutez une touche esthétique à ces divs grâce aux propriétés CSS `background`, `border`, `border-radius` et `box-shadow`.

## Conseils & Ressources

Voici la technique de centrage des divs pour le conteneur principal :

```css
div {
  width: 500px;
  margin: 0 auto; /* vous pouvez changer 0 si vous voulez un margin top-bottom */
}
```
