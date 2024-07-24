## Exercice 7 : Promises
**Objectif :** Comprendre les promesses avec un exemple simple.
<br><br>
1. Définis une fonction nommée `getNumber` qui retourne une promesse.
    - Dans cette fonction, génère un nombre aléatoire entre 0 et 1.
    - Si le nombre est supérieur à 0.5, résous la promesse avec ce nombre.
    - Si le nombre est inférieur ou égal à 0.5, rejette la promesse avec un message d'erreur (par exemple, "Number is too small").
<br><br>
2. Utilise la fonction `getNumber` pour obtenir une promesse.
    - Si la promesse est résolue avec succès, affiche le message "Success: " suivi du nombre dans la console.
    - Si la promesse est rejetée, affiche le message "Error: " suivi du message d'erreur dans la console.
