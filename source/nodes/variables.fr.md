# Nœuds de Variables

Les nœuds de variables définissent des variables d'exécution avec des types : Texte, Nombre, Booléen, Date, Liste, Objet/JSON.

- **Propriétés** : `name` (par ex., `${{name}}`), `value` (référence avec `$` ou valeur typée), `transform` (booléen).
- Si `transform` est vrai, accédez à `transformFn` et `transformParam` pour modifier la variable.
