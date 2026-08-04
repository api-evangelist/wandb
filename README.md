# Weights and Biases (wandb)

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

Weights and Biases (W&B) is an MLOps and AI developer platform covering the full lifecycle of model and LLM application development. W&B Models provides experiment tracking, hyperparameter sweeps, artifacts, model registry, and reports. W&B Weave provides LLM tracing, evaluation, cost tracking, guardrails, and prompt/playground tooling for production AI applications. Three CoreWeave- powered serverless capabilities sit alongside the core platform: Serverless Inference (OpenAI-compatible API for open-source foundation models), Serverless RL (post-training with ART/RULER), and Serverless Sandboxes (isolated code execution). The platform exposes a Python SDK, a public REST API, and a GraphQL API at api.wandb.ai, with CLI tooling and webhook integrations. W&B was acquired by CoreWeave in 2025.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/wandb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/wandb/refs/heads/main/apis.yml)

## Tags

- MLOps
- Experiment Tracking
- LLM Observability
- Model Registry
- AI Platform
- Evaluation
- Tracing

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### W&B GraphQL API

Primary programmatic surface for W&B Models. The Python public API (wandb.Api) speaks GraphQL against api.wandb.ai to query and manage runs, projects, sweeps, artifacts, registries, reports, automations, slack and webhook integrations, and viewer/entity context.

- **Human URL:** [https://docs.wandb.ai/ref/python/public-api/api/](https://docs.wandb.ai/ref/python/public-api/api/)
- **Base URL:** `https://api.wandb.ai/graphql`

#### Tags

- GraphQL
- Runs
- Artifacts
- Sweeps
- Model Registry

#### Properties

- [Documentation](https://docs.wandb.ai/ref/python/public-api/api/)
- [Postman Collection](collections/wandb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wandb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### W&B REST API

REST endpoints exposed by the W&B platform for ingestion, artifact upload, file storage, and integration callbacks. Used internally by the wandb SDK and CLI, and available to customers for direct integration.

- **Human URL:** [https://docs.wandb.ai/](https://docs.wandb.ai/)
- **Base URL:** `https://api.wandb.ai`

#### Tags

- REST
- Ingestion
- Artifacts

#### Properties

- [Documentation](https://docs.wandb.ai/)
- [Postman Collection](collections/wandb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wandb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### W&B Weave (LLM Observability)

LLM observability and evaluation platform providing tracing, output evaluation, cost estimation, prompt playground, guardrails, and a Python and TypeScript SDK. Traces and evaluations are persisted to the W&B backend and queryable via the Weave SDK.

- **Human URL:** [https://weave-docs.wandb.ai/](https://weave-docs.wandb.ai/)
- **Base URL:** `https://api.wandb.ai`

#### Tags

- LLM
- Observability
- Tracing
- Evaluation
- Guardrails

#### Properties

- [Documentation](https://weave-docs.wandb.ai/)
- [Repository](https://github.com/wandb/weave)
- [Postman Collection](collections/wandb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wandb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### W&B Python SDK

Official Python SDK (wandb) for logging runs, metrics, gradients, media, and artifacts; running sweeps; and interacting with the W&B public API. Apache-2.0 licensed.

- **Human URL:** [https://docs.wandb.ai/ref/python/](https://docs.wandb.ai/ref/python/)
- **Base URL:** `https://github.com/wandb/wandb`

#### Tags

- SDK
- Python

#### Properties

- [Repository](https://github.com/wandb/wandb)
- [Package](https://pypi.org/project/wandb/)
- [Postman Collection](collections/wandb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wandb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### W&B CLI

Command-line interface bundled with the wandb Python package for login, sweep orchestration, artifact management, and local agent execution.

- **Human URL:** [https://docs.wandb.ai/ref/cli/](https://docs.wandb.ai/ref/cli/)
- **Base URL:** `https://docs.wandb.ai/ref/cli/`

#### Tags

- CLI
- Sweeps
- Agents

#### Properties

- [Documentation](https://docs.wandb.ai/ref/cli/)
- [Postman Collection](collections/wandb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wandb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### W&B Serverless Inference (CoreWeave)

OpenAI-compatible inference API for hosted open-source foundation models, running on CoreWeave GPU infrastructure with native Weave tracing and usage tracking.

- **Human URL:** [https://docs.wandb.ai/guides/inference](https://docs.wandb.ai/guides/inference)
- **Base URL:** `https://api.inference.wandb.ai/v1`

#### Tags

- Inference
- OpenAI-Compatible
- LLM
- Serverless

#### Properties

- [Documentation](https://docs.wandb.ai/guides/inference)
- [Postman Collection](collections/wandb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wandb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### W&B Webhook Automations

Outbound webhook integrations driven by W&B automations. Customers register endpoints that W&B POSTs to when configured events fire (artifact created, alias added, run state changes, registry events).

- **Human URL:** [https://docs.wandb.ai/guides/automations/](https://docs.wandb.ai/guides/automations/)
- **Base URL:** `customer-configured`

#### Tags

- Webhooks
- Automations
- Events

#### Properties

- [Documentation](https://docs.wandb.ai/guides/automations/)
- [Postman Collection](collections/wandb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wandb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/wandbai)
- [Website](https://wandb.ai/)
- [Documentation](https://docs.wandb.ai/)
- [Git Hub](https://github.com/wandb)
- [Weave](https://weave-docs.wandb.ai/)
- [Pricing](https://wandb.ai/site/pricing/)
- [Parent](https://www.coreweave.com/)
- [Plans](plans/wandb-plans-pricing.yml)
- [Rate Limits](rate-limits/wandb-rate-limits.yml)
- [Fin Ops](finops/wandb-finops.yml)
- [L L Ms Txt](https://docs.wandb.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
