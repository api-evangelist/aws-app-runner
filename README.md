# AWS App Runner (aws-app-runner)
AWS App Runner is a fully managed service that makes it easy to build, deploy, and run containerized web applications and APIs at scale. It automatically builds and deploys applications from container images or source code, load balances traffic with encryption, and scales to meet traffic needs without requiring infrastructure management. App Runner integrates with ECR, GitHub, Bitbucket, VPC, IAM, and CloudWatch for complete application delivery.

**URL:** [https://aws.amazon.com/apprunner/](https://aws.amazon.com/apprunner/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, CI/CD, Containers, Deployment, Microservices, Serverless

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-19

## APIs

### AWS App Runner
AWS App Runner is a fully managed service that makes it easy to build, deploy, and run containerized web applications and APIs at scale. It automatically builds and deploys applications, load balances traffic with encryption, and scales to meet traffic needs without requiring infrastructure management.

**Human URL:** [https://aws.amazon.com/apprunner/](https://aws.amazon.com/apprunner/)

#### Tags:

 - AWS, Containers, Deployment, Microservices, Serverless

#### Properties

- [Documentation](https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html)
- [GettingStarted](https://docs.aws.amazon.com/apprunner/latest/dg/getting-started.html)
- [APIReference](https://docs.aws.amazon.com/apprunner/latest/api/Welcome.html)
- [Authentication](https://docs.aws.amazon.com/apprunner/latest/dg/security-iam.html)
- [OpenAPI](openapi/aws-app-runner-openapi.yml)

## Common Properties

- [Website](https://aws.amazon.com/apprunner/)
- [Documentation](https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html)
- [Pricing](https://aws.amazon.com/apprunner/pricing/)
- [FAQ](https://aws.amazon.com/apprunner/faqs/)
- [Customers](https://aws.amazon.com/apprunner/customers/)
- [Console](https://console.aws.amazon.com/apprunner/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Support](https://aws.amazon.com/premiumsupport/)

## Features

| Name | Description |
|------|-------------|
| Automatic Build and Deploy | Automatically builds container images from source code and deploys with zero configuration. |
| Auto-Scaling | Scales automatically based on incoming request volume, with configurable min/max instances. |
| Load Balancing | Built-in load balancing with HTTPS encryption for all traffic to deployed services. |
| Custom Domains | Associate custom domain names with SSL/TLS certificates for branded endpoints. |
| VPC Integration | Connect to private VPC resources like RDS, ElastiCache, and internal services. |
| Pause and Resume | Pause services to stop billing during idle periods and resume instantly when needed. |
| Observability | Integration with CloudWatch and X-Ray for metrics, logs, and distributed tracing. |
| GitHub and ECR Integration | Deploy directly from GitHub repositories or Amazon ECR container registries. |

## Use Cases

| Name | Description |
|------|-------------|
| Web Application Deployment | Deploy containerized web applications without managing servers, load balancers, or scaling. |
| API Backend Deployment | Host REST or GraphQL API backends with automatic scaling and HTTPS termination. |
| Microservices Hosting | Deploy individual microservices with isolated scaling and custom domain routing. |
| Development and Staging Environments | Quickly spin up and tear down environments using pause/resume to minimize costs. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon ECR | Pull container images from Amazon Elastic Container Registry for deployment. |
| GitHub | Connect GitHub repositories for automatic builds and continuous deployment. |
| AWS IAM | Control access to App Runner APIs and service resources using IAM policies. |
| Amazon CloudWatch | Monitor service metrics, CPU usage, request counts, and response latency. |
| AWS X-Ray | Enable distributed tracing for request flows through App Runner services. |
| Amazon VPC | Access private VPC resources from App Runner services via VPC connectors. |
| AWS Certificate Manager | Automatic SSL/TLS certificate provisioning for custom domain names. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AWS App Runner](openapi/aws-app-runner-openapi.yml)

### JSON Schema

17 schema files covering Service, ServiceSummary, VpcConnector, AutoScalingConfiguration, CustomDomain, and related types.

### JSON Structure

17 JSON Structure files converted from JSON Schema using json-structure.org/meta/core/v0.

### JSON-LD

- [AWS App Runner Context](json-ld/aws-app-runner-context.jsonld)

### Examples

17 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [AWS App Runner](capabilities/shared/app-runner.yaml) — 11 operations for application deployment lifecycle management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Application Deployment Workflow](capabilities/app-deployment-workflow.yaml) | App Runner | 11 | Developer, Platform Engineer |

## Vocabulary

- [AWS App Runner Vocabulary](vocabulary/aws-app-runner-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 8 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [AWS App Runner Spectral Rules](rules/aws-app-runner-spectral-rules.yml) — 17 rules across 7 categories enforcing AWS App Runner API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
