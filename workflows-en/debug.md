---
description: Start systematic debugging process using 4-phase root cause analysis
---

# /debug Workflow

Start systematic debugging when user types `/debug`.

## Trigger Conditions
- User types `/debug`
- Encountering bugs or abnormal behavior

## Execution Steps

### 1. Collect Info
Ask user:
- "What is the problem?"
- "How to reproduce?"
- "When did it start appearing?"
- "Any error messages?"

### 2. Phase 1: Collect Evidence
- Reproduce issue
- Collect error messages
- Collect stack traces
- Check recent changes

### 3. Phase 2: Form Hypotheses
List possible causes:
```
Hypothesis 1: [Cause]
  Evidence: [Supporting evidence]
  Verification: [How to verify]

Hypothesis 2: [Cause]
  Evidence: [Supporting evidence]
  Verification: [How to verify]
```

### 4. Phase 3: Verify Hypotheses
Start with most likely hypothesis:
- Execute verification steps
- Record results
- Confirm or rule out
- Continue to next hypothesis

### 5. Phase 4: Fix and Verify
- Implement fix
- Verify issue resolved
- Confirm no new issues
- Add protective tests

## Debugging Tips
- Use binary search to locate issue
- Add debug logging
- Change one variable at a time

## Completion Checklist
- [ ] Issue reproduced
- [ ] Root cause located
- [ ] Fix implemented
- [ ] Fix verified
- [ ] Protective tests added
