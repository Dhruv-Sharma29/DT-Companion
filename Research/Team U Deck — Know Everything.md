---
tags: [key, prep, master]
---

# 🎯 Team U Deck — Know Everything

> [!warning] Deck updated 15 Sep 2026 — my slides are now **3 (User Segment) and 6 (Features)**. See [[My Pitch — User Segment & Features]].

**13 Sep 2026, for the presentation on 14 Sep.** Built from the actual decks:
`Team U.key` (5 slides) and `App Design Workbook.key` (13 slides).
**Your slides: 3 (User Segment) and 4 (Market Opportunity).** You should still know every
slide, because questions can go to anyone.

> [!warning] Before you speak
> CB Insights March 2026 does **not** say "42% no market need". That figure is from the old
> report. The report on your slide says **70% ran out of capital** and **43% had poor
> product-market fit**. See §4.

---

# 1 · The Team U deck, slide by slide

| # | Slide | What it says | Who |
|---|---|---|---|
| 1 | Title | Team U: Akhil Kotnala, Himanshu Butola, Dhruv Sharma, Jatin Kukkar | — |
| 2 | **Problem Statement** | *"AI gives every founder the same answer."* Student startup aspirants commit to the first problem that sounds right, often one that's already crowded, instead of the differentiated one their evidence supports. In a startup, the wrong problem is fatal. *Source: CB Insights, 431 post-mortems, March 2026* | teammate |
| 3 | **User Segment** | *"Students who intend to build."* Primary: student startup aspirants · Secondary: mentors, advisors, faculty · Buyer/channel: college incubators & E-cells | **you** |
| 4 | **Market Opportunity** | *"Ideas got cheap. Judgement didn't."* 3rd largest ecosystem · 2 lakh+ DPIIT startups (Dec 2025) · ~50% from Tier II/III, where mentors are scarce | **you** |
| 5 | **Sources** | CB Insights · PIB "Nine Years of Startup India" (15 Jan 2025) · PIB "A Decade of Startup India" (15 Jan 2026) · Team U Journal | — |

## The workbook: the thinking behind the deck
The workbook is titled **"Procedural Scaffolding"** (Cohort 2, iOSDC GEU). That's the name of
the concept: support that tells you **which step comes next** and withdraws as you get
better. It follows Apple's App Design Cycle: Define → Prototype → Test → Validate → Iterate.
The team has completed the **Define** stage (Discover + Analyze).

| Workbook slide | What the team wrote |
|---|---|
| **Observe** | The questions founders ask most: *has someone already built this? is it real? what makes ours different?* After a week of interviews and AI-summarised notes, **we couldn't tell what people said from what the model concluded**, so we picked what sounded best. **Workaround:** ChatGPT + Notion + Miro, screenshotting between them. ChatGPT gives every team the same answer, and the Miro board is dead once the workshop ends. |
| **Explore Your Users** (persona) | A college student startup aspirant, **age 20**, who sees themselves as a builder or future founder. Works in campus incubators, co-working spaces, design labs and at interview sites, **often in tier 2–3 cities with limited mentor access**. Wants a *mentor-like guide that stress-tests reasoning, checks assumptions against evidence, and makes sure they build something differentiated*. Uses it after interviews, when turning observations into a problem statement, or when preparing for an incubator crit. |
| **Summarize Your Audience** | Main concern: the problem must be **real, differentiated, and based on direct evidence**. Age **18–25**. Environment: incubators, design studios, maker spaces, interview sites. Limits: **poor connectivity, strict privacy during interviews, little desk space**. Design needs: **share-sheet capture, on-device privacy, questions instead of answers, offline use**. |
| **Analyze Causes** (5 whys) | Students **jump to a solution** → because their **research is scattered** → because they **don't follow a structured process** → because they **rely on AI to define the problem** → **core problem: AI gives generic answers, so the problem isn't validated or based on their own evidence.** Solution: *guide users through a structured DT process with nudges, without giving them direct answers.* |
| **Research Competitors** | **Miro** (visual brainstorming) · **Dovetail** (research repository) · **Jira** (task tracking) · **Sprintbase** (guided DT sprints) · **Notion** (all-in-one, can feel overwhelming) · **IDEO Design Kit** (methods, but you apply them alone) |
| **Leverage Capabilities** | **Speech recognition + microphone** to capture interviews · **on-device machine learning**, so evidence never leaves the iPad · **camera** for field material · **drag and drop** to attach evidence to a claim · **notifications** for assumptions still untested |

---

# 2 · Your slide 3 — User Segment

