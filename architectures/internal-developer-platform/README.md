# Internal developer platform reference architecture

This starter reference architecture packages the minimum set of platform capabilities that a consulting team can tailor for a client-specific internal developer platform engagement.

## Goals

- Standardize service onboarding and golden paths
- Centralize software catalog metadata and ownership
- Provide self-service infrastructure workflows with policy guardrails
- Establish observability, cost, and security review checkpoints

## Core components

| Capability | Suggested component |
| --- | --- |
| Developer portal | Backstage |
| Continuous delivery | Argo CD |
| Infrastructure orchestration | Crossplane and Terraform |
| Event-driven autoscaling | KEDA |
| Secrets and identity | Cloud-native secret manager plus SSO |
| Observability | Metrics, logs, and traces with centralized dashboards |

## Delivery phases

1. Foundation: identity, source control standards, environments, and guardrails
2. Platform services: catalog, templates, delivery automation, and observability
3. Golden paths: standardized service blueprints for key workloads
4. Adoption: scorecards, office hours, and operating model handoff
