---
tags: [key, solution, design]
---

# 🧱 Features & App Skeleton

**10 Sep 2026.** Resolves [[Backlog]] #1 and #2. Features derive from the five moves in
[[Product Lexicon]]: **capture → mark → question → commit → trace**.

## Features

### Core — build these
| #   | Feature                                                                                | Move     | Why it exists                                                                                 |
| --- | -------------------------------------------------------------------------------------- | -------- | --------------------------------------------------------------------------------------------- |
| 1   | **Import** — text, photo, audio, files, share sheet                                    | capture  | Meets teams where their material already is                                                   |
| 1b  | **Group import** — a cluster arrives as labelled entries, from Miro, typing, or a scan | capture  | We import groupings; we do not build a canvas. → [[Process Coverage — How Far the App Helps]] |
| 2   | **Provenance pass** — *"were you there?"* on every item                                | mark     | The foundation. → [[Input Requirements]]                                                      |
| 3   | **Four-class sort** — observation / secondhand / inference / assumption                | mark     | The distinction everything rests on                                                           |
| 4   | **Warrant links** — attach an inference to the observations under it                   | mark     | Makes an unwarranted leap visible as an empty link                                            |
| 5   | **The prompt** — the missing question, at commitment                                   | question | The intervention itself. → [[AI Nudging — Interaction Design]]                                |
| 6   | **Contradiction surfacing** — *note 12 disagrees with note 31*                         | question | The one thing AI legitimately does better than the team                                       |
| 6b  | **Anomaly surfacing** — *these observations don't fit the story you've settled on*     | question | Where uniqueness lives. → [[Why Not ChatGPT — The Average Answer]]                            |
| 6c  | **Generic-framing flag** — *this is the default reading of the domain*                 | question | Counters LLM convergence                                                                      |
| 6d  | **Landscape Intel** — what exists in this problem dimension, and where it stops        | commit   | Sourced, secondhand, abstract query only. → [[Landscape Intel]]                               |
| 7   | **Alternative required** — can't commit without a rival explanation on record          | commit   | Direct counter to premature convergence                                                       |
| 8   | **Commitment record** — the problem statement, its evidence, what was rejected         | commit   | The output the course asks for anyway                                                         |
| 9   | **Open assumptions** — a live count of what's untested                                 | commit   | Makes the unexamined visible and countable                                                    |
| 10  | **Trace** — a test result finds the assumption it breaks                               | trace    | Answers *problem, idea, or execution?*                                                        |
| 11  | **Support level & fading** — L1→L4, plus naming the move after the fact                | —        | → [[Teaching Model]]                                                                          |

### Team
| 12 | **Divergence round** — members interpret alone first | Prevents anchoring on the loudest |
| 13 | **Collision view** — differing interpretations side by side | The shared-surface moment iPad exists for |

### Secondary — after the core works
| 14 | **Instructor view** — read the reasoning, not just the artifact | The buyer's whole value. Web, not iPad |
| 15 | **Pitch assembly** — assembles the final submission *from recorded decisions* | [[Backlog]] #13. Must assemble, never generate |
| 15b | **Mock Crit** — the app questions the project using its own weak links, before the instructor does | The strongest attraction lever. → [[Making It Attractive]] |
| 16 | **Pencil annotation** — mark up evidence directly | A native differentiator. → [[Native vs Web — The Differentiators]] |

### Deliberately absent #key
No **clustering canvas** — Miro and paper already do that well, and it isn't the gap.
No insight ranking. No auto-generated problem statements. No idea generation. No scoring of
the team's thinking. Each of these would take over the step the team is meant to be learning.
→ [[The Automation Paradox]]

---

## Skeleton

### Screens
```
PROJECT
  ├── MATERIAL        inbox of everything imported, unsorted → sorted
  ├── LEDGER          the threads: claims with their evidence beneath
  │     └── THREAD    one claim · its observations · alternatives · open assumptions
  ├── COMMIT          the sheet that will not close without an alternative
  ├── ASSUMPTIONS     everything untested, in one list
  ├── TRACE           enter a test result → see which assumption broke, and where it lives
  ├── MOCK CRIT       questions drawn from the project's own leaps and open assumptions
  └── EXPORT          the problem statement, the evidence chain, the pitch
```

### Data model
```
Entry
  id · text · class{observation|secondhand|inference|assumption}
  provenance{when, where, who, present?} · media · createdBy · createdAt

Link            from: Entry(inference) → to: [Entry(observation)]   // the warrant
Thread          claim: Entry · supports: [Link] · alternatives: [Entry] · openAssumptions: [Entry]
Commitment      statement · thread · rejected: [Entry] · committedAt · committedBy
TestResult      prototype · outcome · disconfirms: Entry(assumption)
                → breakPoint: {problem | idea | execution}
```

Everything hangs off **Entry** and its **class**. Get those two right and the rest is views.

### The demo path #key
```
import a messy note  →  mark it  →  write a conclusion  →  app names the jump
   →  add an alternative  →  commit  →  a test fails  →  trace it back
```
Two minutes, and it shows the whole thesis. Build this path first and nothing else until it works.
