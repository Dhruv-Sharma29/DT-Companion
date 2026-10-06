---
tags: [key, solution, design]
---

# 🪄 How AI Nudges, Teaches Questioning, and Digs Deeper

**8 Sep 2026** — the core interaction. Governed by one rule from
[[AI as Tool, Not Master]]: **AI notices, the human commits.** The AI never answers a
design question. It only makes the missing thinking visible.

## The mechanics

### 1. Provenance split — the foundation
As material comes in, every line gets forced into one of three buckets:

```
SAW / HEARD          →  observation   (has a source, a time, a person)
I THINK THIS MEANS   →  inference     (rests on observations — which?)
I'M ASSUMING         →  assumption    (rests on nothing yet — test it)
```

Everything else in the product depends on this. It directly attacks provenance collapse
([[AI Shifted the Bottleneck]]) and it is mechanical enough for AI to draft and a human to
correct in seconds. #key

### 2. The Ladder of Inference — the teaching device #key
==Argyris=='s ladder is the precise tool for *teaching how to question*:

```
observable data → data I selected → meaning I added → assumption →
conclusion → belief → action
```

Novices leap from rung 1 to rung 5. The AI's job is to **name the rung they skipped**,
not to climb it for them: *"You went from 'three users paused at the form' to 'the form is
confusing.' What meaning did you add?"*

### 3. Question laddering — teaching *direction*
A question has a direction, and that is teachable in one sitting:

| Move | Question | Gets you |
|---|---|---|
| **Up** | Why does that matter? | motive, the deeper need |
| **Down** | How exactly does that happen? | mechanism, specifics |
| **Sideways** | What else could explain this? | alternatives |
| **Against** | What would prove me wrong? | falsification |
| **Reframe** | What if the problem isn't X but Y? | a new frame |

The AI classifies the question the student just asked and shows **which move they haven't
made yet**. That is teaching without answering. #insight

### 4. Question quality ladder
Same idea one level up — where is their question on this scale?
`factual → interpretive → assumption-surfacing → falsifying → reframing`
Most novice questions never leave the first two rungs.

### 5. The single highest-value nudge #key
> **"Give me two other explanations for what you saw."**

Premature convergence is the failure mode, so forcing alternatives attacks it directly.
Cheap to build, hard to argue with, and it works on paper — test it in the playbook first.

### 6. Contradiction surfacing
The AI holds all the notes at once, which the team cannot. Legitimate use: *"Note 12 and
note 31 disagree. Which is it?"* Noticing is AI's job; resolving is theirs.

### 7. Silent divergence, then collision (teams)
Each member interprets the evidence **alone** before seeing anyone else's. Then the AI shows
where they disagree. Kills anchoring on the loudest voice — factor #11 in
[[Why Students Struggle — Causal Factors]].

## When to nudge
> [!important] Interrupting **capture** is harmful. Interrupting **commitment** is the point.
Nudge at transitions — when a claim gets written, when the team is about to move stage,
when something is marked "decided." Never mid-flow while they're collecting.

## Fading — how the friction retires itself #key
This is what stops the tool becoming the next crutch ([[The Automation Paradox]]):

| Level | AI behaviour | Trigger to move up |
|---|---|---|
| 1 | Asks the question outright | default for a new user |
| 2 | Says only *"a question is missing here"* | user answers L1 prompts well |
| 3 | Says nothing; the ledger just shows the gap | user starts asking unprompted |
| 4 | Silent record-keeping only | competence demonstrated |

Fading is the feature. It is also the outcome measure: **progress = needing less of it.** #insight
