# Ryntra

Professional trading and strategies for Solana.

Ryntra connects market research, user-defined trading plans, wallet-authorized
execution and trading results in one workspace. Non-custodial. Human-authorized.
No profit promises. Feature availability is documented in the application.

[Application](https://ryntra.io/app) · [Documentation](https://ryntra.io/docs) ·
[Website](https://ryntra.io)

## Open-source Solana tools

The **[Solana Evidence Kit](https://github.com/ryntra-io/ryntra-solana-evidence)**
is the public developer toolkit: a typed SDK, a read-only MCP server, a CLI and
JSON Schemas for mint inspection, structural transfer preflight and offline
receipt verification.

[Source and quick start](https://github.com/ryntra-io/ryntra-solana-evidence) ·
[Automated checks](https://github.com/ryntra-io/ryntra-solana-evidence/actions) ·
[Releases](https://github.com/ryntra-io/ryntra-solana-evidence/releases)

New developer modules are added to that repository and named by what they do.
Repository availability does not imply that every capability is available in
the application; the repository documents its own runnable scope and
limitations.

## Boundaries

The kit does not hold private keys or sign transactions. Evidence, policy,
authorization, execution and settlement are separate facts; an integrity check
alone does not establish authorization or on-chain settlement. Read the
repository's security guidance before integrating. No independent audit or
npm-registry package publication is claimed.

The toolkit is Apache-2.0. The hosted Ryntra application and its operational
services are proprietary.

## Security and maintainer

Read [SECURITY.md](https://github.com/ryntra-io/ryntra-solana-evidence/blob/main/SECURITY.md)
before reporting a vulnerability. Never send seed phrases, private keys or
signing requests.

Maintained by **Dmytro Plavutskyi** ([@plavutskyi](https://github.com/plavutskyi)).
