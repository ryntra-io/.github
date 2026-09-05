# Ryntra

A Solana-first product for financial actions governed by user-defined rules.

Non-custodial. Human-authorized. No profit promises.

[Application](https://ryntra.io/app) · [Documentation](https://ryntra.io/docs) ·
[Website](https://ryntra.io)

## Open-source developer tools

Start with the **[Solana Evidence Kit](https://github.com/ryntra-io/ryntra-solana-evidence)**:
inspect SPL and Token-2022 mints, evaluate transfer preflights against a declared
policy, and verify supplied receipts offline. It includes a typed SDK, a local
MCP server, a CLI, JSON Schemas and reproducible tests.

[Source and quick start](https://github.com/ryntra-io/ryntra-solana-evidence) ·
[Automated checks](https://github.com/ryntra-io/ryntra-solana-evidence/actions)

| Repository | Scope |
|---|---|
| [Solana Evidence Kit](https://github.com/ryntra-io/ryntra-solana-evidence) | Read-only mint inspection, structural transfer preflight and offline receipt verification |
| [Agent Control Developer Kit](https://github.com/ryntra-io/ryntra-agent-control) | Read-only client, MCP server, API contract and non-executing reference examples |
| [Arc Evidence Kit](https://github.com/ryntra-io/ryntra-arc-evidence) | Typed evidence contracts, headless SDK and offline receipt-verification examples |

These are separately versioned developer tools within one Ryntra product.
Repository availability does not imply that every adapter or capability is
available in the application. Each repository documents its own runnable scope
and limitations.

## Boundaries

The kits do not hold private keys or sign transactions. Evidence, policy,
authorization, execution and settlement are separate facts; an integrity check
alone does not establish authorization or on-chain settlement. Read the
repository-specific security guidance before integrating. No independent audit
or npm-registry package publication is claimed.

Selected developer interfaces and evidence tooling are open source. The Ryntra
product remains proprietary. Included source is licensed under Apache-2.0; the
hosted application and operational infrastructure are separate.

## Security and maintainer

Read SECURITY.md in the affected repository before reporting a vulnerability.
[Solana security policy](https://github.com/ryntra-io/ryntra-solana-evidence/blob/main/SECURITY.md).
Never send seed phrases, private keys or signing requests.

Maintained by **Dmytro Plavutskyi** ([@plavutskyi](https://github.com/plavutskyi)).
