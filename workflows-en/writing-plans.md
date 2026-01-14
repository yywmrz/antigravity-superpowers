---
description: Create detailed implementation plan, breaking work into 2-5 minute tasks
---

# /writing-plans Workflow

Start writing implementation plans when user types `/writing-plans`.

## Trigger Conditions
- User types `/writing-plans`
- After design solution is confirmed

## Execution Steps

### 1. Confirm Design
Check for approved design document:
- If exists, create plan based on it
- If not, run `/brainstorming` first

### 2. Task Splitting
Split work into atomic tasks:
- Each task completes in 2-5 minutes
- Each task includes precise file paths
- Each task includes complete code snippets
- Each task includes verification steps

### 3. Order Dependencies
- Identify dependencies between tasks
- Ensure dependent tasks come first
- Mark tasks that can run in parallel

### 4. Output Plan
Generate implementation plan, format for each task:
```markdown
## Task [N]: [Brief Description]

### Goal
[Task Goal]

### Changes
- `[file path]`: [specific changes]

### Code
```[language]
[complete code]
```

### Verification
1. [Verification step]

### Completion Checklist
- [ ] Code modified
- [ ] Tests pass
```

### 5. Request Approval
Present plan to user, wait for approval before execution.

## Completion Checklist
- [ ] Tasks split
- [ ] Dependencies ordered
- [ ] Plan output generated
- [ ] User approved
