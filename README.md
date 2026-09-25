# EssenceBound

First playable browser build of the card game.

## Current playable slice

- Five Essence starter paths
- Ornate dark-fantasy interface
- 20-card starter decks
- Creatures and spells
- Essence/mana progression
- Creature combat and direct attacks
- AI opponent
- Win/loss rewards

The game is a static site: no game engine, Node.js, or build step is required.

## Browser deployment

A GitHub Pages workflow is included in `.github/workflows/pages.yml`.
Once GitHub Pages is enabled with **Source: GitHub Actions**, every push to `main`
will publish the newest version.
