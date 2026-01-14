# Antigravity Superpowers

> 🚀 为 Google Antigravity 打造的完整软件开发工作流技能库

Superpowers 是一套完整的软件开发工作流，由一系列可组合的 "Skills" 和 "Workflows" 构成，让你的 Antigravity Agent 拥有超能力。

## ✨ 特性

- **结构化工作流** - 从需求澄清到代码验证的完整流程
- **即插即用** - 复制到项目即可使用
- **可扩展** - 轻松添加自定义技能
- **最佳实践** - 内置 TDD、代码审查等工程最佳实践

## 📦 安装

将本仓库克隆到你的项目中：

```bash
# 方式1：作为子目录
git clone https://github.com/yywmrz/antigravity-superpowers.git .agent

# 方式2：只复制需要的文件
cp -r antigravity-superpowers/skills .agent/skills
cp -r antigravity-superpowers/workflows .agent/workflows
```

或者手动复制 `skills/` 和 `workflows/` 目录到你项目的 `.agent/` 目录下。

## 🔧 工作原理

启动 Antigravity Agent 后，它会自动：

1. **发现** - 扫描 `.agent/skills/` 和 `.agent/workflows/` 目录
2. **匹配** - 根据任务上下文选择合适的技能
3. **激活** - 加载并遵循技能指令

## 📋 推荐工作流

```
1. brainstorming        → 需求澄清，方案设计
       ↓
2. writing-plans        → 编写详细实施计划
       ↓
3. test-driven-development → RED-GREEN-REFACTOR
       ↓
4. code-review          → 代码审查
       ↓
5. verification         → 完成前验证
```

## 📚 技能库

### 🧠 规划类
| 技能 | 描述 |
|------|------|
| `brainstorming` | 在编写代码前进行头脑风暴，通过提问精炼想法 |
| `writing-plans` | 编写详细的实施计划，每个任务 2-5 分钟 |

### 🧪 测试类
| 技能 | 描述 |
|------|------|
| `test-driven-development` | RED-GREEN-REFACTOR 测试驱动开发循环 |

### 🔍 调试类
| 技能 | 描述 |
|------|------|
| `systematic-debugging` | 4 阶段系统性根因分析流程 |
| `verification-before-completion` | 完成前的全面验证检查 |

### 👀 协作类
| 技能 | 描述 |
|------|------|
| `code-review` | 代码审查检查清单和反馈规范 |

### 📝 元技能
| 技能 | 描述 |
|------|------|
| `writing-skills` | 如何创建新技能的指南 |
| `using-superpowers` | Superpowers 系统介绍 |

## 🔄 Workflows

Workflows 定义了标准化的操作流程：

| Workflow | 描述 |
|----------|------|
| `dev-workflow` | 完整的开发流程：规划 → 实施 → 验证 |
| `bugfix-workflow` | Bug 修复流程：调试 → 修复 → 验证 |
| `review-workflow` | 代码审查流程 |

## 🎯 设计理念

- **测试驱动开发** - 先写测试，再写代码
- **系统优于随机** - 结构化流程优于临时猜测
- **降低复杂度** - 简单是首要目标
- **证据优于声明** - 验证后再宣布完成

## 🤝 贡献

欢迎提交 PR！请参考 `skills/writing-skills/SKILL.md` 了解如何创建新技能。

## 📄 License

MIT License

## 🔗 相关链接

- [Antigravity Skills 官方文档](https://antigravity.google/docs/skills)
- [原版 Claude Code Superpowers](https://github.com/obra/superpowers)
- [教程网站](https://yywmrz.github.io/agent-skill)
