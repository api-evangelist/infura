# Infura (infura)

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

Infura (now MetaMask Developer) is a Web3 RPC provider operated by ConsenSys/MetaMask offering JSON-RPC and REST APIs for 23+ blockchain networks including Ethereum, Linea, Polygon, Arbitrum, Optimism, Base, Avalanche, BNB, Solana, Starknet, plus IPFS and a Gas API. Backed by the Decentralized Infrastructure Network (DIN) for failover.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/infura/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/infura/refs/heads/main/apis.yml)

## Tags

- Web3
- Blockchain
- RPC
- Infrastructure
- MetaMask
- ConsenSys

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-29

## APIs

### Infura JSON-RPC API

Multi-chain JSON-RPC over HTTPS and WebSockets across 23+ networks (Ethereum, Linea, Polygon, Arbitrum, Optimism, Base, Avalanche, BNB, Scroll, Mantle, Blast, Starknet, etc.).

- **Human URL:** [https://docs.metamask.io/services/reference/](https://docs.metamask.io/services/reference/)
- **Base URL:** `https://{network}.infura.io/v3/{apiKey}`

#### Tags

- JSON-RPC
- WebSocket
- Multi-chain

#### Properties

- [Documentation](https://docs.metamask.io/services/reference/)
- [AsyncAPI](asyncapi/infura-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/infura.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/infura.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Infura Solana JSON-RPC

Solana JSON-RPC and WebSocket endpoints.

- **Human URL:** [https://docs.metamask.io/services/reference/solana/](https://docs.metamask.io/services/reference/solana/)
- **Base URL:** `https://solana-mainnet.infura.io/v3/{apiKey}`

#### Tags

- JSON-RPC
- Solana

#### Properties

- [Documentation](https://docs.metamask.io/services/reference/solana/)
- [Postman Collection](collections/infura.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/infura.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Infura Gas API

REST API for EIP-1559 gas estimation, gas prices, and base-fee history across supported chains.

- **Human URL:** [https://docs.metamask.io/services/reference/gas-api/](https://docs.metamask.io/services/reference/gas-api/)
- **Base URL:** `https://gas.api.infura.io/v3/{apiKey}`

#### Tags

- REST
- Gas

#### Properties

- [Documentation](https://docs.metamask.io/services/reference/gas-api/)
- [Postman Collection](collections/infura.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/infura.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Infura IPFS API

REST API for pinning and retrieving content on IPFS.

- **Human URL:** [https://docs.metamask.io/services/reference/ipfs/](https://docs.metamask.io/services/reference/ipfs/)
- **Base URL:** `https://ipfs.infura.io:5001/api/v0`

#### Tags

- REST
- IPFS

#### Properties

- [Documentation](https://docs.metamask.io/services/reference/ipfs/)
- [Postman Collection](collections/infura.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/infura.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Infura NFT API

REST API for NFT metadata, ownership, and collection data on EVM chains.

- **Human URL:** [https://docs.metamask.io/services/reference/nft-api/](https://docs.metamask.io/services/reference/nft-api/)
- **Base URL:** `https://nft.api.infura.io/networks/{chainId}`

#### Tags

- REST
- NFT

#### Properties

- [Documentation](https://docs.metamask.io/services/reference/nft-api/)
- [Postman Collection](collections/infura.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/infura.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/INFURA)
- [LinkedIn](https://www.linkedin.com/company/infuraio)
- [Website](https://www.infura.io/)
- [Plans](plans/infura-plans-pricing.yml)
- [Rate Limits](rate-limits/infura-rate-limits.yml)
- [Fin Ops](finops/infura-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
