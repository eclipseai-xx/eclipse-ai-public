# Public Verification

This repository exists so people can verify the public identity and technical shape of Eclipse AI without receiving private code or operational data.

## What A Public Viewer Can Verify

- The official GitHub repository is `eclipseai-xx/eclipse-ai-public`.
- The official X account listed here is [@EclipseAI127305](https://x.com/EclipseAI127305).
- The public repo is documentation-only.
- The security boundary is explicit.
- The private runtime is not published.

## Repository Contents

The intended public tree is limited to:

- `README.md`
- `NOTICE.md`
- `SECURITY.md`
- `docs/`
- `.github/ISSUE_TEMPLATE/`
- `.gitignore`

No backend source tree, runtime state folder, local database, `.env` file, wallet material, browser profile, or private strategy implementation should appear in this repository.

## Current Security Configuration

The public repo is configured with the following posture:

- Secret scanning enabled
- Secret scanning push protection enabled
- Vulnerability alerts enabled
- Automated security fixes enabled
- GitHub Actions disabled
- Wiki, Projects, and Discussions disabled
- Issues enabled for non-sensitive public documentation feedback
- Default branch protected against force pushes and deletion

## How To Read This Repo

Read it as a technical overview, not as an SDK or code release. The docs explain how Eclipse is organized and what classes of problems it solves. They intentionally do not expose the proprietary implementation.

## Public Claims Boundary

This repo can support claims such as:

- Eclipse has a defined architecture.
- Eclipse has documented capability areas.
- Eclipse has a security boundary.
- Eclipse has an official public identity.

This repo should not be used to claim:

- Guaranteed trading performance
- Financial advice
- Public availability of private runtime code
- Third-party access to private Eclipse systems
