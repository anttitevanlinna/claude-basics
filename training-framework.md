# Training Framework: Claude Basics (TENTATIVE)

Pre-work → 3 x 45-minute modules → Post-work. An agentic training — participants learn Claude BY using Claude, and Claude handles everything that doesn't need a room full of humans.

The facilitator is only needed for the peak: the part where people need to be together, comparing approaches, debriefing failures, making collective decisions. Everything individual and async, Claude handles.

Adapted from agents-102 pedagogy (TBR 4Cs + Bloom's Taxonomy).

---

## Fundamental Questions

### C: "Can you be the person your org trusts to run this?"

Identity question, not skills. Trust = you can use it (Module 1) + you know where it breaks and what the rules are (Module 2) + you have a plan (Module 3).

### D: "Where is this all going?"

The accelerant. Surfaces when they see the trajectory — not lectured, discovered. By Module 3 they're already living the answer: using the tool to plan its own deployment.

C without D = competent but obsolete in six months. D without C = excited but not trusted. Together = the person every org needs.

---

## The Agentic Training Principle

Every participant has Cowork open. Claude is not just the subject — it's a co-participant in the learning. The facilitator is a guide, not a teacher. Cowork does the teaching. The facilitator names what just happened.

This means:
- **No explaining, then trying.** Trying, then understanding.
- **No staged demos.** Everything is live, in their Cowork, on their system.
- **No disposable exercises.** One continuous system that matures across all three modules.
- **The training IS the demo.** If anyone asks "what does good Claude usage look like?" — point at what just happened in this room.

---

## The Continuous Artifact

The throughline is the system each participant builds — and specifically, the CLAUDE.md that matures across the training.

### Two types of CLAUDE.md

**Personal CLAUDE.md** — who you are, how you work, your preferences. Lives with you, travels with you. Built in pre-work.

**Folder CLAUDE.md** — what this task is, what standards apply, what the guardrails are. Lives with the project, travels with the work. Built and hardened across Modules 1 and 2.

The distinction matters: personal shapes how Claude talks to *you*. Folder shapes how Claude does *this work*. Teams share folder CLAUDE.md files. Personal stays personal.

### How the system matures

| Phase | System | CLAUDE.md |
|-------|--------|-----------|
| Pre-work | Morning planner — first personal system | Personal CLAUDE.md — role, preferences, standards |
| Module 1 | Buyer's task — first team system | Folder CLAUDE.md created — task context, guardrails, quality standards |
| Module 2 | Same system, stress-tested and hardened | Same folder CLAUDE.md, hardened — verification instructions, data rules, hallucination prevention added |
| Module 3 | New team workspace — rollout recommendation | New folder CLAUDE.md per group — they know how to set one up now |

They walk out with three things: a personal CLAUDE.md they'll use forever, a hardened folder CLAUDE.md from Modules 1-2 that demonstrates what a mature project setup looks like, and a fresh team CLAUDE.md from Module 3 that they set up from scratch in minutes — proof they've internalised the pattern.

---

## The Shared Workspace

### Technical setup

Buyer (IT Director) creates a SharePoint folder before the session. Everyone syncs. Structure:

```
/claude-basics-training/
  /participants/
    /firstname-lastname/     ← personal folder, Cowork working directory
    /firstname-lastname/
    ...
  /groups/
    /group-1/                ← group folder for Module 3
    /group-2/
    /group-3/
    /group-4/
  /synthesis/                ← buyer's synthesizer folder
```

Each participant sets their personal folder as Cowork's working directory. Most exercises start there. Module 3 adds the group folders. The buyer's synthesis folder is where the final deliverable lands.

This is SharePoint — the IT team already knows how to sync it. No new tools, no Git, no friction. Part of the pre-work setup.

### What this unlocks

- **Live comparison.** Agents peek into each other's personal folders. "Look at how your neighbour set their guardrails differently." Not screenshots — their actual files.
- **Collective intelligence.** The best guardrail idea from one participant becomes everyone's.
- **Module 3 multi-agent exercise.** Personal agents write to personal folders, group synthesizer reads across them, buyer's synthesizer reads across groups. The folder structure IS the multi-agent architecture.
- **Post-training legacy.** The SharePoint folder survives the training. Monday morning: 14 systems, 4 group recommendations, 1 rollout plan — all in a shared space the team already uses.
- **The org pattern.** Sharing Claude context via SharePoint is exactly how teams should work with Claude. They learn the pattern by living it.

---

## The Full Arc

**Make → Verify → Look ahead**

```
Pre-work (async, optional, Claude-led)
  Get set up. Build your first personal system. Write your CLAUDE.md.

    → Module 1: Make something (45 min)
    → Module 2: Ensure it's the right thing (45 min)
    → Break: buyer tests ground truth (15 min)
    → Module 3: Look ahead (45 min)
         ↳ the launchpad — they accidentally build a multi-agent system

Post-work (async)
  Buyer measures adoption. Claude keeps the learning alive.
```

| Phase | Duration | Bloom's | Mode |
|-------|----------|---------|------|
| Pre-work (optional) | ~30-60 min async | Remember → Apply | Individual, Claude-led |
| Module 1: Stop chatting — build a system | 45 min | Apply | Facilitated, in room |
| Module 2: Can you be trusted to run this? | 45 min | Apply → Evaluate | Facilitated, in room |
| Break | 15 min | — | — |
| Module 3: Where is this all going? | 45 min | Evaluate | Facilitated, in room |
| Post-work | Ongoing async | Apply → Analyze | Individual, Claude-led |

---

## Pre-work: "Get to know Claude" (async, Claude-led, optional)

Nice-to-have, not load-bearing. If participants do it, they arrive warmed up. If they skip it, Module 1 still works — as long as Cowork is set up and accessible, the exercise succeeds regardless.

### Pre-work checklist

**Setup (5 min):**
- Account works. Cowork opens. Shared workspace connected.
- O365 and Jira connectors enabled. These are the working environment, not optional integrations.

**Optional: Claude chat tour (15 min):**
- Guided tour of Claude chat features. For participants who haven't used Claude before or want a refresher.
- Skip if you've been chatting with LLMs for two years. No one will check.

**Mandatory: Cowork tour (15 min):**
- Guided tour of Cowork features. What it is, how it differs from chat, how files and connectors work.
- Everyone does this — even experienced Claude users. Cowork is new territory.

**"My morning planner" (20 min):**
- Build an O365 calendar agent that plans your every morning. First personal system. 
- A real, useful thing they keep forever. The pre-work has its own WOW moment.

**"My Claude, my rules" (10 min):**
- Write a CLAUDE.md for yourself. Your role, your preferences, your standards.
- Notice how responses change. This is the first taste of guardrails — before anyone calls them that.

**"Bring a question":**
- One genuine concern about Claude in your org. Write it down. Seeds Module 1's C1.

**Total: ~50 min mandatory, ~65 min with optional chat tour.**

### What this unlocks (when it happens)
- **Module 1 isn't their first system.** They've already built the morning planner. Module 1 is their second system — on a team task, not a personal one.
- **Facilitator signal.** Who did the pre-work, what questions they're bringing.
- **The training starts early.** Pre-work delivered by Claude — meta from minute zero.

### If they skip it
Module 1 is designed to work cold. As long as Cowork opens and connectors are enabled, the exercise succeeds. Participants who did pre-work move faster; participants who didn't still arrive at the same destination.

### Learning goals

| # | Learning goal | Bloom's level |
|---|--------------|---------------|
| P1 | **Navigate** Claude's product landscape — chat, Cowork, Claude Code, API — and explain which tool fits which use case | Understand |
| P2 | **Use** Cowork to complete a guided task with files and connectors | Apply |
| P3 | **Build** a personal O365 calendar agent that plans their morning | Apply |
| P4 | **Write** a personal CLAUDE.md that shapes how Claude interacts with them | Apply |
| P5 | **Connect** O365 and Jira as working data sources in Cowork | Apply |

**Plug point:** Pre-work content and connectors adapt per client. O365 assumed for most enterprise clients. Jira or equivalent project management tool as second connector.

---

## Post-work: "Measure and keep building" (async)

Two tracks: measurement (buyer-led) and continued learning (Claude-led).

### Track 1: Adoption measurement (buyer-led)

The buyer (IT Director) owns this. Simple before/after self-assessment + usage tracking.

**Week 1:** Buyer sends a short self-assessment to all participants via Claude: "Rate your confidence on: using Cowork for real tasks, spotting hallucinations, explaining Claude to a colleague, knowing when NOT to use Claude." Baseline captured during pre-work, repeated now.

**Week 4:** Same assessment. Plus: "How many times did you use your system this month? What did you improve? What broke?"

**Week 12:** Final check. "Is your team using Claude? Are others asking you for help?" — the question C signal.

The buyer synthesizes the results — their agent reads all responses, produces an adoption report. Not a training evaluation form — an actual measurement of whether the rollout is working. The buyer owns the data, the insight, and the next decision.

**Optional add-on:** Facilitator (Bosser) runs the measurement program as a paid service — designing the assessments, analysing trends across the team, recommending adjustments. The buyer can do it alone; the service makes it sharper.

### Track 2: Continued learning (Claude-led)

- **Check in on the system.** "You built a system for incident triage. How's it going? What broke this week?"
- **Answer questions that surface later.** Week 2 questions are the best ones — they come from real usage.
- **Post-training resources.** Participants leave with pointers to Anthropic's documentation, prompt engineering guide, and Claude cookbook for continued self-study.

### Bloom's level
Apply → Analyze. They apply what they learned on real work. They analyze what's working. This is where the training's impact compounds — not in the room, but in the weeks after.

---

## Module 1: "Stop chatting — build a system" (45 min)
*Make something.*

### Big idea
Chat resets. A system remembers. You're about to feel the difference.

### Learning goals

| # | Learning goal | Bloom's level |
|---|--------------|---------------|
| M1.1 | **Build** a working system in Cowork using files, not just conversation | Apply |
| M1.2 | **Create** guardrails that shape Claude's output to match team standards | Apply |
| M1.3 | **Write** a folder CLAUDE.md that gives Claude persistent context about a task | Apply |
| M1.4 | **Share** a system with colleagues via a shared workspace (SharePoint) | Apply |
| M1.5 | **Distinguish** between ephemeral chat and a persistent system that improves over time | Understand |
| M1.6 | **Explain** how a system learns by feeding it better context — data, documents, examples | Understand |

### C1 opener (~3 min)
*"What's a task you keep re-explaining to Claude every time you start a new conversation?"*

### Hero exercise: "Build it for real" (~30 min)
**Format: Personal.** 14 people, same task, 14 different systems. Ownership matters — "my system" is more powerful than "our system."

The buyer (IT Director) pre-selects one real task the IT team does regularly — something everyone has touched. Everyone builds the same system in Cowork: files, CLAUDE.md, guardrails. Same task, 14 different approaches.

Midway checkpoint: systems synced to shared workspace. Participants glance at each other's guardrails. No formal review yet — just awareness that others are solving it differently.

**Plug point:** The case is the main client-specific variable per client.

### C4 conclusion: "How to make your system learn?" (~10 min)
Pairs compare via shared workspace: "What did your neighbour do that you wouldn't have thought of?"

Return to C1: "You said you keep re-explaining X. Does your system solve that?"

Then the facilitator closes with a short concept lecture: **"How to make your system learn?"** This is the one place Module 1 earns a teaching moment — after they've built the system, not before. Covers:
- Your system improves by feeding it better context — data, documents, examples
- But what data? Not everything belongs in Claude. Security, privacy, data classification.
- Your guardrails are the control layer. The system learns what you let it learn.

This bridges naturally to Module 2: the question of trust. You've built something that works. You've seen how to make it learn. But can you trust what it produces? Can you trust what goes in?

**Handoff to Module 2:** "You've got a system that works. Now let's find out if you can trust it."

### Bloom's note
Apply across the board. Build first, understand later. Vocabulary arrives late — they've already created guardrails before anyone calls them that. The closing lecture earns its place because it follows the experience.

---

## Module 2: "Can you be trusted to run this?" (45 min)
*Ensure it's the right thing.*

### Big idea
Control and detection — that's what trust is built on. Knowing where it breaks is more valuable than knowing where it shines.

### Subquestions
- *Do you know how to control your Claude?*
- *Do you know how to spot hallucinations?*

### Learning goals

| # | Learning goal | Bloom's level |
|---|--------------|---------------|
| M2.1 | **Control** Claude's output through systematic prompting that produces reliable results | Apply |
| M2.2 | **Detect** hallucinations using backward validation, confidence calibration, and source grounding | Apply |
| M2.3 | **Prevent** hallucinations through prompt design, context management, and verification guardrails | Apply |
| M2.4 | **Harden** a CLAUDE.md with verification instructions and data handling rules | Apply |
| M2.5 | **Explain** to a colleague why Claude hallucinates and what to do about it | Analyze |
| M2.6 | **Assess** their org's data handling against Claude's data model — GDPR and EU AI Act implications | Analyze |
| M2.7 | **Draft** a data usage guideline for their team | Apply |
| M2.8 | **Judge** whether a given use case is safe and appropriate for their org | Evaluate |

### C1 opener (~3 min)
*"Have you ever caught Claude confidently telling you something wrong? What did you do?"*

### Hero exercise: "Can you trust the output?" (~25 min)
**Format: Personal.** You can't learn verification through a group exercise. This has to be your system, your output, your judgement.

**The setup:** The buyer (IT Director) composes the instructions live, in front of the room. A real, complex task — e.g. O365 configuration for a non-trivial scenario. The buyer doesn't prepare. The instructions may be right. They may be wrong. Nobody knows — including the buyer. The uncertainty IS the exercise.

Everyone runs the same instructions through their agent. The output looks confident and professional. Now: is it right?

**The key learning: hallucinations exist. Here's how to spot them.**

Techniques to practice:
- **Backward validation.** Take the output and verify claims against the source. Don't ask "is this right?" — check each specific claim independently.
- **Confidence calibration.** Ask Claude how confident it is. Compare that to whether it's actually right. Notice the gap.
- **Source grounding.** Does the output cite something specific, or does it sound authoritative while saying nothing verifiable?
- **The "teach it back" test.** Try explaining the output to your neighbour. The parts you can't explain clearly are the parts most likely to be wrong.

Then harden: adjust guardrails to include verification steps, add "cite your sources" instructions, restructure for checkability. Run again. Is the output more trustworthy now?

Via shared workspace: "Look at what your neighbour caught. Did you miss the same thing? Different eyes, different catches."

### Short lecture: "The data question" (~5 min)
Your colleague wants to paste a customer complaint with full name, email, and contract number into Claude. What happens to that data? What does your org's policy say? Where's the line?

Facilitator covers: Claude's data model, what's stored vs not, GDPR implications, the principle of "don't put in what you wouldn't email to a stranger." Practical, not legal. The verification exercise earned this lecture — they've just seen Claude be confidently wrong, so "what data should you trust it with?" lands differently now.

**Governance templates:** The data question naturally produces governance artifacts — acceptable use guidelines, data classification rules for Claude. These live in the shared workspace as drafts. Post-training, the buyer synthesizes them: their agent reads all 14 participants' data guidelines and produces the org's unified acceptable use policy. The team wrote the inputs; the buyer owns the output.

### C4 conclusion (~7 min)
*"If your IT Director asked you right now — is Claude safe for us to use? — what would you say? Not yes or no. The real answer."*

Return to C1: "You caught it being wrong earlier. Can you now prevent it, or just detect it? What's the difference?"

**Handoff to Module 3:** "You've built a system and you've hardened it. You know what it can do and where it breaks. Now: where is all of this going — and what does your org need to do about it?"

---

## Break (~15 min)

After Module 2. Two things happen during the break:

**The room breathes.** They've built, verified, and hardened a system. They need a reset before the perspective shift of Module 3. Informal conversations: "Did you catch the same error I did?" — peer learning that no exercise can force.

**The buyer tests ground truth.** While the room takes a break, the IT Director opens the real O365 admin panel and tests the procedure by hand. 14 verification results are visible in the shared workspace. The buyer checks: was the output actually right or wrong?

Module 3 opens with the buyer's verdict: "I checked. Here's what was right. Here's what was wrong." The room just witnessed the full cycle: instructions → AI output → participant verification → ground truth. The most powerful lesson of the day, delivered by their boss, based on their work.

---

## Module 3: "Where is this all going?" (45 min)
*Look ahead. The launchpad.*

### Big idea
Today's Cowork session is the on-ramp. The trajectory from chat to Cowork to Claude Code to agents changes what "rollout" means.

### Learning goals

| # | Learning goal | Bloom's level |
|---|--------------|---------------|
| M3.1 | **Evaluate** spicy predictions about Claude's trajectory and articulate their reasoning | Evaluate |
| M3.2 | **Identify** the crux — the single hardest problem in their org's Claude rollout | Analyze |
| M3.3 | **Design** an approach to address the crux | Evaluate |
| M3.4 | **Collaborate** through a multi-agent workflow — individual agents, shared workspace, synthesizer | Apply |
| M3.5 | **Evaluate** which teams should get Claude access first and what support they'll need | Evaluate |
| M3.6 | **Anticipate** the top adoption failures and design against them | Evaluate |
| M3.7 | **Contribute** to a rollout strategy synthesized by their IT Director | Evaluate |

### C1 opener (~3 min)
*"If you had to explain to a colleague tomorrow why they should or shouldn't start using Claude, what would you say?"*

The "or shouldn't" gives permission for honest assessment.

### Hero exercise: "Find the crux" (~30 min)

**Format: Multi-agent group exercise.** 4 groups of 3-4 people. Individual divergence, agent-driven convergence.

The question: **"What's the hardest problem in rolling out Claude to our org — the one that, if unsolved, makes everything else pointless?"** (Rumelt's crux.)

**The buyer's opening (~5 min):**
The IT Director works with Claude live, in front of the room: "What are the hardest challenges in rolling out Claude at our org?" Claude produces a list. The buyer ranks them by crux-hardness — which ones kill the rollout if unsolved? Claude recommends an approach for each. The buyer reads each one, reacts live: "I agree with this," "No, that's wrong because..." — standing behind it or pushing back. Their name on it, not Claude's.

The room now has a ranked challenge list with recommendations, endorsed or challenged by their boss. That's the input.

**Spicy takes — prediction rating (~5 min):**
Before divergence, the group chews on 5-7 spicy predictions about Claude's trajectory, sourced from agents-102 continuous research. Provocations, not forecasts:

- *"In 12 months, your helpdesk will be 80% Claude."*
- *"Within 2 years, every employee will have a personal AI agent."*
- *"Claude will write your org's first draft of every policy document by next quarter."*
- *"The IT team that doesn't learn to build agents will be replaced by one that does."*

Each participant rates: **plausible or not?** Then forced two-word follow-up: **"Why so?"**

"Too slow." "Legal blocks." "Already happening." "Users resist." "We're ready." "Nobody cares."

Two words — no hiding behind paragraphs. The constraint forces the actual thinking. The two-word answers tell you more about the room's beliefs, fears, and readiness than any discussion would. And they prime the divergence — the predictions surface assumptions they didn't know they held.

Results visible in shared workspace. The facilitator scans: where does the room agree? Where does it split? That's signal for the crux exercise.

**Plug point:** Predictions adapt per delivery. Sourced from agents-102 continuous research data for accuracy.

**Phase 1 — Divergence (~10 min):**
Each person individually, in their personal folder. The prompt is simple: **"What are going to be the top 3 difficulties in rolling out Claude at our org? Write them briefly."** Answerable in 2 minutes. Then Claude takes over — probing, challenging, expanding. Uses the ask questions tool to dig deeper when it senses something worth exploring. "You said resistance from legal. What specifically? Is it data concerns or workload concerns? Have they said anything, or is this your assumption?"

The participant does the thinking. Claude does the interviewing. The buyer's ranked challenges and the spicy take ratings are visible as context — the predictions surface assumptions that feed directly into identifying the crux.

**Phase 2 — Convergence (~15 min):**
Agents read across the individual outputs in the group folder. One person runs the group synthesizer: "Read everyone's crux candidates. Where do we agree? Where do we disagree? What's the actual crux — the one problem that determines everything else?" The agent synthesises. The group reads, reacts, adjusts.

No one needs to present. No one needs to debate. The quiet person with the best insight doesn't get steamrolled — their agent wrote it, the synthesizer picked it up. Equal voice by design.

Each group produces: one crux + one approach to addressing it.

**The buyer synthesizes.**
The IT Director runs the final synthesizer: reads all 4 group cruxes. Either they converge — "all 4 groups identified the same crux" (strong signal) — or they diverge (even more interesting). The buyer produces the actual strategic recommendation: here's our crux, here's our approach.

Not a training exercise — a real deliverable. The Director's own strategy, informed by 14 people's thinking, synthesized by their own agent. The room watches their boss use Claude to make a real decision based on their input.

**What just happened (the facilitator names it):**
The room just built a multi-agent system without being taught multi-agent systems. Individual agents → shared workspace → synthesizer → executive synthesis. That's question D answered through experience — not "where is this all going?" but "you're already there."

### C4 conclusion (~7 min)
*"One thing you'll do differently starting Monday. Not 'I learned that Claude is useful.' Something specific."*

Return to question C: *"Can you be the person your org trusts to run this?"* Leave it open. Don't answer it for them. The question stays with them after the room empties — that's the point.

Via shared workspace: the recommendations and Module 1 systems survive the training. Monday morning, the team has a shared space with tested systems, hardened guardrails, and a collective rollout recommendation. The collaboration is already happening.

---

## TBR 4Cs — Time Ratios per Module

| Phase | Time | Purpose |
|-------|------|---------|
| C1: Connections | ~3 min (7%) | One sharp question. Surface beliefs fast. |
| C2+C3: Concepts + Practice | ~30-35 min (70%) | Interleaved. Max 7 min facilitator talk before participants do something. |
| C4: Conclusions | ~7 min (15%) | Non-negotiable. If they can't articulate it, it didn't land. |

---

## Design Guardrails

### 1. No slides-only sections
Every concept demonstrated live or practised immediately.

### 2. 7-minute rule
If the facilitator has been talking for 7 minutes, stop. Participants do something.

### 3. Buyer-chosen case
Module 1's hero exercise uses a real task chosen by the buyer. The case is the main plug point per client.

### 4. Honest about failures
When Claude hallucinates, name it. IT people trust trainers who show the warts.

### 5. One big idea per module
- Module 1: "Chat resets. A system remembers. You just built the system."
- Module 2: "Control and detection — that's what trust is built on."
- Module 3: "Today's chatbot is tomorrow's agent platform. Plan accordingly."

### 6. Every module produces a takeaway
- Module 1: A working system with guardrails and CLAUDE.md — synced to the shared workspace
- Module 2: A hardened system + a data usage guideline for the team
- Module 3: A rollout recommendation for the IT Director

### 7. The training IS the demo
The facilitator uses Cowork throughout. The training itself demonstrates competent Claude usage.

### 8. The shared workspace IS the legacy
What survives the training: 14 systems, 14 sets of guardrails, a collective rollout recommendation — all in a shared workspace the team already knows how to use. No post-training "now what?" gap.

### 9. Plug points for reuse
Client-specific content (the case, org size, industry, compliance context) lives in clearly marked plug points. Framework stays constant; context swaps per client.

---

## Bloom's Taxonomy — Full Arc

| Phase | Primary levels | Who teaches |
|-------|---------------|-------------|
| Pre-work | Remember → Understand | Claude |
| Module 1 | Apply | Facilitator + Claude |
| Module 2 | Apply → Evaluate | Facilitator + Claude |
| Module 3 | Analyze → Evaluate | Facilitator + Claude |
| Post-work | Apply → Analyze | Claude |

**Ceiling: Evaluate.** Create is agents-102 territory.

**Floor in the room: Apply.** Remember and Understand happen in pre-work, handled by Claude. The facilitator never wastes session time on content Claude can deliver individually.

The full Bloom's progression across the arc: Remember → Understand → Apply → Analyze → Evaluate. But the facilitator only shows up for Apply through Evaluate — the high-value middle where humans need to be together.

---

## Optional add-ons

### Executive briefing (30 min, pre-session)
A short strategic framing for the IT Director before the training. Positions the training in the bigger picture: this is the experiment-to-scale bridge — the step that turns "we bought licenses" into "we have a team that knows what they're doing." Covers what to expect from the session, how to play the buyer role (composing instructions, testing ground truth, synthesizing), and what the 30/60/90-day measurement looks like.

### Post-training measurement service
Bosser designs and runs the adoption measurement program — assessments at week 1/4/12, trend analysis, recommendations. The buyer can do it alone with Claude; the service makes it sharper and adds external benchmarking.

---

## Where this fits: the experiment-to-scale bridge

Claude Basics is not "AI awareness training" (too shallow) and not "agent building bootcamp" (too deep). It's the bridge between experimenting with Claude and scaling it across the org.

```
Experiment          → Claude Basics →           Scale
(individuals        (IT team learns to          (org-wide rollout
chatting)            govern AND use)              with confidence)
```

For buyers: this is the step that turns "we bought licenses" into "we have people who can run this." For the agents-102 journey: this is Step -1.

---

---

## Reference

Pedagogy adapted from agents-102 (`~/Projects/agents-102/curriculum/lecture-guardrails.md`). That training is 2 days / 8 modules for building agents. This training is 3 hours / 3 modules for the people who'll govern and support the rollout.
