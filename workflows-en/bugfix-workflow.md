---
description: Bug fix workflow - systematic debugging and fix verification
---

# Bug Fix Workflow

## Use Cases
- User reported a bug
- Discovered abnormal code behavior
- Need to troubleshoot and fix issues

## Process

// turbo-all

### 1. Problem Collection
Collect problem-related information:
- Reproduction steps
- Error messages
- Expected vs actual behavior
- When it first appeared

### 2. Systematic Debugging
Use `systematic-debugging` skill:

#### Phase 1: Collect Evidence
- Reproduce the problem
- Collect logs
- Check recent changes

#### Phase 2: Form Hypotheses
- List possible causes
- Rank by likelihood
- Design verification method

#### Phase 3: Verify Hypotheses
- Execute verification
- Record results
- Confirm or rule out

#### Phase 4: Locate Problem
- Determine root cause
- Document findings

### 3. Test-Driven Fix
Use `test-driven-development` skill:
- First write a test that reproduces the bug
- Confirm test fails
- Fix the code
- Confirm test passes

### 4. Verify Fix
Use `verification-before-completion` skill:
- Confirm original problem is resolved
- Confirm no new issues introduced
- Confirm related features work

### 5. Add Protection
- Add regression prevention tests
- Update related documentation
- Commit changes

## Checkpoints
- [ ] Problem reproduced
- [ ] Root cause located
- [ ] Regression test added
- [ ] Fix verified
- [ ] Changes committed
