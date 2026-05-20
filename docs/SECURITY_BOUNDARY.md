# Security Boundary

This repository is intentionally separated from the private Eclipse runtime. Its purpose is public verification and high-level technical explanation, not source-code distribution.

## Safe To Publish

- Public product descriptions
- High-level architecture diagrams
- Capability summaries
- Public roadmap themes
- High-level Mercury persona role and guardrails
- High-level Hermes/OpenClaw integration roles
- High-level persistent memory and cross-agent continuity concepts
- Security and privacy policy text
- Official public links confirmed by the operator
- Non-sensitive documentation corrections

## Never Publish

- Runtime or backend source code
- Agent prompts, private reasoning traces, model routing prompts, or internal memory
- API keys, OAuth credentials, webhook secrets, provider configuration, or auth tokens
- Wallet private keys, seed phrases, operational wallet addresses, raw wallet lists, or transaction dumps
- Browser profiles, cookies, local databases, session files, and signed-in account state
- Exact private thresholds, watchlists, scoring formulas, execution routes, or strategy implementation
- Private Mercury prompts, exact decision rules, source context payloads, post history, or social account session material
- Private Hermes/OpenClaw configuration, prompts, local paths, ports, gateway state, or agent workspace files
- Screenshots containing private dashboards, account IDs, tokens, keys, balances, wallet addresses, or operational state
- Internal coordination files from the private Eclipse workspace

## Repository Hygiene Checklist

Before publishing any update:

1. Work from the clean public documentation checkout.
2. Review `git status --short` and `git diff --cached`.
3. Confirm the staged file list is documentation or GitHub config only.
4. Run a high-confidence secret scan.
5. Avoid screenshots unless they are manually redacted and approved.
6. Keep `.gitignore` strict even though runtime artifacts should never enter this checkout.
7. Do not copy files from the private runtime tree.

## Public Wording Rule

It is safe to explain categories of capability. It is not safe to reveal implementation details that would let someone reconstruct Eclipse's private execution logic.

Examples:

| Safe wording | Unsafe wording |
| --- | --- |
| "Eclipse reviews wallet reputation." | "Here is the full wallet list and scoring formula." |
| "Eclipse uses market-cap and liquidity context." | "Here are the exact private thresholds and routing code." |
| "Eclipse stores compact learning summaries for cross-agent continuity." | "Here are raw logs, prompts, memory files, coordination records, and runtime traces." |
| "Eclipse can attach public source context to posts." | "Here are cookies, browser profiles, tokens, or signed-in session data." |

## License Position

This public repository does not grant a license to private Eclipse code, systems, prompts, strategies, models, or infrastructure. No private runtime source code is published here.

## Official Public Account

The official public X account listed in this repository is [@EclipseAI127305](https://x.com/EclipseAI127305). Do not add other social links unless explicitly confirmed by the operator.
