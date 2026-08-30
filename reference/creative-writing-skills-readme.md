# Creative Writing Skills — Project Layout Reference

Kept for reference. This is the `muse` skill's own recommended project
layout, from the `creative-writing-skills` plugin
(github.com/haowjy/creative-writing-skills). Ashfen's actual layout
(documented in `../CLAUDE.md`) adapts this template rather than following
it exactly — see `../CLAUDE.md` for the specific departures and why.

---

# Project Directory Layout

The recommended structure for a creative writing project using this system is:

```text
my-story/
├── CLAUDE.md              # Project conventions (created by project-setup)
├── story/                 # Chapters and manuscript
├── work/                  # Current drafting effort
│   ├── outline/
│   ├── drafts/
│   ├── critique-reports/
│   └── brainstorm/
└── kb/                    # Durable knowledge base
    ├── styles/            # Voice reference files
    ├── characters/        # Character state and profiles
    ├── world/             # Locations, lore, systems
    ├── timeline/          # Chronology
    ├── canon/             # Established facts
    └── issues/            # Tracked writing problems
```

## Folder Purposes

- **story/**: Contains finalized chapters and manuscript sections
- **work/**: Holds temporary materials including outlines, drafts, critique feedback, and brainstorming notes for the active project phase
- **kb/**: Stores permanent reference materials that persist across sessions—style guides derived from your voice, character documentation, world-building details, timeline records, canonical story facts, and a log of revision issues requiring resolution

*Source: raw.githubusercontent.com/haowjy/creative-writing-skills/main/README.md, retrieved 2026-08-28. The upstream repository does not provide explicit guidance for migrating an existing project into this structure or adapting it to a project's own conventions — Ashfen's adaptation (see `../CLAUDE.md`) was worked out manually.*
