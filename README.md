# Weights and Biases (wandb)

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
