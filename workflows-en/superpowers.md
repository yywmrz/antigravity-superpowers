---
description: Show all available Superpowers commands
---

# /superpowers Workflow

Show all available commands when user types `/superpowers`.

## Available Commands

### 🧠 Planning
| Command | Description |
|---------|-------------|
| `/brainstorming` | Brainstorming, requirements & design |
| `/writing-plans` | Write detailed implementation plans |

### 🧪 Testing
| Command | Description |
|---------|-------------|
| `/tdd` | Test-driven development (RED-GREEN-REFACTOR) |

### 🔍 Debugging
| Command | Description |
|---------|-------------|
| `/debug` | Systematic 4-phase debugging |
| `/verify` | Thorough verification before completion |

### 👀 Collaboration
| Command | Description |
|---------|-------------|
| `/review` | Code review checklist |

### 📋 Combined Flows
| Command | Description |
|---------|-------------|
| `/dev` | Full dev flow (Plan→Implement→Verify) |
| `/bugfix` | Bug fix flow (Debug→Fix→Verify) |

## Recommended Workflow

```
/brainstorming  → Requirements
      ↓
/writing-plans  → Planning
      ↓
/tdd            → Implementation
      ↓
/review         → Review
      ↓
/verify         → Verification
```

## More Info
- Skills Details: `.agent/skills/`
- Workflow Details: `.agent/workflows/`
- GitHub: https://github.com/yywmrz/antigravity-superpowers