## What to say (≈45 seconds)
> Our users are **students who intend to build**. We don't define them by degree; we define
> them by intent. That covers an engineering student with a startup idea, an MBA student on a
> venture track, and E-Cell members.
>
> **Primary users are student startup aspirants.** For them, picking the wrong problem doesn't
> cost a grade, it costs the startup. They already ask three questions: *is my problem real,
> has someone taken it, and what makes it mine?*
>
> **Secondary users are mentors, advisors and faculty.** Right now they see the pitch, but not
> the reasoning behind it.
>
> **Our buyers and channel are college incubators and E-Cells.** They want better-validated
> founders coming through, and they already have access to our users.

## Why each group is there
| Group | Their pain | What they get |
|---|---|---|
| **Student aspirants** | Can't tell whether the problem is real, taken, or theirs; AI gives everyone the same answers | A record of what their conclusions rest on, and the questions they didn't ask |
| **Mentors / faculty** | See the pitch, not the reasoning; catch wrong turns too late | See why a founder believes the problem is real |
| **Incubators / E-Cells** | Too many under-validated applicants; limited mentor time | Founders who arrive with evidence; mentor time goes further |

## Persona to mention if asked
Age 20, a builder, working in a campus incubator, often in a tier 2–3 city with little access to
mentors. Uses the app right after interviews and before a crit.

## Questions on your slide

**"Why not all students?"**
Students without a startup intent have no stake in whether the problem is right. For founders,
the wrong problem is fatal, so they care most.

**"Why engineers in particular?"**
Engineering trains you to solve the problem you're given. A founder has to choose the problem,
and engineers tend to jump straight to building. The workbook's root cause is exactly that:
*jumping to a solution*.

**"Isn't the buyer the same as the user?"**
No, and that's deliberate. Students rarely pay. Incubators and E-Cells have budgets, have
direct access to students, and benefit from better-validated founders.

**"Why would an incubator pay?"**
Mentor time is limited, and a founder who arrives with a reasoning record needs less of it.
*Honest limit:* we haven't tested willingness to pay yet.

**"What about solo founders?"**
The core (evidence marking, questions, competitor search, mock crit) works for one person.
Only the team-comparison feature needs a team.

**"How many users are there?"**
GUESSS India 2023 found **32.5% of Indian college students are already nascent entrepreneurs**,
above the global average of 25.7% (~14,000 students surveyed). That's the size of the intent.
*We haven't built a full market-size estimate yet.*

**"Did you talk to real users?"**
Be honest about what the team did. The workbook's *Observe* slide is based on **the team's own
experience** of running this process. **Check with the team tonight whether the persona quote
came from a real interview**, and say exactly that. Don't claim interviews that didn't happen.

---

# 3 · Your slide 4 — Market Opportunity

## What to say (≈45 seconds)
> *Ideas got cheap. Judgement didn't.*
>
> India is the **world's third-largest startup ecosystem**. It went from about 500 recognised
> startups in 2016 to **over 2 lakh by December 2025**.
>
> And it isn't just the metros: **around half of those startups now come from Tier II and
> Tier III cities**, where experienced mentors are scarce.
>
> So more founders than ever are starting out, most of them far from the mentors who would
> normally ask: *is this problem real?* That's the gap we're building for.

## Every number, where it comes from, and exactly what the source says

| Slide claim | Source | Exact wording in source | Status |
|---|---|---|---|
| **3rd largest** | PIB *Nine Years of Startup India*, 15 Jan 2025 | *"With more than 1.59 lakh startups recognised by DPIIT as of January 15, 2025, India has firmly established itself as the third-largest startup ecosystem in the world."* | ✅ |
| **2 lakh+ (Dec 2025)** | PIB *A Decade of Startup India*, 15 Jan 2026 | *"With over 2 lakh DPIIT-recognised startups as of December 2025…"* | ✅ |
| **~50% Tier II & III** | same, 15 Jan 2026 | *"Around 50% of DPIIT-recognised startups originate from Tier-II and Tier-III cities"* | ✅ |
| **"where mentors are scarce"** | **Not in the PIB document.** Supported by *India Incubator Kaleidoscope 2024* (IIT Madras CREST & IIM Bangalore NSRCEL) | India has **~0.8 incubators per million people** (US/UK/China: 8–10); **48% of incubators are in Tier-I cities** | ✅, but **cite this report if asked**, not PIB |

> [!important] Know this detail
> The **2026** PIB document says India is *"one of the world's largest"* startup ecosystems.
> The explicit **"third-largest"** wording comes from the **2025** document. Your slide cites
> both, so it's correct. Just know which document says what.

