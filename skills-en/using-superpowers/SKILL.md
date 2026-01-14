---
name: using-superpowers
description: Introduction to the Superpowers skills system. Learn how to use this set of development workflow skills. Use when first encountering superpowers or needing to understand the overall process.
---

# Using Superpowers Skill

Superpowers is a complete software development workflow built on composable skills.

## Skills List

### 🧠 Planning
- **brainstorming** - Brainstorming, requirements clarification, solution design
- **writing-plans** - Write detailed implementation plans

### 🧪 Testing
- **test-driven-development** - RED-GREEN-REFACTOR test-driven development

### 🔍 Debugging
- **systematic-debugging** - Systematic 4-phase debugging
- **verification-before-completion** - Thorough verification before completion

### 👀 Collaboration
- **code-review** - Code review checklist

### 📝 Meta Skills
- **writing-skills** - How to create new skills
- **using-superpowers** - This skill, system introduction

## Basic Workflow

```
1. brainstorming
   ↓ Requirements clear
2. writing-plans
   ↓ Plan approved
3. test-driven-development
   ↓ Code written
4. code-review
   ↓ Review passed
5. verification-before-completion
   ↓ Verification complete
```

## Skill Trigger Mechanism

Agent uses skills through **Progressive Disclosure**:

1. **Discovery**: Scans all skill names and descriptions
2. **Activation**: When task matches description, loads full SKILL.md
3. **Application**: Incorporates skill instructions into reasoning process

## Installation Locations

- **Project Level**: `.agent/skills/`
- **Global Level**: `~/.gemini/antigravity/skills/`

## Best Practices
- Let Agent automatically choose appropriate skills
- No manual invocation needed, skills trigger automatically based on context
- If skill doesn't trigger, check if description is clear enough
