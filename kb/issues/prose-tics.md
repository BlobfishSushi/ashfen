# Prose tics — review checklist

**Read this during a critique/editor pass. Do not load it while drafting.**

That restriction is the whole point of this file. Everything here was previously
in `kb/styles/prose-conventions.md`, where a writer agent read it *before*
putting words on the page. A writer holding a twenty-item prohibition list
writes to avoid the list rather than to write the scene, and the prose goes
stiff and self-conscious in a recognizable way. These are diagnostics, not
instructions. They belong after the draft exists.

Only project-specific findings live here. Generic LLM prose failure modes —
over-explaining, labeling emotions, resolving tension early, em-dash overuse,
homogenized character voices — are covered by the writing skills
(`/writing-principles`, its `resources/failure-modes.md`, and `/llm-writing`)
and were removed rather than restated. See
`archive/style-files-superseded.md` for what was dropped and why.

*Chapters 1–6 were converted to third person past on 2026-08-29 and every
finding below was cleared out of them in the same pass. What follows is the
standing checklist for new drafts, not a list of outstanding defects.*

## The flat-period problem

*Flagged by the author as the single biggest problem in the original chapter 5
draft.*

Nearly every line of dialogue ended in a period. Questions were punctuated as
statements. Nobody raised their voice. No question mark appeared anywhere in a
three-thousand-word chapter.

- Search the chapter for `?` and `!`. If a long scene has none, that is the
  finding — no further analysis needed.
- The flat declarative question ("How long's the round." / "Come again.") is
  part of Leo's on-the-job register, a few per scene, and belongs to nobody
  else. See `../characters/leo-castello.md`. The failure was that it spread:
  every character reading as the same withheld affect under different name
  tags. Check who is doing it, not just how often.
- Agnes asks questions like a person, with question marks. Her flatness is
  warmth held steady, not affect withheld. See `../characters/agnes.md`.

## Uniform composure

Every speaker producing clean, complete, grammatically tidy sentences — no
restarts, no repeated words, no visible confusion. Reads as one voice under
several name tags even when the content is correct.

- Watch for the balanced written-not-spoken construction: "I'd rather X than
  Y," or any line with more clauses than a person produces mid-conversation.
  If it could be read aloud as a formal proposition, it is too composed.
- Cut in editing: *"I'd rather you know that going in than spend the next five
  minutes arguing with me about it."* → *"I'd rather just say it than spend
  five minutes arguing with you about whether I've lost it."*
- Each character's hesitation pattern should be their own, not generic verbal
  static distributed evenly.

## Scene-final buttons

A "button" is any line that wraps, resolves, or comments on what just
happened. Four stacked at a chapter's end is the loud version; a single tidy
closing image is the one that still gets written with the rule in mind.

**Read the last one to three lines in isolation.** If they restate what just
happened plus a feeling about it, or add one more image after the scene ended,
cut back to the strongest beat — usually a line of dialogue, alone, no tag.

- Cut: *"'Okay,' Leo says, which is not remotely what he means, but it's the
  only word that comes out steady."* The suppression was already shown two
  paragraphs earlier. Fix: *"'Okay.'"*
- Cut: *"Somewhere in the dim behind the counter, something that might be
  Aldric makes a sound that might be a laugh"* as a final line. Not
  editorializing, still a closing action after the dialogue had landed it.
- Cut: *"He had been very good at knowing which one it was going to be. That
  had never once helped."* The best line in the pilot it came from, and still a
  button: it delivered a verdict on a paragraph that had already landed.

## Redundant work

The general rule, stressed by the author 2026-08-29: **if a phrase or sentence
is doing a job something adjacent already did, it does not need to be there.**
This is the most common cut in this manuscript and it takes several shapes.

- The same beat played twice in one exchange. Agnes asking Leo to hear her out
  before deciding she's lost it, then saying the identical thing again four
  lines later.
- Narration restating what an image already showed. *"She hasn't cleared it.
  From the way she keeps checking on it, that's not because she forgot"* after
  the checking has already been on the page.
- Narration explaining an effect. *"No drama in it at all, which is what makes
  it land."* Cut the second clause; the reader supplies it.
- A motif re-planted every time it appears. The cold in chapters 1–2 was
  established three separate times before it paid off once.
- A word repeated across a sentence because the construction liked the rhythm.
  *"...written on a list and stays on the list, in a building that stopped being
  able to afford its own list."*

## Reaction filler standing in for a beat

"He sits with that a second." / "He lets it sit a second." / "That one takes a
second longer to land." Three sentences in one chapter draft; the same non-beat
in different clothes. Time passing with nothing specific happening.

The fix is a concrete, character-specific action or thought — what does *this*
information make *this* character do or remember? If nothing specific comes,
the beat is not earning its place. Cut to the next line.

## The bolted-on second clause

A sentence lands a specific concrete beat, then tacks on "...like X" to dress
up or explain what it just did. Historically the most frequent line-level
failure in this project. The fix is almost always ending one clause earlier.

- Cut: *"He notices that about himself sometimes, like a man checking a scar to
  see if it still hurts."*
- Cut: *"...uses it on him specifically, like it's been saving it up."*

At most one "like X" or metaphor construction per scene. If a second appears in
revision, cutting one usually strengthens both.

## Escalating triads and fragment-verdicts

*Added 2026-08-29, from the chapter 6 read.* This one was previously being
**actively encouraged** by the since-removed `authorial-sensibility.md`, which
prescribed parallel-clause escalation, rule-of-three repetition, and
long-setup/short-verdict rhythm as house technique. Those patterns were
distilled from the author's first-person comic nonfiction, where they work.
Ported into third-person fiction they are close to the LLM default cadence, and
they accumulate.

Symptoms to count per chapter:

- The three-beat escalating parallel: *"will not let him bend, will not let him
  turn his head, and will not let him have a hand for anything, including a
  door, including a wall, including catching himself."*
- Negation pairs setting up a correction: *"Not stuck. Not bolted."*
- The fragment verdict after a long setup: *"It's not much to look at."*

None of these is wrong once. The finding is density. If a chapter has more than
two or three across all three shapes, the rhythm has become the voice.

## Heightened relay register

Rendering the ghosts' quoted lines with exclamation marks inside Agnes's
quotation marks, as a contrast device against her plainness. This came from the
removed style files and is not a real feature of the relay: what makes a direct
quote land is her *choosing* to give it verbatim instead of paraphrasing. See
`../characters/agnes.md`. Cleared from chapter 6 on 2026-08-29; watch for it
returning.

## Related

`../characters/leo-castello.md` and `../characters/agnes.md` for the voice
notes that *are* meant to be read before drafting; `../open-questions.md` for
the voices that aren't settled; `../archive/style-files-superseded.md` for the
removal record.
