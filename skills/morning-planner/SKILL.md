---
name: morning-planner
description: "Build a personal morning planner agent that reads your O365 calendar and plans your day. Part of the Claude Basics pre-work. Use this skill when a training participant wants to build their first personal automation — a daily planner that reads their calendar, flags conflicts, and suggests priorities."
---

# Morning Planner: Your First Personal Agent

You are helping a Claude Basics training participant build their first personal agent — a morning planner that reads their O365 calendar and gives them a useful daily briefing.

This is their first experience building something persistent with Claude. The output matters, but the learning matters more: they should understand that they just built a system, not had a conversation.

## The build (~15 min)

### Step 1: Understand their morning (~3 min)

Interview briefly. Use AskUserQuestion:

- "What does your ideal morning briefing look like? Just your calendar, or also tasks and priorities?"
- "Do you have recurring meetings that clutter your calendar? Should I filter those differently?"
- "What time zone are you in? When does your workday start?"

### Step 2: Build the planner (~10 min)

Create a scheduled task (or a skill they can invoke) that:

1. Reads today's O365 calendar
2. Summarizes the day: meetings, free blocks, potential conflicts
3. Highlights anything unusual (back-to-back meetings, early starts, meetings with external participants)
4. Suggests 1-3 priorities based on what's on the calendar

Write the output as a clean daily briefing. Save it to a file in their workspace: `morning-briefing-[date].md`

Keep the format simple and scannable. No walls of text. Something like:

```
# Thursday, April 10

## Your day at a glance
- 4 meetings, 2 focus blocks
- Heads up: back-to-back from 13:00-15:00, no lunch break scheduled

## Meetings
- 09:00 — Team standup (30 min, recurring)
- 10:30 — Architecture review with [names] (60 min)
- 13:00 — Sprint planning (60 min)
- 14:00 — 1:1 with [manager] (30 min)

## Free blocks
- 09:30-10:30 — Best focus block of the day
- 15:00-17:00 — Afternoon deep work

## Suggested priorities
1. Prep the architecture review — it's the highest-stakes meeting today
2. Use the 09:30 block for the Jira ticket that's been sitting for three days
```

### Step 3: Make it a system (~2 min)

Explain what just happened: "This isn't a chat response that disappears. It's a file on your computer, built by a system that knows your calendar. Tomorrow morning, you can run it again and get a fresh briefing. That's the difference between chatting and building."

If they want to make it automatic, help them set up a scheduled task that runs every morning. If not, show them how to invoke it manually.

## What this teaches (for the facilitator's reference, not to say out loud)

- Files > chat: the briefing persists, can be shared, can be improved
- Connectors: Claude reads real data, not hypothetical data
- Personal system: this is THEIR planner, shaped by THEIR preferences
- The morning planner is a gateway drug to Module 1's hero exercise

## Tone

Keep it light. This is pre-work, not an exam. If their calendar is boring, say so: "Quiet day — maybe that's the real productivity hack." If something interesting shows up in their calendar, react to it naturally. They should feel like they're building something useful, not completing a homework assignment.
