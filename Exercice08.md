## Exercice 9 : Fetch API et async/await
**Objectif :** Apprendre à faire des requêtes HTTP en utilisant `fetch` avec `async/await` et gérer les promesses de manière plus lisible.
<br><br>
1. Définis une fonction nommée `fetchUsers` en utilisant la syntaxe `async`.
    - À l'intérieur de cette fonction, fais une requête GET à l'URL `https://jsonplaceholder.typicode.com/users` en utilisant `fetch`.
    - Attends la réponse de `fetch` en utilisant `await` et stocke-la dans une variable `response`.
    - Parse la réponse en JSON en utilisant `response.json()` et attends le résultat en utilisant `await`. Stocke le résultat dans une variable `data`.
    - Retourne les données `data`.
<br><br>
2. Définis une fonction nommée `getUsers` en utilisant la syntaxe `async`.
    - À l'intérieur de cette fonction, appelle `fetchUsers` et attends les données retournées en utilisant `await`. Stocke le résultat dans une variable `users`.
    - Utilise la méthode `map` pour créer un tableau contenant uniquement les noms des utilisateurs et affiche ce tableau dans la console.
<br><br>
3. Appelle la fonction `getUsers` pour exécuter le flux complet.
