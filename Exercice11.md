## Exercice 11 : Utilisation de `reduce`
**Objectif :** Apprendre à utiliser la méthode `reduce` pour agréger des données.
<br><br>
1. Réutilisez le code des exercices précédents pour récupérer les utilisateurs depuis l'API `https://jsonplaceholder.typicode.com/users` et stocker les noms et les salaires dans un tableau `listOfUsers`.
<br><br>
2. Déclarez une fonction `getUsers` qui :
    - Utilise `fetchUsers` pour récupérer les utilisateurs.
    - Pour chaque utilisateur récupéré, ajoute un champ `salary` avec une valeur aléatoire entre 30000 et 80000.
    - Stocke les utilisateurs avec leurs salaires dans un tableau `listOfUsers`.
<br><br>
3. Déclarez une fonction `getAverageSalary` qui :
    - Utilise la méthode `reduce` pour calculer le total des salaires des utilisateurs dans `listOfUsers`.
    - Calcule la moyenne des salaires en divisant le total des salaires par le nombre d'utilisateurs.
    - Affiche dans la console la moyenne des salaires, formatée comme suit : "The average salary is : X".
<br><br>
4. Déclarez une fonction `displayUsers` qui :
    - Appelle `getUsers` pour récupérer et afficher tous les noms d'utilisateurs et leurs salaires.
    - Appelle `getUsersWithBizEmails` pour afficher les utilisateurs ayant un email se terminant par `.biz`.
    - Appelle `getAverageSalary` pour afficher la moyenne des salaires des utilisateurs.
    - Affiche tous les utilisateurs récupérés et leurs salaires dans la console.
<br><br>
5. Appelez la fonction `displayUsers` pour exécuter le flux complet.
<br><br>
### Exemple de code pour ajouter les salaires au tableau listOfUsers

```javascript
const getUsers = async () => {
  const users = await fetchUsers();
  users.map((user) => listOfUsers.push(
    {
      name: user.name,
      salary: Math.floor(Math.random() * 50000) + 30000 // Random salary between 30000 and 80000
    }
  ));
}
```
