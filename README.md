# Vendia

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

Vendia is an enterprise data platform company founded by Tim Wagner (creator of AWS Lambda) and Shruthi Rao (founder of the AWS blockchain practice). Its flagship product is the Vendia MCP Gateway — a managed, multi-tenant Model Context Protocol server that gives AI agents governed, audited access to Amazon S3 buckets, third-party REST APIs described by OpenAPI/Swagger ("API Catalogs"), and remote MCP servers behind a single OAuth-protected endpoint. Underneath sits Vendia Share, a real-time distributed data platform that exposes each project as an auto-generated GraphQL API over a consensus-backed ledger, with fine-grained permissions, RBAC, schema evolution, file and folder APIs, block/dead-letter notifications, and analytical data products ingested from S3, Snowflake, Databricks, BigQuery, Cloudera, MySQL and PostgreSQL.

**Areas:** Company · MCP · Artificial Intelligence · Data Sharing · Data Platform · GraphQL · Agents · API Gateway · Data Governance

## Vendia on APIs.io

Everything profiled for Vendia is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/vendia/](https://apis.io/providers/vendia/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Vendia Share GraphQL API](https://apis.io/apis/vendia/vendia-share-graphql-api/) — Every Vendia project (Uni) is provisioned with an auto-generated GraphQL API derived from its JSON Schema data model — get_X / list_XItems / list_XVersions…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Vendia Notifications Webhooks](https://apis.io/asyncapis/vendia/vendia-notifications-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Vendia MCP Gateway](https://apis.io/servers/vendia/vendia-mcp-gateway/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Vendia Authentication](https://apis.io/security/vendia/vendia-authentication/)
- [Vendia Domain Security](https://apis.io/security/vendia/vendia-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Vendia Scopes](https://apis.io/scopes/vendia/vendia-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Vendia Plans](https://apis.io/plans/vendia/vendia-plans/)

#### Rate limits (1)

Published request limits.

- [Vendia Rate Limits](https://apis.io/rate-limits/vendia/vendia-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.vendia.com/)
- [Documentation](https://docs.vendia.com/platform/)
- [Getting started](https://docs.vendia.com/quickstart/)
- [API reference](https://docs.vendia.com/platform/operational/scalar-data/graphql/)
- [Pricing](https://www.vendia.com/platform/pricing/)
- [Sign up](https://share.vendia.net/signup)
- [Support](https://www.vendia.com/company/contact-us/)
- [Changelog](https://www.vendia.com/releases/)
- [Blog](https://www.vendia.com/blog/)
- [Security](https://www.vendia.com/legal/security-policy/)
- [Compliance](https://www.vendia.com/security/soc2)
- [Terms of service](https://www.vendia.com/legal/share-service-terms/)
- [Privacy policy](https://www.vendia.com/legal/privacy-policy/)
- [GitHub](https://github.com/vendia)
- [Status](https://status.vendia.com/)

## API Evangelist rating

**Kin Score 64.8** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 39.0 |
| Contract governance | 18.2 |
| Operational transparency | 84.2 |
| Developer ergonomics | 78.6 |
| Access clarity | 77.6 |

**Agent readiness 38.3** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 36.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/vendia/](https://apis.io/providers/vendia/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Vendia: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/vendia/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
