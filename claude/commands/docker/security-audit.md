---
description: Audit Docker configuration for security issues and secrets in non-git files
allowed-tools: Task, Read, Bash, Grep, Glob
---

# Docker Security Audit
Audit Docker files for security issues: $ARGUMENTS

## Step 1: Find Docker Files and Git Status
```bash
find . -name "Dockerfile*" -o -name "docker-compose*.yml"
git ls-files --others --exclude-standard  # Find untracked files
```

## Step 2: Security Scan
Use the **docker-security-auditor** agent to check for:
- Exposed secrets in Dockerfiles, docker-compose, .env files
- Secrets in files NOT checked into git (critical!)
- Running containers as root
- Exposed ports and vulnerabilities
- Missing .dockerignore entries
- Base image security issues

## Step 3: Report Findings
Generate report with:
- Critical issues (secrets, root user)
- Files not in git that contain secrets
- Security recommendations
