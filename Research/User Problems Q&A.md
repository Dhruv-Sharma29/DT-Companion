---
tags: [key, prep, qa]
---

# ❓ User Problems — Q&A

**24 Sep 2026.** Straight from the current deck (`Team U .key` + `App Design Workbook.key`).
Use with [[Team U Deck — Know Everything]] and [[My Pitch — User Segment & Features]].

---

## Q: What problems does the user face?

**A (one line):** They have information, but no way to tell what's evidence versus assumption,
no record of their reasoning, and no one checking their thinking before it's too late.

**A (full list):**

1. **Can't tell what they learned from what they assumed.**
   After interviews and AI-summarised notes, *"we could not tell which parts were things people
   actually said and which were conclusions the model drew for us."* Every idea looks equally
   well-argued, so they pick whichever sounds best.

2. **Research is scattered across disconnected tools.**
   *"We run the whole process across ChatGPT, Notion and Miro, screenshotting between them
   because none of them connect."*

3. **They jump to a solution before validating the problem.**
   The root-cause chain: jump to a solution ← scattered research ← no structured process ←
   rely on AI to define the problem ← AI gives generic answers not grounded in their own evidence.

4. **AI gives them the same answer as every other team.**
   *"ChatGPT gives us the same answer it gives every other team."* Their problem framing ends up
   looking like everyone else's.

5. **No record of why a decision was made.**
   *"The Miro board is dead the moment the workshop ends — so when a prototype fails, nobody can
   say why we chose that problem in the first place."*

6. **Limited access to experienced mentors**, especially in tier 2–3 cities — no one to
   regularly stress-test their reasoning.

7. **Can't prove the problem is real when it matters** — to themselves, or to a mentor or
   investor asking *"how do you know this is real?"*

8. **Environmental constraints compound it:** poor/offline connectivity, privacy concerns during
   interviews, limited desk space.

---

## Follow-up questions to expect, with answers

**Q: Which of these is the core one — the root cause?**
A: #1, not being able to separate what they observed from what they assumed. Everything else
either causes it (#2 scattered research, #6 no mentors) or follows from it (#3, #4, #5, #7).

**Q: Isn't #2 just "they need better tools" — a Notion problem?**
A: No. Notion would fix storage, not judgement. The real issue is #1 — even with everything in
one place, they still can't tell a real finding from a guess. Scattered tools make it worse, but
organising them wouldn't fix the underlying problem.

**Q: Is #4 (AI gives generic answers) really a problem, or just how AI works?**
A: It's a problem because they don't *notice* it's generic. They treat AI output as if it came
from their own research, so it replaces their evidence instead of supporting it.

**Q: How do you know these are real problems and not assumptions your own team is making?**
A: Right now this is the team's own experience, documented in the workbook's Observe and Analyze
Causes exercises — not yet validated with outside interviews. See [[User Interview Guide]] for
how we'd confirm it with real student founders. *(Say this plainly if asked — it's honest and it
shows the next step.)*

**Q: Do all founders face all eight problems, or different ones at different times?**
A: They cluster in two moments: **while researching** (#2, #6, #8 — data is scattered, no
mentor, no working conditions) and **while deciding** (#1, #3, #4, #5, #7 — can't tell evidence
from assumption, so the decision and the record of it are both weak).

**Q: Which problem does each feature solve?**

| Feature | Solves |
|---|---|
| Capture (saw it / guessed it) | #1, #4 |
| AI Nudge | #1, #3 |
| Log book | #5, #7 |
| Project portfolio | #7 |
| Offline, on-device | #6, #8 |

**Q: What's the single biggest pain point?**
A: #5 — no record of why a decision was made. It's what makes every other problem costly: even
if a team eventually realises they built on an assumption, they can't trace back to fix it.

**Q: Give one concrete example.**
A: Students say *"I can never find a seat in the library during exams."* The team writes *"so
the college needs more study spaces."* Nobody checks whether it's true the rest of the year —
that's #1 and #3 in one moment.
