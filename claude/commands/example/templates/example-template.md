<!-- 
Instructions: Replace all [[PLACEHOLDERS]] or <place-holders> with actual values
Remove sections marked as optional if they don't apply
-->


# Template 
Templates are just templates - they don't need any YAML frontmatter.

## Section One
Specify what Claude needs to replace using either:
- [UPPER_CASE_IN_BRACKETS]
- <angle-brackets>

<!-- Remove this section if no critical issues found -->
## Section Two
Can still
- **Use standard Markdown**
- etc.

## There also can be logic:
```
[For each secret:
- **File:** [file-path] (NOT IN GIT: [YES/NO])
- **Type:** [API Key / Password / Token / etc.]
- **Line:** [line-number]
- **Pattern:** [What was matched]
- **Action Required:** [Immediate steps]
]
```
