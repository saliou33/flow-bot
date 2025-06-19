# Introduction aux Flux de Travail

Les flux de travail FlowBot sont construits à l'aide d'une interface visuelle de nœuds, prenant en charge diverses catégories de nœuds : Déclencheur, Message, Opérateur, Variables et Intégration. Chaque catégorie propose des types spécifiques pour créer une automation complexe.

## Catégories de nœuds

Des aperçus brefs sont fournis dans la section [Nœuds](../nodes/trigger.fr.md).

## Référencement

Utilisez `${{var.name}}` pour référencer des variables, `${{context}}` pour le contexte global, et `prev.output`/`prev.meta` pour les données du nœud précédent.

## Exécution

Les flux s'exécutent en fonction des déclencheurs, avec un suivi en temps réel et une évaluation des variables.
