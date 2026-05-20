# Hermes and OpenClaw Integrations

Eclipse can work with adjacent local-agent tooling without making those tools the core runtime. Hermes and OpenClaw are used as integration surfaces around Eclipse, while the private Eclipse runtime remains the system of record for market intelligence, memory, risk review, simulation, and operator controls.

This page describes the relationship at a public level. It does not publish private source code, prompts, workspace paths, credentials, wallet state, exact ports, or operational configuration.

## Summary

| Component | Public role inside Eclipse |
| --- | --- |
| Eclipse runtime | The private local operator that owns ingestion, wallet intelligence, risk review, simulation, learning, and operator-facing workflows. |
| Hermes | A local agent compatibility lane used for tool-call parsing, local environment readiness, and durable cross-agent decision continuity. |
| OpenClaw | An optional local sidecar/gateway layer used for agent workspace onboarding, heartbeat-style coordination, and external agent access to approved Eclipse context. |

## Hermes

Hermes is treated as a local agent interoperability layer, not as a replacement for Eclipse.

Publicly describable uses include:

- Accepting Hermes-style tool-call output from compatible local models.
- Helping local agent processes find their expected environment when Eclipse starts.
- Writing compact decisions into the shared continuity layer under a Hermes agent identity when Hermes participates in work.
- Keeping multi-agent handoffs focused on durable decisions instead of raw logs.

Hermes does not make private Eclipse strategy public. It does not publish wallet lists, prompts, credentials, private runtime memory, or trading logic.

## OpenClaw

OpenClaw is used as an optional sidecar around Eclipse. It can provide an agent gateway, dashboard, and heartbeat-oriented workspace integration for local agents that need to coordinate with Eclipse.

Publicly describable uses include:

- Registering Eclipse as an agent workspace for local sidecar access.
- Running heartbeat checks against a small operator-approved checklist.
- Routing approved agent coordination into compact shared decisions.
- Keeping OpenClaw separate from the main Eclipse web runtime.
- Allowing external local agents to participate without giving them unrestricted private state.

OpenClaw being present does not mean the public repository contains the private runtime. It is an integration layer around Eclipse, not the published source of Eclipse.

## Shared Continuity

Eclipse, Hermes, OpenClaw, and other approved local agents can write compact coordination records into a shared decision layer. The intent is continuity:

1. Search prior decisions before meaningful work.
2. Perform the work in the correct private or public boundary.
3. Save a short durable decision after meaningful work.
4. Avoid storing secrets, raw logs, private wallet material, browser data, or noisy traces.

This gives local agents memory of what changed without exposing sensitive operational data.

## Boundary Rules

Hermes and OpenClaw integrations follow the same publication boundary as the rest of Eclipse.

Safe to describe publicly:

- Integration roles
- High-level agent coordination
- Tool-call compatibility categories
- Heartbeat and handoff concepts
- Separation between core runtime and sidecars

Not safe to publish:

- Private runtime source code
- Exact private prompts or model-routing instructions
- API keys, OAuth data, cookies, browser profiles, or session state
- Wallet addresses, watchlists, raw wallet logs, or transaction dumps
- Exact operational thresholds, strategy formulas, and execution routes
- Internal workspace paths or environment-specific configuration

## Design Principle

Eclipse uses Hermes and OpenClaw to make local agents easier to coordinate. The core system remains private, local-first, and operator-controlled.
