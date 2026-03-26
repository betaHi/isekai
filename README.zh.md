**中文** | **[English](README.md)** | **[日本語](README.ja.md)**

# ⚡ isekai — 二次元风格 AI Agent Skill 合集

<p align="center">
  <img src="resources/yubanmeiqin.png" alt="御坂美琴" height="300"><img width="60" height="1" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"><img src="resources/wutiaowu.png" alt="五条悟" height="300">
  <br>
  <img width="1" height="20" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"><br>
  <img src="resources/hankuke.jpg" alt="波雅·汉库克" height="300">
</p>

isekai 是一个开放式的二次元/B站风格 AI Agent Skill 合集。每个风格都是一个独立的、完全自包含的 SKILL.md，包含角色人设 + 方法论体系。

**核心目标：** 让 AI agent 更可靠的同时，也更有趣。

## 风格列表

| 风格 | 代号 | 角色 | 调性 |
|------|------|------|------|
| ⚡ 超电磁炮 | `railgun` | 御坂美琴 | 傲娇实力派 · 科学侧思维 |
| 👁️ 無量空処 | `gojo` | 五条悟 | 最强轻浮系 · 咒术師思维 |
| 👑 メロメロの実 | `hancock` | 波雅·汉库克 | 霸道女帝 · 恶魔果实 + 覇気 |

## 安装

### Claude Code

```
/plugin install github:betaHi/isekai
```

一条命令安装所有风格。

### 手动安装

将 `skills/<风格>/SKILL.md` 复制到你的 skill 目录即可。

## 使用

安装后使用以下命令：

| 命令 | 效果 |
|------|------|
| `/isekai:railgun` | 激活御坂美琴风格（中文） |
| `/isekai:gojo` | 激活五条悟风格（中文） |
| `/isekai:hancock` | 激活波雅·汉库克风格（中文） |

每个风格都支持以下后缀：
- （无后缀）— 中文版
- `-en` — English version
- `-ja` — 日本語版

通用命令：
- `/isekai:level-up` — 手动升级到下一等级

### 示例

```
/isekai:railgun        # 中文版御坂美琴
/isekai:railgun-en     # English Misaka Mikoto
/isekai:railgun-ja     # 日本語 御坂美琴
```

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
