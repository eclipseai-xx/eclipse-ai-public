# Capabilities

Eclipse combines autonomous agent orchestration, market intelligence, wallet analytics, narrative analysis, simulation, and source-aware social tooling.

This page describes capabilities at a public level. It does not publish private strategy code, wallet lists, exact thresholds, credentials, prompts, or runtime internals.

## Market Intelligence

| Capability | Public description |
| --- | --- |
| Launch and migration awareness | Tracks public token lifecycle events and distinguishes raw launches from post-migration follow-through. |
| Market structure review | Evaluates market cap, liquidity, volume, holder context, and freshness. |
| Post-graduation monitoring | Watches for tokens that show real activity after initial launch mechanics. |
| Volume quality checks | Treats volume as context, not proof, and considers whether flow looks useful or suspicious. |
| Market-cap tiering | Separates low-cap, medium-cap, and higher-cap setups so evaluation is not one-size-fits-all. |

## Wallet Analytics

| Capability | Public description |
| --- | --- |
| Tracked-wallet monitoring | Watches selected wallets for public on-chain activity. |
| Wallet reputation | Scores wallets from observed behavior and historical outcomes. |
| Round-trip learning | Studies buy-to-sell sequences, hold time, entry zone, exit behavior, and result. |
| Co-buyer discovery | Looks for wallets that repeatedly appear near profitable moves. |
| Funding-graph analysis | Studies relationships between fresh wallets, funders, and clustered activity. |
| Probation and graduation | Lets newly discovered wallets earn trust over time instead of becoming instant signal. |

## Narrative Intelligence

| Capability | Public description |
| --- | --- |
| Social context tracking | Watches public posts, repeated references, and source motion. |
| Meme and lore classification | Separates generic ticker noise from stronger cultural or technical narratives. |
| News and event hooks | Connects public market behavior to relevant cultural, tech, political, or macro events. |
| Source attribution | Preserves the public source behind an opinion or alert when available. |
| Outcome feedback | Learns which narrative categories historically helped or hurt decisions. |

## Risk Controls

| Capability | Public description |
| --- | --- |
| Holder concentration review | Flags concentrated ownership and obvious distribution problems. |
| Cluster review | Looks for suspicious wallet clustering and coordinated patterns. |
| Liquidity checks | Treats thin or stale liquidity as risk evidence. |
| Wash-volume awareness | Avoids treating suspicious volume as automatically bullish. |
| Paper-first evaluation | Uses simulation and outcome tracking to evaluate strategy changes without exposing private infrastructure. |

## Agent Runtime

- Local-first runtime design
- Long-running memory and coordination state
- Browser automation lanes for public-source research
- Shared decision capture across agent tools
- Health and status surfaces for runtime monitoring
- Operator-facing chat and alert workflows

## Agent Interop

| Capability | Public description |
| --- | --- |
| Hermes compatibility | Accepts compatible local-model tool-call formats and keeps Hermes decisions tied into compact shared continuity. |
| OpenClaw sidecar support | Lets approved local agents coordinate with Eclipse through an optional gateway and heartbeat-style workspace layer. |
| Shared decision layer | Stores concise decisions from participating agents without publishing raw logs, prompts, credentials, wallet data, or runtime state. |
| Boundary enforcement | Keeps public documentation separate from private source code, strategy logic, environment configuration, and operational data. |

## Social Automation

| Capability | Public description |
| --- | --- |
| Mercury persona | Uses a short, cryptic, source-aware public voice for Eclipse's X/social boundary. |
| Meme-intel selection | Prefers meme-relevant market and narrative context over generic commentary. |
| Source-grounded posting | Uses quote, repost, source URL, visible thread, media, or link context when available. |
| Reply guardrails | Avoids duplicate replies, self-reply loops, thin-context replies, and spam patterns. |
| Thread-safe posting | Preserves connected context for long-form thoughts when needed. |
| Public boundary control | Avoids private runtime details, prompts, provider data, wallet material, raw logs, and exact strategy rules. |
