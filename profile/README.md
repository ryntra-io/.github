# Ryntra

**A non-custodial Risk, Strategy & Evidence OS for programmable assets.**

Ryntra turns an intended economic action into checkable evidence: what was
proposed, what the evidence supported, what a human authorized, and what the
network actually did — kept as four separate facts rather than one confident
summary.

[ryntra.io](https://ryntra.io)

---

## The products

| | |
|---|---|
| **Ryntra Home** | The human-facing workspace: research, monitoring, planning and a journal over one evidence kernel. |
| **Agent Control** | Operator control for agents that spend: proposals, policy, authorization and receipts, with the signature always outside the agent. |

Both are proprietary and are not in this organization.

## What is public here

| Repository | What it is | Licence |
|---|---|---|
| [ryntra-arc-evidence](https://github.com/ryntra-io/ryntra-arc-evidence) | Decision and settlement evidence on Arc Public Testnet: typed kernel, OpenAPI contract, SDK, HTTP reference implementation and offline receipt verification. | Apache-2.0 |
| [ryntra-agent-control](https://github.com/ryntra-io/ryntra-agent-control) | Read-only SDK, local MCP server, OpenAPI contract and a runnable reference flow for Agent Control. | Apache-2.0 |
| [ryntra-solana-evidence](https://github.com/ryntra-io/ryntra-solana-evidence) | Read-only Solana evidence kit: Token-2022 asset passports, transfer preflight against a declared owner policy, offline receipt verification, published JSON Schemas, SDK, MCP server and CLI. | Apache-2.0 |

These are deliberate, bounded surfaces: types, contracts, interfaces, examples,
fixtures and tests that a developer can read and run. Each one is built from an
explicit publication allowlist rather than by copying a folder.

**Selected developer interfaces and evidence tooling are open source. The Ryntra
product remains proprietary.** The production application, its infrastructure,
its risk and policy logic, its strategies and its provider adapters are
maintained privately and are not published here.

## What the code will not do

Ryntra holds no keys, signs nothing and moves no funds. Reads are bounded to
fixed provider origins and fail closed rather than guessing. A passing integrity
check proves that a document is internally consistent — never that an action was
authorized, executed or settled.

None of this code is audited, none of it is production-ready, and nothing here
is a hosted service. No package is published to a registry.

## Security

Report vulnerabilities through the affected repository's private GitHub Security
Advisory flow, and read its `SECURITY.md` first — each one states the exact
boundaries a report should say whether it crosses. Never send a seed phrase,
private key or signing request; no repository here has a code path that would
accept one.

## Maintainer

Built by **Dmytro Plavutskyi** ([@plavutskyi](https://github.com/plavutskyi)) ·
[ryntra.io](https://ryntra.io)
