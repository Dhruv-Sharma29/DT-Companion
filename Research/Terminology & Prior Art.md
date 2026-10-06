---
tags: [key, reference, source]
---

# 📚 Terminology & Prior Art

**8 Sep 2026** — the vocabulary for this project. Using the field's existing names makes the
work defensible; inventing names makes it look naive.

> [!warning] Cited from memory — verify before putting any of this in a submission. #todo #source

## The area itself
- **Sensemaking** — Weick (organisational); Pirolli & Card (the *sensemaking loop* from
  intelligence analysis, the closest formal model to what you're describing).
- **Design synthesis** — Jon Kolko, *Exposing the Magic of Design*. The DT-specific term, and
  the single most on-target reference for this project.
- **Abductive reasoning** — Peirce. Inference to the *best explanation*. This is literally
  "which reading of the evidence deserves belief," i.e. your problem, formally named. #key
- **Framing / frame creation** — Kees Dorst, *Frame Innovation*.
- **Problem setting** (vs. problem solving) and **reflection-in-action** — Donald Schön,
  *The Reflective Practitioner*.
- **Wicked problems** — Rittel & Webber; Buchanan applied it to design.

## The three problems you named, in field vocabulary #key

| Your words | The field's name | The failure |
|---|---|---|
| approach of dealing with the problem | **problem framing / problem setting** | solving the wrong problem; jumping to solution |
| the sequence | **process orchestration / procedural scaffolding** | treating the double diamond as linear; not knowing what's next |
| adaptiveness / iteration | **reflection-in-action** | after a failed test: change the problem, the idea, or the execution? |

All three are **metacognitive**, not domain questions — ==*what am I working on / where am I /
what changes now==.* That's the unifying spine, and it's the strongest argument that these
three belong in one product. #insight

## Prior art for what you want to build

- **Design rationale** — the HCI/CS field on capturing *why* a decision was made. Closest
  existing category to your idea. #key
- **IBIS** (Issue-Based Information System) — Rittel again; **dialogue mapping** (Conklin);
  the Compendium tool. Structure: Issue → Position → Argument. Proven, and it fails in
  known ways worth reading about (capture overhead kills adoption). #key
- **ADRs — Architecture Decision Records** — software engineering's lightweight, *adopted*
  version of the same idea: context, decision, alternatives, consequences, one page.
  The direct analogue is a **Design Decision Record**. Steal this format. #insight
- **Toulmin's model of argument** — claim, data, warrant, backing, qualifier, rebuttal.
  The rigorous scaffold for "what evidence supports this interpretation," and teachable
  in ten minutes. Strong candidate for the core interaction. #key
- **Lab notebook / logbook** — the oldest version, and the cultural precedent for
  "you record as you go because the record *is* the practice."

## Naming your thing

| Candidate | Reads as | Verdict |
|---|---|---|
| Playbook | prescribed plays for known situations | wrong for wicked problems |
| Companion / co-pilot | AI assistant | overused, and invites [[The Automation Paradox]] |
| Design **decision record** | ADR for design | accurate, inherits proven prior art |
| **Reasoning ledger** | running account of what you believe and why | plain, memorable, honest |
| Design rationale system | the academic category | correct but dry |
| Living design log | a record kept while working | good plain-language fallback |

**Recommendation:** call the artefact a **reasoning ledger** (or *design decision record*)
and the category **metacognitive scaffolding for design practice** — see
[[Where DT Is Used & The Niche]]. "Ledger" carries the right connotations: entries are dated,
appended not overwritten, and every claim is accountable to something.

## Paper before software #key
A playbook is testable **this week**, on paper, with three teams, for nothing. Software is
months. And nothing in [[Open Questions]] is answered yet.

> [!important] The playbook is not a lesser version of the software — it is the experiment
> that tells you whether the software deserves to exist. If the paper version doesn't change
> what teams decide, code won't either.

When it does become software it is a **native iPad app** — decided, with reasoning, in
[[Platform Decision — iPad App]].
