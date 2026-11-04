<h1 align="center">mr-hrydarie</h1>

<p align="center">
  <b>Security Researcher — Smart Contract &amp; Web Application Security</b>
</p>

<p align="center">
  I find vulnerabilities in production systems, prove them with working exploits,<br/>
  and quantify the impact before I report. No scanner noise. No theoretical findings.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/EVM%20%2F%20Solidity-smart%20contract%20auditing-1f6feb?style=flat-square" alt="EVM / Solidity" />
  <img src="https://img.shields.io/badge/Solana%20%2F%20Anchor-program%20security-1f6feb?style=flat-square" alt="Solana / Anchor" />
  <img src="https://img.shields.io/badge/Soroban%20%2F%20Rust-Stellar%20contracts-1f6feb?style=flat-square" alt="Soroban / Rust" />
  <img src="https://img.shields.io/badge/API%20%26%20Web-application%20security-1f6feb?style=flat-square" alt="API and Web" />
</p>

---

### About

Independent bug bounty hunter working directly with project teams and public programmes. My reports are built to survive triage: a root-cause trace to the exact code path, a self-contained proof of concept that reproduces the issue end to end, and a loss figure derived from the programme's own severity rubric.

My method is surface-first. I map the complete attack surface before testing anything, then work the *interactions* between features, roles, and backend processes — the states a system reaches when individually safe components combine. An HTTP 200 is not proof an operation succeeded, and an error message is not proof a system is safe; I verify state changes, side effects, and downstream consequences.

### Expertise

- **Smart contract security** — EVM/Solidity, Solana/Anchor, Soroban (Stellar), Cosmos SDK (Go), Move
- **Accounting & invariant breaks** — share-price and oracle manipulation, solvency drift, cap/rate-limit accounting flaws, reward and fee miscalculation
- **Authorization & trust boundaries** — missing or mis-scoped access control, IDOR, API-key and agent-key scope excess, session and signature replay
- **Web & API security** — cross-account data exposure, unauthenticated read layers, webhook and payment-flow trust, business-logic abuse

### Public record

- **Published advisories (credited reporter):**
  - [GHSA-6qf8-mhpm-jqf6](https://github.com/priors-agents/priors/security/advisories/GHSA-6qf8-mhpm-jqf6) — AutoRepay plan misdirection, Priors (Robinhood Chain)
  - [GHSA-pr4v-mc2c-995x](https://github.com/priors-agents/priors/security/advisories/GHSA-pr4v-mc2c-995x) — x402 double-signing on retry, @priors/agentkit
- **Platforms:** HackerOne · Bugcrowd · YesWeHack · HackenProof — identity-verified accounts
- **Self-hosted programmes:** direct engagements under each project's own SECURITY.md; reports are private by default and disclosed only in coordination with the vendor

### How I work

1. **Reproduce** — every claim is demonstrated live or on a local fork/validator, never inferred from code reading alone
2. **Quantify** — impact stated in concrete terms: funds at risk, accounts affected, preconditions an attacker actually needs
3. **Report responsibly** — through the programme's own channel, with reproduction steps a maintainer can run in minutes

### Tooling

<p>
  <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" alt="Solidity" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Foundry-1C1C1C?style=flat-square" alt="Foundry" />
  <img src="https://img.shields.io/badge/Slither-1C1C1C?style=flat-square" alt="Slither" />
  <img src="https://img.shields.io/badge/Echidna-1C1C1C?style=flat-square" alt="Echidna" />
  <img src="https://img.shields.io/badge/Anchor-1C1C1C?style=flat-square" alt="Anchor" />
</p>

### Contact

- Security reports & research inquiries: **hrydarie@gmail.com**
- Bug reports for a specific project go through that project's programme channel first

<p align="center"><i>Prove it. Quantify it. Then report it.</i></p>
