---
tags: [key, solution, feature]
---

# 🧭 Landscape Intel

**11 Sep 2026.** Feature: as the team moves into a dimension of their problem, the companion
shows what already exists there — competitors, existing solutions, where they stop.

## Why it belongs #key
You cannot claim an angle is unique without knowing the landscape. Landscape research is
**collection** — the step AI legitimately made cheap — so this is AI doing noticing, not
judging. The team still decides whether a gap is real and worth pursuing.
→ [[Why Not ChatGPT — The Average Answer]]

## When it fires
Not constantly. When a team **commits to a problem dimension** —
*"elderly users + medication adherence"* — the companion returns:
- existing products and approaches in that dimension
- what each one does, and **where it stops**
- which of the team's own anomalies none of them address

The last line is the payoff: *here is what your research saw that nobody is serving.*

## The non-negotiable: grounded, sourced, secondhand #key
> [!warning] The single biggest risk in this feature
> LLMs **invent products**. A hallucinated competitor is worse than none — it is provenance-free
> information, the exact thing this project fights.

So:
1. **Search-grounded only.** Every competitor comes from a live search with a link. No link, no entry.
2. **Enters the ledger as *secondhand*.** It is someone else's account, and is marked that way —
   the same rule as any other material. → [[Input Requirements]]
3. **Shown with its date.** Landscapes move; stale intel is labelled stale.

A feature about uniqueness that fabricates the competition would be self-refuting.

## Privacy — how this coexists with on-device processing
This is the one feature that needs the network. It stays compatible with the on-device argument
([[Native vs Web — The Differentiators]]) because only the **abstract problem dimension** leaves
the device — *"medication adherence, elderly"* — never interview material, names, or notes.
State that boundary explicitly; it's the first thing a careful reviewer will ask.
