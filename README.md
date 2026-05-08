# ClearML (clearml)

ClearML is an open-source MLOps platform with experiment tracking, datasets, model serving, and orchestration. The ClearML Server exposes a versioned REST API split across services (auth, projects, tasks, workers, models, queues, events, pipelines).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/clearml/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=clearml-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **ClearML REST API** - Service-oriented REST at `https://api.clear.ml`. Services: auth, projects, tasks (experiments), workers, models, queues, events, pipelines, reports. Access/secret-key pairs minted in UI.

## Tags
- ML, MLOps, Open Source, Experiment Tracking, Orchestration

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://clear.ml/)
- [Documentation](https://clear.ml/docs/latest/docs/)
- [Source (Apache 2.0)](https://github.com/clearml/clearml-server)
- [Pricing](https://clear.ml/pricing)
- [Plans](plans/clearml-plans-pricing.yml)
- [RateLimits](rate-limits/clearml-rate-limits.yml)
- [FinOps](finops/clearml-finops.yml)

## Notes
- Pricing reconciled (research): Community free (3 users, 100 GB artifacts, 1M API calls/mo); Pro $15/user/mo + usage ($0.1/GB storage, $0.01/1MB metrics, $1/100K API calls); Scale & Enterprise custom (VPC, on-prem, air-gap). Self-hosted open source available.
- ClearML actually publishes per-month API call quotas — unusually transparent for an MLOps platform.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
