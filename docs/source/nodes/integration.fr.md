# Nœuds d'Intégration

Deux nœuds d'intégration sont disponibles :

- **Appel API** : Effectue des requêtes API avec les propriétés `method`, `url`, `headers`, `body`. La sortie est référencée avec `${{prev.output}}`.
- **Appel LLM** : Sélectionne un fournisseur (Claude, OpenAI, Gemini) avec un prompt et la propriété `memory`.
