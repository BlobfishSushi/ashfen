# Ashfen — Project Conventions

Story playground for the Ashfen setting: present-day ghosts Sable and Aldric,
the bakery crew, and the hunter network built up around them. This file
orients any session (or the `muse` skill and friends) working in this
project. Read `kb/conventions.md` next — it owns the tag and marker system
referenced throughout the kb.

## Layout

```
story/                    # Manuscript chapters (not yet started — everything
                           # so far is worldbuilding and arc planning)
work/
  outline/                # Arc/chapter/beat outlines once drafting begins
  drafts/                 # In-progress manuscript drafts, plus voice pilots
  critique-reports/       # Critique and editor passes on drafts
  brainstorm/             # Ideas not yet committed to canon — see below
kb/
  characters/             # One page per standing cast member, voice notes included
  world/                  # Locations, lore, systems, and deep background
  arcs/                   # Committed story arcs (see kb/arcs/index.md)
  issues/                 # Recurring prose problems — read at review, not at draft
  archive/                # Shelved arcs, alternate endings, legacy source docs
  conventions.md          # The tag/marker system — read this first
  vocab.md                # Naming disambiguations
  open-questions.md       # Every deliberately unresolved item, collected
reference/
  creative-writing-skills-readme.md   # The muse skill's own layout guide, kept for reference
```

This follows the `muse` skill's recommended shape (`story/`, `work/`,
`kb/{characters,world}/`), adapted to keep this project's own
lifecycle system intact rather than flattened to the generic template.
Four deliberate departures, and why:

- **`kb/arcs/` stays, instead of `kb/canon/`.** Canon here isn't a flat set
  of established facts — it's a graph of arcs with dependencies, foundation
  order, and a canonicity tag on each one (`[CORE]`, `[BRANCH]`,
  `[ALT-TIMELINE]`, `[BACKGROUND]`; see `kb/conventions.md`). `kb/arcs/index.md`
  is the map. `kb/canon/` never existed as a separate thing to preserve.
- **`kb/archive/` holds shelved arcs, alternate endings, *and* the three
  pre-decomposition legacy source docs** (`kb/archive/legacy-source/`) —
  the original monolithic notes this whole kb was built out of. They're
  fully superseded by the structured pages but kept for reference.
- **No `kb/styles/` anymore.** It existed and was removed on 2026-08-29: the
  files in it had grown into a prescriptive ruleset that displaced the writing
  skills' craft layer and was actively producing AI prose cadence. Voice notes
  now live on the character pages, project-wide prose facts are in the Prose
  section below, and the failure log moved to `kb/issues/`. The full removal
  record, including which rulings were dropped as already covered by the
  skills, is in `kb/archive/style-files-superseded.md`. Don't recreate the
  folder — if a new voice needs documenting, it goes on its character's page.
- **No `kb/timeline/` yet.** Nothing has needed it — `kb/arcs/index.md`
  already carries foundation ordering. Add it when something needs it rather
  than pre-building empty structure.

`work/outline/`, `work/drafts/`, and `work/critique-reports/` are set up
per the template. `work/outline/` now holds the serial writing order
(`serial-order.md`) and chapter-level breakdowns as drafting reaches them;
`work/drafts/` holds the manuscript itself as chapters get written, plus the
`leo-voice-pilot-*` scenes, which are disposable craft exercises and not
manuscript. `work/brainstorm/` is populated: it holds every idea that's been
fleshed out enough for its own page but not yet decided either way (tag
`[EXPLORING]`), plus `work/brainstorm/seeds.md` for ideas too small even
for that.

## The lifecycle

An idea moves through exactly one of these paths:

1. **Seed** — a one-line spark, listed untagged in `work/brainstorm/seeds.md`.
2. **Exploring** — grown enough for its own page in `work/brainstorm/`,
   tagged `[EXPLORING]`.
3. From there, either:
   - **Committed** → moves into `kb/arcs/` (or `kb/characters/`,
     `kb/world/`, whichever fits) with a real canonicity tag, or
   - **Passed on** → moves into `kb/archive/` with the `[SHELVED]` tag.
4. **Alternate endings** — a version of an already-committed arc's ending
   that breaks continuity with what comes after it, kept on record but
   tagged `[ALT-ENDING]` and filed in `kb/archive/alternate-endings/`.

