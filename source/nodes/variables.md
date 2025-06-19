# Variables Nodes

Variables nodes define execution variables with types: Text, Number, Boolean, Date, List, Object/JSON.

- **Properties**: `name` (e.g., `${{name}}`), `value` (reference with `$` or typed value), `transform` (boolean).
- If `transform` is true, access `transformFn` and `transformParam` to modify the variable.
