# Scryfall (scryfall)

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

Scryfall is the most comprehensive free Magic - The Gathering card database. The Scryfall API exposes Cards (search, autocomplete, named, random, collection, by various IDs), Sets, Rulings, Symbology, Catalogs, Bulk Data downloads, and card-object Migrations. The service is community-funded (Patreon / Ko-fi) and offered free of charge under the Wizards of the Coast Fan Content Policy for community software, research, and content. The API is HTTPS-only, requires a descriptive User-Agent and Accept header on every request, and asks that clients keep sustained traffic under 10 requests per second.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/scryfall/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/scryfall/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Games And Comics
- Magic The Gathering
- Card Data
- Open Data
- Free
- Community Funded
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### Scryfall API

The Scryfall REST API exposes Magic - The Gathering card data, set metadata, Oracle rulings, symbology, catalogs of in-game data points, daily bulk-data exports, and card-object migration records. The Cards surface alone supports lookup by Scryfall ID, set+number, Multiverse ID, MTGO ID, Arena ID, TCGplayer ID, Cardmarket ID, exact/fuzzy name, autocomplete, random draw, and batch collection. All responses use a discriminated object model keyed by the 'object' field.

- **Human URL:** [https://scryfall.com/docs/api](https://scryfall.com/docs/api)
- **Base URL:** `https://api.scryfall.com`

#### Tags

- Cards
- Sets
- Rulings
- Symbology
- Catalogs
- Bulk Data
- Magic The Gathering

#### Properties

- [Documentation](https://scryfall.com/docs/api)
- [API Reference](https://scryfall.com/docs/api/cards)
- [OpenAPI](openapi/scryfall-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/scryfall-card-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-card-face-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-related-card-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-image-uris-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-legalities-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-prices-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-set-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-ruling-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-card-symbol-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-catalog-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-bulk-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-migration-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scryfall-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/scryfall-card-structure.json)
- [JSON Structure](json-structure/scryfall-set-structure.json)
- [JSON Structure](json-structure/scryfall-ruling-structure.json)
- [JSON Structure](json-structure/scryfall-card-symbol-structure.json)
- [JSON Structure](json-structure/scryfall-catalog-structure.json)
- [JSON Structure](json-structure/scryfall-bulk-data-structure.json)
- [JSON Structure](json-structure/scryfall-migration-structure.json)
- [JSON-LD](json-ld/scryfall-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/scryfall-card-example.json)
- [Example](examples/scryfall-card-list-example.json)
- [Example](examples/scryfall-set-example.json)
- [Example](examples/scryfall-ruling-example.json)
- [Example](examples/scryfall-card-symbol-example.json)
- [Example](examples/scryfall-catalog-example.json)
- [Example](examples/scryfall-bulk-data-example.json)
- [Example](examples/scryfall-migration-example.json)
- [Example](examples/scryfall-error-example.json)
- [Rate Limits](rate-limits/scryfall-rate-limits.yml)
- [Authentication](https://scryfall.com/docs/api)
- [Errors](https://scryfall.com/docs/api/errors)

## Common Properties

- [Website](https://scryfall.com)
- [Documentation](https://scryfall.com/docs/api)
- [API Reference](https://scryfall.com/docs/api/cards)
- [Getting Started](https://scryfall.com/docs/api)
- [Blog](https://scryfall.com/blog/category/api)
- [Changelog](https://scryfall.com/blog/category/api)
- [Support](https://scryfall.com/contact)
- [Contact](https://scryfall.com/contact)
- [Plans](plans/scryfall-plans-pricing.yml)
- [Rate Limits](rate-limits/scryfall-rate-limits.yml)
- [Spectral Rules](rules/scryfall-rules.yml)
- [Vocabulary](vocabulary/scryfall-vocabulary.yml)
- [JSON-LD](json-ld/scryfall-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [GitHub Organization](https://github.com/scryfall)
- [GitHub Repository](https://github.com/scryfall/api-types)
- [GitHub Repository](https://github.com/scryfall/google-sheets)
- [GitHub Repository](https://github.com/scryfall/manamoji-slack)
- [GitHub Repository](https://github.com/scryfall/manamoji-discord)
- [GitHub Repository](https://github.com/scryfall/thopter)
- [GitHub Repository](https://github.com/scryfall/servo)
- [GitHub Repository](https://github.com/scryfall/scion)
- [GitHub Repository](https://github.com/scryfall/gatherer-bugs)
- [GitHub Repository](https://github.com/scryfall/art-game)
- [SDK](https://github.com/crookedneighbor/scryfall-client)
- [SDK](https://www.npmjs.com/package/scryfall-sdk)
- [SDK](https://github.com/NandaScott/Scrython)
- [SDK](https://docs.rs/scryfall)
- [Tools](https://github.com/cryppadotta/scryfall-mcp)
- [Tools](https://github.com/bmurdock/scryfall-mcp)
- [Tools](https://github.com/andershaig/mcp-scryfall)
- [Tools](https://github.com/joemocode/scryfall-mcp)
- [Tools](https://github.com/artillect/mtg-mcp-servers)
- [Pricing](https://scryfall.com/donate)
- [Terms of Service](https://scryfall.com/docs/api)
- [Privacy Policy](https://scryfall.com/privacy)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
