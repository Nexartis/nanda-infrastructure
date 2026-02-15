# Nexartis Fork — nanda-infrastructure

This fork is maintained by [Nexartis](https://github.com/Nexartis) for [KnowYourModel](https://knowyourmodel.ai) (KYM) NANDA integration work.

## License

This project is licensed under the **MIT License** — Copyright (c) 2025 Project NANDA. See [LICENSE](LICENSE) for details. All upstream copyright and license notices are preserved per MIT requirements.

## Upstream

| | |
|---|---|
| **Upstream repo** | [projnanda/nanda-infrastructure](https://github.com/projnanda/nanda-infrastructure) |
| **Fork date** | 2026-02-11 |
| **License** | MIT |

## About Nexartis

**[Nexartis](https://nexartis.com)** builds AI infrastructure for the agentic web:

- **[KnowYourModel](https://knowyourmodel.ai)** — The trust registry for AI agents and models. Decentralized identity (DIDs), W3C Verifiable Credentials, and NANDA global agent discovery.
- **[CubiCube](https://cubicube.app)** — Full-stack web application generation platform.
- **[Pegasus HB3](https://github.com/Nexartis/pegasus-hb3-engine)** — Horizon Breakthrough v3 build engine.

## Purpose

KYM references the NANDA infrastructure agents as examples of agent-to-agent (A2A) communication patterns. This fork allows Nexartis to:
- Study the capability certifier, compliance enforcer, and observer evaluator patterns
- Test infrastructure agents against the KYM registry
- Prototype KYM-specific infrastructure agents

## Branch Strategy

- `dev` — default branch (protected). All feature branches open PRs to `dev`.
- `prod` — production branch (protected). PRs from `dev` → `prod` after validation.
- Feature branches are created from `dev` for all work.

## Syncing with Upstream

```bash
# One-time setup (already done):
git remote add upstream https://github.com/projnanda/nanda-infrastructure.git

# Sync upstream changes into dev:
git checkout dev
git fetch upstream
git merge upstream/main
# Resolve any conflicts, then push:
git push origin dev
```

## Contributing Back Upstream

If you make changes that would benefit the upstream project:
1. Create a branch from upstream's `main`: `git checkout -b fix/my-change upstream/main`
2. Make your changes, commit, and push to origin
3. Open a PR on [projnanda/nanda-infrastructure](https://github.com/projnanda/nanda-infrastructure/pulls) from `Nexartis:fix/my-change`

## Nexartis-Specific Changes

| Date | Change | Files |
|---|---|---|
| 2026-02-11 | Initial fork + `NEXARTIS.md` added | `NEXARTIS.md` |
| 2026-02-15 | Updated NEXARTIS.md with fork best practices | `NEXARTIS.md` |

## Contact

- **GitHub:** [Nexartis](https://github.com/Nexartis)
- **Website:** [nexartis.com](https://nexartis.com)
