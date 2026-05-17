# Security Boundary

This public repository is intentionally separated from the private Eclipse runtime.

## What Is Safe To Publish

- High-level product descriptions
- Public architecture diagrams
- Capability summaries
- Roadmap notes
- Public disclaimers
- Security and privacy policy text

## What Must Stay Private

- Runtime and backend source code
- Agent prompts, internal chain-of-thought, private memory, and coordination files
- API keys, OAuth credentials, webhook secrets, and provider configuration
- Wallet private keys, seed phrases, or operational wallet addresses
- Raw wallet logs, transaction dumps, browser profiles, and local databases
- Trading strategy implementation details
- Exact private thresholds, private watchlists, and live execution logic
- Screenshots containing private dashboards, account IDs, tokens, or operational state

## Repository Hygiene

Before publishing any update:

1. Build the public repo from a clean docs-only folder.
2. Do not copy files from the private runtime tree.
3. Review staged files with `git status` and `git diff --cached`.
4. Scan for secret patterns before pushing.
5. Keep `.gitignore` strict even though the repository should not contain runtime artifacts.

## License Position

This repository does not publish the private Eclipse source code and does not grant permission to use private Eclipse systems. No open-source license is applied to the private runtime.

## Official Public Account

The only public X account currently listed for Eclipse in this repository is [@EclipseAI127305](https://x.com/EclipseAI127305). Do not add other social links unless the operator explicitly confirms them.
