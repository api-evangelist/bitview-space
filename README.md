# Bitview

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Bitview provides a comprehensive Bitcoin data platform offering real‑time blockchain analytics, charting tools, and developer APIs. Users can explore blocks, transactions, mempool activity, fees, and various on‑chain metrics through a web UI and programmatic endpoints. The service is open‑source, licensed under MIT for code and CC BY‑4.0 for data, encouraging community contributions and transparent research. Bitview aims to empower developers, researchers, and enthusiasts with reliable, high‑quality Bitcoin data and visualizations.

**Areas:** Company

## Bitview on APIs.io

Everything profiled for Bitview is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/bitview-space/](https://apis.io/providers/bitview-space/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Bitview Addresses API](https://apis.io/apis/bitview-space/bitview-space-addresses-api/) — Address balances, transaction history and UTXOs. Supports P2PKH, P2SH, P2WPKH, P2WSH, P2TR and P2A addresses, and P2PK public keys in hex (33 or 65 bytes).…
- [Bitview Blocks API](https://apis.io/apis/bitview-space/bitview-space-blocks-api/) — Blocks by hash or height: headers, transaction lists and raw block bytes. *[Mempool.space](https://mempool.space/docs/api/rest) compatible.*
- [Bitview Fees API](https://apis.io/apis/bitview-space/bitview-space-fees-api/) — Fee estimation and projected mempool blocks. *[Mempool.space](https://mempool.space/docs/api/rest) compatible.*
- [Bitview General API](https://apis.io/apis/bitview-space/bitview-space-general-api/) — Difficulty adjustments and BTC/USD price data. *[Mempool.space](https://mempool.space/docs/api/rest) compatible.*
- [Bitview Mempool API](https://apis.io/apis/bitview-space/bitview-space-mempool-api/) — Mempool statistics, transaction IDs, fee histogram and recent transactions. *[Mempool.space](https://mempool.space/docs/api/rest) compatible.*
- [Bitview Mining API](https://apis.io/apis/bitview-space/bitview-space-mining-api/) — Mining statistics including pool distribution, hashrate, difficulty adjustments, block rewards, and fee rates across configurable time periods.…
- [Bitview Oracle API](https://apis.io/apis/bitview-space/bitview-space-oracle-api/) — On-chain BTC/USD price derived purely from round-dollar payment patterns in transaction outputs, with no external price feed. Payment activity is binned on…
- [Bitview Series API](https://apis.io/apis/bitview-space/bitview-space-series-api/) — Thousands of historical Bitcoin series across calendar, block and entity indexes, as JSON or CSV. Series are renamed only in releases, each rename listed in…
- [Bitview Server API](https://apis.io/apis/bitview-space/bitview-space-server-api/) — API metadata, health monitoring, and OpenAPI specifications.
- [Bitview Silent Payments API](https://apis.io/apis/bitview-space/bitview-space-silent-payments-api/) — BIP352 silent payments for light wallets: BlindBit oracle v1's HTTP API (what spdk and Dana, Bull Bitcoin and blindbitd speak) under `/blindbit/mainnet/`,…
- [Bitview Transactions API](https://apis.io/apis/bitview-space/bitview-space-transactions-api/) — Transactions by txid: details, confirmation status, raw hex, merkle proofs and output spends. *[Mempool.space](https://mempool.space/docs/api/rest) compatible.*
- [Bitview URPD API](https://apis.io/apis/bitview-space/bitview-space-urpd-api/) — UTXO Realized Price Distribution. For each (cohort, block) pair, supply is grouped by the price at which each UTXO was last moved. Distributions are…
- [Bitview UTXO Set API](https://apis.io/apis/bitview-space/bitview-space-utxo-set-api/) — The UTXO set by creation height: what remains unspent of each block's outputs after a block or a UTC day, and what a block or a day changed. Reconstructed…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Bitview Agentic Access](https://apis.io/agentic-access/bitview-space/bitview-space-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [BlockFeeRatesEntry](https://apis.io/schemas/bitview-space/bitview-space-block-fee-rates-entry/)
- [BlockInfoV1](https://apis.io/schemas/bitview-space/bitview-space-block-info-v1/)
- [BlockTemplate](https://apis.io/schemas/bitview-space/bitview-space-block-template/)
- [DifficultyAdjustment](https://apis.io/schemas/bitview-space/bitview-space-difficulty-adjustment/)
- [OracleBlock](https://apis.io/schemas/bitview-space/bitview-space-oracle-block/)
- [Transaction](https://apis.io/schemas/bitview-space/bitview-space-transaction/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Bitview Space Context](https://apis.io/jsonld/bitview-space/bitview-space-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Bitview API Rules](https://apis.io/rules/bitview-space/bitview-space-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Bitview Domain Security](https://apis.io/security/bitview-space/bitview-space-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://bitview.space/)
- [API reference](https://bitview.space/api/)
- [Support](https://bitview.space/support/)
- [Terms of service](https://bitview.space/terms/)
- [Privacy policy](https://bitview.space/privacy/)

## API Evangelist rating

**Kin Score 38.2** — thin · rubric 0.27.0 · scored 2026-11-16

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 57.7 |
| Contract governance | 79.1 |
| Operational transparency | 0.0 |
| Developer ergonomics | 19.0 |
| Access clarity | 21.1 |

**Agent readiness 28.8** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 18.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/bitview-space/](https://apis.io/providers/bitview-space/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Bitview: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/bitview-space/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
