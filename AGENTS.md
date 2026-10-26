# Project notes for agents

Deliberate decisions in this repo - do NOT silently revert them:

- This fork does not manage Homebrew (no nix-homebrew, no `homebrew` block). This is intentional: the config must work on any Mac, also one where another account owns `/opt/homebrew`. Install apps and CLI tools from nixpkgs in `home.nix` instead.
- Never commit `.no-mistakes/` validation evidence to this public repo. `.no-mistakes/` is gitignored; if a validation pipeline stages evidence into a branch, drop it before merging.

## Maintaining this file

Keep this file for knowledge useful to almost every future agent session in this project.
Do not repeat what the codebase already shows; point to the authoritative file or command instead.
Prefer rewriting or pruning existing entries over appending new ones.
When updating this file, preserve this bar for all agents and keep entries concise.
