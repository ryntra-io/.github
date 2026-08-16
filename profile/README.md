# Ryntra

**A non-custodial Risk, Strategy & Evidence OS for programmable assets.**

Ryntra turns an intended economic action into checkable evidence: what was
proposed, what the evidence supported, what a human authorized, and what the
network actually did — kept as four separate facts rather than one confident
summary.

[ryntra.io](https://ryntra.io)

---

## What is public here

| Repository | What it is |
|---|---|
| [ryntra-agent-control](https://github.com/ryntra-io/ryntra-agent-control) | Read-only SDK, local MCP server, OpenAPI contract and a runnable reference flow for Agent Control. Apache-2.0. |
| [ryntra-arc-demo](https://github.com/ryntra-io/ryntra-arc-demo) | Arc Public Testnet reference implementation for the decision and settlement evidence model. MIT. |

These are deliberate, bounded surfaces: types, contracts, interfaces, examples
and tests that a developer can read and run. The production application, its
infrastructure, the risk logic and internal planning are maintained privately.
Nothing here is a hosted service, and no package is published to a registry.

## What the code will not do

Ryntra holds no keys, signs nothing, and moves no funds. Reads are bounded to
fixed provider origins and fail closed rather than guessing. A passing
integrity check proves that a document is internally consistent — never that an
action was authorized, executed or settled.

## Contact

Built by [Dmytro Plavutskyi](https://github.com/plavutskyi) · [ryntra.io](https://ryntra.io)
