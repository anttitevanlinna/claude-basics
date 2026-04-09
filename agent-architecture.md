# Agent Architecture: Claude Basics Training

How Cowork agents run the entire training. The facilitator guides the room. The agents do the work.

---

## The principle

Every phase of the training — pre-work, live modules, post-work — is handled by a purpose-built Cowork agent. Participants interact with their agents in their personal Cowork sessions. The shared SharePoint workspace is the message bus: agents write to it, other agents read from it.

The facilitator never touches Claude directly. They watch the room, name what's happening, and keep the 7-minute rule.

---

## Agent map

### Pre-work agents (async, Claude-led)

| Agent | What it does | Output |
|-------|-------------|--------|
| **Prework Tour** | Walks participant through Cowork features, connects O365 + Jira, builds personal CLAUDE.md | Connected workspace, personal CLAUDE.md |
| **Morning Planner** | Helps participant build their first O365 calendar agent | Scheduled daily briefing, morning-briefing-[date].md |

### Module 1 agents (in-session)

| Agent | What it does | Output |
|-------|-------------|--------|
| **System Builder** | Scaffolds the hero exercise — guides participant through building a system for the buyer's task, prompts for CLAUDE.md creation, checks guardrails | Working system + folder CLAUDE.md in personal folder |

### Module 2 agents (in-session)

| Agent | What it does | Output |
|-------|-------------|--------|
| **Verification Coach** | Runs the buyer's instructions, then coaches verification techniques: backward validation, confidence calibration, source grounding | Hardened CLAUDE.md with verification rules |
| **Data Guidelines Drafter** | Helps participant draft their team's data usage guidelines based on the data lecture | Data guideline draft in personal folder |

### Module 3 agents (in-session, multi-agent)

| Agent | What it does | Output |
|-------|-------------|--------|
| **Spicy Take Rater** | Presents predictions, collects ratings + two-word reactions | Ratings file in personal folder |
| **Divergence Interviewer** | Probes participant's top 3 rollout difficulties, digs past the obvious | crux-analysis-[name].md in personal folder |
| **Group Synthesizer** | Reads across 3-4 individual crux analyses, finds the group crux | group-[N]-crux.md in group folder |
| **Executive Synthesizer** | Reads all 4 group cruxes, produces the rollout strategy | rollout-strategy.md in buyer's synthesis folder |

### Post-work agents (async)

| Agent | What it does | Output |
|-------|-------------|--------|
| **Adoption Measurer** | Sends self-assessments at week 1/4/12, synthesizes results for the buyer | Adoption report in buyer's folder |
| **System Check-in** | "How's your system going? What broke this week?" — keeps learning alive | Updated personal systems |

---

## Data flow

```
Pre-work:
  participant ↔ prework-tour → personal CLAUDE.md
  participant ↔ morning-planner → morning briefing

Module 1:
  participant ↔ system-builder → personal folder/system + CLAUDE.md
  all personal folders → shared workspace (midway sync)

Module 2:
  buyer composes instructions → everyone runs them
  participant ↔ verification-coach → hardened CLAUDE.md
  participant ↔ data-guidelines → data guideline draft
  [break: buyer tests ground truth on real admin panel]

Module 3:
  buyer ↔ Claude → ranked challenges + recommendations
  spicy-take-rater → ratings per participant
  participant ↔ divergence-interviewer → crux-analysis-[name].md
  group-synthesizer reads personal folders → group-[N]-crux.md
  executive-synthesizer reads group folders → rollout-strategy.md
```

---

## The shared workspace IS the architecture

```
/claude-basics-training/
  /participants/
    /participant-a/           ← their Cowork working directory
      CLAUDE.md               ← personal (pre-work)
      system/                 ← Module 1 hero exercise output
        CLAUDE.md             ← folder (Module 1, hardened in Module 2)
      crux-analysis.md        ← Module 3 divergence output
      data-guidelines.md      ← Module 2 draft
    /participant-b/
      ...
  /groups/
    /group-1/
      group-1-crux.md         ← group synthesizer output
    /group-2/
      ...
  /synthesis/
    rollout-strategy.md       ← executive synthesizer output
    adoption-report-week1.md  ← post-work measurement
```

No special infrastructure. SharePoint syncs the files. Cowork reads and writes them. The folder structure is the multi-agent message bus.

---

## Skills built (4 of 11)

| Skill | Status | Path |
|-------|--------|------|
| prework-tour | ✅ Built | skills/prework-tour/SKILL.md |
| morning-planner | ✅ Built | skills/morning-planner/SKILL.md |
| module3-divergence | ✅ Built | skills/module3-divergence/SKILL.md |
| module3-synthesizer | ✅ Built | skills/module3-synthesizer/SKILL.md |
| system-builder | ⬜ Next | — |
| verification-coach | ⬜ Planned | — |
| data-guidelines | ⬜ Planned | — |
| spicy-take-rater | ⬜ Planned | — |
| adoption-measurer | ⬜ Planned | — |
| system-checkin | ⬜ Planned | — |
| executive-briefing | ⬜ Planned | — |

---

## What this proves

The entire training runs on Cowork + SharePoint. No custom software. No staging environment. No slides that get stale. The agents ARE the training materials — and they improve every time they're used.

The facilitator's job: be in the room for the 2.5 hours where humans need to be together. Everything else, the agents handle.
