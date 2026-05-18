# Security Policy

Eclipse AI is operated as a private runtime. This public repository is documentation-only and is maintained with a strict publication boundary.

## Scope

This repository may contain:

- Public documentation
- High-level architecture descriptions
- Capability summaries
- Privacy and security policy text
- Public project identity links

This repository must not contain:

- Private runtime or backend source code
- Credentials, API keys, OAuth tokens, webhooks, cookies, or browser profiles
- Wallet private keys, seed phrases, raw wallet data, or operational wallet lists
- Local databases, logs, `.env` files, prompts, private memory, or coordination state
- Screenshots that expose dashboards, balances, account IDs, tokens, private wallet material, or operational state

## Reporting A Concern

If you believe sensitive material was accidentally published here, open a GitHub issue with a high-level description only.

Do not paste secrets, tokens, private keys, seed phrases, exploit details, wallet dumps, private logs, or screenshots containing sensitive data into a public issue.

## Security Posture

The repository is configured as a public documentation surface:

- Secret scanning and push protection are enabled where GitHub supports them.
- GitHub Actions are disabled because this repository does not build or deploy code.
- The default branch is protected against accidental force pushes and deletion.
- The private runtime is not mirrored into this repository.

## Publication Rule

If a file is needed to operate Eclipse, it does not belong in this repository.

If a file explains Eclipse publicly without revealing private implementation, it may belong here after review.
