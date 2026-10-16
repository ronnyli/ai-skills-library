# AI Skills Library

A collection of AI skills I've found useful, packaged in a portable `SKILL.md`
format. Each skill is a self-contained prompt that can be loaded by an AI agent
to gain a specific capability.

## Skills

| Skill | Description |
| --- | --- |
| [ambitious-advisor](skills/ambitious-advisor/SKILL.md) | Raises the ambition of a goal or project across five dimensions (speed, altitude, depth, range, self-belief) whenever someone asks for feedback on what they're building. |
| [design-critic](skills/design-critic/SKILL.md) | Reviews the aesthetics of any visual media (landing pages, videos, etc.) with the taste of a world-class design critic and returns actionable, studio-level feedback plus a score out of 10. |

## Structure

```
skills/
└── <skill-name>/
    └── SKILL.md
```

Each `SKILL.md` starts with YAML frontmatter:

```yaml
---
name: skill-name
description: When and why to use this skill.
---
```

The body contains the instructions the agent should follow.

## Usage

Copy the skill directory into your agent's skills folder, or point your tooling
at the `skills/` directory directly. Skills are plain markdown and are not tied
to any single framework.

## License

[MIT](LICENSE)
