### Exercice 6 : Event Listeners
**Objectif :** Comprendre et utiliser les event listeners pour interagir avec le DOM.
<br><br>
1. Ajoute un bouton avec l'id `myButton` dans ton HTML.
<br><br>
2. Déclare un tableau `arrayOfColors` contenant plusieurs noms de couleurs (par exemple : `'blue'`, `'green'`, `'red'`, `'yellow'`).
<br><br>
3. Définis une fonction `randomColor` qui change la couleur de fond du document en une couleur aléatoire du tableau `arrayOfColors`.
<br><br>
4. Utilise `document.getElementById` pour sélectionner le bouton par son id `myButton` et stocke-le dans une variable `BigRedButton`.
<br><br>
5. Ajoute un event listener au bouton `BigRedButton` pour écouter l'événement `click`.
    - Lorsque le bouton est cliqué, la fonction `randomColor` doit être appelée pour changer la couleur de fond du document.
