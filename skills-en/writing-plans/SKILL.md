---
name: writing-plans
description: Write detailed implementation plans. Break work into small tasks (2-5 minutes each), with precise file paths, complete code, and verification steps. Use before starting implementation.
---

# Writing Plans Skill

Create clear, executable implementation plans.

## Core Principles
- **Atomic Tasks** - Each task takes 2-5 minutes to complete
- **Self-Contained** - Tasks include all necessary information
- **Verifiable** - Each task has clear completion criteria

## Plan Format

### Task Structure
```markdown
## Task [N]: [Brief Description]

### Goal
[What this task accomplishes]

### Changes
- `[file path]`: [specific changes]

### Code
```[language]
[complete code snippet]
```

### Verification
1. [Verification step 1]
2. [Verification step 2]

### Completion Checklist
- [ ] Code modified
- [ ] Tests pass
- [ ] Committed
```

## Splitting Principles

### Good Task Splitting
- ✅ "Add email validation method to User model"
- ✅ "Create user registration API endpoint"
- ✅ "Add unit tests for registration endpoint"

### Bad Task Splitting
- ❌ "Implement user system" (too large)
- ❌ "Fix bug" (too vague)
- ❌ "Refactor code" (no specific goal)

## Dependency Management
1. Identify dependencies between tasks
2. Ensure dependent tasks are ordered first
3. Mark tasks that can be executed in parallel

## Plan Review Checklist
- [ ] Each task has clear completion criteria
- [ ] Task order is logical
- [ ] No missing steps
- [ ] Includes necessary testing tasks
