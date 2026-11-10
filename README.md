# Cap 90 · Conciergerie de prise de poste

Site vitrine de l'offre Cap 90 : sécuriser les 90 premiers jours des profils clés.

Page unique et statique (`index.html`), sans dépendance à installer. Publiée avec GitHub Pages.

## Brancher le bouton de réservation

Dans `index.html`, en bas du fichier, renseigner le lien de prise de rendez-vous :

```js
const BOOKING_URL = "https://calendly.com/…";
```

Tous les boutons « Réserver » pointeront alors vers ce lien.
