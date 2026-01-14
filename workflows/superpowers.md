---
description: 查看所有可用的 Superpowers 命令
---

# /superpowers 工作流

当用户输入 `/superpowers` 时，显示所有可用命令。

## 可用命令

### 🧠 规划类
| 命令 | 描述 |
|------|------|
| `/brainstorming` | 头脑风暴，需求澄清和方案设计 |
| `/writing-plans` | 编写详细的实施计划 |

### 🧪 测试类
| 命令 | 描述 |
|------|------|
| `/tdd` | 测试驱动开发 RED-GREEN-REFACTOR |

### 🔍 调试类
| 命令 | 描述 |
|------|------|
| `/debug` | 系统性 4 阶段调试流程 |
| `/verify` | 完成前的全面验证 |

### 👀 协作类
| 命令 | 描述 |
|------|------|
| `/review` | 代码审查检查清单 |

### 📋 组合流程
| 命令 | 描述 |
|------|------|
| `/dev` | 完整开发流程 (规划→实施→验证) |
| `/bugfix` | Bug 修复流程 (调试→修复→验证) |

## 推荐工作流

```
/brainstorming  → 需求澄清
      ↓
/writing-plans  → 编写计划
      ↓
/tdd            → 测试驱动开发
      ↓
/review         → 代码审查
      ↓
/verify         → 最终验证
```

## 更多信息
- 查看技能详情: `.agent/skills/`
- 查看工作流详情: `.agent/workflows/`
- GitHub: https://github.com/yywmrz/antigravity-superpowers
