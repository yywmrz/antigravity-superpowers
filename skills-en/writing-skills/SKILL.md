---
name: writing-skills
description: Skill for creating new skills. Follow best practices to write SKILL.md files. Use when creating or improving Agent skills.
---

# Writing Skills Skill

Learn how to create high-quality Agent skills.

## Skill File Structure

```
.agent/skills/[skill-name]/
├── SKILL.md           # Required: Main instruction file
├── scripts/           # Optional: Helper scripts
├── examples/          # Optional: Example files
└── resources/         # Optional: Other resources
```

## SKILL.md Format

```markdown
---
name: skill-name
description: Clear description of the skill's purpose and trigger conditions
---

# Skill Name

[Detailed skill description]

## Trigger Conditions
[When to use this skill]

## Workflow
[Step-by-step operational guide]

## Best Practices
[Important tips and suggestions]

## Examples
[Usage examples]
```

## Writing Principles

### 1. Clear Description
Description is key for Agent skill discovery:
- ✅ "Check security vulnerabilities and performance issues during code review"
- ❌ "Help review code"

### 2. Specific Instructions
Provide executable steps:
- ✅ "First check if all inputs are validated"
- ❌ "Ensure code is secure"

### 3. Include Examples
Show expected output format:
```markdown
## Example Output
```json
{
  "issues": [
    {"severity": "high", "message": "Unvalidated user input"}
  ]
}
```
```

### 4. Define Decision Trees
Help Agent choose correct actions:
```markdown
## Decision Flow
If [Condition A]:
  Execute [Action A]
Else if [Condition B]:
  Execute [Action B]
Else:
  Execute [Default Action]
```

## Testing Skills
1. Create skill file
2. Trigger related tasks
3. Verify Agent correctly uses the skill
4. Adjust instructions based on results
