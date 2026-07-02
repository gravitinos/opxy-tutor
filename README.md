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
| `manuals/op-xy-guide.md` | Text version of the OP-XY guide (converted from the official web guide — the PDF's text is vector outlines) |
| `manuals/sp-404mk2-reference-manual-v5.50.pdf` | Official SP-404MKII reference manual, firmware v5.50 (Roland) |
| `manuals/sp-404mk2-reference-manual-v5.50.md` | Text extraction of the reference manual, with `<!-- PDF page N -->` markers |
| `manuals/sp-404mk2-shortcut-list.pdf` | Official SP-404MK2 shortcut/button-combo list |
| `manuals/sp-404mk2-shortcut-list.md` | Text extraction of the shortcut list |

The `.md` versions are for searching and reading; the PDFs remain the source of truth for anything visual (diagrams, panel layouts, signal-flow charts).
| `MISSION.md` | Why you're learning this — grounds every lesson |
| `RESOURCES.md` | Curated high-trust sources (the manuals above + web/community links) |

As you learn, the skill will grow the workspace with `lessons/` (interactive HTML lessons), `reference/` (cheat sheets), `learning-records/` (what you've learned), and `NOTES.md`.
