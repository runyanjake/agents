---
name: Example Skill (Named similarly to directory but can be human-readable)
description: Verbose description of the skill.
allowed-tools: Read, Grep, Bash
license: optional
---

# Example Skill

## Purpose

## When Claude Uses This

## Ability 1

### 1. Step 1 Name
Steps may include explicit commands:
```bash
find . -name "Dockerfile*" -o -name "docker-compose*.yml"
```

### 2. Step 2 Name
They may include verbose descriptions:

Check for:
- Running as root (missing USER directive)
- Using `latest` tags
- Exposed secrets in ENV
- Privileged containers
- Exposed ports

### 3. Step 3 Name
They may include items to bring into context:

For comprehensive checks, read `resources/example-checklist.md`Use template in `resources/example-template.md`

### 4. Step 4 Name
Or they may invoke scripts:

Run automated scan: `python scripts/example-scanner.py <path>`


