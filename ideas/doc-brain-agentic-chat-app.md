# Doc Brain — Agentic Chat App

A WhatsApp-style chat app where conversations are agentic — you can connect databases, other apps, and run agents inline.

## Details

- Each chat thread can have agents attached to it: a thread connected to a Postgres DB can answer data questions in natural language; a thread connected to GitHub can summarize PRs or triage issues.
- **Key differentiator:** Other apps can plug into Doc Brain as a communication and orchestration layer — it becomes the unified inbox for human-to-agent and agent-to-agent communication.
- **Core features:**
  - Familiar chat UI (WhatsApp-style threads, reactions, read receipts).
  - Agent marketplace: connect pre-built agents (DB query, web search, code execution) or bring your own via an API/webhook.
  - Inline tool calls rendered visually in the chat (e.g., a table result from a DB query shows as a formatted card).
  - Multi-agent orchestration: chain agents within a single thread to build workflows.
- **Integration surface:** REST/WebSocket API so external apps can send and receive messages, enabling Doc Brain to act as the "nervous system" for a stack of tools.
- Early use case: internal ops teams replacing a mix of Slack bots + dashboards with a single agentic chat interface.
