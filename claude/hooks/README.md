# Hooks
Actions that are invoked at certain points in the Claude Code lifecycle.

Hooks are not based on a file being included but rather are incldued in `settings/settings.json` or `settings/settings.local.json`.
- Use `.claude/settings.json` for project actions shared with team (check this into git)
- Use `.claude/settings.local.json` for personal project actions (add this to a .gitignore)
- Use ~/.claude/settings.json for hooks that should be user-wide`

You can create these via the `/hooks` command (recommended) but can also edit `settings.*.json` explicitly.

See [Hooks Reference](https://code.claude.com/docs/en/hooks).
