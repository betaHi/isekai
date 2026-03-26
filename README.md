**[中文](README.zh.md)** | **English** | **[日本語](README.ja.md)**

# ⚡ isekai — Anime-Style AI Agent Skill Collection

<p align="center">
  <img src="resources/yubanmeiqin.png" alt="Misaka Mikoto" height="300"><img width="60" height="1" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"><img src="resources/wutiaowu.png" alt="Gojo Satoru" height="300">
  <br>
  <img width="1" height="20" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"><br>
  <img src="resources/hankuke.jpg" alt="Boa Hancock" height="300"><img width="60" height="1" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"><img src="resources/uchiha.png" alt="Uchiha Madara" height="300">
</p>

isekai is an open, extensible collection of anime / Bilibili-style AI Agent Skills. Each style is a standalone, self-contained SKILL.md with its own character persona + methodology system.

**Core goal:** Make AI agents more reliable *and* more fun.

## Style List

| Style | Code | Character | Tone |
|-------|------|-----------|------|
| ⚡ Railgun | `railgun` | Misaka Mikoto | Tsundere powerhouse · Science-side thinking |
| 👁️ Unlimited Void | `gojo` | Gojo Satoru | Overpowered & carefree · Jujutsu sorcerer |
| 👑 Mero Mero no Mi | `hancock` | Boa Hancock | Domineering empress · Devil Fruit + Haki |
| 👁️ Rinnegan | `uchiha` | Uchiha Madara | Composed dominance · Sharingan + Six Paths |

## Installation

### Claude Code

```
/plugin install github:betaHi/isekai
```

One command installs all styles.

### Manual

Copy `skills/<style>/SKILL.md` to your skill directory.

## Usage

After installation, use the following commands:

| Command | Effect |
|---------|--------|
| `/isekai:railgun-en` | Activate Misaka Mikoto style (English) |
| `/isekai:gojo-en` | Activate Gojo Satoru style (English) |
| `/isekai:hancock-en` | Activate Boa Hancock style (English) |
| `/isekai:uchiha-en` | Activate Uchiha Madara style (English) |

Each style supports these suffixes:
- (no suffix) — 中文版
- `-en` — English version
- `-ja` — 日本語版

General command:
- `/isekai:level-up` — Manually escalate to the next level

### Example

```
/isekai:railgun-en     # English Misaka Mikoto
/isekai:railgun        # 中文版御坂美琴
/isekai:railgun-ja     # 日本語 御坂美琴
```

## Demo

<p align="center">
  <img src="resources/demo-railgun.png" alt="Railgun Demo" width="700">
</p>

## Features

### Awakening + Dark-Side Escalation

Auto-escalates when hitting obstacles — from tsundere girl to cold-blooded operative:

- **Lv.1** ビリビリ Normal Mode — Tsundere, business as usual
- **Lv.2** Ability Awakening! — Switch approach, re-examine assumptions
- **Lv.3** Railgun Fire! — Full search, dive into source code
- **Lv.4** Dark-Side Activated — Calm & efficient, 7-point checklist
- **Lv.5** Accelerator Mode — Final report, honest handoff

### Science-Side vs Magic-Side

- **Science-Side:** Observe → Hypothesize → Experiment → Verify → Report
- **Magic-Side:** Imagine Breaker (challenge assumptions) · Index (broad search) · Cabal (seek external help)

## Contributing

New styles are welcome! To add one:

1. Create `skills/<style-code>/SKILL.md`
2. Define: character persona, methodology, escalation system, auto-triggers, command system
3. Open a PR

## License

MIT
