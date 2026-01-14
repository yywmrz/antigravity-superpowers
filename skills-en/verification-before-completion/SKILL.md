---
name: verification-before-completion
description: Verification before completion. Ensure the problem is truly fixed, not just superficially passing. Use before declaring a task complete.
---

# Verification Before Completion Skill

Perform thorough verification before declaring a task complete.

## Core Principles
- **Evidence Over Claims** - Show verification results, don't just say "done"
- **Multi-Angle Verification** - Don't just run one test
- **Boundary Testing** - Passing normal cases doesn't mean complete

## Verification Checklist

### 1. Functional Verification
- [ ] Does the main functionality work?
- [ ] Are boundary cases handled?
- [ ] Are error conditions handled correctly?

### 2. Regression Verification
- [ ] Do all existing tests pass?
- [ ] Are related features affected?
- [ ] Are there new warnings or errors?

### 3. Integration Verification
- [ ] Are interactions with other components normal?
- [ ] Is the API contract maintained?
- [ ] Did database migrations succeed?

### 4. Documentation Verification
- [ ] Does README need updating?
- [ ] Does API documentation need updating?
- [ ] Is the changelog updated?

## Verification Report Template

```markdown
## Verification Report

### Functional Tests
- Test: [Description]
- Result: [Pass/Fail]
- Evidence: [Screenshot/Log]

### Regression Tests
- Command: `npm test`
- Result: [X/Y tests passed]

### Manual Verification
- Scenario: [Description]
- Steps: [1, 2, 3...]
- Result: [Description]
```

## Common Pitfalls
- ❌ Only testing in local environment
- ❌ Only testing normal cases
- ❌ Relying on cached old state
- ❌ Not cleaning up test data
