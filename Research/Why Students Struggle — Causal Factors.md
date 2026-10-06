---
tags: [key, problem, analysis]
---

# 🔍 Why Students Struggle With Sensemaking — Causal Factors

Root-cause pass on [[Problem Definition]]. **8 Sep 2026**

## First, separate the types of cause #key
The candidate causes are not the same kind of thing, and mixing them is why the problem
feels slippery. Borrowing the clinical **predisposing / precipitating / perpetuating** frame:

```
PREDISPOSING          what was already true before AI
   (novice, no method, no baseline, ambiguity aversion)
        ↓
PRECIPITATING         what AI changed
   (offloading, volume, fluency illusion, lost provenance)
        ↓
PERPETUATING          what stops them recovering
   (graded on artifact, no outcome feedback, team consensus)
        ↓
        SYMPTOM: commits to the first plausible reading
```

> [!important] "Low critical thinking" is the **symptom**, not a cause.
> Naming it as the cause is circular — *they think badly because they think badly* —
> and it gives you nothing to design against. Everything below is upstream of it.

---

## The factors

### A — They don't know *how* (procedural)

**1. The synthesis stage has no methods.** #key
Look at what Design Thinking actually teaches per stage:

| Stage | Methods taught | Count |
|---|---|---|
| Empathize | interviews, shadowing, diary studies, probes | many |
| Ideate | Crazy 8s, SCAMPER, brainwriting, analogies | many |
| Prototype | paper, Wizard-of-Oz, wireframes | many |
| **Define / synthesise** | *"write a POV statement"* | **a template, not a method** |

Define is taught as an **output to produce**, not a **procedure to follow**. That is a real
hole in the curriculum, and it sits exactly where the pain is. Strongest single factor to
build on — it is specific, checkable, and nobody owns it. #insight

**2. No domain baseline.** #key
You can only notice an anomaly against a norm. A student who has spent three days in a
hospital ward does not know what *normal* looks like there, so nothing stands out as
significant. Expertise is largely a stored library of patterns to match against — which is
why "what matters here?" is genuinely unanswerable for a novice, not just hard.
This is the honest limit on how much any tool can help. #question

### B — They know but can't (capability & affect)

**3. Ambiguity is aversive, and closing early relieves it.** #insight
Synthesis means holding 40 unconnected observations *without resolving them*. That is
uncomfortable. Premature convergence is best understood as **anxiety management, not a
reasoning error** — which matters enormously: if it is emotional, teaching the method will
not fix it. The intervention has to make staying open feel safe and finite.

**4. Working memory.** You cannot see a pattern across items you cannot hold at once.
Affinity walls and sticky notes exist to offload exactly this. AI raises the item count
while the notes stay trapped in a scrolling document — strictly worse than paper. #insight

### C — They can't tell how they're doing (metacognitive)

**5. No standard for "good."** Without a picture of what a strong insight looks like,
any insight feels finished. They cannot self-assess, so they cannot self-correct.
This is the **awareness** half of the question — see the verdict below.

### D — AI-specific (precipitating) → [[AI Shifted the Bottleneck]]

**6. Cognitive offloading.** The stated cause. Real, but see the caution below.
**7. Fluency illusion.** Well-formed prose produces the *feeling* of understanding without
the work of it. AI output reads like an insight, so it is accepted as one.
**8. Anchoring.** A coherent answer arriving first shuts down the search for a better one.

### E — The environment rewards the failure (perpetuating) #key

**9. They are graded on the artifact, not the reasoning.**
==A polished wrong answer scores better than a well-reasoned uncertain one==. The incentive
**actively rewards** premature convergence. No tool defeats an incentive.

**10. Deadlines force convergence.** A semester ends whether the insight is earned or not.

**11. Team consensus is mistaken for validity.** Groups settle on the loudest or
highest-status member's reading, and disagreeing is socially expensive — so the divergence
that would have improved the interpretation is suppressed.

**12. No outcome feedback.** #insight
Projects end at the prototype. Students almost never learn whether their interpretation was
*right*. **Judgement cannot develop in an environment that never reveals the answer** —
this is the deepest structural cause, and it explains why the deficit persists across an
entire degree.

---

## Verdict: knowledge, or awareness, or both? #key

Neither alone — and the either/or framing mislocates the fix. They bind **in sequence**:

```
Stage 1  AWARENESS is binding    "I don't know that my insight is weak"
Stage 2  KNOWLEDGE is binding    "I know it's weak, but not how to make it strong"
Stage 3  STRUCTURE is binding    "I know how, but nothing rewards me for doing it"
```

A student with the method *and* the awareness still fails at stage 3, because of #3, #9 and
#12. So a product that only delivers **knowledge** — a method, a template, a checklist —
solves the least binding constraint. Start at awareness. #insight

---

## Which factors can a product actually move?

| Factor | Tractable? |
|---|---|
| #5 awareness of quality | **High** — make the gap visible; this is the wedge |
| #4 working memory / externalisation | **High** — a solved interface problem |
| #11 team disagreement | **High** — surface divergence before consensus forms |
| #1 missing method | **Medium** — teachable, but see [[The Automation Paradox]] |
| #12 feedback loop | **Medium** — simulate consequences, can't provide real ones |
| #3 ambiguity tolerance | **Low–medium** — scaffolding helps, disposition is slow |
| #2 domain expertise | **Low** — takes years |
| #9 assessment structure | **None** — institutional, outside the product |

Design for the top three. Do not pretend to fix the bottom two.

---

## Caution on the "AI killed critical thinking" framing #question
Of the four candidates, **over-use of tech** is the weakest to build the pitch on:
- Hardest to prove — the evidence is correlational and contested.
- It positions the product as **scolding the user**, which students reject.
- It is also unfalsifiable as stated, which makes it look like an opinion in a review.

"They lack a method and any signal of quality" is stronger: provable, specific, and it
blames the **process**, not the person. Same product, defensible pitch. #key
