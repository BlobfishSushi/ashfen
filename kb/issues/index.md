# Issues

Recurring writing problems, tracked so a review pass can check for them
deliberately instead of rediscovering them each time.

The distinction that governs this folder: **intentional patterns a writer
should reproduce** are voice, and live on the relevant character page or in
`../CLAUDE.md`. **Unconscious tics a critic should catch** are issues, and live
here. The test is whether the author would want a writer agent to reproduce it.

Everything here is read *after* a draft exists, never before. A writer holding a
list of prohibitions writes to avoid the list.

**As of 2026-08-30, critique itself is the `creative-writing-skills` plugin's
job**, via its `critic` and `editor` agents (backed by `/writing-principles`,
`/llm-writing`, and `/creative-writing-craft`). This folder no longer carries
a hand-written substitute checklist — the one that used to live here,
`prose-tics.md`, is archived at `../archive/prose-tics-superseded.md` because
it was actively dangerous to keep around as a fallback: a session without the
plugin loaded could run that short list, find nothing wrong, and report the
chapter clean, when all it had actually verified was the absence of five
specific tics caught in earlier chapters — not a real critique pass.

**If you are about to critique or edit a chapter, confirm the plugin's
`critic`/`editor` agents (or the `writing-principles`/`llm-writing`/
`creative-writing-craft` skills) are actually loaded in this session before
starting.** If they are not, say so and stop rather than substituting the
archived checklist, your own general judgment presented as equivalent, or any
other stand-in — an unavailable base layer is a gap for the author to fix
(get the plugin installed/enabled), not something to quietly work around.

Once a plugin-run critique pass surfaces a *project-specific* recurring
problem — something particular to this manuscript's cast or history, not a
generic craft issue the skills already cover — it belongs back in this
folder as its own page, the way `prose-tics.md` originally started.

## Related

`../archive/prose-tics-superseded.md` for the retired checklist and its
worked examples; `../archive/style-files-superseded.md` for why this folder
exists (the old `kb/styles/` tree was collapsed into it and the character
pages); `../conventions.md` for the kb's tag system.
