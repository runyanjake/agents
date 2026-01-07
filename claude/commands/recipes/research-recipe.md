---
description: Recipe researcher that reads a recipe page and formats it for Docusaurus.
argument-hint: <recipe-url>
allowed-tools: Write, WebFetch
---

# Research Recipe
User Request: $AGRUMENTS

## Steps
1. Read the data on the page passed in as the first argument and identify the ingredients list, cooking steps list, and any special instructions from the recipe.
2. Create a new file named after the recipe. Use kebab case for the naming. Use the template at `~/.claude/commands/recipes/templates/recipe-template.md`.
