# Launch copy

These drafts are for Attractor's team to adapt and post. Publishing them
externally is intentionally a human decision.

## Production AI Checklist

Shipping an AI feature takes more than a convincing demo. We open-sourced
Production AI Checklist: a vendor-neutral set of controls, evidence templates,
and a small CI-ready TypeScript CLI covering evaluation, security, reliability,
cost, and operational ownership.

No API key is required. Start an assessment, attach evidence, and make missing
production controls visible before launch.

<https://github.com/attractorhq/production-ai-checklist>

## AI Evals Starter

We open-sourced a deliberately small Python starter for evaluating AI outputs
in CI. It runs against recorded JSONL fixtures, uses deterministic scorers, and
produces actionable JSON and Markdown reports without API keys.

<https://github.com/attractorhq/ai-evals-starter>

## RAG Quality Workshop

Plausible answers are not enough. Our self-paced TypeScript workshop starts
with a flawed support-search prototype and builds toward tested retrieval,
grounding, citations, injection resistance, access control, monitoring, and
cost awareness.

<https://github.com/attractorhq/rag-quality-workshop>

## Tips for Building AI

Building an AI product is mostly work around the model: choosing a useful
decision, designing for uncertainty, understanding context, evaluating failure,
keeping users in control, and owning the production system.

We collected 24 practical, opinionated tips for engineers, designers, product
people, and technical leaders. The guide is provider-neutral, openly licensed,
and meant to evolve through real experience.

<https://github.com/attractorhq/tips-for-building-ai>

## AI Failure Drills

The hardest time to decide who can stop an AI feature is during an incident. We
open-sourced eight facilitator-ready tabletop exercises for rehearsing quality
regressions, prompt injection, data exposure, provider outages, runaway agents,
unsafe actions, stale data, and monitoring blind spots.

Each drill takes 45–60 minutes, works offline, and includes roles, timed
injects, debrief prompts, follow-up tools, and an A4 printable pack. No API keys
or participant coding are required.

<https://github.com/attractorhq/ai-failure-drills>
