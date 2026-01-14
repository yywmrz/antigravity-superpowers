---
name: test-driven-development
description: Test-driven development. Follow the RED-GREEN-REFACTOR cycle - write failing tests first, then write minimal code to pass, then refactor. Use when writing new features or fixing bugs.
---

# Test-Driven Development Skill

Strictly follow the TDD RED-GREEN-REFACTOR cycle.

## Core Principles
1. **Always Write Tests First** - No production code without a failing test
2. **Minimal Implementation** - Only write code to make the test pass
3. **Continuous Refactoring** - Refactor immediately after tests pass

## Workflow

### RED Phase (Failing Test)
1. Define the behavior to implement
2. Write a test describing that behavior
3. Run the test, confirm it fails
4. Confirm failure is due to missing functionality, not test errors

### GREEN Phase (Passing Test)
1. Write the simplest code to make the test pass
2. Don't over-engineer
3. Run the test, confirm it passes
4. Commit immediately

### REFACTOR Phase
1. Check for code duplication
2. Check naming clarity
3. Check single responsibility
4. Run tests to confirm nothing broke
5. Commit refactoring

## Anti-Pattern Warnings
Avoid these behaviors:
- ❌ Writing code before tests
- ❌ Writing too many tests at once
- ❌ Refactoring before tests pass
- ❌ Skipping the failing test verification step

## Test Naming Convention
```
test_[feature]_[scenario]_[expected_result]
```

Examples:
- `test_login_with_valid_credentials_returns_token`
- `test_login_with_invalid_password_returns_401`
