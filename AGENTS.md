# Agent Guidelines for dccgame

This repository currently centers on `flesh_pits_v2_engine.html`. Use these guidelines before changing any files.

## General expectations
- Keep edits focused and describe why changes are needed in commit messages.
- Prefer small, reviewable changes rather than sweeping rewrites.
- When altering behavior or visuals in the HTML, first read the specialized instructions in the scoped `AGENTS.md` files described below.

## Specialized scopes
- **Functionality changes** (logic, gameplay flow, inputs, data handling): follow the rules in `functionality/AGENTS.md` even when editing files that live outside that folder.
- **Appearance changes** (styling, layout, color, typography, spacing): follow `appearance/AGENTS.md`.

If you add new directories for assets or content, place another `AGENTS.md` inside them with any additional rules the area requires.
