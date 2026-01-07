# Commands 
One-off commands that you can invoke.

Link to `~/.claude/commands/` if they should be available user-wide.
Link to `./claude/commands` they should be available in just the project folder.

Example:
```bash
ln -sfn /path/to/repo/claude/commands/command.md /path/to/claude/commands/command.md
ln -sfn /path/to/repo/claude/commands/command-folder/ /path/to/claude/commands/comamnd-folder/
```

Commands have a notion of namespacing and it's based on the folder structure under `commands/`.
Invoke these commands by namespace like `/git:commit`.

