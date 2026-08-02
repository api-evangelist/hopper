# Hopper

Hopper Inc. is a Montreal-based online travel agency and B2B travel fintech company. Its consumer app pairs flight, hotel, car, and homes booking with price prediction and "for any reason" fintech ancillaries (Price Freeze, CFAR, Disruption Guarantee). Hopper Technology Solutions (HTS) licenses those ancillaries, agentic AI servicing, white-label travel commerce, and loyalty portals to airlines, banks, and travel providers.

- https://www.hopper.com
- https://hts.hopper.com

## Duplicate — pending merge

This repo was created from the secondary-market harvest backlog against the Forge Global private-stock listing for "Hopper". That listing is **Hopper Inc.**, the same company already profiled in the network at:

- **`all/hopper-com`** — the survivor by depth (5 harvested HTS Airline API OpenAPIs, `authentication/`, `agentic-access/`, `security/`, `collections/`, blogs, screenshots)
- **`all/hopper-travel`** — a second, thinner duplicate (`plans/`, `rate-limits/`, `finops/`, blogs)

No artifact tree was generated here on purpose — a third profile would split one company across three apis.io pages and three Kin Scores. This slug should be merged into `hopper-com` and tombstoned in `api-search/network/_data/retired.yml` per the duplicate-provider-retirement procedure.

## Contract discovery (2026-08-01)

No agent card, `llms.txt`, `security.txt`, `/.well-known/*` document, or self-hosted machine-readable contract exists on any Hopper host. `www.hopper.com` and `hts.hopper.com` are single-page-app catch-alls that return HTTP 200 with an HTML shell for any path; `airlines-api.hopper.com` returns 404. The only real Hopper OpenAPI in the network was harvested from the HTS SDK repos under https://github.com/hopper and lives in `all/hopper-com/openapi/`.
