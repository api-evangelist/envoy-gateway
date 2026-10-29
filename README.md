# Envoy Gateway

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

Envoy Gateway is a CNCF project that manages Envoy Proxy as a standalone or Kubernetes-based application gateway. It implements the Kubernetes Gateway API and extends it with its own API group, gateway.envoyproxy.io, whose eight Custom Resource Definitions cover infrastructure shape, client and backend traffic behaviour, security policy, extensibility and direct xDS patching. There is no REST API and no hosted endpoint: the machine-readable contract is the CRD structural schemas plus two first-party gRPC services — an extension server hook and a remote infrastructure provider — that Envoy Gateway calls out to. Apache-2.0 licensed and free, with a published compatibility matrix giving every release a dated end of life, and Gateway API v1.6.1 core and extended conformance certified by report in the standard body's own repository.

**Areas:** API Gateway · CNCF · Envoy · Kubernetes · Open Source · Gateway API · Ingress · Service Mesh · Cloud-Native · gRPC

## Envoy Gateway on APIs.io

Everything profiled for Envoy Gateway is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/envoy-gateway/](https://apis.io/providers/envoy-gateway/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Envoy Gateway](https://apis.io/apis/envoy-gateway/envoy-gateway/) — Envoy Gateway's configuration API is a set of Kubernetes Custom Resource Definitions in the gateway.envoyproxy.io/v1alpha1 group — Backend,…
- [Envoy Gateway Extension Server](https://apis.io/apis/envoy-gateway/envoy-gateway-extension-server/) — A gRPC contract an operator implements to extend Envoy Gateway. Envoy Gateway is the client: during xDS translation it calls the six EnvoyGatewayExtension…
- [Envoy Gateway Remote Infrastructure Provider](https://apis.io/apis/envoy-gateway/envoy-gateway-remote-infrastructure/) — A gRPC contract added in v1.9.0 that lets an operator supply their own infrastructure management strategy in place of Envoy Gateway creating Kubernetes…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Envoy Gateway Authentication](https://apis.io/security/envoy-gateway/envoy-gateway-authentication/)
- [Envoy Gateway Domain Security](https://apis.io/security/envoy-gateway/envoy-gateway-domain-security/)
- [Envoy Gateway Vulnerability Disclosure](https://apis.io/security/envoy-gateway/envoy-gateway-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Envoy Gateway Plans Pricing](https://apis.io/plans/envoy-gateway/envoy-gateway-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Envoy Gateway Rate Limits](https://apis.io/rate-limits/envoy-gateway/envoy-gateway-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Envoy Gateway Finops](https://apis.io/finops/envoy-gateway/envoy-gateway-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://gateway.envoyproxy.io/)
- [Documentation](https://gateway.envoyproxy.io/docs/)
- [Getting started](https://gateway.envoyproxy.io/docs/tasks/quickstart/)
- [API reference](https://gateway.envoyproxy.io/docs/api/extension_types/)
- [Support](https://github.com/envoyproxy/gateway/issues)
- [GitHub](https://github.com/envoyproxy)

## API Evangelist rating

**Kin Score 40.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 36.0 |
| Contract governance | 18.2 |
| Operational transparency | 42.1 |
| Developer ergonomics | 76.2 |
| Access clarity | 0.0 |

**Agent readiness 22.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | derived (partial credit) |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 22.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/envoy-gateway/](https://apis.io/providers/envoy-gateway/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Envoy Gateway: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/envoy-gateway/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
