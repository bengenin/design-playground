# AGENTS.md

## Purpose

This repository is Ben's public design playground: a collection of small interface, interaction, typography, motion, and web experiments.

Treat the repository as a public-facing archive of design exploration. Keep it easy to browse, easy to run locally, and clean enough that someone discovering it on GitHub can understand what each experiment is for.

## Instructions for Codex

1. Keep every experiment self-contained in its own folder.
2. Do not change unrelated experiments unless the task explicitly requires it.
3. Before editing, inspect the relevant files and understand the existing implementation.
4. Prefer the smallest coherent change that achieves the requested visual or interaction result.
5. Use plain HTML, CSS, and JavaScript for lightweight prototypes unless there is a clear reason to introduce a framework.
6. Avoid unnecessary packages, build tooling, and abstractions.
7. Preserve responsive behavior and accessibility basics.
8. For motion, support `prefers-reduced-motion` where practical.
9. Do not add secrets, API keys, tokens, private data, customer material, or internal company content.
10. Do not expose local machine paths or personal credentials in committed files.
11. Keep code readable enough for a non-developer to continue editing with an AI coding assistant.
12. When an experiment becomes worth surfacing, update the root `README.md`.
13. Do not reorganize the whole repository unless explicitly asked.
14. If a requested change introduces a significant dependency or architectural decision, explain the tradeoff before implementing it.

## Design direction

Favor restraint, proportion, typography, spacing, and interaction quality. The work should feel considered rather than decorated.

Avoid generic SaaS styling, excessive cards, gratuitous gradients, heavy shadows, cyberpunk or hacker aesthetics, and unnecessary animation unless the experiment specifically calls for them.

When reproducing a reference, identify the underlying design characteristics instead of blindly copying surface details.

## Repository structure

- `website-intro/` - entrance animations and identity experiments
- `navigation/` - navigation and menu studies
- `typography/` - typography and hierarchy studies
- `interactions/` - micro-interactions and motion
- `layouts/` - page composition and responsive layout studies
- `references/` - design references and notes

## Validation

Before considering a task complete:

- Check that the changed prototype still runs.
- Check desktop and narrow/mobile layouts where relevant.
- Check for obvious console errors.
- Confirm no secrets or private material were introduced.
- Summarize what changed and identify the main files edited.
