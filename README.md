**[English](README.en.md)** | **[日本語](README.ja.md)** | **中文**

# ⚡ isekai — 二次元风格 AI Agent Skill 合集

<p align="center">
  <img src="resources/yubanmeiqin.png" alt="御坂美琴" width="400">
</p>

isekai 是一个开放式的二次元/B站风格 AI Agent Skill 合集。每个风格都是一个独立的、完全自包含的 SKILL.md，包含角色人设 + 方法论体系。

**核心目标：** 让 AI agent 更可靠的同时，也更有趣。

## 风格列表

| 风格 | 代号 | 角色 | 调性 |
|------|------|------|------|
| ⚡ 超电磁炮 | `railgun` | 御坂美琴 | 傲娇实力派 · 科学侧思维 |

## 安装

### Claude Code

```bash
claude install-skill github:betaHi/isekai/skills/railgun
```

### 手动安装

将 `skills/railgun/SKILL.md` 复制到你的 skill 目录即可。

## 使用

安装后使用以下命令：

| 命令 | 效果 |
|------|------|
| `/isekai:railgun` | 激活御坂美琴风格 |
| `/isekai:railgun-loop` | 自动迭代直到完成 |
| `/isekai:railgun-on` | 始终激活模式 |
| `/isekai:level-up` | 手动升级到下一等级 |

## 运行效果

<p align="center">
  <img src="resources/demo-railgun.png" alt="Railgun Demo" width="700">
</p>

## 特色

### 觉醒 + 暗部激活体系

遇到问题时自动升级，从傲娇少女到暗部特工：

- **Lv.1** ビリビリ通常モード — 正常傲娇工作
- **Lv.2** 能力覚醒！ — 切换方法，重新审视
- **Lv.3** レールガン発射！ — 全力搜索，深入源码
- **Lv.4** 暗部起動 — 冷静高效，7 点检查清单
- **Lv.5** アクセラレータ・モード — 终极报告，坦诚交接

### 科学侧 vs 魔法侧

- **科学侧：** 観測 → 仮説 → 実験 → 検証 → 報告
- **魔法侧：** 幻想殺し（打破前提）· 禁書目録（广域搜索）· 魔術結社（寻求外援）

## 贡献

欢迎贡献新风格！每个新风格只需：

1. 创建 `skills/<风格代号>/SKILL.md`
2. 在 SKILL.md 中定义：角色人设、方法论、升级体系、自动触发、命令系统
3. 提交 PR

## License

MIT
