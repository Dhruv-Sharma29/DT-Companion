---
tags: [key, reference, naming]
---

# 🔤 Product Lexicon

**9 Sep 2026.** The vocabulary of the solution — what each part is called, and why.
For the *field's* vocabulary see [[Terminology & Prior Art]]; for the product's name,
[[Naming]].

Use these words consistently. Half of sounding unfinished is calling the same thing three
different names across one presentation.

---

## The thing itself

| Term | Definition |
|---|---|
| **Reasoning ledger** | The record: what the team observed, what they concluded, and what each conclusion rests on. Dated, append-only, kept for the whole project |
| **Entry** | One item in the ledger |
| **Thread** | A claim plus everything under it — its evidence, alternatives and open assumptions |

## The kinds of entry #key
This is the core distinction the whole product rests on.

| Term | Definition | Test |
|---|---|---|
| **Observation** | Something seen or heard, with a source | *Could you point to where this happened?* |
| **Secondhand** | Reported by a teammate, a source, or a model — nobody here was present | *Who was actually there?* |
| **Inference** | An interpretation drawn from observations | *Which observations?* |
| **Assumption** | Taken as true, with nothing under it yet | *What would you need to check?* |
| **Commitment** | A decision the team locks in — the problem statement, the chosen idea | *What did you reject to get here?* |

## The relationships

| Term | Definition |
|---|---|
| **Provenance** | Where an entry came from — when, where, who said it |
| **Warrant** | The link that shows *why* given observations support a given inference (Toulmin) |
| **Unwarranted leap** | An inference with no observations attached — the thing the app surfaces |
| **Alternative** | A rival explanation, recorded before a commitment is allowed |
| **Open assumption** | An assumption not yet tested; the ledger keeps a live count |

## The interaction

| Term | Definition |
|---|---|
| **Prompt** | The question the app asks. Never an answer |
| **The missing question** | The specific move not yet made — *up, down, sideways, against* |
| **Divergence round** | Team members interpret alone, before seeing each other |
| **Collision** | The moment their differing interpretations are shown side by side |
| **Support level** | How much help the app is giving — L1 asks outright, L2 hints, L3 silent, L4 record-only |
| **Fading** | The planned reduction of support as the team improves. **The success measure** |

## The payoff

| Term | Definition |
|---|---|
| **Trace** | Following a failed test back to the assumption it disconfirms |
| **Break point** | Where that assumption lives — in the *problem*, the *idea*, or the *execution* |
| **Mock Crit** | The app questions the project using its own weak links, before the real crit. A *crit* is design education's standard critique session |

## The five moves — the spine of a demo #key
```
CAPTURE  →  MARK  →  QUESTION  →  COMMIT  →  TRACE
material    sort by   surface the  lock it in   find what
comes in    kind      missing      with its     broke, and
                      question     alternatives  where
```

---

## Founder vocabulary — speak their language #key
Startup aspirants learn Lean Startup and customer discovery. Use their words where they map:

| Their term | Ours |
|---|---|
| Customer discovery | observation vs. inference |
| Riskiest assumption | open assumptions, ranked |
| Problem–solution fit hypothesis | commitment |
| **Pivot or persevere** | trace → break point |
| *Is it already done?* | Landscape Intel |

## Say this, not that #key

| Say | Not | Why |
|---|---|---|
| **prompt / the missing question** | "AI suggestion" | Suggestion implies an answer. We never answer |
| **fading** | "onboarding" | Onboarding ends; fading is the whole arc |
| **commitment** | "final answer" | It is revisable — that's the point of the ledger |
| **unwarranted leap** | "mistake" | It is a normal, necessary move. The fault is leaving it unmarked |
| **reasoning ledger** | "notes app" / "database" | Names the purpose, not the storage |
| **support level** | "difficulty" | Nothing about it is a difficulty setting |
| **alternative** | "other idea" | An alternative is a rival *explanation*, not a rival solution |

> [!important] The one distinction to never blur
> **Observation vs. inference.** Everything else in the product is built on it, and it is the
> thing AI-summarised notes destroy. If a listener leaves understanding only that, the
> explanation worked.
