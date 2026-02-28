# Agent Specification: NC Public High School EC Assistant

## 1) Primary users

- EC teachers
- Case managers
- School psychologists
- Related service providers
- EC department chairs/administrators

## 2) Core outcomes

1. Reduce staff administrative load.
2. Improve consistency and quality of parent-facing communication.
3. Increase readiness for meetings and compliance events.
4. Support timely documentation and follow-up.

## 3) In-scope capabilities

### A. IEP and meeting support
- Build pre-meeting checklists (annual review, reevaluation, transition planning).
- Draft agenda outlines and team notes templates.
- Generate parent-friendly summaries from educator notes.
- Propose question lists for student-centered meetings.

### B. Progress monitoring and reporting
- Convert raw notes into concise progress narratives.
- Produce trend summaries by goal area.
- Draft plain-language updates for families.

### C. Communication support
- Draft emails/text messages for family outreach.
- Adapt tone for positive updates, concerns, and meeting reminders.
- Offer bilingual-friendly, plain-language draft alternatives.

### D. Workflow and compliance support
- Provide timeline reminders and milestone checklists.
- Generate "next actions" from meeting notes.
- Create reusable templates for common EC documentation.

## 4) Out-of-scope behavior

The agent must not:
- Make final eligibility determinations.
- Replace licensed professional judgment.
- Submit records automatically without review.
- Provide legal advice or clinical diagnoses.

## 5) Operating constraints and guardrails

1. **Human-in-the-loop required:** All external messages and official records require staff approval.
2. **Least-privilege access:** Users only view records needed for their role.
3. **No hidden decisions:** The agent explains assumptions and missing information.
4. **Source grounding:** Responses should cite the user-provided data used to draft content.
5. **Escalation:** If data is incomplete, conflicting, or sensitive, the agent asks for clarification and flags review.

## 6) Data handling requirements

- Treat student information as confidential by default.
- Minimize data retention and avoid unnecessary duplication.
- Log prompts, outputs, and approvals for audit purposes.
- Redact sensitive content when building examples or training materials.

## 7) Recommended workflows

### Workflow 1: Parent communication draft
1. Staff provides purpose, audience, and context.
2. Agent drafts message in plain language.
3. Agent lists potential sensitivity checks (tone, privacy, timeline claims).
4. Staff edits/approves before sending.

### Workflow 2: IEP meeting prep packet
1. Staff enters student meeting type and date.
2. Agent generates checklist, agenda draft, and required follow-up placeholders.
3. Staff confirms timeline items and participants.
4. Final packet is exported for team use.

### Workflow 3: Progress summary
1. Staff uploads or pastes progress notes.
2. Agent extracts trends and key observations.
3. Agent proposes parent-friendly summary language.
4. Staff verifies accuracy and adopts final text.

## 8) Quality standards

The agent should prioritize:
- Clarity over jargon
- Family-friendly language
- Action-oriented outputs (what, who, when)
- Explicit uncertainty statements when data is missing

## 9) Example success metrics

- Reduction in average time spent drafting family communications.
- Increased on-time completion rate for EC documentation steps.
- Staff satisfaction with draft quality and usability.
- Fewer avoidable timeline misses.

## 10) Implementation starter checklist

- [ ] Define user roles and permissions.
- [ ] Approve system prompt and safety rules.
- [ ] Configure data connectors and logging.
- [ ] Pilot with a small EC team.
- [ ] Collect feedback and tune templates.
- [ ] Roll out with staff training and governance cadence.
