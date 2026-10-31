# Scryfall

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

Scryfall is the most comprehensive free Magic - The Gathering card database. The Scryfall API exposes Cards (search, autocomplete, named, random, collection, by various IDs), Sets, Rulings, Symbology, Catalogs, Bulk Data downloads, and card-object Migrations. The service is community-funded (Patreon / Ko-fi) and offered free of charge under the Wizards of the Coast Fan Content Policy for community software, research, and content. The API is HTTPS-only, requires a descriptive User-Agent and Accept header on every request, and asks that clients keep sustained traffic under 10 requests per second.

**Areas:** Magic The Gathering · Card Data · Open Data · Free · Community Funded · Public APIs · Gaming · Card Games

## Scryfall on APIs.io

Everything profiled for Scryfall is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/scryfall/](https://apis.io/providers/scryfall/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Scryfall Bulk Data API](https://apis.io/apis/scryfall/scryfall-bulk-data-api/) — Large daily exports of the entire Scryfall card database.
- [Scryfall Cards API](https://apis.io/apis/scryfall/scryfall-cards-api/) — Look up, search, and fetch Magic card objects in many ways.
- [Scryfall Catalogs API](https://apis.io/apis/scryfall/scryfall-catalogs-api/) — Convenience lists of Magic data points (card names, types, supertypes, etc.).
- [Scryfall Migrations API](https://apis.io/apis/scryfall/scryfall-migrations-api/) — Records of card-object migrations and merges.
- [Scryfall Rulings API](https://apis.io/apis/scryfall/scryfall-rulings-api/) — Oracle rulings, WotC release notes, and Scryfall notes for a card.
- [Scryfall Sets API](https://apis.io/apis/scryfall/scryfall-sets-api/) — List and retrieve Magic: The Gathering set metadata.
- [Scryfall Symbology API](https://apis.io/apis/scryfall/scryfall-symbology-api/) — All card symbols and their semantics.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (14)

The data models the API reads and writes.

- [Scryfall Bulk Data](https://apis.io/schemas/scryfall/scryfall-bulk-data/)
- [Scryfall Card](https://apis.io/schemas/scryfall/scryfall-card/)
- [Scryfall Card Face](https://apis.io/schemas/scryfall/scryfall-card-face/)
- [Scryfall Card Symbol](https://apis.io/schemas/scryfall/scryfall-card-symbol/)
- [Scryfall Catalog](https://apis.io/schemas/scryfall/scryfall-catalog/)
- [Scryfall Error](https://apis.io/schemas/scryfall/scryfall-error/)
- [Scryfall Image URIs](https://apis.io/schemas/scryfall/scryfall-image-uris/)
- [Scryfall Legalities](https://apis.io/schemas/scryfall/scryfall-legalities/)
- [Scryfall List](https://apis.io/schemas/scryfall/scryfall-list/)
- [Scryfall Migration](https://apis.io/schemas/scryfall/scryfall-migration/)
- [Scryfall Prices](https://apis.io/schemas/scryfall/scryfall-prices/)
- [Scryfall Related Card](https://apis.io/schemas/scryfall/scryfall-related-card/)
- [Scryfall Ruling](https://apis.io/schemas/scryfall/scryfall-ruling/)
- [Scryfall Set](https://apis.io/schemas/scryfall/scryfall-set/)

#### JSON Structure (7)

Data models expressed in JSON Structure.

- [Scryfall Bulk Data Structure](https://apis.io/json-structure/scryfall/scryfall-bulk-data-structure/)
- [Scryfall Card Structure](https://apis.io/json-structure/scryfall/scryfall-card-structure/)
- [Scryfall Card Symbol Structure](https://apis.io/json-structure/scryfall/scryfall-card-symbol-structure/)
- [Scryfall Catalog Structure](https://apis.io/json-structure/scryfall/scryfall-catalog-structure/)
- [Scryfall Migration Structure](https://apis.io/json-structure/scryfall/scryfall-migration-structure/)
- [Scryfall Ruling Structure](https://apis.io/json-structure/scryfall/scryfall-ruling-structure/)
- [Scryfall Set Structure](https://apis.io/json-structure/scryfall/scryfall-set-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Scryfall Context](https://apis.io/jsonld/scryfall/scryfall-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Scryfall Domain Vocabulary](https://apis.io/vocabularies/scryfall/scryfall-vocabulary/)

#### Examples (9)

Example requests and responses.

- [Scryfall Bulk Data Example](https://apis.io/examples/scryfall/scryfall-bulk-data-example/)
- [Scryfall Card Example](https://apis.io/examples/scryfall/scryfall-card-example/)
- [Scryfall Card List Example](https://apis.io/examples/scryfall/scryfall-card-list-example/)
- [Scryfall Card Symbol Example](https://apis.io/examples/scryfall/scryfall-card-symbol-example/)
- [Scryfall Catalog Example](https://apis.io/examples/scryfall/scryfall-catalog-example/)
- [Scryfall Error Example](https://apis.io/examples/scryfall/scryfall-error-example/)
- [Scryfall Migration Example](https://apis.io/examples/scryfall/scryfall-migration-example/)
- [Scryfall Ruling Example](https://apis.io/examples/scryfall/scryfall-ruling-example/)
- [Scryfall Set Example](https://apis.io/examples/scryfall/scryfall-set-example/)

#### Collections (7)

Postman and Open Collection request collections.

- [Scryfall Bulk Data API](https://apis.io/collections/scryfall/open-scryfall-bulk-data-api/)
- [Scryfall Cards API](https://apis.io/collections/scryfall/open-scryfall-cards-api/)
- [Scryfall Catalogs API](https://apis.io/collections/scryfall/open-scryfall-catalogs-api/)
- [Scryfall Migrations API](https://apis.io/collections/scryfall/open-scryfall-migrations-api/)
- [Scryfall Rulings API](https://apis.io/collections/scryfall/open-scryfall-rulings-api/)
- [Scryfall Sets API](https://apis.io/collections/scryfall/open-scryfall-sets-api/)
- [Scryfall Symbology API](https://apis.io/collections/scryfall/open-scryfall-symbology-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Scryfall — jsonschema rules](https://apis.io/rules/scryfall/scryfall-jsonschema-spectral-rules/)
- [Scryfall API Rules](https://apis.io/rules/scryfall/scryfall-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Scryfall Domain Security](https://apis.io/security/scryfall/scryfall-domain-security/)
- [Scryfall Vulnerability Disclosure](https://apis.io/security/scryfall/scryfall-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Scryfall Plans Pricing](https://apis.io/plans/scryfall/scryfall-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Scryfall Rate Limits](https://apis.io/rate-limits/scryfall/scryfall-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://scryfall.com)
- [Documentation](https://scryfall.com/docs/api)
- [Getting started](https://scryfall.com/docs/api)
- [API reference](https://scryfall.com/docs/api/cards)
- [Pricing](https://scryfall.com/donate)
- [Support](https://scryfall.com/contact)
- [Changelog](https://scryfall.com/blog/category/api)
- [Blog](https://scryfall.com/blog/category/api)
- [Terms of service](https://scryfall.com/docs/api)
- [Privacy policy](https://scryfall.com/privacy)
- [GitHub](https://github.com/scryfall)

## API Evangelist rating

**Kin Score 48.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 56.6 |
| Contract governance | 23.5 |
| Operational transparency | 36.8 |
| Developer ergonomics | 65.5 |
| Access clarity | 36.8 |

**Agent readiness 23.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 30.4** — Government & Public Sector

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/scryfall/](https://apis.io/providers/scryfall/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Scryfall: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/scryfall/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
