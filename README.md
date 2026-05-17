# Eclipse AI

Eclipse is a private autonomous AI agent system for real-time market intelligence, wallet-behavior analytics, narrative tracking, paper-trade simulation, and operator-controlled social execution.

This repository is the public verification and overview page for the project. It is intentionally documentation-only. The private runtime, backend source code, trading logic, wallet data, prompts, logs, browser profiles, API keys, and infrastructure configuration are not included.

## What Eclipse Does

- Tracks public market and social signals across crypto-native sources.
- Monitors wallet behavior, wallet reputation, and clustered funding patterns.
- Scores token opportunities using confluence from wallet activity, market structure, narrative strength, and risk evidence.
- Simulates paper-trade entries, exits, position sizing, market cap at entry, and PnL for strategy evaluation.
- Maintains long-running memory so prior decisions, outcomes, and operator feedback can improve later behavior.
- Uses browser automation for public-source research while keeping signed-in profiles and runtime state local.
- Supports operator-controlled X/Twitter posting, replies, quote context, and source-aware public commentary.

## Public vs Private Boundary

This repo contains only safe public documentation.

Not published here:

- Backend/runtime source code
- Agent prompts and private reasoning traces
- API keys, provider credentials, webhook URLs, or auth tokens
- Wallet private keys, seed phrases, or operational wallet addresses
- Raw wallet logs, transaction dumps, browser profiles, local databases, or `.env` files
- Strategy implementation details that would expose execution logic
- Internal coordination state or private memory files

See [Security Boundary](docs/SECURITY_BOUNDARY.md) for the full publication policy.

## System Areas

- **Signal ingestion:** public market feeds, launch/migration signals, Dex data, and social/news context.
- **Wallet intelligence:** tracked-wallet monitoring, reputation scoring, round-trip outcome learning, and funding-graph analysis.
- **Risk analysis:** holder concentration checks, suspicious clustering patterns, liquidity/volume sanity checks, and manipulation evidence.
- **Narrative intelligence:** internet-culture and news-aware context mapping so meme/lore strength can be separated from generic noise.
- **Paper trading:** simulated entries/exits with fast scalp logic, confidence sizing, and runner handling for unusually strong narratives.
- **Shared memory:** compact decision records and self-knowledge for cross-agent continuity without storing raw secrets or noisy logs.
- **Social automation:** source-attached opinions, quote/retweet context, reply safety, and thread-safe long-post behavior.

## Documentation

- [Architecture Overview](docs/ARCHITECTURE.md)
- [Capabilities](docs/CAPABILITIES.md)
- [Security Boundary](docs/SECURITY_BOUNDARY.md)
- [Privacy and Data Handling](docs/PRIVACY.md)
- [Roadmap](docs/ROADMAP.md)
- [FAQ](docs/FAQ.md)

## Official Links

- X/Twitter: [@EclipseAI127305](https://x.com/EclipseAI127305)
- GitHub: [eclipseai-xx/eclipse-ai-public](https://github.com/eclipseai-xx/eclipse-ai-public)

## Status

Eclipse is an active private research/runtime project. This public repository exists so people can verify the project identity and understand the system at a high level without exposing the proprietary backend.

## Disclaimer

Eclipse is experimental software. Nothing in this repository is financial advice, trading advice, or an invitation to copy trades. Any live or simulated market behavior should be treated as high risk.
