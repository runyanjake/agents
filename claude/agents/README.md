# Agents

Parallelizable agents that can be invoked from the main Claude Code instance.

Link to `~/.claude/agents/` if they should be available user-wide.
Link to `./claude/agents` they should be available in just the project folder.

```bash
ln -sfn /path/to/repo/claude/agents/agent.md /path/to/config/agents/agent.md
```

Then mention agents explicitly by name:
```bash
Use the **docker-expert** to create docker configuration files for this repo.
```

## Example Agent | example.md
An example of agent file syntax.

## Docker Expert | docker-expert.md
A subagent that can dockerize a project, build configuration files for a published container, or tweak incorrect project files.



