# Claude Basics — IT Admin & Usage Training

## Purpose

Training material for IT teams rolling out Claude in their organisation.

## The engagement

- 3 x 45-minute modules, plus pre-work and post-work
- An agentic training: participants learn Claude BY using Claude
- The IT team needs to both manage the rollout AND understand what Claude can actually do
- 10-14 IT team members + the buyer (IT Director as active participant)

## Fundamental questions

Two questions drive the entire training:

- **C: "Can you be the person your org trusts to run this?"** — Identity question, not skills. The spine of Modules 1-2, returned to at the end of Module 3. Left open.
- **D: "Where is this all going?"** — The accelerant. Surfaces through experience, not lecture. By Module 3 they're living the answer.

## Training structure

### Pre-work (async, Claude-led, optional)
- Setup: account, Cowork, SharePoint shared workspace, O365/Jira connectors
- Optional: Claude chat tour (15 min)
- Mandatory: Cowork tour (15 min)
- Build personal morning planner agent with O365 (20 min)
- Write personal CLAUDE.md (10 min)
- Bring a question

### Module 1: "Stop chatting — build a system" (45 min, Apply)
- Hero exercise: build a system for buyer-chosen task. Personal format, 14 approaches.
- Create folder CLAUDE.md with guardrails and quality standards
- Closing lecture: "How to make your system learn?" — bridges to data, security, Module 2
- Takeaway: working system with guardrails in shared workspace

### Module 2: "Can you be trusted to run this?" (45 min, Apply → Evaluate)
- Subquestions: Do you know how to control your Claude? Do you know how to spot hallucinations?
- Hero exercise: buyer composes instructions live, everyone verifies output. Backward validation, confidence calibration, source grounding.
- Harden the folder CLAUDE.md — add verification, data rules, hallucination prevention
- Short lecture: "The data question" — GDPR, data model, practical guidelines
- Takeaway: hardened system + verification techniques

### Break (15 min)
- Buyer tests ground truth on real O365 admin panel
- Opens Module 3 with verdict: what was right, what was wrong

### Module 3: "Where is this all going?" (45 min, Evaluate)
- Opens with buyer's ground truth verdict from break
- Buyer works with Claude live: ranks rollout challenges by crux-hardness (Rumelt)
- Hero exercise "Find the crux": multi-agent group exercise (4 groups of 3-4)
  - Divergence (10 min): individual agents, "top 3 difficulties," Claude interviews deeper
  - Convergence (15 min): group synthesizer reads across, finds the crux
  - Buyer synthesizes all 4 groups into actual rollout strategy
- New team workspace per group — fresh CLAUDE.md from scratch (they know how now)
- The room accidentally builds a multi-agent system. Facilitator names it.
- Takeaway: real rollout strategy owned by the IT Director

### Post-work (async)
- **Measurement (buyer-led):** Self-assessment at week 1/4/12. Buyer synthesizes adoption data with Claude.
- **Continued learning (Claude-led):** System check-ins, week-2 questions, resource links (Anthropic docs, prompt guide, cookbook)
- **Optional add-on:** Bosser runs measurement program as paid service

## Key design concepts

### Agentic training principle
Every participant has Cowork open. Claude is co-participant, not just subject. Facilitator is guide, not teacher. No explaining then trying — trying then understanding.

### Continuous artifact
One system, born in Module 1, hardened in Module 2. Module 3 starts fresh per group. Two types of CLAUDE.md: personal (pre-work, travels with you) and folder (Modules 1-2, travels with the work).

### Shared workspace
SharePoint folder synced by all. Personal folders → group folders → buyer's synthesis folder. The folder structure IS the multi-agent architecture in Module 3. Survives the training as post-training legacy.

### Exercise formats
- Modules 1 & 2: Personal. Ownership matters.
- Module 3: Multi-agent group. Individual agents write to shared space, synthesizer converges, buyer produces final output.

## Design principles

