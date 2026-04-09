# Agentic Training Approaches: "Learn the Tool BY Using the Tool"

> CAVEAT: Based on knowledge through early 2025. Web search was unavailable. This is a genuinely emerging space with few established examples.

---

## The Core Idea

"Agentic training" = the AI tool is not just the subject of the training but a co-participant in the learning process. The learner uses the tool to learn the tool. The training itself demonstrates competent usage.

Our framework does this. The question: who else does, and what can we learn?

---

## Known Examples and Analogues

### 1. Anthropic's Own "Dogfooding" Culture
- Anthropic employees use Claude to write documentation about Claude, to draft training materials about Claude, and to debug Claude. The company is its own best case study in agentic work.
- **Relevance:** Not a training program per se, but the philosophy is identical to our framework's "the training IS the demo" principle. If anyone asks what mature Claude usage looks like, the answer is already in the room.

### 2. GitHub Copilot "Copilot-in-Copilot" Pattern
- Some organisations use GitHub Copilot to build GitHub Copilot extensions. The tool accelerates its own expansion.
- **Relevance:** Technical, not pedagogical. But it demonstrates the meta-pattern: using the tool to extend the tool's capabilities.

### 3. AI-Assisted Course Design (Higher Education)
- Multiple universities (Stanford, MIT, Harvard) have experimented with using LLMs to co-design courses about LLMs. Students use the AI to critique the AI. The assessment IS the learning.
- **Structure:** Typically semester-long courses where students build increasingly sophisticated AI workflows, critique AI outputs, and document failure modes.
- **What they do well:** Deep critical thinking about AI capabilities and limitations. Students develop genuine evaluation skills because they're constantly stress-testing.
- **What they miss:** Semester timescale is irrelevant for enterprise training. No governance or organisational rollout dimension.

### 4. "Prompt Engineering Bootcamps" (Various Providers)
- Multiple providers (Coursera, Udemy, specialist firms) offer intensive prompt engineering courses where participants practice prompting throughout.
- **Structure:** Typically 1-3 days. Progressive exercises from basic prompting to complex chain-of-thought and tool use.
- **What they do well:** High practice density. Lots of reps.
- **What they miss:** Prompting is a means, not an end. Our framework builds SYSTEMS that include prompts. The difference: a prompt engineering bootcamp teaches you to fish. Our training teaches you to build a fishing business.

### 5. Salesforce "Trailhead" Model (Pre-AI Analogue)
- Salesforce Trailhead is the gold standard for "learn the platform by using the platform." Interactive, in-product, gamified, progressive.
- **Structure:** Badges, trails, superbadges. Each module has a hands-on challenge completed in a real Salesforce environment.
- **What they do well:** In-product learning eliminates the transfer gap. You learn Salesforce IN Salesforce. Skills transfer is immediate because there's nothing to transfer — you're already in the tool.
- **What they miss:** Self-paced only. No facilitation, no peer learning, no collective decision-making. Our framework adds the human layer that Trailhead deliberately omits.

### 6. "Pair Programming with AI" Training Models
- Some engineering teams train developers on AI coding assistants by pair programming: one human, one AI, real tasks. The training IS the work.
- **Structure:** Informal, team-embedded, ongoing. A senior developer models good AI collaboration; juniors observe and then practice.
- **What they do well:** Zero artificial exercises. Every training moment produces real work output.
- **What they miss:** Unstructured. No governance. No assessment of whether the AI output is trustworthy. Our Module 2 adds the critical evaluation layer that pure "pair with AI" approaches lack.

---

## What Makes Our Approach Distinctive

### 1. The AI is facilitator AND subject
In most "learn by doing" approaches, the AI helps you learn about something else (a platform, a language, a concept). In our framework, the AI helps you learn about the AI itself. Claude leads the pre-work. Claude co-facilitates the exercises. Claude synthesises in Module 3. The meta-layer is the pedagogy.

### 2. The artifact matures WITH the learning
Most training produces disposable exercises or static certificates. Our CLAUDE.md evolves across the entire arc — from personal preferences (pre-work) to task guardrails (Module 1) to hardened verification (Module 2) to new team setup (Module 3). The artifact IS the learning, externalised and persistent.

### 3. The multi-agent exercise is agentic training at scale
Module 3's individual-to-group-to-buyer synthesiser chain is, as far as I can tell, unique. No other training program uses multiple AI agents reading each other's outputs to produce a collective deliverable. This is not a gimmick — it's a preview of how agentic work actually operates.

### 4. The facilitator role is redefined
Traditional training: facilitator teaches, learner receives. Our framework: facilitator guides, Claude teaches, learner builds. The facilitator's job is to "name what just happened" — not to deliver content but to make the implicit explicit. This is closer to coaching than teaching.

---

## Implications for Our Framework

### Strengthen

1. **Name the meta-layer explicitly.** Participants should hear, at some point: "Notice that this training is itself an example of what we're teaching. Claude is leading your pre-work. Claude is co-facilitating these exercises. You're learning to work with Claude BY working with Claude. This IS the demo." The facilitator should say this once, precisely, at a moment when it lands.

2. **Track the "agentic confidence" arc.** Participants start the pre-work with Claude as a novelty. By Module 3, they're delegating synthesis to Claude and evaluating its output critically. The shift from "talking to AI" to "delegating to AI and evaluating the result" is the core competency. We should name this progression more explicitly.

3. **Steal from Trailhead's gamification (carefully).** Trailhead's badge/trail system creates momentum and visible progress. Our framework has natural checkpoints (personal CLAUDE.md created, system built, system hardened, rollout recommendation drafted). Making these visible — even just a checklist in the shared workspace — would give participants a sense of progression without trivialising the learning.

4. **Document the facilitator's "naming" moments.** If the facilitator's key skill is naming what just happened (not teaching), the facilitator guide should include specific "name this" prompts for each module. E.g., after the Module 1 midway checkpoint: "Name: you all solved the same problem differently. That's why guardrails matter — they encode your judgment, and judgment varies." These naming moments are the facilitation craft.

### Protect

1. **Don't over-explain the meta.** The power of agentic training is that the meta-layer is experienced, not lectured. If you spend 10 minutes explaining "this is agentic training where you learn the tool by using the tool," you've killed it. One sentence, once, at the right moment.

2. **Don't gamify the substance.** Badges for completing a CLAUDE.md are fine. Badges for "best hallucination catch" are cringe. The exercises produce real work — treat them that way.

3. **The facilitator is NOT optional.** Some agentic training proponents argue that if the AI can teach, you don't need a human. Wrong. Claude can deliver content and guide exercises. Claude cannot read the room, notice when someone is lost, spot the moment when two participants' approaches reveal a deeper insight, or decide to let a productive failure run longer. The facilitator makes the agentic training work by doing the things AI cannot.

---

## The Competitive Landscape (Honest Assessment)

As of early 2025, we are ahead of the market on agentic training design. The reasons:
- **Most AI training vendors haven't internalised the meta-possibility.** They treat AI as subject matter, not as pedagogy.
- **Most enterprise training buyers don't know to ask for this.** They ask for "Claude training" and expect slides and exercises. The agentic approach needs to be sold, not assumed.
- **The tooling just became capable enough.** Cowork's file system, connectors, and multi-agent patterns make agentic training possible in a way that chat-only interfaces don't.

The risk: this advantage is temporary. Once Anthropic, Microsoft, or a major training provider builds an agentic training product, the market will expect it. Our window is now.
