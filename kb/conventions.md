# Conventions

The marker and tag system used across this kb, centralized here instead of repeated at the top of every page. Two systems, inherited from the two original reference docs and kept distinct because they answer different questions: the **status markers** answer "how provisional is this fact," the **canonicity tags** answer "does this arc happen in your active timeline."

## Status markers (inline, used anywhere)

| Marker | Meaning |
|---|---|
| *(historical only)* | Dead long before the present day; appears in backstory, not on the page. |
| *(arc-conditional)* | Only exists, or only true, if the named arc is in your active timeline. |
| *(branch-conditional)* | Depends on which branch of a fork you're running. |
| *[Open: …]* | Deliberately unresolved, or not yet decided. Not an error — some of these are meant to stay open. |
| *(Not known in-world)* | True, but no character currently has access to this information. |

## Canonicity tags (arc-level, used on arc and background pages)

| Tag | Meaning |
|---|---|
| `[CORE]` | Happened. Fixed. Assume it in any timeline. |
| `[CORE · PLACEHOLDER]` | Happened, but the details aren't written yet. |
| `[BRANCH]` | Conditional — only in timelines that took that fork. |
| `[ALT-TIMELINE]` | Happened elsewhere; changes nothing at home except memories and any physical object that crossed over. |
| `[BACKGROUND]` | Deep history, complete and unchangeable — not something to be replayed or altered, only drawn on for detail and texture. |

The default assumption throughout the kb is that everything tagged `[CORE]` happened, in foundation order where an order is specified (see `arcs/index.md`), and that branch, alt-timeline, and background material is exactly as conditional as its tag says. When exploring a branch that diverges from a `[CORE]` event, treat the affected pages as provisional for that exploration rather than editing them directly.

## Curation markers (arc-level, layered on top of the canonicity tags)

A third, separate system — these answer "does the author still want this in the story," which is a different question from either of the two above. An arc can be `[CORE]` in every sense that matters to continuity and still carry one of these on top.

| Marker | Meaning |
|---|---|
| ⭐ Key arc | Pure curation, nothing more — no relocation, no change to canonicity. Marks an arc the author considers to shine a light on the characters and drive the plot forward the most. A "start here" flag, not a claim about what's true. |
| `[EXPLORING]` | Fleshed out enough to need its own page — characters, stakes, some shape — but not yet decided either way. Lives in `work/brainstorm/`. Not a claim about canonicity in either direction; it resolves one way or the other once a decision gets made. |
| `[SHELVED]` | Pulled from the active story. The author wrote it, then decided not to carry it forward. Physically relocated out of `arcs/` (and `kb/world/`) into `kb/archive/`, so a scan of `arcs/index.md` reflects what's actually active rather than everything ever drafted. Still complete and kept for reference — nothing here is deleted. |
| `[ALT-ENDING]` | A version of an arc's ending that breaks continuity with whatever comes after it, kept because it's worth having on record. Lives in `kb/archive/alternate-endings/`, cross-linked from the canonical page it diverges from. The canonical ending stays canon; this is the road not taken. |

A `[SHELVED]`, `[ALT-ENDING]`, or `[EXPLORING]` page uses that marker in place of its canonicity tag — none of them are trying to answer "did this happen," only "why is this here" (or "not here yet"). A `[SHELVED]`/`[ALT-ENDING]` page's body text says what it would have been canonically, for context. See `archive/index.md` for the current shelved list, and `work/brainstorm/index.md` / `work/brainstorm/seeds.md` for what's still being explored.

**Ideas too small for even a draft page** don't get a tag or a page at all — they go as a running list entry in `work/brainstorm/seeds.md` instead, until they've grown enough to earn a real `work/brainstorm/` page.

## Where each system lives

Status markers appear inline on cast, world, and arc pages wherever a specific fact needs one. Canonicity tags appear at the top of arc pages and in `arcs/index.md`, and on `world/aura-chronicle/overview.md`. Curation markers appear at the top of arc pages the same way, in `arcs/index.md`, and are collected together on `archive/index.md` (shelved arcs and alternate endings) and `work/brainstorm/index.md` (arcs still being explored). Ideas too small to be a page yet live as list entries on `work/brainstorm/seeds.md`, untagged. Character-specific open questions live on the character's own page (see e.g. `characters/sable-and-aldric.md`) and are also collected on `open-questions.md`.
