# Functionality Changes

Use these rules when adjusting gameplay logic, input handling, or data mutations.

- Keep JavaScript functions small and descriptive; prefer pure functions where possible.
- Comment non-obvious state changes and document expected inputs/outputs near the functions they describe.
- Favor progressive enhancement: core interactions should still work if cosmetic effects are unavailable.
- Avoid introducing hidden globals; keep new symbols scoped to modules or IIFEs.
- When refactoring, change one behavior at a time and note the rationale in the commit message.
