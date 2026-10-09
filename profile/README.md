# Ryntra

**Launch once. The market keeps working.**

One app for onchain markets, built around your own wallet. Ryntra prepares
every action and shows it before you sign, your wallet signs it, and the chain
proves it. Non-custodial. Human-authorized. No profit promises.

## Ryntra on Solana — [ryntra.io](https://ryntra.io)

- **Launch** — a token in one signature on Meteora's bonding curve, with
  fair-launch rules, a creator lock and fee sharing fixed before launch.
- **Markets on Ryntra** — every market launched on Ryntra on one public page,
  with each market's health and a flight log of what happened and why.
- **Trade** — swap and spot on Solana tokens through Jupiter, and tokenized
  stocks from $1.
- **Recurring buys and rewards** — buy by your own rule and sign every
  purchase; cashback and friend invites.

The launch is the first step, and it is live. The market engine that runs a
market after it graduates — a liquidity ladder funded by the market's own fees
and a holder autopilot that sends fees only to the holder's own wallet — is
built and tested, and opens to people after its first full mainnet cycle.

The same Ryntra is an Android app in the **Solana dApp Store**: swap, markets,
portfolio and a token launch from the phone, signed in the Seeker's Seed Vault.

[Application](https://ryntra.io/app) · [Documentation](https://ryntra.io/docs) ·
[Website](https://ryntra.io)

## Ryntra on Arc — [arc.ryntra.io](https://arc.ryntra.io)

Dollar money on Circle's chain: send and receive USDC with a payment link,
swap any Arc token, spot with a live chart, bridge USDC in from other chains
and pay out a team — every operation with a receipt anyone can verify.

## Open source

- **[ryntra-solana-evidence](https://github.com/ryntra-io/ryntra-solana-evidence)** —
  Apache-2.0 TypeScript tools the product runs on: see what a token's issuer
  can do, preflight a transfer against your own rules and verify a receipt
  offline. SDK, MCP server and CLI.
  [Quick start](https://github.com/ryntra-io/ryntra-solana-evidence#try-it-in-30-seconds) ·
  [Build log](https://github.com/ryntra-io/ryntra-solana-evidence/blob/main/BUILDLOG.md) ·
  [Releases](https://github.com/ryntra-io/ryntra-solana-evidence/releases)
- **[ryntra-arc](https://github.com/ryntra-io/ryntra-arc)** — check a Ryntra
  receipt on Arc yourself: the schema, its seals and the operation read back
  from the chain.
  [Releases](https://github.com/ryntra-io/ryntra-arc/releases)

The product's own code is private. Partners and investors can ask for
read-only access to a snapshot of it.

## Boundaries

Ryntra never holds a private key or signs on anyone's behalf. Evidence,
policy, authorization, execution and settlement are separate facts; an
integrity check alone does not establish authorization or on-chain settlement.
The open-source tools are Apache-2.0 and read-only; the hosted applications and
their operational services are proprietary. No independent audit or
npm-registry package publication is claimed.

## Contact and security

[hello@ryntra.io](mailto:hello@ryntra.io) · [@Ryntra_io on X](https://x.com/Ryntra_io)

Read the repository's `SECURITY.md` before reporting a vulnerability. Never
send seed phrases, private keys or signing requests.

Maintained by **Dmytro Plavutskyi** ([@plavutskyi](https://github.com/plavutskyi)).
