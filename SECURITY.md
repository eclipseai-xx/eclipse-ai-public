# Security Policy

## Scope

This public repository is documentation-only. It does not contain the private Eclipse runtime, backend source code, credentials, wallet data, browser profiles, local databases, logs, or production infrastructure configuration.

## Reporting

If you believe something sensitive was accidentally published here, open a GitHub issue with a high-level description only. Do not paste secrets, tokens, private keys, wallet seed material, private logs, or exploit details into a public issue.

## Publication Rules

The following must never be committed:

- `.env` files or environment-specific configuration
- API keys, OAuth tokens, webhook secrets, or provider credentials
- Wallet private keys, seed phrases, or private operational wallet addresses
- Raw transaction logs, wallet dumps, browser profiles, or local databases
- Runtime source code, backend implementation files, internal prompts, or private memory
- Screenshots that reveal dashboards, keys, account identifiers, or private operational state

## Current Posture

The repository is intentionally limited to public-facing documentation and high-level architecture descriptions. It should be safe to share publicly because it does not include executable backend code or private runtime artifacts.
