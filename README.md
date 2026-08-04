# Hopper

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
