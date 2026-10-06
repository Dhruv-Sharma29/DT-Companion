---
tags: [key, scope, solution]
---

# 🔁 Process Coverage — How Far Along the Process the App Helps

**9 Sep 2026.** Not *how far to build* (that's staging, in [[Scope, Platform & Users]]) —
**how much of the Design Thinking loop the product accompanies.**

## The short answer #key
> **Deep before the prototype. Thin at it. A second peak after it.**
> The app's *coaching* is concentrated at **Define**. Its *record* runs the whole loop, and
> earns its keep again at **Iterate**.

## Why it isn't one stage
The mechanic — *claim → evidence → alternatives → commitment* — is **stage-agnostic**. It
fires at every point where accumulated material has to become a decision. There are three
such convergences, not one:

```
EMPATHIZE / OBSERVE
      ↓
  ◆ CONVERGENCE 1 — which problem?        ← the product
DEFINE
      ↓
IDEATE
      ↓
  ◆ CONVERGENCE 2 — which idea?           ← thin: does it answer the problem?
PROTOTYPE
      ↓
  ◆ CONVERGENCE 3 — what did we learn?    ← second peak
TEST → ITERATE ↺
```

Double Diamond names the first two as the **necks of the diamonds**. The third is where
Schön's *reflection-in-action* lives. Say it this way to an expert — it shows the coverage is
derived from the process, not chosen for convenience.

## Coverage, stage by stage

| Stage | Depth | What the app does | Why not more |
|---|---|---|---|
| **Empathize / Observe** | **light** | Accepts material; asks for provenance at import — *when, where, who said it* | Doesn't plan or run research. Collection is the step AI already made cheap — helping there contradicts the thesis |
| **Define** | **FULL — this is the product** | Provenance split, the missing question, alternatives before commitment, the committed problem with its evidence chain | — |
| **Ideate** | **deliberately light** | One job: *does this idea actually address the committed problem?* A link back to the ledger | Generating ideas is what AI made free. Helping generate them is the disease |
| **Prototype** | **thin** | One job: *what is this prototype testing?* Forces a testable hypothesis before building | Not a prototyping tool; those exist and are good |
| **Test → Iterate** | **second peak** | *What did the result disconfirm?* Traces the failure to the assumption it breaks | — |

## The Iterate payoff — why the record must be wide #key
When a prototype fails, the question every team gets stuck on is the one they listed at the
start: **change the problem, the idea, or the execution?** They cannot answer it, because
nobody wrote down what the idea rested on.

The ledger answers it mechanically:

```
the test disconfirmed assumption A
     ↓  where does A live?
in the PROBLEM DEFINITION  → go back to Define. The frame was wrong.
in the IDEA                → go back to Ideate. The frame holds; the response didn't.
in the EXECUTION           → rebuild. Both hold; you built it badly.
```

> [!important] This is the strongest argument for keeping the record. #insight
> The ledger's value at **Define** is immediate but modest — better thinking, once.
> Its value at **Iterate** is what makes keeping it *rational*: it is the only thing that
> tells you what to change. Without this payoff the ledger is homework. With it, it is the
> reason the project doesn't die after a failed test.

And it directly answers "adaptiveness / iteration," which was one of the three problems named
at the start. → [[Terminology & Prior Art]]

## Are we discarding the rest of Design Thinking? No #key
Two different things, easily confused:

| | |
|---|---|
| **The process we work inside** | the full Design Thinking loop, unchanged |
| **The step we add support to** | one convergence: material → committed problem |

Everything else still happens, in the normal way, with the normal methods. We are not
replacing them and we are not competing with them.

### DT methods we depend on
- **Interviews, observation, shadowing** — students still do them. We just don't tool them.
  Our input is whatever they gathered.
- **Affinity mapping** — still done, **elsewhere**, and we pick up after it. See the scope
  decision below.
- **POV / problem statements** — this is our **output format**. We produce the thing DT asks for.
- **How Might We** — follows from the committed problem, in the usual way.
- **Ideation, prototyping, testing** — entirely normal, entirely untouched.
- **The iterative loop** — not optional for us. The Iterate payoff above only exists because
  DT loops back. We depend on it.

### What we add that DT does not have
Design Thinking has no method for the interpretation step. That is the gap we identified in
[[Why Students Struggle — Causal Factors]], and we fill it by borrowing from outside DT —
the **Ladder of Inference**, **Toulmin's argument structure**, and **provenance tracking**
([[Terminology & Prior Art]]).

> [!important] The honest framing: we are not replacing Design Thinking, and we are not
> reinventing it. **We are adding the missing method to the one stage that never had one.**

## Scope decision: we do not build a clustering canvas #key
Deliberate, and worth being able to defend.

**Why not build it**
- Clustering is **well served** — Miro, FigJam, Mural, and paper walls all do it well. Building
  a canvas means competing with Miro on Miro's ground, which we lose.
- It is **not the gap**. Clustering tells you what is *similar*; the unmethoded move is from a
  cluster to a claim you can defend. → [[MASTER — Full Problem Brief]] Q3
- For a course-scale build, a canvas would consume the whole budget and produce a worse Miro.
- A physical wall has real value — embodied, collaborative, tactile. Replacing it with a
  screen is not obviously an improvement.

**But we do accept clusters as input**
Not a canvas — a *data structure*. A cluster arrives as **a group of entries with a label**,
however the team made it: exported from Miro, typed in, or photographed off a wall. That keeps
the provenance link intact across the boundary without us building a canvas.

> [!important] The line: **we import groupings, we do not provide grouping.** #insight
> This is also why the camera matters less here than it first appeared — its real job is
> capturing observations in the field, not scanning walls.
> → [[Native vs Web — The Differentiators]] §6

## Explicitly beyond scope
Business modelling, go-to-market, roadmapping, launch, scale. The loop ends at *iterate*.
Saying this out loud is what keeps the scope from drifting.

## What this means for the build #key
For a course project: **build Define fully, stub the rest.**
- Define carries the thesis. If it doesn't work there, nothing else matters.
- Iterate is second — and it is what a demo should end on, because tracing a failure back to
  a recorded assumption is the most convincing thing this product can show.
- Ideate and Prototype are one screen each and can stay one screen each.

> A demo that shows the Define loop *and* the Iterate trace tells the whole story in two
> minutes. Everything else is scaffolding around those two moments.
