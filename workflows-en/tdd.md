---
description: Start Test-Driven Development flow, following RED-GREEN-REFACTOR cycle
---

# /tdd Workflow

Start TDD flow when user types `/tdd`.

## Trigger Conditions
- User types `/tdd`
- When writing new features or fixing bugs

## Execution Steps

### 1. Define Goal
Ask user:
- "What feature to implement?"
- "What is the expected behavior?"
- "What are the edge cases?"

### 2. RED Phase
Write a failing test:
```
1. Define behavior to test
2. Write test code
3. Run test, confirm failure
4. Confirm failure is due to missing feature
```

### 3. GREEN Phase
Write minimal code to pass:
```
1. Write simplest implementation
2. Do not over-engineer
3. Run test, confirm pass
4. Commit immediately
```

### 4. REFACTOR Phase
Refactor code:
```
1. Check usage of duplicates
2. Improve naming
3. Simplify structure
4. Run tests to ensure no regression
5. Commit refactoring
```

### 5. Cycle
Repeat RED-GREEN-REFACTOR until feature complete.

## Anti-Pattern Warnings
- ❌ Writing code before tests
- ❌ Writing too many tests at once
- ❌ Refactoring before tests pass
- ❌ Skipping failure verification

## Completion Checklist
- [ ] Test written
- [ ] Test failed initially
- [ ] Code implemented
- [ ] Test passes now
- [ ] Code refactored
