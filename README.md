# Ribbon Finance

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Ribbon Finance is a DeFi structured products platform that helps users access crypto structured products through automated options strategies. The platform offers Theta Vaults (Decentralized Options Vaults) for covered calls and cash-secured puts, Ribbon Earn for yield optimization, Ribbon Treasury for institutional treasury management, and Ribbon Lend for unsecured lending.

Ribbon Finance merged with Aevo, a high-performance Layer-2 order-book decentralized exchange built on the OP Stack, creating a comprehensive DeFi options and perpetuals trading ecosystem.

## APIs

- **Aevo Exchange Public REST API** - Free unauthenticated access to market data, orderbooks, pricing, funding rates, and vault statistics at `https://api.aevo.xyz`
- **Aevo Exchange Private REST API** - Authenticated access for account management, order placement, position tracking, and trading operations using AEVO-KEY/AEVO-SECRET headers
- **Aevo Exchange WebSocket API** - Real-time streaming data for orderbooks, trades, fills, and positions via `wss://ws.aevo.xyz`
- **Ribbon Finance Subgraph API** - GraphQL API on The Graph for indexed on-chain vault performance data, APY history, and fee metrics

## Documentation

- Ribbon Finance Docs: https://docs.ribbon.finance/
- Aevo Docs: https://docs.aevo.xyz/
- Aevo API Reference: https://api-docs.aevo.xyz/
- GitHub: https://github.com/ribbon-finance

## Links

- [APIs.yml](apis.yml)
- [Plans](plans/plans.yml)
- [Rate Limits](rate-limits/rate-limits.yml)
- [FinOps](finops/finops.yml)