Full tag and marker definitions are in `kb/conventions.md`. Don't edit a
page's canonicity by moving it manually without also updating its tag and
any pages that pointed to it — `kb/conventions.md` and `kb/arcs/index.md`
are the two places that assume the folder structure matches the tags.

## Prose

**The writing skills are the base layer. The kb does not restate them.**
`/writing-principles`, its `resources/failure-modes.md`, `/llm-writing`, and
`/creative-writing-craft` own general craft: em-dash discipline, trusting the
reader, showing rather than labeling emotion, keeping character voices
distinct, not resolving tension early, not over-explaining. Those are loaded
by the writer, critic, and editor agents already. This project's kb carries
only what those skills cannot know — who sounds like what, and what this
manuscript has actually gotten wrong before. When the two seem to conflict,
the skill wins unless a kb page names the specific exception.

That precedence was inverted until 2026-08-29 and it degraded the prose. If
you find yourself writing a prohibition into the kb that any competent editor
would already apply, it belongs in neither place.

Five project-wide facts, all the general prose rules there are here:

- **Third person, past tense** is the baseline, settled 2026-08-29 on Leo's
  voice pilots. Chapters 1–6 were converted in the same pass.
- **If a phrase or sentence is doing a job something adjacent already did, it
  does not need to be there.** Author's standing instruction. This is the most
  frequent cut in this manuscript: a beat played twice in one exchange,
  narration restating an image, a clause explaining the effect of the clause
  before it, a motif re-planted every time it appears.
- **Trailing and interrupted speech uses an ellipsis, not an em dash.** The
  skills defer to "the project's documented interruption pattern" — this is it.
- **Flair is one continuous, hyper-specific, almost mock-technical description
  of an actual mechanism, delivered deadpan, that just ends.** The
  author-approved target: *"That gets something out of her, not quite a laugh,
  but a wet snort that would have led to a cough if she hadn't held her breath
  and adjusted her diaphragm for modesty."* The mechanism can be physical,
  social, administrative, anything — it has to be one continuous specific idea
  with no second comparison stapled on to explain it. A line or two per scene,
  never on every beat; the flourish works because it's rare.
- **Wordplay and cleverness for its own sake is not wanted**, even though it
  can look similar on the page. A pun — "a policy exception to not laughing" —
  was tried and rejected. The wet-snort line works because it is absurdly
  literal, not because it is witty.

**Voice is deliberately thin.** Leo (`kb/characters/leo-castello.md`) and Agnes
(`kb/characters/agnes.md`) have working voice notes; read the relevant page
before drafting that character. Everyone else has none, and the untested edges
of Leo's are marked on his page. Don't derive a voice from the existing drafts,
and don't write a voice file on the strength of one scene — that is exactly how
the last set of style files went wrong. Voices get settled the way Leo's was:
disposable pilot scenes written on purpose, in more than one mode, with the
author choosing.

**`kb/issues/` is read at review, never at draft time.** It is the log of what
has actually gone wrong in these drafts, for the critic and editor passes. A
writer holding a list of prohibitions writes to avoid the list, and the prose
goes stiff — which is the failure this whole structure exists to prevent.

## Working here

- **Don't title chapters.** The heading is `# Chapter N` and nothing else.
  Titles are the author's to write if they ever want them; don't supply one,
  don't suggest one unasked, and don't fill an untitled chapter's heading.
- Check `kb/open-questions.md` before inventing an answer to something the
  author left deliberately unresolved.
- Cross-references inside kb pages use backtick shorthand relative to the
  project root inside `kb/` (e.g. `` `arcs/origin.md` `` means
  `kb/arcs/origin.md`) or spelled out in full when pointing outside `kb/`
  (e.g. `` `work/brainstorm/seeds.md` ``). Real markdown links
  (`[text](path)`) are genuine relative paths from the linking file.
- Don't decide major plot points unprompted — this project is the author's own
  playground, and Claude's job is narration, detail, and brainstorming
  alongside them, not authoring the story's direction.
- **That last point has a concrete workflow.** Before drafting a chapter's
  prose, outline it beat by beat first and flag every point that needs an
  author decision — who a new character is, a case's specifics, a cause of
  death, a location that matters to plot, anything not already on record
  in `kb/` — as an explicit open question in the outline. Ask, then draft;
  don't invent a plot specific and flag it as changeable after the fact.
  Atmospheric and descriptive detail (blocking, physical description,
  dialogue phrasing, scene texture) is fair game to just write.
