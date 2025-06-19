# Integration Nodes

Two integration nodes are available:

- **API Call**: Makes API requests with properties `method`, `url`, `headers`, `body`. Output is referable with `${{prev.output}}`.
- **LLM Call**: Selects a provider (Claude, OpenAI, Gemini) with a prompt and `memory` property.