- **Hands-on from minute one.** No slides-only sections. Every concept demonstrated live, then practised.
- **7-minute rule.** Max facilitator talking time before participants do something.
- **Use their real work.** Buyer-chosen case for Module 1. Real O365 tasks for Module 2.
- **Honest about limitations.** When Claude fails, show why. IT people respect honesty more than hype.
- **The training IS the demo.** If we deliver this well, they see what good Claude usage looks like.
- **Buyer as active participant.** Not a spectator — composes instructions, tests ground truth, synthesizes the final deliverable.

## Pedagogical approach

Adapted from agents-102 (`~/Projects/agents-102/curriculum/lecture-guardrails.md`):
- **TBR 4Cs:** Connections (~3 min) → Concepts + Practice interleaved (~35 min) → Conclusions (~7 min)
- **Bloom's taxonomy:** Pre-work (Remember → Apply) → Module 1 (Apply) → Module 2 (Apply → Evaluate) → Module 3 (Evaluate) → Post-work (Apply → Analyze)
- Ceiling: Evaluate. Create is agents-102 territory.
- Floor in room: Apply. Remember/Understand handled by Claude in pre-work.

## Reusability

This material will be used across multiple clients. Design it as a template:
- Core content stays the same across clients
- Plug points: buyer-chosen case, org size, industry, compliance context, connectors
- The SharePoint folder structure, exercise formats, and module arc are constant
- Every client delivery produces improved material

## Positioning

Claude Basics is the experiment-to-scale bridge: the step that turns "we bought licenses" into "we have people who can run this." Step -1 in the agents-102 journey.

## Optional add-ons

- **Executive briefing (30 min):** Strategic framing for the IT Director before the session
- **Post-training measurement service:** Bosser designs/runs adoption assessments at week 1/4/12

## Reference

- agents-102 project: `~/Projects/agents-102`
- Lecture guardrails: `~/Projects/agents-102/curriculum/lecture-guardrails.md`
- Training framework (detailed): `./training-framework.md`
- Research benchmarking: `./research/`

## Author

10+ years designing enterprise training. Background in product ownership masterclasses and scaled AI training programs (200+ participants).

## Tone

Practitioner, not vendor. "Here's what works and here's what doesn't" not "Claude is amazing." IT people have excellent bullshit detectors. Respect that.

## How modules are designed (process notes)

This is how the framework was built — follow the same process for new modules or revisions.

1. **Start with fundamental questions, not content.** The two questions (C and D) came first. Modules exist to answer them. If a module doesn't serve a question, it doesn't exist.

2. **Name the module as a provocation, not a topic.** "Stop chatting — build a system" not "Introduction to Cowork." The title IS the insight. If the title is boring, the module is boring.

3. **One hero exercise per module.** Design the exercise first, then derive learning goals from it. Not the other way around. The exercise is the module — everything else serves it.

4. **Exercises come from real work, not pedagogy.** Start from "what will they do at work Monday?" not "what makes a good learning activity?" The buyer chooses the case. The O365 tasks are real. The rollout recommendation is a real deliverable.

5. **Buyer as active participant in every module.** The buyer isn't watching — they're composing instructions (Module 2), testing ground truth (break), ranking challenges (Module 3), synthesizing the final output. If the buyer is passive, redesign.

6. **Learning goals use Bloom's verbs and are written after the exercise is designed.** The exercise determines what they'll actually be able to do. The learning goals name it formally. Never write goals first and design exercises to match — that produces exercises that serve goals instead of goals that describe exercises.

7. **Format follows function.** Personal exercises when ownership matters (Modules 1-2). Group exercises when collision of perspectives matters (Module 3). Multi-agent format when you want to demonstrate the trajectory without lecturing about it.

8. **Lectures earn their place.** Only after hands-on experience, never before. Module 1's "How to make your system learn?" works because they've already built the system. Module 2's "The data question" works because they've already seen hallucinations. A lecture that precedes experience is a lecture nobody remembers.

9. **Each module hands off to the next.** The handoff is explicit and creates tension: "You've got a system that works. Now let's find out if you can trust it." The arc is a story, not a list.
