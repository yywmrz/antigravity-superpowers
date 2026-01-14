---
description: Code review workflow - systematic review of code changes
---

# Code Review Workflow

## Use Cases
- Reviewing someone's PR submission
- Pre-commit self-review
- Code quality check

## Process

### 1. Understand Context
- Read PR description
- Understand the purpose of changes
- Check related issues

### 2. High-Level Review
- Do changes align with design?
- Is there a simpler approach?
- Does it follow project architecture?

### 3. Detailed Review
Use `code-review` skill to check:

#### Correctness
- Is the logic correct?
- Does it implement expected functionality?

#### Edge Cases
- Null handling
- Error handling
- Concurrency cases
- Extreme inputs

#### Code Style
- Clear naming
- Reasonable structure
- Appropriate comments

#### Performance
- No obvious performance issues
- Optimized queries
- No memory leaks

#### Security
- Input validation
- Sensitive data protection
- No injection risks

### 4. Provide Feedback
Provide feedback using template:
```
**[Severity: Must/Suggest/Note]**

Issue: [Specific description]
Reason: [Why this is a problem]
Suggestion: [How to fix]
```

### 5. Follow Up
- Ensure author understands feedback
- Verify fixes are correct
- Approve or request more changes

## Review Checklist
- [ ] Change purpose is clear
- [ ] Code logic is correct
- [ ] Edge cases handled
- [ ] Test coverage adequate
- [ ] No security issues
- [ ] Documentation updated
