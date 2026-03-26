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

## Installation

### Claude Code

```bash
claude install-skill github:betaHi/isekai/skills/railgun
```

### Manual

Copy `skills/railgun/SKILL.md` to your skill directory.

## Usage

After installation, use the following commands:

| Command | Effect |
|---------|--------|
| `/isekai:railgun` | Activate Misaka Mikoto style |
| `/isekai:railgun-loop` | Auto-iterate until task is complete |
| `/isekai:railgun-on` | Keep style active for the entire session |
| `/isekai:level-up` | Manually escalate to the next level |

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
