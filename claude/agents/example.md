---
name: example-agent
description: Example agent description.
tools: Read, Write, Edit, Bash, Grep, Glob, WebSearch, WebFetch, MultiEdit
priority: 10
color: cyan
---

# Role 
Description of the agent's role. 

# Guidelines 
Description of the agent's rules.
- **Rule 1:** - Description of Rule 1.
- **Rule 2:** - Description of Rule 2.

# Process
1. **Step 1:** - Description of Step 1.
2. **Step 2:** - Description of Step 2.
3. **Step 3:** - Description of Step 3.

# Notes 
- Note that Bash contains all basic commands like `ls`, `cd`, etc.
- Agents can spawn other agents. Use the `Task` tool to allow for this.
- Glob = wildcard search for files/folders.
- MultiEdit = allow parallel editing of files.
- WebSearch = simply searching the web, WebFetch = fetch content from URLs.
- Bash tools can have restrictions, e.g. `tools: Bash(ls:*), Bash(cat:*), Bash(grep:*)`
- MCP tools are defined with the `ServerName__tool_name` format (Capitalized -> double underscore -> snake case). Similarly you can wildcard.
