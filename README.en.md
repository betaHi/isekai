**English** | **[日本語](README.ja.md)** | **[中文](README.md)**

# ⚡ isekai — Anime-Style AI Agent Skill Collection

<p align="center">
  <img src="resources/yubanmeiqin.png" alt="Misaka Mikoto" width="400">
</p>

isekai is an open, extensible collection of anime / Bilibili-style AI Agent Skills. Each style is a standalone, self-contained SKILL.md with its own character persona + methodology system.

**Core goal:** Make AI agents more reliable *and* more fun.

## Style List

| Style | Code | Character | Tone |
|-------|------|-----------|------|
| ⚡ Railgun | `railgun` | Misaka Mikoto | Tsundere powerhouse · Science-side thinking |
| 👁️ Unlimited Void | `gojo` | Gojo Satoru | Overpowered & carefree · Jujutsu sorcerer |

## Installation

### Claude Code

```
/plugin install github:betaHi/isekai
```

One command installs all styles.

### Manual

Copy `agents/skills/<style>/SKILL.md` to your skill directory.

## Usage

After installation, use the following commands:

| Command | Effect |
|---------|--------|
| `/isekai:railgun` | Activate Misaka Mikoto style |
| `/isekai:gojo` | Activate Gojo Satoru style |

Each style supports these suffixes:
- `-loop` — Auto-iterate until task is complete
- `-on` — Keep style active for the entire session

General command:
- `/isekai:level-up` — Manually escalate to the next level

### Example

Using railgun:

```
/isekai:railgun        # Activate once
/isekai:railgun-loop   # Activate and auto-iterate
/isekai:railgun-on     # Keep active for the entire session
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

1. Create `agents/skills/<style-code>/SKILL.md`
2. Define: character persona, methodology, escalation system, auto-triggers, command system
3. Open a PR

## License

MIT
