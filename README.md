# NC High School Exceptional Children (EC) Agent Blueprint

This repository contains a practical, implementation-ready blueprint for an AI assistant that supports a **public high school in North Carolina** and its **Exceptional Children (EC) department**.

## Purpose

The agent is designed to help EC staff save time, improve consistency, and strengthen family communication while staying within legal and district boundaries.

It is intended to assist with:
- IEP and meeting preparation
- Parent communication drafts
- Progress-monitoring summaries
- Compliance checklists and scheduling support
- Staff-facing workflow support and document generation

## Safety and compliance first

The agent should be deployed with strict safeguards for:
- **FERPA-protected data handling**
- **IDEA procedural timelines and documentation support**
- Human review before any external communication or official record submission
- Role-based access and audit logging

See [`docs/agent-spec.md`](docs/agent-spec.md) for the full specification and [`prompts/system-prompt.md`](prompts/system-prompt.md) for a ready-to-use baseline system prompt.
