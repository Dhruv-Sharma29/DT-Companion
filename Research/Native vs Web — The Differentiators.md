---
tags: [key, decision, argument]
---

# ⚔️ Native iPad vs Web — The Real Differentiators

**9 Sep 2026.** The weakest link in the platform argument, answered properly.
Companion to [[Platform Decision — iPad App]].

> [!warning] Verify Apple framework details before presenting — names and availability move.
> #todo #source

## Answer the question the right way #key
A feature list loses this argument. Any list invites *"the web has something like that."*
Ask instead:

> **What would the product no longer be able to promise, if it were a website?**

Four things. Everything else is convenience, and convenience does not justify a platform.

---

## 1. On-device AI — the load-bearing one #key

A web app must send interview material to a server to process it. An iPad app can run a
capable model **on the device** (Apple's Foundation Models framework), so the data never
leaves.

This is not a privacy *feature*. It is a **permission** difference:

> [!important] The strongest argument you have.
> Design research involves real interviews with real named people — sometimes patients,
> children, vulnerable users. If the tool ships that to a server, the consent form gets harder,
> the ethics review gets harder, and students **self-censor what they put in**.
>
> **A tool that cannot hold the real data cannot teach judgement about the real data.** #insight

A sanitised, paraphrased version of an interview is exactly the provenance-stripped text this
whole project exists to fight. On-device processing is what lets the ledger hold the raw thing.

Secondary benefits that follow for free: no inference cost per student, and it works with no
connection.

## 2. Apple Pencil at native latency
Annotation **is** reasoning work — circling the weak link, marking the sentence a claim rests
on, sketching a frame. The web has pointer events; it does not have ~9ms Pencil latency,
pressure, hover, or Scribble. At web latency, annotation feels like a diagram tool. At native
latency, it feels like writing on the evidence.

And handwriting is **slower than typing**, which this product wants — see
[[The Automation Paradox]]. The Pencil supplies deliberate friction without the tool nagging.

## 3. Storage that cannot be silently evicted
The ledger is a **semester-long record**. Browser storage on iOS can be cleared by the OS under
pressure or by tracking-prevention policy — quietly, with no warning.

> A project record that can vanish is not a record. This alone disqualifies a browser-storage
> approach for the one artifact the whole product is built around.

The alternative — a server — puts you back in problem #1.

## 4. Complete offline function
Fieldwork happens in wards, factories, villages, basements. iOS's support for offline web apps
is the weakest of any major platform. A native app just works, fully, with no connection.

---

## 5. Getting material *in* — the share sheet #key
Possibly the most practically important of all, because it attacks the known killer.

Every app on iPad can send content **into** ours: Safari, Photos, Voice Memos, Files, Notes,
Mail, a transcription app. Share → done. A website cannot receive from other apps; it can only
sit there while you export, find the file, and upload it.

> [!important] Capture overhead is what killed IBIS and Compendium
> ([[Terminology & Prior Art]]) and it is our single largest risk. **The share sheet is a
> direct structural answer to it** — three taps instead of a five-step export. Nothing else on
> this list attacks the #1 failure mode so directly. #insight

Same family: **inter-app drag and drop** in Stage Manager — drag a quote from a PDF straight
into a thread — which iPadOS does properly and the browser does not.

## 6. The camera — capturing observations, not clustering them #key

> [!question] Fair challenge: *if we build affinity mapping in the app, why scan a wall?*
> We **don't** build affinity mapping — see the scope note below. But that makes the
> wall-scanning use **secondary and contingent**, and it was wrong to rank it above the
> camera's real job.

### The camera's primary job: an observation *is* often a photograph
The purest provenance-bearing entry is a picture of the thing you saw — the queue, the
handwritten sign, the workaround taped to the machine, the form someone struggled with.
It arrives with time, place and the fact that **you were there**, which is exactly the
signal [[AI Shifted the Bottleneck]] says AI destroys.

A photograph cannot be an AI summary. It is the one kind of entry whose provenance is
self-evident. That is the argument, and it does not depend on any scope decision.

Also in this family: scanning **handwritten field notes**, and photographing documents,
posters and artefacts encountered in the field.

### The secondary job: ingesting a physical affinity wall
Real, but only when three things hold: the team clusters on **paper** rather than in Miro,
they are working in a studio, and they want the grouping carried across. That is a subset of
teams, so treat it as a nice-to-have, not a pillar.

## 7. Background processing
Transcribing an hour of audio, or running the model across forty notes, continues while the app
is closed. A web app stops when the tab does.

## 8. Ambient nudging without notifications
We gave up the in-the-moment push nudge when we chose iPad ([[Platform Decision — iPad App]]).
A **home-screen widget** partially recovers it: *"3 open assumptions"* sitting on the home
screen is a nudge with zero interaction cost, ambient rather than interruptive — which suits
this product better than an alert anyway. No web equivalent.

## 9. The ledger as a document you own
A document-based app puts the record in Files and iCloud Drive: owned, backed up, exportable,
institutionally acceptable. For a semester-long record that matters more than it sounds.

## 10. A bounded room, not a tab
Softer, but honest: the product asks for slow, deliberate thinking, and a browser tab is the
most distraction-dense place ever built — sitting one tab away from the AI that will just
answer the question. An app is a room you enter. Say it once; don't build the case on it.

## What is *not* a differentiator — don't claim these
Say these plainly; volunteering them is what makes the four above credible.

| Claim | Why it fails |
|---|---|
| "Better performance" | Web is fast enough for text and cards |
| "Better UI / feels nicer" | Taste, not an argument. An expert will say so |
| "Push notifications" | Web push exists — and we already dropped the in-the-moment nudge on iPad |
| "Camera and microphone" | The web has both |
| "Offline-ish caching" | PWAs do some of this; the strong claim is *complete* offline, not caching |

## What web genuinely wins #key
- **Distribution** — one link to sixty students, no install, no review queue.
  *Nuance:* in an institution with **managed iPads**, MDM deployment is arguably easier than
  asking sixty students to bookmark a URL. Worth checking for the target department
- **Reach** — Android and Windows students are simply excluded by an iPad app
- **Ship speed** — same-day fixes
- **The instructor's grading view** — genuinely desktop-shaped, and a different user

> The clean resolution: **iPad app for the team's reasoning work, a small web view for the
> instructor.** Different users, different jobs, different platforms — and saying so shows the
> choice was reasoned rather than assumed.

---

## If you only get to say three #key

Ranked by how much the product would actually lose:

| # | Differentiator | Why it ranks here |
|---|---|---|
| **1** | **On-device AI** | A *permission* difference, not a feature. Decides whether the tool may hold real interview data at all — and a tool that can't hold the real data can't teach judgement about it |
| **2** | **Share sheet + drag-drop capture** | Attacks capture overhead, the failure that killed every previous rationale system. The most *practically* decisive item on the list |
| **3** | **Camera capture of observations** | A photograph is the one entry type whose provenance is self-evident and that AI cannot fabricate from nothing. *(Scanning a paper affinity wall is a real but secondary use — see §6.)* |

Then: durable storage, Pencil, offline, background processing, widgets.

> [!important] The pattern worth naming out loud #insight
> Every strong differentiator lives at the **edges** — where the product touches the physical
> world (camera, Pencil, field), the operating system (share sheet, drag, background,
> widgets), or the data's legal status (on-device processing).
>
> **Web loses at the edges and competes fine in the middle.** Since our middle is text on a
> screen, the entire platform argument is an argument about edges — and stating it that way is
> far stronger than reciting a feature list.

## The softer argument, worth one line
A website is a place you go. An app is a thing you have. This product accompanies a
**semester-long** project, not a session — and presence drives the repetition that judgement
needs ([[Why Students Struggle — Causal Factors]] #12). Say it once; don't lean on it.

## And if it is simply the brief #key
If the course requires iOS, say that first and without embarrassment:

> *"Native is the brief. Given that constraint, here is what I exploit that a web build
> could not have: on-device processing of real interview data, Pencil annotation, a record
> that can't be evicted, and complete offline function."*

That is a stronger answer than a manufactured rationalisation, and an expert will respect it.
**Retrofitting product logic onto a constraint is the thing that actually gets punished.**
