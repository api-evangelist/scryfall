# Scryfall (scryfall)

Scryfall is the most comprehensive free Magic - The Gathering card database. The Scryfall API exposes Cards (search, autocomplete, named, random, collection, by various IDs), Sets, Rulings, Symbology, Catalogs, Bulk Data downloads, and card-object Migrations. The service is community-funded (Patreon / Ko-fi) and offered free of charge under the Wizards of the Coast Fan Content Policy for community software, research, and content. The API is HTTPS-only, requires a descriptive User-Agent and Accept header on every request, and asks that clients keep sustained traffic under 10 requests per second.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/scryfall/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Games And Comics, Magic The Gathering, Card Data, Open Data, Free, Community Funded, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### Scryfall API

The Scryfall REST API exposes Magic - The Gathering card data, set metadata, Oracle rulings, symbology, catalogs of in-game data points, daily bulk-data exports, and card-object migration records. The Cards surface alone supports lookup by Scryfall ID, set+number, Multiverse ID, MTGO ID, Arena ID, TCGplayer ID, Cardmarket ID, exact/fuzzy name, autocomplete, random draw, and batch collection. All responses use a discriminated object model keyed by the 'object' field.

**Human URL:** [https://scryfall.com/docs/api](https://scryfall.com/docs/api)

**Base URL:** `https://api.scryfall.com`

#### Tags:

 - Cards, Sets, Rulings, Symbology, Catalogs, Bulk Data, Magic The Gathering

#### Properties

- [Documentation](https://scryfall.com/docs/api)
- [APIReference](https://scryfall.com/docs/api/cards)
- [OpenAPI](openapi/scryfall-openapi.yml)
- [JSONSchema — Card](json-schema/scryfall-card-schema.json)
- [JSONSchema — CardFace](json-schema/scryfall-card-face-schema.json)
- [JSONSchema — RelatedCard](json-schema/scryfall-related-card-schema.json)
- [JSONSchema — ImageUris](json-schema/scryfall-image-uris-schema.json)
- [JSONSchema — Legalities](json-schema/scryfall-legalities-schema.json)
- [JSONSchema — Prices](json-schema/scryfall-prices-schema.json)
- [JSONSchema — Set](json-schema/scryfall-set-schema.json)
- [JSONSchema — Ruling](json-schema/scryfall-ruling-schema.json)
- [JSONSchema — CardSymbol](json-schema/scryfall-card-symbol-schema.json)
- [JSONSchema — Catalog](json-schema/scryfall-catalog-schema.json)
- [JSONSchema — BulkData](json-schema/scryfall-bulk-data-schema.json)
- [JSONSchema — Migration](json-schema/scryfall-migration-schema.json)
- [JSONSchema — List](json-schema/scryfall-list-schema.json)
- [JSONSchema — Error](json-schema/scryfall-error-schema.json)
- [JSONStructure — Card](json-structure/scryfall-card-structure.json)
- [JSONStructure — Set](json-structure/scryfall-set-structure.json)
- [JSONStructure — Ruling](json-structure/scryfall-ruling-structure.json)
- [JSONStructure — CardSymbol](json-structure/scryfall-card-symbol-structure.json)
- [JSONStructure — Catalog](json-structure/scryfall-catalog-structure.json)
- [JSONStructure — BulkData](json-structure/scryfall-bulk-data-structure.json)
- [JSONStructure — Migration](json-structure/scryfall-migration-structure.json)
- [JSONLD](json-ld/scryfall-context.jsonld)
- [Example — Card](examples/scryfall-card-example.json)
- [Example — CardList](examples/scryfall-card-list-example.json)
- [Example — Set](examples/scryfall-set-example.json)
- [Example — Ruling](examples/scryfall-ruling-example.json)
- [Example — CardSymbol](examples/scryfall-card-symbol-example.json)
- [Example — Catalog](examples/scryfall-catalog-example.json)
- [Example — BulkData](examples/scryfall-bulk-data-example.json)
- [Example — Migration](examples/scryfall-migration-example.json)
- [Example — Error](examples/scryfall-error-example.json)
- [NaftikoCapability — Cards](capabilities/scryfall-cards.yaml)
- [NaftikoCapability — Sets](capabilities/scryfall-sets.yaml)
- [NaftikoCapability — Rulings](capabilities/scryfall-rulings.yaml)
- [NaftikoCapability — Symbology](capabilities/scryfall-symbology.yaml)
- [NaftikoCapability — Catalogs](capabilities/scryfall-catalogs.yaml)
- [NaftikoCapability — Bulk Data](capabilities/scryfall-bulk-data.yaml)
- [NaftikoCapability — Migrations](capabilities/scryfall-migrations.yaml)
- [RateLimits](rate-limits/scryfall-rate-limits.yml)
- [Errors](https://scryfall.com/docs/api/errors)

## Common Properties

- [Website](https://scryfall.com)
- [Documentation](https://scryfall.com/docs/api)
- [APIReference](https://scryfall.com/docs/api/cards)
- [GettingStarted](https://scryfall.com/docs/api)
- [Blog](https://scryfall.com/blog/category/api)
- [ChangeLog](https://scryfall.com/blog/category/api)
- [Support](https://scryfall.com/contact)
- [Contact](https://scryfall.com/contact)
- [Plans](plans/scryfall-plans-pricing.yml)
- [RateLimits](rate-limits/scryfall-rate-limits.yml)
- [SpectralRules](rules/scryfall-rules.yml)
- [Vocabulary](vocabulary/scryfall-vocabulary.yml)
- [JSONLD](json-ld/scryfall-context.jsonld)
- [GitHubOrganization](https://github.com/scryfall)
- [GitHubRepository — scryfall/api-types](https://github.com/scryfall/api-types)
- [GitHubRepository — scryfall/google-sheets](https://github.com/scryfall/google-sheets)
- [GitHubRepository — scryfall/manamoji-slack](https://github.com/scryfall/manamoji-slack)
- [GitHubRepository — scryfall/manamoji-discord](https://github.com/scryfall/manamoji-discord)
- [GitHubRepository — scryfall/thopter](https://github.com/scryfall/thopter)
- [GitHubRepository — scryfall/servo](https://github.com/scryfall/servo)
- [GitHubRepository — scryfall/scion](https://github.com/scryfall/scion)
- [GitHubRepository — scryfall/gatherer-bugs](https://github.com/scryfall/gatherer-bugs)
- [GitHubRepository — scryfall/art-game](https://github.com/scryfall/art-game)
- [SDK — scryfall-client (JavaScript)](https://github.com/crookedneighbor/scryfall-client)
- [SDK — scryfall-sdk (TypeScript)](https://www.npmjs.com/package/scryfall-sdk)
- [SDK — scrython (Python)](https://github.com/NandaScott/Scrython)
- [SDK — scryfall (Rust)](https://docs.rs/scryfall)
- [Tools — cryppadotta/scryfall-mcp](https://github.com/cryppadotta/scryfall-mcp)
- [Tools — bmurdock/scryfall-mcp](https://github.com/bmurdock/scryfall-mcp)
- [Tools — andershaig/mcp-scryfall](https://github.com/andershaig/mcp-scryfall)
- [Tools — JoeMoCode/Scryfall-MCP](https://github.com/joemocode/scryfall-mcp)
- [Tools — artillect/mtg-mcp-servers](https://github.com/artillect/mtg-mcp-servers)
- [Pricing — Community Funding](https://scryfall.com/donate)
- [TermsOfService](https://scryfall.com/docs/api)
- [PrivacyPolicy](https://scryfall.com/privacy)

## Features

| Name | Description |
|------|-------------|
| Comprehensive card database | Every Magic - The Gathering printing across paper, MTGO, and Arena with localized translations. |
| Fulltext search query language | Powerful Scryfall search syntax supporting color, type, format legality, set, price, oracle text, and more. |
| Daily bulk-data exports | Five daily JSON exports - oracle_cards, unique_artwork, default_cards, all_cards, and rulings - for offline ingestion. |
| Multi-resolution card imagery | Six image renderings per card - small, normal, large, png, art_crop, border_crop. |
| Up-to-date market prices | USD / EUR / MTGO Tix pricing across normal, foil, and etched finishes. |
| Oracle rulings | Wizards of the Coast Oracle rulings plus Scryfall editorial notes per card. |
| Symbology with SVG renderings | All Magic mana and text symbols with parser endpoint and downloadable SVG art. |
| Catalogs of in-game data points | Canonical lists of card names, creature types, supertypes, keyword abilities, and more for autocomplete and validation. |
| Free with attribution | No API key, no paid tier - usage is governed by attribution and a documented rate-limit policy. |

## Use Cases

| Name | Description |
|------|-------------|
| Deck building applications | Powering search, autocomplete, and legality checks in deck-builder web and mobile apps. |
| Price tracking and portfolio tools | Aggregating USD / EUR / Tix prices across reprints for collection valuation. |
| Discord and Slack card-lookup bots | Inline card images, prices, and rulings inside team chat channels. |
| LLM and AI agent integrations | MCP servers exposing card data, rulings, and search to Claude and other agents. |
| Research and dataset publishing | Bulk-data exports feed academic and journalistic research on Magic's design history and card economy. |
| Spoiler and set-release coverage | Tracking newly-spoiled cards into and through release day via the Sets and Cards endpoints. |
| Custom card-rendering and proxy printing | High-resolution PNG and SVG art for personal-use proxies and educational content. |
| Tournament-legality verification | Format-legality checks for Standard, Pioneer, Modern, Legacy, Vintage, Pauper, Commander, Brawl, Alchemy, and historic formats. |

## Integrations

| Name | Description |
|------|-------------|
| TCGplayer | Cross-referenced card identifiers and purchase links via tcgplayer_id. |
| Cardmarket | Cross-referenced card identifiers and purchase links via cardmarket_id. |
| Cardhoarder | MTGO price feed integration and purchase links. |
| Wizards of the Coast Gatherer | Cross-referenced via multiverse_ids for canonical Oracle text. |
| Magic Online (MTGO) | Identifier mapping via mtgo_id and mtgo_foil_id. |
| Magic Arena | Identifier mapping via arena_id. |
| EDHREC | Commander-format recommendation data linked from card.related_uris. |
| Anthropic Claude (MCP) | Multiple community MCP servers expose Scryfall to Claude Desktop and other MCP clients. |
| Google Sheets | Official Scryfall =SCRYFALL() custom function for spreadsheet card lookups. |
| Alfred (macOS) | Official Scryfall Scion workflow for fast card search from Alfred. |

## Solutions

| Name | Description |
|------|-------------|
| Community software | Powering thousands of fan-built deck builders, collection trackers, and tools. |
| Magic content creators | Source of authoritative card data and imagery for podcasts, articles, and video content. |
| Researchers | Bulk-data exports enabling longitudinal analysis of Magic's design and economy. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Scryfall OpenAPI](openapi/scryfall-openapi.yml)

### JSON Schema

- [Card](json-schema/scryfall-card-schema.json)
- [CardFace](json-schema/scryfall-card-face-schema.json)
- [RelatedCard](json-schema/scryfall-related-card-schema.json)
- [ImageUris](json-schema/scryfall-image-uris-schema.json)
- [Legalities](json-schema/scryfall-legalities-schema.json)
- [Prices](json-schema/scryfall-prices-schema.json)
- [Set](json-schema/scryfall-set-schema.json)
- [Ruling](json-schema/scryfall-ruling-schema.json)
- [CardSymbol](json-schema/scryfall-card-symbol-schema.json)
- [Catalog](json-schema/scryfall-catalog-schema.json)
- [BulkData](json-schema/scryfall-bulk-data-schema.json)
- [Migration](json-schema/scryfall-migration-schema.json)
- [List](json-schema/scryfall-list-schema.json)
- [Error](json-schema/scryfall-error-schema.json)

### JSON Structure

- [Card](json-structure/scryfall-card-structure.json)
- [Set](json-structure/scryfall-set-structure.json)
- [Ruling](json-structure/scryfall-ruling-structure.json)
- [CardSymbol](json-structure/scryfall-card-symbol-structure.json)
- [Catalog](json-structure/scryfall-catalog-structure.json)
- [BulkData](json-structure/scryfall-bulk-data-structure.json)
- [Migration](json-structure/scryfall-migration-structure.json)

### JSON-LD

- [Scryfall Context](json-ld/scryfall-context.jsonld)

### Examples

- [Card](examples/scryfall-card-example.json)
- [CardList](examples/scryfall-card-list-example.json)
- [Set](examples/scryfall-set-example.json)
- [Ruling](examples/scryfall-ruling-example.json)
- [CardSymbol](examples/scryfall-card-symbol-example.json)
- [Catalog](examples/scryfall-catalog-example.json)
- [BulkData](examples/scryfall-bulk-data-example.json)
- [Migration](examples/scryfall-migration-example.json)
- [Error](examples/scryfall-error-example.json)

## Capabilities

Naftiko capabilities for each Scryfall resource surface.

| Capability | File | Operations | Adapters |
|------------|------|------------|----------|
| Scryfall Cards | [scryfall-cards.yaml](capabilities/scryfall-cards.yaml) | 11 | REST + MCP |
| Scryfall Sets | [scryfall-sets.yaml](capabilities/scryfall-sets.yaml) | 4 | REST + MCP |
| Scryfall Rulings | [scryfall-rulings.yaml](capabilities/scryfall-rulings.yaml) | 5 | MCP |
| Scryfall Symbology | [scryfall-symbology.yaml](capabilities/scryfall-symbology.yaml) | 2 | MCP |
| Scryfall Catalogs | [scryfall-catalogs.yaml](capabilities/scryfall-catalogs.yaml) | 17 | MCP |
| Scryfall Bulk Data | [scryfall-bulk-data.yaml](capabilities/scryfall-bulk-data.yaml) | 3 | MCP |
| Scryfall Migrations | [scryfall-migrations.yaml](capabilities/scryfall-migrations.yaml) | 2 | MCP |

## Plans

- [Scryfall Plans & Pricing](plans/scryfall-plans-pricing.yml) — free public API plus optional Patreon/Ko-fi community funding (no paid tier).

## Rate Limits

- [Scryfall Rate Limits](rate-limits/scryfall-rate-limits.yml) — under 10 RPS sustained, 50–100 ms delay between calls, /cards/collection capped at 2 RPS with up to 75 identifiers per batch, bulk-data preferred for large ingestion. Required headers: User-Agent (descriptive) and Accept.

## Vocabulary

- [Scryfall Domain Vocabulary](vocabulary/scryfall-vocabulary.yml) — Magic - The Gathering domain terms covering resources, layouts, formats, identifiers, and headers used across the API.

## Rules

- [Scryfall Spectral Rules](rules/scryfall-rules.yml) — Spectral ruleset enforcing Scryfall conventions (HTTPS-only, Title-Case summaries, required `object` discriminator on response schemas, paginated List shape).

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
