---
name: systematic-debugging
description: Systematic debugging. Use a 4-phase root cause analysis process - collect evidence, form hypotheses, verify hypotheses, fix and verify. Use when troubleshooting bugs or abnormal behavior.
---

# Systematic Debugging Skill

Follow a structured debugging process, avoid blind guessing.

## Core Principles
- **Evidence First** - Based on logs and data, not intuition
- **One Variable at a Time** - Change only one thing at a time
- **Document the Process** - Record attempted solutions

## 4-Phase Debugging Process

### Phase 1: Collect Evidence
1. Reproduce the problem, record exact steps
2. Collect relevant logs and error messages
3. Determine when the problem first appeared
4. Check recent code changes

Output Checklist:
- [ ] Full error message
- [ ] Stack trace
- [ ] Relevant log snippets
- [ ] Recent changes list

### Phase 2: Form Hypotheses
Propose possible causes based on evidence:
1. List all possible causes (at least 3)
2. Rank by likelihood
3. Design verification method for each hypothesis

Hypothesis Template:
```
Hypothesis: [Cause description]
Evidence: [Evidence supporting this hypothesis]
Verification: [How to confirm or rule out]
```

### Phase 3: Verify Hypotheses
Start with the most likely hypothesis:
1. Execute verification steps
2. Record results
3. Confirm or rule out hypothesis
4. If ruled out, continue to next hypothesis

### Phase 4: Fix and Verify
1. Implement the fix
2. Verify original problem is resolved
3. Confirm no new issues introduced
4. Add protective tests

## Debugging Techniques

### Binary Search
- Set breakpoint in the middle of the code path
- Determine if problem is in first or second half
- Repeat until locating the specific line

### Add Defensive Logging
```python
logger.debug(f"Function called with: {args}")
logger.debug(f"State before: {state}")
# ... code ...
logger.debug(f"State after: {state}")
```
