# opxy-tutor

A stateful teaching workspace for learning music production with the **Teenage Engineering OP-XY** and the **Roland SP-404MK2**, driven by Claude Code and [Matt Pocock's `teach` skill](https://github.com/mattpocock/skills).

## How to use

Open this repo in Claude Code and run:

```
/teach <what you want to learn>
```

e.g. `/teach how the OP-XY sequencer works` or `/teach resampling with FX on the SP-404`.

The first session should also pin down [MISSION.md](./MISSION.md) — it's currently a draft.

## What's here

| Path | Purpose |
|---|---|
| `.claude/skills/teach/` | The teach skill (from [mattpocock/skills](https://github.com/mattpocock/skills), MIT) |
| `manuals/op-xy-guide.pdf` | Official OP-XY full guide (Teenage Engineering) |
| `manuals/sp-404mk2-reference-manual-v5.50.pdf` | Official SP-404MKII reference manual, firmware v5.50 (Roland) |
| `manuals/sp-404mk2-shortcut-list.pdf` | Official SP-404MK2 shortcut/button-combo list |
| `MISSION.md` | Why you're learning this — grounds every lesson |
| `RESOURCES.md` | Curated high-trust sources (the manuals above + web/community links) |

As you learn, the skill will grow the workspace with `lessons/` (interactive HTML lessons), `reference/` (cheat sheets), `learning-records/` (what you've learned), and `NOTES.md`.
