## Exercice 8 : Fetch API et async/await
**Objectif :** Apprendre à faire des requêtes HTTP en utilisant `fetch` avec `async/await`.
<br><br>
1. Définis une fonction nommée `fetchUsers` en utilisant la syntaxe `async`.
    - À l'intérieur de cette fonction, fais une requête GET à l'URL `https://jsonplaceholder.typicode.com/users` en utilisant `fetch`.
    - Attends la réponse de `fetch` en utilisant `await` et stocke-la dans une variable `response`.
    - Parse la réponse en JSON en utilisant `response.json()` et attends le résultat en utilisant `await`. Stocke le résultat dans une variable `data`.
    - Affiche les données `data` dans la console.
    - Retourne les données `data`.
<br><br>
2. Appelle la fonction `fetchUsers` pour exécuter la requête et afficher les données dans la console.
