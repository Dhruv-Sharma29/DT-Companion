---
tags: [key, scope, solution]
---

# 📥 Start Point — What Material a Team Needs

**10 Sep 2026.** Resolves [[Backlog]] #7.

## The minimum bar #key
To start, a team needs:

1. **At least one real contact with people or context** — an interview, an observation, a
   site visit — that a team member was personally present for.
2. **Material in raw or near-raw form** — transcript, field notes, photos, audio, quotes.
   Not only a summary.
3. **Someone who can say where each piece came from** — when, where, who.

That is all. No minimum count, no particular research method. The product picks up wherever
the team's own process left off. → [[Process Coverage — How Far the App Helps]]

## "Is this valid material?" — the honest problem
The awkward case: a team arrives with forty AI-summarised notes, no transcripts, and nobody
remembers which interview any line came from. The provenance is already gone. This will be
common — it is the exact behaviour the project exists to address.

### The answer: don't restore it, reveal it #key
The app cannot reconstruct provenance that was never kept. It can make its **absence
countable**, which is more useful.

On import, one question per item: **"Were you there?"**

| Answer | Class |
|---|---|
| Yes, I saw or heard this | **Observation** |
| No — a teammate, a model, or a source told me | **Secondhand** |
| It's something I worked out | **Inference** |
| It's something I'm taking as given | **Assumption** |

**Secondhand** is the fourth entry class, added for exactly this case →
[[Product Lexicon]] should carry it.

### Why this is the right behaviour
A ledger showing **90% secondhand** is not a broken ledger. It is a finding:

> *You have very little evidence. What you have is mostly a model's account of what someone
> else said. Before you define a problem, go and see something.*

> [!important] The product's honest response to weak input is to **show that the input is
> weak** — and that is the most valuable thing it could possibly say to a team about to spend
> three weeks building on it. #insight

This also protects against garbage-in: the tool cannot make a well-warranted claim out of
nothing, and it should never appear to.

## What this rules out
A team with **no** first-hand contact cannot use the product meaningfully — and should be told
so plainly rather than walked through a process that produces a confident-looking output from
nothing. That is a refusal worth building in.
