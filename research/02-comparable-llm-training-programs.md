# Comparable AI/LLM Enterprise Training Programs

> CAVEAT: Based on knowledge through early 2025. Web search was unavailable. Program details change frequently — verify specifics before citing.

---

## Microsoft Copilot Training

### Structure
Microsoft has built the most mature enterprise AI training ecosystem, largely because they had to — Copilot is bundled into tools 400M+ people already use, and adoption without training was embarrassingly low.

- **Microsoft Copilot Success Kit:** Structured rollout program including executive briefings, champion programs, scenario-based training, and adoption measurement.
- **Copilot Lab:** In-product learning environment where users discover prompts by scenario (e.g., "summarise this email thread," "draft a project plan").
- **Microsoft Learn paths:** Self-paced, role-based learning paths (e.g., "Copilot for IT Admins," "Copilot for Executives").
- **Copilot Dashboard:** Usage analytics that show adoption rates, active users, and which features are actually being used — lets IT track whether training translated to behaviour change.
- **Champion program model:** Train 5-10% of the org as "Copilot Champions" who support peers. Structured with monthly calls, scenario challenges, and community forums.

### Duration
- Executive briefing: 1 hour
- End-user training: Typically 2-4 hours, broken into role-specific modules
- Champion training: Ongoing (monthly cadence)
- Full rollout cycle: 8-12 weeks from pilot to broad deployment

### What They Do Well
1. **Role-based scenarios.** Training is anchored in "what does THIS person do every day?" not generic AI capabilities. An HR manager gets HR scenarios. A finance analyst gets finance scenarios.
2. **Adoption measurement built in.** The Copilot Dashboard means you can prove training worked (or didn't). Our framework has no explicit measurement mechanism.
3. **Champion model scales.** Training 14 people is great; training 14 people who each enable 20 more is better. The champion program is the scalability layer.
4. **Scenario library.** Hundreds of pre-built prompt templates organised by role and task. Reduces the "blank page" problem.

### What They Miss
1. **No system-building.** Copilot training teaches features, not systems. "Here's how to summarise an email" is a trick, not a workflow. Our CLAUDE.md/system approach is fundamentally different and more powerful.
2. **No governance integration.** Copilot training and Copilot governance are separate workstreams. Our framework makes them the same thing — the IT team learns the tool BY governing it.
3. **No hallucination training.** Microsoft's materials largely avoid the "when does this go wrong?" question. Our Module 2 puts it centre stage. Microsoft can afford this because Copilot's scope is narrower; we can't.
4. **No trajectory conversation.** Copilot training is about today's features. Our Module 3 is about the 12-month arc. Microsoft doesn't need this because they control the roadmap; enterprise IT teams DO need it because they're making investment decisions.

---

## Google Gemini Enterprise Enablement

### Structure
- **Google Workspace Labs / Gemini for Workspace:** Training integrated into Google Workspace admin console. Structured as admin enablement + end-user enablement.
- **Google Cloud Skills Boost:** Self-paced courses on Gemini, Vertex AI, and generative AI fundamentals. More technically oriented.
- **Gemini Academy:** Role-specific training paths. Similar structure to Microsoft Learn but less mature.
- **Partner-delivered training:** Google relies heavily on partner ecosystem (Deloitte, Accenture, etc.) for enterprise enablement. Less standardised than Microsoft.

### What They Do Well
1. **Technical depth.** Google's training goes deeper on model capabilities, embeddings, and RAG patterns than Microsoft's. Better for technical audiences.
2. **Hands-on labs.** Google Cloud Skills Boost has interactive labs where you build things in a sandbox environment. The "learn by doing" principle is shared with our framework.

### What They Miss
1. **Enterprise readiness gap.** Google's training materials are technically excellent but organisationally naive. They teach you how to use Gemini, not how to roll it out to 500 people safely. Our framework's IT governance angle fills exactly this gap.
2. **No facilitated component.** Everything is self-paced. No room for the peer comparison, live debugging, and collective decision-making that makes our Modules 1-3 work.

---

## OpenAI Enterprise Onboarding

### Structure
- **ChatGPT Enterprise / Team onboarding:** White-glove onboarding for enterprise customers. Includes admin setup, SSO configuration, usage policy templates, and initial training sessions.
- **OpenAI Cookbook:** Technical recipes for developers. Excellent but not training.
- **Custom GPTs as training tools:** Some enterprises build custom GPTs that serve as onboarding assistants for their own teams. Meta-training — the tool teaches about the tool.
- **OpenAI Academy:** Launched in late 2024/early 2025. Structured courses on prompt engineering, GPT building, and enterprise deployment. Still maturing.

### What They Do Well
1. **Custom GPTs as enablement.** The idea that teams build their own specialised assistants is powerful. Our CLAUDE.md approach is the Claude equivalent — but Custom GPTs are more visual and shareable. Worth noting as a competitive comparison point.
2. **Usage policy templates.** OpenAI provides ready-made acceptable use policies for enterprise customers. Practical governance material that our framework touches conceptually (Module 2's data question) but doesn't provide as a deliverable.

### What They Miss
1. **No structured learning progression.** OpenAI's approach is "here's the tool, here are some resources, good luck." No Bloom's taxonomy, no pedagogical arc. Our framework's deliberate progression from Apply through Evaluate is a real differentiator.
2. **No live facilitation model.** Same gap as Google — everything is async, self-paced, documentation-first.

---

## Cross-Cutting Observations

### What the big vendors share (and we should note)
- All three invest heavily in **self-paced, role-based content**. Our framework has almost none of this — by design, since we're building systems not teaching features. But post-training reference materials organised by role could extend our impact.
- All three measure **adoption quantitatively**. We have no measurement model. This is a gap.
- All three provide **policy/governance templates**. We teach governance thinking but don't hand over templates. Adding a template pack (acceptable use policy, data classification guide, incident response for AI errors) would make Module 2's output more concrete.

### What none of them do (and we should protect)
- **Experiential, build-first pedagogy.** Every vendor teaches features before practice. We reverse this. Don't lose it.
- **Continuous artifact.** No vendor uses a maturing artifact as a learning spine. This is our distinctive advantage.
- **Governance-integrated training.** Every vendor separates "learn the tool" from "govern the tool." We merge them. This is exactly right for IT audiences.
- **Trajectory/strategy conversation.** No vendor training asks "where is this all going?" because they'd rather you just buy more licenses. Our Module 3 fills a genuine strategic gap.