## Extra verified figures you can say out loud (not on the slide)
- **Growth:** ~500 recognised startups in 2016 → 1.59 lakh (Jan 2025) → 2 lakh+ (Dec 2025). *(PIB 2025 and 2026)*
- **Student intent:** 32.5% of college students are nascent entrepreneurs. *(GUESSS India 2023)*
- **Incubator gap:** 0.8 incubators per million people vs 8–10 in the US, UK and China; 48% in Tier-I cities. *(Incubator Kaleidoscope 2024)*
- **Channel size:** 1,100+ active incubators *(Kaleidoscope 2024)*; MeitY Startup Hub supports **517+ incubators**, and Startup India Seed Fund money went to **215+ incubators** *(PIB 2026)*.
- **Future founders:** 10,000+ Atal Tinkering Labs across 733 districts, engaging **1.1 crore+ students**. *(PIB 2026)*
- **Women founders:** 45%+ of recognised startups have at least one woman director or partner. *(PIB 2026)*

## Questions on your slide

**"2 lakh startups isn't your market. Your users are students."** ⚠️ *most likely hard question*
Correct. The 2 lakh figure shows **where our users are heading** and how fast that route is
growing. Our **users** are the students before that point, and 32.5% of college students already
show startup intent (GUESSS). Our **buyers** are the incubators in between: 1,100+ of them.

**"Where's the source for 'mentors are scarce'?"**
The India Incubator Kaleidoscope 2024 from IIT Madras and IIM Bangalore. India has about 0.8
incubators per million people versus 8–10 in the US, UK and China, and 48% of incubators are in
Tier-I cities, while about half of startups come from Tier II/III.

**"What's your TAM / SAM / SOM?"**
*Don't make one up.* "We haven't built a rigorous estimate yet. The addressable users are college
students with startup intent, and the reachable channel is the 1,100+ incubators. Sizing it
properly is our next step."

**"Why is 'ideas got cheap, judgement didn't' true?"**
AI made generating ideas and research nearly free, and it gives everyone similar outputs. Deciding
which problem is real still depends on your own evidence and reasoning, and AI can't do that for
you.

**"Is this opportunity India-only?"**
We're starting with India because that's where the evidence is. The problem, AI giving everyone
the same answer, applies to founders everywhere.

**"Aren't there already enough government programmes and incubators?"**
They provide funding and space. What's scarce is **mentor time spent questioning a founder's
reasoning**, and incubator density is about a tenth of the US's. We add to incubators; we don't
replace them.

---

# 4 · Slide 2 — the CB Insights correction

The report cited on slide 2 is **CB Insights, *Why Startups Fail*, 5 March 2026**: 431 VC-backed
companies that shut down after 2023, having raised **$17.5 billion** between them.

| Rank | Reason | % |
|---|---|---|
| 1 | Ran out of capital | **70%** |
| 2 | **Poor product-market fit** | **43%** |
| 3 | Bad timing / macro conditions | 29% |
| 4 | Unsustainable unit economics | 19% |

**If someone says "running out of money is the top reason, not the wrong problem":**
> CB Insights makes that point itself: running out of capital is almost always the **final**
> cause, not the root one. Companies without product-market fit don't earn revenue, so they run
> out of money. **43% failed on poor product-market fit**, and building for the wrong problem is
> what causes that.

**Don't say "42% no market need"**, since that's the old report and the slide cites the new one.

---

# 5 · Everything else you should know

**The product in one line:** an iPad app that uses procedural scaffolding to guide student
founders from research to a validated problem. It marks evidence versus assumption, asks the
question they skipped, and never hands them the answer.

**Why iPad:** the workbook's reasons are on-device machine learning (privacy during interviews),
offline use, speech capture of interviews, camera, and drag and drop. A reasoning chain also needs
enough screen to be seen as a whole.

**Why not ChatGPT:** it returns the most probable answer, so every team gets the same one. What's
unique is in the founder's own evidence.

**How it's different from each competitor:**
| Competitor | They do | They don't |
|---|---|---|
| Miro | Visual brainstorming | Remember why you decided; the board dies after the workshop |
| Dovetail | Store and tag research | Serve beginners; it assumes you already know how to synthesise |
| Jira | Track tasks | Track what you believe and why |
| Sprintbase | Guide DT workshops | Check your conclusions against your evidence |
| Notion | Hold everything | Tell you a claim has no evidence; can feel overwhelming |
| IDEO Design Kit | Teach methods | Stay with you while you work; you apply them alone |

**Main risks:** no primary user interviews yet; willingness to pay untested; the effort of adding
material has killed similar tools before; iPad ownership among student founders not checked.

**Check with the team tonight**
- [ ] Who presents which slide, and what the hand-off line is
- [ ] Did anyone actually interview users? What does the Team U Journal contain?
- [ ] Everyone uses **43% poor product-market fit**, not 42%
- [ ] Agree on one answer to "who pays"
