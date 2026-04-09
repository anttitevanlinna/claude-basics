# IT-Specific AI Training Programs

> CAVEAT: Based on knowledge through early 2025. Web search was unavailable. This is a thin market — most AI training is role-generic or developer-specific, not IT-team-specific.

---

## The Problem: IT Teams Have a Dual Mandate

IT teams don't just USE AI tools — they GOVERN them. They need to:
1. Be competent users (so they can support others)
2. Be competent evaluators (so they can set policy)
3. Be competent deployers (so they can roll it out safely)

Most AI training addresses exactly one of these. Our framework addresses all three. This is genuinely rare.

---

## What Exists

### Microsoft IT Admin Training for Copilot
- **Copilot for Microsoft 365 Admin Enablement:** Focused on tenant configuration, policy settings, data access controls, and usage reporting.
- **Structure:** Self-paced modules on Microsoft Learn, plus admin-specific documentation.
- **Content:** Technical governance — who gets access, what data Copilot can see, how to monitor usage. Light on "how to use it well" and heavy on "how to control it."
- **Gap:** Teaches the knobs and switches but not the judgment. Our Module 2 builds the judgment ("is this output trustworthy?") that makes the knobs and switches meaningful.

### ITIL/ITSM + AI Integration
- **ITIL v4 and AI:** ITIL has begun incorporating AI into service management practices — AI-assisted incident management, AI-driven change analysis, predictive capacity planning.
- **PeopleCert / Axelos courses:** Some ITIL-aligned courses now include AI modules. Focus is on where AI fits in ITSM workflows, not on how to use specific AI tools.
- **Gap:** Process-oriented, not tool-oriented. Useful as context but not as training. Our framework could reference ITSM integration as a use case in the buyer's case selection (Module 1 plug point).

### CompTIA AI+ / AI Fundamentals
- **CompTIA AI+ certification:** Vendor-neutral AI competency certification. Covers AI concepts, applications, ethics, and governance.
- **Structure:** Study guide + exam. Conceptual, not practical.
- **Audience:** IT professionals broadly, not specifically IT governance teams.
- **Gap:** Certification proves you can pass a test about AI. Our training proves you can build a system, verify its output, and write a rollout plan. The difference between knowing about and knowing how.

### Vendor-Specific Security/Governance Training
- **AWS AI Governance training:** Focused on responsible AI in AWS services.
- **Azure AI governance modules:** Focused on content safety, Responsible AI dashboard, and model monitoring.
- **Gap:** Platform-specific governance, not tool-usage governance. These train you to configure guardrails in a cloud console, not to evaluate whether an AI's output should be trusted.

---

## What Doesn't Exist (And Should)

### The "IT Team AI Readiness" Program
No one is offering a structured training that says: "Your IT team needs to simultaneously learn to use Claude, learn to evaluate its risks, and learn to plan its rollout — in a single program that produces actionable deliverables."

That's our framework. The market gap is real.

### The "Governance-Integrated Learning" Approach
Every existing program separates:
- **Skill training:** "Here's how to use the tool"
- **Governance training:** "Here's how to write policies about the tool"
- **Strategy training:** "Here's how to plan the rollout"

Our framework merges all three into a single arc where each module builds on the previous. Module 1 (skill) produces guardrails that become Module 2's (governance) input, which produces the judgment that informs Module 3's (strategy) output.

This integration is the core differentiator. No one else does it.

---

## Implications for Our Framework

### Strengthen
1. **Name the dual mandate explicitly.** In positioning materials, say: "This is training for IT teams who need to both USE and GOVERN AI tools. Most training does one or the other. This does both." The clarity of this positioning would be powerful.

2. **ITSM use case library.** For IT-team buyers specifically, pre-built cases mapped to ITSM processes (incident triage, change request analysis, knowledge base maintenance, capacity planning) would make Module 1's plug point immediately relevant. "Your Module 1 case: build a system for L1 incident triage using your Jira connector."

3. **Certification or credential path.** IT teams value credentials. A lightweight "Claude Governance Readiness" certificate (even self-assessed) that participants earn by completing the training could increase buyer appeal. Not a CompTIA-style exam — a portfolio-based credential: "here's my system, here's my hardened CLAUDE.md, here's my rollout recommendation."

4. **Post-training governance toolkit.** Module 2 teaches governance thinking. A toolkit delivered post-training (acceptable use policy template, data classification checklist, incident response procedure for AI errors, user access request form) turns the learning into immediately deployable artifacts.

### Protect
1. **The merge.** Don't let buyers or participants push you toward separating skill/governance/strategy into independent tracks. The integration IS the pedagogy. Separate them and you get three mediocre workshops instead of one powerful one.

2. **The IT-specific angle.** Resist pressure to make this "generic enterprise AI training." IT teams have specific anxieties (security, data classification, support burden, shadow AI) that generic training doesn't address. The specificity is the value.
