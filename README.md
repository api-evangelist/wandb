# Weights and Biases

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

Weights and Biases (W&B) is an MLOps and AI developer platform covering the full lifecycle of model and LLM application development. W&B Models provides experiment tracking, hyperparameter sweeps, artifacts, model registry, and reports. W&B Weave provides LLM tracing, evaluation, cost tracking, guardrails, and prompt/playground tooling for production AI applications. Three CoreWeave- powered serverless capabilities sit alongside the core platform: Serverless Inference (OpenAI-compatible API for open-source foundation models), Serverless RL (post-training with ART/RULER), and Serverless Sandboxes (isolated code execution). The platform exposes a Python SDK, a public REST API, and a GraphQL API at api.wandb.ai, with CLI tooling and webhook integrations. W&B was acquired by CoreWeave in 2025.

**Areas:** MLOps · Experiment Tracking · LLM Observability · Model Registry · AI Platform · Evaluation · Tracing

## Weights and Biases on APIs.io

Everything profiled for Weights and Biases is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/wandb/](https://apis.io/providers/wandb/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [W&B GraphQL API](https://apis.io/apis/wandb/graphql/) — Primary programmatic surface for W&B Models. The Python public API (wandb.Api) speaks GraphQL against api.wandb.ai to query and manage runs, projects,…
- [W&B REST API](https://apis.io/apis/wandb/rest/) — REST endpoints exposed by the W&B platform for ingestion, artifact upload, file storage, and integration callbacks. Used internally by the wandb SDK and…
- [W&B Weave (LLM Observability)](https://apis.io/apis/wandb/weave/) — LLM observability and evaluation platform providing tracing, output evaluation, cost estimation, prompt playground, guardrails, and a Python and TypeScript…
- [W&B Python SDK](https://apis.io/apis/wandb/python-sdk/) — Official Python SDK (wandb) for logging runs, metrics, gradients, media, and artifacts; running sweeps; and interacting with the W&B public API. Apache-2.0…
- [W&B CLI](https://apis.io/apis/wandb/cli/) — Command-line interface bundled with the wandb Python package for login, sweep orchestration, artifact management, and local agent execution.
- [W&B Serverless Inference (CoreWeave)](https://apis.io/apis/wandb/serverless-inference/) — OpenAI-compatible inference API for hosted open-source foundation models, running on CoreWeave GPU infrastructure with native Weave tracing and usage tracking.
- [W&B Webhook Automations](https://apis.io/apis/wandb/webhook-automations/) — Outbound webhook integrations driven by W&B automations. Customers register endpoints that W&B POSTs to when configured events fire (artifact created, alias…
- [Weights and Biases Calls API](https://apis.io/apis/wandb/wandb-calls-api/) — The Calls API from Weights and Biases — 8 operation(s) for calls.
- [Weights and Biases Costs API](https://apis.io/apis/wandb/wandb-costs-api/) — The Costs API from Weights and Biases — 3 operation(s) for costs.
- [Weights and Biases Feedback API](https://apis.io/apis/wandb/wandb-feedback-api/) — The Feedback API from Weights and Biases — 4 operation(s) for feedback.
- [Weights and Biases Files API](https://apis.io/apis/wandb/wandb-files-api/) — The Files API from Weights and Biases — 2 operation(s) for files.
- [Weights and Biases Objects API](https://apis.io/apis/wandb/wandb-objects-api/) — The Objects API from Weights and Biases — 4 operation(s) for objects.
- [Weights and Biases Refs API](https://apis.io/apis/wandb/wandb-refs-api/) — The Refs API from Weights and Biases — 1 operation(s) for refs.
- [Weights and Biases Service API](https://apis.io/apis/wandb/wandb-service-api/) — The Service API from Weights and Biases — 2 operation(s) for service.
- [Weights and Biases Table API](https://apis.io/apis/wandb/wandb-table-api/) — The Table API from Weights and Biases — 1 operation(s) for table.
- [Weights and Biases Tables API](https://apis.io/apis/wandb/wandb-tables-api/) — The Tables API from Weights and Biases — 4 operation(s) for tables.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Weights and Biases GraphQL API](https://apis.io/graphqls/wandb/wandb-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Moved to /providers/wandb/](https://apis.io/servers/wandb/wandb/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Wandb Agentic Access](https://apis.io/agentic-access/wandb/wandb-agentic-access/)

#### Collections (10)

Postman and Open Collection request collections.

- [FastAPI](https://apis.io/collections/wandb/open-wandb/)
- [Fast Calls API](https://apis.io/collections/wandb/open-wandb-calls-api/)
- [Fast Calls Costs API](https://apis.io/collections/wandb/open-wandb-costs-api/)
- [Fast Calls Feedback API](https://apis.io/collections/wandb/open-wandb-feedback-api/)
- [Fast Calls Files API](https://apis.io/collections/wandb/open-wandb-files-api/)
- [Fast Calls Objects API](https://apis.io/collections/wandb/open-wandb-objects-api/)
- [Fast Calls Refs API](https://apis.io/collections/wandb/open-wandb-refs-api/)
- [Fast Calls Service API](https://apis.io/collections/wandb/open-wandb-service-api/)
- [Fast Calls Table API](https://apis.io/collections/wandb/open-wandb-table-api/)
- [Fast Calls Tables API](https://apis.io/collections/wandb/open-wandb-tables-api/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Wandb Authentication](https://apis.io/security/wandb/wandb-authentication/)
- [Wandb Domain Security](https://apis.io/security/wandb/wandb-domain-security/)
- [Wandb Vulnerability Disclosure](https://apis.io/security/wandb/wandb-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Wandb Plans Pricing](https://apis.io/plans/wandb/wandb-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Wandb Rate Limits](https://apis.io/rate-limits/wandb/wandb-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Wandb Finops](https://apis.io/finops/wandb/wandb-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://wandb.ai/)
- [Documentation](https://docs.wandb.ai/)
- [Pricing](https://wandb.ai/site/pricing/)
- [Blog](https://wandb.ai/fully-connected)

## API Evangelist rating

**Kin Score 36.4** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 46.7 |
| Contract governance | 0.0 |
| Operational transparency | 36.8 |
| Developer ergonomics | 21.4 |
| Access clarity | 15.8 |

**Agent readiness 33.7** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
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
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 17.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/wandb/](https://apis.io/providers/wandb/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Weights and Biases: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/wandb/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
