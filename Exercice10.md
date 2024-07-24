## Exercice 11 : Utilisation de `filter`
**Objectif :** Apprendre à utiliser la méthode `filter` pour filtrer des données.
<br><br>
1. Réutilisez le code de l'exercice précédent pour récupérer les utilisateurs depuis l'API `https://jsonplaceholder.typicode.com/users`.
   <br><br>
2. Déclarez une fonction `getUsersWithBizEmails` qui :
    - Utilise `fetchUsers` pour récupérer les utilisateurs.
    - Utilise la méthode `filter` pour créer un nouveau tableau contenant uniquement les utilisateurs dont l'email se termine par `.biz`.
    - Affiche dans la console le nombre d'utilisateurs ayant un email se terminant par `.biz` et leurs noms, formaté comme suit : "X users have a .biz email: User1, User2, ...".
    - Retourne le tableau des utilisateurs filtrés.
<br><br>
3. Déclarez une fonction `displayUsers` qui :
    - Appelle `getUsers` pour récupérer et afficher tous les noms d'utilisateurs.
    - Appelle `getUsersWithBizEmails` pour afficher les utilisateurs ayant un email se terminant par `.biz`.
    - Affiche tous les noms d'utilisateurs récupérés dans la console.
<br><br>
4. Appelez la fonction `displayUsers` pour exécuter le flux complet.
