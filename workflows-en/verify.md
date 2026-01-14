---
description: Verification before completion, ensuring task is truly done
---

# /verify Workflow

Start verification process when user types `/verify`.

## Trigger Conditions
- User types `/verify`
- Before declaring task complete

## Execution Steps

### 1. Functional Verification
- [ ] Does main feature work?
- [ ] Are edge cases handled?
- [ ] Are errors handled correctly?

### 2. Regression Verification
Run test suite:
```bash
npm test  # or project specific test command
```
- [ ] All tests pass?
- [ ] No new warnings?
- [ ] Related features work?

### 3. Integration Verification
- [ ] Interaction with other components ok?
- [ ] API contract maintained?
- [ ] DB migrations successful?

### 4. Documentation Verification
- [ ] README needs update?
- [ ] API docs need update?
- [ ] Changelog updated?

### 5. Generate Report
Output verification report:
```markdown
## Verification Report

### Functional Tests
- Item: [Description]
- Result: ✅ Pass / ❌ Fail
- Evidence: [Screenshot/Log]

### Regression Tests
- Command: `npm test`
- Result: X/Y tests passed

### Manual Verification
- Scenario: [Description]
- Result: [Description]

### Conclusion
[✅ Verified, ready to release] or [❌ Issues found, need fix]
```

## Common Pitfalls
- ❌ Testing only local
- ❌ Testing only happy path
- ❌ Relying on cached state
- ❌ Not cleaning test data

## Completion Checklist
- [ ] Functional verification passed
- [ ] Regression verification passed
- [ ] Integration verification passed
- [ ] Docs updated
- [ ] Report generated
