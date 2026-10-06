---
tags: [key, problem]
---

# 🎯 Problem Definition — Working Note

Started **8 Sep 2026**. This is the live note; earlier framing lives in
the `project sel` folder — **outdated, do not use**.

## Where we started

> Because of the rise of AI, collecting information and generating ideas is no longer
> a big deal — but because of this, people struggle to make sense of evidence, decide
> what matters, choose what to investigate next, and know how to adapt when their
> solution does not work.

## What's strong in it

The causal move is the good part. It is a **bottleneck-shift** argument — see
[[AI Shifted the Bottleneck]] — and bottleneck shifts are one of the most reliable
ways to find a real, newly-urgent problem. #key

## What's weak in it

### 1. It is four problems wearing one coat #key
"Make sense of evidence" / "decide what matters" / "choose what to investigate next" /
"adapt when the solution fails" are four separate problems. Different moment, different
user state, different failure, different fix. A statement joined by *and* is a **scope**,
not a problem. You cannot design against it and you cannot test it.

> [!important] A problem statement you can't be wrong about is not a problem statement.
> Narrow until someone could reasonably disagree with you.

### 2. "AI caused it" is overclaiming #key
Students struggled with synthesis long before 2022. If you pitch AI as the *cause*,
one question kills it: *"Didn't this always happen?"*

The defensible version is a change in **ratio and shape**, not origin:

| | Before | Now |
|---|---|---|
| Effort spent collecting + ideating | most of it | little |
| Difficulty of judging | hard | equally hard |
| Volume to judge | small | large |
| Provenance of material | you were there | unclear |
| Reps building judgment | many | few |

So: AI did not create the problem. **It removed the work that used to hide it, multiplied
the material it operates on, and stripped the signal people used to judge with.** #insight

### 3. No moment, no person
"People" and "nowadays" cannot be observed. A problem must name a person at a moment.

## Sharpened statement — draft 1

> AI has made evidence and ideas cheap to produce but no easier to trust. Novice design
> teams now hold more material, with weaker provenance, and have had less practice judging
> it — so they commit to the **first plausible** interpretation rather than the
> **best-supported** one.

### Narrowed to one moment
Of the four, take the **Observe → Define handoff**: *"which of these is the real problem?"*

Why this one:
- Highest leverage — a wrong problem wastes everything downstream.
- It is where teams visibly stall, so it is observable.
- It is where AI's *fluent-but-ungrounded* failure bites hardest. #insight

## Point of View

- **User** — a student design team two weeks in, holding 40 AI-summarised interview notes
  and 30 AI-generated How-Might-Wes.
- **Need** — to know which reading of their evidence deserves the next two weeks.
- **Insight** — they cannot tell what they *observed* from what a model *inferred*, so every
  option reads as equally well-argued, and equally unearned. #insight

## How Might We
- HMW make the difference between an observation and an inference impossible to miss?
- HMW make a team's reasoning visible to itself, so disagreement surfaces early instead of at the demo?
- HMW make the *weakest* link in an argument the most obvious thing on screen?
- HMW let a team spend conviction like a budget — you may back one reading, so which?

## Assumptions to test → [[Open Questions]]
Each is falsifiable. Do not build until the first three are checked.

1. Teams using AI actually converge **faster and earlier** than teams that don't.
2. They cannot reliably separate observed from inferred material in their own notes.
3. The pain is **felt** — they notice it — rather than only visible to an instructor.
4. Wrong-problem selection, not weak execution, is what sinks their projects.

See [[The Automation Paradox]] before designing anything.
