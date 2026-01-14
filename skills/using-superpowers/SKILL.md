---
name: using-superpowers
description: Superpowers 技能系统介绍。了解如何使用这套开发工作流技能。用于初次接触 superpowers 或需要了解整体流程时。
---

# 使用 Superpowers 技能

Superpowers 是一套完整的软件开发工作流，由一系列可组合的技能构成。

## 技能列表

### 🧠 规划类
- **brainstorming** - 头脑风暴，需求澄清和方案设计
- **writing-plans** - 编写详细的实施计划

### 🧪 测试类
- **test-driven-development** - RED-GREEN-REFACTOR 测试驱动开发

### 🔍 调试类
- **systematic-debugging** - 系统性4阶段调试流程
- **verification-before-completion** - 完成前的全面验证

### 👀 协作类
- **code-review** - 代码审查检查清单

### 📝 元技能
- **writing-skills** - 如何创建新技能
- **using-superpowers** - 本技能，系统介绍

## 基本工作流

```
1. brainstorming
   ↓ 需求明确
2. writing-plans
   ↓ 计划批准
3. test-driven-development
   ↓ 编写代码
4. code-review
   ↓ 审查通过
5. verification-before-completion
   ↓ 验证完成
```

## 技能触发机制

Agent 通过 **Progressive Disclosure** 机制使用技能：

1. **发现**: 扫描所有技能的名称和描述
2. **激活**: 任务匹配描述时，加载完整 SKILL.md
3. **应用**: 将技能指令融入推理过程

## 安装位置

- **项目级别**: `.agent/skills/`
- **全局级别**: `~/.gemini/antigravity/skills/`

## 最佳实践
- 让 Agent 自动选择合适的技能
- 不需要手动调用，技能会根据上下文自动触发
- 如果技能没有触发，检查描述是否足够清晰
