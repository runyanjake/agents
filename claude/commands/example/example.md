---
description: Example Command for Claude.
argument-hint: <required-arg1> <required-arg2> [optional-arg1] [optional-arg2] (This is just purely for documentation)
allowed-tools: Read, Write, Edit, Bash, Grep, Glob, WebSearch, WebFetch, MultiEdit
model: sonnet
---

# Example Command Name
[Instructions for Claude on what to do]

User request: $ARGUMENTS     <-- $ARGUMENTS is everything the user typed after the command. It is direct text replacement.

## Steps
1. First step
2. Second step
3. Third step

## Report
Use the template at `.claude/commands/example/templates/example-template.md`

