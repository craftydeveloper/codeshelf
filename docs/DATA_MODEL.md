# Data model

## Proposed fields

Snippets need a title, language, code text, tags, and a short usage note.

The examples are synthetic contract examples and are not loaded automatically. Before changing persistence, inspect the current serialized state and write a migration that preserves user data. Validate imported records and avoid storing credentials.