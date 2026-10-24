# mv-pv-arrangement

An agent skill for **structuring a lyric PV as a system instead of a slideshow**.

The symptom it addresses: a cut that is smooth, technically fine, and still feels ordinary. That is almost never a rendering problem — it is an arrangement problem. If 15 shots differ only by framing and position, the viewer sees one image rescaled fifteen times.

## The five ideas

| # | Idea | Why it matters |
|---|---|---|
| 1 | **6–10 named style families with a mood tag**, not sliders | Selection by intent; a slider cannot express "quiet" vs "loud" |
| 2 | **Three-stage text**: enter / *emphasise-when-sung* / exit | Only-enter text looks pasted on; emphasis also removes the sync problem |
| 3 | **One continuous world**, camera moves through it | Per-shot layouts read as a slideshow; a continuous world reads as one motion |
| 4 | **Transitions as pure functions** of (phase, progress) | Parameterised means changing the whole film's feel by swapping a function |
| 5 | **Typography decoupled from composition** | Restyle text without rebuilding shots |

The single highest-leverage change is #2: a per-character emphasis triggered by the vocal energy peak. It makes text feel sung *without* asking the viewer to check alignment against the vocal.

## What it deliberately does NOT do

It does not say "never break a line into phrases" — it says **express phrase breaks in layout, not in time**. A per-phrase reveal is an invitation to audit sync; a column break is not.

## Provenance and licence boundary

The structural vocabulary here was learned by reading the design docs of `chthollyphile/lumisynth` (`docs/HANABI.md`, `docs/PACKS.md`). That project is **AGPL-3.0**. Only the *organisation* was taken, never code. Keep that boundary.

## Licence

MIT. See `LICENSE`.
