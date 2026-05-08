# Bandcamp (bandcamp)

Bandcamp is an artist-direct music marketplace and streaming platform. Its developer APIs are limited and gated to labels and merchandise fulfillment partners; access is granted on request and uses OAuth 2.0.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/bandcamp/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- Music, Marketplace, Indie, Audio, Sales, Merch

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Bandcamp Account API
Account API for retrieving the list of bands a user manages and basic account metadata. OAuth 2.0 client credentials with token endpoint at /oauth_token; access tokens expire after one hour.
- **Base URL:** `https://bandcamp.com/api`
- **Docs:** https://bandcamp.com/developer

### Bandcamp Sales Report API
Sales Report API for labels: retrieves sales line items (digital, physical, merch, subscriptions) over a date range. Restricted to labels.
- **Base URL:** `https://bandcamp.com/api`
- **Docs:** https://bandcamp.com/developer/sales

### Bandcamp Merch Orders API
Merch Orders API for fulfillment partners: list and update merchandise orders (mark shipped, set tracking). Restricted to merchandise fulfillment partners.
- **Base URL:** `https://bandcamp.com/api`
- **Docs:** https://bandcamp.com/developer/merch

## Common Properties
- [Website](https://bandcamp.com/)
- [Developer Portal](https://bandcamp.com/developer)
- [Plans](plans/bandcamp-plans-pricing.yml) — reconciled (free API; seller-share cost model)
- [RateLimits](rate-limits/bandcamp-rate-limits.yml) — partial (RPS not publicly documented)
- [FinOps](finops/bandcamp-finops.yml) — reconciled (FOCUS-aligned)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
