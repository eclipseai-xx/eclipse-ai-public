# Privacy and Data Handling

Eclipse is designed as a local-first private runtime. The public repository intentionally contains no private runtime data.

## Data Not Published Here

- Private user data
- Browser sessions, cookies, profiles, or signed-in account state
- Wallet private keys, seed phrases, wallet watchlists, or raw wallet activity logs
- Operational wallet addresses or transaction signing configuration
- API keys, OAuth tokens, provider credentials, and webhook URLs
- Agent prompts, private memory, coordination logs, and runtime traces
- Backend source code, local databases, or infrastructure configuration

## Public Documentation Principle

Public documentation should explain the system's shape, not its exploitable internals. The repo is intended to make Eclipse understandable and verifiable without publishing enough detail to reconstruct private execution logic.

## Operator Control

Social posting and account actions are operator-controlled. Public documentation should not imply that third parties can access Eclipse accounts, wallets, browser sessions, private runtime state, or local agent tools.

## Memory Design

Eclipse is designed to retain compact learning summaries and decisions instead of raw private dumps. That distinction matters: durable intelligence is useful, but raw logs, secrets, wallet material, and browser state do not belong in public memory or public repositories.

## Public Source Context

When Eclipse comments on public events, the preferred design is to attach source context through a quote, repost, source URL, or thread. Public commentary should be traceable to public material without exposing private runtime state.
