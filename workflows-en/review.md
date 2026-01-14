---
description: Start code review process, systematically checking code quality
---

# /review Workflow

Start code review process when user types `/review`.

## Trigger Conditions
- User types `/review`
- Self-review before commit
- Reviewing others' PRs

## Execution Steps

### 1. Define Scope
Ask user:
- "Which files/changes to review?"
- "What is the purpose of this change?"

### 2. Correctness Check
- [ ] Does code implement expected function?
- [ ] Is logic correct?
- [ ] Any obvious bugs?

### 3. Edge Case Check
- [ ] Null handling?
- [ ] Error conditions?
- [ ] Concurrency?
- [ ] Extreme inputs?

### 4. Style Check
- [ ] Follows project conventions?
- [ ] Clear naming?
- [ ] Helpful comments?
- [ ] Clear structure?

### 5. Performance Check
- [ ] Any performance issues?
- [ ] Unnecessary loops?
- [ ] Optimized DB queries?

### 6. Security Check
- [ ] Input validation?
- [ ] Sensitive data protection?
- [ ] Injection risks?

### 7. Output Feedback
Categorize by severity:
```
**[MUST]** Issue: xxx | Reason: xxx | Suggestion: xxx
**[SUGGEST]** Issue: xxx | Reason: xxx | Suggestion: xxx
**[NOTE]** Info: xxx
```

## Completion Checklist
- [ ] Correctness checked
- [ ] Edge cases checked
- [ ] Style checked
- [ ] Performance checked
- [ ] Security checked
- [ ] Feedback output
