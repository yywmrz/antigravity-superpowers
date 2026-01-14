---
name: code-review
description: Code review skill. Check code for correctness, edge cases, code style, and performance issues. Use when reviewing PRs or checking code quality.
---

# Code Review Skill

Perform systematic code reviews.

## Review Checklist

### 1. Correctness
- [ ] Does the code implement the expected functionality?
- [ ] Is the logic correct?
- [ ] Are there obvious bugs?

### 2. Edge Cases
- [ ] Is null handling correct?
- [ ] Are error conditions handled?
- [ ] Are concurrency cases considered?
- [ ] Are extreme inputs handled?

### 3. Code Style
- [ ] Does it follow project conventions?
- [ ] Is naming clear?
- [ ] Are comments necessary and helpful?
- [ ] Is code structure clear?

### 4. Performance
- [ ] Are there obvious performance issues?
- [ ] Are there unnecessary loops or computations?
- [ ] Are database queries optimized?
- [ ] Is there memory leak risk?

### 5. Security
- [ ] Is input validated?
- [ ] Is sensitive data protected?
- [ ] Is there injection risk?

## Feedback Principles

### Do
- ✅ Specifically state what needs to change
- ✅ Explain why it needs to change
- ✅ Provide alternatives
- ✅ Distinguish must-fix from suggestions

### Don't
- ❌ Just say "there's a problem here"
- ❌ Use vague descriptions
- ❌ Treat personal style preferences as issues

## Feedback Template
```
**[Severity: Must/Suggest/Note]**

Issue: [Specific description]
Reason: [Why this is a problem]
Suggestion: [How to fix]
```

## Severity Definitions
- **Must**: Will cause bugs, security issues, or breaking changes
- **Suggest**: Can improve but not required
- **Note**: For reference only
