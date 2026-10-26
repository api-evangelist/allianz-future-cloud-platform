# Allianz Future Cloud Platform (allianz-future-cloud-platform)

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

The Allianz Future Cloud Platform is an internal developer platform powering cloud-native insurance microservices at Allianz. Built on Kubernetes and AWS, it provides platform engineering capabilities including service deployment, infrastructure management, observability, and GitOps automation across Allianz's global insurance operations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/allianz-future-cloud-platform/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cloud Platform, Enterprise, Financial Services, Insurance, Platform Engineering, Kubernetes

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Allianz Future Cloud Platform Services API
Platform engineering APIs for managing cloud-native services on the Allianz Future Cloud Platform. Provides capabilities for service registration, deployment management, observability configuration, and infrastructure provisioning across Kubernetes clusters.

**Human URL:** [https://architecture.cncf.io/architectures/allianz/](https://architecture.cncf.io/architectures/allianz/)

#### Tags:

 - Cloud Platform, Platform Engineering, Microservices, DevOps

#### Properties

- [Documentation](https://architecture.cncf.io/architectures/allianz/)
- [Documentation](https://www.cncf.io/case-studies/allianz/)
- [OpenAPI](openapi/allianz-future-cloud-platform-services.yaml)
- [JSONSchema](json-schema/platform-services-service-schema.json)
- [JSONSchema](json-schema/platform-services-deployment-schema.json)
- [JSONStructure](json-structure/platform-services-service-structure.json)
- [JSONLD](json-ld/allianz-future-cloud-platform-context.jsonld)
- [Example](examples/platform-services-service-example.json)
- [Example](examples/platform-services-deployment-example.json)

### Allianz Insurance Policy Microservice API
Insurance policy microservice running on the Allianz Future Cloud Platform. Provides REST APIs for policy lifecycle management including creation, endorsements, renewals, and cancellations built with Kotlin and Java on Kubernetes.

**Human URL:** [https://www.allianz.com/en/about-us/technology.html](https://www.allianz.com/en/about-us/technology.html)

#### Tags:

 - Insurance, Policy Management, Microservices

#### Properties

- [Documentation](https://www.allianz.com/en/about-us/technology.html)

## Common Properties

- [Website](https://www.allianz.com/)
- [GitHubOrganization](https://github.com/allianz)
- [Documentation](https://architecture.cncf.io/architectures/allianz/)
- [SpectralRules](rules/allianz-future-cloud-platform-spectral-rules.yml)
- [Vocabulary](vocabulary/allianz-future-cloud-platform-vocabulary.yaml)
- [NaftikoCapability](capabilities/cloud-platform-operations.yaml)

## Features

| Name | Description |
|------|-------------|
| Kubernetes Platform Engineering | Internal developer platform built on Kubernetes (EKS) providing standardized deployment, scaling, and orchestration for insurance microservices. |
| GitOps Deployment | ArgoCD and Tekton-based CI/CD pipelines enabling GitOps workflows for continuous delivery of insurance applications. |
| Infrastructure as Code | Terraform and Crossplane-based infrastructure management enabling repeatable, auditable cloud resource provisioning. |
| Observability Stack | Prometheus, Grafana, and OpenTelemetry based observability platform providing metrics, tracing, and alerting for platform services. |
| Multi-tenant Architecture | Namespace-level multi-tenancy supporting multiple insurance product teams on shared Kubernetes infrastructure. |
| Event Streaming | AWS MSK (Managed Kafka) for high-throughput event streaming between insurance microservices and downstream consumers. |

## Use Cases

| Name | Description |
|------|-------------|
| Insurance Microservice Deployment | Deploy and manage Kotlin and Java insurance microservices on the platform with standardized CI/CD pipelines and GitOps workflows. |
| Platform Onboarding | Onboard new insurance product teams onto the shared Kubernetes platform with pre-configured namespaces and RBAC policies. |
| Observability and Monitoring | Configure monitoring dashboards and alerting for insurance services using the platform's built-in Prometheus and Grafana stack. |
| Infrastructure Provisioning | Provision cloud infrastructure resources using Terraform and Crossplane through the platform's infrastructure API. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon Web Services | Primary cloud provider with EKS, MSK, ElastiCache Redis, and storage services powering the platform. |
| ArgoCD | GitOps continuous delivery for declarative application deployment and state synchronization. |
| Terraform | Infrastructure as code for cloud resource provisioning and management integrated with Atlantis for PR automation. |
| Crossplane | Multi-cloud resource management extending Kubernetes for cloud-agnostic infrastructure provisioning. |
| OpenTelemetry | Distributed tracing and metrics collection across microservices for observability and performance analysis. |
| Apache Kafka | AWS MSK for event-driven communication between insurance microservices and downstream systems. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Allianz Future Cloud Platform Services API](openapi/allianz-future-cloud-platform-services.yaml)

### JSON Schema

- [platform-services-service-schema.json](json-schema/platform-services-service-schema.json)
- [platform-services-service-list-schema.json](json-schema/platform-services-service-list-schema.json)
- [platform-services-register-service-request-schema.json](json-schema/platform-services-register-service-request-schema.json)
- [platform-services-resource-requirements-schema.json](json-schema/platform-services-resource-requirements-schema.json)
- [platform-services-deployment-schema.json](json-schema/platform-services-deployment-schema.json)
- [platform-services-deployment-list-schema.json](json-schema/platform-services-deployment-list-schema.json)
- [platform-services-deploy-service-request-schema.json](json-schema/platform-services-deploy-service-request-schema.json)
- [platform-services-namespace-schema.json](json-schema/platform-services-namespace-schema.json)
- [platform-services-namespace-list-schema.json](json-schema/platform-services-namespace-list-schema.json)
- [platform-services-metrics-response-schema.json](json-schema/platform-services-metrics-response-schema.json)
- [platform-services-provision-resource-request-schema.json](json-schema/platform-services-provision-resource-request-schema.json)
- [platform-services-infrastructure-resource-schema.json](json-schema/platform-services-infrastructure-resource-schema.json)

### JSON Structure

- [platform-services-service-structure.json](json-structure/platform-services-service-structure.json)
- [platform-services-deployment-structure.json](json-structure/platform-services-deployment-structure.json)
- [platform-services-metrics-response-structure.json](json-structure/platform-services-metrics-response-structure.json)

### JSON-LD

- [allianz-future-cloud-platform-context.jsonld](json-ld/allianz-future-cloud-platform-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Allianz Future Cloud Platform Services API](capabilities/shared/platform-services.yaml) — 8 operations for cloud platform operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Allianz Cloud Platform Operations](capabilities/cloud-platform-operations.yaml) | Allianz Future Cloud Platform Services API | 8 | Platform Engineer, DevOps Engineer, Insurance Product Developer |

## Vocabulary

- [Allianz Future Cloud Platform Vocabulary](vocabulary/allianz-future-cloud-platform-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 5 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Allianz Future Cloud Platform Spectral Rules](rules/allianz-future-cloud-platform-spectral-rules.yml) — 23 rules across 9 categories enforcing Allianz Future Cloud Platform API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
