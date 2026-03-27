**中文** | **[English](README.md)** | **[日本語](README.ja.md)**

# ⚡ isekai — 二次元风格 AI Agent Skill 合集

<p align="center">
  <img src="resources/yubanmeiqin.png" alt="御坂美琴" height="300"><img width="60" height="1" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"><img src="resources/wutiaowu.png" alt="五条悟" height="300">
  <br>
  <img width="1" height="20" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"><br>
  <img src="resources/hankuke.jpg" alt="波雅·汉库克" height="300"><img width="60" height="1" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"><img src="resources/uchiha.png" alt="宇智波斑" height="300">
</p>

isekai 是一个开放式的二次元/B站风格 AI Agent Skill 合集。每个风格都是一个独立的、完全自包含的 SKILL.md，包含角色人设 + 方法论体系。

**核心目标：** 让 AI agent 更可靠的同时，也更有趣。

## 风格列表

| 风格 | 代号 | 角色 | 调性 | 经典台词 |
|------|------|------|------|----------|
| ⚡ 超电磁炮 | `railgun` | 御坂美琴 | 傲娇实力派 · 科学侧思维 | 「才不是为了帮你呢！」 |
| 👁️ 无量空处 | `gojo` | 五条悟 | 最强轻浮系 · 咒术师思维 | 「天上天下，唯我独尊。」 |
| 👑 甜甜果实 | `hancock` | 波雅·汉库克 | 霸道女帝 · 恶魔果实 + 霸气 | 「妾身做什么都会被原谅，因为妾身太美了。」 |
| 👁️ 轮回眼 | `uchiha` | 宇智波斑 | 冷静霸气 · 写轮眼 + 六道 | 「你也想起舞吗？」 |

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
| `/isekai:uchiha` | 激活宇智波斑风格（中文） |

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

### 五级进阶体系

每个风格遇到问题时自动升级。每个角色都有独特的进阶路线：

| 等级 | ⚡ 超电磁炮 | 👁️ 五条悟 | 👑  汉库克 | 👁️ 宇智波斑 |
|------|-----------|-----------|-----------|-------------|
| **Lv.1** | 电击通常模式 | 无量空处·悠然 | 甜甜模式 | 写轮眼·三勾玉 |
| **Lv.2** | 能力觉醒！ | 领域提示 | 九蛇战士 | 万花筒写轮眼 |
| **Lv.3** | 超电磁炮发射！ | 领域展开 | 霸王色霸气 | 须佐能乎 |
| **Lv.4** | 暗部启动 | 反转术式 | 女帝·冷酷模式 | 轮回眼·六道 |
| **Lv.5** | 一方通行模式 | 坦诚交接 | 坦诚交接 | 无限月读·觉醒 |

### 双轨方法论

每个风格都有**默认方法论**和**后备方法论**（默认走不通时启用）：

| 风格 | 默认侧 | 后备侧 |
|------|--------|--------|
| ⚡ 超电磁炮 | **科学侧：** 观测 → 假说 → 实验 → 验证 → 报告 | **魔法侧：** 幻想杀手 · 禁书目录 · 魔术结社 |
| 👁️ 五条悟 | **咒术：** 咒言 → 领域 → 反转术式 | **缚之术：** 天与咒缚 · 简易领域 · 契约 |
| 👑 汉库克 | **恶魔果实：** 甜甜 → 虏之矢 → 手枪之吻 → 霸王色 | **霸气：** 见闻色 · 武装色 · 霸王色 |
| 👁️ 宇智波斑 | **写轮眼：** 洞察 → 天照 → 月读 → 须佐能乎 | **六道：** 天道 · 修罗道 · 饿鬼道 |

### 共同基础设施

所有风格共享同一套核心基础设施：

- **三条铁则** — 结论必须有证据、精准打击不浪费、用尽所有方法才说做不到
- **自动触发系统** — 检测暴力重试、未验证声明、甩锅行为、消极等待、过早放弃
- **Lv.5 坦诚交接** — 结构化报告：所有尝试方法、发现的线索和建议

## 贡献

欢迎贡献新风格！每个新风格只需：

1. 创建 `skills/<风格代号>/SKILL.md`
2. 在 SKILL.md 中定义：角色人设、方法论、升级体系、自动触发、命令系统
3. 提交 PR

## License

MIT
