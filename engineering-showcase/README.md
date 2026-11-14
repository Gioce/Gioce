# Engineering showcase

**Private implementations. Public engineering decisions.**

This is a **read-only portfolio of architecture notes and technical case studies** for selected personal projects. It is not a mirror of the private repositories, a claim of production deployment, or a collection of proprietary code.

I build around three themes:

1. **Trustworthy automation** — deterministic validation, reproducibility, observability, and clear failure modes.
2. **Constrained intelligence** — useful AI agents with explicit boundaries rather than unlimited permissions.
3. **Research before execution** — realistic transaction costs, backtesting discipline, and explicit simulation/live boundaries.

## Deep dives

| Case study | The engineering question | What to look for |
| --- | --- | --- |
| [Forge AI — local-first AI systems](forge-ai.md) | Can an assistant be useful without surrendering privacy or control? | Retrieval, memory boundaries, auditable tool calls |
| [Systematic research & macro engines](quant-research.md) | What survives out-of-sample evaluation and trading friction? | Data normalization, point-in-time logic, risk controls |
| [FairFlight — honest cost comparison](fairflight.md) | What is the true cost of an offer after compulsory extras? | Provider adapters, normalization, cost modeling |
| [Neyra OS — media quality gates](media-qa.md) | How do we prevent a broken asset from being published? | Offline checks, manifests, deterministic QA, approval state |

## Also in the lab

| Project | Focus | Boundary |
| --- | --- | --- |
| **Triangular Arbitrage Scanner** | Bid/ask-aware route scanning with liquidity and fee filters | Paper simulation, not live orders |
| **Smart Accumulation** | Drawdown, momentum, and volatility as transparent accumulation signals | Research tool |
| **Small Cap Command Center** | A local research workspace for US small-cap screening | No live brokerage integration |
| **Wallet Scanner** | Public on-chain wallet discovery and ranking | Research and manual review |

## Principles

- **A dashboard is not a system.** Data lineage, error handling, and verification are the system.
- **A backtest is not a track record.** Assumptions, fees, slippage, and leakage decide whether a result is credible.
- **An AI agent is not trusted by default.** Tools should have scoped privileges and actions should be inspectable.
- **Automation should fail clearly.** Unknown states should become visible exceptions, not silent success.

> The diagrams in these pages are **conceptual illustrations**, intentionally simplified. They are not exact internal infrastructure maps or runnable implementation specifications.

[Back to GitHub profile](../README.md) · [Professional profile](https://www.linkedin.com/in/giorgiocesano)
