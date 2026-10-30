# Loops

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

Loops is an email platform built for software companies, combining marketing campaigns, product and lifecycle automation, and transactional email on one contact model. Its REST API v1 exposes 64 operations across contacts, contact properties, mailing lists, audience segments, events and event patterns, campaigns, transactional emails, email messages authored in its own LMX markup, themes, components, uploads and workflow graphs, plus a 17-event signed webhook surface. Loops publishes its OpenAPI 3.1 document openly, ships first-party SDKs for JavaScript, Go, PHP, Ruby and Nuxt, a Go CLI, four versioned Agent Skills, and a hosted OAuth-protected MCP server at mcp.loops.so. Pricing is based on stored subscribed contacts rather than send volume, with a permanent free tier. The operating company is Astrodon Corporation.

**Areas:** Email · Email API · Marketing Automation · Transactional Email · Lifecycle Email · Webhook · Software-as-a-Service · Communications · Developer Tools · MCP · Agents · Campaigns

## Loops on APIs.io

Everything profiled for Loops is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/loops/](https://apis.io/providers/loops/)** — or go straight to one of the APIs or properties below.

### APIs (21)

- [Loops API key API](https://apis.io/apis/loops/loops-api-key-api/) — Validate a Loops API key and discover which team it belongs to. 1 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Audience segments API](https://apis.io/apis/loops/loops-audience-segments-api/) — Read and create saved audience segments used to target campaigns and workflows. 3 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Campaign groups API](https://apis.io/apis/loops/loops-campaign-groups-api/) — Organize campaigns into groups. 4 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Campaigns API](https://apis.io/apis/loops/loops-campaigns-api/) — Create, target, schedule and update email campaigns. 4 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Components API](https://apis.io/apis/loops/loops-components-api/) — Create, read and update reusable LMX email components. 4 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Configuration API](https://apis.io/apis/loops/loops-configuration-api/) — Read team configuration, including dedicated sending IP addresses. 1 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Contact properties API](https://apis.io/apis/loops/loops-contact-properties-api/) — Create and list the custom properties available on contacts. 2 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Contacts API](https://apis.io/apis/loops/loops-contacts-api/) — Create, update, find and delete contacts, and manage suppression status. 6 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Email messages API](https://apis.io/apis/loops/loops-email-messages-api/) — Read, update, preview and Guardian-validate the LMX body of campaigns, workflow emails and transactional templates. 4 operation(s) in the Loops REST API v1…
- [Loops Event patterns API](https://apis.io/apis/loops/loops-event-patterns-api/) — Read the event patterns Loops has detected from incoming events, including their observed properties. 3 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Events API](https://apis.io/apis/loops/loops-events-api/) — Send events that update contact activity and trigger published workflows. 1 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Mailing lists API](https://apis.io/apis/loops/loops-mailing-lists-api/) — List the mailing lists in your account. 1 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Themes API](https://apis.io/apis/loops/loops-themes-api/) — Create, read and update reusable email themes. 4 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Transactional emails API](https://apis.io/apis/loops/loops-transactional-emails-api/) — Create, edit, publish, list and send transactional email templates with data variables. 8 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Transactional groups API](https://apis.io/apis/loops/loops-transactional-groups-api/) — Organize transactional emails into groups. 4 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Uploads API](https://apis.io/apis/loops/loops-uploads-api/) — Upload image assets for use in emails via a presigned-URL flow. 2 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Workflow nodes API](https://apis.io/apis/loops/loops-workflow-nodes-api/) — Create, read, update, delete and reroute the nodes of a workflow graph. 7 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops Workflows API](https://apis.io/apis/loops/loops-workflows-api/) — List, create, inspect and update automation workflows and their mailing-list targeting. 5 operation(s) in the Loops REST API v1 (OpenAPI 1.21.6).
- [Loops MCP Server](https://apis.io/apis/loops/loops-mcp-server/) — Remote Model Context Protocol server for Loops, reachable at https://mcp.loops.so over Streamable HTTP with OAuth 2.0 (PKCE, scope "mcp"). Exposes four…
- [Loops Webhooks](https://apis.io/apis/loops/loops-webhooks/) — Outbound event surface. Seventeen signed event types covering contact lifecycle, mailing-list membership, and email delivery, engagement and complaint…
- [Loops Webhooks API](https://apis.io/apis/loops/loops-webhooks-api/) — Events Loops sends to your configured webhook endpoint when certain events happen in your account. Configure an endpoint in Settings → Webhooks. Each…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Loops Webhooks](https://apis.io/asyncapis/loops/loops-webhooks-asyncapi/)

#### Event channels (17)

Individual events and webhooks the provider emits.

- [/](https://apis.io/channels/loops/campaignemailsent/)
- [/](https://apis.io/channels/loops/contactcreated/)
- [/](https://apis.io/channels/loops/contactdeleted/)
- [/](https://apis.io/channels/loops/contactmailinglistsubscribed/)
- [/](https://apis.io/channels/loops/contactmailinglistunsubscribed/)
- [/](https://apis.io/channels/loops/contactunsubscribed/)
- [/](https://apis.io/channels/loops/emailclicked/)
- [/](https://apis.io/channels/loops/emaildelivered/)
- [/](https://apis.io/channels/loops/emailhardbounced/)
- [/](https://apis.io/channels/loops/emailopened/)
- [/](https://apis.io/channels/loops/emailresubscribed/)
- [/](https://apis.io/channels/loops/emailsoftbounced/)
- [/](https://apis.io/channels/loops/emailspamreported/)
- [/](https://apis.io/channels/loops/emailunsubscribed/)
- [/](https://apis.io/channels/loops/loopemailsent/)
- [/](https://apis.io/channels/loops/testingtestevent/)
- [/](https://apis.io/channels/loops/transactionalemailsent/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [loops](https://apis.io/servers/loops/loops/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Loops Agentic Access](https://apis.io/agentic-access/loops/loops-agentic-access/)

#### Collections (11)

Postman and Open Collection request collections.

- [Loops OpenAPI Spec API key API](https://apis.io/collections/loops/open-loops-api-key-api/)
- [Loops OpenAPI Spec API key Campaigns API](https://apis.io/collections/loops/open-loops-campaigns-api/)
- [Loops OpenAPI Spec API key Components API](https://apis.io/collections/loops/open-loops-components-api/)
- [Loops OpenAPI Spec API key Contact properties API](https://apis.io/collections/loops/open-loops-contact-properties-api/)
- [Loops OpenAPI Spec API key Contacts API](https://apis.io/collections/loops/open-loops-contacts-api/)
- [Loops OpenAPI Spec API key Dedicated sending IPs API](https://apis.io/collections/loops/open-loops-dedicated-sending-ips-api/)
- [Loops OpenAPI Spec API key Email messages API](https://apis.io/collections/loops/open-loops-email-messages-api/)
- [Loops OpenAPI Spec API key Events API](https://apis.io/collections/loops/open-loops-events-api/)
- [Loops OpenAPI Spec API key Mailing lists API](https://apis.io/collections/loops/open-loops-mailing-lists-api/)
- [Loops OpenAPI Spec API key Themes API](https://apis.io/collections/loops/open-loops-themes-api/)
- [Loops OpenAPI Spec API key Transactional emails API](https://apis.io/collections/loops/open-loops-transactional-emails-api/)

#### Overlays (36)

OpenAPI overlays, including conversational phrasing for each operation.

- [Loops Api Key Api Phrasing Overlay](https://apis.io/overlays/loops/loops-api-key-api-phrasing-overlay/)
- [Loops Api Key Overlay](https://apis.io/overlays/loops/loops-api-key-overlay/)
- [Loops Audience Segments Api Phrasing Overlay](https://apis.io/overlays/loops/loops-audience-segments-api-phrasing-overlay/)
- [Loops Audience Segments Overlay](https://apis.io/overlays/loops/loops-audience-segments-overlay/)
- [Loops Campaign Groups Api Phrasing Overlay](https://apis.io/overlays/loops/loops-campaign-groups-api-phrasing-overlay/)
- [Loops Campaign Groups Overlay](https://apis.io/overlays/loops/loops-campaign-groups-overlay/)
- [Loops Campaigns Api Phrasing Overlay](https://apis.io/overlays/loops/loops-campaigns-api-phrasing-overlay/)
- [Loops Campaigns Overlay](https://apis.io/overlays/loops/loops-campaigns-overlay/)
- [Loops Components Api Phrasing Overlay](https://apis.io/overlays/loops/loops-components-api-phrasing-overlay/)
- [Loops Components Overlay](https://apis.io/overlays/loops/loops-components-overlay/)
- [Loops Configuration Api Phrasing Overlay](https://apis.io/overlays/loops/loops-configuration-api-phrasing-overlay/)
- [Loops Configuration Overlay](https://apis.io/overlays/loops/loops-configuration-overlay/)
- [Loops Contact Properties Api Phrasing Overlay](https://apis.io/overlays/loops/loops-contact-properties-api-phrasing-overlay/)
- [Loops Contact Properties Overlay](https://apis.io/overlays/loops/loops-contact-properties-overlay/)
- [Loops Contacts Api Phrasing Overlay](https://apis.io/overlays/loops/loops-contacts-api-phrasing-overlay/)
- [Loops Contacts Overlay](https://apis.io/overlays/loops/loops-contacts-overlay/)
- [Loops Email Messages Api Phrasing Overlay](https://apis.io/overlays/loops/loops-email-messages-api-phrasing-overlay/)
- [Loops Email Messages Overlay](https://apis.io/overlays/loops/loops-email-messages-overlay/)
- [Loops Event Patterns Api Phrasing Overlay](https://apis.io/overlays/loops/loops-event-patterns-api-phrasing-overlay/)
- [Loops Event Patterns Overlay](https://apis.io/overlays/loops/loops-event-patterns-overlay/)
- [Loops Events Api Phrasing Overlay](https://apis.io/overlays/loops/loops-events-api-phrasing-overlay/)
- [Loops Events Overlay](https://apis.io/overlays/loops/loops-events-overlay/)
- [Loops Mailing Lists Api Phrasing Overlay](https://apis.io/overlays/loops/loops-mailing-lists-api-phrasing-overlay/)
- [Loops Mailing Lists Overlay](https://apis.io/overlays/loops/loops-mailing-lists-overlay/)
- [Loops Themes Api Phrasing Overlay](https://apis.io/overlays/loops/loops-themes-api-phrasing-overlay/)
- …and 11 more published on APIs.io

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Loops Authentication](https://apis.io/security/loops/loops-authentication/)
- [Loops Domain Security](https://apis.io/security/loops/loops-domain-security/)
- [Loops Trust Center](https://apis.io/security/loops/loops-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Loops Scopes](https://apis.io/scopes/loops/loops-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Loops Plans Pricing](https://apis.io/plans/loops/loops-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Loops Rate Limits](https://apis.io/rate-limits/loops/loops-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Loops Finops](https://apis.io/finops/loops/loops-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://loops.so/)
- [Documentation](https://loops.so/docs)
- [Getting started](https://loops.so/docs/quickstart)
- [API reference](https://loops.so/docs/api-reference/intro)
- [Pricing](https://loops.so/pricing)
- [Sign up](https://app.loops.so/register)
- [Support](https://app.loops.so/settings?page=support)
- [Blog](https://loops.so/engineering)
- [Terms of service](https://loops.so/terms)
- [Privacy policy](https://loops.so/privacy)
- [GitHub](https://github.com/Loops-so)
- [Status](https://status.loops.so)

## API Evangelist rating

**Kin Score 70.1** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 59.0 |
| Contract governance | 18.2 |
| Operational transparency | 73.7 |
| Developer ergonomics | 78.6 |
| Access clarity | 81.6 |

**Agent readiness 62.2** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | mostly |

**Regulatory alignment 39.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/loops/](https://apis.io/providers/loops/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Loops: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/loops/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
