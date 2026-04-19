# Allianz Future Cloud Platform (allianz-future-cloud-platform)
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
