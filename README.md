# Zenscrape (zenscrape)

Zenscrape is a web scraping API that returns the rendered HTML of any target URL while handling proxy rotation, headless-browser JavaScript rendering, geotargeting, and Cloudflare protection. A single GET /get request fetches a page through a rotating pool of standard or premium residential proxies, with a /status endpoint for remaining credits and an HTTP proxy-mode interface for existing proxy-based clients.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zenscrape/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zenscrape/refs/heads/main/apis.yml)

## Tags

- Web Scraping
- Proxy
- HTML
- Data Extraction
- JavaScript Rendering

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Zenscrape Scrape API

Fetches the HTML of a target URL via GET /get, routing the request through rotating standard or premium proxies with optional headless-browser JavaScript rendering, geolocation, device emulation, and custom/forwarded headers. Request cost varies from 1 to 25 credits by configuration.

- **Human URL:** [https://app.zenscrape.com/documentation](https://app.zenscrape.com/documentation)
- **Base URL:** `https://app.zenscrape.com/api/v1`

#### Tags

- Web Scraping
- HTML
- Proxy
- JavaScript Rendering

#### Properties

- [Documentation](https://app.zenscrape.com/documentation)
- [API Reference](https://app.zenscrape.com/documentation)
- [OpenAPI](openapi/zenscrape-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zenscrape.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zenscrape.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zenscrape Account API

Returns the remaining request credits for the authenticated account via GET /status, supporting usage monitoring and quota-aware client logic.

- **Human URL:** [https://app.zenscrape.com/documentation](https://app.zenscrape.com/documentation)
- **Base URL:** `https://app.zenscrape.com/api/v1`

#### Tags

- Account
- Usage
- Credits

#### Properties

- [Documentation](https://app.zenscrape.com/documentation)
- [API Reference](https://app.zenscrape.com/documentation)
- [OpenAPI](openapi/zenscrape-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zenscrape.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zenscrape.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/zenscrape)
- [Website](https://zenscrape.com/)
- [Documentation](https://app.zenscrape.com/documentation)
- [Plans](plans/zenscrape-plans-pricing.yml)
- [Rate Limits](rate-limits/zenscrape-rate-limits.yml)
- [Fin Ops](finops/zenscrape-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
