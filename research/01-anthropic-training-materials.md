# Anthropic's Own Training & Enablement Materials

> CAVEAT: Based on knowledge through early 2025. Web search was unavailable. Anthropic's enablement offerings evolve rapidly — verify current state before acting.

## What Anthropic Provides

### Documentation & Prompt Engineering Guides
- **Anthropic Docs (docs.anthropic.com):** Comprehensive API documentation, prompt engineering guide, and cookbook. Technically excellent but aimed at developers, not enterprise end-users or IT governance teams.
- **Prompt Engineering Guide:** Detailed, well-structured. Covers techniques like chain-of-thought, XML tags, role prompting. Strong on the "how to talk to Claude" mechanics.
- **Claude for Enterprise resources:** Anthropic offers enterprise-tier support including dedicated account teams, custom onboarding, and security reviews. The exact training structure varies by deal size.

### Anthropic Academy / Learning Resources
- Anthropic has published course materials (e.g., on platforms like GitHub and partner sites) covering prompt engineering fundamentals, tool use, and agent patterns.
- Content tends to be self-paced, text-heavy, and developer-oriented.
- No known standardised "enterprise rollout training" package comparable to what Microsoft offers for Copilot.

### Enterprise Enablement Model
- Anthropic's enterprise sales typically includes: security review, technical onboarding, and CSM-led check-ins.
- Training is often bespoke — the enterprise team works with the customer to define use cases and build initial workflows.
- No public "Anthropic Certified" program or standardised training curriculum (as of early 2025).

## What They Do Well (That We Should Learn From)

1. **Prompt engineering depth.** Their prompt guide is genuinely excellent — systematic, with clear examples. Our framework assumes participants pick up prompting by doing. We might want a reference card or cheat sheet that links to Anthropic's guide for post-training self-study.

2. **Safety-first framing.** Anthropic leads with responsible use, model limitations, and the Constitutional AI philosophy. Our Module 2 covers trust and hallucination, but we could strengthen the connection to Anthropic's own safety narrative — it gives the IT audience a vendor-backed argument for governance.

3. **Developer-to-production path.** Their docs trace a clear path from experimentation to production deployment. Our framework doesn't currently address what happens after the rollout recommendation (Module 3) becomes an actual deployment.

## What They Miss (That We Already Cover)

1. **The "system, not chat" mental model shift.** Anthropic's materials treat Claude as a capable tool. Our framework explicitly breaks the chat habit and builds the system-thinking muscle. This is the biggest pedagogical gap in vendor materials generally — they teach features, not workflows.

2. **IT governance perspective.** Anthropic's enablement is developer-first. Our framework is built for the people who govern, support, and roll out — not the people who build APIs. This is a different audience with different anxieties.

3. **Facilitated, experiential learning.** Anthropic provides documentation and self-paced materials. Our framework provides a facilitated experience where the learning IS the doing. Documentation tells you what's possible; our training makes you feel the difference.

4. **The continuous artifact.** No Anthropic material (that I've seen) uses a maturing artifact as a learning throughline. Our CLAUDE.md progression across modules is pedagogically distinctive.

5. **Multi-agent collaboration exercise.** Module 3's synthesiser pattern is not something Anthropic teaches in any enablement material. They document tool use; we demonstrate emergent multi-agent workflows.

## Gaps This Reveals in Our Framework

1. **No explicit link to Anthropic's own resources.** Post-training, participants should know where to find Anthropic's prompt guide, docs, and cookbook. A "further reading" handout or CLAUDE.md section pointing to these would extend the training's half-life.

2. **Safety narrative alignment.** We should explicitly connect our trust/governance themes to Anthropic's published safety principles. IT directors who need to justify Claude adoption to leadership want to cite the vendor's own commitments, not just their training notes.

3. **API/developer bridge.** Our framework ends at "rollout recommendation." For IT teams, the next question is often "how do we integrate this into our systems?" A brief mention of the developer path (API, Claude Code) in Module 3's trajectory discussion would prevent the "now what?" that comes after the "where is this going?" answer.
