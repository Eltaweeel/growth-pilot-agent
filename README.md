# Growth Pilot

Growth planning and experimentation agent for SME founders. This repository contains the editable configuration source for the Wesam.ai prototype, exact demo prompts, and a manual evaluation summary.

## Runtime and status

The runnable prototype uses Wesam.ai, a hosted agent platform. This is a configuration repository, not a standalone inference backend. The platform chooses the runtime model. No custom model training, custom MCP server, or standalone API service is included.

Verified on 10 October 2026: saved operating instructions, growth-experimentation skill, three references and an audit template, five native Jood Homes draft outputs, nine manual scenario checks, and an Egyptian Arabic metric regression. Scheduling is disabled. The messaging workflow is a design only. No customer impact has been measured.

## Reviewer run

For an already configured, authorized Wesam agent:

1. Open Growth Pilot and enter Preview with a manual task, without enabling scheduled work.
2. Paste `demo/PROMPTS.md` business-brief prompt.
3. Inspect the diagnosis, 30-day plan, experiment card, English campaign, and WhatsApp automation design. Missing evidence and unverified hypotheses must remain visible.
4. Run the synthetic metric and simulated approval prompts. Expected: EGP 2,000 cost per booking, CAC unknown without unique new customers, and exact action approval requested without execution.

Initial response latency can approach a minute. A fresh setup time has not been measured. The official competition asks for a judge run in under five minutes, so benchmark the actual reviewer route before claiming that. Existing private workspace access is not provided by the public repository. Arrange an authorized demonstration environment through the organizer. Never include account credentials in the repository.

## Recreate in your own workspace

Create a private agent named Growth Pilot, role Growth Intelligence & Experimentation Partner. Paste `agent/WESAM_INSTRUCTIONS.md` into Instructions. Upload `agent/SKILL.md` as its enabled skill. Upload CONSTITUTION.md, WORKFLOW.md, and REFERENCE_FILES.md as enabled references. Upload GROWTH_AUDIT_TEMPLATE.md and mark it Template. Disable long-term memory and past-conversation search for this prototype. Use manual Preview tasks. Do not enable a schedule or connect analytics/messaging accounts for the demo.

The instructions describe approval boundaries, but permission enforcement requires independent platform and connector testing. Wesam business tools were always enabled in the observed builder. Existing shared integrations were not audited.

## Source map

- `agent/WESAM_INSTRUCTIONS.md`: consolidated operating contract, persona, workflow and onboarding, with metric-grain correction.
- `agent/SKILL.md`: growth-experimentation playbook.
- `agent/CONSTITUTION.md`, `WORKFLOW.md`, `REFERENCE_FILES.md`: references.
- `agent/GROWTH_AUDIT_TEMPLATE.md`: expected audit structure.
- `demo/PROMPTS.md`: exact evaluation/demo tasks.
- `evidence/EVALUATION_SUMMARY.md`: observed results and limits.

## Scope

Jood Homes is the first owner-supplied case, not a verified performance case study. All demo funnel numbers are synthetic. The prototype is industry-agnostic and supports English and Arabic. Analytics integrations, deployed messaging, marketplace publication, scheduling, and measured time/cost/revenue benefits remain outside the verified prototype.

## Repository publication

Prepared for the Agents at Work competition as a public configuration-source repository. The project was designed and configured with AI assistance during October 1–10, 2026. The hosted prototype remains private; reviewer access must be arranged through an authorized demonstration environment. Do not add raw workspace transcripts, customer data, secrets, private builder identifiers, or credentials.
